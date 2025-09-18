
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Retro Tec Insulation Llc</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" />
    <link rel="apple-touch-icon" sizes="180x180" href="../icon/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="../icon/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="../icon/favicon-16x16.png">
    <link rel="manifest" href="../icon/site.webmanifest">
    <meta name="theme-color" content="#ffffff" />
    <meta name="description" content="Hall of vrchatians.">
    <meta property="og:url" content="https://RetroTecInsulationLlc.com">
    <meta property="og:type" content="website">
    <meta property="og:title" content="Retro Tec Insulation Llc">
    <meta property="og:description" content="Hall of vrchatians.">
    <meta property="og:image" content="https://r2.Retro Tec Insulation Llc/gangmonkeys/gangmonkeys.png">
    <meta name="twitter:card" content="summary_large_image">
    <meta property="twitter:domain" content="Retro Tec Insulation Llc">
    <meta property="twitter:url" content="https://Retro Tec Insulation Llc">
    <meta name="twitter:title" content="gangmonkeys.com">
    <meta name="twitter:description" content="Hall of vrchatians.">
    <meta name="twitter:image" content="https://r2.Retro Tec Insulation Llc/gangmonkeys/gangmonkeys.png">
    
    <style>
        /* Custom CSS for elements that need more specific styling */
        body {
            font-family: 'Courier New', monospace;
            overflow-x: hidden;
            color: white;
        }
        
        #overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.8);
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 3rem;
            font-weight: bold;
            z-index: 1000;
            cursor: pointer;
            transition: all 0.5s ease;
            text-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #e60073, 0 0 40px #e60073;
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        
        #bgVideo {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            z-index: -1;
        }
        
        .blur-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            backdrop-filter: blur(5px);
            z-index: -1;
        }
        
        .gif-container img {
            max-width: 300px;
            margin: 20px auto;
            display: block;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(255, 255, 255, 0.5);
        }
        
        .button-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 20px 0;
        }
        
        .outlined-button {
            background: transparent;
            color: white;
            border: 2px solid white;
            padding: 10px 25px;
            font-size: 1rem;
            cursor: pointer;
            transition: all 0.3s ease;
            border-radius: 50px;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        .outlined-button:hover {
            background: rgba(255, 255, 255, 0.2);
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(255, 255, 255, 0.3);
        }
        
        #search-container {
            display: flex;
            justify-content: center;
            margin: 20px 0;
        }
        
        #search-input {
            width: 60%;
            padding: 12px 20px;
            border: none;
            border-radius: 50px;
            background: rgba(255, 255, 255, 0.2);
            color: white;
            font-size: 1rem;
            outline: none;
            transition: all 0.3s ease;
        }
        
        #search-input:focus {
            background: rgba(255, 255, 255, 0.3);
            width: 70%;
        }
        
        #search-input::placeholder {
            color: rgba(255, 255, 255, 0.7);
        }
        
        .section-divider {
            height: 2px;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.5), transparent);
            margin: 40px 10%;
        }
        
        .section-title {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 3px;
            text-shadow: 0 0 10px rgba(255, 255, 255, 0.5);
        }
        
        .card-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            padding: 0 5%;
        }
        
        .user-card, .gang-card {
            background: rgba(0, 0, 0, 0.5);
            border-radius: 10px;
            padding: 15px;
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(5px);
        }
        
        .user-card:hover, .gang-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
            border-color: rgba(255, 255, 255, 0.3);
        }
        
        .user-avatar, .gang-avatar {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 5px;
            margin-bottom: 10px;
        }
        
        .user-name, .gang-name {
            font-size: 1.2rem;
            font-weight: bold;
            margin-bottom: 5px;
        }
        
        .user-status, .gang-members {
            font-size: 0.9rem;
            color: rgba(255, 255, 255, 0.7);
        }
        
        .discord-logo {
            position: fixed;
            bottom: 20px;
            right: 20px;
            width: 50px;
            height: 50px;
            transition: all 0.3s ease;
        }
        
        .discord-logo:hover {
            transform: scale(1.1);
        }
        
        .discord-logo img {
            width: 100%;
            height: 100%;
            object-fit: contain;
        }
        
        #clock {
            position: fixed;
            bottom: 20px;
            left: 20px;
            font-size: 1.2rem;
            background: rgba(0, 0, 0, 0.5);
            padding: 5px 10px;
            border-radius: 5px;
        }
        
        #timeCheckPopup {
            position: fixed;
            bottom: 60px;
            left: 20px;
            background: rgba(255, 0, 0, 0.7);
            padding: 10px 15px;
            border-radius: 5px;
            animation: shake 0.5s;
        }
        
        @keyframes shake {
            0%, 100% { transform: translateX(0); }
            25% { transform: translateX(-5px); }
            75% { transform: translateX(5px); }
        }
        
        .volume-slider-container {
            position: fixed;
            top: 20px;
            right: 20px;
            width: 100px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        #volume-slider {
            width: 100%;
            cursor: pointer;
            accent-color: white;
        }
        
        /* Responsive adjustments */
        @media (max-width: 768px) {
            .card-container {
                grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
            }
            
            #search-input {
                width: 80%;
            }
            
            #search-input:focus {
                width: 90%;
            }
            
            .gif-container img {
                max-width: 200px;
            }
            
            .button-container {
                flex-direction: column;
                align-items: center;
            }
        }
        /* Name tag styling */
        .name-tag {
            display: inline-block;
            background: rgba(255, 255, 255, 0.1);
            padding: 8px 15px;
            margin: 5px;
            border-radius: 20px;
            border: 1px solid rgba(255, 255, 255, 0.2);
            transition: all 0.2s ease;
        }
        .name-tag:hover {
            background: rgba(255, 255, 255, 0.2);
            transform: scale(1.05);
        }
        .names-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
    </style>
