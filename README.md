<!doctype html>
<html lang="zh-CN">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Anna Valenti | Personal Profile</title>
  <style>
    :root {
      --ink: #1f2933;
      --muted: #667085;
      --line: #d9e2ec;
      --paper: #fbfcfe;
      --panel: #ffffff;
      --brand: #0f766e;
      --brand-soft: #d9f7f2;
      --accent: #b45309;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      color: var(--ink);
      background: var(--paper);
      font-family: Arial, "Microsoft YaHei", sans-serif;
      line-height: 1.65;
    }

    .hero {
      padding: 56px 24px 40px;
      background:
        linear-gradient(120deg, rgba(15, 118, 110, 0.92), rgba(31, 41, 51, 0.88)),
        url("https://images.unsplash.com/photo-1517649763962-0c623066013b?auto=format&fit=crop&w=1600&q=80");
      background-size: cover;
      background-position: center;
      color: white;
    }

    .wrap {
      width: min(1080px, calc(100% - 32px));
      margin: 0 auto;
    }

    .hero-grid {
      display: grid;
      grid-template-columns: 132px 1fr;
      gap: 28px;
      align-items: center;
    }

    .avatar {
      display: grid;
      place-items: center;
      width: 132px;
      height: 132px;
      border: 2px solid rgba(255, 255, 255, 0.72);
      border-radius: 50%;
      background: rgba(255, 255, 255, 0.16);
      color: white;
      font-size: 42px;
      font-weight: 700;
      letter-spacing: 0;
    }

    h1 {
      margin: 0 0 10px;
      font-size: 44px;
      line-height: 1.1;
      letter-spacing: 0;
    }

    .subtitle {
      max-width: 760px;
      margin: 0;
      color: rgba(255, 255, 255, 0.86);
      font-size: 18px;
    }

    .chips {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 22px;
    }

    .chip {
      padding: 7px 12px;
      border: 1px solid rgba(255, 255, 255, 0.35);
      border-radius: 999px;
      background: rgba(255, 255, 255, 0.14);
      color: white;
      font-size: 14px;
    }

    main {
      padding: 34px 0 56px;
    }

    .grid {
      display: grid;
      grid-template-columns: 320px 1fr;
      gap: 24px;
      align-items: start;
    }

    section,
    aside {
      background: var(--panel);
      border: 1px solid var(--line);
      border-radius: 8px;
      padding: 24px;
    }

    section + section {
      margin-top: 24px;
    }

    h2 {
      margin: 0 0 18px;
      font-size: 22px;
      letter-spacing: 0;
    }

    .facts {
      display: grid;
      gap: 14px;
    }

    .fact {
      padding-bottom: 14px;
      border-bottom: 1px solid var(--line);
    }

    .fact:last-child {
      padding-bottom: 0;
      border-bottom: 0;
    }

    .label {
      display: block;
      color: var(--muted);
      font-size: 13px;
    }

    .value {
      display: block;
      margin-top: 3px;
      font-weight: 700;
    }

    .tag-list {
      display: flex;
      flex-wrap: wrap;
      gap: 9px;
      margin-top: 8px;
    }

    .tag {
      padding: 6px 10px;
      border-radius: 999px;
      background: var(--brand-soft);
      color: #0b5f59;
      font-size: 14px;
      font-weight: 700;
    }

    .timeline {
      display: grid;
      gap: 16px;
    }

    .item {
      position: relative;
      padding: 0 0 18px 24px;
      border-left: 2px solid var(--line);
    }

    .item:last-child {
      padding-bottom: 0;
    }

    .item::before {
      content: "";
      position: absolute;
      left: -7px;
      top: 7px;
      width: 12px;
      height: 12px;
      border-radius: 50%;
      background: var(--brand);
    }

    .item h3 {
      margin: 0 0 4px;
      font-size: 18px;
    }

    .meta {
      margin: 0 0 8px;
      color: var(--accent);
      font-size: 14px;
      font-weight: 700;
    }

    .item p {
      margin: 0;
      color: var(--muted);
    }

    footer {
      padding: 24px;
      border-top: 1px solid var(--line);
      color: var(--muted);
      text-align: center;
      font-size: 14px;
    }

    @media (max-width: 780px) {
      .hero-grid,
      .grid {
        grid-template-columns: 1fr;
      }

      .avatar {
        width: 108px;
        height: 108px;
        font-size: 34px;
      }

      h1 {
        font-size: 34px;
      }
    }
  </style>
