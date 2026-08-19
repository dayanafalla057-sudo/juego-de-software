<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>EL CÓDIGO MALDITO</title>

<style>

/* =========================================================
   CONFIGURACIÓN GENERAL
========================================================= */

*{
    box-sizing:border-box;
    margin:0;
    padding:0;
}

html,body{
    width:100%;
    height:100%;
}

body{
    background:#020303;
    color:#d8ffd8;
    font-family:"Courier New",monospace;
    overflow:hidden;
}

/* CRT */

body:after{
    content:"";
    position:fixed;
    inset:0;
    pointer-events:none;
    z-index:999;
    background:
    repeating-linear-gradient(
        0deg,
        rgba(255,255,255,.025) 0px,
        rgba(255,255,255,.025) 1px,
        transparent 2px,
        transparent 4px
    );
    mix-blend-mode:screen;
}

/* =========================================================
   PANTALLAS
========================================================= */

.screen{
    position:fixed;
    inset:0;
    display:none;
    justify-content:center;
    align-items:center;
    z-index:10;
}

.screen.active{
    display:flex;
}

/* =========================================================
   INTRO
========================================================= */

#intro{
    background:
    radial-gradient(circle at center,#123b1c 0%,#020303 60%);
}

.introBox{
    width:900px;
    max-width:94%;
    padding:45px;
    text-align:center;
    border:1px solid #42ff69;
    background:rgba(2,9,5,.96);
    box-shadow:
    0 0 40px rgba(0,255,70,.15),
    inset 0 0 30px rgba(0,255,70,.04);
}

.warning{
    color:#ff2424;
    letter-spacing:5px;
    animation:flicker 1.4s infinite;
    margin-bottom:20px;
}

.logo{
    color:#5cff78;
    font-size:clamp(45px,8vw,85px);
    text-shadow:
    0 0 10px #22ff4d,
    0 0 30px #0a6b20;
    margin-bottom:15px;
}

.subtitle{
    color:#82ff9a;
    letter-spacing:3px;
    margin-bottom:30px;
}

.story{
    color:#aab7ad;
    line-height:1.9;
    font-size:16px;
}

.story strong{
    color:#ff3434;
}

.startButton{
    margin-top:30px;
    padding:18px 40px;
    font-size:18px;
}

/* =========================================================
   JUEGO
========================================================= */

#game{
    align-items:stretch;
}

.game{
    width:100%;
    height:100%;
    display:flex;
    flex-direction:column;
}

/* HEADER */

.header{
    height:70px;
    min-height:70px;
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding:0 20px;
    background:#030806;
    border-bottom:1px solid #234c2b;
    position:relative;
}

.systemName{
    color:#4cff70;
    font-size:14px;
}

.stats{
    display:flex;
    align-items:center;
    gap:20px;
}

.timer{
    color:#ff4545;
    font-size:19px;
}

.timer.danger{
    animation:dangerBlink .45s infinite;
}

.lives{
    color:#ff4444;
    font-size:20px;
}

.threat{
    color:#ff7070;
    font-size:13px;
}

.threatBar{
    width:100px;
    height:8px;
    border:1px solid #512323;
    display:inline-block;
    margin-left:5px;
}

.threatFill{
    height:100%;
    width:0%;
    background:#ff2020;
    transition:.4s;
}

.progress{
    position:absolute;
    left:0;
    bottom:0;
    height:3px;
    background:#4cff70;
    width:100%;
}

/* =========================================================
   CONTENIDO
========================================================= */

.gameArea{
    flex:1;
    display:flex;
    justify-content:center;
    align-items:center;
    padding:15px;
    overflow:auto;
}

.terminal{
    width:1000px;
    max-width:100%;
    max-height:95%;
    overflow:auto;
    border:1px solid #285734;
    background:#030806;
    box-shadow:0 0 50px rgba(0,255,80,.08);
}

.terminalTop{
    height:38px;
    border-bottom:1px solid #23452b;
    padding:10px 15px;
    color:#3dff62;
}

