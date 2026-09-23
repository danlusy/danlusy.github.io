# danlusy.github.io
<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>典陸教育集團《新營站前校》國二段考複習班</title>
    <style>
        :root {
            --primary-color: #D32F2F;   /* 典陸鮮紅 */
            --dark-red: #8B0000;        /* 深紅 */
            --bg-light: #FDF8F8;         /* 微紅暖調背景 */
            --card-bg: #FFFFFF;
            --text-dark: #2B2B2B;
            --text-muted: #666666;
            --border-color: #EAEAEA;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", "PingFang TC", "Microsoft JhengHei", sans-serif;
            -webkit-tap-highlight-color: transparent;
        }

        body {
            background-color: #121212; /* 桌面上顯示外圍深色背景，突出 9:16 機身 */
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 0;
        }

        /* 9:16 手機容器 */
        .mobile-container {
            width: 100%;
            max-width: 420px; /* 手機黃金寬度比例 */
            background-color: var(--bg-light);
            min-height: 100vh;
            box-shadow: 0 0 20px rgba(0,0,0,0.3);
            overflow-y: auto;
            position: relative;
        }

        /* 手機版 Header */
        header {
            background: linear-gradient(135deg, var(--primary-color) 0%, var(--dark-red) 100%);
            color: #FFFFFF;
            padding: 25px 18px 20px 18px;
            text-align: center;
            border-bottom-left-radius: 16px;
            border-bottom-right-radius: 16px;
            box-shadow: 0 4px 10px rgba(139, 0, 0, 0.2);
        }

        .brand-subtitle {
            color: #FFE6E6;
            font-size: 0.82rem;
            font-weight: 600;
            letter-spacing: 1px;
            margin-bottom: 4px;
        }

        header h1 {
            font-size: 1.5rem;
            margin-bottom: 8px;
            font-weight: 700;
        }

        .tagline {
            font-size: 0.88rem;
            background-color: rgba(255, 255, 255, 0.18);
            display: inline-block;
            padding: 4px 12px;
            border-radius: 12px;
        }

        /* 主內容區 */
        .content {
            padding: 16px 14px;
        }

        /* 卡片設計 */
        .card {
            background: var(--card-bg);
            border-radius: 14px;
            padding: 18px 16px;
            margin-bottom: 16px;
            box-shadow: 0 2px 10px rgba(211, 47, 47, 0.05);
            border: 1px solid rgba(211, 47, 47, 0.08);
        }

        h2 {
            color: var(--primary-color);
            border-left: 4px solid var(--primary-color);
            padding-left: 8px;
            margin-bottom: 12px;
            font-size: 1.15rem;
            font-weight: 700;
        }

        .intro-text {
            font-size: 0.92rem;
            color: #444;
            line-height: 1.6;
            margin-bottom: 12px;
        }

        /* 特色列表 - 手機雙欄 */
        .features {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 8px;
        }

        .feature-item {
            background-color: #FFF0F0;
            padding: 10px 8px;
            border-radius: 8px;
            text-align: center;
            font-size: 0.82rem;
            font-weight: bold;
            color: var(--primary-color);
            border: 1px solid #FFD6D6;
        }

        /* 時間與費用卡片 */
        .info-card {
            background-color: #FFFBFB;
            border: 1px dashed var(--primary-color);
            border-radius: 10px;
            padding: 12px;
            margin-bottom: 10px;
            font-size: 0.9rem;
        }

        .info-card h3 {
            color: var(--primary-color);
            font-size: 0.95rem;
            margin-bottom: 4px;
        }

        .price-tag {
            font-size: 1.1rem;
            color: var(--primary-color);
            font-weight: bold;
        }

        /* 手機版直立式課表 */
        .timeline {
            display: flex;
            flex-direction: column;
            gap: 8px;
            margin-top: 10px;
        }

        .timeline-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #FAFAFA;
            padding: 10px 12px;
            border-radius: 8px;
            border-left: 3px solid var(--primary-color);
            font-size: 0.88rem;
        }

        .timeline-item.rest {
            border-left-color: #CCC;
            background: #F3F3F3;
            color: #666;
        }

        .timeline-time {
            font-weight: bold;
            color: #333;
        }

        .timeline-subject {
            font-weight: 600;
            color: var(--primary-color);
        }

        /* Google 表單容器 (手機優化高) */
        .google-form-container {
            position: relative;
            width: 100%;
            border-radius: 8px;
            overflow: hidden;
        }

        .google-form-container iframe {
            width: 100%;
            height: 980px;
            border: none;
        }

        /* 頁尾 Footer */
        footer {
            background-color: var(--dark-red);
            color: #FFFFFF;
            text-align: center;
            padding: 20px 15px;
            font-size: 0.85rem;
        }

        footer a {
            color: #FFCDD2;
            text-decoration: none;
        }

        .footer-info {
            margin-top: 8px;
            line-height: 1.6;
            opacity: 0.9;
        }
    </style>
