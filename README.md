`index.html`
```html
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
                            <i class="fas fa-mountain text-3xl text-amber-600"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Penambangan</h3>
                        <p class="text-gray-600">Penghasilan batu bara dari tambang-tambang pilihan di Kalimantan dengan standar penambangan bertanggung jawab.</p>
                    </div>
                    
                    <!-- Step 2 -->
                    <div class="flex flex-col items-center text-center">
                        <div class="bg-white border-4 border-amber-500 rounded-full w-24 h-24 flex items-center justify-center mb-4 relative z-10">
                            <i class="fas fa-filter text-3xl text-amber-600"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Pengolahan</h3>
                        <p class="text-gray-600">Proses penyortiran dan pencucian untuk memenuhi berbagai spesifikasi kualitas yang dibutuhkan.</p>
                    </div>
                    
                    <!-- Step 3 -->
                    <div class="flex flex-col items-center text-center">
                        <div class="bg-white border-4 border-amber-500 rounded-full w-24 h-24 flex items-center justify-center mb-4 relative z-10">
                            <i class="fas fa-balance-scale text-3xl text-amber-600"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Pengujian Kualitas</h3>
                        <p class="text-gray-600">Analisis laboratorium independen untuk memastikan kepatuhan terhadap spesifikasi.</p>
                    </div>
                    
                    <!-- Step 4 -->
                    <div class="flex flex-col items-center text-center">
                        <div class="bg-white border-4 border-amber-500 rounded-full w-24 h-24 flex items-center justify-center mb-4 relative z-10">
                            <i class="fas fa-truck text-3xl text-amber-600"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Transportasi</h3>
                        <p class="text-gray-600">Sistem logistik yang efisien ke pelabuhan-pelabuhan utama di Indonesia.</p>
                    </div>
                    
                    <!-- Step 5 -->
                    <div class="flex flex-col items-center text-center">
                        <div class="bg-white border-4 border-amber-500 rounded-full w-24 h-24 flex items-center justify-center mb-4 relative z-10">
                            <i class="fas fa-ship text-3xl text-amber-600"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Pengapalan</h3>
                        <p class="text-gray-600">Pengiriman internasional dengan kapal-kapal terpercaya dan dokumentasi lengkap.</p>
                    </div>
                    
                    <!-- Step 6 -->
                    <div class="flex flex-col items-center text-center">
                        <div class="bg-white border-4 border-amber-500 rounded-full w-24 h-24 flex items-center justify-center mb-4 relative z-10">
                            <i class="fas fa-check-circle text-3xl text-amber-600"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Penerimaan</h3>
                        <p class="text-gray-600">Pemeriksaan kualitas akhir oleh pelanggan dan penyelesaian transaksi.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="py-20 bg-gray-900 text-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-5xl font-bold mb-4 gradient-text">Testimonial Klien</h2>
                <div class="w-24 h-1 bg-amber-500 mx-auto"></div>
                <p class="text-xl text-gray-300 mt-4 max-w-2xl mx-auto">Apa kata pelanggan kami tentang kerja sama dengan PT Indo Jaya Aditama</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="bg-gray-800 rounded-xl p-8 transform transition hover:scale-105">
                    <div class="flex items-center mb-6">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/5d9306cd-128c-4405-bf3f-ef89ebe0f990.png" alt="Foto kepala Cabang Procurement perusahaan baja Jepang dengan ekspresi profesional" class="w-16 h-16 rounded-full mr-4">
                        <div>
                            <h4 class="font-bold">Yamada Hiroshi</h4>
                            <p class="text-gray-400 text-sm">General Manager, Steel Company Japan</p>
                        </div>
                    </div>
                    <p class="text-gray-300 italic">"Kami telah bekerja sama dengan PT Indo Jaya Aditama selama 5 tahun terakhir. Konsistensi kualitas dan ketepatan waktu pengiriman mereka sangat mengesankan."</p>
                    <div class="flex mt-4 text-amber-500">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="bg-gray-800 rounded-xl p-8 transform transition hover:scale-105">
                    <div class="flex items-center mb-6">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/814280c3-8bb8-49f1-b2d6-da7af3c52873.png" alt="Foto Direktur perusahaan energi India dengan latar belakang industri" class="w-16 h-16 rounded-full mr-4">
                        <div>
                            <h4 class="font-bold">Raj Patel</h4>
                            <p class="text-gray-400 text-sm">Director, Power Plant India</p>
                        </div>
                    </div>
                    <p class="text-gray-300 italic">"Dari semua pemasok batu bara Indonesia, PT Indo Jaya Aditama menunjukkan profesionalisme tertinggi. Layanan pelanggan mereka sangat responsif."</p>
                    <div class="flex mt-4 text-amber-500">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                    </div>
                </div>
                
                <!-- Testimonial 3 -->
                <div class="bg-gray-800 rounded-xl p-8 transform transition hover:scale-105">
                    <div class="flex items-center mb-6">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/da0c5a1a-71f9-4555-9b97-af2c66fe5c67.png" alt="Foto CEO perusahaan trading Cina dengan latar belakang perkotaan modern" class="w-16 h-16 rounded-full mr-4">
                        <div>
                            <h4 class="font-bold">Zhang Wei</h4>
                            <p class="text-gray-400 text-sm">CEO, Energy Trading China</p>
                        </div>
                    </div>
                    <p class="text-gray-300 italic">"Kami menghargai fleksibilitas PT Indo Jaya Aditama dalam memenuhi kebutuhan khusus kami. Dokumen-dokumen mereka selalu lengkap dan tepat waktu."</p>
                    <div class="flex mt-4 text-amber-500">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-5xl font-bold mb-4 gradient-text">Hubungi Kami</h2>
                <div class="w-24 h-1 bg-amber-500 mx-auto"></div>
                <p class="text-xl text-gray-600 mt-4 max-w-2xl mx-auto">Kami siap melayani kebutuhan batu bara internasional Anda</p>
            </div>
            
            <div class="flex flex-col md:flex-row">
                <!-- Contact Info -->
                <div class="md:w-1/2 mb-10 md:mb-0 md:pr-10">
                    <div class="bg-gray-100 p-8 rounded-xl shadow-md">
                        <h3 class="text-2xl font-bold mb-6">Informasi Kontak</h3>
                        
                        <div class="space-y-6">
                            <div class="flex items-start">
                                <div class="bg-amber-100 text-amber-600 w-12 h-12 rounded-full flex items-center justify-center flex-shrink-0">
                                    <i class="fas fa-map-marker-alt"></i>
                                </div>
                                <div class="ml-4">
                                    <h4 class="font-bold mb-1">Kantor Pusat</h4>
                                    <p class="text-gray-600">Plaza Kuningan Lt. 12, Jl. HR Rasuna Said Kav. C-17, Jakarta Selatan 12940, Indonesia</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="bg-amber-100 text-amber-600 w-12 h-12 rounded-full flex items-center justify-center flex-shrink-0">
                                    <i class="fas fa-phone-alt"></i>
                                </div>
                                <div class="ml-4">
                                    <h4 class="font-bold mb-1">Telepon</h4>
                                    <p class="text-gray-600">+62 21 5299 3548</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="bg-amber-100 text-amber-600 w-12 h-12 rounded-full flex items-center justify-center flex-shrink-0">
                                    <i class="fas fa-envelope"></i>
                                </div>
                                <div class="ml-4">
                                    <h4 class="font-bold mb-1">Email</h4>
                                    <p class="text-gray-600">marketing@indojayaaditama.co.id</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="bg-amber-100 text-amber-600 w-12 h-12 rounded-full flex items-center justify-center flex-shrink-0">
                                    <i class="fas fa-clock"></i>
                                </div>
                                <div class="ml-4">
                                    <h4 class="font-bold mb-1">Jam Kerja</h4>
                                    <p class="text-gray-600">Senin - Jumat: 08:00 - 17:00 WIB</p>
                                </div>
                            </div>
                        </div>
                        
                        <div class="mt-8">
                            <h4 class="font-bold mb-4">Follow Kami</h4>
                            <div class="flex space-x-4">
                                <a href="#" class="bg-gray-700 hover:bg-gray-900 text-white w-10 h-10 rounded-full flex items-center justify-center transition">
                                    <i class="fab fa-linkedin-in"></i>
                                </a>
                                <a href="#" class="bg-blue-600 hover:bg-blue-800 text-white w-10 h-10 rounded-full flex items-center justify-center transition">
                                    <i class="fab fa-facebook-f"></i>
                                </a>
                                <a href="#" class="bg-blue-400 hover:bg-blue-600 text-white w-10 h-10 rounded-full flex items-center justify-center transition">
                                    <i class="fab fa-twitter"></i>
                                </a>
                                <a href="#" class="bg-gray-900 hover:bg-gray-700 text-white w-10 h-10 rounded-full flex items-center justify-center transition">
                                    <i class="fab fa-instagram"></i>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Contact Form -->
                <div class="md:w-1/2">
                    <div class="bg-gray-100 p-8 rounded-xl shadow-md">
                        <h3 class="text-2xl font-bold mb-6">Kirim Pesan</h3>
                        <form>
                            <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
                                <div>
                                    <label for="name" class="block text-gray-700 font-medium mb-2">Nama Anda</label>
                                    <input type="text" id="name" name="name" class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-amber-500">
                                </div>
                                <div>
                                    <label for="company" class="block text-gray-700 font-medium mb-2">Perusahaan</label>
                                    <input type="text" id="company" name="company" class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-amber-500">
                                </div>
                                <div>
                                    <label for="email" class="block text-gray-700 font-medium mb-2">Email</label>
                                    <input type="email" id="email" name="email" class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-amber-500">
                                </div>
                                <div>
                                    <label for="phone" class="block text-gray-700 font-medium mb-2">Telepon</label>
                                    <input type="tel" id="phone" name="phone" class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-amber-500">
                                </div>
                            </div>
                            <div class="mb-6">
                                <label for="subject" class="block text-gray-700 font-medium mb-2">Subjek</label>
                                <input type="text" id="subject" name="subject" class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-amber-500">
                            </div>
                            <div class="mb-6">
                                <label for="message" class="block text-gray-700 font-medium mb-2">Pesan</label>
                                <textarea id="message" name="message" rows="5" class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-amber-500"></textarea>
                            </div>
                            <div class="mb-6">
                                <label class="inline-flex items-center">
                                    <input type="checkbox" class="text-amber-600 rounded border-gray-300 focus:ring-amber-500">
                                    <span class="ml-2 text-gray-700">Saya setuju dengan Kebijakan Privasi dan Syarat Penggunaan</span>
                                </label>
                            </div>
                            <div>
                                <button type="submit" class="bg-amber-600 hover:bg-amber-700 text-white px-8 py-4 rounded-full font-semibold transition w-full">Kirim Pesan</button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Map Section -->
    <div class="h-96 bg-gray-200">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3966.521260322283!2d106.82256135111558!3d-6.208262395484212!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69f42283789bc9%3A0x7c1c969391f27313!2sPlaza%20Kuningan!5e0!3m2!1sen!2sid!4v1625123456789!5m2!1sen!2sid" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </div>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white">
        <div class="container mx-auto px-6 py-12">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8 mb-8">
                <div>
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/09fe7fc7-0fb6-4415-9769-420e4289f5ba.png" alt="Logo PT Indo Jaya Aditama versi putih dengan tulisan lengkap" class="h-10 mb-4">
                    <p class="text-gray-400">PT Indo Jaya Aditama adalah perusahaan perdagangan batu bara internasional yang berkomitmen pada kualitas dan keberlanjutan.</p>
                </div>
                <div>
                    <h4 class="text-lg font-bold mb-4">Perusahaan</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-amber-500 transition">Tentang Kami</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-amber-500 transition">Visi & Misi</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-amber-500 transition">Manajemen</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-amber-500 transition">Penghargaan</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-bold mb-4">Produk</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-amber-500 transition">High Caloric Coal</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-amber-500 transition">Medium Caloric Coal</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-amber-500 transition">Low Sulphur Coal</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-amber-500 transition">Semua Produk</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-bold mb-4">Hubungi Kami</h4>
                    <ul class="space-y-2">
                        <li class="flex items-center">
                            <i class="fas fa-map-marker-alt text-amber-500 mr-2"></i>
                            <span class="text-gray-400">Plaza Kuningan Lt. 12, Jakarta</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-phone-alt text-amber-500 mr-2"></i>
                            <span class="text-gray-400">+62 21 5299 3548</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-envelope text-amber-500 mr-2"></i>
                            <span class="text-gray-400">marketing@indojayaaditama.co.id</span>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="border-t border-gray-800 pt-8 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-400 mb-4 md:mb-0">© 2023 PT Indo Jaya Aditama. All Rights Reserved.</p>
                <div class="flex space-x-6">
                    <a href="#" class="text-gray-400 hover:text-amber-500 transition">Kebijakan Privasi</a>
                    <a href="#" class="text-gray-400 hover:text-amber-500 transition">Syarat Penggunaan</a>
                    <a href="#" class="text-gray-400 hover:text-amber-500 transition">Site Map</a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Back to Top Button -->
    <button id="backToTop" class="fixed bottom-8 right-8 bg-amber-600 text-white w-12 h-12 rounded-full flex items-center justify-center shadow-lg transition opacity-0 invisible hover:bg-amber-700">
        <i class="fas fa-arrow-up"></i>
    </button>

    <script>
        // Coal particles animation
        function createCoalParticles() {
            const container = document.getElementById('coal-particles');
            const particleCount = 30;
            
            for (let i = 0; i < particleCount; i++) {
                const particle = document.createElement('div');
                particle.className = 'coal-particle';
                
                // Random size between 2px and 6px
                const size = Math.random() * 4 + 2;
                particle.style.width = `${size}px`;
                particle.style.height = `${size}px`;
                
                // Random position
                particle.style.left = `${Math.random() * 100}%`;
                particle.style.top = `${Math.random() * 100}%`;
                
                // Random animation
                const duration = Math.random() * 5 + 5;
                const delay = Math.random() * 5;
                particle.style.animation = `float ${duration}s ease-in-out ${delay}s infinite`;
                
                container.appendChild(particle);
            }
        }
        
        // Counter animation
        function animateCounters() {
            const counters = document.querySelectorAll('.counter');
            const speed = 200;
            
            counters.forEach(counter => {
                const target = +counter.getAttribute('data-target');
                const count = +counter.innerText;
                
                if (count < target) {
                    counter.innerText = Math.ceil(count + (target / speed));
                    setTimeout(animateCounters, 1);
                } else {
                    counter.innerText = target;
                }
            });
        }
        
        // Back to top button
        window.addEventListener('scroll', function() {
            const backToTopBtn = document.getElementById('backToTop');
            if (window.pageYOffset > 300) {
                backToTopBtn.classList.remove('opacity-0', 'invisible');
                backToTopBtn.classList.add('opacity-100', 'visible');
            } else {
                backToTopBtn.classList.remove('opacity-100', 'visible');
                backToTopBtn.classList.add('opacity-0', 'invisible');
            }
        });
        
        document.getElementById('backToTop').addEventListener('click', function() {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });
        
        // Initialize animations when page loads
        window.addEventListener('DOMContentLoaded', function() {
            createCoalParticles();
            
            // Initialize counter animation when scrolled to stats section
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        animateCounters();
                        observer.unobserve(entry.target);
                    }
                });
            }, { threshold: 0.5 });
            
            const statsSection = document.querySelector('.bg-gray-900');
            if (statsSection) {
                observer.observe(statsSection);
            }
        });
    </script>
</body>
</html>

```