.content{
    padding:30px;
}

.roomTitle{
    color:#5cff78;
    font-size:13px;
    margin-bottom:15px;
}

.bigTitle{
    color:#fff;
    font-size:30px;
    margin-bottom:20px;
}

.description{
    color:#aebbb1;
    line-height:1.8;
    margin-bottom:20px;
}

.clue{
    border-left:4px solid #51ff70;
    background:#061309;
    padding:20px;
    color:#b6d9bc;
    line-height:1.8;
    margin:20px 0;
}

.warningBox{
    border:1px solid #6d2020;
    background:#180505;
    color:#ff7b7b;
    padding:15px;
    margin:20px 0;
}

button{
    font-family:inherit;
    color:#c8ffd0;
    background:#061108;
    border:1px solid #347744;
    padding:14px 18px;
    cursor:pointer;
    transition:.2s;
}

button:hover{
    background:#0c2913;
    border-color:#5cff78;
    box-shadow:0 0 18px rgba(50,255,100,.25);
    transform:translateY(-2px);
}

button:disabled{
    opacity:.3;
    cursor:not-allowed;
    transform:none;
}

/* OPCIONES */

.options{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:14px;
}

.option{
    min-height:75px;
    text-align:left;
}

/* =========================================================
   MAPA
========================================================= */

.map{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:12px;
    margin-top:25px;
}

.room{
    min-height:120px;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    gap:10px;
}

.room.locked{
    opacity:.35;
}

.room.current{
    border-color:#5cff78;
    box-shadow:0 0 15px rgba(80,255,110,.2);
}

.roomIcon{
    font-size:35px;
}

/* =========================================================
   INVENTARIO
========================================================= */

.inventory{
    display:flex;
    flex-wrap:wrap;
    gap:10px;
    margin:15px 0;
}

.item{
    border:1px solid #315c39;
    padding:8px 12px;
    color:#9cffac;
}

/* =========================================================
   CÓDIGO
========================================================= */

.codeInput{
    width:100%;
    max-width:350px;
    background:#020503;
    color:#6cff85;
    border:1px solid #3a7546;
    padding:16px;
    font-family:inherit;
    font-size:20px;
    text-align:center;
    letter-spacing:5px;
    outline:none;
}

/* =========================================================
   SUSTO
========================================================= */

.jumpscare{
    position:fixed;
    inset:0;
    display:none;
    align-items:center;
    justify-content:center;
    z-index:500;
    background:#000;
}

.jumpscare.show{
    display:flex;
}

.shadowFace{
    width:280px;
    height:420px;
    background:
    radial-gradient(
        ellipse at center,
        #3c3c3c 0%,
        #181818 45%,
        #000 75%
    );
    border-radius:48% 48% 35% 35%;
    position:relative;
    box-shadow:0 0 80px #000;
    animation:shake .07s infinite;
}

.noEye{
    position:absolute;
    top:120px;
    width:65px;
    height:35px;
    background:#000;
    border-radius:50%;
}

.noEye.left{
    left:55px;
}

.noEye.right{
    right:55px;
}

.mouth{
    position:absolute;
    bottom:80px;
    left:70px;
    right:70px;
    height:100px;
    background:#000;
    border-radius:50%;
}

.scar{
    position:absolute;
    left:50%;
    transform:translateX(-50%);
    top:30px;
    color:#ff1111;
    font-size:17px;
    font-weight:bold;
    white-space:nowrap;
}

/* =========================================================
   FINAL
========================================================= */

#final{
    background:
    radial-gradient(circle,#190303 0%,#000 60%);
}

.finalBox{
    width:900px;
    max-width:95%;
    text-align:center;
}

.finalMonster{
    position:relative;
    width:240px;
    height:350px;
    margin:0 auto 25px;
    background:
    radial-gradient(
        ellipse at center,
        #454545 0%,
        #191919 50%,
        #000 80%
    );
    border-radius:50% 50% 35% 35%;
    box-shadow:0 0 100px #000;
    animation:monsterMove 2s infinite alternate;
}

