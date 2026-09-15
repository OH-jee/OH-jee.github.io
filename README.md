<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Operation: Patawanin Ka ❤️</title>

<style>
*{
    box-sizing:border-box;
    margin:0;
    padding:0;
    -webkit-tap-highlight-color:transparent;
}

body{
    min-height:100vh;
    overflow:hidden;
    font-family:Arial,sans-serif;
    color:white;
    background:
        radial-gradient(circle at 20% 20%,#402080 0%,transparent 30%),
        radial-gradient(circle at 80% 80%,#a51d5c 0%,transparent 30%),
        linear-gradient(135deg,#08051a,#13082c,#070414);
}

/* STARS */

.stars{
    position:fixed;
    inset:0;
    pointer-events:none;
}

.star{
    position:absolute;
    width:3px;
    height:3px;
    background:white;
    border-radius:50%;
    opacity:.7;
    animation:twinkle 2s infinite alternate;
}

@keyframes twinkle{
    from{opacity:.2;transform:scale(.7)}
    to{opacity:1;transform:scale(1.4)}
}

/* PAGES */

.page{
    position:absolute;
    inset:0;
    display:none;
    justify-content:center;
    align-items:center;
    padding:20px;
}

.page.active{
    display:flex;
    animation:show .6s ease;
}

@keyframes show{
    from{opacity:0;transform:scale(.95)}
    to{opacity:1;transform:scale(1)}
}

.card{
    width:100%;
    max-width:650px;
    max-height:90vh;
    overflow:auto;
    padding:35px 25px;
    text-align:center;
    border-radius:30px;
    background:rgba(255,255,255,.08);
    border:1px solid rgba(255,255,255,.16);
    backdrop-filter:blur(18px);
    box-shadow:0 25px 80px rgba(0,0,0,.5);
}

.card::-webkit-scrollbar{
    display:none;
}

.emoji{
    font-size:75px;
    animation:bounce 1.5s infinite;
}

@keyframes bounce{
    50%{transform:translateY(-12px) rotate(5deg)}
}

h1{
    font-size:42px;
    margin:15px 0;
}

h2{
    font-size:30px;
    margin-bottom:15px;
}

p{
    color:#f4e5f0;
    line-height:1.7;
    margin:12px 0;
}

button{
    border:none;
    padding:15px 22px;
    margin:7px;
    border-radius:50px;
    background:linear-gradient(135deg,#ff5d9a,#b957ff);
    color:white;
    font-weight:bold;
    font-size:16px;
    cursor:pointer;
    transition:.2s;
    box-shadow:0 8px 25px #0005;
}

button:active{
    transform:scale(.92);
}

button:hover{
    transform:translateY(-3px);
}

.secondary{
    background:#ffffff12;
    border:1px solid #ffffff22;
}

.small{
    font-size:13px;
    opacity:.65;
}

/* GAME */

.game{
    position:relative;
    height:430px;
    margin-top:15px;
    border-radius:25px;
    overflow:hidden;
    background:rgba(0,0,0,.18);
    border:1px solid #ffffff12;
}

.game-heart{
    position:absolute;
    font-size:42px;
    cursor:pointer;
    user-select:none;
    animation:heartFloat 1s ease;
    filter:drop-shadow(0 0 12px #ff65a5);
}

@keyframes heartFloat{
    from{transform:scale(.3);opacity:0}
    to{transform:scale(1);opacity:1}
}

.scorebox{
    display:flex;
    justify-content:space-around;
    margin:15px 0;
    font-size:19px;
}

.meter{
    width:100%;
    height:15px;
    background:#ffffff15;
    border-radius:20px;
    overflow:hidden;
    margin:15px 0;
}

.meter-fill{
    height:100%;
    width:0%;
    transition:.3s;
    background:linear-gradient(90deg,#ff4f91,#c15cff);
}

#gameMessage{
    min-height:30px;
    font-weight:bold;
}

/* FINAL */

.final-heart{
    font-size:90px;
    animation:pulse 1s infinite;
}

@keyframes pulse{
    50%{transform:scale(1.15)}
}

.letter{
    text-align:left;
    background:#ffffff09;
    padding:22px;
    border-radius:20px;
    border:1px solid #ffffff15;
    margin-top:20px;
}

.letter p{
    margin-bottom:16px;
}

/* FLOATING */

.float{
    position:fixed;
    bottom:-50px;
    pointer-events:none;
    font-size:30px;
    animation:float 4s linear forwards;
    z-index:999;
}

@keyframes float{
    to{
        transform:translateY(-110vh) rotate(360deg);
        opacity:0;
    }
}

/* SHAKE */

.shake{
    animation:shake .4s;
}

@keyframes shake{
    25%{transform:translateX(-8px)}
    50%{transform:translateX(8px)}
    75%{transform:translateX(-8px)}
}

/* MOBILE */

@media(max-width:500px){

    h1{
        font-size:34px;
    }

    h2{
        font-size:25px;
    }

    .card{
        padding:28px 18px;
    }

    .game{
        height:390px;
    }

}
</style>
</head>

<body>

<div class="stars" id="stars"></div>


<!-- PAGE 1 -->

<section class="page active" id="page1">

<div class="card">

    <div class="emoji">🥺</div>

    <h1>HELLO, MISS GALIT 😭</h1>

    <p>
        Hi ikaw. Yes ikaw. 👀
    </p>

    <p>
        May ginawa akong maliit na bagay
        kasi gusto kong kahit konti...
        <b>mapangiti ka ulit.</b> ❤️
    </p>

    <p>
        Pero hindi kita bibigyan ng boring na
        "sorry sorry sorry" page. 😂
    </p>

    <button onclick="go(2)">
        Enter Mission 🎮
    </button>

</div>

</section>


<!-- PAGE 2 -->

<section class="page" id="page2">

<div class="card">

    <div class="emoji">🕵️‍♂️</div>

    <h2>OPERATION: MAKE HER SMILE</h2>

    <p>
        Mission objective:
    </p>

    <p>
        <b>Mapangiti si Baby kahit konti. 😭❤️</b>
    </p>

    <div class="letter">

        <p>
            ⚠️ Warning:
            This game contains excessive lambing,
            bad jokes, and one boyfriend na
            medyo desperate bumawi. 😂
        </p>

    </div>

    <button onclick="go(3)">
        Start Game 🎮
    </button>

</div>

</section>


<!-- PAGE 3 GAME -->

<section class="page" id="page3">

<div class="card">

    <h2>❤️ CATCH THE HEARTS ❤️</h2>

    <p>
        Tap the hearts bago sila mawala!
    </p>

    <div class="scorebox">

        <div>
            Score:
            <b id="score">0</b>
        </div>

        <div>
            Time:
            <b id="time">20</b>
        </div>

    </div>

    <div class="meter">
        <div class="meter-fill" id="meter"></div>
    </div>

    <div class="game" id="game"></div>

    <div id="gameMessage">
        Ready? 😈
    </div>

</div>

</section>


<!-- PAGE 4 -->

<section class="page" id="page4">

<div class="card">

    <div class="emoji">😂</div>

    <h2>GAME REPORT</h2>

    <p id="gameResult"></p>

    <div class="letter">

        <p>
            Scientific analysis says:
        </p>

        <p>
            <b>Mas mabilis kang mag-tap kaysa
            sa akin mag-isip ng pambawi. 😭</b>
        </p>

        <p>
            Kaya ikaw talaga panalo. 😂❤️
        </p>

    </div>

    <button onclick="go(5)">
        Continue 👀
    </button>

</div>

</section>


<!-- PAGE 5 -->

<section class="page" id="page5">

<div class="card">

    <div class="emoji">🤔</div>

    <h2>IMPORTANT QUESTION</h2>

    <p>
        Choose wisely...
    </p>

    <p>
        Kapag may tampuhan,
        ano ang dapat gawin?
    </p>

    <button onclick="wrong()">
        Magtago 😭
    </button>

    <button onclick="wrong()">
        Matulog 😴
    </button>

    <button onclick="wrong()">
        Magkunwaring walang nangyari 💀
    </button>

    <button onclick="right()">
        Makinig + magsorry + bumawi ❤️
    </button>

    <p id="choiceResult"></p>

</div>

</section>


<!-- PAGE 6 -->

<section class="page" id="page6">

<div class="card">

    <div class="final-heart">💗</div>

    <h1>Okay...</h1>

    <p>
        Joke time is over. 🥺
    </p>

    <div class="letter">

        <p>
            Alam kong galit at tampo ka sa akin,
            at hindi ko gustong i-ignore lang
            yung nararamdaman mo.
        </p>

        <p>
            I'm really sorry kung nasaktan kita
            or may nagawa ako na hindi naging okay.
        </p>

        <p>
            Hindi ko ine-expect na mawawala agad
            yung tampo mo dahil lang sa website na 'to.
        </p>

        <p>
            Gusto ko lang sabihin na
            <b>importante ka sa akin.</b>
        </p>

        <p>
            At kung may chance akong bumawi,
            gusto kong gawin ko nang maayos.
        </p>

        <p>
            Pero for now...
            sana kahit isang maliit na smile
            lang ang nakuha ko mula sa'yo. 🥺❤️
        </p>

        <p>
            And yes...
            ikaw pa rin ang favorite kong tao
            kahit minsan ikaw ang dahilan
            kung bakit kinakabahan ako. 😂❤️
        </p>

        <p style="text-align:center;font-size:22px;">
            <b>Sorry. ❤️</b>
        </p>

    </div>

    <button onclick="go(7)">
        May last surprise pa 👀
    </button>

</div>

</section>


<!-- PAGE 7 -->

<section class="page" id="page7">

<div class="card">

    <div class="final-heart">🎉</div>

    <h1>MISSION COMPLETE!</h1>

    <p>
        If you smiled kahit konti...
    </p>

    <h2>
        SUCCESS! 😭❤️
    </h2>

    <p>
        If hindi...
        okay lang.
        <br>
        May rematch tayo. 😂
    </p>

    <button onclick="party()">
        MAKE IT RAIN ❤️
    </button>

    <p class="small">
        P.S. Hindi man perfect ang ginawa kong game,
        sincere yung reason kung bakit ko ginawa.
    </p>

</div>

</section>


<script>

/* STARS */

const stars=document.getElementById("stars");

for(let i=0;i<100;i++){

    const s=document.createElement("div");

    s.className="star";

    s.style.left=Math.random()*100+"%";
    s.style.top=Math.random()*100+"%";

    s.style.animationDelay=
        Math.random()*2+"s";

    stars.appendChild(s);
}


/* PAGE NAVIGATION */

let current=1;

function go(page){

    document.getElementById("page"+current)
        .classList.remove("active");

    document.getElementById("page"+page)
        .classList.add("active");

    current=page;

}


/* GAME */

let score=0;
let time=20;
let gameRunning=false;
let timer;
let heartSpawner;

function startGame(){

    score=0;
    time=20;
    gameRunning=true;

    document.getElementById("score").innerText=score;
    document.getElementById("time").innerText=time;

    heartSpawner=setInterval(createHeart,700);

    timer=setInterval(()=>{

        time--;

        document.getElementById("time").innerText=time;

        if(time<=0){
            endGame();
        }

    },1000);

}


/* Automatically start when game page opens */

const observer=new MutationObserver(()=>{

    if(document.getElementById("page3")
        .classList.contains("active")
        && !gameRunning){

        startGame();

    }

});

observer.observe(
    document.getElementById("page3"),
    {attributes:true}
);


/* CREATE HEART */

function createHeart(){

    if(!gameRunning)return;

    const game=document.getElementById("game");

    const heart=document.createElement("div");

    heart.className="game-heart";

    heart.innerText=
        ["❤️","💗","💖","💕","💘"]
        [Math.floor(Math.random()*5)];

    heart.style.left=
        Math.random()*85+"%";

    heart.style.top=
        Math.random()*85+"%";

    heart.onclick=()=>{

        score++;

        document.getElementById("score")
            .innerText=score;

        document.getElementById("meter")
            .style.width=Math.min(score*5,100)+"%";

        document.getElementById("gameMessage")
            .innerText=randomMessage();

        heart.remove();

        pop(heart);

    };

    game.appendChild(heart);

    setTimeout(()=>{

        if(heart.parentElement)
            heart.remove();

    },1200);

}


/* FUNNY MESSAGES */

function randomMessage(){

    const messages=[

        "AYAN! ❤️",
        "Nice one! 😂",
        "Isa pa! 👀",
        "Grabe bilis! 😭",
        "Certified heart catcher! 💗",
        "Okay may talent ka pala. 😂",
        "Pati puso ko nahuli mo. Char. 😭",
        "Winner ka na! ❤️",
        "HAHAHAHA tap ulit! 😂",
        "Cute mo naman. 🥺"

    ];

    return messages[
        Math.floor(Math.random()*messages.length)
    ];

}


/* END GAME */

function endGame(){

    gameRunning=false;

    clearInterval(timer);
    clearInterval(heartSpawner);

    document.getElementById("gameResult")
        .innerHTML=
        "Final Score: <b>"+score+"</b> ❤️";

    go(4);

}


/* WRONG ANSWERS */

function wrong(){

    const messages=[

        "❌ WRONG! Wag kang gagaya sa'kin. 😭",
        "❌ Ay hindi! Lalo kang tatampuhan. 😂",
        "❌ Certified bad idea. 💀",
        "❌ Nope. Takbo ka agad sa apology department. 😭"

    ];

    document.getElementById("choiceResult")
        .innerText=
        messages[
            Math.floor(Math.random()*messages.length)
        ];

    document.querySelector("#page5 .card")
        .classList.add("shake");

    setTimeout(()=>{
        document.querySelector("#page5 .card")
            .classList.remove("shake");
    },400);

}


/* RIGHT ANSWER */

function right(){

    document.getElementById("choiceResult")
        .innerText=
        "✅ CORRECT! Marunong ka pala. 😭❤️";

    setTimeout(()=>{
        go(6);
    },1200);

}


/* FLOATING PARTY */

function party(){

    for(let i=0;i<80;i++){

        setTimeout(()=>{

            const f=document.createElement("div");

            f.className="float";

            f.innerText=
                [
                    "❤️",
                    "💕",
                    "💗",
                    "💖",
                    "✨",
                    "🌸",
                    "🥺",
                    "🎉"
                ][Math.floor(Math.random()*8)];

            f.style.left=Math.random()*100+"vw";

            f.style.animationDuration=
                (2+Math.random()*3)+"s";

            document.body.appendChild(f);

            setTimeout(()=>{
                f.remove();
            },5000);

        },i*35);

    }

}


/* CLICK POP */

function pop(){

    for(let i=0;i<3;i++){

        const f=document.createElement("div");

        f.className="float";

        f.innerText="💗";

        f.style.left=
            (30+Math.random()*40)+"vw";

        f.style.bottom="30%";

        document.body.appendChild(f);

        setTimeout(()=>{
            f.remove();
        },2500);

    }

}

</script>

</body>
</html>
```