`index.html`
```html
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
                            <i class="fas fa-mountain text-3xl text-amber-600"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Penambangan</h3>
                        <p class="text-gray-600">Penghasilan batu bara dari tambang-tambang pilihan di Kalimantan dengan standar penambangan bertanggung jawab.</p>
                    </div>
                    
                    <!-- Step 2 -->
                    <div class="flex flex-col items-center text-center">
                        <div class="bg-white border-4 border-amber-500 rounded-full w-24 h-24 flex items-center justify-center mb-4 relative z-10">
                            <i class="fas fa-filter text-3xl text-amber-600"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Pengolahan</h3>
                        <p class="text-gray-600">Proses penyortiran dan pencucian untuk memenuhi berbagai spesifikasi kualitas yang dibutuhkan.</p>
                    </div>
                    
                    <!-- Step 3 -->
                    <div class="flex flex-col items-center text-center">
                        <div class="bg-white border-4 border-amber-500 rounded-full w-24 h-24 flex items-center justify-center mb-4 relative z-10">
                            <i class="fas fa-balance-scale text-3xl text-amber-600"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Pengujian Kualitas</h3>
                        <p class="text-gray-600">Analisis laboratorium independen untuk memastikan kepatuhan terhadap spesifikasi.</p>
                    </div>
                    
                    <!-- Step 4 -->
                    <div class="flex flex-col items-center text-center">
                        <div class="bg-white border-4 border-amber-500 rounded-full w-24 h-24 flex items-center justify-center mb-4 relative z-10">
                            <i class="fas fa-truck text-3xl text-amber-600"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Transportasi</h3>
                        <p class="text-gray-600">Sistem logistik yang efisien ke pelabuhan-pelabuhan utama di Indonesia.</p>
                    </div>
                    
                    <!-- Step 5 -->
                    <div class="flex flex-col items-center text-center">
                        <div class="bg-white border-4 border-amber-500 rounded-full w-24 h-24 flex items-center justify-center mb-4 relative z-10">
                            <i class="fas fa-ship text-3xl text-amber-600"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Pengapalan</h3>
                        <p class="text-gray-600">Pengiriman internasional dengan kapal-kapal terpercaya dan dokumentasi lengkap.</p>
                    </div>
                    
                    <!-- Step 6 -->
                    <div class="flex flex-col items-center text-center">
                        <div class="bg-white border-4 border-amber-500 rounded-full w-24 h-24 flex items-center justify-center mb-4 relative z-10">
                            <i class="fas fa-check-circle text-3xl text-amber-600"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Penerimaan</h3>
                        <p class="text-gray-600">Pemeriksaan kualitas akhir oleh pelanggan dan penyelesaian transaksi.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="py-20 bg-gray-900 text-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-5xl font-bold mb-4 gradient-text">Testimonial Klien</h2>
                <div class="w-24 h-1 bg-amber-500 mx-auto"></div>
                <p class="text-xl text-gray-300 mt-4 max-w-2xl mx-auto">Apa kata pelanggan kami tentang kerja sama dengan PT Indo Jaya Aditama</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="bg-gray-800 rounded-xl p-8 transform transition hover:scale-105">
                    <div class="flex items-center mb-6">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/5d9306cd-128c-4405-bf3f-ef89ebe0f990.png" alt="Foto kepala Cabang Procurement perusahaan baja Jepang dengan ekspresi profesional" class="w-16 h-16 rounded-full mr-4">
                        <div>
                            <h4 class="font-bold">Yamada Hiroshi</h4>
                            <p class="text-gray-400 text-sm">General Manager, Steel Company Japan</p>
                        </div>
                    </div>
                    <p class="text-gray-300 italic">"Kami telah bekerja sama dengan PT Indo Jaya Aditama selama 5 tahun terakhir. Konsistensi kualitas dan ketepatan waktu pengiriman mereka sangat mengesankan."</p>
                    <div class="flex mt-4 text-amber-500">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="bg-gray-800 rounded-xl p-8 transform transition hover:scale-105">
                    <div class="flex items-center mb-6">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/814280c3-8bb8-49f1-b2d6-da7af3c52873.png" alt="Foto Direktur perusahaan energi India dengan latar belakang industri" class="w-16 h-16 rounded-full mr-4">
                        <div>
                            <h4 class="font-bold">Raj Patel</h4>
                            <p class="text-gray-400 text-sm">Director, Power Plant India</p>
                        </div>
                    </div>
                    <p class="text-gray-300 italic">"Dari semua pemasok batu bara Indonesia, PT Indo Jaya Aditama menunjukkan profesionalisme tertinggi. Layanan pelanggan mereka sangat responsif."</p>
                    <div class="flex mt-4 text-amber-500">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                    </div>
                </div>
                
                <!-- Testimonial 3 -->
                <div class="bg-gray-800 rounded-xl p-8 transform transition hover:scale-105">
                    <div class="flex items-center mb-6">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/da0c5a1a-71f9-4555-9b97-af2c66fe5c67.png" alt="Foto CEO perusahaan trading Cina dengan latar belakang perkotaan modern" class="w-16 h-16 rounded-full mr-4">
                        <div>
                            <h4 class="font-bold">Zhang Wei</h4>
                            <p class="text-gray-400 text-sm">CEO, Energy Trading China</p>
                        </div>
                    </div>
                    <p class="text-gray-300 italic">"Kami menghargai fleksibilitas PT Indo Jaya Aditama dalam memenuhi kebutuhan khusus kami. Dokumen-dokumen mereka selalu lengkap dan tepat waktu."</p>
                    <div class="flex mt-4 text-amber-500">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-5xl font-bold mb-4 gradient-text">Hubungi Kami</h2>
                <div class="w-24 h-1 bg-amber-500 mx-auto"></div>
                <p class="text-xl text-gray-600 mt-4 max-w-2xl mx-auto">Kami siap melayani kebutuhan batu bara internasional Anda</p>
            </div>
            
            <div class="flex flex-col md:flex-row">
                <!-- Contact Info -->
                <div class="md:w-1/2 mb-10 md:mb-0 md:pr-10">
                    <div class="bg-gray-100 p-8 rounded-xl shadow-md">
                        <h3 class="text-2xl font-bold mb-6">Informasi Kontak</h3>
                        
                        <div class="space-y-6">
                            <div class="flex items-start">
                                <div class="bg-amber-100 text-amber-600 w-12 h-12 rounded-full flex items-center justify-center flex-shrink-0">
                                    <i class="fas fa-map-marker-alt"></i>
                                </div>
                                <div class="ml-4">
                                    <h4 class="font-bold mb-1">Kantor Pusat</h4>
                                    <p class="text-gray-600">Plaza Kuningan Lt. 12, Jl. HR Rasuna Said Kav. C-17, Jakarta Selatan 12940, Indonesia</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="bg-amber-100 text-amber-600 w-12 h-12 rounded-full flex items-center justify-center flex-shrink-0">
                                    <i class="fas fa-phone-alt"></i>
                                </div>
                                <div class="ml-4">
                                    <h4 class="font-bold mb-1">Telepon</h4>
                                    <p class="text-gray-600">+62 21 5299 3548</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="bg-amber-100 text-amber-600 w-12 h-12 rounded-full flex items-center justify-center flex-shrink-0">
                                    <i class="fas fa-envelope"></i>
                                </div>
                                <div class="ml-4">
                                    <h4 class="font-bold mb-1">Email</h4>
                                    <p class="text-gray-600">marketing@indojayaaditama.co.id</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="bg-amber-100 text-amber-600 w-12 h-12 rounded-full flex items-center justify-center flex-shrink-0">
                                    <i class="fas fa-clock"></i>
                                </div>
                                <div class="ml-4">
                                    <h4 class="font-bold mb-1">Jam Kerja</h4>
                                    <p class="text-gray-600">Senin - Jumat: 08:00 - 17:00 WIB</p>
                                </div>
                            </div>
                        </div>
                        
                        <div class="mt-8">
                            <h4 class="font-bold mb-4">Follow Kami</h4>
                            <div class="flex space-x-4">
                                <a href="#" class="bg-gray-700 hover:bg-gray-900 text-white w-10 h-10 rounded-full flex items-center justify-center transition">
                                    <i class="fab fa-linkedin-in"></i>
                                </a>
                                <a href="#" class="bg-blue-600 hover:bg-blue-800 text-white w-10 h-10 rounded-full flex items-center justify-center transition">
                                    <i class="fab fa-facebook-f"></i>
                                </a>
                                <a href="#" class="bg-blue-400 hover:bg-blue-600 text-white w-10 h-10 rounded-full flex items-center justify-center transition">
                                    <i class="fab fa-twitter"></i>
                                </a>
                                <a href="#" class="bg-gray-900 hover:bg-gray-700 text-white w-10 h-10 rounded-full flex items-center justify-center transition">
                                    <i class="fab fa-instagram"></i>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Contact Form -->
                <div class="md:w-1/2">
                    <div class="bg-gray-100 p-8 rounded-xl shadow-md">
                        <h3 class="text-2xl font-bold mb-6">Kirim Pesan</h3>
                        <form>
                            <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
                                <div>
                                    <label for="name" class="block text-gray-700 font-medium mb-2">Nama Anda</label>
                                    <input type="text" id="name" name="name" class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-amber-500">
                                </div>
                                <div>
                                    <label for="company" class="block text-gray-700 font-medium mb-2">Perusahaan</label>
                                    <input type="text" id="company" name="company" class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-amber-500">
                                </div>
                                <div>
                                    <label for="email" class="block text-gray-700 font-medium mb-2">Email</label>
                                    <input type="email" id="email" name="email" class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-amber-500">
                                </div>
                                <div>
                                    <label for="phone" class="block text-gray-700 font-medium mb-2">Telepon</label>
                                    <input type="tel" id="phone" name="phone" class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-amber-500">
                                </div>
                            </div>
                            <div class="mb-6">
                                <label for="subject" class="block text-gray-700 font-medium mb-2">Subjek</label>
                                <input type="text" id="subject" name="subject" class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-amber-500">
                            </div>
                            <div class="mb-6">
                                <label for="message" class="block text-gray-700 font-medium mb-2">Pesan</label>
                                <textarea id="message" name="message" rows="5" class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-amber-500"></textarea>
                            </div>
                            <div class="mb-6">
                                <label class="inline-flex items-center">
                                    <input type="checkbox" class="text-amber-600 rounded border-gray-300 focus:ring-amber-500">
                                    <span class="ml-2 text-gray-700">Saya setuju dengan Kebijakan Privasi dan Syarat Penggunaan</span>
                                </label>
                            </div>
                            <div>
                                <button type="submit" class="bg-amber-600 hover:bg-amber-700 text-white px-8 py-4 rounded-full font-semibold transition w-full">Kirim Pesan</button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Map Section -->
    <div class="h-96 bg-gray-200">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3966.521260322283!2d106.82256135111558!3d-6.208262395484212!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69f42283789bc9%3A0x7c1c969391f27313!2sPlaza%20Kuningan!5e0!3m2!1sen!2sid!4v1625123456789!5m2!1sen!2sid" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </div>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white">
        <div class="container mx-auto px-6 py-12">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8 mb-8">
                <div>
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/09fe7fc7-0fb6-4415-9769-420e4289f5ba.png" alt="Logo PT Indo Jaya Aditama versi putih dengan tulisan lengkap" class="h-10 mb-4">
                    <p class="text-gray-400">PT Indo Jaya Aditama adalah perusahaan perdagangan batu bara internasional yang berkomitmen pada kualitas dan keberlanjutan.</p>
                </div>
                <div>
                    <h4 class="text-lg font-bold mb-4">Perusahaan</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-amber-500 transition">Tentang Kami</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-amber-500 transition">Visi & Misi</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-amber-500 transition">Manajemen</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-amber-500 transition">Penghargaan</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-bold mb-4">Produk</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-amber-500 transition">High Caloric Coal</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-amber-500 transition">Medium Caloric Coal</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-amber-500 transition">Low Sulphur Coal</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-amber-500 transition">Semua Produk</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-bold mb-4">Hubungi Kami</h4>
                    <ul class="space-y-2">
                        <li class="flex items-center">
                            <i class="fas fa-map-marker-alt text-amber-500 mr-2"></i>
                            <span class="text-gray-400">Plaza Kuningan Lt. 12, Jakarta</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-phone-alt text-amber-500 mr-2"></i>
                            <span class="text-gray-400">+62 21 5299 3548</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-envelope text-amber-500 mr-2"></i>
                            <span class="text-gray-400">marketing@indojayaaditama.co.id</span>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="border-t border-gray-800 pt-8 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-400 mb-4 md:mb-0">© 2023 PT Indo Jaya Aditama. All Rights Reserved.</p>
                <div class="flex space-x-6">
                    <a href="#" class="text-gray-400 hover:text-amber-500 transition">Kebijakan Privasi</a>
                    <a href="#" class="text-gray-400 hover:text-amber-500 transition">Syarat Penggunaan</a>
                    <a href="#" class="text-gray-400 hover:text-amber-500 transition">Site Map</a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Back to Top Button -->
    <button id="backToTop" class="fixed bottom-8 right-8 bg-amber-600 text-white w-12 h-12 rounded-full flex items-center justify-center shadow-lg transition opacity-0 invisible hover:bg-amber-700">
        <i class="fas fa-arrow-up"></i>
    </button>

    <script>
        // Coal particles animation
        function createCoalParticles() {
            const container = document.getElementById('coal-particles');
            const particleCount = 30;
            
            for (let i = 0; i < particleCount; i++) {
                const particle = document.createElement('div');
                particle.className = 'coal-particle';
                
                // Random size between 2px and 6px
                const size = Math.random() * 4 + 2;
                particle.style.width = `${size}px`;
                particle.style.height = `${size}px`;
                
                // Random position
                particle.style.left = `${Math.random() * 100}%`;
                particle.style.top = `${Math.random() * 100}%`;
                
                // Random animation
                const duration = Math.random() * 5 + 5;
                const delay = Math.random() * 5;
                particle.style.animation = `float ${duration}s ease-in-out ${delay}s infinite`;
                
                container.appendChild(particle);
            }
        }
        
        // Counter animation
        function animateCounters() {
            const counters = document.querySelectorAll('.counter');
            const speed = 200;
            
            counters.forEach(counter => {
                const target = +counter.getAttribute('data-target');
                const count = +counter.innerText;
                
                if (count < target) {
                    counter.innerText = Math.ceil(count + (target / speed));
                    setTimeout(animateCounters, 1);
                } else {
                    counter.innerText = target;
                }
            });
        }
        
        // Back to top button
        window.addEventListener('scroll', function() {
            const backToTopBtn = document.getElementById('backToTop');
            if (window.pageYOffset > 300) {
                backToTopBtn.classList.remove('opacity-0', 'invisible');
                backToTopBtn.classList.add('opacity-100', 'visible');
            } else {
                backToTopBtn.classList.remove('opacity-100', 'visible');
                backToTopBtn.classList.add('opacity-0', 'invisible');
            }
        });
        
        document.getElementById('backToTop').addEventListener('click', function() {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });
        
        // Initialize animations when page loads
        window.addEventListener('DOMContentLoaded', function() {
            createCoalParticles();
            
            // Initialize counter animation when scrolled to stats section
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        animateCounters();
                        observer.unobserve(entry.target);
                    }
                });
            }, { threshold: 0.5 });
            
            const statsSection = document.querySelector('.bg-gray-900');
            if (statsSection) {
                observer.observe(statsSection);
            }
        });
    </script>
</body>
</html>

```

