<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>橋見幸福 - 自行Check-in方式</title>
    <style>
        :root {
            --primary-color: #4a7c59; 
            --accent-color: #d9534f;
            --notice-bg: #fff9f2;
            --bg-color: #f4f7f4;
        }

        body {
            font-family: "Microsoft JhengHei", sans-serif;
            background-color: var(--bg-color);
            margin: 0;
            padding: 0;
            -webkit-font-smoothing: antialiased;
        }

        .container {
            max-width: 500px; /* 針對手機窄螢幕優化 */
            margin: 0 auto;
            background: #ffffff;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            box-shadow: 0 0 10px rgba(0,0,0,0.05);
        }

        .image-container {
            width: 100%;
            background-color: #f0f0f0;
        }

        .image-container img {
            width: 100%;
            height: auto;
            display: block;
        }

        .content {
            padding: 25px 20px 120px 20px; /* 底部留白給按鈕 */
        }

        h1 {
            color: var(--primary-color);
            font-size: 22px;
            text-align: center;
            margin: 0;
        }

        .subtitle {
            text-align: center;
            color: #888;
            font-size: 14px;
            margin-bottom: 25px;
        }

        .welcome-msg {
            text-align: center;
            background-color: #f9f9f9;
            padding: 12px;
            border-radius: 8px;
            font-size: 15px;
            font-weight: bold;
            margin-bottom: 20px;
            border: 1px solid #eee;
        }

        .step-card {
            margin-bottom: 15px;
            padding: 15px;
            border-radius: 10px;
            background: #fff;
            border: 1px solid #efefef;
            box-shadow: 0 2px 5px rgba(0,0,0,0.02);
        }

        .step-title {
            font-weight: bold;
            font-size: 17px;
            color: var(--primary-color);
            margin-bottom: 8px;
            display: flex;
            align-items: center;
        }

        .step-number {
            background: var(--primary-color);
            color: white;
            border-radius: 5px;
            width: 24px;
            height: 24px;
            display: inline-flex;
            justify-content: center;
            align-items: center;
            margin-right: 10px;
            font-size: 13px;
        }

        .notice-section {
            background-color: var(--notice-bg);
            border-radius: 10px;
            padding: 15px;
            margin-top: 25px;
            border: 1px solid #ffe8cc;
        }

        .notice-title {
            font-weight: bold;
            color: #e67e22;
            text-align: center;
            margin-bottom: 12px;
        }

        .important { color: var(--accent-color); font-weight: bold; }

        /* 浮動聯繫按鈕 - 適合手機大拇指點擊 */
        .contact-buttons {
            position: fixed;
            bottom: 25px;
            right: 20px;
            display: flex;
            flex-direction: column;
            gap: 12px;
        }

        .btn-float {
            width: 55px;
            height: 55px;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-decoration: none;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
            font-size: 11px;
            font-weight: bold;
            text-align: center;
        }

        .btn-line { background-color: #06C755; }
        .btn-phone { background-color: var(--primary-color); }

        footer {
            background: #f8f8f8;
            padding: 20px;
            text-align: center;
            font-size: 12px;
            color: #999;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="image-container">
        <img src="https://i.ibb.co/DfL89Vf9/Gemini-Generated-Image-owv4sdowv4sdowv4.png" alt="橋見幸福">
    </div>

    <div class="content">
        <h1>🔑 橋見幸福民宿 | 自行入住指南</h1>
        <div class="subtitle">Self Check-in Guide</div>
        
        <div class="welcome-msg">歡迎抵達！請參考以下步驟：</div>

        <div class="step-card">
            <div class="step-title"><span class="step-number">1</span> 聯繫小幫手開門</div>
            <div style="font-size:15px;">請於 <span class="important">抵達前 30 分鐘</span> 通知小幫手，我們將為您遠端開啟首道小門。</div>
        </div>

        <div class="step-card">
            <div class="step-title"><span class="step-number">2</span> 領取房卡與鑰匙</div>
            <div style="font-size:15px;">進入大門後，請至 <strong>櫃檯取件盒或密碼鑰匙盒</strong> 領取您的房卡及鑰匙。</div>
        </div>

        <div class="step-card">
            <div class="step-title"><span class="step-number">3</span> 對應房號入住</div>
            <div style="font-size:15px;">請依鑰匙標示前往房間。若有任何問題請立即聯繫小幫手。</div>
        </div>

        <div class="notice-section">
            <div class="notice-title">💡 住宿小提醒</div>
            <div style="font-size:14px; margin-bottom:5px;">• <strong>關於橋件幸福：</strong>請詳閱入住須知。</div>
            <div style="font-size:14px; margin-bottom:5px;">• <strong>進退房：</strong>15:00後入住 / 11:00前退房</div>
            <div style="font-size:14px; margin-bottom:5px;">• <strong>降低音量：</strong>晚上10:00後請保持安靜</div>
            <div style="font-size:14px;">• <strong>室內禁菸：</strong><span class="important">違反規定者將收清潔費 $3000</span></div>
        </div>
    </div>

    <div class="contact-buttons">
        <a href="https://line.me/ti/p/您的ID" class="btn-float btn-line">LINE<br>聯繫</a>
        <a href="tel:您的電話號碼" class="btn-float btn-phone">撥打<br>電話</a>
    </div>

    <footer>
        祝您在 橋見幸福 擁有美好的時光！<br>
        © 2026 橋見幸福 版權所有
    </footer>
</div>

</body>
</html>