</head>
<body class="bg-black text-white">
    <!-- Click to Enter Overlay -->
    <div id="overlay" role="button" aria-label="Click to Enter" onclick="playMusicAndHideOverlay()">
        <div class="text-center">
            <div class="text-4xl md:text-6xl mb-4">Retro Tec Insulation</div>
            <div class="text-xl animate-bounce">Click to Enter</div>
        </div>
    </div>
    
    <!-- Volume Control -->
    <div class="volume-slider-container">
        <i class="fas fa-volume-up text-white"></i>
        <input id="volume-slider" type="range" min="0" max="1" step="0.01" value="0.5">
    </div>
    
    <!-- Background Video -->
    <video id="bgVideo" autoplay muted loop playsinline>
        <source src="https://r2.gangmonkeys.com/gangmonkeys/bg.mp4" type="video/mp4" />
        REEEEEEEEEEEEEEEEEEEEEEEEEEEEEEE
    </video>
    <div class="blur-overlay"></div>
    
    <!-- Main Content -->
    <div class="container mx-auto px-4 py-8">
        <!-- Logo GIF -->

        
        <!-- Navigation Buttons -->
        <div class="button-container">
            <button class="outlined-button" onclick="window.location.href='/depot';">Depot</button>
            <button class="outlined-button" onclick="window.location.href='/archieve';">Archieve</button>
            <button class="outlined-button" onclick="window.location.href='/hoa';">HOA</button>
        </div>
        
        <!-- Search Bar -->
        <div id="search-container">
            <input type="text" id="search-input" placeholder="Search..." />
        </div>
        
        <!-- Users Section -->
        <div class="section-divider"></div>
        <div id="users-section">
            <h2 class="section-title">Users</h2>
            <div class="names-container" id="userList">
                <!-- All names will be dynamically inserted here -->
            </div>
        </div>
        
        <!-- Gangs Section -->
        <div class="section-divider"></div>
        <div id="gangs-section">
            <h2 class="section-title">Gangs</h2>
            <div id="gangList" class="card-container">
                <!-- Gang cards will be dynamically inserted here -->
            </div>
        </div>
    </div>
    
    <!-- Discord Link -->
    <a href="https://discord.gg/pal" target="_blank" class="discord-logo">
        <img src="../discord.png" alt="Discord Logo" />
    </a>
    
    <!-- Background Audio -->
    <audio id="backgroundAudio" src="https://r2.gangmonkeys.com/gangmonkeys/Roi.ogg" loop autoplay></audio>
    
    <!-- Clock -->
    <div id="clock"></div>
    <div id="timeCheckPopup" style="display: none;">
        You should go to bed!
    </div>
    
    <script>
        // Initialize the page
        document.addEventListener('DOMContentLoaded', function() {
            // All the requested names
            const names = [
              
            ];
            // Render all names as tags
            const userList = document.getElementById('userList');
            names.forEach(name => {
                userList.innerHTML += `
                    <div class="name-tag">${name}</div>
                `;
            });
            
            // Sample gang data
            const gangs = [
                { id: 1, name: "Banana Brigade", members: "12 members", avatar: "https://r2.gangmonkeys.com/gangmonkeys/gang1.jpg" },
                { id: 2, name: "Jungle Junkies", members: "8 members", avatar: "https://r2.gangmonkeys.com/gangmonkeys/gang2.jpg" },
                { id: 3, name: "Pixel Punks", members: "15 members", avatar: "https://r2.gangmonkeys.com/gangmonkeys/gang3.jpg" },
                { id: 4, name: "VR Vandals", members: "20 members", avatar: "https://r2.gangmonkeys.com/gangmonkeys/gang4.jpg" }
            ];
            
            // Render gang cards
            const gangList = document.getElementById('gangList');
            gangs.forEach(gang => {
                gangList.innerHTML += `
                    <div class="gang-card">
                        <img src="${gang.avatar}" alt="${gang.name}" class="gang-avatar">
                        <div class="gang-name">${gang.name}</div>
                        <div class="gang-members">${gang.members}</div>
                    </div>
                `;
            });
            
            // Initialize clock
            updateClock();
            setInterval(updateClock, 1000);
            
            // Check if it's late
            checkTime();
            
            // Initialize volume control
            const volumeSlider = document.getElementById('volume-slider');
            const audio = document.getElementById('backgroundAudio');
            
            volumeSlider.addEventListener('input', function() {
                audio.volume = this.value;
            });
            
            // Search functionality
            const searchInput = document.getElementById('search-input');
            searchInput.addEventListener('input', function() {
                const searchTerm = this.value.toLowerCase();
                
                // Filter name tags
                document.querySelectorAll('.name-tag').forEach(tag => {
                    const name = tag.textContent.toLowerCase();
                    tag.style.display = name.includes(searchTerm) ? 'inline-block' : 'none';
                });
                
                // Filter gangs
                document.querySelectorAll('.gang-card').forEach(card => {
                    const name = card.querySelector('.gang-name').textContent.toLowerCase();
                    card.style.display = name.includes(searchTerm) ? 'block' : 'none';
                });
            });
        });
        
        function playMusicAndHideOverlay() {
            const overlay = document.getElementById('overlay');
            const audio = document.getElementById('backgroundAudio');
            
            // Fade out overlay
            overlay.style.opacity = '0';
            
            // Play audio when user interacts with the page
            audio.volume = document.getElementById('volume-slider').value;
            audio.play().catch(e => console.log("Autoplay prevented:", e));
            
            // Remove overlay after fade out
            setTimeout(() => {
                overlay.style.display = 'none';
            }, 500);
        }
        
        function updateClock() {
            const now = new Date();
            const clock = document.getElementById('clock');
            clock.textContent = now.toLocaleTimeString();
        }
        
        function checkTime() {
            const now = new Date();
            const hours = now.getHours();
            const popup = document.getElementById('timeCheckPopup');
            
            if (hours >= 2 && hours <= 6) {
                popup.style.display = 'block';
                setTimeout(() => {
                    popup.style.display = 'none';
                }, 5000);
            }
        }
    </script>
