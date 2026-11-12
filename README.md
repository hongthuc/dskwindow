<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH MỘT THÀNH VIÊN ĐSK WINDOW - dskwindow.com | Cửa Nhôm Xingfa & Nhôm Kính Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH MỘT THÀNH VIÊN ĐSK WINDOW (dskwindow.com) chuyên thiết kế, sản xuất, thi công Cửa nhôm Xingfa, Cửa nhựa lõi thép, Cửa kính cường lực, Cầu thang kính, Phòng tắm kính tại 04 Nguyễn Đình Tứ, Phường An Khê, TP Đà Nẵng. Hotline: 0907.228.282">
    
    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://dskwindow.com/">
    <meta property="og:title" content="CÔNG TY TNHH MỘT THÀNH VIÊN ĐSK WINDOW - dskwindow.com">
    <meta property="og:description" content="Chuyên thi công Cửa Nhôm Xingfa, Cửa Kính Cường Lực, Cửa Nhựa Lõi Thép, Cầu Thang Kính, Phòng Tắm Kính uy tín tại Đà Nẵng. Địa chỉ: 04 Nguyễn Đình Tứ, P. An Khê, TP Đà Nẵng - ĐT: 0907.228.282">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1C_epiUnuYdo1ulRK6agWfUA_Qudc3H8o">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1C_epiUnuYdo1ulRK6agWfUA_Qudc3H8o">
    <link rel="icon" href="https://lh3.googleusercontent.com/d/1C_epiUnuYdo1ulRK6agWfUA_Qudc3H8o" type="image/png">

    <!-- Tailwind CSS & Font Awesome & Google Fonts (Inter / Roboto chuẩn Flatsome) -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        dskBlue: '#0b4f8a',      /* Màu xanh thương hiệu theo logo */
                        dskDarkBlue: '#073763',  /* Xanh đậm Flatsome header/footer */
                        dskLightBlue: '#eaf3fb', /* Nền xanh nhạt */
                        dskRed: '#d9251d',       /* Điểm nhấn đỏ thương hiệu */
                        dskGold: '#f59e0b'       /* Vàng cam điểm nhấn */
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif']
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Thiết kế chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
        .flatsome-container {
            width: 100%;
            padding-left: 12px;
            padding-right: 12px;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95% !important;
                max-width: 95% !important;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Tối ưu tên danh mục trên máy tính: viết liền trên 1 hàng chữ nhỏ gọn, không bao giờ ngắt dòng tên danh mục */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 4px 14px;
        }
        .desktop-nav-item {
            white-space: nowrap !important;
            font-size: 12.5px;
            font-weight: 600;
            letter-spacing: 0.01em;
            padding: 7px 6px;
            transition: color 0.2s ease, background-color 0.2s ease;
            border-radius: 4px;
        }
        @media (min-width: 1280px) {
            .desktop-nav-item {
                font-size: 13px;
                padding: 8px 10px;
            }
        }

        /* Danh mục sản phẩm ở trang chủ nhỏ gọn, không gãy chữ */
        .cat-pill-btn {
            white-space: nowrap;
            font-size: 12px;
            line-height: 1.3;
            padding: 7px 12px;
            border-radius: 6px;
            font-weight: 600;
            transition: all 0.2s ease;
        }

        /* Tên sản phẩm hiển thị đầy đủ, không bị tràn ra ngoài hoặc thiếu chữ */
        .product-title-full {
            word-break: break-word;
            overflow-wrap: break-word;
            white-space: normal;
            line-height: 1.4;
            display: block;
        }

        /* Tiêu đề Section chuẩn Flatsome UX Builder */
        .section-title-container {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 1.5rem;
            width: 100%;
        }
        .section-title-line {
            flex: 1;
            height: 2px;
            background-color: #cbd5e1;
        }
        .section-title-main {
            padding: 8px 20px;
            background-color: #0b4f8a;
            color: #ffffff;
            font-weight: 700;
            text-transform: uppercase;
            border-radius: 4px;
            text-align: center;
            font-size: 14px;
            letter-spacing: 0.03em;
            margin: 0 12px;
        }
        @media (min-width: 768px) {
            .section-title-main {
                font-size: 16px;
                padding: 9px 28px;
            }
        }

        /* Hiệu ứng nút liên hệ nổi bật */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 37, 29, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 37, 29, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 37, 29, 0); }
        }
        @keyframes pulse-blue {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(11, 79, 138, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(11, 79, 138, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(11, 79, 138, 0); }
        }
        .pulse-hotline {
            animation: pulse-ring 2s infinite;
        }
        .pulse-zalo {
            animation: pulse-blue 2s infinite;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800">

    <!-- ==================== HEADER CHUẨN FLATSOME (KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) ==================== -->
    <header class="bg-white shadow-sm sticky top-0 z-40 w-full border-b border-slate-200">
        <!-- Top Bar thông tin công ty -->
        <div class="bg-dskDarkBlue text-white text-xs py-1.5 w-full">
            <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-2 truncate">
                    <i class="fa-solid fa-building text-amber-400 shrink-0"></i>
                    <span class="font-medium truncate">CÔNG TY TNHH MỘT THÀNH VIÊN ĐSK WINDOW - dskwindow.com</span>
                </div>
                <div class="hidden md:flex items-center gap-4 text-[11.5px] text-slate-200 shrink-0">
                    <span><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>04 Nguyễn Đình Tứ, Phường An Khê, TP Đà Nẵng</span>
                    <span>|</span>
                    <span><i class="fa-regular fa-clock text-amber-400 mr-1"></i>Làm việc: Thứ 2 - CN (7:30 - 18:00)</span>
                </div>
            </div>
        </div>

        <!-- Header Main: Logo nhỏ gọn + Tìm kiếm + Giỏ hàng/Báo giá (Không có nút gọi ngay) -->
        <div class="py-2.5 bg-white w-full">
            <div class="flatsome-container flex items-center justify-between gap-3">
                <!-- Nút mở Menu trên Điện thoại -->
                <button id="mobileMenuBtn" onclick="toggleMobileMenu()" class="lg:hidden p-2 text-dskBlue hover:bg-slate-100 rounded border border-slate-200 shrink-0" aria-label="Menu">
                    <i class="fa-solid fa-bars text-lg"></i>
                </button>

                <!-- Logo chỉnh gọn nhỏ lại -->
                <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group">
                    <div class="w-10 h-10 md:w-11 md:h-11 rounded border border-slate-200 bg-white p-0.5 flex items-center justify-center overflow-hidden shrink-0">
                        <img src="https://lh3.googleusercontent.com/d/1C_epiUnuYdo1ulRK6agWfUA_Qudc3H8o" 
                             onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=1C_epiUnuYdo1ulRK6agWfUA_Qudc3H8o&sz=w400';}else{this.src='https://placehold.co/100x100/0b4f8a/ffffff?text=DSK';}"
                             alt="Logo ĐSK Window" 
                             class="w-full h-full object-contain">
                    </div>
                    <div class="flex flex-col">
                        <span class="font-extrabold text-dskBlue text-sm md:text-base tracking-tight leading-tight">ĐSK WINDOW</span>
                        <span class="text-[10px] md:text-[11px] text-slate-500 font-medium leading-tight">dskwindow.com</span>
                    </div>
                </a>

                <!-- Ô tìm kiếm danh mục & sản phẩm trên máy tính -->
                <div class="hidden md:flex flex-1 max-w-xl mx-4">
                    <div class="flex w-full border border-slate-300 rounded overflow-hidden focus-within:border-dskBlue bg-slate-50">
                        <select id="headerCatSelect" onchange="filterProductsByCategory(this.value)" class="bg-slate-100 text-slate-700 text-xs px-2.5 border-r border-slate-300 focus:outline-none">
                            <option value="all">Tất cả danh mục</option>
                            <option value="cua-nhom-xingfa">Cửa Nhôm Xingfa</option>
                            <option value="cua-nhua-loi-thep">Cửa Nhựa Lõi Thép</option>
                            <option value="cua-kinh-tu-dong">Cửa Kính Tự Động</option>
                            <option value="cau-thang-kinh">Cầu Thang Kính</option>
                            <option value="kinh-op-bep">Kính Ốp Bếp</option>
                            <option value="phong-tam-kinh">Phòng Tắm Kính</option>
                        </select>
                        <input id="searchInput" type="text" oninput="searchProducts(this.value)" placeholder="Tìm kiếm cửa nhôm Xingfa, cửa kính, cầu thang kính..." class="w-full px-3 py-1.5 text-xs bg-white focus:outline-none">
                        <button onclick="searchProducts(document.getElementById('searchInput').value)" class="bg-dskBlue text-white px-3.5 hover:bg-dskDarkBlue transition">
                            <i class="fa-solid fa-magnifying-glass text-xs"></i>
                        </button>
                    </div>
                </div>

                <!-- Địa chỉ ngắn gọn bên phải (Không để nút gọi ngay tránh tràn viền) -->
                <div class="hidden xl:flex items-center gap-2 text-xs text-slate-600 shrink-0">
                    <a href="#form-bao-gia" class="px-3 py-1.5 rounded bg-dskLightBlue text-dskBlue font-semibold hover:bg-dskBlue hover:text-white transition">
                        <i class="fa-regular fa-file-lines mr-1"></i>Nhận Báo Giá
                    </a>
                </div>
            </div>
        </div>

        <!-- Thanh Menu Danh Mục trên Máy Tính (Chữ nhỏ gọn, viết liền 1 hàng hoặc xuống hàng 2 nguyên cụm, không ngắt chữ) -->
        <nav class="hidden lg:block bg-dskBlue text-white w-full border-t border-dskDarkBlue">
            <div class="flatsome-container py-1">
                <ul class="desktop-nav-list">
                    <li><a href="#trang-chu" class="desktop-nav-item hover:bg-white/15 text-amber-300"><i class="fa-solid fa-house mr-1"></i>TRANG CHỦ</a></li>
                    <li><a href="#gioi-thieu" class="desktop-nav-item hover:bg-white/15">GIỚI THIỆU</a></li>
                    <li><a href="#san-pham" onclick="filterProductsByCategory('cua-nhom-xingfa')" class="desktop-nav-item hover:bg-white/15">CỬA NHÔM XINGFA</a></li>
                    <li><a href="#san-pham" onclick="filterProductsByCategory('cua-nhua-loi-thep')" class="desktop-nav-item hover:bg-white/15">CỬA NHỰA LÕI THÉP</a></li>
                    <li><a href="#san-pham" onclick="filterProductsByCategory('cua-kinh-tu-dong')" class="desktop-nav-item hover:bg-white/15">CỬA KÍNH TỰ ĐỘNG</a></li>
                    <li><a href="#san-pham" onclick="filterProductsByCategory('cau-thang-kinh')" class="desktop-nav-item hover:bg-white/15">CẦU THANG KÍNH</a></li>
                    <li><a href="#san-pham" onclick="filterProductsByCategory('kinh-op-bep')" class="desktop-nav-item hover:bg-white/15">KÍNH ỐP BẾP</a></li>
                    <li><a href="#san-pham" onclick="filterProductsByCategory('phong-tam-kinh')" class="desktop-nav-item hover:bg-white/15">PHÒNG TẮM KÍNH</a></li>
                    <li><a href="#du-an-da-nang" class="desktop-nav-item hover:bg-white/15">CÔNG TRÌNH ĐÀ NẴNG</a></li>
                    <li><a href="#form-bao-gia" class="desktop-nav-item hover:bg-white/15">BÁO GIÁ</a></li>
                    <li><a href="#tin-tuc" class="desktop-nav-item hover:bg-white/15">TIN TỨC</a></li>
                    <li><a href="#lien-he" class="desktop-nav-item hover:bg-white/15">LIÊN HỆ</a></li>
                </ul>
            </div>
        </nav>

        <!-- Menu Danh Mục trượt trên Điện Thoại -->
        <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-t border-slate-200 px-3 py-3 shadow-inner">
            <div class="mb-2.5 flex border border-slate-300 rounded overflow-hidden">
                <input id="mobileSearchInput" type="text" oninput="searchProducts(this.value)" placeholder="Tìm sản phẩm..." class="w-full px-3 py-1.5 text-xs focus:outline-none">
                <button class="bg-dskBlue text-white px-3"><i class="fa-solid fa-magnifying-glass text-xs"></i></button>
            </div>
            <div class="grid grid-cols-2 gap-1.5 text-xs font-semibold">
                <a href="#trang-chu" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 text-dskBlue">Trang Chủ</a>
                <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 text-slate-700">Giới Thiệu</a>
                <a href="#san-pham" onclick="filterProductsByCategory('cua-nhom-xingfa');toggleMobileMenu()" class="p-2 rounded bg-dskLightBlue text-dskBlue">Cửa Nhôm Xingfa</a>
                <a href="#san-pham" onclick="filterProductsByCategory('cua-nhua-loi-thep');toggleMobileMenu()" class="p-2 rounded bg-dskLightBlue text-dskBlue">Cửa Nhựa Lõi Thép</a>
                <a href="#san-pham" onclick="filterProductsByCategory('cua-kinh-tu-dong');toggleMobileMenu()" class="p-2 rounded bg-dskLightBlue text-dskBlue">Cửa Kính Tự Động</a>
                <a href="#san-pham" onclick="filterProductsByCategory('cau-thang-kinh');toggleMobileMenu()" class="p-2 rounded bg-dskLightBlue text-dskBlue">Cầu Thang Kính</a>
                <a href="#san-pham" onclick="filterProductsByCategory('kinh-op-bep');toggleMobileMenu()" class="p-2 rounded bg-dskLightBlue text-dskBlue">Kính Ốp Bếp</a>
                <a href="#san-pham" onclick="filterProductsByCategory('phong-tam-kinh');toggleMobileMenu()" class="p-2 rounded bg-dskLightBlue text-dskBlue">Phòng Tắm Kính</a>
                <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 text-slate-700">Dự Án Đà Nẵng</a>
                <a href="#form-bao-gia" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 text-slate-700">Báo Giá</a>
                <a href="#tin-tuc" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 text-slate-700">Tin Tức</a>
                <a href="#lien-he" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 text-slate-700">Liên Hệ & Bản Đồ</a>
            </div>
        </div>
    </header>

    <!-- ==================== BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (2 SLIDE KÍCH THƯỚC BẰNG NHAU) ==================== -->
    <!-- Thiết kế tách biệt hoàn toàn: Bản Máy Tính riêng & Bản Điện Thoại riêng để chữ nhỏ gọn, nằm trọn trong ảnh, không tràn viền -->
    <section id="trang-chu" class="pt-3 pb-4 w-full">
        <div class="flatsome-container">
            <div class="relative w-full overflow-hidden rounded-lg shadow border border-slate-200 bg-dskDarkBlue">

                <!-- 1. BANNER DÀNH RIÊNG CHO MÁY TÍNH (Desktop: 2 Slide bằng nhau tuyệt đối h-[360px] lg:h-[400px]) -->
                <div class="hidden md:block relative w-full h-[360px] lg:h-[400px]">
                    <!-- Desktop Slide 1 -->
                    <div class="desktop-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                        <div class="w-full h-full grid grid-cols-12 bg-gradient-to-r from-dskDarkBlue via-dskBlue to-slate-900">
                            <!-- Cột chữ nằm gọn trong khung an toàn -->
                            <div class="col-span-7 flex flex-col justify-center px-10 lg:px-14 py-6 text-white">
                                <div class="inline-flex items-center gap-2 bg-white/15 border border-white/25 px-3 py-1 rounded text-amber-300 text-xs font-semibold w-fit mb-2.5">
                                    <span>ĐSK WINDOW - dskwindow.com</span>
                                </div>
                                <h1 class="text-xl lg:text-2xl font-extrabold leading-snug text-white mb-2">
                                    CÔNG TY TNHH MỘT THÀNH VIÊN ĐSK WINDOW
                                </h1>
                                <p class="text-xs lg:text-sm text-sky-100 mb-3 leading-relaxed">
                                    Chuyên thiết kế, sản xuất & thi công Cửa Nhôm Xingfa nhập khẩu, Cửa Nhựa Lõi Thép, Cửa Kính Cường Lực, Cầu Thang Kính, Kính Ốp Bếp & Phòng Tắm Kính uy tín tại Đà Nẵng.
                                </p>
                                <div class="grid grid-cols-2 gap-2 text-xs text-slate-100 mb-4 bg-black/20 p-3 rounded border border-white/10">
                                    <div><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Phụ kiện Kinlong, VVP đồng bộ</div>
                                    <div><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Khảo sát & báo giá tận nơi miễn phí</div>
                                    <div class="col-span-2"><i class="fa-solid fa-location-dot text-amber-400 mr-1.5"></i>Địa chỉ: 04 Nguyễn Đình Tứ, Phường An Khê, TP Đà Nẵng</div>
                                </div>
                                <div class="flex items-center gap-3">
                                    <a href="#form-bao-gia" class="bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-xs px-4 py-2.5 rounded transition">
                                        ĐĂNG KÝ BÁO GIÁ NGAY
                                    </a>
                                    <span class="text-xs font-semibold text-white bg-white/10 px-3 py-2 rounded border border-white/20">
                                        <i class="fa-solid fa-phone-volume text-amber-400 mr-1"></i>Hotline: 0907.228.282
                                    </span>
                                </div>
                            </div>
                            <!-- Cột ảnh thực tế công trình -->
                            <div class="col-span-5 relative h-full overflow-hidden p-4 flex items-center justify-center">
                                <div class="w-full h-full rounded-lg overflow-hidden border-2 border-white/30 shadow-lg bg-slate-800">
                                    <img src="https://lh3.googleusercontent.com/d/1Y5yj6AFxbhVLcx8osNYW5VjhavQjGC_F"
                                         onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=1Y5yj6AFxbhVLcx8osNYW5VjhavQjGC_F&sz=w1000';}else{this.src='https://placehold.co/600x400/0b4f8a/ffffff?text=DSK+WINDOW';}"
                                         alt="Công ty ĐSK Window Đà Nẵng"
                                         class="w-full h-full object-cover">
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Desktop Slide 2 (Kích thước bằng đúng Slide 1) -->
                    <div class="desktop-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0">
                        <div class="w-full h-full grid grid-cols-12 bg-gradient-to-r from-slate-900 via-dskDarkBlue to-dskBlue">
                            <div class="col-span-7 flex flex-col justify-center px-10 lg:px-14 py-6 text-white">
                                <div class="inline-flex items-center gap-2 bg-amber-400/20 border border-amber-300/40 px-3 py-1 rounded text-amber-300 text-xs font-semibold w-fit mb-2.5">
                                    <span>GIẢI PHÁP CỬA ĐẸP CHO MỌI CÔNG TRÌNH</span>
                                </div>
                                <h2 class="text-xl lg:text-2xl font-extrabold leading-snug text-white mb-2">
                                    THI CÔNG NHÔM KÍNH XINGFA & KÍNH CƯỜNG LỰC ĐÀ NẴNG
                                </h2>
                                <p class="text-xs lg:text-sm text-sky-100 mb-3 leading-relaxed">
                                    Độ bền vượt thời gian, cách âm cách nhiệt tối ưu, thẩm mỹ sang trọng cho Biệt thự, Nhà phố, Khách sạn và Căn hộ tại TP Đà Nẵng & Miền Trung.
                                </p>
                                <div class="grid grid-cols-2 gap-2 text-xs text-slate-100 mb-4 bg-black/20 p-3 rounded border border-white/10">
                                    <div><i class="fa-solid fa-shield-halved text-amber-400 mr-1.5"></i>Bảo hành dài hạn uy tín</div>
                                    <div><i class="fa-solid fa-gears text-amber-400 mr-1.5"></i>Gia công chuẩn kỹ thuật</div>
                                    <div class="col-span-2"><i class="fa-solid fa-globe text-amber-400 mr-1.5"></i>Website: dskwindow.com | ĐT: 0907.228.282</div>
                                </div>
                                <div class="flex items-center gap-3">
                                    <a href="#du-an-da-nang" class="bg-white text-dskBlue hover:bg-slate-100 font-bold text-xs px-4 py-2.5 rounded transition">
                                        XEM DỰ ÁN TẠI ĐÀ NẴNG
                                    </a>
                                    <a href="#san-pham" class="text-xs font-semibold text-white bg-white/10 hover:bg-white/20 px-3.5 py-2.5 rounded border border-white/20 transition">
                                        Xem 13+ Mẫu Thực Tế
                                    </a>
                                </div>
                            </div>
                            <div class="col-span-5 relative h-full overflow-hidden p-4 flex items-center justify-center">
                                <div class="w-full h-full rounded-lg overflow-hidden border-2 border-white/30 shadow-lg bg-slate-800">
                                    <img src="https://lh3.googleusercontent.com/d/1Deg-ThCdcgcmCCvfyp69RiNRNj9LBZFU"
                                         onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=1Deg-ThCdcgcmCCvfyp69RiNRNj9LBZFU&sz=w1000';}else{this.src='https://placehold.co/600x400/073763/ffffff?text=DU+AN+DA+NANG';}"
                                         alt="Dự án ĐSK Window tại Đà Nẵng"
                                         class="w-full h-full object-cover">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- 2. BANNER THIẾT KẾ MỚI DÀNH RIÊNG CHO ĐIỆN THOẠI (Mobile: 2 Slide bằng nhau h-[330px], chữ nhỏ gọn nằm hết bên trong ảnh, không tràn viền) -->
                <div class="block md:hidden relative w-full h-[330px]">
                    <!-- Mobile Slide 1 -->
                    <div class="mobile-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                        <img src="https://lh3.googleusercontent.com/d/1Y5yj6AFxbhVLcx8osNYW5VjhavQjGC_F"
                             onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=1Y5yj6AFxbhVLcx8osNYW5VjhavQjGC_F&sz=w800';}else{this.src='https://placehold.co/600x450/0b4f8a/ffffff?text=DSK+WINDOW';}"
                             alt="ĐSK Window Mobile Banner 1"
                             class="w-full h-full object-cover">
                        <div class="absolute inset-0 bg-gradient-to-t from-slate-950/95 via-dskDarkBlue/85 to-slate-900/60 p-4 flex flex-col justify-center items-center text-center">
                            <span class="px-2.5 py-0.5 rounded bg-amber-400 text-slate-950 text-[10px] font-bold mb-1.5">
                                dskwindow.com
                            </span>
                            <h2 class="text-[13px] font-extrabold text-white leading-snug mb-1.5 px-2">
                                CÔNG TY TNHH MTV ĐSK WINDOW
                            </h2>
                            <p class="text-[11px] text-sky-100 leading-relaxed mb-2 px-2">
                                Chuyên Cửa Nhôm Xingfa, Cửa Nhựa Lõi Thép, Cửa Kính Cường Lực, Cầu Thang Kính, Phòng Tắm Kính tại Đà Nẵng.
                            </p>
                            <div class="bg-black/35 border border-white/15 rounded px-2.5 py-1.5 text-[10.5px] text-slate-100 mb-2.5 w-full max-w-[92%]">
                                <div class="truncate">Đ/c: 04 Nguyễn Đình Tứ, P. An Khê, TP Đà Nẵng</div>
                                <div class="font-bold text-amber-300 mt-0.5">Hotline / Zalo: 0907.228.282</div>
                            </div>
                            <a href="#form-bao-gia" class="bg-amber-500 text-slate-950 font-bold text-[11px] px-3.5 py-1.5 rounded">
                                NHẬN BÁO GIÁ NGAY
                            </a>
                        </div>
                    </div>

                    <!-- Mobile Slide 2 (Kích thước bằng đúng Mobile Slide 1) -->
                    <div class="mobile-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0">
                        <img src="https://lh3.googleusercontent.com/d/1Deg-ThCdcgcmCCvfyp69RiNRNj9LBZFU"
                             onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=1Deg-ThCdcgcmCCvfyp69RiNRNj9LBZFU&sz=w800';}else{this.src='https://placehold.co/600x450/073763/ffffff?text=DU+AN+DSK';}"
                             alt="ĐSK Window Mobile Banner 2"
                             class="w-full h-full object-cover">
                        <div class="absolute inset-0 bg-gradient-to-t from-slate-950/95 via-dskDarkBlue/85 to-slate-900/60 p-4 flex flex-col justify-center items-center text-center">
                            <span class="px-2.5 py-0.5 rounded bg-sky-400 text-slate-950 text-[10px] font-bold mb-1.5">
                                UY TÍN - CHẤT LƯỢNG - THẨM MỸ
                            </span>
                            <h2 class="text-[13px] font-extrabold text-white leading-snug mb-1.5 px-2">
                                THI CÔNG NHÔM KÍNH XINGFA ĐÀ NẴNG
                            </h2>
                            <p class="text-[11px] text-sky-100 leading-relaxed mb-2 px-2">
                                Phụ kiện chính hãng đồng bộ, lắp đặt tận nơi miễn phí, bảo hành chu đáo cho mọi công trình nhà phố, biệt thự, khách sạn.
                            </p>
                            <div class="bg-black/35 border border-white/15 rounded px-2.5 py-1.5 text-[10.5px] text-slate-100 mb-2.5 w-full max-w-[92%]">
                                <div class="truncate">04 Nguyễn Đình Tứ, Phường An Khê, TP Đà Nẵng</div>
                                <div class="font-bold text-amber-300 mt-0.5">Tư vấn 24/7: 0907.228.282</div>
                            </div>
                            <a href="#san-pham" class="bg-white text-dskBlue font-bold text-[11px] px-3.5 py-1.5 rounded">
                                XEM SẢN PHẨM THỰC TẾ
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Slide Banner -->
                <button onclick="changeBannerSlide(-1)" class="absolute left-2 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/40 hover:bg-black/65 text-white flex items-center justify-center transition" aria-label="Slide trước">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button onclick="changeBannerSlide(1)" class="absolute right-2 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/40 hover:bg-black/65 text-white flex items-center justify-center transition" aria-label="Slide tiếp">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>

                <!-- Chấm tròn chỉ báo Slide -->
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button onclick="goToBannerSlide(0)" id="dot-0" class="w-2.5 h-2.5 rounded-full bg-amber-400 transition"></button>
                    <button onclick="goToBannerSlide(1)" id="dot-1" class="w-2.5 h-2.5 rounded-full bg-white/50 transition"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== CAM KẾT DỊCH VỤ CHUẨN MẪU NGOCHANWINDOW ==================== -->
    <section class="py-3 w-full">
        <div class="flatsome-container">
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 md:gap-4">
                <div class="bg-white p-3 rounded border border-slate-200 flex items-center gap-3 shadow-sm">
                    <div class="w-10 h-10 rounded-full bg-dskLightBlue text-dskBlue flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-phone-volume text-base"></i>
                    </div>
                    <div>
                        <div class="text-xs font-bold text-dskBlue">LIÊN HỆ TƯ VẤN</div>
                        <div class="text-xs text-slate-600 font-medium">0907.228.282</div>
                    </div>
                </div>
                <div class="bg-white p-3 rounded border border-slate-200 flex items-center gap-3 shadow-sm">
                    <div class="w-10 h-10 rounded-full bg-dskLightBlue text-dskBlue flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-screwdriver-wrench text-base"></i>
                    </div>
                    <div>
                        <div class="text-xs font-bold text-dskBlue">KHẢO SÁT TẬN NƠI</div>
                        <div class="text-xs text-slate-600">Lắp đặt chuẩn kỹ thuật</div>
                    </div>
                </div>
                <div class="bg-white p-3 rounded border border-slate-200 flex items-center gap-3 shadow-sm">
                    <div class="w-10 h-10 rounded-full bg-dskLightBlue text-dskBlue flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-award text-base"></i>
                    </div>
                    <div>
                        <div class="text-xs font-bold text-dskBlue">VẬT TƯ CHÍNH HÃNG</div>
                        <div class="text-xs text-slate-600">Nhôm Xingfa & Phụ kiện</div>
                    </div>
                </div>
                <div class="bg-white p-3 rounded border border-slate-200 flex items-center gap-3 shadow-sm">
                    <div class="w-10 h-10 rounded-full bg-dskLightBlue text-dskBlue flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-shield-heart text-base"></i>
                    </div>
                    <div>
                        <div class="text-xs font-bold text-dskBlue">BẢO HÀNH UY TÍN</div>
                        <div class="text-xs text-slate-600">Hỗ trợ nhanh tại Đà Nẵng</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC SẢN PHẨM NỔI BẬT (TỪ WEB MẪU NGOCHANWINDOW.COM - CHỮ NHỎ GỌN ĐẸP MẮT) ==================== -->
    <section class="py-5 w-full">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-line"></div>
                <h2 class="section-title-main">DANH MỤC SẢN PHẨM NỔI BẬT</h2>
                <div class="section-title-line"></div>
            </div>

            <!-- Lưới 6 danh mục chuẩn web mẫu: 2 cột trên điện thoại, 6 cột trên máy tính, chữ nhỏ gọn không tràn -->
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
                <!-- Danh mục 1: Cửa Nhôm Xingfa -->
                <div onclick="filterProductsByCategory('cua-nhom-xingfa'); document.getElementById('san-pham').scrollIntoView({behavior:'smooth'});" 
                     class="cursor-pointer bg-white rounded border border-slate-200 overflow-hidden hover:border-dskBlue transition group">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1do1PKpzoa5GIEjkObMrflqJHqtxRqC5u"
                             onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=1do1PKpzoa5GIEjkObMrflqJHqtxRqC5u&sz=w600';}else{this.src='https://placehold.co/400x300/0b4f8a/ffffff?text=Cua+Nhom+Xingfa';}"
                             alt="Cửa Nhôm Xingfa"
                             class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center bg-white">
                        <h3 class="text-xs font-bold text-dskBlue uppercase leading-snug">CỬA NHÔM XINGFA</h3>
                        <p class="text-[11px] text-slate-500 mt-0.5">Mở quay, mở lùa, xếp trượt</p>
                    </div>
                </div>

                <!-- Danh mục 2: Cửa Nhựa Lõi Thép -->
                <div onclick="filterProductsByCategory('cua-nhua-loi-thep'); document.getElementById('san-pham').scrollIntoView({behavior:'smooth'});" 
                     class="cursor-pointer bg-white rounded border border-slate-200 overflow-hidden hover:border-dskBlue transition group">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1-GyY9h3yJdvY5yZ91mSQvjiqT8EenGLe"
                             onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=1-GyY9h3yJdvY5yZ91mSQvjiqT8EenGLe&sz=w600';}else{this.src='https://placehold.co/400x300/0b4f8a/ffffff?text=Cua+Nhua+Loi+Thep';}"
                             alt="Cửa Nhựa Lõi Thép"
                             class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center bg-white">
                        <h3 class="text-xs font-bold text-dskBlue uppercase leading-snug">CỬA NHỰA LÕI THÉP</h3>
                        <p class="text-[11px] text-slate-500 mt-0.5">Cách âm, cách nhiệt cao</p>
                    </div>
                </div>

                <!-- Danh mục 3: Cửa Kính Tự Động / Cường Lực -->
                <div onclick="filterProductsByCategory('cua-kinh-tu-dong'); document.getElementById('san-pham').scrollIntoView({behavior:'smooth'});" 
                     class="cursor-pointer bg-white rounded border border-slate-200 overflow-hidden hover:border-dskBlue transition group">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1dO_txhpwvwvqTX1ZAVsCvCq_54rCDQZN"
                             onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=1dO_txhpwvwvqTX1ZAVsCvCq_54rCDQZN&sz=w600';}else{this.src='https://placehold.co/400x300/0b4f8a/ffffff?text=Cua+Kinh+Tu+Dong';}"
                             alt="Cửa Kính Tự Động"
                             class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center bg-white">
                        <h3 class="text-xs font-bold text-dskBlue uppercase leading-snug">CỬA KÍNH TỰ ĐỘNG</h3>
                        <p class="text-[11px] text-slate-500 mt-0.5">Cửa kính cường lực bản lề sàn</p>
                    </div>
                </div>

                <!-- Danh mục 4: Cầu Thang Kính -->
                <div onclick="filterProductsByCategory('cau-thang-kinh'); document.getElementById('san-pham').scrollIntoView({behavior:'smooth'});" 
                     class="cursor-pointer bg-white rounded border border-slate-200 overflow-hidden hover:border-dskBlue transition group">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1j10IYTaNCPMekLpE-3eqlT-JLXPeDB5x"
                             onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=1j10IYTaNCPMekLpE-3eqlT-JLXPeDB5x&sz=w600';}else{this.src='https://placehold.co/400x300/0b4f8a/ffffff?text=Cau+Thang+Kinh';}"
                             alt="Cầu Thang Kính"
                             class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center bg-white">
                        <h3 class="text-xs font-bold text-dskBlue uppercase leading-snug">CẦU THANG KÍNH</h3>
                        <p class="text-[11px] text-slate-500 mt-0.5">Lan can & cầu thang kính</p>
                    </div>
                </div>

                <!-- Danh mục 5: Kính Ốp Bếp -->
                <div onclick="filterProductsByCategory('kinh-op-bep'); document.getElementById('san-pham').scrollIntoView({behavior:'smooth'});" 
                     class="cursor-pointer bg-white rounded border border-slate-200 overflow-hidden hover:border-dskBlue transition group">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/19_hzNMKX6YYmqwl6LsH64J9cscmoCvmE"
                             onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=19_hzNMKX6YYmqwl6LsH64J9cscmoCvmE&sz=w600';}else{this.src='https://placehold.co/400x300/0b4f8a/ffffff?text=Kinh+Op+Bep';}"
                             alt="Kính Ốp Bếp"
                             class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center bg-white">
                        <h3 class="text-xs font-bold text-dskBlue uppercase leading-snug">KÍNH ỐP BẾP</h3>
                        <p class="text-[11px] text-slate-500 mt-0.5">Kính màu cường lực cao cấp</p>
                    </div>
                </div>

                <!-- Danh mục 6: Phòng Tắm Kính -->
                <div onclick="filterProductsByCategory('phong-tam-kinh'); document.getElementById('san-pham').scrollIntoView({behavior:'smooth'});" 
                     class="cursor-pointer bg-white rounded border border-slate-200 overflow-hidden hover:border-dskBlue transition group">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/15huQBtVZfLCY0SXZegjtXNBQCK5I2ZCc"
                             onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=15huQBtVZfLCY0SXZegjtXNBQCK5I2ZCc&sz=w600';}else{this.src='https://placehold.co/400x300/0b4f8a/ffffff?text=Phong+Tam+Kinh';}"
                             alt="Phòng Tắm Kính"
                             class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center bg-white">
                        <h3 class="text-xs font-bold text-dskBlue uppercase leading-snug">PHÒNG TẮM KÍNH</h3>
                        <p class="text-[11px] text-slate-500 mt-0.5">Cabin vách kính cường lực</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== BÁO GIÁ & SẢN PHẨM THỰC TẾ ĐSK WINDOW (13 ẢNH THỰC TẾ, 2 CỘT TRÊN MOBILE, KHÔNG NHÃN DÁN) ==================== -->
    <section id="san-pham" class="py-6 bg-white border-y border-slate-200 w-full">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-line"></div>
                <h2 class="section-title-main">BÁO GIÁ CỬA NHÔM XINGFA & SẢN PHẨM THỰC TẾ</h2>
                <div class="section-title-line"></div>
            </div>

            <!-- Bộ lọc danh mục nhỏ gọn, viết liền không ngắt chữ -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 md:gap-2 mb-6">
                <button onclick="filterProductsByCategory('all')" data-cat="all" class="cat-filter-btn cat-pill-btn bg-dskBlue text-white">
                    Tất cả sản phẩm (13)
                </button>
                <button onclick="filterProductsByCategory('cua-nhom-xingfa')" data-cat="cua-nhom-xingfa" class="cat-filter-btn cat-pill-btn bg-slate-100 text-slate-700 hover:bg-dskLightBlue hover:text-dskBlue">
                    Cửa Nhôm Xingfa
                </button>
                <button onclick="filterProductsByCategory('cua-nhua-loi-thep')" data-cat="cua-nhua-loi-thep" class="cat-filter-btn cat-pill-btn bg-slate-100 text-slate-700 hover:bg-dskLightBlue hover:text-dskBlue">
                    Cửa Nhựa Lõi Thép
                </button>
                <button onclick="filterProductsByCategory('cua-kinh-tu-dong')" data-cat="cua-kinh-tu-dong" class="cat-filter-btn cat-pill-btn bg-slate-100 text-slate-700 hover:bg-dskLightBlue hover:text-dskBlue">
                    Cửa Kính Tự Động & Cường Lực
                </button>
                <button onclick="filterProductsByCategory('cau-thang-kinh')" data-cat="cau-thang-kinh" class="cat-filter-btn cat-pill-btn bg-slate-100 text-slate-700 hover:bg-dskLightBlue hover:text-dskBlue">
                    Cầu Thang Kính
                </button>
                <button onclick="filterProductsByCategory('kinh-op-bep')" data-cat="kinh-op-bep" class="cat-filter-btn cat-pill-btn bg-slate-100 text-slate-700 hover:bg-dskLightBlue hover:text-dskBlue">
                    Kính Ốp Bếp
                </button>
                <button onclick="filterProductsByCategory('phong-tam-kinh')" data-cat="phong-tam-kinh" class="cat-filter-btn cat-pill-btn bg-slate-100 text-slate-700 hover:bg-dskLightBlue hover:text-dskBlue">
                    Phòng Tắm Kính
                </button>
            </div>

            <!-- Lưới sản phẩm: Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4) -->
            <!-- Không để bất kỳ nhãn dán (sticker/badge) nào trên ảnh, tên sản phẩm đầy đủ không tràn viền -->
            <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 md:gap-5">
                <!-- Được render tự động từ mảng 13 ảnh thực tế bên dưới -->
            </div>
        </div>
    </section>

    <!-- ==================== GIỚI THIỆU CÔNG TY TNHH MỘT THÀNH VIÊN ĐSK WINDOW ==================== -->
    <section id="gioi-thieu" class="py-8 bg-slate-50 w-full">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-line"></div>
                <h2 class="section-title-main">CÔNG TY TNHH MỘT THÀNH VIÊN ĐSK WINDOW</h2>
                <div class="section-title-line"></div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center bg-white p-4 md:p-6 rounded-lg border border-slate-200 shadow-sm">
                <!-- Cột nội dung giới thiệu -->
                <div class="lg:col-span-7 space-y-3 text-xs md:text-sm text-slate-700 leading-relaxed">
                    <h3 class="text-base md:text-lg font-bold text-dskBlue">
                        ĐƠN VỊ THIẾT KẾ, SẢN XUẤT & THI CÔNG CỬA NHÔM KÍNH UY TÍN TẠI ĐÀ NẴNG
                    </h3>
                    <p>
                        <strong>CÔNG TY TNHH MỘT THÀNH VIÊN ĐSK WINDOW</strong> (<a href="https://dskwindow.com" class="text-dskBlue font-semibold">dskwindow.com</a>) là đơn vị chuyên thiết kế, gia công sản xuất và thi công lắp đặt các hạng mục về nhôm kính cao cấp tại TP Đà Nẵng và khu vực Miền Trung.
                    </p>
                    <p>
                        Các dòng sản phẩm chủ lực của <strong>ĐSK Window</strong> bao gồm: <strong>Cửa nhôm Xingfa nhập khẩu chính hãng, Cửa nhựa lõi thép uPVC, Cửa kính cường lực - Cửa kính tự động, Cầu thang kính cường lực, Kính màu ốp bếp và Phòng tắm kính cao cấp</strong>.
                    </p>
                    <p>
                        Với phương châm <em>“Cửa đẹp cho mọi nhà – Uy tín kiến tạo niềm tin”</em>, ĐSK Window cam kết sử dụng vật tư chính hãng, quy trình gia công chuẩn xác tại xưởng <strong>04 Nguyễn Đình Tứ, Phường An Khê, TP Đà Nẵng</strong> cùng chính sách bảo hành – hậu mãi chu đáo, mang lại không gian sống hiện đại, an toàn và bền vững cho mọi công trình.
                    </p>

                    <!-- Thống kê năng lực giống mẫu ngochanwindow.com -->
                    <div class="grid grid-cols-2 sm:grid-cols-4 gap-2.5 pt-2">
                        <div class="bg-dskLightBlue p-3 rounded text-center border border-sky-200">
                            <div class="text-lg md:text-xl font-extrabold text-dskBlue">250+</div>
                            <div class="text-[11px] font-medium text-slate-700">Dự án hoàn thành</div>
                        </div>
                        <div class="bg-dskLightBlue p-3 rounded text-center border border-sky-200">
                            <div class="text-lg md:text-xl font-extrabold text-dskBlue">10+ Năm</div>
                            <div class="text-[11px] font-medium text-slate-700">Kinh nghiệm ngành</div>
                        </div>
                        <div class="bg-dskLightBlue p-3 rounded text-center border border-sky-200">
                            <div class="text-lg md:text-xl font-extrabold text-dskBlue">100+</div>
                            <div class="text-[11px] font-medium text-slate-700">Mẫu cửa chất lượng</div>
                        </div>
                        <div class="bg-dskLightBlue p-3 rounded text-center border border-sky-200">
                            <div class="text-lg md:text-xl font-extrabold text-dskBlue">100%</div>
                            <div class="text-[11px] font-medium text-slate-700">Khách hàng hài lòng</div>
                        </div>
                    </div>
                </div>

                <!-- Cột Ảnh thực tế Công ty ĐSK Window -->
                <div class="lg:col-span-5">
                    <div class="rounded-lg overflow-hidden border border-slate-200 bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1Y5yj6AFxbhVLcx8osNYW5VjhavQjGC_F"
                             onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=1Y5yj6AFxbhVLcx8osNYW5VjhavQjGC_F&sz=w1000';}else{this.src='https://placehold.co/600x420/0b4f8a/ffffff?text=CONG+TY+DSK+WINDOW';}"
                             alt="Hình ảnh Công ty TNHH MTV ĐSK Window"
                             class="w-full h-64 md:h-80 object-cover">
                        <div class="p-2.5 bg-dskDarkBlue text-white text-center text-xs font-medium">
                            CÔNG TY TNHH MỘT THÀNH VIÊN ĐSK WINDOW - 04 Nguyễn Đình Tứ, P. An Khê, TP Đà Nẵng
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (8 ẢNH THỰC TẾ TỪ GOOGLE DRIVE) ==================== -->
    <section id="du-an-da-nang" class="py-7 bg-white border-t border-slate-200 w-full">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-line"></div>
                <h2 class="section-title-main">CÁC DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG</h2>
                <div class="section-title-line"></div>
            </div>

            <!-- Tabs phân loại dự án tại Đà Nẵng chuẩn mẫu ngochanwindow.com -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 md:gap-2 mb-6">
                <button onclick="filterProjects('all')" data-proj="all" class="proj-filter-btn cat-pill-btn bg-dskBlue text-white">
                    Tất cả dự án Đà Nẵng (8)
                </button>
                <button onclick="filterProjects('nha-pho-biet-thu')" data-proj="nha-pho-biet-thu" class="proj-filter-btn cat-pill-btn bg-slate-100 text-slate-700 hover:bg-dskLightBlue hover:text-dskBlue">
                    Dự án Biệt Thự & Nhà Phố
                </button>
                <button onclick="filterProjects('khach-san-can-ho')" data-proj="khach-san-can-ho" class="proj-filter-btn cat-pill-btn bg-slate-100 text-slate-700 hover:bg-dskLightBlue hover:text-dskBlue">
                    Dự án Khách Sạn & Căn Hộ
                </button>
                <button onclick="filterProjects('thuong-mai-van-phong')" data-proj="thuong-mai-van-phong" class="proj-filter-btn cat-pill-btn bg-slate-100 text-slate-700 hover:bg-dskLightBlue hover:text-dskBlue">
                    Dự án Văn Phòng & Thương Mại
                </button>
            </div>

            <!-- Lưới 8 dự án thực tế ở Đà Nẵng (Chia 2 cột trên điện thoại, 4 cột trên máy tính, không nhãn dán) -->
            <div id="projectGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 md:gap-5">
                <!-- Được render từ 8 ảnh dự án thực tế -->
            </div>
        </div>
    </section>

    <!-- ==================== FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ ==================== -->
    <section id="form-bao-gia" class="py-8 bg-dskLightBlue border-y border-sky-200 w-full">
        <div class="flatsome-container">
            <div class="bg-white rounded-lg border border-slate-200 shadow-sm p-4 md:p-7">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                    <!-- Thông tin hỗ trợ báo giá -->
                    <div class="lg:col-span-5 space-y-3">
                        <h2 class="text-base md:text-xl font-extrabold text-dskBlue uppercase">
                            ĐĂNG KÝ NHẬN BÁO GIÁ & KHẢO SÁT MIỄN PHÍ
                        </h2>
                        <p class="text-xs md:text-sm text-slate-600 leading-relaxed">
                            Quý khách hàng tại Đà Nẵng và khu vực lân cận cần tư vấn mẫu cửa nhôm Xingfa, cửa nhựa lõi thép, cửa kính cường lực, cầu thang kính, phòng tắm kính vui lòng để lại thông tin. Kỹ thuật viên <strong>ĐSK WINDOW</strong> sẽ liên hệ báo giá chi tiết trong vòng 15 phút!
                        </p>
                        <div class="space-y-2 text-xs md:text-sm text-slate-700 bg-slate-50 p-3.5 rounded border border-slate-200">
                            <div><i class="fa-solid fa-building text-dskBlue mr-2"></i><strong>Đơn vị:</strong> CÔNG TY TNHH MTV ĐSK WINDOW</div>
                            <div><i class="fa-solid fa-location-dot text-dskBlue mr-2"></i><strong>Địa chỉ:</strong> 04 Nguyễn Đình Tứ, Phường An Khê, TP Đà Nẵng</div>
                            <div><i class="fa-solid fa-phone-volume text-dskRed mr-2"></i><strong>Hotline / Zalo:</strong> <a href="tel:0907228282" class="font-bold text-dskRed">0907.228.282</a></div>
                            <div><i class="fa-solid fa-globe text-dskBlue mr-2"></i><strong>Website:</strong> dskwindow.com</div>
                        </div>
                    </div>

                    <!-- Form nhập thông tin báo giá -->
                    <div class="lg:col-span-7">
                        <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên quý khách *</label>
                                <input id="qName" type="text" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs md:text-sm border border-slate-300 rounded focus:outline-none focus:border-dskBlue">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                <input id="qPhone" type="tel" required placeholder="Nhập số điện thoại..." class="w-full px-3 py-2 text-xs md:text-sm border border-slate-300 rounded focus:outline-none focus:border-dskBlue">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục cần báo giá *</label>
                                <select id="qCategory" class="w-full px-3 py-2 text-xs md:text-sm border border-slate-300 rounded focus:outline-none focus:border-dskBlue bg-white">
                                    <option value="Cửa Nhôm Xingfa">Cửa Nhôm Xingfa nhập khẩu</option>
                                    <option value="Cửa Nhựa Lõi Thép">Cửa Nhựa Lõi Thép</option>
                                    <option value="Cửa Kính Tự Động / Cường Lực">Cửa Kính Tự Động / Kính Cường Lực</option>
                                    <option value="Cầu Thang Kính / Lan Can Kính">Cầu Thang Kính / Lan Can Kính</option>
                                    <option value="Kính Ốp Bếp">Kính Màu Ốp Bếp</option>
                                    <option value="Phòng Tắm Kính">Phòng Tắm Kính Cường Lực</option>
                                    <option value="Trọn gói nhôm kính công trình">Thi công trọn gói nhôm kính công trình</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Địa chỉ công trình tại Đà Nẵng</label>
                                <input id="qAddress" type="text" placeholder="VD: Quận Thanh Khê, Cẩm Lệ, Hải Châu..." class="w-full px-3 py-2 text-xs md:text-sm border border-slate-300 rounded focus:outline-none focus:border-dskBlue">
                            </div>
                            <div class="sm:col-span-2">
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Yêu cầu chi tiết (Kích thước, số lượng cửa...)</label>
                                <textarea id="qNote" rows="3" placeholder="Nhập yêu cầu tư vấn hoặc kích thước sơ bộ cần báo giá..." class="w-full px-3 py-2 text-xs md:text-sm border border-slate-300 rounded focus:outline-none focus:border-dskBlue"></textarea>
                            </div>
                            <div class="sm:col-span-2">
                                <button type="submit" class="w-full bg-dskBlue hover:bg-dskDarkBlue text-white font-bold text-xs md:text-sm py-2.5 px-5 rounded transition">
                                    <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU BÁO GIÁ NGAY
                                </button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC CÁC BÀI VIẾT / TIN TỨC NỔI BẬT TRANG CHỦ ==================== -->
    <section id="tin-tuc" class="py-7 bg-white w-full">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-line"></div>
                <h2 class="section-title-main">TIN TỨC & KINH NGHIỆM NHÔM KÍNH NỔI BẬT</h2>
                <div class="section-title-line"></div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                <!-- Bài viết 1 -->
                <article class="bg-slate-50 rounded border border-slate-200 overflow-hidden flex flex-col justify-between hover:border-dskBlue transition">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                            <img src="https://lh3.googleusercontent.com/d/1do1PKpzoa5GIEjkObMrflqJHqtxRqC5u"
                                 onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=1do1PKpzoa5GIEjkObMrflqJHqtxRqC5u&sz=w600';}else{this.src='https://placehold.co/500x320/0b4f8a/ffffff?text=Tin+Tuc+1';}"
                                 alt="Cửa nhôm Xingfa có phù hợp với khí hậu Đà Nẵng không"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-3.5">
                            <h3 class="text-xs md:text-sm font-bold text-slate-800 hover:text-dskBlue leading-snug mb-2">
                                Cửa nhôm Xingfa có phù hợp với khí hậu miền Trung & Đà Nẵng không? Địa chỉ thi công uy tín
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Cửa nhôm Xingfa với kết cấu khoang rỗng cùng hệ gioăng EPDM kín khít giúp chống chịu mưa bão, chống thấm nước và cách nhiệt vượt trội tại Đà Nẵng.
                            </p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3.5">
                        <button onclick="openArticleModal(0)" class="text-xs font-semibold text-dskBlue hover:underline">
                            Xem chi tiết <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </button>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-slate-50 rounded border border-slate-200 overflow-hidden flex flex-col justify-between hover:border-dskBlue transition">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                            <img src="https://lh3.googleusercontent.com/d/1KyVcG2MZw_RD-VuaE5ODgjcVJvBV_jF9"
                                 onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=1KyVcG2MZw_RD-VuaE5ODgjcVJvBV_jF9&sz=w600';}else{this.src='https://placehold.co/500x320/0b4f8a/ffffff?text=Tin+Tuc+2';}"
                                 alt="So sánh cửa nhôm Xingfa và cửa gỗ, cửa nhựa"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-3.5">
                            <h3 class="text-xs md:text-sm font-bold text-slate-800 hover:text-dskBlue leading-snug mb-2">
                                Kinh nghiệm chọn cửa nhôm Xingfa chính hãng tiết kiệm năng lượng và bền đẹp cho nhà phố
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Tìm hiểu cách phân biệt thanh nhôm Xingfa tiêu chuẩn, phụ kiện đồng bộ và giải pháp chọn hệ cửa mở quay, mở lùa tối ưu diện tích.
                            </p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3.5">
                        <button onclick="openArticleModal(1)" class="text-xs font-semibold text-dskBlue hover:underline">
                            Xem chi tiết <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </button>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-slate-50 rounded border border-slate-200 overflow-hidden flex flex-col justify-between hover:border-dskBlue transition">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                            <img src="https://lh3.googleusercontent.com/d/1j10IYTaNCPMekLpE-3eqlT-JLXPeDB5x"
                                 onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=1j10IYTaNCPMekLpE-3eqlT-JLXPeDB5x&sz=w600';}else{this.src='https://placehold.co/500x320/0b4f8a/ffffff?text=Tin+Tuc+3';}"
                                 alt="Ưu điểm cầu thang kính cường lực và phòng tắm kính"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-3.5">
                            <h3 class="text-xs md:text-sm font-bold text-slate-800 hover:text-dskBlue leading-snug mb-2">
                                Xu hướng lắp đặt Cầu thang kính cường lực & Phòng tắm kính hiện đại tại Đà Nẵng
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Cầu thang kính và vách tắm kính cường lực giúp mở rộng không gian nội thất, lấy sáng tự nhiên và dễ dàng vệ sinh lau chùi hàng ngày.
                            </p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3.5">
                        <button onclick="openArticleModal(2)" class="text-xs font-semibold text-dskBlue hover:underline">
                            Xem chi tiết <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </button>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-slate-50 rounded border border-slate-200 overflow-hidden flex flex-col justify-between hover:border-dskBlue transition">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                            <img src="https://lh3.googleusercontent.com/d/19_hzNMKX6YYmqwl6LsH64J9cscmoCvmE"
                                 onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=19_hzNMKX6YYmqwl6LsH64J9cscmoCvmE&sz=w600';}else{this.src='https://placehold.co/500x320/0b4f8a/ffffff?text=Tin+Tuc+4';}"
                                 alt="Báo giá kính ốp bếp và cửa kính cường lực Đà Nẵng"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-3.5">
                            <h3 class="text-xs md:text-sm font-bold text-slate-800 hover:text-dskBlue leading-snug mb-2">
                                Tư vấn chọn màu Kính ốp bếp cường lực hợp phong thủy và bền màu theo thời gian
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Kính cường lực ốp bếp chịu nhiệt độ cao, không bám bẩn dầu mỡ, đa dạng màu sắc giúp căn bếp gia đình luôn sáng bóng.
                            </p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3.5">
                        <button onclick="openArticleModal(3)" class="text-xs font-semibold text-dskBlue hover:underline">
                            Xem chi tiết <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </button>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC CÁC ĐỐI TÁC CỦA CHÚNG TÔI ==================== -->
    <section class="py-6 bg-slate-100 border-t border-slate-200 w-full">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-line"></div>
                <h2 class="section-title-main">ĐỐI TÁC CỦA CHÚNG TÔI</h2>
                <div class="section-title-line"></div>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
                <div class="bg-white p-3.5 rounded border border-slate-200 flex flex-col items-center justify-center text-center shadow-sm">
                    <div class="text-sm font-extrabold text-dskBlue tracking-wide">XINGFA</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Xingfa Aluminium</div>
                </div>
                <div class="bg-white p-3.5 rounded border border-slate-200 flex flex-col items-center justify-center text-center shadow-sm">
                    <div class="text-sm font-extrabold text-dskRed tracking-wide">KINLONG</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Phụ kiện Kinlong</div>
                </div>
                <div class="bg-white p-3.5 rounded border border-slate-200 flex flex-col items-center justify-center text-center shadow-sm">
                    <div class="text-sm font-extrabold text-slate-800 tracking-wide">VVP THAILAND</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Phụ kiện kính VVP</div>
                </div>
                <div class="bg-white p-3.5 rounded border border-slate-200 flex flex-col items-center justify-center text-center shadow-sm">
                    <div class="text-sm font-extrabold text-dskBlue tracking-wide">HAFELE</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Phụ kiện Hafele</div>
                </div>
                <div class="bg-white p-3.5 rounded border border-slate-200 flex flex-col items-center justify-center text-center shadow-sm">
                    <div class="text-sm font-extrabold text-emerald-700 tracking-wide">PMA ALUMINIUM</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Nhôm hệ PMA</div>
                </div>
                <div class="bg-white p-3.5 rounded border border-slate-200 flex flex-col items-center justify-center text-center shadow-sm">
                    <div class="text-sm font-extrabold text-amber-600 tracking-wide">CHU LAI GLASS</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Phôi kính cường lực</div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== ĐƯA FANPAGE FACEBOOK & GOOGLE MAP RA NGOÀI TRANG CHỦ ==================== -->
    <section id="lien-he" class="py-8 bg-white border-t border-slate-200 w-full">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-line"></div>
                <h2 class="section-title-main">BẢN ĐỒ GOOGLE MAP & FANPAGE ĐSK WINDOW</h2>
                <div class="section-title-line"></div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
                <!-- Cột Google Map trực tiếp ngoài trang chủ (04 Nguyễn Đình Tứ, Phường An Khê, TP Đà Nẵng) -->
                <div class="lg:col-span-7 bg-slate-50 rounded-lg border border-slate-200 overflow-hidden flex flex-col">
                    <div class="p-3 bg-dskBlue text-white flex flex-wrap items-center justify-between gap-2 text-xs">
                        <span class="font-bold"><i class="fa-solid fa-map-location-dot mr-1.5 text-amber-300"></i>BẢN ĐỒ ĐƯỜNG ĐI: 04 Nguyễn Đình Tứ, Phường An Khê, TP Đà Nẵng</span>
                        <a href="https://www.google.com/maps/search/?api=1&query=04+Nguy%E1%BB%85n+%C4%90%C3%ACnh+T%E1%BB%A9,+Ph%C6%B0%E1%BB%9Dng+An+Kh%C3%AA,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener" class="bg-white text-dskBlue px-2.5 py-1 rounded font-semibold hover:bg-amber-300 transition">
                            Mở Google Maps lớn
                        </a>
                    </div>
                    <div class="w-full h-[320px] md:h-[360px]">
                        <iframe 
                            title="Bản đồ Công ty TNHH MTV ĐSK Window - 04 Nguyễn Đình Tứ, Phường An Khê, TP Đà Nẵng"
                            src="https://maps.google.com/maps?q=04%20Nguy%E1%BB%85n%20%C4%90%C3%ACnh%20T%E1%BB%A9,%20An%20Kh%C3%AA,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            allowfullscreen="" 
                            loading="lazy">
                        </iframe>
                    </div>
                </div>

                <!-- Cột Fanpage Facebook ngoài trang chủ -->
                <div class="lg:col-span-5 bg-slate-50 rounded-lg border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <div class="p-3 bg-[#1877F2] text-white flex items-center justify-between text-xs">
                        <span class="font-bold"><i class="fa-brands fa-facebook mr-1.5"></i>FANPAGE CHÍNH THỨC ĐSK WINDOW</span>
                        <a href="https://www.facebook.com/profile.php?id=100063244359184" target="_blank" rel="noopener" class="bg-white text-[#1877F2] px-2.5 py-1 rounded font-semibold hover:bg-slate-100 transition">
                            Theo dõi Fanpage
                        </a>
                    </div>

                    <div class="p-4 flex-1 flex flex-col justify-between space-y-3">
                        <!-- Thẻ Fanpage trực quan kết hợp khung nhúng Facebook Plugin -->
                        <div class="bg-white p-3.5 rounded border border-slate-200 shadow-sm">
                            <div class="flex items-center gap-3">
                                <img src="https://lh3.googleusercontent.com/d/1C_epiUnuYdo1ulRK6agWfUA_Qudc3H8o"
                                     onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=1C_epiUnuYdo1ulRK6agWfUA_Qudc3H8o&sz=w300';}else{this.src='https://placehold.co/80x80/0b4f8a/ffffff?text=DSK';}"
                                     alt="Logo Fanpage ĐSK Window"
                                     class="w-12 h-12 rounded-full object-contain border border-slate-200 p-0.5 shrink-0">
                                <div class="min-w-0">
                                    <a href="https://www.facebook.com/profile.php?id=100063244359184" target="_blank" rel="noopener" class="font-bold text-sm text-dskBlue hover:underline block truncate">
                                        CÔNG TY TNHH MTV ĐSK WINDOW
                                    </a>
                                    <p class="text-xs text-slate-500">Cửa Nhôm Xingfa & Nhôm Kính Đà Nẵng</p>
                                    <div class="flex items-center gap-2 mt-1">
                                        <a href="https://www.facebook.com/profile.php?id=100063244359184" target="_blank" rel="noopener" class="inline-flex items-center gap-1 text-[11px] bg-[#1877F2] text-white px-2.5 py-1 rounded font-medium">
                                            <i class="fa-brands fa-facebook-f"></i> Truy cập Fanpage
                                        </a>
                                        <a href="https://zalo.me/0907228282" target="_blank" rel="noopener" class="inline-flex items-center gap-1 text-[11px] bg-sky-600 text-white px-2.5 py-1 rounded font-medium">
                                            <i class="fa-solid fa-comment-dots"></i> Nhắn Zalo
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Khung Facebook Page Plugin -->
                        <div class="w-full overflow-hidden rounded border border-slate-200 bg-white flex justify-center">
                            <iframe 
                                title="Facebook Fanpage ĐSK Window"
                                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D100063244359184&tabs=timeline&width=340&height=180&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                                width="340" 
                                height="180" 
                                style="border:none;overflow:hidden;max-width:100%;" 
                                scrolling="no" 
                                frameborder="0" 
                                allowfullscreen="true" 
                                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                            </iframe>
                        </div>

                        <div class="text-xs text-slate-600 bg-dskLightBlue p-2.5 rounded border border-sky-200">
                            <i class="fa-solid fa-circle-info text-dskBlue mr-1"></i>
                            Cập nhật hình ảnh thi công thực tế hàng ngày tại Fanpage Facebook chính thức của <strong>ĐSK WINDOW</strong>.
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== FOOTER CHUẨN MẪU NGOCHANWINDOW.COM ==================== -->
    <footer class="bg-dskDarkBlue text-slate-200 pt-8 pb-6 border-t-4 border-amber-400 w-full">
        <div class="flatsome-container">
            <!-- Khối danh mục từ khóa SEO chân trang giống web mẫu -->
            <div class="grid grid-cols-1 md:grid-cols-3 gap-5 pb-6 mb-6 border-b border-white/15 text-xs">
                <div>
                    <h4 class="font-bold text-amber-300 uppercase mb-2">CỬA NHÔM XINGFA ĐÀ NẴNG</h4>
                    <ul class="space-y-1 text-slate-300">
                        <li><a href="#san-pham" onclick="filterProductsByCategory('cua-nhom-xingfa')" class="hover:text-white">• Cửa nhôm Xingfa 1 cánh Đà Nẵng</a></li>
                        <li><a href="#san-pham" onclick="filterProductsByCategory('cua-nhom-xingfa')" class="hover:text-white">• Cửa nhôm Xingfa 2 cánh Đà Nẵng</a></li>
                        <li><a href="#san-pham" onclick="filterProductsByCategory('cua-nhom-xingfa')" class="hover:text-white">• Cửa nhôm Xingfa 4 cánh Đà Nẵng</a></li>
                        <li><a href="#san-pham" onclick="filterProductsByCategory('cua-nhom-xingfa')" class="hover:text-white">• Cửa đi mở quay, mở lùa, xếp trượt Xingfa</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-bold text-amber-300 uppercase mb-2">CỬA NHỰA LÕI THÉP ĐÀ NẴNG</h4>
                    <ul class="space-y-1 text-slate-300">
                        <li><a href="#san-pham" onclick="filterProductsByCategory('cua-nhua-loi-thep')" class="hover:text-white">• Cửa nhựa lõi thép 1 cánh, 2 cánh, 4 cánh</a></li>
                        <li><a href="#san-pham" onclick="filterProductsByCategory('cua-nhua-loi-thep')" class="hover:text-white">• Cửa nhựa lõi thép phòng ngủ, nhà vệ sinh</a></li>
                        <li><a href="#san-pham" onclick="filterProductsByCategory('cua-nhua-loi-thep')" class="hover:text-white">• Cửa sổ nhựa lõi thép cách âm</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-bold text-amber-300 uppercase mb-2">HẠNG MỤC KÍNH CƯỜNG LỰC</h4>
                    <ul class="space-y-1 text-slate-300">
                        <li><a href="#san-pham" onclick="filterProductsByCategory('cua-kinh-tu-dong')" class="hover:text-white">• Cửa kính cường lực & Cửa kính tự động Đà Nẵng</a></li>
                        <li><a href="#san-pham" onclick="filterProductsByCategory('cau-thang-kinh')" class="hover:text-white">• Cầu thang kính & Lan can kính cường lực</a></li>
                        <li><a href="#san-pham" onclick="filterProductsByCategory('kinh-op-bep')" class="hover:text-white">• Kính màu ốp bếp & Phòng tắm kính Đà Nẵng</a></li>
                    </ul>
                </div>
            </div>

            <!-- Thông tin chính công ty -->
            <div class="grid grid-cols-1 md:grid-cols-12 gap-6 text-xs">
                <div class="md:col-span-5 space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <img src="https://lh3.googleusercontent.com/d/1C_epiUnuYdo1ulRK6agWfUA_Qudc3H8o"
                             onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=1C_epiUnuYdo1ulRK6agWfUA_Qudc3H8o&sz=w200';}else{this.src='https://placehold.co/80x80/ffffff/0b4f8a?text=DSK';}"
                             alt="Logo ĐSK Window"
                             class="w-10 h-10 rounded bg-white p-0.5 object-contain shrink-0">
                        <div>
                            <h3 class="font-extrabold text-sm text-white uppercase">CÔNG TY TNHH MỘT THÀNH VIÊN ĐSK WINDOW</h3>
                            <p class="text-amber-300 text-[11px]">Website: dskwindow.com | MST: 0401779739</p>
                        </div>
                    </div>
                    <p class="text-slate-300 leading-relaxed">
                        Chuyên tư vấn, thiết kế, sản xuất và thi công Cửa nhôm Xingfa, Cửa nhựa lõi thép, Cửa kính tự động, Cửa kính cường lực, Cầu thang kính, Kính ốp bếp, Phòng tắm kính tại Đà Nẵng.
                    </p>
                    <ul class="space-y-1.5 text-slate-200">
                        <li><i class="fa-solid fa-location-dot text-amber-400 mr-2"></i><strong>Địa chỉ:</strong> 04 Nguyễn Đình Tứ, Phường An Khê, TP Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone-volume text-amber-400 mr-2"></i><strong>Hotline / Zalo:</strong> <a href="tel:0907228282" class="text-amber-300 font-bold">0907.228.282</a></li>
                        <li><i class="fa-solid fa-globe text-amber-400 mr-2"></i><strong>Website:</strong> <a href="https://dskwindow.com" class="hover:underline">www.dskwindow.com</a></li>
                        <li><i class="fa-brands fa-facebook text-amber-400 mr-2"></i><strong>Fanpage:</strong> <a href="https://www.facebook.com/profile.php?id=100063244359184" target="_blank" rel="noopener" class="hover:underline">fb.com/100063244359184</a></li>
                    </ul>
                </div>

                <div class="md:col-span-4 space-y-2">
                    <h4 class="font-bold text-white uppercase text-sm mb-2">DANH MỤC DỊCH VỤ CHÍNH</h4>
                    <ul class="grid grid-cols-1 gap-1.5 text-slate-300">
                        <li><a href="#san-pham" onclick="filterProductsByCategory('cua-nhom-xingfa')" class="hover:text-amber-300">› Thi công Cửa Nhôm Xingfa Đà Nẵng</a></li>
                        <li><a href="#san-pham" onclick="filterProductsByCategory('cua-nhua-loi-thep')" class="hover:text-amber-300">› Thi công Cửa Nhựa Lõi Thép Đà Nẵng</a></li>
                        <li><a href="#san-pham" onclick="filterProductsByCategory('cua-kinh-tu-dong')" class="hover:text-amber-300">› Thi công Cửa Kính Tự Động & Cường Lực</a></li>
                        <li><a href="#san-pham" onclick="filterProductsByCategory('cau-thang-kinh')" class="hover:text-amber-300">› Thi công Cầu Thang Kính Đà Nẵng</a></li>
                        <li><a href="#san-pham" onclick="filterProductsByCategory('kinh-op-bep')" class="hover:text-amber-300">› Thi công Kính Ốp Bếp Đà Nẵng</a></li>
                        <li><a href="#san-pham" onclick="filterProductsByCategory('phong-tam-kinh')" class="hover:text-amber-300">› Thi công Phòng Tắm Kính Đà Nẵng</a></li>
                    </ul>
                </div>

                <div class="md:col-span-3 space-y-2">
                    <h4 class="font-bold text-white uppercase text-sm mb-2">HỖ TRỢ KHÁCH HÀNG</h4>
                    <div class="bg-white/10 p-3 rounded border border-white/15 space-y-2">
                        <div class="text-amber-300 font-bold">TƯ VẤN & BÁO GIÁ 24/7</div>
                        <div class="text-base font-extrabold text-white">0907.228.282</div>
                        <p class="text-[11px] text-slate-300">Khảo sát đo đạc và báo giá trực tiếp tại công trình ở TP Đà Nẵng.</p>
                        <a href="#form-bao-gia" class="inline-block w-full text-center bg-amber-400 text-slate-950 font-bold py-1.5 rounded text-xs hover:bg-amber-300 transition">
                            Gửi Yêu Cầu Báo Giá
                        </a>
                    </div>
                </div>
            </div>

            <div class="mt-6 pt-4 border-t border-white/15 text-center text-[11px] text-slate-400">
                Copyright © 2026 Bản quyền thuộc về <strong>CÔNG TY TNHH MỘT THÀNH VIÊN ĐSK WINDOW (dskwindow.com)</strong> - Địa chỉ: 04 Nguyễn Đình Tứ, Phường An Khê, TP Đà Nẵng.
            </div>
        </div>
    </footer>

    <!-- ==================== CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH PC & MOBILE ==================== -->
    <div class="fixed bottom-4 left-3 z-50 flex flex-col gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/profile.php?id=100063244359184" target="_blank" rel="noopener"
           class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-sm"></i>
            </span>
            <span class="text-xs font-bold pr-1 hidden sm:inline">Facebook</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a href="https://zalo.me/0907228282" target="_blank" rel="noopener"
           class="pulse-zalo flex items-center gap-2 bg-[#0068ff] hover:bg-blue-600 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-7 h-7 rounded-full bg-white text-[#0068ff] flex items-center justify-center font-extrabold text-[10px] shrink-0">
                Zalo
            </span>
            <span class="text-xs font-bold pr-1">Chat Zalo</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a href="tel:0907228282"
           class="pulse-hotline flex items-center gap-2 bg-dskRed hover:bg-red-700 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-7 h-7 rounded-full bg-white text-dskRed flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <span class="text-xs font-extrabold pr-1">0907.228.282</span>
        </a>
    </div>

    <!-- ==================== MODAL XEM CHI TIẾT SẢN PHẨM / BÀI VIẾT / THÔNG BÁO ==================== -->
    <div id="commonModal" class="fixed inset-0 bg-black/60 z-50 hidden items-center justify-center p-3">
        <div class="bg-white rounded-lg max-w-lg w-full overflow-hidden shadow-xl border border-slate-200">
            <div class="bg-dskBlue text-white px-4 py-3 flex items-center justify-between">
                <h3 id="modalTitle" class="font-bold text-sm">Thông tin chi tiết</h3>
                <button onclick="closeModal()" class="text-white hover:text-amber-300 text-lg leading-none">&times;</button>
            </div>
            <div id="modalBody" class="p-4 text-xs md:text-sm text-slate-700 space-y-3 max-h-[80vh] overflow-y-auto">
            </div>
            <div class="bg-slate-100 px-4 py-2.5 flex justify-end gap-2">
                <a href="tel:0907228282" class="bg-dskRed text-white text-xs font-bold px-3.5 py-1.5 rounded">
                    <i class="fa-solid fa-phone mr-1"></i>Gọi 0907.228.282
                </a>
                <button onclick="closeModal()" class="bg-slate-600 text-white text-xs font-semibold px-3.5 py-1.5 rounded">
                    Đóng
                </button>
            </div>
        </div>
    </div>

    <!-- ==================== JAVASCRIPT QUẢN LÝ DỮ LIỆU & TƯƠNG TÁC ==================== -->
    <script>
        /* 1. Danh sách 13 Sản phẩm thực tế từ 13 file Google Drive của ĐSK Window */
        const productsData = [
            {
                id: 1,
                driveId: '1do1PKpzoa5GIEjkObMrflqJHqtxRqC5u',
                name: 'Cửa đi mở quay 4 cánh nhôm Xingfa nhập khẩu chính hãng',
                category: 'cua-nhom-xingfa',
                categoryName: 'Cửa Nhôm Xingfa',
                price: 'Liên hệ: 0907.228.282'
            },
            {
                id: 2,
                driveId: '1_0OPEN23aiahMJJKTvxpzEF4xBkWv4Gv',
                name: 'Cửa đi mở quay 2 cánh nhôm Xingfa cao cấp tại Đà Nẵng',
                category: 'cua-nhom-xingfa',
                categoryName: 'Cửa Nhôm Xingfa',
                price: 'Liên hệ: 0907.228.282'
            },
            {
                id: 3,
                driveId: '1KyVcG2MZw_RD-VuaE5ODgjcVJvBV_jF9',
                name: 'Cửa đi xếp trượt nhôm Xingfa sang trọng cho mặt tiền',
                category: 'cua-nhom-xingfa',
                categoryName: 'Cửa Nhôm Xingfa',
                price: 'Liên hệ: 0907.228.282'
            },
            {
                id: 4,
                driveId: '1HYJsCgo2je2-Ln49KXHOqpcRzZOtxH6W',
                name: 'Cửa sổ mở hất kết hợp vách kính cố định nhôm Xingfa',
                category: 'cua-nhom-xingfa',
                categoryName: 'Cửa Nhôm Xingfa',
                price: 'Liên hệ: 0907.228.282'
            },
            {
                id: 5,
                driveId: '1Jtqz7YO9GY3xildzF_3wLK2ADMeImN7-',
                name: 'Cửa đi mở quay 1 cánh nhôm Xingfa phòng ngủ & ban công',
                category: 'cua-nhom-xingfa',
                categoryName: 'Cửa Nhôm Xingfa',
                price: 'Liên hệ: 0907.228.282'
            },
            {
                id: 6,
                driveId: '1-GyY9h3yJdvY5yZ91mSQvjiqT8EenGLe',
                name: 'Cửa nhựa lõi thép uPVC 4 cánh cách âm cách nhiệt cao cấp',
                category: 'cua-nhua-loi-thep',
                categoryName: 'Cửa Nhựa Lõi Thép',
                price: 'Liên hệ: 0907.228.282'
            },
            {
                id: 7,
                driveId: '1RgXZDMcfRLNfFQgdBpTGeUIzPXOC8ucz',
                name: 'Cửa nhựa lõi thép 2 cánh kết hợp kính cường lực an toàn',
                category: 'cua-nhua-loi-thep',
                categoryName: 'Cửa Nhựa Lõi Thép',
                price: 'Liên hệ: 0907.228.282'
            },
            {
                id: 8,
                driveId: '1dO_txhpwvwvqTX1ZAVsCvCq_54rCDQZN',
                name: 'Cửa kính tự động & Cửa kính cường lực mặt tiền showroom',
                category: 'cua-kinh-tu-dong',
                categoryName: 'Cửa Kính Tự Động',
                price: 'Liên hệ: 0907.228.282'
            },
            {
                id: 9,
                driveId: '1S_zC1nNmPhYGGpt4aOTVZlb1M3okigkd',
                name: 'Cửa kính cường lực bản lề sàn phụ kiện VVP chính hãng',
                category: 'cua-kinh-tu-dong',
                categoryName: 'Cửa Kính Tự Động',
                price: 'Liên hệ: 0907.228.282'
            },
            {
                id: 10,
                driveId: '1j10IYTaNCPMekLpE-3eqlT-JLXPeDB5x',
                name: 'Cầu thang kính cường lực tay vịn gỗ hiện đại tại Đà Nẵng',
                category: 'cau-thang-kinh',
                categoryName: 'Cầu Thang Kính',
                price: 'Liên hệ: 0907.228.282'
            },
            {
                id: 11,
                driveId: '1k1M5Xw-H0JGait9c2yjQ37mrsfs_fr_t',
                name: 'Lan can cầu thang kính cường lực trụ inox 304 bền đẹp',
                category: 'cau-thang-kinh',
                categoryName: 'Cầu Thang Kính',
                price: 'Liên hệ: 0907.228.282'
            },
            {
                id: 12,
                driveId: '19_hzNMKX6YYmqwl6LsH64J9cscmoCvmE',
                name: 'Kính màu ốp bếp cường lực chịu nhiệt dễ vệ sinh tại Đà Nẵng',
                category: 'kinh-op-bep',
                categoryName: 'Kính Ốp Bếp',
                price: 'Liên hệ: 0907.228.282'
            },
            {
                id: 13,
                driveId: '15huQBtVZfLCY0SXZegjtXNBQCK5I2ZCc',
                name: 'Phòng tắm kính cường lực vách tắm đứng phụ kiện inox 304',
                category: 'phong-tam-kinh',
                categoryName: 'Phòng Tắm Kính',
                price: 'Liên hệ: 0907.228.282'
            }
        ];

        /* 2. Danh sách 8 Dự án thực tế tại Đà Nẵng từ 8 file Google Drive */
        const projectsData = [
            {
                id: 1,
                driveId: '1Deg-ThCdcgcmCCvfyp69RiNRNj9LBZFU',
                title: 'Thi công hạng mục Cửa nhôm Xingfa Biệt thự cao cấp tại Đà Nẵng',
                type: 'nha-pho-biet-thu'
            },
            {
                id: 2,
                driveId: '1p4rJgvPNsO4UbJbiy_T3XHrSCwyvHHY7',
                title: 'Thi công Cửa nhôm kính & Vách kính mặt tiền Nhà phố tại Quận Thanh Khê, Đà Nẵng',
                type: 'nha-pho-biet-thu'
            },
            {
                id: 3,
                driveId: '1u10-Qq0lCjbpfkxtKZJVhZYt44gA4MOX',
                title: 'Dự án lắp đặt hệ thống Cửa nhôm Xingfa Khách sạn & Căn hộ biển Đà Nẵng',
                type: 'khach-san-can-ho'
            },
            {
                id: 4,
                driveId: '17FDL3ycY8hW1_SPq71M0Y1fOZ8oomThn',
                title: 'Thi công Cửa kính cường lực & Nhôm Xingfa Тòa nhà căn hộ tại Đà Nẵng',
                type: 'khach-san-can-ho'
            },
            {
                id: 5,
                driveId: '1eDOBNcO5m5CoXDd2yTXFCo_9EM0ZnRZ0',
                title: 'Hoàn thiện hạng mục Cửa đi mở quay & Cửa sổ nhôm Xingfa Nhà phố Cẩm Lệ, Đà Nẵng',
                type: 'nha-pho-biet-thu'
            },
            {
                id: 6,
                driveId: '19nQOIEdvDhQDbnkvZuITpH6WJrmT19X6',
                title: 'Thi công Vách kính mặt dựng & Cửa kính tự động Văn phòng công ty tại Đà Nẵng',
                type: 'thuong-mai-van-phong'
            },
            {
                id: 7,
                driveId: '1G-en0MsM_XtnFf2ClxAW4SxwR73ZjV9u',
                title: 'Lắp đặt Cầu thang kính, Phòng tắm kính & Cửa nhôm Xingfa Biệt thự Sơn Trà, Đà Nẵng',
                type: 'nha-pho-biet-thu'
            },
            {
                id: 8,
                driveId: '1OBRpk6tAcn4OfGCLWy_O_PcIQ4aob3rV',
                title: 'Thi công trọn gói Cửa nhôm kính Showroom & Công trình thương mại tại TP Đà Nẵng',
                type: 'thuong-mai-van-phong'
            }
        ];

        /* 3. Render Sản Phẩm (2 cột trên điện thoại, tên đầy đủ không tràn, không có nhãn dán trên ảnh) */
        function renderProducts(list) {
            const grid = document.getElementById('productGrid');
            if (!list.length) {
                grid.innerHTML = `<div class="col-span-full text-center py-8 text-xs text-slate-500">Không tìm thấy sản phẩm phù hợp. Vui lòng thử từ khóa khác.</div>`;
                return;
            }
            grid.innerHTML = list.map(item => `
                <div class="bg-white rounded border border-slate-200 overflow-hidden flex flex-col justify-between hover:border-dskBlue transition shadow-sm">
                    <div>
                        <div class="aspect-square w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openProductModal(${item.id})">
                            <img src="https://lh3.googleusercontent.com/d/${item.driveId}"
                                 onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=${item.driveId}&sz=w800';}else{this.src='https://placehold.co/500x500/0b4f8a/ffffff?text=DSK+WINDOW';}"
                                 alt="${item.name}"
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 md:p-3.5">
                            <div class="text-[10.5px] text-slate-500 font-medium mb-1">${item.categoryName}</div>
                            <h3 onclick="openProductModal(${item.id})" class="product-title-full text-xs md:text-sm font-bold text-slate-800 hover:text-dskBlue cursor-pointer mb-1.5">
                                ${item.name}
                            </h3>
                            <div class="text-xs font-extrabold text-dskRed">${item.price}</div>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 md:px-3.5 md:pb-3.5 pt-1 flex items-center gap-1.5">
                        <a href="#form-bao-gia" onclick="prefillQuote('${item.name.replace(/'/g, "\\'")}')" class="w-full text-center bg-dskBlue hover:bg-dskDarkBlue text-white text-[11px] md:text-xs font-semibold py-1.5 px-2 rounded transition">
                            Nhận Báo Giá
                        </a>
                    </div>
                </div>
            `).join('');
        }

        /* 4. Lọc Sản Phẩm theo Danh Mục */
        function filterProductsByCategory(cat) {
            document.querySelectorAll('.cat-filter-btn').forEach(btn => {
                if (btn.dataset.cat === cat) {
                    btn.className = 'cat-filter-btn cat-pill-btn bg-dskBlue text-white';
                } else {
                    btn.className = 'cat-filter-btn cat-pill-btn bg-slate-100 text-slate-700 hover:bg-dskLightBlue hover:text-dskBlue';
                }
            });
            const selectEl = document.getElementById('headerCatSelect');
            if (selectEl) selectEl.value = cat;

            if (cat === 'all') {
                renderProducts(productsData);
            } else {
                renderProducts(productsData.filter(p => p.category === cat));
            }
        }

        /* 5. Tìm kiếm Sản Phẩm */
        function searchProducts(keyword) {
            const q = (keyword || '').trim().toLowerCase();
            if (!q) {
                renderProducts(productsData);
                return;
            }
            const filtered = productsData.filter(p =>
                p.name.toLowerCase().includes(q) || p.categoryName.toLowerCase().includes(q)
            );
            renderProducts(filtered);
        }

        /* 6. Render 8 Dự Án Thực Tế tại Đà Nẵng */
        function renderProjects(list) {
            const grid = document.getElementById('projectGrid');
            grid.innerHTML = list.map(proj => `
                <div class="bg-slate-50 rounded border border-slate-200 overflow-hidden flex flex-col justify-between hover:border-dskBlue transition shadow-sm">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/${proj.driveId}"
                             onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=${proj.driveId}&sz=w800';}else{this.src='https://placehold.co/600x450/073763/ffffff?text=DU+AN+DA+NANG';}"
                             alt="${proj.title}"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 md:p-3.5">
                        <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 leading-snug">
                            ${proj.title}
                        </h3>
                        <p class="text-[11px] text-dskBlue font-medium mt-1">
                            Thi công: ĐSK WINDOW - TP Đà Nẵng
                        </p>
                    </div>
                </div>
            `).join('');
        }

        function filterProjects(type) {
            document.querySelectorAll('.proj-filter-btn').forEach(btn => {
                if (btn.dataset.proj === type) {
                    btn.className = 'proj-filter-btn cat-pill-btn bg-dskBlue text-white';
                } else {
                    btn.className = 'proj-filter-btn cat-pill-btn bg-slate-100 text-slate-700 hover:bg-dskLightBlue hover:text-dskBlue';
                }
            });
            if (type === 'all') {
                renderProjects(projectsData);
            } else {
                renderProjects(projectsData.filter(item => item.type === type));
            }
        }

        /* 7. Điều khiển Banner Tự Trượt (2 Slide đồng bộ cả bản Máy Tính và bản Điện Thoại) */
        let currentBannerIndex = 0;
        const totalBannerSlides = 2;

        function updateBannerDisplay() {
            const desktopSlides = document.querySelectorAll('.desktop-slide');
            const mobileSlides = document.querySelectorAll('.mobile-slide');

            desktopSlides.forEach((slide, idx) => {
                if (idx === currentBannerIndex) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                }
            });

            mobileSlides.forEach((slide, idx) => {
                if (idx === currentBannerIndex) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                }
            });

            for (let i = 0; i < totalBannerSlides; i++) {
                const dot = document.getElementById('dot-' + i);
                if (dot) {
                    dot.className = (i === currentBannerIndex)
                        ? 'w-2.5 h-2.5 rounded-full bg-amber-400 transition'
                        : 'w-2.5 h-2.5 rounded-full bg-white/50 transition';
                }
            }
        }

        function changeBannerSlide(step) {
            currentBannerIndex = (currentBannerIndex + step + totalBannerSlides) % totalBannerSlides;
            updateBannerDisplay();
        }

        function goToBannerSlide(index) {
            currentBannerIndex = index;
            updateBannerDisplay();
        }

        setInterval(() => {
            changeBannerSlide(1);
        }, 5500);

        /* 8. Menu Điện Thoại & Modal tương tác */
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            drawer.classList.toggle('hidden');
        }

        function prefillQuote(productName) {
            const noteEl = document.getElementById('qNote');
            if (noteEl) {
                noteEl.value = 'Tôi cần tư vấn và báo giá mẫu: ' + productName;
            }
        }

        function openProductModal(id) {
            const item = productsData.find(p => p.id === id);
            if (!item) return;
            document.getElementById('modalTitle').textContent = item.categoryName + ' - ĐSK WINDOW';
            document.getElementById('modalBody').innerHTML = `
                <div class="rounded overflow-hidden border border-slate-200 bg-slate-100 aspect-[4/3]">
                    <img src="https://lh3.googleusercontent.com/d/${item.driveId}"
                         onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='https://drive.google.com/thumbnail?id=${item.driveId}&sz=w800';}else{this.src='https://placehold.co/600x450/0b4f8a/ffffff?text=DSK+WINDOW';}"
                         alt="${item.name}"
                         class="w-full h-full object-cover">
                </div>
                <h4 class="font-bold text-base text-dskBlue">${item.name}</h4>
                <p class="text-xs text-slate-600">
                    Sản phẩm được gia công và lắp đặt trực tiếp bởi <strong>CÔNG TY TNHH MỘT THÀNH VIÊN ĐSK WINDOW</strong> tại Đà Nẵng. Cam kết sử dụng thanh nhôm và phụ kiện đồng bộ chính hãng, bảo hành dài hạn.
                </p>
                <div class="bg-slate-50 p-3 rounded border border-slate-200 text-xs space-y-1">
                    <div><strong>Đơn giá:</strong> Tính theo m² thực tế công trình</div>
                    <div><strong>Địa chỉ xưởng & văn phòng:</strong> 04 Nguyễn Đình Tứ, Phường An Khê, TP Đà Nẵng</div>
                    <div><strong>Hotline tư vấn:</strong> <span class="text-dskRed font-bold">0907.228.282</span></div>
                </div>
            `;
            const modal = document.getElementById('commonModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        const articlesContent = [
            {
                title: 'Cửa nhôm Xingfa có phù hợp với khí hậu miền Trung & Đà Nẵng không?',
                content: 'Đà Nẵng và khu vực miền Trung thường xuyên chịu ảnh hưởng của nắng nóng mùa hè và mưa bão vào mùa mưa. Cửa nhôm Xingfa nhập khẩu với cấu trúc khoang rỗng có các đường gân gia cường lực, kết hợp hệ gioăng kép EPDM và phụ kiện Kinlong đồng bộ giúp chống ngấm nước mưa 100%, chịu được áp lực gió lớn và cách âm, cách nhiệt cực tốt.'
            },
            {
                title: 'Kinh nghiệm chọn cửa nhôm Xingfa chính hãng tiết kiệm năng lượng cho nhà phố',
                content: 'Khi lựa chọn cửa nhôm Xingfa cho nhà phố hay biệt thự, quý khách nên lưu ý kiểm tra độ dày thanh nhôm (từ 1.4mm - 2.0mm tùy hệ cửa sổ hay cửa đi), bề mặt sơn tĩnh điện sắc nét và lựa chọn đơn vị trực tiếp sản xuất thi công có địa chỉ rõ ràng tại Đà Nẵng như ĐSK Window (04 Nguyễn Đình Tứ, P. An Khê).'
            },
            {
                title: 'Xu hướng lắp đặt Cầu thang kính cường lực & Phòng tắm kính hiện đại tại Đà Nẵng',
                content: 'Cầu thang kính cường lực 10mm - 12mm kết hợp tay vịn gỗ hoặc inox 304 cùng phòng tắm kính vách đứng đang là giải pháp tối ưu giúp không gian nhà phố Đà Nẵng trở nên rộng rãi, sang trọng và hiện đại hơn.'
            },
            {
                title: 'Tư vấn chọn màu Kính ốp bếp cường lực hợp phong thủy và bền màu',
                content: 'Kính màu ốp bếp cường lực được phủ sơn chịu nhiệt cao cấp giúp bề mặt tường bếp luôn sạch sẽ, không có mạch vữa, dễ dàng lau sạch dầu mỡ và mang lại điểm nhấn thẩm mỹ tinh tế cho gian bếp.'
            }
        ];

        function openArticleModal(idx) {
            const art = articlesContent[idx];
            if (!art) return;
            document.getElementById('modalTitle').textContent = 'Tin tức nhôm kính - ĐSK WINDOW';
            document.getElementById('modalBody').innerHTML = `
                <h4 class="font-bold text-base text-dskBlue">${art.title}</h4>
                <p class="leading-relaxed text-slate-700">${art.content}</p>
                <div class="bg-dskLightBlue p-3 rounded border border-sky-200 text-xs">
                    Quý khách cần tư vấn chi tiết và khảo sát miễn phí tại Đà Nẵng vui lòng liên hệ <strong>CÔNG TY TNHH MTV ĐSK WINDOW</strong> qua số điện thoại <strong>0907.228.282</strong>.
                </div>
            `;
            const modal = document.getElementById('commonModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('qName').value;
            const phone = document.getElementById('qPhone').value;
            const category = document.getElementById('qCategory').value;
            const address = document.getElementById('qAddress').value || 'TP Đà Nẵng';

            document.getElementById('modalTitle').textContent = 'Đã gửi yêu cầu báo giá thành công!';
            document.getElementById('modalBody').innerHTML = `
                <div class="text-center py-2 space-y-2">
                    <div class="w-12 h-12 rounded-full bg-emerald-100 text-emerald-600 flex items-center justify-center mx-auto">
                        <i class="fa-solid fa-check text-xl"></i>
                    </div>
                    <h4 class="font-bold text-base text-dskBlue">Cảm ơn quý khách ${name}!</h4>
                    <p class="text-xs text-slate-600">
                        <strong>CÔNG TY TNHH MỘT THÀNH VIÊN ĐSK WINDOW</strong> đã tiếp nhận yêu cầu báo giá hạng mục <strong>${category}</strong> tại <strong>${address}</strong> (SĐT: <strong>${phone}</strong>).
                    </p>
                    <p class="text-xs text-slate-600">
                        Bộ phận kỹ thuật của chúng tôi sẽ liên hệ lại ngay hoặc quý khách có thể kết nối trực tiếp qua Hotline/Zalo: <strong class="text-dskRed">0907.228.282</strong>.
                    </p>
                </div>
            `;
            const modal = document.getElementById('commonModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
            document.getElementById('quoteRequestForm').reset();
        }

        function closeModal() {
            const modal = document.getElementById('commonModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        /* Khởi tạo dữ liệu khi tải trang */
        window.onload = function () {
            renderProducts(productsData);
            renderProjects(projectsData);
        };
    </script>
</body>
</html>
