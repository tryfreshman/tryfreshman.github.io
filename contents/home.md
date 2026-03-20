<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Homepage</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Helvetica Neue', Arial, sans-serif;
        }

        body {
            background-color: #f6f8fa;
            color: #24292f;
            line-height: 1.5;
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
        }

        .container {
            background-color: #ffffff;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
            padding: 40px;
            margin-top: 20px;
        }

        .header {
            display: flex;
            align-items: center;
            margin-bottom: 30px;
            border-bottom: 1px solid #e1e4e8;
            padding-bottom: 25px;
        }

        .avatar-placeholder {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            background: linear-gradient(135deg, #f0f3f6, #d9dee3);
            margin-right: 25px;
            border: 4px solid #f0f3f6;
        }

        .name-title h1 {
            font-size: 28px;
            font-weight: 600;
            margin-bottom: 5px;
            color: #1f2328;
        }

        .name-title h2 {
            font-size: 18px;
            font-weight: 400;
            color: #656d76;
        }

        .badge {
            display: inline-block;
            background-color: #f6f8fa;
            border: 1px solid #d0d7de;
            border-radius: 20px;
            padding: 5px 12px;
            font-size: 14px;
            color: #656d76;
            margin-top: 10px;
            text-decoration: none;
        }

        .badge img {
            height: 16px;
            vertical-align: text-bottom;
            margin-right: 5px;
        }

        .section {
            margin-bottom: 30px;
        }

        .section-title {
            font-size: 20px;
            font-weight: 600;
            color: #1f2328;
            padding-bottom: 8px;
            border-bottom: 2px solid #0969da;
            margin-bottom: 18px;
        }

        .contact-item, .education-item {
            margin-bottom: 12px;
            display: flex;
            align-items: center;
        }

        .contact-item strong, .education-item strong {
            min-width: 100px;
            color: #656d76;
        }

        .interest-list {
            list-style-type: none;
        }

        .interest-list li {
            padding: 8px 0 8px 20px;
            position: relative;
        }

        .interest-list li:before {
            content: "•";
            color: #0969da;
            font-weight: bold;
            font-size: 18px;
            position: absolute;
            left: 0;
        }

        a {
            color: #0969da;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        @media (max-width: 640px) {
            .header {
                flex-direction: column;
                text-align: center;
            }
            .avatar-placeholder {
                margin-right: 0;
                margin-bottom: 20px;
            }
            .contact-item, .education-item {
                flex-direction: column;
                align-items: flex-start;
            }
            .contact-item strong, .education-item strong {
                margin-bottom: 3px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- 头部信息：头像、姓名、学院 -->
        <header class="header">
            <div class="avatar-placeholder"></div>
            <div class="name-title">
                <h1>tryfreshman</h1>
                <h2>天津大学 精密仪器与光电子工程学院 测控技术与仪器</h2>
                <!-- 添加GitHub徽章链接 -->
                <a href="https://github.com/tryfreshman" class="badge" target="_blank">
                    <img src="https://simpleicons.org/icons/github.svg" alt="GitHub Logo"> tryfreshman
                </a>
            </div>
        </header>

        <!-- 联系方式 -->
        <section class="section">
            <h3 class="section-title">联系方式</h3>
            <div class="contact-item">
                <strong>Email:</strong>
                <a href="mailto:shangguan_666@tju.edu.cn">shangguan_666@tju.edu.cn</a>
            </div>
        </section>

        <!-- 教育背景 -->
        <section class="section">
            <h3 class="section-title">教育背景</h3>
            <div class="education-item">
                <strong>2023-2027</strong>
                <span>天津大学 测控技术与仪器 学士</span>
            </div>
        </section>

        <!-- 研究兴趣 -->
        <section class="section">
            <h3 class="section-title">研究兴趣</h3>
            <ul class="interest-list">
                <li>仪器仪表</li>
                <li>MEMS设计</li>
                <li>传感器设计与应用</li>
                <li>FPGA信号处理</li>
            </ul>
        </section>
    </div>
</body>
</html>