.finalMonster:before,
.finalMonster:after{
    content:"";
    position:absolute;
    top:90px;
    width:65px;
    height:45px;
    background:#000;
    border-radius:50%;
}

.finalMonster:before{
    left:45px;
}

.finalMonster:after{
    right:45px;
}

.finalMouth{
    position:absolute;
    bottom:65px;
    left:60px;
    right:60px;
    height:100px;
    background:#000;
    border-radius:50%;
}

.forehead{
    position:absolute;
    top:25px;
    left:0;
    right:0;
    text-align:center;
    color:#ff1111;
    font-weight:bold;
    font-size:21px;
    text-shadow:0 0 10px red;
}

.failTitle{
    color:#ff1010;
    font-size:65px;
    font-weight:bold;
    text-shadow:0 0 20px red;
}

.successTitle{
    color:#5cff78;
    font-size:60px;
    text-shadow:0 0 20px #1aff49;
}

.finalText{
    color:#aaa;
    line-height:1.8;
    white-space:pre-line;
    margin:20px 0;
}

/* =========================================================
   ANIMACIONES
========================================================= */

@keyframes flicker{
    0%,18%,22%,100%{opacity:1}
    20%,21%{opacity:.2}
}

@keyframes dangerBlink{
    50%{opacity:.2}
}

@keyframes shake{
    0%{transform:translate(5px,2px) rotate(1deg)}
    50%{transform:translate(-5px,-3px) rotate(-1deg)}
    100%{transform:translate(3px,4px)}
}

@keyframes monsterMove{
    from{transform:scale(1)}
    to{transform:scale(1.08) translateY(-5px)}
}

/* =========================================================
   MÓVIL
========================================================= */

@media(max-width:700px){

    body{
        overflow:auto;
    }

    .header{
        height:auto;
        min-height:75px;
        flex-wrap:wrap;
        gap:7px;
        padding:10px;
    }

    .systemName{
        font-size:9px;
    }

    .stats{
        gap:8px;
        font-size:11px;
    }

    .threatBar{
        width:60px;
    }

    .gameArea{
        align-items:flex-start;
        padding:8px;
    }

    .content{
        padding:20px;
    }

    .bigTitle{
        font-size:23px;
    }

    .options{
        grid-template-columns:1fr;
    }

    .map{
        grid-template-columns:1fr 1fr;
    }

    .finalMonster{
        width:160px;
        height:250px;
    }

    .failTitle{
        font-size:42px;
    }

}

</style>
</head>

<body>


<!-- =====================================================
     INTRO
===================================================== -->

<section id="intro" class="screen active">

<div class="introBox">

<div class="warning">
⚠ SISTEMA COMPROMETIDO ⚠
</div>

<div class="logo">
EL CÓDIGO MALDITO
</div>

<div class="subtitle">
ESCAPE ROOM // TERROR TECNOLÓGICO
</div>

<div class="story">

Son las <strong>03:17 AM</strong>.

<br><br>

Has encontrado un laboratorio informático abandonado.

<br><br>

Un computador sigue funcionando.

<br><br>

Al tocar el teclado aparece:

<br><br>

<strong>
"NO DEBISTE DESPERTAR EL SISTEMA."
</strong>

<br><br>

El sistema te ha encerrado.

<br><br>

❤️ Tienes solamente <strong>2 vidas</strong>.

<br>

⏱ Tienes solamente <strong>5 minutos</strong>.

<br><br>

Las preguntas no aparecerán como un examen.

<br>

Tendrás que explorar, encontrar pistas,
descifrar códigos y tomar decisiones.

<br><br>

<strong>
SI TE EQUIVOCAS, ÉL SE ACERCA.
</strong>

</div>

<button
class="startButton"
onclick="startGame()">

▶ DESPERTAR EL SISTEMA

</button>

</div>

</section>


<!-- =====================================================
     JUEGO
===================================================== -->