</head>
<body>
  <header class="hero">
    <div class="wrap hero-grid">
      <div class="avatar">AV</div>
      <div>
        <h1>Anna Valenti</h1>
        <p class="subtitle">欧洲高端美妆销售管理者，热爱健身、网球、徒步与旅行，也持续关注金融市场、加密资产与短期交易策略。</p>
        <div class="chips">
          <span class="chip">San Francisco</span>
          <span class="chip">Luxury Beauty</span>
          <span class="chip">Sales Strategy</span>
          <span class="chip">Finance</span>
        </div>
      </div>
    </div>
  </header>

  <main class="wrap grid">
    <aside>
      <h2>基本信息</h2>
      <div class="facts">
        <div class="fact">
          <span class="label">出生日期</span>
          <span class="value">1988年5月18日，金牛座</span>
        </div>
        <div class="fact">
          <span class="label">年龄</span>
          <span class="value">37岁，即将38岁</span>
        </div>
        <div class="fact">
          <span class="label">身高 / 体重</span>
          <span class="value">178 cm / 62 kg</span>
        </div>
        <div class="fact">
          <span class="label">家庭住址</span>
          <span class="value">2418 Pacific Ave, San Francisco, CA 94115, USA</span>
        </div>
        <div class="fact">
          <span class="label">爱好</span>
          <div class="tag-list">
            <span class="tag">健身</span>
            <span class="tag">网球</span>
            <span class="tag">徒步</span>
            <span class="tag">旅行</span>
          </div>
        </div>
      </div>
    </aside>

    <div>
      <section>
        <h2>学业经历</h2>
        <div class="timeline">
          <article class="item">
            <h3>San Francisco Girls' School</h3>
            <p class="meta">1994 - 1999 | 6岁入学，11岁毕业 | 学制5年</p>
            <p>在旧金山女子学校完成小学阶段教育，建立了稳定的语言、表达与基础学习能力。</p>
          </article>
          <article class="item">
            <h3>Convent of the Sacred Heart</h3>
            <p class="meta">1999 - 2002 | 11岁入学，14岁毕业 | 学制3年</p>
            <p>在圣心修道院女校完成初中阶段学习，开始形成自律、礼仪与国际化视野。</p>
          </article>
          <article class="item">
            <h3>Convent of the Sacred Heart High School</h3>
            <p class="meta">2002 - 2006 | 14岁入学，18岁毕业 | 学制4年</p>
            <p>高中阶段继续接受女子精英教育，为后续商科与经济学学习奠定基础。</p>
          </article>
          <article class="item">
            <h3>University of Pennsylvania</h3>
            <p class="meta">2007 - 2010 | BSc in International Economics and Management</p>
            <p>主修国际经济与管理，关注全球市场、企业管理与跨区域商业运营。</p>
          </article>
          <article class="item">
            <h3>The Wharton School of the University of Pennsylvania</h3>
            <p class="meta">2010 - 2012 | MSc in Finance</p>
            <p>在沃顿商学院完成金融学硕士学习，进一步强化财务分析、资本市场与投资判断能力。</p>
          </article>
        </div>
      </section>

      <section>
        <h2>职业经历</h2>
        <div class="timeline">
          <article class="item">
            <h3>Estée Lauder | 区域销售分析师</h3>
            <p class="meta">2012 - 2016</p>
            <p>毕业后进入雅诗兰黛，负责通过远程数据系统监控欧洲主要机场免税店销售表现，分析热门口红色号的销售原因，并制定补货计划。由于工作高度系统化，Anna 希望获得更自由的职业空间，于2016年离职。</p>
          </article>
          <article class="item">
            <h3>加密资产投资起点</h3>
            <p class="meta">2016</p>
            <p>受到智能合约概念与市场讨论影响，Anna 将约2万欧元季度销售奖金配置到 BTC 与 ETH，当时 BTC 约610美元，ETH 约13美元。</p>
          </article>
          <article class="item">
            <h3>Chanel | 全渠道销售负责人</h3>
            <p class="meta">2017 - 2023</p>
            <p>加入香奈儿后，Anna 负责打造线上、电话咨询与精品店之间一致且无缝衔接的高级客户体验，覆盖移动网页、远程服务与线下门店。</p>
          </article>
          <article class="item">
            <h3>市场压力与短期交易转向</h3>
            <p class="meta">2020</p>
            <p>疫情期间，全球销售分红与高管奖金临时取消，加密市场大幅波动叠加房地产贷款压力，导致现金流紧张。通过姑姑的帮助，Anna 接触短期交易，并逐步认识到短期交易在资金积累中的灵活性。</p>
          </article>
          <article class="item">
            <h3>Chanel | 地区销售总监</h3>
            <p class="meta">2023 - 至今</p>
            <p>疫情结束后，Anna 凭借持续努力晋升为地区销售总监，负责欧洲大部分地区销售业务，并带领自己的团队推进高端美妆市场增长。</p>
          </article>
        </div>
      </section>
    </div>
  </main>

  <footer>
    Personal profile website for Anna Valenti
  </footer>
</body>
</html>
