
:root {
  --red: #DB161B;
  --green: #008000;
  --blue: #1E2A7A;
  --white: #FFFFFF;
  --gray: #F5F5F5;
  --dark: #333333;
  --text2: #555555;
  --text3: #999999;
  --border: #DDDDDD;
  --border2: #CCCCCC;
  --amber: #c07800;
  --purple: #7b3fa0;
  --radius: 6px;
  --radius-lg: 10px;
  --sans: "IBM Plex Sans Arabic", "Segoe UI", Tahoma, sans-serif;
  --mono: "JetBrains Mono", monospace;
}
* { box-sizing:border-box; margin:0; padding:0 }
html { scroll-behavior:smooth }
body { background:var(--gray); color:var(--dark); font-family:var(--sans); font-size:14px; line-height:1.6; min-height:100vh }
::-webkit-scrollbar { width:6px; height:6px }
::-webkit-scrollbar-track { background:var(--gray) }
::-webkit-scrollbar-thumb { background:var(--red); border-radius:3px }

/* ── PAGES ── */
.page { display:none; min-height:100vh }
.page.active { display:block }

/* ══ LOGIN PAGE ══ */
#page-login { display:none; min-height:100vh }
#page-login.active { display:flex }
.login-brand {
  flex:1; background:linear-gradient(145deg,#1E2A7A 0%,#2a3a9a 60%,#1a4a8a 100%);
  display:flex; flex-direction:column; align-items:center; justify-content:center;
  padding:60px 40px; min-height:100vh;
}
.login-brand img { width:100%; display:block }
.login-brand .glitch-wrap { margin-bottom:36px }
.login-brand h1 { color:#fff; font-size:26px; font-weight:700; text-align:center; margin-bottom:8px }
.login-brand p { color:rgba(255,255,255,.6); font-size:12px; font-family:var(--mono); text-align:center }
.login-panel {
  width:440px; flex-shrink:0; background:#fff;
  display:flex; align-items:flex-start; justify-content:center;
  padding:32px 36px; height:100vh; overflow-y:auto;
  box-shadow:-4px 0 24px rgba(0,0,0,0.1);
}
.login-inner { width:100%; max-width:360px; padding:20px 0 40px }
.login-inner h2 { font-size:22px; font-weight:700; color:var(--dark); margin-bottom:6px }
.login-inner > p { font-size:13px; color:var(--text2); margin-bottom:28px }
.form-label { display:block; font-size:11px; font-weight:700; color:var(--text2); margin-bottom:6px; text-transform:uppercase; letter-spacing:.5px }
.form-input { width:100%; background:var(--gray); border:1px solid var(--border); border-radius:var(--radius); padding:10px 14px; color:var(--dark); font-family:var(--sans); font-size:14px; outline:none; transition:border-color .2s; margin-bottom:16px }
.form-input:focus { border-color:var(--blue) }
.btn-login { width:100%; background:var(--blue); color:#fff; border:none; border-radius:var(--radius); padding:12px; font-family:var(--sans); font-size:14px; font-weight:600; cursor:pointer; transition:background .2s; margin-top:4px }
.btn-login:hover { background:var(--green) }
.login-error { color:var(--red); font-size:12px; margin-top:8px; display:none }
.login-divider { text-align:center; color:var(--text3); font-size:11px; margin:20px 0 10px; font-family:var(--mono) }
.demo-accounts { display:grid; gap:8px }
.demo-card {
  background:var(--gray); border:1px solid var(--border); border-radius:var(--radius);
  padding:10px 12px; cursor:pointer; display:flex; align-items:center; justify-content:space-between;
  transition:border-color .2s, background .2s;
}
.demo-card:hover { border-color:var(--blue); background:rgba(30,42,122,.05) }
.demo-card-left { display:flex; align-items:center; gap:10px }
.demo-card-icon { font-size:18px; flex-shrink:0 }
.demo-card-name { font-size:12px; font-weight:600; color:var(--dark) }
.demo-card-dept { font-size:10px; color:var(--text3); margin-top:1px }
.demo-card-badge { background:rgba(30,42,122,.1); color:var(--blue); padding:2px 8px; border-radius:10px; font-size:10px; font-weight:700; white-space:nowrap }

/* ══ APP SHELL ══ */
.shell { display:grid; grid-template-columns:240px 1fr; grid-template-rows:56px 1fr; min-height:100vh }
.topbar { grid-column:1/-1; background:var(--blue); display:flex; align-items:center; padding:0 24px; gap:16px; position:sticky; top:0; z-index:100 }
.topbar-title { font-size:14px; font-weight:700; color:#fff }
.topbar-sub { font-size:10px; color:rgba(255,255,255,.6); font-family:var(--mono) }
.topbar-spacer { flex:1 }
.topbar-user { display:flex; align-items:center; gap:10px; padding:6px 12px; background:rgba(255,255,255,.15); border:1px solid rgba(255,255,255,.25); border-radius:var(--radius) }
.topbar-avatar { width:28px; height:28px; background:rgba(255,255,255,.25); border-radius:50%; display:flex; align-items:center; justify-content:center; font-size:12px; font-weight:700; color:#fff; flex-shrink:0 }
.topbar-uname { font-size:12px; font-weight:600; color:#fff }
.topbar-urole { font-size:10px; color:rgba(255,255,255,.7); font-family:var(--mono) }
.topbar-logout { background:none; border:none; color:rgba(255,255,255,.7); cursor:pointer; font-size:16px; padding:4px; transition:color .2s }
.topbar-logout:hover { color:#fff }
.sidebar { background:#fff; border-left:1px solid var(--border); padding:20px 0; overflow-y:auto }
.nav-label { font-size:10px; font-weight:700; color:var(--text3); text-transform:uppercase; letter-spacing:1.5px; padding:0 16px 8px }
.nav-item { display:flex; align-items:center; gap:10px; padding:9px 16px; color:var(--text2); cursor:pointer; border-right:3px solid transparent; transition:all .15s; font-size:13px }
.nav-item:hover { color:var(--blue); background:rgba(30,42,122,.05) }
.nav-item.active { color:var(--blue); background:rgba(30,42,122,.07); border-right-color:var(--blue); font-weight:600 }
.nav-badge { margin-right:auto; background:var(--blue); color:#fff; font-size:10px; font-weight:700; padding:1px 6px; border-radius:10px; font-family:var(--mono) }
.nav-divider { height:1px; background:var(--border); margin:12px 16px }
.main-content { padding:28px 32px; overflow-y:auto; max-height:calc(100vh - 56px); background:var(--gray) }

/* ── Inner pages ── */
.inner-page { display:none }
.inner-page.active { display:block; animation:fadeIn .2s ease }
@keyframes fadeIn { from{opacity:0;transform:translateY(6px)} to{opacity:1;transform:translateY(0)} }

/* ── Page header ── */
.page-header { margin-bottom:24px }
.page-header h2 { font-size:20px; font-weight:700; color:var(--dark); margin-bottom:4px }
.page-header p { font-size:13px; color:var(--text2) }
.page-actions { display:flex; align-items:center; gap:10px; margin-top:12px }

/* ── Stats ── */
.stats-row { display:grid; grid-template-columns:repeat(auto-fill,minmax(180px,1fr)); gap:14px; margin-bottom:24px }
.stat-card { background:#fff; border:1px solid var(--border); border-radius:var(--radius-lg); padding:18px 20px; display:flex; align-items:center; gap:14px }
.stat-icon { width:42px; height:42px; border-radius:10px; display:flex; align-items:center; justify-content:center; font-size:20px; flex-shrink:0 }
.stat-val { font-size:24px; font-weight:700; font-family:var(--mono); line-height:1; color:var(--dark) }
.stat-label { font-size:12px; color:var(--text2); margin-top:2px }

/* ── Table ── */
.table-wrap { background:#fff; border:1px solid var(--border); border-radius:var(--radius-lg); overflow:hidden; margin-bottom:24px }
.table-header { padding:14px 20px; border-bottom:1px solid var(--border); display:flex; align-items:center; justify-content:space-between }
.table-title { font-size:14px; font-weight:600; color:var(--dark) }
table { width:100%; border-collapse:collapse }
th { padding:10px 16px; text-align:right; font-size:11px; font-weight:700; color:var(--text3); text-transform:uppercase; letter-spacing:.5px; background:var(--gray); border-bottom:1px solid var(--border) }
td { padding:11px 16px; border-bottom:1px solid var(--border); font-size:13px; color:var(--text2) }
tr:last-child td { border-bottom:none }
tr:hover td { background:rgba(30,42,122,.02) }

/* ── Badges ── */
.badge { display:inline-flex; align-items:center; gap:5px; padding:3px 10px; border-radius:20px; font-size:11px; font-weight:600; font-family:var(--mono) }
.badge::before { content:''; width:6px; height:6px; border-radius:50%; flex-shrink:0 }
.badge-pending { background:rgba(192,120,0,.1); color:var(--amber) }.badge-pending::before { background:var(--amber) }
.badge-waiting { background:rgba(30,42,122,.1); color:var(--blue) }.badge-waiting::before { background:var(--blue) }
.badge-approved { background:rgba(0,128,0,.1); color:var(--green) }.badge-approved::before { background:var(--green) }
.badge-rejected { background:rgba(219,22,27,.1); color:var(--red) }.badge-rejected::before { background:var(--red) }
.badge-suspended { background:rgba(123,63,160,.1); color:var(--purple) }.badge-suspended::before { background:var(--purple) }

/* ── Buttons ── */
.btn { display:inline-flex; align-items:center; gap:6px; padding:8px 16px; border-radius:var(--radius); font-family:var(--sans); font-size:13px; font-weight:500; cursor:pointer; border:1px solid transparent; transition:all .15s }
.btn-sm { padding:5px 12px; font-size:12px }
.btn-accent { background:var(--blue); color:#fff }.btn-accent:hover { background:var(--green) }
.btn-ghost { background:transparent; color:var(--text2); border-color:var(--border) }.btn-ghost:hover { color:var(--dark); background:var(--gray) }
.btn-success { background:rgba(0,128,0,.1); color:var(--green); border-color:rgba(0,128,0,.3) }.btn-success:hover { background:rgba(0,128,0,.2) }
.btn-danger { background:rgba(219,22,27,.1); color:var(--red); border-color:rgba(219,22,27,.3) }.btn-danger:hover { background:rgba(219,22,27,.2) }
.btn-warn { background:rgba(192,120,0,.1); color:var(--amber); border-color:rgba(192,120,0,.3) }.btn-warn:hover { background:rgba(192,120,0,.2) }

/* ── Form ── */
.form-card { background:#fff; border:1px solid var(--border); border-radius:var(--radius-lg); padding:28px; max-width:700px }
.form-grid { display:grid; grid-template-columns:1fr 1fr; gap:18px }
.form-field { display:flex; flex-direction:column; gap:6px }
.form-field.full { grid-column:1/-1 }
.form-field label { font-size:11px; font-weight:700; color:var(--text2); text-transform:uppercase; letter-spacing:.5px }
.form-field input,.form-field select,.form-field textarea { background:var(--gray); border:1px solid var(--border); border-radius:var(--radius); padding:10px 14px; color:var(--dark); font-family:var(--sans); font-size:13px; outline:none; transition:border-color .2s; width:100% }
.form-field input:focus,.form-field select:focus,.form-field textarea:focus { border-color:var(--blue) }
.form-field input[readonly] { color:var(--text3); cursor:not-allowed; background:#efefef }
.form-field textarea { resize:vertical; min-height:90px }
.form-actions { display:flex; gap:10px; margin-top:24px; border-top:1px solid var(--border); padding-top:20px }
.req { color:var(--red) }
.empty { text-align:center; padding:60px 20px; color:var(--text3) }
.empty-icon { font-size:40px; margin-bottom:12px }

/* ── Role toggle ── */
.role-toggle { display:flex; background:var(--gray); border:1px solid var(--border); border-radius:var(--radius); overflow:hidden; margin-bottom:20px }
.role-toggle-btn { flex:1; padding:8px 16px; background:none; border:none; color:var(--text2); font-family:var(--sans); font-size:12px; font-weight:500; cursor:pointer; transition:all .15s }
.role-toggle-btn.active { background:var(--blue); color:#fff }

/* ── Approval card ── */
.appr-card { background:#fff; border:1px solid var(--border); border-radius:var(--radius-lg); padding:20px; margin-bottom:14px; transition:border-color .2s }
.appr-card:hover { border-color:var(--blue) }
.appr-card-header { display:flex; align-items:flex-start; justify-content:space-between; margin-bottom:14px }
.appr-meta { font-size:12px; color:var(--text3); font-family:var(--mono); margin-top:3px }
.appr-details { display:grid; grid-template-columns:repeat(3,1fr); gap:12px; margin-bottom:16px; padding:14px; background:var(--gray); border-radius:var(--radius) }
.appr-detail label { font-size:10px; color:var(--text3); text-transform:uppercase; letter-spacing:.5px; display:block; margin-bottom:3px }
.appr-detail span { font-size:13px; color:var(--dark) }
.appr-actions { display:flex; gap:8px; flex-wrap:wrap }

/* ── Alert ── */
.alert { padding:12px 16px; border-radius:var(--radius); margin-bottom:16px; font-size:13px; display:flex; align-items:center; gap:10px }
.alert-success { background:rgba(0,128,0,.08); border:1px solid rgba(0,128,0,.3); color:var(--green) }
.alert-error { background:rgba(219,22,27,.08); border:1px solid rgba(219,22,27,.3); color:var(--red) }
.alert-info { background:rgba(30,42,122,.07); border:1px solid rgba(30,42,122,.2); color:var(--blue) }

/* ── Modal ── */
.modal-overlay { display:none; position:fixed; inset:0; background:rgba(0,0,0,.45); z-index:1000; align-items:center; justify-content:center }
.modal-overlay.open { display:flex; animation:fadeIn .2s ease }
.modal { background:#fff; border:1px solid var(--border); border-radius:var(--radius-lg); width:560px; max-width:calc(100vw - 32px); max-height:90vh; overflow-y:auto; box-shadow:0 8px 40px rgba(0,0,0,.15) }
.modal-header { padding:18px 24px; border-bottom:1px solid var(--border); display:flex; align-items:center; justify-content:space-between; background:var(--blue) }
.modal-title { font-size:16px; font-weight:600; color:#fff }
.modal-close { background:none; border:none; color:rgba(255,255,255,.8); cursor:pointer; font-size:20px; line-height:1 }
.modal-body { padding:24px }
.modal-footer { padding:16px 24px; border-top:1px solid var(--border); display:flex; gap:10px; justify-content:flex-end; background:var(--gray) }

/* ── Filter ── */
.filter-row { display:flex; gap:10px; margin-bottom:18px; flex-wrap:wrap }
.filter-row input,.filter-row select { background:#fff; border:1px solid var(--border); border-radius:var(--radius); padding:8px 12px; color:var(--dark); font-family:var(--sans); font-size:12px; outline:none }
.filter-row input:focus,.filter-row select:focus { border-color:var(--blue) }

/* ── Detail ── */
.detail-grid { display:grid; grid-template-columns:1fr 1fr; gap:16px; margin-bottom:20px }
.detail-item label { font-size:10px; color:var(--text3); text-transform:uppercase; letter-spacing:.5px; display:block; margin-bottom:4px }
.detail-item span { font-size:14px; color:var(--dark); font-weight:500 }

/* ── Cars ── */
.cars-grid { display:grid; grid-template-columns:repeat(auto-fill,minmax(200px,1fr)); gap:14px }
.car-card { background:#fff; border:1px solid var(--border); border-radius:var(--radius-lg); padding:18px; transition:border-color .2s }
.car-card:hover { border-color:var(--blue) }
.car-model { font-size:14px; font-weight:600; margin-bottom:4px; color:var(--dark) }
.car-plate { font-size:11px; color:var(--text3); font-family:var(--mono) }

/* ── Vehicle dropdown ── */
.veh-dropdown { position:relative }
.veh-display { background:var(--gray); border:1px solid var(--border); border-radius:var(--radius); padding:10px 14px; cursor:pointer; display:flex; align-items:center; gap:8px; font-size:13px; color:var(--text3); transition:border-color .2s; user-select:none }
.veh-display:focus { border-color:var(--blue) }
.veh-list { display:none; position:absolute; top:100%; right:0; left:0; background:#fff; border:1px solid var(--border); border-radius:var(--radius); box-shadow:0 4px 16px rgba(0,0,0,.1); z-index:200; max-height:220px; overflow-y:auto; margin-top:4px }
.veh-list.open { display:block }
.veh-item { padding:9px 14px; cursor:pointer; display:flex; align-items:center; gap:10px; font-size:13px; color:var(--dark) }
.veh-item:hover { background:var(--gray) }
.veh-dot { width:10px; height:10px; border-radius:3px; flex-shrink:0 }

@media(max-width:768px){
  .shell{ grid-template-columns:1fr }
  .sidebar{ display:none }
  .form-grid{ grid-template-columns:1fr }
  .appr-details{ grid-template-columns:1fr 1fr }
  .detail-grid{ grid-template-columns:1fr }
  #page-login.active{ flex-direction:column }
  .login-brand{ min-height:200px; padding:40px }
  .login-panel{ width:100%; height:auto }
}

/* ── Lucide Icons ── */
.icon { display:inline-flex; align-items:center; justify-content:center }
.icon svg { width:1em; height:1em; flex-shrink:0 }
.nav-item .icon { width:16px; height:16px }
.nav-item .icon svg { width:16px; height:16px }
.btn .icon { width:14px; height:14px }
.btn .icon svg { width:14px; height:14px }
.stat-icon .icon { width:24px; height:24px }
.stat-icon .icon svg { width:24px; height:24px }
.topbar-logout .icon { width:18px; height:18px }
.topbar-logout .icon svg { width:18px; height:18px }
.demo-card-icon .icon { width:20px; height:20px }
.demo-card-icon .icon svg { width:20px; height:20px }
.empty-icon { width:56px; height:56px; margin:0 auto 16px }
.empty-icon svg { width:56px; height:56px; stroke-width:1.2 }
.form-input {
  background: var(--gray);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  padding: 10px 14px;
  color: var(--dark);
  font-family: var(--sans);
  font-size: 13px;
  outline: none;
  transition: border-color .2s;
  width: 100%;
  margin-bottom: 0;
}
.form-input:focus { border-color: var(--blue) }
.form-field.full { grid-column: 1 / -1 }
#modal-user .form-field { display: flex; flex-direction: column; gap: 6px }
#modal-user label { font-size: 11px; font-weight: 700; color: var(--text2); text-transform: uppercase; letter-spacing: .5px }

/* ── Glitch Logo Effect ── */
.login-brand .glitch-wrap {
  position: relative;
  display: inline-block;
}
.login-brand .glitch-wrap img {
  display: block;
}
.login-brand .glitch-wrap::before,
.login-brand .glitch-wrap::after {
  content: '';
  position: absolute;
  inset: 0;
  background-image: inherit;
  background-size: contain;
  background-repeat: no-repeat;
  background-position: center;
  opacity: 0;
}
/* نحتاج لنهج مختلف - نستخدم filter + animation على الصورة نفسها */
@keyframes glitch-main {
  0%, 90%, 100%   { transform: none; filter: none; opacity:1 }
  91%  { transform: translate(-3px, 1px) skewX(-1deg); filter: hue-rotate(90deg); opacity:.9 }
  92%  { transform: translate(3px, -1px) skewX(1deg);  filter: hue-rotate(-90deg) brightness(1.2); opacity:.85 }
  93%  { transform: translate(-2px, 2px); filter: saturate(3) brightness(.8); opacity:.95 }
  94%  { transform: none; filter: none; opacity:1 }
  95%  { transform: translate(4px, 0) scaleX(1.01); filter: hue-rotate(45deg); opacity:.9 }
  96%  { transform: translate(-4px, 1px) scaleX(.99); filter: hue-rotate(-45deg) contrast(1.3); opacity:.88 }
  97%  { transform: none; filter: none; opacity:1 }
}

@keyframes glitch-clip-1 {
  0%, 89%, 100%  { clip-path: none; transform: none; opacity:0 }
  90%  { clip-path: polygon(0 20%, 100% 20%, 100% 35%, 0 35%); transform: translate(-6px, 0); opacity:.7; filter: hue-rotate(120deg) }
  91%  { clip-path: polygon(0 60%, 100% 60%, 100% 70%, 0 70%); transform: translate(6px, 0);  opacity:.6; filter: hue-rotate(-120deg) }
  92%  { clip-path: polygon(0 45%, 100% 45%, 100% 55%, 0 55%); transform: translate(-3px, 0); opacity:.5 }
  93%  { clip-path: none; opacity:0 }
}

@keyframes glitch-clip-2 {
  0%, 92%, 100%  { clip-path: none; transform: none; opacity:0 }
  93%  { clip-path: polygon(0 5%, 100% 5%, 100% 15%, 0 15%);   transform: translate(8px,0);  opacity:.6; filter: hue-rotate(200deg) }
  94%  { clip-path: polygon(0 80%, 100% 80%, 100% 90%, 0 90%); transform: translate(-8px,0); opacity:.5; filter: hue-rotate(-200deg) }
  95%  { clip-path: polygon(0 50%, 100% 50%, 100% 60%, 0 60%); transform: translate(4px,0);  opacity:.4 }
  96%  { clip-path: none; opacity:0 }
}

.glitch-img {
  animation: glitch-main 8s infinite;
  position: relative;
  z-index: 1;
}
.glitch-layer {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  object-fit: contain;
  pointer-events: none;
}
.glitch-layer-1 { animation: glitch-clip-1 8s infinite; z-index: 2 }
.glitch-layer-2 { animation: glitch-clip-2 8s infinite; z-index: 3 }
