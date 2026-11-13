<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG LÝ CÔNG QUẢNG - lycongquang.com</title>
    <meta name="description" content="CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG LÝ CÔNG QUẢNG chuyên Thiết kế Kiến trúc - Nội thất - Thi công phần thô - Xây nhà trọn gói uy tín tại Đà Nẵng. Hotline: 0905.539.892">
    <meta name="keywords" content="Lý Công Quảng, xây dựng Lý Công Quảng, thiết kế kiến trúc Đà Nẵng, xây nhà trọn gói Đà Nẵng, thi công phần thô Đà Nẵng, lycongquang.com">
    
    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://lycongquang.com/">
    <meta property="og:site_name" content="lycongquang.com">
    <meta property="og:title" content="CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG LÝ CÔNG QUẢNG | Thiết Kế & Xây Dựng Trọn Gói">
    <meta property="og:description" content="Chuyên Thiết kế Kiến trúc, Nội thất, Thi công phần thô & Xây dựng trọn gói Khách sạn, Biệt thự, Nhà phố, Văn phòng tại Đà Nẵng. Địa chỉ: 11 Đoàn Nguyễn Thục, P. Cẩm Lệ, TP Đà Nẵng. ĐT: 0905.539.892">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1p5rawwdWkf8N9dCq2Lxr0m5r8yL2I6ak">
    <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1p5rawwdWkf8N9dCq2Lxr0m5r8yL2I6ak">
    <meta property="og:image:width" content="800">
    <meta property="og:image:height" content="800">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG LÝ CÔNG QUẢNG">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1p5rawwdWkf8N9dCq2Lxr0m5r8yL2I6ak">
    <link rel="icon" href="https://lh3.googleusercontent.com/d/1p5rawwdWkf8N9dCq2Lxr0m5r8yL2I6ak" type="image/png">
    <link rel="apple-touch-icon" href="https://lh3.googleusercontent.com/d/1p5rawwdWkf8N9dCq2Lxr0m5r8yL2I6ak">

    <!-- Tailwind CSS & Font Awesome & Google Fonts (Inter / Montserrat chuẩn Flatsome) -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            DEFAULT: '#16355d', // Xanh kiến trúc chủ đạo theo tông logo
                            dark: '#0f2542',
                            light: '#245086',
                            accent: '#d97706',  // Vàng đồng / Cam kiến trúc nổi bật
                            gold: '#b45309'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Khống chế tuyệt đối chống tràn viền ngang và lệch phải */
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

        /* Khung chuẩn Flatsome UX Builder: Chiều ngang 95% trên máy tính */
        .flatsome-container {
            width: 100%;
            padding-left: 12px;
            padding-right: 12px;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Tối ưu Menu Danh mục trên máy tính: chữ nhỏ gọn, nằm liền trên 1 hàng, không gãy dòng tên danh mục */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: flex-end;
            gap: 2px;
        }
        @media (min-width: 1200px) {
            .desktop-nav-list {
                flex-wrap: nowrap;
                gap: 4px;
            }
        }
        .desktop-nav-item {
            white-space: nowrap !important;
            font-size: 12px;
            font-weight: 600;
            padding: 6px 8px;
            border-radius: 6px;
            color: #1e293b;
            transition: all 0.2s ease;
            text-transform: uppercase;
            letter-spacing: 0.01em;
            line-height: 1.2;
        }
        @media (min-width: 1366px) {
            .desktop-nav-item {
                font-size: 12.5px;
                padding: 7px 10px;
            }
        }
        .desktop-nav-item:hover, .desktop-nav-item.active {
            color: #16355d;
            background-color: #f1f5f9;
        }

        /* Thanh danh mục lọc ở trang chủ nhỏ gọn, không tràn viền */
        .cat-filter-btn {
            white-space: nowrap !important;
            font-size: 11.5px;
            font-weight: 600;
            padding: 6px 11px;
            border-radius: 6px;
            border: 1px solid #cbd5e1;
            background: #ffffff;
            color: #334155;
            transition: all 0.2s ease;
            cursor: pointer;
        }
        .cat-filter-btn:hover, .cat-filter-btn.active {
            background: #16355d;
            color: #ffffff;
            border-color: #16355d;
        }

        /* Tiêu đề Section chuẩn Flatsome (Section Title) */
        .ux-section-title {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 1.25rem;
            text-align: center;
        }
        .ux-section-title b {
            display: block;
            flex: 1;
            height: 2px;
            background-color: #cbd5e1;
            max-width: 120px;
        }
        .ux-section-title span {
            padding: 0 14px;
            font-weight: 800;
            color: #16355d;
            text-transform: uppercase;
            letter-spacing: 0.02em;
        }

        /* Hiệu ứng mượt cho ảnh trong Box Flatsome */
        .ux-box-image {
            overflow: hidden;
            background-color: #e2e8f0;
        }
        .ux-box-image img {
            transition: transform 0.4s ease;
        }
        .ux-product-box:hover .ux-box-image img {
            transform: scale(1.04);
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(220, 38, 38, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(220, 38, 38, 0); }
        }
        .animate-hotline {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="w-full overflow-x-hidden">

    <!-- =====================================================================
         1. TOP BAR (Thông tin địa chỉ, tên miền & SĐT - Chuẩn Flatsome)
         ===================================================================== -->
    <div class="bg-brand-dark text-white text-[11px] sm:text-xs py-1.5 border-b border-slate-700 w-full">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 overflow-hidden">
                <span class="truncate">
                    <i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>
                    11 Đoàn Nguyễn Thục, Phường Cẩm Lệ, TP Đà Nẵng
                </span>
                <span class="hidden md:inline-block text-slate-400">|</span>
                <span class="hidden md:inline-block">
                    <i class="fa-solid fa-globe text-amber-400 mr-1"></i>
                    Website: <strong>lycongquang.com</strong>
                </span>
            </div>
            <div class="flex items-center gap-3 ml-auto">
                <span>
                    <i class="fa-solid fa-phone-volume text-amber-400 mr-1"></i>
                    Hotline: <strong class="text-amber-300">0905.539.892</strong>
                </span>
                <span class="hidden sm:inline-block text-slate-400">|</span>
                <a href="https://www.facebook.com/profile.php?id=61554027984574" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300 transition hidden sm:inline-flex items-center gap-1">
                    <i class="fa-brands fa-facebook"></i> Fanpage
                </a>
            </div>
        </div>
    </div>

    <!-- =====================================================================
         2. HEADER & NAVIGATION (Logo nhỏ gọn, KHÔNG để nút gọi ngay tránh tràn viền)
         ===================================================================== -->
    <header class="bg-white shadow-sm sticky top-0 z-40 w-full border-b border-slate-200">
        <div class="flatsome-container py-2">
            <div class="flex items-center justify-between gap-2">
                <!-- Logo chỉnh gọn nhỏ lại + Tên công ty -->
                <a href="#" class="flex items-center gap-2.5 min-w-0 shrink-0 max-w-[82%] sm:max-w-none">
                    <img 
                        src="https://lh3.googleusercontent.com/d/1p5rawwdWkf8N9dCq2Lxr0m5r8yL2I6ak" 
                        onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1p5rawwdWkf8N9dCq2Lxr0m5r8yL2I6ak&sz=w400';"
                        alt="Logo Công Ty TNHH Kiến Trúc Và Xây Dựng Lý Công Quảng" 
                        class="h-9 w-9 sm:h-11 sm:w-11 object-contain rounded border border-slate-200 bg-white p-0.5 shrink-0"
                    >
                    <div class="min-w-0">
                        <div class="text-[11px] sm:text-[13px] font-extrabold text-brand leading-tight uppercase tracking-tight">
                            CÔNG TY TNHH KIẾN TRÚC & XD LÝ CÔNG QUẢNG
                        </div>
                        <div class="text-[10px] sm:text-[11px] text-slate-500 font-medium leading-tight mt-0.5">
                            lycongquang.com • Kiến Tạo Tổ Ấm Bền Vững
                        </div>
                    </div>
                </a>

                <!-- Menu Danh Mục Máy Tính: chữ nhỏ gọn, viết liền trên 1 hàng (hoặc xuống hàng 2 nguyên cụm, không gãy chữ) -->
                <nav class="hidden lg:block flex-1 min-w-0 pl-2">
                    <ul class="desktop-nav-list">
                        <li><a href="#trang-chu" class="desktop-nav-item active">Trang chủ</a></li>
                        <li><a href="#gioi-thieu" class="desktop-nav-item">Giới thiệu</a></li>
                        <li><a href="#linh-vuc" class="desktop-nav-item">Lĩnh vực hoạt động</a></li>
                        <li><a href="#cong-trinh-thuc-te" class="desktop-nav-item">Công trình thực tế</a></li>
                        <li><a href="#du-an-da-nang" class="desktop-nav-item">Dự án Đà Nẵng</a></li>
                        <li><a href="#mau-thiet-ke" class="desktop-nav-item">Mẫu thiết kế</a></li>
                        <li><a href="#bao-gia" class="desktop-nav-item">Báo giá</a></li>
                        <li><a href="#tin-tuc" class="desktop-nav-item">Bài viết</a></li>
                        <li><a href="#doi-tac" class="desktop-nav-item">Đối tác</a></li>
                        <li><a href="#lien-he" class="desktop-nav-item">Liên hệ</a></li>
                    </ul>
                </nav>

                <!-- Nút mở Menu trên Điện Thoại (Không để nút Gọi ngay trên Header) -->
                <button id="mobileMenuBtn" onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-md text-brand hover:bg-slate-100 border border-slate-200 shrink-0">
                    <i id="mobileMenuIcon" class="fa-solid fa-bars text-lg"></i>
                </button>
            </div>

            <!-- Danh mục Menu trên Điện thoại (Chia lưới 2 cột gọn đẹp, không tràn viền) -->
            <div id="mobileMenuPanel" class="hidden lg:hidden mt-2 pt-2 border-t border-slate-200 pb-1">
                <div class="grid grid-cols-2 gap-1.5 text-xs font-semibold">
                    <a href="#trang-chu" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-brand flex items-center gap-1.5">
                        <i class="fa-solid fa-house text-[11px] text-amber-600"></i> Trang chủ
                    </a>
                    <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-50 text-slate-700 hover:bg-slate-100 flex items-center gap-1.5">
                        <i class="fa-solid fa-building text-[11px] text-amber-600"></i> Giới thiệu
                    </a>
                    <a href="#linh-vuc" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-50 text-slate-700 hover:bg-slate-100 flex items-center gap-1.5">
                        <i class="fa-solid fa-compass-drafting text-[11px] text-amber-600"></i> Lĩnh vực hoạt động
                    </a>
                    <a href="#cong-trinh-thuc-te" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-50 text-slate-700 hover:bg-slate-100 flex items-center gap-1.5">
                        <i class="fa-solid fa-helmet-safety text-[11px] text-amber-600"></i> Công trình thực tế
                    </a>
                    <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-50 text-slate-700 hover:bg-slate-100 flex items-center gap-1.5">
                        <i class="fa-solid fa-city text-[11px] text-amber-600"></i> Dự án Đà Nẵng
                    </a>
                    <a href="#mau-thiet-ke" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-50 text-slate-700 hover:bg-slate-100 flex items-center gap-1.5">
                        <i class="fa-solid fa-layer-group text-[11px] text-amber-600"></i> Mẫu thiết kế
                    </a>
                    <a href="#bao-gia" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-50 text-slate-700 hover:bg-slate-100 flex items-center gap-1.5">
                        <i class="fa-solid fa-file-invoice-dollar text-[11px] text-amber-600"></i> Báo giá xây dựng
                    </a>
                    <a href="#tin-tuc" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-50 text-slate-700 hover:bg-slate-100 flex items-center gap-1.5">
                        <i class="fa-solid fa-newspaper text-[11px] text-amber-600"></i> Bài viết
                    </a>
                    <a href="#doi-tac" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-50 text-slate-700 hover:bg-slate-100 flex items-center gap-1.5">
                        <i class="fa-solid fa-handshake text-[11px] text-amber-600"></i> Đối tác
                    </a>
                    <a href="#lien-he" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-50 text-slate-700 hover:bg-slate-100 flex items-center gap-1.5">
                        <i class="fa-solid fa-map-location-dot text-[11px] text-amber-600"></i> Liên hệ & Bản đồ
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- =====================================================================
         3. UX BUILDER SLIDER: 2 ẢNH BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU
            - Thiết kế riêng Banner Máy Tính (md:block) và Banner Điện Thoại (md:hidden)
            - Chữ thu nhỏ gọn nằm trọn bên trong khung ảnh banner, tuyệt đối không tràn viền
         ===================================================================== -->
    <section id="trang-chu" class="w-full py-3 bg-white border-b border-slate-200">
        <div class="flatsome-container">
            <div class="relative w-full overflow-hidden rounded-xl shadow-md bg-brand-dark">

                <!-- ================= BẢN MÁY TÍNH (DESKTOP BANNERS - Cao bằng nhau 400px) ================= -->
                <div class="hidden md:block relative w-full h-[400px]">
                    <!-- Desktop Slide 1 -->
                    <div id="desktop-slide-0" class="transition-opacity duration-700 ease-in-out opacity-100 absolute inset-0 w-full h-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk&sz=w1600';"
                            alt="Banner 1 Lý Công Quảng Desktop" 
                            class="w-full h-full object-cover object-center"
                        >
                        <div class="absolute inset-0 bg-gradient-to-r from-[#0c1f38]/95 via-[#16355d]/85 to-transparent flex items-center">
                            <!-- Khung chữ thu gọn nằm hoàn toàn bên trong ảnh banner -->
                            <div class="w-[65%] max-w-2xl pl-12 pr-6 py-6 text-white">
                                <div class="inline-flex items-center gap-2 px-3 py-1 rounded bg-amber-500/20 border border-amber-400/40 text-amber-300 text-xs font-semibold mb-2.5">
                                    <i class="fa-solid fa-award"></i> UY TÍN – CHẤT LƯỢNG – ĐÚNG TIẾN ĐỘ TẠI ĐÀ NẴNG
                                </div>
                                <h1 class="text-xl lg:text-2xl font-extrabold leading-snug uppercase tracking-wide text-white mb-2">
                                    CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG LÝ CÔNG QUẢNG
                                </h1>
                                <p class="text-xs lg:text-sm text-slate-200 leading-relaxed mb-4">
                                    Chuyên Thiết kế Kiến trúc – Nội thất – Thi công phần thô & Xây nhà trọn gói Khách sạn, Căn hộ, Biệt thự, Nhà phố, Văn phòng tại Đà Nẵng. Đặt chữ <strong>"TÂM"</strong> trong từng công trình.
                                </p>
                                <div class="grid grid-cols-3 gap-2.5 mb-4 max-w-lg">
                                    <div class="bg-white/10 backdrop-blur-sm border border-white/15 rounded-lg p-2">
                                        <div class="text-amber-400 font-bold text-xs">Thiết Kế Kiến Trúc</div>
                                        <div class="text-[11px] text-slate-200">Tối ưu công năng 3D</div>
                                    </div>
                                    <div class="bg-white/10 backdrop-blur-sm border border-white/15 rounded-lg p-2">
                                        <div class="text-amber-400 font-bold text-xs">Thi Công Trọn Gói</div>
                                        <div class="text-[11px] text-slate-200">Vật tư chính hãng 100%</div>
                                    </div>
                                    <div class="bg-white/10 backdrop-blur-sm border border-white/15 rounded-lg p-2">
                                        <div class="text-amber-400 font-bold text-xs">Bảo Hành Dài Hạn</div>
                                        <div class="text-[11px] text-slate-200">Kết cấu bền vững</div>
                                    </div>
                                </div>
                                <div class="flex flex-wrap items-center gap-3 text-xs text-slate-200 bg-black/30 px-3.5 py-2 rounded-lg border border-white/10 inline-flex">
                                    <span><i class="fa-solid fa-phone text-amber-400 mr-1"></i> Hotline: <strong>0905.539.892</strong></span>
                                    <span>•</span>
                                    <span><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i> 11 Đoàn Nguyễn Thục, P. Cẩm Lệ, TP Đà Nẵng</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Desktop Slide 2 -->
                    <div id="desktop-slide-1" class="transition-opacity duration-700 ease-in-out opacity-0 pointer-events-none absolute inset-0 w-full h-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1PjtEF4hlMU_42b438GmEQhYZTba75kRJ" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1PjtEF4hlMU_42b438GmEQhYZTba75kRJ&sz=w1600';"
                            alt="Banner 2 Lý Công Quảng Desktop" 
                            class="w-full h-full object-cover object-center"
                        >
                        <div class="absolute inset-0 bg-gradient-to-r from-[#0c1f38]/95 via-[#16355d]/85 to-transparent flex items-center">
                            <div class="w-[65%] max-w-2xl pl-12 pr-6 py-6 text-white">
                                <div class="inline-flex items-center gap-2 px-3 py-1 rounded bg-amber-500/20 border border-amber-400/40 text-amber-300 text-xs font-semibold mb-2.5">
                                    <i class="fa-solid fa-helmet-safety"></i> GIẢI PHÁP XÂY DỰNG TỐI ƯU – TIẾT KIỆM CHI PHÍ
                                </div>
                                <h2 class="text-xl lg:text-2xl font-extrabold leading-snug uppercase tracking-wide text-white mb-2">
                                    THIẾT KẾ & THI CÔNG TRỌN GÓI NHÀ PHỐ – BIỆT THỰ – CĂN HỘ
                                </h2>
                                <p class="text-xs lg:text-sm text-slate-200 leading-relaxed mb-4">
                                    Miễn phí 100% hồ sơ thiết kế và giấy phép xây dựng khi ký hợp đồng thi công trọn gói. Giám sát kỹ thuật chặt chẽ, minh bạch vật tư, cam kết không phát sinh chi phí.
                                </p>
                                <div class="grid grid-cols-3 gap-2.5 mb-4 max-w-lg">
                                    <div class="bg-white/10 backdrop-blur-sm border border-white/15 rounded-lg p-2">
                                        <div class="text-amber-400 font-bold text-xs">Khách Sạn - Căn Hộ</div>
                                        <div class="text-[11px] text-slate-200">Hiệu suất đầu tư cao</div>
                                    </div>
                                    <div class="bg-white/10 backdrop-blur-sm border border-white/15 rounded-lg p-2">
                                        <div class="text-amber-400 font-bold text-xs">Nhà Phố - Biệt Thự</div>
                                        <div class="text-[11px] text-slate-200">Kiến trúc hiện đại</div>
                                    </div>
                                    <div class="bg-white/10 backdrop-blur-sm border border-white/15 rounded-lg p-2">
                                        <div class="text-amber-400 font-bold text-xs">Thi Công Nội Thất</div>
                                        <div class="text-[11px] text-slate-200">Sang trọng & tinh tế</div>
                                    </div>
                                </div>
                                <div class="flex flex-wrap items-center gap-3 text-xs text-slate-200 bg-black/30 px-3.5 py-2 rounded-lg border border-white/10 inline-flex">
                                    <span><i class="fa-solid fa-globe text-amber-400 mr-1"></i> Website: <strong>lycongquang.com</strong></span>
                                    <span>•</span>
                                    <span><i class="fa-solid fa-phone text-amber-400 mr-1"></i> Tư vấn miễn phí 24/7: <strong>0905.539.892</strong></span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- ================= BẢN ĐIỆN THOẠI (MOBILE BANNERS RIÊNG BIỆT - Cao bằng nhau 225px) ================= -->
                <!-- Thiết kế mới riêng cho điện thoại: chữ nhỏ gọn nằm trọn trong khung, không tràn viền -->
                <div class="block md:hidden relative w-full h-[225px]">
                    <!-- Mobile Slide 1 -->
                    <div id="mobile-slide-0" class="transition-opacity duration-700 ease-in-out opacity-100 absolute inset-0 w-full h-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW&sz=w800';"
                            alt="Banner Điện Thoại 1 Lý Công Quảng" 
                            class="w-full h-full object-cover object-center"
                        >
                        <div class="absolute inset-0 bg-gradient-to-t from-[#0b1e36]/95 via-[#0f2542]/85 to-[#0f2542]/60 p-3.5 flex flex-col justify-center items-center text-center">
                            <div class="w-full max-w-[94%] mx-auto border border-amber-400/30 bg-black/25 backdrop-blur-[2px] rounded-lg p-2.5 text-white">
                                <div class="text-[10px] font-semibold text-amber-300 uppercase tracking-wider mb-1">
                                    KIẾN TRÚC & XÂY DỰNG ĐÀ NẴNG
                                </div>
                                <h2 class="text-[12.5px] font-extrabold uppercase leading-snug text-white mb-1">
                                    CÔNG TY TNHH KIẾN TRÚC & XD LÝ CÔNG QUẢNG
                                </h2>
                                <p class="text-[10.5px] text-slate-200 leading-tight mb-2">
                                    Thiết kế Kiến trúc • Thi công phần thô • Xây nhà trọn gói Khách sạn, Biệt thự, Nhà phố, Căn hộ.
                                </p>
                                <div class="text-[10px] text-amber-200 font-medium bg-white/10 rounded py-1 px-2">
                                    <i class="fa-solid fa-phone mr-1"></i>0905.539.892 • 11 Đoàn Nguyễn Thục, Cẩm Lệ, ĐN
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Mobile Slide 2 -->
                    <div id="mobile-slide-1" class="transition-opacity duration-700 ease-in-out opacity-0 pointer-events-none absolute inset-0 w-full h-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA&sz=w800';"
                            alt="Banner Điện Thoại 2 Lý Công Quảng" 
                            class="w-full h-full object-cover object-center"
                        >
                        <div class="absolute inset-0 bg-gradient-to-t from-[#0b1e36]/95 via-[#0f2542]/85 to-[#0f2542]/60 p-3.5 flex flex-col justify-center items-center text-center">
                            <div class="w-full max-w-[94%] mx-auto border border-amber-400/30 bg-black/25 backdrop-blur-[2px] rounded-lg p-2.5 text-white">
                                <div class="text-[10px] font-semibold text-amber-300 uppercase tracking-wider mb-1">
                                    AN TOÀN – CHẤT LƯỢNG – ĐÚNG TIẾN ĐỘ
                                </div>
                                <h2 class="text-[12.5px] font-extrabold uppercase leading-snug text-white mb-1">
                                    XÂY NHÀ TRỌN GÓI – MIỄN PHÍ THIẾT KẾ & GPXD
                                </h2>
                                <p class="text-[10.5px] text-slate-200 leading-tight mb-2">
                                    Báo giá minh bạch, vật tư chính hãng, giám sát kỹ thuật 24/7 và bảo hành kết cấu dài hạn.
                                </p>
                                <div class="text-[10px] text-amber-200 font-medium bg-white/10 rounded py-1 px-2">
                                    <i class="fa-solid fa-globe mr-1"></i>lycongquang.com • Hotline: 0905.539.892
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng & Chấm tròn chuyển Slide -->
                <button onclick="changeBannerSlide(-1)" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-black/60 text-white flex items-center justify-center transition z-10">
                    <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                </button>
                <button onclick="changeBannerSlide(1)" aria-label="Slide tiếp theo" class="absolute right-2 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-black/60 text-white flex items-center justify-center transition z-10">
                    <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                </button>
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2 z-10">
                    <button id="banner-dot-0" onclick="setBannerSlide(0)" aria-label="Banner 1" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
                    <button id="banner-dot-1" onclick="setBannerSlide(1)" aria-label="Banner 2" class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         4. UX BUILDER SECTION: LĨNH VỰC HOẠT ĐỘNG & DỊCH VỤ TIÊU BIỂU (Giống web mẫu tintruongthinh.com)
            - Chia 2 cột trên điện thoại, 4 cột trên máy tính, không nhãn dán
         ===================================================================== -->
    <section id="linh-vuc" class="py-7 bg-white border-b border-slate-200">
        <div class="flatsome-container">
            <div class="ux-section-title">
                <b></b>
                <span class="text-sm sm:text-lg">LĨNH VỰC HOẠT ĐỘNG CHÍNH</span>
                <b></b>
            </div>
            <p class="text-center text-xs sm:text-sm text-slate-600 max-w-3xl mx-auto mb-5">
                CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG LÝ CÔNG QUẢNG cung cấp giải pháp khép kín từ Tư vấn Thiết kế Kiến trúc – Kết cấu đến Thi công phần thô, Thi công hoàn thiện và Nội thất trọn gói.
            </p>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Dịch vụ 1 -->
                <div class="ux-product-box bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/11oZAhO2AsbGFYm1pdsPS5Vtgkd9IP2yZ" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=11oZAhO2AsbGFYm1pdsPS5Vtgkd9IP2yZ&sz=w800';"
                            alt="Thiết kế Kiến trúc - Nội thất" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand uppercase leading-snug break-words mb-1.5">
                                Thiết Kế Kiến Trúc – Nội Thất
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Thiết kế hồ sơ bản vẽ kiến trúc, kết cấu, điện nước ME và phối cảnh 3D nhà phố, biệt thự, khách sạn, căn hộ.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-flex items-center text-[11px] sm:text-xs font-semibold text-amber-700 hover:text-brand">
                            Nhận tư vấn thiết kế <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 2 -->
                <div class="ux-product-box bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1ng7_50Be4LsQqNa28KBn8rSCicz40ir9" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1ng7_50Be4LsQqNa28KBn8rSCicz40ir9&sz=w800';"
                            alt="Thi công phần thô và nhân công hoàn thiện" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand uppercase leading-snug break-words mb-1.5">
                                Thi Công Phần Thô
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Thi công móng, cột, dầm, sàn bê tông cốt thép và xây tô đúng quy chuẩn kỹ thuật, vật tư chuẩn chính hãng.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-flex items-center text-[11px] sm:text-xs font-semibold text-amber-700 hover:text-brand">
                            Xem đơn giá phần thô <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 3 -->
                <div class="ux-product-box bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS&sz=w800';"
                            alt="Thi công hoàn thiện - Xây nhà trọn gói" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand uppercase leading-snug break-words mb-1.5">
                                Thi Công Hoàn Thiện Trọn Gói
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Giải pháp chìa khóa trao tay từ xin phép xây dựng, thi công thô đến hoàn thiện ốp lát, sơn bả, cửa và thiết bị.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-flex items-center text-[11px] sm:text-xs font-semibold text-amber-700 hover:text-brand">
                            Báo giá trọn gói <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 4 -->
                <div class="ux-product-box bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1qgl8kz47lsoa_Ju2l7xRZ5Jjt8DLC7yy" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1qgl8kz47lsoa_Ju2l7xRZ5Jjt8DLC7yy&sz=w800';"
                            alt="Thi công nội thất trọn gói" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand uppercase leading-snug break-words mb-1.5">
                                Thi Công Nội Thất
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Sản xuất và lắp đặt nội thất phòng khách, bếp, phòng ngủ, văn phòng, căn hộ cho thuê chuẩn bản vẽ 3D.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-flex items-center text-[11px] sm:text-xs font-semibold text-amber-700 hover:text-brand">
                            Tư vấn nội thất <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         5. UX BUILDER SECTION: GIỚI THIỆU CÔNG TY & 6 THẾ MẠNH CỐT LÕI (Theo mẫu tintruongthinh.com)
         ===================================================================== -->
    <section id="gioi-thieu" class="py-8 bg-slate-50 border-b border-slate-200">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center mb-8">
                <!-- Cột thông tin giới thiệu -->
                <div class="lg:col-span-7">
                    <div class="text-xs font-bold text-amber-600 uppercase tracking-wider mb-1">
                        VỀ CHÚNG TÔI • LYCONGQUANG.COM
                    </div>
                    <h2 class="text-base sm:text-xl font-extrabold text-brand uppercase leading-snug mb-3">
                        CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG LÝ CÔNG QUẢNG
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-3">
                        <strong>CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG LÝ CÔNG QUẢNG</strong> (Mã số thuế: <strong>0402163371</strong>) có trụ sở tại <strong>11 Đoàn Nguyễn Thục, Phường Cẩm Lệ, TP Đà Nẵng</strong>, là đơn vị uy tín chuyên Thiết kế – Thi công Xây dựng – Nội thất các công trình Khách sạn, Căn hộ, Biệt thự, Nhà phố và Văn phòng tại TP. Đà Nẵng và khu vực miền Trung.
                    </p>
                    <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-4">
                        Với phương châm đặt chữ <strong>“TÂM”</strong> và chữ <strong>“TÍN”</strong> lên hàng đầu, mỗi công trình do Lý Công Quảng thực hiện đều tuân thủ nghiêm ngặt tiêu chí: <strong>“AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – SỰ HÀI LÒNG CỦA KHÁCH HÀNG”</strong>. Đội ngũ kiến trúc sư, kỹ sư giàu kinh nghiệm thực chiến luôn đồng hành cùng Chủ đầu tư từ khâu lên ý tưởng, xin phép xây dựng đến khi bàn giao tổ ấm hoàn chỉnh.
                    </p>
                    <div class="grid grid-cols-2 sm:grid-cols-3 gap-2.5 text-xs">
                        <div class="bg-white p-3 rounded-lg border border-slate-200">
                            <div class="font-extrabold text-brand text-sm sm:text-base">100%</div>
                            <div class="text-slate-600 text-[11px]">Vật tư đúng hợp đồng</div>
                        </div>
                        <div class="bg-white p-3 rounded-lg border border-slate-200">
                            <div class="font-extrabold text-brand text-sm sm:text-base">Đúng Tiến Độ</div>
                            <div class="text-slate-600 text-[11px]">Giám sát kỹ thuật 24/7</div>
                        </div>
                        <div class="bg-white p-3 rounded-lg border border-slate-200 col-span-2 sm:col-span-1">
                            <div class="font-extrabold text-brand text-sm sm:text-base">05 - 10 Năm</div>
                            <div class="text-slate-600 text-[11px]">Bảo hành kết cấu bền vững</div>
                        </div>
                    </div>
                </div>

                <!-- Cột hình ảnh thực tế tại công trường -->
                <div class="lg:col-span-5 grid grid-cols-2 gap-3">
                    <div class="rounded-xl overflow-hidden border border-slate-200 shadow-sm aspect-[4/3]">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1stTZuL2puyTkD_2WrDXjg2Yz2NAYyHV3" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1stTZuL2puyTkD_2WrDXjg2Yz2NAYyHV3&sz=w600';"
                            alt="Thực tế thi công Lý Công Quảng 1" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="rounded-xl overflow-hidden border border-slate-200 shadow-sm aspect-[4/3]">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF&sz=w600';"
                            alt="Thực tế thi công Lý Công Quảng 2" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="rounded-xl overflow-hidden border border-slate-200 shadow-sm aspect-[4/3]">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi&sz=w600';"
                            alt="Thực tế thi công Lý Công Quảng 3" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="rounded-xl overflow-hidden border border-slate-200 shadow-sm aspect-[4/3]">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1A271daJ-s3V5Ws6LRrcDIJ9-Il34FXLq" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1A271daJ-s3V5Ws6LRrcDIJ9-Il34FXLq&sz=w600';"
                            alt="Thực tế thi công Lý Công Quảng 4" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                </div>
            </div>

            <!-- 6 Thế mạnh của chúng tôi (Giống cấu trúc tintruongthinh.com, chia 2 cột trên điện thoại, 3 cột trên máy tính) -->
            <div class="ux-section-title">
                <b></b>
                <span class="text-sm sm:text-lg">THẾ MẠNH CỦA CHÚNG TÔI</span>
                <b></b>
            </div>
            <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-4">
                <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-slate-200 flex flex-col sm:flex-row items-start gap-3">
                    <div class="w-9 h-9 rounded-lg bg-brand text-white flex items-center justify-center shrink-0 text-sm">
                        <i class="fa-solid fa-user-tie"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand leading-snug mb-1">Đội ngũ KTS, Kỹ sư chuyên nghiệp</h3>
                        <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư chỉ huy công trường và thợ lành nghề lâu năm tại Đà Nẵng.</p>
                    </div>
                </div>
                <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-slate-200 flex flex-col sm:flex-row items-start gap-3">
                    <div class="w-9 h-9 rounded-lg bg-brand text-white flex items-center justify-center shrink-0 text-sm">
                        <i class="fa-solid fa-cubes"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand leading-snug mb-1">Cập nhật xu hướng hiện đại</h3>
                        <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Ứng dụng giải pháp không gian xanh, thông tầng lấy sáng tự nhiên và vật liệu xây dựng thế hệ mới.</p>
                    </div>
                </div>
                <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-slate-200 flex flex-col sm:flex-row items-start gap-3">
                    <div class="w-9 h-9 rounded-lg bg-brand text-white flex items-center justify-center shrink-0 text-sm">
                        <i class="fa-solid fa-clipboard-check"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand leading-snug mb-1">Giám sát tiến độ chuẩn xác</h3>
                        <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Báo cáo nhật ký thi công định kỳ bằng hình ảnh thực tế giúp Chủ đầu tư theo dõi sát sao mọi hạng mục.</p>
                    </div>
                </div>
                <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-slate-200 flex flex-col sm:flex-row items-start gap-3">
                    <div class="w-9 h-9 rounded-lg bg-brand text-white flex items-center justify-center shrink-0 text-sm">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand leading-snug mb-1">Bảo hành công trình lâu dài</h3>
                        <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Chế độ hậu mãi tận tâm, hỗ trợ kiểm tra bảo trì nhanh chóng giúp khách hàng hoàn toàn an tâm.</p>
                    </div>
                </div>
                <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-slate-200 flex flex-col sm:flex-row items-start gap-3">
                    <div class="w-9 h-9 rounded-lg bg-brand text-white flex items-center justify-center shrink-0 text-sm">
                        <i class="fa-solid fa-scale-balanced"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand leading-snug mb-1">Chi phí hợp lý – Minh bạch</h3>
                        <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Dự toán bóc tách chi tiết từng hạng mục, tối ưu ngân sách cho Chủ đầu tư, cam kết không phát sinh.</p>
                    </div>
                </div>
                <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-slate-200 flex flex-col sm:flex-row items-start gap-3">
                    <div class="w-9 h-9 rounded-lg bg-brand text-white flex items-center justify-center shrink-0 text-sm">
                        <i class="fa-solid fa-headset"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand leading-snug mb-1">Tư vấn miễn phí 24/7</h3>
                        <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Khảo sát hiện trạng thực tế, tư vấn phong thủy, pháp lý xây dựng hoàn toàn miễn phí qua 0905.539.892.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         6. UX BUILDER SECTION: DANH MỤC SẢN PHẨM & CÔNG TRÌNH THỰC TẾ (Theo danh mục web mẫu tintruongthinh.com)
            - Lấy toàn bộ ảnh thực tế Google Drive được cung cấp
            - Chia 2 cột trên điện thoại, 4 cột trên máy tính
            - Tên sản phẩm hiển thị đầy đủ, không tràn ra ngoài, không thiếu chữ
            - KHÔNG để các nhãn dán trên ảnh ở trang chủ
         ===================================================================== -->
    <section id="cong-trinh-thuc-te" class="py-8 bg-white border-b border-slate-200">
        <div class="flatsome-container">
            <div class="ux-section-title">
                <b></b>
                <span class="text-sm sm:text-lg">DANH MỤC SẢN PHẨM & CÔNG TRÌNH THỰC TẾ</span>
                <b></b>
            </div>

            <!-- Thanh nút danh mục ở trang chủ nhỏ gọn, đẹp mắt -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6">
                <button onclick="filterProducts('all', this)" class="cat-filter-btn active">Tất cả danh mục</button>
                <button onclick="filterProducts('nha-pho', this)" class="cat-filter-btn">Nhà phố hiện đại</button>
                <button onclick="filterProducts('biet-thu', this)" class="cat-filter-btn">Biệt thự</button>
                <button onclick="filterProducts('khach-san-can-ho', this)" class="cat-filter-btn">Khách sạn – Căn hộ – Phòng trọ</button>
                <button onclick="filterProducts('phan-tho-hoan-thien', this)" class="cat-filter-btn">Thi công phần thô & Hoàn thiện</button>
                <button onclick="filterProducts('van-phong-noi-that', this)" class="cat-filter-btn">Văn phòng & Nội thất</button>
            </div>

            <!-- Lưới sản phẩm: 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4) -->
            <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                
                <!-- Sản phẩm 1 -->
                <div data-cat="nha-pho" class="product-card ux-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk&sz=w800';" alt="Thiết Kế Và Thi Công Trọn Gói Nhà Phố Hiện Đại 3 Tầng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words mb-1">
                                Thiết Kế & Thi Công Trọn Gói Nhà Phố Hiện Đại 3 Tầng
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-normal">
                                Danh mục: Nhà phố • Kiến trúc mặt tiền thông thoáng
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] font-semibold text-brand">
                            Liên hệ báo giá: 0905.539.892
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 2 -->
                <div data-cat="nha-pho" class="product-card ux-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW&sz=w800';" alt="Thi Công Hoàn Thiện Nhà Phố Lệch Tầng Không Gian Xanh" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words mb-1">
                                Thi Công Hoàn Thiện Nhà Phố Lệch Tầng Không Gian Xanh
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-normal">
                                Danh mục: Nhà phố • Tối ưu giếng trời & ánh sáng
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] font-semibold text-brand">
                            Liên hệ báo giá: 0905.539.892
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 3 -->
                <div data-cat="biet-thu" class="product-card ux-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1PjtEF4hlMU_42b438GmEQhYZTba75kRJ" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1PjtEF4hlMU_42b438GmEQhYZTba75kRJ&sz=w800';" alt="Thiết Kế Và Thi Công Biệt Thự Phố 2 Mặt Tiền Sang Trọng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words mb-1">
                                Thiết Kế & Thi Công Biệt Thự Phố 2 Mặt Tiền Sang Trọng
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-normal">
                                Danh mục: Biệt thự • Kết cấu bền vững, thẩm mỹ cao
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] font-semibold text-brand">
                            Liên hệ báo giá: 0905.539.892
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 4 -->
                <div data-cat="khach-san-can-ho" class="product-card ux-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA&sz=w800';" alt="Thi Công Trọn Gói Tòa Nhà Căn Hộ Cho Thuê Và Khách Sạn" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words mb-1">
                                Thi Công Trọn Gói Tòa Nhà Căn Hộ Cho Thuê & Khách Sạn
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-normal">
                                Danh mục: Khách sạn – Căn hộ • Tối ưu diện tích phòng
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] font-semibold text-brand">
                            Liên hệ báo giá: 0905.539.892
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 5 -->
                <div data-cat="phan-tho-hoan-thien" class="product-card ux-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1ng7_50Be4LsQqNa28KBn8rSCicz40ir9" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1ng7_50Be4LsQqNa28KBn8rSCicz40ir9&sz=w800';" alt="Thi Công Phần Thô Khung Bê Tông Cốt Thép Nhà Phố Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words mb-1">
                                Thi Công Phần Thô Khung Bê Tông Cốt Thép Nhà Phố
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-normal">
                                Danh mục: Thi công phần thô • Thép Việt Úc / Hòa Phát
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] font-semibold text-brand">
                            Liên hệ báo giá: 0905.539.892
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 6 -->
                <div data-cat="phan-tho-hoan-thien" class="product-card ux-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS&sz=w800';" alt="Thi Công Xây Tô Tường Và Chống Thấm Hoàn Thiện Công Trình" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words mb-1">
                                Thi Công Xây Tô Tường & Chống Thấm Hoàn Thiện Công Trình
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-normal">
                                Danh mục: Thi công hoàn thiện • Chuẩn kỹ thuật xây dựng
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] font-semibold text-brand">
                            Liên hệ báo giá: 0905.539.892
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 7 -->
                <div data-cat="phan-tho-hoan-thien" class="product-card ux-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1stTZuL2puyTkD_2WrDXjg2Yz2NAYyHV3" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1stTZuL2puyTkD_2WrDXjg2Yz2NAYyHV3&sz=w800';" alt="Thi Công Cốt Thép Móng Và Dầm Sàn Công Trình Dân Dụng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words mb-1">
                                Thi Công Cốt Thép Móng & Dầm Sàn Công Trình Dân Dụng
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-normal">
                                Danh mục: Thi công phần thô • Nghiệm thu chặt chẽ
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] font-semibold text-brand">
                            Liên hệ báo giá: 0905.539.892
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 8 -->
                <div data-cat="biet-thu" class="product-card ux-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF&sz=w800';" alt="Xây Dựng Trọn Gói Biệt Thự Nghỉ Dưỡng Sân Vườn Hiện Đại" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words mb-1">
                                Xây Dựng Trọn Gói Biệt Thự Nghỉ Dưỡng Sân Vườn Hiện Đại
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-normal">
                                Danh mục: Biệt thự • Không gian mở đẳng cấp
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] font-semibold text-brand">
                            Liên hệ báo giá: 0905.539.892
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 9 -->
                <div data-cat="khach-san-can-ho" class="product-card ux-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi&sz=w800';" alt="Thiết Kế Và Thi Công Căn Hộ Dịch Vụ Kết Hợp Kinh Doanh" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words mb-1">
                                Thiết Kế & Thi Công Căn Hộ Dịch Vụ Kết Hợp Kinh Doanh
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-normal">
                                Danh mục: Khách sạn – Căn hộ – Phòng trọ
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] font-semibold text-brand">
                            Liên hệ báo giá: 0905.539.892
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 10 -->
                <div data-cat="nha-pho" class="product-card ux-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1A271daJ-s3V5Ws6LRrcDIJ9-Il34FXLq" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1A271daJ-s3V5Ws6LRrcDIJ9-Il34FXLq&sz=w800';" alt="Thi Công Nhà Phố 3 Tầng 1 Tum Phong Cách Tối Giản Hiện Đại" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words mb-1">
                                Thi Công Nhà Phố 3 Tầng 1 Tum Phong Cách Hiện Đại
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-normal">
                                Danh mục: Nhà phố • Chìa khóa trao tay trọn gói
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] font-semibold text-brand">
                            Liên hệ báo giá: 0905.539.892
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 11 -->
                <div data-cat="van-phong-noi-that" class="product-card ux-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1G5cVihRDvTKhbx_tNG5uDoSQtvzc0TTt" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1G5cVihRDvTKhbx_tNG5uDoSQtvzc0TTt&sz=w800';" alt="Thiết Kế Và Thi Công Trọn Gói Văn Phòng Công Ty Kết Hợp Nhà Ở" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words mb-1">
                                Thiết Kế & Thi Công Văn Phòng Công Ty Kết Hợp Nhà Ở
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-normal">
                                Danh mục: Văn phòng & Nội thất • Bố trí khoa học
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] font-semibold text-brand">
                            Liên hệ báo giá: 0905.539.892
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 12 -->
                <div data-cat="van-phong-noi-that" class="product-card ux-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1fqJikC677z_7x28XQaAx3VQD7zqWtiUy" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1fqJikC677z_7x28XQaAx3VQD7zqWtiUy&sz=w800';" alt="Thi Công Hoàn Thiện Nội Thất Phòng Khách Và Bếp Hiện Đại" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words mb-1">
                                Thi Công Hoàn Thiện Nội Thất Phòng Khách & Bếp Hiện Đại
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-normal">
                                Danh mục: Thi công nội thất • Gỗ công nghiệp chống ẩm
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] font-semibold text-brand">
                            Liên hệ báo giá: 0905.539.892
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         7. UX BUILDER SECTION: DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (Trang chủ)
            - Chia 2 cột trên điện thoại, 4 cột trên máy tính
            - Không nhãn dán, tên dự án đầy đủ không tràn chữ
         ===================================================================== -->
    <section id="du-an-da-nang" class="py-8 bg-slate-50 border-b border-slate-200">
        <div class="flatsome-container">
            <div class="ux-section-title">
                <b></b>
                <span class="text-sm sm:text-lg">CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG</span>
                <b></b>
            </div>
            <p class="text-center text-xs sm:text-sm text-slate-600 max-w-3xl mx-auto mb-6">
                Tổng hợp các dự án Thiết kế và Thi công thực tế do Công ty TNHH Kiến trúc và Xây dựng Lý Công Quảng triển khai tại Quận Cẩm Lệ, Hòa Xuân, Hải Châu, Sơn Trà, Ngũ Hành Sơn – TP. Đà Nẵng.
            </p>

            <!-- Lưới 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                
                <!-- Dự án Đà Nẵng 1 -->
                <div class="ux-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1ImsuD--QivYj4IV9Nx10yzvXfmuRmZ8x" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1ImsuD--QivYj4IV9Nx10yzvXfmuRmZ8x&sz=w800';" alt="Dự Án Nhà Phố Hiện Đại Khu Đô Thị Hòa Xuân Cẩm Lệ Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand leading-snug break-words mb-1">
                                Dự Án Nhà Phố Hiện Đại Khu Đô Thị Hòa Xuân – Cẩm Lệ, Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-600 leading-normal">
                                Hạng mục: Thiết kế & Thi công trọn gói chìa khóa trao tay
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] text-slate-500">
                            Khu vực: Phường Hòa Xuân, Quận Cẩm Lệ, TP Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 2 -->
                <div class="ux-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/11oZAhO2AsbGFYm1pdsPS5Vtgkd9IP2yZ" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=11oZAhO2AsbGFYm1pdsPS5Vtgkd9IP2yZ&sz=w800';" alt="Dự Án Biệt Thự Phố Khu Nam Việt Á Ngũ Hành Sơn Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand leading-snug break-words mb-1">
                                Dự Án Biệt Thự Phố Khu Đô Thị Nam Việt Á – TP Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-600 leading-normal">
                                Hạng mục: Thiết kế kiến trúc 3D & Thi công hoàn thiện
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] text-slate-500">
                            Khu vực: Quận Ngũ Hành Sơn, TP Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 3 -->
                <div class="ux-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1qgl8kz47lsoa_Ju2l7xRZ5Jjt8DLC7yy" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1qgl8kz47lsoa_Ju2l7xRZ5Jjt8DLC7yy&sz=w800';" alt="Dự Án Căn Hộ Cho Thuê Và Nhà Phố Quận Sơn Trà Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand leading-snug break-words mb-1">
                                Dự Án Căn Hộ Dịch Vụ & Nhà Phố Hiện Đại – Sơn Trà, Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-600 leading-normal">
                                Hạng mục: Thi công phần thô, hoàn thiện & lắp đặt nội thất
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] text-slate-500">
                            Khu vực: Quận Sơn Trà, TP Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 4 -->
                <div class="ux-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1ugKZwI_07LD42SRgLweM-PeRQt9-01Lw" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1ugKZwI_07LD42SRgLweM-PeRQt9-01Lw&sz=w800';" alt="Dự Án Nhà Phố 3 Tầng Hòa Thọ Đông Cẩm Lệ Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand leading-snug break-words mb-1">
                                Dự Án Nhà Phố 3 Tầng Phường Cẩm Lệ – TP Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-600 leading-normal">
                                Hạng mục: Xây dựng nhà trọn gói & hoàn thiện mặt tiền
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] text-slate-500">
                            Khu vực: Quận Cẩm Lệ, TP Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 5 -->
                <div class="ux-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1QcvBpsk1aY6aHVHIVrZs9ALP17TUWfkK" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1QcvBpsk1aY6aHVHIVrZs9ALP17TUWfkK&sz=w800';" alt="Dự Án Thi Công Nhà Phố Kết Hợp Văn Phòng Hải Châu Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand leading-snug break-words mb-1">
                                Dự Án Nhà Phố Kết Hợp Văn Phòng Quận Hải Châu – Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-600 leading-normal">
                                Hạng mục: Thi công kết cấu phần thô & hoàn thiện trọn gói
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] text-slate-500">
                            Khu vực: Quận Hải Châu, TP Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 6 -->
                <div class="ux-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1TWxo6uXoJMty8Qsbu4z8HFR5TeLvWph1" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1TWxo6uXoJMty8Qsbu4z8HFR5TeLvWph1&sz=w800';" alt="Dự Án Nhà Phố Hiện Đại Khu Đô Thị Phước Lý Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand leading-snug break-words mb-1">
                                Dự Án Nhà Phố Hiện Đại Khu Đô Thị Phước Lý – Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-600 leading-normal">
                                Hạng mục: Thiết kế kiến trúc & Xây dựng trọn gói
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] text-slate-500">
                            Khu vực: Cẩm Lệ – Liên Chiểu, TP Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 7 -->
                <div class="ux-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1nv_lSxn0mu-71NGKss3abLOuEMcB-bkQ" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1nv_lSxn0mu-71NGKss3abLOuEMcB-bkQ&sz=w800';" alt="Dự Án Cải Tạo Và Xây Mới Nhà Phố Trung Tâm TP Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand leading-snug break-words mb-1">
                                Dự Án Xây Mới & Hoàn Thiện Nhà Phố Gia Đình Tại Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-600 leading-normal">
                                Hạng mục: Khảo sát, thiết kế & thi công hoàn thiện
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] text-slate-500">
                            Khu vực: TP Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 8 -->
                <div class="ux-product-box bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk&sz=w800';" alt="Dự Án Biệt Thự Gia Đình Cao Cấp Khu Đô Thị Sinh Thái Hòa Xuân" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand leading-snug break-words mb-1">
                                Dự Án Biệt Thự Gia Đình Khu Đô Thị Sinh Thái Hòa Xuân
                            </h3>
                            <p class="text-[11px] text-slate-600 leading-normal">
                                Hạng mục: Thiết kế & Thi công trọn gói tiêu chuẩn cao
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] text-slate-500">
                            Khu vực: Quận Cẩm Lệ, TP Đà Nẵng
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         8. UX BUILDER SECTION: MẪU THIẾT KẾ NHÀ PHỐ & NỘI THẤT (Giống tintruongthinh.com)
            - Chia 2 cột trên điện thoại, 4 cột trên máy tính
         ===================================================================== -->
    <section id="mau-thiet-ke" class="py-8 bg-white border-b border-slate-200">
        <div class="flatsome-container">
            <div class="ux-section-title">
                <b></b>
                <span class="text-sm sm:text-lg">MẪU THIẾT KẾ KIẾN TRÚC & NỘI THẤT ĐẸP</span>
                <b></b>
            </div>
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <div class="ux-product-box bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1PjtEF4hlMU_42b438GmEQhYZTba75kRJ" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1PjtEF4hlMU_42b438GmEQhYZTba75kRJ&sz=w800';" alt="Mẫu Thiết Kế Nhà Phố 3 Tầng Mặt Tiền 5m Hiện Đại" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5">
                        <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words mb-1">
                            Mẫu Thiết Kế Nhà Phố 3 Tầng Mặt Tiền 5m Hiện Đại
                        </h3>
                        <p class="text-[11px] text-slate-500">Công năng: 4 Phòng ngủ, Phòng khách, Bếp, Phòng thờ, Sân thượng</p>
                    </div>
                </div>

                <div class="ux-product-box bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW&sz=w800';" alt="Mẫu Thiết Kế Nhà Phố 2 Tầng 1 Tum Có Giếng Trời" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5">
                        <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words mb-1">
                            Mẫu Thiết Kế Nhà Phố 2 Tầng 1 Tum Thông Thoáng
                        </h3>
                        <p class="text-[11px] text-slate-500">Công năng: 3 Phòng ngủ, Sân để ô tô, Giếng trời xanh mát</p>
                    </div>
                </div>

                <div class="ux-product-box bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1m7VasLcMXKPk2-mSVgIdO3USOnba75kRJ" onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA';" alt="Mẫu Thiết Kế Căn Hộ Cho Thuê Và Khách Sạn Mini" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5">
                        <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words mb-1">
                            Mẫu Thiết Kế Căn Hộ Cho Thuê & Khách Sạn 5 Tầng
                        </h3>
                        <p class="text-[11px] text-slate-500">Công năng: Thang máy, Tầng hầm để xe, 12-18 Căn hộ Studio</p>
                    </div>
                </div>

                <div class="ux-product-box bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1fqJikC677z_7x28XQaAx3VQD7zqWtiUy" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1fqJikC677z_7x28XQaAx3VQD7zqWtiUy&sz=w800';" alt="Mẫu Thiết Kế Nội Thất Nhà Phố Và Biệt Thự Sang Trọng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5">
                        <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words mb-1">
                            Mẫu Thiết Kế Nội Thất Nhà Phố & Biệt Thự Đồng Bộ
                        </h3>
                        <p class="text-[11px] text-slate-500">Công năng: Nội thất gỗ An Cường, Đá tự nhiên, Ánh sáng ấm</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         9. UX BUILDER SECTION: BẢNG BÁO GIÁ XÂY DỰNG & FORM YÊU CẦU BÁO GIÁ TRANG CHỦ
         ===================================================================== -->
    <section id="bao-gia" class="py-8 bg-slate-50 border-b border-slate-200">
        <div class="flatsome-container">
            <div class="ux-section-title">
                <b></b>
                <span class="text-sm sm:text-lg">BÁO GIÁ THIẾT KẾ & THI CÔNG XÂY DỰNG</span>
                <b></b>
            </div>

            <!-- 4 Gói Báo Giá: Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5 mb-8">
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 sm:p-5 flex flex-col justify-between">
                    <div>
                        <h3 class="text-xs sm:text-sm font-extrabold text-brand uppercase mb-1">Báo Giá Thiết Kế Kiến Trúc</h3>
                        <div class="text-sm sm:text-lg font-extrabold text-amber-600 mb-2">120.000đ – 180.000đ/m²</div>
                        <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5">
                            <li>• Bản vẽ kiến trúc 2D & phối cảnh 3D</li>
                            <li>• Hồ sơ kết cấu, điện nước M&E</li>
                            <li>• Dự toán chi tiết khối lượng vật tư</li>
                            <li>• Miễn phí 100% khi thi công trọn gói</li>
                        </ul>
                    </div>
                    <a href="#form-bao-gia" class="mt-3 block text-center py-2 rounded-lg bg-slate-100 hover:bg-brand hover:text-white text-brand text-xs font-bold transition">
                        Nhận Báo Giá Chi Tiết
                    </a>
                </div>

                <div class="bg-white rounded-xl border border-slate-200 p-3.5 sm:p-5 flex flex-col justify-between">
                    <div>
                        <h3 class="text-xs sm:text-sm font-extrabold text-brand uppercase mb-1">Báo Giá Thi Công Phần Thô</h3>
                        <div class="text-sm sm:text-lg font-extrabold text-amber-600 mb-2">3.500.000đ – 3.900.000đ/m²</div>
                        <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5">
                            <li>• Vật tư phần thô chính hãng chuẩn mác</li>
                            <li>• Nhân công hoàn thiện xây tô, ốp lát</li>
                            <li>• Lắp đặt hệ thống điện nước âm tường</li>
                            <li>• Bảo hành kết cấu lên đến 10 năm</li>
                        </ul>
                    </div>
                    <a href="#form-bao-gia" class="mt-3 block text-center py-2 rounded-lg bg-slate-100 hover:bg-brand hover:text-white text-brand text-xs font-bold transition">
                        Nhận Báo Giá Chi Tiết
                    </a>
                </div>

                <div class="bg-white rounded-xl border border-slate-200 p-3.5 sm:p-5 flex flex-col justify-between">
                    <div>
                        <h3 class="text-xs sm:text-sm font-extrabold text-brand uppercase mb-1">Báo Giá Thi Công Hoàn Thiện</h3>
                        <div class="text-sm sm:text-lg font-extrabold text-amber-600 mb-2">2.200.000đ – 3.200.000đ/m²</div>
                        <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5">
                            <li>• Gạch ốp lát, đá cầu thang, trần thạch cao</li>
                            <li>• Sơn nước nội ngoại thất Dulux / Jotun</li>
                            <li>• Hệ cửa nhôm Xingfa, thiết bị vệ sinh</li>
                            <li>• Tùy chọn gói vật tư Khá – Tốt – Cao cấp</li>
                        </ul>
                    </div>
                    <a href="#form-bao-gia" class="mt-3 block text-center py-2 rounded-lg bg-slate-100 hover:bg-brand hover:text-white text-brand text-xs font-bold transition">
                        Nhận Báo Giá Chi Tiết
                    </a>
                </div>

                <div class="bg-white rounded-xl border-2 border-brand p-3.5 sm:p-5 flex flex-col justify-between">
                    <div>
                        <h3 class="text-xs sm:text-sm font-extrabold text-brand uppercase mb-1">Xây Nhà Trọn Gói (Chìa Khóa Trao Tay)</h3>
                        <div class="text-sm sm:text-lg font-extrabold text-amber-600 mb-2">5.600.000đ – 7.200.000đ/m²</div>
                        <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5">
                            <li>• Tặng 100% Giấy phép XD & Bản vẽ 3D</li>
                            <li>• Bao gồm toàn bộ Phần thô + Hoàn thiện</li>
                            <li>• Cam kết không phát sinh chi phí</li>
                            <li>• Bàn giao nhà sạch đẹp đưa vào sử dụng</li>
                        </ul>
                    </div>
                    <a href="#form-bao-gia" class="mt-3 block text-center py-2 rounded-lg bg-brand hover:bg-brand-dark text-white text-xs font-bold transition">
                        Đăng Ký Tư Vấn Ngay
                    </a>
                </div>
            </div>

            <!-- FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ (Chuẩn mẫu tintruongthinh.com) -->
            <div id="form-bao-gia" class="bg-brand rounded-2xl p-4 sm:p-7 text-white shadow-md">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                    <div class="lg:col-span-5">
                        <div class="text-xs font-bold text-amber-400 uppercase tracking-wider mb-1">
                            ĐĂNG KÝ NHẬN BÁO GIÁ NHANH
                        </div>
                        <h3 class="text-base sm:text-xl font-extrabold uppercase leading-snug mb-2">
                            MIỄN PHÍ TƯ VẤN & KHẢO SÁT BÁO GIÁ XÂY DỰNG TẠI ĐÀ NẴNG
                        </h3>
                        <p class="text-xs sm:text-sm text-slate-200 leading-relaxed mb-4">
                            Quý khách vui lòng để lại thông tin nhu cầu xây dựng. Kỹ sư trưởng của <strong>CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG LÝ CÔNG QUẢNG</strong> sẽ liên hệ tư vấn phương án thiết kế và bảng dự toán chi tiết trong vòng 15 phút!
                        </p>
                        <div class="space-y-2 text-xs text-slate-100 bg-white/10 p-3.5 rounded-xl border border-white/15">
                            <div><i class="fa-solid fa-phone-volume text-amber-400 mr-2"></i> Hotline / Zalo: <strong>0905.539.892</strong></div>
                            <div><i class="fa-solid fa-location-dot text-amber-400 mr-2"></i> Địa chỉ: <strong>11 Đoàn Nguyễn Thục, P. Cẩm Lệ, TP Đà Nẵng</strong></div>
                            <div><i class="fa-solid fa-globe text-amber-400 mr-2"></i> Website: <strong>lycongquang.com</strong></div>
                        </div>
                    </div>

                    <div class="lg:col-span-7 bg-white text-slate-800 rounded-xl p-4 sm:p-6">
                        <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên Quý khách *</label>
                                    <input type="text" id="custName" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại liên hệ *</label>
                                    <input type="tel" id="custPhone" required placeholder="Ví dụ: 0905..." class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Loại công trình cần tư vấn</label>
                                    <select id="custType" class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand bg-white">
                                        <option value="Nhà phố hiện đại">Nhà phố</option>
                                        <option value="Biệt thự">Biệt thự</option>
                                        <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                        <option value="Văn phòng công ty">Văn phòng</option>
                                        <option value="Thi công nội thất">Thi công nội thất</option>
                                        <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                                    <select id="custBudget" class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand bg-white">
                                        <option value="Từ 1 - 2 tỷ">Từ 1 - 2 tỷ</option>
                                        <option value="Từ 2 - 3 tỷ">Từ 2 - 3 tỷ</option>
                                        <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                        <option value=" từ 500 triệu - 1 tỷ">500 triệu - 1 tỷ</option>
                                        <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                        <option value="Cần tư vấn khái toán">Chưa xác định (Cần tư vấn báo giá)</option>
                                    </select>
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Diện tích đất & Số tầng dự kiến</label>
                                    <input type="text" id="custArea" placeholder="VD: 5x20m, 3 tầng, tại Cẩm Lệ..." class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Hạng mục yêu cầu</label>
                                    <select id="custService" class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand bg-white">
                                        <option value="Xây nhà trọn gói (Chìa khóa trao tay)">Xây nhà trọn gói (Chìa khóa trao tay)</option>
                                        <option value="Thi công phần thô & nhân công hoàn thiện">Thi công phần thô & nhân công hoàn thiện</option>
                                        <option value="Thiết kế Kiến trúc & Nội thất">Thiết kế Kiến trúc & Nội thất</option>
                                        <option value="Thi công hoàn thiện & Nội thất">Thi công hoàn thiện & Nội thất</option>
                                    </select>
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Ghi chú thêm</label>
                                <textarea id="custNote" rows="2" placeholder="Nhập yêu cầu cụ thể của Quý khách (vị trí lô đất, số phòng ngủ, thời gian dự kiến khởi công...)" class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand"></textarea>
                            </div>

                            <button type="submit" class="w-full py-2.5 px-4 rounded-lg bg-amber-600 hover:bg-amber-700 text-white font-bold text-xs sm:text-sm uppercase tracking-wide transition shadow">
                                <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ
                            </button>
                        </form>

                        <!-- Thông báo gửi form thành công (Không dùng alert) -->
                        <div id="quoteSuccessBox" class="hidden mt-3 p-3.5 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-900 text-xs">
                            <div class="font-bold text-sm mb-1"><i class="fa-solid fa-circle-check text-emerald-600 mr-1"></i> Đã ghi nhận yêu cầu báo giá thành công!</div>
                            <p id="quoteSuccessText" class="leading-relaxed"></p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         10. UX BUILDER SECTION: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Cẩm nang xây dựng)
             - Chia 2 cột trên điện thoại, 4 cột trên máy tính
         ===================================================================== -->
    <section id="tin-tuc" class="py-8 bg-white border-b border-slate-200">
        <div class="flatsome-container">
            <div class="ux-section-title">
                <b></b>
                <span class="text-sm sm:text-lg">BÀI VIẾT & KINH NGHIỆM XÂY DỰNG</span>
                <b></b>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Bài viết 1 -->
                <article class="ux-product-box bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[16/10] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1stTZuL2puyTkD_2WrDXjg2Yz2NAYyHV3" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1stTZuL2puyTkD_2WrDXjg2Yz2NAYyHV3&sz=w800';" alt="Hướng dẫn bảo dưỡng bê tông móng và sàn đúng cách" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand leading-snug break-words mb-1.5">
                                Hướng Dẫn Bảo Dưỡng Bê Tông Móng Và Dầm Sàn Đúng Kỹ Thuật
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Trong quá trình thi công phần thô, quy trình tưới nước giữ ẩm bảo dưỡng bê tông móng và sàn quyết định trực tiếp đến cường độ chịu lực và chống nứt công trình.
                            </p>
                        </div>
                        <span class="mt-2.5 pt-2 border-t border-slate-200 text-[11px] font-semibold text-amber-700">
                            Kinh nghiệm thi công • lycongquang.com
                        </span>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="ux-product-box bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[16/10] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk&sz=w800';" alt="03 Nỗi lo lớn nhất khi xây nhà mà Chủ đầu tư thường gặp phải" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand leading-snug break-words mb-1.5">
                                03 Nỗi Lo Lớn Nhất Khi Xây Nhà Mà Chủ Đầu Tư Cần Lưu Ý
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Giải pháp kiểm soát ngân sách không phát sinh, lựa chọn vật tư chính hãng và quy trình nghiệm thu từng giai đoạn khi xây nhà trọn gói tại Đà Nẵng.
                            </p>
                        </div>
                        <span class="mt-2.5 pt-2 border-t border-slate-200 text-[11px] font-semibold text-amber-700">
                            Cẩm nang xây nhà • lycongquang.com
                        </span>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="ux-product-box bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[16/10] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1fqJikC677z_7x28XQaAx3VQD7zqWtiUy" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1fqJikC677z_7x28XQaAx3VQD7zqWtiUy&sz=w800';" alt="Tâm lý học không gian và tầm quan trọng của thiết kế nội thất" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand leading-snug break-words mb-1.5">
                                Tâm Lý Học Không Gian & Tầm Quan Trọng Của Thiết Kế Nội Thất
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Cách bố trí ánh sáng tự nhiên, thông gió và phối màu vật liệu nội thất giúp mang lại năng lượng tích cực, sự tiện nghi cho từng thành viên gia đình.
                            </p>
                        </div>
                        <span class="mt-2.5 pt-2 border-t border-slate-200 text-[11px] font-semibold text-amber-700">
                            Kiến trúc & Nội thất • lycongquang.com
                        </span>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="ux-product-box bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[16/10] w-full">
                        <img src="https://lh3.googleusercontent.com/d/1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS&sz=w800';" alt="Quy trình xin phép xây dựng và hoàn công nhà ở tại Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand leading-snug break-words mb-1.5">
                                Thủ Tục Xin Cấp Phép Xây Dựng Nhà Ở Dân Dụng Tại TP Đà Nẵng
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Tổng hợp hồ sơ pháp lý, mật độ xây dựng, khoảng lùi và chiều cao tầng theo quy chuẩn hiện hành tại các quận Cẩm Lệ, Hải Châu, Sơn Trà, Ngũ Hành Sơn.
                            </p>
                        </div>
                        <span class="mt-2.5 pt-2 border-t border-slate-200 text-[11px] font-semibold text-amber-700">
                            Pháp lý xây dựng • lycongquang.com
                        </span>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         11. UX BUILDER SECTION: DANH MỤC CÁC ĐỐI TÁC CUNG ỨNG VẬT TƯ CHÍNH HÃNG
             - Chia 2 cột trên điện thoại, 6 cột trên máy tính
         ===================================================================== -->
    <section id="doi-tac" class="py-8 bg-slate-50 border-b border-slate-200">
        <div class="flatsome-container">
            <div class="ux-section-title">
                <b></b>
                <span class="text-sm sm:text-lg">ĐỐI TÁC & THƯƠNG HIỆU VẬT TƯ ĐỒNG HÀNH</span>
                <b></b>
            </div>
            <p class="text-center text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto mb-5">
                CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG LÝ CÔNG QUẢNG cam kết sử dụng 100% vật tư chính hãng từ các nhà sản xuất hàng đầu Việt Nam và Quốc tế.
            </p>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 sm:gap-4">
                <div class="bg-white rounded-xl border border-slate-200 p-3 text-center flex flex-col items-center justify-center">
                    <div class="text-xs sm:text-sm font-extrabold text-brand uppercase">THÉP HÒA PHÁT</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Thép xây dựng chính hãng</div>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3 text-center flex flex-col items-center justify-center">
                    <div class="text-xs sm:text-sm font-extrabold text-brand uppercase">SƠN DULUX & JOTUN</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Sơn nội ngoại thất cao cấp</div>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3 text-center flex flex-col items-center justify-center">
                    <div class="text-xs sm:text-sm font-extrabold text-brand uppercase">GỖ AN CƯỜNG</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Vật liệu nội thất chuẩn</div>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3 text-center flex flex-col items-center justify-center">
                    <div class="text-xs sm:text-sm font-extrabold text-brand uppercase">NHÔM XINGFA</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Hệ cửa nhôm kính cao cấp</div>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3 text-center flex flex-col items-center justify-center">
                    <div class="text-xs sm:text-sm font-extrabold text-brand uppercase">INAX & TOTO</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Thiết bị vệ sinh chính hãng</div>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3 text-center flex flex-col items-center justify-center">
                    <div class="text-xs sm:text-sm font-extrabold text-brand uppercase">PANASONIC & SIKA</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Thiết bị điện & Chống thấm</div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         12. UX BUILDER SECTION: ĐƯA FANPAGE FACEBOOK VÀ BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ
         ===================================================================== -->
    <section id="lien-he" class="py-8 bg-white border-b border-slate-200">
        <div class="flatsome-container">
            <div class="ux-section-title">
                <b></b>
                <span class="text-sm sm:text-lg">FANPAGE FACEBOOK & BẢN ĐỒ GOOGLE MAPS TRỤ SỞ</span>
                <b></b>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                <!-- Cột 1: Đưa Fanpage ra ngoài trang chủ -->
                <div class="lg:col-span-5 bg-slate-50 rounded-xl border border-slate-200 p-4 flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between gap-2 mb-3 pb-2 border-b border-slate-200">
                            <h3 class="text-xs sm:text-sm font-extrabold text-brand uppercase flex items-center gap-1.5">
                                <i class="fa-brands fa-facebook text-blue-600 text-base"></i> FANPAGE CHÍNH THỨC
                            </h3>
                            <a href="https://www.facebook.com/profile.php?id=61554027984574" target="_blank" rel="noopener noreferrer" class="text-[11px] font-bold text-blue-600 hover:underline">
                                Mở Facebook <i class="fa-solid fa-up-right-from-square ml-0.5"></i>
                            </a>
                        </div>

                        <!-- Khung hiển thị trực tiếp Fanpage ngoài trang chủ -->
                        <div class="rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm mb-3">
                            <div class="relative h-32 w-full overflow-hidden bg-brand">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk" 
                                    onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk&sz=w800';"
                                    alt="Ảnh bìa Fanpage Lý Công Quảng" 
                                    class="w-full h-full object-cover opacity-80"
                                >
                                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                                <div class="absolute bottom-2.5 left-3 right-3 flex items-center gap-2.5">
                                    <img 
                                        src="https://lh3.googleusercontent.com/d/1p5rawwdWkf8N9dCq2Lxr0m5r8yL2I6ak" 
                                        onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1p5rawwdWkf8N9dCq2Lxr0m5r8yL2I6ak&sz=w300';"
                                        alt="Logo Fanpage" 
                                        class="w-12 h-12 rounded-lg border-2 border-white bg-white object-contain p-0.5 shrink-0"
                                    >
                                    <div class="text-white min-w-0">
                                        <div class="font-bold text-xs sm:text-sm leading-snug break-words">
                                            CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG LÝ CÔNG QUẢNG
                                        </div>
                                        <div class="text-[11px] text-slate-200">
                                            Thiết kế Kiến trúc & Xây dựng trọn gói Đà Nẵng
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="p-3 text-xs text-slate-700 space-y-2">
                                <p class="leading-relaxed">
                                    Cập nhật hình ảnh nhật ký công trình thực tế, mẫu nhà phố, biệt thự, căn hộ đẹp và bảng báo giá xây dựng mới nhất tại Fanpage chính thức của công ty.
                                </p>
                                <!-- Nhúng Plugin Facebook Fanpage -->
                                <div class="w-full overflow-hidden rounded border border-slate-200 bg-slate-100">
                                    <iframe 
                                        title="Fanpage Công ty TNHH Kiến trúc và Xây dựng Lý Công Quảng"
                                        src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D61554027984574&tabs=timeline&width=340&height=180&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                                        width="100%" 
                                        height="180" 
                                        style="border:none;overflow:hidden;display:block;" 
                                        scrolling="no" 
                                        frameborder="0" 
                                        allowfullscreen="true" 
                                        allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                                    </iframe>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="flex flex-wrap gap-2">
                        <a href="https://www.facebook.com/profile.php?id=61554027984574" target="_blank" rel="noopener noreferrer" class="flex-1 text-center py-2.5 px-3 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs transition">
                            <i class="fa-brands fa-facebook-f mr-1"></i> Theo Dõi Fanpage Facebook
                        </a>
                        <a href="https://zalo.me/0905539892" target="_blank" rel="noopener noreferrer" class="flex-1 text-center py-2.5 px-3 rounded-lg bg-sky-600 hover:bg-sky-700 text-white font-bold text-xs transition">
                            <i class="fa-solid fa-comment-dots mr-1"></i> Nhắn Tin Zalo
                        </a>
                    </div>
                </div>

                <!-- Cột 2: Đưa Google Map ra ngoài trang chủ -->
                <div class="lg:col-span-7 bg-slate-50 rounded-xl border border-slate-200 p-4 flex flex-col justify-between">
                    <div class="flex flex-wrap items-center justify-between gap-2 mb-3 pb-2 border-b border-slate-200">
                        <div>
                            <h3 class="text-xs sm:text-sm font-extrabold text-brand uppercase flex items-center gap-1.5">
                                <i class="fa-solid fa-map-location-dot text-red-600 text-base"></i> BẢN ĐỒ GOOGLE MAPS: 11 ĐOÀN NGUYỄN THỤC, P. CẨM LỆ, TP ĐÀ NẴNG
                            </h3>
                        </div>
                        <a href="https://www.google.com/maps?q=11+%C4%90o%C3%A0n+Nguy%E1%BB%85n+Th%E1%BB%A5c,+Ph%C6%B0%E1%BB%9Dng+C%E1%BA%A9m+L%E1%BB%87,+TP+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-[11px] font-bold text-brand hover:underline">
                            Chỉ đường trên Google Maps <i class="fa-solid fa-diamond-turn-right ml-0.5"></i>
                        </a>
                    </div>

                    <!-- Khung bản đồ Google Map trực quan ngoài trang chủ -->
                    <div class="w-full h-[290px] sm:h-[340px] rounded-xl overflow-hidden border border-slate-300 shadow-sm bg-slate-200">
                        <iframe 
                            title="Bản đồ 11 Đoàn Nguyễn Thục, Phường Cẩm Lệ, TP Đà Nẵng"
                            src="https://maps.google.com/maps?q=11%20%C4%90o%C3%A0n%20Nguy%E1%BB%85n%20Th%E1%BB%A5c,%20C%E1%BA%A9m%20L%E1%BB%87,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                            width="100%" 
                            height="100%" 
                            style="border:0; display:block;" 
                            allowfullscreen="" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>

                    <div class="mt-3 grid grid-cols-1 sm:grid-cols-3 gap-2 text-xs bg-white p-3 rounded-lg border border-slate-200">
                        <div>
                            <span class="text-slate-500 block text-[11px]">Trụ sở chính:</span>
                            <strong class="text-slate-800">11 Đoàn Nguyễn Thục, P. Cẩm Lệ, TP Đà Nẵng</strong>
                        </div>
                        <div>
                            <span class="text-slate-500 block text-[11px]">Hotline / Zalo 24/7:</span>
                            <strong class="text-red-600 text-sm">0905.539.892</strong>
                        </div>
                        <div>
                            <span class="text-slate-500 block text-[11px]">Website chính thức:</span>
                            <strong class="text-brand">lycongquang.com</strong>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         13. FOOTER (Chân trang chuẩn Flatsome)
         ===================================================================== -->
    <footer class="bg-brand-dark text-slate-200 pt-8 pb-20 md:pb-8 w-full border-t-4 border-amber-500">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-slate-700">
                <!-- Cột 1: Thông tin công ty -->
                <div class="lg:col-span-5">
                    <div class="flex items-center gap-3 mb-3">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1p5rawwdWkf8N9dCq2Lxr0m5r8yL2I6ak" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1p5rawwdWkf8N9dCq2Lxr0m5r8yL2I6ak&sz=w300';"
                            alt="Logo Lý Công Quảng" 
                            class="w-11 h-11 rounded bg-white p-0.5 object-contain shrink-0"
                        >
                        <div>
                            <h3 class="text-xs sm:text-sm font-extrabold text-white uppercase leading-snug">
                                CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG LÝ CÔNG QUẢNG
                            </h3>
                            <div class="text-[11px] text-amber-400 font-semibold">Mã số thuế: 0402163371 • Website: lycongquang.com</div>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs text-slate-300">
                        <li><i class="fa-solid fa-location-dot text-amber-400 w-5"></i> <strong>Địa chỉ:</strong> 11 Đoàn Nguyễn Thục, Phường Cẩm Lệ, TP Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone-volume text-amber-400 w-5"></i> <strong>Điện thoại / Zalo:</strong> <a href="tel:0905539892" class="text-amber-300 font-bold hover:underline">0905.539.892</a></li>
                        <li><i class="fa-solid fa-globe text-amber-400 w-5"></i> <strong>Website:</strong> <a href="https://lycongquang.com" class="hover:text-white">https://lycongquang.com</a></li>
                        <li><i class="fa-brands fa-facebook text-amber-400 w-5"></i> <strong>Fanpage:</strong> <a href="https://www.facebook.com/profile.php?id=61554027984574" target="_blank" rel="noopener noreferrer" class="hover:text-white underline">CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG LÝ CÔNG QUẢNG</a></li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-4">
                    <h4 class="text-xs sm:text-sm font-extrabold text-white uppercase mb-3 border-l-4 border-amber-400 pl-2.5">
                        LĨNH VỰC HOẠT ĐỘNG
                    </h4>
                    <ul class="grid grid-cols-1 sm:grid-cols-2 gap-2 text-xs text-slate-300">
                        <li><a href="#linh-vuc" class="hover:text-amber-300">• Thiết kế kiến trúc</a></li>
                        <li><a href="#linh-vuc" class="hover:text-amber-300">• Thiết kế nội thất</a></li>
                        <li><a href="#linh-vuc" class="hover:text-amber-300">• Thi công phần thô</a></li>
                        <li><a href="#linh-vuc" class="hover:text-amber-300">• Thi công hoàn thiện</a></li>
                        <li><a href="#linh-vuc" class="hover:text-amber-300">• Xây nhà trọn gói</a></li>
                        <li><a href="#cong-trinh-thuc-te" class="hover:text-amber-300">• Thi công khách sạn, căn hộ</a></li>
                        <li><a href="#cong-trinh-thuc-te" class="hover:text-amber-300">• Thi công biệt thự, nhà phố</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-amber-300">• Dự án xây dựng Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Cam kết dịch vụ -->
                <div class="lg:col-span-3">
                    <h4 class="text-xs sm:text-sm font-extrabold text-white uppercase mb-3 border-l-4 border-amber-400 pl-2.5">
                        CAM KẾT CHẤT LƯỢNG
                    </h4>
                    <p class="text-xs text-slate-300 leading-relaxed mb-3">
                        Đặt chữ “TÂM” trong nghề lên hàng đầu để mỗi công trình luôn đạt chuẩn: An toàn – Chất lượng – Đúng tiến độ – Chi phí hợp lý.
                    </p>
                    <a href="#form-bao-gia" class="inline-block w-full text-center py-2 px-3 rounded-lg bg-amber-500 hover:bg-amber-600 text-slate-950 font-extrabold text-xs uppercase transition">
                        Đăng Ký Báo Giá Miễn Phí
                    </a>
                </div>
            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between text-[11px] text-slate-400 gap-2 text-center sm:text-left">
                <div>Copyright 2026 © <strong>CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG LÝ CÔNG QUẢNG (lycongquang.com)</strong></div>
                <div>Địa chỉ: 11 Đoàn Nguyễn Thục, Phường Cẩm Lệ, TP Đà Nẵng • SĐT: 0905.539.892</div>
            </div>
        </div>
    </footer>

    <!-- =====================================================================
         14. NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI
         ===================================================================== -->
    <!-- Cụm nút nổi bên phải màn hình -->
    <div class="fixed right-3 bottom-4 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/profile.php?id=61554027984574" target="_blank" rel="noopener noreferrer" aria-label="Chat Facebook" class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105">
            <i class="fa-brands fa-facebook-f text-sm w-4 text-center"></i>
            <span class="text-xs font-bold">Facebook</span>
        </a>

        <!-- Nút Zalo -->
        <a href="https://zalo.me/0905539892" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0905.539.892" class="flex items-center gap-2 bg-[#0068ff] hover:bg-sky-700 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105">
            <span class="font-extrabold text-[11px] bg-white text-[#0068ff] px-1.5 py-0.5 rounded-full leading-none">Zalo</span>
            <span class="text-xs font-bold">Chat Zalo</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a href="tel:0905539892" aria-label="Gọi Hotline 0905.539.892" class="animate-hotline flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white px-3.5 py-2.5 rounded-full shadow-xl transition">
            <i class="fa-solid fa-phone-volume text-sm"></i>
            <span class="text-xs font-extrabold tracking-wide">0905.539.892</span>
        </a>
    </div>

    <!-- =====================================================================
         15. JAVASCRIPT XỬ LÝ SLIDER 2 BANNER TỰ TRƯỢT, LỌC DANH MỤC & FORM BÁO GIÁ
         ===================================================================== -->
    <script>
        // 1. Đóng/Mở Menu trên điện thoại
        function toggleMobileMenu() {
            const panel = document.getElementById('mobileMenuPanel');
            const icon = document.getElementById('mobileMenuIcon');
            if (panel.classList.contains('hidden')) {
                panel.classList.remove('hidden');
                icon.classList.remove('fa-bars');
                icon.classList.add('fa-xmark');
            } else {
                panel.classList.add('hidden');
                icon.classList.remove('fa-xmark');
                icon.classList.add('fa-bars');
            }
        }

        // 2. Tự động trượt 2 Banner trên cả Máy tính và Điện thoại
        let currentBannerIndex = 0;
        const totalBanners = 2;
        let bannerInterval = null;

        function renderBannerSlide(index) {
            for (let i = 0; i < totalBanners; i++) {
                const deskSlide = document.getElementById('desktop-slide-' + i);
                const mobSlide = document.getElementById('mobile-slide-' + i);
                const dot = document.getElementById('banner-dot-' + i);

                if (i === index) {
                    if (deskSlide) {
                        deskSlide.classList.remove('opacity-0', 'pointer-events-none');
                        deskSlide.classList.add('opacity-100');
                    }
                    if (mobSlide) {
                        mobSlide.classList.remove('opacity-0', 'pointer-events-none');
                        mobSlide.classList.add('opacity-100');
                    }
                    if (dot) {
                        dot.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
                    }
                } else {
                    if (deskSlide) {
                        deskSlide.classList.remove('opacity-100');
                        deskSlide.classList.add('opacity-0', 'pointer-events-none');
                    }
                    if (mobSlide) {
                        mobSlide.classList.remove('opacity-100');
                        mobSlide.classList.add('opacity-0', 'pointer-events-none');
                    }
                    if (dot) {
                        dot.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                    }
                }
            }
        }

        function changeBannerSlide(step) {
            currentBannerIndex = (currentBannerIndex + step + totalBanners) % totalBanners;
            renderBannerSlide(currentBannerIndex);
            restartBannerTimer();
        }

        function setBannerSlide(index) {
            currentBannerIndex = index;
            renderBannerSlide(currentBannerIndex);
            restartBannerTimer();
        }

        function restartBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(function () {
                currentBannerIndex = (currentBannerIndex + 1) % totalBanners;
                renderBannerSlide(currentBannerIndex);
            }, 4500);
        }

        // 3. Lọc Danh mục Sản phẩm & Công trình thực tế trên trang chủ
        function filterProducts(category, btnEl) {
            const buttons = document.querySelectorAll('.cat-filter-btn');
            buttons.forEach(function (btn) {
                btn.classList.remove('active');
            });
            if (btnEl) btnEl.classList.add('active');

            const cards = document.querySelectorAll('#productGrid .product-card');
            cards.forEach(function (card) {
                const itemCat = card.getAttribute('data-cat');
                if (category === 'all' || itemCat === category) {
                    card.classList.remove('hidden');
                    card.classList.add('flex');
                } else {
                    card.classList.remove('flex');
                    card.classList.add('hidden');
                }
            });
        }

        // 4. Xử lý gửi Form Yêu cầu & Báo giá trên trang chủ
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('custName').value.trim();
            const phone = document.getElementById('custPhone').value.trim();
            const type = document.getElementById('custType').value;
            const budget = document.getElementById('custBudget').value;
            const service = document.getElementById('custService').value;

            const successBox = document.getElementById('quoteSuccessBox');
            const successText = document.getElementById('quoteSuccessText');

            successText.innerHTML =
                'Cảm ơn Quý khách <strong>' + name + '</strong> (SĐT: <strong>' + phone + '</strong>) đã đăng ký tư vấn hạng mục <strong>' +
                service + ' - ' + type + '</strong> (Mức đầu tư: ' + budget + '). Bộ phận Kỹ thuật & Báo giá của <strong>CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG LÝ CÔNG QUẢNG</strong> sẽ liên hệ ngay qua số <strong>0905.539.892</strong>.';
            successBox.classList.remove('hidden');
            document.getElementById('quoteRequestForm').reset();
        }

        window.onload = function () {
            restartBannerTimer();
        };
    </script>
</body>
</html>