<section id="game" class="screen">

<div class="game">

<header class="header">

<div class="systemName">
[SISTEMA // EL_CODIGO_MALDITO]
</div>

<div class="stats">

<div class="timer" id="timer">
⏱ <span id="time">05:00</span>
</div>

<div class="lives">
❤️ <span id="lives">2</span>
</div>

<div class="threat">

AMENAZA:

<span class="threatBar">
<span id="threatFill" class="threatFill"></span>
</span>

<span id="threatNumber">0%</span>

</div>

</div>

<div
id="progress"
class="progress">
</div>

</header>


<div class="gameArea">

<div class="terminal">

<div class="terminalTop">
● ● ● &nbsp; TERMINAL ACTIVO
</div>

<div id="content" class="content">
</div>

</div>

</div>

</div>

</section>


<!-- =====================================================
     SUSTO
===================================================== -->

<div
id="jumpscare"
class="jumpscare">

<div class="shadowFace">

<div class="scar">
¿ME PUEDES VER?
</div>

<div class="noEye left"></div>
<div class="noEye right"></div>

<div class="mouth"></div>

</div>

</div>


<!-- =====================================================
     FINAL
===================================================== -->

<section id="final" class="screen">

<div class="finalBox">

<div id="monster" class="finalMonster">

<div class="forehead">
FRACASASTE
</div>

<div class="finalMouth">
</div>

</div>

<div id="finalTitle"
class="failTitle">
FRACASASTE
</div>

<div id="finalText"
class="finalText">
</div>

<button onclick="location.reload()">
↻ VOLVER A INTENTAR
</button>

</div>

</section>


<script>

/* =========================================================
   VARIABLES DEL JUEGO
========================================================= */

let vidas = 2;

let tiempo = 300;

let amenaza = 0;

let puntaje = 0;

let habitacion = 0;

let intervalo;

let jugando = false;

let inventario = [];


/* =========================================================
   SONIDOS
   Se generan mediante Web Audio.
   No necesitas descargar archivos.
========================================================= */

let audioContext;

function iniciarAudio(){

    if(!audioContext){

        audioContext =
        new (
        window.AudioContext ||
        window.webkitAudioContext
        )();

    }

    if(audioContext.state==="suspended"){
        audioContext.resume();
    }
}


/* Sonido simple */

function beep(
frequency=440,
duration=.15,
type="square",
volume=.04
){

    if(!audioContext)return;

    const oscillator =
    audioContext.createOscillator();

    const gain =
    audioContext.createGain();

    oscillator.type=type;

    oscillator.frequency.value=frequency;

    gain.gain.setValueAtTime(
        volume,
        audioContext.currentTime
    );

    gain.gain.exponentialRampToValueAtTime(
        .001,
        audioContext.currentTime+duration
    );

    oscillator.connect(gain);

    gain.connect(audioContext.destination);

    oscillator.start();

    oscillator.stop(
        audioContext.currentTime+duration
    );
}


/* Sonido de error */

function sonidoError(){

    beep(100,.3,"sawtooth",.08);

    setTimeout(
        ()=>beep(55,.5,"sawtooth",.08),
        100
    );

}


/* Sonido correcto */

function sonidoCorrecto(){

    beep(440,.1,"sine",.05);

    setTimeout(
        ()=>beep(660,.15,"sine",.05),
        100
    );

}


/* Sonido de pasos */

function pasos(){

    beep(90,.12,"sine",.03);

    setTimeout(
        ()=>beep(70,.12,"sine",.03),
        180
    );

}


/* Sonido de alarma */

function alarma(){

    beep(600,.15,"square",.05);

    setTimeout(
        ()=>beep(300,.15,"square",.05),
        170
    );

}


/* =========================================================
   PREGUNTAS / HABITACIONES
========================================================= */

const habitaciones=[

{

nombre:"SALA DE SERVIDORES",

icon:"🖥️",

tipo:"pregunta",

titulo:"LA MÁQUINA INVISIBLE",

descripcion:
"Los servidores están encendidos. Las luces parpadean. Una pantalla comienza a escribir sola.",

pista:
"NO TENGO CUERPO. NO PUEDES TOCARME. SIN MÍ, ESTA MÁQUINA NO PODRÍA EJECUTAR SUS INSTRUCCIONES.",

pregunta:
"¿Qué está describiendo el sistema?",

opciones:[
"Software",
"Hardware",
"Electricidad",
"Internet"
],

correcta:0

},

{

nombre:"SALA DE HARDWARE",

icon:"🔧",

tipo:"pregunta",

titulo:"EL OBJETO QUE NO EXISTE",

descripcion:
"Hay cuatro objetos sobre una mesa. Tres puedes tocar. Uno pertenece al mundo invisible.",

pista:
"UNO DE ELLOS ESTÁ FORMADO POR PROGRAMAS E INSTRUCCIONES.",

pregunta:
"¿Cuál corresponde al software?",

opciones:[
"Teclado",
"Monitor",
"Sistema operativo",
"Procesador"
],

correcta:2

},

{

nombre:"ARCHIVO PROHIBIDO",

icon:"📁",

tipo:"pregunta",

titulo:"EL ARCHIVO QUE RESPIRA",

descripcion:
"Un archivo aparece y desaparece de la pantalla.",

pista:
"SOY UN CONJUNTO DE PROGRAMAS, DATOS E INSTRUCCIONES QUE PERMITEN REALIZAR TAREAS.",

pregunta:
"¿Qué concepto representa?",

opciones:[
"Software",
"Hardware",
"CPU",
"Memoria"
],

correcta:0

},

{

nombre:"SALA DE LICENCIAS",

icon:"📜",

tipo:"pregunta",

titulo:"EL CONTRATO",

descripcion:
"Encuentras un documento digital. Está lleno de reglas.",

pista:
"NO SOY EL PROGRAMA. ESTABLEZCO LAS CONDICIONES BAJO LAS CUALES PUEDES UTILIZARLO.",

pregunta:
"¿Qué es?",

opciones:[
"Licencia de software",
"Virus",
"Contraseña",
"Hardware"
],

correcta:0

},

{

nombre:"ARCHIVO LEGAL",

icon:"⚖️",

tipo:"pregunta",

titulo:"LAS CONDICIONES",

descripcion:
"La pantalla muestra permisos y restricciones.",

pista:
"PUEDO ESTABLECER DERECHOS, PERMISOS Y RESTRICCIONES PARA EL USUARIO.",

pregunta:
"¿Cuál es una función de una licencia?",

opciones:[
"Establecer condiciones de uso",
"Aumentar memoria RAM",
"Eliminar virus",
"Crear electricidad"
],

correcta:0

},

{

nombre:"SALA DE CONTRATOS",

icon:"🔐",

tipo:"pregunta",

titulo:"NO ROMPAS EL CONTRATO",

descripcion:
"Un usuario instaló un programa pero nunca revisó sus condiciones.",

pista:
"ANTES DE UTILIZAR EL SOFTWARE DEBES SABER QUÉ PUEDES Y QUÉ NO PUEDES HACER CON ÉL.",

pregunta:
"¿Por qué es importante conocer la licencia?",

opciones:[
"Porque establece condiciones de uso",
"Porque aumenta la velocidad",
"Porque cambia el procesador",
"Porque elimina el antivirus"
],

correcta:0

},

{

nombre:"PASILLO DE LAS PUERTAS",

icon:"🚪",

tipo:"puertas",

titulo:"LAS CUATRO PUERTAS"

},

{

nombre:"SALA FREEWARE",

icon:"🆓",

tipo:"pregunta",

titulo:"LA TRAMPA DEL GRATIS",

descripcion:
"La puerta dice FREEWARE.",

pista:
"PUEDES UTILIZARME SIN PAGAR, PERO ESO NO SIGNIFICA NECESARIAMENTE QUE PUEDAS MODIFICAR MI CÓDIGO.",

pregunta:
"¿Cuál afirmación es correcta?",

opciones:[
"Freeware siempre permite modificar el código",
"Freeware puede ser gratuito sin permitir modificar el código",
"Freeware es exactamente igual a software libre",
"Freeware obliga a publicar el código"
],

correcta:1

},

{

nombre:"SALA DE LIBERTADES",

icon:"🕊️",

tipo:"pregunta",

titulo:"LAS CUATRO LIBERTADES",

descripcion:
"El sistema escribe cuatro palabras: EJECUTAR, ESTUDIAR, MODIFICAR, COMPARTIR.",

pista:
"ESTAS LIBERTADES ESTÁN RELACIONADAS CON EL CONCEPTO DE SOFTWARE LIBRE.",

pregunta:
"¿Qué concepto representa?",

opciones:[
"Software libre",
"Software propietario",
"Hardware",
"Malware"
],

correcta:0

},

{

nombre:"TERMINAL OPEN SOURCE",

icon:"💻",

tipo:"pregunta",

titulo:"EL CÓDIGO ABIERTO",

descripcion:
"El código fuente está disponible. Sin embargo, las condiciones de la licencia siguen siendo importantes.",

pista:
"EL CÓDIGO FUENTE PUEDE ESTAR DISPONIBLE PARA ESTUDIARLO O MODIFICARLO SEGÚN LA LICENCIA.",

pregunta:
"¿Con qué concepto se relaciona principalmente?",

opciones:[
"Open Source",
"Hardware",
"Malware",
"Virus"
],

correcta:0

},

{

nombre:"OFICINA DE LA EMPRESA",

icon:"🏢",

tipo:"pregunta",

titulo:"EL CÓDIGO SECRETO",

descripcion:
"Una empresa quiere mantener su código cerrado y controlar su distribución.",

pista:
"EL PROPIETARIO QUIERE CONSERVAR UN ALTO NIVEL DE CONTROL SOBRE EL CÓDIGO.",

pregunta:
"¿Qué tipo de licencia podría ser adecuada?",

opciones:[
"Propietaria",
"Software libre obligatoriamente",
"Freeware obligatoriamente",
"Ninguna"
],

correcta:0

},

{

nombre:"TERMINAL CENTRAL",

icon:"☠️",

tipo:"pregunta",

titulo:"LA ÚLTIMA DECISIÓN",

descripcion:
"Has desarrollado un programa educativo. Quieres que otras personas puedan estudiar, modificar y compartir su código respetando las condiciones de la licencia.",

pista:
"LA LICENCIA DEBE SER COMPATIBLE CON LAS LIBERTADES QUE QUIERES OFRECER.",

pregunta:
"¿Qué opción podría ser adecuada?",

opciones:[
"Una licencia libre o de código abierto compatible con ese objetivo",
"Una licencia que prohíba modificar",
"No utilizar ninguna licencia",
"Elegir cualquier licencia sin leerla"
],

correcta:0

}

];


/* =========================================================
   INICIO
========================================================= */

function startGame(){

    iniciarAudio();

    jugando=true;

    document
    .getElementById("intro")
    .classList.remove("active");

    document
    .getElementById("game")
    .classList.add("active");

    mostrarHabitacion();

    intervalo=setInterval(contador,1000);

    beep(220,.3,"sawtooth",.04);

}


/* =========================================================
   CONTADOR
========================================================= */

function contador(){

    if(!jugando)return;

    tiempo--;

    let minutos=
    Math.floor(tiempo/60);

    let segundos=
    tiempo%60;

    document
    .getElementById("time")
    .textContent=
    String(minutos).padStart(2,"0")
    +":"+
    String(segundos).padStart(2,"0");

    document
    .getElementById("progress")
    .style.width=
    (tiempo/300*100)+"%";


    if(tiempo<=60){

        document
        .getElementById("timer")
        .classList.add("danger");

        alarma();

    }


    if(tiempo<=30){

        mostrarMensajeAmenaza();

    }


    if(tiempo<=0){

        perder(
        "EL TIEMPO TERMINÓ.\n\n"+
        "El sistema ha tomado el control."
        );

    }

}


/* =========================================================
   MOSTRAR HABITACIÓN
========================================================= */

function mostrarHabitacion(){

    if(habitacion>=habitaciones.length){

        ganar();

        return;

    }


    const h=
    habitaciones[habitacion];


    const content=
    document.getElementById("content");


    if(h.tipo==="puertas"){

        mostrarPuertas();

        return;

    }


    content.innerHTML=`

    <div class="roomTitle">

    HABITACIÓN ${habitacion+1}
    // ${h.nombre}

    </div>

    <div class="bigTitle">

    ${h.icon}
    ${h.titulo}

    </div>

    <div class="description">

    ${h.descripcion}

    </div>

    <div class="clue">

    <strong>PISTA ENCONTRADA:</strong>

    <br><br>

    "${h.pista}"

    </div>

    <div class="description">

    ${h.pregunta}

    </div>

    <div class="options">

    ${h.opciones.map(
    (opcion,i)=>`

    <button
    class="option"
    onclick="responder(${i})">

    ${String.fromCharCode(65+i)})
    ${opcion}

    </button>

    `).join("")}

    </div>

    `;


    pasos();

}


