<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile Preview - Yasamin</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d1117;
            color: #c9d1d9;
            line-height: 1.6;
        }
        .readme-box {
            border: 1px solid #30363d;
            border-radius: 12px;
            background-color: #0d1117;
            padding: 40px;
            max-width: 850px;
            margin: 40px auto;
            position: relative;
            box-shadow: 0 0 50px rgba(0,0,0,0.5);
        }
        .readme-box::before {
            content: '';
            position: absolute;
            top: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 100%;
            height: 2px;
            background: linear-gradient(90deg, transparent, #7ee787, #58a6ff, transparent);
        }
        h1 {
            font-size: 3rem;
            font-weight: 800;
            text-align: center;
            letter-spacing: -1px;
            margin-bottom: 10px;
            background: linear-gradient(120deg, #fff, #8b949e);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        h3 {
            font-size: 1.2rem;
            color: #e6edf3;
            border-bottom: 1px solid #21262d;
            padding-bottom: 10px;
            margin-top: 30px;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        .status-bar {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 20px;
            font-size: 0.9rem;
            color: #7d8590;
            margin-bottom: 40px;
            font-weight: 500;
        }
        .status-pill {
            background: #161b22;
            padding: 6px 16px;
            border-radius: 100px;
            border: 1px solid #30363d;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        .status-highlight {
            color: #7ee787;
        }
        .grid-section {
            display: grid;
            grid-template-columns: 1.2fr 0.8fr;
            gap: 40px;
            margin-bottom: 40px;
        }
        a { color: #58a6ff; text-decoration: none; font-weight: 500;}
        a:hover { text-decoration: underline; }
        .typing-effect {
            font-family: monospace;
            color: #8b949e;
            text-align: center;
            margin-bottom: 20px;
        }
        .project-card {
            background: #161b22;
            border: 1px solid #30363d;
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 10px;
        }
        .stats-wrapper {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
        }
    </style>
</head>
<body class="p-4">

    <div class="text-center text-gray-500 mb-4 text-xs">
        PREVIEW OF GITHUB README
    </div>

    <div class="readme-box">
        
        <!-- Header -->
        <div class="text-center">
            <div class="mb-2">
                <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Waving%20Hand.png" width="30">
            </div>
            <h1>Yasamin Amini</h1>
            <div class="typing-effect">
                Frontend Developer Student
            </div>
        </div>

        <!-- Modern Status Bar -->
        <div class="status-bar">
            <div class="status-pill">
                <img src="https://img.shields.io/badge/LIA_Internship-Available_April_2026-2ea44f?style=flat-square&logo=github&logoColor=white" alt="LIA Available">
            </div>
            <div class="status-pill">
                <img src="https://img.shields.io/badge/Location-Stockholm-blue?style=flat-square&logo=googlemaps&logoColor=white" alt="Stockholm">
            </div>
        </div>

        <!-- Main Content Grid -->
        <div class="grid-section">
            
            <!-- Left Column: About -->
            <div>
                <h3>⚡ About Me</h3>
                <p>
                    I’m a <strong>Frontend Developer student</strong> passionate about bridging the gap between design and technical implementation. 
                </p>
                <p>
                    I don't just write code; I explore the intersection of <strong>Logic, Design, and 3D Web</strong>. Currently, I am deepening my knowledge in <strong>TypeScript</strong> to build more robust applications.
                </p>
                
                <h3 style="margin-top: 30px;">What I Bring</h3>
                <div style="margin-bottom: 15px;">
                    <strong>🎯 Attention to Detail</strong><br>
                    <span style="color: #8b949e; font-size: 0.9em;">Pixel-perfect implementations</span>
                </div>
                <div style="margin-bottom: 15px;">
                    <strong>📚 Quick Learner</strong><br>
                    <span style="color: #8b949e; font-size: 0.9em;">Passionate about leveling up skills</span>
                </div>
                <div>
                    <strong>🎨 Design-Minded</strong><br>
                    <span style="color: #8b949e; font-size: 0.9em;">UX/UI awareness in development</span>
                </div>
            </div>

            <!-- Right Column: Tech Stack -->
            <div>
                <h3>🛠 Tech Stack</h3>
                <div style="text-align: center;">
                    <div style="font-size: 0.8em; color: #8b949e; margin-bottom: 5px; font-weight: bold;">Core (Languages & Frameworks)</div>
                    <img src="https://skillicons.dev/icons?i=js,react,ts,html,threejs&theme=dark" style="height: 35px; margin-bottom: 20px;">
                    
                    <div style="font-size: 0.8em; color: #8b949e; margin-bottom: 5px; font-weight: bold;">Styling & Build</div>
                    <img src="https://skillicons.dev/icons?i=css,sass,tailwind,vite&theme=dark" style="height: 35px; margin-bottom: 20px;">

                    <div style="font-size: 0.8em; color: #8b949e; margin-bottom: 5px; font-weight: bold;">Tools & Design</div>
                    <img src="https://skillicons.dev/icons?i=git,figma,vscode,blender&theme=dark" style="height: 35px;">
                </div>
            </div>
        </div>

        <!-- Featured Projects -->
        <h3>🚀 Featured Projects</h3>
        <div class="grid grid-cols-2 gap-4 text-sm mb-8">
            <div class="project-card">
                <div class="font-bold text-blue-400 mb-1">🛍️ [Project Name 1]</div>
                <div class="text-gray-400 text-xs mb-2">React • TypeScript • Vite</div>
                <div class="text-gray-500">A responsive e-commerce dashboard with cart functionality and API integration.</div>
            </div>
            <div class="project-card">
                <div class="font-bold text-purple-400 mb-1">🎲 [Project Name 2]</div>
                <div class="text-gray-400 text-xs mb-2">Three.js • React Three Fiber</div>
                <div class="text-gray-500">An interactive 3D web experience showcasing creative coding skills.</div>
            </div>
        </div>

        <!-- Stats -->
        <h3>📊 GitHub Activity</h3>
        <div class="stats-wrapper">
             <img src="https://github-readme-streak-stats.herokuapp.com/?user=yas-amini&theme=radical&hide_border=true" style="height: 150px; border-radius: 8px;">
             <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yas-amini&layout=compact&theme=radical&hide_border=true&langs_count=6" style="height: 150px; border-radius: 8px;">
        </div>

        <!-- Footer -->
        <div class="mt-10 pt-6 border-t border-gray-800 text-center">
            <h3 style="font-size: 1.1rem; margin-bottom: 15px; color: #fff; justify-content: center; border: none;">Let's Connect!</h3>
            <div class="flex justify-center gap-4 text-sm">
                <a href="#" class="text-blue-400 hover:text-blue-300">🌐 Portfolio</a> • 
                <a href="https://linkedin.com/in/yourprofile" class="text-blue-400 hover:text-blue-300">💼 LinkedIn</a> • 
                <a href="mailto:yaasamin.amini@gmail.com" class="text-blue-400 hover:text-blue-300">📧 Email Me</a> • 
                <a href="https://github.com/yas-amini" class="text-blue-400 hover:text-blue-300">🐙 GitHub</a>
            </div>
        </div>

    </div>

</body>
</html>
