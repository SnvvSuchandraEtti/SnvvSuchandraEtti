<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Suchandra Etti - Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background: linear-gradient(135deg, #6e8efb, #a777e3);
            color: white;
            text-align: center;
            padding: 40px 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 2.5rem;
            margin: 0;
        }

        header h3 {
            font-size: 1.5rem;
            margin: 10px 0 0;
        }

        .badges {
            display: flex;
            justify-content: center;
            margin: 20px 0;
            gap: 10px;
        }

        .badges img {
            height: 30px;
        }

        section {
            padding: 20px;
            margin: 20px auto;
            max-width: 900px;
            background: white;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

        section h2 {
            border-bottom: 2px solid #6e8efb;
            padding-bottom: 5px;
            margin-bottom: 15px;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            margin: 10px 0;
            line-height: 1.5;
        }

        .connect-icons {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
            margin: 20px 0;
        }

        .connect-icons a img {
            height: 40px;
            transition: transform 0.3s ease;
        }

        .connect-icons a img:hover {
            transform: scale(1.1);
        }

        .tools {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(80px, 1fr));
            gap: 15px;
            justify-items: center;
            margin-top: 20px;
        }

        .tools img {
            height: 40px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #6e8efb;
            color: white;
            margin-top: 20px;
        }

        footer a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>👋 Hi, I'm Suchandra Etti</h1>
        <h3>A passionate Frontend and Application Developer from India</h3>
        <div class="badges">
            <img src="https://img.shields.io/badge/Frontend%20Developer-%F0%9F%92%BB-blue" alt="Frontend Developer Badge">
            <img src="https://img.shields.io/badge/Application%20Development-Flutter%20&%20Node.js-brightgreen" alt="Application Developer Badge">
        </div>
    </header>

    <section>
        <h2>👩‍💻 About Me</h2>
        <ul>
            <li>🔭 <strong>Currently working on:</strong> <a href="#">College Application for Students</a></li>
            <li>🌱 <strong>Currently learning:</strong> Google Flutter, Node.js, Express.js, MongoDB</li>
            <li>👯 <strong>Looking to collaborate on:</strong> E-Commerce Applications</li>
            <li>🤝 <strong>Need help with:</strong> Cloud Computing and IoT Projects</li>
            <li>👨‍💻 <strong>My work:</strong> <a href="https://github.com/SnvvSuchandraEtti">GitHub Portfolio</a></li>
            <li>💬 <strong>Ask me about:</strong> Flutter, Java, Python</li>
            <li>📫 <strong>How to reach me:</strong> snvvs369@gmail.com</li>
            <li>📄 <strong>Know my experience:</strong> <a href="https://drive.google.com/file/d/1vjA-xYBa3WOc9dxbQ7PUc5FnGD5ZVpgQ/view?usp=sharing">Resume</a></li>
            <li>⚡ <strong>Fun Fact:</strong> I think I am funny!</li>
        </ul>
    </section>

    <section>
        <h2>🌐 Connect with Me</h2>
        <div class="connect-icons">
            <a href="https://codepen.io/snvvsuchandraetti"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/codepen.svg" alt="CodePen"></a>
            <a href="https://dev.to/suchandra"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/devto.svg" alt="Dev.to"></a>
            <a href="https://twitter.com/snvvs369"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="Twitter"></a>
            <a href="https://linkedin.com/in/suchandra-etti"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn"></a>
            <a href="https://stackoverflow.com/users/22353817/suchandra"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/stack-overflow.svg" alt="Stack Overflow"></a>
            <a href="https://instagram.com/s.u.c.h.a.n.d.r.a"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram"></a>
            <a href="https://www.youtube.com/@snvvs369/videos"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="YouTube"></a>
        </div>
    </section>

    <section>
        <h2>🛠️ Languages and Tools</h2>
        <div class="tools">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="Android">
            <img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="Angular">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3">
            <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="Flutter">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python">
        </div>
    </section>

    <footer>
        <p>✨ Designed by <a href="https://github.com/SnvvSuchandraEtti">Suchandra Etti</a> ✨</p>
    </footer>
</body>
