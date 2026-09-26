<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AVIA TEAM – Abstimmung</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    body {
      background: #050505;
      color: white;
      min-height: 100vh;
    }

    header {
      padding: 30px 50px;
      border-bottom: 1px solid #222;
      background: rgba(5, 5, 5, 0.95);
    }

    .logo {
      font-size: 24px;
      font-weight: bold;
      letter-spacing: 4px;
      color: #aaa;
    }

    .hero {
      text-align: center;
      padding: 80px 20px 50px;
    }

    .hero h1 {
      font-size: 55px;
      letter-spacing: 8px;
      margin-bottom: 15px;
    }

    .hero p {
      color: #888;
      font-size: 17px;
    }

    .categories {
      width: 90%;
      max-width: 1100px;
      margin: auto;
      padding-bottom: 80px;
    }

    .category {
      background: #0d0d0d;
      border: 1px solid #222;
      border-radius: 16px;
      padding: 30px;
      margin-bottom: 30px;
      box-shadow: 0 0 30px rgba(255,255,255,0.02);
    }

    .category h2 {
      margin-bottom: 8px;
      font-size: 25px;
    }

    .category-description {
      color: #777;
      margin-bottom: 25px;
    }

    .members {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 15px;
    }

    .member {
      background: #151515;
      border: 1px solid #292929;
      padding: 20px;
      border-radius: 12px;
      transition: 0.2s;
    }

    .member:hover {
      border-color: #666;
      transform: translateY(-2px);
    }

    .member-name {
      font-size: 18px;
      font-weight: bold;
      margin-bottom: 8px;
    }

    .votes {
      color: #888;
      margin-bottom: 15px;
    }

    button {
      width: 100%;
      padding: 12px;
      border: none;
      border-radius: 8px;
      background: #fff;
      color: #000;
      font-weight: bold;
      cursor: pointer;
      transition: 0.2s;
    }

    button:hover {
      background: #ccc;
    }

    button:disabled {
      background: #333;
      color: #777;
      cursor: not-allowed;
    }

    .notice {
      text-align: center;
      color: #666;
      margin-top: 20px;
      font-size: 14px;
    }

    footer {
      border-top: 1px solid #222;
      padding: 30px;
      text-align: center;
      color: #555;
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">AVIA TEAM</div>
  </header>

  <section class="hero">
    <h1>TEAM AWARDS</h1>
    <p>Stimme für die besten Mitglieder des AVIA Teams ab.</p>
  </section>

  <main class="categories">

    <!-- SUPPORTER -->
    <section class="category">
      <h2>🏆 Bester Supporter</h2>
      <p class="category-description">
        Wähle deinen besten Supporter.
      </p>

      <div class="members">

        <div class="member">
          <div class="member-name">Testname</div>
          <div class="votes">
            Stimmen: <span id="supporter-1">0</span>
          </div>
          <button onclick="vote('supporter', 'supporter-1')">
            ABSTIMMEN
          </button>
        </div>

        <div class="member">
          <div class="member-name">Testnamee</div>
          <div class="votes">
            Stimmen: <span id="supporter-2">0</span>
          </div>
          <button onclick="vote('supporter', 'supporter-2')">
            ABSTIMMEN
          </button>
        </div>

      </div>
    </section>


    <!-- MODERATOR -->
    <section class="category">
      <h2>🛡️ Bester Moderator</h2>
      <p class="category-description">
        Wähle deinen besten Moderator.
      </p>

      <div class="members">

        <div class="member">
          <div class="member-name">ModTest</div>
          <div class="votes">
            Stimmen: <span id="moderator-1">0</span>
          </div>
          <button onclick="vote('moderator', 'moderator-1')">
            ABSTIMMEN
          </button>
        </div>

        <div class="member">
          <div class="member-name">ModTest2</div>
          <div class="votes">
            Stimmen: <span id="moderator-2">0</span>
          </div>
          <button onclick="vote('moderator', 'moderator-2')">
            ABSTIMMEN
          </button>
        </div>

      </div>
    </section>


    <!-- ANALYST -->
    <section class="category">
      <h2>🔎 Bester Analyst</h2>
      <p class="category-description">
        Wähle deinen besten Analysten.
      </p>

      <div class="members">

        <div class="member">
          <div class="member-name">AnalystTest</div>
          <div class="votes">
            Stimmen: <span id="analyst-1">0</span>
          </div>
          <button onclick="vote('analyst', 'analyst-1')">
            ABSTIMMEN
          </button>
        </div>

        <div class="member">
          <div class="member-name">AnalystTest2</div>
          <div class="votes">
            Stimmen: <span id="analyst-2">0</span>
          </div>
          <button onclick="vote('analyst', 'analyst-2')">
            ABSTIMMEN
          </button>
        </div>

      </div>
    </section>

    <div class="notice">
      Du kannst pro Kategorie nur einmal abstimmen.
    </div>

  </main>

  <footer>
    © 2026 AVIA ROLEPLAY — AVIA TEAM
  </footer>


  <script>

    function vote(category, member) {

      const alreadyVoted =
        localStorage.getItem("voted_" + category);

      if (alreadyVoted) {
        alert("Du hast in dieser Kategorie bereits abgestimmt.");
        return;
      }

      let currentVotes =
        Number(localStorage.getItem("votes_" + member)) || 0;

      currentVotes++;

      localStorage.setItem(
        "votes_" + member,
        currentVotes
      );

      localStorage.setItem(
        "voted_" + category,
        "true"
      );

      document.getElementById(member).innerText =
        currentVotes;

      alert("Deine Stimme wurde gespeichert! ✅");

      document.querySelectorAll("button").forEach(button => {
        if (button.getAttribute("onclick")?.includes(category)) {
          button.disabled = true;
        }
      });
    }


    window.onload = function() {

      const members = [
        "supporter-1",
        "supporter-2",
        "supporter-3",
        "supporter-4",
        "moderator-1",
        "moderator-2",
        "analyst-1",
        "analyst-2"
      ];

      members.forEach(member => {

        const votes =
          Number(localStorage.getItem("votes_" + member)) || 0;

        document.getElementById(member).innerText =
          votes;
      });

    };

  </script>

</body>
</html>
