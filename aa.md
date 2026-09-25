<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bloxd.io Chat Translator</title>
    <style>
        body {
            font-family: "Minecraft", "Arial Black", sans-serif;
            background: linear-gradient(135deg, #4CAF50 0%, #2E7D32 100%);
            margin: 0;
            padding: 0;
            width: 320px;
            color: #fff;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.6);
            overflow: hidden;
        }
        .container {
            padding: 15px;
        }
        .logo {
            text-align: center;
            font-size: 26px;
            font-weight: bold;
            margin: 10px 0 15px;
            background: #111;
            padding: 8px 0;
            border: 4px solid #8B4513;
            box-shadow: 0 0 15px #000 inset;
            text-transform: uppercase;
            letter-spacing: 3px;
        }
        .buttons {
            display: flex;
            flex-direction: column;
            gap: 8px;
        }
        button {
            background: #555;
            color: #fff;
            border: 3px solid #8B4513;
            padding: 14px 10px;
            font-size: 18px;
            text-align: center;
            cursor: pointer;
            transition: all 0.15s;
            box-shadow: 3px 3px 0 #000;
            text-transform: uppercase;
        }
        button:hover {
            background: #777;
            transform: translateY(-3px);
            box-shadow: 3px 5px 0 #000;
        }
        .bottom-bar {
            display: flex;
            gap: 8px;
            margin-top: 12px;
        }
        .bottom-bar button {
            flex: 1;
            font-size: 14px;
        }
        .footer {
            text-align: center;
            font-size: 9px;
            padding: 10px 0;
            opacity: 0.85;
            border-top: 1px solid #8B4513;
            margin-top: 15px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="logo">
            BLOXD.IO<br>
            <span style="font-size:18px; opacity:0.9; letter-spacing:2px;">CHAT TRANSLATOR</span>
        </div>
        
        <div class="buttons">
            <button onclick="alert('シングルプレイ機能は現在開発中です！')">シングルプレイ</button>
            <button onclick="alert('マルチプレイ機能は現在開発中です！')">マルチプレイ</button>
            <button onclick="alert('クレジット機能は現在開発中です！')">クレジット</button>
            
            <div class="bottom-bar">
                <button onclick="alert('設定ページを開きます')">設定...</button>
                <button onclick="alert('プロフィール編集')">Edit Profile</button>
            </div>
        </div>
        
        <div class="footer">
            Bloxd.io Chat Translator v1.0<br>
            Minecraft Java Edition風デザイン
        </div>
    </div>
</body>
</html>
