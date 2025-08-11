<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BJG Assados - Banner de Domingo</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Anton&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #1f2937; /* bg-gray-800 */
        }
        .font-anton {
            font-family: 'Anton', sans-serif;
        }
        .text-shadow {
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.8);
        }
        .card-shadow {
            box-shadow: 0 10px 20px -3px rgba(0, 0, 0, 0.4), 0 4px 6px -2px rgba(0, 0, 0, 0.2);
        }
        .banner-bg {
            background: linear-gradient(rgba(41, 23, 10, 0.85), rgba(41, 23, 10, 0.85)), url('https://images.unsplash.com/photo-1543906233-a04de0f959c9?q=80&w=1200&auto=format&fit=crop');
            background-size: cover;
            background-position: center;
        }
        .header-art-bg {
            background: linear-gradient(rgba(20, 10, 5, 0.7), rgba(20, 10, 5, 0.7)), url('https://images.unsplash.com/photo-1555939594-58d7cb561ad1?q=80&w=1200&auto=format&fit=crop');
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body class="flex items-center justify-center min-h-screen p-2 sm:p-4">

    <div class="banner-bg rounded-lg card-shadow w-full lg:max-w-screen-lg overflow-hidden mx-auto">

        <!-- Header Section -->
        <header class="header-art-bg p-4 sm:p-6 text-center text-white border-b-4 border-yellow-400">
            <h1 class="font-anton text-3xl sm:text-5xl md:text-6xl tracking-wider text-shadow">BJG ASSADOS</h1>
            <p class="mt-2 text-sm sm:text-lg md:text-xl text-shadow">Desejamos um ótimo domingo para todos os nossos amigos clientes!</p>
        </header>

        <!-- Main Content -->
        <main class="p-4 sm:p-6 md:p-8">
            <h2 class="text-center text-xl sm:text-3xl font-bold text-white mb-6 text-shadow">HOJE TEREMOS:</h2>
            
            <!-- Grid for Dishes -->
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-6 md:gap-8 mb-8">

                <!-- Exemplo de card -->
                <div class="bg-gray-100 rounded-lg overflow-hidden shadow-lg transform hover:scale-105 transition-transform duration-300">
                    <img src="https://scontent-for2-2.xx.fbcdn.net/v/t39.30808-6/513479382_1314339097361581_3102407698228996289_n.jpg" alt="Costela de Boi no Bafo" class="w-full h-auto lg:h-56 object-contain" onerror="this.src='https://placehold.co/600x400/333/FFF?text=Costela';">
                    <div class="p-4 bg-gray-900 text-white text-center">
                        <h3 class="font-bold text-base sm:text-lg">COSTELA DE BOI</h3>
                    </div>
                </div>

                <!-- Aqui repetem todos os outros pratos com mesma lógica -->
                <!-- ... -->

            </div>

            <!-- Contact Section -->
            <div class="bg-yellow-400 p-4 sm:p-6 rounded-lg text-center shadow-inner">
                <h3 class="text-base sm:text-xl md:text-2xl font-bold text-gray-900">Entre em contato e reserve já seu pedido:</h3>
                <div class="mt-4 flex flex-col md:flex-row items-center justify-center gap-2 md:gap-4 text-gray-800 font-bold text-sm sm:text-lg md:text-xl">
                    <div class="flex items-center gap-2">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="#25D366"><path d="M.057 24..."/></svg>
                        <span>(11) 97499-3225</span>
                    </div>
                    <span class="hidden md:inline">ou</span>
                    <span>(11) 95585-5605</span>
                </div>
            </div>
        </main>

        <!-- Instagram e Local -->
        <div class="mt-8 flex flex-col sm:flex-row items-center justify-center gap-4 px-4">
            <a href="https://www.instagram.com/assados_bjg/" target="_blank" class="flex items-center gap-2 text-white hover:text-yellow-400 transition-colors duration-300">
                <svg width="28" height="28" viewBox="0 0 512 512"><defs>...</defs><path fill="url(#insta-gradient)" d="..."/></svg>
                <span class="font-bold text-base sm:text-lg">@assados_bjg</span>
            </a>
            <a href="https://www.google.com/maps/place/Assados+BJG" target="_blank" class="flex items-center gap-2 text-white hover:text-yellow-400 transition-colors duration-300">
                <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" fill="currentColor"><path d="M12 2C8.134 2..."/></svg>
                <span class="font-bold text-base sm:text-lg text-center">Rua Lourdes Mandu da Silva, 194 A - Jardim das Oliveiras</span>
            </a>
        </div>

    </div>

</body>
</html>
