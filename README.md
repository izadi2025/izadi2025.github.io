<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Ms. Izadi | معلم ریاضی و انگلیسی</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Vazir', -apple-system, BlinkMacSystemFont, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        
        .profile {
            text-align: center;
            background: white;
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            margin-bottom: 30px;
        }
        
        .profile img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-bottom: 20px;
            border: 5px solid #fff;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }
        
        .profile h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            color: #2c3e50;
        }
        
        .profile p {
            font-size: 1.2em;
            color: #7f8c8d;
            margin-bottom: 20px;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
        }
        
        .social-links a {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 12px 24px;
            background: linear-gradient(45deg, #667eea, #764ba2);
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            transition: all 0.3s ease;
        }
        
        .social-links a:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        }
        
        .skills {
            background: white;
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            margin-bottom: 30px;
        }
        
        .skills h2 {
            text-align: center;
            font-size: 2em;
            margin-bottom: 30px;
            color: #2c3e50;
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .skill-item {
            text-align: center;
            padding: 20px;
            background: #f8f9fa;
            border-radius: 15px;
            transition: transform 0.3s ease;
        }
        
        .skill-item:hover {
            transform: translateY(-5px);
        }
        
        .projects {
            background: white;
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }
        
        .projects h2 {
            text-align: center;
            font-size: 2em;
            margin-bottom: 30px;
            color: #2c3e50;
        }
        
        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        
        .project-card {
            background: #f8f9fa;
            border-radius: 15px;
            padding: 25px;
            text-decoration: none;
            color: #333;
            transition: all 0.3s ease;
            border: 1px solid #e9ecef;
            display: block;
        }
        
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 35px rgba(0,0,0,0.1);
            color: #333;
            text-decoration: none;
        }
        
        @media (max-width: 768px) {
            .container {
                padding: 10px;
            }
            .profile {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- پروفایل -->
        <section class="profile">
            <img src="https://avatars.githubusercontent.com/u/129846635?v=4" alt="رها ایزدی">
            <h1> Ms. Izadi </h1>
            <p>دانشجوی کارشناسی ارشد | معلم ریاضی و انگلیسی</p>
            
            <div class="social-links">
                <a href="#" target="_blank">
                    💼 LinkedIn
                </a>
                <a href="mailto:raha.izadi18@gmail.com">
                    📧 Email
                </a>
                <a href="https://t.me/r_izadi18" target="_blank">
                    💬 Telegram
                </a>
            </div>
        </section>

        <!-- مهارت‌ها -->
        <section class="skills">
            <h2>📚 مهارت‌های من</h2>
            <div class="skills-grid">
                <div class="skill-item">
                    <h3>📐 ریاضیات</h3>
                    <p>آموزش و تدریس</p>
                </div>
                <div class="skill-item">
                    <h3>📖 زبان انگلیسی</h3>
                    <p>آموزش و تدریس</p>
                </div>
                <div class="skill-item">
                    <h3>💻 برنامه‌نویسی</h3>
                    <p>یادگیری و توسعه</p>
                </div>
                <div class="skill-item">
                    <h3>🎓 آموزش</h3>
                    <p>طراحی دوره آموزشی</p>
                </div>
                <div class="skill-item">
                    <h3>📝 تولید محتوا</h3>
                    <p>آموزشی و آموزشی</p>
                </div>
                <div class="skill-item">
                    <h3>🔬 تحلیل داده</h3>
                    <p>ریاضی و آماری</p>
                </div>
            </div>
        </section>

        <!-- پروژه‌ها -->
        <section class="projects">
            <h2>📂 پروژه‌های من</h2>
            <div class="project-grid">
                <a href="https://github.com/rahaizadi/math-notes" class="project-card">
                    <h3>📚 جزوه‌های ریاضی</h3>
                    <p>جزوه‌های آموزشی کامل ریاضی دبیرستان</p>
                </a>
                <a href="#" class="project-card">
                    <h3>📖 فلش‌کارت انگلیسی</h3>
                    <p>مجموعه فلش‌کارت‌های واژگان انگلیسی</p>
                </a>
                <a href="#" class="project-card">
                    <h3>🎯 آزمون آنلاین</h3>
                    <p>سامانه آزمون آنلاین ریاضی و انگلیسی</p>
                </a>
            </div>
        </section>
    </div>
</body>
</html>