/* =========================================================
   PUERTAS
========================================================= */

function mostrarPuertas(){

    const content=
    document.getElementById("content");

    content.innerHTML=`

    <div class="roomTitle">
    PASILLO // ARCHIVO DE LICENCIAS
    </div>

    <div class="bigTitle">
    🚪 LAS CUATRO PUERTAS
    </div>

    <div class="description">

    El pasillo está completamente oscuro.

    <br><br>

    Cuatro puertas aparecen.

    <br><br>

    Solo una representa correctamente
    las libertades que buscas.

    </div>

    <div class="clue">

    <strong>PISTA:</strong>

    <br><br>

    "No confundas GRATIS con LIBRE.
    Busca una puerta relacionada con
    las libertades del usuario."

    </div>

    <div class="doors">

    <button
    class="door"
    onclick="puerta('open')">

    <span class="roomIcon">🔓</span>

    OPEN SOURCE

    </button>

    <button
    class="door"
    onclick="puerta('prop')">

    <span class="roomIcon">🔐</span>

    PROPIETARIA

    </button>

    <button
    class="door"
    onclick="puerta('free')">

    <span class="roomIcon">🆓</span>

    FREEWARE

    </button>

    <button
    class="door"
    onclick="puerta('libre')">

    <span class="roomIcon">⚖️</span>

    SOFTWARE LIBRE

    </button>

    </div>

    `;

}


