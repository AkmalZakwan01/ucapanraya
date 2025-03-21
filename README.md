<!DOCTYPE html> <html lang="ms">   <head>     <meta charset="UTF-8" />     <meta name="viewport" content="width=device-width, initial-scale=1.0" />     <title>Selamat Hari Raya Aidilfitri</title>     <style>       body {         background: linear-gradient(to right, #28a745, #218838);         text-align: center;         color: white;         font-family: "Poppins", sans-serif;         overflow: hidden;       }       .container {         margin-top: 50px;       }       h1 {         font-size: 3.5em;         text-shadow: 4px 4px 6px rgba(0, 0, 0, 0.6);         animation: fadeIn 2s ease-in-out;       }       @keyframes fadeIn {         0% {           opacity: 0;           transform: scale(0.8);         }         100% {           opacity: 1;           transform: scale(1);         }       }       .ketupat {         display: flex;         justify-content: center;         gap: 20px;         margin-top: 20px;       }       .ketupat div {         width: 60px;         height: 60px;         background: repeating-linear-gradient(           45deg,           #f4d03f,           #f4d03f 10px,           #16a085 10px,           #16a085 20px         );         transform: rotate(45deg);         animation: swing 2s infinite alternate;       }       @keyframes swing {         0% {           transform: rotate(45deg) translateY(0);         }         100% {           transform: rotate(45deg) translateY(10px);         }       }       .lampu {         position: absolute;         width: 100%;         height: 10px;         top: 10px;         display: flex;         justify-content: center;         gap: 15px;       }       .lampu span {         width: 20px;         height: 20px;         border-radius: 50%;         background: yellow;         animation: flicker 1s infinite alternate;       }       @keyframes flicker {         0% {           opacity: 0.5;         }         100% {           opacity: 1;         }       }       .lampu span:nth-child(odd) {         animation-delay: 0.5s;       }       .ucapan {         margin-top: 30px;         font-size: 1.8em;         background: rgba(255, 255, 255, 0.3);         padding: 15px;         border-radius: 15px;         display: inline-block;         box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.4);         animation: bounce 2s infinite;       }       @keyframes bounce {         0%,         100% {           transform: translateY(0);         }         50% {           transform: translateY(-10px);         }       }     </style>   </head>   <body>     <div class="lampu">       <span></span><span></span><span></span><span></span><span></span>       <span></span><span></span><span></span><span></span><span></span>     </div>     <div class="container">       <h1>🌙 Selamat Hari Raya Aidilfitri! 🌙</h1>       <p>Maaf Zahir dan Batin</p>       <div class="ketupat">         <div></div>         <div></div>         <div></div>       </div>       <div class="ucapan">         "Salam Aidilfitri buat Koperal Anas yang dihormati. Semoga Syawal ini         membawa kebahagiaan, keberkatan, dan ketenangan dalam kehidupan. Terima         kasih atas jasa dan pengorbananmu dalam menjaga keamanan negara. Moga         segala usaha dan keringatmu diberkati oleh-Nya. Selamat Hari Raya, Maaf         Zahir & Batin! 🌟💚"       </div>     </div>   </body> </html>
0 commit commentsComments0 (0)Lock conversationCommentUnsubscribeYou're receiving notifications because y
