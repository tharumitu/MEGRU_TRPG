<!DOCTYPE html>
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
            display: flex;
        }

        nav {
            width: 200px; /* サイドバーの幅 */
            position: fixed;
            top: 0;
            left: 0;
            bottom: 0;
            background-color: rgba(255, 255, 255, 0.8);
            padding: 10%;
            color: #000;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        nav li {
            margin-bottom: 10px;
        }

        nav a {
            color: #000;
            text-decoration: none;
            font-size: 1.2rem;
        }

        main {
            margin-left: 220px; /* サイドバーの横幅分のマージン */
            padding: 20px;
            flex-grow: 1;
        }

        section {
            margin-bottom: 20px;
            background-color: rgba(255, 255, 255, 0.8);
            padding: 20px;
            color: #000;
            max-width: 1200px;
            margin-left: auto;
            margin-right: auto;
        }

        h2 {
            border-bottom: 1px solid #ccc;
            padding-bottom: 10px;
        }

        footer {
            background-color: rgba(255, 255, 255, 0.8);
            color: #000;
            padding: 10px;
            text-align: center;
            position: relative;
            width: 100%;
        }
    </style>
</head>
<body>
    <nav>
        <h2>目次</h2>
        <ul>
            <li><a href="#about">ゲーム概要</a></li>
            <li><a href="#rules">ルール</a></li>
            <li><a href="#character">キャラクター</a></li>
            <li><a href="#scenarios">シナリオ</a></li>
            <li><a href="#blog">ブログ・ニュース</a></li>
            <li><a href="#community">コミュニティ</a></li>
        </ul>
    </nav>

    <main>
        <section id="character">
            <h2>キャラクター</h2>
            <div>
                <h3>キャラクター作成</h3>
                <p><strong>時巡りの旅人（Time Wanderer）</strong><br>
                あなたは旅人となって新世界を旅する。世界の狭間から生まれた存在。</p>
                <p><strong>ステータス</strong></p>
                <ul>
                    <li><strong>STR</strong>（身体）：体の丈夫さや筋力などを表す。困難は己の拳で砕くのみ。</li>
                    <li><strong>INT</strong>（知恵）：知能の良さを表す。知識があればさまざまなものを理解できるだろう。</li>
                    <li><strong>PER</strong>（感性）：感性が優れていれば、生まれる世界も完成に長けたものになるだろう。</li>
                    <li><strong>FAT</strong>（運命）：運命が優れていれば、あなたの旅はきっと素晴らしいものになる。</li>
                </ul>
                <p><strong>旅人の作成方法</strong></p>
                <p>まず運命の値を決める。1d4ダイスを振り、その値をあなたの運命値とする。<br>
                その他のステータスは運命値の分だけ6面ダイスを振る。運命値が1なら1d6、2なら2d6を振る。</p>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 巡る刻の旅人</p>
    </footer>
</body>
</html>
