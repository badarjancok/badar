<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PT Indo Jaya Aditama - International Coal Trading</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-15px); }
            100% { transform: translateY(0px); }
        }
        
        .floating {
            animation: float 3s ease-in-out infinite;
        }
        
        .coal-particle {
            position: absolute;
            background-color: #333;
            border-radius: 50%;
            opacity: 0.6;
        }
        
        .gradient-text {
            background: linear-gradient(90deg, #f59e0b, #b45309);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        
        .hero-bg {
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), 
                        url('https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/36629dbc-22e6-4752-a670-a5f0e302790d.png') no-repeat center center;
            background-size: cover;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        
        .pulse-animation {
            animation: pulse 2s infinite;
        }
    </style>
</head>
<body class="font-sans bg-gray-100">
    <!-- Navbar -->
    <nav class="bg-gray-900 text-white shadow-lg fixed w-full z-50">
        <div class="container mx-auto px-6 py-3">
            <div class="flex justify-between items-center">
                <div class="flex items-center space-x-4">
                    <div class="flex items-center">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/ab64cd60-1d61-4c37-a4ce-a78a3faf5d54.png" alt="Logo PT Indo Jaya Aditama dengan warna hitam dan emas" class="h-12">
                    </div>
                </div>
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#home" class="hover:text-amber-500 transition">Beranda</a>
                    <a href="#about" class="hover:text-amber-500 transition">Tentang Kami</a>
                    <a href="#products" class="hover:text-amber-500 transition">Produk</a>
                    <a href="#contact" class="hover:text-amber-500 transition">Kontak</a>
                    <div class="flex items-center space-x-2">
                        <span class="text-sm">EN</span>
                        <div class="w-8 h-8 rounded-full border-2 border-amber-500 flex items-center justify-center hover:bg-amber-500 transition">
                            <i class="fas fa-globe text-xs"></i>
                        </div>
                    </div>
                </div>
                <div class="md:hidden flex items-center">
                    <button class="outline-none mobile-menu-button">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-bg min-h-screen flex items-center justify-center text-white pt-20">
        <div class="container mx-auto px-6 py-16">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <h1 class="text-4xl md:text-6xl font-bold mb-6 leading-tight">
                        <span class="gradient-text">PT Indo Jaya Aditama</span><br>
                        Solusi Batu Bara Berkualitas Internasional
                    </h1>
                    <p class="text-xl mb-8">
                        Penyedia terkemuka batu bara berkualitas tinggi untuk kebutuhan industri global sejak 2010
                    </p>
                    <div class="flex space-x-4">
                        <a href="#products" class="bg-amber-600 hover:bg-amber-700 text-white px-8 py-3 rounded-full font-semibold transition pulse-animation">Lihat Produk</a>
                        <a href="#contact" class="border-2 border-white hover:border-amber-500 hover:text-amber-500 text-white px-8 py-3 rounded-full font-semibold transition">Hubungi Kami</a>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center relative">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/8cccd99c-c013-47c9-acab-dd727830967f.png" alt="Tumpukan batu bara berkualitas tinggi dengan latar belakang industri" class="rounded-xl shadow-2xl floating">
                </div>
            </div>
        </div>
        
        <!-- Animated coal particles -->
        <div id="coal-particles"></div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-5xl font-bold mb-4 gradient-text">Tentang Perusahaan</h2>
                <div class="w-24 h-1 bg-amber-500 mx-auto"></div>
            </div>
            
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/c4ff7e70-befe-4492-aa92-2520342c4805.png" alt="Kantor pusat PT Indo Jaya Aditama dengan desain modern dan profesional" class="rounded-xl shadow-lg floating">
                </div>
                <div class="md:w-1/2 md:pl-12">
                    <h3 class="text-2xl font-bold mb-6">PT Indo Jaya Aditama</h3>
                    <p class="mb-6 text-gray-700 leading-relaxed">
                        Didirikan pada tahun 2010, PT Indo Jaya Aditama telah tumbuh menjadi salah satu eksportir batu bara terkemuka di Indonesia. Dengan jaringan yang kuat dan komitmen terhadap kualitas, kami menyediakan solusi batu bara untuk berbagai kebutuhan industri di lebih dari 15 negara.
                    </p>
                    
                    <div class="space-y-4">
                        <div class="flex items-start space-x-4">
                            <div class="bg-amber-100 text-amber-600 w-12 h-12 rounded-full flex items-center justify-center flex-shrink-0">
                                <i class="fas fa-check text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-bold mb-1">Visi Kami</h4>
                                <p class="text-gray-600">Menjadi pemimpin global dalam penyediaan batu bara berkualitas tinggi dengan komitmen terhadap keberlanjutan.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start space-x-4">
                            <div class="bg-amber-100 text-amber-600 w-12 h-12 rounded-full flex items-center justify-center flex-shrink-0">
                                <i class="fas fa-check text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-bold mb-1">Misi Kami</h4>
                                <p class="text-gray-600">Menyediakan produk berkualitas dengan layanan terbaik sambil mempertimbangkan dampak lingkungan dan sosial.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start space-x-4">
                            <div class="bg-amber-100 text-amber-600 w-12 h-12 rounded-full flex items-center justify-center flex-shrink-0">
                                <i class="fas fa-check text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-bold mb-1">Nilai Inti</h4>
                                <p class="text-gray-600">Integritas, Kualitas, Inovasi, dan Tanggung Jawab Sosial.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="py-16 bg-gray-900 text-white">
        <div class="container mx-auto px-6">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
                <div class="p-6">
                    <div class="text-4xl md:text-6xl font-bold gradient-text mb-2">
                        <span class="counter" data-target="15">0</span>+
                    </div>
                    <p class="text-gray-300">Negara Tujuan Ekspor</p>
                </div>
                <div class="p-6">
                    <div class="text-4xl md:text-6xl font-bold gradient-text mb-2">
                        <span class="counter" data-target="500">0</span>+
                    </div>
                    <p class="text-gray-300">Ribu Ton/Tahun</p>
                </div>
                <div class="p-6">
                    <div class="text-4xl md:text-6xl font-bold gradient-text mb-2">
                        <span class="counter" data-target="100">0</span>+
                    </div>
                    <p class="text-gray-300">Klien Tetap</p>
                </div>
                <div class="p-6">
                    <div class="text-4xl md:text-6xl font-bold gradient-text mb-2">
                        <span class="counter" data-target="12">0</span>+
                    </div>
                    <p class="text-gray-300">Tahun Pengalaman</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-20 bg-gray-100">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-5xl font-bold mb-4 gradient-text">Produk Kami</h2>
                <div class="w-24 h-1 bg-amber-500 mx-auto"></div>
                <p class="text-xl text-gray-600 mt-4 max-w-2xl mx-auto">Batu bara berkualitas tinggi untuk berbagai kebutuhan industri dengan spesifikasi yang tepat.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Product 1 -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transform transition hover:-translate-y-2 group">
                    <div class="relative overflow-hidden">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/bd1fb77a-d5ec-4ed6-b8b3-c805eb3fc680.png" alt="Batu bara kalori tinggi dengan tekstur mengkilap dan warna hitam pekat" class="w-full h-64 object-cover">
                        <div class="absolute inset-0 bg-gradient-to-t from-black to-transparent opacity-70"></div>
                        <div class="absolute bottom-0 left-0 p-6">
                            <h3 class="text-2xl font-bold text-white">High Caloric Coal</h3>
                        </div>
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-4">
                            <span class="text-amber-600 font-bold">GCV > 7000 kcal/kg</span>
                            <span class="bg-gray-200 px-3 py-1 rounded-full text-xs font-semibold">GAR Basis</span>
                        </div>
                        <div class="mb-4">
                            <ul class="space-y-2 text-gray-600">
                                <li class="flex items-start">
                                    <i class="fas fa-check text-amber-500 mr-2 mt-1"></i>
                                    <span>Total Moisture: < 14%</span>
                                </li>
                                <li class="flex items-start">
                                    <i class="fas fa-check text-amber-500 mr-2 mt-1"></i>
                                    <span>Ash Content: < 5%</span>
                                </li>
                                <li class="flex items-start">
                                    <i class="fas fa-check text-amber-500 mr-2 mt-1"></i>
                                    <span>Sulphur Content: < 0.8%</span>
                                </li>
                            </ul>
                        </div>
                        <div class="flex justify-between items-center mt-6">
                            <button class="text-amber-600 hover:text-amber-700 font-semibold transition">Detail Spesifikasi</button>
                            <button class="bg-amber-600 hover:bg-amber-700 text-white px-4 py-2 rounded-full text-sm font-semibold transition group-hover:scale-105">Minta Penawaran</button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transform transition hover:-translate-y-2 group">
                    <div class="relative overflow-hidden">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/29f76d82-3839-4c6f-b7fc-44614d9390cf.png" alt="Batu bara kalori sedang dengan tekstur kasar dan warna hitam kecoklatan" class="w-full h-64 object-cover">
                        <div class="absolute inset-0 bg-gradient-to-t from-black to-transparent opacity-70"></div>
                        <div class="absolute bottom-0 left-0 p-6">
                            <h3 class="text-2xl font-bold text-white">Medium Caloric Coal</h3>
                        </div>
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-4">
                            <span class="text-amber-600 font-bold">GCV 6000-6500 kcal/kg</span>
                            <span class="bg-gray-200 px-3 py-1 rounded-full text-xs font-semibold">GAR Basis</span>
                        </div>
                        <div class="mb-4">
                            <ul class="space-y-2 text-gray-600">
                                <li class="flex items-start">
                                    <i class="fas fa-check text-amber-500 mr-2 mt-1"></i>
                                    <span>Total Moisture: < 18%</span>
                                </li>
                                <li class="flex items-start">
                                    <i class="fas fa-check text-amber-500 mr-2 mt-1"></i>
                                    <span>Ash Content: < 8%</span>
                                </li>
                                <li class="flex items-start">
                                    <i class="fas fa-check text-amber-500 mr-2 mt-1"></i>
                                    <span>Sulphur Content: < 1%</span>
                                </li>
                            </ul>
                        </div>
                        <div class="flex justify-between items-center mt-6">
                            <button class="text-amber-600 hover:text-amber-700 font-semibold transition">Detail Spesifikasi</button>
                            <button class="bg-amber-600 hover:bg-amber-700 text-white px-4 py-2 rounded-full text-sm font-semibold transition group-hover:scale-105">Minta Penawaran</button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transform transition hover:-translate-y-2 group">
                    <div class="relative overflow-hidden">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/08fa84b0-b1e3-40a9-aa84-89abb6946f6d.png" alt="Batu bara rendah sulfur dengan tekstur halus dan warna hitam metalik" class="w-full h-64 object-cover">
                        <div class="absolute inset-0 bg-gradient-to-t from-black to-transparent opacity-70"></div>
                        <div class="absolute bottom-0 left-0 p-6">
                            <h3 class="text-2xl font-bold text-white">Low Sulphur Coal</h3>
                        </div>
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-4">
                            <span class="text-amber-600 font-bold">GCV > 5800 kcal/kg</span>
                            <span class="bg-gray-200 px-3 py-1 rounded-full text-xs font-semibold">GAR Basis</span>
                        </div>
                        <div class="mb-4">
                            <ul class="space-y-2 text-gray-600">
                                <li class="flex items-start">
                                    <i class="fas fa-check text-amber-500 mr-2 mt-1"></i>
                                    <span>Total Moisture: < 20%</span>
                                </li>
                                <li class="flex items-start">
                                    <i class="fas fa-check text-amber-500 mr-2 mt-1"></i>
                                    <span>Ash Content: < 10%</span>
                                </li>
                                <li class="flex items-start">
                                    <i class="fas fa-check text-amber-500 mr-2 mt-1"></i>
                                    <span>Sulphur Content: < 0.5%</span>
                                </li>
                            </ul>
                        </div>
                        <div class="flex justify-between items-center mt-6">
                            <button class="text-amber-600 hover:text-amber-700 font-semibold transition">Detail Spesifikasi</button>
                            <button class="bg-amber-600 hover:bg-amber-700 text-white px-4 py-2 rounded-full text-sm font-semibold transition group-hover:scale-105">Minta Penawaran</button>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-16">
                <button class="border-2 border-amber-600 text-amber-600 hover:bg-amber-600 hover:text-white px-8 py-3 rounded-full font-semibold transition">Lihat Semua Produk</button>
            </div>
        </div>
    </section>

    <!-- Process Section -->
    <section class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-5xl font-bold mb-4 gradient-text">Proses Bisnis Kami</h2>
                <div class="w-24 h-1 bg-amber-500 mx-auto"></div>
                <p class="text-xl text-gray-600 mt-4 max-w-2xl mx-auto">Proses terintegrasi dari penambangan hingga pengiriman ke pelanggan internasional</p>
            </div>
            
            <div class="relative">
                <!-- Process Line -->
                <div class="hidden md:block absolute left-1/2 top-1/2 transform -translate-y-1/2 -translate-x-1/2 h-2 bg-gray-200 w-5/6"></div>
                
                <!-- Process Steps -->
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <!-- Step 1 -->
                    <div class="flex flex-col items-center text-center">
                        <div class="bg-white border-4 border-amber-500 rounded-full w-24 h-24 flex items-center justify-center mb-4 relative z-10">
                            <i class="fas fa-mountain text-3xl <!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PT Indo Jaya Aditama - International Coal Trading</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-15px); }
            100% { transform: translateY(0px); }
        }
        
        .floating {
            animation: float 3s ease-in-out infinite;
        }
        
        .coal-particle {
            position: absolute;
            background-color: #333;
            border-radius: 50%;
            opacity: 0.6;
        }
        
        .gradient-text {
            background: linear-gradient(90deg, #f59e0b, #b45309);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        
        .hero-bg {
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), 
                        url('https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/36629dbc-22e6-4752-a670-a5f0e302790d.png') no-repeat center center;
            background-size: cover;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        
        .pulse-animation {
            animation: pulse 2s infinite;
        }
    </style>
</head>
<body class="font-sans bg-gray-100">
    <!-- Navbar -->
    <nav class="bg-gray-900 text-white shadow-lg fixed w-full z-50">
        <div class="container mx-auto px-6 py-3">
            <div class="flex justify-between items-center">
                <div class="flex items-center space-x-4">
                    <div class="flex items-center">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/ab64cd60-1d61-4c37-a4ce-a78a3faf5d54.png" alt="Logo PT Indo Jaya Aditama dengan warna hitam dan emas" class="h-12">
                    </div>
                </div>
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#home" class="hover:text-amber-500 transition">Beranda</a>
                    <a href="#about" class="hover:text-amber-500 transition">Tentang Kami</a>
                    <a href="#products" class="hover:text-amber-500 transition">Produk</a>
                    <a href="#contact" class="hover:text-amber-500 transition">Kontak</a>
                    <div class="flex items-center space-x-2">
                        <span class="text-sm">EN</span>
                        <div class="w-8 h-8 rounded-full border-2 border-amber-500 flex items-center justify-center hover:bg-amber-500 transition">
                            <i class="fas fa-globe text-xs"></i>
                        </div>
                    </div>
                </div>
                <div class="md:hidden flex items-center">
                    <button class="outline-none mobile-menu-button">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-bg min-h-screen flex items-center justify-center text-white pt-20">
        <div class="container mx-auto px-6 py-16">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <h1 class="text-4xl md:text-6xl font-bold mb-6 leading-tight">
                        <span class="gradient-text">PT Indo Jaya Aditama</span><br>
                        Solusi Batu Bara Berkualitas Internasional
                    </h1>
                    <p class="text-xl mb-8">
                        Penyedia terkemuka batu bara berkualitas tinggi untuk kebutuhan industri global sejak 2010
                    </p>
                    <div class="flex space-x-4">
                        <a href="#products" class="bg-amber-600 hover:bg-amber-700 text-white px-8 py-3 rounded-full font-semibold transition pulse-animation">Lihat Produk</a>
                        <a href="#contact" class="border-2 border-white hover:border-amber-500 hover:text-amber-500 text-white px-8 py-3 rounded-full font-semibold transition">Hubungi Kami</a>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center relative">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/8cccd99c-c013-47c9-acab-dd727830967f.png" alt="Tumpukan batu bara berkualitas tinggi dengan latar belakang industri" class="rounded-xl shadow-2xl floating">
                </div>
            </div>
        </div>
        
        <!-- Animated coal particles -->
        <div id="coal-particles"></div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-5xl font-bold mb-4 gradient-text">Tentang Perusahaan</h2>
                <div class="w-24 h-1 bg-amber-500 mx-auto"></div>
            </div>
            
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/c4ff7e70-befe-4492-aa92-2520342c4805.png" alt="Kantor pusat PT Indo Jaya Aditama dengan desain modern dan profesional" class="rounded-xl shadow-lg floating">
                </div>
                <div class="md:w-1/2 md:pl-12">
                    <h3 class="text-2xl font-bold mb-6">PT Indo Jaya Aditama</h3>
                    <p class="mb-6 text-gray-700 leading-relaxed">
                        Didirikan pada tahun 2010, PT Indo Jaya Aditama telah tumbuh menjadi salah satu eksportir batu bara terkemuka di Indonesia. Dengan jaringan yang kuat dan komitmen terhadap kualitas, kami menyediakan solusi batu bara untuk berbagai kebutuhan industri di lebih dari 15 negara.
                    </p>
                    
                    <div class="space-y-4">
                        <div class="flex items-start space-x-4">
                            <div class="bg-amber-100 text-amber-600 w-12 h-12 rounded-full flex items-center justify-center flex-shrink-0">
                                <i class="fas fa-check text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-bold mb-1">Visi Kami</h4>
                                <p class="text-gray-600">Menjadi pemimpin global dalam penyediaan batu bara berkualitas tinggi dengan komitmen terhadap keberlanjutan.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start space-x-4">
                            <div class="bg-amber-100 text-amber-600 w-12 h-12 rounded-full flex items-center justify-center flex-shrink-0">
                                <i class="fas fa-check text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-bold mb-1">Misi Kami</h4>
                                <p class="text-gray-600">Menyediakan produk berkualitas dengan layanan terbaik sambil mempertimbangkan dampak lingkungan dan sosial.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start space-x-4">
                            <div class="bg-amber-100 text-amber-600 w-12 h-12 rounded-full flex items-center justify-center flex-shrink-0">
                                <i class="fas fa-check text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-bold mb-1">Nilai Inti</h4>
                                <p class="text-gray-600">Integritas, Kualitas, Inovasi, dan Tanggung Jawab Sosial.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="py-16 bg-gray-900 text-white">
        <div class="container mx-auto px-6">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
                <div class="p-6">
                    <div class="text-4xl md:text-6xl font-bold gradient-text mb-2">
                        <span class="counter" data-target="15">0</span>+
                    </div>
                    <p class="text-gray-300">Negara Tujuan Ekspor</p>
                </div>
                <div class="p-6">
                    <div class="text-4xl md:text-6xl font-bold gradient-text mb-2">
                        <span class="counter" data-target="500">0</span>+
                    </div>
                    <p class="text-gray-300">Ribu Ton/Tahun</p>
                </div>
                <div class="p-6">
                    <div class="text-4xl md:text-6xl font-bold gradient-text mb-2">
                        <span class="counter" data-target="100">0</span>+
                    </div>
                    <p class="text-gray-300">Klien Tetap</p>
                </div>
                <div class="p-6">
                    <div class="text-4xl md:text-6xl font-bold gradient-text mb-2">
                        <span class="counter" data-target="12">0</span>+
                    </div>
                    <p class="text-gray-300">Tahun Pengalaman</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-20 bg-gray-100">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-5xl font-bold mb-4 gradient-text">Produk Kami</h2>
                <div class="w-24 h-1 bg-amber-500 mx-auto"></div>
                <p class="text-xl text-gray-600 mt-4 max-w-2xl mx-auto">Batu bara berkualitas tinggi untuk berbagai kebutuhan industri dengan spesifikasi yang tepat.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Product 1 -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transform transition hover:-translate-y-2 group">
                    <div class="relative overflow-hidden">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/bd1fb77a-d5ec-4ed6-b8b3-c805eb3fc680.png" alt="Batu bara kalori tinggi dengan tekstur mengkilap dan warna hitam pekat" class="w-full h-64 object-cover">
                        <div class="absolute inset-0 bg-gradient-to-t from-black to-transparent opacity-70"></div>
                        <div class="absolute bottom-0 left-0 p-6">
                            <h3 class="text-2xl font-bold text-white">High Caloric Coal</h3>
                        </div>
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-4">
                            <span class="text-amber-600 font-bold">GCV > 7000 kcal/kg</span>
                            <span class="bg-gray-200 px-3 py-1 rounded-full text-xs font-semibold">GAR Basis</span>
                        </div>
                        <div class="mb-4">
                            <ul class="space-y-2 text-gray-600">
                                <li class="flex items-start">
                                    <i class="fas fa-check text-amber-500 mr-2 mt-1"></i>
                                    <span>Total Moisture: < 14%</span>
                                </li>
                                <li class="flex items-start">
                                    <i class="fas fa-check text-amber-500 mr-2 mt-1"></i>
                                    <span>Ash Content: < 5%</span>
                                </li>
                                <li class="flex items-start">
                                    <i class="fas fa-check text-amber-500 mr-2 mt-1"></i>
                                    <span>Sulphur Content: < 0.8%</span>
                                </li>
                            </ul>
                        </div>
                        <div class="flex justify-between items-center mt-6">
                            <button class="text-amber-600 hover:text-amber-700 font-semibold transition">Detail Spesifikasi</button>
                            <button class="bg-amber-600 hover:bg-amber-700 text-white px-4 py-2 rounded-full text-sm font-semibold transition group-hover:scale-105">Minta Penawaran</button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transform transition hover:-translate-y-2 group">
                    <div class="relative overflow-hidden">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/29f76d82-3839-4c6f-b7fc-44614d9390cf.png" alt="Batu bara kalori sedang dengan tekstur kasar dan warna hitam kecoklatan" class="w-full h-64 object-cover">
                        <div class="absolute inset-0 bg-gradient-to-t from-black to-transparent opacity-70"></div>
                        <div class="absolute bottom-0 left-0 p-6">
                            <h3 class="text-2xl font-bold text-white">Medium Caloric Coal</h3>
                        </div>
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-4">
                            <span class="text-amber-600 font-bold">GCV 6000-6500 kcal/kg</span>
                            <span class="bg-gray-200 px-3 py-1 rounded-full text-xs font-semibold">GAR Basis</span>
                        </div>
                        <div class="mb-4">
                            <ul class="space-y-2 text-gray-600">
                                <li class="flex items-start">
                                    <i class="fas fa-check text-amber-500 mr-2 mt-1"></i>
                                    <span>Total Moisture: < 18%</span>
                                </li>
                                <li class="flex items-start">
                                    <i class="fas fa-check text-amber-500 mr-2 mt-1"></i>
                                    <span>Ash Content: < 8%</span>
                                </li>
                                <li class="flex items-start">
                                    <i class="fas fa-check text-amber-500 mr-2 mt-1"></i>
                                    <span>Sulphur Content: < 1%</span>
                                </li>
                            </ul>
                        </div>
                        <div class="flex justify-between items-center mt-6">
                            <button class="text-amber-600 hover:text-amber-700 font-semibold transition">Detail Spesifikasi</button>
                            <button class="bg-amber-600 hover:bg-amber-700 text-white px-4 py-2 rounded-full text-sm font-semibold transition group-hover:scale-105">Minta Penawaran</button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transform transition hover:-translate-y-2 group">
                    <div class="relative overflow-hidden">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/08fa84b0-b1e3-40a9-aa84-89abb6946f6d.png" alt="Batu bara rendah sulfur dengan tekstur halus dan warna hitam metalik" class="w-full h-64 object-cover">
                        <div class="absolute inset-0 bg-gradient-to-t from-black to-transparent opacity-70"></div>
                        <div class="absolute bottom-0 left-0 p-6">
                            <h3 class="text-2xl font-bold text-white">Low Sulphur Coal</h3>
                        </div>
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-4">
                            <span class="text-amber-600 font-bold">GCV > 5800 kcal/kg</span>
                            <span class="bg-gray-200 px-3 py-1 rounded-full text-xs font-semibold">GAR Basis</span>
                        </div>
                        <div class="mb-4">
                            <ul class="space-y-2 text-gray-600">
                                <li class="flex items-start">
                                    <i class="fas fa-check text-amber-500 mr-2 mt-1"></i>
                                    <span>Total Moisture: < 20%</span>
                                </li>
                                <li class="flex items-start">
                                    <i class="fas fa-check text-amber-500 mr-2 mt-1"></i>
                                    <span>Ash Content: < 10%</span>
                                </li>
                                <li class="flex items-start">
                                    <i class="fas fa-check text-amber-500 mr-2 mt-1"></i>
                                    <span>Sulphur Content: < 0.5%</span>
                                </li>
                            </ul>
                        </div>
                        <div class="flex justify-between items-center mt-6">
                            <button class="text-amber-600 hover:text-amber-700 font-semibold transition">Detail Spesifikasi</button>
                            <button class="bg-amber-600 hover:bg-amber-700 text-white px-4 py-2 rounded-full text-sm font-semibold transition group-hover:scale-105">Minta Penawaran</button>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-16">
                <button class="border-2 border-amber-600 text-amber-600 hover:bg-amber-600 hover:text-white px-8 py-3 rounded-full font-semibold transition">Lihat Semua Produk</button>
            </div>
        </div>
    </section>

    <!-- Process Section -->
    <section class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-5xl font-bold mb-4 gradient-text">Proses Bisnis Kami</h2>
                <div class="w-24 h-1 bg-amber-500 mx-auto"></div>
                <p class="text-xl text-gray-600 mt-4 max-w-2xl mx-auto">Proses terintegrasi dari penambangan hingga pengiriman ke pelanggan internasional</p>
            </div>
            
            <div class="relative">
                <!-- Process Line -->
                <div class="hidden md:block absolute left-1/2 top-1/2 transform -translate-y-1/2 -translate-x-1/2 h-2 bg-gray-200 w-5/6"></div>
                
                <!-- Process Steps -->
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <!-- Step 1 -->
                    <div class="flex flex-col items-center text-center">
                        <div class="bg-white border-4 border-amber-500 rounded-full w-24 h-24 flex items-center justify-center mb-4 relative z-10">
                            <i class="fas fa-mountain text-3xl 
