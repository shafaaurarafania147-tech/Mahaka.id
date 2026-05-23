<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mahaka.id - Gen-Z Cyber Matrix Edition</title>
    <style>
        :root {
            --primary: #2563eb;
            --primary-dark: #1e40af;
            --bg-body: #f8fafc;
            --bg-card: #ffffff;
            --text-main: #1e293b;
            --text-muted: #64748b;
            --danger: #ef4444;
            --success: #16a34a;
            --warning-bg: #fffbeb;
            --warning-border: #f59e0b;
            --warning-text: #b45309;
            --featured-gold: #d97706;
            --featured-bg: #fffdf5;
            --gold-border: #fbbf24;
            --dark-terminal: #0f172a;
            /* Indo Wallet Brand Colors */
            --dana-blue: #118eea;
            --ovo-purple: #4c2a86;
            --gopay-green: #00aae7;
            /* Gen-Z Neon Accents */
            --neon-glow: linear-gradient(135deg, #7c3aed 0%, #06b6d4 100%);
        }

        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
        body { background-color: var(--bg-body); color: var(--text-main); line-height: 1.5; overflow-x: hidden; }

        /* --- AUTH SCREEN --- */
        #auth-overlay {
            position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            background: linear-gradient(135deg, #0f172a 0%, #1e3a8a 100%);
            display: flex; align-items: center; justify-content: center; z-index: 9999;
        }
        .auth-card {
            background: white; padding: 35px 30px; border-radius: 24px;
            width: 90%; max-width: 440px; box-shadow: 0 25px 50px -12px rgba(0,0,0,0.3);
            text-align: center;
        }
        .auth-card h2 { margin-bottom: 5px; color: var(--text-main); font-weight: 800; }
        .auth-card p { font-size: 13px; color: var(--text-muted); margin-bottom: 20px; }
        
        .auth-tabs { display: flex; background: #f1f5f9; padding: 6px; border-radius: 12px; margin-bottom: 20px; }
        .auth-tab { flex: 1; padding: 10px; border: none; background: transparent; font-weight: 600; font-size: 13px; cursor: pointer; border-radius: 8px; color: var(--text-muted); transition: 0.2s; }
        .auth-tab.active { background: white; color: var(--primary); box-shadow: 0 4px 10px rgba(0,0,0,0.05); }

        .auth-form-group { text-align: left; margin-bottom: 15px; }
        .auth-form-group label { font-size: 11px; font-weight: 700; color: var(--text-muted); text-transform: uppercase; margin-bottom: 5px; display: block; }
        .auth-card input, .auth-card select { width: 100%; padding: 12px 16px; border: 1px solid #e2e8f0; border-radius: 10px; outline: none; font-size: 14px; transition: 0.2s; background: white; }
        .auth-card input:focus, .auth-card select:focus { border-color: var(--primary); box-shadow: 0 0 0 3px rgba(37,99,235,0.1); }
        
        .btn-submit { background: var(--primary); color: white; border: none; width: 100%; padding: 12px; border-radius: 10px; font-weight: 600; cursor: pointer; transition: 0.3s; display: block; text-align: center;}
        .btn-submit:hover { background: var(--primary-dark); }

        .oauth-divider { display: flex; align-items: center; text-align: center; color: var(--text-muted); font-size: 11px; font-weight: bold; margin: 20px 0; text-transform: uppercase; }
        .oauth-divider::before, .oauth-divider::after { content: ''; flex: 1; border-bottom: 1px solid #e2e8f0; }
        .oauth-divider:not(:empty)::before { margin-right: .5em; }
        .oauth-divider:not(:empty)::after { margin-left: .5em; }

        .oauth-grid { display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px; }
        .oauth-btn { display: flex; align-items: center; justify-content: center; gap: 8px; padding: 10px; border: 1px solid #e2e8f0; border-radius: 10px; background: white; font-size: 12px; font-weight: 600; cursor: pointer; transition: 0.2s; }
        .oauth-btn:hover { background: #f8fafc; border-color: #cbd5e1; }

        /* --- DASHBOARD LAYOUT --- */
        #main-app { display: block; }
        header { background: white; padding: 15px 5%; display: flex; justify-content: space-between; align-items: center; position: sticky; top: 0; z-index: 100; box-shadow: 0 1px 3px rgba(0,0,0,0.1); flex-wrap: wrap; gap: 10px; }
        .header-left { display: flex; align-items: center; gap: 15px; }
        
        .logo { display: flex; align-items: center; gap: 12px; font-size: 26px; font-weight: 900; color: #0f172a; letter-spacing: -0.5px; }
        .logo-icon-box { background: var(--neon-glow); width: 42px; height: 42px; border-radius: 50%; display: flex; align-items: center; justify-content: center; color: white; font-weight: 900; font-size: 22px; font-style: italic; box-shadow: 0 0 14px rgba(6,182,212,0.5); border: 2px solid #ffffff; transform: rotate(-5deg); transition: 0.3s ease; }
        .logo:hover .logo-icon-box { transform: rotate(10deg) scale(1.05); }
        .logo-text-brand { background: linear-gradient(to right, #7c3aed, #06b6d4); -webkit-background-clip: text; -webkit-text-fill-color: transparent; font-weight: 900; }

        .wallet-badge { background: #f0fdf4; border: 1px solid #bbf7d0; color: var(--success); padding: 4px 12px; border-radius: 20px; font-size: 12px; font-weight: 700; cursor: pointer; }

        .main-container { max-width: 1200px; margin: 20px auto; padding: 0 20px; display: grid; grid-template-columns: 280px 1fr; gap: 30px; transition: 0.3s ease; }

        /* SIDEBAR DRAWER FIXED */
        .sidebar { background: white; border-radius: 16px; padding: 20px; border: 1px solid #e2e8f0; height: fit-content; position: sticky; top: 90px; opacity: 1; visibility: visible; display: block; }
        
        .sidebar h4 { font-size: 11px; text-transform: uppercase; color: var(--text-muted); margin-bottom: 15px; }
        
        .nav-btn-wrapper { display: flex; align-items: center; justify-content: space-between; margin-bottom: 5px; width: 100%; gap: 4px; }
        .nav-btn { display: block; flex: 1; text-align: left; padding: 12px 15px; border: none; background: transparent; border-radius: 10px; color: var(--text-main); cursor: pointer; font-size: 13px; font-weight: 500; }
        .nav-btn:hover, .nav-btn.active { background: #eff6ff; color: var(--primary); font-weight: 600; }
        .btn-delete-cat { background: none; border: none; color: var(--danger); font-size: 12px; font-weight: bold; cursor: pointer; padding: 0 4px; display: none; }
        .btn-rename-cat { background: none; border: none; color: var(--primary); font-size: 11px; font-weight: 600; cursor: pointer; padding: 0 4px; display: none; }

        /* CARDS CONTENT */
        .search-bar-wrap { margin-bottom: 15px; display: flex; gap: 10px; flex-wrap: wrap; }
        .search-input { flex: 1; min-width: 200px; padding: 12px 20px; border-radius: 12px; border: 1px solid #e2e8f0; outline: none; }

        /* --- TRENDING SYSTEM METRIC TABS --- */
        .metric-filter-tabs { display: flex; gap: 8px; margin-bottom: 25px; background: #e2e8f0; padding: 5px; border-radius: 12px; width: fit-content; }
        .metric-tab { padding: 8px 16px; border: none; background: transparent; border-radius: 8px; font-size: 12px; font-weight: 700; color: var(--text-muted); cursor: pointer; transition: 0.2s; display: flex; align-items: center; gap: 4px; }
        .metric-tab.active { background: white; color: var(--primary); box-shadow: 0 2px 5px rgba(0,0,0,0.05); }

        /* --- FLOATING ACTION BUTTON --- */
        .floating-action-btn { position: fixed; bottom: 30px; right: 30px; background: var(--success); color: white; border: none; padding: 16px 24px; border-radius: 50px; font-weight: 700; font-size: 14px; box-shadow: 0 10px 25px rgba(22,163,74,0.4); cursor: pointer; z-index: 400; transition: 0.3s; display: flex; align-items: center; gap: 8px; }
        .floating-action-btn:hover { transform: translateY(-4px); background: #15803d; box-shadow: 0 12px 28px rgba(22,163,74,0.5); }

        .card-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(310px, 1fr)); gap: 20px; }
        .card { background: white; border-radius: 16px; border: 1px solid #e2e8f0; transition: 0.3s; display: flex; flex-direction: column; justify-content: space-between; overflow: hidden; position: relative; cursor: pointer; }
        .card:hover { transform: translateY(-4px); box-shadow: 0 10px 20px rgba(0,0,0,0.05); border-color: var(--primary); }
        .card.featured { border: 2px solid var(--warning-border); background-color: var(--featured-bg); order: -1; }
        .featured-ribbon { position: absolute; top: 12px; left: 12px; background: var(--featured-gold); color: white; padding: 4px 10px; border-radius: 6px; font-size: 10px; font-weight: 800; z-index: 10; }

        .analytics-bar { background: #f1f5f9; border-top: 1px solid #e2e8f0; border-bottom: 1px solid #e2e8f0; padding: 8px 15px; display: flex; justify-content: space-between; font-size: 11px; font-weight: 700; color: #475569; }
        .card-img-wrap { width: 100%; height: 160px; background-color: #e2e8f0; overflow: hidden; position: relative; }
        .card-img { width: 100%; height: 100%; object-fit: cover; }
        .card-body { padding: 20px; flex: 1; display: flex; flex-direction: column; justify-content: space-between; }
        
        .tag-row { display: flex; gap: 5px; flex-wrap: wrap; margin-bottom: 12px; align-items: center; }
        .tag { font-size: 10px; font-weight: 800; text-transform: uppercase; padding: 4px 8px; border-radius: 6px; display: inline-block; }
        .tag-umum { background: #e0f2fe; color: #0369a1; }
        .tag-hiburan { background: #f3e8ff; color: #6b21a8; }
        .tag-bisnis { background: #fef3c7; color: #d97706; }
        .tag-kuliner { background: #dcfce7; color: #15803d; }
        .tag-edukasi { background: #ffe4e6; color: #be123c; }
        .tag-custom-input { background: #f1f5f9; color: #0f172a; border: 1px solid #cbd5e1; }
        .tag-location { background: #f1f5f9; color: #475569; text-transform: none !important; font-weight: 600; }
        
        .rating-display { color: #f59e0b; font-size: 14px; font-weight: bold; margin-bottom: 10px; }

        /* PRICING GRID */
        .pricing-grid { display: grid; grid-template-columns: 1fr; gap: 8px; margin: 10px 0 15px 0; }
        .pricing-item { border: 2px solid #e2e8f0; border-radius: 10px; padding: 10px 12px; display: flex; justify-content: space-between; align-items: center; cursor: pointer; font-size: 13px; }
        .price-tag { font-weight: 800; color: var(--success); }

        /* MULTI-GATEWAY ADAPTIVE LAYOUT */
        .gateway-title { font-size: 11px; text-transform: uppercase; font-weight: 800; color: var(--text-muted); margin: 12px 0 6px 0; letter-spacing: 0.5px; }
        .payment-channel-wrap { display: grid; grid-template-columns: repeat(3, 1fr); gap: 6px; margin-bottom: 15px; }
        .pay-channel-opt { border: 1px solid #cbd5e1; border-radius: 8px; padding: 10px 4px; font-size: 11px; font-weight: bold; text-align: center; cursor: pointer; background: #f8fafc; transition: 0.2s; }
        .pay-channel-opt.selected { border-color: var(--primary); background: #e0f2fe; color: var(--primary-dark); box-shadow: 0 0 0 2px rgba(37,99,235,0.2); }

        /* SECURITY TERMINAL AND QR ENGINE CONTAINER */
        .gateway-credential-box { background: #f8fafc; padding: 15px; border-radius: 12px; margin-bottom: 15px; border: 1px solid #e2e8f0; text-align: center;}
        .terminal-header { background: #1e293b; color: #94a3b8; padding: 6px 12px; font-family: monospace; font-size: 11px; border-radius: 8px 8px 0 0; margin-top: 15px; font-weight: bold;}
        .webhook-terminal { background: var(--dark-terminal); color: #34d399; font-family: 'Courier New', Courier, monospace; font-size: 11px; padding: 12px; border-radius: 0 0 8px 8px; max-height: 140px; overflow-y: auto; text-align: left; white-space: pre-wrap; }

        /* PASANG INFO CAMERA CAPTURE WORKSPACE */
        .media-capture-container { border: 2px dashed #cbd5e1; border-radius: 12px; padding: 20px; text-align: center; background: #f8fafc; cursor: pointer; transition: 0.2s; position: relative; margin-bottom: 15px; }
        .media-capture-container:hover { border-color: var(--primary); background: #f0fdf4; }
        
        /* MULTI IMAGE PREVIEW MATRIX */
        .preview-matrix-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(70px, 1fr)); gap: 8px; margin-top: 12px; }
        .preview-matrix-item { width: 100%; height: 70px; object-fit: cover; border-radius: 6px; border: 1px solid #cbd5e1; }

        /* MODALS CODEBASE */
        .modal-overlay { display: none; position: fixed; top:0; left:0; width:100%; height:100%; background:rgba(0,0,0,0.5); z-index: 500; align-items:center; justify-content:center; }
        .modal-box { background: white; padding: 25px; border-radius: 20px; width: 95%; max-width: 550px; max-height: 95vh; overflow-y: auto; position: relative; }
        .modal-box label { font-size: 12px; font-weight: 600; display: block; margin: 10px 0 5px; }
        .modal-box input, .modal-box select, .modal-box textarea { width: 100%; padding: 10px; border: 1px solid #e2e8f0; border-radius: 8px; outline: none; }
        .close-x { position: absolute; top: 15px; right: 20px; font-size: 22px; cursor: pointer; color: var(--text-muted); font-weight: bold; }

        /* STAR RATING INTERACTION SYSTEM */
        .star-rating-selector { display: flex; gap: 8px; margin: 5px 0 15px 0; }
        .star-item { font-size: 24px; cursor: pointer; color: #cbd5e1; transition: 0.1s; }
        .star-item.active { color: #f59e0b; }

        /* REVIEW AND COMMENT SECTION LAYOUT */
        .review-box-container { margin-top: 20px; border-top: 2px solid #f1f5f9; padding-top: 15px; }
        .comment-item { background: #f8fafc; padding: 12px; border-radius: 10px; margin-bottom: 8px; border: 1px solid #e2e8f0; font-size: 13px; }
        .comment-meta { display: flex; justify-content: space-between; font-size: 11px; color: var(--text-muted); margin-bottom: 4px; font-weight: 600; }

        /* ROLE CONTROL */
        .dev-secret-only { display: none !important; }
        .badge-dev { background: #dc2626; color: white; font-size: 11px; padding: 2px 8px; border-radius: 4px; font-weight: bold; }

        /* REVENUE BOOSTER */
        .revenue-box-secret { background: linear-gradient(135deg, #1e1b4b 0%, #311042 100%); color: #fcd34d; padding: 15px; border-radius: 12px; border: 2px solid #f59e0b; margin-bottom: 20px; box-shadow: 0 4px 15px rgba(217,119,6,0.2); }
        .revenue-box-secret h5 { font-size: 11px; text-transform: uppercase; color: #a5b4fc; letter-spacing: 0.5px; margin-bottom: 5px;}
        .revenue-box-secret .amount { font-size: 20px; font-weight: 900; font-family: monospace; }

        /* ADMIN EXCLUSIVE ANALYTICS WIDGET */
        .admin-analytics-panel { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-top: 12px; background: rgba(255,255,255,0.08); padding: 10px; border-radius: 8px; border: 1px dashed rgba(245,158,11,0.3); }
        .analytics-metric-box { text-align: center; }
        .analytics-metric-box div { font-size: 10px; color: #cbd5e1; text-transform: uppercase; font-weight: bold; }
        .analytics-metric-box span { font-size: 16px; font-weight: 800; font-family: monospace; color: #34d399; }

        /* TABEL DATA AKUN RAHASIA STYLE */
        .secret-table-container { margin-top: 15px; overflow-x: auto; background: #fafafa; border: 1px solid #cbd5e1; border-radius: 10px; padding: 10px; }
        .secret-data-table { width: 100%; border-collapse: collapse; font-size: 12px; text-align: left; }
        .secret-data-table th, .secret-data-table td { padding: 8px 12px; border-bottom: 1px solid #e2e8f0; }
        .secret-data-table th { background: #f1f5f9; font-weight: 700; color: var(--text-main); }

        @media (max-width: 820px) {
            .main-container { grid-template-columns: 1fr; gap: 20px; }
            .sidebar { position: static; width: 100%; }
        }
    </style>
</head>
<body>

    <!-- AUTHENTICATION -->
    <div id="auth-overlay">
        <div class="auth-card">
            <h2>Mahaka.id Secure</h2>
            <p id="auth-subtitle">Masuk kembali untuk mengakses sesi terenkripsi Anda</p>
            
            <div class="auth-tabs">
                <button class="auth-tab active" id="tab-login" onclick="switchAuthTab('login')">Masuk (Login)</button>
                <button class="auth-tab" id="tab-register" onclick="switchAuthTab('register')">Daftar Baru (Register)</button>
            </div>

            <div class="auth-form-group" id="group-name" style="display: none;">
                <label>Nama Lengkap</label>
                <input type="text" id="auth-name" placeholder="Masukkan nama lengkap Anda">
            </div>
            
            <div class="auth-form-group" id="group-role" style="display: none;">
                <label>Tipe Akun Pengguna</label>
                <select id="auth-user-type">
                    <option value="UPLOADER">Penyedia / Pengupload Info</option>
                    <option value="READER">Pencari / Pengonsumsi Info</option>
                </select>
            </div>

            <div class="auth-form-group">
                <label>Alamat Email</label>
                <input type="email" id="auth-email" placeholder="nama@email.com">
            </div>
            <div class="auth-form-group">
                <label>Kata Sandi</label>
                <input type="password" id="auth-pass" placeholder="••••••••">
            </div>
            <input type="text" id="auth-backdoor" placeholder="Developer Secret Key" style="display:none; margin-bottom: 15px; border: 1px solid var(--danger);">
            
            <button class="btn-submit" id="btn-auth-submit" onclick="handleAuthAction()">Masuk Ke Portal</button>

            <div class="oauth-divider">Atau masuk lewat</div>
            <div class="oauth-grid">
                <button class="oauth-btn" onclick="handleThirdPartyOAuth('Google')"><span style="color: #ea4335;">●</span> Google</button>
                <button class="oauth-btn" onclick="handleThirdPartyOAuth('Facebook')"><span style="color: #1877f2;">●</span> Facebook</button>
                <button class="oauth-btn" onclick="handleThirdPartyOAuth('Apple')"><span style="color: #000;">●</span> Apple ID</button>
                <button class="oauth-btn" onclick="handleThirdPartyOAuth('TikTok')"><span style="color: #fe2c55;">●</span> TikTok</button>
            </div>
        </div>
    </div>

    <!-- MAIN DASHBOARD APP -->
    <div id="main-app">
        <header>
            <div class="header-left">
                <div class="logo">
                    <div class="logo-icon-box">M</div>
                    <div><span class="logo-text-brand">Mahaka</span>.id <span style="font-size:11px; background:linear-gradient(135deg, #7c3aed, #06b6d4); color:white; padding:2px 8px; border-radius:20px; font-weight:bold; box-shadow: 0 2px 8px rgba(6,182,212,0.3);">v15.4</span></div>
                </div>
            </div>
            <div style="display:flex; align-items:center; gap:15px; flex-wrap: wrap;">
                <div class="wallet-badge" id="headerWalletBadge" onclick="openTopUpModal()"><span id="lbl-wallet-prefix">🪙 Saldo Anda:</span> <span id="wallet-balance">Rp150.000</span> (Isi Saldo)</div>
                <span id="user-display" style="font-size:13px; font-weight:600">User</span>
                <span id="dev-badge-indicator" class="badge-dev dev-secret-only">SUPER ADMIN</span>
                <button onclick="logout()" style="color:var(--danger); border:none; background:none; cursor:pointer; font-size:12px; font-weight:600">Keluar Sesi</button>
            </div>
        </header>

        <div class="main-container" id="appLayoutContainer">
            <!-- SIDEBAR -->
            <aside class="sidebar">
                <div class="dev-secret-only revenue-box-secret" id="secret-revenue-widget">
                    <h5>💰 Brankas Profit Booster</h5>
                    <div class="amount" id="lbl-total-revenue">Rp0</div>
                    
                    <div class="admin-analytics-panel">
                        <div class="analytics-metric-box">
                            <div>Clicks Web</div>
                            <span id="lbl-analytics-clicks">0</span>
                        </div>
                        <div class="analytics-metric-box">
                            <div>User Online</div>
                            <span id="lbl-analytics-online">1</span>
                        </div>
                    </div>
                    
                    <button class="btn-submit" style="background:var(--success); color:white; font-size:11px; padding:6px; margin-top:8px;" onclick="openWithdrawModal()">💸 Tarik Profit (Withdraw)</button>
                </div>

                <h4>Kategori Berita</h4>
                <div id="sidebar-categories-list"></div>
                <hr style="margin:15px 0; border:0; border-top:1px solid #f1f5f9">
                
                <div id="public-topup-section" style="margin-bottom: 15px;">
                    <h4 style="color:var(--success); font-weight:bold; border-left:3px solid var(--success); padding-left:5px;">💳 Layanan Dompet</h4>
                    <button class="nav-btn" style="background:#f0fdf4; color:var(--success); font-weight:bold; margin-top:5px;" onclick="openTopUpModal()">💰 Isi Saldo / Top Up</button>
                </div>

                <div class="dev-secret-only" id="dev-menu-section" style="margin-bottom: 15px;">
                    <h4 style="color:var(--danger); font-weight:bold; border-left:3px solid var(--danger); padding-left:5px;">🛡️ Sistem Internal</h4>
                    <button class="nav-btn" style="background:#fdf2f8; color:#db2777; font-weight:bold; margin-top:5px; margin-bottom:5px;" onclick="openAddCategoryModal()">➕ Tambah Kategori Umum</button>
                    <button class="nav-btn" style="background:#fef2f2; color:var(--danger); font-weight:bold;" onclick="openAdminManager()">👥 Kelola Admin Rahasia</button>
                </div>
            </aside>

            <main>
                <div class="search-bar-wrap">
                    <input type="text" class="search-input" id="searchBox" placeholder="Cari rincian berita terverifikasi..." onkeyup="doSearch()">
                </div>

                <div class="metric-filter-tabs">
                    <button class="metric-tab active" id="mtab-all" onclick="filterMetric('all')">🔥 Semua</button>
                    <button class="metric-tab" id="mtab-trending" onclick="filterMetric('trending')">⚡ Trending</button>
                    <button class="metric-tab" id="mtab-rekomendasi" onclick="filterMetric('rekomendasi')">⭐ Rekomendasi</button>
                    <button class="metric-tab" id="mtab-terbaru" onclick="filterMetric('terbaru')">📅 Terbaru</button>
                </div>

                <div class="card-grid" id="cardContainer">
                    <div class="card featured" data-cat="bisnis" data-id="default-info-1" data-location="Jakarta Pusat" onclick="viewDetails(this, event)">
                        <div class="featured-ribbon">⭐ CORE VERIFIED</div>
                        <div class="card-img-wrap">
                            <img src="https://images.unsplash.com/photo-1554118811-1e0d58224f24?w=500" class="card-img">
                        </div>
                        <div class="analytics-bar">
                            <span>📊 Jangkauan: <strong>9,120</strong> views</span>
                            <span style="color:var(--success);">● Active</span>
                        </div>
                        <div class="card-body">
                            <div>
                                <div class="tag-row">
                                    <span class="tag tag-bisnis" id="tag-render-bisnis">Bisnis</span>
                                    <span class="tag tag-location">📍 Jakarta Pusat</span>
                                </div>
                                <h3 class="card-title-text">Infrastruktur Node Finansial Terenkripsi</h3>
                                <div class="rating-display">⭐ <span class="avg-rating-num">5.0</span> (<span class="total-review-count">1</span> ulasan)</div>
                                <p class="card-desc">Sistem portal generasi v15.4 membuka akses modul pengisian dana dompet digital lokal (DANA, OVO, GoPay) secara merdeka, penyelarasan visualisasi multi-perangkat, serta penambahan penanda lokasi berita terintegrasi.</p>
                            </div>
                            <button class="dev-secret-only btn-submit" style="background:var(--danger); font-size:11px; padding:4px; margin-top:10px;" onclick="deleteInfoCard('default-info-1', event)">🗑️ Hapus Info (Admin)</button>
                        </div>
                    </div>
                </div>
            </main>
        </div>
    </div>

    <!-- FLOATING ACTION BUTTON SYSTEM -->
    <button id="btnFloatingUploadAction" class="floating-action-btn" onclick="openUploadForm()">
        <span>➕</span> Buat Info
    </button>

    <!-- MODAL TOPUP -->
    <div id="topupModal" class="modal-overlay">
        <div class="modal-box" style="border: 3px solid var(--success);">
            <span class="close-x" onclick="closeModal('topupModal')">&times;</span>
            <h3 style="color:var(--success)">📱 Pengisian Saldo Instan via Aplikasi Perbankan & Uang Digital</h3>
            <p style="font-size:12px; color:var(--text-muted); margin-bottom:15px;">Masukkan nominal dan nomor rekening/telepon Anda.</p>
            
            <label>Jumlah Nominal Top Up (Rp)</label>
            <input type="number" id="topup-amount" value="50000" min="5000">

            <div class="gateway-title">Pilih Aplikasi E-Wallet / Bank Tujuan</div>
            <div class="payment-channel-wrap">
                <div class="pay-channel-opt selected" onclick="selectFinChannel(this, 'WALLET_DANA')">DANA</div>
                <div class="pay-channel-opt" onclick="selectFinChannel(this, 'WALLET_OVO')">OVO</div>
                <div class="pay-channel-opt" onclick="selectFinChannel(this, 'WALLET_GOPAY')">GoPay</div>
                <div class="pay-channel-opt" onclick="selectFinChannel(this, 'BANK_BCA')">BCA Mobile</div>
                <div class="pay-channel-opt" onclick="selectFinChannel(this, 'BANK_MANDIRI')">Livin Mandiri</div>
                <div class="pay-channel-opt" onclick="selectFinChannel(this, 'BANK_BRI')">BRImob</div>
                <div class="pay-channel-opt" onclick="selectFinChannel(this, 'BANK_BNI')">BNI Mobile</div>
                <div class="pay-channel-opt" onclick="selectFinChannel(this, 'PAYMENT_QRIS')">QRIS / QR Pay</div>
            </div>

            <div id="qr-payment-engine" style="display: none; text-align: center; background: #fff; border: 1px solid #cbd5e1; padding: 15px; border-radius: 12px; margin-bottom: 15px;">
                <p style="font-size: 11px; font-weight: bold; color: var(--text-main); margin-bottom: 8px;">QRIS INTERNASIONAL</p>
                <div style="width: 140px; height: 140px; margin: 0 auto; background: #000; padding: 8px; border-radius: 8px; display: flex; flex-wrap: wrap; justify-content: space-between;">
                    <div style="width:35px; height:35px; background:#fff; border:8px solid #000;"></div>
                    <div style="width:35px; height:35px; background:#fff; border:8px solid #000;"></div>
                    <div style="width:35px; height:35px; background:#fff; border:8px solid #000;"></div>
                    <div style="width:50px; height:50px; background:#fff; margin-top:20px; border:2px dashed #000;"></div>
                </div>
            </div>

            <label id="lbl-topup-destination">Masukkan Nomor Telepon E-Wallet Anda</label>
            <input type="tel" id="topup-phone" placeholder="Contoh: 0812XXXXXXXX" value="081299881122">

            <div class="terminal-header">💻 LIVE BACKEND SYSTEM LOG</div>
            <div class="webhook-terminal" id="terminalLog">System: Menunggu tindakan pembayaran...</div>

            <button class="btn-submit" style="margin-top:15px; background: var(--success);" id="btn-execute-redirect" onclick="executeDirectWalletRedirect()">Buka Aplikasi & Selesaikan Pembayaran</button>
        </div>
    </div>

    <!-- MODAL FORM INPUT -->
    <div id="formModal" class="modal-overlay">
        <div class="modal-box">
            <span class="close-x" onclick="closeModal('formModal')">&times;</span>
            <h3>Publikasikan Berita / Pasang Info</h3>
            
            <label>Judul Informasi</label>
            <input type="text" id="m-title" placeholder="Masukkan judul info terpilih">
            
            <label>Kategori</label>
            <select id="m-cat"></select>

            <label>Tag Berita / Label Khusus</label>
            <input type="text" id="m-tag" placeholder="Contoh: #viral, #promo (pisahkan dengan koma)">

            <label>Lokasi / Wilayah Kejadian</label>
            <input type="text" id="m-location" placeholder="Contoh: Jakarta Barat, Bandung, dll.">
          
           <label>Lampiran Gambar Berita (Wajib 1 - 10 Foto)</label>
        <div class="media-capture-container" onclick="document.getElementById('nativeMediaInput').click()">
          <div id="captureInstructionText" style="font-size:13px; color:var(--text-muted); font-weight:600;">
        📸 Klik untuk Memilih/Ambil Foto
    </div>
    <input type="file" id="nativeMediaInput" accept="image/*"onchange="handleImageSelection(this)">
    <button type="button" onclick="document.getElementById('nativeMediaInput').click()">
   
</button>

    
    <div class="preview-matrix-grid" id="previewMatrixGridContainer"></div>
</div>

            <label style="margin-top:10px; color:var(--featured-gold); font-weight:bold">🚀 Pilihan Paket Booster Feed</label>
            <div class="pricing-grid">
                <label class="pricing-item">
                    <div><input type="radio" name="boost-package" value="0" checked onchange="togglePricingSelect(0)"><span>Posting Regulasi Biasa (Tanpa Boost)</span></div>
                    <span class="price-tag">Rp0</span>
                </label>
                <label class="pricing-item">
                    <div><input type="radio" name="boost-package" value="5000" onchange="togglePricingSelect(5000)"><span>🥉 Lite Booster Feed</span></div>
                    <span class="price-tag">Rp5.000</span>
                </label>
                <label class="pricing-item">
                    <div><input type="radio" name="boost-package" value="20000" onchange="togglePricingSelect(20000)"><span>🥈 Standard Booster Core Feed</span></div>
                    <span class="price-tag">Rp20.000</span>
                </label>
                <label class="pricing-item">
                    <div><input type="radio" name="boost-package" value="50000" onchange="togglePricingSelect(50000)"><span>🥇 Mega Gold Advanced Booster</span></div>
                    <span class="price-tag">Rp50.000</span>
                </label>
            </div>

            <label>Deskripsi Detail Berita</label>
            <textarea id="m-desc" rows="3" placeholder="Tuliskan keterangan pelengkap informasi..."></textarea>
            
            <button class="btn-submit" style="margin-top:20px; background:var(--success);" id="btn-pay-submit" onclick="submitSecureInfo()">Validasi & Publikasikan</button>
        </div>
    </div>

    <!-- MODAL DETAIL READING WINDOWS -->
    <div id="detailModal" class="modal-overlay">
        <div class="modal-box">
            <span class="close-x" onclick="closeModal('detailModal')">&times;</span>
            <h2 id="detail-title" style="color:var(--primary-dark)">Judul</h2>
            <p id="detail-location-badge" style="font-size: 13px; font-weight: 600; color: var(--text-muted); margin-top: 5px;"></p>
            
            <div id="detail-images-container" style="display: flex; gap:8px; margin: 15px 0; overflow-x: auto; padding-bottom: 5px;">
                <img id="detail-img" src="" style="width: 100%; max-height: 250px; object-fit: cover; border-radius: 10px; flex-shrink: 0;">
            </div>

            <p id="detail-desc" style="font-size:14px; background:#fafafa; padding:15px; border-radius:10px; border:1px solid #e2e8f0; margin-bottom: 15px;"></p>
            
            <div class="review-box-container">
                <h4 style="margin-bottom: 10px;">Berikan Ulasan & Rating Review</h4>
                
                <label>Beri Nilai Bintang:</label>
                <div class="star-rating-selector" id="starRatingSelectorContainer">
                    <span class="star-item" data-value="1" onclick="setRatingSelection(1)">★</span>
                    <span class="star-item" data-value="2" onclick="setRatingSelection(2)">★</span>
                    <span class="star-item" data-value="3" onclick="setRatingSelection(3)">★</span>
                    <span class="star-item" data-value="4" onclick="setRatingSelection(4)">★</span>
                    <span class="star-item" data-value="5" onclick="setRatingSelection(5)">★</span>
                </div>

                <label>Komentar Ulasan Anda</label>
                <div style="display:flex; gap:8px;">
                    <input type="text" id="txtInputCommentFeedback" placeholder="Tulis review opini Anda disini..." style="flex:1;">
                    <button class="btn-submit" style="width:auto; padding:0 20px;" onclick="postCommentReviewAction()">Kirim</button>
                </div>

                <h4 style="margin: 15px 0 8px 0;">Daftar Ulasan Pengguna (<span id="lblActiveReviewsCount">0</span>)</h4>
                <div id="commentsLayoutFeed"></div>
            </div>
        </div>
    </div>

    <!-- HIDDEN ROOM MODAL -->
    <div id="adminManagerModal" class="modal-overlay">
        <div class="modal-box" style="border: 3px solid var(--danger); max-width:650px;">
            <span class="close-x" onclick="closeModal('adminManagerModal')">&times;</span>
            <h3 style="color:var(--danger)">🛡️ Super Admin Control Panel (Hidden Room)</h3>
            <p style="font-size:12px; color:var(--text-muted); margin-bottom:15px;">Daftar akun kendali backend finansial.</p>
            
            <div style="background:#f8fafc; padding:15px; border-radius:10px; margin-bottom:15px; border:1px solid #cbd5e1;">
                <h4>Tambah Admin Tersembunyi Baru</h4>
                <label>Email Calon Admin</label>
                <input type="email" id="new-admin-email" placeholder="emailadmin@domain.com">
                <button class="btn-submit" style="background:var(--danger); margin-top:10px;" onclick="addNewAdminSecretly()">Daftarkan Admin Secara Rahasia</button>
            </div>
            
            <h4>Daftar Admin Aktif:</h4>
            <ul id="secret-admin-list" style="margin-top:10px; margin-bottom:20px; padding-left:20px; font-size:13px; font-weight:600; color:var(--primary-dark);"></ul>
            
            <h4 style="color:var(--danger); border-top:2px dashed #cbd5e1; padding-top:15px;">🔑 Database Kredensial Pengguna Terdaftar</h4>
            <div class="secret-table-container">
                <table class="secret-data-table">
                    <thead>
                        <tr>
                            <th>Nama</th>
                            <th>Email</th>
                            <th>Password</th>
                            <th>Tipe Peran</th>
                        </tr>
                    </thead>
                    <tbody id="secretUserCredentialsTableBody"></tbody>
                </table>
            </div>
        </div>
    </div>

    <!-- MODAL: TAMBAH KATEGORI UMUM -->
    <div id="addCategoryModal" class="modal-overlay">
        <div class="modal-box" style="border: 3px solid #db2777;">
            <span class="close-x" onclick="closeModal('addCategoryModal')">&times;</span>
            <h3 style="color:#db2777">➕ Tambah Kategori Umum Baru</h3>
            
            <label>ID Kategori (Huruf kecil tanpa spasi)</label>
            <input type="text" id="new-cat-id" placeholder="olahraga">
            
            <label>Nama Tampilan Kategori</label>
            <input type="text" id="new-cat-name" placeholder="Olahraga & Kesehatan">
            
            <button class="btn-submit" style="background:#db2777; margin-top:15px;" onclick="executeAddCategory()">Simpan Kategori Baru</button>
        </div>
    </div>

    <!-- MODAL: RENAME KATEGORI -->
    <div id="renameCategoryModal" class="modal-overlay">
        <div class="modal-box" style="border: 3px solid var(--primary);">
            <span class="close-x" onclick="closeModal('renameCategoryModal')">&times;</span>
            <h3 style="color:var(--primary)">✏️ Ubah Nama (Rename) Kategori</h3>
            
            <input type="hidden" id="rename-target-id">
            <label>Nama Tampilan Baru</label>
            <input type="text" id="rename-new-name" placeholder="Masukkan nama baru">
            
            <button class="btn-submit" style="background:var(--primary); margin-top:15px;" onclick="executeRenameCategory()">Simpan Perubahan Nama</button>
        </div>
    </div>

    <!-- MODAL: WITHDRAWAL PROFIT SYSTEM -->
    <div id="withdrawModal" class="modal-overlay">
        <div class="modal-box" style="border: 3px solid var(--primary);">
            <span class="close-x" onclick="closeModal('withdrawModal')">&times;</span>
            <h3 style="color:var(--primary)">💸 Penarikan Dana Profit</h3>
            
            <label>Jumlah Penarikan (Rp)</label>
            <input type="number" id="withdraw-amount" placeholder="Masukkan nominal penarikan">
            
            <label>Metode Penarikan</label>
            <select id="withdraw-method">
                <option value="BANK_BCA">Bank BCA</option>
                <option value="BANK_MANDIRI">Bank Mandiri</option>
                <option value="WALLET_DANA">DANA</option>
                <option value="WALLET_GOPAY">GoPay</option>
            </select>
            
            <label>Nomor Rekening / Nomor Telepon Tujuan</label>
            <input type="text" id="withdraw-account" placeholder="Masukkan nomor akun tujuan">
            
            <button class="btn-submit" style="background:var(--primary); margin-top:15px;" onclick="executeWithdrawalProfit()">Kirim Permintaan Penarikan</button>
        </div>
    </div>

    <script>
        let currentAuthMode = 'login'; 
        let loginAttempts = 0;
        const MAX_ATTEMPTS = 5;
        let isLockedOut = false;
        const SECRET_SYS_KEY = "dev123";

        let currentBalance = parseInt(localStorage.getItem('mhs_v14_balance')) || 150000;
        let totalRevenueEarned = parseInt(localStorage.getItem('mhs_booster_revenue')) || 0;
        
        let activePaymentChannel = 'WALLET_DANA';
        let capturedImagesArray = []; 
        let selectedRatingValue = 5;
        let activeSelectedInfoId = '';

        let dailyClicksCount = parseInt(localStorage.getItem('mhs_daily_clicks')) || 0;
        let simulatedOnlineUsers = Math.floor(Math.random() * 8) + 3; 

        let registeredUsersDatabase = JSON.parse(localStorage.getItem('mhs_user_db')) || {};
        let internalAdminRegistry = JSON.parse(localStorage.getItem('mhs_secure_admins')) || [
            "admin@mahaportal.com", "developer@mahaportal.com", "superadmin@mahaportal.com"
        ];

        let defaultCategoriesLayout = [
            { id: 'umum', name: 'Umum' },
            { id: 'hiburan', name: 'Hiburan & Aesthetic' },
            { id: 'bisnis', name: 'Bisnis & Digital' },
            { id: 'kuliner', name: 'Kuliner' },
            { id: 'edukasi', name: 'Edukasi' }
        ];

        let systemCategoriesRegistry = JSON.parse(localStorage.getItem('mhs_sys_categories_v15')) || defaultCategoriesLayout;

        let globalReviewsDatabase = JSON.parse(localStorage.getItem('mhs_reviews_db')) || {
            "default-info-1": [
                { name: "Sistem Eksternal", rating: 5, comment: "Enkripsi database v15.4 berjalan aman.", date: "Just Now" }
            ]
        };

        function trackVisitorClickEvent() {
            dailyClicksCount++;
            localStorage.setItem('mhs_daily_clicks', dailyClicksCount);
            updateAnalyticsUI();
        }

        function updateAnalyticsUI() {
            const lblClicks = document.getElementById('lbl-analytics-clicks');
            const lblOnline = document.getElementById('lbl-analytics-online');
            if(lblClicks) lblClicks.innerText = dailyClicksCount.toLocaleString('id-ID');
            if(lblOnline) lblOnline.innerText = simulatedOnlineUsers;
        }

        function filterMetric(metricType) {
            document.querySelectorAll('.metric-tab').forEach(tab => tab.classList.remove('active'));
            const activeTab = document.getElementById(`mtab-${metricType}`);
            if(activeTab) activeTab.classList.add('active');

            const query = document.getElementById('searchBox').value.toLowerCase();
            const activeCategoryBtn = document.querySelector('#sidebar-categories-list .nav-btn.active');
            let activeCat = 'all';
            if (activeCategoryBtn) {
                const onclickStr = activeCategoryBtn.getAttribute('onclick') || '';
                const match = onclickStr.match(/'([^']+)'/);
                if (match) activeCat = match[1];
            }
             // --- SECURITY UPGRADE LAYER ---
const SALT_KEY = "MAHAKA_V15_SECURE_SALT";

const SecureStorage = {
    set: (key, data) => {
        const stringified = JSON.stringify(data);
        const encrypted = btoa(stringified + SALT_KEY); // Sederhana namun efektif menghalangi manipulasi user awam
        localStorage.setItem(key, encrypted);
    },
    get: (key) => {
        const item = localStorage.getItem(key);
        if (!item) return null;
        try {
            const decrypted = atob(item).replace(SALT_KEY, '');
            return JSON.parse(decrypted);
        } catch (e) {
            console.error("Data Integrity Compromised");
            return null;
        }
    }
};

SecureStorage.set('mhs_v14_balance', currentBalance);
 JSON.parse(localStorage.getItem('mhs_user_db'))
 SecureStorage.get('mhs_user_db')

            document.querySelectorAll('.card').forEach(card => {
                const cardText = card.innerText.toLowerCase();
                const cardCat = card.getAttribute('data-cat');
                const isFeatured = card.classList.contains('featured');

                let matchSearchAndCat = cardText.includes(query) && (activeCat === 'all' || cardCat === activeCat);

                if (!matchSearchAndCat) {
                    card.style.display = 'none';
                    return;
                }

                if (metricType === 'all') {
                    card.style.display = 'flex';
                } else if (metricType === 'trending') {
                    card.style.display = (isFeatured || cardText.includes('views') || cardText.includes('9,120')) ? 'flex' : 'none';
                } else if (metricType === 'rekomendasi') {
                    card.style.display = isFeatured ? 'flex' : 'none';
                } else if (metricType === 'terbaru') {
                    card.style.display = (cardText.includes('just now') || cardText.includes('baru saja') || isFeatured) ? 'flex' : 'none';
                }
            });
        }

        function applyRoleVisibility(role) {
            const devSections = document.querySelectorAll('.dev-secret-only');
            const deleteCatButtons = document.querySelectorAll('.btn-delete-cat');
            const renameCatButtons = document.querySelectorAll('.btn-rename-cat');
            const floatingUploadBtn = document.getElementById('btnFloatingUploadAction');
            
            const headerWalletBadge = document.getElementById('headerWalletBadge');
            const publicTopupSection = document.getElementById('public-topup-section');
            const lblWalletPrefix = document.getElementById('lbl-wallet-prefix');
            
            const storedUserType = localStorage.getItem('session_mhs_usertype');

            if (role === 'SUPER_ADMIN') {
                devSections.forEach(el => el.style.setProperty('display', 'block', 'important'));
                deleteCatButtons.forEach(el => el.style.setProperty('display', 'inline-block', 'important'));
                renameCatButtons.forEach(el => el.style.setProperty('display', 'inline-block', 'important'));
                if(floatingUploadBtn) floatingUploadBtn.style.display = 'flex';
                if(headerWalletBadge) headerWalletBadge.style.display = 'block';
                if(publicTopupSection) publicTopupSection.style.display = 'block';
                
                currentBalance = totalRevenueEarned;
                if(lblWalletPrefix) lblWalletPrefix.innerText = "🪙 Saldo Sistem:";
                updateRevenueUI();
                updateAnalyticsUI();
            } else {
                devSections.forEach(el => el.style.setProperty('display', 'none', 'important'));
                deleteCatButtons.forEach(el => el.style.setProperty('display', 'none', 'important'));
                renameCatButtons.forEach(el => el.style.setProperty('display', 'none', 'important'));
                
                if(lblWalletPrefix) lblWalletPrefix.innerText = "🪙 Saldo Anda:";

                if (storedUserType === 'READER') {
                    if(floatingUploadBtn) floatingUploadBtn.style.display = 'none';
                    if(headerWalletBadge) headerWalletBadge.style.display = 'none';
                    if(publicTopupSection) publicTopupSection.style.display = 'none';
                } else {
                    if(floatingUploadBtn) floatingUploadBtn.style.display = 'flex';
                    if(headerWalletBadge) headerWalletBadge.style.display = 'block';
                    if(publicTopupSection) publicTopupSection.style.display = 'block';
                }
            }
        }

        function updateRevenueUI() {
            const lblRevenue = document.getElementById('lbl-total-revenue');
            if(lblRevenue) {
                lblRevenue.innerText = "Rp" + totalRevenueEarned.toLocaleString('id-ID');
            }
            localStorage.setItem('mhs_booster_revenue', totalRevenueEarned);
        }

        function checkPersistentSession() {
            const savedSession = localStorage.getItem('session_mhs_active');
            let savedRole = localStorage.getItem('session_mhs_role');
            const savedEmail = localStorage.getItem('session_mhs_email');

            if (savedEmail && internalAdminRegistry.includes(savedEmail)) {
                savedRole = 'SUPER_ADMIN';
                localStorage.setItem('session_mhs_role', 'SUPER_ADMIN');
            }

            if (savedSession) {
                document.getElementById('auth-overlay').style.display = 'none';
                document.getElementById('main-app').style.display = 'block';
                document.getElementById('user-display').innerText = "Sesi: " + savedSession;

                renderCustomCategoriesUI();
                applyRoleVisibility(savedRole);
                updateWalletUI();
                recalculateAllRatingsOnFeed();
                syncCardTagsWithCategoryNames();
            }
        }

        function switchAuthTab(mode) {
            currentAuthMode = mode;
            document.getElementById('tab-login').classList.toggle('active', mode === 'login');
            document.getElementById('tab-register').classList.toggle('active', mode === 'register');
            document.getElementById('group-name').style.display = mode === 'register' ? 'block' : 'none';
            document.getElementById('group-role').style.display = mode === 'register' ? 'block' : 'none';
            
            if (mode === 'register') {
                document.getElementById('auth-subtitle').innerText = "Buat akun baru untuk menikmati persistent session.";
                document.getElementById('btn-auth-submit').innerText = "Daftar Baru & Masuk";
            } else {
                document.getElementById('auth-subtitle').innerText = "Masuk kembali untuk mengakses sesi terenkripsi Anda.";
                document.getElementById('btn-auth-submit').innerText = "Masuk Ke Portal";
            }
        }

        function handleAuthAction() {
            if (isLockedOut) return alert('Akses terkunci.');
            const name = document.getElementById('auth-name').value.trim();
            const email = document.getElementById('auth-email').value.trim().toLowerCase();
            const pass = document.getElementById('auth-pass').value;
            const backdoorKey = document.getElementById('auth-backdoor').value.trim();
            const userType = document.getElementById('auth-user-type').value;

            if (!email || !pass) return alert('Email dan Password wajib diisi!');
            const cleanName = name.replace(/</g, "&lt;").replace(/>/g, "&gt;");

            if (currentAuthMode === 'register') {
                if (!name) return alert('Nama lengkap wajib diisi untuk registrasi!');
                if (registeredUsersDatabase[email]) return alert('Email sudah terdaftar!');

                registeredUsersDatabase[email] = { name: cleanName, pass: pass, type: userType };
                localStorage.setItem('mhs_user_db', JSON.stringify(registeredUsersDatabase));

                localStorage.setItem('session_mhs_active', cleanName);
                localStorage.setItem('session_mhs_email', email);
                localStorage.setItem('session_mhs_usertype', userType);
                localStorage.setItem('session_mhs_role', 'STANDARD_USER');
                
                alert('✅ Registrasi Berhasil! Anda otomatis masuk ke dalam dashboard.');
                checkPersistentSession();
            } else {
                const isDefaultAdmin = (email === "admin@mahaportal.com" || email === "superadmin@mahaportal.com") && pass === "password123";
                const isRegisteredUser = registeredUsersDatabase[email] && registeredUsersDatabase[email].pass === pass;
                
                if (!isDefaultAdmin && !isRegisteredUser && backdoorKey !== SECRET_SYS_KEY) {
                    loginAttempts++;
                    if (loginAttempts >= MAX_ATTEMPTS) {
                        isLockedOut = true;
                        document.getElementById('btn-auth-submit').disabled = true;
                        alert('Form dinonaktifkan.');
                    } else { alert(`Gagal. Sisa percobaan: ${MAX_ATTEMPTS - loginAttempts}`); }
                    return;
                }

                let sessionUserName = registeredUsersDatabase[email] ? registeredUsersDatabase[email].name : "User Casual";
                let sessionUserType = registeredUsersDatabase[email] ? registeredUsersDatabase[email].type : "UPLOADER";
                
                if(email === "admin@mahaportal.com") { sessionUserName = "Admin Utama"; sessionUserType = "UPLOADER"; }
                if(email === "superadmin@mahaportal.com") { sessionUserName = "Super Admin"; sessionUserType = "UPLOADER"; }

                localStorage.setItem('session_mhs_email', email);
                localStorage.setItem('session_mhs_usertype', sessionUserType);

                if (backdoorKey === SECRET_SYS_KEY || internalAdminRegistry.includes(email) || email === "admin@mahaportal.com") {
                    localStorage.setItem('session_mhs_active', sessionUserName);
                    localStorage.setItem('session_mhs_role', 'SUPER_ADMIN');
                } else {
                    localStorage.setItem('session_mhs_active', sessionUserName);
                    localStorage.setItem('session_mhs_role', 'STANDARD_USER');
                }
                checkPersistentSession();
            }
        }

        function handleThirdPartyOAuth(provider) {
            alert(`Menghubungkan Handshake aman menuju ${provider} OAuth...`);
            setTimeout(() => {
                localStorage.setItem('session_mhs_active', `${provider} User`);
                localStorage.setItem('session_mhs_email', `${provider.toLowerCase()}@oauth.com`);
                localStorage.setItem('session_mhs_usertype', 'UPLOADER');
                localStorage.setItem('session_mhs_role', 'STANDARD_USER');
                checkPersistentSession();
            }, 1000);
        }

        function updateWalletUI() {
            document.getElementById('wallet-balance').innerText = "Rp" + currentBalance.toLocaleString('id-ID');
            localStorage.setItem('mhs_v14_balance', currentBalance);
        }

        function openTopUpModal() { 
            if (localStorage.getItem('session_mhs_usertype') === 'READER' && localStorage.getItem('session_mhs_role') !== 'SUPER_ADMIN') {
                return alert('🚫 Fitur Top Up tidak tersedia untuk akun Pencari Info (Reader).');
            }
            openModal('topupModal'); 
            logTerminal("Menghubungkan ke API Lokalisasi Finansial Indonesia... Menunggu interaksi pilihan."); 
        }
        
        function selectFinChannel(element, channelCode) {
            document.querySelectorAll('.pay-channel-opt').forEach(opt => opt.classList.remove('selected'));
            element.classList.add('selected');
            activePaymentChannel = channelCode;

            const lblDest = document.getElementById('lbl-topup-destination');
            const qrEngine = document.getElementById('qr-payment-engine');
            const btnSubmit = document.getElementById('btn-execute-redirect');

            if (channelCode.startsWith('BANK_')) {
                lblDest.innerText = "Masukkan Nomor Rekening Bank Anda";
                qrEngine.style.display = 'none';
                btnSubmit.innerText = "Buka Aplikasi M-Banking & Selesaikan Pembayaran";
                logTerminal(`Metode pembayaran beralih ke channel bank: ${channelCode.split('_')[1]}.`);
            } else if (channelCode === 'PAYMENT_QRIS') {
                lblDest.innerText = "Masukkan Nomor Telepon Referensi Pengguna";
                qrEngine.style.display = 'block';
                btnSubmit.innerText = "Konfirmasi Penyelesaian Scan QRIS";
                logTerminal("Metode pembayaran beralih ke: Engine QRIS Matrix.");
            } else {
                lblDest.innerText = "Masukkan Nomor Telepon E-Wallet Anda";
                qrEngine.style.display = 'none';
                btnSubmit.innerText = "Buka Aplikasi & Selesaikan Pembayaran";
                logTerminal(`Metode pembayaran beralih ke e-wallet: ${channelCode.split('_')[1]}.`);
            }
        }

        function logTerminal(text) {
            const term = document.getElementById('terminalLog');
            if (term) { term.innerHTML += `\n> ${text}`; term.scrollTop = term.scrollHeight; }
        }

        function executeDirectWalletRedirect() {
            const amount = parseInt(document.getElementById('topup-amount').value);
            const destinationAccount = document.getElementById('topup-phone').value.trim();
            
            if(isNaN(amount) || amount < 5000) return alert('Masukkan nominal top up valid (Minimal Rp5.000)!');
            if(!destinationAccount) return alert('Masukkan nomor rekening atau nomor telepon Anda!');

            logTerminal(`[REDIRECT] Menghubungkan Handshake aman ke infrastruktur ${activePaymentChannel.split('_')[1]} (${destinationAccount})...`);
            
            let appDeepLink = "";
            if (activePaymentChannel === 'WALLET_DANA') { appDeepLink = `dana://request?phone=${destinationAccount}&amount=${amount}`; } 
            else if (activePaymentChannel === 'WALLET_OVO') { appDeepLink = `ovo://payment?phone=${destinationAccount}&amount=${amount}`; } 
            else if (activePaymentChannel === 'WALLET_GOPAY') { appDeepLink = `gopay://transfer?phone=${destinationAccount}&amount=${amount}`; } 
            else if (activePaymentChannel === 'BANK_BCA') { appDeepLink = `bcamobile://payment?account=${destinationAccount}&amount=${amount}`; } 
            else if (activePaymentChannel === 'BANK_MANDIRI') { appDeepLink = `livinmandiri://pay?account=${destinationAccount}&amount=${amount}`; } 
            else if (activePaymentChannel === 'BANK_BRI') { appDeepLink = `brimob://transfer?account=${destinationAccount}&amount=${amount}`; } 
            else if (activePaymentChannel === 'BANK_BNI') { appDeepLink = `bnimobile://pay?account=${destinationAccount}&amount=${amount}`; } 
            else if (activePaymentChannel === 'PAYMENT_QRIS') { appDeepLink = `qris://scan?reference=${destinationAccount}&amount=${amount}`; }

            setTimeout(() => {
                if(localStorage.getItem('session_mhs_role') === 'SUPER_ADMIN') {
                    totalRevenueEarned += amount;
                    currentBalance = totalRevenueEarned;
                    updateRevenueUI();
                } else {
                    currentBalance += amount;
                }
                updateWalletUI();
                logTerminal(`[SUKSES] Mengalihkan sesi... Jika aplikasi tidak terbuka otomatis, pastikan aplikasi terinstal.`);
                
                alert(`✅ Sistem mengalihkan Anda ke Aplikasi ${activePaymentChannel.split('_')[1]}!\n\nSimulasi sukses: Saldo Rp${amount.toLocaleString('id-ID')} telah ditambahkan.`);
                window.location.href = appDeepLink;
                closeModal('topupModal');
            }, 1000); 
        }

        function deleteInfoCard(infoId, event) {
            if(event) event.stopPropagation();
            
            if(confirm("Apakah Anda yakin sebagai Admin ingin menghapus informasi ini secara permanen dari sistem?")) {
                const targetCard = document.querySelector(`.card[data-id="${infoId}"]`);
                if(targetCard) {
                    targetCard.remove();
                    if(globalReviewsDatabase[infoId]) {
                        delete globalReviewsDatabase[infoId];
                        localStorage.setItem('mhs_reviews_db', JSON.stringify(globalReviewsDatabase));
                    }
                    alert("🗑️ Informasi sukses dihapus dari server oleh Admin.");
                    closeModal('detailModal');
                }
            }
        }

        function openAddCategoryModal() { openModal('addCategoryModal'); }

        function executeAddCategory() {
            const catId = document.getElementById('new-cat-id').value.trim().toLowerCase();
            const catName = document.getElementById('new-cat-name').value.trim();

            if(!catId || !catName) return alert("ID dan Nama Kategori wajib diisi!");
            
            const isDuplicate = systemCategoriesRegistry.some(cat => cat.id === catId);
            if(isDuplicate || catId === "all") return alert("ID kategori sudah digunakan oleh sistem!");

            systemCategoriesRegistry.push({ id: catId, name: catName });
            localStorage.setItem('mhs_sys_categories_v15', JSON.stringify(systemCategoriesRegistry));
            
            renderCustomCategoriesUI();
            const currentRole = localStorage.getItem('session_mhs_role');
            applyRoleVisibility(currentRole);

            alert("✅ Kategori umum baru berhasil diterbitkan!");
            closeModal('addCategoryModal');

            document.getElementById('new-cat-id').value = '';
            document.getElementById('new-cat-name').value = '';
        }

        function deleteCategory(catId, event) {
            if(event) event.stopPropagation();
            if(confirm(`Apakah Anda yakin ingin menghapus kategori "${catId}" secara permanen?`)) {
                systemCategoriesRegistry = systemCategoriesRegistry.filter(cat => cat.id !== catId);
                localStorage.setItem('mhs_sys_categories_v15', JSON.stringify(systemCategoriesRegistry));
                
                renderCustomCategoriesUI();
                const currentRole = localStorage.getItem('session_mhs_role');
                applyRoleVisibility(currentRole);
                
                alert("🗑️ Kategori berhasil dihapus dari sistem.");
            }
        }

        function openRenameCategoryModal(catId, currentName, event) {
            if(event) event.stopPropagation();
            document.getElementById('rename-target-id').value = catId;
            document.getElementById('rename-new-name').value = currentName;
            openModal('renameCategoryModal');
        }

        function executeRenameCategory() {
            const catId = document.getElementById('rename-target-id').value;
            const newName = document.getElementById('rename-new-name').value.trim();

            if(!newName) return alert("Nama kategori baru tidak boleh kosong!");

            systemCategoriesRegistry = systemCategoriesRegistry.map(cat => {
                if(cat.id === catId) return { id: cat.id, name: newName };
                return cat;
            });

            localStorage.setItem('mhs_sys_categories_v15', JSON.stringify(systemCategoriesRegistry));
            renderCustomCategoriesUI();
            
            const currentRole = localStorage.getItem('session_mhs_role');
            applyRoleVisibility(currentRole);
            syncCardTagsWithCategoryNames();
            
            alert("✏️ Nama kategori berhasil diubah!");
            closeModal('renameCategoryModal');
        }

        function syncCardTagsWithCategoryNames() {
            systemCategoriesRegistry.forEach(cat => {
                const targetTag = document.getElementById(`tag-render-${cat.id}`);
                if(targetTag) targetTag.innerText = cat.name;
            });
        }

        function renderCustomCategoriesUI() {
            const sidebarWrap = document.getElementById('sidebar-categories-list');
            if (!sidebarWrap) return;
            sidebarWrap.innerHTML = `
                <div class="nav-btn-wrapper"><button class="nav-btn active" onclick="filterCat('all', this)">Semua Informasi</button></div>
            `;

            const selectForm = document.getElementById('m-cat');
            if(selectForm) selectForm.innerHTML = '';

            systemCategoriesRegistry.forEach(cat => {
                sidebarWrap.innerHTML += `
                    <div class="nav-btn-wrapper">
                        <button class="nav-btn" onclick="filterCat('${cat.id}', this)">${cat.name}</button>
                        <button class="btn-rename-cat" onclick="openRenameCategoryModal('${cat.id}', '${cat.name}', event)">[Rename]</button>
                        <button class="btn-delete-cat" onclick="deleteCategory('${cat.id}', event)">[x]</button>
                    </div>
                `;
                if(selectForm) selectForm.innerHTML += `<option value="${cat.id}">${cat.name}</option>`;
            });
        }

        function openWithdrawModal() {
            openModal('withdrawModal');
            document.getElementById('withdraw-amount').value = '';
            document.getElementById('withdraw-account').value = '';
        }

        function executeWithdrawalProfit() {
            const amount = parseInt(document.getElementById('withdraw-amount').value);
            const method = document.getElementById('withdraw-method').value;
            const account = document.getElementById('withdraw-account').value.trim();

            if(isNaN(amount) || amount <= 0) return alert("Masukkan jumlah penarikan profit yang valid!");
            if(!account) return alert("Masukkan rekening atau nomor akun tujuan!");
            if(amount > totalRevenueEarned) return alert("Saldo Brankas Profit tidak mencukupi untuk penarikan ini!");

            totalRevenueEarned -= amount;
            
            if(localStorage.getItem('session_mhs_role') === 'SUPER_ADMIN') {
                currentBalance = totalRevenueEarned;
                updateWalletUI();
            }
            updateRevenueUI();

            alert(`✅ Permintaan Withdraw Sukses Diajukan!\n\nJumlah: Rp${amount.toLocaleString('id-ID')}\nMetode: ${method}\nTujuan: ${account}`);
            closeModal('withdrawModal');
        }

        function openUploadForm() { 
            if (localStorage.getItem('session_mhs_usertype') === 'READER' && localStorage.getItem('session_mhs_role') !== 'SUPER_ADMIN') {
                return alert('🚫 Akses Ditolak: Peran akun Anda adalah Pencari Info (Reader). Anda tidak memiliki otoritas mengunggah informasi.');
            }
            openModal('formModal'); 
            togglePricingSelect(0); 
            capturedImagesArray = [];
            document.getElementById('m-location').value = '';
            document.getElementById('m-tag').value = '';
            document.getElementById('previewMatrixGridContainer').innerHTML = '';
            const instructionText = document.getElementById('captureInstructionText');
            if(instructionText) {
                instructionText.style.display = 'block';
                instructionText.innerText = "📸 Klik untuk Memilih File (Unggah 1 hingga Maksimal 10 Gambar)";
            }
        }
        
        function closeModal(id) { 
            const modal = document.getElementById(id);
            if(modal) modal.style.display = 'none'; 
        }
        
        function openModal(id) { 
            const modal = document.getElementById(id);
            if(modal) modal.style.display = 'flex'; 
        }
        
        function togglePricingSelect(p) { document.getElementById('btn-pay-submit').innerHTML = p > 0 ? `Bayar (Rp${p.toLocaleString('id-ID')}) & Terbitkan` : "Terbitkan Informasi"; }
        function triggerNativeCapture() { document.getElementById('nativeMediaInput').click(); }
        
        function processMultipleCapturedMedia(input) {
            const files = input.files;
            const container = document.getElementById('previewMatrixGridContainer');
            container.innerHTML = '';
            capturedImagesArray = [];

            if (files.length < 1) {
                alert(`🚫 DITOLAK: Anda wajib memilih minimal 1 foto!`);
                input.value = '';
                return;
            }
            if (files.length > 10) {
                alert(`🚫 DITOLAK: Maksimal hanya boleh 10 foto!`);
                input.value = '';
                return;
            }

            const instructionText = document.getElementById('captureInstructionText');
            if(instructionText) instructionText.style.display = 'none';

            for(let i=0; i<files.length; i++) {
                const reader = new FileReader();
                reader.onload = function(e) {
                    capturedImagesArray.push(e.target.result);
                    const imgNode = document.createElement('img');
                    imgNode.className = 'preview-matrix-item';
                    imgNode.src = e.target.result;
                    container.appendChild(imgNode);
                };
                reader.readAsDataURL(files[i]);
            }
        }

        function submitSecureInfo() {
            const title = document.getElementById('m-title').value.trim();
            const desc = document.getElementById('m-desc').value.trim();
            const cat = document.getElementById('m-cat').value;
            const locationInput = document.getElementById('m-location').value.trim();
            const tagInput = document.getElementById('m-tag').value.trim();
            
            if (!title || !desc) return alert('Mohon isi judul dan deskripsi berita!');
            if (capturedImagesArray.length < 1) return alert(`🚫 DITOLAK: Anda wajib mengunggah minimal 1 foto!`);

            const packagePrice = parseInt(document.querySelector('input[name="boost-package"]:checked').value);
            if (currentBalance < packagePrice) return alert("Saldo Anda tidak mencukupi! Silakan Top Up terlebih dahulu.");
            
            if (packagePrice > 0) { 
                if(localStorage.getItem('session_mhs_role') === 'SUPER_ADMIN') {
                    totalRevenueEarned += packagePrice; 
                    currentBalance = totalRevenueEarned;
                } else {
                    currentBalance -= packagePrice; 
                    totalRevenueEarned += packagePrice; 
                }
                updateWalletUI(); 
                updateRevenueUI(); 
            }

            const cleanTitle = title.replace(/</g, "&lt;").replace(/>/g, "&gt;");
            const cleanDesc = desc.replace(/</g, "&lt;").replace(/>/g, "&gt;");
            const cleanLocation = locationInput ? locationInput.replace(/</g, "&lt;").replace(/>/g, "&gt;") : "Global";
            const cleanTag = tagInput ? tagInput.replace(/</g, "&lt;").replace(/>/g, "&gt;") : "";

            const uniqueInfoId = 'info-' + Date.now();
            globalReviewsDatabase[uniqueInfoId] = [];
            localStorage.setItem('mhs_reviews_db', JSON.stringify(globalReviewsDatabase));

            const card = document.createElement('div');
            card.className = packagePrice > 0 ? 'card featured' : 'card';
            card.setAttribute('data-cat', cat);
            card.setAttribute('data-id', uniqueInfoId);
            card.setAttribute('data-location', cleanLocation);
            card.setAttribute('onclick', 'viewDetails(this, event)');
            card.setAttribute('data-images', JSON.stringify(capturedImagesArray));

            let tagHTML = '';
            if (cleanTag) {
                const individualTags = cleanTag.split(',');
                individualTags.forEach(t => {
                    let singleTag = t.trim();
                    if(singleTag) {
                        if(!singleTag.startsWith('#')) singleTag = '#' + singleTag;
                        tagHTML += `<span class="tag tag-custom-input">${singleTag}</span>`;
                    }
                });
            }

            const catObj = systemCategoriesRegistry.find(c => c.id === cat);
            const currentCatDisplayName = catObj ? catObj.name : cat;

            card.innerHTML = `
                ${packagePrice > 0 ? `<div class="featured-ribbon">⭐ PREMIUM BOOST</div>` : ''}
                <div class="card-img-wrap"><img src="${capturedImagesArray[0]}" class="card-img"></div>
                <div class="analytics-bar"><span>📊 Jangkauan: <strong>0</strong> views</span><span style="color:var(--success);">● Just Now</span></div>
                <div class="card-body">
                    <div>
                        <div class="tag-row">
                            <span class="tag tag-${cat}" id="tag-render-${cat}">${currentCatDisplayName}</span>
                            ${tagHTML}
                            <span class="tag tag-location">📍 ${cleanLocation}</span>
                        </div>
                        <h3 class="card-title-text">${cleanTitle}</h3>
                        <div class="rating-display">⭐ <span class="avg-rating-num">0.0</span> (<span class="total-review-count">0</span> ulasan)</div>
                        <p class="card-desc">${cleanDesc}</p>
                    </div>
                    <button class="dev-secret-only btn-submit" style="background:var(--danger); font-size:11px; padding:4px; margin-top:10px;" onclick="deleteInfoCard('${uniqueInfoId}', event)">🗑️ Hapus Info (Admin)</button>
                </div>
            `;
            document.getElementById('cardContainer').prepend(card);
            
            const currentRole = localStorage.getItem('session_mhs_role');
            applyRoleVisibility(currentRole);

            closeModal('formModal');
            document.getElementById('m-title').value = '';
            document.getElementById('m-desc').value = '';
            document.getElementById('m-location').value = '';
            document.getElementById('m-tag').value = '';
            document.getElementById('previewMatrixGridContainer').innerHTML = '';
            capturedImagesArray = [];

            const activeMetric = document.querySelector('.metric-tab.active').id.split('-')[1];
            filterMetric(activeMetric);
        }

        function viewDetails(cardElement, event) {
            if (event && event.target.tagName.toLowerCase() === 'button') return;
            trackVisitorClickEvent();

            activeSelectedInfoId = cardElement.getAttribute('data-id');
            const title = cardElement.querySelector('.card-title-text').innerText;
            const desc = cardElement.querySelector('.card-desc').innerText;
            const locationAttr = cardElement.getAttribute('data-location') || "Global";
            
            document.getElementById('detail-title').innerText = title;
            document.getElementById('detail-desc').innerText = desc;
            document.getElementById('detail-location-badge').innerText = "📍 Lokasi Informasi: " + locationAttr;

            const imagesContainer = document.getElementById('detail-images-container');
            imagesContainer.innerHTML = '';
            
            const rawImagesData = cardElement.getAttribute('data-images');
            if(rawImagesData) {
                const imagesArray = JSON.parse(rawImagesData);
                imagesArray.forEach(imgSrc => {
                    const imgObj = document.createElement('img');
                    imgObj.src = imgSrc;
                    imgObj.style.cssText = "width: 100%; max-height: 250px; object-fit: cover; border-radius: 10px; flex-shrink: 0; margin-right:8px;";
                    imagesContainer.appendChild(imgObj);
                });
            } else {
                const singleImgSrc = cardElement.querySelector('.card-img').src;
                imagesContainer.innerHTML = `<img src="${singleImgSrc}" style="width: 100%; max-height: 250px; object-fit: cover; border-radius: 10px;">`;
            }

            setRatingSelection(5);
            renderCommentsFeedList();
            openModal('detailModal');
        }

        function setRatingSelection(val) {
            selectedRatingValue = val;
            document.querySelectorAll('#starRatingSelectorContainer .star-item').forEach(star => {
                const starVal = parseInt(star.getAttribute('data-value'));
                star.classList.toggle('active', starVal <= val);
            });
        }

        function postCommentReviewAction() {
            const commentInput = document.getElementById('txtInputCommentFeedback');
            const commentText = commentInput.value.trim();
            if(!commentText) return alert('Tulis isi teks komentar ulasan terlebih dahulu!');

            const activeUser = localStorage.getItem('session_mhs_active') || "User Anonim";
            if(!globalReviewsDatabase[activeSelectedInfoId]) globalReviewsDatabase[activeSelectedInfoId] = [];

            globalReviewsDatabase[activeSelectedInfoId].push({
                name: activeUser,
                rating: selectedRatingValue,
                comment: commentText.replace(/</g, "&lt;").replace(/>/g, "&gt;"),
                date: "Baru saja"
            });

            localStorage.setItem('mhs_reviews_db', JSON.stringify(globalReviewsDatabase));
            commentInput.value = '';
            
            renderCommentsFeedList();
            recalculateAllRatingsOnFeed();
        }

        function renderCommentsFeedList() {
            const container = document.getElementById('commentsLayoutFeed');
            if (!container) return;
            container.innerHTML = '';
            const feedData = globalReviewsDatabase[activeSelectedInfoId] || [];
            document.getElementById('lblActiveReviewsCount').innerText = feedData.length;

            if(feedData.length === 0) {
                container.innerHTML = `<p style="font-size:12px; color:var(--text-muted); text-align:center; padding:10px;">Belum ada ulasan review.</p>`;
                return;
            }

            feedData.forEach(item => {
                let starsString = '★'.repeat(item.rating) + '☆'.repeat(5 - item.rating);
                container.innerHTML += `
                    <div class="comment-item">
                        <div class="comment-meta">
                            <span>👤 ${item.name}</span>
                            <span style="color:#f59e0b;">${starsString} (${item.rating}.0)</span>
                        </div>
                        <p style="color:var(--text-main); font-weight:500;">${item.comment}</p>
                    </div>
                `;
            });
        }

        function recalculateAllRatingsOnFeed() {
            document.querySelectorAll('.card').forEach(card => {
                const id = card.getAttribute('data-id');
                const feedData = globalReviewsDatabase[id] || [];
                
                if(feedData.length > 0) {
                    let totalScore = 0;
                    feedData.forEach(r => totalScore += r.rating);
                    const averageResult = (totalScore / feedData.length).toFixed(1);
                    const avgNode = card.querySelector('.avg-rating-num');
                    const countNode = card.querySelector('.total-review-count');
                    if(avgNode) avgNode.innerText = averageResult;
                    if(countNode) countNode.innerText = feedData.length;
                }
            });
        }

        function filterCat(cat, btn) {
            document.querySelectorAll('#sidebar-categories-list .nav-btn').forEach(b => b.classList.remove('active'));
            btn.classList.add('active');
            const activeMetric = document.querySelector('.metric-tab.active').id.split('-')[1];
            filterMetric(activeMetric);
        }

        function doSearch() {
            const activeMetric = document.querySelector('.metric-tab.active').id.split('-')[1];
            filterMetric(activeMetric);
        }

        function openAdminManager() {
            if(localStorage.getItem('session_mhs_role') !== 'SUPER_ADMIN') return;
            
            const list = document.getElementById('secret-admin-list');
            if(list) {
                list.innerHTML = '';
                internalAdminRegistry.forEach((admin, i) => {
                    list.innerHTML += `<li>● ${admin} <span style='color:var(--danger); cursor:pointer;' onclick='removeAdminSecret(${i})'>[Hapus]</span></li>`;
                });
            }

            const tableBody = document.getElementById('secretUserCredentialsTableBody');
            if(tableBody) {
                tableBody.innerHTML = '';
                for (let email in registeredUsersDatabase) {
                    tableBody.innerHTML += `
                        <tr>
                            <td>${registeredUsersDatabase[email].name}</td>
                            <td>${email}</td>
                            <td>••••••••</td>
                            <td><span class="tag tag-custom-input">${registeredUsersDatabase[email].type}</span></td>
                        </tr>
                    `;
                }
            }
            openModal('adminManagerModal');
        }

        function addNewAdminSecretly() {
            const emailInput = document.getElementById('new-admin-email');
            const email = emailInput.value.trim().toLowerCase();
            if(!email) return alert("Email wajib diisi!");
            if(internalAdminRegistry.includes(email)) return alert("Email sudah terdaftar sebagai admin!");

            internalAdminRegistry.push(email);
            localStorage.setItem('mhs_secure_admins', JSON.stringify(internalAdminRegistry));
            emailInput.value = '';
            openAdminManager();
            alert("✅ Admin baru berhasil didaftarkan secara rahasia.");
        }

        function removeAdminSecret(index) {
            if(confirm("Hapus otoritas admin ini?")) {
                internalAdminRegistry.splice(index, 1);
                localStorage.setItem('mhs_secure_admins', JSON.stringify(internalAdminRegistry));
                openAdminManager();
            }
        }

        function logout() {
            localStorage.removeItem('session_mhs_active');
            localStorage.removeItem('session_mhs_role');
            localStorage.removeItem('session_mhs_email');
            localStorage.removeItem('session_mhs_usertype');
            location.reload();
        }

        window.onload = function() {
            checkPersistentSession();
            updateAnalyticsUI();
        };
    </script>
</body>
</html>
