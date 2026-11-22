<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CÔNG TY TNHH THIẾT KẾ XÂY DỰNG AN VIỆT QUẢNG NAM | xaydunganviet.com</title>
  <meta name="description" content="CÔNG TY TNHH THIẾT KẾ XÂY DỰNG AN VIỆT QUẢNG NAM (MST: 4001226455) - Chuyên thiết kế kiến trúc, thi công phần thô, xây nhà trọn gói và hoàn thiện nội thất tại Đà Nẵng - Quảng Nam. Hotline: 0877.939.667." />

  <!-- Meta Thumbnail / Open Graph khi chia sẻ đường link website -->
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="xaydunganviet.com" />
  <meta property="og:url" content="https://xaydunganviet.com/" />
  <meta property="og:title" content="CÔNG TY TNHH THIẾT KẾ XÂY DỰNG AN VIỆT QUẢNG NAM | Xây Nhà Trọn Gói" />
  <meta property="og:description" content="Thiết kế kiến trúc - Thi công phần thô - Xây nhà trọn gói uy tín tại Đà Nẵng & Quảng Nam. Hotline: 0877.939.667." />
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1il9j6mH-XUfulXpD8vxeQWZWz_Ht0UfL=w1200" />
  <meta property="og:image:width" content="1200" />
  <meta property="og:image:height" content="630" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="CÔNG TY TNHH THIẾT KẾ XÂY DỰNG AN VIỆT QUẢNG NAM" />
  <meta name="twitter:description" content="Chuyên thiết kế & thi công xây dựng trọn gói tại Đà Nẵng - Quảng Nam. Hotline: 0877.939.667." />
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1il9j6mH-XUfulXpD8vxeQWZWz_Ht0UfL=w1200" />
  <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1il9j6mH-XUfulXpD8vxeQWZWz_Ht0UfL=w200" />

  <!-- Font Inter hiện đại, dễ đọc và chuẩn Flatsome -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Tailwind CSS CDN -->
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
              primary: '#0E355E',   /* Xanh dương đậm kiến trúc theo tông logo */
              dark: '#092340',      /* Xanh navy đậm cho footer & header hover */
              accent: '#D98218',    /* Vàng đồng xây dựng tạo điểm nhấn sang trọng */
              accentHover: '#BC6E10',
              soft: '#F4F7FB',      /* Nền xám xanh dịu mắt chuẩn Flatsome */
            }
          }
        }
      }
    };
  </script>

  <style>
    /* =====================================================================
       THIẾT LẬP HỆ THỐNG CHỐNG TRÀN VIỀN & BỐ CỤC 95% TRÊN MÁY TÍNH (FLATSOME)
       Bạn có thể chỉnh 2 biến màu bên dưới nếu muốn tinh chỉnh thêm theo sắc độ logo
    ===================================================================== */
    :root {
      --brand-primary: #0E355E;
      --brand-dark: #092340;
      --brand-accent: #D98218;
      --brand-soft: #F4F7FB;
    }

    *, *::before, *::after {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
      overflow-x: hidden;
      width: 100%;
      max-width: 100%;
    }

    body {
      font-family: 'Inter', sans-serif;
      color: #1F2937;
      background-color: #FFFFFF;
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      -webkit-font-smoothing: antialiased;
    }

    /* Chiều ngang giao diện: Mobile full gọn gàng, Máy tính đúng 95% màn hình */
    .av-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 14px;
      padding-right: 14px;
    }

    @media (min-width: 1024px) {
      .av-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Tiêu đề danh mục chuẩn Flatsome tinh gọn */
    .section-heading {
      position: relative;
      display: inline-block;
      padding-bottom: 10px;
    }
    .section-heading::after {
      content: "";
      position: absolute;
      left: 50%;
      bottom: 0;
      transform: translateX(-50%);
      width: 56px;
      height: 3px;
      background-color: var(--brand-accent);
      border-radius: 999px;
    }

    /* Dropdown Menu chuẩn Flatsome */
    .nav-item-has-dropdown {
      position: relative;
    }
    .nav-dropdown {
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
    }
    .nav-item-has-dropdown:hover .nav-dropdown,
    .nav-item-has-dropdown:focus-within .nav-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    /* Slider 2 Banner bằng nhau tuyệt đối, không cắt chữ */
    .hero-slider-wrapper {
      display: grid;
      grid-template-columns: 1fr;
      position: relative;
      width: 100%;
      overflow: hidden;
      background-color: var(--brand-dark);
    }
    .hero-slide {
      grid-area: 1 / 1 / 2 / 2;
      opacity: 0;
      visibility: hidden;
      transition: opacity 0.7s ease-in-out, visibility 0.7s ease-in-out;
      position: relative;
      display: flex;
      align-items: center;
      width: 100%;
      min-height: 290px;
    }
    @media (min-width: 640px) {
      .hero-slide {
        min-height: 380px;
      }
    }
    @media (min-width: 1024px) {
      .hero-slide {
        min-height: 470px;
      }
    }
    .hero-slide.active {
      opacity: 1;
      visibility: visible;
      z-index: 2;
    }

    /* Hiệu ứng rung nhẹ cho nút Hotline / Zalo / Facebook nổi */
    @keyframes avPulseRing {
      0% {
        box-shadow: 0 0 0 0 rgba(217, 130, 24, 0.5);
      }
      70% {
        box-shadow: 0 0 0 12px rgba(217, 130, 24, 0);
      }
      100% {
        box-shadow: 0 0 0 0 rgba(217, 130, 24, 0);
      }
    }
    .pulse-hotline {
      animation: avPulseRing 2.1s infinite;
    }

    /* Ẩn thanh cuộn phụ nhưng vẫn vuốt mượt cho thanh lọc danh mục trên mobile */
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }
  </style>
</head>

