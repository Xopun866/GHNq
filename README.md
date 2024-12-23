<html lang="en">
<head>
    <meta charset="utf-8"/>
    <meta content="width=device-width, initial-scale=1.0" name="viewport"/>
    <title>GAY</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet"/>
    <style>
        .bg-red-black {
            background: linear-gradient(45deg, black 70%, red 30%);
        }
        @keyframes colorChange {
            0% {
                filter: hue-rotate(0deg);
            }
            100% {
                filter: hue-rotate(360deg);
            }
        }
        .color-changing {
            animation: colorChange 5s infinite linear;
        }
        .bg-color-changing {
            animation: colorChange 5s infinite linear;
        }
        .text-color-changing {
            animation: colorChange 5s infinite linear;
        }
        .glow-green {
            color: green;
            border: 1px solid green;
            padding: 1px 4px;
            border-radius: 2px;
            box-shadow: 0 0 5px green;
            font-size: 0.75rem;
        }
        .glow-red {
            color: red;
            border: 1px solid red;
            padding: 1px 4px;
            border-radius: 2px;
            box-shadow: 0 0 5px red;
            font-size: 0.75rem;
        }
        .scroll-container {
            display: flex;
            overflow: hidden;
            gap: 1rem;
            padding: 1rem 0;
            position: relative;
        }
        .scroll-item {
            flex: 0 0 auto;
            transition: transform 0.5s ease;
        }
        .emoji-rain {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
        }
        .emoji {
            position: absolute;
            top: -50px;
            font-size: 24px;
            animation: fall linear infinite;
        }
        @keyframes fall {
            to {
                transform: translateY(100vh);
            }
        }
        .glowing-border {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 10;
            border: 5px solid green;
            box-shadow: 0 0 10px green;
            animation: colorChange 5s infinite linear;
        }
    </style>
</head>
<body class="font-roboto bg-gray-100">
    <header class="bg-red-black bg-color-changing">
        <div class="container mx-auto flex justify-between items-center p-4 relative">
            <a href="#">
                <img alt="Road Rage Font - News App Logo" class="h-12 color-changing" src="https://fontmeme.com/permalink/241222/da378936e49ec01ba7853623ab210c0b.png"/>
            </a>
            <div class="absolute inset-0 flex justify-center items-center">
                <div class="text-sm font-bold flex flex-col items-center">
                    <span class="text-red-500 text-color-changing">G</span>
                    <span class="text-green-500 text-color-changing">A</span>
                    <span class="text-blue-500 text-color-changing">Y</span>
                </div>
            </div>
        </div>
    </header>
    <nav class="bg-white shadow-md relative">
        <div class="container mx-auto flex justify-between items-center p-4">
            <ul class="flex space-x-4">
                <li class="text-gray-700 hover:text-red-500">Hi</li>
                <li class="text-gray-700 hover:text-red-500">I'm</li>
                <li class="text-gray-700 hover:text-red-500">Rajdeep</li>
                <li class="text-gray-700 hover:text-red-500">🤡</li>
            </ul>
            <span class="glow-red">POPIYA</span>
        </div>
        <div class="glowing-border"></div>
    </nav>
    <main class="container mx-auto p-4">
        <section class="mb-8">
            <div class="flex justify-between items-center mb-4">
                <h2 class="text-2xl font-bold">This is me</h2>
                <span class="glow-green">Don't underestimate GHN</span>
            </div>
            <div class="scroll-container" id="scroll-container">
                <article class="scroll-item">
                    <h3 class="text-center">🤡</h3>
                    <img class="w-32 h-32 object-cover rounded-lg" src="https://i.ibb.co/6wd5Srr/IMG-20241222-171640.jpg" alt="A person with a clown face"/>
                    <p class="text-center text-sm mt-2">Gandu</p>
                </article>
                <article class="scroll-item">
                    <h3 class="text-center">🤡</h3>
                    <img class="w-32 h-32 object-cover rounded-lg" src="https://i.ibb.co/HYm2rbH/IMG-20241222-171622.jpg" alt="A person with a clown face"/>
                    <p class="text-center text-sm mt-2">Hagisu</p>
                </article>
                <article class="scroll-item">
                    <h3 class="text-center">🤡</h3>
                    <img class="w-32 h-32 object-cover rounded-lg" src="https://i.ibb.co/ySNQpYH/IMG-20241222-171603.jpg" alt="A person with a clown face"/>
                    <p class="text-center text-sm mt-2">Hagisu</p>
                </article>
                <article class="scroll-item">
                    <h3 class="text-center">🤡</h3>
                    <img class="w-32 h-32 object-cover rounded-lg" src="https://i.ibb.co/WD5Y7st/IMG-20241222-171549.jpg" alt="A person with a clown face"/>
                    <p class="text-center text-sm mt-2">Poliyo</p>
                </article>
                <article class="scroll-item">
                    <h3 class="text-center">🤡</h3>
                    <img class="w-32 h-32 object-cover rounded-lg" src="https://i.ibb.co/Rc9TWRp/IMG-20241221-WA0003.jpg" alt="A person with a clown face"/>
                    <p class="text-center text-sm mt-2">Chapri</p>
                </article>
            </div>
            <div class="flex justify-center space-x-4 mt-8">
                <a href="https://wa.me/916000768120">
                    <i class="fab fa-whatsapp text-2xl text-green-500"></i>
                </a>
                <a href="https://www.instagram.com/_rajdeep_0_r?igsh=MW9wZ2R6a3I3ZWRzeQ==">
                    <i class="fab fa-instagram text-2xl text-pink-500"></i>
                </a>
                <a href="https://t.me/+916000768120">
                    <i class="fab fa-telegram text-2xl text-blue-500"></i>
                </a>
            </div>
            <div class="flex justify-center mt-4">
                <iframe id="audio-frame" src="https://whyp.it/tracks/embed?id=238370&autoplay=1&loop=1" width="100%" height="50" scrolling="no" frameborder="0"></iframe>
            </div>
            <div class="flex justify-center items-center mt-2">
                <i class="fas fa-arrow-up mr-2 text-lg"></i>
                <span class="text-lg font-bold">Play This</span>
            </div>
        </section>
    </main>
    <div class="emoji-rain" id="emoji-rain"></div>
    <script>
        const scrollContainer = document.getElementById('scroll-container');
        let scrollAmount = 0;
        const scrollStep = 200; // Adjust this value to control the scroll speed
        const scrollInterval = 2000; // Adjust this value to control the interval between scrolls

        function autoScroll() {
            scrollAmount += scrollStep;
            if (scrollAmount >= scrollContainer.scrollWidth - scrollContainer.clientWidth + scrollStep) {
                scrollAmount = 0;
            }
            scrollContainer.scrollTo({
                left: scrollAmount,
                behavior: 'smooth'
            });
        }

        setInterval(autoScroll, scrollInterval);

        // Emoji rain
        const emojiRain = document.getElementById('emoji-rain');
        const emojis = ['🤣', '🤡', '😂', '🤣'];

        function createEmoji() {
            const emoji = document.createElement('div');
            emoji.classList.add('emoji');
            emoji.textContent = emojis[Math.floor(Math.random() * emojis.length)];
            emoji.style.left = Math.random() * 100 + 'vw';
            emoji.style.animationDuration = Math.random() * 3 + 2 + 's';
            emojiRain.appendChild(emoji);

            setTimeout(() => {
                emoji.remove();
            }, 5000);
        }

        setInterval(createEmoji, 300);
    </script>
</body>
</html>
