<!DOCTYPE html>  
<html lang="ru">  
<head>  
  <meta charset="UTF-8">  
  <title>Лига Прогнозистов</title>  
  
  <!-- Telegram WebApp JS (для мини-приложения) -->  
  <script src="https://telegram.org/js/telegram-web-app.js"></script>  
  
  <style>  
    body {  
      font-family: Arial, sans-serif;  
      background: #0b0c10;  
      color: #f5f5f5;  
      text-align: center;  
      margin: 0;  
      padding: 15px;  
    }  
  
    h1 {  
      margin-bottom: 10px;  
    }  
  
    .menu {  
      margin-bottom: 10px;  
    }  
  
    .menu button {  
      background: #45f3ff;  
      border: none;  
      padding: 8px 12px;  
      border-radius: 7px;  
      margin: 4px;  
      cursor: pointer;  
      font-size: 14px;  
      color: #000;  
    }  
  
    .screen {  
      display: none;  
      margin-top: 10px;  
      background: #1f2833;  
      padding: 15px;  
      border-radius: 10px;  
    }  
  
    .club-btn {  
      background: #243447;  
      padding: 12px;  
      margin: 5px auto;  
      border-radius: 10px;  
      max-width: 260px;  
      cursor: pointer;  
      border: 1px solid #2e3b4e;  
    }  
  
    .club-btn:hover {  
      background: #2d3b4d;  
    }  
  
    .club-selected {  
      border: 2px solid #45f3ff;  
      background: #16202a;  
    }  
  
    button {  
      border: none;  
      padding: 7px 12px;  
      border-radius: 7px;  
      cursor: pointer;  
      margin-top: 5px;  
    }  
  
    input, select {  
      padding: 5px;  
      border-radius: 5px;  
      border: none;  
      margin: 3px;  
    }  
  
    input[type="number"] {  
      width: 70px;  
      text-align: center;  
    }  
  
    .table-wrapper {  
      max-height: 260px;  
      overflow-y: auto;  
      margin-top: 8px;  
      border-radius: 8px;  
      border: 1px solid #2e3b4e;  
    }  
  
    table {  
      width: 100%;  
      border-collapse: collapse;  
      font-size: 14px;  
    }  
  
    th, td {  
      border-bottom: 1px solid #34495e;  
      padding: 6px;  
    }  
  
    th {  
      font-weight: bold;  
      position: sticky;  
      top: 0;  
      background: #1f2833;  
    }  
  
    .nick {  
      color: #45f3ff;  
      cursor: pointer;  
    }  
  
    .nick:hover {  
      text-decoration: underline;  
    }  
  
    /* Награды */  
    .reward-grid {  
      display: flex;  
      flex-wrap: wrap;  
      justify-content: center;  
      gap: 8px;  
      margin-top: 8px;  
    }  
  
    .reward-card {  
      background: #243447;  
      border-radius: 8px;  
      padding: 8px 10px;  
      min-width: 140px;  
      max-width: 180px;  
      text-align: left;  
      font-size: 13px;  
      border: 1px solid #2e3b4e;  
    }  
  
    .reward-card-title {  
      font-weight: bold;  
      margin-bottom: 4px;  
    }  
  
    .reward-card-count {  
      font-size: 12px;  
      color: #9fdcff;  
    }  
  
    /* Призы */  
    .prize-card {  
      background: #243447;  
      border-radius: 10px;  
      padding: 10px 12px;  
      margin: 6px auto;  
      max-width: 320px;  
      text-align: left;  
      border: 1px solid #2e3b4e;  
      font-size: 14px;  
    }  
  
    .prize-title {  
      font-weight: bold;  
      margin-bottom: 4px;  
    }  
  
    .small-note {  
      font-size: 12px;  
      opacity: 0.7;  
      margin-top: 6px;  
    }  
  
    .dead-note {  
      font-size: 13px;  
      margin-top: 6px;  
      opacity: 0.9;  
    }  
  </style>  
</head>  
<body>  
  
<h1>⚽ Лига прогнозистов</h1>  
  
<div class="menu">  
  <button onclick="openScreen('home')">Главная</button>  
  <button onclick="openScreen('table')">Таблица</button>  
  <button onclick="openScreen('predictions')">Прогноз</button>  
  <button onclick="openScreen('profile')">Профиль</button>  
  <button onclick="openScreen('prizes')">Призы</button>  
  <button onclick="openScreen('rewards')">🏆 Награды</button>  
  <button onclick="openScreen('strike')">🎯 Точный удар</button>  
</div>  
  
