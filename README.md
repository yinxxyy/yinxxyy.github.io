<!DOCTYPE html>

<html lang="zh-CN">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>志翼翱翔 - 志愿填报系统下载中心</title>

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <style>

        * {

            margin: 0;

            padding: 0;

            box-sizing: border-box;

            font-family: 'Microsoft YaHei', 'Segoe UI', sans-serif;

        }

       

        body {

            background: linear-gradient(135deg, #1a2980, #26d0ce);

            color: #333;

            line-height: 1.6;

            min-height: 100vh;

            padding: 20px;

        }

       

        .container {

            max-width: 1200px;

            margin: 0 auto;

        }

       

        header {

            text-align: center;

            padding: 40px 20px;

            color: white;

            animation: fadeInDown 1s ease;

        }

       

        header h1 {

            font-size: 2.8rem;

            margin-bottom: 10px;

            text-shadow: 0 2px 4px rgba(0,0,0,0.2);

        }

       

        header p {

            font-size: 1.2rem;

            max-width: 700px;

            margin: 0 auto;

            opacity: 0.9;

        }

       

        .download-container {

            display: flex;

            flex-wrap: wrap;

            justify-content: center;

            gap: 30px;

            padding: 20px;

        }

       

        .download-card {

            background: white;

            border-radius: 15px;

            box-shadow: 0 10px 30px rgba(0,0,0,0.15);

            width: 100%;

            max-width: 350px;

            overflow: hidden;

            transition: transform 0.3s ease, box-shadow 0.3s ease;

            animation: fadeInUp 0.8s ease;

        }

       

        .download-card:hover {

            transform: translateY(-10px);

            box-shadow: 0 15px 35px rgba(0,0,0,0.2);

        }

        

        .card-header {

            background: linear-gradient(to right, #3a7bd5, #00d2ff);

            color: white;

            padding: 25px 20px;

            text-align: center;

        }

       

        .card-header i {

            font-size: 3.5rem;

            margin-bottom: 15px;

            display: block;

        }

       

        .card-header h2 {

            font-size: 1.6rem;

            margin-bottom: 10px;

        }

       

        .card-body {

            padding: 25px;

        }

        

        .features {

            margin-bottom: 25px;

        }

       

        .features li {

            margin-bottom: 10px;

            padding-left: 25px;

            position: relative;

        }

       

        .features li:before {

            content: "✓";

            position: absolute;

            left: 0;

            color: #3a7bd5;

            font-weight: bold;

        }

       

        .specs {

            background: #f8f9fa;

            border-left: 4px solid #3a7bd5;

            padding: 15px;

            border-radius: 0 5px 5px 0;

            margin-bottom: 25px;

            font-size: 0.9rem;

        }

       

        .specs p {

            margin-bottom: 8px;

        }

       

        .download-btn {

            display: block;

            width: 100%;

            padding: 15px;

            background: linear-gradient(to right, #3a7bd5, #00d2ff);

            color: white;

            text-align: center;

            text-decoration: none;

            font-size: 1.2rem;

            font-weight: bold;

            border-radius: 8px;

            transition: all 0.3s ease;

            border: none;

            cursor: pointer;

            box-shadow: 0 4px 15px rgba(58, 123, 213, 0.4);

        }

       

        .download-btn:hover {

            background: linear-gradient(to right, #2a6bc5, #00b2e2);

            box-shadow: 0 6px 20px rgba(58, 123, 213, 0.6);

            transform: translateY(-2px);

        }

       

        .download-btn i {

            margin-right: 10px;

        }

       

        footer {

            text-align: center;

            color: white;

            padding: 40px 20px;

            margin-top: 30px;

            font-size: 0.9rem;

            opacity: 0.8;

        }

       

        .logo {

            font-size: 2.5rem;

            font-weight: bold;

            margin-bottom: 20px;

            color: white;

            display: inline-block;

        }

       

        .logo span {

            color: #ffd700;

        }

       

        .contact-info {

            margin-top: 20px;

            font-size: 1rem;

        }

       

        .contact-info a {

            color: #ffd700;

            text-decoration: none;

        }

       

        .contact-info a:hover {

            text-decoration: underline;

        }

       

        /* Animations */

        @keyframes fadeInDown {

            from {

                opacity: 0;

                transform: translateY(-30px);

            }

            to {

                opacity: 1;

                transform: translateY(0);

            }

        }

       

        @keyframes fadeInUp {

            from {

                opacity: 0;

                transform: translateY(30px);

            }

            to {

                opacity: 1;

                transform: translateY(0);

            }

        }

       

        .download-card:nth-child(1) {

            animation-delay: 0.2s;

        }

       

        .download-card:nth-child(2) {

            animation-delay: 0.4s;

        }

        

        .download-card:nth-child(3) {

            animation-delay: 0.6s;

        }

       

        /* Responsive design */

        @media (max-width: 768px) {

            .download-container {

                flex-direction: column;

                align-items: center;

            }

           

            .download-card {

                max-width: 100%;

            }

           

            header h1 {

                font-size: 2.2rem;

            }

        }

    </style>

</head>

<body>

    <div class="container">

        <header>

            <div class="logo">志翼<span>翱翔</span></div>

            <h1>志愿填报系统下载中心</h1>

            <p>专业、智能、高效的志愿填报解决方案，助力考生实现大学梦想</p >

        </header>

       

        <div class="download-container">

            <!-- 专业组版 -->

            <div class="download-card">

                <div class="card-header">

                    <i class="fas fa-graduation-cap"></i>

                    <h2>专业组版试用版</h2>

                    <p>志翼翱翔志愿填报系统</p >

                </div>

                <div class="card-body">

                    <ul class="features">

                        <li>智能匹配院校专业组</li>

                        <li>大数据精准分析录取概率</li>

                        <li>个性化志愿方案推荐</li>

                        <li>历年录取分数线查询</li>

                    </ul>

                   

                    <div class="specs">

                        <p><strong>适用对象：</strong>新高考省份考生</p >

                        <p><strong>系统要求：</strong>Windows 7/8/10/11</p >

                        <p><strong>版本：</strong>试用版 v2.5.1</p >

                        <p><strong>大小：</strong>约 85 MB</p >

                    </div>

                   

                    <a href=" " class="download-btn">

                        <i class="fas fa-download"></i>点击下载

                    </a >

                </div>

            </div>

           

            <!-- 非专业组版 -->

            <div class="download-card">

                <div class="card-header">

                    <i class="fas fa-university"></i>

                    <h2>非专业组版试用版</h2>

                    <p>志翼翱翔志愿填报系统</p >

                </div>

                <div class="card-body">

                    <ul class="features">

                        <li>传统志愿填报模式</li>

                        <li>院校与专业独立分析</li>

                        <li>智能冲稳保策略推荐</li>

                        <li>就业前景分析</li>

                    </ul>

                   

                    <div class="specs">

                        <p><strong>适用对象：</strong>传统高考省份考生</p >

                        <p><strong>系统要求：</strong>Windows 7/8/10/11</p >

                        <p><strong>版本：</strong>试用版 v2.3.0</p >

                        <p><strong>大小：</strong>约 78 MB</p >

                    </div>

                   

                    <a href="http://ljyxy.ip-ddns.com/zyax/bzy/zyaxsybsetup.exe" class="download-btn">

                        <i class="fas fa-download"></i>点击下载

                    </a >

                </div>

            </div>

           

            <!-- 剪课大师 -->

            <div class="download-card">

                <div class="card-header">

                    <i class="fas fa-cut"></i>

                    <h2>剪课大师试用版</h2>

                    <p>高效课程编辑工具</p >

                </div>

                <div class="card-body">

                    <ul class="features">

                        <li>智能视频课程剪辑</li>

                        <li>一键去除空白片段</li>

                        <li>课件与视频同步编辑</li>

                        <li>多格式导出支持</li>

                    </ul>

                   

                    <div class="specs">

                        <p><strong>适用对象：</strong>教育工作者、学生</p >

                        <p><strong>系统要求：</strong>Windows 10/11</p >

                        <p><strong>版本：</strong>试用版 v1.8.2</p >

                        <p><strong>大小：</strong>约 120 MB</p >

                    </div>

                   

                    <a href="http://qny.ljyxy.ip-ddns.com/jkds/syb/jkdssybsetup.exe" class="download-btn">

                        <i class="fas fa-download"></i>点击下载

                    </a >

                </div>

            </div>

        </div>

       

        <footer>

            <p>© 2023 志翼翱翔教育科技 版权所有</p >

            <div class="contact-info">

                <p>客服电话：400-123-4567 | 邮箱：<a href="mailto:support@zhiyiaoxiang.com">support@zhiyiaoxiang.com</a ></p >

                <p>试用版说明：试用版包含全部功能，可使用30天，无学员数量限制</p >

            </div>

        </footer>

    </div>

 

    <script>

        // 添加下载按钮点击动画

        document.querySelectorAll('.download-btn').forEach(button => {

            button.addEventListener('click', function(e) {

                // 添加点击效果

                this.classList.add('clicked');

               

                // 获取软件名称

                const softwareName = this.closest('.download-card').querySelector('h2').textContent;

               

                // 提示信息（实际应用中这里可以添加统计代码）

                alert(`开始下载: ${softwareName}\n请稍候...`);

               

                // 防止重复点击

                this.style.pointerEvents = 'none';

                setTimeout(() => {

                    this.style.pointerEvents = 'auto';

                }, 3000);

            });

        });

    </script>

</body>

</html>
