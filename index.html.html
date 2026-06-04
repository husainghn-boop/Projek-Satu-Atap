<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SatuAtap — Manajemen Kos</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@latest/dist/tabler-icons.min.css">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{
  --primary:#F97316;--primary-light:#FFF7ED;--primary-mid:#FDBA74;
  --teal:#0F9B8E;--teal-light:#E0F5F3;
  --navy:#1A2A4A;
  --bg:#F0F2F8;--card:#FFFFFF;--border:#E8EAF0;
  --text1:#1A1D2E;--text2:#5A6072;--text3:#9AA0B4;
  --green:#16A34A;--green-light:#DCFCE7;
  --red:#DC2626;--red-light:#FEE2E2;
  --amber:#D97706;--amber-light:#FEF3C7;
  --blue:#2563EB;--blue-light:#EFF6FF;
  --radius:14px;--radius-sm:10px;--radius-xs:8px;
}
body{font-family:'Plus Jakarta Sans',sans-serif;background:var(--bg);color:var(--text1);min-height:100vh;display:flex;flex-direction:column;align-items:center}

/* ── APP SHELL ── */
.app-shell{width:100%;max-width:420px;min-height:100vh;background:var(--bg);display:flex;flex-direction:column;position:relative;overflow:hidden}
.status-bar{background:var(--primary);padding:10px 18px;display:flex;justify-content:space-between;align-items:center;flex-shrink:0}
.status-bar span{font-size:11px;color:#fff;font-weight:700}

/* ── SCREENS ── */
.screen{flex:1;overflow-y:auto;padding-bottom:72px;display:none;flex-direction:column}
.screen.active{display:flex}
.screen-inner{padding:16px;flex:1}

/* ── BOTTOM NAV ── */
.bottom-nav{position:fixed;bottom:0;left:50%;transform:translateX(-50%);width:100%;max-width:420px;background:#fff;border-top:1.5px solid var(--border);display:flex;padding:6px 0 10px;z-index:100;box-shadow:0 -4px 20px rgba(0,0,0,.06)}
.nav-item{flex:1;display:flex;flex-direction:column;align-items:center;gap:2px;cursor:pointer;transition:all .2s}
.nav-item i{font-size:20px;color:var(--text3);transition:.2s}
.nav-item span{font-size:9px;color:var(--text3);font-weight:600;transition:.2s}
.nav-item.active i,.nav-item.active span{color:var(--primary)}
.nav-item.active i{transform:translateY(-1px)}

/* ── LOGIN SCREEN ── */
#screen-login{padding-bottom:0}
#screen-login .screen-inner{display:flex;flex-direction:column;align-items:center;justify-content:center;min-height:calc(100vh - 40px);padding:32px 24px}
.login-logo{text-align:center;margin-bottom:32px}
.login-logo svg{display:block;margin:0 auto 8px}
.login-logo p{font-size:13px;color:var(--text2)}
.form-group{width:100%;margin-bottom:12px}
.form-group label{font-size:11px;font-weight:700;color:var(--text2);display:block;margin-bottom:5px}
.inp-field{width:100%;background:#F4F6FB;border:1.5px solid var(--border);border-radius:var(--radius-xs);padding:12px 14px;font-size:13px;color:var(--text1);font-family:inherit;outline:none;transition:.2s;display:flex;align-items:center;gap:8px}
.inp-field:focus{border-color:var(--primary);background:#fff}
input.inp-field{display:block}
.btn-primary{width:100%;background:var(--primary);color:#fff;border:none;border-radius:var(--radius-xs);padding:13px;font-size:13px;font-weight:800;cursor:pointer;transition:.2s;font-family:inherit;letter-spacing:.04em}
.btn-primary:hover{background:#EA580C;transform:translateY(-1px);box-shadow:0 4px 16px rgba(249,115,22,.35)}
.btn-outline{width:100%;background:#fff;color:var(--primary);border:2px solid var(--primary);border-radius:var(--radius-xs);padding:12px;font-size:13px;font-weight:800;cursor:pointer;transition:.2s;font-family:inherit;margin-top:8px}
.btn-outline:hover{background:var(--primary-light)}
.link-text{text-align:center;font-size:12px;color:var(--text3);margin:10px 0 6px}
.link-text a{color:var(--primary);font-weight:700;text-decoration:none}

/* ── DASHBOARD ── */
.page-header{display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:14px}
.page-header h2{font-size:18px;font-weight:800;color:var(--text1)}
.page-header p{font-size:12px;color:var(--text2);margin-top:1px}
.bell-btn{width:36px;height:36px;background:var(--amber-light);border-radius:10px;display:flex;align-items:center;justify-content:center;position:relative;cursor:pointer;flex-shrink:0}
.bell-btn i{color:var(--amber);font-size:18px}
.notif-dot{width:8px;height:8px;background:var(--red);border-radius:50%;position:absolute;top:5px;right:5px;border:1.5px solid var(--amber-light)}
.section-title{font-size:11px;font-weight:700;color:var(--text3);text-transform:uppercase;letter-spacing:.07em;margin:14px 0 8px}
.summary-card{background:linear-gradient(135deg,#FFF7ED,#FEF3C7);border-radius:var(--radius-sm);padding:14px 16px;border:1.5px solid var(--primary-mid);margin-bottom:4px}
.summary-card .lbl{font-size:11px;color:var(--text2);margin-bottom:4px}
.summary-card .val{font-size:22px;font-weight:800;color:var(--primary)}
.stat-grid{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-bottom:0}
.mini-stat{background:#fff;border-radius:var(--radius-xs);padding:10px 12px;display:flex;align-items:center;gap:10px;border:1px solid var(--border)}
.mini-stat .ico{width:32px;height:32px;border-radius:8px;display:flex;align-items:center;justify-content:center;flex-shrink:0}
.ico.orange{background:var(--primary-light)} .ico.orange i{color:var(--primary)}
.ico.teal{background:var(--teal-light)} .ico.teal i{color:var(--teal)}
.ico.blue{background:var(--blue-light)} .ico.blue i{color:var(--blue)}
.ico.green{background:var(--green-light)} .ico.green i{color:var(--green)}
.ico.red{background:var(--red-light)} .ico.red i{color:var(--red)}
.ico.amber{background:var(--amber-light)} .ico.amber i{color:var(--amber)}
.mini-stat .info p:first-child{font-size:10px;color:var(--text2)}
.mini-stat .info p:last-child{font-size:13px;font-weight:700;color:var(--text1);margin-top:1px}
.agenda-card{background:#fff;border-radius:var(--radius-xs);padding:10px 14px;border:1px solid var(--border);display:flex;align-items:center;gap:10px;margin-bottom:7px}
.agenda-dot{width:8px;height:8px;border-radius:50%;background:var(--primary);flex-shrink:0}
.agenda-card p{font-size:13px;font-weight:600;color:var(--text1)}
.agenda-card span{font-size:11px;color:var(--text3)}
.agenda-icon{width:32px;height:32px;background:var(--primary-light);border-radius:8px;display:flex;align-items:center;justify-content:center;margin-left:auto;flex-shrink:0}
.agenda-icon i{color:var(--primary);font-size:16px}
.quick-actions{display:grid;grid-template-columns:1fr 1fr 1fr;gap:8px;margin-top:4px}
.qa-btn{background:var(--primary-light);border-radius:var(--radius-xs);padding:12px 6px;text-align:center;cursor:pointer;transition:.2s;border:1.5px solid transparent}
.qa-btn:hover{border-color:var(--primary);transform:translateY(-2px)}
.qa-btn i{font-size:22px;color:var(--primary);display:block;margin-bottom:4px}
.qa-btn span{font-size:10px;color:var(--primary);font-weight:700}

/* ── FINANCE ── */
.tab-bar{display:flex;background:#F4F6FB;border-radius:var(--radius-xs);padding:3px;margin-bottom:14px}
.tab{flex:1;text-align:center;padding:8px;font-size:12px;font-weight:700;color:var(--text2);border-radius:6px;cursor:pointer;transition:.2s}
.tab.active{background:#fff;color:var(--primary);box-shadow:0 2px 8px rgba(0,0,0,.08)}
.total-card{background:linear-gradient(135deg,var(--primary),#FB923C);border-radius:var(--radius-sm);padding:18px;text-align:center;margin-bottom:14px;box-shadow:0 4px 20px rgba(249,115,22,.3)}
.total-card p{font-size:11px;color:rgba(255,255,255,.85);margin-bottom:4px}
.total-card h2{font-size:26px;font-weight:800;color:#fff}
.bill-item{display:flex;align-items:center;gap:10px;padding:10px 0;border-bottom:1px solid var(--border)}
.bill-icon{width:36px;height:36px;border-radius:10px;display:flex;align-items:center;justify-content:center;flex-shrink:0}
.bill-icon i{font-size:18px}
.bill-info{flex:1}
.bill-info p{font-size:13px;font-weight:600;color:var(--text1)}
.bill-info span{font-size:11px;color:var(--text3)}
.bill-right{text-align:right}
.bill-right p{font-size:13px;font-weight:700;color:var(--text1);margin-bottom:4px}
.badge{padding:3px 9px;border-radius:12px;font-size:10px;font-weight:700;display:inline-block}
.badge.unpaid{background:var(--red-light);color:var(--red)}
.badge.paid{background:var(--green-light);color:var(--green)}
.badge.partial{background:var(--amber-light);color:var(--amber)}
.add-btn{background:var(--primary);color:#fff;border:none;border-radius:var(--radius-xs);padding:13px;width:100%;font-size:13px;font-weight:800;cursor:pointer;margin-top:14px;display:flex;align-items:center;justify-content:center;gap:6px;font-family:inherit;transition:.2s}
.add-btn:hover{background:#EA580C;transform:translateY(-1px)}
.add-btn i{font-size:16px}

/* ── TASKS ── */
.sched-item{display:flex;align-items:center;gap:10px;padding:10px 0;border-bottom:1px solid var(--border)}
.avatar{width:34px;height:34px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:11px;font-weight:700;flex-shrink:0}
.av-o{background:var(--primary-light);color:var(--primary)}
.av-t{background:var(--teal-light);color:var(--teal)}
.av-b{background:var(--blue-light);color:var(--blue)}
.av-g{background:var(--green-light);color:var(--green)}
.av-a{background:var(--amber-light);color:var(--amber)}
.av-r{background:var(--red-light);color:var(--red)}
.sched-info{flex:1}
.sched-info p{font-size:13px;font-weight:600;color:var(--text1)}
.sched-info span{font-size:11px;color:var(--text3)}
.today-badge{background:var(--primary);color:#fff;padding:3px 10px;border-radius:12px;font-size:10px;font-weight:700}
.task-list-item{display:flex;align-items:center;gap:10px;padding:10px 12px;background:#fff;border-radius:var(--radius-xs);border:1px solid var(--border);margin-bottom:7px;cursor:pointer;transition:.2s}
.task-list-item:hover{border-color:var(--primary);box-shadow:0 2px 8px rgba(249,115,22,.1)}
.task-check{width:20px;height:20px;border-radius:6px;border:2px solid var(--border);display:flex;align-items:center;justify-content:center;flex-shrink:0;transition:.2s}
.task-check.done{background:var(--green);border-color:var(--green)}
.task-check.done i{color:#fff;font-size:12px}
.task-info{flex:1}
.task-info p{font-size:13px;font-weight:600;color:var(--text1)}
.task-info span{font-size:11px;color:var(--text3)}

/* ── COMMUNITY ── */
.vote-card{background:#fff;border-radius:var(--radius-sm);padding:14px;border:1px solid var(--border);margin-bottom:10px}
.vote-card h4{font-size:14px;font-weight:700;color:var(--text1);margin-bottom:3px}
.vote-card .timer{font-size:11px;color:var(--text3);margin-bottom:12px;display:flex;align-items:center;gap:4px}
.vote-card .timer i{font-size:13px}
.vote-opt{margin-bottom:8px}
.vote-opt-label{display:flex;justify-content:space-between;font-size:12px;color:var(--text2);margin-bottom:4px;font-weight:500}
.vote-bar{height:8px;background:#E8EAF0;border-radius:4px;overflow:hidden}
.vote-bar .fill{height:100%;border-radius:4px;transition:width .6s ease}
.fill-orange{background:var(--primary)}
.fill-teal{background:var(--teal)}
.fill-gray{background:#B4B2A9}
.vote-detail-btn{text-align:center;font-size:12px;color:var(--primary);font-weight:700;margin-top:10px;cursor:pointer;padding:4px}
.agenda-list-item{display:flex;gap:12px;padding:10px 12px;background:#fff;border-radius:var(--radius-xs);border:1px solid var(--border);margin-bottom:7px;align-items:center}
.agenda-date-box{background:var(--primary-light);border-radius:8px;padding:6px 10px;text-align:center;flex-shrink:0}
.agenda-date-box p{font-size:16px;font-weight:800;color:var(--primary);line-height:1}
.agenda-date-box span{font-size:9px;color:var(--primary-mid);font-weight:700;text-transform:uppercase}
.rules-list{list-style:none;padding:0}
.rules-list li{padding:10px 12px;background:#fff;border-radius:var(--radius-xs);border:1px solid var(--border);margin-bottom:7px;font-size:13px;color:var(--text1);display:flex;align-items:center;gap:10px}
.rule-num{width:24px;height:24px;background:var(--primary-light);border-radius:6px;display:flex;align-items:center;justify-content:center;font-size:11px;font-weight:800;color:var(--primary);flex-shrink:0}

/* ── MODAL / SHEET ── */
.modal-overlay{position:fixed;inset:0;background:rgba(0,0,0,.4);z-index:200;display:flex;align-items:flex-end;justify-content:center;opacity:0;pointer-events:none;transition:.3s}
.modal-overlay.show{opacity:1;pointer-events:all}
.modal-sheet{background:#fff;border-radius:20px 20px 0 0;width:100%;max-width:420px;padding:20px 20px 36px;transform:translateY(100%);transition:.35s cubic-bezier(.34,1.56,.64,1)}
.modal-overlay.show .modal-sheet{transform:translateY(0)}
.modal-handle{width:40px;height:4px;background:var(--border);border-radius:2px;margin:0 auto 18px}
.modal-title{font-size:17px;font-weight:800;color:var(--text1);margin-bottom:16px;display:flex;align-items:center;justify-content:space-between}
.modal-title .close-btn{width:28px;height:28px;background:#F4F6FB;border-radius:8px;display:flex;align-items:center;justify-content:center;cursor:pointer;border:none}
.modal-title .close-btn i{font-size:16px;color:var(--text2)}
.form-label{font-size:11px;font-weight:700;color:var(--text2);margin-bottom:4px;margin-top:12px;display:block}
.form-inp{width:100%;background:#F4F6FB;border:1.5px solid var(--border);border-radius:var(--radius-xs);padding:10px 12px;font-size:13px;color:var(--text1);font-family:inherit;outline:none;transition:.2s;resize:none}
.form-inp:focus{border-color:var(--primary);background:#fff}
.form-select-el{width:100%;background:#F4F6FB;border:1.5px solid var(--border);border-radius:var(--radius-xs);padding:10px 12px;font-size:13px;color:var(--text1);font-family:inherit;outline:none;appearance:none;cursor:pointer}
.priority-row{display:grid;grid-template-columns:1fr 1fr 1fr;gap:6px;margin-top:4px}
.prio-btn{padding:8px;text-align:center;border-radius:8px;font-size:12px;font-weight:700;cursor:pointer;border:2px solid transparent;transition:.2s}
.prio-btn.low{background:var(--green-light);color:var(--green)}
.prio-btn.normal{background:var(--blue-light);color:var(--blue)}
.prio-btn.high{background:var(--red-light);color:var(--red)}
.prio-btn.selected{border-color:currentColor}

/* ── PAGE HEADER (subscreen) ── */
.sub-header{display:flex;align-items:center;gap:10px;margin-bottom:16px}
.back-btn{width:32px;height:32px;background:#fff;border-radius:8px;display:flex;align-items:center;justify-content:center;cursor:pointer;border:1px solid var(--border);transition:.2s;flex-shrink:0}
.back-btn:hover{background:var(--primary-light);border-color:var(--primary)}
.back-btn i{font-size:16px;color:var(--text2)}
.sub-header h2{font-size:16px;font-weight:800;color:var(--text1)}

/* ── UPLOAD AREA ── */
.upload-area{border:2px dashed var(--primary-mid);border-radius:10px;padding:24px;text-align:center;background:var(--primary-light);cursor:pointer;transition:.2s}
.upload-area:hover{border-color:var(--primary)}
.upload-area i{font-size:32px;color:var(--primary-mid);display:block;margin-bottom:6px}
.upload-area span{font-size:12px;color:var(--text3)}

/* ── TOAST ── */
.toast{position:fixed;bottom:90px;left:50%;transform:translateX(-50%) translateY(20px);background:var(--text1);color:#fff;padding:10px 18px;border-radius:12px;font-size:13px;font-weight:600;z-index:500;opacity:0;transition:.3s;white-space:nowrap}
.toast.show{opacity:1;transform:translateX(-50%) translateY(0)}
.toast.success{background:var(--green)}
.toast.error{background:var(--red)}

/* ── NOTIF PANEL ── */
.notif-panel{position:fixed;top:40px;left:50%;transform:translateX(-50%);width:100%;max-width:420px;background:#fff;border-radius:0 0 16px 16px;box-shadow:0 8px 30px rgba(0,0,0,.15);z-index:150;padding:12px 16px 16px;display:none}
.notif-panel.show{display:block}
.notif-item{padding:10px 0;border-bottom:1px solid var(--border);display:flex;gap:10px;align-items:flex-start}
.notif-item:last-child{border-bottom:none}
.notif-ico{width:32px;height:32px;border-radius:8px;display:flex;align-items:center;justify-content:center;flex-shrink:0}
.notif-text p{font-size:12px;font-weight:600;color:var(--text1)}
.notif-text span{font-size:11px;color:var(--text3)}

/* ── PROFILE ── */
.profile-banner{background:linear-gradient(135deg,var(--navy),#1e3a5f);border-radius:var(--radius);padding:24px 20px;text-align:center;margin-bottom:16px;position:relative;overflow:hidden}
.profile-banner::before{content:'';position:absolute;top:-30px;right:-30px;width:100px;height:100px;background:rgba(249,115,22,.2);border-radius:50%}
.profile-banner::after{content:'';position:absolute;bottom:-20px;left:-20px;width:80px;height:80px;background:rgba(255,255,255,.05);border-radius:50%}
.profile-avatar{width:72px;height:72px;border-radius:50%;background:linear-gradient(135deg,var(--primary),#FB923C);margin:0 auto 10px;display:flex;align-items:center;justify-content:center;font-size:28px;font-weight:800;color:#fff;border:3px solid rgba(255,255,255,.3);position:relative;z-index:1}
.profile-banner h3{font-size:18px;font-weight:800;color:#fff;position:relative;z-index:1}
.profile-banner p{font-size:12px;color:rgba(255,255,255,.7);position:relative;z-index:1;margin-top:2px}
.profile-badge{display:inline-flex;align-items:center;gap:5px;background:rgba(249,115,22,.3);border:1px solid rgba(249,115,22,.5);border-radius:20px;padding:3px 10px;margin-top:6px;position:relative;z-index:1}
.profile-badge span{font-size:11px;color:var(--primary-mid);font-weight:700}
.profile-menu-item{display:flex;align-items:center;gap:12px;padding:14px 16px;background:#fff;border-radius:var(--radius-xs);border:1px solid var(--border);margin-bottom:8px;cursor:pointer;transition:.2s}
.profile-menu-item:hover{border-color:var(--primary);background:var(--primary-light)}
.profile-menu-item .pm-ico{width:36px;height:36px;border-radius:10px;display:flex;align-items:center;justify-content:center;flex-shrink:0}
.profile-menu-item p{font-size:13px;font-weight:600;color:var(--text1);flex:1}
.profile-menu-item i.chevron{font-size:18px;color:var(--text3)}
.logout-btn{width:100%;background:var(--red-light);color:var(--red);border:none;border-radius:var(--radius-xs);padding:13px;font-size:13px;font-weight:800;cursor:pointer;font-family:inherit;display:flex;align-items:center;justify-content:center;gap:6px;margin-top:8px;transition:.2s}
.logout-btn:hover{background:var(--red);color:#fff}

/* ── SCROLLBAR ── */
.screen::-webkit-scrollbar{width:0}
</style>
</head>
<body>

<div class="app-shell" id="app">

  <!-- STATUS BAR -->
  <div class="status-bar">
    <span>9:41</span>
    <span id="status-title">SatuAtap</span>
    <span>⚡ 100%</span>
  </div>

  <!-- ───── LOGIN SCREEN ───── -->
  <div class="screen active" id="screen-login">
    <div class="screen-inner">
      <div class="login-logo">
        <svg width="140" height="60" viewBox="0 0 140 60" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="rg1" x1="0%" y1="0%" x2="100%" y2="0%">
              <stop offset="0%" stop-color="#F97316"/>
              <stop offset="100%" stop-color="#FBBF24"/>
            </linearGradient>
            <linearGradient id="rg2" x1="0%" y1="0%" x2="100%" y2="0%">
              <stop offset="0%" stop-color="#EA580C"/>
              <stop offset="100%" stop-color="#F97316"/>
            </linearGradient>
          </defs>
          <polyline points="46,22 70,6 94,22" stroke="url(#rg1)" stroke-width="6" stroke-linecap="round" stroke-linejoin="round" fill="none"/>
          <polyline points="46,32 70,16 94,32" stroke="url(#rg2)" stroke-width="6" stroke-linecap="round" stroke-linejoin="round" fill="none"/>
          <text x="70" y="56" text-anchor="middle" font-family="'Plus Jakarta Sans',sans-serif" font-size="20" font-weight="800" fill="#1A2A4A" letter-spacing="-0.5">Satuatap</text>
        </svg>
        <p>Atur kos, lebih mudah bersama</p>
      </div>
      <div class="form-group">
        <label>Email</label>
        <input class="inp-field" type="email" id="login-email" placeholder="email@example.com" value="andi@satuatap.id">
      </div>
      <div class="form-group">
        <label>Password</label>
        <input class="inp-field" type="password" id="login-pass" placeholder="••••••••" value="password123">
      </div>
      <div style="text-align:right;margin-bottom:14px"><a href="#" style="font-size:12px;color:var(--primary);font-weight:700;text-decoration:none">Lupa Password?</a></div>
      <button class="btn-primary" onclick="doLogin()">MASUK</button>
      <p class="link-text">Belum punya akun? <a href="#" onclick="showToast('Fitur pendaftaran segera hadir!','')">Daftar disini</a></p>
      <button class="btn-outline" onclick="showToast('Daftar sebagai penghuni baru','')">DAFTAR</button>
    </div>
  </div>

  <!-- ───── HOME / DASHBOARD ───── -->
  <div class="screen" id="screen-home">
    <div class="screen-inner">
      <div class="page-header">
        <div>
          <h2>Halo, Andi 👋</h2>
          <p>Selamat datang kembali!</p>
        </div>
        <div class="bell-btn" onclick="toggleNotif()">
          <i class="ti ti-bell"></i>
          <div class="notif-dot"></div>
        </div>
      </div>

      <div class="section-title">Ringkasan Rumah</div>
      <div class="summary-card">
        <div class="lbl">Total Tagihan Bulan Ini</div>
        <div class="val">Rp 1.250.000</div>
      </div>
      <div class="stat-grid" style="margin-top:8px">
        <div class="mini-stat">
          <div class="ico orange"><i class="ti ti-users"></i></div>
          <div class="info"><p>Pembayaran</p><p>5 / 8 Lunas</p></div>
        </div>
        <div class="mini-stat">
          <div class="ico blue"><i class="ti ti-calendar"></i></div>
          <div class="info"><p>Piket Hari Ini</p><p>Andi</p></div>
        </div>
        <div class="mini-stat">
          <div class="ico green"><i class="ti ti-checkup-list"></i></div>
          <div class="info"><p>Tugas Selesai</p><p>3 / 5</p></div>
        </div>
        <div class="mini-stat">
          <div class="ico amber"><i class="ti ti-chart-bar"></i></div>
          <div class="info"><p>Voting Aktif</p><p>2</p></div>
        </div>
      </div>

      <div class="section-title">Agenda Terdekat</div>
      <div class="agenda-card">
        <div class="agenda-dot"></div>
        <div style="flex:1">
          <p>Kerja Bakti</p>
          <span>Minggu, 26 Mei 2024</span>
        </div>
        <div class="agenda-icon"><i class="ti ti-calendar-event"></i></div>
      </div>
      <div class="agenda-card">
        <div class="agenda-dot" style="background:var(--teal)"></div>
        <div style="flex:1">
          <p>Rapat Penghuni</p>
          <span>Jumat, 31 Mei 2024</span>
        </div>
        <div class="agenda-icon"><i class="ti ti-calendar-event"></i></div>
      </div>

      <div class="section-title">Quick Action</div>
      <div class="quick-actions">
        <div class="qa-btn" onclick="openModal('modal-tagihan')">
          <i class="ti ti-receipt"></i>
          <span>Tambah Tagihan</span>
        </div>
        <div class="qa-btn" onclick="openModal('modal-tugas')">
          <i class="ti ti-clipboard-list"></i>
          <span>Tambah Tugas</span>
        </div>
        <div class="qa-btn" onclick="openModal('modal-voting')">
          <i class="ti ti-chart-pie"></i>
          <span>Buat Voting</span>
        </div>
      </div>
    </div>
  </div>

  <!-- ───── FINANCE SCREEN ───── -->
  <div class="screen" id="screen-finance">
    <div class="screen-inner">
      <div class="page-header">
        <div><h2>Finance</h2><p>Manajemen keuangan kos</p></div>
      </div>
      <div class="tab-bar">
        <div class="tab active" onclick="switchFinTab(this,'fin-tagihan')">Tagihan</div>
        <div class="tab" onclick="switchFinTab(this,'fin-pembayaran')">Pembayaran</div>
      </div>

      <!-- Tagihan -->
      <div id="fin-tagihan">
        <div class="total-card">
          <p>Total Tagihan Bulan Ini</p>
          <h2>Rp 1.250.000</h2>
        </div>
        <p style="font-size:11px;font-weight:700;color:var(--text2);text-transform:uppercase;letter-spacing:.07em;margin-bottom:8px">Daftar Tagihan</p>
        <div id="tagihan-list">
          <div class="bill-item">
            <div class="bill-icon orange"><i class="ti ti-bolt"></i></div>
            <div class="bill-info"><p>Listrik</p><span>Jatuh tempo: 25 Mei 2024</span></div>
            <div class="bill-right"><p>Rp 350.000</p><span class="badge unpaid">Belum Lunas</span></div>
          </div>
          <div class="bill-item">
            <div class="bill-icon blue"><i class="ti ti-droplet"></i></div>
            <div class="bill-info"><p>Air</p><span>Jatuh tempo: 25 Mei 2024</span></div>
            <div class="bill-right"><p>Rp 150.000</p><span class="badge paid">Lunas</span></div>
          </div>
          <div class="bill-item">
            <div class="bill-icon teal"><i class="ti ti-wifi"></i></div>
            <div class="bill-info"><p>Internet</p><span>Jatuh tempo: 25 Mei 2024</span></div>
            <div class="bill-right"><p>Rp 200.000</p><span class="badge unpaid">Belum Lunas</span></div>
          </div>
          <div class="bill-item">
            <div class="bill-icon green"><i class="ti ti-sparkles"></i></div>
            <div class="bill-info"><p>Kebersihan</p><span>Jatuh tempo: 25 Mei 2024</span></div>
            <div class="bill-right"><p>Rp 100.000</p><span class="badge paid">Lunas</span></div>
          </div>
          <div class="bill-item">
            <div class="bill-icon amber"><i class="ti ti-home"></i></div>
            <div class="bill-info"><p>Sewa Kamar</p><span>Jatuh tempo: 25 Mei 2024</span></div>
            <div class="bill-right"><p>Rp 450.000</p><span class="badge unpaid">Belum Lunas</span></div>
          </div>
        </div>
        <button class="add-btn" onclick="openModal('modal-tagihan')"><i class="ti ti-plus"></i> Tambah Tagihan</button>
      </div>

      <!-- Pembayaran -->
      <div id="fin-pembayaran" style="display:none">
        <div style="background:#F4F6FB;border-radius:var(--radius-sm);padding:14px;margin-bottom:14px">
          <p style="font-size:12px;font-weight:700;color:var(--text2);margin-bottom:8px">Status Pembayaran Penghuni</p>
          <div id="payment-list">
            <div class="sched-item">
              <div class="avatar av-o">AN</div>
              <div class="sched-info"><p>Andi (Kamu)</p><span>Kamar 1</span></div>
              <span class="badge paid">Lunas</span>
            </div>
            <div class="sched-item">
              <div class="avatar av-t">SI</div>
              <div class="sched-info"><p>Siti</p><span>Kamar 2</span></div>
              <span class="badge paid">Lunas</span>
            </div>
            <div class="sched-item">
              <div class="avatar av-b">DO</div>
              <div class="sched-info"><p>Doni</p><span>Kamar 3</span></div>
              <span class="badge unpaid">Belum</span>
            </div>
            <div class="sched-item">
              <div class="avatar av-g">RI</div>
              <div class="sched-info"><p>Rina</p><span>Kamar 4</span></div>
              <span class="badge partial">Sebagian</span>
            </div>
            <div class="sched-item">
              <div class="avatar av-a">FA</div>
              <div class="sched-info"><p>Fahmi</p><span>Kamar 5</span></div>
              <span class="badge paid">Lunas</span>
            </div>
          </div>
        </div>
        <button class="add-btn" onclick="openModal('modal-konfirmasi')"><i class="ti ti-upload"></i> Upload Bukti Bayar</button>
      </div>
    </div>
  </div>

  <!-- ───── TASKS SCREEN ───── -->
  <div class="screen" id="screen-tasks">
    <div class="screen-inner">
      <div class="page-header">
        <div><h2>Tasks</h2><p>Jadwal & daftar tugas</p></div>
      </div>
      <div class="tab-bar">
        <div class="tab active" onclick="switchTaskTab(this,'tasks-piket')">Jadwal Piket</div>
        <div class="tab" onclick="switchTaskTab(this,'tasks-daftar')">Daftar Tugas</div>
      </div>

      <!-- Jadwal Piket -->
      <div id="tasks-piket">
        <p class="section-title">Jadwal Piket Minggu Ini</p>
        <div class="sched-item">
          <div class="avatar av-t">BU</div>
          <div class="sched-info"><p>Budi</p><span>Senin</span></div>
        </div>
        <div class="sched-item">
          <div class="avatar av-g">SI</div>
          <div class="sched-info"><p>Siti</p><span>Selasa</span></div>
        </div>
        <div class="sched-item" style="background:var(--primary-light);margin:0 -4px;padding:10px 4px;border-radius:8px">
          <div class="avatar av-o">AN</div>
          <div class="sched-info"><p>Andi <span style="color:var(--primary);font-size:10px">(Kamu)</span></p><span>Rabu</span></div>
          <span class="today-badge">Hari Ini</span>
        </div>
        <div class="sched-item">
          <div class="avatar av-b">DO</div>
          <div class="sched-info"><p>Doni</p><span>Kamis</span></div>
        </div>
        <div class="sched-item">
          <div class="avatar av-r">RI</div>
          <div class="sched-info"><p>Rina</p><span>Jumat</span></div>
        </div>
        <div class="sched-item">
          <div class="avatar av-a">FA</div>
          <div class="sched-info"><p>Fahmi</p><span>Sabtu</span></div>
        </div>
        <div class="sched-item">
          <div class="avatar av-g">BA</div>
          <div class="sched-info"><p>Bagas</p><span>Minggu</span></div>
        </div>
        <button class="add-btn" onclick="openModal('modal-tugas')"><i class="ti ti-plus"></i> Tambah Tugas</button>
      </div>

      <!-- Daftar Tugas -->
      <div id="tasks-daftar" style="display:none">
        <p class="section-title">Tugas Aktif</p>
        <div id="task-list">
          <div class="task-list-item" onclick="toggleTask(this)">
            <div class="task-check"><i class="ti ti-check" style="display:none"></i></div>
            <div class="task-info"><p>Bersih Kamar Mandi</p><span>Andi · Normal · 25 Mei</span></div>
            <span class="badge unpaid" style="font-size:9px">Aktif</span>
          </div>
          <div class="task-list-item" onclick="toggleTask(this)">
            <div class="task-check done"><i class="ti ti-check"></i></div>
            <div class="task-info"><p style="text-decoration:line-through;color:var(--text3)">Cuci Piring Bersama</p><span>Siti · Low · 24 Mei</span></div>
            <span class="badge paid" style="font-size:9px">Selesai</span>
          </div>
          <div class="task-list-item" onclick="toggleTask(this)">
            <div class="task-check"><i class="ti ti-check" style="display:none"></i></div>
            <div class="task-info"><p>Bayar Listrik</p><span>Doni · High · 25 Mei</span></div>
            <span class="badge" style="background:var(--red-light);color:var(--red);font-size:9px">Urgent</span>
          </div>
          <div class="task-list-item" onclick="toggleTask(this)">
            <div class="task-check done"><i class="ti ti-check"></i></div>
            <div class="task-info"><p style="text-decoration:line-through;color:var(--text3)">Bersihkan Kulkas</p><span>Rina · Normal · 22 Mei</span></div>
            <span class="badge paid" style="font-size:9px">Selesai</span>
          </div>
          <div class="task-list-item" onclick="toggleTask(this)">
            <div class="task-check"><i class="ti ti-check" style="display:none"></i></div>
            <div class="task-info"><p>Servis AC Kamar 3</p><span>Fahmi · High · 30 Mei</span></div>
            <span class="badge unpaid" style="font-size:9px">Aktif</span>
          </div>
        </div>
        <button class="add-btn" onclick="openModal('modal-tugas')"><i class="ti ti-plus"></i> Tambah Tugas</button>
      </div>
    </div>
  </div>

  <!-- ───── COMMUNITY SCREEN ───── -->
  <div class="screen" id="screen-community">
    <div class="screen-inner">
      <div class="page-header">
        <div><h2>Community</h2><p>Forum & kegiatan bersama</p></div>
      </div>
      <div class="tab-bar">
        <div class="tab active" onclick="switchComTab(this,'com-voting')">Voting</div>
        <div class="tab" onclick="switchComTab(this,'com-agenda')">Agenda</div>
        <div class="tab" onclick="switchComTab(this,'com-peraturan')">Peraturan</div>
      </div>

      <!-- Voting -->
      <div id="com-voting">
        <p class="section-title">Voting Aktif</p>
        <div class="vote-card">
          <h4>Langganan WiFi Bulan Depan?</h4>
          <div class="timer"><i class="ti ti-clock"></i>Berakhir dalam 2 hari</div>
          <div class="vote-opt">
            <div class="vote-opt-label"><span>IndiHome</span><span>60% (6)</span></div>
            <div class="vote-bar"><div class="fill fill-orange" style="width:60%"></div></div>
          </div>
          <div class="vote-opt">
            <div class="vote-opt-label"><span>Biznet</span><span>30% (3)</span></div>
            <div class="vote-bar"><div class="fill fill-teal" style="width:30%"></div></div>
          </div>
          <div class="vote-opt">
            <div class="vote-opt-label"><span>Lainnya</span><span>10% (1)</span></div>
            <div class="vote-bar"><div class="fill fill-gray" style="width:10%"></div></div>
          </div>
          <div class="vote-detail-btn" onclick="showToast('Detail voting ditampilkan','')">Lihat Detail →</div>
        </div>
        <div class="vote-card">
          <h4>Jadwal Kerja Bakti?</h4>
          <div class="timer"><i class="ti ti-clock"></i>Berakhir dalam 5 hari</div>
          <div class="vote-opt">
            <div class="vote-opt-label"><span>Sabtu Pagi</span><span>50% (4)</span></div>
            <div class="vote-bar"><div class="fill fill-orange" style="width:50%"></div></div>
          </div>
          <div class="vote-opt">
            <div class="vote-opt-label"><span>Minggu Pagi</span><span>38% (3)</span></div>
            <div class="vote-bar"><div class="fill fill-teal" style="width:38%"></div></div>
          </div>
          <div class="vote-opt">
            <div class="vote-opt-label"><span>Minggu Sore</span><span>12% (1)</span></div>
            <div class="vote-bar"><div class="fill fill-gray" style="width:12%"></div></div>
          </div>
          <div class="vote-detail-btn" onclick="showToast('Detail voting ditampilkan','')">Lihat Detail →</div>
        </div>
        <button class="add-btn" onclick="openModal('modal-voting')"><i class="ti ti-plus"></i> Buat Voting Baru</button>
      </div>

      <!-- Agenda -->
      <div id="com-agenda" style="display:none">
        <p class="section-title">Agenda Mendatang</p>
        <div class="agenda-list-item">
          <div class="agenda-date-box"><p>26</p><span>Mei</span></div>
          <div style="flex:1">
            <p style="font-size:13px;font-weight:700;color:var(--text1)">Kerja Bakti</p>
            <span style="font-size:11px;color:var(--text3)">08:00 WIB · Seluruh Penghuni</span>
          </div>
        </div>
        <div class="agenda-list-item">
          <div class="agenda-date-box"><p>31</p><span>Mei</span></div>
          <div style="flex:1">
            <p style="font-size:13px;font-weight:700;color:var(--text1)">Rapat Penghuni Bulanan</p>
            <span style="font-size:11px;color:var(--text3)">19:00 WIB · Ruang Tamu</span>
          </div>
        </div>
        <div class="agenda-list-item">
          <div class="agenda-date-box"><p>10</p><span>Jun</span></div>
          <div style="flex:1">
            <p style="font-size:13px;font-weight:700;color:var(--text1)">Pemilihan Ketua Baru</p>
            <span style="font-size:11px;color:var(--text3)">20:00 WIB · Seluruh Penghuni</span>
          </div>
        </div>
        <button class="add-btn" onclick="openModal('modal-agenda')"><i class="ti ti-plus"></i> Tambah Agenda</button>
      </div>

      <!-- Peraturan -->
      <div id="com-peraturan" style="display:none">
        <div style="background:var(--primary-light);border-radius:var(--radius-sm);padding:12px 14px;margin-bottom:14px;border:1.5px solid var(--primary-mid);display:flex;align-items:center;gap:10px">
          <i class="ti ti-shield-check" style="font-size:22px;color:var(--primary)"></i>
          <div>
            <p style="font-size:13px;font-weight:700;color:var(--primary)">Aturan Bersama</p>
            <span style="font-size:11px;color:var(--text2)">Berlaku untuk semua penghuni</span>
          </div>
        </div>
        <ol class="rules-list">
          <li><div class="rule-num">1</div>Buang sampah pada tempatnya</li>
          <li><div class="rule-num">2</div>Hemat listrik dan air</li>
          <li><div class="rule-num">3</div>Tamu menginap maksimal 2 hari</li>
          <li><div class="rule-num">4</div>Jaga kebersihan bersama</li>
          <li><div class="rule-num">5</div>Tidak membuat keributan setelah jam 22.00</li>
          <li><div class="rule-num">6</div>Bayar iuran paling lambat tanggal 25</li>
        </ol>
        <button class="add-btn" style="background:var(--navy)" onclick="showToast('Edit peraturan (khusus Ketua)','')"><i class="ti ti-pencil"></i> Edit Peraturan</button>
        <p style="text-align:center;font-size:11px;color:var(--text3);margin-top:6px">(Khusus Ketua/Admin)</p>
      </div>
    </div>
  </div>

  <!-- ───── PROFILE SCREEN ───── -->
  <div class="screen" id="screen-profile">
    <div class="screen-inner">
      <div class="profile-banner">
        <div class="profile-avatar">A</div>
        <h3>Andi Pratama</h3>
        <p>andi@satuatap.id</p>
        <div class="profile-badge"><i class="ti ti-star" style="font-size:12px;color:var(--primary-mid)"></i><span>Penghuni Aktif</span></div>
      </div>

      <p class="section-title">Informasi Kamar</p>
      <div class="profile-menu-item" onclick="showToast('Kamar 1 · Lantai 1','')">
        <div class="pm-ico orange"><i class="ti ti-door" style="font-size:18px;color:var(--primary)"></i></div>
        <div><p>Kamar 1</p><span style="font-size:11px;color:var(--text3)">Lantai 1 · Bergabung sejak Jan 2024</span></div>
        <i class="ti ti-chevron-right chevron"></i>
      </div>

      <p class="section-title">Pengaturan</p>
      <div class="profile-menu-item" onclick="showToast('Edit profil dibuka','')">
        <div class="pm-ico blue"><i class="ti ti-user-edit" style="font-size:18px;color:var(--blue)"></i></div>
        <p>Edit Profil</p>
        <i class="ti ti-chevron-right chevron"></i>
      </div>
      <div class="profile-menu-item" onclick="showToast('Pengaturan notifikasi','')">
        <div class="pm-ico amber"><i class="ti ti-bell" style="font-size:18px;color:var(--amber)"></i></div>
        <p>Notifikasi</p>
        <i class="ti ti-chevron-right chevron"></i>
      </div>
      <div class="profile-menu-item" onclick="showToast('Ubah password','')">
        <div class="pm-ico teal"><i class="ti ti-lock" style="font-size:18px;color:var(--teal)"></i></div>
        <p>Keamanan & Password</p>
        <i class="ti ti-chevron-right chevron"></i>
      </div>
      <div class="profile-menu-item" onclick="showToast('Bantuan & FAQ dibuka','')">
        <div class="pm-ico green"><i class="ti ti-help" style="font-size:18px;color:var(--green)"></i></div>
        <p>Bantuan & FAQ</p>
        <i class="ti ti-chevron-right chevron"></i>
      </div>

      <button class="logout-btn" onclick="doLogout()"><i class="ti ti-logout" style="font-size:16px"></i> Keluar</button>
      <p style="text-align:center;font-size:11px;color:var(--text3);margin-top:12px">SatuAtap v1.0 · © 2024</p>
    </div>
  </div>

  <!-- ───── BOTTOM NAV ───── -->
  <nav class="bottom-nav" id="bottom-nav" style="display:none">
    <div class="nav-item active" onclick="goTo('home',this)">
      <i class="ti ti-home"></i><span>Home</span>
    </div>
    <div class="nav-item" onclick="goTo('finance',this)">
      <i class="ti ti-wallet"></i><span>Finance</span>
    </div>
    <div class="nav-item" onclick="goTo('tasks',this)">
      <i class="ti ti-checkup-list"></i><span>Tasks</span>
    </div>
    <div class="nav-item" onclick="goTo('community',this)">
      <i class="ti ti-users"></i><span>Community</span>
    </div>
    <div class="nav-item" onclick="goTo('profile',this)">
      <i class="ti ti-user-circle"></i><span>Profil</span>
    </div>
  </nav>

</div><!-- /app-shell -->

<!-- ───── MODALS ───── -->

<!-- Tambah Tagihan -->
<div class="modal-overlay" id="modal-tagihan" onclick="closeOnOverlay(event,'modal-tagihan')">
  <div class="modal-sheet">
    <div class="modal-handle"></div>
    <div class="modal-title">Tambah Tagihan
      <button class="close-btn" onclick="closeModal('modal-tagihan')"><i class="ti ti-x"></i></button>
    </div>
    <label class="form-label">Nama Tagihan</label>
    <input class="form-inp" placeholder="Contoh: Listrik" id="t-nama">
    <label class="form-label">Nominal (Rp)</label>
    <input class="form-inp" type="number" placeholder="350000" id="t-nominal">
    <label class="form-label">Jatuh Tempo</label>
    <input class="form-inp" type="date" id="t-date">
    <label class="form-label">Dibagi ke</label>
    <select class="form-select-el" id="t-bagi">
      <option>Semua Penghuni</option>
      <option>Kamar 1 - Andi</option>
      <option>Kamar 2 - Siti</option>
    </select>
    <label class="form-label">Catatan (opsional)</label>
    <textarea class="form-inp" rows="2" placeholder="Tulis catatan..." id="t-catatan"></textarea>
    <button class="btn-primary" style="margin-top:16px" onclick="submitTagihan()">SIMPAN TAGIHAN</button>
  </div>
</div>

<!-- Konfirmasi Pembayaran -->
<div class="modal-overlay" id="modal-konfirmasi" onclick="closeOnOverlay(event,'modal-konfirmasi')">
  <div class="modal-sheet">
    <div class="modal-handle"></div>
    <div class="modal-title">Upload Bukti Bayar
      <button class="close-btn" onclick="closeModal('modal-konfirmasi')"><i class="ti ti-x"></i></button>
    </div>
    <div style="background:var(--primary-light);border-radius:var(--radius-xs);padding:12px 14px;margin-bottom:4px">
      <p style="font-size:16px;font-weight:800;color:var(--primary)">Listrik</p>
      <p style="font-size:20px;font-weight:800;color:var(--text1);margin:2px 0">Rp 350.000</p>
      <p style="font-size:12px;color:var(--text2)">Jatuh tempo: 25 Mei 2024</p>
      <span class="badge unpaid" style="margin-top:4px">Belum Lunas</span>
    </div>
    <label class="form-label">Upload Bukti Transfer</label>
    <div class="upload-area" onclick="showToast('Pilih foto dari galeri','')">
      <i class="ti ti-photo"></i>
      <span>Klik untuk pilih atau ambil foto</span>
    </div>
    <label class="form-label">Catatan (opsional)</label>
    <textarea class="form-inp" rows="2" placeholder="Tulis catatan..."></textarea>
    <button class="btn-primary" style="margin-top:16px" onclick="submitKonfirmasi()">KIRIM KONFIRMASI</button>
  </div>
</div>

<!-- Tambah Tugas -->
<div class="modal-overlay" id="modal-tugas" onclick="closeOnOverlay(event,'modal-tugas')">
  <div class="modal-sheet">
    <div class="modal-handle"></div>
    <div class="modal-title">Tambah Tugas
      <button class="close-btn" onclick="closeModal('modal-tugas')"><i class="ti ti-x"></i></button>
    </div>
    <label class="form-label">Nama Tugas</label>
    <input class="form-inp" placeholder="Contoh: Bersih Kamar Mandi" id="tu-nama">
    <label class="form-label">Penanggung Jawab</label>
    <select class="form-select-el" id="tu-pj">
      <option value="">Pilih Penghuni</option>
      <option>Andi</option><option>Siti</option><option>Doni</option><option>Rina</option><option>Fahmi</option>
    </select>
    <label class="form-label">Tanggal</label>
    <input class="form-inp" type="date" id="tu-date">
    <label class="form-label">Prioritas</label>
    <div class="priority-row">
      <div class="prio-btn low" onclick="selectPrio(this)">Low</div>
      <div class="prio-btn normal selected" onclick="selectPrio(this)">Normal</div>
      <div class="prio-btn high" onclick="selectPrio(this)">High</div>
    </div>
    <label class="form-label">Catatan (opsional)</label>
    <textarea class="form-inp" rows="2" placeholder="Tulis catatan..." id="tu-catatan"></textarea>
    <button class="btn-primary" style="margin-top:16px" onclick="submitTugas()">SIMPAN TUGAS</button>
  </div>
</div>

<!-- Buat Voting -->
<div class="modal-overlay" id="modal-voting" onclick="closeOnOverlay(event,'modal-voting')">
  <div class="modal-sheet">
    <div class="modal-handle"></div>
    <div class="modal-title">Buat Voting Baru
      <button class="close-btn" onclick="closeModal('modal-voting')"><i class="ti ti-x"></i></button>
    </div>
    <label class="form-label">Judul Voting</label>
    <input class="form-inp" placeholder="Contoh: Langganan WiFi" id="v-judul">
    <label class="form-label">Deskripsi (opsional)</label>
    <textarea class="form-inp" rows="2" placeholder="Tulis deskripsi..." id="v-desc"></textarea>
    <label class="form-label">Opsi Pilihan</label>
    <div id="voting-options">
      <input class="form-inp" style="margin-bottom:6px" placeholder="Opsi 1">
      <input class="form-inp" style="margin-bottom:6px" placeholder="Opsi 2">
    </div>
    <div style="text-align:center;margin:6px 0">
      <span style="font-size:12px;color:var(--primary);font-weight:700;cursor:pointer" onclick="addVotingOption()">
        <i class="ti ti-plus" style="font-size:12px"></i> Tambah Opsi
      </span>
    </div>
    <label class="form-label">Berakhir Pada</label>
    <input class="form-inp" type="date" id="v-deadline">
    <button class="btn-primary" style="margin-top:16px" onclick="submitVoting()">BUAT VOTING</button>
  </div>
</div>

<!-- Tambah Agenda -->
<div class="modal-overlay" id="modal-agenda" onclick="closeOnOverlay(event,'modal-agenda')">
  <div class="modal-sheet">
    <div class="modal-handle"></div>
    <div class="modal-title">Tambah Agenda
      <button class="close-btn" onclick="closeModal('modal-agenda')"><i class="ti ti-x"></i></button>
    </div>
    <label class="form-label">Judul Agenda</label>
    <input class="form-inp" placeholder="Contoh: Kerja Bakti" id="ag-judul">
    <label class="form-label">Tanggal</label>
    <input class="form-inp" type="date" id="ag-date">
    <label class="form-label">Waktu</label>
    <input class="form-inp" type="time" id="ag-time">
    <label class="form-label">Deskripsi</label>
    <textarea class="form-inp" rows="3" placeholder="Tulis deskripsi..." id="ag-desc"></textarea>
    <button class="btn-primary" style="margin-top:16px" onclick="submitAgenda()">SIMPAN AGENDA</button>
  </div>
</div>

<!-- NOTIF PANEL -->
<div class="notif-panel" id="notif-panel">
  <p style="font-size:12px;font-weight:700;color:var(--text2);margin-bottom:8px;text-transform:uppercase;letter-spacing:.05em">Notifikasi</p>
  <div class="notif-item">
    <div class="notif-ico red"><i class="ti ti-bolt" style="color:var(--red);font-size:16px"></i></div>
    <div class="notif-text"><p>Tagihan listrik jatuh tempo besok!</p><span>5 menit yang lalu</span></div>
  </div>
  <div class="notif-item">
    <div class="notif-ico blue"><i class="ti ti-chart-pie" style="color:var(--blue);font-size:16px"></i></div>
    <div class="notif-text"><p>Voting WiFi berakhir dalam 2 hari</p><span>1 jam yang lalu</span></div>
  </div>
  <div class="notif-item">
    <div class="notif-ico green"><i class="ti ti-check" style="color:var(--green);font-size:16px"></i></div>
    <div class="notif-text"><p>Doni telah mengkonfirmasi pembayaran</p><span>3 jam yang lalu</span></div>
  </div>
</div>

<!-- TOAST -->
<div class="toast" id="toast"></div>

<script>
// ── NAV ──
function goTo(screen, el) {
  document.querySelectorAll('.screen').forEach(s => s.classList.remove('active'));
  document.getElementById('screen-' + screen).classList.add('active');
  document.querySelectorAll('.nav-item').forEach(n => n.classList.remove('active'));
  el.classList.add('active');
  document.getElementById('status-title').textContent =
    {home:'Beranda',finance:'Finance',tasks:'Tasks',community:'Community',profile:'Profil'}[screen];
  closeNotif();
}

// ── LOGIN ──
function doLogin() {
  const email = document.getElementById('login-email').value;
  const pass = document.getElementById('login-pass').value;
  if (!email || !pass) { showToast('Isi email dan password dulu!','error'); return; }
  showToast('Selamat datang, Andi! 👋','success');
  setTimeout(() => {
    document.getElementById('screen-login').classList.remove('active');
    document.getElementById('screen-home').classList.add('active');
    document.getElementById('bottom-nav').style.display = 'flex';
    document.getElementById('status-title').textContent = 'Beranda';
  }, 700);
}

function doLogout() {
  document.querySelectorAll('.screen').forEach(s => s.classList.remove('active'));
  document.getElementById('screen-login').classList.add('active');
  document.getElementById('bottom-nav').style.display = 'none';
  document.getElementById('status-title').textContent = 'SatuAtap';
  showToast('Berhasil keluar','');
}

// ── TAB SWITCHES ──
function switchFinTab(el, id) {
  document.querySelectorAll('#screen-finance .tab').forEach(t => t.classList.remove('active'));
  el.classList.add('active');
  ['fin-tagihan','fin-pembayaran'].forEach(i => document.getElementById(i).style.display='none');
  document.getElementById(id).style.display='block';
}
function switchTaskTab(el, id) {
  document.querySelectorAll('#screen-tasks .tab').forEach(t => t.classList.remove('active'));
  el.classList.add('active');
  ['tasks-piket','tasks-daftar'].forEach(i => document.getElementById(i).style.display='none');
  document.getElementById(id).style.display='block';
}
function switchComTab(el, id) {
  document.querySelectorAll('#screen-community .tab').forEach(t => t.classList.remove('active'));
  el.classList.add('active');
  ['com-voting','com-agenda','com-peraturan'].forEach(i => document.getElementById(i).style.display='none');
  document.getElementById(id).style.display='block';
}

// ── MODALS ──
function openModal(id) { document.getElementById(id).classList.add('show'); }
function closeModal(id) { document.getElementById(id).classList.remove('show'); }
function closeOnOverlay(e, id) { if(e.target === document.getElementById(id)) closeModal(id); }

// ── PRIORITY SELECTOR ──
function selectPrio(el) {
  document.querySelectorAll('#modal-tugas .prio-btn').forEach(b => b.classList.remove('selected'));
  el.classList.add('selected');
}

// ── ADD VOTING OPTION ──
function addVotingOption() {
  const cont = document.getElementById('voting-options');
  const count = cont.children.length + 1;
  const inp = document.createElement('input');
  inp.className = 'form-inp'; inp.style.marginBottom = '6px';
  inp.placeholder = 'Opsi ' + count;
  cont.appendChild(inp);
}

// ── TASK TOGGLE ──
function toggleTask(el) {
  const check = el.querySelector('.task-check');
  const title = el.querySelector('.task-info p');
  const badge = el.querySelector('.badge');
  const done = check.classList.toggle('done');
  check.querySelector('i').style.display = done ? '' : 'none';
  title.style.textDecoration = done ? 'line-through' : '';
  title.style.color = done ? 'var(--text3)' : '';
  badge.className = 'badge ' + (done ? 'paid' : 'unpaid');
  badge.textContent = done ? 'Selesai' : 'Aktif';
  badge.style.fontSize = '9px';
  showToast(done ? '✓ Tugas diselesaikan' : 'Tugas diaktifkan kembali', done ? 'success' : '');
}

// ── FORM SUBMISSIONS ──
function submitTagihan() {
  const nama = document.getElementById('t-nama').value;
  const nominal = document.getElementById('t-nominal').value;
  if (!nama || !nominal) { showToast('Isi nama dan nominal tagihan!','error'); return; }
  const list = document.getElementById('tagihan-list');
  const item = document.createElement('div');
  item.className = 'bill-item';
  item.innerHTML = `<div class="bill-icon orange"><i class="ti ti-receipt"></i></div>
    <div class="bill-info"><p>${nama}</p><span>Baru ditambahkan</span></div>
    <div class="bill-right"><p>Rp ${parseInt(nominal).toLocaleString('id')}</p><span class="badge unpaid">Belum Lunas</span></div>`;
  list.appendChild(item);
  closeModal('modal-tagihan');
  document.getElementById('t-nama').value=''; document.getElementById('t-nominal').value='';
  showToast('Tagihan berhasil ditambahkan!','success');
}

function submitKonfirmasi() {
  closeModal('modal-konfirmasi');
  showToast('Bukti pembayaran terkirim!','success');
}

function submitTugas() {
  const nama = document.getElementById('tu-nama').value;
  const pj = document.getElementById('tu-pj').value;
  if (!nama || !pj) { showToast('Isi nama tugas dan penghuni!','error'); return; }
  const sel = document.querySelector('#modal-tugas .prio-btn.selected');
  const prio = sel ? sel.textContent : 'Normal';
  const list = document.getElementById('task-list');
  const item = document.createElement('div');
  item.className = 'task-list-item'; item.onclick = function(){toggleTask(this)};
  item.innerHTML = `<div class="task-check"><i class="ti ti-check" style="display:none"></i></div>
    <div class="task-info"><p>${nama}</p><span>${pj} · ${prio} · Baru</span></div>
    <span class="badge unpaid" style="font-size:9px">Aktif</span>`;
  list.appendChild(item);
  closeModal('modal-tugas');
  document.getElementById('tu-nama').value='';
  showToast('Tugas berhasil ditambahkan!','success');
}

function submitVoting() {
  const judul = document.getElementById('v-judul').value;
  if (!judul) { showToast('Isi judul voting dulu!','error'); return; }
  closeModal('modal-voting');
  document.getElementById('v-judul').value='';
  showToast('Voting berhasil dibuat!','success');
}

function submitAgenda() {
  const judul = document.getElementById('ag-judul').value;
  if (!judul) { showToast('Isi judul agenda dulu!','error'); return; }
  closeModal('modal-agenda');
  document.getElementById('ag-judul').value='';
  showToast('Agenda berhasil ditambahkan!','success');
}

// ── NOTIF ──
let notifOpen = false;
function toggleNotif() {
  notifOpen = !notifOpen;
  document.getElementById('notif-panel').classList.toggle('show', notifOpen);
}
function closeNotif() { notifOpen = false; document.getElementById('notif-panel').classList.remove('show'); }

// ── TOAST ──
let toastTimer;
function showToast(msg, type='') {
  const t = document.getElementById('toast');
  t.textContent = msg;
  t.className = 'toast' + (type ? ' ' + type : '');
  t.classList.add('show');
  clearTimeout(toastTimer);
  toastTimer = setTimeout(() => t.classList.remove('show'), 2500);
}

// close notif when clicking outside
document.addEventListener('click', e => {
  const panel = document.getElementById('notif-panel');
  const bell = document.querySelector('.bell-btn');
  if (notifOpen && !panel.contains(e.target) && (!bell || !bell.contains(e.target))) closeNotif();
});
</script>
</body>
</html>