<!-- ВЫБОР КЛУБА -->  
<div id="clubSelect">  
  <h3>Выбери любимый клуб (1 раз за сезон)</h3>  
  
  <div class="club-btn" onclick="selectClub(this, 'Барселона')">🔵🔴 Барселона</div>  
  <div class="club-btn" onclick="selectClub(this, 'Реал Мадрид')">⚪ Реал Мадрид</div>  
  <div class="club-btn" onclick="selectClub(this, 'Бавария')">🔴 Бавария</div>  
  <div class="club-btn" onclick="selectClub(this, 'Арсенал')">🔴 Арсенал</div>  
  <div class="club-btn" onclick="selectClub(this, 'Ливерпуль')">🔴 Ливерпуль</div>  
  <div class="club-btn" onclick="selectClub(this, 'Манчестер Юнайтед')">🔴 Манчестер Юнайтед</div>  
  <div class="club-btn" onclick="selectClub(this, 'Манчестер Сити')">🔷 Манчестер Сити</div>  
  <div class="club-btn" onclick="selectClub(this, 'ПСЖ')">🔵🔴 ПСЖ</div>  
  
  <button id="clubConfirm" disabled onclick="confirmClub()">Подтвердить выбор</button>  
</div>  
  
<!-- ГЛАВНАЯ -->  
<div id="home" class="screen">  
  <h2>Главная</h2>  
  <p>Любимый клуб: <span id="homeClub">—</span></p>  
  <p>Твои очки: <span id="homePoints">0</span></p>  
  <p>Твоё место: <span id="homePlace">—</span></p>  
  <p>  
    Баланс:  
    <b><span id="homeStars">0</span> ⭐</b>  
  </p>  
  <p>  
    <button onclick="topUpStars()">Пополнить ⭐</button>  
    <button onclick="withdrawStars()">Вывести</button>  
  </p>  
  <p>Билеты на розыгрыш: <span id="homeTickets">0</span></p>  
</div>  
  
<!-- ТАБЛИЦА -->  
<div id="table" class="screen">  
  <h2>Таблица</h2>  
  <div class="table-wrapper">  
    <table>  
      <thead>  
      <tr><th>Место</th><th>Ник</th><th>Очки</th></tr>  
      </thead>  
      <tbody id="playersTable"></tbody>  
    </table>  
  </div>  
</div>  
  
<!-- ПРОГНОЗЫ -->  
<div id="predictions" class="screen">  
  <h2>Сделать прогноз (демо-тур)</h2>  
  <p id="predictionsDeadlineInfo" class="dead-note"></p>  
  <div id="matchesList"></div>  
  <button onclick="submitPredictions()" id="predictionsButton">Отправить прогноз</button>  
  <p id="predictionsResult"></p>  
</div>  
  
<!-- ПРОФИЛЬ -->  
<div id="profile" class="screen">  
  <h2>Твой профиль</h2>  
  <p>Ник: <b><span id="profileNick"></span></b></p>  
  <p>Любимый клуб: <span id="profileClub">—</span></p>  
  <p>Очки: <span id="profilePoints">0</span></p>  
  <p>Сыграно туров: <span id="profileTours">0</span></p>  
  <p>Процент правильных исходов: <span id="profileAccuracy">0%</span></p>  
  <p>Лучший тур: пока нет данных</p>  
  <p>Баланс: <span id="profileStars">0</span> ⭐</p>  
  <p>  
    <button onclick="topUpStars()">Пополнить ⭐</button>  
    <button onclick="withdrawStars()">Вывести</button>  
  </p>  
  <p>Билеты: <span id="profileTickets">0</span></p>  
  <p>Награды смотри во вкладке «Награды»</p>  
</div>  
  
<!-- ПРОФИЛЬ ИГРОКА ИЗ ТАБЛИЦЫ -->  
<div id="playerModal" class="screen">  
  <h2>Профиль игрока</h2>  
  <p>Ник: <span id="pmNick"></span></p>  
  <p>Место: <span id="pmPlace"></span></p>  
  <p>Очки: <span id="pmPoints"></span></p>  
  <p>Любимый клуб: <span id="pmClub"></span></p>  
  <p>Процент правильных исходов: <span id="pmAccuracy"></span>%</p>  
  <p>Лучший тур: <span id="pmBestRound"></span></p>  
  <button onclick="openScreen('table')">Назад к таблице</button>  
</div>  
  
<!-- ПРИЗЫ -->  
<div id="prizes" class="screen">  
  <h2>🎁 Призы сезона</h2>  
  
  <div class="prize-card">  
    <div class="prize-title">🥇 1 место</div>  
    <div>Футболка любимого клуба победителя.</div>  
  </div>  
  
  <div class="prize-card">  
    <div class="prize-title">🥈 2 место</div>  
    <div>Билет на футбол в любом городе (до 5 000 ₽).</div>  
  </div>  
  
  <div class="prize-card">  
    <div class="prize-title">🥉 3 место</div>  
    <div>Telegram Premium на 3 месяца.</div>  
  </div>  
  
  <p class="small-note">  
    Призы выдаются по итогам сезона по результатам таблицы Лиги прогнозистов.  
  </p>  
