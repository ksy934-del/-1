<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>文化祭特設サイト</title>
    <style>
        :root {
            --primary-color: #ff6b6b;
            --secondary-color: #4ecdc4;
            --bg-color: #f7f9fc;
            --text-color: #2d3748;
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            text-align: center;
            padding: 40px 20px;
        }
        header h1 {
            margin: 0;
            font-size: 26px;
        }
        header p {
            margin: 10px 0 0;
            font-size: 14px;
            opacity: 0.9;
        }
        .container {
            max-width: 600px;
            margin: 20px auto;
            padding: 0 15px;
        }
        .card {
            background: white;
            border-radius: 12px;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        }
        .card h2 {
            font-size: 18px;
            color: var(--primary-color);
            border-bottom: 2px solid #edf2f7;
            padding-bottom: 8px;
            margin-top: 0;
        }
        ul {
            padding-left: 20px;
            margin: 10px 0;
        }
        li {
            margin-bottom: 8px;
        }
        .btn {
            display: block;
            background: var(--primary-color);
            color: white;
            text-align: center;
            padding: 14px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 15px;
            box-shadow: 0 4px 10px rgba(255, 107, 107, 0.3);
        }
        .btn:active {
            transform: scale(0.98);
        }
        footer {
            text-align: center;
            padding: 20px;
            font-size: 12px;
            color: #a0aec0;
        }
    </style>
</head>
<body>

    <header>
        <h1>🎉 〇〇高校 文化祭特設サイト 🎉</h1>
        <p>青春の思い出をこの場所に！最新情報をお届けします</p>
    </header>

    <div class="container">
        
        <!-- タイムスケジュール -->
        <div class="card">
            <h2>⏰ タイムスケジュール</h2>
            <ul>
                <li><strong>9:00〜</strong> オープニングセレモニー（体育館）</li>
                <li><strong>10:00〜</strong> 各クラス・部活の模擬店・展示スタート</li>
                <li><strong>13:30〜</strong> 中夜祭・ステージ発表</li>
                <li><strong>15:00〜</strong> エンディング＆閉会式</li>
            </ul>
        </div>

        <!-- 企画紹介 -->
        <div class="card">
            <h2>🏫 見どころ・おすすめ企画</h2>
            <ul>
                <li><strong>2年3組：</strong> 本格お化け屋敷「恐怖の病棟」</li>
                <li><strong>3年1組：</strong> カフェ＆パンケーキ（中庭）</li>
                <li><strong>写真部：</strong> 校内フォトコンテスト（視聴覚室）</li>
            </ul>
        </div>

        <!-- 掲示板（フォームへのリンク） -->
        <div class="card">
            <h2>💬 文化祭 掲示板・メッセージ</h2>
            <p>みんなからの感想や、先生からの連絡事項はこちらからチェック＆投稿できます！</p>
            <!-- 以下の href=" " の中にGoogleフォームのURLを入れてね -->
            <a href="ここにGoogleフォームのURLを貼る" class="btn">📝 掲示板（フォーム）を開く</a>
        </div>

    </div>

    <footer>
        &copy; 2026 〇〇高校 文化祭実行委員会
    </footer>

</body>
</html>
