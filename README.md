<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>简创网络 - 专业网站建设服务</title>
    <style>
        /* 全局样式 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Helvetica Neue', Arial, sans-serif;
        }
        
        body {
            line-height: 1.6;
            color: #333;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* 导航栏 */
        header {
            background-color: #fff;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: fixed;
            width: 100%;
            z-index: 100;
        }
        
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
        }
        
        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #2c3e50;
        }
        
        .logo span {
            color: #3498db;
        }
        
        .nav-links {
            display: flex;
            list-style: none;
        }
        
        .nav-links li {
            margin-left: 30px;
        }
        
        .nav-links a {
            text-decoration: none;
            color: #2c3e50;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        .nav-links a:hover {
            color: #3498db;
        }
        
        /* 英雄区域 */
        .hero {
            background: linear-gradient(135deg, #3498db, #2c3e50);
            color: white;
            padding: 180px 0 100px;
            text-align: center;
        }
        
        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
        }
        
        .hero p {
            font-size: 20px;
            max-width: 700px;
            margin: 0 auto 40px;
        }
        
        .btn {
            display: inline-block;
            background-color: #fff;
            color: #3498db;
            padding: 12px 30px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s;
        }
        
        .btn:hover {
            background-color: #f8f9fa;
            transform: translateY(-3px);
        }
        
        /* 服务区域 */
        .services {
            padding: 100px 0;
            text-align: center;
        }
        
        .section-title {
            font-size: 36px;
            margin-bottom: 60px;
            color: #2c3e50;
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .service-card {
            background-color: #fff;
            border-radius: 10px;
            padding: 40px 30px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            transition: transform 0.3s;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
        }
        
        .service-icon {
            font-size: 50px;
            color: #3498db;
            margin-bottom: 20px;
        }
        
        .service-card h3 {
            font-size: 22px;
            margin-bottom: 15px;
            color: #2c3e50;
        }
        
        /* 页脚 */
        footer {
            background-color: #2c3e50;
            color: white;
            padding: 50px 0 20px;
            text-align: center;
        }
        
        .footer-links {
            display: flex;
            justify-content: center;
            list-style: none;
            margin-bottom: 30px;
        }
        
        .footer-links li {
            margin: 0 15px;
        }
        
        .footer-links a {
            color: white;
            text-decoration: none;
        }
        
        .copyright {
            opacity: 0.7;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <!-- 导航栏 -->
    <header>
        <div class="container">
            <nav>
                <div class="logo">简创<span>网络</span></div>
                <ul class="nav-links">
                    <li><a href="#home">首页</a></li>
                    <li><a href="#services">服务</a></li>
                    <li><a href="#portfolio">案例</a></li>
                    <li><a href="#about">关于</a></li>
                    <li><a href="#contact">联系</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- 英雄区域 -->
    <section class="hero" id="home">
        <div class="container">
            <h1>打造您的专业在线形象</h1>
            <p>我们为企业和个人提供高品质的网站设计与开发服务，帮助您在数字世界中脱颖而出。</p>
            <a href="#contact" class="btn">免费咨询</a>
        </div>
    </section>

    <!-- 服务区域 -->
    <section class="services" id="services">
        <div class="container">
            <h2 class="section-title">我们的服务</h2>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">🖥️</div>
                    <h3>网站设计</h3>
                    <p>定制化的网站设计，完美匹配您的品牌形象和业务需求。</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">📱</div>
                    <h3>响应式开发</h3>
                    <p>适配所有设备的网站开发，确保在手机、平板和电脑上都有完美体验。</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">⚡</div>
                    <h3>网站优化</h3>
                    <p>提升网站速度和SEO表现，让您的网站在搜索引擎中排名更高。</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 页脚 -->
    <footer>
        <div class="container">
            <div class="logo" style="color: white; margin-bottom: 20px;">简创<span style="color: #3498db;">网络</span></div>
            <ul class="footer-links">
                <li><a href="#home">首页</a></li>
                <li><a href="#services">服务</a></li>
                <li><a href="#portfolio">案例</a></li>
                <li><a href="#about">关于</a></li>
                <li><a href="#contact">联系</a></li>
            </ul>
            <p class="copyright">© 2023 简创网络. 保留所有权利.</p>
        </div>
    </footer>
</body>
</html>