/* =========================================================
   RESPUESTA
========================================================= */

function responder(respuesta){

    const h=
    habitaciones[habitacion];


    if(respuesta===h.correcta){

        puntaje+=100;

        sonidoCorrecto();

        inventario.push(
        "Pista "+(habitacion+1)
        );

        habitacion++;

        amenaza=Math.max(
        0,
        amenaza-4
        );

        actualizarAmenaza();

        setTimeout(
        mostrarHabitacion,
        500
        );

    }else{

        error();

    }

}


/* =========================================================
   PUERTAS
========================================================= */

function puerta(tipo){

    if(
    tipo==="open" ||
    tipo==="libre"
    ){

        puntaje+=100;

        sonidoCorrecto();

        habitacion++;

        setTimeout(
        mostrarHabitacion,
        500
        );

    }else{

        error();

    }

}


/* =========================================================
   ERROR
========================================================= */

function error(){

    vidas--;

    amenaza+=25;

    if(amenaza>100)
    amenaza=100;

    document
    .getElementById("lives")
    .textContent=vidas;

    actualizarAmenaza();

    sonidoError();

    mostrarSusto();


    if(vidas<=0){

        setTimeout(
        function(){

            perder(
            "Has perdido tus 2 vidas.\n\n"+
            "El sistema ya no puede contenerlo."
            );

        },
        900
        );

    }

}


