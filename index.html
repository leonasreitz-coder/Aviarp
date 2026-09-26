```html
<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Team Abstimmung</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: 'Inter', sans-serif;
    background: #030303;
    color: white;
    min-height: 100vh;
    overflow-x: hidden;
}

/* =========================
   ANIMIERTER HINTERGRUND
========================= */

.background {
    position: fixed;
    inset: 0;
    z-index: -10;
    overflow: hidden;
    background:
        radial-gradient(circle at 15% 20%, rgba(80,80,80,.18), transparent 30%),
        radial-gradient(circle at 85% 15%, rgba(255,255,255,.07), transparent 25%),
        radial-gradient(circle at 50% 90%, rgba(120,120,120,.10), transparent 35%),
        #030303;
}

.background::before {
    content: "";
    position: absolute;
    width: 900px;
    height: 900px;
    left: -350px;
    top: -400px;
    border-radius: 50%;
    background: radial-gradient(circle, rgba(255,255,255,.09), transparent 65%);
    filter: blur(40px);
    animation: floatOne 12s ease-in-out infinite alternate;
}

.background::after {
    content: "";
    position: absolute;
    width: 800px;
    height: 800px;
    right: -350px;
    bottom: -350px;
    border-radius: 50%;
    background: radial-gradient(circle, rgba(150,150,150,.10), transparent 65%);
    filter: blur(45px);
    animation: floatTwo 15s ease-in-out infinite alternate;
}

@keyframes floatOne {
    from { transform: translate(0,0) scale(1); }
    to { transform: translate(180px,120px) scale(1.25); }
}

@keyframes floatTwo {
    from { transform: translate(0,0) scale(1); }
    to { transform: translate(-160px,-130px) scale(1.2); }
}

/* Lichtlinien */

.light {
    position: fixed;
    height: 1px;
    width: 80vw;
    background: linear-gradient(90deg, transparent, rgba(255,255,255,.20), transparent);
    filter: blur(1px);
    z-index: -5;
    opacity: .5;
}

.light.one {
    top: 20%;
    left: -20%;
    transform: rotate(-18deg);
    animation: lightMove 10s linear infinite;
}

.light.two {
    top: 60%;
    left: -30%;
    transform: rotate(14deg);
    animation: lightMove 14s linear infinite reverse;
}

.light.three {
    top: 82%;
    left: -20%;
    transform: rotate(-8deg);
    animation: lightMove 18s linear infinite;
}

@keyframes lightMove {
    0% { transform: translateX(-30%) rotate(-15deg); }
    100% { transform: translateX(160%) rotate(-15deg); }
}

/* Partikel */

.particles {
    position: fixed;
    inset: 0;
    z-index: -4;
    pointer-events: none;
}

.particle {
    position: absolute;
    width: 3px;
    height: 3px;
    background: white;
    border-radius: 50%;
    opacity: .35;
    box-shadow: 0 0 10px white;
    animation: particleFloat linear infinite;
}

@keyframes particleFloat {
    from {
        transform: translateY(110vh) scale(.5);
        opacity: 0;
    }

    20% {
        opacity: .4;
    }

    80% {
        opacity: .25;
    }

    to {
        transform: translateY(-10vh) scale(1.2);
        opacity: 0;
    }
}

/* =========================
   HEADER
========================= */

header {
    position: relative;
    padding: 80px 20px 60px;
    text-align: center;
}

.header-line {
    width: 100px;
    height: 3px;
    margin: 0 auto 25px;
    border-radius: 10px;
    background: linear-gradient(90deg, transparent, white, transparent);
    box-shadow: 0 0 20px rgba(255,255,255,.6);
}

h1 {
    font-size: clamp(42px, 7vw, 82px);
    font-weight: 800;
    letter-spacing: -4px;
    background: linear-gradient(180deg, #fff, #8d8d8d);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    text-shadow: 0 0 40px rgba(255,255,255,.12);
}

.subtitle {
    margin-top: 15px;
    color: #888;
    font-size: 15px;
    letter-spacing: 2px;
    text-transform: uppercase;
}

/* =========================
   CONTENT
========================= */

.container {
    width: min(1250px, 92%);
    margin: auto;
    padding-bottom: 100px;
}

.category {
    margin: 45px 0;
}

.category-title {
    display: flex;
    align-items: center;
    gap: 14px;
    margin-bottom: 22px;
}

.category-title h2 {
    font-size: 25px;
    font-weight: 700;
}

.category-line {
    height: 1px;
    flex: 1;
    background: linear-gradient(90deg, rgba(255,255,255,.25), transparent);
}

/* =========================
   CARDS
========================= */

.members {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(210px, 1fr));
    gap: 18px;
}

.member {
    position: relative;
    overflow: hidden;
    padding: 25px;
    min-height: 145px;
    border: 1px solid rgba(255,255,255,.08);
    border-radius: 18px;
    background: rgba(15,15,15,.72);
    backdrop-filter: blur(18px);
    transition: .35s ease;
}

.member::before {
    content: "";
    position: absolute;
    inset: 0;
    background: linear-gradient(
        135deg,
        rgba(255,255,255,.08),
        transparent 45%
    );
    opacity: 0;
    transition: .35s;
}

.member:hover {
    transform: translateY(-7px);
    border-color: var(--rank-color);
    box-shadow:
        0 15px 50px rgba(0,0,0,.5),
        0 0 30px var(--rank-glow);
}

.member:hover::before {
    opacity: 1;
}

.rank-dot {
    width: 10px;
    height: 10px;
    display: inline-block;
    border-radius: 50%;
    background: var(--rank-color);
    box-shadow: 0 0 15px var(--rank-color);
    margin-right: 8px;
}

.member-name {
    position: relative;
    font-size: 19px;
    font-weight: 700;
    margin-bottom: 9px;
}

.member-role {
    position: relative;
    color: var(--rank-color);
    font-size: 12px;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 1.5px;
}

.vote-button {
    position: relative;
    width: 100%;
    margin-top: 20px;
    padding: 11px;
    border: 1px solid rgba(255,255,255,.12);
    border-radius: 10px;
    background: rgba(255,255,255,.04);
    color: white;
    cursor: pointer;
    font-weight: 600;
    transition: .25s;
}

.vote-button:hover {
    background: var(--rank-color);
    color: #050505;
    border-color: var(--rank-color);
    box-shadow: 0 0 25px var(--rank-glow);
}

.vote-button.voted {
    background: var(--rank-color);
    color: #050505;
}

.votes {
    position: relative;
    margin-top: 12px;
    color: #777;
    font-size: 12px;
}

/* =========================
   COLORS
========================= */

.supporter {
    --rank-color: #38e87c;
    --rank-glow: rgba(56,232,124,.30);
}

.moderator {
    --rank-color: #4287ff;
    --rank-glow: rgba(66,135,255,.30);
}

.analyst {
    --rank-color: #777;
    --rank-glow: rgba(150,150,150,.25);
}

.fraktion {
    --rank-color: #72d9ff;
    --rank-glow: rgba(114,217,255,.30);
}

.admin {
    --rank-color: #ffd83d;
    --rank-glow: rgba(255,216,61,.30);
}

.teamleitung {
    --rank-color: #ff62c9;
    --rank-glow: rgba(255,98,201,.30);
}

.projektleitung {
    --rank-color: #ff4747;
    --rank-glow: rgba(255,71,71,.30);
}

.projektinhaber {
    --rank-color: #ffffff;
    --rank-glow: rgba(255,255,255,.35);
}

/* =========================
   INFO BOX
========================= */

.info {
    margin-top: 70px;
    padding: 30px;
    border-radius: 20px;
    border: 1px solid rgba(255,255,255,.08);
    background: rgba(10,10,10,.7);
    backdrop-filter: blur(20px);
    text-align: center;
}

.info h3 {
    font-size: 22px;
    margin-bottom: 10px;
}

.info p {
    color: #777;
    line-height: 1.7;
}

/* =========================
   FOOTER
========================= */

footer {
    padding: 35px 20px;
    text-align: center;
    color: #555;
    border-top: 1px solid rgba(255,255,255,.06);
    font-size: 13px;
}

/* =========================
   MOBILE
========================= */

@media(max-width:600px) {

    header {
        padding-top: 55px;
    }

    h1 {
        letter-spacing: -2px;
    }

    .members {
        grid-template-columns: 1fr;
    }

    .category-title h2 {
        font-size: 21px;
    }
}
</style>
</head>

<body>

<div class="background"></div>

<div class="light one"></div>
<div class="light two"></div>
<div class="light three"></div>

<div class="particles" id="particles"></div>

<header>

    <div class="header-line"></div>

    <h1>Team Abstimmung</h1>

    <p class="subtitle">
        Bester Teamler der Woche
    </p>

</header>

<main class="container">

    <!-- SUPPORTER -->

    <section class="category">
        <div class="category-title">
            <h2>🟢 Supporter</h2>
            <div class="category-line"></div>
        </div>

        <div class="members">

            <div class="member supporter" data-name="Damien" data-role="Supporter">
                <div class="member-name">
                    <span class="rank-dot"></span>
                    Damien
                </div>

                <div class="member-role">Supporter</div>

                <button class="vote-button">Für Damien abstimmen</button>

                <div class="votes">0 Stimmen</div>
            </div>

        </div>
    </section>


    <!-- MODERATOR -->

    <section class="category">
        <div class="category-title">
            <h2>🔵 Moderator</h2>
            <div class="category-line"></div>
        </div>

        <div class="members">

            <div class="member moderator" data-name="Nuri" data-role="Moderator">
                <div class="member-name"><span class="rank-dot"></span>Nuri</div>
                <div class="member-role">Moderator</div>
                <button class="vote-button">Für Nuri abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

            <div class="member moderator" data-name="Jiyo" data-role="Moderator">
                <div class="member-name"><span class="rank-dot"></span>Jiyo</div>
                <div class="member-role">Moderator</div>
                <button class="vote-button">Für Jiyo abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

            <div class="member moderator" data-name="Peter" data-role="Moderator">
                <div class="member-name"><span class="rank-dot"></span>Peter</div>
                <div class="member-role">Moderator</div>
                <button class="vote-button">Für Peter abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

        </div>
    </section>


    <!-- ANALYST -->

    <section class="category">
        <div class="category-title">
            <h2>⚫ Analyst</h2>
            <div class="category-line"></div>
        </div>

        <div class="members">

            <div class="member analyst" data-name="Adrian" data-role="Analyst">
                <div class="member-name"><span class="rank-dot"></span>Adrian</div>
                <div class="member-role">Analyst</div>
                <button class="vote-button">Für Adrian abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

            <div class="member analyst" data-name="Jan" data-role="Analyst">
                <div class="member-name"><span class="rank-dot"></span>Jan</div>
                <div class="member-role">Analyst</div>
                <button class="vote-button">Für Jan abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

            <div class="member analyst" data-name="Reji" data-role="Analyst">
                <div class="member-name"><span class="rank-dot"></span>Reji</div>
                <div class="member-role">Analyst</div>
                <button class="vote-button">Für Reji abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

            <div class="member analyst" data-name="Rayk" data-role="Analyst">
                <div class="member-name"><span class="rank-dot"></span>Rayk</div>
                <div class="member-role">Analyst</div>
                <button class="vote-button">Für Rayk abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

            <div class="member analyst" data-name="RyanArafat" data-role="Analyst">
                <div class="member-name"><span class="rank-dot"></span>RyanArafat</div>
                <div class="member-role">Analyst</div>
                <button class="vote-button">Für RyanArafat abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

        </div>
    </section>


    <!-- FRAKTIONSVERWALTUNG -->

    <section class="category">
        <div class="category-title">
            <h2>🔷 Fraktionsverwaltung</h2>
            <div class="category-line"></div>
        </div>

        <div class="members">

            <div class="member fraktion" data-name="Amin" data-role="Fraktionsverwaltung">
                <div class="member-name"><span class="rank-dot"></span>Amin</div>
                <div class="member-role">Fraktionsverwaltung</div>
                <button class="vote-button">Für Amin abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

            <div class="member fraktion" data-name="Damien" data-role="Fraktionsverwaltung">
                <div class="member-name"><span class="rank-dot"></span>Damien</div>
                <div class="member-role">Fraktionsverwaltung</div>
                <button class="vote-button">Für Damien abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

            <div class="member fraktion" data-name="Kdot" data-role="Fraktionsverwaltung">
                <div class="member-name"><span class="rank-dot"></span>Kdot</div>
                <div class="member-role">Fraktionsverwaltung</div>
                <button class="vote-button">Für Kdot abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

            <div class="member fraktion" data-name="Syroo" data-role="Fraktionsverwaltung">
                <div class="member-name"><span class="rank-dot"></span>Syroo</div>
                <div class="member-role">Fraktionsverwaltung</div>
                <button class="vote-button">Für Syroo abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

            <div class="member fraktion" data-name="Hamed" data-role="Fraktionsverwaltung">
                <div class="member-name"><span class="rank-dot"></span>Hamed</div>
                <div class="member-role">Fraktionsverwaltung</div>
                <button class="vote-button">Für Hamed abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

            <div class="member fraktion" data-name="Enso" data-role="Fraktionsverwaltung">
                <div class="member-name"><span class="rank-dot"></span>Enso</div>
                <div class="member-role">Fraktionsverwaltung</div>
                <button class="vote-button">Für Enso abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

        </div>
    </section>


    <!-- ADMIN -->

    <section class="category">
        <div class="category-title">
            <h2>🟡 Admin</h2>
            <div class="category-line"></div>
        </div>

        <div class="members">

            <div class="member admin" data-name="Antonio" data-role="Admin">
                <div class="member-name"><span class="rank-dot"></span>Antonio</div>
                <div class="member-role">Admin</div>
                <button class="vote-button">Für Antonio abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

            <div class="member admin" data-name="Leon" data-role="Admin">
                <div class="member-name"><span class="rank-dot"></span>Leon</div>
                <div class="member-role">Admin</div>
                <button class="vote-button">Für Leon abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

            <div class="member admin" data-name="matron3" data-role="Admin">
                <div class="member-name"><span class="rank-dot"></span>matron3</div>
                <div class="member-role">Admin</div>
                <button class="vote-button">Für matron3 abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

        </div>
    </section>


    <!-- TEAMLEITUNG -->

    <section class="category">
        <div class="category-title">
            <h2>🩷 Teamleitung</h2>
            <div class="category-line"></div>
        </div>

        <div class="members">

            <div class="member teamleitung" data-name="3M!L" data-role="Teamleitung">
                <div class="member-name"><span class="rank-dot"></span>3M!L</div>
                <div class="member-role">Teamleitung</div>
                <button class="vote-button">Für 3M!L abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

        </div>
    </section>


    <!-- PROJEKTLEITUNG -->

    <section class="category">
        <div class="category-title">
            <h2>🔴 Projektleitung</h2>
            <div class="category-line"></div>
        </div>

        <div class="members">

            <div class="member projektleitung" data-name="Hamed" data-role="Projektleitung">
                <div class="member-name"><span class="rank-dot"></span>Hamed</div>
                <div class="member-role">Projektleitung</div>
                <button class="vote-button">Für Hamed abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

            <div class="member projektleitung" data-name="Enso" data-role="Projektleitung">
                <div class="member-name"><span class="rank-dot"></span>Enso</div>
                <div class="member-role">Projektleitung</div>
                <button class="vote-button">Für Enso abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

            <div class="member projektleitung" data-name="Loco" data-role="Projektleitung">
                <div class="member-name"><span class="rank-dot"></span>Loco</div>
                <div class="member-role">Projektleitung</div>
                <button class="vote-button">Für Loco abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

            <div class="member projektleitung" data-name="Sonic" data-role="Projektleitung">
                <div class="member-name"><span class="rank-dot"></span>Sonic</div>
                <div class="member-role">Projektleitung</div>
                <button class="vote-button">Für Sonic abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

        </div>
    </section>


    <!-- PROJEKTINHABER -->

    <section class="category">
        <div class="category-title">
            <h2>⚪ Projektinhaber</h2>
            <div class="category-line"></div>
        </div>

        <div class="members">

            <div class="member projektinhaber" data-name="Benjamin" data-role="Projektinhaber">
                <div class="member-name"><span class="rank-dot"></span>Benjamin</div>
                <div class="member-role">Projektinhaber</div>
                <button class="vote-button">Für Benjamin abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

            <div class="member projektinhaber" data-name="Kdot" data-role="Projektinhaber">
                <div class="member-name"><span class="rank-dot"></span>Kdot</div>
                <div class="member-role">Projektinhaber</div>
                <button class="vote-button">Für Kdot abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

            <div class="member projektinhaber" data-name="eddx" data-role="Projektinhaber">
                <div class="member-name"><span class="rank-dot"></span>eddx</div>
                <div class="member-role">Projektinhaber</div>
                <button class="vote-button">Für eddx abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

            <div class="member projektinhaber" data-name="Kuna" data-role="Projektinhaber">
                <div class="member-name"><span class="rank-dot"></span>Kuna 👑</div>
                <div class="member-role">Projektinhaber</div>
                <button class="vote-button">Für Kuna abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

            <div class="member projektinhaber" data-name="Rave" data-role="Projektinhaber">
                <div class="member-name"><span class="rank-dot"></span>Rave 👑</div>
                <div class="member-role">Projektinhaber</div>
                <button class="vote-button">Für Rave abstimmen</button>
                <div class="votes">0 Stimmen</div>
            </div>

        </div>
    </section>


    <div class="info">
        <h3>🏆 Bester Teamler der Woche</h3>

        <p>
            Stimme in jedem Bereich genau einmal für deinen Favoriten ab.
            Deine Auswahl wird auf diesem Gerät gespeichert.
        </p>
    </div>

</main>

<footer>
    Team Abstimmung • Bester Teamler der Woche
</footer>


<script>

/* =========================
   PARTIKEL ERSTELLEN
========================= */

const particleContainer = document.getElementById("particles");

for(let i = 0; i < 75; i++) {

    const particle = document.createElement("div");

    particle.classList.add("particle");

    particle.style.left = Math.random() * 100 + "%";

    particle.style.animationDuration =
        (8 + Math.random() * 18) + "s";

    particle.style.animationDelay =
        (-Math.random() * 20) + "s";

    particle.style.opacity =
        (0.15 + Math.random() * 0.4);

    const size = 1 + Math.random() * 3;

    particle.style.width = size + "px";
    particle.style.height = size + "px";

    particleContainer.appendChild(particle);
}


/* =========================
   ABSTIMMUNG
========================= */

const members = document.querySelectorAll(".member");


members.forEach(member => {

    const button = member.querySelector(".vote-button");
    const voteText = member.querySelector(".votes");

    const name = member.dataset.name;
    const role = member.dataset.role;

    const voteKey = "votes_" + role + "_" + name;
    const selectedKey = "selected_" + role;


    /* Stimmen laden */

    let votes = Number(localStorage.getItem(voteKey)) || 0;

    voteText.textContent =
        votes + (votes === 1 ? " Stimme" : " Stimmen");


    /* Bereits abgestimmt? */

    const selected = localStorage.getItem(selectedKey);

    if(selected === name) {

        button.classList.add("voted");

        button.textContent = "✓ Deine Stimme";
    }


    /* Abstimmen */

    button.addEventListener("click", () => {

        const previousVote =
            localStorage.getItem(selectedKey);


        /* Wenn bereits gewählt */

        if(previousVote) {

            if(previousVote === name) {

                alert("Du hast in diesem Bereich bereits für diese Person abgestimmt.");

            } else {

                alert(
                    "Du hast in diesem Bereich bereits abgestimmt."
                );
            }

            return;
        }


        /* Stimme hinzufügen */

        votes++;

        localStorage.setItem(voteKey, votes);

        localStorage.setItem(selectedKey, name);


        /* Anzeige aktualisieren */

        voteText.textContent =
            votes + (votes === 1 ? " Stimme" : " Stimmen");


        button.classList.add("voted");

        button.textContent =
            "✓ Deine Stimme";


        /* Alle anderen Buttons dieses Bereiches deaktivieren */

        const category =
            member.closest(".category");

        category
            .querySelectorAll(".vote-button")
            .forEach(otherButton => {

                if(otherButton !== button) {

                    otherButton.disabled = true;

                    otherButton.style.opacity = ".45";

                    otherButton.style.cursor = "not-allowed";
                }

            });

    });

});


/* =========================
   BEREITS ABGESTIMMTE BEREICHE
========================= */

document.querySelectorAll(".category").forEach(category => {

    const selectedButtons =
        category.querySelectorAll(".vote-button.voted");

    if(selectedButtons.length > 0) {

        category
            .querySelectorAll(".vote-button")
            .forEach(button => {

                if(!button.classList.contains("voted")) {

                    button.disabled = true;

                    button.style.opacity = ".45";

                    button.style.cursor = "not-allowed";
                }

            });
    }

});

</script>

</body>
</html>
```
