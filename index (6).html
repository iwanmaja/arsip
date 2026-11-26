<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
  <meta name="theme-color" content="#1e40af" />
  <meta name="mobile-web-app-capable" content="yes" />
  <title>ARSIP SKh KEKERABATAN</title>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/mammoth/1.8.0/mammoth.browser.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.18.5/xlsx.full.min.js"></script>
  <style>
    :root {
      --primary: #1e40af;
      --primary-dark: #1e3a8a;
      --primary-light: #3b82f6;
      --success: #059669;
      --danger: #dc2626;
      --warning: #d97706;
      --bg: #f1f5f9;
      --card: #ffffff;
      --text: #1e293b;
      --text-muted: #64748b;
      --border: #e2e8f0;
      --sidebar-w: 260px;
      --rightbar-w: 280px;
      --radius: 12px;
      --shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
      background: var(--bg);
      color: var(--text);
      min-height: 100vh;
      line-height: 1.5;
    }

    /* ========== LOGIN ========== */
    #login-page {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 50%, #60a5fa 100%);
      padding: 20px;
    }

    .login-card {
      background: white;
      border-radius: 20px;
      padding: 40px 32px;
      width: 100%;
      max-width: 400px;
      box-shadow: 0 25px 50px -12px rgb(0 0 0 / 0.25);
    }

    .login-logo { text-align: center; margin-bottom: 28px; }

    .login-logo .icon {
      width: 72px; height: 72px;
      background: linear-gradient(135deg, var(--primary), var(--primary-light));
      border-radius: 18px;
      display: inline-flex; align-items: center; justify-content: center;
      font-size: 36px; margin-bottom: 12px;
      box-shadow: 0 10px 15px -3px rgb(30 64 175 / 0.3);
    }

    .login-logo h1 { font-size: 1.5rem; color: var(--primary-dark); font-weight: 700; }
    .login-logo p { color: var(--text-muted); font-size: 0.9rem; margin-top: 4px; }

    .form-group { margin-bottom: 16px; }
    .form-group label { display: block; font-size: 0.875rem; font-weight: 600; color: var(--text); margin-bottom: 6px; }
    .form-group input, .form-group select, .form-group textarea {
      width: 100%; padding: 11px 14px; border: 2px solid var(--border); border-radius: 10px;
      font-size: 0.95rem; transition: border-color 0.2s; background: #fff; font-family: inherit;
    }
    .form-group input:focus, .form-group select:focus, .form-group textarea:focus {
      outline: none; border-color: var(--primary-light);
    }
    .form-group textarea { resize: vertical; min-height: 80px; }

    .btn {
      display: inline-flex; align-items: center; justify-content: center; gap: 6px;
      padding: 11px 18px; border: none; border-radius: 10px;
      font-size: 0.95rem; font-weight: 600; cursor: pointer; transition: all 0.2s;
    }
    .btn-primary { background: var(--primary); color: white; }
    .btn-primary:hover { background: var(--primary-dark); }
    .btn-primary:active { transform: scale(0.98); }
    .btn-secondary { background: #e2e8f0; color: var(--text); }
    .btn-secondary:hover { background: #cbd5e1; }
    .btn-success { background: var(--success); color: white; }
    .btn-danger { background: var(--danger); color: white; }
    .btn-sm { padding: 7px 12px; font-size: 0.8rem; }
    .btn-block { width: 100%; }

    .error-msg {
      background: #fef2f2; color: var(--danger); padding: 10px 14px;
      border-radius: 8px; font-size: 0.875rem; margin-bottom: 16px; display: none;
    }

    .demo-info {
      margin-top: 24px; padding: 14px; background: #eff6ff; border-radius: 10px;
      font-size: 0.8rem; color: #1e40af; line-height: 1.6;
    }
    .demo-info strong { display: block; margin-bottom: 4px; }

    /* ========== APP LAYOUT ========== */
    #app-page { display: none; min-height: 100vh; flex-direction: column; }

    .navbar {
      background: var(--primary); color: white; padding: 10px 16px;
      display: flex; align-items: center; justify-content: space-between;
      position: sticky; top: 0; z-index: 100; box-shadow: var(--shadow);
    }

    .navbar-left { display: flex; align-items: center; gap: 12px; }

    .navbar-brand {
      display: flex; align-items: center; gap: 8px;
      font-weight: 700; font-size: 1.1rem;
    }

    .btn-menu-toggle {
      display: none; background: rgba(255,255,255,0.15); border: none;
      color: white; width: 36px; height: 36px; border-radius: 8px;
      font-size: 1.2rem; cursor: pointer; align-items: center; justify-content: center;
    }

    .navbar-user { display: flex; align-items: center; gap: 10px; font-size: 0.85rem; }
    .navbar-user .role-badge {
      background: rgba(255,255,255,0.2); padding: 3px 10px; border-radius: 20px; font-size: 0.75rem;
    }
    .btn-logout {
      background: rgba(255,255,255,0.15); border: 1px solid rgba(255,255,255,0.3);
      color: white; padding: 6px 12px; border-radius: 8px; font-size: 0.8rem; cursor: pointer;
    }
    .btn-logout:hover { background: rgba(255,255,255,0.25); }

    /* Body with 3 columns */
    .app-body {
      display: flex; flex: 1; min-height: 0;
    }

    /* ========== LEFT SIDEBAR ========== */
    .sidebar-left {
      width: var(--sidebar-w); background: white; border-right: 1px solid var(--border);
      display: flex; flex-direction: column; flex-shrink: 0;
      overflow-y: auto; max-height: calc(100vh - 52px);
    }

    .sidebar-section { padding: 14px 12px; border-bottom: 1px solid var(--border); }

    .sidebar-section-title {
      font-size: 0.7rem; font-weight: 700; text-transform: uppercase;
      letter-spacing: 0.05em; color: var(--text-muted); margin-bottom: 8px; padding: 0 6px;
    }

    .nav-item {
      display: flex; align-items: center; gap: 10px;
      padding: 9px 12px; border-radius: 8px; cursor: pointer;
      font-size: 0.9rem; font-weight: 500; color: var(--text);
      transition: all 0.15s; border: none; background: none; width: 100%; text-align: left;
    }
    .nav-item:hover { background: #f1f5f9; }
    .nav-item.active { background: #eff6ff; color: var(--primary); font-weight: 600; }
    .nav-item .icon { font-size: 1.1rem; width: 22px; text-align: center; flex-shrink: 0; }

    /* Folder tree */
    .folder-tree { padding: 4px 0; }

    .tree-item {
      display: flex; align-items: center; gap: 6px;
      padding: 7px 10px; border-radius: 6px; cursor: pointer;
      font-size: 0.85rem; color: var(--text); transition: background 0.15s;
      user-select: none;
    }
    .tree-item:hover { background: #f1f5f9; }
    .tree-item.active { background: #eff6ff; color: var(--primary); font-weight: 600; }
    .tree-item .toggle {
      width: 18px; height: 18px; display: flex; align-items: center; justify-content: center;
      font-size: 0.7rem; color: var(--text-muted); flex-shrink: 0;
      transition: transform 0.15s;
    }
    .tree-item .toggle.open { transform: rotate(90deg); }
    .tree-item .toggle.empty { visibility: hidden; }
    .tree-item .fname { flex: 1; overflow: hidden; text-overflow: ellipsis; white-space: nowrap; }
    .tree-children { padding-left: 16px; display: none; }
    .tree-children.open { display: block; }

    /* ========== MAIN CONTENT ========== */
    .main-area {
      flex: 1; display: flex; flex-direction: column; min-width: 0;
      overflow-y: auto; max-height: calc(100vh - 52px);
    }

    .main-content { padding: 16px 20px; flex: 1; }

    /* Nav buttons bar */
    .nav-bar {
      display: flex; align-items: center; gap: 8px; margin-bottom: 14px; flex-wrap: wrap;
    }

    .btn-nav {
      display: inline-flex; align-items: center; gap: 5px;
      padding: 7px 14px; border: 1px solid var(--border); border-radius: 8px;
      background: white; font-size: 0.85rem; font-weight: 500; cursor: pointer;
      color: var(--text); transition: all 0.15s;
    }
    .btn-nav:hover { background: #f1f5f9; border-color: var(--primary-light); color: var(--primary); }
    .btn-nav:disabled { opacity: 0.4; cursor: not-allowed; }

    .toolbar {
      display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 16px; align-items: center;
    }

    .search-box { flex: 1; min-width: 180px; position: relative; }
    .search-box input {
      width: 100%; padding: 9px 12px 9px 36px; border: 2px solid var(--border);
      border-radius: 10px; font-size: 0.9rem; background: white;
    }
    .search-box input:focus { outline: none; border-color: var(--primary-light); }
    .search-box::before {
      content: "🔍"; position: absolute; left: 10px; top: 50%;
      transform: translateY(-50%); font-size: 0.9rem;
    }

    .breadcrumb {
      display: flex; align-items: center; gap: 5px; margin-bottom: 14px;
      font-size: 0.85rem; color: var(--text-muted); flex-wrap: wrap;
    }
    .breadcrumb a { color: var(--primary); text-decoration: none; font-weight: 500; }
    .breadcrumb a:hover { text-decoration: underline; }

    .section-title { font-size: 1rem; font-weight: 700; margin-bottom: 10px; color: var(--text); }

    .grid {
      display: grid; grid-template-columns: repeat(auto-fill, minmax(130px, 1fr));
      gap: 10px; margin-bottom: 24px;
    }

    .item-card {
      background: var(--card); border: 1px solid var(--border); border-radius: var(--radius);
      padding: 14px 10px; text-align: center; cursor: pointer; transition: all 0.2s; position: relative;
    }
    .item-card:hover { border-color: var(--primary-light); box-shadow: var(--shadow); transform: translateY(-2px); }
    .item-card .icon { font-size: 2.2rem; margin-bottom: 6px; }
    .item-card .name { font-size: 0.8rem; font-weight: 600; word-break: break-word; line-height: 1.3; }
    .item-card .meta { font-size: 0.68rem; color: var(--text-muted); margin-top: 3px; }
    .item-card .actions {
      position: absolute; top: 4px; right: 4px; display: none; gap: 3px;
    }
    .item-card:hover .actions { display: flex; }
    .item-card .actions button {
      width: 26px; height: 26px; border: none; border-radius: 6px;
      background: #f1f5f9; cursor: pointer; font-size: 0.75rem;
      display: flex; align-items: center; justify-content: center;
    }
    .item-card .actions button:hover { background: #e2e8f0; }

    .empty-state { text-align: center; padding: 40px 20px; color: var(--text-muted); }
    .empty-state .icon { font-size: 2.8rem; margin-bottom: 10px; opacity: 0.5; }

    .file-list { display: flex; flex-direction: column; gap: 6px; }
    .file-row {
      background: white; border: 1px solid var(--border); border-radius: 10px;
      padding: 10px 12px; display: flex; align-items: center; gap: 10px;
      cursor: pointer; transition: all 0.15s;
    }
    .file-row:hover { border-color: var(--primary-light); background: #f8fafc; }
    .file-row .icon { font-size: 1.5rem; flex-shrink: 0; }
    .file-row .info { flex: 1; min-width: 0; }
    .file-row .info .name { font-weight: 600; font-size: 0.85rem; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
    .file-row .info .path { font-size: 0.72rem; color: var(--text-muted); }
    .file-row .size { font-size: 0.72rem; color: var(--text-muted); flex-shrink: 0; }

    /* ========== RIGHT SIDEBAR ========== */
    .sidebar-right {
      width: var(--rightbar-w); background: white; border-left: 1px solid var(--border);
      display: flex; flex-direction: column; flex-shrink: 0;
      overflow-y: auto; max-height: calc(100vh - 52px); padding: 16px;
    }

    .widget { margin-bottom: 20px; }

    .widget-title {
      font-size: 0.7rem; font-weight: 700; text-transform: uppercase;
      letter-spacing: 0.05em; color: var(--text-muted); margin-bottom: 10px; text-align: center;
    }

    /* Analog Clock */
    .clock-container {
      display: flex; flex-direction: column; align-items: center;
    }

    .analog-clock {
      width: 180px; height: 180px; border-radius: 50%;
      background: linear-gradient(145deg, #ffffff, #f0f4f8);
      border: 6px solid var(--primary);
      position: relative; box-shadow:
        0 0 0 4px #dbeafe,
        inset 0 2px 8px rgba(0,0,0,0.06),
        0 8px 20px rgba(30,64,175,0.15);
    }

    .clock-face {
      width: 100%; height: 100%; position: relative; border-radius: 50%;
    }

    .clock-center {
      position: absolute; top: 50%; left: 50%;
      width: 12px; height: 12px; background: var(--primary);
      border-radius: 50%; transform: translate(-50%, -50%); z-index: 10;
      box-shadow: 0 0 0 3px white, 0 0 0 5px var(--primary-light);
    }

    .hand {
      position: absolute; bottom: 50%; left: 50%;
      transform-origin: bottom center; border-radius: 4px;
      background: var(--text);
    }

    .hand-hour {
      width: 5px; height: 45px; margin-left: -2.5px;
      background: var(--primary-dark);
    }

    .hand-minute {
      width: 3.5px; height: 60px; margin-left: -1.75px;
      background: var(--primary);
    }

    .hand-second {
      width: 2px; height: 68px; margin-left: -1px;
      background: var(--danger);
    }

    .clock-number {
      position: absolute; font-size: 0.75rem; font-weight: 700;
      color: var(--primary-dark); width: 20px; height: 20px;
      text-align: center; line-height: 20px;
    }

    .digital-time {
      margin-top: 12px; font-size: 1.3rem; font-weight: 700;
      color: var(--primary-dark); letter-spacing: 0.05em;
      font-variant-numeric: tabular-nums;
    }

    .digital-date {
      font-size: 0.8rem; color: var(--text-muted); margin-top: 2px;
    }

    /* Calendar */
    .calendar {
      background: #f8fafc; border-radius: 12px; overflow: hidden;
      border: 1px solid var(--border);
    }

    .cal-header {
      background: var(--primary); color: white; padding: 10px 12px;
      display: flex; align-items: center; justify-content: space-between;
    }

    .cal-header .cal-title { font-weight: 700; font-size: 0.9rem; }

    .cal-nav-btn {
      background: rgba(255,255,255,0.2); border: none; color: white;
      width: 28px; height: 28px; border-radius: 6px; cursor: pointer;
      font-size: 0.9rem; display: flex; align-items: center; justify-content: center;
    }
    .cal-nav-btn:hover { background: rgba(255,255,255,0.35); }

    .cal-days-header {
      display: grid; grid-template-columns: repeat(7, 1fr);
      background: #eff6ff; padding: 6px 4px;
    }
    .cal-days-header span {
      text-align: center; font-size: 0.65rem; font-weight: 700;
      color: var(--primary); text-transform: uppercase;
    }

    .cal-grid {
      display: grid; grid-template-columns: repeat(7, 1fr); padding: 4px;
      gap: 1px;
    }

    .cal-day {
      aspect-ratio: 1; display: flex; align-items: center; justify-content: center;
      font-size: 0.75rem; border-radius: 6px; cursor: default;
      color: var(--text);
    }
    .cal-day.other { color: #cbd5e1; }
    .cal-day.today {
      background: var(--primary); color: white; font-weight: 700;
      box-shadow: 0 2px 6px rgba(30,64,175,0.3);
    }
    .cal-day.selected { background: #dbeafe; color: var(--primary); font-weight: 600; }

    /* ========== MODALS ========== */
    .modal-overlay {
      position: fixed; inset: 0; background: rgba(0,0,0,0.5);
      display: none; align-items: center; justify-content: center;
      z-index: 200; padding: 16px;
    }
    .modal-overlay.show { display: flex; }

    .modal {
      background: white; border-radius: 16px; width: 100%; max-width: 480px;
      max-height: 90vh; overflow-y: auto;
      box-shadow: 0 25px 50px -12px rgb(0 0 0 / 0.25);
    }
    .modal-lg { max-width: 600px; }
    .modal-preview { max-width: 900px; }

    .modal-header {
      padding: 16px 20px; border-bottom: 1px solid var(--border);
      display: flex; align-items: center; justify-content: space-between;
    }
    .modal-header h3 { font-size: 1.05rem; font-weight: 700; }
    .modal-close {
      background: none; border: none; font-size: 1.4rem; cursor: pointer;
      color: var(--text-muted); line-height: 1;
    }
    .modal-body { padding: 18px 20px; }
    .modal-footer {
      padding: 12px 20px; border-top: 1px solid var(--border);
      display: flex; gap: 8px; justify-content: flex-end;
    }

    .preview-area {
      min-height: 180px; display: flex; align-items: center; justify-content: center;
      background: #f8fafc; border-radius: 10px; overflow: hidden;
    }
    .preview-area img { max-width: 100%; max-height: 70vh; object-fit: contain; }
    .preview-area iframe { width: 100%; height: 70vh; border: none; }
    .preview-area .no-preview { text-align: center; padding: 40px; color: var(--text-muted); }
    .preview-area .no-preview .icon { font-size: 2.8rem; margin-bottom: 8px; }

    .upload-zone {
      border: 2px dashed var(--border); border-radius: 12px; padding: 28px 16px;
      text-align: center; cursor: pointer; transition: all 0.2s; background: #f8fafc;
    }
    .upload-zone:hover, .upload-zone.dragover { border-color: var(--primary-light); background: #eff6ff; }
    .upload-zone .icon { font-size: 2.2rem; margin-bottom: 6px; }
    .upload-zone p { color: var(--text-muted); font-size: 0.85rem; }
    .upload-zone input { display: none; }

    /* User table */
    .user-table { width: 100%; border-collapse: collapse; font-size: 0.85rem; }
    .user-table th {
      text-align: left; padding: 8px 10px; background: #f1f5f9;
      font-weight: 600; border-bottom: 2px solid var(--border); font-size: 0.75rem;
      text-transform: uppercase; color: var(--text-muted);
    }
    .user-table td { padding: 10px; border-bottom: 1px solid var(--border); }
    .user-table tr:hover td { background: #f8fafc; }
    .badge {
      display: inline-block; padding: 2px 8px; border-radius: 12px;
      font-size: 0.7rem; font-weight: 600;
    }
    .badge-operator { background: #dbeafe; color: #1e40af; }
    .badge-guru { background: #d1fae5; color: #065f46; }

    /* Surat keluar form */
    .surat-preview-box {
      background: #f8fafc; border: 1px solid var(--border); border-radius: 10px;
      padding: 14px; margin-top: 12px; font-size: 0.9rem;
    }
    .surat-preview-box .nomor {
      font-size: 1.2rem; font-weight: 700; color: var(--primary); letter-spacing: 0.03em;
    }

    /* Toast */
    .toast {
      position: fixed; bottom: 24px; left: 50%; transform: translateX(-50%) translateY(100px);
      background: #1e293b; color: white; padding: 12px 24px; border-radius: 10px;
      font-size: 0.9rem; z-index: 300; transition: transform 0.3s; box-shadow: var(--shadow);
    }
    .toast.show { transform: translateX(-50%) translateY(0); }

    /* Overlay for mobile sidebar */
    .sidebar-overlay {
      display: none; position: fixed; inset: 0; background: rgba(0,0,0,0.4); z-index: 90;
    }
    .sidebar-overlay.show { display: block; }

    /* ========== RESPONSIVE ========== */
    @media (max-width: 1024px) {
      .sidebar-right { display: none; }
    }

    @media (max-width: 768px) {
      .btn-menu-toggle { display: flex; }
      .sidebar-left {
        position: fixed; left: 0; top: 52px; bottom: 0; z-index: 95;
        transform: translateX(-100%); transition: transform 0.25s;
        max-height: none;
      }
      .sidebar-left.open { transform: translateX(0); }
      .sidebar-right { display: none; }
      .grid { grid-template-columns: repeat(auto-fill, minmax(110px, 1fr)); gap: 8px; }
      .navbar-user .role-badge { display: none; }
      .main-content { padding: 12px; }
    }
  
    #profile-photo-wrap:hover .edit-overlay { opacity: 1 !important; }
    .docx-content img { max-width: 100%; }
    .excel-content table { border-collapse: collapse; width: 100%; font-size: 0.8rem; }
  </style>
</head>
<body>

  <!-- ==================== LOGIN ==================== -->
  <div id="login-page">
    <div class="login-card">
      <div class="login-logo">
        <div class="logo-wrap" style="width:140px;height:150px;margin:0 auto 16px;background:transparent;display:flex;align-items:center;justify-content:center;">
          <img src="data:image/png;base64,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" alt="Logo SKh KEKERABATAN" style="width:100%;height:100%;object-fit:contain;display:block;" />
        </div>
        <h1 style="font-size:1.25rem;color:#1e3a8a;font-weight:800;letter-spacing:0.02em;">ARSIP SKh KEKERABATAN</h1>
        <p style="color:#64748b;font-size:0.82rem;margin-top:6px;">Jl. M. Amir Hamzah, Maja, Lebak – Banten</p>
      </div>
      <div class="error-msg" id="login-error"></div>
      <form id="login-form">
        <div class="form-group">
          <label for="username">Username</label>
          <input type="text" id="username" placeholder="Masukkan username" required autocomplete="username" />
        </div>
        <div class="form-group">
          <label for="password">Password</label>
          <input type="password" id="password" placeholder="Masukkan password" required autocomplete="current-password" />
        </div>
        <button type="submit" class="btn btn-primary btn-block">Masuk</button>
      </form>
      
    </div>
  </div>

  <!-- ==================== APP ==================== -->
  <div id="app-page">
    <nav class="navbar">
      <div class="navbar-left">
        <button class="btn-menu-toggle" onclick="toggleSidebar()" title="Menu">☰</button>
        <div class="navbar-brand">
          <div style="width:40px;height:40px;border-radius:6px;background:white;display:flex;align-items:center;justify-content:center;overflow:hidden;padding:2px;">
            <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFgAAABgCAIAAAAW3iKjAAAlbUlEQVR42s18e1RUR7b+rjqnz+nmLWAUQVFphaAgRKMQmYuaLDGO4iPoGHF0BpwkGk3MuolxEn8Gmbw0JtFojOOIdzSacZSoOC6NrozRGQzo1QAiiNqgPAQUREGg+7yqfn9Uc2iaBsE85tZisZqm+1TVd/b+9rd3VR1EKYX/SCMEKAWOa/8TADCG/1DD/xkICAGMKcdRa1PjrnT5aiHFGDAGSuyI/OIN/aIW0XbbKYBytdCaewit32C/IeYwYX0GFxrB6Z/8Za0D/9JWgLF8tbBlxljb7PHcwaPGg2e9Lt0zHjwLALbZ460zxspXCzXmI7+sdfz8QFACmuYEAQAYD56Vdn/7SeUPc+f96oPcf0m7v/W8UKXNntYOB8KAsR3BX6DRn7WpKqWUUCqVXHqQ+GRjuOeDxCelkkv19xvT/rpl2MT5Quq/hLcsQuq/hk2c/84nSy9eLiatjff/ulb/pKpfh2g/60h/NiA0+7idJuYIAfdhq7hJyzz/WvzuUrSBCKn/MkXNcwkHcYD1Z2o/A1lSAhQAYw2geVc6Wr+BEeGD/sFbDn+5d9f35UNfks2xyMBRq2r2qr32/KD0Y1vSKl9AJh4ADFeyuYtbVy70TZy8bCSvyitTiaWErnzda+4KZPLSL/5/PmpoGnAcCwqOc0jfb4dAGz4Oi4ZgVPVh7KcAYBZORw7Iu1QdbZEnAMDmkmXZ9UMwBlRoh2N5ygeeteX6pTwWreHaevm/CkTbvaLWpqb9G9H6DQyCvLJb85a/Wz70JW3YGN4kajaZUmrAdM+E1c+FfkolkGUsCASJUHAjOulM1g3bY4gSziSqGuKKsoPLtiUvemrN3N+yazLjMoRGoJ86xP5EQBDCfEG7WmibPZ4N97LKf5iWetQSrE19F/UbQiSFEAIII6AUsCajtIHb3566gqoq4vmsm8uTTqwDHvFYpYCAEgTAmUTVKnHXLwSXbdu3eXX00MCWec/8TKaBfxp3wJham6wzxtpmj6crX3ff9+0Huf+KW5Ce5b1O/d1Xmv9Q1SoRCoAwAFBABqSyr/KiWnwnmhftfxo5mQICAECYIqxaJYQQihxfHpsetyB97bY/Sru/NR48i9ZvYCEWOA4oAUr+00BQAgCU4+SrhQ/GBDF1UDpmTuivl7z/70jbgq9oRByx2UCRGATt0AEHPJoZlfH11deSzmStPbTFLJw2iopNExA4WCjCFJBqlTT/oervvvqgaF7srCWfVP6gK47GXekawoAwaNp/zjXa3IGFBsYIa7f9cf3uBuukdDE4RLNKFMAJgvaOgQ421llaA9ifZreaKslPoTwA7Qpx3iSqVknYlzLNXP7Fjm88a8uZG7rv+xaZvH6kmzwqECw6WJuY0xoPnr2s8owUaUQcABCbrTME7G5TQAakqRSrhOexCgA8IjZN4LHKI6JQrhsDxBhj0UAvnQ0u25by1uQ3x8/SB2AIjUCEAOoS+u4bl5aW1vvoQCnHKVcLW58eiXz9PU7mb7j83aIlGbefWsuHjtJsElVVx9EYkMYhSgBrhCcUYwSKzBHEGTkZI6oBJsBRigjFKuUwojpqjC0cgEQUgCgqFzTkbvCvsz/9WFW+/6+Pv1a9NO2VxZKHYoiegBECQgChn9kiKAEADWHdHcTktz/c/Mr63Q22BV/xfAdDQEB5RBTKazICAF7QxgdU37pnAAAmIlhbcPrdPRNWs9eXi0PSal5kgUMjHABwWHM0JUfTAEFAhdksoIzk1R/pJr0BoiMpOLoDihzPBAJDgUFg0wRQKS9oL4wofaz+NADMjMpIOpN10+p/Ycp4ADicnwoAaZUv5E8fx3oI8y/w+eqBQnmN4MynVzJcjJxs0wQWU1SK2+CgQClvEqXyUtOpNWs+msLcBACE9RlCaERvscCPECPR+g2eF6ouq3zcgvTr0WkocrxqlSggphEAqEp4m2SID6xIG7h9sLHuhaDf/vdTy2dGZRzOT7U09VcV/nB+aohb/syojD2NiY6dHK1+1aYJGsHxgRXTBmyaGZXBI0WhfHxghdmtxiYZVKKzKQKEVatkGGSWn/+f9De+Wbvtjx6Hc1k6b4+svQkluOfUqMdIr0v30vd/GbcgXZ630zDIrFol3RBUwmuEjw+syEx4c3nYFgCokvwO56e6+9Aw/4JVz7ySNnC7UVRGhpe6edBXL2V+GPtp2sDtYf4FTGJPG7CJR0p8YMWmyKSj1a+G+RcMNtVrMloetuXyc4MzE940u9VohEdAGeKAMLHZMEIsuM6dG8d/nUNXvs4iK2VY9Exl4J6jYHfCrPNpn72ybmO2+ruvMMaMFBBQA9JUwpvdajhMJpLjswd/erk4ZGR4KQDsaUzUVCipH3W0+tV3Zi3bM2H19cZRh6pemxLw78vFId/hZ49Wv3q5OGR71Zcl9aP+NHr/psgkizzBLJwWBBLYRwGABJ+NJfWjzMLpzPgZLMpQwPbBI0wIITYbihyf5b0ucvJCdeYKuvJ1tH5D0650jeOA0J5g8TCOcECBUePC53+V5b0ORY53kAlUIzyoNG3g9pHhpQtOv2uTDJkJb84YvPm9YxsBwMzlj4y4aJEnJP1zvdmtpuK2DLerAWB03yrHri7WBQEA9BswqJ9gaQ34YMze10ctZld4e+qKrJvLpw3Y9OG3n/3p9h80go2crBJEEdeuOyhhlDEsL02nT7sY70FY7RaIjiioM1csWTyFoeDkDma3mgXeRxgLpFW+AADxwZXfTQk5ePM1llPmlFC4XT26b9Xkx7JnTcoJcctnPbh52HtvbbZHhNLWqEOnYk/eibtYFwT9BsSGoU2RSQBwuXB0cuKOCVmlZ8oHmr1qM+NnMGSNnAwAdvVBCW8S6e0b3LHV2XvW9AqLroHQNCYWdBRiZy1hAcIRBQCggC8mxLBsOsy/oKR+lEWewPxic8myM/larHBh8mPZr0/7ws2DYncAACqxKGSfPMWcnnqwF0ozFNdFHzoV+0HRPDkgIn54A4Pj1UuZE8nxkeGlCT4bS1ujoo6fB5UCj4ycrGOBjUalvtF0dEmvsOgCCFcoXI9OE4NDdBT0MKlSPNhYlxk/Y9SQvIIb0exfr17KPHPNN1Y9/vKIUzPGZXj0owCgWZGqIgAQBNJyHxnbzIFS4BAgHgBAlu0XFz0JADTfRlnnUlNOL5QHx4he3Ln4MQBgkSck+Gw8cX9F0ol1aQO3f4efPVM+0CgqOhYgGEG2CftSWFh9MCbooVjgrjyiexQYO1JALMJbWgOSzmSpEg8ASWeyoo6fzzlz6x3ft0+mJCcn7jD6cNIDrDQDJZTN8KsTi/3Wnfn7PxdzPGgEcwgUgtOPbUk/tgUAeJ4KAim4Ef3UB19lnUtNTtxx9834d9xXSOWlSWeyYk5mA4BHP3rqTioLQEdjzEujr9kkgz1hQxhkG8ZYfv6v6W9884+zn3peqELrNzTvStcwBgouuRM/lBdc2oJKeJsmGJAWH1jBI8KwyLq5nCmFYScXnV/+alrqVgYBVVQOE4RAI1j0JHuPLF5w9SM5IMKiRSERAADxUFI/Ks2SfKLEVxAIxnTtnqVRmady+GdTrqxqvo3cfWha6tb8hb/pW5NtkwyXi0OkB7iowcReu/vQT6Ii0wZuVwmvY0EIwQjk53fNe6PEEQuKscs4gnuLAgKqES4+sCIt4M+rHvuf0zNCcifHmd1qeKT8JvvjNEvynIL4H/78t1FD8hwhAACNYHafPy+alGbeCwC0odjuYqJdZb484hQSIf3YlrUN70FrHQCMJueNPpwsY+kBHjUk72RK8rBTv0urfGHk1zcBIDPhzXdmLTt487UPv/1sZlQGqJTdFQcsqPz8X+e9UZJXdosVMpqYviC0ayAIcYqUjB2dbIFHBFQ6kRx/Z9aymVEZaw9tCXHLz4yfQRGnNTTOKZm6d1MOMwQdAntPiDDyP5mSbObyAWBYX5n9S3qA3782BVrrkibuXHtoS5olOc28N3/hb9LMe7+Y9xEHKkaEw0R6gD360R/+/Lc5BfGWpv637hkSfDYW3Iied+q9D+/8nrmMTRNYktLBLubtjFuQflnlO2DRUXe2kSUlgDC1Num88vycp5wipWMSwSNldf+dq555hWmhPY2JljrPOSVT932WQ3ieKqrL9I8CEIJFT8Jmuyf0jfkJOwDgqxOLF1z9iJkJez85cQeLLACgKu3JpEYwJ2DbfS3lrZgDo86YvWoXeB/58M7vAWBc/1oWUBacfrdDXaMtjgw7+7KuL9rT9raqJ6LU7jDU1sySFlPWeZcoAIBGOFAp6z6t8oX44MoTk4YlnLp+pnzgnIL4Lzee4wTcFQp6gOANMP6Tr3L4Z/OTJkUOyJNlPHHLnhz+WXPfB5Y6T4aC9KC9Uw538Gcdi8k79+Z4z+GRwlI4x7SNVTc6ZKtGI7pTFpyzJufQF/zhjSxpFEIj9Aowb79TGCsV5cRS4nmhKn3X5y5tgQmnwD7KRHJ8ZlQGk88jv75paQ2IbTmw8/1cTuA0mXBd6zcKgDkky6guIA7q7OyQeSIlh38WABxRcJp8hwoKJpoMHv3oyZRkv3VByuNxuriYNmDT0epXbZKBFxxQYD5is/H9hpQPfWnJ4il/O/C99eBRa+4hQ2gEYstcbXIdAMAwKBgAlIpyl90zaljgfeT0jJCZURkhbvkJPhsvF4eUKkGCJeeLeR959KOaTLqZAEMCY6q0Uku5TSB3w/wLmm+jlCur2D97goKOBeOLnRN202rLmVuD9jQmThuwSWmlq3JeAx7xiAAgcMJCUrRhY/LvDuHa2AHZyz0IIVfSQgz06PymSjHw6Dv8LGNHow/38feb02pepFZ1RuObLEY8dAKEYiaiwa3vaHJe9CQff79Zxn4AIJC7SRN3alaEUY+SRYbF80/vmFOxiOW4JfWjPv5+s6WpP4+UPRNW/79+f9FkZEBa+00QBO1O1fzpPgBALCWmmFkMBoeoweAweWFzmDX30OSAsQBAKHKsNaoyl/n0yuVhW/Y0Jk7LtRRVRwAAMnDCzdyd7+eqEt/DCegtIayh4EZ0miVZf0dppRj3roCK3eHt1TbBkiNhU9KZLABIG7j9wpTxz4V+yjy3AznpL+WWrgVVx6V37uJWJxTigyvNwunLxSHXfzdoU2RS0pmstfVL6f3GGY1vMqfoYZUQiXC5cDQAnCjxXbLvjVj1OHtftpHS1qjelVsxkR7gyAF5fxyxj1pVS1P/keGlM6MyLPIEKsHmkmXMkB3XB4TGWuQbztyfUYHuPVgHTJ9IcFBgUB+sqvbPMIkykRwf2T9/9ZTlBTeiQ9zyWZlAqCnc+X6urhF62CxaFAAwgkwIa7C/69bX0X16UWsUYdakHOFmLufOr8p5bcw3ZwGg5T6aSI5nJrypEt6l42NzGBg9u1SW2uxp3MGjdmQUjfkPY4c9jYmXa6MOV6w4nJ964v6Kc7X9GTu4+1DpAe590Rigte6LeR85lep6XYPHRLOiiMfyRvet0iTN0how2FQ/c9BGgxuaGZVhL3PquhuAu7h1csBYa+4hOzsQoodFrFfKAYDxh5+HOwBASzNCiNWOOaxaWgOi/nFuVc5rLLmWsAnu3Xx7tY0lC71qTFbuiV7PQmaselwgdx8ZC1VF2B1eHnEKWpqRgQvsoxyuWJFw6nrU8fNJJ9apFHNYo4AQgKpCUB8cHBTIbjnqSBw6EG1cYSmhcsv86T7QWgeC0JacIB6rBpFYWgOSTqw7c2sQAMQKF0Lc8qnUC79gN3DGuIz8pEnJiTv0/GI0Oc/U9yPAihGhEswYlyHUFGIM2dX2EfJYNYqKriYQxlSxRxDd6rt0DV1KIN9wobFWX2thdkEo8FjlBc3IyVTRgiyb3TyoLPfOLwihJi+IHJDXfBu9f22KQO7OGJfhyB29XphB9gLP6L5VrNpgFBUmKx0WzSgIArQ0A4CvALrtO64D6RaBAQC1RdDpYyY5RVAdDgpIAw5amsOfimblpt6NG0BVkQZ81rlUGfu9NfwbVrNhcUTPL3rrHe4+dPJj2dSq8pgqlOsgK9tcQKgpTF70FLN6Jz/oaBGa5hjEg8u2MYBdLHYJArTWzZqU8+gkB+rnRZOgtY5RGosdF/FY+6YR3PsFO9Fhnd21B1EWMljsFMzh3bkGagscdkaRNORqS8qjbffTCKYUNIJ5nl6qjs7hn02LPBk5II9K9sKEjP0+2P/SpepoaxM8AhazJuWA1EJ4wWUBilCkhwxsDqMc5xgyOgLRFjiIpcRXgPnTfaDuBgiC0zo9alMmrBLdQ6akFASB8AYAAM5ED+enCuTuqmdeUdW2OQAAwNqG96IyT5W2RmFMNdL7Re3Wui54BOkhgzt4tHPIcAKiC77sVN3trUWw1PtSdXTLfcRKdWmW5PNz5wgCIQRrKoT5F8Sqx6G1TiB308x7w/wLCEEPzVx60b9BpPcbu2HKtjRc50tKoJ0v57z/7/rOfPkIHiEI5FJ19Nj9Bwb1E/rWZOfwz+4JfYPlaRgRCsBh8t2yBSX1o0Lc8j36UdICmkt6elQcMAaupjB50VOs1OAkrl3VLAl1pIngsm260H70vUmIEIKW7HtDxn6WOs8ceQwrTEkPsN1ZKHA8YEQiB+QxnUrgp0PBoU0fM4kRBLD9mh0zb9xhXcNBXzIrovcbqWB0pAm23VP27s9ypIemBggBIvSLeR+lmffuCX3jwUuhyYk7VBVET9JyH7XcR8xrDB72qtyP8giWsHS0eaYpg8u2dSAIl8XbdizaaIJYSpSK8uRFTzG55swrvWQxjULkgLx3Zi1LTtzB7rnUjPYeWew5HKW8FXOpOjoqqmBuauyl6mjMoUfe0sWSWqzKTvaEMGYEYU8durRchJAOIaMJo6cuqxzz8fZbLMvg1pd13EPxx+rx0gMsy5jnaWlrVFZW0Zykcc7ujLneZp/2L0pwvU4A0Z0DrbPqYVJKthQTS4nX3BVs3g9b4CEUIaTThD0f72BsiAMNRPesrKKeC0EOEw4TjAhGBGMa3jdvf0YOAIQ/FT1qSJ4pau7bq22jhuRRRRUE0luj4HlKVTh5Jw549HCCMHp2JogOQNC2MibtqCZotQWJoiNNqAQhE19lXt5yH3EC7uG4WRBFBp4xQsGN6AOZ54b1lVWJt+bvf+9dIwBILajlPjJ4QM+xoBQwpq3N6GJdEDJwKkFOCkKxao4EAQgBobTT+QzsCAFCCDBCDmrCGDG2s5pgfHmxLqi0NYoXVUIxbfu//tvxx/4+gpb7aP7SJxkjREUVOI74QOa5uamxKW/FeA5HBTfsZOF4tc6XZT+EYiRCaWuU7N2frWw6+gUSRai7MX+6j69gr1OiNjJEHRt2BM9OE5qmZ19/eHJWcNk2WUHO/KPKckDEoVOx7aEBtRM2+1P/YcEFY9TDYtzlwtFso4Dj1TpfVn+fSnDoVCz0GWxQrZ1tXmisNUaMVSrKsTnMnmK40u9Yr2c7f399Blq/wc/DPcrvhqGhDBk7BlFCkI/3yTtxzbcf7h2UAs9TVUWjhuTNmDFiTtK4P7/r2pnfXm0bNnFecuIOqqg9iSBMubfcRx8UzUMm3tkv2gLnH56cJa9M1WZPg04pRrfbAjDStbZsKX7ixRfhdnVn7xAMNEceo3tH99RAMccJWJX4Bb/dCQAVNmtXn7/+3b6CG9EGD7A2gcHjYdUNipEIG44ukQMieCJTx9tJCTIaabVl/nQfPw/39vp9LzaTIQykXWt35R2aVUIDzHNee7wbo6DQTg3spyeuERVVsPfI4pS3YgpuRAPPd2UXlAIn4Obb6OSdOOTjTYkLRcr8QrYUdy5b92xXHaVI9w4vD3vsMDpLTJ6H69FpWedSuzQKCjwPWedSD2SeY4zYw1iQlVV0IPPce+8abfe1rnyEUMyL6oajS3Lck3gi044GjxAikqL7BV35OrAduV1sHcJd6ax277hWxGKH0zIJIExtNi7InHJ6YVdGwaRUcuKOOUnjGDv0EAj24bdX2zz6UVXtzGD2PScFN6I/KJrHufPUKSOmBIkid+2cc7zouqzYBRBtsYOufF1embpiwoLgsm3EZsMd1TVF2KBa5cExKW/FYFVFBmcz1ofbc1twDKhMXHTjFEv2vSGbYw2qlbq6z9zFrYmTlzXt32iPF7S7o0+4O2HcpqxEpSV50VPc9QtYNDjVfxSCRC/uwKBd816J1TWFY7Bovo26mk/3bU7SuAOZ5/YeWexka0w7cKCmvBWT455k4DSlk1dijJX6xqA+eNSIx+06ytUumZ4BgTFQwoVGYHNY0/6NLO9QtU621bYhOst73d4ji0VPomNBKOZMtLQ16hHMwZEsnGyBUCx6krV7lh4IOyZ6caQzR1KCRQPLL7Srhe3xotvyH+4+OnFsLWT9hidGPD7NXK5VWTiT6FwURJjabDQiLuX0woIb0Y5Y/LSNUkAGntW41latMPh7a1bJxfEYhGQFBZdtWzbztyy/MLANId3uvMXdF1UAgKVr8tXCVWkZplNrXNasaBsWYzdvYnaBDPxPi4JGMDLwHKhpGUsX5K00DDJTm80FNVDCGQXDlWwmH9D6DcL6jJ6UeboFgh0aa6PMUSMeD+qDlfpGjLGLk1cIUZttUOTgBXkr56bG2u5rbMfoT9KYO9jua79ZGru24T0xOIS4RIGpSQ0Fl21LnLyscc972BzGhUZ0T5M9AILVK9ooU7tamPLWZKGmEAShc3qIEFIV/u9PN9ev6Xcg7NgTLz6v78L9kY0XVbYvcfLOvUd+lb17jogkG8bYhctTgoxGrcoyf7rPEyMeR+s3aLOnca7qUb0HAmEgxBAagc1h3cRRjECR8NLoa9HhYcfKDbvniAN+/6exmzelZSztef2mq9Z8G63dszRq999/CPjNXyZIAGBrkhUJK1Lnw3MAAKZTaxInL5OvFtr9mhKdJrvZgd+Do0yEAAL5WpFt9njPC1Xp+798/9+R9gOdunFS8uLIss+nPk4BNTQ9OFZuAIA/nBaluiahppC7uNWav79zaOz8unMzRc3VRi+VB8csjb72cULYgWJ5arByrNyQW1lW1GDKrgnsUN8SRaXCMqdi0f4D3zfPGKvNnua9aI3jmSZKKepCUyFCCHroMi4hGsbWGWO12dPE5LcjJy8sS9iBMWYWx8xhd6LKhjg/0uTxUatNMgBAfHDlCF/r1sJQwZLDqn5OiHQzfwBg50dj+tw8V9t/XP/arxP9/bw87jY1swLky9+UbM0bbhCJ3fApwUYj/9f5+qZ8zwtVyOjB1kEd5+gSDkQIcfqcK8rWACMno3Daf6jJ2CgqKeE3Pv/1iGGfVVqa+pu9anMXeft5uJs+kYLEu5UQqFol7U6V0FgbXLat6p5rKtVGL5W9+0PfIaIbllpJfGDF6fnBd5tbYnY1Vkl+VS+oAPDckfpztf1tkoETSLt2MBqdzMFr0RrUsyNu7c+P6MZmnIwCAExZ5x+flHx9/OcGL5NOQ8wujKKyPQFlFNSM8LWmxw08Vm6YEy70+VTanoCYvWQU1LAHI7BHprA9C8jAUUUzmLhgVBXYRxnha40ZOHRqsLImu3Jn8RD2XT8vj5ePXWHvx+xqtDT1b7eFrs1BX+j/0WTZYQkbhPUZxFKCrU0pb002HV3isJMECAWDSBTKLTzCA0B63MA12ZVTgxWni3zzfLBBtRKbTWtRl4QV756qLI24GmKo2j1VyZhoWzPB/5MnpI8TwtiHYwYOZS+OlRvuNjV/nBCWW1nWb5vB0hrghAJvElFh9sqFvk+MeLw91yTUJQouabHHsgdjIHbF3TLvmTeyzu/sc7L8Thn2CWLOBQgRijACLJIztwYFbZcBhqTHqUYOBYl3pwZ7Hys3TA1WDhSDTTIYRKIBFDWYPp8q5lbCTas/g2xNduULxUO2a/KccOFAMcwJFwDkqcHKc0fqMwrg1r1GS9NwTiAGrOm8oGuHoWXbEl9b3bgrHVlKvOZ+iyg7dOzC2F3aPu4+qDgbBSXMKLSrhfs2r+aOrQZB4E0iNhoxQggoIYQQwmNVIUglKGZX48vHrqyZ4O/nZS82TQ1WzF61+uqDTaNFDSa1WTpWbnB3d48ZODRIvJtbWWbk2se6Jrvy1j3DmfKBN6z+vKAhSgghiBKMABuN2GjkTCJXlK1rB90cHhoE9Kq1PXy2l7AfLvEIYNy4K507eNQj63zapy+v392gjV4KAHJABPLx5nn7lgxCEciyonGgUqOojOtfmzoqAAByK8s+Tgib8rfyM9d8l8bc+nzq4y8fu8K84LcRImMBvbeMgprs6gBN4TmDyptEpu4xooQiVQV6vxFa64TGWu7i1qA++NLJ3dLe97iDR/mvc4wc6gk1OE68XUdQSiWNiBzuDhRCAAG1NeunGQqKrvzjwinaUPzVP+4DQNU9YsfFuz+49QV3D4OJU9UOHhbnfyP33mBZQUvCih2nzWAqajDl3hvMpgoAPA8AoFg1aGlm02aFhqA+GADmT/dBvuHTx0wKDx0uKi0PxgQ57bnvAgDSvskMIeY7rgUVM1y2eZvijtC0GYXdCAFMMbOE0AgAuNvYVF5162TNeelWsw4NQ4fFRccuZO/+neuLnSsrAMDmzKYNAGzmwUGBPt5eHAC1NikV5expb9gcZso6z2kaxVgfsOME2f5gritlySD5oegKAAQHBfoKgAR3p/CrOSyfI0JsFJgd6huzsDlMmz2N4WIYFIyMHhRhSdVaWlrKq24BAAMIHE4wdal2fcMBQAz0YLvCg4MC3d3dDTzHUUJtzWzaANC5d6+5K5DoAZRS3H56iOtsDrbmBhnYqMJDh4s8hxw5oqHpwZbDX54o8WWfTwhrcByKrwDI5OXSdrSrhfrIwGHPGjaHAQBDp32fil5NBkBCh+Vpx73i+mkJl1fujDsxeXFdeYGtWakov6zyAPCPC6fu+E/Iy750sS5odN+qLQuiosPD7Cs7Tq7xQ9GVZXvyL9YFyQERAMDckp1dZnvfdHRG8iqblTNAmsbK545zcJpGT0O22S4oHNF00SMl1NbM4GMT1g2Q3Vf9sLWM/aC1Lla4kPi0vGriAkerdyZLI89Ra9O6s4eO/FPIkcegAWaeB1UFalVBamHQ6C6tH+5u31sOwBzYz9uLAiB2jovNytoEXR+McWrMaojJi0V4R+q2qVrx1Wu6owGAbsUX8VgAkG2kfdOI6A484kQOALSGxlj1eOLT8h+enMWGB5QioJQt9TlZBGXvA3SGA2QZAEAQCAGtoVEgd2Ub6cxwALB2XtmbTy+UNAIARmSnW+a0WMelqwDd9l/iQEkAYKMAACKH84pLYj+td/ldFqo4X2+M20cLAOhO2WhyPiGs4Y8x/yWERmjssm3xgv3mOwtPNgLO5LXqmUVvjm/KK7u1bM++i3VBNHQsIQQkhbt2Tri4FQCG9cHlQ1+yf7/fAPtobASgDAE18pxjmYBzkOrdC/kOLxBiBmyEdinJZIt9K/vtavaOnshFTUn8X5+ZFHEYUXagjT3bjDmU1hY+OE0Dh4DoKnw6EMzJmvOV0hjGLjR0LKEAgLhr5+SACHD3gJZml3bBXCY6LpI9UYUdkWDM0tt2suY8eyHdar7jP+Gx+tMnSnztPu9gCIIRy9iP9xA5k0gvnYV+AzT/oViVldoKobF28SzfgeIFNoDooYHI6OEkt9qzT1tbnNNnXhcQV3FbZgeukA8zNhsgBIC5a+di4wNv3TNUQqDUSpCBY0pJlzAdOMVJLJC7dh/uqCCcZIVgxADAeu/QRHfgEeuxw+cNlEiKImFk4g1XshkQINtAMDJ2YF0DwGhyPjouUsclPHQ4s1xez0n+8r+HjvxTABAu1jUABMmyDfoMRiaeTQ9jAKORKVwKMMLX+skTUsbNKydLvaokPwBQVaQoDikcj4D34DDRCOYw4Y281EoAQAYPw2McIaBJGidy7OIUzFzbQ5CZoKQ8qCpwGDRJ0y+iEQwq5ZAyxFDDjhCljgpIP11fJfmlhNxg3RY1mHKudBgwIcD5ehMCstUdpJYc25iLh2oBhh7pm58Q1hAcFGj09nLxPEtqbcoru+UYe/Two1ugUFOIQ0dvT0AsiVqTXakrZVaJKGowAcCte4YqyS9IvMuQ2p6AcivLAGBr3nBWwvnz5aEAwFIJe5hU+PjgSgBgj0FQCXphZNnJUi8AqJL8xvWvBYCz1QHjB9R8nejPCoIAMIK7mXGTsFLFsXLD4s8u2AV+myTXvVUXR8FBgX4e7l2Gz85ZBhOwjCz0cLV31/eVz/6FDSt1VEBuZVnMwKG5lWWpg3GRNtjJaNkot+YNZ7U8hhr7CksuHP/s6h1W42G4P3ek/tY9w5oJ/k4d5VaWnSz1qoTAJ2r+3ln1uNaEbWLclUUwOAhhKtUlw6/d9bn+QFL2lNLJIU07i4cAQJB4lxktAIzwbd8NwgpN3ZAim/kI7qYTlMyIdLPvbGjsaVfxwZW59wYzwoqp33d2za9dMCIAAXBcg7Of1eom6eqqniNpxMBz7+76/P1/R9rpzUG32K/exmRU0fTXjMwAwHkfZBdNpRghRCjSCGaFPMcrdxieonFI0ZolPZqO7lt1ds2vicnLad2x+zpD7x7RxsBjWaZjHuXEJi7yy7bTjCD2+NRPW9BxDDSOcbqzru3gCN5eQCnq8Tmrn+gJp20pnWdtB7XP4r+TEO5Vc5ykoxgZyasP+gezDeNIcAfcXolhUsDP26tXHT0KEJ0z/M4ZQVdgOWacLo8mt2elGPWwBk0d9LhLF6A9MI2f8inIXV3K6bi0nkd0X0QnDhWQ7ibQieb09OFnt4hfptFO9P6ztv8PdoB97aPoDJEAAAAASUVORK5CYII=" alt="Logo" style="width:100%;height:100%;object-fit:contain;display:block;" />
          </div>
          <span>SKh KEKERABATAN</span>
        </div>
      </div>
      <div class="navbar-user">
        <span id="user-display"></span>
        <span class="role-badge" id="role-badge"></span>
        <button class="btn-logout" onclick="logout()">Keluar</button>
      </div>
    </nav>

    <div class="sidebar-overlay" id="sidebar-overlay" onclick="closeSidebar()"></div>

    <div class="app-body">
      <!-- LEFT SIDEBAR -->
      <aside class="sidebar-left" id="sidebar-left">
        <div class="sidebar-section">
          <div class="sidebar-section-title">Navigasi</div>
          <button class="nav-item" id="nav-home" onclick="goHome()">
            <span class="icon">🏠</span> Menu Utama
          </button>
          <button class="nav-item" onclick="goUp()" id="nav-back">
            <span class="icon">⬅️</span> Kembali
          </button>
        </div>

        <div class="sidebar-section" style="flex:1;">
          <div class="sidebar-section-title">Folder</div>
          <div class="folder-tree" id="folder-tree"></div>
        </div>

        <!-- Admin menus -->
        <div class="sidebar-section" id="admin-menus" style="display:none;">
          <div class="sidebar-section-title">Administrasi</div>
          <button class="nav-item" id="nav-users" onclick="showUserManage()">
            <span class="icon">👥</span> Kelola User
          </button>
          <button class="nav-item" id="nav-surat" onclick="showSuratKeluar()">
            <span class="icon">📝</span> Surat Keluar
          </button>
          <button class="nav-item" id="nav-surat-list" onclick="showSuratList()">
            <span class="icon">📋</span> Daftar Surat
          </button>
          <button class="nav-item" id="nav-surat-setting" onclick="showSuratSetting()">
            <span class="icon">⚙️</span> Format Nomor
          </button>
        </div>
      </aside>

      <!-- MAIN -->
      <div class="main-area">
        <div class="main-content" id="main-content">
          <!-- filled by JS -->
        </div>
      </div>

      <!-- RIGHT SIDEBAR -->
      <aside class="sidebar-right" id="sidebar-right">
        <!-- Profile Photo -->
        <div class="widget" style="text-align:center;">
          <div id="profile-photo-wrap" onclick="editProfilePhoto()" title="Klik untuk ganti foto" style="width:90px;height:90px;border-radius:50%;margin:0 auto 8px;border:3px solid #1e40af;overflow:hidden;position:relative;background:#e2e8f0;cursor:pointer;box-shadow:0 4px 12px rgba(30,64,175,0.2);">
            <div id="profile-photo-display"><div style="width:100%;height:100%;display:flex;align-items:center;justify-content:center;font-size:2.4rem;background:linear-gradient(135deg,#dbeafe,#eff6ff);">👤</div></div>
            <div style="position:absolute;inset:0;background:rgba(0,0,0,0.45);display:flex;align-items:center;justify-content:center;opacity:0;transition:opacity 0.2s;color:white;font-size:0.75rem;font-weight:600;" onmouseover="this.style.opacity=1" onmouseout="this.style.opacity=0" class="edit-overlay">📷 Ganti</div>
          </div>
          <div id="profile-name-display" style="font-weight:700;font-size:0.9rem;"></div>
          <div id="profile-role-display" style="font-size:0.75rem;color:#64748b;"></div>
          <input type="file" id="profile-photo-input" accept="image/*" style="display:none" onchange="handleProfilePhoto(event)" />
        </div>
        <div class="widget">
          <div class="widget-title">Jam</div>
          <div class="clock-container">
            <div class="analog-clock">
              <div class="clock-face" id="clock-face">
                <!-- numbers injected by JS -->
                <div class="hand hand-hour" id="hand-hour"></div>
                <div class="hand hand-minute" id="hand-minute"></div>
                <div class="hand hand-second" id="hand-second"></div>
                <div class="clock-center"></div>
              </div>
            </div>
            <div class="digital-time" id="digital-time">00:00:00</div>
            <div class="digital-date" id="digital-date"></div>
          </div>
        </div>

        <div class="widget">
          <div class="widget-title">Kalender</div>
          <div class="calendar">
            <div class="cal-header">
              <button class="cal-nav-btn" onclick="changeMonth(-1)">‹</button>
              <span class="cal-title" id="cal-title">Nov 2026</span>
              <button class="cal-nav-btn" onclick="changeMonth(1)">›</button>
            </div>
            <div class="cal-days-header">
              <span>Min</span><span>Sen</span><span>Sel</span><span>Rab</span>
              <span>Kam</span><span>Jum</span><span>Sab</span>
            </div>
            <div class="cal-grid" id="cal-grid"></div>
          </div>
        </div>
      </aside>
    </div>
  </div>

  <!-- Modal: New Folder -->
  <div class="modal-overlay" id="modal-folder">
    <div class="modal">
      <div class="modal-header">
        <h3>Buat Folder Baru</h3>
        <button class="modal-close" onclick="closeModal('modal-folder')">&times;</button>
      </div>
      <div class="modal-body">
        <div class="form-group">
          <label for="folder-name">Nama Folder</label>
          <input type="text" id="folder-name" placeholder="Contoh: RPP, Absensi, Laporan..." />
        </div>
      </div>
      <div class="modal-footer">
        <button class="btn btn-secondary btn-sm" onclick="closeModal('modal-folder')">Batal</button>
        <button class="btn btn-primary btn-sm" onclick="createFolder()">Buat</button>
      </div>
    </div>
  </div>

  <!-- Modal: Upload -->
  <div class="modal-overlay" id="modal-upload">
    <div class="modal">
      <div class="modal-header">
        <h3>Unggah File</h3>
        <button class="modal-close" onclick="closeModal('modal-upload')">&times;</button>
      </div>
      <div class="modal-body">
        <div class="upload-zone" id="upload-zone" onclick="document.getElementById('file-input').click()">
          <div class="icon">📄</div>
          <p>Klik atau seret file ke sini<br><small>PDF, DOC, DOCX, XLS, XLSX, JPG, PNG, TXT (max 8 MB)</small></p>
          <input type="file" id="file-input" accept=".pdf,.doc,.docx,.xls,.xlsx,.jpg,.jpeg,.png,.txt,.gif,.webp" multiple onchange="handleFileSelect(event)" />
        </div>
        <div id="upload-list" style="margin-top:12px;"></div>
      </div>
      <div class="modal-footer">
        <button class="btn btn-secondary btn-sm" onclick="closeModal('modal-upload')">Tutup</button>
      </div>
    </div>
  </div>

  <!-- Modal: Preview -->
  <div class="modal-overlay" id="modal-preview">
    <div class="modal modal-preview">
      <div class="modal-header">
        <h3 id="preview-title">Preview</h3>
        <button class="modal-close" onclick="closeModal('modal-preview')">&times;</button>
      </div>
      <div class="modal-body">
        <div class="preview-area" id="preview-area"></div>
      </div>
      <div class="modal-footer">
        <button class="btn btn-secondary btn-sm" onclick="closeModal('modal-preview')">Tutup</button>
        <a id="preview-download" class="btn btn-primary btn-sm" download>⬇️ Unduh</a>
      </div>
    </div>
  </div>

  <!-- Modal: Delete -->
  <div class="modal-overlay" id="modal-delete">
    <div class="modal">
      <div class="modal-header">
        <h3>Hapus Item</h3>
        <button class="modal-close" onclick="closeModal('modal-delete')">&times;</button>
      </div>
      <div class="modal-body">
        <p id="delete-msg">Apakah Anda yakin?</p>
      </div>
      <div class="modal-footer">
        <button class="btn btn-secondary btn-sm" onclick="closeModal('modal-delete')">Batal</button>
        <button class="btn btn-danger btn-sm" id="btn-confirm-delete">Hapus</button>
      </div>
    </div>
  </div>

  <!-- Modal: Add / Edit User -->
  <div class="modal-overlay" id="modal-user">
    <div class="modal">
      <div class="modal-header">
        <h3 id="user-modal-title">Tambah User Baru</h3>
        <button class="modal-close" onclick="closeModal('modal-user')">&times;</button>
      </div>
      <div class="modal-body">
        <div class="form-group">
          <label for="new-username">Username</label>
          <input type="text" id="new-username" placeholder="username (tanpa spasi)" />
        </div>
        <div class="form-group">
          <label for="new-fullname">Nama Lengkap</label>
          <input type="text" id="new-fullname" placeholder="Nama lengkap" />
        </div>
        <div class="form-group">
          <label for="new-password">Password</label>
          <input type="text" id="new-password" placeholder="Password" />
        </div>
        <div class="form-group">
          <label for="new-role">Peran</label>
          <select id="new-role">
            <option value="guru">Guru</option>
            <option value="operator">Operator</option>
          </select>
        </div>
      </div>
      <div class="modal-footer">
        <button class="btn btn-secondary btn-sm" onclick="closeModal('modal-user')">Batal</button>
        <button class="btn btn-primary btn-sm" onclick="saveUser()">Simpan</button>
      </div>
    </div>
  </div>

  <!-- Modal: Surat Keluar (custom) -->
  <div class="modal-overlay" id="modal-surat">
    <div class="modal modal-lg">
      <div class="modal-header">
        <h3>Buat Surat Keluar</h3>
        <button class="modal-close" onclick="closeModal('modal-surat')">&times;</button>
      </div>
      <div class="modal-body">
        <div style="display:flex;gap:10px;">
          <div class="form-group" style="flex:0.35">
            <label for="surat-num">Nomor</label>
            <input type="number" id="surat-num" min="1" placeholder="123" />
          </div>
          <div class="form-group" style="flex:0.65">
            <label for="surat-kode">Kode / Instansi</label>
            <input type="text" id="surat-kode" placeholder="SKh.YK" />
          </div>
        </div>
        <div style="display:flex;gap:10px;">
          <div class="form-group" style="flex:1">
            <label for="surat-bulan">Bulan (Romawi)</label>
            <select id="surat-bulan">
              <option value="I">I – Januari</option><option value="II">II – Februari</option>
              <option value="III">III – Maret</option><option value="IV">IV – April</option>
              <option value="V">V – Mei</option><option value="VI">VI – Juni</option>
              <option value="VII">VII – Juli</option><option value="VIII">VIII – Agustus</option>
              <option value="IX">IX – September</option><option value="X">X – Oktober</option>
              <option value="XI">XI – November</option><option value="XII">XII – Desember</option>
            </select>
          </div>
          <div class="form-group" style="flex:1">
            <label for="surat-tahun">Tahun</label>
            <input type="number" id="surat-tahun" min="2020" max="2099" />
          </div>
        </div>
        <div class="form-group">
          <label>Pratinjau Nomor Surat</label>
          <div class="surat-preview-box">
            <div class="nomor" id="surat-nomor-preview" style="font-family:monospace;">—</div>
            <div style="font-size:0.78rem;color:var(--text-muted);margin-top:4px;" id="surat-nomor-info"></div>
          </div>
        </div>
        <div class="form-group">
          <label for="surat-perihal">Perihal</label>
          <input type="text" id="surat-perihal" placeholder="Perihal surat" />
        </div>
        <div class="form-group">
          <label for="surat-tujuan">Tujuan / Penerima</label>
          <input type="text" id="surat-tujuan" placeholder="Kepada..." />
        </div>
        <div class="form-group">
          <label for="surat-keterangan">Keterangan (opsional)</label>
          <textarea id="surat-keterangan" placeholder="Catatan tambahan..."></textarea>
        </div>
      </div>
      <div class="modal-footer">
        <button class="btn btn-secondary btn-sm" onclick="closeModal('modal-surat')">Batal</button>
        <button class="btn btn-primary btn-sm" onclick="saveSuratKeluar()">Simpan Surat</button>
      </div>
    </div>
  </div>

  <!-- Modal: Format Nomor Setting -->
  <div class="modal-overlay" id="modal-surat-setting">
    <div class="modal">
      <div class="modal-header">
        <h3>Pengaturan Format Nomor Surat</h3>
        <button class="modal-close" onclick="closeModal('modal-surat-setting')">&times;</button>
      </div>
      <div class="modal-body">
        <div class="form-group">
          <label for="cfg-kode">Kode / Instansi Default</label>
          <input type="text" id="cfg-kode" placeholder="SKh.YK" />
          <div style="font-size:0.75rem;color:#64748b;margin-top:4px;">Contoh hasil: 123/SKh.YK/XI/2026</div>
        </div>
        <div class="form-group">
          <label for="cfg-prefix-pad">Panjang nomor (padding nol)</label>
          <select id="cfg-prefix-pad">
            <option value="0">Tanpa nol di depan (123)</option>
            <option value="3">3 digit (001, 123)</option>
            <option value="4">4 digit (0001, 0123)</option>
          </select>
        </div>
        <div class="form-group">
          <label>Contoh format</label>
          <div class="surat-preview-box"><div class="nomor" id="cfg-preview" style="font-family:monospace;">123/SKh.YK/XI/2026</div></div>
        </div>
      </div>
      <div class="modal-footer">
        <button class="btn btn-secondary btn-sm" onclick="closeModal('modal-surat-setting')">Batal</button>
        <button class="btn btn-primary btn-sm" onclick="saveSuratSetting()">Simpan</button>
      </div>
    </div>
  </div>

  <div class="toast" id="toast"></div>

  <script>
    // ==================== DATA ====================
    const DEFAULT_USERS = {
      operator: { password: 'admin123', name: 'Operator Sekolah', role: 'operator', photo: null },
      guru1: { password: 'guru123', name: 'Ibu Siti Aminah', role: 'guru', folderId: 'guru1', photo: null },
      guru2: { password: 'guru123', name: 'Bapak Ahmad Fauzi', role: 'guru', folderId: 'guru2', photo: null },
      guru3: { password: 'guru123', name: 'Ibu Rina Wati', role: 'guru', folderId: 'guru3', photo: null },
    };

    let currentUser = null;
    let currentPath = [];
    let deleteTarget = null;
    let searchQuery = '';
    let currentView = 'files'; // files | users | surat-list
    let calMonth = new Date().getMonth();
    let calYear = new Date().getFullYear();
    let editingUser = null; // username being edited, or null for new

    // ==================== STORAGE ====================
    function loadUsers() {
      const raw = localStorage.getItem('arsip_slb_users');
      if (raw) return JSON.parse(raw);
      localStorage.setItem('arsip_slb_users', JSON.stringify(DEFAULT_USERS));
      return { ...DEFAULT_USERS };
    }

    function saveUsers(users) {
      localStorage.setItem('arsip_slb_users', JSON.stringify(users));
    }

    function loadFS() {
      const raw = localStorage.getItem('arsip_slb_fs');
      if (raw) return JSON.parse(raw);
      const initial = [
        { id: 'root', name: 'Root', type: 'folder', parentId: null, ownerId: 'system', createdAt: Date.now() },
        { id: 'guru1', name: 'Ibu Siti Aminah', type: 'folder', parentId: 'root', ownerId: 'guru1', createdAt: Date.now() },
        { id: 'guru2', name: 'Bapak Ahmad Fauzi', type: 'folder', parentId: 'root', ownerId: 'guru2', createdAt: Date.now() },
        { id: 'guru3', name: 'Ibu Rina Wati', type: 'folder', parentId: 'root', ownerId: 'guru3', createdAt: Date.now() },
        { id: 'g1_rpp', name: 'RPP', type: 'folder', parentId: 'guru1', ownerId: 'guru1', createdAt: Date.now() },
        { id: 'g1_absensi', name: 'Absensi', type: 'folder', parentId: 'guru1', ownerId: 'guru1', createdAt: Date.now() },
        { id: 'g2_rpp', name: 'RPP', type: 'folder', parentId: 'guru2', ownerId: 'guru2', createdAt: Date.now() },
        { id: 'g3_laporan', name: 'Laporan', type: 'folder', parentId: 'guru3', ownerId: 'guru3', createdAt: Date.now() },
      ];
      saveFS(initial);
      return initial;
    }

    function saveFS(fs) { localStorage.setItem('arsip_slb_fs', JSON.stringify(fs)); }
    function getFS() { return loadFS(); }

    function loadSurat() {
      const raw = localStorage.getItem('arsip_slb_surat');
      return raw ? JSON.parse(raw) : [];
    }

    function saveSurat(list) {
      localStorage.setItem('arsip_slb_surat', JSON.stringify(list));
    }

    function getNextSuratNumber() {
      const list = loadSurat();
      const year = new Date().getFullYear();
      const thisYear = list.filter(s => s.year === year);
      const lastNum = thisYear.length > 0 ? Math.max(...thisYear.map(s => s.number)) : 0;
      return { number: lastNum + 1, year, lastNum };
    }

    function loadSuratCfg() {
      const raw = localStorage.getItem('arsip_slb_surat_cfg');
      return raw ? JSON.parse(raw) : { kode: 'SKh.YK', pad: 0 };
    }
    function saveSuratCfg(cfg) { localStorage.setItem('arsip_slb_surat_cfg', JSON.stringify(cfg)); }

    function formatNomorSurat(num, kode, bulan, year, pad) {
      let n = String(num);
      if (pad > 0) n = n.padStart(pad, '0');
      return n + '/' + kode + '/' + bulan + '/' + year;
    }

    function getSuggestedNumber() {
      const list = loadSurat();
      const year = new Date().getFullYear();
      const thisYear = list.filter(s => s.year === year);
      if (thisYear.length === 0) return 1;
      return Math.max(...thisYear.map(s => s.number)) + 1;
    }

    function uid() {
      return 'id_' + Date.now() + '_' + Math.random().toString(36).slice(2, 8);
    }

    // ==================== AUTH ====================
    function login(e) {
      e.preventDefault();
      const username = document.getElementById('username').value.trim().toLowerCase();
      const password = document.getElementById('password').value;
      const errorEl = document.getElementById('login-error');
      const users = loadUsers();
      const user = users[username];
      if (!user || user.password !== password) {
        errorEl.textContent = 'Username atau password salah!';
        errorEl.style.display = 'block';
        return;
      }
      currentUser = { username, ...user };
      sessionStorage.setItem('arsip_user', JSON.stringify(currentUser));
      showApp();
    }

    function logout() {
      currentUser = null;
      currentPath = [];
      currentView = 'files';
      sessionStorage.removeItem('arsip_user');
      document.getElementById('app-page').style.display = 'none';
      document.getElementById('login-page').style.display = 'flex';
      document.getElementById('username').value = '';
      document.getElementById('password').value = '';
      document.getElementById('login-error').style.display = 'none';
    }

    function checkSession() {
      const raw = sessionStorage.getItem('arsip_user');
      if (raw) {
        currentUser = JSON.parse(raw);
        // Refresh user data from storage (in case password/name changed)
        const users = loadUsers();
        if (users[currentUser.username]) {
          currentUser = { username: currentUser.username, ...users[currentUser.username] };
          sessionStorage.setItem('arsip_user', JSON.stringify(currentUser));
        }
        showApp();
      }
    }

    function showApp() {
      document.getElementById('login-page').style.display = 'none';
      document.getElementById('app-page').style.display = 'flex';
      document.getElementById('user-display').textContent = currentUser.name;
      document.getElementById('role-badge').textContent = currentUser.role === 'operator' ? 'Operator' : 'Guru';
      document.getElementById('admin-menus').style.display = currentUser.role === 'operator' ? 'block' : 'none';
      updateProfileDisplay();

      if (currentUser.role === 'operator') {
        currentPath = ['root'];
      } else {
        currentPath = [currentUser.folderId];
      }
      currentView = 'files';
      renderFolderTree();
      render();
      startClock();
      renderCalendar();
    }

    
    // ==================== PROFILE PHOTO ====================
    function updateProfileDisplay() {
      const users = loadUsers();
      const u = users[currentUser.username] || currentUser;
      currentUser.photo = u.photo || null;
      currentUser.name = u.name;
      const nameEl = document.getElementById('profile-name-display');
      const roleEl = document.getElementById('profile-role-display');
      if (nameEl) nameEl.textContent = currentUser.name;
      if (roleEl) roleEl.textContent = currentUser.role === 'operator' ? 'Operator / Administrator' : 'Guru';
      const el = document.getElementById('profile-photo-display');
      if (!el) return;
      if (currentUser.photo) {
        el.innerHTML = '<img src="' + currentUser.photo + '" alt="Foto" style="width:100%;height:100%;object-fit:cover;" />';
      } else {
        el.innerHTML = '<div style="width:100%;height:100%;display:flex;align-items:center;justify-content:center;font-size:2.4rem;background:linear-gradient(135deg,#dbeafe,#eff6ff);">👤</div>';
      }
    }

    function editProfilePhoto() {
      document.getElementById('profile-photo-input').click();
    }

    function handleProfilePhoto(e) {
      const file = e.target.files[0];
      if (!file) return;
      if (file.size > 2 * 1024 * 1024) { showToast('Foto maksimal 2 MB'); return; }
      const reader = new FileReader();
      reader.onload = function() {
        const img = new Image();
        img.onload = function() {
          const canvas = document.createElement('canvas');
          const size = 200;
          canvas.width = size; canvas.height = size;
          const ctx = canvas.getContext('2d');
          const min = Math.min(img.width, img.height);
          const sx = (img.width - min) / 2;
          const sy = (img.height - min) / 2;
          ctx.drawImage(img, sx, sy, min, min, 0, 0, size, size);
          const dataUrl = canvas.toDataURL('image/jpeg', 0.85);
          const users = loadUsers();
          if (users[currentUser.username]) {
            users[currentUser.username].photo = dataUrl;
            saveUsers(users);
            currentUser.photo = dataUrl;
            sessionStorage.setItem('arsip_user', JSON.stringify(currentUser));
            updateProfileDisplay();
            showToast('Foto profil berhasil diubah');
          }
        };
        img.src = reader.result;
      };
      reader.readAsDataURL(file);
      e.target.value = '';
    }

    // ==================== NAVIGATION ====================
    function getCurrentFolderId() { return currentPath[currentPath.length - 1]; }

    function canAccess(item) {
      if (currentUser.role === 'operator') return true;
      return item.ownerId === currentUser.folderId || item.ownerId === currentUser.username;
    }

    function getChildren(parentId) {
      return getFS().filter(item => item.parentId === parentId && canAccess(item));
    }

    function getItem(id) { return getFS().find(i => i.id === id); }

    function navigateTo(folderId) {
      currentView = 'files';
      if (folderId === 'root' && currentUser.role === 'operator') {
        currentPath = ['root'];
      } else if (folderId === currentUser.folderId && currentUser.role === 'guru') {
        currentPath = [currentUser.folderId];
      } else {
        const path = [];
        let current = getItem(folderId);
        while (current) {
          path.unshift(current.id);
          if (current.parentId === null || (currentUser.role === 'guru' && current.id === currentUser.folderId)) break;
          current = getItem(current.parentId);
        }
        currentPath = path;
      }
      searchQuery = '';
      closeSidebar();
      renderFolderTree();
      render();
    }

    function goHome() {
      currentView = 'files';
      if (currentUser.role === 'operator') {
        currentPath = ['root'];
      } else {
        currentPath = [currentUser.folderId];
      }
      searchQuery = '';
      setActiveNav('nav-home');
      closeSidebar();
      renderFolderTree();
      render();
    }

    function goUp() {
      if (currentView !== 'files') {
        goHome();
        return;
      }
      if (currentPath.length > 1) {
        currentPath.pop();
        renderFolderTree();
        render();
      } else {
        showToast('Sudah di menu utama');
      }
    }

    function setActiveNav(id) {
      document.querySelectorAll('.nav-item').forEach(el => el.classList.remove('active'));
      const el = document.getElementById(id);
      if (el) el.classList.add('active');
    }

    // ==================== FOLDER TREE (LEFT SIDEBAR) ====================
    function renderFolderTree() {
      const container = document.getElementById('folder-tree');
      const fs = getFS();
      let html = '';

      function buildTree(parentId, depth) {
        const children = fs.filter(i => i.parentId === parentId && i.type === 'folder' && canAccess(i));
        children.forEach(folder => {
          const hasKids = fs.some(i => i.parentId === folder.id && i.type === 'folder' && canAccess(i));
          const isActive = currentPath[currentPath.length - 1] === folder.id && currentView === 'files';
          const isInPath = currentPath.includes(folder.id);
          const name = folder.id === 'root' ? 'Semua Guru' : folder.name;

          html += `<div class="tree-item ${isActive ? 'active' : ''}" onclick="navigateTo('${folder.id}')" style="padding-left:${8 + depth * 12}px">
            <span class="toggle ${hasKids ? (isInPath ? 'open' : '') : 'empty'}" onclick="event.stopPropagation();toggleTreeNode(this,'${folder.id}')">${hasKids ? '▶' : ''}</span>
            <span>📁</span>
            <span class="fname">${escapeHtml(name)}</span>
          </div>`;
          if (hasKids) {
            html += `<div class="tree-children ${isInPath ? 'open' : ''}" id="tree-${folder.id}">`;
            // Temporarily append children
            const saved = html;
            // We need recursive build - use a different approach
          }
        });
      }

      // Better recursive approach
      html = buildTreeHTML('root', 0, fs);
      container.innerHTML = html || '<div style="padding:8px 12px;color:var(--text-muted);font-size:0.8rem;">Tidak ada folder</div>';
    }

    function buildTreeHTML(parentId, depth, fs) {
      let html = '';
      const children = fs.filter(i => i.parentId === parentId && i.type === 'folder' && canAccess(i));
      children.forEach(folder => {
        const hasKids = fs.some(i => i.parentId === folder.id && i.type === 'folder' && canAccess(i));
        const isActive = currentPath[currentPath.length - 1] === folder.id && currentView === 'files';
        const isInPath = currentPath.includes(folder.id);
        const name = folder.id === 'root' ? 'Semua Guru' : folder.name;

        html += `<div class="tree-item ${isActive ? 'active' : ''}" onclick="navigateTo('${folder.id}')" style="padding-left:${6 + depth * 14}px">
          <span class="toggle ${hasKids ? (isInPath ? 'open' : '') : 'empty'}" onclick="event.stopPropagation();toggleTreeNode(this,'${folder.id}')">${hasKids ? '▶' : ''}</span>
          <span style="font-size:0.95rem">📁</span>
          <span class="fname">${escapeHtml(name)}</span>
        </div>`;
        if (hasKids) {
          html += `<div class="tree-children ${isInPath ? 'open' : ''}" id="tree-${folder.id}">`;
          html += buildTreeHTML(folder.id, depth + 1, fs);
          html += `</div>`;
        }
      });
      return html;
    }

    function toggleTreeNode(el, folderId) {
      el.classList.toggle('open');
      const kids = document.getElementById('tree-' + folderId);
      if (kids) kids.classList.toggle('open');
    }

    // ==================== RENDER MAIN ====================
    function render() {
      if (currentView === 'users') { renderUserManage(); return; }
      if (currentView === 'surat-list') { renderSuratList(); return; }
      renderFilesView();
    }

    function renderFilesView() {
      setActiveNav(currentPath.length <= 1 ? 'nav-home' : null);
      const area = document.getElementById('main-content');

      // Nav bar + toolbar
      let html = `
        <div class="nav-bar">
          <button class="btn-nav" onclick="goHome()" title="Menu Utama">🏠 Menu Utama</button>
          <button class="btn-nav" onclick="goUp()" ${currentPath.length <= 1 ? 'disabled' : ''} title="Kembali">⬅️ Kembali</button>
        </div>
        <div class="toolbar">
          <div class="search-box">
            <input type="text" id="search-input" placeholder="Cari file atau folder..." value="${escapeHtml(searchQuery)}" oninput="handleSearch()" />
          </div>
          <button class="btn btn-primary btn-sm" onclick="openUploadModal()">⬆️ Unggah</button>
          <button class="btn btn-secondary btn-sm" onclick="openNewFolderModal()">📂 Folder Baru</button>
        </div>
        <div class="breadcrumb" id="breadcrumb"></div>
        <div id="content-area"></div>
      `;
      area.innerHTML = html;
      renderBreadcrumb();
      renderContentArea();
    }

    function renderBreadcrumb() {
      const el = document.getElementById('breadcrumb');
      if (!el) return;
      let html = '';
      currentPath.forEach((id, idx) => {
        const item = getItem(id);
        const name = item ? (id === 'root' ? 'Semua Guru' : item.name) : id;
        if (idx > 0) html += '<span>›</span>';
        if (idx === currentPath.length - 1) {
          html += `<span style="color:var(--text);font-weight:600">${escapeHtml(name)}</span>`;
        } else {
          html += `<a href="#" onclick="navigateTo('${id}');return false;">${escapeHtml(name)}</a>`;
        }
      });
      el.innerHTML = html;
    }

    function renderContentArea() {
      const area = document.getElementById('content-area');
      if (!area) return;

      if (searchQuery.trim()) {
        renderSearchResults(area);
        return;
      }

      const children = getChildren(getCurrentFolderId());
      const folders = children.filter(c => c.type === 'folder');
      const files = children.filter(c => c.type === 'file');
      let html = '';

      if (folders.length === 0 && files.length === 0) {
        html = `<div class="empty-state"><div class="icon">📂</div><p>Folder ini masih kosong.<br>Unggah file atau buat folder baru.</p></div>`;
      } else {
        if (folders.length > 0) {
          html += `<div class="section-title">📁 Folder</div><div class="grid">`;
          folders.forEach(f => {
            html += `<div class="item-card" onclick="navigateTo('${f.id}')">
              <div class="actions">
                <button onclick="event.stopPropagation();confirmDelete('${f.id}')" title="Hapus">🗑️</button>
              </div>
              <div class="icon">📁</div>
              <div class="name">${escapeHtml(f.name)}</div>
              <div class="meta">${formatDate(f.createdAt)}</div>
            </div>`;
          });
          html += `</div>`;
        }
        if (files.length > 0) {
          html += `<div class="section-title">📄 File</div><div class="grid">`;
          files.forEach(f => {
            html += `<div class="item-card" onclick="previewFile('${f.id}')">
              <div class="actions">
                <button onclick="event.stopPropagation();downloadFile('${f.id}')" title="Unduh">⬇️</button>
                <button onclick="event.stopPropagation();confirmDelete('${f.id}')" title="Hapus">🗑️</button>
              </div>
              <div class="icon">${getFileIcon(f.name, f.mime)}</div>
              <div class="name">${escapeHtml(f.name)}</div>
              <div class="meta">${formatSize(f.size)} · ${formatDate(f.createdAt)}</div>
            </div>`;
          });
          html += `</div>`;
        }
      }
      area.innerHTML = html;
    }

    function renderSearchResults(area) {
      const q = searchQuery.toLowerCase().trim();
      const all = getFS().filter(item => {
        if (!canAccess(item) || item.id === 'root') return false;
        return item.name.toLowerCase().includes(q);
      });
      if (all.length === 0) {
        area.innerHTML = `<div class="empty-state"><div class="icon">🔍</div><p>Tidak ditemukan hasil untuk "<b>${escapeHtml(searchQuery)}</b>"</p></div>`;
        return;
      }
      let html = `<div class="section-title">Hasil pencarian (${all.length})</div><div class="file-list">`;
      all.forEach(item => {
        const parent = getItem(item.parentId);
        const pathName = parent ? (parent.id === 'root' ? 'Semua Guru' : parent.name) : '';
        if (item.type === 'folder') {
          html += `<div class="file-row" onclick="navigateTo('${item.id}')">
            <div class="icon">📁</div>
            <div class="info"><div class="name">${escapeHtml(item.name)}</div><div class="path">${escapeHtml(pathName)}</div></div>
          </div>`;
        } else {
          html += `<div class="file-row" onclick="previewFile('${item.id}')">
            <div class="icon">${getFileIcon(item.name, item.mime)}</div>
            <div class="info"><div class="name">${escapeHtml(item.name)}</div><div class="path">${escapeHtml(pathName)}</div></div>
            <div class="size">${formatSize(item.size)}</div>
          </div>`;
        }
      });
      html += `</div>`;
      area.innerHTML = html;
    }

    function handleSearch() {
      searchQuery = document.getElementById('search-input').value;
      renderContentArea();
    }

    // ==================== USER MANAGEMENT (OPERATOR) ====================
    function showUserManage() {
      currentView = 'users';
      setActiveNav('nav-users');
      closeSidebar();
      renderUserManage();
    }

    function renderUserManage() {
      const users = loadUsers();
      const area = document.getElementById('main-content');
      let rows = '';
      Object.keys(users).forEach(uname => {
        const u = users[uname];
        rows += `<tr>
          <td><b>${escapeHtml(uname)}</b></td>
          <td>${escapeHtml(u.name)}</td>
          <td><span class="badge ${u.role === 'operator' ? 'badge-operator' : 'badge-guru'}">${u.role === 'operator' ? 'Operator' : 'Guru'}</span></td>
          <td style="font-family:monospace;font-size:0.8rem;">${escapeHtml(u.password)}</td>
          <td>
            <button class="btn btn-secondary btn-sm" onclick="editUser('${uname}')" title="Edit">✏️</button>
            ${uname !== 'operator' ? `<button class="btn btn-danger btn-sm" onclick="deleteUser('${uname}')" title="Hapus">🗑️</button>` : ''}
          </td>
        </tr>`;
      });

      area.innerHTML = `
        <div class="nav-bar">
          <button class="btn-nav" onclick="goHome()">🏠 Menu Utama</button>
          <button class="btn-nav" onclick="goUp()">⬅️ Kembali</button>
        </div>
        <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:16px;flex-wrap:wrap;gap:10px;">
          <div class="section-title" style="margin:0;">👥 Kelola User</div>
          <button class="btn btn-primary btn-sm" onclick="openAddUser()">➕ Tambah User</button>
        </div>
        <div style="overflow-x:auto;">
          <table class="user-table">
            <thead>
              <tr><th>Username</th><th>Nama</th><th>Peran</th><th>Password</th><th>Aksi</th></tr>
            </thead>
            <tbody>${rows}</tbody>
          </table>
        </div>
      `;
    }

    function openAddUser() {
      editingUser = null;
      document.getElementById('user-modal-title').textContent = 'Tambah User Baru';
      document.getElementById('new-username').value = '';
      document.getElementById('new-username').disabled = false;
      document.getElementById('new-fullname').value = '';
      document.getElementById('new-password').value = '';
      document.getElementById('new-role').value = 'guru';
      openModal('modal-user');
    }

    function editUser(uname) {
      const users = loadUsers();
      const u = users[uname];
      if (!u) return;
      editingUser = uname;
      document.getElementById('user-modal-title').textContent = 'Edit User';
      document.getElementById('new-username').value = uname;
      document.getElementById('new-username').disabled = true;
      document.getElementById('new-fullname').value = u.name;
      document.getElementById('new-password').value = u.password;
      document.getElementById('new-role').value = u.role;
      openModal('modal-user');
    }

    function saveUser() {
      const uname = document.getElementById('new-username').value.trim().toLowerCase().replace(/\s+/g, '');
      const fullname = document.getElementById('new-fullname').value.trim();
      const password = document.getElementById('new-password').value;
      const role = document.getElementById('new-role').value;

      if (!uname || !fullname || !password) {
        showToast('Semua field wajib diisi');
        return;
      }

      const users = loadUsers();

      if (!editingUser && users[uname]) {
        showToast('Username sudah digunakan');
        return;
      }

      if (editingUser) {
        // Update existing
        users[editingUser].name = fullname;
        users[editingUser].password = password;
        users[editingUser].role = role;
        // Update folder name if guru
        if (role === 'guru' && users[editingUser].folderId) {
          const fs = getFS();
          const folder = fs.find(i => i.id === users[editingUser].folderId);
          if (folder) { folder.name = fullname; saveFS(fs); }
        }
      } else {
        // New user
        const folderId = role === 'guru' ? uname : undefined;
        users[uname] = { password, name: fullname, role, folderId, photo: null };
        // Create folder for guru
        if (role === 'guru') {
          const fs = getFS();
          if (!fs.find(i => i.id === folderId)) {
            fs.push({
              id: folderId, name: fullname, type: 'folder',
              parentId: 'root', ownerId: folderId, createdAt: Date.now()
            });
            saveFS(fs);
          }
        }
      }

      saveUsers(users);
      closeModal('modal-user');
      showToast(editingUser ? 'User berhasil diubah' : 'User baru berhasil ditambahkan');
      renderFolderTree();
      renderUserManage();
    }

    function deleteUser(uname) {
      if (uname === 'operator') { showToast('Tidak bisa menghapus operator utama'); return; }
      if (!confirm(`Hapus user "${uname}"? Folder miliknya tidak ikut terhapus.`)) return;
      const users = loadUsers();
      delete users[uname];
      saveUsers(users);
      showToast('User dihapus');
      renderUserManage();
    }

    // ==================== SURAT KELUAR ====================
    function showSuratKeluar() {
      setActiveNav('nav-surat');
      closeSidebar();
      const cfg = loadSuratCfg();
      const suggested = getSuggestedNumber();
      const now = new Date();
      const bulanRomawi = ['I','II','III','IV','V','VI','VII','VIII','IX','X','XI','XII'];

      document.getElementById('surat-num').value = suggested;
      document.getElementById('surat-kode').value = cfg.kode || 'SKh.YK';
      document.getElementById('surat-bulan').value = bulanRomawi[now.getMonth()];
      document.getElementById('surat-tahun').value = now.getFullYear();
      document.getElementById('surat-perihal').value = '';
      document.getElementById('surat-tujuan').value = '';
      document.getElementById('surat-keterangan').value = '';

      const lastList = loadSurat().filter(s => s.year === now.getFullYear());
      const lastNum = lastList.length ? Math.max(...lastList.map(s => s.number)) : 0;
      document.getElementById('surat-nomor-info').textContent = lastNum > 0
        ? 'Saran nomor berikutnya: ' + suggested + ' (terakhir: ' + lastNum + '). Anda bisa mengubah nomor secara manual.'
        : 'Belum ada surat tahun ' + now.getFullYear() + '. Nomor bisa diubah sesuai kebutuhan.';

      updateSuratPreview();
      ['surat-num','surat-kode','surat-bulan','surat-tahun'].forEach(function(id) {
        var el = document.getElementById(id);
        if (el) { el.oninput = updateSuratPreview; el.onchange = updateSuratPreview; }
      });
      openModal('modal-surat');
    }

    function updateSuratPreview() {
      var num = parseInt(document.getElementById('surat-num').value) || 0;
      var kode = (document.getElementById('surat-kode').value || 'SKh.YK').trim();
      var bulan = document.getElementById('surat-bulan').value;
      var tahun = parseInt(document.getElementById('surat-tahun').value) || new Date().getFullYear();
      var cfg = loadSuratCfg();
      document.getElementById('surat-nomor-preview').textContent = formatNomorSurat(num, kode, bulan, tahun, cfg.pad || 0);
    }

    
    function saveSuratKeluar() {
      var num = parseInt(document.getElementById('surat-num').value);
      var kode = document.getElementById('surat-kode').value.trim();
      var bulan = document.getElementById('surat-bulan').value;
      var tahun = parseInt(document.getElementById('surat-tahun').value);
      var perihal = document.getElementById('surat-perihal').value.trim();
      var tujuan = document.getElementById('surat-tujuan').value.trim();
      var keterangan = document.getElementById('surat-keterangan').value.trim();

      if (!num || num < 1) { showToast('Nomor surat wajib diisi'); return; }
      if (!kode) { showToast('Kode/instansi wajib diisi'); return; }
      if (!perihal || !tujuan) { showToast('Perihal dan Tujuan wajib diisi'); return; }

      var cfg = loadSuratCfg();
      var nomor = formatNomorSurat(num, kode, bulan, tahun, cfg.pad || 0);
      var list = loadSurat();

      if (list.some(function(s) { return s.nomor === nomor; })) {
        if (!confirm('Nomor ' + nomor + ' sudah ada. Tetap simpan?')) return;
      }

      list.push({
        id: uid(), number: num, year: tahun, bulan: bulan, kode: kode, nomor: nomor,
        perihal: perihal, tujuan: tujuan, keterangan: keterangan,
        createdAt: Date.now(), createdBy: currentUser.username
      });
      saveSurat(list);
      closeModal('modal-surat');
      showToast('Surat tersimpan: ' + nomor);
      showSuratList();
    }

    function showSuratSetting() {
      setActiveNav('nav-surat-setting');
      closeSidebar();
      var cfg = loadSuratCfg();
      document.getElementById('cfg-kode').value = cfg.kode || 'SKh.YK';
      document.getElementById('cfg-prefix-pad').value = String(cfg.pad || 0);
      updateCfgPreview();
      document.getElementById('cfg-kode').oninput = updateCfgPreview;
      document.getElementById('cfg-prefix-pad').onchange = updateCfgPreview;
      openModal('modal-surat-setting');
    }

    function updateCfgPreview() {
      var kode = (document.getElementById('cfg-kode').value || 'SKh.YK').trim();
      var pad = parseInt(document.getElementById('cfg-prefix-pad').value) || 0;
      var now = new Date();
      var bulanRomawi = ['I','II','III','IV','V','VI','VII','VIII','IX','X','XI','XII'];
      document.getElementById('cfg-preview').textContent =
        formatNomorSurat(123, kode, bulanRomawi[now.getMonth()], now.getFullYear(), pad);
    }

    function saveSuratSetting() {
      var kode = document.getElementById('cfg-kode').value.trim() || 'SKh.YK';
      var pad = parseInt(document.getElementById('cfg-prefix-pad').value) || 0;
      saveSuratCfg({ kode: kode, pad: pad });
      closeModal('modal-surat-setting');
      showToast('Pengaturan format nomor disimpan');
    }

    
    function showSuratList() {
      currentView = 'surat-list';
      setActiveNav('nav-surat-list');
      closeSidebar();
      renderSuratList();
    }

    function renderSuratList() {
      const list = loadSurat().sort((a, b) => b.createdAt - a.createdAt);
      const area = document.getElementById('main-content');

      let rows = '';
      if (list.length === 0) {
        rows = `<tr><td colspan="5" style="text-align:center;padding:30px;color:var(--text-muted);">Belum ada surat keluar</td></tr>`;
      } else {
        list.forEach(s => {
          rows += `<tr>
            <td><b style="color:var(--primary)">${escapeHtml(s.nomor)}</b></td>
            <td>${escapeHtml(s.perihal)}</td>
            <td>${escapeHtml(s.tujuan)}</td>
            <td style="font-size:0.8rem;color:var(--text-muted)">${formatDate(s.createdAt)}</td>
            <td>
              <button class="btn btn-danger btn-sm" onclick="deleteSurat('${s.id}')" title="Hapus">🗑️</button>
            </td>
          </tr>`;
        });
      }

      const suggested = getSuggestedNumber();
      const cfg = loadSuratCfg();
      const now = new Date();
      const bulanRomawi = ['I','II','III','IV','V','VI','VII','VIII','IX','X','XI','XII'];
      const contoh = formatNomorSurat(suggested, cfg.kode || 'SKh.YK', bulanRomawi[now.getMonth()], now.getFullYear(), cfg.pad || 0);
      area.innerHTML = `
        <div class="nav-bar">
          <button class="btn-nav" onclick="goHome()">🏠 Menu Utama</button>
          <button class="btn-nav" onclick="goUp()">⬅️ Kembali</button>
        </div>
        <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:16px;flex-wrap:wrap;gap:10px;">
          <div>
            <div class="section-title" style="margin:0;">📋 Daftar Surat Keluar</div>
            <div style="font-size:0.8rem;color:var(--text-muted);margin-top:2px;">
              Saran nomor berikutnya: <b style="color:var(--primary);font-family:monospace">${contoh}</b>
            </div>
          </div>
          <button class="btn btn-primary btn-sm" onclick="showSuratKeluar()">➕ Buat Surat</button>
        </div>
        <div style="overflow-x:auto;">
          <table class="user-table">
            <thead>
              <tr><th>Nomor Surat</th><th>Perihal</th><th>Tujuan</th><th>Tanggal</th><th>Aksi</th></tr>
            </thead>
            <tbody>${rows}</tbody>
          </table>
        </div>
      `;
    }

    function deleteSurat(id) {
      if (!confirm('Hapus surat ini dari daftar?')) return;
      let list = loadSurat();
      list = list.filter(s => s.id !== id);
      saveSurat(list);
      showToast('Surat dihapus');
      renderSuratList();
    }

    // ==================== FOLDER / FILE OPS ====================
    function openNewFolderModal() {
      document.getElementById('folder-name').value = '';
      openModal('modal-folder');
      setTimeout(() => document.getElementById('folder-name').focus(), 100);
    }

    function createFolder() {
      const name = document.getElementById('folder-name').value.trim();
      if (!name) { showToast('Nama folder tidak boleh kosong'); return; }
      const fs = getFS();
      const parentId = getCurrentFolderId();
      let ownerId = currentUser.role === 'guru' ? currentUser.folderId : 'system';
      if (currentUser.role === 'operator' && parentId !== 'root') {
        ownerId = getItem(parentId)?.ownerId || 'system';
      }
      fs.push({ id: uid(), name, type: 'folder', parentId, ownerId, createdAt: Date.now() });
      saveFS(fs);
      closeModal('modal-folder');
      showToast('Folder berhasil dibuat');
      renderFolderTree();
      render();
    }

    function openUploadModal() {
      document.getElementById('upload-list').innerHTML = '';
      document.getElementById('file-input').value = '';
      openModal('modal-upload');
    }

    const zone = document.getElementById('upload-zone');
    zone.addEventListener('dragover', e => { e.preventDefault(); zone.classList.add('dragover'); });
    zone.addEventListener('dragleave', () => zone.classList.remove('dragover'));
    zone.addEventListener('drop', e => {
      e.preventDefault(); zone.classList.remove('dragover');
      handleFiles(e.dataTransfer.files);
    });

    function handleFileSelect(e) { handleFiles(e.target.files); }

    function handleFiles(fileList) {
      const files = Array.from(fileList);
      const listEl = document.getElementById('upload-list');
      files.forEach(file => {
        if (file.size > 8 * 1024 * 1024) {
          showToast(`File ${file.name} terlalu besar (max 8 MB)`);
          return;
        }
        const reader = new FileReader();
        reader.onload = () => {
          const fs = getFS();
          const parentId = getCurrentFolderId();
          let ownerId = currentUser.role === 'guru' ? currentUser.folderId : 'system';
          if (currentUser.role === 'operator' && parentId !== 'root') {
            ownerId = getItem(parentId)?.ownerId || 'system';
          }
          fs.push({
            id: uid(), name: file.name, type: 'file', parentId, ownerId,
            createdAt: Date.now(), size: file.size,
            mime: file.type || guessMime(file.name), data: reader.result
          });
          saveFS(fs);
          const div = document.createElement('div');
          div.style.cssText = 'padding:8px 12px;background:#ecfdf5;border-radius:8px;margin-bottom:6px;font-size:0.85rem;color:#065f46;';
          div.textContent = '✓ ' + file.name + ' berhasil diunggah';
          listEl.appendChild(div);
          render();
        };
        reader.readAsDataURL(file);
      });
    }

    function guessMime(name) {
      const ext = name.split('.').pop().toLowerCase();
      const map = {
        pdf: 'application/pdf', jpg: 'image/jpeg', jpeg: 'image/jpeg',
        png: 'image/png', gif: 'image/gif', webp: 'image/webp',
        doc: 'application/msword',
        docx: 'application/vnd.openxmlformats-officedocument.wordprocessingml.document',
        txt: 'text/plain'
      };
      return map[ext] || 'application/octet-stream';
    }

    function previewFile(id) {
      const file = getItem(id);
      if (!file || file.type !== 'file') return;
      document.getElementById('preview-title').textContent = file.name;
      const area = document.getElementById('preview-area');
      const downloadBtn = document.getElementById('preview-download');
      downloadBtn.href = file.data;
      downloadBtn.download = file.name;
      const ext = file.name.split('.').pop().toLowerCase();
      const isImage = ['jpg','jpeg','png','gif','webp'].includes(ext) || (file.mime && file.mime.startsWith('image/'));
      const isPdf = ext === 'pdf' || file.mime === 'application/pdf';
      const isText = ['txt','md','csv'].includes(ext) || (file.mime && file.mime.startsWith('text/'));
      const isDocx = ext === 'docx';
      const isDoc = ext === 'doc';
      const isXlsx = ext === 'xlsx' || ext === 'xls';

      area.innerHTML = '<div style="padding:30px;color:var(--text-muted);">Memuat preview...</div>';
      openModal('modal-preview');

      function dataURLtoArrayBuffer(dataURL) {
        const base64 = dataURL.split(',')[1];
        const binary = atob(base64);
        const bytes = new Uint8Array(binary.length);
        for (let i = 0; i < binary.length; i++) bytes[i] = binary.charCodeAt(i);
        return bytes.buffer;
      }

      if (isImage) {
        area.innerHTML = '<img src="' + file.data + '" alt="' + escapeHtml(file.name) + '" style="max-width:100%;max-height:70vh;object-fit:contain;" />';
      } else if (isPdf) {
        area.innerHTML = '<iframe src="' + file.data + '" title="PDF Preview" style="width:100%;height:70vh;border:none;"></iframe>';
      } else if (isText) {
        try {
          const base64 = file.data.split(',')[1];
          const text = decodeURIComponent(escape(atob(base64)));
          area.innerHTML = '<pre style="padding:16px;text-align:left;white-space:pre-wrap;word-break:break-word;max-height:70vh;overflow:auto;font-size:0.85rem;width:100%;">' + escapeHtml(text) + '</pre>';
        } catch (e) {
          area.innerHTML = noPreviewHtml(file.name);
        }
      } else if (isDocx && typeof mammoth !== 'undefined') {
        try {
          const ab = dataURLtoArrayBuffer(file.data);
          mammoth.convertToHtml({ arrayBuffer: ab }).then(function(result) {
            area.innerHTML = '<div class="docx-content" style="padding:16px;text-align:left;width:100%;font-size:0.9rem;line-height:1.6;">' + (result.value || '<p><i>(Dokumen kosong)</i></p>') + '</div>';
          }).catch(function(err) {
            console.error(err);
            area.innerHTML = noPreviewHtml(file.name, 'Gagal membaca file DOCX. Silakan unduh.');
          });
        } catch (err) {
          area.innerHTML = noPreviewHtml(file.name, 'Gagal membaca file DOCX.');
        }
      } else if (isDoc) {
        area.innerHTML = noPreviewHtml(file.name, 'File .DOC (format lama) tidak dapat di-preview di browser. Silakan unduh atau konversi ke .DOCX.');
      } else if (isXlsx && typeof XLSX !== 'undefined') {
        try {
          const ab = dataURLtoArrayBuffer(file.data);
          const wb = XLSX.read(ab, { type: 'array' });
          let htmlContent = '<div class="excel-content" style="padding:16px;text-align:left;width:100%;overflow:auto;">';
          wb.SheetNames.forEach(function(sheetName, idx) {
            const sheet = wb.Sheets[sheetName];
            const tableHtml = XLSX.utils.sheet_to_html(sheet, { editable: false });
            if (wb.SheetNames.length > 1) {
              htmlContent += '<h4 style="margin:12px 0 6px;color:var(--primary);">📄 ' + escapeHtml(sheetName) + '</h4>';
            }
            htmlContent += tableHtml;
            if (idx < wb.SheetNames.length - 1) htmlContent += '<hr style="margin:16px 0;border:none;border-top:1px solid #e2e8f0;">';
          });
          htmlContent += '</div>';
          // Style tables
          htmlContent = htmlContent.replace(/<table/g, '<table style="border-collapse:collapse;width:100%;font-size:0.8rem;"');
          htmlContent = htmlContent.replace(/<td/g, '<td style="border:1px solid #cbd5e1;padding:4px 8px;"');
          htmlContent = htmlContent.replace(/<th/g, '<th style="border:1px solid #cbd5e1;padding:4px 8px;background:#eff6ff;font-weight:600;"');
          area.innerHTML = htmlContent;
        } catch (err) {
          console.error(err);
          area.innerHTML = noPreviewHtml(file.name, 'Gagal membaca file Excel. Silakan unduh.');
        }
      } else {
        area.innerHTML = noPreviewHtml(file.name);
      }
    }

    
        function noPreviewHtml(name, extra) {
      return '<div class="no-preview" style="text-align:center;padding:40px;color:var(--text-muted);"><div class="icon" style="font-size:2.8rem;margin-bottom:8px;">📄</div><p><b>' + escapeHtml(name) + '</b></p><p style="margin-top:8px;">' + (extra || 'Preview tidak tersedia untuk jenis file ini.') + '<br>Silakan unduh untuk membuka.</p></div>';
    }

    
    function downloadFile(id) {
      const file = getItem(id);
      if (!file) return;
      const a = document.createElement('a');
      a.href = file.data; a.download = file.name; a.click();
    }

    function confirmDelete(id) {
      const item = getItem(id);
      if (!item) return;
      deleteTarget = id;
      document.getElementById('delete-msg').textContent =
        `Apakah Anda yakin ingin menghapus ${item.type === 'folder' ? 'folder' : 'file'} "${item.name}"?` +
        (item.type === 'folder' ? ' Semua isi di dalamnya juga akan terhapus.' : '');
      openModal('modal-delete');
      document.getElementById('btn-confirm-delete').onclick = doDelete;
    }

    function doDelete() {
      if (!deleteTarget) return;
      let fs = getFS();
      const toDelete = new Set();
      function collect(id) {
        toDelete.add(id);
        fs.filter(i => i.parentId === id).forEach(child => collect(child.id));
      }
      collect(deleteTarget);
      fs = fs.filter(i => !toDelete.has(i.id));
      saveFS(fs);
      closeModal('modal-delete');
      deleteTarget = null;
      showToast('Item berhasil dihapus');
      renderFolderTree();
      render();
    }

    // ==================== CLOCK ====================
    function startClock() {
      // Place numbers
      const face = document.getElementById('clock-face');
      // Remove old numbers
      face.querySelectorAll('.clock-number').forEach(n => n.remove());
      for (let i = 1; i <= 12; i++) {
        const angle = (i * 30 - 90) * (Math.PI / 180);
        const r = 72;
        const x = 90 + r * Math.cos(angle);
        const y = 90 + r * Math.sin(angle);
        const num = document.createElement('div');
        num.className = 'clock-number';
        num.textContent = i;
        num.style.left = (x - 10) + 'px';
        num.style.top = (y - 10) + 'px';
        face.appendChild(num);
      }
      updateClock();
      setInterval(updateClock, 1000);
    }

    function updateClock() {
      const now = new Date();
      const h = now.getHours() % 12;
      const m = now.getMinutes();
      const s = now.getSeconds();

      const hAngle = (h * 30) + (m * 0.5);
      const mAngle = m * 6;
      const sAngle = s * 6;

      const hourEl = document.getElementById('hand-hour');
      const minEl = document.getElementById('hand-minute');
      const secEl = document.getElementById('hand-second');
      if (hourEl) hourEl.style.transform = `rotate(${hAngle}deg)`;
      if (minEl) minEl.style.transform = `rotate(${mAngle}deg)`;
      if (secEl) secEl.style.transform = `rotate(${sAngle}deg)`;

      const pad = n => String(n).padStart(2, '0');
      const dig = document.getElementById('digital-time');
      if (dig) dig.textContent = `${pad(now.getHours())}:${pad(m)}:${pad(s)}`;

      const dateEl = document.getElementById('digital-date');
      if (dateEl) {
        dateEl.textContent = now.toLocaleDateString('id-ID', {
          weekday: 'long', day: 'numeric', month: 'long', year: 'numeric'
        });
      }
    }

    // ==================== CALENDAR ====================
    function renderCalendar() {
      const title = document.getElementById('cal-title');
      const grid = document.getElementById('cal-grid');
      if (!title || !grid) return;

      const monthNames = ['Januari','Februari','Maret','April','Mei','Juni',
        'Juli','Agustus','September','Oktober','November','Desember'];
      title.textContent = monthNames[calMonth] + ' ' + calYear;

      const firstDay = new Date(calYear, calMonth, 1).getDay();
      const daysInMonth = new Date(calYear, calMonth + 1, 0).getDate();
      const daysInPrev = new Date(calYear, calMonth, 0).getDate();
      const today = new Date();

      let html = '';
      // Previous month days
      for (let i = firstDay - 1; i >= 0; i--) {
        html += `<div class="cal-day other">${daysInPrev - i}</div>`;
      }
      // Current month
      for (let d = 1; d <= daysInMonth; d++) {
        const isToday = d === today.getDate() && calMonth === today.getMonth() && calYear === today.getFullYear();
        html += `<div class="cal-day ${isToday ? 'today' : ''}">${d}</div>`;
      }
      // Next month fill
      const totalCells = firstDay + daysInMonth;
      const remaining = totalCells % 7 === 0 ? 0 : 7 - (totalCells % 7);
      for (let i = 1; i <= remaining; i++) {
        html += `<div class="cal-day other">${i}</div>`;
      }
      grid.innerHTML = html;
    }

    function changeMonth(delta) {
      calMonth += delta;
      if (calMonth > 11) { calMonth = 0; calYear++; }
      if (calMonth < 0) { calMonth = 11; calYear--; }
      renderCalendar();
    }

    // ==================== HELPERS ====================
    function openModal(id) { document.getElementById(id).classList.add('show'); }
    function closeModal(id) { document.getElementById(id).classList.remove('show'); }

    function showToast(msg) {
      const t = document.getElementById('toast');
      t.textContent = msg;
      t.classList.add('show');
      setTimeout(() => t.classList.remove('show'), 2800);
    }

    function escapeHtml(str) {
      const div = document.createElement('div');
      div.textContent = str;
      return div.innerHTML;
    }

    function getFileIcon(name, mime) {
      const ext = name.split('.').pop().toLowerCase();
      if (['jpg','jpeg','png','gif','webp'].includes(ext) || (mime && mime.startsWith('image/'))) return '🖼️';
      if (ext === 'pdf' || mime === 'application/pdf') return '📕';
      if (['doc','docx'].includes(ext)) return '📘';
      if (['xls','xlsx'].includes(ext)) return '📗';
      if (['txt','md'].includes(ext)) return '📄';
      return '📎';
    }

    function formatSize(bytes) {
      if (!bytes) return '';
      if (bytes < 1024) return bytes + ' B';
      if (bytes < 1048576) return (bytes / 1024).toFixed(1) + ' KB';
      return (bytes / 1048576).toFixed(1) + ' MB';
    }

    function formatDate(ts) {
      return new Date(ts).toLocaleDateString('id-ID', { day: 'numeric', month: 'short', year: 'numeric' });
    }

    function toggleSidebar() {
      document.getElementById('sidebar-left').classList.toggle('open');
      document.getElementById('sidebar-overlay').classList.toggle('show');
    }

    function closeSidebar() {
      document.getElementById('sidebar-left').classList.remove('open');
      document.getElementById('sidebar-overlay').classList.remove('show');
    }

    // Close modal on overlay click
    document.querySelectorAll('.modal-overlay').forEach(el => {
      el.addEventListener('click', e => { if (e.target === el) el.classList.remove('show'); });
    });

    // ==================== INIT ====================
    document.getElementById('login-form').addEventListener('submit', login);
    checkSession();
  </script>
</body>
</html>
