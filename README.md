<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UPT Puskesmas Batu Horpak</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f0f2f5;
        }
        .text-shadow-light {
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800">

    <!-- Header -->
    <header class="bg-blue-700 text-white shadow-lg">
        <nav class="container mx-auto px-4 py-4 flex flex-col md:flex-row justify-between items-center">
            <div class="flex items-center space-x-3 mb-4 md:mb-0">
                <!-- Placeholder for logo. You can replace this with your actual logo URL -->
                <img src="c:\Users\ASUS\Documents\upt\Gemini_Generated_Image_1nzdos1nzdos1nzd.png" alt="c:\Users\ASUS\Documents\upt\Gemini_Generated_Image_1nzdos1nzdos1nzd.png" class="w-16 h-16 rounded-full border-2 border-white">
                <h1 class="text-3xl font-bold">UPT Puskesmas Batu Horpak</h1>
            </div>
            <ul class="flex flex-wrap justify-center space-x-6">
                <li><a href="#beranda" class="hover:text-blue-200 text-lg font-medium transition duration-300 ease-in-out py-2 px-3 rounded-md hover:bg-blue-600">Beranda</a></li>
                <li><a href="#tentang-kami" class="hover:text-blue-200 text-lg font-medium transition duration-300 ease-in-out py-2 px-3 rounded-md hover:bg-blue-600">Tentang Kami</a></li>
                <li><a href="#layanan" class="hover:text-blue-200 text-lg font-medium transition duration-300 ease-in-out py-2 px-3 rounded-md hover:bg-blue-600">Layanan</a></li>
                <li><a href="#galeri" class="hover:text-blue-200 text-lg font-medium transition duration-300 ease-in-out py-2 px-3 rounded-md hover:bg-blue-600">Galeri</a></li>
                <li><a href="#kontak" class="hover:text-blue-200 text-lg font-medium transition duration-300 ease-in-out py-2 px-3 rounded-md hover:bg-blue-600">Kontak</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section (Beranda) -->
    <section id="beranda" class="relative bg-gradient-to-r from-blue-600 to-blue-800 text-white py-20 md:py-32 flex items-center justify-center min-h-screen-75 overflow-hidden">
        <div class="absolute inset-0 bg-cover bg-center opacity-30" style="background-image: url('https://placehold.co/1920x1080/0A2342/FFFFFF?text=Puskesmas+Depan');"></div>
        <div class="container mx-auto px-4 text-center relative z-10">
            <h2 class="text-5xl md:text-7xl font-extrabold mb-6 text-shadow-light">Selamat Datang di UPT Puskesmas Batu Horpak</h2>
            <p class="text-xl md:text-2xl mb-8 leading-relaxed">Melayani dengan Sepenuh Hati untuk Kesehatan Masyarakat yang Lebih Baik</p>
            <a href="#layanan" class="bg-white text-blue-700 hover:bg-gray-200 px-8 py-4 rounded-full text-lg font-semibold shadow-lg hover:shadow-xl transition duration-300 ease-in-out transform hover:scale-105">Lihat Layanan Kami</a>
        </div>
    </section>

    <!-- About Us Section (Tentang Kami) -->
    <section id="tentang-kami" class="py-16 md:py-24 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-12 text-blue-700">Tentang Kami</h2>
            <div class="flex flex-col md:flex-row items-center md:space-x-12">
                <div class="md:w-1/2 mb-8 md:mb-0">
                    <img src="c:\Users\ASUS\Pictures\pkm\480420828_603202762591671_7768024684632327180_n.jpg" alt="Tim Puskesmas" class="rounded-lg shadow-lg w-full h-auto object-cover">
                </div>
                <div class="md:w-1/2 text-lg leading-relaxed text-gray-700">
                    <p class="mb-6">UPT Puskesmas Batu Horpak berkomitmen untuk memberikan pelayanan kesehatan yang prima dan merata bagi seluruh lapisan masyarakat. Kami berupaya meningkatkan derajat kesehatan melalui berbagai program promotif, preventif, kuratif, dan rehabilitatif.</p>
                    <p class="mb-6">Dengan didukung oleh tenaga medis profesional dan fasilitas yang memadai, kami siap menjadi mitra terdepan dalam menjaga kesehatan keluarga Anda. Visi kami adalah terwujudnya masyarakat yang sehat dan mandiri.</p>
                    <p>Misi kami meliputi peningkatan kualitas pelayanan, pemberdayaan masyarakat, dan penciptaan lingkungan sehat.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section (Layanan) -->
    <section id="layanan" class="py-16 md:py-24 bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-12 text-blue-700">Layanan Kami</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Service Card 1 -->
                <div class="bg-white rounded-lg shadow-md p-8 text-center transition duration-300 ease-in-out hover:shadow-xl hover:scale-105">
                    <div class="text-blue-500 mb-4">
                        <svg class="w-16 h-16 mx-auto" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm-1-13h2v6h-2zm0 8h2v2h-2z"/>
                        </svg>
                    </div>
                    <h3 class="text-2xl font-semibold mb-4 text-gray-900">Pemeriksaan Umum</h3>
                    <p class="text-gray-600">Pelayanan pemeriksaan kesehatan dasar dan konsultasi medis oleh dokter umum yang berpengalaman.</p>
                </div>
                <!-- Service Card 2 -->
                <div class="bg-white rounded-lg shadow-md p-8 text-center transition duration-300 ease-in-out hover:shadow-xl hover:scale-105">
                    <div class="text-green-500 mb-4">
                        <svg class="w-16 h-16 mx-auto" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M12 2c-4.97 0-9 4.03-9 9 0 3.73 2.37 6.94 5.67 8.32L12 22l4.33-2.68C18.63 17.94 21 14.73 21 11c0-4.97-4.03-9-9-9zm0 16.5c-3.03 0-5.5-2.47-5.5-5.5s2.47-5.5 5.5-5.5 5.5 2.47 5.5 5.5-2.47 5.5-5.5 5.5zm.5-9H11v5h1.5zm0-2h-1.5v-1.5h1.5z"/>
                        </svg>
                    </div>
                    <h3 class="text-2xl font-semibold mb-4 text-gray-900">Kesehatan Ibu & Anak</h3>
                    <p class="text-gray-600">Layanan antenatal, imunisasi anak, pemeriksaan pasca-melahirkan, dan konsultasi gizi.</p>
                </div>
                <!-- Service Card 3 -->
                <div class="bg-white rounded-lg shadow-md p-8 text-center transition duration-300 ease-in-out hover:shadow-xl hover:scale-105">
                    <div class="text-yellow-500 mb-4">
                        <svg class="w-16 h-16 mx-auto" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M12 11.5c.83 0 1.5-.67 1.5-1.5s-.67-1.5-1.5-1.5-1.5.67-1.5 1.5.67 1.5 1.5 1.5zM12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm0-10c-2.03 0-3.8-.93-5-2.38V17h10v-7.38c-1.2.45-2.97.38-5 0z"/>
                        </svg>
                    </div>
                    <h3 class="text-2xl font-semibold mb-4 text-gray-900">Pelayanan Vaksinasi</h3>
                    <p class="text-gray-600">Jadwal vaksinasi lengkap untuk anak-anak dan dewasa sesuai standar kesehatan nasional.</p>
                </div>
                <!-- Service Card 4 -->
                <div class="bg-white rounded-lg shadow-md p-8 text-center transition duration-300 ease-in-out hover:shadow-xl hover:scale-105">
                    <div class="text-red-500 mb-4">
                        <svg class="w-16 h-16 mx-auto" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 15.5V13h2v4.5zm0-6V7h2v4.5z"/>
                        </svg>
                    </div>
                    <h3 class="text-2xl font-semibold mb-4 text-gray-900">Gawat Darurat</h3>
                    <p class="text-gray-600">Pelayanan kegawatdaruratan medis dengan respons cepat untuk penanganan kasus darurat.</p>
                </div>
                <!-- Service Card 5 -->
                <div class="bg-white rounded-lg shadow-md p-8 text-center transition duration-300 ease-in-out hover:shadow-xl hover:scale-105">
                    <div class="text-purple-500 mb-4">
                        <svg class="w-16 h-16 mx-auto" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm-1-10h2v4h-2zm0-2h2v2h-2z"/>
                        </svg>
                    </div>
                    <h3 class="text-2xl font-semibold mb-4 text-gray-900">Laboratorium</h3>
                    <p class="text-gray-600">Fasilitas laboratorium lengkap untuk berbagai pemeriksaan diagnostik medis.</p>
                </div>
                <!-- Service Card 6 -->
                <div class="bg-white rounded-lg shadow-md p-8 text-center transition duration-300 ease-in-out hover:shadow-xl hover:scale-105">
                    <div class="text-orange-500 mb-4">
                        <svg class="w-16 h-16 mx-auto" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15h4v-2h-4v2zm0-4h4v-2h-4v2zm0-4h4V7h-4v2z"/>
                        </svg>
                    </div>
                    <h3 class="text-2xl font-semibold mb-4 text-gray-900">Farmasi</h3>
                    <p class="text-gray-600">Penyediaan obat-obatan esensial dan konsultasi apoteker untuk penggunaan yang benar.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Gallery Section (Galeri) -->
    <section id="galeri" class="py-16 md:py-24 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-12 text-blue-700">Galeri Kegiatan Kami</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Gallery Item 1 -->
                <div class="relative overflow-hidden rounded-lg shadow-lg group">
                    <img src="c:\Users\ASUS\Pictures\pkm\480886891_609874548591159_2558481219378004471_n.jpg" alt="Kegiatan Puskesmas 1" class="w-full h-64 object-cover transform transition duration-500 ease-in-out group-hover:scale-110">
                    <div class="absolute inset-0 bg-black bg-opacity-40 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-xl font-semibold">Edukasi Kesehatan</p>
                    </div>
                </div>
                <!-- Gallery Item 2 -->
                <div class="relative overflow-hidden rounded-lg shadow-lg group">
                    <img src="c:\Users\ASUS\Pictures\pkm\480665473_603192942592653_3349037202736735458_n.jpg" alt="Kegiatan Puskesmas 2" class="w-full h-64 object-cover transform transition duration-500 ease-in-out group-hover:scale-110">
                    <div class="absolute inset-0 bg-black bg-opacity-40 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-xl font-semibold">Vaksinasi Massal</p>
                    </div>
                </div>
                <!-- Gallery Item 3 -->
                <div class="relative overflow-hidden rounded-lg shadow-lg group">
                    <img src="c:\Users\ASUS\Pictures\pkm\497813661_669147019330578_6249055683616796474_n.jpg" alt="Kegiatan Puskesmas 3" class="w-full h-64 object-cover transform transition duration-500 ease-in-out group-hover:scale-110">
                    <div class="absolute inset-0 bg-black bg-opacity-40 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-xl font-semibold">Penyuluhan Gizi</p>
                    </div>
                </div>
                <!-- Gallery Item 4 -->
                <div class="relative overflow-hidden rounded-lg shadow-lg group">
                    <img src="c:\Users\ASUS\Pictures\pkm\481702637_615827947995819_4747443648754871247_n.jpg" alt="Kegiatan Puskesmas 4" class="w-full h-64 object-cover transform transition duration-500 ease-in-out group-hover:scale-110">
                    <div class="absolute inset-0 bg-black bg-opacity-40 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-xl font-semibold">Senam Sehat</p>
                    </div>
                </div>
                <!-- Gallery Item 5 -->
                <div class="relative overflow-hidden rounded-lg shadow-lg group">
                    <img src="c:\Users\ASUS\Pictures\pkm\480793986_609874091924538_3980657809515763440_n.jpg" alt="Kegiatan Puskesmas 5" class="w-full h-64 object-cover transform transition duration-500 ease-in-out group-hover:scale-110">
                    <div class="absolute inset-0 bg-black bg-opacity-40 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-xl font-semibold">Posyandu</p>
                    </div>
                </div>
                <!-- Gallery Item 6 -->
                <div class="relative overflow-hidden rounded-lg shadow-lg group">
                    <img src="c:\Users\ASUS\Pictures\pkm\481087928_603896592522288_8200061877437248591_n.jpg" alt="Kegiatan Puskesmas 6" class="w-full h-64 object-cover transform transition duration-500 ease-in-out group-hover:scale-110">
                    <div class="absolute inset-0 bg-black bg-opacity-40 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-xl font-semibold">Pemeriksaan Gratis</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section (Kontak) -->
    <section id="kontak" class="py-16 md:py-24 bg-gray-800 text-white">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-4xl font-bold mb-12 text-blue-300">Hubungi Kami</h2>
            <div class="max-w-3xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-8 text-lg">
                <div class="bg-gray-700 p-8 rounded-lg shadow-md">
                    <h3 class="text-2xl font-semibold mb-4 text-white">Informasi Kontak</h3>
                    <p class="mb-2"><strong class="text-blue-300">Alamat:</strong> Desa Batu horpak kec.Tantom Angkola, Tapsel, Sumatera Utara(22774)</p>
                    <p class="mb-2"><strong class="text-blue-300">Telepon:</strong> (0630)0852-7506-8796</p>
                    <p class="mb-2"><strong class="text-blue-300">Email:</strong> uptpuskesmasbatuhorpak@gmail.com</p>
                    <p><strong class="text-blue-300">Jam Operasional:</strong> Senin - Sabtu, 08.00 - 14.00 WIB</p>
                </div>
                <div class="bg-gray-700 p-8 rounded-lg shadow-md">
                    <h3 class="text-2xl font-semibold mb-4 text-white">Kirim Pesan</h3>
                    <form>
                        <div class="mb-4">
                            <input type="text" placeholder="Nama Lengkap" class="w-full p-3 rounded-md bg-gray-600 border border-gray-500 text-white focus:outline-none focus:ring-2 focus:ring-blue-500">
                        </div>
                        <div class="mb-4">
                            <input type="email" placeholder="Email Anda" class="w-full p-3 rounded-md bg-gray-600 border border-gray-500 text-white focus:outline-none focus:ring-2 focus:ring-blue-500">
                        </div>
                        <div class="mb-4">
                            <textarea placeholder="Pesan Anda" rows="5" class="w-full p-3 rounded-md bg-gray-600 border border-gray-500 text-white focus:outline-none focus:ring-2 focus:ring-blue-500"></textarea>
                        </div>
                        <button type="submit" class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-6 rounded-full shadow-lg transition duration-300 ease-in-out transform hover:scale-105">Kirim Pesan</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-blue-900 text-white py-8">
        <div class="container mx-auto px-4 text-center">
            <p>&copy; 2023 UPT Puskesmas Batu Horpak. Hak Cipta Dilindungi Undang-Undang.</p>
            <div class="flex justify-center space-x-6 mt-4">
                <a href="#" class="hover:text-blue-300 transition duration-300 ease-in-out">Kebijakan Privasi</a>
                <span class="text-gray-500">|</span>
                <a href="#" class="hover:text-blue-300 transition duration-300 ease-in-out">Syarat & Ketentuan</a>
            </div>
        </div>
    </footer>

</body>
</html>
