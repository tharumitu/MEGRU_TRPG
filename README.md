<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>巡る刻の旅人</title>
    <style>
        body {
            font-family: sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000;
            color: #fff;
        }
        .container {
            display: flex;
        }
        .sidebar {
            width: 250px;
            background-color: #ccc;
            padding: 15px;
            min-height: 100vh;
            color: #000;
            position: fixed;
            left: 0;
            top: 0;
            bottom: 0;
            transform: translateX(-100%);
            transition: transform 0.3s ease-in-out;
        }
        .sidebar.open {
            transform: translateX(0);
        }
        .toggle-button {
            position: fixed;
            left: 10px;
            top: 10px;
            background: #ccc;
            color: #000;
            border: none;
            padding: 10px;
            cursor: pointer;
        }
        .content {
            flex-grow: 1;
            background-color: #fff;
            padding: 20px;
            color: #000;
            margin-left: 260px;
        }
        h2 {
            border-bottom: 1px solid #999;
            padding-bottom: 10px;
            width: 60%;
            margin: auto;
        }
        footer {
            background-color: #ccc;
            color: #000;
            padding: 10px;
            text-align: center;
            position: relative;
            width: 100%;
        }
    </style>
    <script>
        function toggleSidebar() {
            document.querySelector('.sidebar').classList.toggle('open');
        }
    </script>
</head>
<body>
    <button class="toggle-button" onclick="toggleSidebar()">☰</button>
    <div class="container">
        <aside class="sidebar">
            <h2>目次</h2>
            <ul>
                <li><a href="#about">概要</a></li>
                <li><a href="#system">基本システム</a></li>
                <li><a href="#character">プレイヤーキャラクター</a></li>
                <li><a href="#gameplay">ゲームの進行</a></li>
                <li><a href="#scenario">サンプルシナリオ</a></li>
            </ul>
        </aside>
        <main class="content">
            <section id="about">
                <h2>TRPG『巡る刻の旅人（めぐるときのたびびと）』</h2>
                <p>
                    プレイヤーは「時巡りの旅人」となり、まだ見ぬ世界へ足を踏み出します。
                    歩みを進めるたびに大地が形作られ、川が流れ、山がそびえ、文明が生まれていく。
                    この旅がどこへ向かうのか、それは旅人たちの選択次第。
                </p>
            </section>
            <section id="system">
                <h2>基本システム（D6ベース）</h2>
                <ul>
                    <li><strong>判定方法：</strong>D6を振り、結果に応じて行動の成否や世界の変化が決まる。</li>
                    <li><strong>探索と発展：</strong>旅を進めるたびに新たな土地や出来事が発生し、マップが広がる。</li>
                    <li><strong>「刻（とき）の軌跡」システム：</strong>プレイヤーの選択により、地形・歴史・文明が変化。</li>
                    <li><strong>時間の流れ：</strong>ゲームが進むと、世界に「時の変遷」が訪れ、旅の終わりが近づく。</li>
                </ul>
            </section>
            <section id="character">
                <h2>プレイヤーキャラクター（PC）</h2>
                <h3>時巡りの旅人（Time Wanderer）</h3>
                <p>
                    あなたは旅人となって新世界を旅する。世界の狭間から生まれた存在。
                </p>
                <h4>ステータス</h4>
                <ul>
                    <li><strong>STR（身体）：</strong> 体の丈夫さや筋力などを表す。困難は己の拳で砕くのみ。</li>
                    <li><strong>INT（知恵）：</strong> 知能の良さを表す。知識があればさまざまなものを理解できるだろう。</li>
                    <li><strong>PER（感性）：</strong> 感性が優れていれば、生まれる世界も完成に長けたものになるだろう。</li>
                    <li><strong>FAT（運命）：</strong> 運命が優れていれば、あなたの旅はきっと素晴らしいものになる。</li>
                </ul>
            </section>
            <section id="gameplay">
                <h2>ゲームの進行</h2>
                <p>旅のフェーズごとに世界が変わっていく。</p>
                <ul>
                    <li>「新たな世界が拓く」フェーズ：世界が形作られる。</li>
                    <li>「旅の軌跡」フェーズ：D6の結果によって土地や文明が広がる。</li>
                    <li>「時の変遷」フェーズ：過去の選択が影響を及ぼし、状況が変化。</li>
                    <li>「旅の終わり」フェーズ：旅の果てに何を残すのかが決まる。</li>
                </ul>
            </section>
            <section id="scenario">
                <h2>サンプルシナリオ「黎明の川」</h2>
                <p>
                    旅人たちは、広大な平原を進む中で、突如として大河が生まれる瞬間を目撃する。
                    しかし、その源流には「時の淀み」と呼ばれる不思議な領域が広がっていた。
                </p>
                <p>旅人たちは、この地をどう導くのか？そして、旅の終わりには何を残すのか？</p>
                <p>
                    このTRPGでは、プレイヤーの選択が直接世界の姿を変えていきます。
                    その場限りの偶然ではなく、あなたの足跡が未来を築いていくのです。
                </p>
                <p>さあ、時を巡る旅へ出かけましょう。</p>
            </section>
        </main>
    </div>
    <footer>
        <p>&copy; 2023 巡る刻の旅人</p>
    </footer>
</body>
</html>
