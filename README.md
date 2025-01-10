<!DOCTYPE html>
<html>
<head>
    <style>
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
        }
        
        .fade-in {
            animation: fadeIn 2s ease-in;
            opacity: 0;
            animation-fill-mode: forwards;
        }
        
        .slide-in {
            animation: slideIn 1s ease-out;
            transform: translateX(-100%);
            animation-fill-mode: forwards;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        @keyframes slideIn {
            from { transform: translateX(-100%); }
            to { transform: translateX(0); }
        }
        
        .delay-1 { animation-delay: 0.5s; }
        .delay-2 { animation-delay: 1s; }
        .delay-3 { animation-delay: 1.5s; }
        
        h1 {
            color: #2f80ed;
            border-bottom: 2px solid #2f80ed;
            padding-bottom: 10px;
        }
        
        .section {
            margin: 20px 0;
            padding: 15px;
            border-radius: 8px;
            background: #f6f8fa;
        }
        
        .contact {
            display: flex;
            gap: 10px;
            align-items: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="fade-in">
            <h1>Welcome to My Profile! 👋</h1>
        </div>

        <div class="section slide-in delay-1">
            <h2>💻 Technical Skills</h2>
            <p>I specialize in Software Development and Network Security, bringing innovative solutions to complex challenges.</p>
        </div>

        <div class="section slide-in delay-2">
            <h2>🛠️ Technology Stack</h2>
            <p>
                • 📱 Flutter Development<br>
                • ⚛️ React<br>
                • ☕ Java<br>
                • 🔒 Junior Penetration Tester<br>
                • 📊 Log Analysis Specialist
            </p>
        </div>

        <div class="section slide-in delay-3">
            <h2>📫 Get in Touch</h2>
            <div class="contact">
                <p>
                    📧 Personal: <a href="mailto:wisdomsibafo45@gmail.com">wisdomsibafo45@gmail.com</a><br>
                    🎓 Academic: <a href="mailto:wisdom.sibafo@facsciences-uy1.cm">wisdom.sibafo@facsciences-uy1.cm</a>
                </p>
            </div>
        </div>
    </div>
</body>
</html>
