<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            background: linear-gradient(135deg, #f5f7fa 0%, #e8eef3 100%);
            min-height: 100vh;
            padding: 40px 20px;
            color: #2d3748;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
        }

        .glass {
            background: rgba(255, 255, 255, 0.7);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border-radius: 20px;
            border: 1px solid rgba(255, 255, 255, 0.8);
            box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.15);
            padding: 40px;
            margin-bottom: 30px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .glass:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 40px 0 rgba(31, 38, 135, 0.2);
        }

        .header {
            text-align: center;
            margin-bottom: 20px;
        }

        .header h1 {
            font-size: 3em;
            font-weight: 700;
            color: #1a202c;
            margin-bottom: 10px;
        }

        .header .emoji {
            display: inline-block;
            animation: wave 2s infinite;
        }

        @keyframes wave {
            0%, 100% { transform: rotate(0deg); }
            25% { transform: rotate(20deg); }
            75% { transform: rotate(-20deg); }
        }

        .subtitle {
            font-size: 1.3em;
            color: #4a5568;
            font-weight: 500;
            margin-bottom: 10px;
        }

        .tagline {
            font-style: italic;
            color: #718096;
            font-size: 1em;
        }

        .section-title {
            font-size: 1.8em;
            font-weight: 600;
            color: #2d3748;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .code-block {
            background: rgba(45, 55, 72, 0.05);
            border-radius: 12px;
            padding: 20px;
            font-family: 'Courier New', monospace;
            color: #2d3748;
            border: 1px solid rgba(203, 213, 224, 0.5);
            margin-bottom: 20px;
        }

        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            justify-content: center;
        }

        .tech-badge {
            background: rgba(255, 255, 255, 0.6);
            backdrop-filter: blur(5px);
            padding: 10px 20px;
            border-radius: 25px;
            font-weight: 500;
            color: #2d3748;
            border: 1px solid rgba(226, 232, 240, 0.8);
            transition: all 0.3s ease;
        }

        .tech-badge:hover {
            background: rgba(255, 255, 255, 0.9);
            transform: scale(1.05);
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }

        .quest-list {
            list-style: none;
            padding-left: 0;
        }

        .quest-list li {
            padding: 12px 0;
            font-size: 1.1em;
            color: #4a5568;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .quote-box {
            background: rgba(255, 255, 255, 0.5);
            backdrop-filter: blur(8px);
            border-left: 4px solid #cbd5e0;
            padding: 20px;
            border-radius: 8px;
            font-style: italic;
            color: #4a5568;
            margin: 20px 0;
        }

        .philosophy-list {
            list-style: none;
            padding-left: 0;
        }

        .philosophy-list li {
            padding: 10px 0;
            font-size: 1.05em;
            color: #4a5568;
            display: flex;
            align-items: flex-start;
            gap: 10px;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .social-btn {
            background: rgba(255, 255, 255, 0.7);
            backdrop-filter: blur(5px);
            padding: 12px 24px;
            border-radius: 30px;
            text-decoration: none;
            color: #2d3748;
            font-weight: 500;
            border: 1px solid rgba(226, 232, 240, 0.8);
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .social-btn:hover {
            background: rgba(255, 255, 255, 0.95);
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.15);
        }

        .footer {
            text-align: center;
            padding: 30px;
            color: #718096;
            font-style: italic;
        }

        .stats-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .stat-card {
            background: rgba(255, 255, 255, 0.5);
            backdrop-filter: blur(8px);
            border-radius: 15px;
            padding: 20px;
            text-align: center;
            border: 1px solid rgba(226, 232, 240, 0.8);
        }

        .stat-number {
            font-size: 2.5em;
            font-weight: 700;
            color: #2d3748;
        }

        .stat-label {
            color: #718096;
            font-size: 0.9em;
            margin-top: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="glass">
            <div class="header">
                <h1>Hey there! <span class="emoji">👋</span> I'm [Your Name]</h1>
                <div class="subtitle">🎯 Head of IT | Tech Leader | Problem Solver</div>
                <div class="tagline">Turning coffee into infrastructure and bugs into features since [year]</div>
            </div>
        </div>

        <div class="glass">
            <h2 class="section-title">🚀 What I Do</h2>
            <div class="code-block">
const myRole = {<br>
&nbsp;&nbsp;&nbsp;&nbsp;title: "Head of IT",<br>
&nbsp;&nbsp;&nbsp;&nbsp;responsibilities: ["Strategic Planning", "Team Leadership", "Infrastructure", "Innovation"],<br>
&nbsp;&nbsp;&nbsp;&nbsp;dailyDrive: "Making tech work so others don't have to think about it",<br>
&nbsp;&nbsp;&nbsp;&nbsp;superpower: "Explaining technical stuff to non-technical humans 🎭"<br>
};
            </div>
        </div>

        <div class="glass">
            <h2 class="section-title">💻 Tech Stack</h2>
            <div class="tech-stack">
                <div class="tech-badge">Python</div>
                <div class="tech-badge">JavaScript</div>
                <div class="tech-badge">Docker</div>
                <div class="tech-badge">Kubernetes</div>
                <div class="tech-badge">AWS</div>
                <div class="tech-badge">Linux</div>
                <div class="tech-badge">React</div>
                <div class="tech-badge">Node.js</div>
            </div>
        </div>

        <div class="glass">
            <h2 class="section-title">🎮 Current Quests</h2>
            <ul class="quest-list">
                <li>🏗️ Building scalable infrastructure that doesn't wake me up at 3am</li>
                <li>🧙‍♂️ Mentoring the next generation of tech wizards</li>
                <li>🔐 Making security actually user-friendly (yes, it's possible!)</li>
                <li>📚 Learning [new tech/skill you're exploring]</li>
                <li>☕ Perfecting my coffee-to-code ratio</li>
            </ul>
        </div>

        <div class="glass">
            <h2 class="section-title">📊 GitHub Stats</h2>
            <div class="stats-container">
                <div class="stat-card">
                    <div class="stat-number">500+</div>
                    <div class="stat-label">Commits This Year</div>
                </div>
                <div class="stat-card">
                    <div class="stat-number">50+</div>
                    <div class="stat-label">Repositories</div>
                </div>
                <div class="stat-card">
                    <div class="stat-number">15+</div>
                    <div class="stat-label">Languages Used</div>
                </div>
            </div>
        </div>

        <div class="glass">
            <h2 class="section-title">🎯 Leadership Philosophy</h2>
            <div class="quote-box">
                "The best IT is invisible IT. Also, always have backups. And backups of your backups."
            </div>
            <ul class="philosophy-list">
                <li>🤝 People over processes (but good processes help people)</li>
                <li>🚀 Automation is love, automation is life</li>
                <li>💡 If it's not documented, it doesn't exist</li>
                <li>🎪 Make work fun, because life's too short for boring code</li>
            </ul>
        </div>

        <div class="glass">
            <h2 class="section-title">🌐 Let's Connect!</h2>
            <div class="social-links">
                <a href="https://linkedin.com/in/YOUR_PROFILE" class="social-btn">💼 LinkedIn</a>
                <a href="https://twitter.com/YOUR_HANDLE" class="social-btn">🐦 Twitter</a>
                <a href="https://yourwebsite.com" class="social-btn">🌐 Website</a>
                <a href="mailto:your.email@example.com" class="social-btn">📧 Email</a>
            </div>
        </div>

        <div class="footer">
            <p>"In a world full of bugs, be the debugger." 🐛🔍</p>
        </div>
    </div>
</body>
</html>