</div>  
  
<!-- НАГРАДЫ -->  
<div id="rewards" class="screen">  
  <h2>🏆 Твои награды</h2>  
  <div id="rewardGrid" class="reward-grid"></div>  
  <p style="margin-top:10px;">  
    🎫 Всего билетов (туры + награды + Точный удар):  
    <b><span id="rewardsTickets">0</span></b>  
  </p>  
  <p style="font-size:12px;opacity:0.7;">  
    Каждая награда даёт 1 билет на финальный розыгрыш.  
  </p>  
</div>  
  
<!-- ТОЧНЫЙ УДАР -->  
<div id="strike" class="screen">  
  <h2>🎯 Точный удар</h2>  
  
  <p>  
    Баланс:  
    <b><span id="strikeStars">0</span> ⭐</b>  
  </p>  
  
  <h3 id="strikeMatchTitle"></h3>  
  <p id="strikeMatchTime"></p>  
  <p id="strikeDeadlineInfo" class="dead-note"></p>  
  
  <div id="strikeInputs">  
    <p>  
      Твой прогноз счёта:  
      <input type="number" id="strikeHome" min="0" placeholder="Дом">  
      :  
      <input type="number" id="strikeAway" min="0" placeholder="Гости">  
    </p>  
  
    <p>  
      Сумма ставки (⭐):  
      <input type="number" id="strikeBet" min="0" oninput="updateStrikePotential()">  
    </p>  
  
    <p>Минимум: 10 ⭐</p>  
  
    <p>💰 Выигрыш при исходе: <b><span id="strikeOutcomeWin">0 ⭐</span></b></p>  
    <p>🎯 Выигрыш при точном счёте: <b><span id="strikeExactWin">0 ⭐</span></b></p>  
  
    <button onclick="makeStrikeBet()" id="strikeBetButton">Сделать ставку</button>  
  </div>  
  
  <p id="strikeStatus"></p>  
  
  <hr style="margin:15px 0;border-color:#444;">  
  
  <h3>Результат матча (для тебя, как админа)</h3>  
  <p>  
    Фактический счёт:  
    <input type="number" id="strikeRealHome" min="0" placeholder="Дом">  
    :  
    <input type="number" id="strikeRealAway" min="0" placeholder="Гости">  
  </p>  
  <button onclick="settleLastStrikeBet()">Рассчитать последнюю ставку</button>  
  <p id="strikeSettleStatus"></p>  
</div>  
  
