<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile Readme</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            text-align: center;
            padding-top: 50px;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .glow {
            font-size: 30px;
            font-weight: bold;
            color: transparent;
            text-shadow: 0 0 10px #00cfff, 0 0 20px #00cfff, 0 0 40px #00cfff, 0 0 80px #00cfff, 0 0 120px #00cfff;
            animation: glow 1.5s ease-in-out infinite alternate;
        }
        @keyframes glow {
            0% {
                text-shadow: 0 0 10px #00cfff, 0 0 20px #00cfff, 0 0 40px #00cfff, 0 0 80px #00cfff, 0 0 120px #00cfff;
            }
            100% {
                text-shadow: 0 0 20px #00cfff, 0 0 30px #00cfff, 0 0 40px #00cfff, 0 0 90px #00cfff, 0 0 140px #00cfff;
            }
        }
        .social-link {
            display: inline-block;
            margin-right: 10px;
        }
        .tech-badge {
            display: inline-block;
            margin: 5px;
        }
        .github-stats {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hello, GitHub!</h1>
        <p class="glow">💫 About Me:</p>
        <p>🌱 I’m currently learning <strong>Kotlin, React.js</strong></p>
        <p>💬 Ask me about <strong>React-native, React.js, Kotlin</strong></p>
        <p>📫 How to reach me <strong>tahaalper1992@gmail.com</strong></p>

        <h2>🌐 Socials:</h2>
        <a href="https://linkedin.com/in/https://www.linkedin.com/in/tahaalper1/" class="social-link">
            <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" alt="LinkedIn">
        </a>

        <h2>💻 Tech Stack:</h2>
        <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" class="tech-badge">
        <img src="https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white" alt="Dart" class="tech-badge">
        <!-- Diğer teknoloji rozetleriniz -->
        
        <h2>📊 GitHub Stats:</h2>
        <div class="github-stats">
            <img src="https://github-readme-stats.vercel.app/api?username=tahaalper1&theme=vue&hide_border=false&include_all_commits=false&count_private=false" alt="GitHub Stats"><br>
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=tahaalper1&theme=vue&hide_border=false" alt="GitHub Streak Stats"><br>
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tahaalper1&theme=vue&hide_border=false&include_all_commits=false&count_private=false&layout=compact" alt="Top Languages">
        </div>
    </div>
</body>
</html>
