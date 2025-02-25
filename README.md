<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohamed Kandil</title>
    <style>
        body {
            font-family: 'Ubuntu', sans-serif;
            margin: 0;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: white;
        }

        .profile-container {
            max-width: 1200px;
            width: 100%;
            padding: 2rem;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin: 2rem 0;
        }

        .profile-card {
            background: rgba(255, 255, 255, 0.05);
            border-radius: 16px;
            backdrop-filter: blur(10px);
            padding: 2rem;
            display: flex;
            flex-direction: column;
            align-items: center;
            transition: transform 0.3s ease;
        }

        .profile-card:hover {
            transform: translateY(-5px);
        }

        .profile-pic {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            object-fit: cover;
            box-shadow: 0 0 0 5px rgba(255, 255, 255, 0.2);
            transition: transform 0.3s ease;
        }

        .profile-card:hover .profile-pic {
            transform: rotate(15deg);
        }

        .skill-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 1rem;
            padding: 1rem;
        }

        .skill-card {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            padding: 1.5rem;
            display: flex;
            flex-direction: column;
            align-items: center;
            transition: transform 0.3s ease;
        }

        .skill-card:hover {
            transform: scale(1.05);
        }

        .social-icon {
            color: white;
            padding: 0.5rem;
            transition: color 0.3s ease;
        }

        .social-icon:hover {
            color: #00bcd4;
        }

        @media (max-width: 768px) {
            .profile-container {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="profile-container">
        <div class="profile-card">
            <img src="https://github.com/Kandil7.png" alt="Profile" class="profile-pic">
            <h1>Mohamed Kandil</h1>
            <h3>Flutter Engineer | AI Enthusiast | Mobile Development Advocate</h3>
            <p>"Building intuitive mobile experiences with machine learning magic"</p>
            <div class="social-icons">
                <a href="mailto:mohamedkandeal7@gmail.com" class="social-icon">📧</a>
                <a href="https://linkedin.com/in/mohamedkandil" class="social-icon">🔗</a>
                <a href="https://github.com/Kandil7" class="social-icon">💻</a>
            </div>
        </div>

        <div class="profile-card">
            <h2>🚀 Skills Matrix</h2>
            <div class="skill-container">
                <div class="skill-card">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flutter/flutter-original.svg" alt="Flutter" width="48">
                    <h4>Flutter</h4>
                    <p>Native-like apps with Dart</p>
                </div>
                <div class="skill-card">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dart/dart-original.svg" alt="Dart" width="48">
                    <h4>Dart</h4>
                    <p>Modern backend-agnostic language</p>
                </div>
                <div class="skill-card">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/firebase/firebase-plain-wordmark.svg" alt="Firebase" width="48">
                    <h4>Firebase</h4>
                    <p>Cloud-based mobile solutions</p>
                </div>
                <div class="skill-card">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="48">
                    <h4>Python</h4>
                    <p>Machine Learning & Data Science</p>
                </div>
                <div class="skill-card">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tensorflow/tensorflow-original.svg" alt="TensorFlow" width="48">
                    <h4>TensorFlow</h4>
                    <p>Deep Learning Solutions</p>
                </div>
            </div>
        </div>

        <div class="profile-card">
            <h2>📊 GitHub Activity</h2>
            <img src="https://github-readme-stats.vercel.app/api?username=Kandil7&theme=react&show_icons=true&count_private=true" alt="Stats">
            <img src="https://github-readme-streak-stats.herokuapp.com?user=Kandil7&theme=react" alt="Streak">
        </div>

        <div class="profile-card">
            <h2>🌐 Recent Projects</h2>
            <a href="https://github.com/Kandil7/Flutter-ML-Kit">
                <div class="project-card">
                    <h3>Flutter ML Kit Integration</h3>
                    <p>Machine learning capabilities for mobile apps</p>
                </div>
            </a>
            <a href="https://github.com/Kandil7/Smart-Inventory">
                <div class="project-card">
                    <h3>Smart Inventory System</h3>
                    <p>Real-time inventory management solution</p>
                </div>
            </a>
        </div>
    </div>
</body>
</html>

## Connect with me:
<p align="center">
  <a href="https://linkedin.com/in/linkedin.com/in/mohamed-kandil-97k" target="blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="linkedin.com/in/mohamed-kandil-97k" height="30" width="40" />
  </a>
  <a href="https://instagram.com/mohamed.kandil_" target="blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="mohamed.kandil_" height="30" width="40" />
  </a>
</p>