<script>  
  // ==== Telegram WebApp / user ====  
  const tg = window.Telegram ? window.Telegram.WebApp : null;  
  
  const currentUserName = tg && tg.initDataUnsafe && tg.initDataUnsafe.user  
    ? (tg.initDataUnsafe.user.username || ("user_" + tg.initDataUnsafe.user.id))  
    : "guest";  
  
  if (tg) {  
    tg.expand();  
  }  
  
  function tgAlert(text) {  
    if (tg && tg.showAlert) tg.showAlert(text);  
    else alert(text);  
  }  
  
  // ====== КЛЮЧИ v4 ======  
  const KEY_CLUB          = "lp_v4_favoriteClub";  
  const KEY_STARS         = "lp_v4_balanceStars";  
  const KEY_TICKETS       = "lp_v4_tickets";  
  const KEY_STRIKE_BETS   = "lp_v4_strikeBets";  
  const KEY_USER_POINTS   = "lp_v4_userPoints";  
  const KEY_TOTAL_PREDS   = "lp_v4_totalPredictions";  
  const KEY_CORRECT_RES   = "lp_v4_correctResults";  
  const KEY_TOURS         = "lp_v4_totalTours";  
  const KEY_REWARDS       = "lp_v4_rewards";  
  const KEY_EXACT_STREAK  = "lp_v4_exactStreak";  
  
  // ====== ДЕДЛАЙНЫ (пример) ======  
  // Тур лиги прогнозистов: приём прогнозов до 26 ноября, 11:00 (по местному времени устройства)  
  const TOUR_DEADLINE_TEXT = "26 ноября, 11:00 (МСК)";  
  const TOUR_DEADLINE_ISO  = "2025-11-26T11:00:00"; // Можешь поменять под нужную дату/время  
  
  // "Точный удар": ставки принимаются до этого времени  
  const STRIKE_DEADLINE_TEXT = "26 ноября, 11:00 (МСК)";  
  const STRIKE_DEADLINE_ISO  = "2025-11-26T11:00:00";  
  
  function isTourClosed() {  
    return new Date() > new Date(TOUR_DEADLINE_ISO);  
  }  
  
  function isStrikeClosed() {  
    return new Date() > new Date(STRIKE_DEADLINE_ISO);  
  }  
  
  // ====== СОСТОЯНИЕ ======  
  let favoriteClub = localStorage.getItem(KEY_CLUB) || null;  
  let balanceStars = parseInt(localStorage.getItem(KEY_STARS) || "100", 10);  
  let tickets      = parseInt(localStorage.getItem(KEY_TICKETS) || "0", 10);  
  let userPoints   = parseInt(localStorage.getItem(KEY_USER_POINTS) || "27", 10);  
  let totalPredictions = parseInt(localStorage.getItem(KEY_TOTAL_PREDS) || "0", 10);  
  let correctResults   = parseInt(localStorage.getItem(KEY_CORRECT_RES) || "0", 10);  
  let totalTours       = parseInt(localStorage.getItem(KEY_TOURS) || "0", 10);  
  
  let earnedRewards = JSON.parse(localStorage.getItem(KEY_REWARDS) || "[]");  
  let exactStreak   = parseInt(localStorage.getItem(KEY_EXACT_STREAK) || "0", 10);  
  
  let strikeBets = JSON.parse(localStorage.getItem(KEY_STRIKE_BETS) || "[]");  
  
  // Справочник наград  
  const REWARDS_DEFS = {  
    firstTour:        "Первый тур",  
    perfectFirstTour: "100% в первом туре",  
    perfectTour:      "Идеальный тур (все исходы)",  
    threeExact:       "3 точных счёта подряд",  
    tenTours:         "10 сыгранных туров",  
    fiftyTours:       "50 сыгранных туров",  
    hundredTours:     "100 сыгранных туров",  
    kingOfResults:    "Король исходов (≥70%)"  
  };  
  
  // Демонстрационный список игроков (для таблицы)  
  const playersBase = [  
    { name: currentUserName, points: userPoints, club: "Барселона", accuracy: 67, bestRound: "3 тур" },  
    { name: "kinggoals",   points: 18, club: "Реал Мадрид", accuracy: 42, bestRound: "1 тур" },  
    { name: "footlord",    points: 13, club: "ПСЖ", accuracy: 31, bestRound: "2 тур" },  
    { name: "predator",    points: 7,  club: "Манчестер Сити", accuracy: 21, bestRound: "1 тур" },  
    { name: "goalstorm",   points: 5,  club: "Ливерпуль", accuracy: 10, bestRound: "-" },  
    { name: "xg_master",   points: 4,  club: "Бавария", accuracy: 9, bestRound: "-" },  
    { name: "clean_sheet", points: 3,  club: "Арсенал", accuracy: 5, bestRound: "-" },  
    { name: "pressinggod", points: 2,  club: "Манчестер Юнайтед", accuracy: 4, bestRound: "-" },  
    { name: "hat_trick",   points: 1,  club: "Барселона", accuracy: 3, bestRound: "-" },  
    { name: "latewinner",  points: 0,  club: "Реал Мадрид", accuracy: 0, bestRound: "-" }  
  ];  
  
  // Матчи для обычных прогнозов (демо тур)  
  // Пример: Олимпиакос — Реал Мадрид (как ты говорил)  
  const matches = [  
    {  
      id: 1,  
      home: "Олимпиакос",  
      away: "Реал Мадрид",  
      realHome: 2,  
      realAway: 1  
    },  
    {  
      id: 2,  
      home: "Барселона",  
      away: "Манчестер Сити",  
      realHome: 3,  
      realAway: 2  
    },  
    {  
      id: 3,  
      home: "Ливерпуль",  
      away: "Бавария",  
      realHome: 1,  
      realAway: 1  
    }  
  ];  
  
  // Матч для точного удара  
  const STRIKE_MATCH = {  
    home: "Олимпиакос",  
    away: "Реал Мадрид",  
    time: "26 ноября, 11:00 (МСК)"  // пример; можно менять  
  };  
  
  // ====== ОБЩИЕ ФУНКЦИИ ======  
  function saveAll() {  
    localStorage.setItem(KEY_CLUB, favoriteClub || "");  
    localStorage.setItem(KEY_STARS, String(balanceStars));  
    localStorage.setItem(KEY_TICKETS, String(tickets));  
    localStorage.setItem(KEY_USER_POINTS, String(userPoints));  
    localStorage.setItem(KEY_TOTAL_PREDS, String(totalPredictions));  
    localStorage.setItem(KEY_CORRECT_RES, String(correctResults));  
    localStorage.setItem(KEY_TOURS, String(totalTours));  
    localStorage.setItem(KEY_STRIKE_BETS, JSON.stringify(strikeBets));  
    localStorage.setItem(KEY_REWARDS, JSON.stringify(earnedRewards));  
    localStorage.setItem(KEY_EXACT_STREAK, String(exactStreak));  
  }  
  
  function openScreen(id) {  
    document.querySelectorAll(".screen").forEach(s => s.style.display = "none");  
    document.getElementById(id).style.display = "block";  
    if (id === "rewards") renderRewardsUI();  
    if (id === "predictions") updatePredictionsAvailabilityUI();  
    if (id === "strike") updateStrikeAvailabilityUI();  
  }  
  
  function updateBalancesUI() {  
    document.getElementById("homeStars").innerText   = balanceStars;  
    document.getElementById("profileStars").innerText= balanceStars;  
    document.getElementById("strikeStars").innerText = balanceStars;  
  }  
  
  function updateClubUI() {  
    const c = favoriteClub || "не выбран";  
    document.getElementById("homeClub").innerText    = c;  
    document.getElementById("profileClub").innerText = c;  
  }  
  
  function updateTicketsUI() {  
    document.getElementById("homeTickets").innerText    = tickets;  
    document.getElementById("profileTickets").innerText = tickets;  
    const rEl = document.getElementById("rewardsTickets");  
    if (rEl) rEl.innerText = tickets;  
  }  
  
  function updatePointsAndStatsUI() {  
    document.getElementById("homePoints").innerText    = userPoints;  
    document.getElementById("profilePoints").innerText = userPoints;  
    document.getElementById("profileTours").innerText  = totalTours;  
    const acc = totalPredictions > 0  
      ? Math.round((correctResults / totalPredictions) * 100)  
      : 0;  
    document.getElementById("profileAccuracy").innerText = acc + "%";  
  }  
  
  function initStrikeMatchUI() {  
    document.getElementById("strikeMatchTitle").innerText =  
      STRIKE_MATCH.home + " — " + STRIKE_MATCH.away;  
    document.getElementById("strikeMatchTime").innerText =  
      "Время матча: " + STRIKE_MATCH.time;  
    document.getElementById("strikeDeadlineInfo").innerText =  
      "Ставки принимаются до: " + STRIKE_DEADLINE_TEXT;  
  }  
  
  // ====== ВЫБОР КЛУБА ======  
  let tempSelectedClub = null;  
  
  function selectClub(elem, clubName) {  
    document.querySelectorAll(".club-btn").forEach(c => c.classList.remove("club-selected"));  
    elem.classList.add("club-selected");  
    tempSelectedClub = clubName;  
    document.getElementById("clubConfirm").disabled = false;  
  }  
  
  function confirmClub() {  
    if (!tempSelectedClub) return;  
    favoriteClub = tempSelectedClub;  
    saveAll();  
    updateClubUI();  
    document.getElementById("clubSelect").style.display = "none";  
    openScreen("home");  
    rebuildTable(); // обновить клуб в таблице  
  }  
  
  // ====== ТАБЛИЦА (с кликабельными никами) ======  
  function getPlayersForTable() {  
    const copy = playersBase.map(p => ({ ...p }));  
    const me = copy.find(p => p.name === currentUserName);  
    if (me) {  
      me.points = userPoints;  
      if (favoriteClub) me.club = favoriteClub;  
      const acc = totalPredictions > 0  
        ? Math.round((correctResults / totalPredictions) * 100)  
        : me.accuracy;  
      me.accuracy = acc;  
    }  
    copy.sort((a, b) => b.points - a.points);  
    return copy;  
  }  
  
  function rebuildTable() {  
    const tbody = document.getElementById("playersTable");  
    tbody.innerHTML = "";  
    const players = getPlayersForTable();  
  
    players.forEach((p, index) => {  
      const tr = document.createElement("tr");  
      const place = index + 1;  
      tr.innerHTML = `  
        <td>${place}</td>  
        <td><span class="nick" onclick="openPlayer('${p.name}')">${p.name}</span></td>  
        <td>${p.points}</td>  
      `;  
      tbody.appendChild(tr);  
  
      if (p.name === currentUserName) {  
        document.getElementById("homePlace").innerText = place;  
      }  
    });  
  }  
  
  function openPlayer(nick) {  
    const players = getPlayersForTable();  
    const idx = players.findIndex(p => p.name === nick);  
    if (idx === -1) return;  
    const p = players[idx];  
  
    document.getElementById("pmNick").innerText = p.name;  
    document.getElementById("pmPlace").innerText = idx + 1;  
    document.getElementById("pmPoints").innerText = p.points;  
    document.getElementById("pmClub").innerText = p.club || "-";  
    document.getElementById("pmAccuracy").innerText = p.accuracy ?? 0;  
    document.getElementById("pmBestRound").innerText = p.bestRound || "-";  
  
    openScreen("playerModal");  
  }  
  
  // ====== ПРОГНОЗЫ (обычная лига) ======  
  function buildMatchesUI() {  
    const container = document.getElementById("matchesList");  
    container.innerHTML = "";  
  
    const deadInfo = document.getElementById("predictionsDeadlineInfo");  
    deadInfo.innerText = "Приём прогнозов до: " + TOUR_DEADLINE_TEXT;  
  
    matches.forEach(m => {  
      const wrapper = document.createElement("div");  
      wrapper.style.margin = "6px 0";  
      wrapper.innerHTML = `  
        ${m.home}  
        <input type="number" id="pred-home-${m.id}" min="0" style="width:50px;">  
        :  
        <input type="number" id="pred-away-${m.id}" min="0" style="width:50px;">  
        ${m.away}  
      `;  
      container.appendChild(wrapper);  
    });  
  }  
  
  let predictionsSent = false;  
  
  function giveReward(key) {  
    earnedRewards.push(key);  
    tickets += 1;  
    saveAll();  
    updateTicketsUI();  
  }  
  
  function renderRewardsUI() {  
    const grid = document.getElementById("rewardGrid");  
    if (!grid) return;  
    grid.innerHTML = "";  
  
    if (earnedRewards.length === 0) {  
      grid.innerHTML = "<p>Пока нет наград</p>";  
    } else {  
      const counts = {};  
      earnedRewards.forEach(k => {  
        counts[k] = (counts[k] || 0) + 1;  
      });  
      Object.keys(counts).forEach(key => {  
        const card = document.createElement("div");  
        card.className = "reward-card";  
        const title = REWARDS_DEFS[key] || key;  
        card.innerHTML = `  
          <div class="reward-card-title">🎖 ${title}</div>  
          <div class="reward-card-count">×${counts[key]} (билетов)</div>  
        `;  
        grid.appendChild(card);  
      });  
    }  
  
    const tEl = document.getElementById("rewardsTickets");  
    if (tEl) tEl.innerText = tickets;  
  }  
  
  function updatePredictionsAvailabilityUI() {  
    const closed = isTourClosed();  
    const container = document.getElementById("matchesList");  
    const btn = document.getElementById("predictionsButton");  
    const result = document.getElementById("predictionsResult");  
  
    if (closed) {  
      container.innerHTML = "<p>⛔ Приём прогнозов на этот тур завершён.</p>";  
      btn.disabled = true;  
      result.innerText = "";  
    } else {  
      if (!predictionsSent) {  
        if (container.innerHTML.trim() === "" || container.innerHTML.indexOf("⛔") !== -1) {  
          buildMatchesUI();  
        }  
        btn.disabled = false;  
        result.innerText = "";  
      }  
    }  
  }  
  
  function submitPredictions() {  
    if (isTourClosed()) {  
      document.getElementById("predictionsResult").innerText =  
        "⛔ Приём прогнозов на этот тур завершён.";  
      return;  
    }  
  
    if (predictionsSent) {  
      document.getElementById("predictionsResult").innerText =  
        "Ты уже отправил прогноз на этот тур (демо).";  
      return;  
    }  
  
    let gainedPoints = 0;  
    let tourPredictions = 0;  
    let tourCorrectResults = 0;  
    let tourExactCount = 0; // количество точных счётов в этом туре  
  
    const fav = favoriteClub;  
  
    matches.forEach(m => {  
      const hStr = document.getElementById(`pred-home-${m.id}`).value;  
      const aStr = document.getElementById(`pred-away-${m.id}`).value;  
      if (hStr === "" || aStr === "") return;  
  
      const ph = parseInt(hStr, 10);  
      const pa = parseInt(aStr, 10);  
  
      tourPredictions++;  
      totalPredictions++;  
  
      let pts = 0;  
      let isExact = false;  
  
      if (ph === m.realHome && pa === m.realAway) {  
        pts = 3;  
        tourCorrectResults++;  
        correctResults++;  
        isExact = true;  
      } else {  
        const realDiff = m.realHome - m.realAway;  
        const predDiff = ph - pa;  
        const realRes = realDiff === 0 ? 0 : (realDiff > 0 ? 1 : -1);  
        const predRes = predDiff === 0 ? 0 : (predDiff > 0 ? 1 : -1);  
        if (realRes === predRes) {  
          pts = 1;  
          tourCorrectResults++;  
          correctResults++;  
        }  
      }  
  
      if (fav && (m.home === fav || m.away === fav)) {  
        pts *= 2; // матчи любимого клуба ×2  
      }  
  
      if (isExact) {  
        tourExactCount++;  
        exactStreak++;  
      } else {  
        exactStreak = 0; // сброс глобальной серии точных счётов  
      }  
  
      gainedPoints += pts;  
    });  
  
    if (tourPredictions === 0) {  
      document.getElementById("predictionsResult").innerText =  
        "Сначала введи прогноз хотя бы для одного матча.";  
      return;  
    }  
  
    userPoints = userPoints + gainedPoints;  
    totalTours++;  
    tickets += 1; // за сыгранный тур даём 1 билет  
  
    // === НАГРАДЫ ===  
  
    // 1. Первый тур  
    if (totalTours === 1) {  
      giveReward("firstTour");  
    }  
  
    // 2. 100% в первом туре  
    if (totalTours === 1 && tourCorrectResults === tourPredictions) {  
      giveReward("perfectFirstTour");  
    }  
  
    // 3. Идеальный тур (все исходы)  
    if (tourCorrectResults === tourPredictions) {  
      giveReward("perfectTour");  
    }  
  
    // 4. 3 точных счёта подряд  
    if (exactStreak >= 3) {  
      giveReward("threeExact");  
      exactStreak = 0; // обнуляем серию после награды  
    }  
  
    // 5. 10, 50, 100 туров  
    if (totalTours === 10)  giveReward("tenTours");  
    if (totalTours === 50)  giveReward("fiftyTours");  
    if (totalTours === 100) giveReward("hundredTours");  
  
    // 6. Король исходов (общий % >= 70)  
    const overallAcc =  
      totalPredictions > 0  
        ? Math.round((correctResults / totalPredictions) * 100)  
        : 0;  
  
    if (overallAcc >= 70) {  
      giveReward("kingOfResults");  
    }  
  
    predictionsSent = true;  
    document.getElementById("predictionsButton").disabled = true;  
    document.getElementById("predictionsResult").innerText =  
      "Тур сыгран. Ты набрал " + gainedPoints + " очков за этот тур (демо).";  
  
    saveAll();  
    updatePointsAndStatsUI();  
    updateTicketsUI();  
    rebuildTable();  
    renderRewardsUI();  
  }  
  
  // ====== ТОЧНЫЙ УДАР (ТОЛЬКО ЗВЁЗДЫ) ======  
  function updateStrikePotential() {  
    const betStr = document.getElementById("strikeBet").value;  
    const bet = parseFloat(betStr || "0");  
    const symbol = "⭐";  
  
    if (bet <= 0) {  
      document.getElementById("strikeOutcomeWin").innerText = "0 " + symbol;  
      document.getElementById("strikeExactWin").innerText   = "0 " + symbol;  
      return;  
    }  
  
    const winOutcome = Math.floor(bet * 1.95);  
    const winExact   = Math.floor(bet * 4.8);  
  
    document.getElementById("strikeOutcomeWin").innerText = winOutcome + " " + symbol;  
    document.getElementById("strikeExactWin").innerText   = winExact   + " " + symbol;  
  }  
  
  function updateStrikeAvailabilityUI() {  
    const closed = isStrikeClosed();  
    const inputsBlock = document.getElementById("strikeInputs");  
    const status = document.getElementById("strikeStatus");  
  
    if (closed) {  
      if (inputsBlock) inputsBlock.style.display = "none";  
      status.innerText = "⛔ Приём ставок по режиму «Точный удар» завершён.";  
    } else {  
      if (inputsBlock) inputsBlock.style.display = "block";  
      if (!strikeBets.length) status.innerText = "";  
    }  
  }  
  
  function makeStrikeBet() {  
    if (isStrikeClosed()) {  
      document.getElementById("strikeStatus").innerText =  
        "⛔ Приём ставок по режиму «Точный удар» завершён.";  
      return;  
    }  
  
    const homeStr = document.getElementById("strikeHome").value;  
    const awayStr = document.getElementById("strikeAway").value;  
    const betStr  = document.getElementById("strikeBet").value;  
    const status  = document.getElementById("strikeStatus");  
  
    const home = parseInt(homeStr || "-1", 10);  
    const away = parseInt(awayStr || "-1", 10);  
    const bet  = parseFloat(betStr || "0");  
  
    if (isNaN(home) || isNaN(away) || home < 0 || away < 0) {  
      status.innerText = "Сначала введи прогноз счёта.";  
      return;  
    }  
  
    const minBet = 10;  
  
    if (bet < minBet) {  
      status.innerText = "Минимальная ставка: " + minBet + " ⭐";  
      return;  
    }  
  
    if (bet > balanceStars) {  
      status.innerText = "Недостаточно звёзд. Баланс: " + balanceStars + " ⭐";  
      return;  
    }  
  
    balanceStars -= bet;  
  
    strikeBets.push({  
      match: STRIKE_MATCH.home + " — " + STRIKE_MATCH.away,  
      home,  
      away,  
      bet,  
      currency: "stars",  
      time: new Date().toISOString()  
    });  
  
    status.innerText = "✅ Ставка принята. Ждём результат матча.";  
  
    document.getElementById("strikeBet").value   = "";  
    document.getElementById("strikeHome").value  = "";  
    document.getElementById("strikeAway").value  = "";  
    document.getElementById("strikeOutcomeWin").innerText = "0 ⭐";  
    document.getElementById("strikeExactWin").innerText   = "0 ⭐";  
  
    saveAll();  
    updateBalancesUI();  
  }  
  
  function settleLastStrikeBet() {  
    const status = document.getElementById("strikeSettleStatus");  
    const realHomeStr = document.getElementById("strikeRealHome").value;  
    const realAwayStr = document.getElementById("strikeRealAway").value;  
  
    if (strikeBets.length === 0) {  
      status.innerText = "Нет ставок для расчёта.";  
      return;  
    }  
  
    if (realHomeStr === "" || realAwayStr === "") {  
      status.innerText = "Введи фактический счёт матча.";  
      return;  
    }  
  
    const realHome = parseInt(realHomeStr, 10);  
    const realAway = parseInt(realAwayStr, 10);  
  
    const bet = strikeBets[strikeBets.length - 1];  
  
    const betHome = bet.home;  
    const betAway = bet.away;  
    const amount  = bet.bet;  
  
    const realDiff = realHome - realAway;  
    const betDiff  = betHome - betAway;  
    const realRes = realDiff === 0 ? 0 : (realDiff > 0 ? 1 : -1);  
    const betRes  = betDiff === 0 ? 0 : (betDiff > 0 ? 1 : -1);  
  
    let win = 0;  
    let type = "проигрыш";  
  
    if (betHome === realHome && betAway === realAway) {  
      win = Math.floor(amount * 4.8);  
      type = "ТОЧНЫЙ СЧЁТ";  
    } else if (betRes === realRes) {  
      win = Math.floor(amount * 1.95);  
      type = "исход";  
    }  
  
    if (win > 0) {  
      balanceStars += win;  
      tickets += 1; // за выигранный "Точный удар"  
      status.innerText =  
        `✅ Ставка рассчитана: ${type}. Выигрыш +${win} ⭐`;  
    } else {  
      status.innerText = "❌ Ставка не сыграла. Выигрыша нет.";  
    }  
  
    strikeBets.pop();  
    saveAll();  
    updateBalancesUI();  
    updateTicketsUI();  
    renderRewardsUI();  
  }  
  
  // ====== ПОПОЛНЕНИЕ / ВЫВОД (демо — вместо Telegram Stars) ======  
  function topUpStars() {  
    if (tg && tg.showPopup) {  
      tg.showPopup({  
        title: "Пополнение ⭐",  
        message: "Скоро здесь будет настоящая покупка Telegram Stars.\nПока работает демо-пополнение.",  
        buttons: [  
          { id: "50", text: "Пополнить 50 ⭐" },  
          { id: "100", text: "Пополнить 100 ⭐" },  
          { id: "cancel", type: "cancel" }  
        ]  
      }, (id) => {  
        if (id === "50" || id === "100") {  
          const amount = parseInt(id, 10);  
          balanceStars += amount;  
          saveAll();  
          updateBalancesUI();  
          tgAlert("Баланс пополнен на " + amount + " ⭐ (демо).");  
        }  
      });  
    } else {  
      const v = prompt("Сколько ⭐ пополнить? (демо)");  
      const amount = parseInt(v || "0", 10);  
      if (!amount || amount <= 0) return;  
      balanceStars += amount;  
      saveAll();  
      updateBalancesUI();  
      alert("Баланс пополнен на " + amount + " ⭐ (демо).");  
    }  
  }  
  
  function withdrawStars() {  
    const v = prompt("Сколько ⭐ вывести? (демо)");  
    const amount = parseInt(v || "0", 10);  
    if (!amount || amount <= 0) return;  
    if (amount > balanceStars) {  
      tgAlert("Недостаточно ⭐ для вывода.");  
      return;  
    }  
    balanceStars -= amount;  
    saveAll();  
    updateBalancesUI();  
    tgAlert("Выведено " + amount + " ⭐ (демо).\nВ реальном боте это будет заявка на вывод или авто-вывод.");  
  }  
  
  // ====== ИНИЦИАЛИЗАЦИЯ ======  
  document.addEventListener("DOMContentLoaded", function () {  
    document.getElementById("profileNick").innerText = currentUserName;  
  
    initStrikeMatchUI();  
    updateBalancesUI();  
    updateClubUI();  
    updateTicketsUI();  
    updatePointsAndStatsUI();  
    buildMatchesUI();  
    rebuildTable();  
    renderRewardsUI();  
    updatePredictionsAvailabilityUI();  
    updateStrikeAvailabilityUI();  
  
    if (favoriteClub) {  
      document.getElementById("clubSelect").style.display = "none";  
      openScreen("home");  
    } else {  
      document.getElementById("clubSelect").style.display = "block";  
    }  
  });  
</script>  
  
</body>  
</html>  
