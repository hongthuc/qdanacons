<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CÔNG TY TNHH XÂY DỰNG QDANACONS | Thiết Kế & Thi Công Xây Dựng Tại Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH XÂY DỰNG QDANACONS - Chuyên Thiết kế kiến trúc, Thi công phần thô, Thi công hoàn thiện và Nội thất trọn gói tại Đà Nẵng. Hotline: 0913.735.458.">

    <!-- Meta Thumbnail Chia Sẻ Link (Open Graph & Zalo/Facebook Preview sử dụng Logo QDANACONS) -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="CÔNG TY TNHH XÂY DỰNG QDANACONS">
    <meta property="og:title" content="CÔNG TY TNHH XÂY DỰNG QDANACONS - qdanacons.com">
    <meta property="og:description" content="Thiết Kế Kiến Trúc – Thi Công Xây Dựng Trọn Gói – Nội Thất Chuyên Nghiệp Tại Đà Nẵng. Địa chỉ: K45/29 Lê Độ, P. Thanh Khê, TP Đà Nẵng. Hotline: 0913.735.458.">
    <meta property="og:url" content="https://qdanacons.com">
    <meta property="og:image" content="https://qdanacons.com/wp-content/uploads/logo-qdanacons-thumbnail.png">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta property="og:image:alt" content="Logo CÔNG TY TNHH XÂY DỰNG QDANACONS">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://qdanacons.com/wp-content/uploads/logo-qdanacons-thumbnail.png">

    <!-- Favicon SVG gọn nhẹ theo Logo QDANACONS -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230F2942'/%3E%3Cpath d='M32 10L12 24v28h40V24L32 10z' fill='none' stroke='%23D99B26' stroke-width='4'/%3E%3Cpath d='M24 52V32h16v20' fill='none' stroke='%23FFFFFF' stroke-width='3.5'/%3E%3Cpath d='M32 18v14' stroke='%23D99B26' stroke-width='3'/%3E%3C/svg%3E">

    <!-- Font Inter & Tailwind CSS -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            navy: '#0F2942',
                            navyDark: '#0A1D30',
                            navyLight: '#1A3E63',
                            gold: '#D99B26',
                            goldDark: '#B87E14',
                            goldLight: '#F3C668',
                            bg: '#F8FAFC',
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Thiết lập chuẩn chống tràn viền ngang và lệch trang trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
            background-color: #FFFFFF;
            color: #1E293B;
        }

        /* Khung chuẩn 95% chiều rộng màn hình trên máy tính - Không tràn viền, cân giữa tuyệt đối */
        .site-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .site-container {
                width: 95%;
                max-width: 95vw;
                padding-left: 16px;
                padding-right: 16px;
            }
        }

        /* Dropdown menu chuẩn Flatsome */
        .nav-item {
            position: relative;
        }
        .nav-dropdown {
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
        }
        .nav-item:hover .nav-dropdown {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        /* Banner Slider kích thước đồng nhất giữa 2 slide */
        .banner-slider-track {
            display: flex;
            width: 200%;
            transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
        }
        .banner-slide {
            width: 50%;
            flex-shrink: 0;
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
        @keyframes softPulse {
            0%, 100% { box-shadow: 0 0 0 0 rgba(217, 155, 38, 0.55); }
            50% { box-shadow: 0 0 0 10px rgba(217, 155, 38, 0); }
        }
        .hotline-pulse {
            animation: softPulse 2.2s infinite;
        }

        /* Ẩn thanh cuộn phụ của dải danh mục nếu có */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="bg-white text-slate-800 antialiased pb-16 md:pb-0">

    <!-- ===================================================================== -->
    <!-- [UXBUILDER: TOP BAR - THANH THÔNG TIN ĐẦU TRANG]                      -->
    <!-- ===================================================================== -->
    <div class="bg-brand-navyDark text-slate-200 text-xs border-b border-white/10">
        <div class="site-container py-2 flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <a href="tel:0913735458" class="inline-flex items-center gap-1.5 hover:text-brand-gold transition font-medium">
                    <svg class="w-3.5 h-3.5 text-brand-gold shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                    <span>0913.735.458</span>
                </a>
                <span class="hidden sm:inline text-white/30">|</span>
                <span class="hidden sm:inline-flex items-center gap-1.5 text-slate-300">
                    <svg class="w-3.5 h-3.5 text-brand-gold shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                    <span>K45/29 Lê Độ, P. Thanh Khê, TP Đà Nẵng</span>
                </span>
            </div>
            <div class="hidden md:flex items-center gap-3 text-slate-300">
                <span>Website: <strong class="text-brand-gold font-semibold">qdanacons.com</strong></span>
                <span class="text-white/30">|</span>
                <span>MST: 0402246395</span>
            </div>
        </div>
    </div>

    <!-- ===================================================================== -->
    <!-- [UXBUILDER: HEADER CHÍNH - LOGO NHỎ GỌN + MENU 1 HÀNG KHÔNG NÚT GỌI]  -->
    <!-- ===================================================================== -->
    <header class="sticky top-0 z-40 bg-white/95 backdrop-blur border-b border-slate-200 shadow-sm">
        <div class="site-container h-16 lg:h-[72px] flex items-center justify-between gap-3">

            <!-- Logo Công Ty QDANACONS (Thiết kế gọn nhỏ, sắc nét) -->
            <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group" aria-label="QDANACONS Trang chủ">
                <svg class="w-9 h-9 lg:w-10 lg:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <rect width="64" height="64" rx="12" fill="#0F2942"/>
                    <!-- Biểu tượng mái kiến trúc + chữ Q cách điệu -->
                    <path d="M32 10L12 24.5V48C12 50.2091 13.7909 52 16 52H48C50.2091 52 52 50.2091 52 48V24.5L32 10Z" stroke="#D99B26" stroke-width="3.5" stroke-linejoin="round"/>
                    <path d="M23 52V31H41V52" stroke="#FFFFFF" stroke-width="3" stroke-linejoin="round"/>
                    <path d="M32 17V31" stroke="#D99B26" stroke-width="2.5" stroke-linecap="round"/>
                    <path d="M37 45L46 53" stroke="#D99B26" stroke-width="3.5" stroke-linecap="round"/>
                    <rect x="28.5" y="37" width="7" height="7" rx="1" fill="#D99B26"/>
                </svg>
                <div class="leading-tight">
                    <div class="text-[15px] lg:text-[17px] font-extrabold tracking-tight text-brand-navy group-hover:text-brand-gold transition whitespace-nowrap">QDANACONS</div>
                    <div class="text-[9px] lg:text-[9.5px] font-semibold uppercase tracking-wider text-brand-gold whitespace-nowrap">Thiết Kế &amp; Xây Dựng</div>
                </div>
            </a>

            <!-- Menu Điều Hướng Máy Tính (Viết gọn 1 hàng, chữ nhỏ, tuyệt đối không xuống dòng tên danh mục) -->
            <nav class="hidden lg:flex items-center justify-end flex-1 min-w-0" aria-label="Menu chính">
                <ul class="flex items-center flex-nowrap gap-x-2.5 xl:gap-x-5 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-brand-navy">
                    <li class="shrink-0">
                        <a href="#trang-chu" class="block py-2 whitespace-nowrap text-brand-gold hover:text-brand-goldDark transition">Trang chủ</a>
                    </li>
                    <li class="shrink-0">
                        <a href="#gioi-thieu" class="block py-2 whitespace-nowrap hover:text-brand-gold transition">Giới thiệu</a>
                    </li>
                    <li class="nav-item shrink-0">
                        <a href="#linh-vuc" class="inline-flex items-center gap-0.5 py-2 whitespace-nowrap hover:text-brand-gold transition">
                            <span>Lĩnh vực hoạt động</span>
                            <svg class="w-3 h-3 opacity-60" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                        </a>
                        <div class="nav-dropdown absolute left-0 top-full pt-1 w-60 z-50">
                            <div class="bg-white rounded-lg shadow-xl border border-slate-100 py-2 text-[12.5px] normal-case font-medium text-slate-700">
                                <a href="#linh-vuc" class="block px-4 py-2 hover:bg-slate-50 hover:text-brand-gold transition">Thiết kế Kiến trúc – Nội thất</a>
                                <a href="#linh-vuc" class="block px-4 py-2 hover:bg-slate-50 hover:text-brand-gold transition">Thi công phần thô</a>
                                <a href="#linh-vuc" class="block px-4 py-2 hover:bg-slate-50 hover:text-brand-gold transition">Thi công hoàn thiện</a>
                                <a href="#linh-vuc" class="block px-4 py-2 hover:bg-slate-50 hover:text-brand-gold transition">Thi công nội thất</a>
                            </div>
                        </div>
                    </li>
                    <li class="nav-item shrink-0">
                        <a href="#cong-trinh" class="inline-flex items-center gap-0.5 py-2 whitespace-nowrap hover:text-brand-gold transition">
                            <span>Công trình thực tế</span>
                            <svg class="w-3 h-3 opacity-60" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                        </a>
                        <div class="nav-dropdown absolute left-0 top-full pt-1 w-60 z-50">
                            <div class="bg-white rounded-lg shadow-xl border border-slate-100 py-2 text-[12.5px] normal-case font-medium text-slate-700">
                                <a href="#cong-trinh" onclick="filterProjects('khach-san')" class="block px-4 py-2 hover:bg-slate-50 hover:text-brand-gold transition">Khách sạn – Căn hộ – Phòng trọ</a>
                                <a href="#cong-trinh" onclick="filterProjects('biet-thu')" class="block px-4 py-2 hover:bg-slate-50 hover:text-brand-gold transition">Biệt thự</a>
                                <a href="#cong-trinh" onclick="filterProjects('nha-pho')" class="block px-4 py-2 hover:bg-slate-50 hover:text-brand-gold transition">Nhà phố</a>
                                <a href="#cong-trinh" onclick="filterProjects('van-phong')" class="block px-4 py-2 hover:bg-slate-50 hover:text-brand-gold transition">Văn phòng</a>
                            </div>
                        </div>
                    </li>
                    <li class="shrink-0">
                        <a href="#du-an-da-nang" class="block py-2 whitespace-nowrap hover:text-brand-gold transition">Dự án Đà Nẵng</a>
                    </li>
                    <li class="nav-item shrink-0">
                        <a href="#bao-gia" class="inline-flex items-center gap-0.5 py-2 whitespace-nowrap hover:text-brand-gold transition">
                            <span>Báo giá</span>
                            <svg class="w-3 h-3 opacity-60" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                        </a>
                        <div class="nav-dropdown absolute right-0 top-full pt-1 w-60 z-50">
                            <div class="bg-white rounded-lg shadow-xl border border-slate-100 py-2 text-[12.5px] normal-case font-medium text-slate-700">
                                <a href="#bao-gia" onclick="selectQuoteType('Thiết kế Kiến trúc – Nội thất')" class="block px-4 py-2 hover:bg-slate-50 hover:text-brand-gold transition">Báo giá thiết kế kiến trúc</a>
                                <a href="#bao-gia" onclick="selectQuoteType('Thi công phần thô')" class="block px-4 py-2 hover:bg-slate-50 hover:text-brand-gold transition">Báo giá thi công phần thô</a>
                                <a href="#bao-gia" onclick="selectQuoteType('Thi công hoàn thiện')" class="block px-4 py-2 hover:bg-slate-50 hover:text-brand-gold transition">Báo giá thi công hoàn thiện</a>
                                <a href="#bao-gia" onclick="selectQuoteType('Thi công trọn gói')" class="block px-4 py-2 hover:bg-slate-50 hover:text-brand-gold transition">Báo giá thi công trọn gói</a>
                            </div>
                        </div>
                    </li>
                    <li class="shrink-0">
                        <a href="#doi-tac" class="block py-2 whitespace-nowrap hover:text-brand-gold transition">Đối tác</a>
                    </li>
                    <li class="shrink-0">
                        <a href="#tin-tuc" class="block py-2 whitespace-nowrap hover:text-brand-gold transition">Tin tức</a>
                    </li>
                    <li class="shrink-0">
                        <a href="#lien-he" class="block py-2 whitespace-nowrap hover:text-brand-gold transition">Liên hệ</a>
                    </li>
                </ul>
            </nav>

            <!-- Nút Mở Menu Mobile (Không đặt nút Gọi ngay trên Header) -->
            <button id="mobileMenuBtn" type="button" class="lg:hidden p-2.5 rounded-lg text-brand-navy hover:bg-slate-100 transition" aria-label="Mở menu điều hướng">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16"/>
                </svg>
            </button>
        </div>
    </header>

    <!-- Ngăn Kéo Menu Mobile (Flatsome Off-Canvas Sidebar) -->
    <div id="mobileDrawerOverlay" class="fixed inset-0 bg-brand-navyDark/60 z-50 hidden transition-opacity"></div>
    <aside id="mobileDrawer" class="fixed top-0 left-0 h-full w-72 max-w-[85vw] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
        <div class="px-5 py-4 bg-brand-navy text-white flex items-center justify-between">
            <span class="font-bold text-sm tracking-wide uppercase">Danh Mục QDANACONS</span>
            <button id="closeMobileMenuBtn" type="button" class="p-1.5 rounded-lg hover:bg-white/10" aria-label="Đóng menu">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
            </button>
        </div>
        <div class="flex-1 overflow-y-auto py-3 px-4">
            <ul class="divide-y divide-slate-100 text-sm font-semibold text-brand-navy">
                <li><a href="#trang-chu" class="mobile-nav-link block py-3 hover:text-brand-gold">Trang chủ</a></li>
                <li><a href="#gioi-thieu" class="mobile-nav-link block py-3 hover:text-brand-gold">Giới thiệu</a></li>
                <li>
                    <a href="#linh-vuc" class="mobile-nav-link block py-3 hover:text-brand-gold">Lĩnh vực hoạt động</a>
                    <ul class="pl-4 pb-2 space-y-1.5 text-xs font-medium text-slate-600">
                        <li><a href="#linh-vuc" class="mobile-nav-link block py-1">Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#linh-vuc" class="mobile-nav-link block py-1">Thi công phần thô</a></li>
                        <li><a href="#linh-vuc" class="mobile-nav-link block py-1">Thi công hoàn thiện</a></li>
                        <li><a href="#linh-vuc" class="mobile-nav-link block py-1">Thi công nội thất</a></li>
                    </ul>
                </li>
                <li>
                    <a href="#cong-trinh" class="mobile-nav-link block py-3 hover:text-brand-gold">Công trình thực tế</a>
                    <ul class="pl-4 pb-2 space-y-1.5 text-xs font-medium text-slate-600">
                        <li><a href="#cong-trinh" onclick="filterProjects('khach-san')" class="mobile-nav-link block py-1">Khách sạn – Căn hộ – Phòng trọ</a></li>
                        <li><a href="#cong-trinh" onclick="filterProjects('biet-thu')" class="mobile-nav-link block py-1">Biệt thự</a></li>
                        <li><a href="#cong-trinh" onclick="filterProjects('nha-pho')" class="mobile-nav-link block py-1">Nhà phố</a></li>
                        <li><a href="#cong-trinh" onclick="filterProjects('van-phong')" class="mobile-nav-link block py-1">Văn phòng</a></li>
                    </ul>
                </li>
                <li><a href="#du-an-da-nang" class="mobile-nav-link block py-3 hover:text-brand-gold">Dự án tại Đà Nẵng</a></li>
                <li><a href="#bao-gia" class="mobile-nav-link block py-3 hover:text-brand-gold">Yêu cầu báo giá</a></li>
                <li><a href="#doi-tac" class="mobile-nav-link block py-3 hover:text-brand-gold">Đối tác</a></li>
                <li><a href="#tin-tuc" class="mobile-nav-link block py-3 hover:text-brand-gold">Tin tức xây dựng</a></li>
                <li><a href="#lien-he" class="mobile-nav-link block py-3 hover:text-brand-gold">Liên hệ &amp; Bản đồ</a></li>
            </ul>
        </div>
        <div class="p-4 bg-slate-50 border-t border-slate-200 text-xs text-slate-600 space-y-1">
            <div class="font-bold text-brand-navy">CÔNG TY TNHH XÂY DỰNG QDANACONS</div>
            <div>K45/29 Lê Độ, P. Thanh Khê, TP Đà Nẵng</div>
            <div>Hotline: <a href="tel:0913735458" class="text-brand-gold font-bold">0913.735.458</a></div>
        </div>
    </aside>

    <!-- ===================================================================== -->
    <!-- [UXBUILDER: SECTION 1 - 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU]       -->
    <!-- Ảnh và chữ nằm trọn bên trong, cách xa viền, không mất chữ trên Mobile -->
    <!-- ===================================================================== -->
    <section id="trang-chu" class="bg-slate-50 pt-3 pb-4 lg:pt-4 lg:pb-6">
        <div class="site-container">
            <div id="heroSlider" class="relative overflow-hidden rounded-xl shadow-md bg-brand-navy select-none">
                <div id="heroTrack" class="banner-slider-track">

                    <!-- BANNER 1: Chiều cao & cấu trúc đồng nhất tuyệt đối với Banner 2 -->
                    <div class="banner-slide relative h-[320px] sm:h-[400px] lg:h-[480px] flex items-center justify-center overflow-hidden">
                        <img
                            src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1400"
                            data-fallback="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1400"
                            onerror="handleImgError(this, 'QDANACONS+XAY+DUNG')"
                            alt="Thi công xây dựng công trình thực tế QDANACONS"
                            class="absolute inset-0 w-full h-full object-cover object-center"
                        >
                        <!-- Lớp phủ tối tạo độ tương phản chữ sắc nét -->
                        <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/90 via-brand-navy/75 to-brand-navyDark/65"></div>

                        <!-- Vùng chữ nằm trọn bên trong khung an toàn, cách xa cả 4 cạnh viền -->
                        <div class="relative z-10 w-full h-full flex items-center justify-center px-11 sm:px-16 lg:px-24 py-8 sm:py-12">
                            <div class="max-w-3xl text-center text-white space-y-2.5 sm:space-y-4">
                                <p class="text-[11px] sm:text-xs lg:text-sm font-semibold uppercase tracking-[0.18em] text-brand-goldLight">
                                    CÔNG TY TNHH XÂY DỰNG QDANACONS
                                </p>
                                <h1 class="text-lg sm:text-3xl lg:text-4xl font-extrabold leading-snug tracking-tight">
                                    THIẾT KẾ KIẾN TRÚC &amp; THI CÔNG XÂY DỰNG TRỌN GÓI TẠI ĐÀ NẴNG
                                </h1>
                                <p class="text-xs sm:text-sm lg:text-base text-slate-200 max-w-2xl mx-auto leading-relaxed">
                                    Đặt chữ Tâm trong từng kết cấu — Cam kết An toàn, Chất lượng bền vững, Đúng tiến độ và Chi phí tối ưu nhất cho mọi công trình.
                                </p>
                                <div class="pt-1.5 sm:pt-2 flex flex-wrap items-center justify-center gap-2.5 sm:gap-3">
                                    <a href="#bao-gia" class="px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white text-xs sm:text-sm font-semibold transition shadow">
                                        Nhận Báo Giá Miễn Phí
                                    </a>
                                    <a href="#cong-trinh" class="px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold transition">
                                        Xem Công Trình Thực Tế
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 2: Kích thước & vùng đệm an toàn giống hệt Banner 1 -->
                    <div class="banner-slide relative h-[320px] sm:h-[400px] lg:h-[480px] flex items-center justify-center overflow-hidden">
                        <img
                            src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1400"
                            data-fallback="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1400"
                            onerror="handleImgError(this, 'DU+AN+DA+NANG')"
                            alt="Dự án xây dựng biệt thự, nhà phố và khách sạn tại Đà Nẵng"
                            class="absolute inset-0 w-full h-full object-cover object-center"
                        >
                        <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/90 via-brand-navy/75 to-brand-navyDark/65"></div>

                        <!-- Vùng chữ nằm trọn bên trong khung an toàn, cách xa cả 4 cạnh viền -->
                        <div class="relative z-10 w-full h-full flex items-center justify-center px-11 sm:px-16 lg:px-24 py-8 sm:py-12">
                            <div class="max-w-3xl text-center text-white space-y-2.5 sm:space-y-4">
                                <p class="text-[11px] sm:text-xs lg:text-sm font-semibold uppercase tracking-[0.18em] text-brand-goldLight">
                                    NHÀ Ở GIA ĐÌNH — TIÊU CHUẨN CÔNG TRÌNH
                                </p>
                                <h2 class="text-lg sm:text-3xl lg:text-4xl font-extrabold leading-snug tracking-tight">
                                    BIỆT THỰ, NHÀ PHỐ, KHÁCH SẠN &amp; CĂN HỘ CAO CẤP QDANACONS
                                </h2>
                                <p class="text-xs sm:text-sm lg:text-base text-slate-200 max-w-2xl mx-auto leading-relaxed">
                                    Đồng hành cùng chủ đầu tư từ khâu thiết kế kiến trúc, thi công phần thô đến hoàn thiện nội thất chìa khóa trao tay tại Đà Nẵng.
                                </p>
                                <div class="pt-1.5 sm:pt-2 flex flex-wrap items-center justify-center gap-2.5 sm:gap-3">
                                    <a href="#du-an-da-nang" class="px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white text-xs sm:text-sm font-semibold transition shadow">
                                        Khám Phá Dự Án Đà Nẵng
                                    </a>
                                    <a href="tel:0913735458" class="px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold transition">
                                        Tư Vấn: 0913.735.458
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>

                <!-- Nút chuyển trái/phải gọn gàng sát mép, không đè lên vùng chữ -->
                <button id="prevBannerBtn" type="button" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition" aria-label="Banner trước">
                    <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7"/></svg>
                </button>
                <button id="nextBannerBtn" type="button" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition" aria-label="Banner tiếp theo">
                    <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
                </button>

                <!-- Dấu chấm chỉ báo vị trí slide -->
                <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" data-slide="0" class="banner-dot w-6 h-2 rounded-full bg-brand-gold transition-all" aria-label="Xem banner 1"></button>
                    <button type="button" data-slide="1" class="banner-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all" aria-label="Xem banner 2"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- [UXBUILDER: SECTION 2 - LĨNH VỰC HOẠT ĐỘNG / DỊCH VỤ TIÊU BIỂU]       -->
    <!-- ===================================================================== -->
    <section id="linh-vuc" class="py-10 lg:py-14 bg-white">
        <div class="site-container">
            <div class="text-center mb-7 lg:mb-10">
                <h2 class="text-lg sm:text-xl lg:text-2xl font-extrabold uppercase tracking-wide text-brand-navy">
                    Dịch Vụ Tiêu Biểu
                </h2>
                <div class="w-14 h-1 bg-brand-gold mx-auto mt-2.5 rounded-full"></div>
                <p class="text-xs sm:text-sm text-slate-500 mt-2.5 max-w-xl mx-auto">
                    Giải pháp thiết kế và thi công xây dựng đồng bộ cho mọi quy mô công trình dân dụng và thương mại.
                </p>
            </div>

            <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Dịch vụ 1 -->
                <a href="#bao-gia" onclick="selectQuoteType('Thiết kế Kiến trúc – Nội thất')" class="group bg-slate-50 hover:bg-brand-navy rounded-xl p-4 sm:p-6 border border-slate-200 hover:border-brand-navy transition duration-300 text-center flex flex-col items-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-brand-navy group-hover:bg-brand-gold text-brand-gold group-hover:text-white flex items-center justify-center mb-3.5 transition">
                        <svg class="w-6 h-6 sm:w-7 sm:h-7" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 17V7m0 10a2 2 0 01-2 2H5a2 2 0 01-2-2V7a2 2 0 012-2h2a2 2 0 012 2m0 10a2 2 0 002 2h2a2 2 0 002-2M9 7a2 2 0 012-2h2a2 2 0 012 2m0 10V7m0 10a2 2 0 002 2h2a2 2 0 002-2V7a2 2 0 00-2-2h-2a2 2 0 00-2 2"/></svg>
                    </div>
                    <h3 class="text-[13px] sm:text-base font-bold text-brand-navy group-hover:text-white leading-snug break-words">
                        Thiết Kế Kiến Trúc – Nội Thất
                    </h3>
                    <p class="text-[11.5px] sm:text-xs text-slate-600 group-hover:text-slate-200 mt-2 leading-relaxed">
                        Hồ sơ kiến trúc, kết cấu, điện nước và phối cảnh 3D tối ưu công năng.
                    </p>
                </a>

                <!-- Dịch vụ 2 -->
                <a href="#bao-gia" onclick="selectQuoteType('Thi công phần thô')" class="group bg-slate-50 hover:bg-brand-navy rounded-xl p-4 sm:p-6 border border-slate-200 hover:border-brand-navy transition duration-300 text-center flex flex-col items-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-brand-navy group-hover:bg-brand-gold text-brand-gold group-hover:text-white flex items-center justify-center mb-3.5 transition">
                        <svg class="w-6 h-6 sm:w-7 sm:h-7" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"/></svg>
                    </div>
                    <h3 class="text-[13px] sm:text-base font-bold text-brand-navy group-hover:text-white leading-snug break-words">
                        Thi Công Phần Thô
                    </h3>
                    <p class="text-[11.5px] sm:text-xs text-slate-600 group-hover:text-slate-200 mt-2 leading-relaxed">
                        Chuẩn kỹ thuật kết cấu móng, cột, dầm, sàn bền vững theo tiêu chuẩn xây dựng.
                    </p>
                </a>

                <!-- Dịch vụ 3 -->
                <a href="#bao-gia" onclick="selectQuoteType('Thi công hoàn thiện')" class="group bg-slate-50 hover:bg-brand-navy rounded-xl p-4 sm:p-6 border border-slate-200 hover:border-brand-navy transition duration-300 text-center flex flex-col items-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-brand-navy group-hover:bg-brand-gold text-brand-gold group-hover:text-white flex items-center justify-center mb-3.5 transition">
                        <svg class="w-6 h-6 sm:w-7 sm:h-7" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"/></svg>
                    </div>
                    <h3 class="text-[13px] sm:text-base font-bold text-brand-navy group-hover:text-white leading-snug break-words">
                        Thi Công Hoàn Thiện Trọn Gói
                    </h3>
                    <p class="text-[11.5px] sm:text-xs text-slate-600 group-hover:text-slate-200 mt-2 leading-relaxed">
                        Hoàn thiện sắc nét từ ốp lát, sơn nước, trần thạch cao đến thiết bị điện nước.
                    </p>
                </a>

                <!-- Dịch vụ 4 -->
                <a href="#bao-gia" onclick="selectQuoteType('Thi công nội thất')" class="group bg-slate-50 hover:bg-brand-navy rounded-xl p-4 sm:p-6 border border-slate-200 hover:border-brand-navy transition duration-300 text-center flex flex-col items-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-brand-navy group-hover:bg-brand-gold text-brand-gold group-hover:text-white flex items-center justify-center mb-3.5 transition">
                        <svg class="w-6 h-6 sm:w-7 sm:h-7" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M4 5a1 1 0 011-1h14a1 1 0 011 1v2a1 1 0 01-1 1H5a1 1 0 01-1-1V5zM4 13a1 1 0 011-1h6a1 1 0 011 1v6a1 1 0 01-1 1H5a1 1 0 01-1-1v-6zM16 13a1 1 0 011-1h2a1 1 0 011 1v6a1 1 0 01-1 1h-2a1 1 0 01-1-1v-6z"/></svg>
                    </div>
                    <h3 class="text-[13px] sm:text-base font-bold text-brand-navy group-hover:text-white leading-snug break-words">
                        Thi Công Nội Thất
                    </h3>
                    <p class="text-[11.5px] sm:text-xs text-slate-600 group-hover:text-slate-200 mt-2 leading-relaxed">
                        Sản xuất và lắp đặt nội thất gỗ tinh tế, đồng bộ đúng bản vẽ thiết kế.
                    </p>
                </a>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- [UXBUILDER: SECTION 3 - GIỚI THIỆU QDANACONS & THẾ MẠNH]              -->
    <!-- ===================================================================== -->
    <section id="gioi-thieu" class="py-10 lg:py-16 bg-slate-50 border-y border-slate-200/80">
        <div class="site-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                <!-- Hình ảnh thực tế thi công -->
                <div class="lg:col-span-5">
                    <div class="rounded-xl overflow-hidden shadow-md border border-slate-200 bg-white">
                        <img
                            src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w1000"
                            data-fallback="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w1000"
                            onerror="handleImgError(this, 'QDANACONS+THI+CONG')"
                            alt="Đội ngũ thi công xây dựng CÔNG TY TNHH XÂY DỰNG QDANACONS"
                            class="w-full aspect-[4/3] object-cover"
                        >
                    </div>
                </div>

                <!-- Nội dung giới thiệu theo bố cục mẫu tintruongthinh.com -->
                <div class="lg:col-span-7 space-y-4">
                    <div>
                        <p class="text-xs font-bold uppercase tracking-widest text-brand-gold">Về Chúng Tôi</p>
                        <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-navy mt-1">
                            CÔNG TY TNHH XÂY DỰNG QDANACONS
                        </h2>
                        <div class="w-14 h-1 bg-brand-gold mt-3 rounded-full"></div>
                    </div>
                    <p class="text-sm sm:text-[15px] text-slate-600 leading-relaxed">
                        <strong>QDANACONS</strong> chuyên Thiết kế – Xây dựng – Thi công trọn gói các công trình Khách sạn, Biệt thự, Căn hộ cho thuê, Văn phòng và Nhà phố tại khu vực <strong>Đà Nẵng – Miền Trung</strong>.
                    </p>
                    <p class="text-sm sm:text-[15px] text-slate-600 leading-relaxed">
                        Với phương châm <strong>“Nhà ở Gia đình – Tiêu chuẩn Công trình”</strong>, chúng tôi đặt cái <strong>TÂM</strong> nghề nghiệp lên hàng đầu để mỗi công trình bàn giao luôn đạt chuẩn: <strong>AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – SỰ HÀI LÒNG CỦA KHÁCH HÀNG</strong>.
                    </p>

                    <!-- 6 Thế mạnh cốt lõi -->
                    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-3 pt-2">
                        <div class="bg-white rounded-lg p-3.5 border border-slate-200/80">
                            <h3 class="text-xs sm:text-[13px] font-bold text-brand-navy">Đội ngũ kỹ sư chuyên nghiệp</h3>
                            <p class="text-[11.5px] text-slate-500 mt-1">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư, thợ lành nghề nhiều năm kinh nghiệm.</p>
                        </div>
                        <div class="bg-white rounded-lg p-3.5 border border-slate-200/80">
                            <h3 class="text-xs sm:text-[13px] font-bold text-brand-navy">Cập nhật xu hướng hiện đại</h3>
                            <p class="text-[11.5px] text-slate-500 mt-1">Ứng dụng vật liệu bền vững và biện pháp thi công tiên tiến nhất.</p>
                        </div>
                        <div class="bg-white rounded-lg p-3.5 border border-slate-200/80">
                            <h3 class="text-xs sm:text-[13px] font-bold text-brand-navy">Giám sát tiến độ chuẩn xác</h3>
                            <p class="text-[11.5px] text-slate-500 mt-1">Báo cáo hình ảnh thi công thường xuyên, cam kết đúng tiến độ hợp đồng.</p>
                        </div>
                        <div class="bg-white rounded-lg p-3.5 border border-slate-200/80">
                            <h3 class="text-xs sm:text-[13px] font-bold text-brand-navy">Bảo hành công trình lâu dài</h3>
                            <p class="text-[11.5px] text-slate-500 mt-1">Chính sách hậu mãi tận tâm, bảo hành kết cấu và chống thấm dài hạn.</p>
                        </div>
                        <div class="bg-white rounded-lg p-3.5 border border-slate-200/80">
                            <h3 class="text-xs sm:text-[13px] font-bold text-brand-navy">Chi phí hợp lý, minh bạch</h3>
                            <p class="text-[11.5px] text-slate-500 mt-1">Dự toán rõ ràng từng hạng mục, cam kết không phát sinh chi phí ẩn.</p>
                        </div>
                        <div class="bg-white rounded-lg p-3.5 border border-slate-200/80">
                            <h3 class="text-xs sm:text-[13px] font-bold text-brand-navy">Tư vấn miễn phí 24/7</h3>
                            <p class="text-[11.5px] text-slate-500 mt-1">Hỗ trợ khảo sát thực tế, xin phép xây dựng và lên phương án sơ bộ.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- [UXBUILDER: SECTION 4 - CÔNG TRÌNH THỰC TẾ THI CÔNG (9 ẢNH DRIVE 1)]  -->
    <!-- Chia 2 cột trên điện thoại, 3 cột trên máy tính, không nhãn dán        -->
    <!-- ===================================================================== -->
    <section id="cong-trinh" class="py-10 lg:py-16 bg-white">
        <div class="site-container">
            <div class="text-center mb-6 lg:mb-8">
                <h2 class="text-lg sm:text-xl lg:text-2xl font-extrabold uppercase tracking-wide text-brand-navy">
                    Công Trình Thực Tế Thi Công Xây Dựng
                </h2>
                <div class="w-14 h-1 bg-brand-gold mx-auto mt-2.5 rounded-full"></div>
                <p class="text-xs sm:text-sm text-slate-500 mt-2.5 max-w-2xl mx-auto">
                    Hình ảnh ghi nhận thực tế quá trình thi công phần thô, hoàn thiện và bàn giao công trình của đội ngũ QDANACONS.
                </p>
            </div>

            <!-- Thanh Danh Mục Lọc Sản Phẩm / Công Trình (Nhỏ gọn, viết liền không xuống dòng tên danh mục) -->
            <div class="flex flex-wrap items-center justify-center gap-2 mb-6 lg:mb-8">
                <button type="button" onclick="filterProjects('all')" data-filter="all" class="filter-tab px-3.5 py-1.5 sm:px-4 sm:py-2 rounded-lg text-xs sm:text-[13px] font-semibold whitespace-nowrap bg-brand-navy text-white transition">
                    Tất cả
                </button>
                <button type="button" onclick="filterProjects('khach-san')" data-filter="khach-san" class="filter-tab px-3.5 py-1.5 sm:px-4 sm:py-2 rounded-lg text-xs sm:text-[13px] font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-gold hover:text-white transition">
                    Khách sạn – Căn hộ
                </button>
                <button type="button" onclick="filterProjects('biet-thu')" data-filter="biet-thu" class="filter-tab px-3.5 py-1.5 sm:px-4 sm:py-2 rounded-lg text-xs sm:text-[13px] font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-gold hover:text-white transition">
                    Biệt thự
                </button>
                <button type="button" onclick="filterProjects('nha-pho')" data-filter="nha-pho" class="filter-tab px-3.5 py-1.5 sm:px-4 sm:py-2 rounded-lg text-xs sm:text-[13px] font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-gold hover:text-white transition">
                    Nhà phố
                </button>
                <button type="button" onclick="filterProjects('van-phong')" data-filter="van-phong" class="filter-tab px-3.5 py-1.5 sm:px-4 sm:py-2 rounded-lg text-xs sm:text-[13px] font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-gold hover:text-white transition">
                    Văn phòng
                </button>
            </div>

            <!-- Lưới 9 Công Trình Thực Tế (2 cột trên điện thoại, 3 cột trên máy tính) -->
            <div id="constructionGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5 lg:gap-6">
                <!-- Nội dung được render đầy đủ 9 ảnh thực tế từ Google Drive bằng JavaScript -->
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- [UXBUILDER: SECTION 5 - DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (10 ẢNH DRIVE 2)] -->
    <!-- ===================================================================== -->
    <section id="du-an-da-nang" class="py-10 lg:py-16 bg-slate-50 border-y border-slate-200/80">
        <div class="site-container">
            <div class="text-center mb-7 lg:mb-10">
                <h2 class="text-lg sm:text-xl lg:text-2xl font-extrabold uppercase tracking-wide text-brand-navy">
                    Các Dự Án Tiêu Biểu Tại Đà Nẵng
                </h2>
                <div class="w-14 h-1 bg-brand-gold mx-auto mt-2.5 rounded-full"></div>
                <p class="text-xs sm:text-sm text-slate-500 mt-2.5 max-w-2xl mx-auto">
                    Tổng hợp những dự án nhà phố, biệt thự, khách sạn và căn hộ do CÔNG TY TNHH XÂY DỰNG QDANACONS thực hiện trên địa bàn Thành phố Đà Nẵng.
                </p>
            </div>

            <!-- Lưới 10 Dự Án Tại Đà Nẵng (2 cột trên điện thoại, 5 cột x 2 hàng cân đối trên máy tính) -->
            <div id="danangProjectsGrid" class="grid grid-cols-2 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4 lg:gap-5">
                <!-- Nội dung được render đầy đủ 10 ảnh dự án Đà Nẵng từ Google Drive bằng JavaScript -->
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- [UXBUILDER: SECTION 6 - DANH MỤC CÁC ĐỐI TÁC CHIẾN LƯỢC]              -->
    <!-- ===================================================================== -->
    <section id="doi-tac" class="py-10 lg:py-14 bg-white">
        <div class="site-container">
            <div class="text-center mb-7 lg:mb-9">
                <h2 class="text-lg sm:text-xl lg:text-2xl font-extrabold uppercase tracking-wide text-brand-navy">
                    Đối Tác Cung Ứng Vật Tư &amp; Thiết Bị
                </h2>
                <div class="w-14 h-1 bg-brand-gold mx-auto mt-2.5 rounded-full"></div>
                <p class="text-xs sm:text-sm text-slate-500 mt-2.5">
                    Cam kết sử dụng vật liệu xây dựng chính hãng từ các thương hiệu hàng đầu.
                </p>
            </div>

            <!-- 2 cột trên điện thoại, 3 cột tablet, 6 cột desktop -->
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
                <!-- Đối tác 1: Thép Hòa Phát -->
                <div class="bg-slate-50 border border-slate-200 rounded-xl p-4 h-24 flex flex-col items-center justify-center hover:border-brand-gold transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-navy">HÒA PHÁT</span>
                    <span class="text-[10px] font-semibold uppercase tracking-widest text-slate-500 mt-0.5">Thép Xây Dựng</span>
                </div>
                <!-- Đối tác 2: Xi măng Sông Gianh -->
                <div class="bg-slate-50 border border-slate-200 rounded-xl p-4 h-24 flex flex-col items-center justify-center hover:border-brand-gold transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-navy">SÔNG GIANH</span>
                    <span class="text-[10px] font-semibold uppercase tracking-widest text-slate-500 mt-0.5">Xi Măng Cao Cấp</span>
                </div>
                <!-- Đối tác 3: Sơn Jotun -->
                <div class="bg-slate-50 border border-slate-200 rounded-xl p-4 h-24 flex flex-col items-center justify-center hover:border-brand-gold transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-navy">JOTUN</span>
                    <span class="text-[10px] font-semibold uppercase tracking-widest text-slate-500 mt-0.5">Sơn Nội Ngoại Thất</span>
                </div>
                <!-- Đối tác 4: Gỗ An Cường -->
                <div class="bg-slate-50 border border-slate-200 rounded-xl p-4 h-24 flex flex-col items-center justify-center hover:border-brand-gold transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-navy">AN CƯỜNG</span>
                    <span class="text-[10px] font-semibold uppercase tracking-widest text-slate-500 mt-0.5">Vật Liệu Nội Thất</span>
                </div>
                <!-- Đối tác 5: Thiết bị TOTO -->
                <div class="bg-slate-50 border border-slate-200 rounded-xl p-4 h-24 flex flex-col items-center justify-center hover:border-brand-gold transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-navy">TOTO</span>
                    <span class="text-[10px] font-semibold uppercase tracking-widest text-slate-500 mt-0.5">Thiết Bị Vệ Sinh</span>
                </div>
                <!-- Đối tác 6: Nhôm Xingfa -->
                <div class="bg-slate-50 border border-slate-200 rounded-xl p-4 h-24 flex flex-col items-center justify-center hover:border-brand-gold transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-navy">XINGFA</span>
                    <span class="text-[10px] font-semibold uppercase tracking-widest text-slate-500 mt-0.5">Cửa Nhôm Kính</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- [UXBUILDER: SECTION 7 - FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ]      -->
    <!-- ===================================================================== -->
    <section id="bao-gia" class="py-10 lg:py-16 bg-brand-navy text-white">
        <div class="site-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">

                <!-- Cột Trái: Danh mục báo giá tham khảo nhanh (chuẩn web mẫu) -->
                <div class="lg:col-span-5 space-y-5">
                    <div>
                        <p class="text-xs font-bold uppercase tracking-widest text-brand-goldLight">Dự Toán Minh Bạch</p>
                        <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold mt-1 leading-snug">
                            Yêu Cầu Tư Vấn &amp; Báo Giá Miễn Phí
                        </h2>
                        <div class="w-14 h-1 bg-brand-gold mt-3 rounded-full"></div>
                    </div>
                    <p class="text-sm text-slate-300 leading-relaxed">
                        Quý khách hàng chỉ cần để lại thông tin công trình dự kiến. Đội ngũ kỹ sư QDANACONS sẽ liên hệ khảo sát và lập bảng dự toán chi tiết từng hạng mục hoàn toàn miễn phí.
                    </p>

                    <div class="space-y-2.5 pt-1">
                        <div onclick="selectQuoteType('Thiết kế Kiến trúc – Nội thất')" class="cursor-pointer bg-white/10 hover:bg-white/15 border border-white/15 rounded-xl p-3.5 flex items-center justify-between gap-3 transition">
                            <div>
                                <div class="text-sm font-bold text-white">Báo giá thiết kế kiến trúc – nội thất</div>
                                <div class="text-xs text-slate-300 mt-0.5">Hồ sơ 2D, phối cảnh 3D &amp; kết cấu chi tiết</div>
                            </div>
                            <span class="text-brand-goldLight font-bold text-xs whitespace-nowrap">Từ 150.000đ/m²</span>
                        </div>
                        <div onclick="selectQuoteType('Thi công phần thô')" class="cursor-pointer bg-white/10 hover:bg-white/15 border border-white/15 rounded-xl p-3.5 flex items-center justify-between gap-3 transition">
                            <div>
                                <div class="text-sm font-bold text-white">Báo giá thi công phần thô</div>
                                <div class="text-xs text-slate-300 mt-0.5">Vật tư thô chính hãng &amp; nhân công hoàn thiện</div>
                            </div>
                            <span class="text-brand-goldLight font-bold text-xs whitespace-nowrap">Từ 3.600.000đ/m²</span>
                        </div>
                        <div onclick="selectQuoteType('Thi công hoàn thiện')" class="cursor-pointer bg-white/10 hover:bg-white/15 border border-white/15 rounded-xl p-3.5 flex items-center justify-between gap-3 transition">
                            <div>
                                <div class="text-sm font-bold text-white">Báo giá thi công hoàn thiện</div>
                                <div class="text-xs text-slate-300 mt-0.5">Ốp lát, sơn bả, trần thạch cao, cửa nhôm kính</div>
                            </div>
                            <span class="text-brand-goldLight font-bold text-xs whitespace-nowrap">Từ 2.200.000đ/m²</span>
                        </div>
                        <div onclick="selectQuoteType('Thi công trọn gói')" class="cursor-pointer bg-white/10 hover:bg-white/15 border border-white/15 rounded-xl p-3.5 flex items-center justify-between gap-3 transition">
                            <div>
                                <div class="text-sm font-bold text-white">Báo giá thi công xây nhà trọn gói</div>
                                <div class="text-xs text-slate-300 mt-0.5">Chìa khóa trao tay – Tặng bản vẽ xin phép XD</div>
                            </div>
                            <span class="text-brand-goldLight font-bold text-xs whitespace-nowrap">Từ 5.800.000đ/m²</span>
                        </div>
                    </div>
                </div>

                <!-- Cột Phải: Form Nhập Liệu Gửi Yêu Cầu Báo Giá -->
                <div class="lg:col-span-7">
                    <div class="bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-xl">
                        <h3 class="text-base sm:text-lg font-extrabold text-brand-navy mb-4">
                            Gửi Thông Tin Nhận Báo Giá Nhanh
                        </h3>
                        <form id="quoteForm" class="space-y-4">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label for="customerName" class="block text-xs font-semibold text-slate-700 mb-1.5">Họ và tên *</label>
                                    <input id="customerName" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-gold focus:ring-1 focus:ring-brand-gold">
                                </div>
                                <div>
                                    <label for="customerPhone" class="block text-xs font-semibold text-slate-700 mb-1.5">Số điện thoại / Zalo *</label>
                                    <input id="customerPhone" type="tel" required placeholder="VD: 0913 735 458" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-gold focus:ring-1 focus:ring-brand-gold">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label for="projectType" class="block text-xs font-semibold text-slate-700 mb-1.5">Loại công trình</label>
                                    <select id="projectType" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-gold focus:ring-1 focus:ring-brand-gold">
                                        <option value="Nhà phố">Nhà phố</option>
                                        <option value="Biệt thự">Biệt thự</option>
                                        <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                        <option value="Văn phòng">Văn phòng</option>
                                        <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                    </select>
                                </div>
                                <div>
                                    <label for="servicePackage" class="block text-xs font-semibold text-slate-700 mb-1.5">Gói dịch vụ quan tâm</label>
                                    <select id="servicePackage" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-gold focus:ring-1 focus:ring-brand-gold">
                                        <option value="Thi công trọn gói">Thi công trọn gói</option>
                                        <option value="Thiết kế Kiến trúc – Nội thất">Thiết kế Kiến trúc – Nội thất</option>
                                        <option value="Thi công phần thô">Thi công phần thô</option>
                                        <option value="Thi công hoàn thiện">Thi công hoàn thiện</option>
                                        <option value="Thi công nội thất">Thi công nội thất</option>
                                    </select>
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label for="customerEmail" class="block text-xs font-semibold text-slate-700 mb-1.5">Email (nếu có)</label>
                                    <input id="customerEmail" type="email" placeholder="example@gmail.com" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-gold focus:ring-1 focus:ring-brand-gold">
                                </div>
                                <div>
                                    <label for="investmentBudget" class="block text-xs font-semibold text-slate-700 mb-1.5">Mức đầu tư dự kiến</label>
                                    <select id="investmentBudget" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-gold focus:ring-1 focus:ring-brand-gold">
                                        <option value="Chưa xác định">Chưa xác định</option>
                                        <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                        <option value="500 triệu – 1 tỷ">500 triệu – 1 tỷ</option>
                                        <option value="1 tỷ – 2 tỷ">1 tỷ – 2 tỷ</option>
                                        <option value="2 tỷ – 3 tỷ">2 tỷ – 3 tỷ</option>
                                        <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                    </select>
                                </div>
                            </div>

                            <div>
                                <label for="customerNote" class="block text-xs font-semibold text-slate-700 mb-1.5">Yêu cầu chi tiết (diện tích đất, số tầng, địa điểm...)</label>
                                <textarea id="customerNote" rows="3" placeholder="Ví dụ: Đất 5x20m tại quận Thanh Khê, Đà Nẵng, dự kiến xây nhà phố 3 tầng..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-gold focus:ring-1 focus:ring-brand-gold"></textarea>
                            </div>

                            <button type="submit" class="w-full py-3 px-6 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white font-bold text-sm uppercase tracking-wide transition shadow-md">
                                Gửi Yêu Cầu Báo Giá Ngay
                            </button>

                            <!-- Hộp thông báo phản hồi trực tiếp (không dùng alert) -->
                            <div id="quoteFeedback" class="hidden rounded-lg p-3.5 bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium"></div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- [UXBUILDER: SECTION 8 - DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ]    -->
    <!-- ===================================================================== -->
    <section id="tin-tuc" class="py-10 lg:py-16 bg-white">
        <div class="site-container">
            <div class="text-center mb-7 lg:mb-10">
                <h2 class="text-lg sm:text-xl lg:text-2xl font-extrabold uppercase tracking-wide text-brand-navy">
                    Tin Tức &amp; Cẩm Nang Xây Dựng
                </h2>
                <div class="w-14 h-1 bg-brand-gold mx-auto mt-2.5 rounded-full"></div>
                <p class="text-xs sm:text-sm text-slate-500 mt-2.5 max-w-2xl mx-auto">
                    Chia sẻ kinh nghiệm kỹ thuật thi công, xu hướng thiết kế kiến trúc và dự toán xây dựng nhà ở tại Đà Nẵng.
                </p>
            </div>

            <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div id="newsGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Danh sách bài viết được render bằng JavaScript và có thể bấm đọc chi tiết -->
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- [UXBUILDER: SECTION 9 - GOOGLE MAP & FANPAGE NGOÀI TRANG CHỦ]         -->
    <!-- ===================================================================== -->
    <section id="lien-he" class="py-10 lg:py-16 bg-slate-50 border-t border-slate-200/80">
        <div class="site-container">
            <div class="text-center mb-7 lg:mb-10">
                <h2 class="text-lg sm:text-xl lg:text-2xl font-extrabold uppercase tracking-wide text-brand-navy">
                    Kết Nối Fanpage &amp; Bản Đồ Chỉ Đường
                </h2>
                <div class="w-14 h-1 bg-brand-gold mx-auto mt-2.5 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">

                <!-- Cột Trái: Bản Đồ Google Map Ngoài Trang Chủ (K45/29 Lê Độ, P. Thanh Khê, TP Đà Nẵng) -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
                    <div class="px-5 py-3.5 border-b border-slate-100 flex flex-wrap items-center justify-between gap-2">
                        <div>
                            <h3 class="text-sm sm:text-base font-bold text-brand-navy">Vị Trí Văn Phòng QDANACONS Trên Google Map</h3>
                            <p class="text-xs text-slate-500 mt-0.5">K45/29 Lê Độ, Phường Thanh Khê, TP Đà Nẵng</p>
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=K45/29+L%C3%AA+%C4%90%E1%BB%99,+Thanh+Kh%C3%AA,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-brand-gold hover:text-brand-goldDark underline">
                            Mở bản đồ lớn
                        </a>
                    </div>
                    <div class="w-full flex-1 min-h-[300px] sm:min-h-[340px]">
                        <iframe
                            title="Bản đồ CÔNG TY TNHH XÂY DỰNG QDANACONS - K45/29 Lê Độ, Thanh Khê, Đà Nẵng"
                            src="https://maps.google.com/maps?q=K45/29%20L%C3%AA%20%C4%90%E1%BB%99,%20Thanh%20Kh%C3%AA,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full min-h-[300px] sm:min-h-[340px] border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade"
                            allowfullscreen>
                        </iframe>
                    </div>
                </div>

                <!-- Cột Phải: Fanpage Facebook Ngoài Trang Chủ -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
                    <div class="px-5 py-3.5 border-b border-slate-100 flex items-center justify-between">
                        <h3 class="text-sm sm:text-base font-bold text-brand-navy">Fanpage Chính Thức QDANACONS</h3>
                        <a href="https://www.facebook.com/qdanacons" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-blue-600 hover:underline">
                            facebook.com/qdanacons
                        </a>
                    </div>

                    <!-- Khung Fanpage trực quan, hiển thị đẹp ổn định cả trên máy tính & điện thoại -->
                    <div class="p-4 sm:p-5 flex-1 flex flex-col justify-between space-y-4">
                        <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-50">
                            <!-- Ảnh bìa Fanpage lấy từ công trình thực tế -->
                            <div class="relative h-36 sm:h-40 overflow-hidden bg-brand-navy">
                                <img
                                    src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w900"
                                    data-fallback="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w900"
                                    onerror="handleImgError(this, 'FANPAGE+QDANACONS')"
                                    alt="Ảnh bìa Fanpage CÔNG TY TNHH XÂY DỰNG QDANACONS"
                                    class="w-full h-full object-cover"
                                >
                                <div class="absolute inset-0 bg-gradient-to-t from-brand-navyDark/85 via-brand-navyDark/30 to-transparent"></div>
                                <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                                    <div class="w-12 h-12 rounded-lg bg-brand-navy border-2 border-white shadow flex items-center justify-center shrink-0">
                                        <svg class="w-8 h-8" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path d="M32 10L12 24.5V48C12 50.2 13.8 52 16 52H48C50.2 52 52 50.2 52 48V24.5L32 10Z" stroke="#D99B26" stroke-width="4" stroke-linejoin="round"/>
                                            <path d="M23 52V31H41V52" stroke="#FFFFFF" stroke-width="3.5" stroke-linejoin="round"/>
                                        </svg>
                                    </div>
                                    <div class="text-white min-w-0">
                                        <div class="text-sm font-extrabold leading-tight">CÔNG TY TNHH XÂY DỰNG QDANACONS</div>
                                        <div class="text-[11px] text-slate-200 mt-0.5">Thiết kế &amp; Thi công xây dựng tại Đà Nẵng</div>
                                    </div>
                                </div>
                            </div>

                            <!-- Nội dung bài ghim trên Fanpage -->
                            <div class="p-3.5 bg-white space-y-2.5">
                                <p class="text-xs text-slate-600 leading-relaxed">
                                    Cập nhật tiến độ thi công thực tế hàng ngày, mẫu thiết kế nhà phố, biệt thự, khách sạn và báo giá xây nhà trọn gói mới nhất tại Đà Nẵng.
                                </p>
                                <div class="flex flex-wrap items-center gap-2 pt-1">
                                    <a href="https://www.facebook.com/qdanacons" target="_blank" rel="noopener noreferrer" class="flex-1 inline-flex items-center justify-center gap-1.5 px-3 py-2 rounded-lg bg-[#1877F2] hover:bg-[#166FE5] text-white text-xs font-semibold transition">
                                        <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
                                        <span>Theo Dõi Fanpage</span>
                                    </a>
                                    <a href="https://zalo.me/0913735458" target="_blank" rel="noopener noreferrer" class="flex-1 inline-flex items-center justify-center gap-1.5 px-3 py-2 rounded-lg bg-brand-navy hover:bg-brand-navyLight text-white text-xs font-semibold transition">
                                        <span>Nhắn Tin Tư Vấn</span>
                                    </a>
                                </div>
                            </div>
                        </div>

                        <!-- Thông tin liên hệ nhanh bổ sung -->
                        <div class="grid grid-cols-2 gap-2.5 text-xs">
                            <div class="bg-slate-50 rounded-lg p-3 border border-slate-200/80">
                                <div class="text-slate-500">Hotline / Zalo</div>
                                <a href="tel:0913735458" class="font-bold text-brand-navy hover:text-brand-gold block mt-0.5">0913.735.458</a>
                            </div>
                            <div class="bg-slate-50 rounded-lg p-3 border border-slate-200/80">
                                <div class="text-slate-500">Website chính thức</div>
                                <a href="https://qdanacons.com" class="font-bold text-brand-navy hover:text-brand-gold block mt-0.5">qdanacons.com</a>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- [UXBUILDER: FOOTER CHUẨN FLATSOME 3 CỘT]                              -->
    <!-- ===================================================================== -->
    <footer class="bg-brand-navyDark text-slate-300 pt-10 pb-8 border-t-4 border-brand-gold">
        <div class="site-container">
            <div class="grid grid-cols-1 md:grid-cols-12 gap-8 pb-8 border-b border-white/10">

                <!-- Cột 1: Thông tin pháp lý công ty -->
                <div class="md:col-span-5 space-y-3">
                    <div class="flex items-center gap-2.5">
                        <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <rect width="64" height="64" rx="12" fill="#1A3E63"/>
                            <path d="M32 10L12 24.5V48C12 50.2 13.8 52 16 52H48C50.2 52 52 50.2 52 48V24.5L32 10Z" stroke="#D99B26" stroke-width="3.5" stroke-linejoin="round"/>
                            <path d="M23 52V31H41V52" stroke="#FFFFFF" stroke-width="3" stroke-linejoin="round"/>
                            <path d="M32 17V31" stroke="#D99B26" stroke-width="2.5" stroke-linecap="round"/>
                            <rect x="28.5" y="37" width="7" height="7" rx="1" fill="#D99B26"/>
                        </svg>
                        <div>
                            <div class="text-base font-extrabold text-white tracking-tight">CÔNG TY TNHH XÂY DỰNG QDANACONS</div>
                            <div class="text-[11px] text-brand-goldLight font-medium">qdanacons.com</div>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300 pt-1">
                        <li><strong class="text-white">Địa chỉ:</strong> K45/29 Lê Độ, Phường Thanh Khê, TP Đà Nẵng</li>
                        <li><strong class="text-white">Hotline / Zalo:</strong> <a href="tel:0913735458" class="text-brand-goldLight hover:underline font-semibold">0913.735.458</a></li>
                        <li><strong class="text-white">Mã số thuế:</strong> 0402246395</li>
                        <li><strong class="text-white">Website:</strong> <a href="https://qdanacons.com" class="hover:text-brand-goldLight">https://qdanacons.com</a></li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="md:col-span-3 space-y-3">
                    <h4 class="text-sm font-bold uppercase tracking-wider text-white">Lĩnh Vực Hoạt Động</h4>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><a href="#linh-vuc" class="hover:text-brand-goldLight transition">Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#linh-vuc" class="hover:text-brand-goldLight transition">Thi công phần thô</a></li>
                        <li><a href="#linh-vuc" class="hover:text-brand-goldLight transition">Thi công hoàn thiện</a></li>
                        <li><a href="#linh-vuc" class="hover:text-brand-goldLight transition">Thi công nội thất trọn gói</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục công trình & báo giá -->
                <div class="md:col-span-4 space-y-3">
                    <h4 class="text-sm font-bold uppercase tracking-wider text-white">Danh Mục Công Trình</h4>
                    <ul class="grid grid-cols-2 gap-2 text-xs sm:text-sm">
                        <li><a href="#cong-trinh" onclick="filterProjects('khach-san')" class="hover:text-brand-goldLight transition">Khách sạn – Căn hộ</a></li>
                        <li><a href="#cong-trinh" onclick="filterProjects('biet-thu')" class="hover:text-brand-goldLight transition">Biệt thự hiện đại</a></li>
                        <li><a href="#cong-trinh" onclick="filterProjects('nha-pho')" class="hover:text-brand-goldLight transition">Nhà phố Đà Nẵng</a></li>
                        <li><a href="#cong-trinh" onclick="filterProjects('van-phong')" class="hover:text-brand-goldLight transition">Văn phòng – Showroom</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-brand-goldLight transition">Dự án tại Đà Nẵng</a></li>
                        <li><a href="#bao-gia" class="hover:text-brand-goldLight transition">Báo giá xây dựng</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
                <div>Copyright 2026 &copy; CÔNG TY TNHH XÂY DỰNG QDANACONS. Bảo lưu mọi quyền.</div>
                <div>Thiết kế chuẩn giao diện Flatsome — <span class="text-brand-goldLight">qdanacons.com</span></div>
            </div>
        </div>
    </footer>

    <!-- ===================================================================== -->
    <!-- NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (MÁY TÍNH & ĐIỆN THOẠI)  -->
    <!-- ===================================================================== -->

    <!-- Phiên bản Máy Tính (Cụm nút nổi gọn gàng bên phải dưới) -->
    <div class="hidden md:flex fixed right-4 bottom-6 z-40 flex-col items-end gap-2.5">
        <!-- Nút Zalo -->
        <a href="https://zalo.me/0913735458" target="_blank" rel="noopener noreferrer" class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition">
            <span class="font-extrabold text-xs tracking-tight bg-white text-[#0068FF] w-6 h-6 rounded-full flex items-center justify-center">Z</span>
            <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
        </a>
        <!-- Nút Facebook -->
        <a href="https://www.facebook.com/qdanacons" target="_blank" rel="noopener noreferrer" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1465D1] text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition">
            <svg class="w-5 h-5 fill-current shrink-0" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
            <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>
        <!-- Nút Hotline -->
        <a href="tel:0913735458" class="hotline-pulse flex items-center gap-2 bg-brand-gold hover:bg-brand-goldDark text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition">
            <svg class="w-5 h-5 shrink-0" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
            <span class="text-xs font-extrabold whitespace-nowrap">0913.735.458</span>
        </a>
    </div>

    <!-- Phiên bản Điện Thoại (Thanh liên hệ cố định dưới đáy - Dễ chạm, không che hình sản phẩm) -->
    <div class="md:hidden fixed bottom-0 left-0 right-0 z-40 bg-white border-t border-slate-200 shadow-[0_-4px_12px_rgba(0,0,0,0.08)] grid grid-cols-3 divide-x divide-slate-200">
        <a href="tel:0913735458" class="flex items-center justify-center gap-1.5 py-3 bg-brand-gold text-white font-bold text-xs">
            <svg class="w-4 h-4 shrink-0" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
            <span>Hotline</span>
        </a>
        <a href="https://zalo.me/0913735458" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 py-3 bg-[#0068FF] text-white font-bold text-xs">
            <span class="w-4 h-4 rounded-full bg-white text-[#0068FF] text-[10px] font-extrabold flex items-center justify-center">Z</span>
            <span>Zalo</span>
        </a>
        <a href="https://www.facebook.com/qdanacons" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 py-3 bg-[#1877F2] text-white font-bold text-xs">
            <svg class="w-4 h-4 fill-current shrink-0" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
            <span>Facebook</span>
        </a>
    </div>

    <!-- ===================================================================== -->
    <!-- MODAL XEM ẢNH CÔNG TRÌNH THỰC TẾ & ĐỌC BÀI VIẾT                       -->
    <!-- ===================================================================== -->
    <div id="detailModal" class="fixed inset-0 z-50 hidden items-center justify-center bg-brand-navyDark/80 p-3 sm:p-6">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl">
            <div class="sticky top-0 bg-white px-4 sm:px-6 py-3.5 border-b border-slate-200 flex items-center justify-between gap-3">
                <h3 id="modalTitle" class="text-sm sm:text-base font-extrabold text-brand-navy leading-snug"></h3>
                <button type="button" onclick="closeDetailModal()" class="p-1.5 rounded-lg text-slate-500 hover:bg-slate-100" aria-label="Đóng cửa sổ">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
                </button>
            </div>
            <div class="p-4 sm:p-6 space-y-4">
                <div class="rounded-lg overflow-hidden bg-slate-100">
                    <img id="modalImage" src="" alt="" class="w-full max-h-[420px] object-cover">
                </div>
                <div id="modalSubtitle" class="text-xs font-semibold uppercase tracking-wider text-brand-gold"></div>
                <p id="modalDesc" class="text-sm text-slate-600 leading-relaxed"></p>
                <div class="pt-2 flex flex-wrap gap-2.5">
                    <a href="#bao-gia" onclick="closeDetailModal()" class="px-4 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white text-xs sm:text-sm font-bold transition">
                        Nhận Báo Giá Công Trình Tương Tự
                    </a>
                    <a href="tel:0913735458" class="px-4 py-2.5 rounded-lg bg-brand-navy hover:bg-brand-navyLight text-white text-xs sm:text-sm font-bold transition">
                        Gọi Kỹ Sư: 0913.735.458
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- ===================================================================== -->
    <!-- JAVASCRIPT: DỮ LIỆU 19 ẢNH DRIVE, SLIDER, BỘ LỌC & XỬ LÝ FORM         -->
    <!-- ===================================================================== -->
    <script>
        /**
         * Hàm xử lý fallback thông minh khi tải ảnh từ Google Drive:
         * 1. Thử link trực tiếp lh3.googleusercontent.com
         * 2. Nếu lỗi, chuyển sang drive.google.com/thumbnail
         * 3. Nếu vẫn lỗi, hiển thị ảnh placeholder chuyên nghiệp
         */
        function handleImgError(imgEl, label) {
            try {
                if (!imgEl.dataset.triedFallback && imgEl.dataset.fallback) {
                    imgEl.dataset.triedFallback = '1';
                    imgEl.src = imgEl.dataset.fallback;
                } else if (!imgEl.dataset.triedPlaceholder) {
                    imgEl.dataset.triedPlaceholder = '1';
                    imgEl.src = 'https://placehold.co/800x600/0F2942/D99B26?text=' + encodeURIComponent(label || 'QDANACONS');
                }
            } catch (e) {
                console.error('Lỗi tải ảnh:', e);
            }
        }

        function drivePrimaryUrl(id) {
            return 'https://lh3.googleusercontent.com/d/' + id + '=w1000';
        }
        function driveFallbackUrl(id) {
            return 'https://drive.google.com/thumbnail?id=' + id + '&sz=w1000';
        }

        // =====================================================================
        // DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (NHÓM GOOGLE DRIVE 1)
        // =====================================================================
        const constructionProjects = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                title: 'Thi Công Phần Thô & Kết Cấu Móng Bê Tông Cốt Thép',
                category: 'nha-pho',
                categoryName: 'Nhà phố – Thi công phần thô',
                desc: 'Hạng mục thi công móng, gia công lắp dựng cốt thép và đổ bê tông đúng mác kỹ thuật dưới sự giám sát chặt chẽ của kỹ sư QDANACONS.'
            },
            {
                id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                title: 'Thi Công Khung Sàn Nhà Phố 3 Tầng Tại Thanh Khê',
                category: 'nha-pho',
                categoryName: 'Nhà phố – Thi công phần thô',
                desc: 'Công trình nhà phố hiện đại được triển khai hệ cốp pha, cây chống an toàn và kiểm tra cao độ sàn chuẩn xác từng milimet.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                title: 'Thi Công Xây Dựng Khách Sạn & Căn Hộ Cho Thuê',
                category: 'khach-san',
                categoryName: 'Khách sạn – Căn hộ',
                desc: 'Thi công trọn gói công trình căn hộ dịch vụ nhiều tầng, tối ưu không gian khai thác kinh doanh và hệ thống kỹ thuật PCCC, cấp thoát nước.'
            },
            {
                id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                title: 'Thi Công Kết Cấu Biệt Thự Hiện Đại 2 Mặt Tiền',
                category: 'biet-thu',
                categoryName: 'Biệt thự – Thi công trọn gói',
                desc: 'Biệt thự sân vườn được thi công khung kết cấu vượt nhịp lớn, đảm bảo tính thẩm mỹ kiến trúc và độ bền vững dài lâu.'
            },
            {
                id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                title: 'Thi Công Hoàn Thiện Mặt Tiền Nhà Phố Hiện Đại',
                category: 'nha-pho',
                categoryName: 'Nhà phố – Thi công hoàn thiện',
                desc: 'Hạng mục tô trát tường phẳng mịn, chống thấm ngoài trời và hoàn thiện mặt đứng sang trọng đúng theo bản vẽ 3D.'
            },
            {
                id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                title: 'Thi Công Xây Dựng Căn Hộ Dịch Vụ Cao Cấp',
                category: 'khach-san',
                categoryName: 'Khách sạn – Căn hộ',
                desc: 'Triển khai đồng bộ từ phần thô đến hệ thống điện nước âm tường, đảm bảo tiến độ nhanh và chất lượng bàn giao vượt trội.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                title: 'Thi Công Trọn Gói Văn Phòng Làm Việc & Showroom',
                category: 'van-phong',
                categoryName: 'Văn phòng – Thương mại',
                desc: 'Thiết kế và thi công cải tạo không gian văn phòng hiện đại, tối ưu ánh sáng tự nhiên và công năng vận hành doanh nghiệp.'
            },
            {
                id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                title: 'Thi Công Hoàn Thiện Biệt Thự Khu Đô Thị Hòa Xuân',
                category: 'biet-thu',
                categoryName: 'Biệt thự – Hoàn thiện nội ngoại thất',
                desc: 'Kiểm soát tỉ mỉ từng hạng mục ốp lát gạch đá, trần thạch cao và sơn nước cao cấp mang lại vẻ đẹp tinh tế cho ngôi nhà.'
            },
            {
                id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                title: 'Thi Công Xây Dựng Tòa Nhà Văn Phòng Kết Hợp Ở',
                category: 'van-phong',
                categoryName: 'Văn phòng – Nhà phố kinh doanh',
                desc: 'Giải pháp thiết kế và xây dựng trọn gói tối ưu diện tích sàn sử dụng, kết hợp hài hòa giữa không gian làm việc và sinh hoạt gia đình.'
            }
        ];

        // =====================================================================
        // DỮ LIỆU 10 ẢNH DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (NHÓM GOOGLE DRIVE 2)
        // =====================================================================
        const danangProjects = [
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                title: 'Biệt Thự Hiện Đại Khu Đô Thị Hòa Xuân – Cẩm Lệ',
                location: 'Quận Cẩm Lệ, TP Đà Nẵng',
                desc: 'Dự án thiết kế và thi công trọn gói biệt thự gia đình phong cách hiện đại, không gian mở thoáng đãng gần sông.'
            },
            {
                id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                title: 'Khách Sạn Boutique Ven Biển Mỹ Khê – Sơn Trà',
                location: 'Quận Sơn Trà, TP Đà Nẵng',
                desc: 'Công trình khách sạn tiêu chuẩn du lịch được QDANACONS triển khai đúng tiến độ khai trương mùa cao điểm.'
            },
            {
                id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                title: 'Nhà Phố 3 Tầng Hiện Đại Đường Lê Độ – Thanh Khê',
                location: 'Quận Thanh Khê, TP Đà Nẵng',
                desc: 'Mẫu nhà phố tối ưu thông gió tự nhiên với hệ giếng trời trung tâm và mặt tiền ốp đá tự nhiên bền đẹp.'
            },
            {
                id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                title: 'Căn Hộ Cho Thuê Cao Cấp Khu An Thượng – Ngũ Hành Sơn',
                location: 'Quận Ngũ Hành Sơn, TP Đà Nẵng',
                desc: 'Dự án căn hộ dịch vụ 6 tầng với công năng tối ưu, nội thất đồng bộ phục vụ khách lưu trú dài hạn tại Đà Nẵng.'
            },
            {
                id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                title: 'Nhà Phố Kết Hợp Văn Phòng Quận Hải Châu',
                location: 'Quận Hải Châu, TP Đà Nẵng',
                desc: 'Công trình trung tâm thành phố kết hợp không gian văn phòng tầng trệt và căn hộ gia đình tiện nghi các tầng trên.'
            },
            {
                id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                title: 'Biệt Thự 2 Mặt Tiền Khu Đô Thị Nam Việt Á',
                location: 'Quận Ngũ Hành Sơn, TP Đà Nẵng',
                desc: 'Thiết kế sang trọng với hình khối kiến trúc khỏe khoắn, sân vườn tiểu cảnh xanh mát và nội thất gỗ cao cấp.'
            },
            {
                id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                title: 'Nhà Phố Gia Đình Khu Đô Thị Phước Lý – Liên Chiểu',
                location: 'Quận Liên Chiểu, TP Đà Nẵng',
                desc: 'Thi công chìa khóa trao tay cho gia đình trẻ với ngân sách tối ưu, bảo hành kết cấu dài hạn.'
            },
            {
                id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                title: 'Tòa Nhà Căn Hộ Dịch Vụ View Sông Hàn',
                location: 'Quận Sơn Trà, TP Đà Nẵng',
                desc: 'Công trình căn hộ cao cấp thiết kế hiện đại, ban công rộng đón gió sông và hệ thống kỹ thuật tiêu chuẩn.'
            },
            {
                id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                title: 'Biệt Thự Vườn Nghỉ Dưỡng Huyện Hòa Vang',
                location: 'Huyện Hòa Vang, TP Đà Nẵng',
                desc: 'Không gian sống hòa mình vào thiên nhiên với kết cấu mái Nhật thanh lịch và vật liệu hoàn thiện thân thiện.'
            },
            {
                id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                title: 'Nhà Phố 4 Tầng Khu Đô Thị Euro Village Đà Nẵng',
                location: 'Quận Sơn Trà, TP Đà Nẵng',
                desc: 'Công trình nhà ở cao cấp được thi công hoàn thiện tỉ mỉ từ ngoại thất đến từng chi tiết nội thất phòng khách và bếp.'
            }
        ];

        // =====================================================================
        // DỮ LIỆU 4 BÀI VIẾT CẨM NANG XÂY DỰNG TRANG CHỦ
        // =====================================================================
        const newsArticles = [
            {
                imgId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                date: '18/11/2026',
                title: 'Hướng dẫn bảo dưỡng bê tông móng đúng cách khi thi công nhà ở',
                excerpt: 'Bê tông móng đóng vai trò quyết định khả năng chịu tải toàn bộ công trình. Tìm hiểu quy trình tưới nước giữ ẩm chuẩn kỹ thuật.',
                content: 'Trong quá trình thi công xây dựng, việc bảo dưỡng bê tông móng sau khi đổ là bước tối quan trọng giúp bê tông đạt cường độ thiết kế và hạn chế tối đa vết nứt co ngót. Trong 7 ngày đầu tiên, cần giữ ẩm liên tục bề mặt bê tông bằng bao tải ướt hoặc phun sương nhẹ, tránh ánh nắng trực tiếp và không tác động rung chấn mạnh lên kết cấu mới đổ.'
            },
            {
                imgId: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                date: '12/11/2026',
                title: '03 nỗi lo lớn nhất khi xây nhà mà chủ đầu tư thường gặp phải',
                excerpt: 'Phát sinh chi phí, chậm tiến độ và chất lượng vật tư không đúng cam kết là ba vấn đề cần kiểm soát ngay từ khâu ký hợp đồng.',
                content: 'Để tránh những rủi ro phổ biến khi xây nhà tại Đà Nẵng, chủ đầu tư nên lựa chọn đơn vị nhà thầu có hồ sơ thiết kế chi tiết trước khi khởi công, bảng dự toán vật tư ghi rõ thương hiệu và đơn giá minh bạch, đồng thời quy định lộ trình thanh toán theo từng giai đoạn nghiệm thu thực tế.'
            },
            {
                imgId: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                date: '05/11/2026',
                title: 'Tâm lý học không gian: Nội thất tác động thế nào đến cuộc sống?',
                excerpt: 'Ánh sáng tự nhiên, tỷ lệ không gian và bảng màu vật liệu hài hòa giúp nâng cao chất lượng nghỉ ngơi cho mọi thành viên.',
                content: 'Thiết kế kiến trúc và nội thất hiện đại không chỉ dừng lại ở vẻ đẹp hình thức mà còn hướng đến trải nghiệm cảm xúc của gia chủ. Việc bố trí giếng trời thông thoáng, tận dụng ánh sáng tự nhiên và lựa chọn gam màu trung tính ấm áp sẽ mang lại nguồn năng lượng tích cực mỗi ngày.'
            },
            {
                imgId: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                date: '29/10/2026',
                title: 'Kinh nghiệm dự toán chi phí xây nhà trọn gói tại Đà Nẵng năm 2026',
                excerpt: 'Cách tính diện tích xây dựng (móng, sàn, mái) và phân bổ ngân sách hợp lý giữa phần thô và phần hoàn thiện nội thất.',
                content: 'Chi phí xây nhà trọn gói phụ thuộc vào diện tích sàn, loại móng (móng đơn, móng băng hay móng cọc), phong cách kiến trúc và phân khúc vật liệu hoàn thiện. Liên hệ trực tiếp kỹ sư QDANACONS qua hotline 0913.735.458 để nhận bảng bóc tách dự toán chi tiết miễn phí theo đúng kích thước lô đất của bạn.'
            }
        ];

        // =====================================================================
        // RENDER CÔNG TRÌNH THỰC TẾ (KHÔNG NHÃN DÁN, 2 CỘT MOBILE, FULL CHỮ)
        // =====================================================================
        function renderConstructionProjects(filter) {
            const container = document.getElementById('constructionGrid');
            if (!container) return;

            const filtered = filter === 'all'
                ? constructionProjects
                : constructionProjects.filter(item => item.category === filter);

            container.innerHTML = filtered.map((item, idx) => `
                <article onclick="openProjectModal('construction', ${constructionProjects.indexOf(item)})" class="cursor-pointer group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-gold hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                        <img
                            src="${drivePrimaryUrl(item.id)}"
                            data-fallback="${driveFallbackUrl(item.id)}"
                            onerror="handleImgError(this, 'CONG+TRINH+QDANACONS')"
                            alt="${item.title}"
                            loading="lazy"
                            class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] font-semibold text-brand-gold mb-1">${item.categoryName}</div>
                            <h3 class="text-[12.5px] sm:text-sm md:text-[15px] font-bold text-brand-navy group-hover:text-brand-gold transition leading-snug break-words">
                                ${item.title}
                            </h3>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        function filterProjects(category) {
            renderConstructionProjects(category);
            document.querySelectorAll('.filter-tab').forEach(btn => {
                if (btn.dataset.filter === category) {
                    btn.classList.remove('bg-slate-100', 'text-slate-700');
                    btn.classList.add('bg-brand-navy', 'text-white');
                } else {
                    btn.classList.remove('bg-brand-navy', 'text-white');
                    btn.classList.add('bg-slate-100', 'text-slate-700');
                }
            });
        }

        // =====================================================================
        // RENDER 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (2 CỘT MOBILE, 5 CỘT DESKTOP)
        // =====================================================================
        function renderDaNangProjects() {
            const container = document.getElementById('danangProjectsGrid');
            if (!container) return;

            container.innerHTML = danangProjects.map((item, idx) => `
                <article onclick="openProjectModal('danang', ${idx})" class="cursor-pointer group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-gold hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                        <img
                            src="${drivePrimaryUrl(item.id)}"
                            data-fallback="${driveFallbackUrl(item.id)}"
                            onerror="handleImgError(this, 'DU+AN+DA+NANG')"
                            alt="${item.title}"
                            loading="lazy"
                            class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-3 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-[12.5px] sm:text-[13.5px] font-bold text-brand-navy group-hover:text-brand-gold transition leading-snug break-words">
                                ${item.title}
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5">${item.location}</p>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        // =====================================================================
        // RENDER BÀI VIẾT TRANG CHỦ
        // =====================================================================
        function renderNews() {
            const container = document.getElementById('newsGrid');
            if (!container) return;

            container.innerHTML = newsArticles.map((art, idx) => `
                <article onclick="openNewsModal(${idx})" class="cursor-pointer group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-gold hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[16/10] overflow-hidden bg-slate-100">
                        <img
                            src="${drivePrimaryUrl(art.imgId)}"
                            data-fallback="${driveFallbackUrl(art.imgId)}"
                            onerror="handleImgError(this, 'TIN+TUC+QDANACONS')"
                            alt="${art.title}"
                            loading="lazy"
                            class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-slate-400 font-medium mb-1">${art.date}</div>
                            <h3 class="text-[12.5px] sm:text-sm font-bold text-brand-navy group-hover:text-brand-gold transition leading-snug break-words">
                                ${art.title}
                            </h3>
                            <p class="hidden sm:block text-xs text-slate-600 mt-2 leading-relaxed">
                                ${art.excerpt}
                            </p>
                        </div>
                        <div class="pt-2.5 text-[11.5px] font-semibold text-brand-gold">Đọc tiếp &rarr;</div>
                    </div>
                </article>
            `).join('');
        }

        // =====================================================================
        // MODAL CHI TIẾT CÔNG TRÌNH & BÀI VIẾT
        // =====================================================================
        function openProjectModal(group, index) {
            const item = group === 'construction' ? constructionProjects[index] : danangProjects[index];
            if (!item) return;

            const modal = document.getElementById('detailModal');
            const img = document.getElementById('modalImage');
            img.dataset.triedFallback = '';
            img.dataset.triedPlaceholder = '';
            img.dataset.fallback = driveFallbackUrl(item.id);
            img.onerror = function() { handleImgError(this, 'QDANACONS'); };
            img.src = drivePrimaryUrl(item.id);
            img.alt = item.title;

            document.getElementById('modalTitle').textContent = item.title;
            document.getElementById('modalSubtitle').textContent = item.categoryName || item.location || 'CÔNG TY TNHH XÂY DỰNG QDANACONS';
            document.getElementById('modalDesc').textContent = item.desc;

            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function openNewsModal(index) {
            const art = newsArticles[index];
            if (!art) return;

            const modal = document.getElementById('detailModal');
            const img = document.getElementById('modalImage');
            img.dataset.triedFallback = '';
            img.dataset.triedPlaceholder = '';
            img.dataset.fallback = driveFallbackUrl(art.imgId);
            img.onerror = function() { handleImgError(this, 'TIN+TUC'); };
            img.src = drivePrimaryUrl(art.imgId);
            img.alt = art.title;

            document.getElementById('modalTitle').textContent = art.title;
            document.getElementById('modalSubtitle').textContent = 'Cẩm nang xây dựng • ' + art.date;
            document.getElementById('modalDesc').textContent = art.content;

            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeDetailModal() {
            const modal = document.getElementById('detailModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        // =====================================================================
        // CHỌN NHANH GÓI BÁO GIÁ TỪ MENU / DANH SÁCH
        // =====================================================================
        function selectQuoteType(packageName) {
            const selectEl = document.getElementById('servicePackage');
            if (selectEl) {
                selectEl.value = packageName;
            }
            const nameInput = document.getElementById('customerName');
            if (nameInput) {
                setTimeout(() => nameInput.focus(), 350);
            }
        }

        // =====================================================================
        // SLIDER 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT CẢM ỨNG MOBILE
        // =====================================================================
        let currentSlide = 0;
        const totalSlides = 2;
        let autoSlideTimer = null;

        function goToSlide(index) {
            currentSlide = (index + totalSlides) % totalSlides;
            const track = document.getElementById('heroTrack');
            if (track) {
                track.style.transform = 'translateX(-' + (currentSlide * 50) + '%)';
            }
            document.querySelectorAll('.banner-dot').forEach((dot, idx) => {
                if (idx === currentSlide) {
                    dot.classList.remove('w-2.5', 'bg-white/50');
                    dot.classList.add('w-6', 'bg-brand-gold');
                } else {
                    dot.classList.remove('w-6', 'bg-brand-gold');
                    dot.classList.add('w-2.5', 'bg-white/50');
                }
            });
        }

        function startAutoSlide() {
            stopAutoSlide();
            autoSlideTimer = setInterval(() => {
                goToSlide(currentSlide + 1);
            }, 5000);
        }

        function stopAutoSlide() {
            if (autoSlideTimer) {
                clearInterval(autoSlideTimer);
                autoSlideTimer = null;
            }
        }

        // =====================================================================
        // KHỞI TẠO SỰ KIỆN KHI TRANG TẢI XONG
        // =====================================================================
        document.addEventListener('DOMContentLoaded', function() {
            renderConstructionProjects('all');
            renderDaNangProjects();
            renderNews();

            // Điều khiển Banner Slider
            const prevBtn = document.getElementById('prevBannerBtn');
            const nextBtn = document.getElementById('nextBannerBtn');
            const sliderEl = document.getElementById('heroSlider');

            if (prevBtn) prevBtn.addEventListener('click', () => { goToSlide(currentSlide - 1); startAutoSlide(); });
            if (nextBtn) nextBtn.addEventListener('click', () => { goToSlide(currentSlide + 1); startAutoSlide(); });

            document.querySelectorAll('.banner-dot').forEach(dot => {
                dot.addEventListener('click', () => {
                    goToSlide(parseInt(dot.dataset.slide, 10));
                    startAutoSlide();
                });
            });

            if (sliderEl) {
                sliderEl.addEventListener('mouseenter', stopAutoSlide);
                sliderEl.addEventListener('mouseleave', startAutoSlide);

                // Vuốt cảm ứng trái/phải trên điện thoại
                let touchStartX = 0;
                sliderEl.addEventListener('touchstart', (e) => {
                    touchStartX = e.changedTouches[0].screenX;
                    stopAutoSlide();
                }, { passive: true });
                sliderEl.addEventListener('touchend', (e) => {
                    const diff = e.changedTouches[0].screenX - touchStartX;
                    if (Math.abs(diff) > 40) {
                        goToSlide(diff < 0 ? currentSlide + 1 : currentSlide - 1);
                    }
                    startAutoSlide();
                }, { passive: true });
            }

            startAutoSlide();

            // Điều khiển Menu Mobile
            const mobileMenuBtn = document.getElementById('mobileMenuBtn');
            const closeMobileMenuBtn = document.getElementById('closeMobileMenuBtn');
            const mobileDrawer = document.getElementById('mobileDrawer');
            const mobileDrawerOverlay = document.getElementById('mobileDrawerOverlay');

            function openMobileMenu() {
                mobileDrawer.classList.remove('-translate-x-full');
                mobileDrawerOverlay.classList.remove('hidden');
            }
            function closeMobileMenu() {
                mobileDrawer.classList.add('-translate-x-full');
                mobileDrawerOverlay.classList.add('hidden');
            }

            if (mobileMenuBtn) mobileMenuBtn.addEventListener('click', openMobileMenu);
            if (closeMobileMenuBtn) closeMobileMenuBtn.addEventListener('click', closeMobileMenu);
            if (mobileDrawerOverlay) mobileDrawerOverlay.addEventListener('click', closeMobileMenu);
            document.querySelectorAll('.mobile-nav-link').forEach(link => {
                link.addEventListener('click', closeMobileMenu);
            });

            // Đóng modal khi bấm ra ngoài
            const detailModal = document.getElementById('detailModal');
            if (detailModal) {
                detailModal.addEventListener('click', function(e) {
                    if (e.target === detailModal) closeDetailModal();
                });
            }

            // Xử lý Form Báo Giá (dùng hộp thông báo nội tuyến, không dùng alert)
            const quoteForm = document.getElementById('quoteForm');
            if (quoteForm) {
                quoteForm.addEventListener('submit', function(e) {
                    e.preventDefault();
                    const name = document.getElementById('customerName').value.trim();
                    const phone = document.getElementById('customerPhone').value.trim();
                    const pkg = document.getElementById('servicePackage').value;
                    const feedback = document.getElementById('quoteFeedback');

                    if (!name || !phone) return;

                    feedback.textContent = 'Cảm ơn ' + name + '! QDANACONS đã tiếp nhận yêu cầu "' + pkg + '" qua số ' + phone + '. Kỹ sư tư vấn sẽ liên hệ bạn trong thời gian sớm nhất (Hotline: 0913.735.458).';
                    feedback.classList.remove('hidden');
                    quoteForm.reset();
                });
            }
        });
    </script>
</body>
</html>