/* =========================================================
   AMENAZA
========================================================= */

function actualizarAmenaza(){

    document
    .getElementById("threatFill")
    .style.width=
    amenaza+"%";

    document
    .getElementById("threatNumber")
    .textContent=
    amenaza+"%";


    if(amenaza>=75){

        document.body.style.background="#160202";

    }


    if(amenaza>=100){

        setTimeout(
        mostrarSusto,
        300
        );

    }

}


/* =========================================================
   SUSTO
========================================================= */

function mostrarSusto(){

    const j=
    document.getElementById("jumpscare");

    j.classList.add("show");

    beep(45,.7,"sawtooth",.1);

    setTimeout(
    ()=>{
        j.classList.remove("show");
    },
    750
    );

}


/* =========================================================
   MENSAJES DE AMENAZA
========================================================= */

function mostrarMensajeAmenaza(){

    const mensajes=[

    "ÉL TE ESTÁ OBSERVANDO.",

    "NO MIRES DETRÁS DE TI.",

    "EL TIEMPO SE TERMINA.",

    "ÉL YA SABE TU RESPUESTA.",

    "NO COMETAS OTRO ERROR."

    ];

    const mensaje=
    mensajes[
    Math.floor(
    Math.random()*mensajes.length
    )
    ];

    const content=
    document.getElementById("content");

    const anterior=
    content.innerHTML;

    content.innerHTML=`

    <div class="warningBox">

    ⚠ ALERTA DEL SISTEMA

    <br><br>

    ${mensaje}

    </div>

    `;

    setTimeout(
    ()=>{
        if(jugando){
            content.innerHTML=anterior;
        }
    },
    900
    );

}