<body class="bg-white text-gray-800 antialiased">

  <!-- =======================================================================
       1. TOP BAR THÔNG TIN NHANH (CHUẨN FLATSOME - GỌN GÀNG, KHÔNG TRÀN VIỀN)
  ======================================================================== -->
  <div class="bg-brand-dark text-white/90 text-[11px] sm:text-xs border-b border-white/10">
    <div class="av-container py-2 flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <span class="font-medium">CÔNG TY TNHH THIẾT KẾ XÂY DỰNG AN VIỆT QUẢNG NAM</span>
        <span class="hidden md:inline text-white/40">|</span>
        <span class="hidden md:inline text-white/80">MST: 4001226455</span>
      </div>
      <div class="flex items-center gap-x-4">
        <span class="hidden sm:inline text-white/85">Thôn Hưng Mỹ, Xã Thăng An, TP Đà Nẵng</span>
        <a href="tel:0877939667" class="font-semibold text-amber-400 hover:text-amber-300 transition whitespace-nowrap">
          Hotline: 0877.939.667
        </a>
      </div>
    </div>
  </div>

  <!-- =======================================================================
       2. HEADER CHÍNH (LOGO NHỎ GỌN, MENU 1 HÀNG CHỮ NHỎ, KHÔNG CÓ NÚT GỌI NGAY)
  ======================================================================== -->
  <header class="sticky top-0 z-40 bg-white/95 backdrop-blur-md shadow-sm border-b border-gray-100 w-full">
    <div class="av-container py-2.5 flex items-center justify-between gap-3">
      <!-- Logo gọn nhỏ -->
      <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 min-w-0">
        <img
          src="https://lh3.googleusercontent.com/d/1il9j6mH-XUfulXpD8vxeQWZWz_Ht0UfL=w400"
          data-fallback="https://drive.google.com/thumbnail?id=1il9j6mH-XUfulXpD8vxeQWZWz_Ht0UfL&sz=w400"
          alt="Logo Công Ty TNHH Thiết Kế Xây Dựng An Việt Quảng Nam"
          referrerpolicy="no-referrer"
          onerror="handleDriveImageError(this, 'AN VIET')"
          class="h-10 sm:h-11 w-auto max-w-[125px] object-contain rounded"
        />
        <div class="leading-tight hidden xl:block">
          <div class="text-xs font-extrabold text-brand-primary tracking-tight uppercase">AN VIỆT QUẢNG NAM</div>
          <div class="text-[10px] font-medium text-gray-500">xaydunganviet.com</div>
        </div>
      </a>

      <!-- Thanh điều hướng Desktop: Chữ nhỏ gọn, viết liền 1 hàng, không xuống dòng tên danh mục -->
      <nav aria-label="Menu chính" class="hidden lg:flex items-center justify-end flex-wrap gap-x-3.5 xl:gap-x-5 gap-y-1.5">
        <a href="#trang-chu" class="text-[12px] xl:text-[13px] font-semibold uppercase text-brand-primary hover:text-brand-accent transition whitespace-nowrap py-1">
          Trang chủ
        </a>

        <a href="#gioi-thieu" class="text-[12px] xl:text-[13px] font-semibold uppercase text-gray-700 hover:text-brand-accent transition whitespace-nowrap py-1">
          Giới thiệu
        </a>

        <!-- Dropdown Công trình thực tế (theo mẫu tintruongthinh.com) -->
        <div class="nav-item-has-dropdown py-1">
          <a href="#cong-trinh-thuc-te" class="text-[12px] xl:text-[13px] font-semibold uppercase text-gray-700 hover:text-brand-accent transition whitespace-nowrap inline-flex items-center gap-1">
            Công trình thực tế
            <svg class="w-3 h-3 opacity-70" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" /></svg>
          </a>
          <div class="nav-dropdown absolute left-0 top-full pt-2 w-56 z-50">
            <div class="bg-white rounded-lg shadow-xl border border-gray-100 py-2 text-[13px]">
              <a href="#cong-trinh-thuc-te" onclick="filterProjects('nha-pho')" class="block px-4 py-2 text-gray-700 hover:bg-brand-soft hover:text-brand-primary whitespace-nowrap">Nhà phố hiện đại</a>
              <a href="#cong-trinh-thuc-te" onclick="filterProjects('biet-thu')" class="block px-4 py-2 text-gray-700 hover:bg-brand-soft hover:text-brand-primary whitespace-nowrap">Biệt thự &amp; Nhà vườn</a>
              <a href="#cong-trinh-thuc-te" onclick="filterProjects('can-ho')" class="block px-4 py-2 text-gray-700 hover:bg-brand-soft hover:text-brand-primary whitespace-nowrap">Khách sạn – Căn hộ – Phòng trọ</a>
              <a href="#cong-trinh-thuc-te" onclick="filterProjects('phan-tho')" class="block px-4 py-2 text-gray-700 hover:bg-brand-soft hover:text-brand-primary whitespace-nowrap">Thi công phần thô &amp; Kết cấu</a>
            </div>
          </div>
        </div>

        <!-- Dropdown Lĩnh vực hoạt động -->
        <div class="nav-item-has-dropdown py-1">
          <a href="#linh-vuc-hoat-dong" class="text-[12px] xl:text-[13px] font-semibold uppercase text-gray-700 hover:text-brand-accent transition whitespace-nowrap inline-flex items-center gap-1">
            Lĩnh vực hoạt động
            <svg class="w-3 h-3 opacity-70" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" /></svg>
          </a>
          <div class="nav-dropdown absolute left-0 top-full pt-2 w-56 z-50">
            <div class="bg-white rounded-lg shadow-xl border border-gray-100 py-2 text-[13px]">
              <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-gray-700 hover:bg-brand-soft hover:text-brand-primary whitespace-nowrap">Thiết kế Kiến trúc – Nội thất</a>
              <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-gray-700 hover:bg-brand-soft hover:text-brand-primary whitespace-nowrap">Thi công phần thô</a>
              <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-gray-700 hover:bg-brand-soft hover:text-brand-primary whitespace-nowrap">Thi công hoàn thiện</a>
              <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-gray-700 hover:bg-brand-soft hover:text-brand-primary whitespace-nowrap">Thi công trọn gói &amp; Nội thất</a>
            </div>
          </div>
        </div>

        <a href="#du-an-da-nang" class="text-[12px] xl:text-[13px] font-semibold uppercase text-gray-700 hover:text-brand-accent transition whitespace-nowrap py-1">
          Dự án Đà Nẵng
        </a>

        <!-- Dropdown Báo giá -->
        <div class="nav-item-has-dropdown py-1">
          <a href="#bao-gia" class="text-[12px] xl:text-[13px] font-semibold uppercase text-gray-700 hover:text-brand-accent transition whitespace-nowrap inline-flex items-center gap-1">
            Báo giá
            <svg class="w-3 h-3 opacity-70" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" /></svg>
          </a>
          <div class="nav-dropdown absolute left-0 top-full pt-2 w-56 z-50">
            <div class="bg-white rounded-lg shadow-xl border border-gray-100 py-2 text-[13px]">
              <a href="#bao-gia" class="block px-4 py-2 text-gray-700 hover:bg-brand-soft hover:text-brand-primary whitespace-nowrap">Báo giá thiết kế kiến trúc</a>
              <a href="#bao-gia" class="block px-4 py-2 text-gray-700 hover:bg-brand-soft hover:text-brand-primary whitespace-nowrap">Báo giá thi công phần thô</a>
              <a href="#bao-gia" class="block px-4 py-2 text-gray-700 hover:bg-brand-soft hover:text-brand-primary whitespace-nowrap">Báo giá thi công hoàn thiện</a>
              <a href="#bao-gia" class="block px-4 py-2 text-gray-700 hover:bg-brand-soft hover:text-brand-primary whitespace-nowrap">Báo giá xây nhà trọn gói</a>
            </div>
          </div>
        </div>

        <a href="#bai-viet" class="text-[12px] xl:text-[13px] font-semibold uppercase text-gray-700 hover:text-brand-accent transition whitespace-nowrap py-1">
          Tin tức
        </a>

        <a href="#lien-he" class="text-[12px] xl:text-[13px] font-semibold uppercase text-gray-700 hover:text-brand-accent transition whitespace-nowrap py-1">
          Liên hệ
        </a>
      </nav>

      <!-- Nút mở Menu Mobile (Không đặt nút gọi ngay trên header để tránh tràn viền) -->
      <button
        id="mobileMenuBtn"
        type="button"
        aria-label="Mở danh mục điều hướng"
        class="lg:hidden inline-flex items-center justify-center p-2.5 rounded-lg text-brand-primary hover:bg-brand-soft border border-gray-200 transition"
      >
        <svg id="menuIconOpen" class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
        </svg>
        <svg id="menuIconClose" class="w-5 h-5 hidden" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
        </svg>
      </button>
    </div>

    <!-- Menu thả xuống trên Mobile -->
    <div id="mobileMenu" class="hidden lg:hidden bg-white border-t border-gray-100 shadow-lg">
      <div class="av-container py-3 flex flex-col divide-y divide-gray-100 text-sm font-semibold">
        <a href="#trang-chu" class="mobile-nav-link py-2.5 text-brand-primary">Trang chủ</a>
        <a href="#gioi-thieu" class="mobile-nav-link py-2.5 text-gray-700">Giới thiệu</a>
        <a href="#linh-vuc-hoat-dong" class="mobile-nav-link py-2.5 text-gray-700">Lĩnh vực hoạt động</a>
        <a href="#cong-trinh-thuc-te" class="mobile-nav-link py-2.5 text-gray-700">Công trình thực tế</a>
        <a href="#du-an-da-nang" class="mobile-nav-link py-2.5 text-gray-700">Các dự án tại Đà Nẵng</a>
        <a href="#bao-gia" class="mobile-nav-link py-2.5 text-gray-700">Báo giá xây dựng</a>
        <a href="#bai-viet" class="mobile-nav-link py-2.5 text-gray-700">Tin tức &amp; Kiến thức</a>
        <a href="#doi-tac" class="mobile-nav-link py-2.5 text-gray-700">Đối tác vật tư</a>
        <a href="#lien-he" class="mobile-nav-link py-2.5 text-gray-700">Liên hệ &amp; Bản đồ</a>
      </div>
    </div>
  </header>

  <main id="trang-chu" class="w-full overflow-x-hidden">

    <!-- =======================================================================
         3. SLIDER 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (KÍCH THƯỚC BẰNG NHAU,
            CHỮ CÁCH XA VIỀN ẢNH, KHÔNG BỊ THIẾU CHỮ TRÊN MOBILE & DESKTOP)
    ======================================================================== -->
    <section aria-label="Banner nổi bật" class="w-full bg-brand-dark">
      <div id="heroSlider" class="hero-slider-wrapper">

        <!-- BANNER 1 -->
        <div class="hero-slide active">
          <img
            src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1600"
            data-fallback="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
            alt="Xây nhà trọn gói An Việt Quảng Nam - Đà Nẵng"
            referrerpolicy="no-referrer"
            onerror="handleDriveImageError(this, 'AN VIET QUANG NAM')"
            class="absolute inset-0 w-full h-full object-cover object-center"
          />
          <div class="absolute inset-0 bg-gradient-to-r from-[#081F3A]/90 via-[#0E355E]/78 to-[#081F3A]/55"></div>

          <!-- Vùng nội dung an toàn: Cách xa viền banner ở cả 4 phía -->
          <div class="relative z-10 av-container py-10 sm:py-14 lg:py-20">
            <div class="px-8 sm:px-14 lg:px-20 max-w-3xl">
              <p class="text-[11px] sm:text-xs lg:text-sm font-semibold uppercase tracking-widest text-amber-400 mb-2 sm:mb-3">
                AN VIỆT QUẢNG NAM – XÂY CHẤT LƯỢNG, DỰNG NIỀM TIN
              </p>
              <h1 class="text-lg sm:text-2xl lg:text-4xl font-extrabold text-white leading-snug sm:leading-tight mb-3 sm:mb-4">
                THIẾT KẾ &amp; XÂY NHÀ TRỌN GÓI CHUYÊN NGHIỆP TẠI ĐÀ NẴNG – QUẢNG NAM
              </h1>
              <p class="text-xs sm:text-sm lg:text-base text-white/90 leading-relaxed mb-5 sm:mb-7 max-w-2xl">
                Làm thật – Giá trị thật – Uy tín thật. Đồng hành cùng gia chủ từ bản vẽ kiến trúc, thi công phần thô chuẩn kỹ thuật đến hoàn thiện chìa khóa trao tay.
              </p>
              <div class="flex flex-wrap items-center gap-2.5 sm:gap-3.5">
                <a href="#form-bao-gia" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-bold shadow-md transition">
                  Nhận Báo Giá Miễn Phí
                </a>
                <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/35 text-xs sm:text-sm font-semibold transition">
                  Xem Công Trình Thực Tế
                </a>
              </div>
            </div>
          </div>
        </div>

        <!-- BANNER 2 (Cùng cấu trúc & kích thước 100% với Banner 1) -->
        <div class="hero-slide">
          <img
            src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1600"
            data-fallback="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600"
            alt="Thi công phần thô và hoàn thiện nội thất An Việt Quảng Nam"
            referrerpolicy="no-referrer"
            onerror="handleDriveImageError(this, 'THI CONG XAY DUNG')"
            class="absolute inset-0 w-full h-full object-cover object-center"
          />
          <div class="absolute inset-0 bg-gradient-to-r from-[#081F3A]/90 via-[#0E355E]/78 to-[#081F3A]/55"></div>

          <!-- Vùng nội dung an toàn: Cách xa viền banner ở cả 4 phía -->
          <div class="relative z-10 av-container py-10 sm:py-14 lg:py-20">
            <div class="px-8 sm:px-14 lg:px-20 max-w-3xl">
              <p class="text-[11px] sm:text-xs lg:text-sm font-semibold uppercase tracking-widest text-amber-400 mb-2 sm:mb-3">
                NHÀ THẦU TRỌN GÓI UY TÍN – MINH BẠCH CHI PHÍ
              </p>
              <h2 class="text-lg sm:text-2xl lg:text-4xl font-extrabold text-white leading-snug sm:leading-tight mb-3 sm:mb-4">
                VỮNG NỀN MÓNG – CHUẨN KẾT CẤU – BÀN GIAO ĐÚNG TIẾN ĐỘ CAM KẾT
              </h2>
              <p class="text-xs sm:text-sm lg:text-base text-white/90 leading-relaxed mb-5 sm:mb-7 max-w-2xl">
                Chuyên thi công nhà phố, biệt thự, căn hộ, khách sạn và cải tạo công trình. Vật tư đúng chuẩn, giám sát chặt chẽ từng hạng mục, bảo hành lâu dài.
              </p>
              <div class="flex flex-wrap items-center gap-2.5 sm:gap-3.5">
                <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-bold shadow-md transition">
                  Xem Dự Án Tại Đà Nẵng
                </a>
                <a href="tel:0877939667" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/35 text-xs sm:text-sm font-semibold transition">
                  Tư Vấn: 0877.939.667
                </a>
              </div>
            </div>
          </div>
        </div>

        <!-- Nút chuyển trái / phải gọn sát mép, không đè chữ -->
        <button
          id="prevSlideBtn"
          type="button"
          aria-label="Banner trước"
          class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition"
        >
          <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M15 19l-7-7 7-7" /></svg>
        </button>
        <button
          id="nextSlideBtn"
          type="button"
          aria-label="Banner tiếp theo"
          class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition"
        >
          <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M9 5l7 7-7 7" /></svg>
        </button>

        <!-- Chấm chỉ báo Slide -->
        <div class="absolute bottom-3 sm:bottom-4 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button type="button" data-slide-dot="0" aria-label="Chọn banner 1" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
          <button type="button" data-slide-dot="1" aria-label="Chọn banner 2" class="w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all"></button>
        </div>
      </div>
    </section>

    <!-- =======================================================================
         4. LĨNH VỰC HOẠT ĐỘNG / DỊCH VỤ TIÊU BIỂU (THEO MẪU TINTRUONGTHINH.COM)
            Chia 2 cột trên điện thoại, 4 cột trên máy tính, không nhãn dán
    ======================================================================== -->
    <section id="linh-vuc-hoat-dong" class="py-10 sm:py-14 bg-white">
      <div class="av-container">
        <div class="text-center mb-7 sm:mb-10">
          <h2 class="section-heading text-lg sm:text-xl lg:text-2xl font-extrabold uppercase text-brand-primary tracking-tight">
            Lĩnh Vực Hoạt Động
          </h2>
          <p class="mt-3 text-xs sm:text-sm text-gray-600 max-w-2xl mx-auto">
            Giải pháp thiết kế và xây dựng đồng bộ cho nhà phố, biệt thự, khách sạn, căn hộ và công trình dân dụng.
          </p>
        </div>

        <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
          <!-- Dịch vụ 1 -->
          <a href="#form-bao-gia" class="group bg-white rounded-xl border border-gray-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
              <img
                src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w700"
                data-fallback="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w700"
                alt="Thiết kế Kiến trúc và Nội thất"
                referrerpolicy="no-referrer"
                onerror="handleDriveImageError(this, 'THIET KE')"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              />
            </div>
            <div class="p-3 sm:p-4 text-center flex-1 flex flex-col justify-between">
              <h3 class="text-[13px] sm:text-sm lg:text-[15px] font-bold text-brand-primary group-hover:text-brand-accent transition leading-snug break-words">
                Thiết Kế Kiến Trúc – Nội Thất
              </h3>
              <p class="mt-1.5 text-[11px] sm:text-xs text-gray-600 leading-relaxed">
                Phối cảnh 3D trực quan, tối ưu công năng sử dụng và phong thủy từng không gian.
              </p>
            </div>
          </a>

          <!-- Dịch vụ 2 -->
          <a href="#form-bao-gia" class="group bg-white rounded-xl border border-gray-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
              <img
                src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w700"
                data-fallback="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w700"
                alt="Thi công phần thô chuẩn kỹ thuật"
                referrerpolicy="no-referrer"
                onerror="handleDriveImageError(this, 'PHAN THO')"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              />
            </div>
            <div class="p-3 sm:p-4 text-center flex-1 flex flex-col justify-between">
              <h3 class="text-[13px] sm:text-sm lg:text-[15px] font-bold text-brand-primary group-hover:text-brand-accent transition leading-snug break-words">
                Thi Công Phần Thô &amp; Kết Cấu
              </h3>
              <p class="mt-1.5 text-[11px] sm:text-xs text-gray-600 leading-relaxed">
                Triển khai móng, cột, dầm, sàn bê tông đúng bản vẽ kết cấu và kiểm soát cao độ kỹ lưỡng.
              </p>
            </div>
          </a>

          <!-- Dịch vụ 3 -->
          <a href="#form-bao-gia" class="group bg-white rounded-xl border border-gray-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
              <img
                src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w700"
                data-fallback="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w700"
                alt="Thi công hoàn thiện công trình"
                referrerpolicy="no-referrer"
                onerror="handleDriveImageError(this, 'HOAN THIEN')"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              />
            </div>
            <div class="p-3 sm:p-4 text-center flex-1 flex flex-col justify-between">
              <h3 class="text-[13px] sm:text-sm lg:text-[15px] font-bold text-brand-primary group-hover:text-brand-accent transition leading-snug break-words">
                Thi Công Hoàn Thiện &amp; Nội Thất
              </h3>
              <p class="mt-1.5 text-[11px] sm:text-xs text-gray-600 leading-relaxed">
                Ốp lát, sơn nước, điện nước âm tường, cửa nhôm kính và lắp đặt nội thất tinh tế.
              </p>
            </div>
          </a>

          <!-- Dịch vụ 4 -->
          <a href="#form-bao-gia" class="group bg-white rounded-xl border border-gray-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
              <img
                src="https://lh3.googleusercontent.com/d/1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz=w700"
                data-fallback="https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w700"
                alt="Xây nhà trọn gói chìa khóa trao tay"
                referrerpolicy="no-referrer"
                onerror="handleDriveImageError(this, 'TRON GOI')"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              />
            </div>
            <div class="p-3 sm:p-4 text-center flex-1 flex flex-col justify-between">
              <h3 class="text-[13px] sm:text-sm lg:text-[15px] font-bold text-brand-primary group-hover:text-brand-accent transition leading-snug break-words">
                Xây Nhà Trọn Gói – Cải Tạo Nhà
              </h3>
              <p class="mt-1.5 text-[11px] sm:text-xs text-gray-600 leading-relaxed">
                Quản lý trọn gói từ xin phép xây dựng, vật tư, nhân công đến bàn giao nhà hoàn chỉnh.
              </p>
            </div>
          </a>
        </div>
      </div>
    </section>

    <!-- =======================================================================
         5. GIỚI THIỆU CÔNG TY & THẾ MẠNH CỦA CHÚNG TÔI (THEO MẪU TINTRUONGTHINH)
    ======================================================================== -->
    <section id="gioi-thieu" class="py-10 sm:py-14 bg-brand-soft border-y border-gray-200/70">
      <div class="av-container">
        <!-- Phần Giới thiệu 2 cột Flatsome -->
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center mb-10 sm:mb-14">
          <div class="lg:col-span-6">
            <div class="rounded-xl overflow-hidden shadow-md border border-gray-200 bg-white">
              <img
                src="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_=w1000"
                data-fallback="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w1000"
                alt="Đội ngũ thi công Công ty TNHH Thiết Kế Xây Dựng An Việt Quảng Nam"
                referrerpolicy="no-referrer"
                onerror="handleDriveImageError(this, 'AN VIET QUANG NAM')"
                class="w-full aspect-[16/10] object-cover"
              />
            </div>
          </div>

          <div class="lg:col-span-6 space-y-3.5">
            <p class="text-xs font-bold uppercase tracking-wider text-brand-accent">
              Về Chúng Tôi – MST: 4001226455
            </p>
            <h2 class="text-lg sm:text-xl lg:text-2xl font-extrabold text-brand-primary leading-snug">
              CÔNG TY TNHH THIẾT KẾ XÂY DỰNG AN VIỆT QUẢNG NAM
            </h2>
            <p class="text-xs sm:text-sm text-gray-700 leading-relaxed">
              Hoạt động chuyên sâu trong lĩnh vực <strong>Thiết kế kiến trúc – Thi công phần thô – Xây nhà trọn gói – Hoàn thiện nội thất</strong> các công trình nhà phố, biệt thự, căn hộ cho thuê, khách sạn và cải tạo công trình tại khu vực <strong>Đà Nẵng – Quảng Nam</strong>.
            </p>
            <p class="text-xs sm:text-sm text-gray-700 leading-relaxed">
              Với phương châm <strong>“Làm thật – Giá trị thật – Uy tín thật”</strong>, mỗi mét vuông sàn được An Việt hoàn thiện đều đặt tâm huyết, kỹ thuật chuẩn mực và sự minh bạch lên hàng đầu. Chúng tôi cam kết kiến tạo tổ ấm vững chắc từ nền móng, bền đẹp theo thời gian và đúng tiến độ đã ký kết.
            </p>

            <div class="grid grid-cols-3 gap-3 pt-2">
              <div class="bg-white rounded-lg p-3 border border-gray-200 text-center">
                <div class="text-lg sm:text-xl font-extrabold text-brand-primary">100%</div>
                <div class="text-[11px] sm:text-xs text-gray-600 mt-0.5">Thi công đúng kỹ thuật</div>
              </div>
              <div class="bg-white rounded-lg p-3 border border-gray-200 text-center">
                <div class="text-lg sm:text-xl font-extrabold text-brand-accent">0đ</div>
                <div class="text-[11px] sm:text-xs text-gray-600 mt-0.5">Chi phí phát sinh ẩn</div>
              </div>
              <div class="bg-white rounded-lg p-3 border border-gray-200 text-center">
                <div class="text-lg sm:text-xl font-extrabold text-brand-primary">24/7</div>
                <div class="text-[11px] sm:text-xs text-gray-600 mt-0.5">Tư vấn &amp; hỗ trợ tận tâm</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Phần Thế mạnh 6 mục theo bố cục tintruongthinh.com -->
        <div class="text-center mb-7">
          <h3 class="section-heading text-base sm:text-lg lg:text-xl font-extrabold uppercase text-brand-primary">
            Thế Mạnh Của An Việt Quảng Nam
          </h3>
        </div>

        <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
          <div class="bg-white rounded-xl p-4 sm:p-5 border border-gray-200 shadow-sm">
            <div class="w-9 h-9 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center mb-3">
              <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0z" /></svg>
            </div>
            <h4 class="text-[13px] sm:text-sm font-bold text-brand-primary mb-1.5 leading-snug">Đội Ngũ Kỹ Sư &amp; Tổ Đội Lành Nghề</h4>
            <p class="text-[11px] sm:text-xs text-gray-600 leading-relaxed">Kiến trúc sư sáng tạo kết hợp cùng đội ngũ kỹ sư hiện trường và thợ xây dựng tay nghề cao.</p>
          </div>

          <div class="bg-white rounded-xl p-4 sm:p-5 border border-gray-200 shadow-sm">
            <div class="w-9 h-9 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center mb-3">
              <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
            </div>
            <h4 class="text-[13px] sm:text-sm font-bold text-brand-primary mb-1.5 leading-snug">Thi Công Bài Bản – Chuẩn Quy Trình</h4>
            <p class="text-[11px] sm:text-xs text-gray-600 leading-relaxed">Kiểm tra cao độ, độ phẳng, cốt thép và nghiệm thu chặt chẽ từng giai đoạn trước khi đổ bê tông.</p>
          </div>

          <div class="bg-white rounded-xl p-4 sm:p-5 border border-gray-200 shadow-sm">
            <div class="w-9 h-9 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center mb-3">
              <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
            </div>
            <h4 class="text-[13px] sm:text-sm font-bold text-brand-primary mb-1.5 leading-snug">Giám Sát Tiến Độ Chuẩn Xác</h4>
            <p class="text-[11px] sm:text-xs text-gray-600 leading-relaxed">Báo cáo tiến độ thường xuyên bằng hình ảnh thực tế giúp gia chủ dễ dàng theo dõi từ xa.</p>
          </div>

          <div class="bg-white rounded-xl p-4 sm:p-5 border border-gray-200 shadow-sm">
            <div class="w-9 h-9 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center mb-3">
              <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
            </div>
            <h4 class="text-[13px] sm:text-sm font-bold text-brand-primary mb-1.5 leading-snug">Minh Bạch Chi Phí &amp; Vật Tư</h4>
            <p class="text-[11px] sm:text-xs text-gray-600 leading-relaxed">Dự toán rõ ràng ngay từ đầu, sử dụng vật liệu chính hãng có nguồn gốc rõ ràng, giá hợp lý.</p>
          </div>

          <div class="bg-white rounded-xl p-4 sm:p-5 border border-gray-200 shadow-sm">
            <div class="w-9 h-9 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center mb-3">
              <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z" /></svg>
            </div>
            <h4 class="text-[13px] sm:text-sm font-bold text-brand-primary mb-1.5 leading-snug">Bảo Hành Công Trình Lâu Dài</h4>
            <p class="text-[11px] sm:text-xs text-gray-600 leading-relaxed">Chế độ hậu mãi rõ ràng, bảo hành kết cấu và hỗ trợ xử lý kịp thời sau khi bàn giao.</p>
          </div>

          <div class="bg-white rounded-xl p-4 sm:p-5 border border-gray-200 shadow-sm">
            <div class="w-9 h-9 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center mb-3">
              <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" /></svg>
            </div>
            <h4 class="text-[13px] sm:text-sm font-bold text-brand-primary mb-1.5 leading-snug">Tư Vấn Khảo Sát Miễn Phí 24/7</h4>
            <p class="text-[11px] sm:text-xs text-gray-600 leading-relaxed">Hỗ trợ khảo sát thực địa, tư vấn phương án thiết kế và lên dự toán sơ bộ hoàn toàn miễn phí.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- =======================================================================
         6. CÔNG TRÌNH THỰC TẾ THI CÔNG XÂY DỰNG (9 ẢNH THỰC TẾ GOOGLE DRIVE)
            Không nhãn dán, 2 cột trên điện thoại, tên công trình rõ đủ chữ
    ======================================================================== -->
    <section id="cong-trinh-thuc-te" class="py-10 sm:py-14 bg-white">
      <div class="av-container">
        <div class="text-center mb-6 sm:mb-8">
          <h2 class="section-heading text-lg sm:text-xl lg:text-2xl font-extrabold uppercase text-brand-primary tracking-tight">
            Công Trình Thực Tế Thi Công
          </h2>
          <p class="mt-3 text-xs sm:text-sm text-gray-600 max-w-2xl mx-auto">
            Hình ảnh thi công thực tế tại công trường do đội ngũ kỹ sư An Việt Quảng Nam trực tiếp triển khai và giám sát.
          </p>
        </div>

        <!-- Thanh lọc danh mục tinh gọn, không xuống dòng từng tên danh mục -->
        <div class="flex items-center justify-start sm:justify-center gap-2 overflow-x-auto no-scrollbar pb-2 mb-6">
          <button type="button" data-filter="all" onclick="filterProjects('all')" class="project-filter-btn active px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold whitespace-nowrap bg-brand-primary text-white transition">
            Tất cả
          </button>
          <button type="button" data-filter="phan-tho" onclick="filterProjects('phan-tho')" class="project-filter-btn px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold whitespace-nowrap bg-gray-100 text-gray-700 hover:bg-brand-soft hover:text-brand-primary transition">
            Thi công phần thô
          </button>
          <button type="button" data-filter="nha-pho" onclick="filterProjects('nha-pho')" class="project-filter-btn px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold whitespace-nowrap bg-gray-100 text-gray-700 hover:bg-brand-soft hover:text-brand-primary transition">
            Nhà phố trọn gói
          </button>
          <button type="button" data-filter="biet-thu" onclick="filterProjects('biet-thu')" class="project-filter-btn px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold whitespace-nowrap bg-gray-100 text-gray-700 hover:bg-brand-soft hover:text-brand-primary transition">
            Biệt thự – Nhà vườn
          </button>
          <button type="button" data-filter="can-ho" onclick="filterProjects('can-ho')" class="project-filter-btn px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold whitespace-nowrap bg-gray-100 text-gray-700 hover:bg-brand-soft hover:text-brand-primary transition">
            Khách sạn – Căn hộ
          </button>
        </div>

        <!-- Lưới 9 ảnh thực tế thi công: 2 cột trên điện thoại, 3 cột trên máy tính -->
        <div id="realProjectsGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
          <!-- Render tự động bằng JS để hỗ trợ lọc danh mục mượt mà và xem ảnh lớn -->
        </div>
      </div>
    </section>

    <!-- =======================================================================
         7. DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (10 ẢNH DỰ ÁN GOOGLE DRIVE)
            2 cột trên điện thoại, 5 cột trên máy tính (2 hàng đều đẹp)
    ======================================================================== -->
    <section id="du-an-da-nang" class="py-10 sm:py-14 bg-brand-soft border-y border-gray-200/70">
      <div class="av-container">
        <div class="text-center mb-7 sm:mb-9">
          <h2 class="section-heading text-lg sm:text-xl lg:text-2xl font-extrabold uppercase text-brand-primary tracking-tight">
            Các Dự Án Tiêu Biểu Tại Đà Nẵng
          </h2>
          <p class="mt-3 text-xs sm:text-sm text-gray-600 max-w-2xl mx-auto">
            Tuyển chọn các mẫu thiết kế và công trình xây dựng nhà phố, biệt thự, căn hộ do An Việt Quảng Nam thực hiện tại TP. Đà Nẵng.
          </p>
        </div>

        <!-- Lưới 10 ảnh dự án Đà Nẵng: 2 cột trên điện thoại, 5 cột trên máy tính -->
        <div id="daNangProjectsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
          <!-- Render tự động 10 dự án Đà Nẵng -->
        </div>
      </div>
    </section>

    <!-- =======================================================================
         8. BẢNG BÁO GIÁ THAM KHẢO (THEO DANH MỤC MẪU TINTRUONGTHINH.COM)
    ======================================================================== -->
    <section id="bao-gia" class="py-10 sm:py-14 bg-white">
      <div class="av-container">
        <div class="text-center mb-7 sm:mb-9">
          <h2 class="section-heading text-lg sm:text-xl lg:text-2xl font-extrabold uppercase text-brand-primary tracking-tight">
            Báo Giá Thiết Kế &amp; Thi Công Tham Khảo
          </h2>
          <p class="mt-3 text-xs sm:text-sm text-gray-600 max-w-2xl mx-auto">
            Đơn giá minh bạch, linh hoạt theo quy mô diện tích và chủng loại vật tư thực tế của từng công trình.
          </p>
        </div>

        <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
          <!-- Gói 1 -->
          <div class="rounded-xl border border-gray-200 bg-white p-4 sm:p-5 shadow-sm flex flex-col justify-between">
            <div>
              <h3 class="text-[13px] sm:text-sm font-bold text-brand-primary uppercase leading-snug">Thiết Kế Kiến Trúc</h3>
              <div class="mt-2.5 text-base sm:text-xl font-extrabold text-brand-accent">Từ 120.000đ<span class="text-xs font-medium text-gray-500">/m²</span></div>
              <ul class="mt-3 space-y-1.5 text-[11px] sm:text-xs text-gray-600">
                <li>• Hồ sơ kiến trúc &amp; kết cấu chi tiết</li>
                <li>• Phối cảnh 3D ngoại thất hiện đại</li>
                <li>• Bản vẽ điện nước M&amp;E đồng bộ</li>
                <li>• Miễn phí thiết kế khi ký trọn gói</li>
              </ul>
            </div>
            <a href="#form-bao-gia" class="mt-4 block text-center py-2 px-3 rounded-lg bg-brand-soft hover:bg-brand-primary text-brand-primary hover:text-white text-xs font-bold transition">
              Nhận Báo Giá
            </a>
          </div>

          <!-- Gói 2 -->
          <div class="rounded-xl border border-gray-200 bg-white p-4 sm:p-5 shadow-sm flex flex-col justify-between">
            <div>
              <h3 class="text-[13px] sm:text-sm font-bold text-brand-primary uppercase leading-snug">Thi Công Phần Thô</h3>
              <div class="mt-2.5 text-base sm:text-xl font-extrabold text-brand-accent">Từ 3.400.000đ<span class="text-xs font-medium text-gray-500">/m²</span></div>
              <ul class="mt-3 space-y-1.5 text-[11px] sm:text-xs text-gray-600">
                <li>• Vật tư phần thô chính hãng đạt chuẩn</li>
                <li>• Nhân công hoàn thiện toàn công trình</li>
                <li>• Kỹ sư giám sát trực tiếp hiện trường</li>
                <li>• Bảo hành kết cấu dài hạn</li>
              </ul>
            </div>
            <a href="#form-bao-gia" class="mt-4 block text-center py-2 px-3 rounded-lg bg-brand-soft hover:bg-brand-primary text-brand-primary hover:text-white text-xs font-bold transition">
              Nhận Báo Giá
            </a>
          </div>

          <!-- Gói 3 -->
          <div class="rounded-xl border border-gray-200 bg-white p-4 sm:p-5 shadow-sm flex flex-col justify-between">
            <div>
              <h3 class="text-[13px] sm:text-sm font-bold text-brand-primary uppercase leading-snug">Thi Công Hoàn Thiện</h3>
              <div class="mt-2.5 text-base sm:text-xl font-extrabold text-brand-accent">Từ 2.300.000đ<span class="text-xs font-medium text-gray-500">/m²</span></div>
              <ul class="mt-3 space-y-1.5 text-[11px] sm:text-xs text-gray-600">
                <li>• Sơn nước nội ngoại thất cao cấp</li>
                <li>• Ốp lát gạch, đá cầu thang &amp; mặt tiền</li>
                <li>• Lắp đặt cửa nhôm kính, thiết bị vệ sinh</li>
                <li>• Nghiệm thu sắc nét từng hạng mục</li>
              </ul>
            </div>
            <a href="#form-bao-gia" class="mt-4 block text-center py-2 px-3 rounded-lg bg-brand-soft hover:bg-brand-primary text-brand-primary hover:text-white text-xs font-bold transition">
              Nhận Báo Giá
            </a>
          </div>

          <!-- Gói 4 -->
          <div class="rounded-xl border-2 border-brand-primary bg-brand-primary text-white p-4 sm:p-5 shadow-md flex flex-col justify-between">
            <div>
              <h3 class="text-[13px] sm:text-sm font-bold uppercase leading-snug text-amber-300">Xây Nhà Trọn Gói</h3>
              <div class="mt-2.5 text-base sm:text-xl font-extrabold text-white">Từ 5.500.000đ<span class="text-xs font-medium text-white/75">/m²</span></div>
              <ul class="mt-3 space-y-1.5 text-[11px] sm:text-xs text-white/90">
                <li>• Chìa khóa trao tay từ A đến Z</li>
                <li>• Hỗ trợ hồ sơ xin phép xây dựng</li>
                <li>• Cam kết không phát sinh chi phí</li>
                <li>• Bàn giao sạch sẽ đúng tiến độ</li>
              </ul>
            </div>
            <a href="#form-bao-gia" class="mt-4 block text-center py-2 px-3 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-xs font-bold transition">
              Đăng Ký Dự Toán
            </a>
          </div>
        </div>
      </div>
    </section>

    <!-- =======================================================================
         9. FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ (THEO MẪU TINTRUONGTHINH)
    ======================================================================== -->
    <section id="form-bao-gia" class="py-10 sm:py-14 bg-brand-primary text-white">
      <div class="av-container">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
          <!-- Cột thông tin tư vấn -->
          <div class="lg:col-span-5 space-y-3.5">
            <p class="text-xs font-bold uppercase tracking-widest text-amber-400">Miễn Phí Tư Vấn &amp; Khảo Sát</p>
            <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold leading-tight">
              Gửi Yêu Cầu Báo Giá Xây Dựng Nhanh Chóng
            </h2>
            <p class="text-xs sm:text-sm text-white/85 leading-relaxed">
              Để lại thông tin công trình của quý khách, đội ngũ kỹ sư Công ty TNHH Thiết Kế Xây Dựng An Việt Quảng Nam sẽ liên hệ tư vấn phương án tối ưu và gửi bảng dự toán chi tiết trong ngày.
            </p>
            <div class="pt-2 space-y-2 text-xs sm:text-sm text-white/90">
              <div class="flex items-start gap-2.5">
                <span class="text-amber-400 font-bold">✓</span>
                <span>Địa chỉ: Thôn Hưng Mỹ, Xã Thăng An, TP Đà Nẵng</span>
              </div>
              <div class="flex items-start gap-2.5">
                <span class="text-amber-400 font-bold">✓</span>
                <span>Hotline / Zalo: <a href="tel:0877939667" class="font-bold text-amber-300 hover:underline">0877.939.667</a></span>
              </div>
              <div class="flex items-start gap-2.5">
                <span class="text-amber-400 font-bold">✓</span>
                <span>Phục vụ: Đà Nẵng, Quảng Nam và các khu vực lân cận</span>
              </div>
            </div>
          </div>

          <!-- Cột Form điền thông tin -->
          <div class="lg:col-span-7">
            <form id="quoteForm" class="bg-white text-gray-800 rounded-xl p-5 sm:p-7 shadow-xl space-y-4">
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <div>
                  <label for="customerName" class="block text-xs font-semibold text-gray-700 mb-1">Họ và tên *</label>
                  <input id="customerName" name="customerName" type="text" required placeholder="Nhập họ tên của quý khách" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-brand-primary focus:border-brand-primary" />
                </div>
                <div>
                  <label for="customerPhone" class="block text-xs font-semibold text-gray-700 mb-1">Số điện thoại / Zalo *</label>
                  <input id="customerPhone" name="customerPhone" type="tel" required placeholder="Ví dụ: 0877.939.667" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-brand-primary focus:border-brand-primary" />
                </div>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <div>
                  <label for="projectType" class="block text-xs font-semibold text-gray-700 mb-1">Loại công trình</label>
                  <select id="projectType" name="projectType" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-gray-300 bg-white focus:outline-none focus:ring-2 focus:ring-brand-primary">
                    <option value="Nhà phố">Nhà phố</option>
                    <option value="Biệt thự">Biệt thự</option>
                    <option value="Khách sạn - Căn hộ - Phòng trọ">Khách sạn – Căn hộ – Phòng trọ</option>
                    <option value="Văn phòng">Văn phòng</option>
                    <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                    <option value="Thi công nội thất">Thi công nội thất</option>
                  </select>
                </div>
                <div>
                  <label for="budgetRange" class="block text-xs font-semibold text-gray-700 mb-1">Mức đầu tư dự kiến</label>
                  <select id="budgetRange" name="budgetRange" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-gray-300 bg-white focus:outline-none focus:ring-2 focus:ring-brand-primary">
                    <option value="Chưa xác định">Chưa xác định</option>
                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                    <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                    <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                    <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                  </select>
                </div>
              </div>

              <div>
                <label for="projectNote" class="block text-xs font-semibold text-gray-700 mb-1">Diện tích &amp; Yêu cầu chi tiết</label>
                <textarea id="projectNote" name="projectNote" rows="3" placeholder="Ví dụ: Đất 5x20m tại Hòa Xuân, dự kiến xây nhà phố 3 tầng trọn gói..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-brand-primary"></textarea>
              </div>

              <!-- Thông báo phản hồi form (Không dùng alert) -->
              <div id="quoteFeedback" class="hidden rounded-lg p-3.5 text-xs sm:text-sm font-medium"></div>

              <div class="flex flex-wrap items-center justify-between gap-3 pt-1">
                <button type="submit" class="w-full sm:w-auto px-6 py-3 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-sm font-bold shadow transition">
                  Gửi Yêu Cầu Báo Giá Ngay
                </button>
                <a href="https://zalo.me/0877939667" target="_blank" rel="noopener noreferrer" class="w-full sm:w-auto text-center px-5 py-3 rounded-lg border border-brand-primary text-brand-primary hover:bg-brand-soft text-sm font-semibold transition">
                  Nhắn Zalo 0877.939.667
                </a>
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>

    <!-- =======================================================================
         10. DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ
             2 cột trên điện thoại, 4 cột trên máy tính
    ======================================================================== -->
    <section id="bai-viet" class="py-10 sm:py-14 bg-white">
      <div class="av-container">
        <div class="text-center mb-7 sm:mb-9">
          <h2 class="section-heading text-lg sm:text-xl lg:text-2xl font-extrabold uppercase text-brand-primary tracking-tight">
            Tin Tức &amp; Kinh Nghiệm Xây Dựng
          </h2>
          <p class="mt-3 text-xs sm:text-sm text-gray-600 max-w-2xl mx-auto">
            Chia sẻ kiến thức kỹ thuật thi công, nhật ký công trình và kinh nghiệm chuẩn bị xây nhà tiết kiệm, bền vững.
          </p>
        </div>

        <div id="articlesGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
          <!-- Render tự động các bài viết, click mở hộp thoại đọc chi tiết -->
        </div>
      </div>
    </section>

    <!-- =======================================================================
         11. DANH MỤC CÁC ĐỐI TÁC CUNG ỨNG VẬT TƯ & THIẾT BỊ XÂY DỰNG
    ======================================================================== -->
    <section id="doi-tac" class="py-10 sm:py-12 bg-brand-soft border-t border-gray-200/70">
      <div class="av-container">
        <div class="text-center mb-7">
          <h2 class="section-heading text-lg sm:text-xl lg:text-2xl font-extrabold uppercase text-brand-primary tracking-tight">
            Đối Tác Vật Tư &amp; Đồng Hành
          </h2>
          <p class="mt-3 text-xs sm:text-sm text-gray-600 max-w-2xl mx-auto">
            An Việt Quảng Nam cam kết sử dụng vật liệu xây dựng chính hãng từ những thương hiệu hàng đầu tại Việt Nam.
          </p>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3">
          <div class="bg-white rounded-xl border border-gray-200 p-3.5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-primary transition">
            <span class="text-sm font-extrabold text-brand-primary tracking-tight">HÒA PHÁT</span>
            <span class="text-[10px] text-gray-500 mt-0.5">Thép xây dựng</span>
          </div>
          <div class="bg-white rounded-xl border border-gray-200 p-3.5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-primary transition">
            <span class="text-sm font-extrabold text-emerald-700 tracking-tight">SÔNG GIANH</span>
            <span class="text-[10px] text-gray-500 mt-0.5">Xi măng cao cấp</span>
          </div>
          <div class="bg-white rounded-xl border border-gray-200 p-3.5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-primary transition">
            <span class="text-sm font-extrabold text-blue-700 tracking-tight">DULUX</span>
            <span class="text-[10px] text-gray-500 mt-0.5">Sơn trang trí</span>
          </div>
          <div class="bg-white rounded-xl border border-gray-200 p-3.5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-primary transition">
            <span class="text-sm font-extrabold text-amber-600 tracking-tight">JOTUN</span>
            <span class="text-[10px] text-gray-500 mt-0.5">Sơn chống thấm</span>
          </div>
          <div class="bg-white rounded-xl border border-gray-200 p-3.5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-primary transition">
            <span class="text-sm font-extrabold text-sky-700 tracking-tight">BÌNH MINH</span>
            <span class="text-[10px] text-gray-500 mt-0.5">Ống nhựa cấp thoát</span>
          </div>
          <div class="bg-white rounded-xl border border-gray-200 p-3.5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-primary transition">
            <span class="text-sm font-extrabold text-indigo-800 tracking-tight">PANASONIC</span>
            <span class="text-[10px] text-gray-500 mt-0.5">Thiết bị điện</span>
          </div>
          <div class="bg-white rounded-xl border border-gray-200 p-3.5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-primary transition">
            <span class="text-sm font-extrabold text-red-700 tracking-tight">ĐỒNG TÂM</span>
            <span class="text-[10px] text-gray-500 mt-0.5">Gạch ốp lát</span>
          </div>
          <div class="bg-white rounded-xl border border-gray-200 p-3.5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-primary transition">
            <span class="text-sm font-extrabold text-cyan-800 tracking-tight">INAX</span>
            <span class="text-[10px] text-gray-500 mt-0.5">Thiết bị vệ sinh</span>
          </div>
        </div>
      </div>
    </section>

    <!-- =======================================================================
         12. KẾT NỐI FANPAGE & BẢN ĐỒ GOOGLE MAP NGAY TRÊN TRANG CHỦ
    ======================================================================== -->
    <section id="lien-he" class="py-10 sm:py-14 bg-white border-t border-gray-200/70">
      <div class="av-container">
        <div class="text-center mb-7 sm:mb-9">
          <h2 class="section-heading text-lg sm:text-xl lg:text-2xl font-extrabold uppercase text-brand-primary tracking-tight">
            Fanpage &amp; Bản Đồ Chỉ Đường
          </h2>
          <p class="mt-3 text-xs sm:text-sm text-gray-600 max-w-2xl mx-auto">
            Theo dõi nhật ký thi công mỗi ngày trên Fanpage chính thức hoặc ghé trực tiếp văn phòng Công ty TNHH Thiết Kế Xây Dựng An Việt Quảng Nam.
          </p>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 sm:gap-6 items-stretch">
          <!-- Cột Fanpage chính thức trên trang chủ -->
          <div class="lg:col-span-5 bg-brand-soft rounded-xl border border-gray-200 p-4 sm:p-5 flex flex-col justify-between">
            <div>
              <div class="flex items-center gap-3 pb-3.5 border-b border-gray-200">
                <img
                  src="https://lh3.googleusercontent.com/d/1il9j6mH-XUfulXpD8vxeQWZWz_Ht0UfL=w200"
                  data-fallback="https://drive.google.com/thumbnail?id=1il9j6mH-XUfulXpD8vxeQWZWz_Ht0UfL&sz=w200"
                  alt="Logo Fanpage An Việt Quảng Nam"
                  referrerpolicy="no-referrer"
                  onerror="handleDriveImageError(this, 'AV')"
                  class="w-12 h-12 rounded-lg object-contain bg-white border border-gray-200 p-1 shrink-0"
                />
                <div class="min-w-0">
                  <h3 class="text-sm font-bold text-brand-primary leading-snug break-words">
                    Xây Nhà Trọn Gói - An Việt Quảng Nam Construction
                  </h3>
                  <p class="text-xs text-gray-600 mt-0.5">facebook.com/nhathautrongoi.anviet</p>
                </div>
              </div>

              <!-- Khung nhúng Fanpage Facebook -->
              <div class="mt-4 w-full overflow-hidden rounded-lg bg-white border border-gray-200">
                <iframe
                  title="Fanpage Xây Nhà Trọn Gói - An Việt Quảng Nam Construction"
                  src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fnhathautrongoi.anviet%2F&tabs=timeline&width=500&height=300&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
                  width="100%"
                  height="300"
                  style="border:none; overflow:hidden; display:block; width:100%;"
                  scrolling="no"
                  frameborder="0"
                  allowfullscreen="true"
                  allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                ></iframe>
              </div>
            </div>

            <div class="mt-4 flex flex-wrap items-center justify-between gap-2">
              <span class="text-xs text-gray-600">Cập nhật hình ảnh công trình thực tế hằng ngày</span>
              <a
                href="https://www.facebook.com/nhathautrongoi.anviet/"
                target="_blank"
                rel="noopener noreferrer"
                class="inline-flex items-center gap-1.5 px-4 py-2 rounded-lg bg-[#1877F2] hover:bg-[#1465CC] text-white text-xs font-bold transition"
              >
                Truy Cập Fanpage
              </a>
            </div>
          </div>

          <!-- Cột Bản đồ Google Map trên trang chủ -->
          <div class="lg:col-span-7 bg-brand-soft rounded-xl border border-gray-200 p-4 sm:p-5 flex flex-col justify-between">
            <div>
              <div class="flex flex-wrap items-center justify-between gap-2 pb-3.5 border-b border-gray-200">
                <div>
                  <h3 class="text-sm font-bold text-brand-primary">Trụ Sở Công Ty Trên Google Maps</h3>
                  <p class="text-xs text-gray-600 mt-0.5">Thôn Hưng Mỹ, Xã Thăng An, TP Đà Nẵng</p>
                </div>
                <a
                  href="https://www.google.com/maps/place//data=!4m2!3m1!19sChIJF1QsC3nhaTER9bdeeoQWnq0"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="inline-flex items-center gap-1.5 px-3.5 py-2 rounded-lg bg-brand-primary hover:bg-brand-dark text-white text-xs font-bold transition"
                >
                  Mở Chỉ Đường
                </a>
              </div>

              <!-- Khung nhúng Google Map trực tiếp -->
              <div class="mt-4 w-full h-[300px] sm:h-[320px] rounded-lg overflow-hidden border border-gray-200 bg-white">
                <iframe
                  title="Bản đồ Công Ty TNHH Thiết Kế Xây Dựng An Việt Quảng Nam"
                  src="https://maps.google.com/maps?q=C%C3%94NG%20TY%20TNHH%20THI%E1%BA%BET%20K%E1%BA%BE%20X%C3%82Y%20D%E1%BB%B0NG%20AN%20VI%E1%BB%86T%20QU%E1%BA%A2NG%20NAM%20Th%C3%B4n%20H%C6%B0ng%20M%E1%BB%B9%20Th%C4%83ng%20An%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed"
                  width="100%"
                  height="100%"
                  style="border:0; display:block;"
                  allowfullscreen=""
                  loading="lazy"
                  referrerpolicy="no-referrer-when-downgrade"
                ></iframe>
              </div>
            </div>

            <div class="mt-4 flex flex-wrap items-center justify-between gap-2 text-xs text-gray-700">
              <span><strong>Hotline / Zalo:</strong> 0877.939.667</span>
              <span><strong>Website:</strong> xaydunganviet.com</span>
            </div>
          </div>
        </div>
      </div>
    </section>

  </main>

  <!-- =======================================================================
       13. FOOTER CHUYÊN NGHIỆP (THEO BỐ CỤC FLATSOME TINTRUONGTHINH.COM)
  ======================================================================== -->
  <footer class="bg-brand-dark text-white/85 pt-10 pb-6 border-t-4 border-brand-accent">
    <div class="av-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-12 gap-7 pb-8 border-b border-white/10">
        <!-- Cột 1: Thông tin doanh nghiệp -->
        <div class="lg:col-span-5 space-y-3">
          <div class="flex items-center gap-3">
            <img
              src="https://lh3.googleusercontent.com/d/1il9j6mH-XUfulXpD8vxeQWZWz_Ht0UfL=w300"
              data-fallback="https://drive.google.com/thumbnail?id=1il9j6mH-XUfulXpD8vxeQWZWz_Ht0UfL&sz=w300"
              alt="Logo An Việt Quảng Nam"
              referrerpolicy="no-referrer"
              onerror="handleDriveImageError(this, 'AN VIET')"
              class="h-11 w-auto bg-white rounded-md p-1 object-contain"
            />
            <div>
              <div class="text-sm font-extrabold text-white uppercase leading-snug">CÔNG TY TNHH THIẾT KẾ XÂY DỰNG AN VIỆT QUẢNG NAM</div>
              <div class="text-xs text-amber-400 font-medium">Xây Chất Lượng – Dựng Niềm Tin</div>
            </div>
          </div>
          <ul class="space-y-1.5 text-xs sm:text-[13px] text-white/80 leading-relaxed">
            <li><strong class="text-white">Mã số thuế:</strong> 4001226455</li>
            <li><strong class="text-white">Địa chỉ:</strong> Thôn Hưng Mỹ, Xã Thăng An, TP Đà Nẵng</li>
            <li><strong class="text-white">Hotline / Zalo:</strong> <a href="tel:0877939667" class="text-amber-300 font-semibold hover:underline">0877.939.667</a></li>
            <li><strong class="text-white">Website:</strong> <a href="https://xaydunganviet.com" class="hover:text-white underline">xaydunganviet.com</a></li>
            <li><strong class="text-white">Fanpage:</strong> <a href="https://www.facebook.com/nhathautrongoi.anviet/" target="_blank" rel="noopener noreferrer" class="hover:text-white underline">facebook.com/nhathautrongoi.anviet</a></li>
          </ul>
        </div>

        <!-- Cột 2: Lĩnh vực hoạt động -->
        <div class="lg:col-span-3 space-y-2.5">
          <h3 class="text-xs sm:text-sm font-bold uppercase text-white tracking-wide">Lĩnh Vực Hoạt Động</h3>
          <ul class="space-y-2 text-xs sm:text-[13px] text-white/75">
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-300 transition">Thiết kế Kiến trúc – Nội thất</a></li>
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-300 transition">Thi công phần thô chuẩn kỹ thuật</a></li>
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-300 transition">Thi công hoàn thiện công trình</a></li>
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-300 transition">Xây nhà trọn gói chìa khóa trao tay</a></li>
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-300 transition">Cải tạo, sửa chữa nhà ở trọn gói</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục nhanh -->
        <div class="lg:col-span-4 space-y-2.5">
          <h3 class="text-xs sm:text-sm font-bold uppercase text-white tracking-wide">Danh Mục Trang Chủ</h3>
          <div class="grid grid-cols-2 gap-2 text-xs sm:text-[13px] text-white/75">
            <a href="#gioi-thieu" class="hover:text-amber-300 transition">Giới thiệu công ty</a>
            <a href="#cong-trinh-thuc-te" class="hover:text-amber-300 transition">Công trình thực tế</a>
            <a href="#du-an-da-nang" class="hover:text-amber-300 transition">Dự án tại Đà Nẵng</a>
            <a href="#bao-gia" class="hover:text-amber-300 transition">Báo giá xây dựng</a>
            <a href="#form-bao-gia" class="hover:text-amber-300 transition">Gửi yêu cầu báo giá</a>
            <a href="#bai-viet" class="hover:text-amber-300 transition">Tin tức xây dựng</a>
            <a href="#doi-tac" class="hover:text-amber-300 transition">Đối tác vật tư</a>
            <a href="#lien-he" class="hover:text-amber-300 transition">Bản đồ &amp; Fanpage</a>
          </div>
        </div>
      </div>

      <div class="pt-5 text-center text-[11px] sm:text-xs text-white/60">
        Copyright 2026 © CÔNG TY TNHH THIẾT KẾ XÂY DỰNG AN VIỆT QUẢNG NAM – xaydunganviet.com
      </div>
    </div>
  </footer>

  <!-- =======================================================================
       14. CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
           Tương thích mượt mà trên cả máy tính và điện thoại, không tràn viền
  ======================================================================== -->
  <div class="fixed right-3 sm:right-5 bottom-4 sm:bottom-6 z-50 flex flex-col items-end gap-2.5">
    <!-- Nút Facebook -->
    <a
      href="https://www.facebook.com/nhathautrongoi.anviet/"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Liên hệ Facebook An Việt Quảng Nam"
      class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1465CC] text-white rounded-full shadow-lg p-2.5 sm:px-4 sm:py-2.5 transition"
    >
      <svg class="w-5 h-5 shrink-0" fill="currentColor" viewBox="0 0 24 24">
        <path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z" />
      </svg>
      <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Facebook</span>
    </a>

    <!-- Nút Zalo -->
    <a
      href="https://zalo.me/0877939667"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Nhắn Zalo 0877939667"
      class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white rounded-full shadow-lg p-2.5 sm:px-4 sm:py-2.5 transition"
    >
      <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Chat Zalo</span>
    </a>

    <!-- Nút Hotline nổi bật -->
    <a
      href="tel:0877939667"
      aria-label="Gọi Hotline 0877.939.667"
      class="pulse-hotline group flex items-center gap-2 bg-brand-accent hover:bg-brand-accentHover text-white rounded-full shadow-xl p-2.5 sm:px-4 sm:py-2.5 transition"
    >
      <svg class="w-5 h-5 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
      </svg>
      <span class="hidden sm:inline text-xs font-extrabold whitespace-nowrap">0877.939.667</span>
    </a>
  </div>

  <!-- =======================================================================
       15. MODAL XEM ẢNH CÔNG TRÌNH & ĐỌC CHI TIẾT BÀI VIẾT
  ======================================================================== -->
  <div id="previewModal" class="hidden fixed inset-0 z-50 bg-black/75 backdrop-blur-sm flex items-center justify-center p-4">
    <div class="bg-white rounded-2xl max-w-3xl w-full max-h-[90vh] overflow-y-auto shadow-2xl">
      <div class="flex items-center justify-between gap-3 px-5 py-3.5 border-b border-gray-100 sticky top-0 bg-white">
        <h3 id="modalTitle" class="text-sm sm:text-base font-bold text-brand-primary leading-snug"></h3>
        <button id="closeModalBtn" type="button" aria-label="Đóng cửa sổ" class="p-1.5 rounded-lg text-gray-500 hover:bg-gray-100 hover:text-gray-800 transition">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" /></svg>
        </button>
      </div>
      <div class="p-5 space-y-4">
        <img id="modalImage" src="" alt="" referrerpolicy="no-referrer" class="w-full max-h-[60vh] object-contain rounded-xl bg-gray-100" />
        <div id="modalBody" class="text-xs sm:text-sm text-gray-700 leading-relaxed space-y-2.5"></div>
      </div>
    </div>
  </div>

  <!-- =======================================================================
       16. JAVASCRIPT ĐIỀU KHIỂN DỮ LIỆU CÔNG TRÌNH, SLIDER, LỌC & FORM
  ======================================================================== -->
  <script>
    /**
     * Hàm xử lý fallback thông minh khi tải ảnh từ Google Drive:
     * Bước 1: Thử đường dẫn thumbnail Google Drive nếu đường dẫn lh3 lỗi.
     * Bước 2: Hiển thị ảnh placeholder gọn đẹp để giao diện không bao giờ vỡ.
     */
    function handleDriveImageError(imgEl, labelText) {
      try {
        const fallbackUrl = imgEl.getAttribute('data-fallback');
        if (fallbackUrl && !imgEl.dataset.triedFallback) {
          imgEl.dataset.triedFallback = 'true';
          imgEl.src = fallbackUrl;
          return;
        }
        if (!imgEl.dataset.triedPlaceholder) {
          imgEl.dataset.triedPlaceholder = 'true';
          const text = encodeURIComponent(labelText || 'An Viet Quang Nam');
          imgEl.src = `https://placehold.co/800x600/0E355E/FFFFFF?text=${text}`;
        }
      } catch (e) {
        console.error('Lỗi tải ảnh dự phòng:', e);
      }
    }

    /**
     * Hàm tạo cặp URL chính + URL dự phòng từ Google Drive File ID
     */
    function driveImg(id, size = 1000) {
      return {
        primary: `https://lh3.googleusercontent.com/d/${id}=w${size}`,
        fallback: `https://drive.google.com/thumbnail?id=${id}&sz=w${size}`
      };
    }

    /**
     * Dữ liệu 9 hình ảnh thực tế thi công xây dựng của Công ty An Việt Quảng Nam
     * (Khớp 100% với 9 link Google Drive người dùng cung cấp & nội dung Fanpage)
     */
    const realProjects = [
      {
        id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        category: 'nha-pho',
        title: 'Thi Công Nhà Phố 3 Tầng Trọn Gói – Hòa Xuân, Đà Nẵng',
        desc: 'Công trình nhà ở trọn gói quy mô 3 tầng khởi công và triển khai đồng bộ phần thô đến hoàn thiện bởi đội ngũ kỹ sư An Việt Quảng Nam.'
      },
      {
        id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        category: 'phan-tho',
        title: 'Hoàn Thành Đổ Bê Tông Sàn 1 – Thi Công Phần Thô Chuẩn Kỹ Thuật',
        desc: 'Công tác kiểm tra cao độ, độ phẳng, cốt thép sàn và tổ chức đổ bê tông sàn 1 bảo đảm an toàn, chắc chắn và đúng tiến độ cam kết.'
      },
      {
        id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        category: 'nha-pho',
        title: 'Thi Công Hoàn Thiện Mặt Tiền & Nội Thất Nhà Phố Hiện Đại',
        desc: 'Hạng mục hoàn thiện tường, ốp lát, sơn nước và lắp đặt hệ thống kỹ thuật sắc nét, mang đến không gian sống thẩm mỹ cho gia chủ.'
      },
      {
        id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        category: 'phan-tho',
        title: 'Thi Công Nền Móng Vững Chắc – Công Trình Tại Hưng Mỹ, Thăng An',
        desc: 'Triển khai khởi công khai móng và hoàn thiện toàn bộ kết cấu móng băng đạt chuẩn kỹ thuật, đặt nền tảng bền vững lâu dài cho ngôi nhà.'
      },
      {
        id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        category: 'phan-tho',
        title: 'Cất Nóc & Hoàn Thiện Bê Tông Mái Công Trình Nhà Ở Trọn Gói',
        desc: 'Hoàn thành hạng mục đổ bê tông mái cất nóc đúng tiến độ, tiếp tục đẩy nhanh giai đoạn hoàn thiện để kịp bàn giao nhà mới.'
      },
      {
        id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
        category: 'phan-tho',
        title: 'Thi Công Bê Tông Trụ Cột & Kết Cấu Khung Chịu Lực',
        desc: 'Kiểm soát chặt chẽ vật liệu thép, cốp pha và mác bê tông cho toàn bộ hệ trụ cột, chuẩn bị sẵn sàng cho các tầng sàn tiếp theo.'
      },
      {
        id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        category: 'biet-thu',
        title: 'Xây Dựng Biệt Thự Nhà Vườn Trọn Gói – Khu Vực Quảng Nam',
        desc: 'Thiết kế và thi công biệt thự sân vườn thông thoáng, tối ưu ánh sáng tự nhiên và công năng sinh hoạt cho gia đình đa thế hệ.'
      },
      {
        id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        category: 'can-ho',
        title: 'Thi Công Căn Hộ Cho Thuê & Nhà Ở Kết Hợp Kinh Doanh',
        desc: 'Giải pháp kết cấu và bố trí mặt bằng khoa học cho công trình căn hộ dịch vụ, tối ưu hiệu suất đầu tư và chi phí vận hành.'
      },
      {
        id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
        category: 'nha-pho',
        title: 'Cải Tạo & Hoàn Thiện Nhà Phố Trọn Gói Chìa Khóa Trao Tay',
        desc: 'Nâng cấp kết cấu, làm mới mặt tiền và hoàn thiện toàn bộ nội thất tinh gọn, bàn giao sạch sẽ đúng cam kết với chủ đầu tư.'
      }
    ];

    /**
     * Dữ liệu 10 dự án tiêu biểu tại Đà Nẵng
     * (Khớp 100% với 10 link Google Drive người dùng cung cấp)
     */
    const daNangProjects = [
      {
        id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        title: 'Nhà Phố Hiện Đại 3 Tầng – Hòa Xuân, TP. Đà Nẵng',
        desc: 'Dự án nhà phố 3 tầng phong cách hiện đại với mặt tiền thông thoáng, sử dụng hệ lam che nắng và mảng xanh tinh tế tại Hòa Xuân.'
      },
      {
        id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
        title: 'Biệt Thự Phố Sang Trọng – Nam Hòa Xuân, Đà Nẵng',
        desc: 'Thiết kế kiến trúc sang trọng kết hợp thi công trọn gói chuẩn chỉnh từng chi tiết ngoại thất và không gian sinh hoạt.'
      },
      {
        id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
        title: 'Nhà Phố 2 Mặt Tiền Kinh Doanh – Quận Cẩm Lệ, Đà Nẵng',
        desc: 'Công trình nhà phố 2 mặt tiền nổi bật, tối ưu không gian kinh doanh tầng trệt và khu vực sinh hoạt riêng tư các tầng trên.'
      },
      {
        id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
        title: 'Căn Hộ Dịch Vụ Cao Cấp – Ngũ Hành Sơn, Đà Nẵng',
        desc: 'Mô hình căn hộ cho thuê hiện đại gần biển, thiết kế thông gió tự nhiên, dễ bảo trì và mang lại hiệu quả khai thác lâu dài.'
      },
      {
        id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
        title: 'Nhà Phố 3 Tầng Có Gara Ô Tô – Khu Phước Lý, Đà Nẵng',
        desc: 'Giải pháp kiến trúc nhà ống hiện đại tích hợp gara rộng rãi, giếng trời đón sáng tự nhiên và không gian phòng khách bếp liên thông.'
      },
      {
        id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
        title: 'Khách Sạn Mini & Căn Hộ Lưu Trú – Quận Sơn Trà, Đà Nẵng',
        desc: 'Thiết kế mặt tiền ấn tượng cùng quy trình thi công phần thô và hoàn thiện đồng bộ đạt tiêu chuẩn công trình lưu trú.'
      },
      {
        id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
        title: 'Nhà Phố Mái Nhật Hiện Đại – Quận Liên Chiểu, Đà Nẵng',
        desc: 'Kiến trúc thanh lịch, đường nét gọn gàng, tối ưu công năng 4 phòng ngủ với chi phí xây dựng trọn gói hợp lý.'
      },
      {
        id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
        title: 'Biệt Thự Vườn Không Gian Mở – Hòa Quý, Đà Nẵng',
        desc: 'Không gian sống gần gũi thiên nhiên với hệ cửa kính lớn, ban công rộng và chất liệu hoàn thiện bền đẹp với khí hậu miền Trung.'
      },
      {
        id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
        title: 'Nhà Phố 4 Tầng Kết Hợp Văn Phòng – Hải Châu, Đà Nẵng',
        desc: 'Công trình trung tâm thành phố có thiết kế hiện đại, tối ưu diện tích sàn sử dụng cho cả văn phòng làm việc và nhà ở gia đình.'
      },
      {
        id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
        title: 'Nhà Phố Trọn Gói Đầy Đủ Nội Thất – Thanh Khê, Đà Nẵng',
        desc: 'Bàn giao chìa khóa trao tay hoàn chỉnh từ phần thô, hoàn thiện mặt tiền đến toàn bộ hệ tủ bếp, phòng khách và phòng ngủ.'
      }
    ];

    /**
     * Dữ liệu 4 bài viết tin tức & kinh nghiệm xây dựng trên trang chủ
     */
    const articlesData = [
      {
        imgId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        date: '16/05/2026',
        title: 'Quy Trình Kiểm Tra Và Đổ Bê Tông Sàn Đúng Kỹ Thuật Cho Nhà Phố',
        summary: 'Hướng dẫn các bước kiểm tra cốp pha, cốt thép, cao độ và bảo dưỡng bê tông sau khi đổ giúp kết cấu sàn bền chắc lâu dài.',
        content: 'Đổ bê tông sàn là một trong những hạng mục quan trọng bậc nhất quyết định độ bền vững của ngôi nhà. Trước khi tiến hành đổ bê tông, đội ngũ kỹ sư An Việt Quảng Nam luôn nghiệm thu kỹ hệ chống đỡ cốp pha, khoảng cách thép lớp trên – lớp dưới, con kê bảo vệ cốt thép và hệ thống ống điện nước âm sàn. Sau khi đổ xong, công tác tưới nước bảo dưỡng đều đặn giúp bê tông đạt cường độ tối ưu và hạn chế nứt bề mặt.'
      },
      {
        imgId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        date: '20/04/2026',
        title: 'Kinh Nghiệm Xây Nhà Trọn Gói Không Phát Sinh Chi Phí Tại Đà Nẵng',
        summary: 'Những lưu ý quan trọng về hồ sơ thiết kế, bảng dự toán vật tư và hợp đồng thi công giúp gia chủ kiểm soát ngân sách hiệu quả.',
        content: 'Để xây nhà trọn gói không phát sinh ngoài dự kiến, gia chủ cần hoàn thiện hồ sơ thiết kế kiến trúc – kết cấu rõ ràng ngay từ đầu, thống nhất chi tiết chủng loại vật tư phần thô lẫn hoàn thiện trong phụ lục hợp đồng. Lựa chọn nhà thầu minh bạch như An Việt Quảng Nam giúp bạn chủ động tiến độ, đảm bảo chất lượng và tiết kiệm tối đa thời gian giám sát.'
      },
      {
        imgId: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        date: '12/03/2026',
        title: '3 Nỗi Lo Lớn Nhất Khi Xây Nhà Và Giải Pháp Từ Nhà Thầu Uy Tín',
        summary: 'Giải đáp bài toán chất lượng kết cấu, tiến độ thi công và chế độ bảo hành sau bàn giao cho các chủ đầu tư lần đầu xây nhà.',
        content: 'Phần lớn chủ đầu tư khi chuẩn bị xây tổ ấm đều lo ngại ba vấn đề: chất lượng vật tư không đúng cam kết, công trình chậm tiến độ và phát sinh chi phí. Với quy trình báo cáo tiến độ hằng tuần, nghiệm thu công khai từng giai đoạn móng – thân – mái và chính sách bảo hành rõ ràng, An Việt Quảng Nam giúp gia chủ hoàn toàn an tâm trong suốt hành trình xây nhà.'
      },
      {
        imgId: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        date: '05/02/2026',
        title: 'Xu Hướng Thiết Kế Nhà Phố Hiện Đại Chống Nóng Tốt Cho Miền Trung',
        summary: 'Tối ưu thông gió tự nhiên, giếng trời, vật liệu cách nhiệt và mảng xanh ban công để ngôi nhà luôn mát mẻ quanh năm.',
        content: 'Đặc thù khí hậu nắng nóng và mưa bão tại Đà Nẵng – Quảng Nam đòi hỏi giải pháp kiến trúc phải vừa bền vững vừa thông thoáng. Việc bố trí giếng trời hợp lý, kết hợp hệ lam chắn nắng, tường chống thấm nhiều lớp và cửa nhôm kính cách nhiệt giúp giảm đáng kể nhiệt độ trong nhà và tiết kiệm điện năng lâu dài.'
      }
    ];

    /**
     * Render danh sách 9 công trình thực tế (hỗ trợ lọc danh mục)
     */
    function renderRealProjects(filter = 'all') {
      const grid = document.getElementById('realProjectsGrid');
      if (!grid) return;

      const items = filter === 'all'
        ? realProjects
        : realProjects.filter((item) => item.category === filter);

      grid.innerHTML = items.map((item) => {
        const img = driveImg(item.id, 900);
        return `
          <article
            onclick="openPreviewModal('${escapeAttr(item.title)}', '${img.primary}', '${img.fallback}', '${escapeAttr(item.desc)}')"
            class="group cursor-pointer bg-white rounded-xl border border-gray-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col"
          >
            <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
              <img
                src="${img.primary}"
                data-fallback="${img.fallback}"
                alt="${escapeAttr(item.title)}"
                loading="lazy"
                referrerpolicy="no-referrer"
                onerror="handleDriveImageError(this, 'CONG TRINH THUC TE')"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              />
            </div>
            <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
              <h3 class="text-[12.5px] sm:text-sm font-bold text-gray-900 group-hover:text-brand-primary transition leading-snug break-words">
                ${item.title}
              </h3>
            </div>
          </article>
        `;
      }).join('');
    }

    /**
     * Xử lý nút lọc danh mục công trình thực tế
     */
    function filterProjects(category) {
      document.querySelectorAll('.project-filter-btn').forEach((btn) => {
        const isActive = btn.getAttribute('data-filter') === category;
        btn.classList.toggle('bg-brand-primary', isActive);
        btn.classList.toggle('text-white', isActive);
        btn.classList.toggle('bg-gray-100', !isActive);
        btn.classList.toggle('text-gray-700', !isActive);
      });
      renderRealProjects(category);
    }

    /**
     * Render 10 dự án tiêu biểu tại Đà Nẵng (2 cột trên mobile, 5 cột trên desktop)
     */
    function renderDaNangProjects() {
      const grid = document.getElementById('daNangProjectsGrid');
      if (!grid) return;

      grid.innerHTML = daNangProjects.map((item) => {
        const img = driveImg(item.id, 800);
        return `
          <article
            onclick="openPreviewModal('${escapeAttr(item.title)}', '${img.primary}', '${img.fallback}', '${escapeAttr(item.desc)}')"
            class="group cursor-pointer bg-white rounded-xl border border-gray-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col"
          >
            <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
              <img
                src="${img.primary}"
                data-fallback="${img.fallback}"
                alt="${escapeAttr(item.title)}"
                loading="lazy"
                referrerpolicy="no-referrer"
                onerror="handleDriveImageError(this, 'DU AN DA NANG')"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              />
            </div>
            <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
              <h3 class="text-[12px] sm:text-[13px] font-bold text-gray-900 group-hover:text-brand-primary transition leading-snug break-words">
                ${item.title}
              </h3>
            </div>
          </article>
        `;
      }).join('');
    }

    /**
     * Render danh mục bài viết trang chủ
     */
    function renderArticles() {
      const grid = document.getElementById('articlesGrid');
      if (!grid) return;

      grid.innerHTML = articlesData.map((art) => {
        const img = driveImg(art.imgId, 700);
        return `
          <article
            onclick="openPreviewModal('${escapeAttr(art.title)}', '${img.primary}', '${img.fallback}', '${escapeAttr(art.content)}')"
            class="group cursor-pointer bg-white rounded-xl border border-gray-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col"
          >
            <div class="aspect-[16/10] w-full overflow-hidden bg-gray-100">
              <img
                src="${img.primary}"
                data-fallback="${img.fallback}"
                alt="${escapeAttr(art.title)}"
                loading="lazy"
                referrerpolicy="no-referrer"
                onerror="handleDriveImageError(this, 'TIN TUC XAY DUNG')"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              />
            </div>
            <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between space-y-2">
              <div>
                <div class="text-[11px] text-gray-500 font-medium mb-1">${art.date}</div>
                <h3 class="text-[12.5px] sm:text-sm font-bold text-brand-primary group-hover:text-brand-accent transition leading-snug break-words">
                  ${art.title}
                </h3>
                <p class="mt-1.5 text-[11px] sm:text-xs text-gray-600 leading-relaxed hidden sm:block">
                  ${art.summary}
                </p>
              </div>
              <span class="inline-block text-[11px] sm:text-xs font-bold text-brand-accent">Xem chi tiết →</span>
            </div>
          </article>
        `;
      }).join('');
    }

    /**
     * Escaping chuỗi an toàn cho thuộc tính onclick HTML
     */
    function escapeAttr(str) {
      return String(str || '')
        .replace(/\\/g, '\\\\')
        .replace(/'/g, "\\'")
        .replace(/"/g, '&quot;')
        .replace(/\n/g, ' ');
    }

    /**
     * Mở hộp thoại xem chi tiết ảnh công trình hoặc bài viết
     */
    function openPreviewModal(title, imgUrl, fallbackUrl, bodyText) {
      const modal = document.getElementById('previewModal');
      const modalTitle = document.getElementById('modalTitle');
      const modalImage = document.getElementById('modalImage');
      const modalBody = document.getElementById('modalBody');

      modalTitle.textContent = title;
      modalImage.dataset.triedFallback = '';
      modalImage.dataset.triedPlaceholder = '';
      modalImage.setAttribute('data-fallback', fallbackUrl);
      modalImage.onerror = function () {
        handleDriveImageError(this, 'AN VIET QUANG NAM');
      };
      modalImage.src = imgUrl;
      modalImage.alt = title;
      modalBody.textContent = bodyText;

      modal.classList.remove('hidden');
      document.body.style.overflow = 'hidden';
    }

    function closePreviewModal() {
      const modal = document.getElementById('previewModal');
      modal.classList.add('hidden');
      document.body.style.overflow = '';
    }

    /**
     * Khởi tạo toàn bộ sự kiện giao diện khi DOM sẵn sàng
     */
    document.addEventListener('DOMContentLoaded', () => {
      renderRealProjects('all');
      renderDaNangProjects();
      renderArticles();

      // 1. Điều khiển Menu Mobile
      const mobileMenuBtn = document.getElementById('mobileMenuBtn');
      const mobileMenu = document.getElementById('mobileMenu');
      const menuIconOpen = document.getElementById('menuIconOpen');
      const menuIconClose = document.getElementById('menuIconClose');

      if (mobileMenuBtn && mobileMenu) {
        mobileMenuBtn.addEventListener('click', () => {
          const isHidden = mobileMenu.classList.toggle('hidden');
          menuIconOpen.classList.toggle('hidden', !isHidden);
          menuIconClose.classList.toggle('hidden', isHidden);
        });

        document.querySelectorAll('.mobile-nav-link').forEach((link) => {
          link.addEventListener('click', () => {
            mobileMenu.classList.add('hidden');
            menuIconOpen.classList.remove('hidden');
            menuIconClose.classList.add('hidden');
          });
        });
      }

      // 2. Điều khiển Slider 2 Banner tự trượt + vuốt cảm ứng trên điện thoại
      const slides = document.querySelectorAll('#heroSlider .hero-slide');
      const dots = document.querySelectorAll('[data-slide-dot]');
      let currentSlide = 0;
      let autoSlideTimer = null;

      function showSlide(index) {
        currentSlide = (index + slides.length) % slides.length;
        slides.forEach((slide, i) => {
          slide.classList.toggle('active', i === currentSlide);
        });
        dots.forEach((dot, i) => {
          if (i === currentSlide) {
            dot.classList.add('w-6', 'bg-amber-400');
            dot.classList.remove('w-2.5', 'bg-white/50');
          } else {
            dot.classList.remove('w-6', 'bg-amber-400');
            dot.classList.add('w-2.5', 'bg-white/50');
          }
        });
      }

      function startAutoSlide() {
        stopAutoSlide();
        autoSlideTimer = setInterval(() => showSlide(currentSlide + 1), 5000);
      }

      function stopAutoSlide() {
        if (autoSlideTimer) clearInterval(autoSlideTimer);
      }

      document.getElementById('prevSlideBtn')?.addEventListener('click', () => {
        showSlide(currentSlide - 1);
        startAutoSlide();
      });

      document.getElementById('nextSlideBtn')?.addEventListener('click', () => {
        showSlide(currentSlide + 1);
        startAutoSlide();
      });

      dots.forEach((dot) => {
        dot.addEventListener('click', () => {
          const idx = Number(dot.getAttribute('data-slide-dot'));
          showSlide(idx);
          startAutoSlide();
        });
      });

      const heroSlider = document.getElementById('heroSlider');
      if (heroSlider) {
        heroSlider.addEventListener('mouseenter', stopAutoSlide);
        heroSlider.addEventListener('mouseleave', startAutoSlide);

        // Hỗ trợ vuốt ngang trên điện thoại
        let touchStartX = 0;
        heroSlider.addEventListener('touchstart', (e) => {
          touchStartX = e.changedTouches[0].screenX;
        }, { passive: true });
        heroSlider.addEventListener('touchend', (e) => {
          const diff = e.changedTouches[0].screenX - touchStartX;
          if (Math.abs(diff) > 40) {
            showSlide(diff > 0 ? currentSlide - 1 : currentSlide + 1);
            startAutoSlide();
          }
        }, { passive: true });
      }
      startAutoSlide();

      // 3. Xử lý đóng Modal
      document.getElementById('closeModalBtn')?.addEventListener('click', closePreviewModal);
      document.getElementById('previewModal')?.addEventListener('click', (e) => {
        if (e.target.id === 'previewModal') closePreviewModal();
      });
      document.addEventListener('keydown', (e) => {
        if (e.key === 'Escape') closePreviewModal();
      });

      // 4. Xử lý gửi Form yêu cầu tư vấn & báo giá (Hiển thị thông báo đẹp, không dùng alert)
      const quoteForm = document.getElementById('quoteForm');
      const quoteFeedback = document.getElementById('quoteFeedback');

      if (quoteForm && quoteFeedback) {
        quoteForm.addEventListener('submit', (e) => {
          e.preventDefault();
          const name = document.getElementById('customerName').value.trim();
          const phone = document.getElementById('customerPhone').value.trim();
          const type = document.getElementById('projectType').value;

          if (!name || !phone) {
            quoteFeedback.className = 'rounded-lg p-3.5 text-xs sm:text-sm font-medium bg-red-50 text-red-700 border border-red-200';
            quoteFeedback.textContent = 'Vui lòng nhập đầy đủ họ tên và số điện thoại để An Việt Quảng Nam liên hệ báo giá.';
            return;
          }

          quoteFeedback.className = 'rounded-lg p-3.5 text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200';
          quoteFeedback.textContent = `Cảm ơn anh/chị ${name}! Yêu cầu báo giá hạng mục "${type}" đã được ghi nhận. Kỹ sư An Việt Quảng Nam sẽ gọi lại số ${phone} trong thời gian sớm nhất.`;
          quoteForm.reset();
        });
      }
    });
  </script>
</body>
</html>
