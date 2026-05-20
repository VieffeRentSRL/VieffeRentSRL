<!DOCTYPE html>
<html lang="it">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Vieffe Rent Srl — Gestionale Flotta</title>
<meta name="description" content="Gestionale operativo flotta Vieffe Rent Srl">
<meta name="theme-color" content="#FF6600">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
body{font-family:system-ui,-apple-system,sans-serif;background:#f0efeb;color:#1a1a18;display:flex;min-height:100vh}

/* ── SIDEBAR ─────────────────────────────── */
.sidebar{width:220px;min-height:100vh;background:#1a1a18;display:flex;flex-direction:column;flex-shrink:0;position:sticky;top:0;height:100vh;overflow-y:auto}
.sidebar-logo{padding:20px 16px 16px;border-bottom:1px solid rgba(255,255,255,0.08)}
.sidebar-logo img{height:36px;width:auto;object-fit:contain}
.sidebar-company{margin-top:8px;font-size:11px;color:rgba(255,255,255,0.4);letter-spacing:0.03em}
.sidebar-nav{flex:1;padding:12px 0}
.sidebar-section{font-size:10px;font-weight:600;color:rgba(255,255,255,0.3);text-transform:uppercase;letter-spacing:0.08em;padding:12px 16px 4px}
.nav-item{display:flex;align-items:center;gap:10px;padding:9px 16px;cursor:pointer;font-size:13px;color:rgba(255,255,255,0.6);border:none;background:none;width:100%;text-align:left;font-family:inherit;transition:background .15s,color .15s;border-left:3px solid transparent}
.nav-item:hover{background:rgba(255,255,255,0.06);color:rgba(255,255,255,0.9)}
.nav-item.active{background:rgba(255,102,0,0.15);color:#FF6600;border-left-color:#FF6600;font-weight:600}
.nav-item .nav-icon{font-size:15px;width:20px;text-align:center;flex-shrink:0}
.nav-badge{margin-left:auto;background:#E24B4A;color:#fff;font-size:10px;font-weight:700;padding:1px 6px;border-radius:99px;min-width:18px;text-align:center}
.nav-badge.amber{background:#EF9F27}
.sidebar-footer{padding:12px 16px;border-top:1px solid rgba(255,255,255,0.08);font-size:10px;color:rgba(255,255,255,0.25);line-height:1.5}

/* ── MAIN AREA ───────────────────────────── */
.main-area{flex:1;min-width:0;display:flex;flex-direction:column}
.topbar{background:#fff;border-bottom:1px solid rgba(0,0,0,0.08);padding:0 24px;height:52px;display:flex;align-items:center;gap:12px;position:sticky;top:0;z-index:10}
.topbar-title{font-size:15px;font-weight:600;color:#1a1a18;flex:1}
.topbar-date{font-size:12px;color:#999}
.topbar-badge{font-size:11px;font-weight:600;padding:3px 10px;border-radius:99px;cursor:pointer}
.topbar-badge.scad{background:#FCEBEB;color:#A32D2D}
.topbar-badge.ok{background:#EAF3DE;color:#3B6D11}
.content{flex:1;padding:24px;max-width:1100px;width:100%}

/* Hamburger for mobile */
.menu-toggle{display:none;background:none;border:none;cursor:pointer;padding:8px;color:#1a1a18;font-size:20px}

.wrap{width:100%}
.header{display:none} /* replaced by sidebar */
.main-tabs{display:none} /* replaced by sidebar nav */
.page{display:none}.page.active{display:block}

/* ── MOBILE ──────────────────────────────── */
@media(max-width:768px){
  body{flex-direction:column}
  .sidebar{width:100%;min-height:auto;height:auto;position:relative;flex-direction:row;flex-wrap:wrap}
  .sidebar-logo{padding:12px 16px;flex:1}
  .sidebar-nav{display:none;width:100%;padding:0}
  .sidebar-nav.open{display:block}
  .sidebar-footer{display:none}
  .menu-toggle{display:block;padding:12px 16px;color:#fff}
  .content{padding:16px}
  .nav-item{padding:10px 16px}
}
.stats{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-bottom:1.5rem}
.stat{background:#eceae3;border-radius:8px;padding:0.75rem 1rem}
.stat-label{font-size:12px;color:#666;margin-bottom:4px}
.stat-value{font-size:22px;font-weight:500}
.stat-value.red{color:#A32D2D}.stat-value.amber{color:#854F0B}.stat-value.green{color:#3B6D11}
.top-bar{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:1.25rem;align-items:center}
input[type=text],input[type=date],input[type=email],input[type=tel],input[type=number],input[type=time],textarea,select{
  height:36px;border:0.5px solid rgba(0,0,0,0.3);border-radius:8px;
  padding:0 10px;font-size:14px;background:#fff;color:#1a1a18;
  font-family:inherit;outline:none;width:100%}
textarea{height:64px;padding:8px 10px;resize:vertical}
input:focus,select:focus,textarea:focus{border-color:rgba(0,0,0,0.5)}
button{height:36px;padding:0 16px;border:0.5px solid rgba(0,0,0,0.3);border-radius:8px;
  background:transparent;font-size:14px;font-family:inherit;cursor:pointer;white-space:nowrap;color:#1a1a18}
button:hover{background:#eceae3}
.btn-primary{background:#FFF0E6;color:#CC5200;border-color:#FF9955}
.btn-primary:hover{background:#FF6600;color:#fff;border-color:#FF6600}
.btn-danger{color:#A32D2D;border-color:#F7C1C1}
.btn-green{background:#EAF3DE;color:#3B6D11;border-color:#C0DD97}
.vehicle-block{margin-bottom:1rem}
.vehicle-label{font-size:13px;font-weight:500;color:#555;margin:1rem 0 0.4rem;display:flex;align-items:center;gap:8px;flex-wrap:wrap}
.plate{background:#eceae3;border:0.5px solid rgba(0,0,0,0.25);border-radius:4px;padding:2px 8px;font-size:12px;font-weight:500;letter-spacing:0.08em;font-family:monospace}
.pill{font-size:11px;font-weight:500;padding:2px 9px;border-radius:99px}
.pill.prop{background:#FFF0E6;color:#CC5200}.pill.nol{background:#1a1a18;color:#FF6600}
.card{background:#fff;border:0.5px solid rgba(0,0,0,0.12);border-radius:12px;padding:0.75rem 1rem;margin-bottom:6px;display:flex;align-items:center;gap:12px}
.card:hover{border-color:rgba(0,0,0,0.25)}
.dot{width:9px;height:9px;border-radius:50%;flex-shrink:0}
.dot.scaduto{background:#E24B4A}.dot.urgente{background:#EF9F27}.dot.ok{background:#639922}
.card-info{flex:1;min-width:0}
.card-name{font-size:14px;font-weight:500}
.card-meta{font-size:12px;color:#666;margin-top:2px}
.badge{font-size:11px;font-weight:500;padding:3px 9px;border-radius:99px;white-space:nowrap;flex-shrink:0}
.badge.scaduto{background:#FCEBEB;color:#A32D2D}.badge.urgente{background:#FAEEDA;color:#854F0B}.badge.ok{background:#EAF3DE;color:#3B6D11}
.badge.rientro{background:#EAF3DE;color:#3B6D11}.badge.aperto{background:#FAEEDA;color:#854F0B}
.del-btn{font-size:18px;cursor:pointer;color:#bbb;padding:0 4px;flex-shrink:0;line-height:1;background:none;border:none;height:auto}
.del-btn:hover{color:#A32D2D;background:none}
.add-panel{margin-top:1.5rem;padding-top:1.25rem;border-top:0.5px solid rgba(0,0,0,0.12)}
.panel-tabs{display:flex;gap:4px;margin-bottom:1.25rem}
.tab{font-size:13px;padding:6px 14px;border-radius:8px;cursor:pointer;border:0.5px solid transparent;color:#666;background:none}
.tab:hover{background:#eceae3}
.tab.active{background:#eceae3;border-color:rgba(0,0,0,0.2);color:#1a1a18;font-weight:500}
.tab-content{display:none}.tab-content.active{display:block}
.fg{display:flex;flex-direction:column;gap:4px}
.fg label{font-size:12px;color:#666}
.row{display:grid;gap:8px;align-items:end;margin-bottom:8px}
.r2{grid-template-columns:1fr 1fr}
.r3{grid-template-columns:1fr 1fr 1fr}
.r4{grid-template-columns:1fr 1fr 1fr 1fr}
.r5{grid-template-columns:1fr 1fr 1fr 1fr auto}
.section-sep{font-size:11px;color:#aaa;text-transform:uppercase;letter-spacing:0.05em;margin:10px 0 6px}
.empty{text-align:center;color:#bbb;font-size:14px;padding:2rem 0}
.toast{position:fixed;bottom:20px;right:20px;background:#fff;border:0.5px solid rgba(0,0,0,0.2);border-radius:8px;padding:10px 16px;font-size:13px;box-shadow:0 2px 8px rgba(0,0,0,0.1);opacity:0;transition:opacity 0.3s;pointer-events:none;z-index:999}
.toast.show{opacity:1}
.edit-v-btn{font-size:12px;padding:3px 10px;height:auto;border-radius:6px;color:#666}
.cliente-section{background:#f5f4f0;border-radius:8px;padding:10px 14px;margin-bottom:6px;font-size:12px}
.cli-row{display:flex;gap:16px;flex-wrap:wrap;margin-top:4px}
.cli-item{display:flex;flex-direction:column;gap:2px}
.cli-key{color:#aaa;font-size:11px}
.cli-val{color:#1a1a18;font-size:12px}
.mov-card{background:#fff;border:0.5px solid rgba(0,0,0,0.12);border-radius:12px;padding:1rem;margin-bottom:8px}
.mov-card:hover{border-color:rgba(0,0,0,0.25)}
.mov-header{display:flex;align-items:center;gap:10px;margin-bottom:8px;flex-wrap:wrap}
.mov-grid{display:grid;grid-template-columns:1fr 1fr;gap:8px 24px;font-size:13px}
.mov-label{color:#aaa;font-size:11px}
.mov-val{color:#1a1a18;font-weight:500}
.half-section{border-left:3px solid #ddd;padding-left:10px}
.half-section.out{border-left-color:#378ADD}
.half-section.in{border-left-color:#639922}
.mov-actions{display:flex;gap:6px;margin-top:10px;flex-wrap:wrap}
.filter-bar{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:1rem;align-items:center}
@media(max-width:600px){.r3,.r4,.r5{grid-template-columns:1fr 1fr}.r2{grid-template-columns:1fr}.mov-grid{grid-template-columns:1fr}}

/* ═══════════════════════════════════════════
   DASHBOARD
═══════════════════════════════════════════ */
.dash-grid{display:grid;grid-template-columns:repeat(5,1fr);gap:10px;margin-bottom:1.5rem}
.kpi{background:#fff;border:0.5px solid rgba(0,0,0,0.1);border-radius:12px;padding:1rem 1.25rem;position:relative;overflow:hidden;cursor:default}
.kpi::before{content:'';position:absolute;top:0;left:0;width:100%;height:3px}
.kpi.kpi-green::before{background:#639922}
.kpi.kpi-red::before{background:#E24B4A}
.kpi.kpi-orange::before{background:#FF6600}
.kpi.kpi-blue::before{background:#378ADD}
.kpi.kpi-amber::before{background:#EF9F27}
.kpi-icon{font-size:22px;margin-bottom:6px}
.kpi-value{font-size:28px;font-weight:700;line-height:1;margin-bottom:4px}
.kpi-value.green{color:#3B6D11}.kpi-value.red{color:#A32D2D}
.kpi-value.orange{color:#CC5200}.kpi-value.blue{color:#185FA5}
.kpi-value.amber{color:#854F0B}
.kpi-label{font-size:11px;color:#999;text-transform:uppercase;letter-spacing:0.05em;font-weight:500}

.dash-row{display:grid;grid-template-columns:1fr 1fr;gap:14px;margin-bottom:1.25rem}
.dash-row.r3{grid-template-columns:1fr 1fr 1fr}
.dash-panel{background:#fff;border:0.5px solid rgba(0,0,0,0.1);border-radius:12px;padding:1rem 1.25rem}
.dash-panel-title{font-size:12px;font-weight:600;color:#999;text-transform:uppercase;letter-spacing:0.06em;margin-bottom:0.75rem;display:flex;align-items:center;gap:6px}
.dash-panel-title span{font-size:14px}

/* Flotta stato */
.fleet-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(80px,1fr));gap:8px}
.fleet-card{border-radius:8px;padding:8px 6px;text-align:center;font-size:11px;font-weight:500;cursor:pointer;transition:opacity .15s}
.fleet-card:hover{opacity:.8}
.fleet-card .fc-icon{font-size:20px;display:block;margin-bottom:3px}
.fleet-card .fc-plate{font-family:monospace;font-size:10px;font-weight:700;letter-spacing:0.06em}
.fleet-card .fc-stato{font-size:9px;margin-top:2px;opacity:.8}
.fc-disponibile{background:#EAF3DE;color:#3B6D11;border:0.5px solid #C0DD97}
.fc-noleggiato{background:#FCEBEB;color:#A32D2D;border:0.5px solid #F7C1C1}
.fc-officina{background:#FFF0E6;color:#CC5200;border:0.5px solid #FFCBA4}
.fc-prenotato{background:#E6F1FB;color:#185FA5;border:0.5px solid #A8CFF0}
.fc-fuori{background:#eceae3;color:#666;border:0.5px solid #ccc}

/* Alert scadenze */
.alert-list{display:flex;flex-direction:column;gap:6px;max-height:220px;overflow-y:auto}
.alert-item{display:flex;align-items:center;gap:10px;padding:8px 10px;border-radius:8px;font-size:12px}
.alert-item.scaduto{background:#FCEBEB;border:0.5px solid #F7C1C1}
.alert-item.urgente{background:#FAEEDA;border:0.5px solid #F5D49A}
.alert-dot{width:7px;height:7px;border-radius:50%;flex-shrink:0}
.alert-dot.scaduto{background:#E24B4A}.alert-dot.urgente{background:#EF9F27}
.alert-info{flex:1}
.alert-targa{font-weight:600;font-family:monospace}
.alert-days{font-weight:600;margin-left:auto;white-space:nowrap}
.alert-days.scaduto{color:#A32D2D}.alert-days.urgente{color:#854F0B}

/* Movimenti recenti */
.activity-list{display:flex;flex-direction:column;gap:6px;max-height:220px;overflow-y:auto}
.activity-item{display:flex;align-items:center;gap:10px;padding:8px 10px;background:#f5f4f0;border-radius:8px;font-size:12px}
.activity-icon{font-size:15px;flex-shrink:0}
.activity-info{flex:1}
.activity-time{font-size:11px;color:#aaa;white-space:nowrap}

/* Rientri oggi */
.rientri-list{display:flex;flex-direction:column;gap:6px;max-height:180px;overflow-y:auto}
.rientro-item{display:flex;align-items:center;gap:10px;padding:8px 10px;background:#EAF3DE;border:0.5px solid #C0DD97;border-radius:8px;font-size:12px}
.rientro-item.ritardo{background:#FCEBEB;border-color:#F7C1C1}

/* Barra arancione separazione sezione */
.dash-sep{height:2px;background:linear-gradient(90deg,#FF6600,transparent);margin:0.5rem 0 1.25rem;border-radius:2px}

@media(max-width:800px){.dash-grid{grid-template-columns:repeat(3,1fr)}.dash-row,.dash-row.r3{grid-template-columns:1fr}}


/* ═══════════════════════════════════════════
   MODULO CLIENTI
═══════════════════════════════════════════ */
.cli-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(300px,1fr));gap:12px;margin-bottom:1rem}
.cliente-card{background:#fff;border:0.5px solid rgba(0,0,0,0.1);border-radius:12px;padding:1rem 1.25rem;cursor:pointer;transition:box-shadow .15s,border-color .15s;position:relative}
.cliente-card:hover{border-color:rgba(255,102,0,0.4);box-shadow:0 2px 10px rgba(255,102,0,0.08)}
.cliente-card-header{display:flex;align-items:flex-start;gap:10px;margin-bottom:8px}
.cliente-avatar{width:38px;height:38px;border-radius:8px;background:#1a1a18;color:#FF6600;display:flex;align-items:center;justify-content:center;font-size:15px;font-weight:700;flex-shrink:0;font-family:monospace}
.cliente-nome{font-size:14px;font-weight:600;line-height:1.2}
.cliente-azienda{font-size:12px;color:#888;margin-top:1px}
.cliente-tags{display:flex;gap:4px;flex-wrap:wrap;margin-top:6px}
.tag{font-size:10px;font-weight:600;padding:2px 7px;border-radius:99px}
.tag-blacklist{background:#FCEBEB;color:#A32D2D;border:0.5px solid #F7C1C1}
.tag-attivo{background:#EAF3DE;color:#3B6D11;border:0.5px solid #C0DD97}
.tag-inattivo{background:#eceae3;color:#888;border:0.5px solid #ccc}
.cliente-contacts{font-size:12px;color:#666;display:flex;flex-direction:column;gap:3px;margin-top:8px}
.cliente-contacts a{color:#185FA5;text-decoration:none}
.cliente-contacts a:hover{text-decoration:underline}
.cliente-stats-row{display:flex;gap:12px;margin-top:10px;padding-top:8px;border-top:0.5px solid rgba(0,0,0,0.07)}
.cliente-stat{display:flex;flex-direction:column;align-items:center;gap:1px;flex:1}
.cliente-stat-val{font-size:16px;font-weight:700;color:#1a1a18}
.cliente-stat-lbl{font-size:10px;color:#aaa;text-transform:uppercase;letter-spacing:0.04em}
.cliente-actions{position:absolute;top:10px;right:10px;display:flex;gap:4px}

/* Detail panel */
.detail-panel{background:#fff;border:0.5px solid rgba(0,0,0,0.1);border-radius:12px;padding:1.25rem;margin-bottom:1rem}
.detail-header{display:flex;align-items:center;gap:12px;margin-bottom:1.25rem;padding-bottom:1rem;border-bottom:0.5px solid rgba(0,0,0,0.08)}
.detail-avatar{width:52px;height:52px;border-radius:10px;background:#1a1a18;color:#FF6600;display:flex;align-items:center;justify-content:center;font-size:20px;font-weight:700;flex-shrink:0}
.detail-title{flex:1}
.detail-name{font-size:18px;font-weight:700}
.detail-sub{font-size:13px;color:#888;margin-top:2px}
.detail-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px 24px;font-size:13px;margin-bottom:1rem}
.detail-field{display:flex;flex-direction:column;gap:3px}
.detail-label{font-size:11px;color:#aaa;text-transform:uppercase;letter-spacing:0.04em;font-weight:600}
.detail-value{color:#1a1a18;font-weight:500}
.storico-list{display:flex;flex-direction:column;gap:6px;max-height:260px;overflow-y:auto}
.storico-item{background:#f5f4f0;border-radius:8px;padding:10px 12px;display:flex;align-items:center;gap:10px;font-size:12px}
.storico-icon{font-size:14px;flex-shrink:0}
.storico-info{flex:1}
.storico-date{font-size:11px;color:#aaa;white-space:nowrap}

/* Form scheda cliente */
.form-cliente{background:#f5f4f0;border-radius:12px;padding:1.25rem;margin-top:1rem}
.form-cliente-title{font-size:13px;font-weight:600;margin-bottom:1rem;display:flex;align-items:center;gap:8px}
.blacklist-toggle{display:flex;align-items:center;gap:8px;font-size:13px;cursor:pointer;padding:8px 0}
.blacklist-toggle input[type=checkbox]{width:16px;height:16px;cursor:pointer;accent-color:#E24B4A}

/* Search + filter bar clienti */
.cli-topbar{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:1.25rem;align-items:center}
.cli-count{font-size:12px;color:#aaa;margin-left:auto}

@media(max-width:600px){.cli-grid{grid-template-columns:1fr}.detail-grid{grid-template-columns:1fr}}


/* ═══════════════════════════════════════════
   MODULO GARAGE / OFFICINA
═══════════════════════════════════════════ */
.garage-kanban{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;margin-bottom:1.5rem}
.kanban-col{background:#f5f4f0;border-radius:12px;padding:10px}
.kanban-col-header{font-size:11px;font-weight:700;text-transform:uppercase;letter-spacing:.06em;padding:4px 6px 10px;display:flex;align-items:center;gap:6px}
.kanban-dot{width:8px;height:8px;border-radius:50%;flex-shrink:0}
.kd-aperto{background:#EF9F27}.kd-in_corso{background:#378ADD}.kd-attesa{background:#9B59B6}.kd-completato{background:#639922}
.kanban-count{margin-left:auto;font-size:11px;font-weight:700;color:#aaa}
.kanban-cards{display:flex;flex-direction:column;gap:6px;min-height:60px}

.maint-card{background:#fff;border:0.5px solid rgba(0,0,0,0.1);border-radius:10px;padding:10px 12px;cursor:pointer;transition:border-color .15s,box-shadow .15s}
.maint-card:hover{border-color:rgba(255,102,0,0.35);box-shadow:0 1px 6px rgba(0,0,0,0.07)}
.maint-card-top{display:flex;align-items:center;gap:8px;margin-bottom:6px}
.maint-card-targa{font-family:monospace;font-size:11px;font-weight:700;background:#eceae3;padding:2px 6px;border-radius:4px;letter-spacing:.06em}
.maint-card-tipo{font-size:12px;font-weight:600;flex:1}
.maint-card-data{font-size:10px;color:#aaa;white-space:nowrap}
.maint-card-desc{font-size:11px;color:#666;line-height:1.4;margin-bottom:6px}
.maint-card-footer{display:flex;align-items:center;gap:6px}
.maint-badge{font-size:10px;font-weight:600;padding:2px 7px;border-radius:99px}
.mb-aperto{background:#FAEEDA;color:#854F0B}
.mb-in_corso{background:#E6F1FB;color:#185FA5}
.mb-attesa{background:#F3E9FB;color:#6C3483}
.mb-completato{background:#EAF3DE;color:#3B6D11}
.maint-priority{font-size:10px;font-weight:700;padding:1px 6px;border-radius:99px}
.mp-alta{background:#FCEBEB;color:#A32D2D}
.mp-media{background:#FAEEDA;color:#854F0B}
.mp-bassa{background:#EAF3DE;color:#3B6D11}

/* Form intervento */
.garage-form{background:#f5f4f0;border-radius:12px;padding:1.25rem;margin-bottom:1.25rem}
.garage-form-title{font-size:13px;font-weight:600;margin-bottom:1rem;display:flex;align-items:center;gap:8px}
.stato-selector{display:flex;gap:6px;flex-wrap:wrap}
.stato-btn{font-size:12px;padding:5px 12px;border-radius:8px;cursor:pointer;border:0.5px solid rgba(0,0,0,0.2);background:#fff;color:#666;font-family:inherit;transition:all .15s}
.stato-btn.selected{font-weight:600}
.stato-btn[data-stato="aperto"].selected{background:#FAEEDA;color:#854F0B;border-color:#EF9F27}
.stato-btn[data-stato="in_corso"].selected{background:#E6F1FB;color:#185FA5;border-color:#378ADD}
.stato-btn[data-stato="attesa"].selected{background:#F3E9FB;color:#6C3483;border-color:#9B59B6}
.stato-btn[data-stato="completato"].selected{background:#EAF3DE;color:#3B6D11;border-color:#639922}

/* Detail modale */
.maint-detail{background:#fff;border:0.5px solid rgba(0,0,0,0.1);border-radius:12px;padding:1.25rem;margin-bottom:1rem}
.maint-detail-header{display:flex;align-items:flex-start;gap:12px;margin-bottom:1rem;padding-bottom:1rem;border-bottom:.5px solid rgba(0,0,0,.08)}

/* Alert automazioni */
.auto-alerts{display:grid;grid-template-columns:repeat(auto-fill,minmax(240px,1fr));gap:8px;margin-bottom:1.25rem}
.auto-alert-card{border-radius:10px;padding:10px 14px;display:flex;align-items:center;gap:10px;font-size:12px;cursor:pointer;transition:opacity .15s}
.auto-alert-card:hover{opacity:.85}
.auto-alert-card.scaduto{background:#FCEBEB;border:0.5px solid #F7C1C1}
.auto-alert-card.urgente{background:#FAEEDA;border:0.5px solid #F5D49A}
.auto-alert-icon{font-size:18px;flex-shrink:0}
.auto-alert-info{flex:1}
.auto-alert-title{font-weight:600;color:#1a1a18}
.auto-alert-sub{color:#888;margin-top:1px}
.auto-alert-days{font-size:11px;font-weight:700;white-space:nowrap}
.auto-alert-days.scaduto{color:#A32D2D}.auto-alert-days.urgente{color:#854F0B}

@media(max-width:900px){.garage-kanban{grid-template-columns:1fr 1fr}}
@media(max-width:600px){.garage-kanban{grid-template-columns:1fr}}


/* ═══════════════════════════════════════════
   MODULO SINISTRI
═══════════════════════════════════════════ */
.sinistri-list{display:flex;flex-direction:column;gap:10px;margin-bottom:1.5rem}

.sinistro-card{background:#fff;border:0.5px solid rgba(0,0,0,0.1);border-radius:12px;padding:1rem 1.25rem;cursor:pointer;transition:border-color .15s,box-shadow .15s}
.sinistro-card:hover{border-color:rgba(255,102,0,.35);box-shadow:0 2px 10px rgba(0,0,0,.07)}
.sinistro-card-header{display:flex;align-items:center;gap:10px;margin-bottom:8px}
.sinistro-num{font-size:11px;font-weight:700;color:#aaa;font-family:monospace}
.sinistro-title{font-size:14px;font-weight:600;flex:1}
.sinistro-data{font-size:11px;color:#aaa;white-space:nowrap}

.sin-badge{font-size:11px;font-weight:600;padding:3px 9px;border-radius:99px;white-space:nowrap}
.sin-aperto{background:#FAEEDA;color:#854F0B;border:0.5px solid #F5D49A}
.sin-in_gestione{background:#E6F1FB;color:#185FA5;border:0.5px solid #A8CFF0}
.sin-chiuso{background:#EAF3DE;color:#3B6D11;border:0.5px solid #C0DD97}
.sin-contestato{background:#FCEBEB;color:#A32D2D;border:0.5px solid #F7C1C1}

.sinistro-meta{display:flex;gap:16px;flex-wrap:wrap;font-size:12px;color:#666;margin-top:6px}
.sinistro-meta span{display:flex;align-items:center;gap:4px}

.sin-form{background:#f5f4f0;border-radius:12px;padding:1.25rem;margin-bottom:1.25rem}
.sin-form-title{font-size:13px;font-weight:600;margin-bottom:1rem;display:flex;align-items:center;gap:8px}

.sin-stato-selector{display:flex;gap:6px;flex-wrap:wrap}
.sin-stato-btn{font-size:12px;padding:5px 12px;border-radius:8px;cursor:pointer;border:0.5px solid rgba(0,0,0,.2);background:#fff;color:#666;font-family:inherit;transition:all .15s}
.sin-stato-btn[data-stato="aperto"].selected{background:#FAEEDA;color:#854F0B;border-color:#EF9F27}
.sin-stato-btn[data-stato="in_gestione"].selected{background:#E6F1FB;color:#185FA5;border-color:#378ADD}
.sin-stato-btn[data-stato="chiuso"].selected{background:#EAF3DE;color:#3B6D11;border-color:#639922}
.sin-stato-btn[data-stato="contestato"].selected{background:#FCEBEB;color:#A32D2D;border-color:#E24B4A}

.sin-detail{background:#fff;border:0.5px solid rgba(0,0,0,.1);border-radius:12px;padding:1.25rem;margin-bottom:1rem}
.sin-detail-header{display:flex;align-items:flex-start;gap:12px;margin-bottom:1rem;padding-bottom:1rem;border-bottom:.5px solid rgba(0,0,0,.08)}

.foto-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(80px,1fr));gap:8px;margin-top:8px}
.foto-placeholder{background:#f5f4f0;border:.5px dashed #ccc;border-radius:8px;aspect-ratio:1;display:flex;align-items:center;justify-content:center;font-size:22px;color:#bbb;cursor:pointer}
.foto-placeholder:hover{background:#eceae3;border-color:#aaa}

.timeline{display:flex;flex-direction:column;gap:0}
.timeline-item{display:flex;gap:12px;padding:8px 0;position:relative}
.timeline-item:not(:last-child)::after{content:'';position:absolute;left:10px;top:28px;bottom:0;width:1px;background:rgba(0,0,0,.1)}
.timeline-dot{width:20px;height:20px;border-radius:50%;flex-shrink:0;display:flex;align-items:center;justify-content:center;font-size:10px;margin-top:2px}
.tl-aperto{background:#FAEEDA;color:#854F0B}
.tl-update{background:#E6F1FB;color:#185FA5}
.tl-chiuso{background:#EAF3DE;color:#3B6D11}
.timeline-content{flex:1}
.timeline-text{font-size:12px;color:#333}
.timeline-date{font-size:11px;color:#aaa;margin-top:1px}


/* ═══════════════════════════════════════════
   POLISH & AUTOMAZIONI
═══════════════════════════════════════════ */

/* Notifica bell in topbar */
.topbar-notif{position:relative;cursor:pointer;display:flex;align-items:center;padding:6px 8px;border-radius:8px;transition:background .15s}
.topbar-notif:hover{background:#f5f4f0}
.notif-icon{font-size:18px}
.notif-dot{position:absolute;top:4px;right:4px;width:8px;height:8px;border-radius:50%;background:#E24B4A;border:2px solid #fff;display:none}
.notif-dot.show{display:block}

/* Notifiche dropdown */
.notif-panel{position:fixed;top:56px;right:16px;width:340px;background:#fff;border:.5px solid rgba(0,0,0,.15);border-radius:14px;box-shadow:0 8px 32px rgba(0,0,0,.12);z-index:200;display:none;overflow:hidden}
.notif-panel.open{display:block}
.notif-header{padding:12px 16px;border-bottom:.5px solid rgba(0,0,0,.08);font-size:13px;font-weight:600;display:flex;align-items:center;gap:8px}
.notif-list{max-height:360px;overflow-y:auto}
.notif-item{padding:10px 16px;border-bottom:.5px solid rgba(0,0,0,.05);display:flex;gap:10px;align-items:flex-start;cursor:pointer;transition:background .12s}
.notif-item:hover{background:#f5f4f0}
.notif-item:last-child{border-bottom:none}
.notif-item-icon{font-size:16px;flex-shrink:0;margin-top:1px}
.notif-item-body{flex:1}
.notif-item-title{font-size:12px;font-weight:600;color:#1a1a18}
.notif-item-sub{font-size:11px;color:#888;margin-top:1px}
.notif-item.red .notif-item-title{color:#A32D2D}
.notif-item.amber .notif-item-title{color:#854F0B}
.notif-empty{padding:20px 16px;text-align:center;font-size:13px;color:#bbb}

/* Modal overlay generico */
.modal-overlay{position:fixed;inset:0;background:rgba(0,0,0,.45);z-index:300;display:none;align-items:center;justify-content:center}
.modal-overlay.open{display:flex}
.modal-box{background:#fff;border-radius:16px;padding:1.5rem;max-width:480px;width:calc(100% - 32px);box-shadow:0 16px 48px rgba(0,0,0,.18)}
.modal-title{font-size:16px;font-weight:700;margin-bottom:1rem;display:flex;align-items:center;gap:8px}
.modal-actions{display:flex;gap:8px;justify-content:flex-end;margin-top:1.25rem}

/* Scroll to top button */
.scroll-top{position:fixed;bottom:24px;right:24px;width:40px;height:40px;border-radius:50%;background:#FF6600;color:#fff;border:none;cursor:pointer;font-size:18px;display:none;align-items:center;justify-content:center;box-shadow:0 2px 10px rgba(255,102,0,.4);z-index:100;transition:opacity .2s}
.scroll-top.show{display:flex}
.scroll-top:hover{background:#CC5200}

/* Empty state migliorato */
.empty-state{text-align:center;padding:3rem 1rem;color:#bbb}
.empty-state-icon{font-size:48px;margin-bottom:12px;opacity:.4}
.empty-state-title{font-size:15px;font-weight:600;color:#999;margin-bottom:4px}
.empty-state-sub{font-size:13px}

/* Tooltip */
[data-tooltip]{position:relative}
[data-tooltip]::after{content:attr(data-tooltip);position:absolute;bottom:calc(100% + 6px);left:50%;transform:translateX(-50%);background:#1a1a18;color:#fff;font-size:11px;padding:4px 8px;border-radius:6px;white-space:nowrap;pointer-events:none;opacity:0;transition:opacity .15s;z-index:50}
[data-tooltip]:hover::after{opacity:1}

/* Miglioramento topbar su mobile */
@media(max-width:768px){
  .topbar{padding:0 12px;gap:8px}
  .topbar-date{display:none}
  .notif-panel{right:8px;width:calc(100vw - 16px)}
}

/* Improved stat cards */
.stat{background:#fff;border:.5px solid rgba(0,0,0,.08);transition:box-shadow .15s}
.stat:hover{box-shadow:0 2px 8px rgba(0,0,0,.07)}

/* Page transition */
.page.active{animation:fadeIn .18s ease}
@keyframes fadeIn{from{opacity:0;transform:translateY(4px)}to{opacity:1;transform:translateY(0)}}

/* Better scrollbars */
::-webkit-scrollbar{width:6px;height:6px}
::-webkit-scrollbar-track{background:transparent}
::-webkit-scrollbar-thumb{background:rgba(0,0,0,.15);border-radius:99px}
::-webkit-scrollbar-thumb:hover{background:rgba(0,0,0,.25)}

/* Print styles */
@media print{
  .sidebar,.topbar,.scroll-top,.notif-panel{display:none!important}
  .main-area{width:100%}
  .content{padding:0}
}


/* ═══════════════════════════════════════════
   CHECKLIST CONSEGNA / RIENTRO
═══════════════════════════════════════════ */
.checklist-wrap{background:#fff;border:.5px solid rgba(0,0,0,.1);border-radius:10px;padding:12px 14px;margin:8px 0}
.checklist-title{font-size:11px;font-weight:700;text-transform:uppercase;letter-spacing:.06em;color:#aaa;margin-bottom:10px;display:flex;align-items:center;gap:6px}
.checklist-grid{display:grid;grid-template-columns:1fr 1fr;gap:6px 16px}
.checklist-item{display:flex;align-items:center;gap:8px;font-size:13px;cursor:pointer;padding:4px 6px;border-radius:6px;transition:background .12s;user-select:none}
.checklist-item:hover{background:#f5f4f0}
.checklist-item input[type=checkbox]{width:15px;height:15px;accent-color:#FF6600;cursor:pointer;flex-shrink:0}
.checklist-item.checked{color:#3B6D11;font-weight:500}
.checklist-item.checked input{accent-color:#639922}
.checklist-progress{display:flex;align-items:center;gap:8px;margin-top:10px;padding-top:8px;border-top:.5px solid rgba(0,0,0,.07)}
.checklist-bar-wrap{flex:1;height:6px;background:#eceae3;border-radius:99px;overflow:hidden}
.checklist-bar{height:100%;background:#FF6600;border-radius:99px;transition:width .3s}
.checklist-bar.complete{background:#639922}
.checklist-pct{font-size:11px;font-weight:700;color:#aaa;white-space:nowrap}
.checklist-badge{font-size:10px;font-weight:700;padding:2px 7px;border-radius:99px}
.cb-ok{background:#EAF3DE;color:#3B6D11}
.cb-parziale{background:#FAEEDA;color:#854F0B}
.cb-no{background:#eceae3;color:#888}

/* Recap checklist nelle schede movimenti */
.mov-checklist-recap{display:flex;gap:6px;flex-wrap:wrap;margin-top:6px}
.mcr-item{display:flex;align-items:center;gap:4px;font-size:11px;color:#666}
.mcr-dot{width:6px;height:6px;border-radius:50%;flex-shrink:0}
.mcr-dot.ok{background:#639922}.mcr-dot.ko{background:#bbb}

@media(max-width:600px){.checklist-grid{grid-template-columns:1fr}}


/* ═══════════════════════════════════════════
   GARAGE V2 — VISTA VEICOLI + SCHEDA
═══════════════════════════════════════════ */

/* ── Vista flotta ── */
.garage-fleet-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(280px,1fr));gap:12px;margin-bottom:1.5rem}
.veh-card{background:#fff;border:.5px solid rgba(0,0,0,.1);border-radius:14px;padding:1rem 1.25rem;cursor:pointer;transition:box-shadow .15s,border-color .15s;position:relative;overflow:hidden}
.veh-card::before{content:'';position:absolute;top:0;left:0;width:100%;height:3px}
.veh-card.vc-disponibile::before{background:#639922}
.veh-card.vc-officina::before{background:#FF6600}
.veh-card.vc-noleggiato::before{background:#E24B4A}
.veh-card.vc-prenotato::before{background:#378ADD}
.veh-card.vc-fuori_servizio::before{background:#999}
.veh-card:hover{border-color:rgba(255,102,0,.35);box-shadow:0 4px 16px rgba(0,0,0,.08)}
.veh-card-top{display:flex;align-items:flex-start;gap:10px;margin-bottom:10px}
.veh-icon{font-size:26px;flex-shrink:0;margin-top:2px}
.veh-title{flex:1;min-width:0}
.veh-targa{font-family:monospace;font-size:13px;font-weight:700;letter-spacing:.08em;background:#eceae3;padding:2px 8px;border-radius:4px;display:inline-block;margin-bottom:3px}
.veh-modello{font-size:13px;font-weight:600;color:#1a1a18;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.veh-tipo-badge{font-size:10px;color:#888;margin-top:1px}
.veh-stato-badge{font-size:10px;font-weight:700;padding:3px 8px;border-radius:99px;white-space:nowrap;flex-shrink:0}
.vsb-disponibile{background:#EAF3DE;color:#3B6D11}
.vsb-officina{background:#FFF0E6;color:#CC5200}
.vsb-noleggiato{background:#FCEBEB;color:#A32D2D}
.vsb-prenotato{background:#E6F1FB;color:#185FA5}
.vsb-fuori_servizio{background:#eceae3;color:#666}
.veh-info-grid{display:grid;grid-template-columns:1fr 1fr;gap:4px 16px;font-size:11px;color:#888;margin-bottom:10px}
.veh-info-item{display:flex;flex-direction:column;gap:1px}
.veh-info-val{font-size:12px;font-weight:600;color:#1a1a18}
.veh-alerts{display:flex;gap:4px;flex-wrap:wrap;margin-top:8px;padding-top:8px;border-top:.5px solid rgba(0,0,0,.06)}
.veh-alert-pill{font-size:10px;font-weight:600;padding:2px 7px;border-radius:99px}
.vap-scaduto{background:#FCEBEB;color:#A32D2D}
.vap-urgente{background:#FAEEDA;color:#854F0B}
.veh-card-actions{position:absolute;bottom:10px;right:10px;display:flex;gap:4px;opacity:0;transition:opacity .15s}
.veh-card:hover .veh-card-actions{opacity:1}

/* ── Vista tabella ── */
.veh-table{width:100%;border-collapse:collapse;font-size:13px;background:#fff;border-radius:12px;overflow:hidden;border:.5px solid rgba(0,0,0,.1)}
.veh-table th{background:#f5f4f0;padding:8px 12px;text-align:left;font-size:11px;font-weight:700;text-transform:uppercase;letter-spacing:.05em;color:#888;white-space:nowrap}
.veh-table td{padding:10px 12px;border-bottom:.5px solid rgba(0,0,0,.05);vertical-align:middle}
.veh-table tr:last-child td{border-bottom:none}
.veh-table tr:hover td{background:#fafaf8;cursor:pointer}

/* ── Vista toggle ── */
.view-toggle{display:flex;gap:4px;background:#f5f4f0;padding:3px;border-radius:8px}
.vtb{padding:4px 10px;border:none;background:none;cursor:pointer;border-radius:6px;font-size:12px;color:#888;font-family:inherit}
.vtb.active{background:#fff;color:#1a1a18;font-weight:600;box-shadow:0 1px 3px rgba(0,0,0,.1)}

/* ── Scheda veicolo ── */
.veh-scheda{background:#fff;border:.5px solid rgba(0,0,0,.1);border-radius:14px;overflow:hidden;margin-bottom:1.5rem}
.veh-scheda-header{background:#1a1a18;padding:1.25rem 1.5rem;display:flex;align-items:center;gap:16px}
.veh-scheda-icon{font-size:36px}
.veh-scheda-info{flex:1}
.veh-scheda-targa{font-family:monospace;font-size:16px;font-weight:700;color:#FF6600;letter-spacing:.1em}
.veh-scheda-modello{font-size:20px;font-weight:700;color:#fff;margin-top:2px}
.veh-scheda-sub{font-size:12px;color:rgba(255,255,255,.5);margin-top:3px}
.veh-scheda-stato{display:flex;flex-direction:column;align-items:flex-end;gap:8px}
.veh-scheda-back{color:rgba(255,255,255,.6);font-size:12px;cursor:pointer;padding:4px 10px;border:.5px solid rgba(255,255,255,.2);border-radius:6px;background:none;font-family:inherit;transition:background .15s}
.veh-scheda-back:hover{background:rgba(255,255,255,.1);color:#fff}

/* ── Tab sistema ── */
.veh-tabs{display:flex;border-bottom:.5px solid rgba(0,0,0,.1);background:#fafaf8;overflow-x:auto}
.veh-tab{padding:10px 18px;font-size:13px;font-weight:500;color:#888;cursor:pointer;border:none;background:none;border-bottom:2px solid transparent;white-space:nowrap;font-family:inherit;transition:color .15s}
.veh-tab:hover{color:#1a1a18}
.veh-tab.active{color:#FF6600;border-bottom-color:#FF6600;font-weight:700}
.veh-tab-content{display:none;padding:1.25rem 1.5rem}
.veh-tab-content.active{display:block}

/* ── Dati veicolo ── */
.veh-data-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:12px 24px;margin-bottom:1.25rem}
.veh-data-field{display:flex;flex-direction:column;gap:3px}
.vdf-label{font-size:11px;font-weight:600;color:#aaa;text-transform:uppercase;letter-spacing:.04em}
.vdf-value{font-size:14px;font-weight:600;color:#1a1a18}
.vdf-value.editable{cursor:pointer;border-bottom:1px dashed #ddd;padding-bottom:1px}
.vdf-value.editable:hover{border-bottom-color:#FF6600;color:#FF6600}

/* ── Documenti tab ── */
.doc-list{display:flex;flex-direction:column;gap:8px}
.doc-item{background:#f5f4f0;border-radius:10px;padding:12px 14px;display:flex;align-items:center;gap:12px}
.doc-item-icon{font-size:20px;flex-shrink:0}
.doc-item-info{flex:1}
.doc-item-name{font-size:13px;font-weight:600}
.doc-item-sub{font-size:11px;color:#888;margin-top:2px}
.doc-scad-badge{font-size:11px;font-weight:700;padding:3px 9px;border-radius:99px;white-space:nowrap;flex-shrink:0}
.dsb-ok{background:#EAF3DE;color:#3B6D11}
.dsb-urgente{background:#FAEEDA;color:#854F0B}
.dsb-scaduto{background:#FCEBEB;color:#A32D2D}
.dsb-nd{background:#eceae3;color:#888}

/* ── Manutenzioni tab ── */
.maint-timeline{display:flex;flex-direction:column;gap:0}
.mt-item{display:flex;gap:14px;padding:12px 0;position:relative}
.mt-item:not(:last-child)::after{content:'';position:absolute;left:15px;top:36px;bottom:0;width:2px;background:rgba(0,0,0,.07)}
.mt-dot{width:30px;height:30px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:13px;flex-shrink:0;border:2px solid #fff;box-shadow:0 0 0 1px rgba(0,0,0,.1)}
.mt-dot.completato{background:#EAF3DE}
.mt-dot.aperto{background:#FAEEDA}
.mt-dot.in_corso{background:#E6F1FB}
.mt-dot.attesa{background:#F3E9FB}
.mt-content{flex:1}
.mt-title{font-size:13px;font-weight:600}
.mt-meta{font-size:11px;color:#888;margin-top:2px;display:flex;gap:10px;flex-wrap:wrap}
.mt-desc{font-size:12px;color:#555;margin-top:4px;line-height:1.4}

/* ── Storico tab ── */
.storico-timeline{display:flex;flex-direction:column;gap:0}
.st-item{display:flex;gap:12px;padding:10px 0;position:relative}
.st-item:not(:last-child)::after{content:'';position:absolute;left:11px;top:32px;bottom:0;width:1.5px;background:rgba(0,0,0,.07)}
.st-dot{width:22px;height:22px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:10px;flex-shrink:0;margin-top:2px}
.std-noleggio{background:#E6F1FB;color:#185FA5}
.std-manutenzione{background:#FFF0E6;color:#CC5200}
.std-sinistro{background:#FCEBEB;color:#A32D2D}
.std-documento{background:#EAF3DE;color:#3B6D11}
.std-stato{background:#eceae3;color:#666}
.st-content{flex:1}
.st-title{font-size:12px;font-weight:600}
.st-sub{font-size:11px;color:#888;margin-top:1px}
.st-date{font-size:11px;color:#aaa;white-space:nowrap;margin-left:auto}

@media(max-width:700px){
  .veh-data-grid{grid-template-columns:1fr 1fr}
  .garage-fleet-grid{grid-template-columns:1fr}
  .veh-tabs{gap:0}
  .veh-tab{padding:8px 12px;font-size:12px}
}


/* ═══════════════════════════════════════════
   NOLEGGI WIZARD + OFFICINA SEPARATA
═══════════════════════════════════════════ */

/* ── Wizard steps ── */
.wizard-steps{display:flex;gap:0;margin-bottom:1.5rem;overflow-x:auto}
.wizard-step{display:flex;align-items:center;gap:0;flex:1;min-width:0}
.ws-dot{width:28px;height:28px;border-radius:50%;background:#eceae3;color:#aaa;display:flex;align-items:center;justify-content:center;font-size:12px;font-weight:700;flex-shrink:0;border:2px solid #eceae3;transition:all .2s}
.ws-label{font-size:11px;font-weight:600;color:#aaa;margin:0 8px;white-space:nowrap;transition:color .2s}
.ws-line{flex:1;height:2px;background:#eceae3;margin:0 4px;transition:background .2s}
.wizard-step.active .ws-dot{background:#FF6600;border-color:#FF6600;color:#fff}
.wizard-step.active .ws-label{color:#FF6600}
.wizard-step.done .ws-dot{background:#639922;border-color:#639922;color:#fff}
.wizard-step.done .ws-label{color:#639922}
.wizard-step.done .ws-line{background:#639922}

.wizard-panel{display:none}
.wizard-panel.active{display:block}
.wizard-nav{display:flex;justify-content:space-between;align-items:center;margin-top:1.25rem;padding-top:1rem;border-top:.5px solid rgba(0,0,0,.08)}

/* ── Selezione azienda/autista ── */
.search-select-wrap{position:relative;margin-bottom:1rem}
.search-select-input{width:100%;padding:8px 12px 8px 32px;border:.5px solid rgba(0,0,0,.2);border-radius:8px;font-size:13px;font-family:inherit;background:#fff url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='14' height='14' fill='%23999' viewBox='0 0 16 16'%3E%3Cpath d='M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.099zm-5.242 1.656a5.5 5.5 0 1 1 0-11 5.5 5.5 0 0 1 0 11z'/%3E%3C/svg%3E") 10px center no-repeat}
.search-dropdown{position:absolute;top:100%;left:0;right:0;background:#fff;border:.5px solid rgba(0,0,0,.15);border-top:none;border-radius:0 0 8px 8px;box-shadow:0 4px 16px rgba(0,0,0,.1);z-index:50;max-height:220px;overflow-y:auto;display:none}
.search-dropdown.open{display:block}
.search-opt{padding:9px 12px;cursor:pointer;font-size:13px;transition:background .12s;display:flex;align-items:center;gap:8px}
.search-opt:hover{background:#f5f4f0}
.search-opt.selected{background:#FFF0E6;color:#CC5200;font-weight:600}
.search-opt-icon{font-size:14px;flex-shrink:0}
.search-opt-main{font-weight:600}
.search-opt-sub{font-size:11px;color:#888;margin-top:1px}
.search-opt-new{padding:9px 12px;cursor:pointer;font-size:12px;color:#FF6600;font-weight:600;border-top:.5px solid rgba(0,0,0,.06);display:flex;align-items:center;gap:6px}
.search-opt-new:hover{background:#FFF0E6}

/* ── Selected card ── */
.selected-card{background:#EAF3DE;border:.5px solid #C0DD97;border-radius:10px;padding:10px 14px;display:flex;align-items:center;gap:10px;margin-bottom:1rem}
.selected-card.azienda{background:#E6F1FB;border-color:#A8CFF0}
.selected-card.autista{background:#EAF3DE;border-color:#C0DD97}
.selected-card.veicolo{background:#FFF0E6;border-color:#FFCBA4}
.selected-card-icon{font-size:20px;flex-shrink:0}
.selected-card-info{flex:1}
.selected-card-name{font-size:13px;font-weight:700}
.selected-card-sub{font-size:11px;color:#666;margin-top:1px}
.selected-card-clear{font-size:11px;color:#aaa;cursor:pointer;padding:2px 6px;border-radius:4px;background:rgba(0,0,0,.05)}
.selected-card-clear:hover{background:rgba(0,0,0,.1)}

/* ── Autisti per azienda ── */
.autisti-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(200px,1fr));gap:8px;margin-bottom:1rem}
.autista-card{background:#fff;border:.5px solid rgba(0,0,0,.1);border-radius:10px;padding:10px 12px;cursor:pointer;transition:border-color .15s}
.autista-card:hover{border-color:#FF6600}
.autista-card.selected{border-color:#FF6600;background:#FFF0E6}
.autista-card-name{font-size:13px;font-weight:600}
.autista-card-sub{font-size:11px;color:#888;margin-top:2px}
.autista-card-badge{font-size:10px;font-weight:700;padding:1px 6px;border-radius:99px;margin-top:4px;display:inline-block}
.acb-ok{background:#EAF3DE;color:#3B6D11}
.acb-warn{background:#FAEEDA;color:#854F0B}
.acb-exp{background:#FCEBEB;color:#A32D2D}

/* ── Veicoli disponibili ── */
.veh-pick-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(220px,1fr));gap:8px;margin-bottom:1rem}
.veh-pick-card{background:#fff;border:.5px solid rgba(0,0,0,.1);border-radius:10px;padding:10px 12px;cursor:pointer;transition:border-color .15s}
.veh-pick-card:hover{border-color:#FF6600}
.veh-pick-card.selected{border-color:#FF6600;background:#FFF0E6}
.veh-pick-card.blocked{opacity:.45;cursor:not-allowed;background:#f5f4f0}
.vpc-plate{font-family:monospace;font-weight:700;font-size:12px;background:#eceae3;padding:1px 6px;border-radius:3px}
.vpc-model{font-size:13px;font-weight:600;margin-top:4px}
.vpc-meta{font-size:11px;color:#888;margin-top:2px}
.vpc-block-reason{font-size:10px;color:#A32D2D;font-weight:600;margin-top:3px}

/* ── Officina separata ── */
.off-kanban{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;margin-bottom:1.5rem}
.off-topbar{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:1.25rem;align-items:center}

/* ── Noleggi lista moderna ── */
.nol-list{display:flex;flex-direction:column;gap:8px;margin-bottom:1.5rem}
.nol-card{background:#fff;border:.5px solid rgba(0,0,0,.1);border-radius:12px;padding:1rem 1.25rem;transition:box-shadow .15s;border-left:3px solid transparent}
.nol-card.aperto{border-left-color:#EF9F27}
.nol-card.chiuso{border-left-color:#639922}
.nol-card.ritardo{border-left-color:#E24B4A}
.nol-card-header{display:flex;align-items:center;gap:10px;margin-bottom:8px}
.nol-badge{font-size:10px;font-weight:700;padding:3px 8px;border-radius:99px}
.nb-aperto{background:#FAEEDA;color:#854F0B}
.nb-chiuso{background:#EAF3DE;color:#3B6D11}
.nb-ritardo{background:#FCEBEB;color:#A32D2D}
.nol-meta{display:flex;gap:16px;flex-wrap:wrap;font-size:12px;color:#666}

/* ── Form inline autista ── */
.new-autista-form{background:#f5f4f0;border-radius:10px;padding:1rem;margin-top:.75rem;border:.5px dashed #FF6600}
.new-autista-title{font-size:12px;font-weight:600;color:#FF6600;margin-bottom:.75rem;display:flex;align-items:center;gap:6px}

@media(max-width:700px){
  .off-kanban{grid-template-columns:1fr 1fr}
  .autisti-grid,.veh-pick-grid{grid-template-columns:1fr}
  .wizard-steps{gap:0}
}


/* ═══════════════════════════════════════════
   SCADENZE V2 — ALERT CENTER
═══════════════════════════════════════════ */
.scad-topbar{display:flex;gap:8px;flex-wrap:wrap;align-items:center;margin-bottom:1.25rem}
.scad-filter-tabs{display:flex;gap:4px;background:#f5f4f0;padding:3px;border-radius:8px}
.sft{padding:4px 12px;border:none;background:none;cursor:pointer;border-radius:6px;font-size:12px;font-weight:600;color:#888;font-family:inherit;transition:all .15s}
.sft.active{background:#fff;box-shadow:0 1px 3px rgba(0,0,0,.1)}
.sft.rosso.active{color:#A32D2D}
.sft.arancio.active{color:#854F0B}
.sft.verde.active{color:#3B6D11}
.sft.tutti.active{color:#1a1a18}

/* Alert list */
.alert-center{display:flex;flex-direction:column;gap:6px}

.scad-row{display:flex;align-items:center;gap:12px;background:#fff;border:.5px solid rgba(0,0,0,.1);border-radius:10px;padding:10px 14px;transition:box-shadow .15s;cursor:pointer;border-left:3px solid transparent}
.scad-row:hover{box-shadow:0 2px 8px rgba(0,0,0,.08)}
.scad-row.scaduto{border-left-color:#E24B4A;background:#FFFAFA}
.scad-row.urgente7{border-left-color:#E24B4A;background:#FFFAFA}
.scad-row.urgente{border-left-color:#EF9F27;background:#FFFDF7}
.scad-row.ok{border-left-color:#C0DD97;background:#FAFFF7}

.scad-icon{font-size:20px;flex-shrink:0;width:28px;text-align:center}
.scad-targa{font-family:monospace;font-size:12px;font-weight:700;background:#eceae3;padding:2px 7px;border-radius:4px;letter-spacing:.06em;flex-shrink:0}
.scad-tipo{font-size:13px;font-weight:600;flex:1;min-width:0}
.scad-sottotipo{font-size:11px;color:#888;margin-top:1px}
.scad-data{font-size:12px;color:#666;white-space:nowrap;flex-shrink:0}

.scad-giorni{font-size:12px;font-weight:700;white-space:nowrap;flex-shrink:0;padding:3px 9px;border-radius:99px}
.scad-giorni.scaduto{background:#FCEBEB;color:#A32D2D}
.scad-giorni.urgente7{background:#FCEBEB;color:#A32D2D}
.scad-giorni.urgente{background:#FAEEDA;color:#854F0B}
.scad-giorni.ok{background:#EAF3DE;color:#3B6D11}

.scad-goto{font-size:11px;color:#FF6600;padding:3px 8px;border:.5px solid #FF9955;border-radius:5px;background:none;cursor:pointer;font-family:inherit;flex-shrink:0;transition:background .12s}
.scad-goto:hover{background:#FFF0E6}

/* Separatori gruppo */
.scad-group-header{font-size:11px;font-weight:700;text-transform:uppercase;letter-spacing:.07em;color:#aaa;padding:10px 2px 4px;display:flex;align-items:center;gap:8px}
.scad-group-header::after{content:'';flex:1;height:1px;background:rgba(0,0,0,.07)}
.scad-group-header.rosso{color:#A32D2D}
.scad-group-header.arancio{color:#854F0B}
.scad-group-header.verde{color:#639922}

/* Form aggiunta scadenza — compatto */
.scad-add-form{background:#f5f4f0;border-radius:12px;padding:1rem 1.25rem;margin-top:1rem}
.scad-add-title{font-size:12px;font-weight:600;color:#888;text-transform:uppercase;letter-spacing:.05em;margin-bottom:.75rem;display:flex;align-items:center;gap:6px}

/* KPI migliorati */
.scad-kpi-row{display:grid;grid-template-columns:repeat(5,1fr);gap:10px;margin-bottom:1.25rem}
.scad-kpi{background:#fff;border:.5px solid rgba(0,0,0,.1);border-radius:10px;padding:.75rem 1rem;text-align:center;cursor:pointer;transition:box-shadow .15s}
.scad-kpi:hover{box-shadow:0 2px 8px rgba(0,0,0,.07)}
.scad-kpi-val{font-size:24px;font-weight:700;line-height:1}
.scad-kpi-lbl{font-size:10px;color:#aaa;text-transform:uppercase;letter-spacing:.05em;margin-top:3px;font-weight:600}
.skv-red{color:#A32D2D}.skv-amber{color:#854F0B}.skv-green{color:#3B6D11}
.skv-blue{color:#185FA5}.skv-gray{color:#888}

@media(max-width:700px){
  .scad-kpi-row{grid-template-columns:repeat(3,1fr)}
  .scad-row{flex-wrap:wrap;gap:8px}
}


/* ═══════════════════════════════════════════
   SCHEDA VEICOLO — DOCUMENTI & COSTI INLINE
═══════════════════════════════════════════ */

/* Tab documenti */
.doc-inline-grid{display:flex;flex-direction:column;gap:10px}
.doc-inline-card{background:#f5f4f0;border-radius:10px;overflow:hidden}
.doc-inline-header{display:flex;align-items:center;gap:10px;padding:10px 14px;cursor:pointer;transition:background .12s}
.doc-inline-header:hover{background:#eceae3}
.dic-icon{font-size:18px;flex-shrink:0}
.dic-name{font-size:13px;font-weight:600;flex:1}
.dic-scad{font-size:12px;font-weight:700;padding:2px 8px;border-radius:99px;white-space:nowrap}
.dic-scad.scaduto{background:#FCEBEB;color:#A32D2D}
.dic-scad.urgente7{background:#FCEBEB;color:#A32D2D}
.dic-scad.urgente{background:#FAEEDA;color:#854F0B}
.dic-scad.ok{background:#EAF3DE;color:#3B6D11}
.dic-scad.nd{background:#eceae3;color:#888}
.dic-edit-btn{font-size:11px;padding:2px 8px;height:auto;color:#FF6600;border-color:#FF9955;background:none;cursor:pointer;font-family:inherit;border:.5px solid;border-radius:5px;transition:background .12s;flex-shrink:0}
.dic-edit-btn:hover{background:#FFF0E6}
.dic-chevron{font-size:10px;color:#aaa;flex-shrink:0;transition:transform .2s}
.dic-chevron.open{transform:rotate(90deg)}

.doc-inline-form{display:none;padding:12px 14px;border-top:.5px solid rgba(0,0,0,.08);background:#fff}
.doc-inline-form.open{display:block}
.doc-form-row{display:grid;grid-template-columns:repeat(4,1fr);gap:8px;margin-bottom:8px}
.doc-form-row.r3{grid-template-columns:repeat(3,1fr)}
.doc-form-row.r2{grid-template-columns:1fr 1fr}
.doc-save-btn{height:32px;padding:0 14px;font-size:12px;background:#FF6600;color:#fff;border:none;border-radius:6px;cursor:pointer;font-family:inherit;font-weight:600}
.doc-save-btn:hover{background:#CC5200}

/* KM update inline */
.km-inline{display:flex;align-items:center;gap:8px;background:#f5f4f0;border-radius:8px;padding:8px 12px;margin-bottom:.75rem}
.km-inline-val{font-size:18px;font-weight:700;color:#1a1a18;min-width:80px}
.km-inline-input{width:120px;text-align:right}

/* Costi tab */
.costi-summary{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-bottom:1.25rem}
.costo-kpi{background:#f5f4f0;border-radius:10px;padding:10px 14px;text-align:center}
.ck-val{font-size:20px;font-weight:700;color:#1a1a18}
.ck-lbl{font-size:10px;color:#aaa;text-transform:uppercase;letter-spacing:.05em;margin-top:2px;font-weight:600}
.costi-list{display:flex;flex-direction:column;gap:6px}
.costo-row{display:flex;align-items:center;gap:10px;background:#fff;border:.5px solid rgba(0,0,0,.1);border-radius:8px;padding:8px 12px;font-size:12px}
.costo-row-tipo{font-size:14px;flex-shrink:0}
.costo-row-desc{flex:1;font-weight:500}
.costo-row-data{color:#888;white-space:nowrap}
.costo-row-val{font-weight:700;color:#1a1a18;white-space:nowrap}
.costo-row-del{color:#bbb;cursor:pointer;padding:0 4px;font-size:14px}
.costo-row-del:hover{color:#E24B4A}

/* Allegati tab */
.allegati-area{border:1.5px dashed #ddd;border-radius:10px;padding:1.5rem;text-align:center;color:#aaa;font-size:13px;margin-bottom:1rem;cursor:pointer;transition:border-color .15s,background .15s}
.allegati-area:hover{border-color:#FF6600;background:#FFF0E6}
.allegati-list{display:grid;grid-template-columns:repeat(auto-fill,minmax(140px,1fr));gap:8px}
.allegato-card{background:#f5f4f0;border-radius:8px;padding:10px;text-align:center;font-size:11px;position:relative}
.allegato-icon{font-size:24px;margin-bottom:4px}
.allegato-name{font-weight:600;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
.allegato-del{position:absolute;top:4px;right:4px;color:#bbb;cursor:pointer;font-size:12px}
.allegato-del:hover{color:#E24B4A}

/* Stato scadenze nella sezione — read only */
.scad-readonly-notice{background:#EAF3DE;border:.5px solid #C0DD97;border-radius:8px;padding:10px 14px;font-size:12px;color:#3B6D11;display:flex;align-items:center;gap:8px;margin-bottom:1rem}

@media(max-width:600px){
  .doc-form-row{grid-template-columns:1fr 1fr}
  .costi-summary{grid-template-columns:1fr 1fr}
}


/* ═══════════════════════════════════════════
   NOLEGGIO — MODIFICA & STORICO
═══════════════════════════════════════════ */

/* Stato contratto badge */
.stato-nol{font-size:11px;font-weight:700;padding:3px 9px;border-radius:99px;white-space:nowrap}
.sn-aperto  {background:#FAEEDA;color:#854F0B;border:.5px solid #F5D49A}
.sn-attivo  {background:#EAF3DE;color:#3B6D11;border:.5px solid #C0DD97}
.sn-scaduto {background:#FCEBEB;color:#A32D2D;border:.5px solid #F7C1C1}
.sn-chiuso  {background:#eceae3;color:#666;border:.5px solid #ccc}
.sn-rinnovato{background:#E6F1FB;color:#185FA5;border:.5px solid #A8CFF0}

/* Card noleggio migliorata */
.mov-card{border-left:3px solid transparent;transition:border-color .15s}
.mov-card.mc-aperto   {border-left-color:#EF9F27}
.mov-card.mc-attivo   {border-left-color:#639922}
.mov-card.mc-scaduto  {border-left-color:#E24B4A}
.mov-card.mc-chiuso   {border-left-color:#aaa}
.mov-card.mc-ritardo  {border-left-color:#E24B4A}

/* Panel modifica noleggio */
.edit-nol-panel{background:#f5f4f0;border-radius:12px;padding:1.25rem;margin-top:10px;border:.5px solid rgba(0,0,0,.12)}
.edit-nol-title{font-size:13px;font-weight:600;margin-bottom:1rem;display:flex;align-items:center;gap:8px;color:#1a1a18}
.edit-nol-tabs{display:flex;gap:4px;margin-bottom:1rem;border-bottom:.5px solid rgba(0,0,0,.1);padding-bottom:0}
.ent{padding:6px 14px;border:none;background:none;cursor:pointer;font-size:12px;font-weight:600;color:#aaa;border-bottom:2px solid transparent;font-family:inherit;transition:color .15s}
.ent.active{color:#FF6600;border-bottom-color:#FF6600}
.ent-panel{display:none}.ent-panel.active{display:block}

/* Sezione dati contratto */
.contratto-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:8px 12px;margin-bottom:.75rem}
.contratto-grid.r3{grid-template-columns:repeat(3,1fr)}
.contratto-grid.r2{grid-template-columns:1fr 1fr}

/* Riepilogo costi contratto */
.costo-summary-nol{display:grid;grid-template-columns:repeat(4,1fr);gap:8px;background:#fff;border-radius:10px;padding:10px;margin-bottom:.75rem}
.csn-item{text-align:center}
.csn-val{font-size:16px;font-weight:700;color:#1a1a18}
.csn-lbl{font-size:10px;color:#aaa;text-transform:uppercase;letter-spacing:.04em;margin-top:2px}

/* Timeline modifiche */
.edit-timeline{display:flex;flex-direction:column;gap:0;max-height:300px;overflow-y:auto}
.et-item{display:flex;gap:10px;padding:8px 0;position:relative;font-size:12px}
.et-item:not(:last-child)::after{content:'';position:absolute;left:9px;top:28px;bottom:0;width:1.5px;background:rgba(0,0,0,.08)}
.et-dot{width:18px;height:18px;border-radius:50%;background:#f5f4f0;border:.5px solid #ddd;display:flex;align-items:center;justify-content:center;font-size:9px;flex-shrink:0;margin-top:2px}
.et-content{flex:1}
.et-what{font-weight:600;color:#1a1a18}
.et-detail{color:#888;margin-top:1px;line-height:1.4}
.et-date{font-size:10px;color:#bbb;white-space:nowrap;margin-left:auto}

/* Stato selector per noleggio */
.stato-nol-selector{display:flex;gap:6px;flex-wrap:wrap;margin-top:6px}
.sns-btn{font-size:11px;padding:4px 10px;border-radius:6px;cursor:pointer;border:.5px solid rgba(0,0,0,.2);background:#fff;color:#666;font-family:inherit;transition:all .15s;font-weight:600}
.sns-btn.selected{box-shadow:inset 0 0 0 1.5px currentColor}
.sns-btn[data-s="aperto"].selected  {background:#FAEEDA;color:#854F0B}
.sns-btn[data-s="attivo"].selected  {background:#EAF3DE;color:#3B6D11}
.sns-btn[data-s="scaduto"].selected {background:#FCEBEB;color:#A32D2D}
.sns-btn[data-s="chiuso"].selected  {background:#eceae3;color:#555}
.sns-btn[data-s="rinnovato"].selected{background:#E6F1FB;color:#185FA5}

/* Differenza giorni badge */
.diff-badge{font-size:10px;font-weight:700;padding:2px 6px;border-radius:4px}
.db-ok{background:#EAF3DE;color:#3B6D11}
.db-warn{background:#FAEEDA;color:#854F0B}
.db-exp{background:#FCEBEB;color:#A32D2D}

@media(max-width:700px){
  .contratto-grid{grid-template-columns:1fr 1fr}
  .costo-summary-nol{grid-template-columns:1fr 1fr}
}


/* ═══════════════════════════════════════════
   FORM NUOVO VEICOLO
═══════════════════════════════════════════ */
.new-veh-panel{background:#fff;border:.5px solid rgba(0,0,0,.12);border-radius:14px;padding:1.25rem;margin-bottom:1.25rem}
.new-veh-title{font-size:15px;font-weight:700;margin-bottom:1.25rem;display:flex;align-items:center;gap:10px}
.new-veh-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:10px 14px;margin-bottom:.75rem}
.new-veh-grid.r3{grid-template-columns:repeat(3,1fr)}
.new-veh-grid.r2{grid-template-columns:1fr 1fr}
.new-veh-sep{font-size:11px;font-weight:700;text-transform:uppercase;letter-spacing:.06em;color:#aaa;padding:.5rem 0 .25rem;border-top:.5px solid rgba(0,0,0,.08);margin-top:.25rem;grid-column:1/-1}
.poss-toggle{display:flex;gap:6px;margin-bottom:.75rem}
.pt-btn{padding:6px 16px;border:.5px solid rgba(0,0,0,.2);border-radius:8px;cursor:pointer;font-size:13px;font-weight:600;font-family:inherit;background:#fff;color:#666;transition:all .15s}
.pt-btn.active{background:#1a1a18;color:#fff;border-color:#1a1a18}
@media(max-width:700px){.new-veh-grid{grid-template-columns:1fr 1fr}}


/* ═══════════════════════════════════════════
   PERIODO NOLEGGIO
═══════════════════════════════════════════ */
.periodo-bar{background:#f5f4f0;border-radius:10px;padding:10px 14px;margin:8px 0;display:flex;align-items:center;gap:12px;flex-wrap:wrap;border:.5px solid rgba(0,0,0,.07)}
.periodo-badge{font-size:12px;font-weight:700;padding:4px 10px;border-radius:99px;white-space:nowrap}
.pb-inCorso{background:#FFF0E6;color:#CC5200;border:.5px solid #FFCBA4}
.pb-completato{background:#EAF3DE;color:#3B6D11;border:.5px solid #C0DD97}
.pb-ritardo{background:#FCEBEB;color:#A32D2D;border:.5px solid #F7C1C1}
.periodo-col{display:flex;flex-direction:column;gap:1px;min-width:80px}
.periodo-lbl{font-size:10px;font-weight:700;color:#aaa;text-transform:uppercase;letter-spacing:.05em}
.periodo-val{font-size:13px;font-weight:700;color:#1a1a18}
.periodo-val.arancio{color:#CC5200}
.periodo-val.verde{color:#3B6D11}
.periodo-sep{width:1px;height:32px;background:rgba(0,0,0,.1);flex-shrink:0}
.periodo-progressbar{flex:1;min-width:100px}
.periodo-pb-wrap{height:6px;background:#eceae3;border-radius:99px;overflow:hidden;margin-top:4px}
.periodo-pb-fill{height:100%;border-radius:99px;transition:width .3s}
.periodo-pb-lbl{font-size:10px;color:#aaa;margin-top:2px}

</style>
</head>
<body>

<!-- ══ SIDEBAR ════════════════════════════════════════════ -->
<aside class="sidebar" id="sidebar">
  <div class="sidebar-logo">
    <img src="data:image/jpeg;base64,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" alt="Vieffe Rent">
    <div class="sidebar-company">Via Canturina 49, Como (CO) 22100</div>
  </div>
  <nav class="sidebar-nav" id="sidebar-nav">
    <div class="sidebar-section">Principale</div>
    <button class="nav-item active" id="nav-dashboard" onclick="switchMain('dashboard')">
      <span class="nav-icon">📊</span> Dashboard
    </button>
    <div class="sidebar-section">Flotta</div>
    <button class="nav-item" id="nav-noleggi" onclick="switchMain('noleggi')">
      <span class="nav-icon">🔑</span> Noleggi
      <span class="nav-badge" id="nb-mov" style="display:none">0</span>
    </button>
    <button class="nav-item" id="nav-clienti" onclick="switchMain('clienti')">
      <span class="nav-icon">👥</span> Clienti
      <span class="nav-badge" id="nb-cli-bl" style="display:none">BL</span>
    </button>
    <button class="nav-item" id="nav-garage" onclick="switchMain('garage')">
      <span class="nav-icon">🚛</span> Mezzi
      <span class="nav-badge amber" id="nb-gar" style="display:none">0</span>
    </button>
    <div class="sidebar-section">Tecnico</div>
    <button class="nav-item" id="nav-officina" onclick="switchMain('officina')">
      <span class="nav-icon">🔧</span> Officina
      <span class="nav-badge amber" id="nb-off" style="display:none">0</span>
    </button>
    <button class="nav-item" id="nav-sinistri" onclick="switchMain('sinistri')">
      <span class="nav-icon">⚠️</span> Sinistri
      <span class="nav-badge" id="nb-sin" style="display:none">0</span>
    </button>
    <div class="sidebar-section">Sistema</div>
    <button class="nav-item" id="nav-scadenze" onclick="switchMain('scadenze')">
      <span class="nav-icon">📋</span> Scadenze
      <span class="nav-badge amber" id="nb-scad" style="display:none">0</span>
    </button>
  </nav>
  <div class="sidebar-footer">
    Vieffe Rent Srl &nbsp;·&nbsp; Gestionale flotta v2.0
  </div>
</aside>

<!-- ══ MAIN AREA ═══════════════════════════════════════════ -->
<div class="main-area">

  <!-- Topbar -->
  <div class="topbar">
    <button class="menu-toggle" onclick="toggleMenu()">☰</button>
    <div class="topbar-title" id="topbar-title">Dashboard</div>
    <div class="topbar-date" id="topbar-date"></div>
    <span class="topbar-badge scad" id="tb-alerts" style="display:none" onclick="switchMain('scadenze')">⚠️ Scadenze</span>
    <div class="topbar-notif" onclick="toggleNotifPanel()" data-tooltip="Notifiche" id="notif-btn">
      <span class="notif-icon">🔔</span>
      <span class="notif-dot" id="notif-dot"></span>
    </div>
  </div>

  <!-- Notifiche dropdown -->
  <div class="notif-panel" id="notif-panel">
    <div class="notif-header">🔔 Notifiche operative <span id="notif-count" style="margin-left:auto;font-size:11px;color:#aaa"></span></div>
    <div class="notif-list" id="notif-list"></div>
  </div>

  <!-- Modal overlay -->
  <div class="modal-overlay" id="modal-overlay" onclick="closeModal(event)">
    <div class="modal-box" id="modal-box">
      <div class="modal-title" id="modal-title"></div>
      <div id="modal-body"></div>
      <div class="modal-actions">
        <button onclick="closeModal()">Chiudi</button>
      </div>
    </div>
  </div>

  <!-- Scroll to top -->
  <button class="scroll-top" id="scroll-top" onclick="scrollToTop()" data-tooltip="Torna su">↑</button>

  <!-- Content -->
  <div class="content">
  <div class="wrap">

<!-- PAGE DASHBOARD -->
<div id="page-dashboard" class="page active">
  <!-- KPI Row -->
  <div class="dash-grid">
    <div class="kpi kpi-green">
      <div class="kpi-icon">✅</div>
      <div class="kpi-value green" id="kpi-disponibili">—</div>
      <div class="kpi-label">Disponibili</div>
    </div>
    <div class="kpi kpi-red">
      <div class="kpi-icon">🔑</div>
      <div class="kpi-value red" id="kpi-noleggiati">—</div>
      <div class="kpi-label">Noleggiati</div>
    </div>
    <div class="kpi kpi-orange">
      <div class="kpi-icon">🔧</div>
      <div class="kpi-value orange" id="kpi-officina">—</div>
      <div class="kpi-label">In officina</div>
    </div>
    <div class="kpi kpi-blue">
      <div class="kpi-icon">📅</div>
      <div class="kpi-value blue" id="kpi-rientri">—</div>
      <div class="kpi-label">Rientri oggi</div>
    </div>
    <div class="kpi kpi-amber">
      <div class="kpi-icon">⚠️</div>
      <div class="kpi-value amber" id="kpi-scadenze">—</div>
      <div class="kpi-label">Scadenze urgenti</div>
    </div>
  </div>

  <div class="dash-sep"></div>

  <!-- Stato flotta + Alert scadenze -->
  <div class="dash-row">
    <div class="dash-panel">
      <div class="dash-panel-title"><span>🚛</span> Stato flotta live</div>
      <div class="fleet-grid" id="dash-fleet"></div>
    </div>
    <div class="dash-panel">
      <div class="dash-panel-title"><span>⚠️</span> Alert scadenze</div>
      <div class="alert-list" id="dash-alerts"></div>
    </div>
  </div>

  <!-- Garage + Sinistri summary -->
  <div class="dash-row" style="margin-bottom:14px">
    <div class="dash-panel">
      <div class="dash-panel-title"><span>🔧</span> Interventi aperti
        <button onclick="switchMain('garage')" style="margin-left:auto;height:auto;padding:2px 8px;font-size:11px;color:#FF6600;border-color:#FF6600">Vedi tutti →</button>
      </div>
      <div id="dash-garage-preview" style="display:flex;flex-direction:column;gap:6px"></div>
    </div>
    <div class="dash-panel">
      <div class="dash-panel-title"><span>⚠️</span> Sinistri aperti
        <button onclick="switchMain('sinistri')" style="margin-left:auto;height:auto;padding:2px 8px;font-size:11px;color:#FF6600;border-color:#FF6600">Vedi tutti →</button>
      </div>
      <div id="dash-sinistri-preview" style="display:flex;flex-direction:column;gap:6px"></div>
    </div>
  </div>

  <!-- Rientri previsti + Attività recenti -->
  <div class="dash-row">
    <div class="dash-panel">
      <div class="dash-panel-title"><span>🏁</span> Rientri previsti oggi</div>
      <div class="rientri-list" id="dash-rientri"></div>
    </div>
    <div class="dash-panel">
      <div class="dash-panel-title"><span>🕐</span> Attività recenti</div>
      <div class="activity-list" id="dash-activity"></div>
    </div>
  </div>
</div>

<!-- PAGE SCADENZE -->
<div id="page-scadenze" class="page">

  <!-- KPI rapidi -->
  <div class="scad-kpi-row">
    <div class="scad-kpi" onclick="setScadFilter('scaduto')">
      <div class="scad-kpi-val skv-red" id="cnt-s">0</div>
      <div class="scad-kpi-lbl">🔴 Scaduti</div>
    </div>
    <div class="scad-kpi" onclick="setScadFilter('urgente7')">
      <div class="scad-kpi-val skv-red" id="cnt-u7">0</div>
      <div class="scad-kpi-lbl">🔴 Entro 7 gg</div>
    </div>
    <div class="scad-kpi" onclick="setScadFilter('urgente')">
      <div class="scad-kpi-val skv-amber" id="cnt-u">0</div>
      <div class="scad-kpi-lbl">🟡 Entro 30 gg</div>
    </div>
    <div class="scad-kpi" onclick="setScadFilter('ok')">
      <div class="scad-kpi-val skv-green" id="cnt-o">0</div>
      <div class="scad-kpi-lbl">🟢 OK</div>
    </div>
    <div class="scad-kpi" onclick="setScadFilter('all')">
      <div class="scad-kpi-val skv-gray" id="cnt-tot">0</div>
      <div class="scad-kpi-lbl">Totali</div>
    </div>
  </div>

  <!-- Topbar filtri -->
  <div class="scad-topbar">
    <input type="text" id="search" placeholder="Cerca targa, tipo..." oninput="render()" style="max-width:200px">
    <select id="scad-filter-tipo" onchange="render()" style="max-width:170px">
      <option value="all">Tutti i tipi</option>
      <option value="Assicurazione">📄 Assicurazione</option>
      <option value="Revisione">🔍 Revisione</option>
      <option value="Bollo">💳 Bollo</option>
      <option value="Tagliando">🔩 Tagliando</option>
      <option value="Tachigrafo">📡 Tachigrafo</option>
      <option value="Leasing">🏦 Leasing</option>
      <option value="Licenza">📜 Licenze</option>
      <option value="Permesso">🛂 Permessi</option>
      <option value="Patente">🪪 Patente autisti</option>
      <option value="Manutenzione">🔧 Manutenzione</option>
      <option value="Contratto">📋 Contratti</option>
    </select>
    <div class="scad-filter-tabs" id="scad-filter-tabs">
      <button class="sft rosso active" onclick="setScadFilter('urgenti')" id="sft-urgenti">🔴 Urgenti</button>
      <button class="sft arancio" onclick="setScadFilter('prossimi')" id="sft-prossimi">🟡 30 gg</button>
      <button class="sft verde" onclick="setScadFilter('ok')" id="sft-ok">🟢 OK</button>
      <button class="sft tutti" onclick="setScadFilter('all')" id="sft-all">Tutti</button>
    </div>
    <button class="btn-primary" onclick="switchMain('garage')" style="background:#1a1a18;border-color:#1a1a18" title="Le scadenze si gestiscono dalla scheda veicolo">🚛 Gestisci dalla scheda mezzo</button>
    <button onclick="exportCSV('scadenze')" style="font-size:12px;padding:0 12px" data-tooltip="Esporta CSV">📥 CSV</button>
  </div>

  <!-- Form aggiunta scadenza (nascosto di default) -->
  <div id="scad-add-form" style="display:none" aria-hidden="true">
    <div class="scad-add-form">
      <div class="scad-add-title">✏️ Aggiungi scadenza operativa</div>
      <div class="row r5">
        <div class="fg"><label>Targa *</label><input type="text" id="n-targa" placeholder="AB123CD" style="text-transform:uppercase"></div>
        <div class="fg"><label>Tipo scadenza</label>
          <select id="n-cat"><option>Assicurazione</option><option>Revisione</option><option>Bollo</option><option>Tagliando</option><option>Altro</option></select>
        </div>
        <div class="fg"><label>Data scadenza *</label><input type="date" id="n-date"></div>
        <div class="fg"><label>Note</label><input type="text" id="n-note" placeholder="Opzionale"></div>
        <button class="btn-primary" onclick="addScad()">Aggiungi</button>
      </div>
    </div>
    <!-- Form mezzo nascosto ma presente per compatibilità con saveMezzo/deleteMezzo -->
    <div style="display:none">
      <input type="text" id="m-targa"><input type="text" id="m-fornitore">
      <select id="m-tipo"><option>Auto</option><option>Furgone</option><option>Camion</option><option>Moto</option><option>Muletto</option><option>Altro</option></select>
      <select id="m-poss"><option value="proprieta">Proprietà</option><option value="noleggio">Noleggio</option></select>
      <input type="date" id="m-ini-for"><input type="date" id="m-scad-for">
      <input type="number" id="m-canone"><input type="text" id="m-cliente">
      <input type="text" id="m-piva"><input type="tel" id="m-tel">
      <input type="email" id="m-email"><input type="text" id="m-indirizzo">
      <input type="text" id="m-ncontr"><input type="date" id="m-ini-cli">
      <input type="date" id="m-scad-cli">
      <div id="wrap-nol"></div><div id="wrap-fornitore"></div>
    </div>
  </div>

  <!-- Lista alert scadenze -->
  <div class="scad-readonly-notice">
    ℹ️ Le scadenze sono gestite direttamente dalla <strong>scheda del veicolo</strong> nella sezione Mezzi. Questa sezione mostra solo gli alert automatici.
    <button onclick="switchMain('garage')" style="margin-left:auto;font-size:11px;padding:2px 8px;border:.5px solid #3B6D11;border-radius:4px;background:none;color:#3B6D11;cursor:pointer">→ Vai ai Mezzi</button>
  </div>
  <div class="alert-center" id="list"></div>

</div>

<!-- PAGE MOVIMENTI -->
<div id="page-noleggi" class="page">
  <div class="stats">
    <div class="stat"><div class="stat-label">Schede totali</div><div class="stat-value green" id="mov-cnt-tot">0</div></div>
    <div class="stat"><div class="stat-label">Aperte (solo uscita)</div><div class="stat-value amber" id="mov-cnt-open">0</div></div>
    <div class="stat"><div class="stat-label">Completate</div><div class="stat-value" id="mov-cnt-done">0</div></div>
  </div>
  <div class="filter-bar" style="margin-bottom:.75rem">
    <button class="btn-primary" onclick="openWizard()">+ Nuovo noleggio</button>
    <input type="text" id="mov-search" placeholder="Cerca targa, conducente..." oninput="renderMov()" style="max-width:220px">
    <select id="mov-filter-targa" onchange="renderMov()" style="max-width:180px">
      <option value="all">Tutti i mezzi</option>
    </select>
    <select id="mov-filter-stato" onchange="renderMov()" style="max-width:160px">
      <option value="all">Tutti gli stati</option>
      <option value="aperto">Solo aperte</option>
      <option value="chiuso">Solo completate</option>
    </select>
  </div>
  <div id="mov-list"></div>
  <!-- Wizard nuovo noleggio -->
  <div id="nol-wizard" style="display:none">
    <div class="add-panel">
      <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:1rem">
        <div style="font-size:14px;font-weight:600">🔑 Nuovo noleggio</div>
        <button onclick="closeWizard()" style="font-size:12px;padding:0 10px;height:28px">✕ Chiudi</button>
      </div>
      <!-- Progress steps -->
      <div class="wizard-steps" id="wiz-steps">
        <div class="wizard-step active" id="ws-0"><div class="ws-dot">1</div><div class="ws-label">Azienda</div><div class="ws-line"></div></div>
        <div class="wizard-step" id="ws-1"><div class="ws-dot">2</div><div class="ws-label">Autista</div><div class="ws-line"></div></div>
        <div class="wizard-step" id="ws-2"><div class="ws-dot">3</div><div class="ws-label">Veicolo</div><div class="ws-line"></div></div>
        <div class="wizard-step" id="ws-3"><div class="ws-dot">4</div><div class="ws-label">Uscita</div><div class="ws-line"></div></div>
      </div>

      <!-- STEP 1: Azienda -->
      <div class="wizard-panel active" id="wp-0">
        <div class="section-sep">Seleziona azienda cliente</div>
        <div class="search-select-wrap">
          <input type="text" class="search-select-input" id="wiz-az-search" placeholder="Cerca per nome azienda, P.IVA..." oninput="searchAzienda(this.value)" autocomplete="off">
          <div class="search-dropdown" id="wiz-az-dropdown"></div>
        </div>
        <div id="wiz-az-selected" style="display:none"></div>
        <div id="wiz-az-new-form" style="display:none">
          <div class="new-autista-form" style="border-color:#378ADD;background:#E6F1FB20">
            <div class="new-autista-title" style="color:#185FA5">🏢 Nuova azienda</div>
            <div class="row r4">
              <div class="fg"><label>Ragione sociale *</label><input type="text" id="naz-nome" placeholder="Rossi Srl"></div>
              <div class="fg"><label>P.IVA</label><input type="text" id="naz-piva" placeholder="01234567890"></div>
              <div class="fg"><label>Telefono</label><input type="tel" id="naz-tel" placeholder="02 1234567"></div>
              <div class="fg"><label>Email</label><input type="email" id="naz-email" placeholder="info@azienda.it"></div>
            </div>
            <div class="fg" style="margin-bottom:8px"><label>Indirizzo</label><input type="text" id="naz-indirizzo" placeholder="Via Roma 1, Milano"></div>
            <div style="display:flex;gap:6px">
              <button class="btn-primary" style="font-size:12px;height:30px;padding:0 12px" onclick="saveNuovaAzienda()">Salva azienda</button>
              <button style="font-size:12px;height:30px;padding:0 10px" onclick="document.getElementById('wiz-az-new-form').style.display='none'">Annulla</button>
            </div>
          </div>
        </div>
        <div class="wizard-nav">
          <div></div>
          <button class="btn-primary" onclick="wizStep(1)" id="wiz-next-0" disabled>Avanti →</button>
        </div>
      </div>

      <!-- STEP 2: Autista -->
      <div class="wizard-panel" id="wp-1">
        <div class="section-sep">Seleziona autista</div>
        <div id="wiz-aut-azienda-info" style="margin-bottom:.75rem"></div>
        <div class="autisti-grid" id="wiz-autisti-grid"></div>
        <div id="wiz-aut-selected" style="display:none"></div>
        <button onclick="toggleNewAutistaForm()" style="font-size:12px;padding:0 12px;height:30px;margin-bottom:.75rem">+ Nuovo autista</button>
        <div id="wiz-aut-new-form" style="display:none">
          <div class="new-autista-form">
            <div class="new-autista-title">👤 Nuovo autista</div>
            <div class="row r4">
              <div class="fg"><label>Nome *</label><input type="text" id="nau-nome" placeholder="Mario"></div>
              <div class="fg"><label>Cognome *</label><input type="text" id="nau-cognome" placeholder="Rossi"></div>
              <div class="fg"><label>Telefono</label><input type="tel" id="nau-tel" placeholder="333 1234567"></div>
              <div class="fg"><label>N° patente</label><input type="text" id="nau-patente" placeholder="MI0123456A"></div>
            </div>
            <div class="row r4">
              <div class="fg"><label>Scad. patente</label><input type="date" id="nau-scad-patente"></div>
              <div class="fg"><label>Tipo documento</label>
                <select id="nau-tipo-doc"><option value="">— nessuno —</option><option>Carta d'identità</option><option>Passaporto</option></select>
              </div>
              <div class="fg"><label>N° documento</label><input type="text" id="nau-ndoc" placeholder="CA00000AA"></div>
              <div class="fg"><label>Scad. documento</label><input type="date" id="nau-scad-doc"></div>
            </div>
            <div class="fg" style="margin-bottom:8px"><label>Note</label><input type="text" id="nau-note" placeholder="Opzionale"></div>
            <div style="display:flex;gap:6px">
              <button class="btn-primary" style="font-size:12px;height:30px;padding:0 12px" onclick="saveNuovoAutista()">Salva autista</button>
              <button style="font-size:12px;height:30px;padding:0 10px" onclick="document.getElementById('wiz-aut-new-form').style.display='none'">Annulla</button>
            </div>
          </div>
        </div>
        <div class="wizard-nav">
          <button onclick="wizStep(0)">← Indietro</button>
          <button class="btn-primary" onclick="wizStep(2)" id="wiz-next-1" disabled>Avanti →</button>
        </div>
      </div>

      <!-- STEP 3: Veicolo -->
      <div class="wizard-panel" id="wp-2">
        <div class="section-sep">Seleziona veicolo disponibile</div>
        <div class="row r3" style="margin-bottom:.75rem">
          <div class="fg"><label>Data uscita *</label><input type="date" id="wiz-data-out" oninput="renderVehPicker()"></div>
          <div class="fg"><label>Ora uscita</label><input type="time" id="wiz-ora-out"></div>
          <div class="fg"></div>
        </div>
        <div class="veh-pick-grid" id="wiz-veh-grid"></div>
        <div id="wiz-veh-selected" style="display:none"></div>
        <div class="wizard-nav">
          <button onclick="wizStep(1)">← Indietro</button>
          <button class="btn-primary" onclick="wizStep(3)" id="wiz-next-2" disabled>Avanti →</button>
        </div>
      </div>

      <!-- STEP 4: Uscita -->
      <div class="wizard-panel" id="wp-3">
        <div class="section-sep">Stato mezzo all'uscita</div>
        <!-- Hidden compat fields (used by addMovimento) -->
        <input type="hidden" id="s-targa">
        <input type="hidden" id="s-conducente">
        <input type="hidden" id="s-data-out">
        <input type="hidden" id="s-ora-out">
        <div class="row r4">
          <div class="fg"><label>KM uscita</label><input type="number" id="s-km-out" placeholder="es. 45230"></div>
          <div class="fg"><label>Carburante (%)</label><input type="number" id="s-gasolio-out" placeholder="es. 75" min="0" max="100"></div>
          <div class="fg"><label>Danni presenti</label><input type="text" id="s-danni-out" placeholder="es. Graffio sx, nessuno…"></div>
          <div class="fg"><label>Note uscita</label><input type="text" id="s-note-out" placeholder="Opzionale"></div>
        </div>
        <div class="section-sep">Checklist consegna</div>
        <div class="checklist-wrap" id="cl-out-wrap">
          <div class="checklist-title"><span>✅</span> Verifica uscita mezzo</div>
          <div class="checklist-grid" id="cl-out-grid"></div>
          <div class="checklist-progress">
            <div class="checklist-bar-wrap"><div class="checklist-bar" id="cl-out-bar" style="width:0%"></div></div>
            <span class="checklist-pct" id="cl-out-pct">0/10</span>
          </div>
        </div>
        <!-- Riepilogo wizard -->
        <div id="wiz-riepilogo" style="background:#f5f4f0;border-radius:10px;padding:12px 14px;margin-top:10px;font-size:12px"></div>
        <div class="wizard-nav">
          <button onclick="wizStep(2)">← Indietro</button>
          <button class="btn-primary" onclick="addMovimento()">✅ Registra uscita</button>
        </div>
      </div>

    </div>
  </div>

  <!-- Lista noleggi esistente -->
</div>

<!-- PAGE CLIENTI -->
<div id="page-clienti" class="page">

  <!-- Stats row -->
  <div class="stats" style="grid-template-columns:repeat(4,1fr)">
    <div class="stat"><div class="stat-label">Clienti totali</div><div class="stat-value" id="cli-cnt-tot">0</div></div>
    <div class="stat"><div class="stat-label">Attivi</div><div class="stat-value green" id="cli-cnt-att">0</div></div>
    <div class="stat"><div class="stat-label">Blacklist</div><div class="stat-value red" id="cli-cnt-bl">0</div></div>
    <div class="stat"><div class="stat-label">Doc. scaduti</div><div class="stat-value amber" id="cli-cnt-doc">0</div></div>
  </div>

  <!-- Search bar -->
  <div class="cli-topbar">
    <input type="text" id="cli-search" placeholder="Cerca nome, azienda, telefono..." oninput="renderClienti()" style="max-width:240px">
    <select id="cli-filter" onchange="renderClienti()" style="max-width:180px">
      <option value="all">Tutti</option>
      <option value="attivo">Solo attivi</option>
      <option value="blacklist">Blacklist</option>
    </select>
    <button class="btn-primary" onclick="showFormCliente()">+ Nuovo cliente</button>
    <span class="cli-count" id="cli-count-lbl"></span>
  </div>

  <!-- Detail view (hidden by default) -->
  <div id="cli-detail" style="display:none"></div>

  <!-- Cards grid -->
  <div class="cli-grid" id="cli-list"></div>

  <!-- Form nuovo/modifica cliente -->
  <div id="cli-form" style="display:none">
    <div class="form-cliente">
      <div class="form-cliente-title">
        <span id="cli-form-icon">👤</span>
        <span id="cli-form-title">Nuovo cliente</span>
        <button onclick="hideFormCliente()" style="margin-left:auto;height:auto;padding:2px 8px;font-size:12px">✕ Chiudi</button>
      </div>
      <div class="section-sep">Dati anagrafici</div>
      <div class="row r4" style="margin-top:8px">
        <div class="fg"><label>Nome *</label><input type="text" id="cf-nome" placeholder="Mario Rossi"></div>
        <div class="fg"><label>Azienda / Ragione sociale</label><input type="text" id="cf-azienda" placeholder="Rossi Srl"></div>
        <div class="fg"><label>Telefono</label><input type="tel" id="cf-tel" placeholder="02 1234567"></div>
        <div class="fg"><label>Email</label><input type="email" id="cf-email" placeholder="mario@rossi.it"></div>
      </div>
      <div class="row r4">
        <div class="fg"><label>P.IVA / C.F.</label><input type="text" id="cf-piva" placeholder="01234567890"></div>
        <div class="fg"><label>Indirizzo</label><input type="text" id="cf-indirizzo" placeholder="Via Roma 1, Milano"></div>
        <div class="fg"><label>N° patente</label><input type="text" id="cf-patente" placeholder="MI0123456A"></div>
        <div class="fg"><label>Scad. patente</label><input type="date" id="cf-scad-patente"></div>
      </div>
      <div class="section-sep">Documento identità</div>
      <div class="row r4">
        <div class="fg"><label>Tipo documento</label>
          <select id="cf-tipo-doc"><option value="">— nessuno —</option><option>Carta d'identità</option><option>Passaporto</option><option>Patente</option></select>
        </div>
        <div class="fg"><label>N° documento</label><input type="text" id="cf-ndoc" placeholder="CA00000AA"></div>
        <div class="fg"><label>Scadenza documento</label><input type="date" id="cf-scad-doc"></div>
        <div class="fg"></div>
      </div>
      <div class="section-sep">Note operative</div>
      <div class="row r2">
        <div class="fg"><label>Note interne</label><textarea id="cf-note" placeholder="Note visibili solo allo staff..."></textarea></div>
        <div class="fg" style="justify-content:flex-end">
          <label class="blacklist-toggle">
            <input type="checkbox" id="cf-blacklist">
            <span style="color:#A32D2D;font-weight:600">🚫 Inserisci in blacklist</span>
          </label>
          <div id="cf-blacklist-wrap" style="display:none">
            <div class="fg" style="margin-top:6px"><label>Motivo blacklist</label><textarea id="cf-motivo-bl" placeholder="Motivo del blocco..."></textarea></div>
          </div>
        </div>
      </div>
      <input type="hidden" id="cf-editing-id">
      <div style="display:flex;gap:8px;margin-top:12px">
        <button class="btn-primary" onclick="saveCliente()">💾 Salva cliente</button>
        <button class="btn-danger" id="cf-delete-btn" onclick="deleteCliente()" style="display:none">Elimina</button>
        <button onclick="hideFormCliente()">Annulla</button>
      </div>
    </div>
  </div>

</div>


<!-- PAGE GARAGE -->
<div id="page-garage" class="page">

  <!-- Vista FLOTTA (default) -->
  <div id="gar-fleet-view">
    <!-- KPI -->
    <div class="stats" style="grid-template-columns:repeat(4,1fr);margin-bottom:1.25rem">
      <div class="stat"><div class="stat-label">Interventi totali</div><div class="stat-value" id="gar-cnt-tot">0</div></div>
      <div class="stat"><div class="stat-label">Aperti / In corso</div><div class="stat-value amber" id="gar-cnt-open">0</div></div>
      <div class="stat"><div class="stat-label">Attesa ricambi</div><div class="stat-value" style="color:#6C3483" id="gar-cnt-att">0</div></div>
      <div class="stat"><div class="stat-label">Completati</div><div class="stat-value green" id="gar-cnt-done">0</div></div>
    </div>

    <!-- Alert automazioni -->
    <div class="dash-panel-title" style="margin-bottom:.5rem"><span>🔔</span> Alert automazioni</div>
    <div class="auto-alerts" id="gar-alerts"></div>

    <!-- Topbar flotta -->
    <div class="cli-topbar" style="margin-top:1rem">
      <input type="text" id="gar-search" placeholder="Cerca targa, marca, modello..." oninput="renderGarage()" style="max-width:220px">
      <select id="gar-filter-stato-v" onchange="renderGarage()" style="max-width:170px">
        <option value="all">Tutti gli stati</option>
        <option value="disponibile">Disponibili</option>
        <option value="officina">In officina</option>
        <option value="noleggiato">Noleggiati</option>
      </select>
      <div class="view-toggle" style="margin-left:auto">
        <button class="vtb active" id="vtb-card" onclick="setGarView('card')">⊞ Card</button>
        <button class="vtb" id="vtb-table" onclick="setGarView('table')">☰ Tabella</button>
      </div>
      <button class="btn-primary" onclick="showFormGarage()">+ Nuovo intervento</button>
      <button class="btn-primary" onclick="toggleNewVehicleForm()" style="background:#1a1a18;border-color:#1a1a18">🚛 + Nuovo veicolo</button>
    </div>

    <!-- Form nuovo veicolo -->
    <div id="new-veh-form" style="display:none">
      <div class="new-veh-panel">
        <div class="new-veh-title">
          <span style="font-size:22px">🚛</span> Aggiungi nuovo veicolo
          <button onclick="toggleNewVehicleForm()" style="margin-left:auto;height:auto;padding:2px 10px;font-size:12px">✕ Chiudi</button>
        </div>

        <!-- Possesso -->
        <div style="margin-bottom:.75rem">
          <label style="font-size:12px;font-weight:600;color:#888;display:block;margin-bottom:6px">TIPO POSSESSO</label>
          <div class="poss-toggle">
            <button class="pt-btn active" id="pt-prop" onclick="setNVPoss('proprieta')">🏠 Proprietà</button>
            <button class="pt-btn" id="pt-nol" onclick="setNVPoss('noleggio')">📋 Noleggio</button>
          </div>
          <input type="hidden" id="nv-poss" value="proprieta">
        </div>

        <!-- Dati principali -->
        <div class="new-veh-grid">
          <div class="fg"><label>Targa *</label><input type="text" id="nv-targa" placeholder="AB123CD" style="text-transform:uppercase;font-family:monospace;font-weight:700"></div>
          <div class="fg"><label>Marca</label><input type="text" id="nv-marca" placeholder="es. Ford"></div>
          <div class="fg"><label>Modello</label><input type="text" id="nv-modello" placeholder="es. Transit"></div>
          <div class="fg"><label>Tipo categoria *</label>
            <select id="nv-tipo">
              <option>Auto</option><option>Furgone</option><option>Camion</option>
              <option>Moto</option><option>Muletto</option><option>Altro</option>
            </select>
          </div>
        </div>
        <div class="new-veh-grid">
          <div class="fg"><label>Anno</label><input type="number" id="nv-anno" placeholder="es. 2022" min="1990" max="2030"></div>
          <div class="fg"><label>VIN / Telaio</label><input type="text" id="nv-vin" placeholder="WF0XXXTTG..."></div>
          <div class="fg"><label>Alimentazione</label>
            <select id="nv-alimentazione">
              <option>Diesel</option><option>Benzina</option><option>Ibrido</option>
              <option>Elettrico</option><option>GPL</option><option>Metano</option>
            </select>
          </div>
          <div class="fg"><label>Cambio</label>
            <select id="nv-cambio"><option>Manuale</option><option>Automatico</option><option>Semi-automatico</option></select>
          </div>
        </div>
        <div class="new-veh-grid">
          <div class="fg"><label>KM attuali</label><input type="number" id="nv-km" placeholder="es. 0"></div>
          <div class="fg"><label>Portata (kg)</label><input type="number" id="nv-portata" placeholder="es. 1000"></div>
          <div class="fg"><label>Volume (m³)</label><input type="number" id="nv-volume" step="0.1" placeholder="es. 8.5"></div>
          <div class="fg"><label>Sede operativa</label><input type="text" id="nv-sede" placeholder="es. Pero (MI)"></div>
        </div>

        <!-- Sezione noleggio (nascosta di default) -->
        <div id="nv-nol-section" style="display:none">
          <div class="new-veh-grid">
            <div class="new-veh-sep">Dati contratto noleggio</div>
            <div class="fg"><label>Fornitore noleggio</label><input type="text" id="nv-fornitore" placeholder="es. Arval, LeasePlan"></div>
            <div class="fg"><label>Data inizio contratto</label><input type="date" id="nv-ini-for"></div>
            <div class="fg"><label>Scadenza contratto</label><input type="date" id="nv-scad-for"></div>
            <div class="fg"><label>Canone mensile (€)</label><input type="number" id="nv-canone" placeholder="es. 480"></div>
          </div>
          <div class="new-veh-grid">
            <div class="fg"><label>Cliente / Azienda</label><input type="text" id="nv-cliente" placeholder="Nome azienda"></div>
            <div class="fg"><label>P.IVA cliente</label><input type="text" id="nv-piva" placeholder="01234567890"></div>
            <div class="fg"><label>N° contratto</label><input type="text" id="nv-ncontr" placeholder="CT-2024-001"></div>
            <div class="fg"><label>Scad. contratto cliente</label><input type="date" id="nv-scad-cli"></div>
          </div>
        </div>

        <!-- Note -->
        <div class="new-veh-grid r2" style="margin-top:4px">
          <div class="fg"><label>Note</label><input type="text" id="nv-note" placeholder="Opzionale"></div>
          <div class="fg"></div>
        </div>

        <div style="display:flex;gap:8px;margin-top:1rem;padding-top:.75rem;border-top:.5px solid rgba(0,0,0,.08)">
          <button class="btn-primary" onclick="saveNewVehicle()">💾 Salva veicolo</button>
          <button onclick="toggleNewVehicleForm()">Annulla</button>
        </div>
      </div>
    </div>

    <!-- Grid card veicoli -->
    <div class="garage-fleet-grid" id="gar-fleet-cards"></div>

    <!-- Tabella veicoli (hidden by default) -->
    <div id="gar-fleet-table" style="display:none;overflow-x:auto;margin-bottom:1.5rem">
      <table class="veh-table" id="veh-table-el">
        <thead>
          <tr>
            <th>Targa</th><th>Marca / Modello</th><th>Tipo</th>
            <th>Stato</th><th>KM</th><th>Sede</th>
            <th>Revisione</th><th>Assicurazione</th><th>Interv.</th>
          </tr>
        </thead>
        <tbody id="gar-fleet-tbody"></tbody>
      </table>
    </div>

    <!-- Form intervento (rimane qui) -->
    <div id="gar-form" style="display:none">
      <div class="garage-form">
        <div class="garage-form-title">
          <span>🔧</span> <span id="gar-form-title">Nuovo intervento</span>
          <button onclick="hideFormGarage()" style="margin-left:auto;height:auto;padding:2px 8px;font-size:12px">✕</button>
        </div>
        <div class="row r4" style="margin-bottom:10px">
          <div class="fg"><label>Targa *</label>
            <select id="gf-targa"><option value="">— seleziona —</option></select>
          </div>
          <div class="fg"><label>Tipo intervento *</label>
            <select id="gf-tipo">
              <option>Tagliando</option><option>Revisione</option><option>Riparazione</option>
              <option>Pneumatici</option><option>Freni</option><option>Carrozzeria</option>
              <option>Elettrico</option><option>Altro</option>
            </select>
          </div>
          <div class="fg"><label>Priorità</label>
            <select id="gf-priorita">
              <option value="bassa">🟢 Bassa</option>
              <option value="media" selected>🟡 Media</option>
              <option value="alta">🔴 Alta</option>
            </select>
          </div>
          <div class="fg"><label>Officina / Meccanico</label>
            <input type="text" id="gf-officina" placeholder="es. Autofficina Rossi">
          </div>
        </div>
        <div class="row r4" style="margin-bottom:10px">
          <div class="fg"><label>Data apertura</label><input type="date" id="gf-data-in"></div>
          <div class="fg"><label>Data prevista chiusura</label><input type="date" id="gf-data-prev"></div>
          <div class="fg"><label>Data chiusura effettiva</label><input type="date" id="gf-data-out"></div>
          <div class="fg"><label>KM al momento</label><input type="number" id="gf-km" placeholder="es. 45230"></div>
        </div>
        <div class="row r2" style="margin-bottom:10px">
          <div class="fg"><label>Descrizione intervento *</label>
            <textarea id="gf-desc" placeholder="Descrivi il problema e il lavoro da eseguire..."></textarea>
          </div>
          <div class="fg"><label>Note interne</label>
            <textarea id="gf-note" placeholder="Ricambi ordinati, costi previsti..."></textarea>
          </div>
        </div>
        <div class="fg" style="margin-bottom:12px">
          <label>Stato intervento</label>
          <div class="stato-selector" id="gf-stato-selector">
            <button class="stato-btn selected" data-stato="aperto" onclick="selectStatoGar('aperto')">🟡 Aperto</button>
            <button class="stato-btn" data-stato="in_corso" onclick="selectStatoGar('in_corso')">🔵 In corso</button>
            <button class="stato-btn" data-stato="attesa" onclick="selectStatoGar('attesa')">🟣 Attesa ricambi</button>
            <button class="stato-btn" data-stato="completato" onclick="selectStatoGar('completato')">🟢 Completato</button>
          </div>
          <input type="hidden" id="gf-stato" value="aperto">
        </div>
        <input type="hidden" id="gf-editing-id">
        <div style="display:flex;gap:8px">
          <button class="btn-primary" onclick="saveIntervento()">💾 Salva intervento</button>
          <button class="btn-danger" id="gf-delete-btn" onclick="deleteIntervento()" style="display:none">Elimina</button>
          <button onclick="hideFormGarage()">Annulla</button>
        </div>
      </div>
    </div>

    <!-- Detail intervento -->
    <div id="gar-detail" style="display:none"></div>

    <!-- Kanban board (accessibile da scheda) -->
    <div id="gar-kanban-wrap" style="display:none">
      <div class="cli-topbar" style="margin-bottom:.75rem">
        <div style="font-size:14px;font-weight:600">📋 Tutti gli interventi — Kanban</div>
        <select id="gar-filter-targa" onchange="renderKanban()" style="max-width:160px">
          <option value="all">Tutti i mezzi</option>
        </select>
        <select id="gar-filter-stato" onchange="renderKanban()" style="max-width:160px">
          <option value="all">Tutti gli stati</option>
          <option value="aperto">Aperto</option>
          <option value="in_corso">In corso</option>
          <option value="attesa">Attesa ricambi</option>
          <option value="completato">Completato</option>
        </select>
        <button onclick="document.getElementById('gar-kanban-wrap').style.display='none'" style="font-size:12px;padding:0 10px">✕ Chiudi</button>
      </div>
      <div class="garage-kanban">
        <div class="kanban-col"><div class="kanban-col-header"><span class="kanban-dot kd-aperto"></span>Aperto<span class="kanban-count" id="kc-aperto">0</span></div><div class="kanban-cards" id="kc-cards-aperto"></div></div>
        <div class="kanban-col"><div class="kanban-col-header"><span class="kanban-dot kd-in_corso"></span>In corso<span class="kanban-count" id="kc-in_corso">0</span></div><div class="kanban-cards" id="kc-cards-in_corso"></div></div>
        <div class="kanban-col"><div class="kanban-col-header"><span class="kanban-dot kd-attesa"></span>Attesa ricambi<span class="kanban-count" id="kc-attesa">0</span></div><div class="kanban-cards" id="kc-cards-attesa"></div></div>
        <div class="kanban-col"><div class="kanban-col-header"><span class="kanban-dot kd-completato"></span>Completato<span class="kanban-count" id="kc-completato">0</span></div><div class="kanban-cards" id="kc-cards-completato"></div></div>
      </div>
    </div>
  </div>

  <!-- Vista SCHEDA VEICOLO (hidden by default) -->
  <div id="gar-scheda-view" style="display:none"></div>

</div>

<!-- PAGE OFFICINA -->
<div id="page-officina" class="page">

  <div class="stats" style="grid-template-columns:repeat(4,1fr)">
    <div class="stat"><div class="stat-label">Interventi totali</div><div class="stat-value" id="off-cnt-tot">0</div></div>
    <div class="stat"><div class="stat-label">Aperti / In corso</div><div class="stat-value amber" id="off-cnt-open">0</div></div>
    <div class="stat"><div class="stat-label">Attesa ricambi</div><div class="stat-value" style="color:#6C3483" id="off-cnt-att">0</div></div>
    <div class="stat"><div class="stat-label">Completati</div><div class="stat-value green" id="off-cnt-done">0</div></div>
  </div>

  <div class="off-topbar">
    <input type="text" id="off-search" placeholder="Cerca targa, tipo, descrizione..." oninput="renderOfficina()" style="max-width:240px">
    <select id="off-filter-targa" onchange="renderOfficina()" style="max-width:160px">
      <option value="all">Tutti i mezzi</option>
    </select>
    <select id="off-filter-stato" onchange="renderOfficina()" style="max-width:160px">
      <option value="all">Tutti gli stati</option>
      <option value="aperto">Aperto</option>
      <option value="in_corso">In corso</option>
      <option value="attesa">Attesa ricambi</option>
      <option value="completato">Completato</option>
    </select>
    <button class="btn-primary" onclick="showFormGarage()">+ Nuovo intervento</button>
    <button onclick="document.getElementById('gar-kanban-wrap').style.display='';switchMain('garage')" style="font-size:12px;padding:0 12px">📋 Vista Kanban</button>
  </div>

  <div id="off-form-wrap"></div>
  <div id="off-detail" style="display:none"></div>

  <div class="off-kanban" id="off-kanban">
    <div class="kanban-col"><div class="kanban-col-header"><span class="kanban-dot kd-aperto"></span>Aperto<span class="kanban-count" id="off-kc-aperto">0</span></div><div class="kanban-cards" id="off-kc-cards-aperto"></div></div>
    <div class="kanban-col"><div class="kanban-col-header"><span class="kanban-dot kd-in_corso"></span>In corso<span class="kanban-count" id="off-kc-in_corso">0</span></div><div class="kanban-cards" id="off-kc-cards-in_corso"></div></div>
    <div class="kanban-col"><div class="kanban-col-header"><span class="kanban-dot kd-attesa"></span>Attesa ricambi<span class="kanban-count" id="off-kc-attesa">0</span></div><div class="kanban-cards" id="off-kc-cards-attesa"></div></div>
    <div class="kanban-col"><div class="kanban-col-header"><span class="kanban-dot kd-completato"></span>Completato<span class="kanban-count" id="off-kc-completato">0</span></div><div class="kanban-cards" id="off-kc-cards-completato"></div></div>
  </div>

</div>

<!-- PAGE SINISTRI -->
<div id="page-sinistri" class="page">

  <!-- KPI -->
  <div class="stats" style="grid-template-columns:repeat(4,1fr)">
    <div class="stat"><div class="stat-label">Sinistri totali</div><div class="stat-value" id="sin-cnt-tot">0</div></div>
    <div class="stat"><div class="stat-label">Aperti</div><div class="stat-value amber" id="sin-cnt-open">0</div></div>
    <div class="stat"><div class="stat-label">In gestione</div><div class="stat-value blue" style="color:#185FA5" id="sin-cnt-gest">0</div></div>
    <div class="stat"><div class="stat-label">Chiusi</div><div class="stat-value green" id="sin-cnt-closed">0</div></div>
  </div>

  <!-- Topbar -->
  <div class="cli-topbar">
    <input type="text" id="sin-search" placeholder="Cerca targa, conducente, descrizione..." oninput="renderSinistri()" style="max-width:260px">
    <select id="sin-filter-stato" onchange="renderSinistri()" style="max-width:180px">
      <option value="all">Tutti gli stati</option>
      <option value="aperto">Aperti</option>
      <option value="in_gestione">In gestione</option>
      <option value="chiuso">Chiusi</option>
      <option value="contestato">Contestati</option>
    </select>
    <select id="sin-filter-targa" onchange="renderSinistri()" style="max-width:160px">
      <option value="all">Tutti i mezzi</option>
    </select>
    <button class="btn-primary" onclick="showFormSinistro()">+ Nuovo sinistro</button>
    <button onclick="exportCSV('sinistri')" style="font-size:12px;padding:0 12px" data-tooltip="Esporta CSV">📥 Export CSV</button>
  </div>

  <!-- Form -->
  <div id="sin-form" style="display:none">
    <div class="sin-form">
      <div class="sin-form-title">
        <span>⚠️</span> <span id="sin-form-title">Nuovo sinistro</span>
        <button onclick="hideFormSinistro()" style="margin-left:auto;height:auto;padding:2px 8px;font-size:12px">✕</button>
      </div>

      <div class="section-sep">Dati sinistro</div>
      <div class="row r4" style="margin-top:8px">
        <div class="fg"><label>Targa *</label>
          <select id="sf-targa"><option value="">— seleziona —</option></select>
        </div>
        <div class="fg"><label>Data sinistro *</label><input type="date" id="sf-data"></div>
        <div class="fg"><label>Conducente / Responsabile</label>
          <input type="text" id="sf-conducente" placeholder="Nome conducente">
        </div>
        <div class="fg"><label>Luogo</label>
          <input type="text" id="sf-luogo" placeholder="es. Via Roma 1, Milano">
        </div>
      </div>
      <div class="row r2">
        <div class="fg"><label>Descrizione evento *</label>
          <textarea id="sf-desc" placeholder="Descrivi cosa è successo, dinamica dell'incidente..."></textarea>
        </div>
        <div class="fg"><label>Danni riscontrati</label>
          <textarea id="sf-danni" placeholder="es. Ammaccatura paraurti anteriore, faro rotto sx..."></textarea>
        </div>
      </div>

      <div class="section-sep">Controparte (se presente)</div>
      <div class="row r4">
        <div class="fg"><label>Nome controparte</label><input type="text" id="sf-cp-nome" placeholder="Mario Verdi"></div>
        <div class="fg"><label>Targa controparte</label><input type="text" id="sf-cp-targa" placeholder="XY999ZZ" style="text-transform:uppercase"></div>
        <div class="fg"><label>Compagnia assicurativa</label><input type="text" id="sf-assicurazione" placeholder="es. Generali"></div>
        <div class="fg"><label>N° polizza / sinistro</label><input type="text" id="sf-npolizza" placeholder="es. POL-2024-001"></div>
      </div>

      <div class="section-sep">Gestione pratica</div>
      <div class="row r4">
        <div class="fg"><label>Data apertura pratica</label><input type="date" id="sf-data-pratica"></div>
        <div class="fg"><label>Data chiusura pratica</label><input type="date" id="sf-data-chiusura"></div>
        <div class="fg"><label>Importo danno stimato (€)</label><input type="number" id="sf-importo" placeholder="es. 1500"></div>
        <div class="fg"><label>Note interne</label><input type="text" id="sf-note" placeholder="Opzionale"></div>
      </div>

      <div class="fg" style="margin:10px 0">
        <label>Stato pratica</label>
        <div class="sin-stato-selector" id="sf-stato-selector" style="margin-top:6px">
          <button class="sin-stato-btn selected" data-stato="aperto" onclick="selectStatoSin('aperto')">🟡 Aperto</button>
          <button class="sin-stato-btn" data-stato="in_gestione" onclick="selectStatoSin('in_gestione')">🔵 In gestione</button>
          <button class="sin-stato-btn" data-stato="chiuso" onclick="selectStatoSin('chiuso')">🟢 Chiuso</button>
          <button class="sin-stato-btn" data-stato="contestato" onclick="selectStatoSin('contestato')">🔴 Contestato</button>
        </div>
        <input type="hidden" id="sf-stato" value="aperto">
      </div>

      <input type="hidden" id="sf-editing-id">
      <div style="display:flex;gap:8px;margin-top:12px">
        <button class="btn-primary" onclick="saveSinistro()">💾 Salva sinistro</button>
        <button class="btn-danger" id="sf-delete-btn" onclick="deleteSinistro()" style="display:none">Elimina</button>
        <button onclick="hideFormSinistro()">Annulla</button>
      </div>
    </div>
  </div>

  <!-- Detail -->
  <div id="sin-detail" style="display:none"></div>

  <!-- Lista sinistri -->
  <div class="sinistri-list" id="sin-list"></div>

</div>
</div><!-- /wrap -->
  </div><!-- /content -->
</div><!-- /main-area -->

<div class="toast" id="toast"></div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
<script>
const today = new Date(); today.setHours(0,0,0,0);
let vehicles={}, items=[], movimenti=[], clienti=[], interventi=[], sinistri=[], autisti=[], nextId=1, nextMovId=1, nextCliId=1, nextIntId=1, nextSinId=1, nextAutId=1, loaded=false;

const STORAGE_KEY_V = 'vr_vehicles';
const STORAGE_KEY_I = 'vr_items';
const STORAGE_KEY_N = 'vr_nextid';
const STORAGE_KEY_M = 'vr_movimenti';
const STORAGE_KEY_MN = 'vr_nextmovid';
const STORAGE_KEY_C  = 'vr_clienti';
const STORAGE_KEY_CN = 'vr_nextcliid';
const STORAGE_KEY_INT= 'vr_interventi';
const STORAGE_KEY_IN = 'vr_nextintid';
const STORAGE_KEY_SIN= 'vr_sinistri';
const STORAGE_KEY_SN = 'vr_nextsinid';
const STORAGE_KEY_AUT= 'vr_autisti';
const STORAGE_KEY_AN = 'vr_nextautid';

function lsGet(k){ try{ return localStorage.getItem(k); }catch(e){ return null; } }
function lsSet(k,v){ try{ localStorage.setItem(k,v); }catch(e){} }

function loadData(){
  try{
    const vr=lsGet(STORAGE_KEY_V);
    const ir=lsGet(STORAGE_KEY_I);
    const nr=lsGet(STORAGE_KEY_N);
    const mr=lsGet(STORAGE_KEY_M);
    const mn=lsGet(STORAGE_KEY_MN);
    if(vr) vehicles=JSON.parse(vr);
    if(ir) items=JSON.parse(ir);
    if(nr) nextId=parseInt(nr);
    if(mr) movimenti=JSON.parse(mr);
    if(mn) nextMovId=parseInt(mn);
    // Migrazione: aggiungi campi contratto ai movimenti esistenti
    movimenti.forEach(function(m){
      if(!m.contratto) m.contratto={
        societa:'', numContratto:'', dataInizio:m.dataOut||'', dataFine:'',
        durataMesi:'', canone:'', costoTotale:'', kmInclusi:'', kmExtra:'',
        deposito:'', pagamento:'', note:'', stato:'aperto'
      };
      if(!m.storico) m.storico=[];
    });
    const ar=lsGet(STORAGE_KEY_AUT); const an=lsGet(STORAGE_KEY_AN);
    if(ar) autisti=JSON.parse(ar);
    if(an) nextAutId=parseInt(an);
    if(!ar){
      autisti=[
        {id:1,nome:"Mario",cognome:"Rossi",aziendaId:1,tel:"333 1111111",patente:"MI0123456A",scadPatente:"2027-06-30",tipoDoc:"Carta d'identità",nDoc:"CA00000AA",scadDoc:"2028-12-31",note:"Autista principale Rossi Srl"},
        {id:2,nome:"Luigi",cognome:"Bianchi",aziendaId:1,tel:"333 2222222",patente:"BG4567890B",scadPatente:"2026-12-31",tipoDoc:"",nDoc:"",scadDoc:"",note:""},
        {id:3,nome:"Giuseppe",cognome:"Verdi",aziendaId:2,tel:"339 3333333",patente:"TO9876543C",scadPatente:"2028-03-20",tipoDoc:"Passaporto",nDoc:"YA1234567",scadDoc:"2029-01-15",note:"Autista Bianchi SpA"},
      ];
      nextAutId=10;
    }
    const sr=lsGet(STORAGE_KEY_SIN); const sn=lsGet(STORAGE_KEY_SN);
    if(sr) sinistri=JSON.parse(sr);
    if(sn) nextSinId=parseInt(sn);
    if(!sr){
      sinistri=[
        {id:1,targa:"AB123CD",data:"2026-03-10",conducente:"Mario Rossi",luogo:"SS 11 Km 5, Pero (MI)",desc:"Tamponamento lieve in coda al semaforo. Urto posteriore da parte di veicolo sconosciuto.",danni:"Paraurti posteriore ammaccato, fanale sx rotto",cpNome:"Luigi Verdi",cpTarga:"FH321ZZ",assicurazione:"Generali",nPolizza:"GEN-2026-0042",dataPratica:"2026-03-11",dataChiusura:"",importo:"850",note:"Preventivo in attesa",stato:"in_gestione",eventi:[{data:"2026-03-10",testo:"Sinistro aperto",tipo:"aperto"},{data:"2026-03-11",testo:"Pratica aperta con Generali",tipo:"update"}]},
      ];
      nextSinId=10;
    }
    const ir2=lsGet(STORAGE_KEY_INT); const in2=lsGet(STORAGE_KEY_IN);
    if(ir2) interventi=JSON.parse(ir2);
    if(in2) nextIntId=parseInt(in2);
    if(!ir2){
      interventi=[
        {id:1,targa:"FG482KL",tipo:"Tagliando",priorita:"media",officina:"Autofficina Bianchi",dataIn:"2026-04-10",dataPrev:"2026-04-15",dataOut:"2026-04-14",km:"48000",desc:"Tagliando 30.000 km - olio, filtri, candele",note:"Completato in anticipo",stato:"completato"},
        {id:2,targa:"MU001AZ",tipo:"Riparazione",priorita:"alta",officina:"",dataIn:"2026-05-01",dataPrev:"2026-05-10",dataOut:"",km:"12500",desc:"Problema idraulico braccio sollevamento",note:"In attesa pezzo di ricambio",stato:"attesa"},
      ];
      nextIntId=10;
    }
    const cr=lsGet(STORAGE_KEY_C); const cn=lsGet(STORAGE_KEY_CN);
    if(cr) clienti=JSON.parse(cr);
    if(cn) nextCliId=parseInt(cn);
    if(!cr){
      clienti=[
        {id:1,nome:"Contatto Rossi Srl",azienda:"Rossi Srl",tel:"02 9876543",email:"admin@rossisrl.it",piva:"01234567890",indirizzo:"Via Roma 1, Milano",patente:"",scadPatente:"",tipoDoc:"",nDoc:"",scadDoc:"",note:"Azienda cliente abituale",blacklist:false,motivoBl:""},
        {id:2,nome:"Contatto Bianchi SpA",azienda:"Bianchi SpA",tel:"333 1234567",email:"info@bianchi.it",piva:"09876543210",indirizzo:"Via Garibaldi 5, Pero",patente:"",scadPatente:"",tipoDoc:"",nDoc:"",scadDoc:"",note:"",blacklist:false,motivoBl:""},
      ];
      nextCliId=10;
    }
    if(!vr){
      vehicles={
        "FG482KL":{tipo:"Furgone",poss:"proprieta",marca:"Ford",modello:"Transit",vin:"WF0XXXTTGXKA12345",anno:"2021",alimentazione:"Diesel",cambio:"Manuale",portata:"1000",volume:"8",sede:"Pero (MI)",km:"48000",fornitore:"",cliente:"",piva:"",tel:"",email:"",indirizzo:"",ncontr:"",scadFor:"",scadCli:"",iniFor:"",iniCli:"",canone:"",docs:{assicurazione:{dataEmissione:"2024-01-15",dataScadenza:"2026-01-15",costo:"1200",compagnia:"AXA",polizza:"AXA-2024-001",note:""},revisione:{dataEmissione:"2024-06-01",dataScadenza:"2026-06-01",costo:"180",note:"Superata regolarmente"},bollo:{dataEmissione:"2024-03-01",dataScadenza:"2025-03-01",costo:"320",note:""},tagliando:{dataEmissione:"2024-04-10",dataScadenza:"",kmProssimo:"60000",costo:"380",note:"Prossimo a 60.000 km"}},costi:[{id:1,tipo:"Carburante",desc:"Rifornimento",data:"2026-04-15",importo:"85",note:""},{id:2,tipo:"Manutenzione",desc:"Tagliando",data:"2026-04-10",importo:"380",note:""}],allegati:[],kmHistory:[{data:"2026-04-10",km:"48000",note:"Tagliando"}]},
        "AB123CD":{tipo:"Auto",poss:"noleggio",marca:"Volkswagen",modello:"Passat",vin:"WVWZZZ3CZ8E012345",anno:"2022",alimentazione:"Benzina",cambio:"Automatico",portata:"",volume:"",sede:"Pero (MI)",km:"32000",fornitore:"Arval",cliente:"Rossi Srl",piva:"01234567890",tel:"02 9876543",email:"admin@rossisrl.it",indirizzo:"Via Roma 1, Milano",ncontr:"CT-2024-001",scadFor:"2026-12-31",scadCli:"2026-11-30",iniFor:"2024-01-01",iniCli:"2024-02-01",canone:"480"},
        "MU001AZ":{tipo:"Muletto",poss:"proprieta",marca:"Toyota",modello:"Tonero 25",vin:"",anno:"2019",alimentazione:"Elettrico",cambio:"Automatico",portata:"2500",volume:"",sede:"Pero (MI)",km:"12500",fornitore:"",cliente:"",piva:"",tel:"",email:"",indirizzo:"",ncontr:"",scadFor:"",scadCli:"",iniFor:"",iniCli:"",canone:""},
      };
      items=[
        {id:1,targa:"FG482KL",cat:"Assicurazione",date:"2025-04-15",note:""},
        {id:2,targa:"FG482KL",cat:"Revisione",date:"2026-05-03",note:""},
        {id:3,targa:"AB123CD",cat:"Assicurazione",date:"2026-04-28",note:"Generali"},
        {id:4,targa:"AB123CD",cat:"Bollo",date:"2026-04-30",note:""},
        {id:5,targa:"AB123CD",cat:"Revisione",date:"2026-08-10",note:""},
        {id:6,targa:"MU001AZ",cat:"Revisione",date:"2025-03-20",note:""},
      ];
      nextId=30;
      save();
    }
  }catch(e){}
  loaded=true;
  // Migra items[] → vehicles.docs (prima volta)
  initDocsFromItems();
  // Sincronizza docs → items
  syncAllDocsToItems();
  populateTargaSelect();
  render();
  renderMov();
  renderDashboard();
  renderClienti();
  renderGarage();
  populateGarTargaSelect();
  renderSinistri();
  populateSinTargaSelect();
  renderOfficina();
  populateOffTargaSelect();
}

function save(){
  lsSet(STORAGE_KEY_V, JSON.stringify(vehicles));
  lsSet(STORAGE_KEY_I, JSON.stringify(items));
  lsSet(STORAGE_KEY_N, String(nextId));
  lsSet(STORAGE_KEY_M, JSON.stringify(movimenti));
  lsSet(STORAGE_KEY_MN, String(nextMovId));
  lsSet(STORAGE_KEY_C, JSON.stringify(clienti));
  lsSet(STORAGE_KEY_CN, String(nextCliId));
  lsSet(STORAGE_KEY_INT, JSON.stringify(interventi));
  lsSet(STORAGE_KEY_IN, String(nextIntId));
  lsSet(STORAGE_KEY_SIN, JSON.stringify(sinistri));
  lsSet(STORAGE_KEY_SN, String(nextSinId));
  lsSet(STORAGE_KEY_AUT, JSON.stringify(autisti));
  lsSet(STORAGE_KEY_AN, String(nextAutId));
  if(loaded){ syncAllDocsToItems(); renderDashboard(); if(document.getElementById('page-scadenze').classList.contains('active')) render(); if(document.getElementById('page-officina').classList.contains('active')) renderOfficina(); }
}

function toast(msg){
  const t=document.getElementById('toast');
  t.textContent=msg; t.classList.add('show');
  setTimeout(()=>t.classList.remove('show'),2500);
}

function st(d){
  if(!d) return "ok";
  const dd=new Date(d); dd.setHours(0,0,0,0);
  const diff=Math.round((dd-today)/86400000);
  return diff<0?"scaduto":diff<=30?"urgente":"ok";
}
function lbl(d){
  if(!d) return "";
  const dd=new Date(d); dd.setHours(0,0,0,0);
  const diff=Math.round((dd-today)/86400000);
  if(diff<0) return `Scaduto ${Math.abs(diff)}gg fa`;
  if(diff===0) return "Scade oggi";
  if(diff<=30) return `Tra ${diff} giorni`;
  return new Date(d).toLocaleDateString("it-IT");
}
function fmt(d){ return d ? new Date(d).toLocaleDateString("it-IT") : "—"; }
function fmtEur(n){ return n ? `€ ${parseFloat(n).toLocaleString("it-IT")}` : "—"; }
const ICON={Auto:"🚗",Furgone:"🚐",Camion:"🚚",Moto:"🏍",Muletto:"🏗",Altro:"🚘"};
const STATO_LABELS={aperto:'Aperto',in_corso:'In corso',attesa:'Attesa ricambi',completato:'Completato'};
const TIPO_ICONS={Tagliando:'🔩',Revisione:'📋',Riparazione:'🔨',Pneumatici:'🛞',Freni:'🛑',Carrozzeria:'🚗',Elettrico:'⚡',Altro:'🔧'};
const SIN_LABELS={aperto:'Aperto',in_gestione:'In gestione',chiuso:'Chiuso',contestato:'Contestato'};

// ════════════════════════════════════════════
// CHECKLIST VOCI
// ════════════════════════════════════════════
const CHECKLIST_USCITA=[
  {id:'luci',        label:'Luci funzionanti'},
  {id:'specchi',     label:'Specchi integri'},
  {id:'pneumatici',  label:'Pneumatici OK'},
  {id:'carburante',  label:'Carburante verificato'},
  {id:'documenti',   label:'Documenti a bordo'},
  {id:'kit_pronto',  label:'Kit emergenza presente'},
  {id:'pulizia',     label:'Interno pulito'},
  {id:'graffii',     label:'Carrozzeria verificata'},
  {id:'cinture',     label:'Cinture di sicurezza OK'},
  {id:'chiavi',      label:'Chiavi consegnate'},
];
const CHECKLIST_RIENTRO=[
  {id:'luci',        label:'Luci funzionanti'},
  {id:'specchi',     label:'Specchi integri'},
  {id:'pneumatici',  label:'Pneumatici OK'},
  {id:'carburante',  label:'Carburante verificato'},
  {id:'documenti',   label:'Documenti a bordo'},
  {id:'kit_pronto',  label:'Kit emergenza presente'},
  {id:'pulizia',     label:'Interno pulito'},
  {id:'graffii',     label:'Nuovi danni visivi'},
  {id:'chiavi',      label:'Chiavi restituite'},
  {id:'rifornimento',label:'Rifornimento effettuato'},
];


function allDatesForVehicle(targa){
  const v=vehicles[targa];
  const dates=items.filter(i=>i.targa===targa).map(i=>i.date);
  if(v&&v.scadFor) dates.push(v.scadFor);
  if(v&&v.scadCli) dates.push(v.scadCli);
  return dates;
}
function worstStatus(dates){
  let s="ok";
  dates.forEach(d=>{
    const ds=st(d);
    if(ds==="scaduto") s="scaduto";
    else if(ds==="urgente"&&s!=="scaduto") s="urgente";
  });
  return s;
}

const PAGE_TITLES={'dashboard':'Dashboard','scadenze':'Scadenze operative','noleggi':'Noleggi','clienti':'Clienti','garage':'Mezzi','officina':'Officina','sinistri':'Sinistri'};
function switchMain(p){
  ['dashboard','scadenze','noleggi','clienti','garage','officina','sinistri'].forEach(id=>{
    const pg=document.getElementById('page-'+id);
    const nb=document.getElementById('nav-'+id);
    if(pg) pg.classList.toggle('active',id===p);
    if(nb) nb.classList.toggle('active',id===p);
  });
  const tt=document.getElementById('topbar-title');
  if(tt) tt.textContent=PAGE_TITLES[p]||p;
  // close mobile menu
  const sn=document.getElementById('sidebar-nav');
  if(sn) sn.classList.remove('open');
  if(p==='noleggi') renderMov();
  if(p==='dashboard') renderDashboard();
  if(p==='clienti') renderClienti();
  if(p==='garage'){ renderGarage(); populateGarTargaSelect(); }
  if(p==='officina'){ renderOfficina(); populateOffTargaSelect(); }
  if(p==='sinistri'){ renderSinistri(); populateSinTargaSelect(); }
}
function toggleMenu(){
  document.getElementById('sidebar-nav').classList.toggle('open');
}

function switchTab(t){
  document.querySelectorAll('.tab').forEach((el,i)=>el.classList.toggle('active',(i===0&&t==='scad')||(i===1&&t==='mezzo')));
  document.getElementById('tab-scad').classList.toggle('active',t==='scad');
  document.getElementById('tab-mezzo').classList.toggle('active',t==='mezzo');
}

function toggleNolForm(){
  const isNol=document.getElementById("m-poss").value==="noleggio";
  document.getElementById("wrap-fornitore").style.display=isNol?"":"none";
  document.getElementById("wrap-nol").style.display=isNol?"":"none";
}

function populateTargaSelect(){
  const sel=document.getElementById('mov-filter-targa');
  const sel2=document.getElementById('s-targa');
  const targas=Object.keys(vehicles);
  sel.innerHTML='<option value="all">Tutti i mezzi</option>'+targas.map(t=>`<option value="${t}">${t}</option>`).join('');
  sel2.innerHTML='<option value="">— seleziona —</option>'+targas.map(t=>`<option value="${t}">${t} — ${vehicles[t].tipo}</option>`).join('');
}

function render(){
  if(!loaded) return;
  const q=(document.getElementById('search')||{value:''}).value.toLowerCase();
  const filterTipo=(document.getElementById('scad-filter-tipo')||{value:'all'}).value;

  // Costruisci lista completa di tutti gli alert
  let allAlerts=[];

  // 1. Scadenze operative (items)
  const CAT_ICONS={
    Assicurazione:'📄',Revisione:'🔍',Bollo:'💳',Tagliando:'🔩',
    Tachigrafo:'📡',Leasing:'🏦',Licenza:'📜',Permesso:'🛂',
    'Contratto fornitore':'📋','Contratto cliente':'🤝',Altro:'📋'
  };
  items.forEach(i=>{
    const s=stAlert(i.date);
    const diff=Math.round((new Date(i.date)-today)/86400000);
    allAlerts.push({
      tipo:'veicolo', cat:i.cat, targa:i.targa,
      data:i.date, diff, stato:s,
      icon:CAT_ICONS[i.cat]||'📋',
      sottotipo:'', id:i.id,
      label: diff<0?'Scaduto '+Math.abs(diff)+'gg fa':diff===0?'Scade oggi':'Tra '+diff+' gg',
      canDelete:true
    });
  });

  // 2. Contratti veicoli (scadFor, scadCli)
  Object.keys(vehicles).forEach(targa=>{
    const v=vehicles[targa];
    if(v.scadFor){
      const diff=Math.round((new Date(v.scadFor)-today)/86400000);
      allAlerts.push({tipo:'contratto',cat:'Contratto',targa,data:v.scadFor,diff,stato:stAlert(v.scadFor),
        icon:'📋',sottotipo:'Fornitore: '+(v.fornitore||'—'),label:diff<0?'Scaduto '+Math.abs(diff)+'gg fa':diff===0?'Scade oggi':'Tra '+diff+' gg',canDelete:false});
    }
    if(v.scadCli){
      const diff=Math.round((new Date(v.scadCli)-today)/86400000);
      allAlerts.push({tipo:'contratto',cat:'Contratto',targa,data:v.scadCli,diff,stato:stAlert(v.scadCli),
        icon:'🤝',sottotipo:'Cliente: '+(v.cliente||'—'),label:diff<0?'Scaduto '+Math.abs(diff)+'gg fa':diff===0?'Scade oggi':'Tra '+diff+' gg',canDelete:false});
    }
  });

  // 3. Patenti autisti
  autisti.forEach(a=>{
    if(a.scadPatente){
      const diff=Math.round((new Date(a.scadPatente)-today)/86400000);
      const s=stAlert(a.scadPatente);
      allAlerts.push({tipo:'autista',cat:'Patente',targa:'',data:a.scadPatente,diff,stato:s,
        icon:'🪪',sottotipo:a.nome+' '+a.cognome+(a.patente?' · '+a.patente:''),
        label:diff<0?'Scaduta '+Math.abs(diff)+'gg fa':diff===0?'Scade oggi':'Tra '+diff+' gg',canDelete:false,autId:a.id});
    }
    if(a.scadDoc&&a.scadDoc!==''){
      const diff=Math.round((new Date(a.scadDoc)-today)/86400000);
      const s=stAlert(a.scadDoc);
      allAlerts.push({tipo:'autista',cat:'Documento',targa:'',data:a.scadDoc,diff,stato:s,
        icon:'📄',sottotipo:a.nome+' '+a.cognome+(a.tipoDoc?' · '+a.tipoDoc:''),
        label:diff<0?'Scaduto '+Math.abs(diff)+'gg fa':diff===0?'Scade oggi':'Tra '+diff+' gg',canDelete:false,autId:a.id});
    }
  });

  // 4. Manutenzioni imminenti (interventi aperti con dataPrev entro 14gg)
  interventi.filter(i=>i.stato!=='completato'&&i.dataPrev).forEach(i=>{
    const diff=Math.round((new Date(i.dataPrev)-today)/86400000);
    if(diff<=14){
      const s=diff<0?'scaduto':diff<=7?'urgente7':'urgente';
      allAlerts.push({tipo:'manutenzione',cat:'Manutenzione',targa:i.targa,data:i.dataPrev,diff,stato:s,
        icon:TIPO_ICONS[i.tipo]||'🔧',sottotipo:i.tipo+' — '+STATO_LABELS[i.stato],
        label:diff<0?'Scaduto '+Math.abs(diff)+'gg fa':diff===0?'Previsto oggi':'Tra '+diff+' gg',canDelete:false,intId:i.id});
    }
  });

  // KPI
  const scaduti=allAlerts.filter(a=>a.stato==='scaduto').length;
  const urg7=allAlerts.filter(a=>a.stato==='urgente7').length;
  const urgenti=allAlerts.filter(a=>a.stato==='urgente').length;
  const ok=allAlerts.filter(a=>a.stato==='ok').length;
  const setEl=(id,v)=>{const el=document.getElementById(id);if(el)el.textContent=v;};
  setEl('cnt-s',scaduti); setEl('cnt-u7',urg7); setEl('cnt-u',urgenti);
  setEl('cnt-o',ok); setEl('cnt-tot',allAlerts.length);
  // anche vecchi KPI
  setEl('cnt-s',scaduti);

  // Sidebar badge
  const nbScad=document.getElementById('nb-scad');
  if(nbScad){const n=scaduti+urg7;nbScad.textContent=n;nbScad.style.display=n>0?'':'none';}
  // topbar badge
  const tba=document.getElementById('tb-alerts');
  if(tba){tba.style.display=scaduti+urg7>0?'':'none';tba.textContent='⚠️ '+(scaduti+urg7)+' scadenze';}

  // Applica filtro attivo
  const filtroAttivo=window._scadFiltro||'urgenti';
  let filtered=allAlerts;
  if(filtroAttivo==='urgenti') filtered=allAlerts.filter(a=>a.stato==='scaduto'||a.stato==='urgente7');
  else if(filtroAttivo==='prossimi') filtered=allAlerts.filter(a=>a.stato==='urgente');
  else if(filtroAttivo==='ok') filtered=allAlerts.filter(a=>a.stato==='ok');
  // filtro tipo
  if(filterTipo!=='all') filtered=filtered.filter(a=>a.cat===filterTipo||(filterTipo==='Patente'&&a.tipo==='autista')||(filterTipo==='Manutenzione'&&a.tipo==='manutenzione')||(filterTipo==='Contratto'&&a.tipo==='contratto'));
  // ricerca
  if(q) filtered=filtered.filter(a=>(a.targa||'').toLowerCase().includes(q)||(a.cat||'').toLowerCase().includes(q)||(a.sottotipo||'').toLowerCase().includes(q));

  // Ordina: scaduti prima, poi per diff crescente
  filtered.sort((a,b)=>a.diff-b.diff);

  const listEl=document.getElementById('list');
  if(!filtered.length){
    const msg={urgenti:'Nessuna scadenza urgente 🎉',prossimi:'Nessuna scadenza nei prossimi 30 giorni',ok:'Nessun documento in regola trovato (controlla i filtri)',all:'Nessuna scadenza trovata'}[filtroAttivo]||'Nessuna scadenza trovata';
    listEl.innerHTML=`<div style="text-align:center;padding:3rem 1rem;color:#aaa"><div style="font-size:40px;margin-bottom:12px">${filtroAttivo==='urgenti'?'✅':'🔍'}</div><div style="font-size:15px;font-weight:600;color:#999">${msg}</div></div>`;
    return;
  }

  // Raggruppa per stato
  const groups=[
    {key:'scaduto',  label:'Scaduti',          cls:'rosso',  items:filtered.filter(a=>a.stato==='scaduto')},
    {key:'urgente7', label:'Critici — entro 7 giorni', cls:'rosso',items:filtered.filter(a=>a.stato==='urgente7')},
    {key:'urgente',  label:'Attenzione — entro 30 giorni',cls:'arancio',items:filtered.filter(a=>a.stato==='urgente')},
    {key:'ok',       label:'In regola',         cls:'verde',  items:filtered.filter(a=>a.stato==='ok')},
  ].filter(g=>g.items.length>0);

  let html2='';
  groups.forEach(g=>{
    html2+=`<div class="scad-group-header ${g.cls}">${g.label} <span style="font-weight:400;opacity:.7">(${g.items.length})</span></div>`;
    g.items.forEach(a=>{
      const rowCls=a.stato==='urgente7'?'urgente7':a.stato;
      const targaHtml=a.targa?`<span class="scad-targa">${a.targa}</span>`:'';
      const gotoBtn=a.targa
        ? `<button class="scad-goto" onclick="event.stopPropagation();switchMain('garage');setTimeout(()=>openSchedaVeicolo('${a.targa}'),200)">→ Scheda</button>`
        : (a.autId?`<button class="scad-goto" onclick="event.stopPropagation();switchMain('clienti')">→ Clienti</button>`:'');
      const delBtn=a.canDelete
        ? `<button class="del-btn" onclick="event.stopPropagation();delItem(${a.id})" title="Elimina">×</button>`
        : '';
      html2+=`<div class="scad-row ${rowCls}" onclick="${a.targa?`switchMain('garage');setTimeout(()=>openSchedaVeicolo('${a.targa}'),200)`:''}" >
        <span class="scad-icon">${a.icon}</span>
        ${targaHtml}
        <div style="flex:1;min-width:0">
          <div class="scad-tipo">${a.cat}</div>
          ${a.sottotipo?`<div class="scad-sottotipo">${a.sottotipo}</div>`:''}
        </div>
        <span class="scad-data">${fmt(a.data)}</span>
        <span class="scad-giorni ${rowCls}">${a.label}</span>
        ${gotoBtn}
        ${delBtn}
      </div>`;
    });
  });
  listEl.innerHTML=html2;
}

// Funzione stato alert con soglia 7gg
function stAlert(d){
  if(!d) return 'ok';
  const dd=new Date(d); dd.setHours(0,0,0,0);
  const diff=Math.round((dd-today)/86400000);
  if(diff<0) return 'scaduto';
  if(diff<=7) return 'urgente7';
  if(diff<=30) return 'urgente';
  return 'ok';
}

// Imposta filtro scadenze
window._scadFiltro='urgenti';
function setScadFilter(f){
  window._scadFiltro=f;
  // Aggiorna tab attivo
  ['urgenti','prossimi','ok','all'].forEach(k=>{
    const el=document.getElementById('sft-'+k);
    if(el) el.classList.toggle('active',k===f);
  });
  render();
}

function renderMov(){
  if(!loaded) return;
  const q=(document.getElementById("mov-search").value||"").toLowerCase();
  const ft=document.getElementById("mov-filter-targa").value;
  const fs=document.getElementById("mov-filter-stato").value;
  const tot=movimenti.length;
  const open=movimenti.filter(m=>!m.rientro).length;
  document.getElementById("mov-cnt-tot").textContent=tot;
  document.getElementById("mov-cnt-open").textContent=open;
  document.getElementById("mov-cnt-done").textContent=tot-open;
  const list=movimenti.filter(m=>{
    if(ft!=="all"&&m.targa!==ft) return false;
    if(fs==="aperto"&&m.rientro) return false;
    if(fs==="chiuso"&&!m.rientro) return false;
    if(q&&!m.targa.toLowerCase().includes(q)&&!(m.conducente||"").toLowerCase().includes(q)) return false;
    return true;
  }).sort((a,b)=>new Date(b.dataOut)-new Date(a.dataOut));
  if(!list.length){ document.getElementById("mov-list").innerHTML=`<div class="empty">Nessuna scheda trovata</div>`; return; }
  let html="";
  list.forEach(m=>{
    const v=vehicles[m.targa]||{};
    const statoBadge=m.rientro?"badge rientro":"badge aperto";
    const statoLbl=m.rientro?"Completata":"In corso";
    const c=m.contratto||{};
    const statoNol=c.stato||'aperto';
    const STATO_NOL_LBL={aperto:'Aperto',attivo:'Attivo',scaduto:'Scaduto',chiuso:'Chiuso',rinnovato:'Rinnovato'};
    // Calcola giorni rimasti/scaduti dalla data fine contratto
    let diffBadge='';
    if(c.dataFine){
      const diff=Math.round((new Date(c.dataFine)-today)/86400000);
      if(diff<0) diffBadge=`<span class="diff-badge db-exp">Scaduto ${Math.abs(diff)}gg fa</span>`;
      else if(diff<=14) diffBadge=`<span class="diff-badge db-warn">Scade tra ${diff}gg</span>`;
      else diffBadge=`<span class="diff-badge db-ok">Attivo ${diff}gg rimasti</span>`;
    }
    const aziendaInfo=(()=>{const az=m.aziendaId&&clienti.find(c=>c.id===m.aziendaId);return az?az.azienda:'';})();
    const autistaInfo=(()=>{const a=m.autistId&&autisti.find(a=>a.id===m.autistId);return a?a.nome+' '+a.cognome:'';})();
    // Usa autista da wizard se disponibile, altrimenti conducente libero
    const conducente=autistaInfo||m.conducente||'';
    html+=`<div class="mov-card mc-${m.rientro?'chiuso':'aperto'}">
      <div class="mov-header">
        <span style="font-size:15px">${ICON[v.tipo]||"🚘"}</span>
        <span class="plate">${m.targa}</span>
        <span style="font-size:13px;color:#666">${v.tipo||""}</span>
        ${conducente?`<span style="font-size:13px;font-weight:500">👤 ${conducente}</span>`:""}
        ${aziendaInfo?`<span style="font-size:12px;color:#888">🏢 ${aziendaInfo}</span>`:""}
        <span class="${statoBadge}">${statoLbl}</span>
        <span class="stato-nol sn-${statoNol}">${STATO_NOL_LBL[statoNol]||statoNol}</span>
        ${diffBadge}
        <span style="font-size:12px;color:#aaa;margin-left:auto">Scheda #${m.id}</span>
      </div>
      ${periodoBarHTML(m)}
      <div style="display:grid;grid-template-columns:1fr 1fr;gap:12px">
        <div class="half-section out">
          <div style="font-size:11px;font-weight:500;color:#185FA5;margin-bottom:6px;text-transform:uppercase;letter-spacing:0.04em">Uscita — ${fmt(m.dataOut)}${m.oraOut?" "+m.oraOut:""}</div>
          <div class="mov-grid">
            <div><div class="mov-label">KM</div><div class="mov-val">${m.kmOut?Number(m.kmOut).toLocaleString("it-IT")+" km":"—"}</div></div>
            <div><div class="mov-label">Carburante</div><div class="mov-val">${m.gasolioOut?m.gasolioOut+"%":"—"}</div></div>
            <div><div class="mov-label">Danni</div><div class="mov-val" style="font-weight:400;font-size:12px">${m.danniOut||"Nessuno"}</div></div>
            <div><div class="mov-label">Note</div><div class="mov-val" style="font-weight:400;font-size:12px">${m.noteOut||"—"}</div></div>
          </div>
          ${m.checklistOut?`<div style="margin-top:6px"><span style="font-size:10px;color:#aaa;text-transform:uppercase;letter-spacing:.04em;font-weight:600">Checklist uscita </span>${checklistBadge(m.checklistOut)}</div>`:''}
        </div>
        <div class="half-section in">
          ${m.rientro?`
          <div style="font-size:11px;font-weight:500;color:#3B6D11;margin-bottom:6px;text-transform:uppercase;letter-spacing:0.04em">Rientro — ${fmt(m.rientro.dataIn)}${m.rientro.oraIn?" "+m.rientro.oraIn:""}</div>
          <div class="mov-grid">
            <div><div class="mov-label">KM</div><div class="mov-val">${m.rientro.kmIn?Number(m.rientro.kmIn).toLocaleString("it-IT")+" km":"—"}</div></div>
            <div><div class="mov-label">KM percorsi</div><div class="mov-val">${(m.kmOut&&m.rientro.kmIn)?(Number(m.rientro.kmIn)-Number(m.kmOut)).toLocaleString("it-IT")+" km":"—"}</div></div>
            <div><div class="mov-label">Carburante</div><div class="mov-val">${m.rientro.gasolioIn?m.rientro.gasolioIn+"%":"—"}</div></div>
            <div><div class="mov-label">Rifornimento</div><div class="mov-val">${m.rientro.rifornimento?m.rientro.rifornimento+" L":"—"}</div></div>
            <div><div class="mov-label">Danni</div><div class="mov-val" style="font-weight:400;font-size:12px">${m.rientro.danniIn||"Nessuno"}</div></div>
            <div><div class="mov-label">Note</div><div class="mov-val" style="font-weight:400;font-size:12px">${m.rientro.noteIn||"—"}</div></div>
          </div>
          ${m.rientro.checklistIn?`<div style="margin-top:6px"><span style="font-size:10px;color:#aaa;text-transform:uppercase;letter-spacing:.04em;font-weight:600">Checklist rientro </span>${checklistBadge(m.rientro.checklistIn)}</div>`:''}`:`
          <div style="font-size:11px;font-weight:500;color:#aaa;margin-bottom:6px;text-transform:uppercase;letter-spacing:0.04em">Rientro — non ancora registrato</div>
          <button class="btn-green" style="margin-top:4px" onclick="openRientro(${m.id})">Registra rientro</button>`}
        </div>
      </div>
      <!-- Riepilogo contratto se presente -->
      ${(()=>{
        const c=m.contratto||{};
        if(!c.societa&&!c.numContratto&&!c.canone&&!c.dataFine) return '';
        const STATO_NOL_LBL={aperto:'Aperto',attivo:'Attivo',scaduto:'Scaduto',chiuso:'Chiuso',rinnovato:'Rinnovato'};
        return '<div style="background:#f5f4f0;border-radius:8px;padding:8px 12px;margin-top:8px;font-size:12px;display:flex;gap:16px;flex-wrap:wrap;align-items:center">'+
          '<span style="font-weight:600;color:#aaa;font-size:10px;text-transform:uppercase;letter-spacing:.05em">Contratto</span>'+
          (c.societa?'<span>🏢 '+c.societa+'</span>':'')+
          (c.numContratto?'<span>📋 '+c.numContratto+'</span>':'')+
          (c.canone?'<span>💶 €'+Number(c.canone).toLocaleString("it-IT")+'/mese</span>':'')+
          (c.dataFine?'<span>📅 Fine: '+fmt(c.dataFine)+'</span>':'')+
          (c.kmInclusi?'<span>🛣 '+Number(c.kmInclusi).toLocaleString("it-IT")+' km</span>':'')+
        '</div>';
      })()}
      <div class="mov-actions">
        <button onclick="stampaPDF(${m.id})">🖨️ PDF</button>
        <button class="btn-primary" onclick="openEditNol(${m.id})" style="background:#1a1a18;border-color:#1a1a18">✏️ Modifica noleggio</button>
        ${!m.rientro?`<button class="btn-green" onclick="openRientro(${m.id})">🏁 Registra rientro</button>`:""}
        <button class="btn-danger" onclick="delMov(${m.id})">Elimina</button>
      </div>
      <div class="edit-nol-panel" id="edit-panel-${m.id}" style="display:none"></div>
    </div>`;
  });
  document.getElementById("mov-list").innerHTML=html;
}

function openRientro(id){
  const existing=document.getElementById('modal-rientro');
  if(existing) existing.remove();
  const m=movimenti.find(x=>x.id===id);
  if(!m) return;
  const div=document.createElement('div');
  div.id='modal-rientro';
  div.style.cssText='background:#f5f4f0;border:0.5px solid rgba(0,0,0,0.2);border-radius:12px;padding:1.25rem;margin-bottom:1rem';
  div.innerHTML=`
    <div style="font-size:14px;font-weight:500;margin-bottom:12px">Registra rientro — Scheda #${id} (${m.targa})</div>
    <div class="row r4">
      <div class="fg"><label>Data rientro *</label><input type="date" id="r-data-in" value="${new Date().toISOString().slice(0,10)}"></div>
      <div class="fg"><label>Ora rientro</label><input type="time" id="r-ora-in"></div>
      <div class="fg"><label>KM rientro</label><input type="number" id="r-km-in" placeholder="es. 45890"></div>
      <div class="fg"><label>Carburante rientro (%)</label><input type="number" id="r-gasolio-in" placeholder="es. 30" min="0" max="100"></div>
    </div>
    <div class="row r3">
      <div class="fg"><label>Danni al rientro</label><input type="text" id="r-danni-in" placeholder="es. Nuovo graffio paraurti, nessuno…"></div>
      <div class="fg"><label>Note rientro</label><input type="text" id="r-note-in" placeholder="Opzionale"></div>
      <div class="fg"><label>Rifornimento effettuato (L)</label><input type="number" id="r-riforn" placeholder="es. 40"></div>
    </div>
    <div class="section-sep" style="margin-top:10px">Checklist rientro</div>
    <div class="checklist-wrap">
      <div class="checklist-title"><span>🔍</span> Verifica rientro mezzo</div>
      <div class="checklist-grid" id="cl-in-grid"></div>
      <div class="checklist-progress">
        <div class="checklist-bar-wrap"><div class="checklist-bar" id="cl-in-bar" style="width:0%"></div></div>
        <span class="checklist-pct" id="cl-in-pct">0/10</span>
      </div>
    </div>
    <div style="display:flex;gap:8px;margin-top:8px">
      <button class="btn-green" onclick="salvaRientro(${id})">Salva rientro</button>
      <button onclick="document.getElementById('modal-rientro').remove()">Annulla</button>
    </div>`;
  const list=document.getElementById('mov-list');
  list.insertBefore(div,list.firstChild);
  div.scrollIntoView({behavior:'smooth',block:'start'});
  // Render checklist rientro dopo inserimento DOM
  renderChecklist(CHECKLIST_RIENTRO,'cl-in-grid','cl-in-bar','cl-in-pct','cl-in');
}

function salvaRientro(id){
  const dataIn=document.getElementById('r-data-in').value;
  if(!dataIn){ document.getElementById('r-data-in').focus(); return; }
  const m=movimenti.find(x=>x.id===id);
  if(!m) return;
  m.rientro={
    dataIn,
    oraIn:document.getElementById('r-ora-in').value,
    kmIn:document.getElementById('r-km-in').value,
    gasolioIn:document.getElementById('r-gasolio-in').value,
    danniIn:document.getElementById('r-danni-in').value.trim(),
    noteIn:document.getElementById('r-note-in').value.trim(),
    rifornimento:document.getElementById('r-riforn').value,
    checklistIn:getChecklistValues('cl-in', CHECKLIST_RIENTRO),
  };
  save();
  document.getElementById('modal-rientro').remove();
  toast('Rientro salvato');
  renderMov();
}

function addMovimento(){
  const targa=document.getElementById('s-targa').value;
  const dataOut=document.getElementById('s-data-out').value;
  if(!targa){ document.getElementById('s-targa').focus(); return; }
  if(!dataOut){ document.getElementById('s-data-out').focus(); return; }
  movimenti.push({
    id:nextMovId++, targa,
    conducente:document.getElementById('s-conducente').value.trim(),
    dataOut,
    oraOut:document.getElementById('s-ora-out').value,
    kmOut:document.getElementById('s-km-out').value,
    gasolioOut:document.getElementById('s-gasolio-out').value,
    danniOut:document.getElementById('s-danni-out').value.trim(),
    noteOut:document.getElementById('s-note-out').value.trim(),
    checklistOut:getChecklistValues('cl-out', CHECKLIST_USCITA),
    rientro:null,
    contratto:{societa:'',numContratto:'',dataInizio:dataOut,dataFine:'',durataMesi:'',
               canone:'',costoTotale:'',kmInclusi:'',kmExtra:'',deposito:'',
               pagamento:'',note:'',stato:'aperto'},
    storico:[{data:today.toISOString().slice(0,10),campo:'Creazione',vecchio:'',nuovo:'Noleggio creato per '+targa}],
  });
  save();
  toast('Uscita registrata');
  ['s-conducente','s-km-out','s-gasolio-out','s-danni-out','s-note-out'].forEach(id=>{ document.getElementById(id).value=''; });
  // Reset checklist uscita
  renderChecklist(CHECKLIST_USCITA,'cl-out-grid','cl-out-bar','cl-out-pct','cl-out');
  document.getElementById('s-targa').value='';
  document.getElementById('s-data-out').value=new Date().toISOString().slice(0,10);
  renderMov();
}

function delMov(id){
  const m=movimenti.find(x=>x.id===id);
  if(!m) return;
  const confirmMsg='Eliminare la scheda #'+id+' ('+m.targa+')?'+(m.storico&&m.storico.length?' Verranno perse '+m.storico.length+' modifiche nel log.':'');
  if(!confirm(confirmMsg)) return;
  // Rimuovi scadenza contratto collegata se presente
  if(m.contratto&&m.contratto.dataFine){
    items=items.filter(function(i){return !(i.targa===m.targa&&i.cat==='Contratto cliente'&&i.date===m.contratto.dataFine);});
  }
  movimenti=movimenti.filter(x=>x.id!==id);
  save();
  renderMov();
  renderDashboard();
  toast('Scheda #'+id+' eliminata');
}

async function stampaPDF(id){
  const m=movimenti.find(function(x){return x.id===id;});
  if(!m) return;
  const {jsPDF}=window.jspdf;
  const doc=new jsPDF({unit:'mm',format:'a4',orientation:'portrait'});

  // ── Font: tenta Aptos (Microsoft), fallback Helvetica ───────
  let _font='helvetica';
  try{
    const tf=new FontFace('Aptos','local(Aptos)');
    await tf.load();
    document.fonts.add(tf);
    _font='Aptos';
  }catch(e){ _font='helvetica'; }
  function SF(style){ // setFont wrapper
    try{ doc.setFont(_font,style); }catch(e){ doc.setFont('helvetica',style); }
  }

  // ── Palette ufficiale Vieffe ─────────────────────────────────
  const NERO   =[26,26,24];
  const ARANCIO=[255,102,0];
  const VERDE  =[59,109,17];
  const GRIGIO =[80,80,90];
  const BIANCO =[255,255,255];
  const TESTO  =[25,25,35];
  const LABEL  =[115,115,135];
  const BORDO  =[215,212,208];
  const SFONDO1=[248,247,245];

  // ── Layout fisso ─────────────────────────────────────────────
  const W=210, H=297, MG=10, CW=190;
  const HEADER_H=28, FOOTER_H=10, FIRMA_H=26;
  const FIRMA_Y=H-FOOTER_H-FIRMA_H;   // 261mm
  const BODY_TOP=HEADER_H+2;          // 30mm
  const BODY_BOT=FIRMA_Y-2;           // 259mm

  // ── Tipografia — offset FISSI calcolati geometricamente ──────
  // 1 punto tipografico = 0.353mm
  const FS_LBL=6.0, FS_DAT=8.0, FS_SEC=7.5, FS_CL=5.5;
  const H_LBL=FS_LBL*0.353; // 2.12mm — altezza reale font label
  const H_DAT=FS_DAT*0.353; // 2.82mm — altezza reale font dato
  // Offset baseline dal bordo superiore della riga:
  const O_LBL=1.8;                 // label a 1.8mm dalla cima
  const O_VAL=O_LBL+H_LBL+1.2;   // valore a 5.12mm dalla cima
  // Altezza minima riga: garantisce ZERO sovrapposizioni
  const RH=O_VAL+H_DAT+1.5;       // 9.44mm — mai meno di questo
  const SH=FS_SEC*0.353+4.0;      // 6.65mm — altezza barra sezione
  const CLH=FS_CL*0.353+2.2;      // 4.14mm — altezza riga checklist
  const GAP=1.2;                   // gap tra sezioni
  const CL_COLS=5;                 // colonne checklist

  // ── Dati correlati ───────────────────────────────────────────
  const v=vehicles[m.targa]||{};
  const pdfAz=m.aziendaId&&clienti.find(function(cl){return cl.id===m.aziendaId;})||null;
  const pdfAut=m.autistId&&autisti.find(function(a){return a.id===m.autistId;})||null;
  const pdfConducente=pdfAut?pdfAut.nome+' '+pdfAut.cognome:(m.conducente||'—');
  const hasR=!!m.rientro;
  const pdfP=calcPeriodo(m);
  const clOut=m.checklistOut||null;
  const clIn=hasR&&m.rientro.checklistIn?m.rientro.checklistIn:null;

  // ── Logo ─────────────────────────────────────────────────────
  const logoB64=(function(){
    const imgs=document.querySelectorAll('img');
    for(let i=0;i<imgs.length;i++){
      if(imgs[i].src&&imgs[i].src.indexOf('base64')>=0)
        return imgs[i].src.split(',')[1]||'';
    }
    return '';
  })();

  let y=BODY_TOP;
  let zebra=false;

  // ── HEADER ───────────────────────────────────────────────────
  doc.setFillColor.apply(doc,NERO);
  doc.rect(0,0,W,HEADER_H,'F');
  doc.setFillColor.apply(doc,ARANCIO);
  doc.rect(0,HEADER_H-1.2,W,1.2,'F');
  if(logoB64) try{doc.addImage('data:image/jpeg;base64,'+logoB64,'JPEG',MG,5,26,16);}catch(e){}
  doc.setFontSize(10);SF('bold');
  doc.setTextColor(255,255,255);
  doc.text('SCHEDA USCITA / RIENTRO MEZZO',MG+30,12);
  doc.setFontSize(6.5);SF('normal');
  doc.setTextColor(170,170,170);
  doc.text('Via Canturina 49, Como (CO) 22100  ·  Gestione Flotta Vieffe Rent Srl',MG+30,18);
  doc.setFontSize(6);
  doc.text('Scheda n.'+m.id+'  ·  '+new Date().toLocaleDateString('it-IT'),W-MG,23,{align:'right'});

  // ── HELPERS ──────────────────────────────────────────────────
  function clip(s,n){s=String(s||'—');return s.length>n?s.slice(0,n-1)+'…':s;}

  function secTitle(lbl,rgb){
    doc.setFillColor.apply(doc,rgb||ARANCIO);
    doc.rect(MG,y,CW,SH,'F');
    doc.setFontSize(FS_SEC);SF('bold');
    doc.setTextColor(255,255,255);
    doc.text(lbl,MG+2.5,y+SH*0.70);
    y+=SH;
    zebra=false;
  }

  function row2(l1,v1,l2,v2){
    const x2=MG+CW/2+2;
    doc.setFillColor.apply(doc,zebra?SFONDO1:[255,255,255]);
    doc.rect(MG,y,CW,RH,'F');
    zebra=!zebra;
    // Label — sempre sopra, mai tocca il valore
    doc.setFontSize(FS_LBL);SF('bold');
    doc.setTextColor.apply(doc,LABEL);
    doc.text(String(l1||''),MG+1.5,y+O_LBL);
    if(l2!==undefined) doc.text(String(l2||''),x2,y+O_LBL);
    // Valore — sempre sotto la label
    doc.setFontSize(FS_DAT);SF('normal');
    doc.setTextColor.apply(doc,TESTO);
    doc.text(clip(v1,38),MG+1.5,y+O_VAL);
    if(l2!==undefined) doc.text(clip(v2,38),x2,y+O_VAL);
    y+=RH;
  }

  function row1(l,v){
    doc.setFillColor.apply(doc,zebra?SFONDO1:[255,255,255]);
    doc.rect(MG,y,CW,RH,'F');
    zebra=!zebra;
    doc.setFontSize(FS_LBL);SF('bold');
    doc.setTextColor.apply(doc,LABEL);
    doc.text(String(l||''),MG+1.5,y+O_LBL);
    doc.setFontSize(FS_DAT);SF('normal');
    doc.setTextColor.apply(doc,TESTO);
    doc.text(clip(v,75),MG+1.5,y+O_VAL);
    y+=RH;
  }

  function sGap(){
    doc.setDrawColor.apply(doc,BORDO);
    doc.setLineWidth(0.1);
    doc.line(MG,y+GAP,MG+CW,y+GAP);
    y+=GAP*2.5;
    zebra=false;
  }

  function drawCL(cl,voci){
    if(!cl||!voci||!voci.length) return;
    const cols=CL_COLS;
    const cw=CW/cols;
    const rows=Math.ceil(voci.length/cols);
    const totH=rows*CLH+2;
    doc.setFillColor(246,245,243);
    doc.rect(MG,y,CW,totH,'F');
    doc.setDrawColor.apply(doc,BORDO);
    doc.setLineWidth(0.08);
    doc.rect(MG,y,CW,totH,'S');
    for(let i=0;i<voci.length;i++){
      const col=i%cols, row=Math.floor(i/cols);
      const cx=MG+col*cw+1.5;
      const cy=y+row*CLH+CLH*0.72;
      const bx=cx, by=cy-CLH*0.55;
      const checked=cl[voci[i].id]===true;
      doc.setDrawColor.apply(doc,checked?VERDE:BORDO);
      doc.setLineWidth(0.3);
      doc.rect(bx,by,2.0,2.0,'S');
      if(checked){doc.setFillColor.apply(doc,VERDE);doc.rect(bx+0.25,by+0.25,1.5,1.5,'F');}
      doc.setFontSize(FS_CL);SF('normal');
      doc.setTextColor.apply(doc,checked?VERDE:LABEL);
      doc.text(clip(voci[i].label,13),bx+2.7,cy);
    }
    y+=totH+1;
    doc.setTextColor.apply(doc,TESTO);
  }

  // ════════════════════════════════════════════════════
  // SEZ 1 — AZIENDA DESTINATARIA
  // ════════════════════════════════════════════════════
  secTitle('AZIENDA DESTINATARIA',NERO);
  if(pdfAz){
    row2('Ragione sociale',pdfAz.azienda||pdfAz.nome,'P.IVA',pdfAz.piva||'—');
    row2('Telefono',pdfAz.tel||'—','Email',pdfAz.email||'—');
    if(pdfAz.indirizzo) row1('Indirizzo',pdfAz.indirizzo);
  } else {
    row2('Azienda / Cliente','Non collegata','','');
  }
  row2('Autista / Conducente',pdfConducente,'Patente',pdfAut&&pdfAut.patente?pdfAut.patente:'—');
  sGap();

  // ════════════════════════════════════════════════════
  // SEZ 2 — DATI VEICOLO
  // ════════════════════════════════════════════════════
  secTitle('DATI VEICOLO',GRIGIO);
  row2('Targa',m.targa,'Categoria',v.tipo||'—');
  row2('Marca / Modello',[(v.marca||''),(v.modello||'')].filter(Boolean).join(' ')||'—','Anno',v.anno||'—');
  row2('Sede operativa',v.sede||'—','Alimentazione',v.alimentazione||'—');
  sGap();

  // ════════════════════════════════════════════════════
  // SEZ 3 — PERIODO NOLEGGIO
  // ════════════════════════════════════════════════════
  secTitle('PERIODO NOLEGGIO',[90,90,100]);
  const _dOut=new Date(m.dataOut); _dOut.setHours(0,0,0,0);
  const _dIn=hasR&&m.rientro.dataIn?new Date(m.rientro.dataIn):null;
  if(_dIn) _dIn.setHours(0,0,0,0);
  const _giorni=Math.round(((_dIn||today)-_dOut)/86400000);
  const _kmP=(m.kmOut&&hasR&&m.rientro.kmIn)?Number(m.rientro.kmIn)-Number(m.kmOut):null;
  const _stato=hasR?'Completato':_giorni>30?'Lungo':'In corso';
  row2('Data uscita',fmt(m.dataOut),'Data rientro',hasR?fmt(m.rientro.dataIn):'Non ancora registrato');
  row2('Durata noleggio',_giorni+(_giorni===1?' giorno':' giorni'),'Stato',_stato);
  row2('KM percorsi',_kmP!==null?_kmP.toLocaleString('it-IT')+' km':'—','KM uscita',m.kmOut?Number(m.kmOut).toLocaleString('it-IT')+' km':'—');
  sGap();

  // ════════════════════════════════════════════════════
  // SEZ 4 — USCITA
  // ════════════════════════════════════════════════════
  secTitle('USCITA VEICOLO',ARANCIO);
  row2('Data uscita',fmt(m.dataOut),'Ora',m.oraOut||'—');
  row2('KM uscita',m.kmOut?Number(m.kmOut).toLocaleString('it-IT')+' km':'—','Carburante',m.gasolioOut?m.gasolioOut+'%':'—');
  row2('Danni presenti',m.danniOut||'Nessuno','Note',m.noteOut||'—');
  if(clOut&&Object.keys(clOut).length>0) drawCL(clOut,CHECKLIST_USCITA);
  sGap();

  // ════════════════════════════════════════════════════
  // SEZ 5 — RIENTRO
  // ════════════════════════════════════════════════════
  secTitle('RIENTRO VEICOLO',hasR?ARANCIO:[150,150,150]);
  if(hasR){
    const r=m.rientro;
    const kmP=pdfP&&pdfP.kmPercorsi!==null?pdfP.kmPercorsi.toLocaleString('it-IT')+' km':'—';
    row2('Data rientro',fmt(r.dataIn),'Ora',r.oraIn||'—');
    row2('KM rientro',r.kmIn?Number(r.kmIn).toLocaleString('it-IT')+' km':'—','KM percorsi',kmP);
    row2('Carburante',r.gasolioIn?r.gasolioIn+'%':'—','Rifornimento',r.rifornimento?r.rifornimento+' L':'—');
    row2('Nuovi danni',r.danniIn||'Nessuno','Note',r.noteIn||'—');
    if(clIn&&Object.keys(clIn).length>0) drawCL(clIn,CHECKLIST_RIENTRO);
  } else {
    doc.setFontSize(FS_DAT);SF('italic');
    doc.setTextColor(170,170,170);
    doc.text('Rientro non ancora registrato — da compilare al rientro.',MG+1.5,y+O_VAL);
    y+=RH;
    row2('Data rientro','______________','Ora','____________');
    row2('KM rientro','______________','Carburante','____________');
    row2('Danni rilevati','______________________________________','Note','____________________');
  }

  // ════════════════════════════════════════════════════
  // FIRME — posizione FISSA
  // ════════════════════════════════════════════════════
  const FY=FIRMA_Y;
  doc.setFillColor(252,250,248);
  doc.rect(MG,FY,CW,FIRMA_H,'F');
  doc.setFillColor.apply(doc,ARANCIO);
  doc.rect(MG,FY,CW,1.2,'F');
  doc.setDrawColor.apply(doc,ARANCIO);
  doc.setLineWidth(0.3);
  doc.rect(MG,FY,CW,FIRMA_H,'S');
  doc.setDrawColor.apply(doc,BORDO);
  doc.setLineWidth(0.15);
  doc.line(MG+CW/2,FY+1.2,MG+CW/2,FY+FIRMA_H);
  doc.setFontSize(6.5);SF('bold');
  doc.setTextColor.apply(doc,LABEL);
  doc.text('FIRMA AUTISTA / CONDUCENTE',MG+3,FY+8);
  doc.text('FIRMA RESPONSABILE VIEFFE RENT',MG+CW/2+3,FY+8);
  const LY=FY+FIRMA_H-8;
  doc.setDrawColor.apply(doc,ARANCIO);
  doc.setLineWidth(0.35);
  doc.line(MG+3,LY,MG+CW/2-3,LY);
  doc.line(MG+CW/2+3,LY,MG+CW-3,LY);
  doc.setFontSize(6);SF('normal');
  doc.setTextColor.apply(doc,LABEL);
  doc.text('Data ___ /___ /______   Nome e firma',MG+3,LY+4);
  doc.text('Data ___ /___ /______   Nome e firma',MG+CW/2+3,LY+4);

  // ════════════════════════════════════════════════════
  // FOOTER — posizione FISSA
  // ════════════════════════════════════════════════════
  doc.setFillColor.apply(doc,NERO);
  doc.rect(0,H-FOOTER_H,W,FOOTER_H,'F');
  doc.setFillColor.apply(doc,ARANCIO);
  doc.rect(0,H-FOOTER_H,W,0.8,'F');
  doc.setFontSize(6);SF('normal');
  doc.setTextColor(150,150,150);
  doc.text('Vieffe Rent Srl  —  Via Canturina 49, Como (CO) 22100  —  '+new Date().toLocaleDateString('it-IT'),W/2,H-FOOTER_H+5,{align:'center'});

  doc.save('VR_'+m.targa+'_'+m.id+'.pdf');
  toast('📄 PDF generato');
}


function editMezzo(targa){
  const v=vehicles[targa];
  switchTab('mezzo');
  document.getElementById('m-targa').value=targa;
  document.getElementById('m-tipo').value=v.tipo;
  document.getElementById('m-poss').value=v.poss;
  toggleNolForm();
  if(v.poss==='noleggio'){
    document.getElementById('m-fornitore').value=v.fornitore||'';
    document.getElementById('m-ini-for').value=v.iniFor||'';
    document.getElementById('m-scad-for').value=v.scadFor||'';
    document.getElementById('m-canone').value=v.canone||'';
    document.getElementById('m-cliente').value=v.cliente||'';
    document.getElementById('m-piva').value=v.piva||'';
    document.getElementById('m-tel').value=v.tel||'';
    document.getElementById('m-email').value=v.email||'';
    document.getElementById('m-indirizzo').value=v.indirizzo||'';
    document.getElementById('m-ncontr').value=v.ncontr||'';
    document.getElementById('m-ini-cli').value=v.iniCli||'';
    document.getElementById('m-scad-cli').value=v.scadCli||'';
  }
  document.getElementById('m-targa').scrollIntoView({behavior:'smooth',block:'center'});
}

function saveMezzo(){
  const targa=document.getElementById('m-targa').value.trim().toUpperCase();
  if(!targa){ document.getElementById('m-targa').focus(); return; }
  const poss=document.getElementById('m-poss').value;
  vehicles[targa]={
    tipo:document.getElementById('m-tipo').value, poss,
    fornitore:poss==='noleggio'?document.getElementById('m-fornitore').value.trim():'',
    iniFor:poss==='noleggio'?document.getElementById('m-ini-for').value:'',
    scadFor:poss==='noleggio'?document.getElementById('m-scad-for').value:'',
    canone:poss==='noleggio'?document.getElementById('m-canone').value:'',
    cliente:poss==='noleggio'?document.getElementById('m-cliente').value.trim():'',
    piva:poss==='noleggio'?document.getElementById('m-piva').value.trim():'',
    tel:poss==='noleggio'?document.getElementById('m-tel').value.trim():'',
    email:poss==='noleggio'?document.getElementById('m-email').value.trim():'',
    indirizzo:poss==='noleggio'?document.getElementById('m-indirizzo').value.trim():'',
    ncontr:poss==='noleggio'?document.getElementById('m-ncontr').value.trim():'',
    iniCli:poss==='noleggio'?document.getElementById('m-ini-cli').value:'',
    scadCli:poss==='noleggio'?document.getElementById('m-scad-cli').value:'',
  };
  save();
  populateTargaSelect();
  toast('Mezzo salvato');
  ['m-targa','m-fornitore','m-cliente','m-piva','m-tel','m-email','m-indirizzo','m-ncontr'].forEach(id=>{ document.getElementById(id).value=''; });
  ['m-ini-for','m-scad-for','m-ini-cli','m-scad-cli'].forEach(id=>{ document.getElementById(id).value=''; });
  document.getElementById('m-canone').value='';
  toggleNolForm();
  render();
}

function deleteMezzo(){
  const targa=document.getElementById('m-targa').value.trim().toUpperCase();
  if(!targa||!vehicles[targa]){ toast('Inserisci una targa valida'); return; }
  if(!confirm(`Eliminare il mezzo ${targa} e tutte le sue scadenze?`)) return;
  delete vehicles[targa];
  items=items.filter(i=>i.targa!==targa);
  save();
  populateTargaSelect();
  toast('Mezzo eliminato');
  document.getElementById('m-targa').value='';
  render();
}

function addScad(){
  const targa=document.getElementById("n-targa").value.trim().toUpperCase();
  const date=document.getElementById("n-date").value;
  const cat=document.getElementById("n-cat").value;
  const note=document.getElementById("n-note").value.trim();
  if(!targa){ document.getElementById("n-targa").focus(); return; }
  if(!vehicles[targa]) vehicles[targa]={tipo:"Auto",poss:"proprieta",fornitore:"",cliente:"",piva:"",tel:"",email:"",indirizzo:"",ncontr:"",scadFor:"",scadCli:"",iniFor:"",iniCli:"",canone:""};
  if(date) items.push({id:nextId++,targa,cat,date,note});
  save();
  toast('Scadenza aggiunta');
  document.getElementById("n-targa").value="";
  document.getElementById("n-note").value="";
  render();
}

function delItem(id){
  items=items.filter(i=>i.id!==id);
  save();
  render();
}

document.getElementById("n-date").value=new Date(today.getTime()+90*86400000).toISOString().slice(0,10);
document.getElementById("s-data-out").value=new Date().toISOString().slice(0,10);
loadData();

// ════════════════════════════════════════════
// DASHBOARD
// ════════════════════════════════════════════

// Stato operativo mezzo: dedotto dai movimenti aperti
function getStatoMezzo(targa){
  const v=vehicles[targa]||{};
  // Se ha movimento aperto (uscita senza rientro) → noleggiato
  const aperto=movimenti.find(m=>m.targa===targa&&!m.rientro);
  if(aperto) return 'noleggiato';
  // Altrimenti usa stato custom se impostato
  if(v.statoOp) return v.statoOp;
  return 'disponibile';
}

function renderDashboard(){
  if(!loaded) return;

  // Topbar date
  const dateEl=document.getElementById('topbar-date');
  if(dateEl) dateEl.textContent=new Date().toLocaleDateString('it-IT',{weekday:'long',day:'numeric',month:'long',year:'numeric'});

  const targas=Object.keys(vehicles);
  const todayStr=today.toISOString().slice(0,10);

  // ── KPI ──────────────────────────────────
  let nDisp=0, nNol=0, nOff=0, nRientri=0, nScadUrgenti=0;
  targas.forEach(t=>{
    const s=getStatoMezzo(t);
    if(s==='disponibile') nDisp++;
    else if(s==='noleggiato') nNol++;
    else if(s==='officina') nOff++;
  });
  // Rientri previsti oggi = movimenti aperti con dataOut <= oggi (in ritardo o uscita oggi)
  // + movimenti con rientro atteso oggi (non abbiamo campo rientro previsto → mostriamo aperti)
  nRientri = movimenti.filter(m=>!m.rientro&&m.dataOut===todayStr).length;
  // Scadenze urgenti (scadute o entro 30gg)
  targas.forEach(t=>{
    const dates=allDatesForVehicle(t);
    dates.forEach(d=>{ if(st(d)!=='ok') nScadUrgenti++; });
  });

  // Sidebar badges
  const nbScad=document.getElementById('nb-scad');
  const nbMov=document.getElementById('nb-mov');
  const tbAlerts=document.getElementById('tb-alerts');
  if(nbScad){nbScad.textContent=nScadUrgenti;nbScad.style.display=nScadUrgenti>0?'':'none';}
  const movAperti=movimenti.filter(m=>!m.rientro).length;
  // Anche contratti in scadenza entro 30gg
  const contrScad=movimenti.filter(function(m){
    if(!m.contratto||!m.contratto.dataFine) return false;
    const diff=Math.round((new Date(m.contratto.dataFine)-today)/86400000);
    return diff>=0&&diff<=30;
  }).length;
  if(nbMov){
    const totBadge=movAperti+contrScad;
    nbMov.textContent=totBadge;
    nbMov.style.display=totBadge>0?'':'none';
  }
  if(tbAlerts){tbAlerts.style.display=nScadUrgenti>0?'':'none';tbAlerts.textContent=`⚠️ ${nScadUrgenti} scadenze`;}

  document.getElementById('kpi-disponibili').textContent=nDisp;
  document.getElementById('kpi-noleggiati').textContent=nNol;
  document.getElementById('kpi-officina').textContent=nOff;
  document.getElementById('kpi-rientri').textContent=nRientri;
  document.getElementById('kpi-scadenze').textContent=nScadUrgenti;

  // ── STATO FLOTTA LIVE ────────────────────
  const fleetEl=document.getElementById('dash-fleet');
  if(!targas.length){ fleetEl.innerHTML='<div style="color:#bbb;font-size:13px">Nessun mezzo</div>'; }
  else {
    fleetEl.innerHTML=targas.map(t=>{
      const v=vehicles[t];
      const s=getStatoMezzo(t);
      const cls={'disponibile':'fc-disponibile','noleggiato':'fc-noleggiato','officina':'fc-officina','prenotato':'fc-prenotato'}[s]||'fc-fuori';
      const lbl={'disponibile':'Disponibile','noleggiato':'Noleggiato','officina':'Officina','prenotato':'Prenotato','fuori_servizio':'Fuori servizio'}[s]||s;
      const icon=ICON[v.tipo]||'🚘';
      return `<div class="fleet-card ${cls}" onclick="switchMain('scadenze')" title="${t} — ${lbl}">
        <span class="fc-icon">${icon}</span>
        <span class="fc-plate">${t}</span>
        <span class="fc-stato">${lbl}</span>
      </div>`;
    }).join('');
  }

  // ── ALERT SCADENZE ───────────────────────
  const alertEl=document.getElementById('dash-alerts');
  let alerts=[];
  targas.forEach(t=>{
    const allD=items.filter(i=>i.targa===t);
    const v=vehicles[t];
    if(v.scadFor) allD.push({targa:t,cat:'Contratto fornitore',date:v.scadFor});
    if(v.scadCli) allD.push({targa:t,cat:'Contratto cliente',date:v.scadCli});
    allD.forEach(i=>{
      const s=st(i.date);
      if(s!=='ok'){
        const diff=Math.round((new Date(i.date)-today)/86400000);
        alerts.push({targa:t,cat:i.cat,date:i.date,stato:s,diff});
      }
    });
  });
  alerts.sort((a,b)=>a.diff-b.diff);
  if(!alerts.length){
    alertEl.innerHTML='<div style="color:#bbb;font-size:13px;padding:8px 0">✅ Nessuna scadenza urgente</div>';
  } else {
    alertEl.innerHTML=alerts.slice(0,8).map(a=>{
      const daysLbl=a.diff<0?`Scaduto ${Math.abs(a.diff)}gg fa`:(a.diff===0?'Scade oggi':`Tra ${a.diff} giorni`);
      return `<div class="alert-item ${a.stato}">
        <div class="alert-dot ${a.stato}"></div>
        <div class="alert-info">
          <span class="alert-targa">${a.targa}</span>
          <span style="color:#666;margin-left:6px">${a.cat}</span>
        </div>
        <span class="alert-days ${a.stato}">${daysLbl}</span>
      </div>`;
    }).join('');
  }

  // ── RIENTRI PREVISTI OGGI ────────────────
  const rientriEl=document.getElementById('dash-rientri');
  const aperti=movimenti.filter(m=>!m.rientro).sort((a,b)=>new Date(a.dataOut)-new Date(b.dataOut));
  if(!aperti.length){
    rientriEl.innerHTML='<div style="color:#bbb;font-size:13px;padding:8px 0">Nessun mezzo fuori</div>';
  } else {
    rientriEl.innerHTML=aperti.map(m=>{
      const v=vehicles[m.targa]||{};
      const dOut=new Date(m.dataOut);
      const diffOut=Math.round((today-dOut)/86400000);
      const isRitardo=diffOut>1;
      const icon=ICON[v.tipo]||'🚘';
      return `<div class="rientro-item ${isRitardo?'ritardo':''}">
        <span style="font-size:15px">${icon}</span>
        <div style="flex:1">
          <span style="font-weight:600;font-family:monospace">${m.targa}</span>
          ${m.conducente?`<span style="color:#666;margin-left:6px;font-size:11px">${m.conducente}</span>`:''}
          <div style="font-size:11px;color:#888;margin-top:1px">Uscita: ${fmt(m.dataOut)}</div>
        </div>
        <span style="font-size:11px;font-weight:600;${isRitardo?'color:#A32D2D':'color:#3B6D11'}">${isRitardo?`Ritardo ${diffOut}gg`:'Fuori oggi'}</span>
      </div>`;
    }).join('');
  }

  // ── ATTIVITÀ RECENTI ─────────────────────
  const actEl=document.getElementById('dash-activity');
  // Combina movimenti recenti + scadenze recenti aggiunte
  let activities=[];
  [...movimenti].sort((a,b)=>new Date(b.dataOut)-new Date(a.dataOut)).slice(0,4).forEach(m=>{
    const v=vehicles[m.targa]||{};
    activities.push({
      icon: m.rientro?'🏁':'🚗',
      text: `<strong>${m.targa}</strong> ${m.rientro?'rientro':'uscita'}${m.conducente?' — '+m.conducente:''}`,
      time: fmt(m.rientro?m.rientro.dataIn:m.dataOut)
    });
  });
  // Aggiungi ultime scadenze inserite
  [...items].sort((a,b)=>b.id-a.id).slice(0,3).forEach(i=>{
    activities.push({
      icon:'📋',
      text:`<strong>${i.targa}</strong> ${i.cat} aggiunta`,
      time: fmt(i.date)
    });
  });
  activities=activities.slice(0,7);
  if(!activities.length){
    actEl.innerHTML='<div style="color:#bbb;font-size:13px;padding:8px 0">Nessuna attività recente</div>';
  } else {
    actEl.innerHTML=activities.map(a=>`
      <div class="activity-item">
        <span class="activity-icon">${a.icon}</span>
        <div class="activity-info">${a.text}</div>
        <span class="activity-time">${a.time}</span>
      </div>`).join('');
  }

  // ── Garage preview ─────────────────────────
  const garPrev=document.getElementById('dash-garage-preview');
  if(garPrev){
    const aperti=interventi.filter(i=>i.stato!=='completato').sort((a,b)=>new Date(a.dataIn)-new Date(b.dataIn)).slice(0,4);
    if(!aperti.length){
      garPrev.innerHTML='<div style="color:#bbb;font-size:13px;padding:4px 0">✅ Nessun intervento aperto</div>';
    } else {
      garPrev.innerHTML=aperti.map(i=>`
        <div class="activity-item" style="cursor:pointer" onclick="switchMain('garage');setTimeout(()=>openSchedaVeicolo(''+i.targa,'manutenzioni'),200)">
          <span class="activity-icon">${TIPO_ICONS[i.tipo]||'🔧'}</span>
          <div class="activity-info"><strong>${i.targa}</strong> — ${i.tipo}<div style="font-size:11px;color:#888">${STATO_LABELS[i.stato]}</div></div>
          <span class="activity-time">${fmt(i.dataIn)}</span>
        </div>`).join('');
    }
  }

  // ── Sinistri preview ────────────────────────
  const sinPrev=document.getElementById('dash-sinistri-preview');
  if(sinPrev){
    const apertiSin=sinistri.filter(s=>s.stato==='aperto'||s.stato==='in_gestione').sort((a,b)=>new Date(b.data)-new Date(a.data)).slice(0,4);
    if(!apertiSin.length){
      sinPrev.innerHTML='<div style="color:#bbb;font-size:13px;padding:4px 0">✅ Nessun sinistro aperto</div>';
    } else {
      sinPrev.innerHTML=apertiSin.map(s=>`
        <div class="activity-item" style="cursor:pointer" onclick="switchMain('sinistri')">
          <span class="activity-icon">⚠️</span>
          <div class="activity-info"><strong>${s.targa}</strong> — ${(s.desc||'').slice(0,45)}…<div style="font-size:11px;color:#888">${SIN_LABELS[s.stato]}</div></div>
          <span class="activity-time">${fmt(s.data)}</span>
        </div>`).join('');
    }
  }
}


// ════════════════════════════════════════════
// MODULO CLIENTI
// ════════════════════════════════════════════

function getInitials(nome){
  return nome.split(' ').map(w=>w[0]||'').join('').toUpperCase().slice(0,2)||'?';
}

function clienteIsAttivo(c){
  // Attivo = ha almeno un movimento come conducente o collegato a mezzo noleggio
  const nomeLC=(c.nome||'').toLowerCase();
  const azLC=(c.azienda||'').toLowerCase();
  // Controlla per aziendaId (collegamento diretto wizard)
  if(movimenti.some(function(m){return m.aziendaId&&m.aziendaId===c.id;})) return true;
  return movimenti.some(function(m){
    const cond=(m.conducente||'').toLowerCase();
    return cond===nomeLC||cond.includes(nomeLC)||(azLC&&cond.includes(azLC));
  })||Object.values(vehicles).some(function(v){
    const vCli=(v.cliente||'').toLowerCase();
    return vCli===azLC||vCli===nomeLC;
  });
}

function docScaduto(c){
  const oggi=today.toISOString().slice(0,10);
  if(c.scadDoc && c.scadDoc < oggi) return true;
  if(c.scadPatente && c.scadPatente < oggi) return true;
  return false;
}

function renderClienti(){
  if(!loaded) return;
  const q=(document.getElementById('cli-search')||{value:''}).value.toLowerCase();
  const f=(document.getElementById('cli-filter')||{value:'all'}).value;

  const tot=clienti.length;
  const att=clienti.filter(c=>clienteIsAttivo(c)&&!c.blacklist).length;
  const bl=clienti.filter(c=>c.blacklist).length;
  const doc=clienti.filter(c=>docScaduto(c)).length;

  const setEl=(id,v)=>{ const el=document.getElementById(id); if(el) el.textContent=v; };
  setEl('cli-cnt-tot',tot); setEl('cli-cnt-att',att); setEl('cli-cnt-bl',bl); setEl('cli-cnt-doc',doc);

  // Sidebar blacklist badge
  const nbBl=document.getElementById('nb-cli-bl');
  if(nbBl){nbBl.textContent=bl;nbBl.style.display=bl>0?'':'none';}

  const filtered=clienti.filter(c=>{
    if(f==='blacklist'&&!c.blacklist) return false;
    if(f==='attivo'&&(c.blacklist||!clienteIsAttivo(c))) return false;
    if(q&&!(c.nome||'').toLowerCase().includes(q)&&!(c.azienda||'').toLowerCase().includes(q)&&!(c.tel||'').toLowerCase().includes(q)&&!(c.email||'').toLowerCase().includes(q)) return false;
    return true;
  });

  const countEl=document.getElementById('cli-count-lbl');
  if(countEl) countEl.textContent=filtered.length!==tot?`${filtered.length} di ${tot} clienti`:`${tot} clienti`;

  const listEl=document.getElementById('cli-list');
  if(!listEl) return;
  if(!filtered.length){ listEl.innerHTML='<div class="empty">Nessun cliente trovato</div>'; return; }

  listEl.innerHTML=filtered.map(c=>{
    const attivo=clienteIsAttivo(c)&&!c.blacklist;
    const docExp=docScaduto(c);
    // Count movimenti
    const nomeLc=(c.nome||'').toLowerCase();
    const azLc=(c.azienda||'').toLowerCase();
    // Conta per aziendaId (collegamento wizard) O per nome/azienda nel conducente
    const nMov=movimenti.filter(function(m){
      if(m.aziendaId&&m.aziendaId===c.id) return true;
      const cond=(m.conducente||'').toLowerCase();
      return cond.includes(nomeLc)||(azLc&&cond.includes(azLc));
    }).length;
    return `<div class="cliente-card" onclick="showDetailCliente(${c.id})">
      <div class="cliente-card-header">
        <div class="cliente-avatar">${getInitials(c.nome)}</div>
        <div style="flex:1;min-width:0">
          <div class="cliente-nome">${c.nome||'—'}</div>
          ${c.azienda?`<div class="cliente-azienda">${c.azienda}</div>`:''}
        </div>
      </div>
      <div class="cliente-tags">
        ${c.blacklist?'<span class="tag tag-blacklist">🚫 Blacklist</span>':''}
        ${attivo?'<span class="tag tag-attivo">✓ Attivo</span>':'<span class="tag tag-inattivo">Inattivo</span>'}
        ${docExp?'<span class="tag" style="background:#FAEEDA;color:#854F0B;border:0.5px solid #F5D49A">⚠️ Doc. scaduto</span>':''}
      </div>
      <div class="cliente-contacts">
        ${c.tel?`<span>📞 <a href="tel:${c.tel}" onclick="event.stopPropagation()">${c.tel}</a></span>`:''}
        ${c.email?`<span>✉️ <a href="mailto:${c.email}" onclick="event.stopPropagation()">${c.email}</a></span>`:''}
      </div>
      <div class="cliente-stats-row">
        <div class="cliente-stat"><span class="cliente-stat-val">${nMov}</span><span class="cliente-stat-lbl">Noleggi</span></div>
        <div class="cliente-stat"><span class="cliente-stat-val">${c.piva?'✓':'—'}</span><span class="cliente-stat-lbl">P.IVA</span></div>
        <div class="cliente-stat"><span class="cliente-stat-val">${c.patente?'✓':'—'}</span><span class="cliente-stat-lbl">Patente</span></div>
      </div>
      <div class="cliente-actions">
        <button class="edit-v-btn" onclick="event.stopPropagation();editCliente(${c.id})" title="Modifica">✏️</button>
      </div>
    </div>`;
  }).join('');
}

function showDetailCliente(id){
  const c=clienti.find(x=>x.id===id);
  if(!c) return;
  const detEl=document.getElementById('cli-detail');
  if(!detEl) return;

  const nomeLc=(c.nome||'').toLowerCase();
  const azIdLc=c.id;
  const movCliente=movimenti.filter(function(m){
    if(m.aziendaId&&m.aziendaId===azIdLc) return true;
    return (m.conducente||'').toLowerCase().includes(nomeLc);
  });
  const docExp=docScaduto(c);

  const storicoHtml=movCliente.length
    ? movCliente.sort((a,b)=>new Date(b.dataOut)-new Date(a.dataOut)).map(m=>{
        const v=vehicles[m.targa]||{};
        return `<div class="storico-item">
          <span class="storico-icon">${ICON[v.tipo]||'🚘'}</span>
          <div class="storico-info">
            <strong>${m.targa}</strong> ${v.tipo||''} — ${m.rientro?'Completato':'In corso'}
          </div>
          <span class="storico-date">${fmt(m.dataOut)}</span>
        </div>`;
      }).join('')
    : '<div style="color:#bbb;font-size:13px;padding:8px 0">Nessun noleggio registrato</div>';

  detEl.innerHTML=`
    <div class="detail-panel">
      <div class="detail-header">
        <div class="detail-avatar">${getInitials(c.nome)}</div>
        <div class="detail-title">
          <div class="detail-name">${c.nome||'—'} ${c.blacklist?'<span class="tag tag-blacklist">🚫 Blacklist</span>':''}</div>
          <div class="detail-sub">${c.azienda||'Cliente privato'}</div>
        </div>
        <button class="edit-v-btn" onclick="editCliente(${c.id})">✏️ Modifica</button>
        <button onclick="document.getElementById('cli-detail').style.display='none'" style="height:auto;padding:3px 8px;font-size:12px">✕</button>
      </div>
      <div class="detail-grid">
        <div class="detail-field"><span class="detail-label">Telefono</span><span class="detail-value">${c.tel?`<a href="tel:${c.tel}" style="color:#185FA5">${c.tel}</a>`:'—'}</span></div>
        <div class="detail-field"><span class="detail-label">Email</span><span class="detail-value">${c.email?`<a href="mailto:${c.email}" style="color:#185FA5">${c.email}</a>`:'—'}</span></div>
        <div class="detail-field"><span class="detail-label">P.IVA / C.F.</span><span class="detail-value">${c.piva||'—'}</span></div>
        <div class="detail-field"><span class="detail-label">Indirizzo</span><span class="detail-value">${c.indirizzo||'—'}</span></div>
        <div class="detail-field"><span class="detail-label">N° patente</span><span class="detail-value">${c.patente||'—'}</span></div>
        <div class="detail-field"><span class="detail-label">Scad. patente</span><span class="detail-value" style="${c.scadPatente&&c.scadPatente<today.toISOString().slice(0,10)?'color:#A32D2D;font-weight:600':''}">${c.scadPatente?fmt(c.scadPatente):'—'}</span></div>
        <div class="detail-field"><span class="detail-label">Documento</span><span class="detail-value">${c.tipoDoc||'—'} ${c.nDoc?'#'+c.nDoc:''}</span></div>
        <div class="detail-field"><span class="detail-label">Scad. documento</span><span class="detail-value" style="${c.scadDoc&&c.scadDoc<today.toISOString().slice(0,10)?'color:#A32D2D;font-weight:600':''}">${c.scadDoc?fmt(c.scadDoc):'—'}</span></div>
      </div>
      ${c.note?`<div style="background:#f5f4f0;border-radius:8px;padding:10px 12px;font-size:13px;margin-bottom:1rem"><span style="font-size:11px;color:#aaa;font-weight:600;text-transform:uppercase;letter-spacing:.04em">Note interne</span><p style="margin-top:4px;color:#444">${c.note}</p></div>`:''}
      ${c.blacklist&&c.motivoBl?`<div style="background:#FCEBEB;border:0.5px solid #F7C1C1;border-radius:8px;padding:10px 12px;font-size:13px;margin-bottom:1rem"><span style="font-size:11px;color:#A32D2D;font-weight:600;text-transform:uppercase">🚫 Motivo blacklist</span><p style="margin-top:4px;color:#A32D2D">${c.motivoBl}</p></div>`:''}
      <div class="dash-panel-title" style="margin-bottom:8px"><span>🚗</span> Storico noleggi (${movCliente.length})</div>
      <div class="storico-list">${storicoHtml}</div>
    </div>`;

  detEl.style.display='block';
  detEl.scrollIntoView({behavior:'smooth',block:'start'});
}

function showFormCliente(){
  document.getElementById('cf-editing-id').value='';
  document.getElementById('cli-form-title').textContent='Nuovo cliente';
  document.getElementById('cli-form-icon').textContent='👤';
  document.getElementById('cf-delete-btn').style.display='none';
  ['cf-nome','cf-azienda','cf-tel','cf-email','cf-piva','cf-indirizzo','cf-patente','cf-ndoc','cf-note','cf-motivo-bl'].forEach(id=>{const el=document.getElementById(id);if(el)el.value='';});
  ['cf-scad-patente','cf-scad-doc'].forEach(id=>{const el=document.getElementById(id);if(el)el.value='';});
  document.getElementById('cf-tipo-doc').value='';
  document.getElementById('cf-blacklist').checked=false;
  document.getElementById('cf-blacklist-wrap').style.display='none';
  document.getElementById('cli-form').style.display='block';
  document.getElementById('cli-form').scrollIntoView({behavior:'smooth',block:'start'});
}

function hideFormCliente(){
  document.getElementById('cli-form').style.display='none';
}

function editCliente(id){
  const c=clienti.find(x=>x.id===id);
  if(!c) return;
  showFormCliente();
  document.getElementById('cf-editing-id').value=id;
  document.getElementById('cli-form-title').textContent='Modifica cliente';
  document.getElementById('cf-delete-btn').style.display='';
  document.getElementById('cf-nome').value=c.nome||'';
  document.getElementById('cf-azienda').value=c.azienda||'';
  document.getElementById('cf-tel').value=c.tel||'';
  document.getElementById('cf-email').value=c.email||'';
  document.getElementById('cf-piva').value=c.piva||'';
  document.getElementById('cf-indirizzo').value=c.indirizzo||'';
  document.getElementById('cf-patente').value=c.patente||'';
  document.getElementById('cf-scad-patente').value=c.scadPatente||'';
  document.getElementById('cf-tipo-doc').value=c.tipoDoc||'';
  document.getElementById('cf-ndoc').value=c.nDoc||'';
  document.getElementById('cf-scad-doc').value=c.scadDoc||'';
  document.getElementById('cf-note').value=c.note||'';
  document.getElementById('cf-blacklist').checked=!!c.blacklist;
  document.getElementById('cf-blacklist-wrap').style.display=c.blacklist?'block':'none';
  document.getElementById('cf-motivo-bl').value=c.motivoBl||'';
}

function saveCliente(){
  const nome=document.getElementById('cf-nome').value.trim();
  if(!nome){ document.getElementById('cf-nome').focus(); toast('Inserisci il nome'); return; }
  const editId=document.getElementById('cf-editing-id').value;
  const isBlacklist=document.getElementById('cf-blacklist').checked;
  const obj={
    nome, azienda:document.getElementById('cf-azienda').value.trim(),
    tel:document.getElementById('cf-tel').value.trim(),
    email:document.getElementById('cf-email').value.trim(),
    piva:document.getElementById('cf-piva').value.trim(),
    indirizzo:document.getElementById('cf-indirizzo').value.trim(),
    patente:document.getElementById('cf-patente').value.trim(),
    scadPatente:document.getElementById('cf-scad-patente').value,
    tipoDoc:document.getElementById('cf-tipo-doc').value,
    nDoc:document.getElementById('cf-ndoc').value.trim(),
    scadDoc:document.getElementById('cf-scad-doc').value,
    note:document.getElementById('cf-note').value.trim(),
    blacklist:isBlacklist,
    motivoBl:isBlacklist?document.getElementById('cf-motivo-bl').value.trim():'',
  };
  if(editId){
    const idx=clienti.findIndex(c=>c.id===parseInt(editId));
    if(idx>=0){ obj.id=parseInt(editId); clienti[idx]=obj; }
  } else {
    obj.id=nextCliId++;
    clienti.push(obj);
  }
  save();
  hideFormCliente();
  renderClienti();
  toast(editId?'Cliente aggiornato':'Cliente aggiunto');
}

function deleteCliente(){
  const editId=document.getElementById('cf-editing-id').value;
  if(!editId) return;
  const c=clienti.find(x=>x.id===parseInt(editId));
  if(!c||!confirm('Eliminare il cliente '+c.nome+'?')) return;
  clienti=clienti.filter(x=>x.id!==parseInt(editId));
  save();
  hideFormCliente();
  renderClienti();
  toast('Cliente eliminato');
}

// Toggle blacklist reason field
document.addEventListener('change', function(e){
  if(e.target.id==='cf-blacklist'){
    document.getElementById('cf-blacklist-wrap').style.display=e.target.checked?'block':'none';
  }
});


// ════════════════════════════════════════════
// MODULO GARAGE / OFFICINA
// ════════════════════════════════════════════

function populateGarTargaSelect(){
  const targas=Object.keys(vehicles);
  const opts='<option value="">— seleziona —</option>'+targas.map(t=>`<option value="${t}">${t} — ${vehicles[t].tipo}</option>`).join('');
  const fopts='<option value="all">Tutti i mezzi</option>'+targas.map(t=>`<option value="${t}">${t}</option>`).join('');
  ['gf-targa'].forEach(id=>{const el=document.getElementById(id);if(el)el.innerHTML=opts;});
  ['gar-filter-targa'].forEach(id=>{const el=document.getElementById(id);if(el)el.innerHTML=fopts;});
}

function selectStatoGar(stato){
  document.querySelectorAll('#gf-stato-selector .stato-btn').forEach(b=>{
    b.classList.toggle('selected', b.dataset.stato===stato);
  });
  document.getElementById('gf-stato').value=stato;
}

function renderGarage(){
  if(!loaded) return;
  const q=(document.getElementById('gar-search')||{value:''}).value.toLowerCase();
  const fs=(document.getElementById('gar-filter-stato-v')||{value:'all'}).value;

  // KPI interventi
  const tot=interventi.length;
  const open=interventi.filter(i=>i.stato==='aperto'||i.stato==='in_corso').length;
  const att=interventi.filter(i=>i.stato==='attesa').length;
  const done=interventi.filter(i=>i.stato==='completato').length;
  const setEl=(id,v)=>{const el=document.getElementById(id);if(el)el.textContent=v;};
  setEl('gar-cnt-tot',tot); setEl('gar-cnt-open',open); setEl('gar-cnt-att',att); setEl('gar-cnt-done',done);

  // Sidebar badge
  const nbGar=document.getElementById('nb-gar');
  if(nbGar){nbGar.textContent=open+att; nbGar.style.display=(open+att)>0?'':'none';}

  // Alert automazioni
  const alertEl=document.getElementById('gar-alerts');
  if(alertEl){
    const tecnici=['Revisione','Tagliando','Assicurazione','Bollo','Tachigrafo','Leasing','Licenza','Permesso'];
    let autoAlerts=[];
    Object.keys(vehicles).forEach(targa=>{
      items.filter(i=>i.targa===targa&&tecnici.includes(i.cat)).forEach(i=>{
        const s=st(i.date);
        if(s!=='ok'){
          const diff=Math.round((new Date(i.date)-today)/86400000);
          autoAlerts.push({targa,cat:i.cat,date:i.date,stato:s,diff});
        }
      });
    });
    autoAlerts.sort((a,b)=>a.diff-b.diff);
    if(!autoAlerts.length){
      alertEl.innerHTML='<div style="background:#EAF3DE;border:.5px solid #C0DD97;border-radius:10px;padding:10px 14px;font-size:12px;color:#3B6D11;display:flex;align-items:center;gap:8px"><span style="font-size:16px">✅</span> Nessuna scadenza tecnica urgente</div>';
    } else {
      alertEl.innerHTML=autoAlerts.slice(0,6).map(a=>{
        const icon={Revisione:'🔍',Tagliando:'🔩',Assicurazione:'📄',Bollo:'💳'}[a.cat]||'⚠️';
        const daysLbl=a.diff<0?`Scaduto ${Math.abs(a.diff)}gg fa`:(a.diff===0?'Scade oggi':`Tra ${a.diff}gg`);
        return `<div class="auto-alert-card ${a.stato}" onclick="switchMain('scadenze')">
          <span class="auto-alert-icon">${icon}</span>
          <div class="auto-alert-info">
            <div class="auto-alert-title">${a.targa} — ${a.cat}</div>
            <div class="auto-alert-sub">${fmt(a.date)}</div>
          </div>
          <span class="auto-alert-days ${a.stato}">${daysLbl}</span>
        </div>`;
      }).join('');
    }
  }

  // Filtra veicoli
  const targas=Object.keys(vehicles).filter(t=>{
    const v=vehicles[t];
    const stato=getStatoMezzo(t);
    if(fs!=='all'&&stato!==fs) return false;
    if(q&&!t.toLowerCase().includes(q)&&!(v.marca||'').toLowerCase().includes(q)&&!(v.modello||'').toLowerCase().includes(q)&&!(v.tipo||'').toLowerCase().includes(q)) return false;
    return true;
  });

  // Render card o tabella
  renderFleetCards(targas);
  renderFleetTable(targas);
  renderKanban();
}

let _garView='card';
function setGarView(v){
  _garView=v;
  document.getElementById('vtb-card').classList.toggle('active',v==='card');
  document.getElementById('vtb-table').classList.toggle('active',v==='table');
  document.getElementById('gar-fleet-cards').style.display=v==='card'?'':'none';
  document.getElementById('gar-fleet-table').style.display=v==='table'?'':'none';
}

function getVehAlerts(targa){
  const alerts=[];
  items.filter(i=>i.targa===targa).forEach(i=>{
    const s=st(i.date);
    if(s!=='ok') alerts.push({cat:i.cat,stato:s});
  });
  return alerts;
}

function renderFleetCards(targas){
  const el=document.getElementById('gar-fleet-cards');
  if(!el) return;
  if(!targas.length){el.innerHTML='<div class="empty">Nessun veicolo trovato</div>';return;}
  el.innerHTML=targas.map(t=>{
    const v=vehicles[t];
    const stato=getStatoMezzo(t);
    const alerts=getVehAlerts(t);
    const intAperti=interventi.filter(i=>i.targa===t&&i.stato!=='completato').length;
    const modello=[(v.marca||''),(v.modello||'')].filter(Boolean).join(' ')||(v.tipo||'—');
    return `<div class="veh-card vc-${stato}" onclick="openSchedaVeicolo('${t}')">
      <div class="veh-card-top">
        <span class="veh-icon">${ICON[v.tipo]||'🚘'}</span>
        <div class="veh-title">
          <span class="veh-targa">${t}</span>
          <div class="veh-modello">${modello}</div>
          <div class="veh-tipo-badge">${v.tipo||''} ${v.anno?'· '+v.anno:''}</div>
        </div>
        <span class="veh-stato-badge vsb-${stato}">${{disponibile:'✓ Disponibile',officina:'🔧 Officina',noleggiato:'🔑 Noleggiato',prenotato:'📅 Prenotato',fuori_servizio:'⛔ Fuori servizio'}[stato]||stato}</span>
      </div>
      <div class="veh-info-grid">
        <div class="veh-info-item"><span>KM</span><span class="veh-info-val">${v.km?Number(v.km).toLocaleString('it-IT')+' km':'—'}</span></div>
        <div class="veh-info-item"><span>Sede</span><span class="veh-info-val">${v.sede||'—'}</span></div>
        <div class="veh-info-item"><span>Alimentazione</span><span class="veh-info-val">${v.alimentazione||'—'}</span></div>
        <div class="veh-info-item"><span>Interventi aperti</span><span class="veh-info-val" style="${intAperti>0?'color:#CC5200':'color:#3B6D11'}">${intAperti>0?intAperti+' aperti':'OK'}</span></div>
      </div>
      ${alerts.length?`<div class="veh-alerts">${alerts.slice(0,3).map(a=>`<span class="veh-alert-pill vap-${a.stato}">${a.cat}</span>`).join('')}${alerts.length>3?`<span class="veh-alert-pill vap-scaduto">+${alerts.length-3}</span>`:''}</div>`:''}
      <div class="veh-card-actions">
        <button class="edit-v-btn" onclick="event.stopPropagation();showFormGarage('${t}')" title="Nuovo intervento">+ Interv.</button>
      </div>
    </div>`;
  }).join('');
}

function renderFleetTable(targas){
  const tbody=document.getElementById('gar-fleet-tbody');
  if(!tbody) return;
  if(!targas.length){tbody.innerHTML='<tr><td colspan="9" class="empty">Nessun veicolo</td></tr>';return;}
  tbody.innerHTML=targas.map(t=>{
    const v=vehicles[t];
    const stato=getStatoMezzo(t);
    const intAperti=interventi.filter(i=>i.targa===t&&i.stato!=='completato').length;
    const modello=[(v.marca||''),(v.modello||'')].filter(Boolean).join(' ')||v.tipo;
    // Scadenza revisione e assicurazione
    const rev=items.find(i=>i.targa===t&&i.cat==='Revisione');
    const ass=items.find(i=>i.targa===t&&i.cat==='Assicurazione');
    const scadBadge=(item)=>item?`<span class="doc-scad-badge dsb-${st(item.date)}">${lbl(item.date)}</span>`:'<span style="color:#bbb">—</span>';
    return `<tr onclick="openSchedaVeicolo('${t}')">
      <td><span style="font-family:monospace;font-weight:700">${t}</span></td>
      <td><strong>${modello}</strong><div style="font-size:11px;color:#888">${v.anno||''}</div></td>
      <td>${ICON[v.tipo]||''} ${v.tipo}</td>
      <td><span class="veh-stato-badge vsb-${stato}">${{disponibile:'✓ Disp.',officina:'🔧 Off.',noleggiato:'🔑 Nol.',prenotato:'📅 Pren.',fuori_servizio:'⛔ F.S.'}[stato]||stato}</span></td>
      <td>${v.km?Number(v.km).toLocaleString('it-IT')+' km':'—'}</td>
      <td>${v.sede||'—'}</td>
      <td>${scadBadge(rev)}</td>
      <td>${scadBadge(ass)}</td>
      <td>${intAperti>0?`<span style="color:#CC5200;font-weight:600">${intAperti}</span>`:'<span style="color:#3B6D11">0</span>'}</td>
    </tr>`;
  }).join('');
}

function renderKanban(){
  const ft=(document.getElementById('gar-filter-targa')||{value:'all'}).value;
  const fs=(document.getElementById('gar-filter-stato')||{value:'all'}).value;
  const filtered=interventi.filter(i=>{
    if(ft!=='all'&&i.targa!==ft) return false;
    if(fs!=='all'&&i.stato!==fs) return false;
    return true;
  });
  const states=['aperto','in_corso','attesa','completato'];
  states.forEach(s=>{
    const cards=filtered.filter(i=>i.stato===s).sort((a,b)=>new Date(b.dataIn)-new Date(a.dataIn));
    const cntEl=document.getElementById('kc-'+s);
    const listEl=document.getElementById('kc-cards-'+s);
    if(cntEl) cntEl.textContent=cards.length;
    if(!listEl) return;
    if(!cards.length){listEl.innerHTML='<div style="font-size:11px;color:#bbb;text-align:center;padding:12px 0">Nessuno</div>';return;}
    listEl.innerHTML=cards.map(i=>{
      const v=vehicles[i.targa]||{};
      const icon=TIPO_ICONS[i.tipo]||'🔧';
      const isOverdue=i.dataPrev&&!i.dataOut&&i.dataPrev<today.toISOString().slice(0,10);
      return `<div class="maint-card" onclick="openSchedaVeicolo('${i.targa}','manutenzioni')">
        <div class="maint-card-top">
          <span class="maint-card-targa">${i.targa}</span>
          <span class="maint-card-tipo">${icon} ${i.tipo}</span>
          <span class="maint-card-data">${fmt(i.dataIn)}</span>
        </div>
        <div class="maint-card-desc">${(i.desc||'').slice(0,80)}${(i.desc||'').length>80?'…':''}</div>
        <div class="maint-card-footer">
          <span class="maint-badge mb-${i.stato}">${STATO_LABELS[i.stato]}</span>
          <span class="maint-priority mp-${i.priorita}">${i.priorita.charAt(0).toUpperCase()+i.priorita.slice(1)}</span>
          ${isOverdue?'<span style="font-size:10px;color:#A32D2D;font-weight:600;margin-left:auto">⚠️ In ritardo</span>':''}
        </div>
      </div>`;
    }).join('');
  });
}


function showDetailIntervento(id){
  const i=interventi.find(x=>x.id===id);
  if(!i) return;
  const v=vehicles[i.targa]||{};
  // Usa off-detail se officina attiva, gar-detail altrimenti
  const offActive=document.getElementById('page-officina').classList.contains('active');
  const detId=offActive?'off-detail':'gar-detail';
  const detEl=document.getElementById(detId);
  if(!detEl) return;
  const isOverdue=i.dataPrev&&!i.dataOut&&i.dataPrev<today.toISOString().slice(0,10);
  detEl.innerHTML=`
    <div class="maint-detail">
      <div class="maint-detail-header">
        <div style="font-size:28px">${TIPO_ICONS[i.tipo]||'🔧'}</div>
        <div style="flex:1">
          <div style="font-size:16px;font-weight:700">${i.tipo} — <span style="font-family:monospace">${i.targa}</span></div>
          <div style="font-size:12px;color:#888;margin-top:2px">${v.tipo||''} ${i.officina?'· '+i.officina:''}</div>
        </div>
        <span class="maint-badge mb-${i.stato}" style="font-size:12px;padding:4px 10px">${STATO_LABELS[i.stato]}</span>
        <button class="edit-v-btn" onclick="editIntervento(${i.id})">✏️ Modifica</button>
        <button onclick="document.getElementById('gar-detail').style.display='none'" style="height:auto;padding:3px 8px;font-size:12px">✕</button>
      </div>
      <div style="display:grid;grid-template-columns:1fr 1fr 1fr 1fr;gap:10px 20px;font-size:13px;margin-bottom:1rem">
        <div class="detail-field"><span class="detail-label">Apertura</span><span class="detail-value">${fmt(i.dataIn)}</span></div>
        <div class="detail-field"><span class="detail-label">Prevista chiusura</span><span class="detail-value" style="${isOverdue?'color:#A32D2D;font-weight:600':''}">${fmt(i.dataPrev)||'—'}${isOverdue?' ⚠️':''}</span></div>
        <div class="detail-field"><span class="detail-label">Chiusura effettiva</span><span class="detail-value">${fmt(i.dataOut)||'—'}</span></div>
        <div class="detail-field"><span class="detail-label">KM</span><span class="detail-value">${i.km?Number(i.km).toLocaleString('it-IT')+' km':'—'}</span></div>
      </div>
      <div style="background:#f5f4f0;border-radius:8px;padding:10px 14px;margin-bottom:10px">
        <div class="detail-label" style="margin-bottom:4px">Descrizione intervento</div>
        <div style="font-size:13px;color:#333;line-height:1.5">${i.desc||'—'}</div>
      </div>
      ${i.note?`<div style="background:#f5f4f0;border-radius:8px;padding:10px 14px;margin-bottom:10px"><div class="detail-label" style="margin-bottom:4px">Note interne</div><div style="font-size:13px;color:#555;line-height:1.5">${i.note}</div></div>`:''}
      <div style="display:flex;gap:8px;flex-wrap:wrap">
        ${['aperto','in_corso','attesa','completato'].map(s=>
          `<button class="stato-btn${i.stato===s?' selected':''}" data-stato="${s}" onclick="cambiaStatoIntervento(${i.id},'${s}')">${{aperto:'🟡 Aperto',in_corso:'🔵 In corso',attesa:'🟣 Attesa ricambi',completato:'🟢 Completato'}[s]}</button>`
        ).join('')}
      </div>
    </div>`;
  if(detEl){
    detEl.style.display='block';
    detEl.scrollIntoView({behavior:'smooth',block:'start'});
  }
}

function cambiaStatoIntervento(id,nuovoStato){
  const i=interventi.find(x=>x.id===id);
  if(!i) return;
  i.stato=nuovoStato;
  if(nuovoStato==='completato'&&!i.dataOut) i.dataOut=today.toISOString().slice(0,10);
  // Se mezzo in officina e ora completato → aggiorna statoOp
  const v=vehicles[i.targa];
  if(v){
    if(nuovoStato==='completato'&&v.statoOp==='officina') v.statoOp='disponibile';
    if((nuovoStato==='aperto'||nuovoStato==='in_corso'||nuovoStato==='attesa')) v.statoOp='officina';
  }
  save();
  renderGarage();
  if(document.getElementById('page-officina').classList.contains('active')) renderOfficina();
  showDetailIntervento(id);
  toast('Stato aggiornato: '+STATO_LABELS[nuovoStato]);
}

function showFormGarage(prefillTarga){
  document.getElementById('gf-editing-id').value='';
  document.getElementById('gar-form-title').textContent='Nuovo intervento';
  document.getElementById('gf-delete-btn').style.display='none';
  ['gf-km','gf-officina','gf-desc','gf-note'].forEach(id=>{const el=document.getElementById(id);if(el)el.value='';});
  ['gf-data-in','gf-data-prev','gf-data-out'].forEach(id=>{const el=document.getElementById(id);if(el)el.value='';});
  document.getElementById('gf-data-in').value=today.toISOString().slice(0,10);
  document.getElementById('gf-tipo').value='Tagliando';
  document.getElementById('gf-priorita').value='media';
  selectStatoGar('aperto');
  if(prefillTarga) document.getElementById('gf-targa').value=prefillTarga;
  else document.getElementById('gf-targa').value='';
  document.getElementById('gar-form').style.display='block';
  document.getElementById('gar-form').scrollIntoView({behavior:'smooth',block:'start'});
}

function hideFormGarage(){
  document.getElementById('gar-form').style.display='none';
}

function editIntervento(id){
  const i=interventi.find(x=>x.id===id);
  if(!i) return;
  showFormGarage();
  document.getElementById('gf-editing-id').value=id;
  document.getElementById('gar-form-title').textContent='Modifica intervento';
  document.getElementById('gf-delete-btn').style.display='';
  document.getElementById('gf-targa').value=i.targa||'';
  document.getElementById('gf-tipo').value=i.tipo||'Tagliando';
  document.getElementById('gf-priorita').value=i.priorita||'media';
  document.getElementById('gf-officina').value=i.officina||'';
  document.getElementById('gf-data-in').value=i.dataIn||'';
  document.getElementById('gf-data-prev').value=i.dataPrev||'';
  document.getElementById('gf-data-out').value=i.dataOut||'';
  document.getElementById('gf-km').value=i.km||'';
  document.getElementById('gf-desc').value=i.desc||'';
  document.getElementById('gf-note').value=i.note||'';
  selectStatoGar(i.stato||'aperto');
}

function saveIntervento(){
  const targa=document.getElementById('gf-targa').value;
  const desc=document.getElementById('gf-desc').value.trim();
  if(!targa){document.getElementById('gf-targa').focus();toast('Seleziona una targa');return;}
  if(!desc){document.getElementById('gf-desc').focus();toast('Inserisci la descrizione');return;}
  const editId=document.getElementById('gf-editing-id').value;
  const stato=document.getElementById('gf-stato').value;
  const obj={
    targa, tipo:document.getElementById('gf-tipo').value,
    priorita:document.getElementById('gf-priorita').value,
    officina:document.getElementById('gf-officina').value.trim(),
    dataIn:document.getElementById('gf-data-in').value,
    dataPrev:document.getElementById('gf-data-prev').value,
    dataOut:document.getElementById('gf-data-out').value,
    km:document.getElementById('gf-km').value,
    desc, note:document.getElementById('gf-note').value.trim(),
    stato,
  };
  // Aggiorna statoOp del mezzo
  const v=vehicles[targa];
  if(v){
    if(stato==='completato') { if(v.statoOp==='officina') v.statoOp='disponibile'; }
    else v.statoOp='officina';
  }
  if(editId){
    const idx=interventi.findIndex(x=>x.id===parseInt(editId));
    if(idx>=0){obj.id=parseInt(editId);interventi[idx]=obj;}
  } else {
    obj.id=nextIntId++;
    interventi.push(obj);
  }
  save();
  hideFormGarage();
  renderGarage();
  // Se la scheda del mezzo è aperta, aggiornala
  if(_scedaVeicoloTarga && _scedaVeicoloTarga===obj.targa){
    openSchedaVeicolo(_scedaVeicoloTarga,'manutenzioni');
  }
  toast(editId?'Intervento aggiornato':'Intervento aggiunto');
}

function deleteIntervento(){
  const editId=document.getElementById('gf-editing-id').value;
  if(!editId) return;
  const i=interventi.find(x=>x.id===parseInt(editId));
  if(!i||!confirm('Eliminare questo intervento?')) return;
  // Reset statoOp se era in officina per questo mezzo
  const v=vehicles[i.targa];
  if(v&&v.statoOp==='officina'){
    const altriAperti=interventi.filter(x=>x.id!==parseInt(editId)&&x.targa===i.targa&&x.stato!=='completato');
    if(!altriAperti.length) v.statoOp='disponibile';
  }
  interventi=interventi.filter(x=>x.id!==parseInt(editId));
  save();
  hideFormGarage();
  document.getElementById('gar-detail').style.display='none';
  renderGarage();
  toast('Intervento eliminato');
}


// ════════════════════════════════════════════
// MODULO SINISTRI
// ════════════════════════════════════════════


function populateSinTargaSelect(){
  const sel=document.getElementById('sf-targa');
  const fsel=document.getElementById('sin-filter-targa');
  const targas=Object.keys(vehicles);
  if(sel) sel.innerHTML='<option value="">— seleziona —</option>'+targas.map(t=>`<option value="${t}">${t} — ${vehicles[t].tipo}</option>`).join('');
  if(fsel) fsel.innerHTML='<option value="all">Tutti i mezzi</option>'+targas.map(t=>`<option value="${t}">${t}</option>`).join('');
}

function selectStatoSin(stato){
  document.querySelectorAll('#sf-stato-selector .sin-stato-btn').forEach(b=>{
    b.classList.toggle('selected', b.dataset.stato===stato);
  });
  document.getElementById('sf-stato').value=stato;
}

function renderSinistri(){
  if(!loaded) return;
  const q=(document.getElementById('sin-search')||{value:''}).value.toLowerCase();
  const fs=(document.getElementById('sin-filter-stato')||{value:'all'}).value;
  const ft=(document.getElementById('sin-filter-targa')||{value:'all'}).value;

  // KPI
  const tot=sinistri.length;
  const open=sinistri.filter(s=>s.stato==='aperto').length;
  const gest=sinistri.filter(s=>s.stato==='in_gestione').length;
  const closed=sinistri.filter(s=>s.stato==='chiuso').length;
  const setEl=(id,v)=>{const el=document.getElementById(id);if(el)el.textContent=v;};
  setEl('sin-cnt-tot',tot); setEl('sin-cnt-open',open); setEl('sin-cnt-gest',gest); setEl('sin-cnt-closed',closed);

  // Sidebar badge (aperti + in gestione)
  const nbSin=document.getElementById('nb-sin');
  if(nbSin){const n=open+gest; nbSin.textContent=n; nbSin.style.display=n>0?'':'none';}

  const filtered=sinistri.filter(s=>{
    if(fs!=='all'&&s.stato!==fs) return false;
    if(ft!=='all'&&s.targa!==ft) return false;
    if(q&&!s.targa.toLowerCase().includes(q)&&!(s.conducente||'').toLowerCase().includes(q)&&!(s.desc||'').toLowerCase().includes(q)&&!(s.luogo||'').toLowerCase().includes(q)) return false;
    return true;
  }).sort((a,b)=>new Date(b.data)-new Date(a.data));

  const listEl=document.getElementById('sin-list');
  if(!listEl) return;
  if(!filtered.length){listEl.innerHTML='<div class="empty">Nessun sinistro trovato</div>';return;}

  listEl.innerHTML=filtered.map(s=>{
    const v=vehicles[s.targa]||{};
    const importoFmt=s.importo?`€ ${Number(s.importo).toLocaleString('it-IT')}`:'—';
    return `<div class="sinistro-card" onclick="showDetailSinistro(${s.id})">
      <div class="sinistro-card-header">
        <span style="font-size:18px">${ICON[v.tipo]||'🚘'}</span>
        <span class="plate">${s.targa}</span>
        <div class="sinistro-title">${s.desc.slice(0,60)}${s.desc.length>60?'…':''}</div>
        <span class="sin-badge sin-${s.stato}">${SIN_LABELS[s.stato]}</span>
        <span class="sinistro-num">#${String(s.id).padStart(3,'0')}</span>
      </div>
      <div class="sinistro-meta">
        <span>📅 ${fmt(s.data)}</span>
        ${s.conducente?`<span>👤 ${s.conducente}</span>`:''}
        ${s.luogo?`<span>📍 ${s.luogo}</span>`:''}
        ${s.assicurazione?`<span>📄 ${s.assicurazione}</span>`:''}
        <span style="margin-left:auto;font-weight:600;color:${s.importo?'#A32D2D':'#aaa'}">${importoFmt}</span>
      </div>
      ${s.danni?`<div style="font-size:11px;color:#888;margin-top:6px;padding-top:6px;border-top:.5px solid rgba(0,0,0,.06)">🔧 ${s.danni}</div>`:''}
    </div>`;
  }).join('');
}

function showDetailSinistro(id){
  const s=sinistri.find(x=>x.id===id);
  if(!s) return;
  const v=vehicles[s.targa]||{};
  const detEl=document.getElementById('sin-detail');
  if(!detEl) return;

  const eventi=s.eventi||[];
  const timelineHtml=eventi.length
    ? eventi.map(e=>`<div class="timeline-item">
        <div class="timeline-dot tl-${e.tipo==='aperto'?'aperto':e.tipo==='chiuso'?'chiuso':'update'}">${e.tipo==='aperto'?'🟡':e.tipo==='chiuso'?'✅':'📝'}</div>
        <div class="timeline-content">
          <div class="timeline-text">${e.testo}</div>
          <div class="timeline-date">${fmt(e.data)}</div>
        </div>
      </div>`).join('')
    : '<div style="color:#bbb;font-size:13px">Nessun evento registrato</div>';

  detEl.innerHTML=`
    <div class="sin-detail">
      <div class="sin-detail-header">
        <span style="font-size:32px">${ICON[v.tipo]||'🚘'}</span>
        <div style="flex:1">
          <div style="font-size:16px;font-weight:700"><span style="font-family:monospace">${s.targa}</span> — Sinistro #${String(s.id).padStart(3,'0')}</div>
          <div style="font-size:12px;color:#888;margin-top:2px">${fmt(s.data)} ${s.luogo?'· '+s.luogo:''}</div>
        </div>
        <span class="sin-badge sin-${s.stato}" style="font-size:12px;padding:4px 12px">${SIN_LABELS[s.stato]}</span>
        <button class="edit-v-btn" onclick="editSinistro(${s.id})">✏️ Modifica</button>
        <button onclick="document.getElementById('sin-detail').style.display='none'" style="height:auto;padding:3px 8px;font-size:12px">✕</button>
      </div>

      <div style="display:grid;grid-template-columns:1fr 1fr;gap:16px">
        <div>
          <div class="detail-label" style="margin-bottom:6px">Evento</div>
          <div style="background:#f5f4f0;border-radius:8px;padding:10px 12px;font-size:13px;color:#333;line-height:1.5;margin-bottom:10px">${s.desc}</div>
          ${s.danni?`<div class="detail-label" style="margin-bottom:6px">Danni</div><div style="background:#FCEBEB;border:.5px solid #F7C1C1;border-radius:8px;padding:10px 12px;font-size:13px;color:#A32D2D;line-height:1.5;margin-bottom:10px">${s.danni}</div>`:''}
          <div style="display:grid;grid-template-columns:1fr 1fr;gap:8px 16px;font-size:13px">
            <div class="detail-field"><span class="detail-label">Conducente</span><span class="detail-value">${s.conducente||'—'}</span></div>
            <div class="detail-field"><span class="detail-label">Importo stimato</span><span class="detail-value" style="color:#A32D2D">${s.importo?'€ '+Number(s.importo).toLocaleString('it-IT'):'—'}</span></div>
            <div class="detail-field"><span class="detail-label">Compagnia</span><span class="detail-value">${s.assicurazione||'—'}</span></div>
            <div class="detail-field"><span class="detail-label">N° polizza</span><span class="detail-value">${s.nPolizza||'—'}</span></div>
            ${s.cpNome?`<div class="detail-field"><span class="detail-label">Controparte</span><span class="detail-value">${s.cpNome}</span></div>`:''}
            ${s.cpTarga?`<div class="detail-field"><span class="detail-label">Targa controparte</span><span class="detail-value" style="font-family:monospace">${s.cpTarga}</span></div>`:''}
            <div class="detail-field"><span class="detail-label">Apertura pratica</span><span class="detail-value">${fmt(s.dataPratica)||'—'}</span></div>
            <div class="detail-field"><span class="detail-label">Chiusura pratica</span><span class="detail-value">${fmt(s.dataChiusura)||'—'}</span></div>
          </div>
          ${s.note?`<div style="background:#f5f4f0;border-radius:8px;padding:8px 12px;font-size:12px;color:#666;margin-top:10px">📝 ${s.note}</div>`:''}
        </div>
        <div>
          <div class="detail-label" style="margin-bottom:8px">Timeline pratica</div>
          <div class="timeline">${timelineHtml}</div>
          <div style="margin-top:12px">
            <div class="detail-label" style="margin-bottom:6px">Aggiungi aggiornamento</div>
            <div style="display:flex;gap:6px">
              <input type="text" id="sin-evento-txt-${s.id}" placeholder="es. Perizia effettuata..." style="flex:1;height:32px;font-size:12px">
              <button class="btn-primary" style="height:32px;font-size:12px;padding:0 12px" onclick="addEventoSinistro(${s.id})">+ Aggiungi</button>
            </div>
          </div>
          <div style="margin-top:12px">
            <div class="detail-label" style="margin-bottom:6px">Cambia stato</div>
            <div style="display:flex;gap:6px;flex-wrap:wrap">
              ${['aperto','in_gestione','chiuso','contestato'].map(st=>
                `<button class="sin-stato-btn${s.stato===st?' selected':''}" data-stato="${st}" onclick="cambiaStatoSinistro(${s.id},'${st}')">${{aperto:'🟡 Aperto',in_gestione:'🔵 In gestione',chiuso:'🟢 Chiuso',contestato:'🔴 Contestato'}[st]}</button>`
              ).join('')}
            </div>
          </div>
        </div>
      </div>
    </div>`;

  detEl.style.display='block';
  detEl.scrollIntoView({behavior:'smooth',block:'start'});
}

function addEventoSinistro(id){
  const s=sinistri.find(x=>x.id===id);
  if(!s) return;
  const inp=document.getElementById('sin-evento-txt-'+id);
  if(!inp||!inp.value.trim()){toast('Inserisci il testo');return;}
  if(!s.eventi) s.eventi=[];
  s.eventi.push({data:today.toISOString().slice(0,10),testo:inp.value.trim(),tipo:'update'});
  save();
  showDetailSinistro(id);
  toast('Aggiornamento aggiunto');
}

function cambiaStatoSinistro(id,nuovoStato){
  const s=sinistri.find(x=>x.id===id);
  if(!s) return;
  s.stato=nuovoStato;
  if(!s.eventi) s.eventi=[];
  if(nuovoStato==='chiuso'){
    s.dataChiusura=today.toISOString().slice(0,10);
    s.eventi.push({data:s.dataChiusura,testo:'Pratica chiusa',tipo:'chiuso'});
  } else {
    s.eventi.push({data:today.toISOString().slice(0,10),testo:'Stato aggiornato: '+SIN_LABELS[nuovoStato],tipo:'update'});
  }
  save();
  renderSinistri();
  showDetailSinistro(id);
  toast('Stato: '+SIN_LABELS[nuovoStato]);
}

function showFormSinistro(prefillTarga){
  document.getElementById('sf-editing-id').value='';
  document.getElementById('sin-form-title').textContent='Nuovo sinistro';
  document.getElementById('sf-delete-btn').style.display='none';
  ['sf-conducente','sf-luogo','sf-desc','sf-danni','sf-cp-nome','sf-cp-targa','sf-assicurazione','sf-npolizza','sf-importo','sf-note'].forEach(id=>{
    const el=document.getElementById(id); if(el) el.value='';
  });
  ['sf-data','sf-data-pratica','sf-data-chiusura'].forEach(id=>{
    const el=document.getElementById(id); if(el) el.value='';
  });
  document.getElementById('sf-data').value=today.toISOString().slice(0,10);
  document.getElementById('sf-data-pratica').value=today.toISOString().slice(0,10);
  if(prefillTarga) document.getElementById('sf-targa').value=prefillTarga;
  else document.getElementById('sf-targa').value='';
  selectStatoSin('aperto');
  document.getElementById('sin-form').style.display='block';
  document.getElementById('sin-form').scrollIntoView({behavior:'smooth',block:'start'});
}

function hideFormSinistro(){
  document.getElementById('sin-form').style.display='none';
}

function editSinistro(id){
  const s=sinistri.find(x=>x.id===id);
  if(!s) return;
  showFormSinistro();
  document.getElementById('sf-editing-id').value=id;
  document.getElementById('sin-form-title').textContent='Modifica sinistro';
  document.getElementById('sf-delete-btn').style.display='';
  document.getElementById('sf-targa').value=s.targa||'';
  document.getElementById('sf-data').value=s.data||'';
  document.getElementById('sf-conducente').value=s.conducente||'';
  document.getElementById('sf-luogo').value=s.luogo||'';
  document.getElementById('sf-desc').value=s.desc||'';
  document.getElementById('sf-danni').value=s.danni||'';
  document.getElementById('sf-cp-nome').value=s.cpNome||'';
  document.getElementById('sf-cp-targa').value=s.cpTarga||'';
  document.getElementById('sf-assicurazione').value=s.assicurazione||'';
  document.getElementById('sf-npolizza').value=s.nPolizza||'';
  document.getElementById('sf-data-pratica').value=s.dataPratica||'';
  document.getElementById('sf-data-chiusura').value=s.dataChiusura||'';
  document.getElementById('sf-importo').value=s.importo||'';
  document.getElementById('sf-note').value=s.note||'';
  selectStatoSin(s.stato||'aperto');
}

function saveSinistro(){
  const targa=document.getElementById('sf-targa').value;
  const desc=document.getElementById('sf-desc').value.trim();
  const data=document.getElementById('sf-data').value;
  if(!targa){document.getElementById('sf-targa').focus();toast('Seleziona una targa');return;}
  if(!desc){document.getElementById('sf-desc').focus();toast('Inserisci la descrizione');return;}
  if(!data){document.getElementById('sf-data').focus();toast('Inserisci la data');return;}
  const editId=document.getElementById('sf-editing-id').value;
  const stato=document.getElementById('sf-stato').value;
  const obj={
    targa, data, stato,
    conducente:document.getElementById('sf-conducente').value.trim(),
    luogo:document.getElementById('sf-luogo').value.trim(),
    desc,
    danni:document.getElementById('sf-danni').value.trim(),
    cpNome:document.getElementById('sf-cp-nome').value.trim(),
    cpTarga:document.getElementById('sf-cp-targa').value.trim().toUpperCase(),
    assicurazione:document.getElementById('sf-assicurazione').value.trim(),
    nPolizza:document.getElementById('sf-npolizza').value.trim(),
    dataPratica:document.getElementById('sf-data-pratica').value,
    dataChiusura:document.getElementById('sf-data-chiusura').value,
    importo:document.getElementById('sf-importo').value,
    note:document.getElementById('sf-note').value.trim(),
  };
  if(editId){
    const idx=sinistri.findIndex(x=>x.id===parseInt(editId));
    if(idx>=0){
      obj.id=parseInt(editId);
      obj.eventi=sinistri[idx].eventi||[];
      sinistri[idx]=obj;
    }
  } else {
    obj.id=nextSinId++;
    obj.eventi=[{data:today.toISOString().slice(0,10),testo:'Sinistro aperto',tipo:'aperto'}];
    sinistri.push(obj);
  }
  save();
  hideFormSinistro();
  renderSinistri();
  toast(editId?'Sinistro aggiornato':'Sinistro registrato');
}

function deleteSinistro(){
  const editId=document.getElementById('sf-editing-id').value;
  if(!editId) return;
  const s=sinistri.find(x=>x.id===parseInt(editId));
  if(!s||!confirm('Eliminare il sinistro #'+String(s.id).padStart(3,'0')+'?')) return;
  sinistri=sinistri.filter(x=>x.id!==parseInt(editId));
  save();
  hideFormSinistro();
  document.getElementById('sin-detail').style.display='none';
  renderSinistri();
  toast('Sinistro eliminato');
}



// ════════════════════════════════════════════
// CHECKLIST CONSEGNA / RIENTRO
// ════════════════════════════════════════════

function renderChecklist(voci, containerId, barId, pctId, prefix){
  const grid = document.getElementById(containerId);
  const bar  = document.getElementById(barId);
  const pct  = document.getElementById(pctId);
  if(!grid) return;
  grid.innerHTML = voci.map(v => `
    <label class="checklist-item" id="${prefix}-${v.id}">
      <input type="checkbox" id="${prefix}-chk-${v.id}"
        onchange="updateChecklistProgress('${containerId}','${barId}','${pctId}','${prefix}')">
      ${v.label}
    </label>`).join('');
  grid._voci = voci;
  updateChecklistProgress(containerId, barId, pctId, prefix, voci);
}

function updateChecklistProgress(containerId, barId, pctId, prefix, voci){
  // voci può essere passata direttamente o recuperata dal grid
  if(!voci){
    const grid = document.getElementById(containerId);
    voci = (grid && grid._voci) ? grid._voci : [];
  }
  const checked = voci.filter(v => {
    const el = document.getElementById(prefix+'-chk-'+v.id);
    return el && el.checked;
  }).length;
  const tot = voci.length;
  const perc = Math.round(checked/tot*100);
  const bar = document.getElementById(barId);
  const pct = document.getElementById(pctId);
  if(bar){ bar.style.width=perc+'%'; bar.classList.toggle('complete', checked===tot); }
  if(pct) pct.textContent = checked+'/'+tot;
  // Update item style
  voci.forEach(v=>{
    const lbl=document.getElementById(prefix+'-'+v.id);
    const chk=document.getElementById(prefix+'-chk-'+v.id);
    if(lbl&&chk) lbl.classList.toggle('checked', chk.checked);
  });
}

function getChecklistValues(prefix, voci){
  const result={};
  voci.forEach(v=>{
    const el=document.getElementById(prefix+'-chk-'+v.id);
    result[v.id]=el?el.checked:false;
  });
  return result;
}

function checklistBadge(cl){
  if(!cl) return '';
  const keys=Object.keys(cl);
  if(!keys.length) return '';
  const checked=keys.filter(k=>cl[k]).length;
  const tot=keys.length;
  if(checked===tot) return `<span class="checklist-badge cb-ok">✓ ${checked}/${tot}</span>`;
  if(checked===0)   return `<span class="checklist-badge cb-no">— ${checked}/${tot}</span>`;
  return `<span class="checklist-badge cb-parziale">⚡ ${checked}/${tot}</span>`;
}

function checklistRecap(cl, voci){
  if(!cl) return '';
  return `<div class="mov-checklist-recap">`+
    voci.slice(0,6).map(v=>`
      <div class="mcr-item">
        <div class="mcr-dot ${cl[v.id]?'ok':'ko'}"></div>
        ${v.label}
      </div>`).join('')+
    (voci.length>6?`<div class="mcr-item" style="color:#aaa">+${voci.length-6} voci</div>`:'')+
  `</div>`;
}

// Checklist uscita inizializzata in openWizard()

// ════════════════════════════════════════════
// SISTEMA NOTIFICHE & AUTOMAZIONI
// ════════════════════════════════════════════

function buildNotifiche(){
  const notifiche=[];
  const todayStr=today.toISOString().slice(0,10);

  // 1. Scadenze urgenti / scadute
  Object.keys(vehicles).forEach(targa=>{
    const allD=items.filter(i=>i.targa===targa);
    const v=vehicles[targa];
    if(v.scadFor) allD.push({targa,cat:'Contratto fornitore',date:v.scadFor});
    if(v.scadCli) allD.push({targa,cat:'Contratto cliente',date:v.scadCli});
    allD.forEach(i=>{
      const s=st(i.date);
      if(s!=='ok'){
        const diff=Math.round((new Date(i.date)-today)/86400000);
        const daysLbl=diff<0?`Scaduto ${Math.abs(diff)}gg fa`:(diff===0?'Scade oggi':`Tra ${diff} giorni`);
        notifiche.push({
          tipo: s, icon: s==='scaduto'?'🔴':'🟡',
          title: `${targa} — ${i.cat}`,
          sub: daysLbl,
          action: ()=>switchMain('scadenze'),
          priority: diff
        });
      }
    });
  });

  // 2. Mezzi fuori da più di 3 giorni (ritardo rientro)
  movimenti.filter(m=>!m.rientro).forEach(m=>{
    const diff=Math.round((today-new Date(m.dataOut))/86400000);
    if(diff>=3){
      notifiche.push({
        tipo:'red', icon:'🚗',
        title:`${m.targa} — Fuori da ${diff} giorni`,
        sub: m.conducente?`Conducente: ${m.conducente}`:'Nessun conducente registrato',
        action: ()=>switchMain('noleggi'),
        priority: -diff
      });
    }
  });

  // 3. Interventi in ritardo (dataPrev superata, non completati)
  interventi.filter(i=>i.stato!=='completato'&&i.dataPrev&&i.dataPrev<todayStr).forEach(i=>{
    const diff=Math.round((today-new Date(i.dataPrev))/86400000);
    notifiche.push({
      tipo:'amber', icon:'🔧',
      title:`${i.targa} — ${i.tipo} in ritardo`,
      sub:`Previsto il ${fmt(i.dataPrev)}, ritardo ${diff}gg`,
      action: ()=>switchMain('garage'),
      priority: -diff
    });
  });

  // 4. Sinistri aperti da più di 30 giorni
  sinistri.filter(s=>s.stato==='aperto'||s.stato==='in_gestione').forEach(s=>{
    const diff=Math.round((today-new Date(s.data))/86400000);
    if(diff>30){
      notifiche.push({
        tipo:'amber', icon:'⚠️',
        title:`Sinistro #${String(s.id).padStart(3,'0')} — ${s.targa}`,
        sub:`Aperto da ${diff} giorni, ancora non chiuso`,
        action: ()=>switchMain('sinistri'),
        priority: -diff
      });
    }
  });

  // 5. Documenti clienti scaduti
  clienti.filter(c=>docScaduto(c)&&!c.blacklist).forEach(c=>{
    notifiche.push({
      tipo:'amber', icon:'📄',
      title:`${c.nome} — Documento scaduto`,
      sub: c.scadDoc&&c.scadDoc<todayStr?`Doc. scaduto il ${fmt(c.scadDoc)}`:`Patente scaduta il ${fmt(c.scadPatente)}`,
      action: ()=>switchMain('clienti'),
      priority: 0
    });
  });
  // 6. Patente autisti in scadenza
  autisti.forEach(a=>{
    if(a.scadPatente&&a.scadPatente<=todayStr){
      const diff=Math.round((new Date(a.scadPatente)-today)/86400000);
      notifiche.push({
        tipo: diff<0?'red':'amber', icon:'🪪',
        title:`${a.nome} ${a.cognome} — Patente ${diff<0?'scaduta':'in scadenza'}`,
        sub: diff<0?`Scaduta ${Math.abs(diff)}gg fa`:`Tra ${diff} giorni`,
        action: ()=>switchMain('noleggi'),
        priority: diff
      });
    }
  });

  return notifiche.sort((a,b)=>a.priority-b.priority);
}

function renderNotifiche(){
  const notifiche=buildNotifiche();
  const dot=document.getElementById('notif-dot');
  const listEl=document.getElementById('notif-list');
  const countEl=document.getElementById('notif-count');
  if(!listEl) return;

  if(dot) dot.classList.toggle('show', notifiche.length>0);
  if(countEl) countEl.textContent=notifiche.length>0?`${notifiche.length} nuove`:'';

  if(!notifiche.length){
    listEl.innerHTML='<div class="notif-empty">✅ Nessuna notifica attiva</div>';
    return;
  }
  listEl.innerHTML=notifiche.slice(0,12).map(n=>`
    <div class="notif-item ${n.tipo==='red'?'red':'amber'}" onclick="closeNotifPanel();(${n.action.toString()})()">
      <span class="notif-item-icon">${n.icon}</span>
      <div class="notif-item-body">
        <div class="notif-item-title">${n.title}</div>
        <div class="notif-item-sub">${n.sub}</div>
      </div>
    </div>`).join('');
}

function toggleNotifPanel(){
  const panel=document.getElementById('notif-panel');
  if(!panel) return;
  panel.classList.toggle('open');
  if(panel.classList.contains('open')) renderNotifiche();
}

function closeNotifPanel(){
  const panel=document.getElementById('notif-panel');
  if(panel) panel.classList.remove('open');
}

// Close notif panel on outside click
document.addEventListener('click',function(e){
  const panel=document.getElementById('notif-panel');
  const btn=document.getElementById('notif-btn');
  if(panel&&btn&&!panel.contains(e.target)&&!btn.contains(e.target)){
    panel.classList.remove('open');
  }
});

// ── MODAL ──────────────────────────────────
function openModal(title, body){
  document.getElementById('modal-title').innerHTML=title;
  document.getElementById('modal-body').innerHTML=body;
  document.getElementById('modal-overlay').classList.add('open');
}
function closeModal(e){
  if(!e||e.target===document.getElementById('modal-overlay')){
    document.getElementById('modal-overlay').classList.remove('open');
  }
}

// ── SCROLL TO TOP ──────────────────────────
const scrollTopBtn=document.getElementById('scroll-top');
if(scrollTopBtn){
  document.querySelector('.content').addEventListener('scroll',function(){
    scrollTopBtn.classList.toggle('show',this.scrollTop>200);
  });
  window.addEventListener('scroll',function(){
    scrollTopBtn.classList.toggle('show',window.scrollY>200);
  });
}
function scrollToTop(){
  window.scrollTo({top:0,behavior:'smooth'});
  const c=document.querySelector('.content');
  if(c) c.scrollTo({top:0,behavior:'smooth'});
}

// ── AUTOMAZIONI PERIODICHE ─────────────────
// Aggiorna badge notifiche ogni 60 secondi
function autoRefresh(){
  if(!loaded) return;
  renderNotifiche();
  renderDashboard();
}
setInterval(autoRefresh, 60000);

// Aggiorna stato mezzi automaticamente (rientri in ritardo)
function autoUpdateStatiMezzi(){
  const todayStr=today.toISOString().slice(0,10);
  // Se mezzo ha intervento aperto non completato → statoOp = officina
  Object.keys(vehicles).forEach(targa=>{
    const v=vehicles[targa];
    const hasIntOpen=interventi.some(i=>i.targa===targa&&i.stato!=='completato');
    const hasMov=movimenti.some(m=>m.targa===targa&&!m.rientro);
    if(hasIntOpen) v.statoOp='officina';
    else if(hasMov) v.statoOp='noleggiato';
    else if(v.statoOp==='officina'||v.statoOp==='noleggiato') v.statoOp='disponibile';
  });
}

// ── EXPORT CSV ─────────────────────────────
function exportCSV(tipo){
  let csv='', filename='';
  if(tipo==='scadenze'){
    csv='Targa,Tipo,Categoria,Data Scadenza,Stato,Note\n';
    items.forEach(i=>{
      const v=vehicles[i.targa]||{};
      csv+=`"${i.targa}","${v.tipo||''}","${i.cat}","${i.date}","${st(i.date)}","${i.note||''}"\n`;
    });
    filename='scadenze_vieffe.csv';
  } else if(tipo==='mezzi'){
    csv='Targa,Tipo,Possesso,Cliente/Fornitore,Stato\n';
    Object.keys(vehicles).forEach(t=>{
      const v=vehicles[t];
      csv+=`"${t}","${v.tipo}","${v.poss}","${v.poss==='noleggio'?v.cliente||v.fornitore:'—'}","${getStatoMezzo(t)}"\n`;
    });
    filename='flotta_vieffe.csv';
  } else if(tipo==='sinistri'){
    csv='N°,Targa,Data,Conducente,Stato,Importo,Assicurazione\n';
    sinistri.forEach(s=>{
      csv+=`"${String(s.id).padStart(3,'0')}","${s.targa}","${s.data}","${s.conducente||''}","${SIN_LABELS[s.stato]}","${s.importo||''}","${s.assicurazione||''}"\n`;
    });
    filename='sinistri_vieffe.csv';
  }
  const blob=new Blob([csv],{type:'text/csv;charset=utf-8;'});
  const a=document.createElement('a');
  a.href=URL.createObjectURL(blob);
  a.download=filename;
  a.click();
  toast('Export CSV completato');
}

// ── QUICK STATS per dashboard (aggiorna anche sinistri/garage) ──
const _origRenderDashboard=renderDashboard;
renderDashboard=function(){
  autoUpdateStatiMezzi();
  _origRenderDashboard();
  renderNotifiche();
};


// ════════════════════════════════════════════
// SCHEDA VEICOLO — 5 TAB
// ════════════════════════════════════════════

let _scedaVeicoloTarga = null;

function openSchedaVeicolo(targa, defaultTab){
  _scedaVeicoloTarga = targa;
  const fleetView = document.getElementById('gar-fleet-view');
  const schedaView = document.getElementById('gar-scheda-view');
  if(fleetView) fleetView.style.display = 'none';
  if(schedaView){ schedaView.style.display = ''; schedaView.innerHTML = buildSchedaHTML(targa); }
  const tab = defaultTab||'dati';
  switchVehTab(tab);
  if(tab==='dati') setTimeout(()=>renderTabDati(targa),0);
  schedaView.scrollIntoView({behavior:'smooth',block:'start'});
}

function closeSchedaVeicolo(){
  _scedaVeicoloTarga = null;
  document.getElementById('gar-fleet-view').style.display = '';
  document.getElementById('gar-scheda-view').style.display = 'none';
  document.getElementById('gar-scheda-view').innerHTML = '';
}

function switchVehTab(tab){
  document.querySelectorAll('.veh-tab').forEach(t=>t.classList.toggle('active',t.dataset.tab===tab));
  document.querySelectorAll('.veh-tab-content').forEach(c=>c.classList.toggle('active',c.id==='vt-'+tab));
  if(!_scedaVeicoloTarga) return;
  if(tab==='dati')          setTimeout(()=>renderTabDati(_scedaVeicoloTarga),0);
  if(tab==='manutenzioni')  renderTabManutenzioni(_scedaVeicoloTarga);
  if(tab==='storico')       renderTabStorico(_scedaVeicoloTarga);
  if(tab==='documenti')     renderTabDocumenti(_scedaVeicoloTarga);
  if(tab==='checklist')     renderTabChecklist(_scedaVeicoloTarga);
  if(tab==='costi')         renderTabCosti(_scedaVeicoloTarga);
}

function buildSchedaHTML(targa){
  const v = vehicles[targa]||{};
  const stato = getStatoMezzo(targa);
  const modello = [(v.marca||''),(v.modello||'')].filter(Boolean).join(' ')||(v.tipo||'—');
  return `
  <div class="veh-scheda">
    <div class="veh-scheda-header">
      <span class="veh-scheda-icon">${ICON[v.tipo]||'🚘'}</span>
      <div class="veh-scheda-info">
        <div class="veh-scheda-targa">${targa}</div>
        <div class="veh-scheda-modello">${modello}</div>
        <div class="veh-scheda-sub">${v.tipo||''} ${v.anno?'· Anno '+v.anno:''} ${v.sede?'· '+v.sede:''}</div>
      </div>
      <div class="veh-scheda-stato">
        <span class="veh-stato-badge vsb-${stato}" style="font-size:12px;padding:5px 12px">${{disponibile:'✓ Disponibile',officina:'🔧 Officina',noleggiato:'🔑 Noleggiato',prenotato:'📅 Prenotato',fuori_servizio:'⛔ Fuori servizio'}[stato]||stato}</span>
        <button class="veh-scheda-back" onclick="closeSchedaVeicolo()">← Torna alla flotta</button>
      </div>
    </div>
    <div class="veh-tabs">
      <button class="veh-tab active" data-tab="dati" onclick="switchVehTab('dati')">📋 Dati veicolo</button>
      <button class="veh-tab" data-tab="documenti" onclick="switchVehTab('documenti')">📄 Documenti</button>
      <button class="veh-tab" data-tab="manutenzioni" onclick="switchVehTab('manutenzioni')">🔧 Manutenzioni</button>
      <button class="veh-tab" data-tab="storico" onclick="switchVehTab('storico')">🕐 Storico</button>
      <button class="veh-tab" data-tab="checklist" onclick="switchVehTab('checklist')">✅ Checklist</button>
      <button class="veh-tab" data-tab="costi" onclick="switchVehTab('costi')">💰 Costi</button>
    </div>

    <!-- TAB 1: DATI -->
    <div class="veh-tab-content active" id="vt-dati">
      <div id="vt-dati-view"></div>
    </div>

    <!-- TAB 2: DOCUMENTI -->
    <div class="veh-tab-content" id="vt-documenti">
      <div id="vt-doc-list"></div>
    </div>

    <!-- TAB 3: MANUTENZIONI -->
    <div class="veh-tab-content" id="vt-manutenzioni">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:1rem">
        <div style="font-size:13px;font-weight:600;color:#888">Cronologia interventi per <span style="font-family:monospace;color:#FF6600">${targa}</span></div>
        <button class="btn-primary" style="font-size:12px;padding:0 12px;height:30px" onclick="showFormGarageFromScheda('${targa}')">+ Nuovo intervento</button>
      </div>
      <div id="vt-maint-list"></div>
    </div>

    <!-- TAB 4: STORICO -->
    <div class="veh-tab-content" id="vt-storico">
      <div id="vt-storico-list"></div>
    </div>

    <!-- TAB 5: CHECKLIST -->
    <div class="veh-tab-content" id="vt-checklist">
      <div id="vt-checklist-content"></div>
    </div>
    <!-- TAB 6: COSTI -->
    <div class="veh-tab-content" id="vt-costi">
      <div id="vt-costi-content"></div>
    </div>
  </div>`;
}

// ── TAB 1: Dati veicolo ──────────────────────
function renderTabDati(targa){
  const v = vehicles[targa]||{};
  const el = document.getElementById('vt-dati-view');
  if(!el) return;

  // Edit mode vs view mode
  el.innerHTML = `
    <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:1.25rem">
      <div style="font-size:13px;color:#888">Dettagli tecnici e operativi del veicolo</div>
      <button class="btn-primary" style="font-size:12px;padding:0 12px;height:30px" onclick="showEditDatiVeicolo('${targa}')">✏️ Modifica dati</button>
    </div>
    <div class="veh-data-grid">
      <div class="veh-data-field"><span class="vdf-label">Marca</span><span class="vdf-value">${v.marca||'—'}</span></div>
      <div class="veh-data-field"><span class="vdf-label">Modello</span><span class="vdf-value">${v.modello||'—'}</span></div>
      <div class="veh-data-field"><span class="vdf-label">Targa</span><span class="vdf-value" style="font-family:monospace;color:#FF6600">${targa}</span></div>
      <div class="veh-data-field"><span class="vdf-label">VIN / Telaio</span><span class="vdf-value" style="font-family:monospace;font-size:12px">${v.vin||'—'}</span></div>
      <div class="veh-data-field"><span class="vdf-label">Anno</span><span class="vdf-value">${v.anno||'—'}</span></div>
      <div class="veh-data-field"><span class="vdf-label">Alimentazione</span><span class="vdf-value">${v.alimentazione||'—'}</span></div>
      <div class="veh-data-field"><span class="vdf-label">Cambio</span><span class="vdf-value">${v.cambio||'—'}</span></div>
      <div class="veh-data-field"><span class="vdf-label">Categoria</span><span class="vdf-value">${v.tipo||'—'}</span></div>
      <div class="veh-data-field"><span class="vdf-label">Portata (kg)</span><span class="vdf-value">${v.portata?v.portata+' kg':'—'}</span></div>
      <div class="veh-data-field"><span class="vdf-label">Volume (m³)</span><span class="vdf-value">${v.volume?v.volume+' m³':'—'}</span></div>
      <div class="veh-data-field"><span class="vdf-label">KM attuali</span><span class="vdf-value">${v.km?Number(v.km).toLocaleString('it-IT')+' km':'—'}</span></div>
      <div class="veh-data-field"><span class="vdf-label">Sede</span><span class="vdf-value">${v.sede||'—'}</span></div>
      <div class="veh-data-field"><span class="vdf-label">Possesso</span><span class="vdf-value">${v.poss==='noleggio'?'Noleggio da '+v.fornitore:'Proprietà'}</span></div>
      ${v.poss==='noleggio'?`
      <div class="veh-data-field"><span class="vdf-label">Cliente</span><span class="vdf-value">${v.cliente||'—'}</span></div>
      <div class="veh-data-field"><span class="vdf-label">Canone mensile</span><span class="vdf-value">${v.canone?'€ '+v.canone:'—'}</span></div>`:''}
    </div>
    <div id="vt-edit-form" style="display:none"></div>`;
}

function showEditDatiVeicolo(targa){
  const v = vehicles[targa]||{};
  const el = document.getElementById('vt-edit-form');
  if(!el) return;
  el.style.display='';
  el.innerHTML=`
    <div style="background:#f5f4f0;border-radius:12px;padding:1.25rem;margin-top:1rem">
      <div style="font-size:13px;font-weight:600;margin-bottom:1rem">✏️ Modifica dati veicolo</div>
      <div class="row r4" style="margin-bottom:8px">
        <div class="fg"><label>Marca</label><input type="text" id="ed-marca" value="${v.marca||''}" placeholder="es. Ford"></div>
        <div class="fg"><label>Modello</label><input type="text" id="ed-modello" value="${v.modello||''}" placeholder="es. Transit"></div>
        <div class="fg"><label>VIN / Telaio</label><input type="text" id="ed-vin" value="${v.vin||''}" placeholder="WFOXXX..."></div>
        <div class="fg"><label>Anno</label><input type="number" id="ed-anno" value="${v.anno||''}" placeholder="2021" min="1990" max="2030"></div>
      </div>
      <div class="row r4" style="margin-bottom:8px">
        <div class="fg"><label>Alimentazione</label>
          <select id="ed-alimentazione">
            ${['Diesel','Benzina','Ibrido','Elettrico','GPL','Metano','Altro'].map(a=>`<option${v.alimentazione===a?' selected':''}>${a}</option>`).join('')}
          </select>
        </div>
        <div class="fg"><label>Cambio</label>
          <select id="ed-cambio">
            ${['Manuale','Automatico','Semi-automatico'].map(a=>`<option${v.cambio===a?' selected':''}>${a}</option>`).join('')}
          </select>
        </div>
        <div class="fg"><label>Portata (kg)</label><input type="number" id="ed-portata" value="${v.portata||''}" placeholder="es. 1000"></div>
        <div class="fg"><label>Volume (m³)</label><input type="number" id="ed-volume" value="${v.volume||''}" step="0.1" placeholder="es. 8.5"></div>
      </div>
      <div class="row r3" style="margin-bottom:12px">
        <div class="fg"><label>KM attuali</label><input type="number" id="ed-km" value="${v.km||''}" placeholder="es. 48000"></div>
        <div class="fg"><label>Sede operativa</label><input type="text" id="ed-sede" value="${v.sede||''}" placeholder="es. Pero (MI)"></div>
        <div class="fg"><label>Stato operativo</label>
          <select id="ed-stato">
            ${['disponibile','prenotato','officina','fuori_servizio'].map(s=>`<option value="${s}"${(v.statoOp||'disponibile')===s?' selected':''}>${{disponibile:'Disponibile',prenotato:'Prenotato',officina:'Officina',fuori_servizio:'Fuori servizio'}[s]}</option>`).join('')}
          </select>
        </div>
      </div>
      <div style="display:flex;gap:8px">
        <button class="btn-primary" onclick="saveDatiVeicolo('${targa}')">💾 Salva modifiche</button>
        <button onclick="document.getElementById('vt-edit-form').style.display='none'">Annulla</button>
      </div>
    </div>`;
}

function saveDatiVeicolo(targa){
  const v = vehicles[targa];
  if(!v) return;
  v.marca    = document.getElementById('ed-marca').value.trim();
  v.modello  = document.getElementById('ed-modello').value.trim();
  v.vin      = document.getElementById('ed-vin').value.trim();
  v.anno     = document.getElementById('ed-anno').value;
  v.alimentazione = document.getElementById('ed-alimentazione').value;
  v.cambio   = document.getElementById('ed-cambio').value;
  v.portata  = document.getElementById('ed-portata').value;
  v.volume   = document.getElementById('ed-volume').value;
  v.km       = document.getElementById('ed-km').value;
  v.sede     = document.getElementById('ed-sede').value.trim();
  v.statoOp  = document.getElementById('ed-stato').value;
  save();
  renderGarage();
  // Rebuild scheda
  openSchedaVeicolo(targa,'dati');
  toast('Dati veicolo aggiornati');
}

// ── TAB 2: Documenti ─────────────────────────
function renderExtraDocs(targa){
  const el=document.getElementById('extra-docs-'+targa);
  if(!el) return;
  const v=vehicles[targa]||{};
  const extra=(v.docs&&v.docs.extra)||[];
  if(!extra.length){el.innerHTML='<div style="font-size:12px;color:#bbb;padding:4px 0">Nessun documento aggiuntivo</div>';return;}
  el.innerHTML=extra.map((d,idx)=>`
    <div class="doc-inline-card" style="margin-bottom:6px">
      <div class="doc-inline-header">
        <span class="dic-icon">📎</span>
        <span class="dic-name">${d.nome||'Documento'}</span>
        ${d.dataScadenza?`<span style="font-size:11px;color:#888">Scade: ${fmt(d.dataScadenza)}</span>`:''}
        <span class="dic-scad ${d.dataScadenza?stAlert(d.dataScadenza):'nd'}">${d.dataScadenza?(stAlert(d.dataScadenza)==='ok'?'Valido':'Attenzione'):'—'}</span>
        <button class="dic-edit-btn" onclick="removeExtraDoc('${targa}',${idx})">✕</button>
      </div>
    </div>`).join('');
}

function addExtraDoc(targa){
  const nome=prompt('Nome documento:');
  if(!nome) return;
  const scad=prompt('Data scadenza (YYYY-MM-DD, lascia vuoto se nessuna):');
  const v=vehicles[targa];
  if(!v.docs) v.docs={};
  if(!v.docs.extra) v.docs.extra=[];
  v.docs.extra.push({nome,dataScadenza:scad||'',dataEmissione:'',costo:'',note:''});
  save();
  renderExtraDocs(targa);
  toast('Documento aggiunto');
}

function removeExtraDoc(targa,idx){
  const v=vehicles[targa];
  if(!v||!v.docs||!v.docs.extra) return;
  v.docs.extra.splice(idx,1);
  save();
  renderExtraDocs(targa);
}


function renderTabDocumenti(targa){
  const el=document.getElementById('vt-doc-list');
  if(!el) return;
  const v=vehicles[targa]||{};
  const docs=v.docs||{};
  syncDocsToItems(targa);

  const DOC_DEFS=[
    {key:'assicurazione',icon:'📄',label:'Assicurazione',extras:['compagnia','polizza']},
    {key:'revisione',    icon:'🔍',label:'Revisione',    extras:[]},
    {key:'bollo',        icon:'💳',label:'Bollo',        extras:[]},
    {key:'tagliando',    icon:'🔩',label:'Tagliando',    extras:['kmProssimo']},
    {key:'tachigrafo',   icon:'📡',label:'Tachigrafo',   extras:[]},
    {key:'leasing',      icon:'🏦',label:'Leasing / Finanziamento',extras:['compagnia']},
    {key:'licenza',      icon:'📜',label:'Licenza operativa',extras:[]},
    {key:'permesso',     icon:'🛂',label:'Permesso speciale',extras:[]},
  ];

  let docsHtml='';
  DOC_DEFS.forEach(function(d){
    const doc=docs[d.key]||{};
    const stato=doc.dataScadenza?stAlert(doc.dataScadenza):'nd';
    const statoLbl={'scaduto':'🔴 Scaduta','urgente7':'🔴 Critica','urgente':'🟡 In scadenza','ok':'🟢 Valida','nd':'⬜ Non inserita'}[stato]||'—';
    const syncIcon=doc.dataScadenza?'<span style="font-size:9px;color:#3B6D11;margin-left:4px" title="Sincronizzato con Scadenze">↻</span>':'';
    const scadInfo=doc.dataScadenza?('<span style="font-size:11px;color:#666">Scade: <strong>'+fmt(doc.dataScadenza)+'</strong></span>'):'<span style="font-size:11px;color:#ccc">Nessuna data</span>';
    const costoInfo=doc.costo?('<span style="font-size:11px;color:#888">€ '+doc.costo+'</span>'):'';

    let extraFields='';
    if(d.extras.indexOf('compagnia')>=0){
      extraFields+='<div class="doc-form-row r2" style="margin-bottom:8px"><div class="fg"><label>Compagnia</label><input type="text" id="df-'+targa+'-'+d.key+'-compagnia" value="'+(doc.compagnia||'')+'" placeholder="es. AXA"></div><div class="fg"><label>N° polizza</label><input type="text" id="df-'+targa+'-'+d.key+'-polizza" value="'+(doc.polizza||'')+'" placeholder="es. POL-2024"></div></div>';
    }
    if(d.extras.indexOf('kmProssimo')>=0){
      extraFields+='<div class="doc-form-row r2" style="margin-bottom:8px"><div class="fg"><label>KM prossimo intervento</label><input type="number" id="df-'+targa+'-'+d.key+'-kmProssimo" value="'+(doc.kmProssimo||'')+'" placeholder="es. 60000"></div><div class="fg"></div></div>';
    }

    docsHtml+='<div class="doc-inline-card">'+
      '<div class="doc-inline-header" onclick="toggleDocForm(\''+targa+'\',\''+d.key+'\')">'+
        '<span class="dic-icon">'+d.icon+'</span>'+
        '<span class="dic-name">'+d.label+'</span>'+
        scadInfo+
        '<span class="dic-scad '+stato+'">'+statoLbl+syncIcon+'</span>'+
        costoInfo+
        '<span class="dic-chevron" id="chev-'+targa+'-'+d.key+'">▶</span>'+
      '</div>'+
      '<div class="doc-inline-form" id="docform-'+targa+'-'+d.key+'">'+
        '<div class="doc-form-row">'+
          '<div class="fg"><label>Data emissione</label><input type="date" id="df-'+targa+'-'+d.key+'-dataEmissione" value="'+(doc.dataEmissione||'')+'"></div>'+
          '<div class="fg"><label>Data scadenza</label><input type="date" id="df-'+targa+'-'+d.key+'-dataScadenza" value="'+(doc.dataScadenza||'')+'"></div>'+
          '<div class="fg"><label>Costo (€)</label><input type="number" id="df-'+targa+'-'+d.key+'-costo" value="'+(doc.costo||'')+'" placeholder="es. 1200"></div>'+
          '<div class="fg"><label>Note</label><input type="text" id="df-'+targa+'-'+d.key+'-note" value="'+(doc.note||'')+'" placeholder="Opzionale"></div>'+
        '</div>'+
        extraFields+
        '<div style="display:flex;gap:6px;margin-top:4px">'+
          '<button class="doc-save-btn" onclick="saveDoc(\''+targa+'\',\''+d.key+'\')">💾 Salva</button>'+
          '<button style="font-size:12px;padding:0 10px;height:32px" onclick="toggleDocForm(\''+targa+'\',\''+d.key+'\')">Annulla</button>'+
        '</div>'+
      '</div>'+
    '</div>';
  });

  el.innerHTML=
    '<div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:.75rem">'+
    '<div style="font-size:12px;color:#888">Modifica scadenze direttamente qui. Le altre sezioni si aggiornano automaticamente.</div></div>'+
    '<div class="km-inline">'+
      '<span style="font-size:13px;font-weight:600;color:#888;white-space:nowrap">KM attuali</span>'+
      '<span class="km-inline-val" id="km-display-'+targa+'">'+(v.km?Number(v.km).toLocaleString('it-IT')+' km':'—')+'</span>'+
      '<input type="number" class="km-inline-input" id="km-input-'+targa+'" value="'+(v.km||'')+'" placeholder="Aggiorna KM">'+
      '<button class="doc-save-btn" onclick="updateKm(\''+targa+'\')">Aggiorna</button>'+
    '</div>'+
    '<div class="doc-inline-grid" id="docs-grid-'+targa+'">'+docsHtml+'</div>'+
    '<div style="margin-top:1rem">'+
      '<div style="font-size:11px;font-weight:700;text-transform:uppercase;letter-spacing:.05em;color:#aaa;margin-bottom:.75rem">Altri documenti</div>'+
      '<div id="extra-docs-'+targa+'"></div>'+
      '<button onclick="addExtraDoc(\''+targa+'\')" style="font-size:12px;padding:0 12px;height:30px;margin-top:6px">+ Aggiungi documento</button>'+
    '</div>';

  renderExtraDocs(targa);
}

function toggleDocForm(targa,key){
  const form=document.getElementById('docform-'+targa+'-'+key);
  const chev=document.getElementById('chev-'+targa+'-'+key);
  if(!form) return;
  const isOpen=form.classList.contains('open');
  form.classList.toggle('open',!isOpen);
  if(chev) chev.classList.toggle('open',!isOpen);
}

function saveDoc(targa,key){
  const v=vehicles[targa];
  if(!v) return;
  if(!v.docs) v.docs={};
  const get=function(field){const el=document.getElementById('df-'+targa+'-'+key+'-'+field);return el?el.value.trim():'';};
  v.docs[key]={
    dataEmissione:get('dataEmissione'),
    dataScadenza: get('dataScadenza'),
    costo:        get('costo'),
    kmProssimo:   get('kmProssimo'),
    compagnia:    get('compagnia'),
    polizza:      get('polizza'),
    note:         get('note'),
  };
  syncDocsToItems(targa);
  save();
  renderTabDocumenti(targa);
  renderGarage();
  if(document.getElementById('page-scadenze').classList.contains('active')) render();
  const lbl=key.charAt(0).toUpperCase()+key.slice(1);
  toast('✅ '+lbl+' aggiornata — scadenze e notifiche sincronizzate automaticamente');
}

function updateKm(targa){
  const v=vehicles[targa];
  if(!v) return;
  const inp=document.getElementById('km-input-'+targa);
  if(!inp||!inp.value) return;
  if(!v.kmHistory) v.kmHistory=[];
  v.kmHistory.push({data:today.toISOString().slice(0,10),km:v.km||'',note:'Aggiornamento manuale'});
  v.km=inp.value;
  save();
  const disp=document.getElementById('km-display-'+targa);
  if(disp) disp.textContent=Number(inp.value).toLocaleString('it-IT')+' km';
  renderGarage();
  toast('KM aggiornati: '+Number(inp.value).toLocaleString('it-IT')+' km');
}

function syncDocsToItems(targa){
  const v=vehicles[targa];
  if(!v) return;
  const docs=v.docs||{};

  // Mappa completa: chiave docs → categoria items
  const MAP={
    assicurazione:'Assicurazione',
    revisione:'Revisione',
    bollo:'Bollo',
    tagliando:'Tagliando',
    tachigrafo:'Tachigrafo',
    leasing:'Leasing',
    licenza:'Licenza',
    permesso:'Permesso',
  };

  Object.keys(MAP).forEach(function(key){
    const doc=docs[key]||{};
    const cat=MAP[key];
    if(!doc.dataScadenza) return;
    const existing=items.find(function(i){return i.targa===targa&&i.cat===cat;});
    if(existing){
      existing.date=doc.dataScadenza;
      existing.note=doc.note||'';
    } else {
      items.push({id:nextId++,targa:targa,cat:cat,date:doc.dataScadenza,note:doc.note||''});
    }
  });

  // Contratti da campi diretti vehicles (noleggio)
  if(v.scadFor){
    const ex=items.find(function(i){return i.targa===targa&&i.cat==='Contratto fornitore';});
    if(ex){ ex.date=v.scadFor; ex.note=v.fornitore||''; }
    else items.push({id:nextId++,targa:targa,cat:'Contratto fornitore',date:v.scadFor,note:v.fornitore||''});
  }
  if(v.scadCli){
    const ex=items.find(function(i){return i.targa===targa&&i.cat==='Contratto cliente';});
    if(ex){ ex.date=v.scadCli; ex.note=v.cliente||''; }
    else items.push({id:nextId++,targa:targa,cat:'Contratto cliente',date:v.scadCli,note:v.cliente||''});
  }

  // Documenti extra (array libero)
  const extra=docs.extra||[];
  extra.forEach(function(d,idx){
    if(!d.dataScadenza) return;
    const cat='Doc: '+(d.nome||'Documento '+(idx+1));
    const ex=items.find(function(i){return i.targa===targa&&i.cat===cat;});
    if(ex){ ex.date=d.dataScadenza; }
    else items.push({id:nextId++,targa:targa,cat:cat,date:d.dataScadenza,note:d.note||''});
  });
}


// ════════════════════════════════════════════
// INIT DOCS: popola vehicles.docs dai items[]
// (migrazione dati vecchi: items → docs)
// ════════════════════════════════════════════
function initDocsFromItems(){
  const MAP_REVERSE={
    'Assicurazione':'assicurazione',
    'Revisione':'revisione',
    'Bollo':'bollo',
    'Tagliando':'tagliando',
    'Tachigrafo':'tachigrafo',
    'Leasing':'leasing',
    'Licenza':'licenza',
    'Permesso':'permesso',
  };
  items.forEach(function(item){
    const v=vehicles[item.targa];
    if(!v) return;
    if(!v.docs) v.docs={};
    const key=MAP_REVERSE[item.cat];
    if(!key) return;
    // Solo se il campo docs non è già valorizzato
    if(!v.docs[key]||!v.docs[key].dataScadenza){
      v.docs[key]=v.docs[key]||{};
      v.docs[key].dataScadenza=item.date;
      v.docs[key].note=item.note||'';
    }
  });
  // Stessa cosa per scadFor/scadCli
  Object.keys(vehicles).forEach(function(targa){
    const v=vehicles[targa];
    if(!v.docs) v.docs={};
    // Contratto fornitore → leasing se non già impostato
    if(v.scadFor&&(!v.docs.leasing||!v.docs.leasing.dataScadenza)){
      v.docs.leasing=v.docs.leasing||{};
      if(!v.docs.leasing.dataScadenza) v.docs.leasing.dataScadenza=v.scadFor;
      if(!v.docs.leasing.compagnia) v.docs.leasing.compagnia=v.fornitore||'';
    }
  });
}

// Sincronizza TUTTI i veicoli (chiamata globale)
function syncAllDocsToItems(){
  Object.keys(vehicles).forEach(function(t){
    syncDocsToItems(t);
  });
}

function renderExtraDocs(targa){
  const el=document.getElementById('extra-docs-'+targa);
  if(!el) return;
  const v=vehicles[targa]||{};
  const extra=(v.docs&&v.docs.extra)||[];
  if(!extra.length){el.innerHTML='<div style="font-size:12px;color:#bbb;padding:4px 0">Nessun documento aggiuntivo</div>';return;}
  el.innerHTML=extra.map(function(d,idx){
    const stato=d.dataScadenza?stAlert(d.dataScadenza):'nd';
    return '<div class="doc-inline-card" style="margin-bottom:6px">'+
      '<div class="doc-inline-header">'+
        '<span class="dic-icon">📎</span>'+
        '<span class="dic-name">'+(d.nome||'Documento')+'</span>'+
        (d.dataScadenza?'<span style="font-size:11px;color:#888">Scade: '+fmt(d.dataScadenza)+'</span>':'') +
        '<span class="dic-scad '+stato+'">'+(d.dataScadenza?(stato==='ok'?'Valido':'Attenzione'):'—')+'</span>'+
        '<button class="dic-edit-btn" onclick="removeExtraDoc(\''+targa+'\','+idx+')">✕</button>'+
      '</div></div>';
  }).join('');
}

function addExtraDoc(targa){
  const nome=prompt('Nome documento:');
  if(!nome) return;
  const scad=prompt('Data scadenza (YYYY-MM-DD, lascia vuoto se nessuna):')||'';
  const v=vehicles[targa];
  if(!v.docs) v.docs={};
  if(!v.docs.extra) v.docs.extra=[];
  v.docs.extra.push({nome:nome,dataScadenza:scad,dataEmissione:'',costo:'',note:''});
  save();
  renderExtraDocs(targa);
  toast('Documento aggiunto');
}

function removeExtraDoc(targa,idx){
  const v=vehicles[targa];
  if(!v||!v.docs||!v.docs.extra) return;
  v.docs.extra.splice(idx,1);
  save();
  renderExtraDocs(targa);
}


// ── TAB 3: Manutenzioni ──────────────────────
function renderTabManutenzioni(targa){
  const el = document.getElementById('vt-maint-list');
  if(!el) return;
  const maint = interventi.filter(i=>i.targa===targa).sort((a,b)=>new Date(b.dataIn)-new Date(a.dataIn));
  if(!maint.length){
    el.innerHTML='<div class="empty-state"><div class="empty-state-icon">🔧</div><div class="empty-state-title">Nessun intervento registrato</div><div class="empty-state-sub">Gli interventi creati in Officina appariranno qui automaticamente</div></div>';
    return;
  }
  el.innerHTML=`<div class="maint-timeline">`+maint.map(i=>{
    const isOverdue=i.dataPrev&&!i.dataOut&&i.dataPrev<today.toISOString().slice(0,10);
    return `<div class="mt-item">
      <div class="mt-dot ${i.stato}">${TIPO_ICONS[i.tipo]||'🔧'}</div>
      <div class="mt-content">
        <div style="display:flex;align-items:center;gap:8px;flex-wrap:wrap">
          <div class="mt-title">${i.tipo}</div>
          <span class="maint-badge mb-${i.stato}">${STATO_LABELS[i.stato]}</span>
          <span class="maint-priority mp-${i.priorita}">${i.priorita}</span>
          ${isOverdue?'<span style="font-size:10px;color:#A32D2D;font-weight:600">⚠️ In ritardo</span>':''}
        </div>
        <div class="mt-meta">
          <span>📅 ${fmt(i.dataIn)}</span>
          ${i.dataPrev?`<span>⏳ Previsto: ${fmt(i.dataPrev)}</span>`:''}
          ${i.dataOut?`<span>✅ Chiuso: ${fmt(i.dataOut)}</span>`:''}
          ${i.km?`<span>🛣 ${Number(i.km).toLocaleString('it-IT')} km</span>`:''}
          ${i.officina?`<span>🏭 ${i.officina}</span>`:''}
        </div>
        <div class="mt-desc">${i.desc||''}</div>
        ${i.note?`<div class="mt-desc" style="color:#aaa;font-style:italic;margin-top:2px">${i.note}</div>`:''}
        <div style="margin-top:6px;display:flex;gap:6px">
          ${['aperto','in_corso','attesa','completato'].map(s=>
            `<button class="stato-btn${i.stato===s?' selected':''}" data-stato="${s}" style="font-size:11px;padding:3px 8px" onclick="cambiaStatoIntervento(${i.id},'${s}');renderTabManutenzioni('${targa}')">${{aperto:'🟡',in_corso:'🔵',attesa:'🟣',completato:'🟢'}[s]} ${STATO_LABELS[s]}</button>`
          ).join('')}
          <button class="edit-v-btn" onclick="showFormGarageFromScheda();editIntervento(${i.id})">✏️</button>
        </div>
      </div>
    </div>`;
  }).join('')+'</div>';
}

// ── TAB 4: Storico ───────────────────────────
function renderTabStorico(targa){
  const el = document.getElementById('vt-storico-list');
  if(!el) return;
  let eventi=[];
  // Movimenti
  movimenti.filter(m=>m.targa===targa).forEach(m=>{
    const pStor=calcPeriodo(m);
    const azStor=m.aziendaId&&clienti.find(function(c){return c.id===m.aziendaId;});
    const azNome=azStor?azStor.azienda:'';
    const condNome=m.autistId&&autisti.find(function(a){return a.id===m.autistId;});
    const condStr=condNome?condNome.nome+' '+condNome.cognome:m.conducente||'';
    const titUscita='Uscita'+(condStr?' — '+condStr:'')+(azNome?' ('+azNome+')':'');
    const subUscita='KM: '+(m.kmOut?Number(m.kmOut).toLocaleString('it-IT')+' km':'—')+(pStor&&!pStor.completato?' · In corso da '+pStor.giorni+' giorni':'');
    eventi.push({data:m.dataOut,tipo:'noleggio',icon:'🚗',title:titUscita,sub:subUscita});
    if(m.rientro){
      const kmP=pStor&&pStor.kmPercorsi!==null?pStor.kmPercorsi.toLocaleString('it-IT')+' km percorsi':'';
      eventi.push({data:m.rientro.dataIn,tipo:'noleggio',icon:'🏁',
        title:'Rientro — '+(pStor?pStor.giorni+' giorni totali':''),
        sub:'KM: '+(m.rientro.kmIn?Number(m.rientro.kmIn).toLocaleString('it-IT')+' km':'—')+(kmP?' · '+kmP:'')});
    }
  });
  // Manutenzioni
  interventi.filter(i=>i.targa===targa).forEach(i=>{
    eventi.push({data:i.dataIn,tipo:'manutenzione',icon:TIPO_ICONS[i.tipo]||'🔧',title:i.tipo,sub:STATO_LABELS[i.stato]});
    if(i.dataOut) eventi.push({data:i.dataOut,tipo:'manutenzione',icon:'✅',title:`${i.tipo} — Completato`,sub:i.officina||''});
  });
  // Sinistri
  sinistri.filter(s=>s.targa===targa).forEach(s=>{
    eventi.push({data:s.data,tipo:'sinistro',icon:'⚠️',title:'Sinistro registrato',sub:s.desc.slice(0,50)+'…'});
  });
  // Scadenze
  items.filter(i=>i.targa===targa).forEach(i=>{
    eventi.push({data:i.date,tipo:'documento',icon:'📋',title:`Scadenza ${i.cat}`,sub:fmt(i.date)});
  });
  eventi.sort((a,b)=>new Date(b.data)-new Date(a.data));
  if(!eventi.length){
    el.innerHTML='<div class="empty-state"><div class="empty-state-icon">🕐</div><div class="empty-state-title">Nessun evento registrato</div></div>';
    return;
  }
  el.innerHTML='<div class="storico-timeline">'+eventi.map(e=>`
    <div class="st-item">
      <div class="st-dot std-${e.tipo}">${e.icon}</div>
      <div class="st-content">
        <div class="st-title">${e.title}</div>
        <div class="st-sub">${e.sub}</div>
      </div>
      <span class="st-date">${fmt(e.data)}</span>
    </div>`).join('')+'</div>';
}

// ── TAB 5: Checklist ─────────────────────────
function renderTabChecklist(targa){
  const el = document.getElementById('vt-checklist-content');
  if(!el) return;
  // Recupera ultima uscita e ultimo rientro per questo mezzo
  const ultMovs = movimenti.filter(m=>m.targa===targa).sort((a,b)=>new Date(b.dataOut)-new Date(a.dataOut));
  const ultMov = ultMovs[0]||null;
  el.innerHTML=`
    <div style="display:grid;grid-template-columns:1fr 1fr;gap:1.25rem">
      <div>
        <div style="font-size:13px;font-weight:600;margin-bottom:.75rem;display:flex;align-items:center;gap:6px">🚗 Ultima uscita ${ultMov?fmt(ultMov.dataOut):'—'}</div>
        ${ultMov&&ultMov.checklistOut ? renderChecklistReadonly(ultMov.checklistOut, CHECKLIST_USCITA) : '<div style="color:#bbb;font-size:13px">Nessuna checklist compilata</div>'}
      </div>
      <div>
        <div style="font-size:13px;font-weight:600;margin-bottom:.75rem;display:flex;align-items:center;gap:6px">🏁 Ultimo rientro ${ultMov&&ultMov.rientro?fmt(ultMov.rientro.dataIn):'—'}</div>
        ${ultMov&&ultMov.rientro&&ultMov.rientro.checklistIn ? renderChecklistReadonly(ultMov.rientro.checklistIn, CHECKLIST_RIENTRO) : '<div style="color:#bbb;font-size:13px">Nessuna checklist compilata</div>'}
      </div>
    </div>
    ${ultMovs.length>1?`
    <div style="margin-top:1.5rem">
      <div style="font-size:12px;font-weight:600;color:#888;text-transform:uppercase;letter-spacing:.05em;margin-bottom:.75rem">Storico checklist (${ultMovs.length} movimenti)</div>
      <div style="display:flex;flex-direction:column;gap:6px">
        ${ultMovs.slice(0,5).map(m=>`
          <div style="background:#f5f4f0;border-radius:8px;padding:8px 12px;display:flex;align-items:center;gap:10px;font-size:12px">
            <span>📅 ${fmt(m.dataOut)}</span>
            <span style="flex:1">${m.conducente||'Conducente non specificato'}</span>
            <span>Uscita: ${m.checklistOut?checklistBadge(m.checklistOut):'<span style="color:#bbb">—</span>'}</span>
            <span>Rientro: ${m.rientro&&m.rientro.checklistIn?checklistBadge(m.rientro.checklistIn):'<span style="color:#bbb">—</span>'}</span>
          </div>`).join('')}
      </div>
    </div>`:''}`;
}

function renderChecklistReadonly(cl, voci){
  if(!cl) return '';
  const checked=Object.values(cl).filter(Boolean).length;
  const tot=voci.length;
  return `<div style="display:flex;flex-direction:column;gap:4px">
    ${voci.map(v=>`
      <div style="display:flex;align-items:center;gap:8px;font-size:12px;padding:4px 8px;border-radius:6px;background:${cl[v.id]?'#EAF3DE':'#f5f4f0'}">
        <span style="font-size:13px">${cl[v.id]?'✅':'⬜'}</span>
        <span style="color:${cl[v.id]?'#3B6D11':'#888'}">${v.label}</span>
      </div>`).join('')}
    <div style="margin-top:6px;font-size:11px;font-weight:600;color:${checked===tot?'#3B6D11':'#854F0B'}">${checked}/${tot} voci completate</div>
  </div>`;
}

// ── Patch: apertura form da scheda — torna alla flotta prima ──
function showFormGarageFromScheda(prefillTarga){
  if(_scedaVeicoloTarga) closeSchedaVeicolo();
  showFormGarage(prefillTarga);
}

// ── Render dati tab on click ────────────────────────────
document.addEventListener('click',function(e){
  if(e.target.classList.contains('veh-tab')&&e.target.dataset.tab==='dati'&&_scedaVeicoloTarga){
    setTimeout(()=>renderTabDati(_scedaVeicoloTarga),0);
  }
});


// ════════════════════════════════════════════
// OFFICINA — SEZIONE SEPARATA
// ════════════════════════════════════════════

function populateOffTargaSelect(){
  const targas=Object.keys(vehicles);
  const fopts='<option value="all">Tutti i mezzi</option>'+targas.map(t=>`<option value="${t}">${t}</option>`).join('');
  const el=document.getElementById('off-filter-targa');
  if(el) el.innerHTML=fopts;
}

function renderOfficina(){
  if(!loaded) return;
  const q=(document.getElementById('off-search')||{value:''}).value.toLowerCase();
  const ft=(document.getElementById('off-filter-targa')||{value:'all'}).value;
  const fs=(document.getElementById('off-filter-stato')||{value:'all'}).value;

  // KPI
  const tot=interventi.length;
  const open=interventi.filter(i=>i.stato==='aperto'||i.stato==='in_corso').length;
  const att=interventi.filter(i=>i.stato==='attesa').length;
  const done=interventi.filter(i=>i.stato==='completato').length;
  const se=(id,v)=>{const el=document.getElementById(id);if(el)el.textContent=v;};
  se('off-cnt-tot',tot);se('off-cnt-open',open);se('off-cnt-att',att);se('off-cnt-done',done);

  // Badge sidebar
  const nbOff=document.getElementById('nb-off');
  if(nbOff){nbOff.textContent=open+att;nbOff.style.display=(open+att)>0?'':'none';}

  // Kanban
  const filtered=interventi.filter(i=>{
    if(ft!=='all'&&i.targa!==ft) return false;
    if(fs!=='all'&&i.stato!==fs) return false;
    if(q&&!i.targa.toLowerCase().includes(q)&&!(i.tipo||'').toLowerCase().includes(q)&&!(i.desc||'').toLowerCase().includes(q)) return false;
    return true;
  });

  ['aperto','in_corso','attesa','completato'].forEach(s=>{
    const cards=filtered.filter(i=>i.stato===s).sort((a,b)=>new Date(b.dataIn)-new Date(a.dataIn));
    const cntEl=document.getElementById('off-kc-'+s);
    const listEl=document.getElementById('off-kc-cards-'+s);
    if(cntEl) cntEl.textContent=cards.length;
    if(!listEl) return;
    if(!cards.length){listEl.innerHTML='<div style="font-size:11px;color:#bbb;text-align:center;padding:12px 0">Nessuno</div>';return;}
    listEl.innerHTML=cards.map(i=>{
      const v=vehicles[i.targa]||{};
      const icon=TIPO_ICONS[i.tipo]||'🔧';
      const isOverdue=i.dataPrev&&!i.dataOut&&i.dataPrev<today.toISOString().slice(0,10);
      return `<div class="maint-card" onclick="showDetailIntervento(${i.id})">
        <div class="maint-card-top">
          <span class="maint-card-targa">${i.targa}</span>
          <span class="maint-card-tipo">${icon} ${i.tipo}</span>
          <span class="maint-card-data">${fmt(i.dataIn)}</span>
        </div>
        <div class="maint-card-desc">${(i.desc||'').slice(0,80)}${(i.desc||'').length>80?'…':''}</div>
        <div class="maint-card-footer">
          <span class="maint-badge mb-${i.stato}">${STATO_LABELS[i.stato]}</span>
          <span class="maint-priority mp-${i.priorita}">${i.priorita}</span>
          ${isOverdue?'<span style="font-size:10px;color:#A32D2D;font-weight:600;margin-left:auto">⚠️ In ritardo</span>':''}
          ${i.officina?`<span style="font-size:10px;color:#888;margin-left:auto">🏭 ${i.officina}</span>`:''}
        </div>
      </div>`;
    }).join('');
  });
}

// ════════════════════════════════════════════
// WIZARD NOLEGGI
// ════════════════════════════════════════════

let _wizStep=0;
let _wizAziendaId=null, _wizAutistaId=null, _wizTarga=null;

function openWizard(){
  _wizStep=0; _wizAziendaId=null; _wizAutistaId=null; _wizTarga=null;
  document.getElementById('nol-wizard').style.display='';
  document.getElementById('wiz-az-search').value='';
  document.getElementById('wiz-az-selected').style.display='none';
  document.getElementById('wiz-az-new-form').style.display='none';
  document.getElementById('wiz-az-dropdown').classList.remove('open');
  document.getElementById('wiz-next-0').disabled=true;
  document.getElementById('wiz-data-out').value=today.toISOString().slice(0,10);
  wizStep(0);
  document.getElementById('nol-wizard').scrollIntoView({behavior:'smooth',block:'start'});
  // Init checklist
  renderChecklist(CHECKLIST_USCITA,'cl-out-grid','cl-out-bar','cl-out-pct','cl-out');
}

function closeWizard(){
  document.getElementById('nol-wizard').style.display='none';
}

function wizStep(n){
  _wizStep=n;
  // Update step indicators
  document.querySelectorAll('.wizard-step').forEach((el,i)=>{
    el.classList.toggle('active',i===n);
    el.classList.toggle('done',i<n);
  });
  // Show/hide panels
  document.querySelectorAll('.wizard-panel').forEach((el,i)=>{
    el.classList.toggle('active',i===n);
  });
  // Step-specific init
  if(n===1) renderAutistiGrid();
  if(n===2) renderVehPicker();
  if(n===3) renderWizRiepilogo();
}

// ── Step 1: Ricerca azienda ──────────────────
function searchAzienda(q){
  const dd=document.getElementById('wiz-az-dropdown');
  const ql=q.trim().toLowerCase();
  if(!ql){dd.classList.remove('open');return;}
  const matches=clienti.filter(c=>c.azienda&&(c.azienda.toLowerCase().includes(ql)||(c.piva||'').includes(ql)));
  dd.classList.add('open');
  dd.innerHTML=(matches.length
    ? matches.slice(0,6).map(c=>`
      <div class="search-opt" onclick="selectAzienda(${c.id})">
        <span class="search-opt-icon">🏢</span>
        <div><div class="search-opt-main">${c.azienda}</div>
        <div class="search-opt-sub">${c.piva?'P.IVA '+c.piva:''}${c.tel?' · '+c.tel:''}</div></div>
      </div>`).join('')
    : '<div style="padding:10px 12px;font-size:12px;color:#aaa">Nessuna azienda trovata</div>'
  ) + '<div class="search-opt-new" onclick="showNewAziendaForm()">+ Crea nuova azienda</div>';
}

function selectAzienda(id){
  const c=clienti.find(x=>x.id===id);
  if(!c) return;
  _wizAziendaId=id;
  document.getElementById('wiz-az-dropdown').classList.remove('open');
  document.getElementById('wiz-az-search').value=c.azienda;
  const sel=document.getElementById('wiz-az-selected');
  sel.style.display='';
  sel.innerHTML=`<div class="selected-card azienda">
    <span class="selected-card-icon">🏢</span>
    <div class="selected-card-info">
      <div class="selected-card-name">${c.azienda}</div>
      <div class="selected-card-sub">${c.piva?'P.IVA: '+c.piva+' &nbsp;':''}${c.tel?'Tel: '+c.tel:''}</div>
    </div>
    <span class="selected-card-clear" onclick="clearAzienda()">✕ Cambia</span>
  </div>`;
  document.getElementById('wiz-next-0').disabled=false;
}

function clearAzienda(){
  _wizAziendaId=null;
  document.getElementById('wiz-az-selected').style.display='none';
  document.getElementById('wiz-az-search').value='';
  document.getElementById('wiz-next-0').disabled=true;
}

function showNewAziendaForm(){
  document.getElementById('wiz-az-dropdown').classList.remove('open');
  document.getElementById('wiz-az-new-form').style.display='';
}

function saveNuovaAzienda(){
  const nome=document.getElementById('naz-nome').value.trim();
  if(!nome){toast('Inserisci ragione sociale');return;}
  const c={
    id:nextCliId++, nome,
    azienda:nome,
    tel:document.getElementById('naz-tel').value.trim(),
    email:document.getElementById('naz-email').value.trim(),
    piva:document.getElementById('naz-piva').value.trim(),
    indirizzo:document.getElementById('naz-indirizzo').value.trim(),
    blacklist:false, motivoBl:'', note:'',
    patente:'', scadPatente:'', tipoDoc:'', nDoc:'', scadDoc:''
  };
  clienti.push(c);
  save();
  renderClienti();
  document.getElementById('wiz-az-new-form').style.display='none';
  selectAzienda(c.id);
  toast('Azienda creata');
}

// ── Step 2: Autisti ──────────────────────────
function renderAutistiGrid(){
  const grid=document.getElementById('wiz-autisti-grid');
  const infoEl=document.getElementById('wiz-aut-azienda-info');
  if(!grid) return;
  const az=clienti.find(c=>c.id===_wizAziendaId);
  if(infoEl&&az) infoEl.innerHTML=`<div style="font-size:12px;color:#666;margin-bottom:.5rem">Autisti associati a <strong>${az.azienda}</strong></div>`;

  const autistiAz=autisti.filter(a=>a.aziendaId===_wizAziendaId);
  if(!autistiAz.length){
    grid.innerHTML='<div style="font-size:13px;color:#aaa;padding:8px 0;grid-column:1/-1">Nessun autista associato — creane uno qui sotto.</div>';
    return;
  }
  const oggi=today.toISOString().slice(0,10);
  grid.innerHTML=autistiAz.map(a=>{
    const patScad=a.scadPatente&&a.scadPatente<oggi;
    const docScad=a.scadDoc&&a.scadDoc<oggi;
    const warn=patScad||docScad;
    const badgeCls=patScad||docScad?'acb-exp':a.scadPatente?'acb-ok':'acb-warn';
    const badgeLbl=patScad?'⚠️ Patente scaduta':docScad?'⚠️ Doc. scaduto':a.patente?'✓ Patente OK':'– Patente mancante';
    return `<div class="autista-card${_wizAutistaId===a.id?' selected':''}" onclick="selectAutista(${a.id})">
      <div class="autista-card-name">👤 ${a.nome} ${a.cognome}</div>
      <div class="autista-card-sub">${a.tel||'—'} ${a.patente?'· Pat. '+a.patente:''}</div>
      <span class="autista-card-badge ${badgeCls}">${badgeLbl}</span>
    </div>`;
  }).join('');
}

function selectAutista(id){
  _wizAutistaId=id;
  renderAutistiGrid();
  const a=autisti.find(x=>x.id===id);
  if(!a) return;
  const sel=document.getElementById('wiz-aut-selected');
  sel.style.display='';
  sel.innerHTML=`<div class="selected-card autista" style="margin-top:.75rem">
    <span class="selected-card-icon">👤</span>
    <div class="selected-card-info">
      <div class="selected-card-name">${a.nome} ${a.cognome}</div>
      <div class="selected-card-sub">${a.tel||''} ${a.patente?'· Pat. '+a.patente:''}</div>
    </div>
    <span class="selected-card-clear" onclick="clearAutista()">✕ Cambia</span>
  </div>`;
  document.getElementById('wiz-next-1').disabled=false;
}

function clearAutista(){
  _wizAutistaId=null;
  document.getElementById('wiz-aut-selected').style.display='none';
  document.getElementById('wiz-next-1').disabled=true;
  renderAutistiGrid();
}

function toggleNewAutistaForm(){
  const f=document.getElementById('wiz-aut-new-form');
  f.style.display=f.style.display==='none'?'':'none';
}

function saveNuovoAutista(){
  const nome=document.getElementById('nau-nome').value.trim();
  const cognome=document.getElementById('nau-cognome').value.trim();
  if(!nome||!cognome){toast('Inserisci nome e cognome');return;}
  const a={
    id:nextAutId++, nome, cognome,
    aziendaId:_wizAziendaId,
    tel:document.getElementById('nau-tel').value.trim(),
    patente:document.getElementById('nau-patente').value.trim(),
    scadPatente:document.getElementById('nau-scad-patente').value,
    tipoDoc:document.getElementById('nau-tipo-doc').value,
    nDoc:document.getElementById('nau-ndoc').value.trim(),
    scadDoc:document.getElementById('nau-scad-doc').value,
    note:document.getElementById('nau-note').value.trim(),
  };
  autisti.push(a);
  save();
  document.getElementById('wiz-aut-new-form').style.display='none';
  renderAutistiGrid();
  selectAutista(a.id);
  toast('Autista creato');
}

// ── Step 3: Veicolo ──────────────────────────
function renderVehPicker(){
  const grid=document.getElementById('wiz-veh-grid');
  if(!grid) return;
  const dataOut=document.getElementById('wiz-data-out').value;
  grid.innerHTML=Object.keys(vehicles).map(t=>{
    const v=vehicles[t];
    const stato=getStatoMezzo(t);
    const blocked=stato==='officina'||stato==='fuori_servizio';
    // Controlla conflitti data
    const conflict=dataOut&&movimenti.some(m=>m.targa===t&&!m.rientro&&m.dataOut<=dataOut);
    const isBlocked=blocked||conflict;
    const modello=[(v.marca||''),(v.modello||'')].filter(Boolean).join(' ')||v.tipo;
    const blockReason=stato==='officina'?'In officina':stato==='fuori_servizio'?'Fuori servizio':conflict?'Già noleggiato':'';
    return `<div class="veh-pick-card${_wizTarga===t?' selected':''}${isBlocked?' blocked':''}" data-targa="${t}" data-blocked="${isBlocked}" onclick="handleVehPick(this)" title="${isBlocked?blockReason:'Seleziona'}">
      <div style="display:flex;align-items:center;gap:6px;margin-bottom:4px">
        <span style="font-size:18px">${ICON[v.tipo]||'🚘'}</span>
        <span class="vpc-plate">${t}</span>
        ${!isBlocked?`<span class="veh-stato-badge vsb-disponibile" style="margin-left:auto;font-size:9px">Disponibile</span>`:''}
      </div>
      <div class="vpc-model">${modello}</div>
      <div class="vpc-meta">${v.tipo} ${v.km?'· '+Number(v.km).toLocaleString('it-IT')+' km':''} ${v.sede?'· '+v.sede:''}</div>
      ${isBlocked?`<div class="vpc-block-reason">⛔ ${blockReason}</div>`:''}
    </div>`;
  }).join('');
  if(!Object.keys(vehicles).length) grid.innerHTML='<div style="color:#bbb;font-size:13px;grid-column:1/-1">Nessun veicolo nel sistema</div>';
}

function handleVehPick(el){
  if(el.dataset.blocked==='true') return;
  selectVeicolo(el.dataset.targa);
}

function selectVeicolo(targa){
  _wizTarga=targa;
  renderVehPicker();
  const v=vehicles[targa]||{};
  const modello=[(v.marca||''),(v.modello||'')].filter(Boolean).join(' ')||v.tipo;
  const sel=document.getElementById('wiz-veh-selected');
  sel.style.display='';
  sel.innerHTML=`<div class="selected-card veicolo" style="margin-top:.75rem">
    <span class="selected-card-icon">${ICON[v.tipo]||'🚘'}</span>
    <div class="selected-card-info">
      <div class="selected-card-name"><span style="font-family:monospace">${targa}</span> — ${modello}</div>
      <div class="selected-card-sub">${v.tipo} ${v.km?'· '+Number(v.km).toLocaleString('it-IT')+' km':''} ${v.sede?'· '+v.sede:''}</div>
    </div>
    <span class="selected-card-clear" onclick="clearVeicolo()">✕ Cambia</span>
  </div>`;
  document.getElementById('wiz-next-2').disabled=false;
}

function clearVeicolo(){
  _wizTarga=null;
  document.getElementById('wiz-veh-selected').style.display='none';
  document.getElementById('wiz-next-2').disabled=true;
  renderVehPicker();
}

// ── Step 4: Riepilogo + uscita ───────────────
function renderWizRiepilogo(){
  const el=document.getElementById('wiz-riepilogo');
  if(!el) return;
  const az=clienti.find(c=>c.id===_wizAziendaId);
  const aut=autisti.find(a=>a.id===_wizAutistaId);
  const v=vehicles[_wizTarga]||{};
  const dataOut=document.getElementById('wiz-data-out').value;
  // Pre-fill hidden fields for addMovimento
  document.getElementById('s-targa').value=_wizTarga||'';
  document.getElementById('s-conducente').value=aut?`${aut.nome} ${aut.cognome}`:'';
  document.getElementById('s-data-out').value=dataOut||today.toISOString().slice(0,10);
  document.getElementById('s-ora-out').value=document.getElementById('wiz-ora-out').value||'';
  el.innerHTML=`<div style="display:grid;grid-template-columns:repeat(3,1fr);gap:8px">
    <div><div style="font-size:10px;color:#aaa;font-weight:700;text-transform:uppercase">Azienda</div><div style="font-size:13px;font-weight:600">${az?az.azienda:'—'}</div></div>
    <div><div style="font-size:10px;color:#aaa;font-weight:700;text-transform:uppercase">Autista</div><div style="font-size:13px;font-weight:600">${aut?aut.nome+' '+aut.cognome:'—'}</div></div>
    <div><div style="font-size:10px;color:#aaa;font-weight:700;text-transform:uppercase">Veicolo</div><div style="font-size:13px;font-weight:600;font-family:monospace">${_wizTarga||'—'}</div></div>
    <div><div style="font-size:10px;color:#aaa;font-weight:700;text-transform:uppercase">Data uscita</div><div style="font-size:13px;font-weight:600">${dataOut?fmt(dataOut):'—'}</div></div>
  </div>`;
}

// ── Patch addMovimento per wizard ────────────
const _origAddMovimento = addMovimento;
addMovimento = function(){
  // Se wizard aperto, salva info extra nel movimento
  const wizOpen = document.getElementById('nol-wizard') && document.getElementById('nol-wizard').style.display !== 'none';
  if(wizOpen){
    // I campi hidden s-targa, s-conducente, s-data-out già popolati da renderWizRiepilogo
    // Chiudiamo wizard dopo save
    const origPush = movimenti.length;
    _origAddMovimento();
    if(movimenti.length > origPush){
      const m=movimenti[movimenti.length-1];
      m.aziendaId=_wizAziendaId;
      m.autistId=_wizAutistaId;
      save();
      closeWizard();
    }
  } else {
    _origAddMovimento();
  }
};

// renderMov aggiorna direttamente gli elementi nel page-noleggi (stessi ID)


// Close search dropdowns on outside click
document.addEventListener('click',function(e){
  const dd=document.getElementById('wiz-az-dropdown');
  const inp=document.getElementById('wiz-az-search');
  if(dd&&inp&&!dd.contains(e.target)&&e.target!==inp) dd.classList.remove('open');
});


// ── TAB 6: Costi ─────────────────────────────
function renderTabCosti(targa){
  const el=document.getElementById('vt-costi-content');
  if(!el) return;
  const v=vehicles[targa]||{};
  const costi=(v.costi)||[];

  // KPI totali per categoria
  const totali={Carburante:0,Manutenzione:0,Assicurazione:0,Altro:0};
  costi.forEach(function(c){
    const k=totali.hasOwnProperty(c.tipo)?c.tipo:'Altro';
    totali[k]+=parseFloat(c.importo||0);
  });
  const totale=Object.values(totali).reduce(function(a,b){return a+b;},0);

  let html2='<div class="costi-summary">'+
    '<div class="costo-kpi"><div class="ck-val">€ '+totale.toLocaleString('it-IT',{minimumFractionDigits:0})+'</div><div class="ck-lbl">Totale</div></div>'+
    '<div class="costo-kpi"><div class="ck-val">€ '+totali.Carburante.toLocaleString('it-IT',{minimumFractionDigits:0})+'</div><div class="ck-lbl">⛽ Carburante</div></div>'+
    '<div class="costo-kpi"><div class="ck-val">€ '+totali.Manutenzione.toLocaleString('it-IT',{minimumFractionDigits:0})+'</div><div class="ck-lbl">🔧 Manutenzione</div></div>'+
  '</div>';

  // Form aggiungi costo
  html2+='<div class="scad-add-form" style="margin-bottom:1rem">'+
    '<div class="scad-add-title">+ Aggiungi costo</div>'+
    '<div class="doc-form-row">'+
      '<div class="fg"><label>Tipo</label><select id="nc-tipo-'+targa+'"><option>Carburante</option><option>Manutenzione</option><option>Assicurazione</option><option>Pedaggio</option><option>Multa</option><option>Altro</option></select></div>'+
      '<div class="fg"><label>Descrizione</label><input type="text" id="nc-desc-'+targa+'" placeholder="es. Rifornimento"></div>'+
      '<div class="fg"><label>Data</label><input type="date" id="nc-data-'+targa+'" value="'+today.toISOString().slice(0,10)+'"></div>'+
      '<div class="fg"><label>Importo (€)</label><input type="number" id="nc-importo-'+targa+'" placeholder="es. 85"></div>'+
    '</div>'+
    '<button class="doc-save-btn" onclick="addCosto(\''+targa+'\')">💾 Aggiungi</button>'+
  '</div>';

  // Lista costi
  if(!costi.length){
    html2+='<div style="color:#bbb;font-size:13px;text-align:center;padding:2rem">Nessun costo registrato</div>';
  } else {
    html2+='<div class="costi-list">';
    const TIPO_ICON={Carburante:'⛽',Manutenzione:'🔧',Assicurazione:'📄',Pedaggio:'🛣️',Multa:'🚨',Altro:'💰'};
    [...costi].sort(function(a,b){return new Date(b.data)-new Date(a.data);}).forEach(function(c){
      html2+='<div class="costo-row">'+
        '<span class="costo-row-tipo">'+(TIPO_ICON[c.tipo]||'💰')+'</span>'+
        '<div class="costo-row-desc">'+c.tipo+(c.desc?' — '+c.desc:'')+'</div>'+
        '<span class="costo-row-data">'+fmt(c.data)+'</span>'+
        '<span class="costo-row-val">€ '+parseFloat(c.importo||0).toLocaleString('it-IT',{minimumFractionDigits:2})+'</span>'+
        '<span class="costo-row-del" onclick="delCosto(\''+targa+'\','+c.id+')" title="Elimina">×</span>'+
      '</div>';
    });
    html2+='</div>';
  }

  el.innerHTML=html2;
}

function addCosto(targa){
  const v=vehicles[targa];
  if(!v) return;
  if(!v.costi) v.costi=[];
  const get=function(id){return (document.getElementById(id)||{value:''}).value.trim();};
  const importo=get('nc-importo-'+targa);
  if(!importo){toast('Inserisci importo');return;}
  const maxId=v.costi.reduce(function(m,c){return Math.max(m,c.id||0);},0);
  v.costi.push({id:maxId+1,tipo:get('nc-tipo-'+targa),desc:get('nc-desc-'+targa),data:get('nc-data-'+targa),importo:importo,note:''});
  save();
  renderTabCosti(targa);
  toast('💰 Costo aggiunto');
}

function delCosto(targa,id){
  const v=vehicles[targa];
  if(!v||!v.costi) return;
  v.costi=v.costi.filter(function(c){return c.id!==id;});
  save();
  renderTabCosti(targa);
  toast('Costo eliminato');
}



// ════════════════════════════════════════════
// MODIFICA NOLEGGIO — CRUD COMPLETO
// ════════════════════════════════════════════

function openEditNol(id){
  const m=movimenti.find(function(x){return x.id===id;});
  if(!m) return;
  const panel=document.getElementById('edit-panel-'+id);
  if(!panel) return;

  // Toggle: se già aperto, chiudi
  if(panel.style.display!=='none'&&panel.innerHTML!==''){
    panel.style.display='none';
    panel.innerHTML='';
    return;
  }

  const c=m.contratto||{};
  const aut=m.autistId&&autisti.find(function(a){return a.id===m.autistId;});
  const az=m.aziendaId&&clienti.find(function(cl){return cl.id===m.aziendaId;});

  // Calcola costo totale automatico
  function calcTotale(canone,durata){
    const c=parseFloat(canone)||0;
    const d=parseInt(durata)||0;
    return c&&d?(c*d).toFixed(2):'';
  }

  const storico=m.storico||[];
  const storicoHtml=storico.length
    ? storico.slice().reverse().map(function(s){
        return '<div class="et-item">'+
          '<div class="et-dot">✎</div>'+
          '<div class="et-content">'+
            '<div class="et-what">'+s.campo+'</div>'+
            '<div class="et-detail">'+
              (s.vecchio?'<span style="color:#aaa;text-decoration:line-through">'+s.vecchio+'</span> → ':'') +
              '<strong>'+s.nuovo+'</strong>'+
            '</div>'+
          '</div>'+
          '<span class="et-date">'+fmt(s.data)+'</span>'+
        '</div>';
      }).join('')
    : '<div style="color:#bbb;font-size:12px;padding:8px 0">Nessuna modifica registrata</div>';

  panel.innerHTML =
    '<div class="edit-nol-title">✏️ Modifica noleggio #'+id+' — '+m.targa+'</div>'+

    // Tab navigation
    '<div class="edit-nol-tabs">'+
      '<button class="ent active" onclick="switchNolTab('+id+',\'dati\')" id="ent-'+id+'-dati">📋 Dati</button>'+
      '<button class="ent" onclick="switchNolTab('+id+',\'contratto\')" id="ent-'+id+'-contratto">📄 Contratto</button>'+
      '<button class="ent" onclick="switchNolTab('+id+',\'stato\')" id="ent-'+id+'-stato">🏷️ Stato</button>'+
      '<button class="ent" onclick="switchNolTab('+id+',\'storico\')" id="ent-'+id+'-storico">🕐 Storico ('+storico.length+')</button>'+
    '</div>'+

    // TAB 1: Dati uscita/rientro
    '<div class="ent-panel active" id="enp-'+id+'-dati">'+
      '<div class="contratto-grid">'+
        '<div class="fg"><label>Targa *</label>'+
          '<select id="en-targa-'+id+'">'+
            Object.keys(vehicles).map(function(t){
              return '<option value="'+t+'"'+(m.targa===t?' selected':'')+'>'+t+' — '+vehicles[t].tipo+'</option>';
            }).join('')+
          '</select></div>'+
        '<div class="fg"><label>Conducente / Autista</label>'+
          '<input type="text" id="en-conducente-'+id+'" value="'+(m.conducente||'')+'" placeholder="Nome cognome"></div>'+
        '<div class="fg"><label>Data uscita *</label>'+
          '<input type="date" id="en-dataOut-'+id+'" value="'+(m.dataOut||'')+'"></div>'+
        '<div class="fg"><label>Ora uscita</label>'+
          '<input type="time" id="en-oraOut-'+id+'" value="'+(m.oraOut||'')+'"></div>'+
      '</div>'+
      '<div class="contratto-grid">'+
        '<div class="fg"><label>KM uscita</label>'+
          '<input type="number" id="en-kmOut-'+id+'" value="'+(m.kmOut||'')+'" placeholder="es. 45230"></div>'+
        '<div class="fg"><label>Carburante uscita (%)</label>'+
          '<input type="number" id="en-gasolioOut-'+id+'" value="'+(m.gasolioOut||'')+'" min="0" max="100"></div>'+
        '<div class="fg"><label>Danni uscita</label>'+
          '<input type="text" id="en-danniOut-'+id+'" value="'+(m.danniOut||'')+'" placeholder="es. Nessuno"></div>'+
        '<div class="fg"><label>Note uscita</label>'+
          '<input type="text" id="en-noteOut-'+id+'" value="'+(m.noteOut||'')+'"></div>'+
      '</div>'+
      (m.rientro?
        '<div style="font-size:11px;font-weight:700;text-transform:uppercase;letter-spacing:.05em;color:#3B6D11;margin:.75rem 0 .5rem">Rientro</div>'+
        '<div class="contratto-grid">'+
          '<div class="fg"><label>Data rientro</label>'+
            '<input type="date" id="en-dataIn-'+id+'" value="'+(m.rientro.dataIn||'')+'"></div>'+
          '<div class="fg"><label>Ora rientro</label>'+
            '<input type="time" id="en-oraIn-'+id+'" value="'+(m.rientro.oraIn||'')+'"></div>'+
          '<div class="fg"><label>KM rientro</label>'+
            '<input type="number" id="en-kmIn-'+id+'" value="'+(m.rientro.kmIn||'')+'"></div>'+
          '<div class="fg"><label>Carburante rientro (%)</label>'+
            '<input type="number" id="en-gasolioIn-'+id+'" value="'+(m.rientro.gasolioIn||'')+'" min="0" max="100"></div>'+
        '</div>'+
        '<div class="contratto-grid r2">'+
          '<div class="fg"><label>Danni al rientro</label>'+
            '<input type="text" id="en-danniIn-'+id+'" value="'+(m.rientro.danniIn||'')+'" placeholder="es. Nessuno"></div>'+
          '<div class="fg"><label>Note rientro</label>'+
            '<input type="text" id="en-noteIn-'+id+'" value="'+(m.rientro.noteIn||'')+'"></div>'+
        '</div>'
      : '<div style="font-size:12px;color:#aaa;padding:8px 0">Rientro non ancora registrato.</div>')+
    '</div>'+

    // TAB 2: Contratto
    '<div class="ent-panel" id="enp-'+id+'-contratto">'+
      '<div class="contratto-grid">'+
        '<div class="fg"><label>Società di noleggio</label>'+
          '<input type="text" id="en-societa-'+id+'" value="'+(c.societa||'')+'" placeholder="es. Arval, LeasePlan"></div>'+
        '<div class="fg"><label>N° contratto</label>'+
          '<input type="text" id="en-numContr-'+id+'" value="'+(c.numContratto||'')+'" placeholder="CT-2024-001"></div>'+
        '<div class="fg"><label>Data inizio</label>'+
          '<input type="date" id="en-dataInizio-'+id+'" value="'+(c.dataInizio||m.dataOut||'')+'"></div>'+
        '<div class="fg"><label>Data fine</label>'+
          '<input type="date" id="en-dataFine-'+id+'" value="'+(c.dataFine||'')+'" oninput="calcCostoNol('+id+')"></div>'+
      '</div>'+
      '<div class="contratto-grid">'+
        '<div class="fg"><label>Durata (mesi)</label>'+
          '<input type="number" id="en-durata-'+id+'" value="'+(c.durataMesi||'')+'" placeholder="es. 24" oninput="calcCostoNol('+id+')"></div>'+
        '<div class="fg"><label>Canone mensile (€)</label>'+
          '<input type="number" id="en-canone-'+id+'" value="'+(c.canone||'')+'" placeholder="es. 480" oninput="calcCostoNol('+id+')"></div>'+
        '<div class="fg"><label>Costo totale (€)</label>'+
          '<input type="number" id="en-costoTot-'+id+'" value="'+(c.costoTotale||'')+'" placeholder="Calcolato auto"></div>'+
        '<div class="fg"><label>KM inclusi</label>'+
          '<input type="number" id="en-kmIncl-'+id+'" value="'+(c.kmInclusi||'')+'" placeholder="es. 30000"></div>'+
      '</div>'+
      '<div class="contratto-grid r3">'+
        '<div class="fg"><label>Costo KM extra (€/km)</label>'+
          '<input type="number" id="en-kmExtra-'+id+'" value="'+(c.kmExtra||'')+'" placeholder="es. 0.08" step="0.01"></div>'+
        '<div class="fg"><label>Deposito cauzionale (€)</label>'+
          '<input type="number" id="en-deposito-'+id+'" value="'+(c.deposito||'')+'" placeholder="es. 1500"></div>'+
        '<div class="fg"><label>Metodo pagamento</label>'+
          '<select id="en-pagamento-'+id+'">'+
            ['','Bonifico','Carta di credito','RID bancario','Contanti','Altro'].map(function(p){
              return '<option'+(c.pagamento===p?' selected':'')+'>'+p+'</option>';
            }).join('')+
          '</select></div>'+
      '</div>'+
      '<div class="contratto-grid r2" style="margin-bottom:4px">'+
        '<div class="fg"><label>Note contratto</label>'+
          '<textarea id="en-noteContr-'+id+'" style="height:60px">'+(c.note||'')+'</textarea></div>'+
        '<div class="fg">'+
          '<div class="costo-summary-nol" id="en-riepilogo-'+id+'" style="margin-top:24px">'+
            '<div class="csn-item"><div class="csn-val" id="en-cs-canone-'+id+'">'+(c.canone?'€ '+Number(c.canone).toLocaleString('it-IT'):'—')+'</div><div class="csn-lbl">Canone/mese</div></div>'+
            '<div class="csn-item"><div class="csn-val" id="en-cs-durata-'+id+'">'+(c.durataMesi?c.durataMesi+' mesi':'—')+'</div><div class="csn-lbl">Durata</div></div>'+
            '<div class="csn-item"><div class="csn-val" id="en-cs-totale-'+id+'">'+(c.costoTotale?'€ '+Number(c.costoTotale).toLocaleString('it-IT'):'—')+'</div><div class="csn-lbl">Totale</div></div>'+
            '<div class="csn-item"><div class="csn-val" id="en-cs-km-'+id+'">'+(c.kmInclusi?Number(c.kmInclusi).toLocaleString('it-IT')+' km':'—')+'</div><div class="csn-lbl">KM inclusi</div></div>'+
          '</div>'+
        '</div>'+
      '</div>'+
    '</div>'+

    // TAB 3: Stato contratto
    '<div class="ent-panel" id="enp-'+id+'-stato">'+
      '<div class="fg" style="margin-bottom:.75rem"><label>Stato contratto</label>'+
        '<div class="stato-nol-selector">'+
          ['aperto','attivo','scaduto','chiuso','rinnovato'].map(function(s){
            const lbl={aperto:'🟡 Aperto',attivo:'🟢 Attivo',scaduto:'🔴 Scaduto',chiuso:'⬛ Chiuso',rinnovato:'🔵 Rinnovato'}[s];
            return '<button class="sns-btn'+(((c.stato||'aperto')===s)?' selected':'')+'" data-s="'+s+'" onclick="selectStatoNol('+id+',\''+s+'\')">'+lbl+'</button>';
          }).join('')+
        '</div>'+
        '<input type="hidden" id="en-stato-'+id+'" value="'+(c.stato||'aperto')+'">'+
      '</div>'+
      '<div class="fg"><label>Motivazione cambio stato (opzionale)</label>'+
        '<input type="text" id="en-motivo-'+id+'" placeholder="es. Contratto rinnovato per ulteriori 12 mesi"></div>'+
      '<div style="margin-top:.75rem;padding:.75rem;background:#fff;border-radius:8px;font-size:12px;color:#888">'+
        '💡 Cambiando lo stato, il sistema aggiorna automaticamente il badge sulla scheda, le notifiche e la dashboard.'+
      '</div>'+
    '</div>'+

    // TAB 4: Storico modifiche
    '<div class="ent-panel" id="enp-'+id+'-storico">'+
      '<div style="font-size:12px;color:#888;margin-bottom:.75rem">Tutte le modifiche apportate a questo noleggio.</div>'+
      '<div class="edit-timeline">'+storicoHtml+'</div>'+
    '</div>'+

    // Azioni
    '<div style="display:flex;gap:8px;margin-top:1rem;padding-top:.75rem;border-top:.5px solid rgba(0,0,0,.08)">'+
      '<button class="btn-primary" onclick="saveEditNol('+id+')">💾 Salva modifiche</button>'+
      '<button onclick="document.getElementById(\'edit-panel-'+id+'\').style.display=\'none\';document.getElementById(\'edit-panel-'+id+'\').innerHTML=\'\'">✕ Annulla</button>'+
      (m.rientro?'':`<button style="background:#EAF3DE;color:#3B6D11;border-color:#C0DD97" onclick="rinnovaNoleggio(${id})">🔄 Rinnova</button>`)+
    '</div>';

  panel.style.display='block';
  panel.scrollIntoView({behavior:'smooth',block:'start'});
}

function switchNolTab(id, tab){
  ['dati','contratto','stato','storico'].forEach(function(t){
    const btn=document.getElementById('ent-'+id+'-'+t);
    const pnl=document.getElementById('enp-'+id+'-'+t);
    if(btn) btn.classList.toggle('active',t===tab);
    if(pnl) pnl.classList.toggle('active',t===tab);
  });
}

function selectStatoNol(id, stato){
  document.querySelectorAll('#enp-'+id+'-stato .sns-btn').forEach(function(b){
    b.classList.toggle('selected', b.dataset.s===stato);
  });
  const inp=document.getElementById('en-stato-'+id);
  if(inp) inp.value=stato;
}

function calcCostoNol(id){
  const canone=parseFloat((document.getElementById('en-canone-'+id)||{value:0}).value)||0;
  const durata=parseInt((document.getElementById('en-durata-'+id)||{value:0}).value)||0;
  const totale=canone&&durata?canone*durata:0;
  const km=(document.getElementById('en-kmIncl-'+id)||{value:''}).value;

  // Auto-fill costo totale
  const ctEl=document.getElementById('en-costoTot-'+id);
  if(ctEl&&totale&&!ctEl.value) ctEl.value=totale.toFixed(2);

  // Aggiorna riepilogo
  const csCanone=document.getElementById('en-cs-canone-'+id);
  const csDurata=document.getElementById('en-cs-durata-'+id);
  const csTotale=document.getElementById('en-cs-totale-'+id);
  const csKm=document.getElementById('en-cs-km-'+id);
  if(csCanone) csCanone.textContent=canone?'€ '+canone.toLocaleString('it-IT'):'—';
  if(csDurata) csDurata.textContent=durata?durata+' mesi':'—';
  if(csTotale) csTotale.textContent=totale?'€ '+totale.toLocaleString('it-IT'):'—';
  if(csKm)     csKm.textContent=km?Number(km).toLocaleString('it-IT')+' km':'—';
}

function saveEditNol(id){
  const m=movimenti.find(function(x){return x.id===id;});
  if(!m) return;

  const get=function(field){
    const el=document.getElementById('en-'+field+'-'+id);
    return el?(el.value||'').trim():'';
  };

  // Validazione
  const nuovaTarga=get('targa');
  const nuovaDataOut=get('dataOut');
  if(!nuovaTarga||!nuovaDataOut){
    toast('⚠️ Targa e data uscita obbligatorie');
    return;
  }
  // Controlla date: data fine > data inizio
  const dataInizio=get('dataInizio');
  const dataFine=get('dataFine');
  if(dataInizio&&dataFine&&dataFine<dataInizio){
    toast('⚠️ Data fine contratto prima di data inizio');
    return;
  }
  // Controlla KM: rientro > uscita
  const kmOut=get('kmOut');
  const kmIn=m.rientro?get('kmIn'):'';
  if(kmOut&&kmIn&&parseInt(kmIn)<parseInt(kmOut)){
    toast('⚠️ KM rientro inferiori a KM uscita');
    return;
  }

  // Registra storico modifiche
  if(!m.storico) m.storico=[];
  const now=today.toISOString().slice(0,10);
  const c=m.contratto||{};

  function logChange(campo, vecchio, nuovo){
    const v=String(vecchio||'').trim();
    const n=String(nuovo||'').trim();
    if(v!==n && (v||n)){
      m.storico.push({data:now,campo:campo,vecchio:v,nuovo:n});
    }
  }

  // Log campi principali
  logChange('Targa', m.targa, nuovaTarga);
  logChange('Conducente', m.conducente, get('conducente'));
  logChange('Data uscita', m.dataOut, nuovaDataOut);
  logChange('KM uscita', m.kmOut, kmOut);
  logChange('Danni uscita', m.danniOut, get('danniOut'));
  logChange('Società noleggio', c.societa, get('societa'));
  logChange('N° contratto', c.numContratto, get('numContr'));
  logChange('Data fine', c.dataFine, dataFine);
  logChange('Canone mensile', c.canone, get('canone'));
  logChange('Costo totale', c.costoTotale, get('costoTot'));
  logChange('KM inclusi', c.kmInclusi, get('kmIncl'));
  logChange('Stato contratto', c.stato||'aperto', get('stato'));
  if(get('motivo')) m.storico.push({data:now,campo:'Nota operatore',vecchio:'',nuovo:get('motivo')});

  // Aggiorna dati uscita
  m.targa      = nuovaTarga;
  m.conducente = get('conducente');
  m.dataOut    = nuovaDataOut;
  m.oraOut     = get('oraOut');
  m.kmOut      = kmOut;
  m.gasolioOut = get('gasolioOut');
  m.danniOut   = get('danniOut');
  m.noteOut    = get('noteOut');

  // Aggiorna rientro se presente
  if(m.rientro){
    m.rientro.dataIn    = get('dataIn');
    m.rientro.oraIn     = get('oraIn');
    m.rientro.kmIn      = kmIn;
    m.rientro.gasolioIn = get('gasolioIn');
    m.rientro.danniIn   = get('danniIn');
    m.rientro.noteIn    = get('noteIn');
  }

  // Aggiorna contratto
  m.contratto={
    societa:     get('societa'),
    numContratto:get('numContr'),
    dataInizio:  dataInizio||nuovaDataOut,
    dataFine:    dataFine,
    durataMesi:  get('durata'),
    canone:      get('canone'),
    costoTotale: get('costoTot'),
    kmInclusi:   get('kmIncl'),
    kmExtra:     get('kmExtra'),
    deposito:    get('deposito'),
    pagamento:   get('pagamento'),
    note:        get('noteContr'),
    stato:       get('stato')||'aperto',
  };

  // Sincronizzazione automatica
  // 1. Aggiorna stato veicolo
  const v=vehicles[nuovaTarga];
  if(v){
    if(m.rientro) v.statoOp='disponibile';
    else v.statoOp='noleggiato';
  }

  // 2. Se ha data fine contratto → sync scadenza items
  if(m.contratto.dataFine&&nuovaTarga){
    const existing=items.find(function(i){return i.targa===nuovaTarga&&i.cat==='Contratto cliente';});
    if(existing){ existing.date=m.contratto.dataFine; }
    else { items.push({id:nextId++,targa:nuovaTarga,cat:'Contratto cliente',date:m.contratto.dataFine,note:m.contratto.societa||''}); }
  }

  save();

  // Chiudi pannello e ricarica lista
  const panel=document.getElementById('edit-panel-'+id);
  if(panel){panel.style.display='none';panel.innerHTML='';}
  renderMov();
  renderDashboard();
  toast('✅ Noleggio #'+id+' aggiornato — '+m.storico.length+' modifiche nel log');
}

function rinnovaNoleggio(id){
  const m=movimenti.find(function(x){return x.id===id;});
  if(!m) return;
  if(!confirm('Rinnova il noleggio #'+id+'?\n\nVerrà creato un nuovo noleggio con gli stessi dati, partendo da oggi.')) return;

  const c=m.contratto||{};
  const nuovoId=nextMovId++;
  const nuovo={
    id:nuovoId,
    targa:m.targa,
    conducente:m.conducente,
    aziendaId:m.aziendaId,
    autistId:m.autistId,
    dataOut:today.toISOString().slice(0,10),
    oraOut:'',
    kmOut:vehicles[m.targa]?vehicles[m.targa].km||'':'',
    gasolioOut:'',
    danniOut:'',
    noteOut:'Rinnovo da noleggio #'+id,
    checklistOut:null,
    rientro:null,
    contratto:{
      societa:c.societa||'',
      numContratto:(c.numContratto?c.numContratto+'-R':''),
      dataInizio:today.toISOString().slice(0,10),
      dataFine:'',
      durataMesi:c.durataMesi||'',
      canone:c.canone||'',
      costoTotale:'',
      kmInclusi:c.kmInclusi||'',
      kmExtra:c.kmExtra||'',
      deposito:c.deposito||'',
      pagamento:c.pagamento||'',
      note:'Rinnovo da contratto #'+id,
      stato:'attivo',
    },
    storico:[{data:today.toISOString().slice(0,10),campo:'Creazione',vecchio:'',nuovo:'Rinnovato da noleggio #'+id}],
  };
  movimenti.push(nuovo);

  // Segna originale come rinnovato
  m.contratto.stato='rinnovato';
  m.storico=m.storico||[];
  m.storico.push({data:today.toISOString().slice(0,10),campo:'Rinnovo',vecchio:'aperto',nuovo:'Rinnovato → nuovo ID #'+nuovoId});

  save();
  renderMov();
  toast('🔄 Noleggio rinnovato — nuova scheda #'+nuovoId+' creata');
}


// ════════════════════════════════════════════
// NUOVO VEICOLO — dalla sezione Mezzi
// ════════════════════════════════════════════

function toggleNewVehicleForm(){
  const f=document.getElementById('new-veh-form');
  if(!f) return;
  const isOpen=f.style.display!=='none';
  f.style.display=isOpen?'none':'';
  if(!isOpen) f.scrollIntoView({behavior:'smooth',block:'start'});
}

function setNVPoss(poss){
  document.getElementById('nv-poss').value=poss;
  document.getElementById('pt-prop').classList.toggle('active',poss==='proprieta');
  document.getElementById('pt-nol').classList.toggle('active',poss==='noleggio');
  document.getElementById('nv-nol-section').style.display=poss==='noleggio'?'':'none';
}

function saveNewVehicle(){
  const targa=(document.getElementById('nv-targa').value||'').trim().toUpperCase();
  if(!targa){
    document.getElementById('nv-targa').focus();
    toast('⚠️ Inserisci la targa');
    return;
  }
  if(vehicles[targa]){
    toast('⚠️ Targa '+targa+' già presente nel sistema');
    document.getElementById('nv-targa').focus();
    return;
  }
  // Validazione date noleggio
  const nvIniFor=get('nv-ini-for');
  const nvScadFor=get('nv-scad-for');
  if(poss==='noleggio'&&nvIniFor&&nvScadFor&&nvScadFor<nvIniFor){
    toast('⚠️ La data fine contratto è precedente alla data inizio');
    return;
  }
  const get=function(id){return (document.getElementById(id)||{value:''}).value.trim();};
  const poss=get('nv-poss')||'proprieta';

  vehicles[targa]={
    tipo:get('nv-tipo')||'Auto',
    poss:poss,
    marca:get('nv-marca'),
    modello:get('nv-modello'),
    vin:get('nv-vin'),
    anno:get('nv-anno'),
    alimentazione:get('nv-alimentazione'),
    cambio:get('nv-cambio'),
    km:get('nv-km')||'0',
    portata:get('nv-portata'),
    volume:get('nv-volume'),
    sede:get('nv-sede'),
    note:get('nv-note'),
    statoOp:'disponibile',
    docs:{},
    costi:[],
    allegati:[],
    kmHistory:[],
    // campi noleggio
    fornitore:poss==='noleggio'?get('nv-fornitore'):'',
    iniFor:poss==='noleggio'?get('nv-ini-for'):'',
    scadFor:poss==='noleggio'?get('nv-scad-for'):'',
    canone:poss==='noleggio'?get('nv-canone'):'',
    cliente:poss==='noleggio'?get('nv-cliente'):'',
    piva:poss==='noleggio'?get('nv-piva'):'',
    tel:'',
    email:'',
    indirizzo:'',
    ncontr:poss==='noleggio'?get('nv-ncontr'):'',
    iniCli:'',
    scadCli:poss==='noleggio'?get('nv-scad-cli'):'',
    scadFor:poss==='noleggio'?get('nv-scad-for'):'',
    scadCli:poss==='noleggio'?get('nv-scad-cli'):'',
  };

  // Aggiungi scadenza contratto a items se presente
  if(poss==='noleggio'&&get('nv-scad-for')){
    items.push({id:nextId++,targa:targa,cat:'Contratto fornitore',date:get('nv-scad-for'),note:get('nv-fornitore')});
  }
  if(poss==='noleggio'&&get('nv-scad-cli')){
    items.push({id:nextId++,targa:targa,cat:'Contratto cliente',date:get('nv-scad-cli'),note:get('nv-cliente')});
  }

  save();
  populateTargaSelect();
  populateGarTargaSelect();
  populateOffTargaSelect();
  populateSinTargaSelect();

  // Reset form
  ['nv-targa','nv-marca','nv-modello','nv-vin','nv-anno','nv-km',
   'nv-portata','nv-volume','nv-sede','nv-note','nv-fornitore',
   'nv-cliente','nv-piva','nv-ncontr','nv-canone'].forEach(function(id){
    const el=document.getElementById(id);
    if(el) el.value='';
  });
  ['nv-ini-for','nv-scad-for','nv-scad-cli'].forEach(function(id){
    const el=document.getElementById(id);
    if(el) el.value='';
  });
  setNVPoss('proprieta');

  toggleNewVehicleForm();
  renderGarage();
  renderDashboard();
  toast('✅ Veicolo '+targa+' aggiunto alla flotta');
}


// ════════════════════════════════════════════
// CALCOLO PERIODO NOLEGGIO
// ════════════════════════════════════════════
function calcPeriodo(m){
  if(!m||!m.dataOut) return null;
  const dOut=new Date(m.dataOut);
  dOut.setHours(0,0,0,0);
  const dIn=m.rientro&&m.rientro.dataIn?new Date(m.rientro.dataIn):null;
  if(dIn) dIn.setHours(0,0,0,0);
  const dFine=dIn||today;
  const giorni=Math.round((dFine-dOut)/86400000);
  const kmPercorsi=(m.kmOut&&m.rientro&&m.rientro.kmIn)
    ?Number(m.rientro.kmIn)-Number(m.kmOut):null;
  const completato=!!m.rientro;
  // Ritardo = mezzo non rientrato oltre la data fine contratto
  const c_rit=m.contratto||{};
  const dataFineContr=c_rit.dataFine;
  const inRitardo=!completato&&(
    dataFineContr?today>new Date(dataFineContr):giorni>30
  );
  // Contratto: durata prevista
  const c=m.contratto||{};
  const durPrev=c.durataMesi?parseInt(c.durataMesi)*30:null;
  const percAvanz=durPrev?Math.min(100,Math.round(giorni/durPrev*100)):null;
  return {
    dOut,dIn,giorni,kmPercorsi,completato,inRitardo,
    durPrev,percAvanz,
    stato: completato?'completato':inRitardo?'ritardo':'inCorso',
    dataOutFmt:fmt(m.dataOut),
    dataInFmt:dIn?fmt(m.rientro.dataIn):'In corso',
  };
}

function periodoBarHTML(m){
  const p=calcPeriodo(m);
  if(!p) return '';
  const STATO_LBL={completato:'✅ Completato',inCorso:'🔄 In corso',ritardo:'⚠️ In ritardo'};
  const STATO_CLS={completato:'pb-completato',inCorso:'pb-inCorso',ritardo:'pb-ritardo'};
  let pbHTML='';
  if(p.percAvanz!==null){
    pbHTML='<div class="periodo-progressbar">'+
      '<div class="periodo-lbl">Avanzamento periodo</div>'+
      '<div class="periodo-pb-wrap"><div class="periodo-pb-fill" style="width:'+p.percAvanz+'%;background:'+(p.stato==='completato'?'#639922':p.stato==='ritardo'?'#E24B4A':'#FF6600')+'"></div></div>'+
      '<div class="periodo-pb-lbl">'+p.percAvanz+'% di '+p.durPrev+' giorni previsti</div>'+
    '</div>';
  }
  return '<div class="periodo-bar">'+
    '<span class="periodo-badge '+STATO_CLS[p.stato]+'">'+STATO_LBL[p.stato]+'</span>'+
    '<div class="periodo-sep"></div>'+
    '<div class="periodo-col"><span class="periodo-lbl">Uscita</span><span class="periodo-val">'+p.dataOutFmt+'</span></div>'+
    '<div class="periodo-col"><span class="periodo-lbl">Rientro</span><span class="periodo-val '+(p.completato?'verde':'arancio')+'">'+p.dataInFmt+'</span></div>'+
    '<div class="periodo-sep"></div>'+
    '<div class="periodo-col"><span class="periodo-lbl">Giorni</span><span class="periodo-val '+(p.stato==='ritardo'?'arancio':p.completato?'verde':'')+'">'+p.giorni+' gg</span></div>'+
    (p.kmPercorsi!==null?'<div class="periodo-col"><span class="periodo-lbl">KM percorsi</span><span class="periodo-val">'+p.kmPercorsi.toLocaleString('it-IT')+' km</span></div>':'')+
    pbHTML+
  '</div>';
}

</script>
</body>
</html>
