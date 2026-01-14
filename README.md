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
        /* Subtle Glow at top */
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
        
        /* Typography */
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
        h2 {
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
        
        /* Custom Status Bar */
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
            color: #7ee787; /* Green for LIA */
        }
        
        /* Grid Layout for About + Stack */
        .grid-section {
            display: grid;
            grid-template-columns: 1.2fr 0.8fr;
            gap: 40px;
            margin-bottom: 40px;
        }
        
        /* Stats Styling */
        .stats-wrapper {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
        }
        
        /* Links */
        a { color: #58a6ff; text-decoration: none; font-weight: 500;}
        a:hover { text-decoration: underline; }

        .typing-effect {
            font-family: monospace;
            color: #8b949e;
            text-align: center;
            margin-bottom: 20px;
        }

        /* Project Cards (Simulated for Preview) */
        .project-card {
            background: #161b22;
            border: 1px solid #30363d;
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 10px;
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
                &lt;FrontendDeveloper /&gt;
            </div>
        </div>

        <!-- Modern Status Bar -->
        <div class="status-bar">
            <div class="status-pill">
                <i class="fas fa-map-marker-alt text-red-400"></i> Stockholm
            </div>
            <div class="status-pill" style="border-color: #238636;">
                <span class="relative flex h-2 w-2">
                  <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-green-400 opacity-75"></span>
                  <span class="relative inline-flex rounded-full h-2 w-2 bg-green-500"></span>
                </span>
                <span class="status-highlight">LIA: April 2026</span>
            </div>
            <div class="status-pill">
                <i class="fas fa-graduation-cap text-blue-400"></i> Student
            </div>
        </div>

        <!-- Main Content Grid -->
        <div class="grid-section">
            
            <!-- Left Column: About -->
            <div>
                <h2>⚡ About Me</h2>
                <p>
                    I’m a <strong>Frontend Developer student</strong> passionate about bridging the gap between design and technical implementation. 
                </p>
                <p>
                    I don't just write code; I explore the intersection of <strong>logic, design, and 3D web</strong>. Currently, I am deepening my knowledge in <strong>TypeScript</strong> to build more robust applications.
                </p>
                <p style="margin-top: 20px; font-size: 0.9em; color: #8b949e;">
                    <em>Looking for a LIA internship where I can contribute to real-world products and level up my React skills.</em>
                </p>
            </div>

            <!-- Right Column: Tech Stack (Reorganized) -->
            <div>
                <h2>🛠 Tech Stack</h2>
                <div style="margin-bottom: 15px;">
                    <div class="text-xs text-gray-500 mb-2 uppercase tracking-widest font-bold">Core (Languages & Frameworks)</div>
                    <img src="https://skillicons.dev/icons?i=js,react,ts,html,threejs&theme=dark" style="height: 35px;">
                </div>
                
                <div style="margin-bottom: 15px;">
                    <div class="text-xs text-gray-500 mb-2 uppercase tracking-widest font-bold">Styling & Build</div>
                    <img src="https://skillicons.dev/icons?i=css,sass,tailwind,vite&theme=dark" style="height: 35px;">
                </div>

                <div style="margin-bottom: 15px;">
                    <div class="text-xs text-gray-500 mb-2 uppercase tracking-widest font-bold">Tools & Design</div>
                    <img src="https://skillicons.dev/icons?i=git,figma,vscode,blender&theme=dark" style="height: 35px;">
                </div>
            </div>
        </div>

        <!-- Featured Projects (New Section) -->
        <h2>🚀 Featured Projects</h2>
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

        <!-- What I Bring (Updated) -->
        <h2>What I Bring</h2>
        <div class="grid grid-cols-3 gap-4 text-center text-sm">
            <div class="bg-gray-900 p-4 rounded-lg border border-gray-800">
                <div class="text-2xl mb-2">🎯</div>
                <div class="font-bold text-gray-300">Attention to Detail</div>
                <div class="text-gray-500 text-xs mt-1">Pixel-perfect implementations</div>
            </div>
            <div class="bg-gray-900 p-4 rounded-lg border border-gray-800">
                <div class="text-2xl mb-2">📚</div>
                <div class="font-bold text-gray-300">Quick Learner</div>
                <div class="text-gray-500 text-xs mt-1">Passionate about leveling up skills</div>
            </div>
            <div class="bg-gray-900 p-4 rounded-lg border border-gray-800">
                <div class="text-2xl mb-2">🎨</div>
                <div class="font-bold text-gray-300">Design-Minded</div>
                <div class="text-gray-500 text-xs mt-1">UX/UI awareness in development</div>
            </div>
        </div>

        <!-- Stats -->
        <h2>📊 GitHub Activity</h2>
        <div class="stats-wrapper">
             <img src="https://github-readme-streak-stats.herokuapp.com/?user=yas-amini&theme=radical&hide_border=true" style="height: 150px; border-radius: 8px;">
             <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yas-amini&layout=compact&theme=radical&hide_border=true&langs_count=6" style="height: 150px; border-radius: 8px;">
        </div>

        <!-- Footer (Reverted to Original Style) -->
        <div class="mt-10 pt-6 border-t border-gray-800 text-center">
            <h2 style="font-size: 1.5rem; margin-bottom: 10px; border: none;">Let's Connect!</h2>
            <p style="color: #8b949e; margin-bottom: 20px;">I'm always open to discussing frontend trends or potential internship opportunities.</p>
            <div class="flex justify-center gap-4 text-lg font-medium">
                <a href="#" class="text-blue-400 hover:text-blue-300 transition"><i class="fas fa-globe"></i> Portfolio</a>
                <span class="text-gray-700">•</span>
                <a href="https://linkedin.com/in/yourprofile" class="text-blue-400 hover:text-blue-300 transition"><i class="fab fa-linkedin"></i> LinkedIn</a>
                <span class="text-gray-700">•</span>
                <a href="mailto:yaasamin.amini@gmail.com" class="text-blue-400 hover:text-blue-300 transition"><i class="fas fa-envelope"></i> Email Me</a>
                <span class="text-gray-700">•</span>
                <a href="https://github.com/yas-amini" class="text-blue-400 hover:text-blue-300 transition"><i class="fab fa-github"></i> GitHub</a>
            </div>
        </div>

    </div>

</body>
</html>
