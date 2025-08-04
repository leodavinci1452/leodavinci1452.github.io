<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional Certifications - M. Jimenez</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }

        .header {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 40px;
            margin-bottom: 30px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 4px;
            background: linear-gradient(90deg, #667eea, #764ba2, #f093fb, #f5576c);
            animation: shimmer 3s ease-in-out infinite;
        }

        @keyframes shimmer {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.7; }
        }

        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            background: linear-gradient(135deg, #667eea, #764ba2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .header .subtitle {
            font-size: 1.2rem;
            color: #666;
            margin-bottom: 20px;
        }

        .back-button {
            display: inline-block;
            background: rgba(102, 126, 234, 0.1);
            color: #667eea;
            padding: 10px 20px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: 600;
            margin-top: 15px;
            transition: all 0.3s ease;
        }

        .back-button:hover {
            background: rgba(102, 126, 234, 0.2);
            transform: translateY(-2px);
        }

        .section {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
        }

        .section:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.15);
        }

        .section h2 {
            font-size: 2rem;
            margin-bottom: 25px;
            color: #333;
            position: relative;
            display: inline-block;
        }

        .section h2::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 100%;
            height: 3px;
            background: linear-gradient(90deg, #667eea, #764ba2);
            border-radius: 2px;
        }

        .certification {
            margin-bottom: 25px;
            padding: 20px;
            border-radius: 15px;
            background: rgba(102, 126, 234, 0.05);
            border-left: 4px solid #667eea;
            transition: all 0.3s ease;
        }

        .certification:hover {
            background: rgba(102, 126, 234, 0.1);
            transform: translateX(5px);
        }

        .cert-name {
            font-size: 1.3rem;
            font-weight: bold;
            color: #667eea;
            margin-bottom: 8px;
        }

        .cert-issuer {
            font-size: 1.1rem;
            color: #333;
            margin-bottom: 5px;
        }

        .cert-date {
            color: #666;
            font-style: italic;
            margin-bottom: 10px;
        }

        .cert-description {
            color: #555;
            line-height: 1.6;
        }

        .cert-status {
            display: inline-block;
            padding: 5px 12px;
            border-radius: 15px;
            font-size: 0.9rem;
            font-weight: 600;
            margin-top: 10px;
        }

        .active {
            background: rgba(76, 175, 80, 0.1);
            color: #4CAF50;
        }

        .expired {
            background: rgba(244, 67, 54, 0.1);
            color: #F44336;
        }

        .placeholder-text {
            text-align: center;
            color: #666;
            font-style: italic;
            padding: 40px;
            background: rgba(102, 126, 234, 0.05);
            border-radius: 15px;
            border: 2px dashed #667eea;
        }

        @media (max-width: 768px) {
            .container {
                padding: 10px;
            }
            
            .header h1 {
                font-size: 2rem;
            }
            
            .section {
                padding: 20px;
            }
        }

        .floating-elements {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
        }

        .floating-circle {
            position: absolute;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.1);
            animation: float 6s ease-in-out infinite;
        }

        .floating-circle:nth-child(1) {
            width: 80px;
            height: 80px;
            top: 20%;
            left: 10%;
            animation-delay: 0s;
        }

        .floating-circle:nth-child(2) {
            width: 120px;
            height: 120px;
            top: 60%;
            right: 15%;
            animation-delay: 2s;
        }

        .floating-circle:nth-child(3) {
            width: 60px;
            height: 60px;
            bottom: 20%;
            left: 20%;
            animation-delay: 4s;
        }

        @keyframes float {
            0%, 100% {
                transform: translateY(0px) rotate(0deg);
                opacity: 0.5;
            }
            50% {
                transform: translateY(-20px) rotate(180deg);
                opacity: 0.8;
            }
        }
    </style>
</head>
<body>
    <div class="floating-elements">
        <div class="floating-circle"></div>
        <div class="floating-circle"></div>
        <div class="floating-circle"></div>
    </div>

    <div class="container">
        <header class="header">
            <h1>Professional Certifications</h1>
            <p class="subtitle">M. Jimenez - Multidisciplinary Senior Scientist</p>
            <a href="index.html" class="back-button">← Back to Main Page</a>
        </header>

        <section class="section">
            <h2>Education</h2>
            
            <div class="placeholder-text">
                <p><strong>Add your professional training and continuing education here.</strong></p>
                <p>Include workshops, seminars, online courses, and other professional development activities.</p>
            </div>
        </section>

        <section class="section">
            <h2>Professional Certifications</h2>
            
            <div class="certification">
                <div class="cert-name">Google Data Analytics Professional Certificate</div>
                <div class="cert-issuer">Google (via Coursera)</div>
                <div class="cert-date">Completed: 2022</div>
                <div class="cert-description">
                    Comprehensive program covering data analysis fundamentals, data cleaning, visualization, and analysis using tools like spreadsheets, SQL, R, and Tableau. Includes hands-on projects and real-world data analysis scenarios.
                </div>
                <div data-iframe-width="150" data-iframe-height="270" data-share-badge-id="e26f15a2-9fa1-4235-9069-42bc7a603b44" data-share-badge-host="https://www.credly.com"></div>
                <script type="text/javascript" async src="//cdn.credly.com/assets/utilities/embed.js"></script>
                <p style="margin-top: 10px;"><a href="https://www.credly.com/badges/e26f15a2-9fa1-4235-9069-42bc7a603b44" target="_blank" rel="noopener noreferrer" style="color: #667eea; text-decoration: none; font-weight: 600;">🏆 View Digital Badge on Credly</a></p>
                <span class="cert-status active">Active</span>
            </div>

            <h3 style="margin-top: 40px; margin-bottom: 20px; color: #667eea; font-size: 1.5rem;">Specialist Certifications (2020-2021)</h3>
            <div class="placeholder-text">
                <p><strong>Please provide details for your specialist certifications.</strong></p>
                <p>I can see you have specialist certifications from 2020-2021, but need the specific names and details to display them properly.</p>
            </div>

            <h3 style="margin-top: 40px; margin-bottom: 20px; color: #667eea; font-size: 1.5rem;">IBM Digital Badges (2020-Present)</h3>
            <div class="placeholder-text">
                <p><strong>Please provide details for your IBM Digital Badges.</strong></p>
                <p>I can see you have multiple IBM digital badges, but need the specific badge names and descriptions to display them properly.</p>
            </div>
        </section>
    </div>

    <script>
        // Add smooth scrolling and animations
        document.addEventListener('DOMContentLoaded', function() {
            const observerOptions = {
                threshold: 0.1,
                rootMargin: '0px 0px -50px 0px'
            };

            const observer = new IntersectionObserver(function(entries) {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.style.opacity = '1';
                        entry.target.style.transform = 'translateY(0)';
                    }
                });
            }, observerOptions);

            document.querySelectorAll('.section').forEach(section => {
                section.style.opacity = '0';
                section.style.transform = 'translateY(30px)';
                section.style.transition = 'all 0.6s ease';
                observer.observe(section);
            });
        });
    </script>
</body>
</html>
