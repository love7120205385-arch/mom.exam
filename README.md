<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>金融市場常識與職業道德｜100題快速背誦版</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@500;600;700&family=Noto+Sans+TC:wght@400;500;700;900&display=swap" rel="stylesheet" />
  <style>
    :root {
      --bg: #f6efe6;
      --bg-soft: #efe4d6;
      --card: #fffdf9;
      --ink: #2d1e17;
      --muted: #6b5344;
      --accent: #a66a3e;
      --accent-deep: #7a3e18;
      --accent-soft: #fbf2e6;
      --border: #e3d4c2;
      --shadow: 0 4px 16px rgba(74, 47, 29, 0.06);
      --q-size: 1.2rem;
      --a-size: 1.25rem;
      --meta-size: 0.95rem;
    }

    body.font-lg {
      --q-size: 1.4rem;
      --a-size: 1.45rem;
      --meta-size: 1.05rem;
    }

    body.font-xl {
      --q-size: 1.65rem;
      --a-size: 1.7rem;
      --meta-size: 1.15rem;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      padding: 0;
      background-color: var(--bg);
      color: var(--ink);
      font-family: 'Noto Sans TC', 'PingFang TC', 'Microsoft JhengHei', 'Inter', sans-serif;
      line-height: 1.65;
      -webkit-font-smoothing: antialiased;
    }

    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 24px 16px 64px;
    }

    /* Header */
    .hero {
      background: linear-gradient(135deg, #fffdf9 0%, #f3e7d8 100%);
      border: 1px solid var(--border);
      border-radius: 20px;
      padding: 24px 24px 20px;
      margin-bottom: 18px;
      box-shadow: var(--shadow);
    }

    .hero-badge {
      display: inline-block;
      background-color: var(--bg-soft);
      color: var(--accent-deep);
      font-weight: 700;
      font-size: 0.9rem;
      padding: 4px 12px;
      border-radius: 999px;
      margin-bottom: 10px;
      border: 1px solid var(--border);
    }

    .hero h1 {
      margin: 0 0 8px;
      font-size: clamp(1.5rem, 3.5vw, 2.05rem);
      font-weight: 900;
      color: var(--ink);
      line-height: 1.3;
    }

    .hero p {
      margin: 0;
      color: var(--muted);
      font-size: 1.02rem;
    }

    .order-guide {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      gap: 8px;
      margin-top: 14px;
      padding-top: 14px;
      border-top: 1px dashed var(--border);
      font-size: 0.95rem;
      color: var(--muted);
    }

    .order-step {
      background: var(--card);
      border: 1px solid var(--border);
      color: var(--accent-deep);
      font-weight: 700;
      padding: 3px 10px;
      border-radius: 8px;
    }

    /* Controls Bar */
    .controls {
      background: var(--card);
      backdrop-filter: blur(8px);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 14px;
      margin-bottom: 20px;
      box-shadow: 0 6px 20px rgba(74, 47, 29, 0.08);
      display: flex;
      flex-direction: column;
      gap: 12px;
    }

    .controls-row {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      align-items: center;
      justify-content: space-between;
    }

    .tab-group,
    .size-group {
      display: flex;
      flex-wrap: wrap;
      gap: 6px;
    }

    .btn {
      appearance: none;
      border: 1px solid var(--border);
      background: var(--bg);
      color: var(--ink);
      font-family: inherit;
      font-size: 0.95rem;
      font-weight: 700;
      padding: 8px 14px;
      border-radius: 10px;
      cursor: pointer;
      transition: all 0.15s ease;
    }

    .btn:hover {
      background: var(--bg-soft);
    }

    .btn.active {
      background: var(--accent);
      color: #ffffff;
      border-color: var(--accent);
    }

    .btn-print {
      background: var(--card);
      color: var(--accent-deep);
    }

    .search-row {
      display: flex;
      gap: 10px;
      align-items: center;
      flex-wrap: wrap;
    }

    .search-input {
      flex: 1;
      min-width: 200px;
      padding: 10px 14px;
      border-radius: 10px;
      border: 1px solid var(--border);
      background: var(--card);
      color: var(--ink);
      font-family: inherit;
      font-size: 1rem;
      outline: none;
    }

    .search-input:focus {
      border-color: var(--accent);
      box-shadow: 0 0 0 3px rgba(166, 106, 62, 0.16);
    }

    .count-label {
      font-size: 0.92rem;
      color: var(--muted);
      font-weight: 600;
      white-space: nowrap;
    }

    /* Section Header */
    .section-divider {
      margin: 26px 0 14px;
      padding: 12px 18px;
      background: var(--bg-soft);
      border-left: 5px solid var(--accent);
      border-radius: 10px;
      font-size: 1.2rem;
      font-weight: 900;
      color: var(--ink);
    }

    /* Question Card: 答案 — 題目 — 必須點選答案 */
    .q-list {
      display: flex;
      flex-direction: column;
      gap: 14px;
    }

    .q-card {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 18px 20px;
      box-shadow: 0 2px 10px rgba(74, 47, 29, 0.04);
      display: flex;
      flex-direction: column;
      gap: 12px;
      page-break-inside: avoid;
      break-inside: avoid;
    }

    /* 1. 答案 */
    .q-answer-row {
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 8px;
    }

    .ans-pill {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      background: var(--accent);
      color: #ffffff;
      font-weight: 900;
      font-size: var(--meta-size);
      padding: 5px 14px;
      border-radius: 999px;
      letter-spacing: 0.03em;
    }

    .q-num-tag {
      font-size: var(--meta-size);
      font-weight: 700;
      color: var(--muted);
      background: var(--bg);
      padding: 4px 10px;
      border-radius: 8px;
      border: 1px solid var(--border);
    }

    /* 2. 題目 */
    .q-title {
      font-size: var(--q-size);
      font-weight: 700;
      color: var(--ink);
      line-height: 1.55;
      margin: 0;
    }

    /* 3. 必須點選答案 */
    .must-pick {
      background: var(--accent-soft);
      border: 1px solid #e6cdb2;
      border-left: 5px solid var(--accent);
      border-radius: 10px;
      padding: 11px 14px;
      display: flex;
      flex-wrap: wrap;
      align-items: baseline;
      gap: 8px;
    }

    .must-pick-label {
      font-size: var(--meta-size);
      font-weight: 700;
      color: var(--accent-deep);
      white-space: nowrap;
    }

    .must-pick-text {
      font-size: var(--a-size);
      font-weight: 900;
      color: var(--accent-deep);
      line-height: 1.45;
    }

    /* Tips Box */
    .tips-box {
      margin-top: 28px;
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 20px 22px;
      box-shadow: var(--shadow);
    }

    .tips-box h2 {
      margin: 0 0 10px;
      font-size: 1.2rem;
      color: var(--accent-deep);
    }

    .tips-box ul {
      margin: 0;
      padding-left: 20px;
      color: var(--ink);
    }

    .tips-box li {
      margin-bottom: 6px;
      font-size: 1.02rem;
    }

    .empty-state {
      text-align: center;
      padding: 40px 20px;
      background: var(--card);
      border: 1px dashed var(--border);
      border-radius: 16px;
      color: var(--muted);
      font-size: 1.1rem;
    }

    .back-top {
      position: fixed;
      right: 18px;
      bottom: 18px;
      background: var(--accent);
      color: #ffffff;
      border: none;
      border-radius: 999px;
      padding: 10px 16px;
      font-family: inherit;
      font-weight: 700;
      font-size: 0.95rem;
      cursor: pointer;
      box-shadow: 0 4px 14px rgba(74, 47, 29, 0.25);
      z-index: 30;
    }

    .back-top:hover {
      background: var(--accent-deep);
    }

    @media (max-width: 600px) {
      .container {
        padding: 14px 12px 64px;
      }
      .q-card {
        padding: 14px 15px;
      }
      .btn {
        padding: 7px 11px;
        font-size: 0.9rem;
      }
    }

    @media print {
      body {
        background: #ffffff;
      }
      .controls,
      .back-top {
        display: none !important;
      }
      .container {
        max-width: 100%;
        padding: 0;
      }
      .q-card {
        box-shadow: none;
        border: 1px solid #cccccc;
      }
    }
  </style>
</head>
<body class="font-lg">
  <div class="container" id="top">
    <header class="hero">
      <div class="hero-badge">媽媽專屬・快速背誦版</div>
      <h1>金融市場常識與職業道德（100 題）</h1>
    </header>

    <section class="controls" aria-label="瀏覽與字體設定">
      <div class="controls-row">
        <div class="tab-group" id="tabGroup">
          <button type="button" class="btn active" data-filter="all">全部 100 題</button>
          <button type="button" class="btn" data-filter="part1">一、金融市場常識 (1–50)</button>
          <button type="button" class="btn" data-filter="part2">二、職業道德 (51–100)</button>
        </div>
        <div class="size-group" id="sizeGroup">
          <button type="button" class="btn" data-size="font-md">標準字</button>
          <button type="button" class="btn active" data-size="font-lg">大字體</button>
          <button type="button" class="btn" data-size="font-xl">超大字</button>
        </div>
      </div>
    </section>

    <main id="quizContainer"></main>

    <section class="tips-box">
      <h2>考前快速檢核建議</h2>
      <ul>
        <li><strong>第 1～50 題（金融市場常識）</strong>：若有不熟的觀念（如貨幣／資本市場工具、存保額度 300 萬元、ETF、洗錢防制），建議多看兩遍。</li>
        <li><strong>第 51～100 題（職業道德）</strong>：只要把握「<strong>誠信、保密、不代操、不保證獲利、客戶利益優先</strong>」五大原則，正式考試時這 50 題幾乎可以全拿。</li>
      </ul>
    </section>
  </div>

  <button type="button" class="back-top" id="backTopBtn">回頂部</button>

  <script>
    const QUESTIONS = [
      // 一、金融市場常識（第 1～50 題）
      { id: 1, part: 'part1', ans: 'B', q: '依金融市場工具的到期期間長短，一般以幾年為界分為貨幣市場與資本市場？', pick: '(B) 一年' },
      { id: 2, part: 'part1', ans: 'C', q: '下列何者「不屬於」貨幣市場的信用工具？', pick: '(C) 公司債' },
      { id: 3, part: 'part1', ans: 'A', q: '企業首次公開發行股票（IPO）並向投資人募集資金的市場稱為？', pick: '(A) 初級市場' },
      { id: 4, part: 'part1', ans: 'D', q: '我國中央銀行的貨幣政策工具中，最常在公開市場買賣的標的為何？', pick: '(D) 政府公債與國庫券' },
      { id: 5, part: 'part1', ans: 'B', q: '銀行辦理授信業務時，評估借款戶的「5P 原則」不包括下列何者？', pick: '(B) 獲利性（Profit）' },
      { id: 6, part: 'part1', ans: 'A', q: '當中央銀行調升「存款準備率」時，對市場資金的影響為何？', pick: '(A) 市場資金緊縮，利率傾向上升' },
      { id: 7, part: 'part1', ans: 'C', q: '下列何者為我國目前負責金融監理的主管機關？', pick: '(C) 金融監督管理委員會' },
      { id: 8, part: 'part1', ans: 'D', q: '商業銀行辦理定期存款，其存款期限最長不得超過幾年？', pick: '(D) 不受限制（一般常見為一年至三年）' },
      { id: 9, part: 'part1', ans: 'B', q: '關於「可轉讓定期存單（NCD）」的敘述，下列何者正確？', pick: '(B) 屬於貨幣市場工具' },
      { id: 10, part: 'part1', ans: 'A', q: '下列何種金融機構的主要業務為吸收社會大眾存款並辦理放款？', pick: '(A) 商業銀行' },
      { id: 11, part: 'part1', ans: 'C', q: '投資人買進股票後，能享有的權利不包括下列何者？', pick: '(C) 固定利息請求權' },
      { id: 12, part: 'part1', ans: 'B', q: '關於「特別股」與「普通股」的比較，下列何者正確？', pick: '(B) 特別股在股利分配上優先於普通股' },
      { id: 13, part: 'part1', ans: 'D', q: '我國上市股票集中交易市場的漲跌幅限制目前為前一日收盤價的多少？', pick: '(D) 10%' },
      { id: 14, part: 'part1', ans: 'A', q: '台灣證券交易所編製的「發行量加權股價指數」是以什麼作為權數計算？', pick: '(A) 發行股數（市值）' },
      { id: 15, part: 'part1', ans: 'C', q: '債券的「票面利率」高於「市場利率」時，該債券通常會以何種價格發行？', pick: '(C) 溢價發行' },
      { id: 16, part: 'part1', ans: 'B', q: '債券價格與市場殖利率之間的關係為何？', pick: '(B) 反向變動' },
      { id: 17, part: 'part1', ans: 'A', q: '下列何種債券風險最低，常被視為「無風險利率」的指標？', pick: '(A) 中央政府公債' },
      { id: 18, part: 'part1', ans: 'D', q: '共同基金依投資標的區分，風險與報酬通常最高的是哪一種？', pick: '(D) 股票型基金' },
      { id: 19, part: 'part1', ans: 'B', q: '指數股票型基金（ETF）與一般開放式共同基金最大的差異在於？', pick: '(B) ETF 可在證券交易所盤中即時買賣' },
      { id: 20, part: 'part1', ans: 'C', q: '期貨交易中，當投資人帳戶內的保證金低於「維持保證金」時，會收到何種通知？', pick: '(C) 追繳保證金通知（Margin Call）' },
      { id: 21, part: 'part1', ans: 'A', q: '關於「選擇權（Options）」的敘述，下列何者正確？', pick: '(A) 買方有權利但無義務履約' },
      { id: 22, part: 'part1', ans: 'B', q: '下列何者為我國期貨市場的集中交易場所？', pick: '(B) 台灣期貨交易所' },
      { id: 23, part: 'part1', ans: 'D', q: '保險法中規定，要保人對保險標的必須具有經濟上的利害關係，稱為什麼原則？', pick: '(D) 保險利益原則' },
      { id: 24, part: 'part1', ans: 'C', q: '下列何種保險「不適用」損害填補原則（即不適用複保險超額無效規定）？', pick: '(C) 人壽保險' },
      { id: 25, part: 'part1', ans: 'B', q: '在人壽保險契約中，有權指定或變更受益人的是誰？', pick: '(B) 要保人' },
      { id: 26, part: 'part1', ans: 'A', q: '保險契約訂立後，要保人在收到保單翌日起算幾日內，得以書面檢同保險單向保險人撤銷契約？', pick: '(A) 10 日' },
      { id: 27, part: 'part1', ans: 'D', q: '投資型保險商品的投資風險由誰承擔？', pick: '(D) 要保人（保戶）' },
      { id: 28, part: 'part1', ans: 'C', q: '下列何者屬於「系統性風險」（市場風險），無法透過分散投資完全消除？', pick: '(C) 中央銀行大幅升息' },
      { id: 29, part: 'part1', ans: 'B', q: '衡量投資組合「每承擔一單位總風險所能獲得的超額報酬」之指標為何？', pick: '(B) 夏普比率（Sharpe Ratio）' },
      { id: 30, part: 'part1', ans: 'A', q: '當新台幣對美元匯率由 32 元升值為 30 元時，對台灣哪一類廠商較為有利？', pick: '(A) 進口商' },
      { id: 31, part: 'part1', ans: 'C', q: '銀行辦理防制洗錢作業時，對客戶進行身分確認的程序簡稱為什麼？', pick: '(C) KYC（認識客戶）' },
      { id: 32, part: 'part1', ans: 'B', q: '金融機構對疑似洗錢交易之申報，應向法務部哪一個機關辦理？', pick: '(B) 調查局（洗錢防制處）' },
      { id: 33, part: 'part1', ans: 'D', q: '關於「人頭帳戶」的敘述，下列何者正確？', pick: '(D) 無正當理由交付帳戶給他人使用，可能觸犯洗錢防制法' },
      { id: 34, part: 'part1', ans: 'A', q: '近年常見的「假投資詐騙」手法，通常具有下列何種特徵？', pick: '(A) 標榜穩賺不賠、高報酬零風險並要求加入群組' },
      { id: 35, part: 'part1', ans: 'C', q: '永續金融中的「ESG」三個英文字母分別代表什麼？', pick: '(C) 環境保護、社會責任、公司治理' },
      { id: 36, part: 'part1', ans: 'B', q: '企業或金融機構刻意誇大其產品或營運在環保永續上的表現以誤導消費者，稱為什麼行為？', pick: '(B) 漂綠（Greenwashing）' },
      { id: 37, part: 'part1', ans: 'A', q: '金融機構為落實「普惠金融」，提供無障礙環境與友善服務，主要保障哪一族群的金融權益？', pick: '(A) 高齡者及身心障礙者' },
      { id: 38, part: 'part1', ans: 'D', q: '關於「純網路銀行」的敘述，下列何者正確？', pick: '(D) 除總行及客服中心外，不設立實體分行' },
      { id: 39, part: 'part1', ans: 'C', q: '中央存款保險公司目前對每一存款人在同一家要保機構的最高保額為新台幣多少元？', pick: '(C) 300 萬元' },
      { id: 40, part: 'part1', ans: 'B', q: '金融消費者與金融服務業發生民事爭議時，可向哪一個機構申請評議？', pick: '(B) 金融消費評議中心' },
      { id: 41, part: 'part1', ans: 'A', q: '信用卡循環信用利息的計算，若持卡人未在當期繳款截止日前繳清全額，通常從何時起算利息？', pick: '(A) 各筆消費入帳日' },
      { id: 42, part: 'part1', ans: 'D', q: '個人在銀行的信用紀錄是由哪一個機構負責蒐集、處理並提供查詢？', pick: '(D) 財團法人金融聯合徵信中心（聯徵中心）' },
      { id: 43, part: 'part1', ans: 'C', q: '股票除息交易日當天，其開盤參考價的計算方式為何？', pick: '(C) 前一日收盤價減現金股利' },
      { id: 44, part: 'part1', ans: 'B', q: '買賣台灣上市櫃股票時，證券交易稅的稅率一般為多少？（當沖交易除外）', pick: '(B) 千分之三' },
      { id: 45, part: 'part1', ans: 'A', q: '共同基金採取「定期定額」投資策略的主要優點為何？', pick: '(A) 平均投資成本，降低進場時點風險' },
      { id: 46, part: 'part1', ans: 'D', q: '下列何者「不是」衍生性金融商品？', pick: '(D) 普通股股票' },
      { id: 47, part: 'part1', ans: 'C', q: '銀行辦理房屋貸款時，若借款人提供不動產設定抵押，該筆放款屬於？', pick: '(C) 擔保放款' },
      { id: 48, part: 'part1', ans: 'B', q: '關於「開放銀行（Open Banking）」的概念，下列何者正確？', pick: '(B) 經消費者同意後，銀行透過 API 將資料安全分享給第三方服務業者' },
      { id: 49, part: 'part1', ans: 'A', q: '企業發行「綠色債券」所募集的資金，必須全部用於哪一類計畫？', pick: '(A) 氣候、環保或綠色投資計畫' },
      { id: 50, part: 'part1', ans: 'C', q: '投資人在評估股票是否便宜時，常用「股價除以每股盈餘（EPS）」，此指標稱為？', pick: '(C) 本益比（P/E）' },

      // 二、職業道德（第 51～100 題）
      { id: 51, part: 'part2', ans: 'C', q: '金融從業人員在執行業務時，當自身利益與客戶利益發生衝突時，應如何處理？', pick: '(C) 應以客戶利益為優先考量' },
      { id: 52, part: 'part2', ans: 'B', q: '關於金融從業人員的「保密義務」，下列敘述何者正確？', pick: '(B) 除依法令或主管機關查詢外，離職後仍須嚴守客戶秘密' },
      { id: 53, part: 'part2', ans: 'D', q: '下列哪一種行為「違反」金融從業人員職業道德？', pick: '(D) 向客戶承諾商品「保證獲利、絕不虧損」' },
      { id: 54, part: 'part2', ans: 'A', q: '證券營業員接受客戶委託買賣股票時，下列何種行為是合法的？', pick: '(A) 依客戶明確指示下單並留存紀錄' },
      { id: 55, part: 'part2', ans: 'C', q: '金融從業人員知悉公司尚未公開的重大利多消息時，下列行為何者正確？', pick: '(C) 嚴守保密義務，不得買賣亦不得洩漏（防範內線交易）' },
      { id: 56, part: 'part2', ans: 'B', q: '銷售金融商品前，從業人員必須評估客戶的風險承受度與商品適合度，這落實了哪兩項原則？', pick: '(B) 認識客戶（KYC）與認識商品（KYP）' },
      { id: 57, part: 'part2', ans: 'D', q: '金融機構在設計廣告與行銷文宣時，下列何者符合職業道德規範？', pick: '(D) 內容真實、平衡揭露報酬與風險，不誇大不實' },
      { id: 58, part: 'part2', ans: 'A', q: '金融從業人員面對同業競爭時，應抱持何種態度？', pick: '(A) 憑藉專業與服務品質公平競爭，不惡意中傷同業' },
      { id: 59, part: 'part2', ans: 'C', q: '關於「受託人義務（Fiduciary Duty）」，下列敘述何者最正確？', pick: '(C) 應以善良管理人之注意義務及忠實義務為客戶謀取最大利益' },
      { id: 60, part: 'part2', ans: 'B', q: '客戶要求從業人員代為保管印鑑、存摺或空白取款條以便日後交易，從業人員應如何處理？', pick: '(B) 嚴正拒絕，絕不代客戶保管印鑑與存摺' },
      { id: 61, part: 'part2', ans: 'A', q: '金融從業人員向高齡客戶（通常指 65 歲以上）推介高風險金融商品時，下列何者為必要規範？', pick: '(A) 落實關懷提問、評估適合度並依規定錄音或錄影保存紀錄' },
      { id: 62, part: 'part2', ans: 'D', q: '下列何者屬於「不當勸誘」行為？', pick: '(D) 勸誘客戶以保單借款或房屋增貸方式購買高風險投資型保單' },
      { id: 63, part: 'part2', ans: 'C', q: '金融從業人員在招攬業務時，是否可以贈送高額禮品或私下退還佣金給客戶？', pick: '(C) 不得以不當利益、贈品或退佣方式招攬業務' },
      { id: 64, part: 'part2', ans: 'B', q: '當發現同事有挪用客戶款項或偽造文書之行為時，從業人員應如何處理？', pick: '(B) 立即依公司內部檢舉機制向主管或稽核單位通報' },
      { id: 65, part: 'part2', ans: 'A', q: '金融機構建立「吹哨者保護制度（Whistleblower）」的主要目的為何？', pick: '(A) 鼓勵員工勇於揭發不法行為，並保護檢舉人免受報復' },
      { id: 66, part: 'part2', ans: 'D', q: '關於業務員簽署文件的規範，下列何者正確？', pick: '(D) 必須由客戶本人親自簽名，嚴禁代簽或偽造簽名' },
      { id: 67, part: 'part2', ans: 'C', q: '客戶臨櫃辦理大額現金匯款且神色慌張、邊講電話邊操作時，行員應採取何種行動？', pick: '(C) 主動進行關懷提問，防範客戶遭受詐騙並視情況通報警方' },
      { id: 68, part: 'part2', ans: 'B', q: '金融從業人員在社群媒體（如 FB、LINE）發表金融市場評論時，應注意什麼？', pick: '(B) 應遵守公司規範與法令，不得散播不實訊息或未經核准之廣告' },
      { id: 69, part: 'part2', ans: 'A', q: '理財專員與客戶之間發生私人金錢借貸往來，下列敘述何者正確？', pick: '(A) 嚴重違反職業道德與內控規範，絕對禁止' },
      { id: 70, part: 'part2', ans: 'C', q: '保險業務員在招攬保險時，應主動出示何種證件以表明身分？', pick: '(C) 保險業務員登錄證' },
      { id: 71, part: 'part2', ans: 'D', q: '金融從業人員在辦理開戶作業時，發現客戶提供之身分證件疑似偽造，應如何處理？', pick: '(D) 婉拒開戶並依規定通報權責單位' },
      { id: 72, part: 'part2', ans: 'B', q: '關於「誠信原則」在金融業的實踐，下列何者「不正確」？', pick: '(B) 為達成業績目標，隱瞞提前解約的高額違約金' },
      { id: 73, part: 'part2', ans: 'A', q: '投信基金經理人管理基金資產時，下列何種行為是禁止的？', pick: '(A) 利用職務之便為自己或特定人進行利益輸送（如老鼠倉）' },
      { id: 74, part: 'part2', ans: 'C', q: '金融從業人員收到客戶贈送的高價貴重禮品時，最妥當的做法為何？', pick: '(C) 依公司收受饋贈規範婉拒，或陳報單位主管依規定處理' },
      { id: 75, part: 'part2', ans: 'B', q: '當客戶因市場波動導致投資虧損而情緒激動時，從業人員應如何應對？', pick: '(B) 保持冷靜同理心傾聽，客觀說明市場狀況並協助檢視資產配置' },
      { id: 76, part: 'part2', ans: 'D', q: '關於「公平待客原則（Treating Customers Fairly）」，下列何者不在其核心精神內？', pick: '(D) 業績成長最大化原則' },
      { id: 77, part: 'part2', ans: 'A', q: '金融機構內部控制制度中，「牽制原則（職務區隔）」的主要目的為何？', pick: '(A) 避免單一人員從頭到尾經手同一筆交易，以防範舞弊與錯誤' },
      { id: 78, part: 'part2', ans: 'C', q: '從業人員在協助客戶填寫「風險屬性評估問卷（KYC）」時，應遵守何種規範？', pick: '(C) 由客戶親自依真實狀況填寫，不得誘導或代填' },
      { id: 79, part: 'part2', ans: 'B', q: '銀行行員查詢客戶帳戶資料時，必須符合下列哪一項要件？', pick: '(B) 必須基於執行職務之正當業務需求，嚴禁無故查詢' },
      { id: 80, part: 'part2', ans: 'A', q: '金融從業人員未取得相關法定資格或登錄前，是否可以從事招攬或推介業務？', pick: '(A) 絕對不可以，須完成測驗合格並辦理登錄後方可執業' },
      { id: 81, part: 'part2', ans: 'D', q: '關於「洗錢防制」的客戶盡職調查（CDD），何時必須執行？', pick: '(D) 建立業務關係時、進行大額或疑似洗錢交易時均須執行' },
      { id: 82, part: 'part2', ans: 'C', q: '證券分析師在媒體上公開推薦特定股票時，下列何者違反職業道德？', pick: '(C) 自己先買進該股票，在節目上大力吹捧後趁高檔倒貨給觀眾' },
      { id: 83, part: 'part2', ans: 'B', q: '保險業務員在說明保單紅利時，下列何種說法才符合規範？', pick: '(B) 分紅保單之紅利屬於非保證給付項目，視保險公司經營績效而定' },
      { id: 84, part: 'part2', ans: 'A', q: '金融從業人員若因個人財務困難積欠巨額債務，對其職務有何影響？', pick: '(A) 可能引發挪用公款或舞弊之道德風險，應誠實面對並尋求合法債務協商' },
      { id: 85, part: 'part2', ans: 'C', q: '客戶申請提前解約金融商品時，從業人員應採取何種態度？', pick: '(C) 尊重客戶決定，客觀說明解約條件與可能損失後依規辦理' },
      { id: 86, part: 'part2', ans: 'B', q: '關於「個人資料保護法」，金融機構蒐集客戶個人資料時，應遵循何種原則？', pick: '(B) 應告知蒐集目的與利用範圍，並經當事人同意，不得逾越必要範圍' },
      { id: 87, part: 'part2', ans: 'D', q: '下列何種情況最可能構成「利益衝突」？', pick: '(D) 授信經辦人員審核自己配偶所經營公司的貸款申請案' },
      { id: 88, part: 'part2', ans: 'A', q: '金融從業人員在撰寫研究報告或投資建議時，應具備何種專業態度？', pick: '(A) 客觀獨立、具備合理分析基礎，並區分事實與個人意見' },
      { id: 89, part: 'part2', ans: 'C', q: '當客戶詢問對某檔未上市股票的看法時，合法的金融從業人員應如何回應？', pick: '(C) 提醒未上市股票資訊較不透明、流動性低且風險高，不私下仲介違法交易' },
      { id: 90, part: 'part2', ans: 'B', q: '金融機構對於「高資產客戶」提供服務時，職業道德標準是否可以放寬？', pick: '(B) 不可以，所有客戶均適用同樣嚴格的法規與職業道德標準' },
      { id: 91, part: 'part2', ans: 'A', q: '關於「在職訓練」與「專業進修」，金融從業人員應抱持何種認知？', pick: '(A) 金融法規與商品日新月異，持續進修是維持專業與保護客戶的必要責任' },
      { id: 92, part: 'part2', ans: 'D', q: '業務員向客戶銷售外幣計價保單時，必須特別向客戶強調哪一項風險？', pick: '(D) 匯率波動風險' },
      { id: 93, part: 'part2', ans: 'C', q: '金融從業人員使用公司電腦與網路系統時，下列何種行為「違反」資訊安全與職業道德？', pick: '(C) 將自己的帳號密碼借給同事代為操作交易系統' },
      { id: 94, part: 'part2', ans: 'B', q: '若客戶提出的要求明顯違反金融法規，從業人員應如何處理？', pick: '(B) 堅守法規底線，婉轉但堅定地拒絕並向客戶說明法令規定' },
      { id: 95, part: 'part2', ans: 'A', q: '金融消費爭議發生時，從業人員應抱持何種處理態度？', pick: '(A) 積極面對、保存完整交易紀錄，並協助客戶依合法申訴管道妥善處理' },
      { id: 96, part: 'part2', ans: 'C', q: '關於「電子商務與數位金融服務」，從業人員在協助客戶使用 APP 時應注意什麼？', pick: '(C) 指導客戶自行設定密碼並提醒妥善保管，絕不窺探或留存密碼' },
      { id: 97, part: 'part2', ans: 'B', q: '保險業務員得知客戶罹患重病卻在要保書上勾選「健康狀況良好」時，應如何處理？', pick: '(B) 善盡告知義務說明，並提醒客戶務必據實告知以免日後遭解除契約及拒賠' },
      { id: 98, part: 'part2', ans: 'D', q: '金融從業人員對公司內部尚未公開的財務數據或客戶資料，應負有何種責任？', pick: '(D) 負有嚴格保密責任，未經授權不得洩漏或攜出' },
      { id: 99, part: 'part2', ans: 'A', q: '衡量一位金融從業人員是否具備良好職業道德的最高標準為何？', pick: '(A) 在無人監督的情況下，依然能自律守法並以客戶利益為依歸' },
      { id: 100, part: 'part2', ans: 'C', q: '金融市場穩定運作的基石為何？', pick: '(C) 市場參與者共同秉持的「誠信」與「信任」' }
    ];

    let currentFilter = 'all';

    const quizContainer = document.getElementById('quizContainer');
    const tabGroup = document.getElementById('tabGroup');
    const sizeGroup = document.getElementById('sizeGroup');
    const backTopBtn = document.getElementById('backTopBtn');

    function createCard(item) {
      const card = document.createElement('article');
      card.className = 'q-card';
      card.innerHTML = `
        <div class="q-answer-row">
          <span class="ans-pill">答案：${item.ans}</span>
          <span class="q-num-tag">第 ${item.id} 題</span>
        </div>
        <p class="q-title">${item.id}. ${item.q}</p>
        <div class="must-pick">
          <span class="must-pick-label">必須點選答案：</span>
          <span class="must-pick-text">${item.pick}</span>
        </div>
      `;
      return card;
    }

    function render() {
      const filtered = QUESTIONS.filter((item) => {
        return currentFilter === 'all' || item.part === currentFilter;
      });

      quizContainer.innerHTML = '';

      const part2Items = filtered.filter((x) => x.part === 'part2');
      const part1Items = filtered.filter((x) => x.part === 'part1');

      if (part1Items.length > 0) {
        const h1 = document.createElement('div');
        h1.className = 'section-divider';
        h1.textContent = '一、金融市場常識（第 1～50 題）';
        quizContainer.appendChild(h1);

        const list1 = document.createElement('div');
        list1.className = 'q-list';
        part1Items.forEach((item) => list1.appendChild(createCard(item)));
        quizContainer.appendChild(list1);
      }

      if (part2Items.length > 0) {
        const h2 = document.createElement('div');
        h2.className = 'section-divider';
        h2.textContent = '二、職業道德（第 51～100 題）';
        quizContainer.appendChild(h2);

        const list2 = document.createElement('div');
        list2.className = 'q-list';
        part2Items.forEach((item) => list2.appendChild(createCard(item)));
        quizContainer.appendChild(list2);
      }
    }

    tabGroup.addEventListener('click', (e) => {
      const btn = e.target.closest('button[data-filter]');
      if (!btn) return;
      currentFilter = btn.dataset.filter;
      tabGroup.querySelectorAll('button[data-filter]').forEach((b) => {
        b.classList.toggle('active', b === btn);
      });
      render();
    });

    sizeGroup.addEventListener('click', (e) => {
      const btn = e.target.closest('button[data-size]');
      if (!btn) return;
      document.body.classList.remove('font-md', 'font-lg', 'font-xl');
      document.body.classList.add(btn.dataset.size);
      sizeGroup.querySelectorAll('button[data-size]').forEach((b) => {
        b.classList.toggle('active', b === btn);
      });
    });

    backTopBtn.addEventListener('click', () => {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    });

    render();
  </script>
</body>
</html>