/* =========================================================
   FINAL PERDER
========================================================= */

function perder(mensaje){

    if(!jugando)return;

    jugando=false;

    clearInterval(intervalo);

    sonidoError();

    document
    .getElementById("game")
    .classList.remove("active");

    document
    .getElementById("final")
    .classList.add("active");

    document
    .getElementById("finalTitle")
    .textContent="FRACASASTE";

    document
    .getElementById("finalTitle")
    .className="failTitle";

    document
    .getElementById("finalText")
    .textContent=
    mensaje+
    "\n\nPUNTAJE: "+
    puntaje+
    "\n\nEL SISTEMA TE HA ENCONTRADO.";

    document
    .getElementById("monster")
    .style.display="block";

}


/* =========================================================
   FINAL GANAR
========================================================= */

function ganar(){

    jugando=false;

    clearInterval(intervalo);

    sonidoCorrecto();

    document
    .getElementById("game")
    .classList.remove("active");

    document
    .getElementById("final")
    .classList.add("active");

    const monster=
    document.getElementById("monster");

    monster.style.display="none";

    const title=
    document.getElementById("finalTitle");

    title.textContent=
    "HAS ESCAPADO";

    title.className=
    "successTitle";

    document
    .getElementById("finalText")
    .textContent=

    "SISTEMA DESBLOQUEADO.\n\n"+
    "12/12 PRUEBAS SUPERADAS.\n\n"+
    "AMENAZA: "+amenaza+"%.\n\n"+
    "VIDAS RESTANTES: "+vidas+".\n\n"+
    "PUNTAJE FINAL: "+puntaje+".\n\n"+
    "Comprendiste qué es el software,\n"+
    "qué es una licencia de software,\n"+
    "los principales tipos de licencia\n"+
    "y por qué la licencia adecuada\n"+
    "depende de los objetivos del proyecto.\n\n"+
    "EL LABORATORIO TE HA DEJADO ESCAPAR.";

}


/* =========================================================
   TECLADO
========================================================= */

document.addEventListener(
"keydown",
function(e){

    if(
    e.key==="Enter" &&
    document
    .getElementById("intro")
    .classList.contains("active")
    ){

        startGame();

    }

});


</script>

</body>
</html>