</head>
<body>

    <div class="mobile-container">
        
        <!-- 手機頂部 Header -->
        <header>
            <div class="brand-subtitle">典陸教育集團｜12年一貫 專業品牌</div>
            <h1>《新營站前校》國二段考複習班</h1>
            <div class="tagline">115上學期 第一次段考精準衝刺</div>
        </header>

        <div class="content">
            
            <!-- 簡介卡片 -->
            <div class="card">
                <h2>親愛的家長您好</h2>
                <p class="intro-text">
                    為協助孩子有效準備段考，我們以各校範圍為核心，安排符合進度的題型演練。透過<strong>大量刷題、觀念釐清與即時訂正</strong>，提升作答速度與應試信心！
                </p>
                <div class="features">
                    <div class="feature-item">🎯 核心精準演練</div>
                    <div class="feature-item">✍️ 大量實戰刷題</div>
                    <div class="feature-item">💡 觀念即時訂正</div>
                    <div class="feature-item">🚀 提升解題速度</div>
                </div>
            </div>

            <!-- 課程與費用資訊 -->
            <div class="card">
                <h2>課程與費用資訊</h2>
                
                <div class="info-card">
                    <h3>📅 上課時間</h3>
                    <p><strong>115年10月11日 (日)</strong> 09:30 ~ 17:00</p>
                </div>

                <div class="info-card">
                    <h3>💰 課程費用</h3>
                    <p>全科刷題班：<span class="price-tag">300 元</span></p>
                    <p>代訂餐費：<span class="price-tag">100 元</span></p>
                </div>

                <div class="info-card" style="border-color: #E53935; background: #FFF5F5;">
                    <h3 style="color: #E53935;">⚠️ 重要提醒</h3>
                    <p>請於 <strong style="color:#E53935;">10/2 (五) 前</strong> 完成報名與繳費，以利講義印製。</p>
                </div>

                <h2 style="margin-top: 18px;">🕒 詳細課表</h2>
                <div class="timeline">
                    <div class="timeline-item">
                        <span class="timeline-time">09:30 ~ 12:00</span>
                        <span class="timeline-subject">數學 + 自然</span>
                    </div>
                    <div class="timeline-item rest">
                        <span class="timeline-time">12:00 ~ 13:30</span>
                        <span>午餐 + 休息時間</span>
                    </div>
                    <div class="timeline-item">
                        <span class="timeline-time">13:30 ~ 14:30</span>
                        <span class="timeline-subject">英文</span>
                    </div>
                    <div class="timeline-item rest">
                        <span class="timeline-time">14:30 ~ 15:00</span>
                        <span>休息時間</span>
                    </div>
                    <div class="timeline-item">
                        <span class="timeline-time">15:00 ~ 17:00</span>
                        <span class="timeline-subject">國文 + 社會</span>
                    </div>
                </div>
            </div>

            <!-- Google 表單區塊 -->
            <div class="card" style="padding: 12px 8px;">
                <h2 style="margin-left: 8px;">線上報名表單</h2>
                <div class="google-form-container">
                    <iframe 
                        src="https://docs.google.com/forms/d/e/1FAIpQLSeaMCaWgjgS8METbhD3i_Z2i41LJIwujjDa6eeUPTmSeb53oA/viewform?embedded=true" 
                        frameborder="0" 
                        marginheight="0" 
                        marginwidth="0">
                        載入中…
                    </iframe>
                </div>
            </div>

        </div>

        <footer>
            <p><strong>典陸教育集團《新營站前校》</strong></p>
            <div class="footer-info">
                <p>負責老師：岳杰老師</p>
                <p>電話：<a href="tel:066337160">06-6337160</a></p>
                <p>地址：台南市新營區大同路16-6號</p>
            </div>
        </footer>

    </div>

</body>
</html>
