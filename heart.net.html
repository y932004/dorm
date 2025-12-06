<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8" />
  <title>情緒水彩室｜Emotion Watercolor</title>
  <style>
    * {
      box-sizing: border-box;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", "Noto Sans TC", sans-serif;
    }
    body {
      margin: 0;
      padding: 0;
      background: #f4f7fb;
      color: #333;
      min-height: 100vh;
    }

    /* Login */
    .login-wrapper {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 16px;
    }
    .login-card {
      background: #ffffff;
      border-radius: 14px;
      padding: 20px 22px;
      max-width: 360px;
      width: 100%;
      box-shadow: 0 8px 20px rgba(0,0,0,0.08);
    }
    .login-card h1 {
      margin: 0 0 8px;
      font-size: 20px;
    }
    .login-card p {
      margin: 0 0 14px;
      font-size: 13px;
      color: #666;
    }
    .login-card input {
      width: 100%;
      border-radius: 999px;
      border: 1px solid #cfd8dc;
      padding: 8px 10px;
      font-size: 13px;
      outline: none;
      margin-bottom: 12px;
    }
    .login-card input:focus {
      border-color: #64b5f6;
      box-shadow: 0 0 0 2px rgba(100,181,246,0.3);
    }
    .login-card button {
      width: 100%;
      border-radius: 999px;
      border: none;
      background: #1e88e5;
      color: #fff;
      padding: 8px 12px;
      font-size: 14px;
      cursor: pointer;
    }
    .login-card button:hover {
      background: #1976d2;
    }
    .login-note {
      margin-top: 10px;
      font-size: 12px;
      color: #78909c;
      line-height: 1.5;
    }

    /* App layout */
    #appView {
      display: none;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    header {
      padding: 12px 24px;
      background: #e3f2fd;
      border-bottom: 1px solid #cfd8dc;
    }
    .header-main {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 12px;
    }
    header h1 {
      margin: 0;
      font-size: 20px;
    }
    header p {
      margin: 4px 0 0;
      font-size: 13px;
      color: #555;
    }
    .header-left {
      min-width: 0;
    }
    .header-right {
      display: flex;
      align-items: center;
      gap: 16px;
      flex-wrap: wrap;
      justify-content: flex-end;
    }
    .nav-tabs {
      display: inline-flex;
      background: #bbdefb;
      border-radius: 999px;
      padding: 2px;
    }
    .tab {
      border: none;
      background: transparent;
      font-size: 13px;
      padding: 6px 12px;
      border-radius: 999px;
      cursor: pointer;
      color: #1e3a5f;
    }
    .tab.active {
      background: #ffffff;
      box-shadow: 0 2px 6px rgba(0,0,0,0.15);
    }
    .user-info {
      display: flex;
      align-items: center;
      gap: 6px;
      font-size: 12px;
      color: #455a64;
    }
    .user-info strong {
      max-width: 140px;
      overflow: hidden;
      text-overflow: ellipsis;
      white-space: nowrap;
    }
    .link-btn {
      border: none;
      background: transparent;
      font-size: 12px;
      color: #1565c0;
      cursor: pointer;
      padding: 0;
      text-decoration: underline;
    }

    main {
      flex: 1;
      display: grid;
      grid-template-columns: minmax(320px, 450px) minmax(360px, 1fr);
      gap: 16px;
      padding: 16px 24px 24px;
    }
    @media (max-width: 900px) {
      main {
        grid-template-columns: 1fr;
      }
    }

    .panel {
      background: #ffffff;
      border-radius: 12px;
      padding: 16px 18px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.06);
    }
    .panel h2 {
      margin: 0 0 8px;
      font-size: 16px;
    }
    .panel p.hint {
      margin: 0 0 12px;
      font-size: 12px;
      color: #777;
      line-height: 1.4;
    }

    textarea {
      width: 100%;
      min-height: 90px;
      resize: vertical;
      padding: 8px 10px;
      border-radius: 8px;
      border: 1px solid #cfd8dc;
      font-size: 13px;
      outline: none;
    }
    textarea:focus,
    input[type="text"]:focus {
      border-color: #64b5f6;
      box-shadow: 0 0 0 2px rgba(100,181,246,0.25);
    }
    input[type="text"] {
      width: 100%;
      border-radius: 8px;
      border: 1px solid #cfd8dc;
      padding: 6px 8px;
      font-size: 12px;
      margin-top: 4px;
      outline: none;
    }

    .field {
      margin-top: 12px;
      font-size: 13px;
    }
    .field label.title {
      display: block;
      margin-bottom: 4px;
      font-weight: 600;
    }

    .emotion-buttons {
      display: flex;
      flex-wrap: wrap;
      gap: 6px;
    }
    .emotion-btn {
      border-radius: 999px;
      padding: 4px 10px;
      font-size: 11px;
      cursor: pointer;
      display: inline-flex;
      flex-direction: row;
      align-items: center;
      gap: 4px;
      transition: all 0.15s ease;
      max-width: 48%;
      white-space: nowrap;
      border: 1px solid transparent;
      color: #263238;
    }
    .emotion-btn span.emoji {
      font-size: 14px;
    }
    .emotion-btn span.label-text {
      font-size: 11px;
    }
    .emotion-btn.active {
      box-shadow: 0 0 0 2px #1976d2;
      border-color: #1976d2;
      transform: translateY(-1px);
    }

    .chips, .radios {
      display: flex;
      flex-wrap: wrap;
      gap: 6px;
    }
    .chip, .radio-pill {
      font-size: 12px;
      padding: 4px 10px;
      border-radius: 999px;
      border: 1px solid #cfd8dc;
      background: #fafafa;
      cursor: pointer;
      display: inline-flex;
      align-items: center;
      gap: 6px;
      user-select: none;
    }
    .chip input,
    .radio-pill input {
      pointer-events: none;
    }
    .chip.active,
    .radio-pill.active {
      background: #bbdefb;
      border-color: #64b5f6;
    }

    .slider-row {
      display: flex;
      align-items: center;
      gap: 8px;
    }
    .slider-row input[type="range"] {
      flex: 1;
    }
    .slider-value {
      width: 28px;
      text-align: center;
      font-size: 12px;
      color: #555;
    }

    .btn-row {
      margin-top: 12px;
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
    }
    button.ghost {
      padding: 8px 14px;
      border-radius: 999px;
      border: 1px solid #b0bec5;
      background: #ffffff;
      cursor: pointer;
      font-size: 13px;
      color: #546e7a;
    }

    .canvas-wrapper {
      display: flex;
      flex-direction: column;
      gap: 10px;
      height: 100%;
    }
    .canvas-stack {
      position: relative;
      width: 100%;
      height: 100%;
      min-height: 320px;
      border-radius: 16px;
      box-shadow: inset 0 0 0 1px #e0e0e0;
      overflow: hidden;
      background: #ffffff;
    }
    #watercolorCanvas,
    #crayonCanvas {
      position: absolute;
      inset: 0;
      width: 100%;
      height: 100%;
      border-radius: 16px;
      background: transparent;
    }

    .note {
      font-size: 11px;
      color: #777;
      line-height: 1.5;
    }
    .summary {
      font-size: 12px;
      color: #455a64;
      background: #e3f2fd;
      border-radius: 8px;
      padding: 6px 8px;
      margin-top: 4px;
    }

    .crayon-tools {
      margin-top: 6px;
      display: flex;
      flex-direction: column;
      gap: 4px;
    }
    .crayon-colors {
      display: flex;
      flex-wrap: wrap;
      gap: 6px;
      align-items: center;
    }
    .crayon-color-btn {
      width: 18px;
      height: 18px;
      border-radius: 50%;
      border: 2px solid transparent;
      cursor: pointer;
      box-shadow: 0 0 0 1px rgba(0,0,0,0.1);
    }
    .crayon-color-btn.active {
      border-color: #263238;
      box-shadow: 0 0 0 2px rgba(38,50,56,0.6);
    }
    .crayon-label {
      font-size: 11px;
      color: #607d8b;
    }

    /* History view */
    #historyView {
      display: none;
      grid-template-columns: minmax(260px, 380px) minmax(360px, 1fr);
    }
    .stats-chart {
      margin-top: 10px;
      border-radius: 10px;
      background: #f5f9ff;
      padding: 10px 10px 6px;
      max-height: 380px;
      overflow: auto;
    }
    .bar-row {
      display: grid;
      grid-template-columns: 70px 1fr 30px;
      align-items: center;
      gap: 6px;
      margin-bottom: 6px;
      font-size: 11px;
    }
    .bar-label {
      color: #455a64;
    }
    .bar-track {
      height: 8px;
      border-radius: 999px;
      background: #e3f2fd;
      overflow: hidden;
    }
    .bar-fill {
      height: 100%;
      border-radius: 999px;
    }
    .bar-value {
      text-align: right;
      color: #607d8b;
    }

    .records-list {
      max-height: 480px;
      overflow: auto;
      display: flex;
      flex-direction: column;
      gap: 10px;
      padding-right: 4px;
    }
    .record-card {
      border-radius: 10px;
      border: 1px solid #e0e0e0;
      padding: 8px 10px;
      background: #fafafa;
      display: grid;
      grid-template-columns: 1.2fr 1fr;
      gap: 8px;
      align-items: flex-start;
      font-size: 12px;
    }
    @media (max-width: 900px) {
      .record-card {
        grid-template-columns: 1fr;
      }
    }
    .record-meta {
      color: #607d8b;
      margin-bottom: 4px;
    }
    .record-text {
      color: #37474f;
      margin-bottom: 4px;
      white-space: pre-wrap;
      word-break: break-word;
    }
    .record-img {
      width: 100%;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .record-badges {
      display: flex;
      flex-wrap: wrap;
      gap: 4px;
      margin-top: 4px;
    }
    .badge {
      font-size: 11px;
      padding: 2px 6px;
      border-radius: 999px;
      background: #e3f2fd;
      color: #1e3a5f;
    }
    .badge.main {
      background: #ffebee;
      color: #c62828;
    }
    .record-empty {
      font-size: 12px;
      color: #78909c;
      margin-top: 8px;
    }

    .range-pills {
      margin-top: 4px;
    }
  </style>
</head>
<body>

<!-- Login View -->
<div id="loginView" class="login-wrapper">
  <div class="login-card">
    <h1>情緒水彩室</h1>
    <p>輸入想在這裡使用的暱稱，就可以開始創作與紀錄。<br>目前只設計單一帳號，在這台裝置上會記住你的紀錄。</p>
    <input id="loginName" type="text" placeholder="輸入暱稱，例如：Freda" />
    <button id="loginBtn">登入</button>
    <div class="login-note">
      資料僅儲存在你的瀏覽器中（localStorage），不會上傳伺服器。<br>
      若清除瀏覽器資料，紀錄也會一併消失。
    </div>
  </div>
</div>

<!-- App View -->
<div id="appView">
  <header>
    <div class="header-main">
      <div class="header-left">
        <h1>情緒水彩室 Emotion Watercolor</h1>
        <p>輸入當下的心情與脈絡，畫布會自動回應，變成一幅屬於你的水彩＋蠟筆作品。</p>
      </div>
      <div class="header-right">
        <div class="nav-tabs">
          <button id="tabCreate" class="tab active">創作畫布</button>
          <button id="tabHistory" class="tab">情緒紀錄</button>
        </div>
        <div class="user-info">
          <span>登入身分：</span>
          <strong id="userNameLabel"></strong>
          <button id="logoutBtn" class="link-btn">登出</button>
        </div>
      </div>
    </div>
  </header>

  <!-- 創作畫布 view -->
  <main id="createView">
    <!-- 左側：輸入與心理指標 -->
    <section class="panel">
      <h2>1. 跟畫布說說今天的你</h2>
      <p class="hint">這不是測驗，你可以只寫一兩句，也可以多寫一點。這幅畫只屬於現在的你。</p>

      <textarea id="moodText" placeholder="今天發生了什麼事？或此刻你在想什麼呢？"></textarea>

      <!-- 觸發來源：事情／人／自己 -->
      <div class="field">
        <label class="title">這份情緒比較是因為⋯</label>
        <div class="radios" id="sourceGroup">
          <label class="radio-pill active">
            <input type="radio" name="source" value="thing" checked />
            一件事情／情境
          </label>
          <label class="radio-pill">
            <input type="radio" name="source" value="person" />
            某個人或關係
          </label>
          <label class="radio-pill">
            <input type="radio" name="source" value="self" />
            自己的狀態（例如身體、個性）
          </label>
          <label class="radio-pill">
            <input type="radio" name="source" value="unknown" />
            說不太上來
          </label>
        </div>
        <input type="text" id="triggerEvent" placeholder="若是事情：簡單寫一下，例如「報告被退件」「跟家人吵架」⋯" />
        <input type="text" id="triggerPerson" placeholder="若是人：和誰有關？可以寫「室友」「家人」「老師」或暱稱即可。" />
      </div>

      <!-- 情緒十二色相（伊登） -->
      <div class="field">
        <label class="title">這比較像哪一種感覺？（對應伊登十二色相環）</label>
        <div class="emotion-buttons" id="emotionButtons">
          <!-- 憤怒：紅 -->
          <button class="emotion-btn" data-valence="-1.5" data-hue="0" data-key="anger" style="background:#e53935;">
            <span class="emoji">🔥</span><span class="label-text">憤怒／被踩到底線</span>
          </button>
          <button class="emotion-btn" data-valence="-1.2" data-hue="20" data-key="fight" style="background:#ff7043;">
            <span class="emoji">⚡</span><span class="label-text">被點燃／想反擊</span>
          </button>
          <button class="emotion-btn" data-valence="0.5" data-hue="35" data-key="playful" style="background:#fb8c00;">
            <span class="emoji">🎭</span><span class="label-text">好玩／有點調皮</span>
          </button>
          <button class="emotion-btn" data-valence="1.0" data-hue="45" data-key="smallJoy" style="background:#ffb300;">
            <span class="emoji">🌤️</span><span class="label-text">小確幸／微微開心</span>
          </button>
          <button class="emotion-btn" data-valence="1.5" data-hue="60" data-key="joy" style="background:#fdd835;">
            <span class="emoji">😊</span><span class="label-text">開心／有希望</span>
          </button>
          <button class="emotion-btn" data-valence="-0.5" data-hue="90" data-key="anxious" style="background:#9ccc65;">
            <span class="emoji">😰</span><span class="label-text">焦躁／擔心</span>
          </button>
          <button class="emotion-btn" data-valence="0.2" data-hue="130" data-key="calm" style="background:#43a047;">
            <span class="emoji">🌿</span><span class="label-text">安穩／平靜</span>
          </button>
          <button class="emotion-btn" data-valence="-0.8" data-hue="170" data-key="lonely" style="background:#26a69a;">
            <span class="emoji">🚶</span><span class="label-text">孤單／被落下</span>
          </button>
          <button class="emotion-btn" data-valence="-1.2" data-hue="210" data-key="sad" style="background:#1e88e5;">
            <span class="emoji">😢</span><span class="label-text">悲傷／想哭</span>
          </button>
          <button class="emotion-btn" data-valence="-1.8" data-hue="250" data-key="despair" style="background:#5e35b1;">
            <span class="emoji">💧</span><span class="label-text">絕望／非常無力</span>
          </button>
          <button class="emotion-btn" data-valence="-1.0" data-hue="280" data-key="numb" style="background:#8e24aa;">
            <span class="emoji">🪵</span><span class="label-text">麻木／空掉</span>
          </button>
          <button class="emotion-btn" data-valence="-0.8" data-hue="320" data-key="hurt" style="background:#d81b60;">
            <span class="emoji">💔</span><span class="label-text">受傷／委屈</span>
          </button>
        </div>
        <p id="emotionDesc" class="hint" style="margin-top:4px;">
          選一個最接近的就好，不需要「選對」。顏色會一起帶進畫面裡。
        </p>
      </div>

      <!-- 四構面 -->
      <div class="field">
        <label class="title">此刻情緒強度（Arousal）</label>
        <div class="slider-row">
          <input type="range" id="arousal" min="1" max="5" value="3" />
          <span class="slider-value" id="arousalValue">3</span>
        </div>
        <p class="hint" style="margin-top:4px;">
          1 像是遠遠的影子，5 則是整個人都被捲進去。
        </p>
      </div>

      <div class="field">
        <label class="title">掌控感（Control）</label>
        <div class="slider-row">
          <input type="range" id="control" min="1" max="5" value="3" />
          <span class="slider-value" id="controlValue">3</span>
        </div>
        <p class="hint" style="margin-top:4px;">
          1＝完全被情緒拉著走，5＝我還掌握某些選擇。
        </p>
      </div>

      <div class="field">
        <label class="title">與他人的連結感（Social connection）</label>
        <div class="slider-row">
          <input type="range" id="social" min="1" max="5" value="3" />
          <span class="slider-value" id="socialValue">3</span>
        </div>
        <p class="hint" style="margin-top:4px;">
          1＝很孤單／被隔開，5＝有被看見、有人在旁邊。
        </p>
      </div>

      <!-- 支持感 -->
      <div class="field">
        <label class="title">你覺得現在有人在身邊支持嗎？</label>
        <div class="radios" id="supportGroup">
          <label class="radio-pill active">
            <input type="radio" name="support" value="2" checked />
            有，還滿明顯的
          </label>
          <label class="radio-pill">
            <input type="radio" name="support" value="1" />
            有一點，但不多
          </label>
          <label class="radio-pill">
            <input type="radio" name="support" value="0" />
            幾乎是自己撐著
          </label>
        </div>
      </div>

      <!-- 身體感受 -->
      <div class="field">
        <label class="title">身體有什麼感覺？（可複選，多選會疊更多水彩層）</label>
        <div class="chips" id="bodyGroup">
          <label class="chip">
            <input type="checkbox" value="head_pressure" />
            頭很脹／暈
          </label>
          <label class="chip">
            <input type="checkbox" value="eye_strain" />
            眼睛很累
          </label>
          <label class="chip">
            <input type="checkbox" value="shoulder_tense" />
            肩頸緊繃
          </label>
          <label class="chip">
            <input type="checkbox" value="chest_heavy" />
            胸口悶悶的
          </label>
          <label class="chip">
            <input type="checkbox" value="heart_fast" />
            心跳很快
          </label>
          <label class="chip">
            <input type="checkbox" value="stomach_unwell" />
            胃不太舒服
          </label>
          <label class="chip">
            <input type="checkbox" value="cold_limbs" />
            手腳冰冷
          </label>
          <label class="chip">
            <input type="checkbox" value="body_tired" />
            全身很疲憊
          </label>
          <label class="chip">
            <input type="checkbox" value="belly_warm" />
            肚子暖暖的
          </label>
          <label class="chip">
            <input type="checkbox" value="body_relaxed" />
            身體整體滿放鬆
          </label>
        </div>
      </div>

      <!-- 自我接納 -->
      <div class="field">
        <label class="title">你對現在這樣的自己？（Self-compassion）</label>
        <div class="radios" id="selfGroup">
          <label class="radio-pill">
            <input type="radio" name="selfAccept" value="0" />
            有點苛責
          </label>
          <label class="radio-pill active">
            <input type="radio" name="selfAccept" value="1" checked />
            還好，能理解
          </label>
          <label class="radio-pill">
            <input type="radio" name="selfAccept" value="2" />
            可以溫柔看待
          </label>
        </div>
      </div>

      <div class="btn-row">
        <button id="downloadBtn" class="ghost">
          存檔 & 下載圖片
        </button>
      </div>

      <div class="summary" id="summaryText" style="display:none;"></div>
    </section>

    <!-- 右側：畫布 -->
    <section class="panel">
      <div class="canvas-wrapper">
        <h2>2. 你的情緒水彩＋蠟筆畫布</h2>
        <p class="hint">
          作品沒有好壞，只是在記錄「此刻的你」。<br>
          你可以用蠟筆在上層畫線或畫滿一塊區域（左右垂直對稱），當成「我對這個情緒的回應」。
        </p>
        <div class="canvas-stack">
          <canvas id="watercolorCanvas"></canvas>
          <canvas id="crayonCanvas"></canvas>
        </div>

        <div class="crayon-tools">
          <div class="crayon-colors" id="crayonColors">
            <span class="crayon-label">蠟筆顏色：</span>
            <button class="crayon-color-btn active" data-color="#263238" style="background:#263238;"></button>
            <button class="crayon-color-btn" data-color="#ef5350" style="background:#ef5350;"></button>
            <button class="crayon-color-btn" data-color="#ffb300" style="background:#ffb300;"></button>
            <button class="crayon-color-btn" data-color="#66bb6a" style="background:#66bb6a;"></button>
            <button class="crayon-color-btn" data-color="#42a5f5" style="background:#42a5f5;"></button>
            <button class="crayon-color-btn" data-color="#ab47bc" style="background:#ab47bc;"></button>
            <button class="crayon-color-btn" data-color="#f06292" style="background:#f06292;"></button>
            <button class="crayon-color-btn" data-color="#ffffff" style="background:#ffffff;"></button>
          </div>
          <p class="hint">
            滑鼠按住拖曳可以畫出連續、柔軟的線條與面，左右會垂直對稱；蠟筆不會被重新生成的水彩洗掉。
          </p>
        </div>

        <p class="note">
          小提醒：這個網站不取代專業諮商。如果你正經歷很辛苦的狀態，仍然鼓勵尋求專業或信任的人陪伴。<br>
          （技術說明：畫面依據情緒色相（伊登十二色環）、強度、掌控感、連結感、身體感受與文字多重情緒，轉成多層水彩與蠟筆。） 
        </p>
      </div>
    </section>
  </main>

  <!-- 情緒紀錄 view -->
  <main id="historyView">
    <section class="panel">
      <h2>情緒統計</h2>
      <div class="field">
        <label class="title">時間範圍</label>
        <div class="radios range-pills" id="rangeGroup">
          <label class="radio-pill active">
            <input type="radio" name="range" value="all" checked />
            全部
          </label>
          <label class="radio-pill">
            <input type="radio" name="range" value="day" />
            今天
          </label>
          <label class="radio-pill">
            <input type="radio" name="range" value="week" />
            近一週
          </label>
          <label class="radio-pill">
            <input type="radio" name="range" value="month" />
            近一個月
          </label>
        </div>
      </div>
      <div id="statsChart" class="stats-chart"></div>
      <p class="hint">
        柱狀圖顯示在選定範圍內，各種情緒被選擇（主情緒）或在文字中被提到的次數。<br>
        它不是診斷，只是幫你看到一段時間內，哪些感受比較常出現。
      </p>
    </section>

    <section class="panel">
      <h2>歷史作品</h2>
      <div id="recordsList" class="records-list"></div>
    </section>
  </main>
</div>

<script>
  // ====== Login & basic app state ======
  const loginView = document.getElementById('loginView');
  const appView = document.getElementById('appView');
  const loginNameInput = document.getElementById('loginName');
  const loginBtn = document.getElementById('loginBtn');
  const userNameLabel = document.getElementById('userNameLabel');
  const logoutBtn = document.getElementById('logoutBtn');

  const tabCreate = document.getElementById('tabCreate');
  const tabHistory = document.getElementById('tabHistory');
  const createView = document.getElementById('createView');
  const historyView = document.getElementById('historyView');

  let currentUser = null;
  let records = [];
  let currentRange = 'all';

  function loadRecords() {
    const raw = localStorage.getItem('emotionWatercolorRecords');
    if (raw) {
      try {
        records = JSON.parse(raw);
      } catch {
        records = [];
      }
    } else {
      records = [];
    }
  }

  function persistRecords() {
    localStorage.setItem('emotionWatercolorRecords', JSON.stringify(records));
  }

  function showApp(userName) {
    currentUser = userName;
    userNameLabel.textContent = userName;
    loginView.style.display = 'none';
    appView.style.display = 'flex';
    loadRecords();
    renderHistory(currentRange);
    resizeCanvases();
    regenerateNow();
  }

  loginBtn.addEventListener('click', () => {
    const name = (loginNameInput.value || '').trim();
    if (!name) {
      alert('可以隨便打個暱稱，例如：Freda、柏文、心網旅人⋯');
      return;
    }
    localStorage.setItem('emotionWatercolorUser', name);
    showApp(name);
  });

  logoutBtn.addEventListener('click', () => {
    localStorage.removeItem('emotionWatercolorUser');
    location.reload();
  });

  const storedUser = localStorage.getItem('emotionWatercolorUser');
  if (storedUser) {
    showApp(storedUser);
  } else {
    loginView.style.display = 'flex';
    appView.style.display = 'none';
  }

  // Tabs
  tabCreate.addEventListener('click', () => {
    tabCreate.classList.add('active');
    tabHistory.classList.remove('active');
    createView.style.display = 'grid';
    historyView.style.display = 'none';
  });
  tabHistory.addEventListener('click', () => {
    tabHistory.classList.add('active');
    tabCreate.classList.remove('active');
    createView.style.display = 'none';
    historyView.style.display = 'grid';
    renderHistory(currentRange);
  });

  // ====== 互動 &畫布邏輯 ======
  const moodText = document.getElementById('moodText');
  const sourceGroup = document.getElementById('sourceGroup');
  const triggerEventInput = document.getElementById('triggerEvent');
  const triggerPersonInput = document.getElementById('triggerPerson');

  const emotionButtons = document.getElementById('emotionButtons');
  const emotionDesc = document.getElementById('emotionDesc');

  const arousalSlider = document.getElementById('arousal');
  const arousalValue = document.getElementById('arousalValue');
  const controlSlider = document.getElementById('control');
  const controlValue = document.getElementById('controlValue');
  const socialSlider = document.getElementById('social');
  const socialValue = document.getElementById('socialValue');

  const supportGroup = document.getElementById('supportGroup');
  const bodyGroup = document.getElementById('bodyGroup');
  const selfGroup = document.getElementById('selfGroup');
  const downloadBtn = document.getElementById('downloadBtn');
  const summaryText = document.getElementById('summaryText');

  const watercolorCanvas = document.getElementById('watercolorCanvas');
  const watercolorCtx = watercolorCanvas.getContext('2d');
  const crayonCanvas = document.getElementById('crayonCanvas');
  const crayonCtx = crayonCanvas.getContext('2d');
  const crayonColors = document.getElementById('crayonColors');

  const rangeGroup = document.getElementById('rangeGroup');
  const statsChart = document.getElementById('statsChart');
  const recordsList = document.getElementById('recordsList');

  const actionLog = [];
  function logAction(type, payload) {
    actionLog.push({
      type,
      time: new Date().toISOString(),
      payload
    });
  }

  const emotionDescriptions = {
    anger: '憤怒常常跟「界線被踩過」有關，也可能藏著很多委屈和想保護的東西。',
    fight: '被點燃的感覺，有一種「不想再忍了」的能量，既累又帶著動力。',
    playful: '有點調皮、想試試看的狀態，通常代表此刻有一點安全感，可以玩一下。',
    smallJoy: '日常的小確幸，可能只是很小的事，但會讓心裡微微亮起來。',
    joy: '開心與希望讓世界變得比較有顏色，也提醒你自己還有在在意的事物。',
    anxious: '焦躁與擔心常常讓腦袋停不下來，像是在等待一件不知道會不會發生的事。',
    calm: '不特別好也不特別壞，是某種「還撐得住」的平穩。',
    lonely: '人可能在身邊，但心裡卻覺得有一段距離，像被留在原地。',
    sad: '悲傷有時候很安靜，有時候會想哭，背後多半有失去的故事。',
    despair: '像是在很深的水裡，暫時看不到出口，但你還在這裡打字，這本身就不簡單。',
    numb: '麻木並不代表沒有感覺，而是情緒太多、太重，只好暫時關小音量。',
    hurt: '被誤解或被傷到的地方，常常是你很在意的地方。'
  };

  let selectedValence = 0;
  let selectedHue = 200;
  let selectedEmotionKey = null;
  let debounceTimer = null;

  function resizeCanvases() {
    const rect = watercolorCanvas.getBoundingClientRect();
    const dpr = window.devicePixelRatio || 1;

    watercolorCanvas.width = rect.width * dpr;
    watercolorCanvas.height = rect.height * dpr;
    watercolorCtx.setTransform(dpr, 0, 0, dpr, 0, 0);

    crayonCanvas.width = rect.width * dpr;
    crayonCanvas.height = rect.height * dpr;
    crayonCtx.setTransform(dpr, 0, 0, dpr, 0, 0);
  }

  window.addEventListener('resize', () => {
    resizeCanvases();
    regenerateNow();
  });

  // Emotion button
  emotionButtons.addEventListener('click', (e) => {
    const btn = e.target.closest('.emotion-btn');
    if (!btn) return;
    document.querySelectorAll('.emotion-btn').forEach(b => b.classList.remove('active'));
    btn.classList.add('active');
    selectedValence = parseFloat(btn.dataset.valence || '0');
    selectedHue = parseFloat(btn.dataset.hue || '200');
    selectedEmotionKey = btn.dataset.key || null;
    const key = btn.dataset.key;
    if (key && emotionDescriptions[key]) {
      emotionDesc.textContent = emotionDescriptions[key];
    } else {
      emotionDesc.textContent = '選一個最接近的就好，不需要「選對」。顏色會一起帶進畫面裡。';
    }
    logAction('selectEmotion', { key, valence: selectedValence, hue: selectedHue });
    scheduleRegenerate();
  });

  // slider
  arousalSlider.addEventListener('input', () => {
    arousalValue.textContent = arousalSlider.value;
    logAction('changeArousal', { value: arousalSlider.value });
    scheduleRegenerate();
  });
  controlSlider.addEventListener('input', () => {
    controlValue.textContent = controlSlider.value;
    logAction('changeControl', { value: controlSlider.value });
    scheduleRegenerate();
  });
  socialSlider.addEventListener('input', () => {
    socialValue.textContent = socialSlider.value;
    logAction('changeSocial', { value: socialSlider.value });
    scheduleRegenerate();
  });

  // pill / chip
  function setupToggleContainer(container, name) {
    container.addEventListener('click', (e) => {
      const pill = e.target.closest('.radio-pill, .chip');
      if (!pill) return;
      const input = pill.querySelector('input');
      if (!input) return;
      if (input.type === 'radio') {
        container.querySelectorAll('.radio-pill').forEach(p => p.classList.remove('active'));
        pill.classList.add('active');
        input.checked = true;
      } else if (input.type === 'checkbox') {
        pill.classList.toggle('active');
        input.checked = !input.checked;
      }
      logAction('changeField', { group: name, value: input.value, checked: input.checked });
      scheduleRegenerate();
    });
  }
  setupToggleContainer(sourceGroup, 'source');
  setupToggleContainer(supportGroup, 'support');
  setupToggleContainer(bodyGroup, 'body');
  setupToggleContainer(selfGroup, 'selfAccept');

  // range group (history)
  setupToggleContainer(rangeGroup, 'range');
  rangeGroup.addEventListener('click', (e) => {
    const input = e.target.closest('label')?.querySelector('input');
    if (!input) return;
    currentRange = input.value;
    renderHistory(currentRange);
  });

  // text input
  moodText.addEventListener('input', () => {
    logAction('inputMood', { value: moodText.value });
    scheduleRegenerate();
  });
  triggerEventInput.addEventListener('input', () => {
    logAction('inputTriggerEvent', { value: triggerEventInput.value });
    scheduleRegenerate();
  });
  triggerPersonInput.addEventListener('input', () => {
    logAction('inputTriggerPerson', { value: triggerPersonInput.value });
    scheduleRegenerate();
  });

  // valence from text
  function analyzeTextValence(text) {
    const t = text || '';
    const lower = t.toLowerCase();
    let score = 0;

    const negWords = ['難過','好累','壓力','焦慮','崩潰','生氣','討厭','不想','沮喪','孤單','煩','害怕','絕望','麻木','空掉','吵架'];
    const posWords = ['感謝','開心','期待','喜歡','放鬆','還好','舒服','充實','順利','很棒','幸福','安心','被理解'];

    negWords.forEach(w => { if (t.includes(w)) score -= 0.5; });
    posWords.forEach(w => { if (t.includes(w)) score += 0.5; });

    if (lower.includes('sad') || lower.includes('tired') || lower.includes('depress') || lower.includes('anxious')) score -= 0.5;
    if (lower.includes('happy') || lower.includes('grateful') || lower.includes('relax')) score += 0.5;

    if (score > 2) score = 2;
    if (score < -2) score = -2;
    return score;
  }

  // text multi emotion
  function analyzeTextEmotionKeywords(text) {
    const t = text || '';
    const defs = {
      anger: { hue: 0, words: ['生氣','憤怒','火大','不爽','被攻擊','吵架','氣炸'] },
      sad: { hue: 210, words: ['難過','悲傷','想哭','失落','心痛','心碎'] },
      anxious: { hue: 90, words: ['焦慮','緊張','擔心','不安','心慌','怕'] },
      joy: { hue: 60, words: ['開心','快樂','興奮','期待','幸福','感謝'] },
      lonely: { hue: 250, words: ['孤單','寂寞','被丟下','沒人懂','被忽略'] },
      numb: { hue: 280, words: ['麻木','空掉','沒有感覺','像關靜音'] },
      tired: { hue: 35, words: ['好累','疲憊','想睡','累翻','耗盡'] },
      calm: { hue: 130, words: ['平靜','安穩','穩定','還好','OK'] }
    };

    const result = {};
    Object.entries(defs).forEach(([key, def]) => {
      let count = 0;
      def.words.forEach(w => {
        let idx = t.indexOf(w);
        while (idx !== -1) {
          count++;
          idx = t.indexOf(w, idx + w.length);
        }
      });
      if (count > 0) {
        result[key] = { count, hue: def.hue };
      }
    });
    return result;
  }

  // metrics
  function metricsFromInputs() {
    const text = moodText.value.trim();
    const textValence = analyzeTextValence(text);
    const textEmotions = analyzeTextEmotionKeywords(text);

    const valence = (selectedValence || 0) * 0.7 + textValence * 0.3;
    const arousal = parseInt(arousalSlider.value, 10);
    const control = parseInt(controlSlider.value, 10);
    const social = parseInt(socialSlider.value, 10);

    const supportInput = supportGroup.querySelector('input[name="support"]:checked');
    const support = supportInput ? parseInt(supportInput.value, 10) : 1;

    const selfInput = selfGroup.querySelector('input[name="selfAccept"]:checked');
    const selfAccept = selfInput ? parseInt(selfInput.value, 10) : 1;

    const bodyChecked = Array.from(bodyGroup.querySelectorAll('input[type="checkbox"]:checked'))
      .map(i => i.value);

    const sourceInput = sourceGroup.querySelector('input[name="source"]:checked');
    const sourceType = sourceInput ? sourceInput.value : 'thing';
    const triggerEvent = triggerEventInput.value.trim();
    const triggerPerson = triggerPersonInput.value.trim();

    const tenseKeys = ['head_pressure','eye_strain','shoulder_tense','chest_heavy','heart_fast','stomach_unwell','cold_limbs','body_tired'];
    let tension = bodyChecked.filter(v => tenseKeys.includes(v)).length;
    if (tension > 3) tension = 3;

    let baseHue = selectedHue || 200;
    baseHue = (baseHue + valence * 6 + 360) % 360;

    let saturation = 55 + (arousal - 1) * 8;
    saturation -= (control - 3) * 2;
    if (saturation < 45) saturation = 45;
    if (saturation > 90) saturation = 90;

    let lightness = 55 + selfAccept * 6 + (social - 3) * 2;
    if (lightness < 45) lightness = 45;
    if (lightness > 80) lightness = 80;

    const centerStrength = 0.25 + (support + social) * 0.1;
    let spread = 0.7 + (arousal - 3) * 0.18 - (control - 3) * 0.1;
    if (spread < 0.4) spread = 0.4;
    if (spread > 1.4) spread = 1.4;

    return {
      text,
      valence,
      arousal,
      control,
      social,
      support,
      selfAccept,
      tension,
      baseHue,
      saturation,
      lightness,
      centerStrength,
      spread,
      bodyChecked,
      sourceType,
      triggerEvent,
      triggerPerson,
      textEmotions,
      emotionKey: selectedEmotionKey
    };
  }

  function hslToRgba(h, s, l, a) {
    s /= 100;
    l /= 100;
    const C = (1 - Math.abs(2 * l - 1)) * s;
    const X = C * (1 - Math.abs((h / 60) % 2 - 1));
    const m = l - C / 2;
    let r1, g1, b1;
    if (h >= 0 && h < 60)      { r1 = C; g1 = X; b1 = 0; }
    else if (h < 120)          { r1 = X; g1 = C; b1 = 0; }
    else if (h < 180)          { r1 = 0; g1 = C; b1 = X; }
    else if (h < 240)          { r1 = 0; g1 = X; b1 = C; }
    else if (h < 300)          { r1 = X; g1 = 0; b1 = C; }
    else                       { r1 = C; g1 = 0; b1 = C; }
    const r = Math.round((r1 + m) * 255);
    const g = Math.round((g1 + m) * 255);
    const b = Math.round((b1 + m) * 255);
    return `rgba(${r},${g},${b},${a})`;
  }

  function drawBodyOverlays(metrics, w, h) {
    const { bodyChecked, baseHue } = metrics;
    if (!bodyChecked || !bodyChecked.length) return;

    bodyChecked.forEach(type => {
      switch (type) {
        case 'head_pressure': {
          const cx = w / 2;
          const cy = h * 0.1;
          const r = w * 0.25;
          const grad = watercolorCtx.createRadialGradient(cx, cy, 0, cx, cy, r);
          grad.addColorStop(0, hslToRgba(baseHue - 15, 45, 45, 0.18));
          grad.addColorStop(1, hslToRgba(baseHue - 15, 45, 45, 0));
          watercolorCtx.fillStyle = grad;
          watercolorCtx.beginPath();
          watercolorCtx.arc(cx, cy, r, 0, Math.PI * 2);
          watercolorCtx.fill();
          break;
        }
        case 'eye_strain': {
          watercolorCtx.fillStyle = hslToRgba(baseHue - 5, 40, 60, 0.16);
          const rw = w * 0.5;
          const rh = h * 0.06;
          watercolorCtx.fillRect((w - rw)/2, h*0.12, rw, rh);
          break;
        }
        case 'shoulder_tense': {
          const grad = watercolorCtx.createLinearGradient(0, h*0.18, 0, h*0.3);
          grad.addColorStop(0, hslToRgba(baseHue - 10, 45, 50, 0.18));
          grad.addColorStop(1, hslToRgba(baseHue - 10, 45, 50, 0));
          watercolorCtx.fillStyle = grad;
          watercolorCtx.fillRect(w*0.1, h*0.2, w*0.8, h*0.15);
          break;
        }
        case 'chest_heavy': {
          const cx = w / 2;
          const cy = h * 0.4;
          const r = w * 0.3;
          const grad = watercolorCtx.createRadialGradient(cx, cy, 0, cx, cy, r);
          grad.addColorStop(0, hslToRgba(baseHue - 20, 50, 45, 0.18));
          grad.addColorStop(1, hslToRgba(baseHue - 20, 50, 45, 0));
          watercolorCtx.fillStyle = grad;
          watercolorCtx.beginPath();
          watercolorCtx.arc(cx, cy, r, 0, Math.PI * 2);
          watercolorCtx.fill();
          break;
        }
        case 'heart_fast': {
          const cx = w / 2;
          const cy = h * 0.36;
          const r = w * 0.18;
          const grad = watercolorCtx.createRadialGradient(cx, cy, 0, cx, cy, r);
          grad.addColorStop(0, hslToRgba(0, 80, 60, 0.26));
          grad.addColorStop(1, hslToRgba(0, 80, 60, 0));
          watercolorCtx.fillStyle = grad;
          watercolorCtx.beginPath();
          watercolorCtx.arc(cx, cy, r, 0, Math.PI * 2);
          watercolorCtx.fill();
          break;
        }
        case 'stomach_unwell': {
          const cx = w / 2;
          const cy = h * 0.6;
          const r = w * 0.25;
          const grad = watercolorCtx.createRadialGradient(cx, cy, 0, cx, cy, r);
          grad.addColorStop(0, hslToRgba(baseHue - 25, 50, 45, 0.18));
          grad.addColorStop(1, hslToRgba(baseHue - 25, 50, 45, 0));
          watercolorCtx.fillStyle = grad;
          watercolorCtx.beginPath();
          watercolorCtx.arc(cx, cy, r, 0, Math.PI * 2);
          watercolorCtx.fill();
          break;
        }
        case 'cold_limbs': {
          watercolorCtx.fillStyle = hslToRgba(210, 40, 70, 0.18);
          const r = w * 0.06;
          watercolorCtx.beginPath();
          watercolorCtx.arc(w*0.12, h*0.78, r, 0, Math.PI*2);
          watercolorCtx.arc(w*0.88, h*0.78, r, 0, Math.PI*2);
          watercolorCtx.arc(w*0.18, h*0.55, r, 0, Math.PI*2);
          watercolorCtx.arc(w*0.82, h*0.55, r, 0, Math.PI*2);
          watercolorCtx.fill();
          break;
        }
        case 'body_tired': {
          const grad = watercolorCtx.createLinearGradient(0, h*0.4, 0, h);
          grad.addColorStop(0, hslToRgba(baseHue + 190, 25, 55, 0.14));
          grad.addColorStop(1, hslToRgba(baseHue + 190, 25, 45, 0.2));
          watercolorCtx.fillStyle = grad;
          watercolorCtx.fillRect(0, h*0.4, w, h*0.6);
          break;
        }
        case 'belly_warm': {
          const cx = w / 2;
          const cy = h * 0.6;
          const r = w * 0.22;
          const grad = watercolorCtx.createRadialGradient(cx, cy, 0, cx, cy, r);
          grad.addColorStop(0, hslToRgba(35, 80, 75, 0.22));
          grad.addColorStop(1, hslToRgba(35, 80, 75, 0));
          watercolorCtx.fillStyle = grad;
          watercolorCtx.beginPath();
          watercolorCtx.arc(cx, cy, r, 0, Math.PI * 2);
          watercolorCtx.fill();
          break;
        }
        case 'body_relaxed': {
          const grad = watercolorCtx.createRadialGradient(w/2, h*0.5, 0, w/2, h*0.5, Math.max(w,h)*0.6);
          grad.addColorStop(0, hslToRgba(140, 40, 80, 0.22));
          grad.addColorStop(1, hslToRgba(140, 40, 80, 0));
          watercolorCtx.fillStyle = grad;
          watercolorCtx.fillRect(0, 0, w, h);
          break;
        }
      }
    });
  }

  function drawTextEmotionDots(metrics, w, h) {
    const ems = Object.entries(metrics.textEmotions || {});
    if (!ems.length) return;

    const total = ems.reduce((sum, [, v]) => sum + v.count, 0);
    if (total === 0) return;
    const maxCount = Math.max(...ems.map(([, v]) => v.count));
    const tightness = maxCount / total;

    const centerX = w / 2;
    const centerY = h / 2;
    const minSize = Math.min(w, h);

    ems.forEach(([key, v], idx) => {
      const count = v.count;
      const hue = v.hue;
      const angle = (idx / ems.length) * Math.PI * 2;
      const clusterDistance = (0.2 + (1 - tightness) * 0.25) * minSize;
      const cx = centerX + Math.cos(angle) * clusterDistance;
      const cy = centerY + Math.sin(angle) * clusterDistance;
      const dots = 3 + count * 2;
      const clusterRadius = 20 + count * 6;

      for (let i = 0; i < dots; i++) {
        const r = 3 + Math.random() * 4;
        const theta = Math.random() * Math.PI * 2;
        const dist = Math.random() * clusterRadius;
        const x = cx + Math.cos(theta) * dist;
        const y = cy + Math.sin(theta) * dist;
        watercolorCtx.fillStyle = hslToRgba(hue, 80, 65, 0.85);
        watercolorCtx.beginPath();
        watercolorCtx.arc(x, y, r, 0, Math.PI * 2);
        watercolorCtx.fill();
      }
    });
  }

  function drawWatercolor(metrics) {
    const {
      valence, arousal, tension, baseHue, saturation, lightness,
      centerStrength, spread
    } = metrics;

    const w = watercolorCanvas.width / (window.devicePixelRatio || 1);
    const h = watercolorCanvas.height / (window.devicePixelRatio || 1);

    watercolorCtx.clearRect(0, 0, w, h);

    watercolorCtx.fillStyle = '#ffffff';
    watercolorCtx.fillRect(0, 0, w, h);
    const bgColor = hslToRgba(baseHue, saturation * 0.5, lightness + 5, 0.12);
    watercolorCtx.fillStyle = bgColor;
    watercolorCtx.globalAlpha = 1;
    watercolorCtx.fillRect(0, 0, w, h);

    const blobs = 55 + arousal * 8 + (5 - (metrics.control || 3)) * 5;
    for (let i = 0; i < blobs; i++) {
      const centerX = w / 2;
      const centerY = h / 2;
      const randAngle = Math.random() * Math.PI * 2;
      const randRadius = (Math.random() ** centerStrength) *
        (Math.min(w, h) / 2 * spread);
      const x = centerX + Math.cos(randAngle) * randRadius;
      const y = centerY + Math.sin(randAngle) * randRadius;

      const baseR = Math.min(w, h) / 13;
      const radius = baseR * (0.6 + arousal * 0.25 + Math.random());

      const hueJitter = (Math.random() - 0.5) * 22;
      const localHue = (baseHue + hueJitter + 360) % 360;
      const localSat = saturation + (Math.random() - 0.5) * 10;
      const localLight = lightness + (Math.random() - 0.5) * 10;
      const gradient = watercolorCtx.createRadialGradient(x, y, 0, x, y, radius);
      const alphaCenter = 0.12 + arousal * 0.02;
      gradient.addColorStop(0, hslToRgba(localHue, localSat, localLight, alphaCenter));
      gradient.addColorStop(1, hslToRgba(localHue, localSat, localLight, 0));

      watercolorCtx.globalAlpha = 1;
      watercolorCtx.fillStyle = gradient;
      watercolorCtx.beginPath();
      watercolorCtx.arc(x, y, radius, 0, Math.PI * 2);
      watercolorCtx.fill();
    }

    // 緊繃線條：透明度 & 柔和度提高
    if (tension > 0) {
      const lines = 10 * tension;
      watercolorCtx.globalAlpha = 0.18 + tension * 0.04;
      watercolorCtx.lineCap = 'round';
      watercolorCtx.lineJoin = 'round';
      for (let i = 0; i < lines; i++) {
        let startX = Math.random() * w;
        let startY = Math.random() * h;
        let len = (Math.random() * 0.35 + 0.1) * Math.min(w, h);
        const angle = (Math.random() * 0.6 - 0.3) + (valence < 0 ? -Math.PI / 2 : -Math.PI / 4);
        const cp1x = startX + Math.cos(angle) * len * 0.4 + (Math.random() - 0.5) * 20;
        const cp1y = startY + Math.sin(angle) * len * 0.4 + (Math.random() - 0.5) * 20;
        const endX = startX + Math.cos(angle) * len;
        const endY = startY + Math.sin(angle) * len;

        const lineHue = (baseHue + (valence < 0 ? -10 : 10) + 360) % 360;
        watercolorCtx.strokeStyle = hslToRgba(lineHue, saturation + 5, lightness - 10, 0.7);
        watercolorCtx.lineWidth = 0.8 + Math.random() * 1.4;
        watercolorCtx.beginPath();
        watercolorCtx.moveTo(startX, startY);
        watercolorCtx.quadraticCurveTo(cp1x, cp1y, endX, endY);
        watercolorCtx.stroke();
      }
    }

    watercolorCtx.globalAlpha = 1;
    drawBodyOverlays(metrics, w, h);
    drawTextEmotionDots(metrics, w, h);
  }

  function updateSummary(metrics) {
    const { valence, arousal, support, selfAccept, tension, control, social, sourceType } = metrics;

    let tone = '';
    if (valence <= -1.2) tone = '畫面基底偏冷或偏暗，像是最近有不少沈重或辛苦的感受。';
    else if (valence < 0.3) tone = '顏色在冷暖之間，對應一種混雜、說不上好壞的狀態。';
    else tone = '整體色調偏暖、較亮，像是你還保留著一些亮度與希望。';

    let aDesc = '';
    if (arousal >= 4) aDesc = '情緒強度偏高，所以水彩色塊擴散得比較奔放。';
    else if (arousal <= 2) aDesc = '情緒強度較低，色塊也比較集中、安靜。';
    else aDesc = '強度適中，色彩在畫面裡慢慢地鋪散開來。';

    let cDesc = '';
    if (control <= 2) cDesc = '掌控感偏低，畫面稍微顯得凌亂一點，像在提醒情緒此刻很有份量。';
    else if (control >= 4) cDesc = '掌控感偏高，擴散範圍收斂一些，表示你在混亂裡還抓得到某些重心。';
    else cDesc = '掌控感居中，你既受到情緒影響，也還在找調整的空間。';

    let sDesc = '';
    if (social <= 2) sDesc = '連結感偏低，畫面刻意留了一些空白與較冷的色塊，像尚未被填滿的位置。';
    else if (social >= 4) sDesc = '連結感偏高，色塊較集中，畫面核心有一種被圍繞、被接住的感覺。';
    else sDesc = '連結感在中間，自我與他人之間依然在調整距離。';

    let tDesc = '';
    if (tension >= 2) tDesc = '身體緊繃感透過柔軟但明顯的線條被畫進去了，那些都是很值得被看見的訊號。';
    else if (tension === 1) tDesc = '有一些緊繃被畫在畫面上，但仍留有空間讓顏色流動。';
    else tDesc = '線條不多，代表身體相對沒有那麼緊繃或至少沒有被情緒完全拉走。';

    let srcDesc = '';
    if (sourceType === 'person') srcDesc = '這次的情緒比較跟「人或關係」有關，之後若願意，也可以回頭看看：對你最在意的是哪一塊。';
    else if (sourceType === 'thing') srcDesc = '這次的情緒主要來自某個事件或情境，有時也會牽動你對自己的看法。';
    else if (sourceType === 'self') srcDesc = '這份感受比較像是來自自己本身（身體或個性），這樣的覺察本身就很不容易。';
    else srcDesc = '來源暫時說不太上來也沒關係，有時候情緒只是先出現，理解會慢一點到。';

    let selfDesc = '';
    if (selfAccept === 2) selfDesc = '畫面亮度稍微提高，呼應你願意對現在的自己多一點理解與溫柔。';
    else if (selfAccept === 0) selfDesc = '如果此刻對自己有點苛責，畫面裡的對比與陰影，剛好也在提醒：那些批判的聲音也值得被好好看一眼。';
    else selfDesc = '你對自己的態度偏中性，因此畫面也落在明暗之間的一個折衷。';

    summaryText.innerHTML = tone + '<br>' + aDesc + ' ' + cDesc + '<br>' + sDesc + '<br>' + tDesc + '<br>' + srcDesc + '<br>' + selfDesc;
    summaryText.style.display = 'block';
  }

  function regenerateNow() {
    const metrics = metricsFromInputs();
    drawWatercolor(metrics);
    updateSummary(metrics);
    logAction('regenerate', {
      valence: metrics.valence,
      arousal: metrics.arousal,
      control: metrics.control,
      social: metrics.social,
      support: metrics.support,
      selfAccept: metrics.selfAccept,
      body: metrics.bodyChecked,
      sourceType: metrics.sourceType
    });
  }
  function scheduleRegenerate() {
    clearTimeout(debounceTimer);
    debounceTimer = setTimeout(regenerateNow, 250);
  }

  // ====== 蠟筆（垂直對稱＋柔軟弧線） ======
  let currentCrayonColor = '#263238';
  let isDrawing = false;
  let lastX = 0;
  let lastY = 0;
  let lastMidX = 0;
  let lastMidY = 0;
  let hasLastMid = false;

  function getCanvasPos(e) {
    const rect = crayonCanvas.getBoundingClientRect();
    const isTouch = e.touches && e.touches.length > 0;
    const clientX = isTouch ? e.touches[0].clientX : e.clientX;
    const clientY = isTouch ? e.touches[0].clientY : e.clientY;
    return {
      x: clientX - rect.left,
      y: clientY - rect.top,
      width: rect.width
    };
  }

  function startDrawing(e) {
    e.preventDefault();
    const pos = getCanvasPos(e);
    isDrawing = true;
    lastX = pos.x;
    lastY = pos.y;
    lastMidX = pos.x;
    lastMidY = pos.y;
    hasLastMid = false;
    logAction('startDrawing', { x: pos.x, y: pos.y, color: currentCrayonColor });
  }

  function drawCrayon(e) {
    if (!isDrawing) return;
    e.preventDefault();
    const pos = getCanvasPos(e);
    const rectWidth = pos.width;

    const nowX = pos.x;
    const nowY = pos.y;
    const midX = (lastX + nowX) / 2;
    const midY = (lastY + nowY) / 2;

    crayonCtx.strokeStyle = currentCrayonColor;
    crayonCtx.lineWidth = 9;
    crayonCtx.lineCap = 'round';
    crayonCtx.lineJoin = 'round';
    crayonCtx.globalAlpha = 0.9;

    // 原本那條（用 quadratic curve 柔化）
    crayonCtx.beginPath();
    if (!hasLastMid) {
      crayonCtx.moveTo(lastX, lastY);
    } else {
      crayonCtx.moveTo(lastMidX, lastMidY);
    }
    crayonCtx.quadraticCurveTo(lastX, lastY, midX, midY);
    crayonCtx.stroke();

    // 垂直鏡像那條
    const mirrorLastX = rectWidth - lastX;
    const mirrorNowX = rectWidth - nowX;
    const mirrorMidX = (mirrorLastX + mirrorNowX) / 2;

    crayonCtx.beginPath();
    if (!hasLastMid) {
      crayonCtx.moveTo(mirrorLastX, lastY);
    } else {
      const mirrorLastMidX = rectWidth - lastMidX;
      crayonCtx.moveTo(mirrorLastMidX, lastMidY);
    }
    crayonCtx.quadraticCurveTo(mirrorLastX, lastY, mirrorMidX, midY);
    crayonCtx.stroke();

    logAction('drawSegment', {
      from: { x: lastX, y: lastY },
      to: { x: nowX, y: nowY },
      mirror: true,
      color: currentCrayonColor
    });

    lastX = nowX;
    lastY = nowY;
    lastMidX = midX;
    lastMidY = midY;
    hasLastMid = true;
  }

  function stopDrawing() {
    if (isDrawing) {
      logAction('stopDrawing', {});
    }
    isDrawing = false;
    hasLastMid = false;
  }

  crayonCanvas.addEventListener('mousedown', startDrawing);
  crayonCanvas.addEventListener('mousemove', drawCrayon);
  crayonCanvas.addEventListener('mouseup', stopDrawing);
  crayonCanvas.addEventListener('mouseleave', stopDrawing);
  crayonCanvas.addEventListener('touchstart', startDrawing, { passive: false });
  crayonCanvas.addEventListener('touchmove', drawCrayon, { passive: false });
  crayonCanvas.addEventListener('touchend', stopDrawing);

  crayonColors.addEventListener('click', (e) => {
    const btn = e.target.closest('.crayon-color-btn');
    if (!btn) return;
    document.querySelectorAll('.crayon-color-btn').forEach(b => b.classList.remove('active'));
    btn.classList.add('active');
    currentCrayonColor = btn.dataset.color || '#263238';
    logAction('changeCrayonColor', { color: currentCrayonColor });
  });

  // ====== 存檔＋下載（只圖） ======
  function saveRecordAndDownload() {
    const metrics = metricsFromInputs();

    const exportCanvas = document.createElement('canvas');
    exportCanvas.width = watercolorCanvas.width;
    exportCanvas.height = watercolorCanvas.height;
    const exportCtx = exportCanvas.getContext('2d');
    exportCtx.drawImage(watercolorCanvas, 0, 0);
    exportCtx.drawImage(crayonCanvas, 0, 0);
    const imageDataUrl = exportCanvas.toDataURL('image/png');

    const snippet = (metrics.text || '').slice(0, 80);
    const record = {
      id: Date.now(),
      user: currentUser,
      createdAt: new Date().toISOString(),
      metrics,
      textSnippet: snippet,
      imageDataUrl
    };
    records.push(record);
    persistRecords();
    renderHistory(currentRange);

    logAction('saveRecord', { id: record.id });

    const imgLink = document.createElement('a');
    imgLink.download = 'emotion-watercolor.png';
    imgLink.href = imageDataUrl;
    imgLink.click();
  }

  downloadBtn.addEventListener('click', saveRecordAndDownload);

  // ====== History view ======
  const emotionLabels = {
    anger: '憤怒',
    fight: '被點燃',
    playful: '好玩',
    smallJoy: '小確幸',
    joy: '開心',
    anxious: '焦慮',
    calm: '平靜',
    lonely: '孤單',
    sad: '悲傷',
    despair: '絕望',
    numb: '麻木',
    hurt: '受傷',
    tired: '疲憊'
  };

  const emotionHueMap = {
    anger: 0,
    fight: 20,
    playful: 35,
    smallJoy: 45,
    joy: 60,
    anxious: 90,
    calm: 130,
    lonely: 170,
    sad: 210,
    despair: 250,
    numb: 280,
    hurt: 320,
    tired: 35
  };

  function filterRecordsByRange(range) {
    if (!records.length) return [];
    const now = new Date();
    return records.filter(r => {
      if (!r.createdAt) return false;
      const d = new Date(r.createdAt);
      if (range === 'day') {
        return d.toDateString() === now.toDateString();
      } else if (range === 'week') {
        const diff = now - d;
        return diff <= 7 * 24 * 60 * 60 * 1000;
      } else if (range === 'month') {
        const diff = now - d;
        return diff <= 30 * 24 * 60 * 60 * 1000;
      }
      return true;
    });
  }

  function renderStats(range) {
    const filtered = filterRecordsByRange(range);
    statsChart.innerHTML = '';
    if (!filtered.length) {
      statsChart.textContent = '目前這個時間範圍內沒有紀錄。先從創作畫布開始一幅作品吧。';
      return;
    }

    const counts = {};
    filtered.forEach(r => {
      const key = r.metrics?.emotionKey;
      if (key) {
        counts[key] = (counts[key] || 0) + 1;
      }
      const textEmo = r.metrics?.textEmotions || {};
      Object.entries(textEmo).forEach(([k, v]) => {
        counts[k] = (counts[k] || 0) + (v.count || 0);
      });
    });

    const entries = Object.entries(counts).sort((a,b) => b[1] - a[1]);
    const maxCount = entries.length ? Math.max(...entries.map(e => e[1])) : 1;

    entries.forEach(([key, value]) => {
      const row = document.createElement('div');
      row.className = 'bar-row';

      const labelSpan = document.createElement('span');
      labelSpan.className = 'bar-label';
      labelSpan.textContent = emotionLabels[key] || key;

      const track = document.createElement('div');
      track.className = 'bar-track';

      const fill = document.createElement('div');
      fill.className = 'bar-fill';
      const widthPercent = maxCount === 0 ? 0 : (value / maxCount) * 100;
      fill.style.width = widthPercent + '%';
      const hue = emotionHueMap[key] ?? 200;
      fill.style.background = `hsl(${hue}, 80%, 60%)`;

      track.appendChild(fill);

      const valueSpan = document.createElement('span');
      valueSpan.className = 'bar-value';
      valueSpan.textContent = value;

      row.appendChild(labelSpan);
      row.appendChild(track);
      row.appendChild(valueSpan);
      statsChart.appendChild(row);
    });
  }

  function applyRecordToInputs(rec) {
    const m = rec.metrics || {};
    moodText.value = m.text || '';
    arousalSlider.value = m.arousal || 3;
    arousalValue.textContent = arousalSlider.value;
    controlSlider.value = m.control || 3;
    controlValue.textContent = controlSlider.value;
    socialSlider.value = m.social || 3;
    socialValue.textContent = socialSlider.value;

    // source
    if (m.sourceType) {
      const input = sourceGroup.querySelector(`input[value="${m.sourceType}"]`);
      sourceGroup.querySelectorAll('.radio-pill').forEach(p => p.classList.remove('active'));
      if (input) {
        input.checked = true;
        input.closest('.radio-pill').classList.add('active');
      }
    }
    triggerEventInput.value = m.triggerEvent || '';
    triggerPersonInput.value = m.triggerPerson || '';

    // support
    if (typeof m.support === 'number') {
      const input = supportGroup.querySelector(`input[value="${m.support}"]`);
      supportGroup.querySelectorAll('.radio-pill').forEach(p => p.classList.remove('active'));
      if (input) {
        input.checked = true;
        input.closest('.radio-pill').classList.add('active');
      }
    }

    // selfAccept
    if (typeof m.selfAccept === 'number') {
      const input = selfGroup.querySelector(`input[value="${m.selfAccept}"]`);
      selfGroup.querySelectorAll('.radio-pill').forEach(p => p.classList.remove('active'));
      if (input) {
        input.checked = true;
        input.closest('.radio-pill').classList.add('active');
      }
    }

    // body
    bodyGroup.querySelectorAll('.chip').forEach(chip => {
      chip.classList.remove('active');
      const input = chip.querySelector('input');
      if (input) input.checked = false;
    });
    (m.bodyChecked || []).forEach(val => {
      const input = bodyGroup.querySelector(`input[value="${val}"]`);
      if (input) {
        input.checked = true;
        input.closest('.chip').classList.add('active');
      }
    });

    // emotion button
    if (m.emotionKey) {
      document.querySelectorAll('.emotion-btn').forEach(b => b.classList.remove('active'));
      const btn = emotionButtons.querySelector(`.emotion-btn[data-key="${m.emotionKey}"]`);
      if (btn) {
        btn.classList.add('active');
        selectedValence = parseFloat(btn.dataset.valence || '0');
        selectedHue = parseFloat(btn.dataset.hue || '200');
        selectedEmotionKey = m.emotionKey;
        const key = m.emotionKey;
        if (key && emotionDescriptions[key]) {
          emotionDesc.textContent = emotionDescriptions[key];
        }
      }
    }

    regenerateNow();
    tabCreate.click();
  }

  function renderRecords(range) {
    const filtered = filterRecordsByRange(range).slice().sort((a,b) => new Date(b.createdAt) - new Date(a.createdAt));
    recordsList.innerHTML = '';
    if (!filtered.length) {
      const empty = document.createElement('div');
      empty.className = 'record-empty';
      empty.textContent = '這個時間範圍內還沒有作品紀錄。';
      recordsList.appendChild(empty);
      return;
    }

    filtered.forEach(rec => {
      const card = document.createElement('div');
      card.className = 'record-card';

      const left = document.createElement('div');
      const right = document.createElement('div');

      const meta = document.createElement('div');
      meta.className = 'record-meta';
      const d = new Date(rec.createdAt);
      meta.textContent = d.toLocaleString('zh-TW', { hour12: false });

      const text = document.createElement('div');
      text.className = 'record-text';
      text.textContent = rec.textSnippet || '（當時沒有輸入文字）';

      const badges = document.createElement('div');
      badges.className = 'record-badges';

      if (rec.metrics?.emotionKey) {
        const b = document.createElement('span');
        b.className = 'badge main';
        b.textContent = '主情緒：' + (emotionLabels[rec.metrics.emotionKey] || rec.metrics.emotionKey);
        badges.appendChild(b);
      }

      const emoKeys = Object.keys(rec.metrics?.textEmotions || {});
      if (emoKeys.length) {
        const b = document.createElement('span');
        b.className = 'badge';
        const labels = emoKeys.map(k => emotionLabels[k] || k);
        b.textContent = '文字情緒：' + labels.join('、');
        badges.appendChild(b);
      }

      const loadBtn = document.createElement('button');
      loadBtn.className = 'ghost';
      loadBtn.style.marginTop = '6px';
      loadBtn.textContent = '載入到畫布';
      loadBtn.addEventListener('click', () => applyRecordToInputs(rec));

      left.appendChild(meta);
      left.appendChild(text);
      left.appendChild(badges);
      left.appendChild(loadBtn);

      const img = document.createElement('img');
      img.className = 'record-img';
      img.src = rec.imageDataUrl;
      img.alt = '情緒作品';

      right.appendChild(img);

      card.appendChild(left);
      card.appendChild(right);
      recordsList.appendChild(card);
    });
  }

  function renderHistory(range) {
    renderStats(range);
    renderRecords(range);
  }

  // 初始化
  resizeCanvases();
  regenerateNow();
</script>
</body>
</html>
