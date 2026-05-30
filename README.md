<!DOCTYPE html>
<html lang="nl"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Van Den Eynde Auto's — Tweedehandswagens Nijlen</title>
<meta name="description" content="Autohandel Van Den Eynde in Nijlen. Kwaliteitsvolle tweedehands wagens met persoonlijke service. Tom Van Den Eynde — Dorsel 27, 2560 Nijlen.">
<link rel="preconnect" href="https://fonts.googleapis.com/">
<link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin="">
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700;800&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" rel="stylesheet">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:'Open Sans',sans-serif;background:#0a0a0a;color:#fff;overflow-x:hidden}
a{text-decoration:none;color:inherit}
img{max-width:100%;display:block}
:root{
  --red:#e3000f;--red-dark:#b5000c;
  --black:#0a0a0a;--dark:#1a1a1a;--mid:#2a2a2a;
  --white:#fff;--gray:#f5f5f5;--muted:#888;
}
::-webkit-scrollbar{width:5px}
::-webkit-scrollbar-track{background:#111}
::-webkit-scrollbar-thumb{background:var(--red);border-radius:3px}
h1,h2,h3,h4{font-family:'Montserrat',sans-serif}
.wrap{max-width:1200px;margin:0 auto;padding:0 28px}
.section{padding:clamp(64px,10vw,100px) 0}
.lbl{display:inline-block;font-size:.68rem;font-weight:700;letter-spacing:4px;text-transform:uppercase;color:var(--red);margin-bottom:12px}
.h2{font-size:clamp(1.75rem,4vw,2.8rem);font-weight:800;line-height:1.12;margin-bottom:16px}
.sub{font-size:.95rem;color:var(--muted);line-height:1.85;max-width:540px}
.btn-r{display:inline-flex;align-items:center;gap:8px;background:var(--red);color:#fff;font-family:'Montserrat',sans-serif;font-weight:700;font-size:.78rem;letter-spacing:1.5px;text-transform:uppercase;padding:14px 28px;border-radius:4px;border:none;cursor:pointer;transition:background .25s,transform .2s,box-shadow .25s}
.btn-r:hover{background:var(--red-dark);transform:translateY(-2px);box-shadow:0 8px 24px rgba(227,0,15,.4)}
.btn-o{display:inline-flex;align-items:center;gap:8px;background:transparent;color:#fff;font-family:'Montserrat',sans-serif;font-weight:700;font-size:.78rem;letter-spacing:1.5px;text-transform:uppercase;padding:13px 28px;border-radius:4px;border:2px solid rgba(255,255,255,.28);cursor:pointer;transition:all .2s}
.btn-o:hover{border-color:#fff;background:rgba(255,255,255,.07);transform:translateY(-2px)}

/* NAV */
#nav{position:fixed;top:0;left:0;right:0;z-index:999;padding:20px 0;transition:background .35s,padding .35s,box-shadow .35s}
#nav.sc{background:rgba(10,10,10,.96);backdrop-filter:blur(14px);-webkit-backdrop-filter:blur(14px);padding:12px 0;box-shadow:0 2px 28px rgba(0,0,0,.55)}
.nav-i{display:flex;align-items:center;justify-content:space-between}
.logo{font-family:'Montserrat',sans-serif;font-weight:800;font-size:1.1rem;letter-spacing:.4px;color:#fff}
.logo span{color:var(--red)}
.nav-links{display:flex;align-items:center;gap:30px}
.nav-links a{font-family:'Montserrat',sans-serif;font-weight:600;font-size:.74rem;letter-spacing:1.2px;text-transform:uppercase;color:rgba(255,255,255,.7);transition:color .2s}
.nav-links a:hover{color:#fff}
.nav-cta{background:var(--red) !important;color:#fff !important;padding:9px 20px;border-radius:4px}
.nav-cta:hover{background:var(--red-dark) !important}
.hbg{display:none;flex-direction:column;gap:5px;background:none;border:none;cursor:pointer;padding:4px}
.hbg span{display:block;width:25px;height:2px;background:#fff;border-radius:2px;transition:all .3s}
.hbg.open span:nth-child(1){transform:rotate(45deg) translate(5px,5px)}
.hbg.open span:nth-child(2){opacity:0}
.hbg.open span:nth-child(3){transform:rotate(-45deg) translate(5px,-5px)}
#mob-menu{display:none;position:fixed;inset:0;background:rgba(10,10,10,.98);z-index:998;flex-direction:column;align-items:center;justify-content:center;gap:34px}
#mob-menu.open{display:flex}
#mob-menu a{font-family:'Montserrat',sans-serif;font-weight:700;font-size:1.4rem;letter-spacing:2px;text-transform:uppercase;color:rgba(255,255,255,.65);transition:color .2s}
#mob-menu a:hover{color:var(--red)}

/* HERO */
#hero{height:100vh;min-height:600px;position:relative;overflow:hidden;display:flex;align-items:center;justify-content:center;text-align:center}
#hero-video{position:absolute;inset:0;width:100%;height:100%;object-fit:cover;z-index:0}
.hero-ov{position:absolute;inset:0;background:linear-gradient(135deg,rgba(10,10,10,.9) 0%,rgba(10,10,10,.5) 55%,rgba(227,0,15,.06) 100%);z-index:1}
.hero-c{position:relative;z-index:2;padding:0 24px;max-width:820px}
.hero-badge{display:inline-block;background:var(--red);color:#fff;font-family:'Montserrat',sans-serif;font-weight:700;font-size:.62rem;letter-spacing:4px;text-transform:uppercase;padding:6px 18px;border-radius:2px;margin-bottom:28px;opacity:0;transform:translateY(20px);animation:fu .6s .3s forwards}
.hero-h1{font-weight:900;font-size:clamp(2.4rem,7vw,5rem);line-height:1.05;margin-bottom:20px;opacity:0;transform:translateY(30px);animation:fu .7s .55s forwards}
.hero-h1 span{color:var(--red)}
.hero-p{font-size:clamp(.92rem,2vw,1.1rem);color:rgba(255,255,255,.7);line-height:1.75;margin-bottom:38px;opacity:0;transform:translateY(20px);animation:fu .6s .8s forwards}
.hero-btns{display:flex;gap:14px;justify-content:center;flex-wrap:wrap;opacity:0;transform:translateY(20px);animation:fu .6s 1.05s forwards}
.hero-scroll{position:absolute;bottom:30px;left:50%;transform:translateX(-50%);z-index:2;display:flex;flex-direction:column;align-items:center;gap:8px;font-size:.6rem;letter-spacing:3px;text-transform:uppercase;color:rgba(255,255,255,.35);animation:bob 2.2s ease-in-out infinite}
.hero-scroll::after{content:'';width:1px;height:44px;background:rgba(255,255,255,.18)}
@keyframes fu{to{opacity:1;transform:translateY(0)}}
@keyframes bob{0%,100%{transform:translateX(-50%) translateY(0)}50%{transform:translateX(-50%) translateY(-8px)}}

/* COUNTERS */
#counters{background:var(--red);padding:64px 0}
.cnt-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:1px;background:rgba(255,255,255,.12)}
.cnt-item{background:var(--red);text-align:center;padding:36px 20px}
.cnt-num{font-family:'Montserrat',sans-serif;font-weight:900;font-size:clamp(2rem,5vw,3rem);line-height:1;margin-bottom:8px}
.cnt-num em{font-style:normal;font-size:.65em;color:rgba(255,255,255,.55)}
.cnt-lbl{font-family:'Montserrat',sans-serif;font-weight:600;font-size:.7rem;letter-spacing:2.5px;text-transform:uppercase;color:rgba(255,255,255,.72)}

/* STOCK */
#aanbod{background:var(--black)}
.filter-bar{display:flex;gap:10px;flex-wrap:wrap;margin:36px 0 40px}
.fbtn{background:transparent;border:1px solid rgba(255,255,255,.12);color:rgba(255,255,255,.5);font-family:'Montserrat',sans-serif;font-weight:700;font-size:.66rem;letter-spacing:2px;text-transform:uppercase;padding:9px 20px;border-radius:4px;cursor:pointer;transition:all .22s}
.fbtn:hover,.fbtn.act{background:var(--red);border-color:var(--red);color:#fff}
.cars-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:22px}
.car-card{background:var(--dark);border-radius:6px;overflow:hidden;border:1px solid rgba(255,255,255,.06);transition:transform .35s,box-shadow .35s,border-color .35s;cursor:pointer}
.car-card:hover{transform:translateY(-8px) rotateX(1deg);box-shadow:0 24px 60px rgba(0,0,0,.7),0 0 0 1px rgba(227,0,15,.2);border-color:rgba(227,0,15,.25)}
.car-card.hidden{display:none}
.car-ph{position:relative;overflow:hidden;height:220px}
.car-ph img{width:100%;height:100%;object-fit:cover;transition:transform .55s}
.car-card:hover .car-ph img{transform:scale(1.07)}
.car-badge{position:absolute;top:12px;left:12px;background:var(--red);color:#fff;font-family:'Montserrat',sans-serif;font-weight:700;font-size:.58rem;letter-spacing:2px;text-transform:uppercase;padding:4px 12px;border-radius:2px}
.car-badge.g{background:#27ae60}
.car-badge.o{background:#e67e22}
.car-hover-btn{position:absolute;bottom:-44px;left:0;right:0;background:rgba(227,0,15,.93);color:#fff;font-family:'Montserrat',sans-serif;font-weight:700;font-size:.7rem;letter-spacing:2px;text-transform:uppercase;text-align:center;padding:14px;transition:bottom .3s}
.car-card:hover .car-hover-btn{bottom:0}
.car-body{padding:20px 22px 22px}
.car-model{font-family:'Montserrat',sans-serif;font-weight:800;font-size:.98rem;margin-bottom:10px}
.car-pills{display:flex;flex-wrap:wrap;gap:7px;margin-bottom:16px}
.pill{font-size:.62rem;color:rgba(255,255,255,.48);background:rgba(255,255,255,.05);border:1px solid rgba(255,255,255,.09);padding:4px 10px;border-radius:3px;font-family:'Montserrat',sans-serif}
.car-price{font-family:'Montserrat',sans-serif;font-weight:900;font-size:1.4rem;color:var(--red)}
.car-pnote{font-size:.62rem;color:var(--muted);margin-top:2px}

/* MODAL */
.modal-ov{display:none;position:fixed;inset:0;z-index:2000;background:rgba(0,0,0,.86);backdrop-filter:blur(6px);align-items:center;justify-content:center;padding:18px}
.modal-ov.open{display:flex}
.modal-box{background:var(--dark);border-radius:8px;width:100%;max-width:860px;max-height:90vh;overflow-y:auto;border:1px solid rgba(255,255,255,.1);position:relative;animation:mIn .3s ease}
@keyframes mIn{from{opacity:0;transform:scale(.94)}to{opacity:1;transform:scale(1)}}
.m-close{position:absolute;top:14px;right:14px;z-index:10;background:rgba(0,0,0,.5);border:none;color:#fff;width:36px;height:36px;border-radius:50%;font-size:1.1rem;cursor:pointer;display:flex;align-items:center;justify-content:center;transition:background .2s}
.m-close:hover{background:var(--red)}
.m-swiper{height:300px}
.m-swiper .swiper-slide img{width:100%;height:100%;object-fit:cover}
.m-body{padding:26px 32px 32px}
.m-title{font-family:'Montserrat',sans-serif;font-weight:800;font-size:1.4rem;margin-bottom:6px}
.m-price{font-family:'Montserrat',sans-serif;font-weight:900;font-size:2rem;color:var(--red);margin-bottom:22px}
.m-specs{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:22px}
.m-spec{background:rgba(255,255,255,.04);border:1px solid rgba(255,255,255,.07);border-radius:4px;padding:11px 15px}
.m-slbl{font-size:.58rem;letter-spacing:2px;text-transform:uppercase;color:var(--muted);margin-bottom:3px;font-family:'Montserrat',sans-serif;font-weight:600}
.m-sval{font-weight:600;font-size:.88rem}
.m-desc{font-size:.88rem;color:rgba(255,255,255,.62);line-height:1.85;margin-bottom:22px}
.m-acts{display:flex;gap:12px;flex-wrap:wrap}

/* DIENSTEN */
#diensten{background:var(--gray);color:var(--black)}
#diensten .lbl,#contact .lbl{color:var(--red)}
#diensten .h2,#contact .h2{color:var(--black)}
#diensten .sub,#contact .sub{color:#555}
.svc-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:24px;margin-top:52px}
.svc-card{background:#fff;border-radius:6px;padding:38px 30px;border:1px solid rgba(0,0,0,.07);transition:transform .3s,box-shadow .3s;position:relative;overflow:hidden}
.svc-card::before{content:'';position:absolute;top:0;left:0;right:0;height:3px;background:var(--red);transform:scaleX(0);transform-origin:left;transition:transform .35s}
.svc-card:hover{transform:translateY(-6px);box-shadow:0 16px 44px rgba(0,0,0,.11)}
.svc-card:hover::before{transform:scaleX(1)}
.svc-ic{width:58px;height:58px;border-radius:8px;background:rgba(227,0,15,.08);display:flex;align-items:center;justify-content:center;font-size:1.5rem;margin-bottom:20px;transition:background .3s}
.svc-card:hover .svc-ic{background:rgba(227,0,15,.15)}
.svc-card h3{font-size:1rem;font-weight:800;color:var(--black);margin-bottom:12px}
.svc-card p{font-size:.86rem;color:#555;line-height:1.85}

/* OVER ONS */
#over{background:var(--black)}
.over-grid{display:grid;grid-template-columns:1fr 1fr;gap:80px;align-items:center}
.over-img-wrap{position:relative}
.over-img{width:100%;height:480px;object-fit:cover;object-position:top;border-radius:6px;display:block}
.over-acc{position:absolute;top:-16px;left:-16px;right:16px;bottom:16px;border:2px solid var(--red);border-radius:6px;z-index:-1}
.over-badge{position:absolute;bottom:-20px;right:-20px;background:var(--red);border-radius:6px;padding:20px 24px;text-align:center}
.over-badge-n{font-family:'Montserrat',sans-serif;font-weight:900;font-size:2rem;line-height:1}
.over-badge-l{font-size:.62rem;letter-spacing:2px;text-transform:uppercase;color:rgba(255,255,255,.72);margin-top:4px;font-family:'Montserrat',sans-serif;font-weight:600}
.over-list{list-style:none;margin:22px 0;display:flex;flex-direction:column;gap:13px}
.over-list li{display:flex;align-items:flex-start;gap:12px;font-size:.9rem;color:rgba(255,255,255,.68);line-height:1.65}
.over-list li::before{content:'';width:7px;height:7px;border-radius:50%;background:var(--red);flex-shrink:0;margin-top:8px}
.over-sig{margin-top:26px;font-style:italic;font-size:.8rem;color:var(--muted)}
.over-sig strong{display:block;font-family:'Montserrat',sans-serif;font-weight:800;font-size:1rem;color:#fff;font-style:normal;margin-bottom:3px}

/* REVIEWS */
#reviews{background:var(--dark)}
.rev-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:22px;margin-top:52px}
.rev-card{background:var(--mid);border-radius:6px;padding:28px;border:1px solid rgba(255,255,255,.06);transition:transform .3s,border-color .3s}
.rev-card:hover{transform:translateY(-4px);border-color:rgba(227,0,15,.2)}
.rev-stars{color:#f39c12;font-size:.85rem;letter-spacing:2px;margin-bottom:14px}
.rev-text{font-size:.86rem;color:rgba(255,255,255,.68);line-height:1.85;margin-bottom:20px;font-style:italic}
.rev-foot{display:flex;align-items:center;gap:12px}
.rev-av{width:42px;height:42px;border-radius:50%;background:var(--red);display:flex;align-items:center;justify-content:center;font-family:'Montserrat',sans-serif;font-weight:800;font-size:.86rem;flex-shrink:0}
.rev-name{font-family:'Montserrat',sans-serif;font-weight:700;font-size:.86rem}
.rev-loc{font-size:.7rem;color:var(--muted);margin-top:2px}

/* AFSPRAAK */
#afspraak{background:var(--black)}
.afspr-grid{display:grid;grid-template-columns:1fr 1.45fr;gap:72px;align-items:start}
.afspr-info p{font-size:.9rem;color:rgba(255,255,255,.62);line-height:1.85;margin-top:18px}
.steps{list-style:none;margin-top:34px;display:flex;flex-direction:column;gap:20px}
.step{display:flex;gap:16px;align-items:flex-start}
.step-n{width:36px;height:36px;border-radius:50%;background:var(--red);display:flex;align-items:center;justify-content:center;font-family:'Montserrat',sans-serif;font-weight:800;font-size:.84rem;flex-shrink:0}
.step-t{font-size:.86rem;color:rgba(255,255,255,.62);line-height:1.65;padding-top:8px}
.step-t strong{display:block;color:#fff;font-family:'Montserrat',sans-serif;font-weight:700;font-size:.88rem;margin-bottom:2px}
.form-box{background:var(--dark);border-radius:8px;padding:40px;border:1px solid rgba(255,255,255,.08)}
.form-row{display:grid;grid-template-columns:1fr 1fr;gap:16px}
.fg{margin-bottom:18px}
.fg label{display:block;font-family:'Montserrat',sans-serif;font-weight:600;font-size:.62rem;letter-spacing:2.5px;text-transform:uppercase;color:var(--muted);margin-bottom:8px}
.fg input,.fg select,.fg textarea{width:100%;background:rgba(255,255,255,.04);border:1px solid rgba(255,255,255,.1);border-radius:4px;padding:12px 15px;color:#fff;font-family:'Open Sans',sans-serif;font-size:.88rem;outline:none;transition:border-color .2s,background .2s;-webkit-appearance:none}
.fg input:focus,.fg select:focus,.fg textarea:focus{border-color:var(--red);background:rgba(227,0,15,.04)}
.fg input::placeholder,.fg textarea::placeholder{color:rgba(255,255,255,.2)}
.fg select option{background:var(--dark);color:#fff}
.fg textarea{min-height:90px;resize:vertical}
.ferr{font-size:.7rem;color:#ff6b6b;margin-top:4px;display:none}
.ferr.show{display:block}
#form-ok{display:none;text-align:center;padding:28px 16px}
#form-ok.show{display:block;animation:fu .4s ease}
#form-ok .ok-icon{font-size:2.8rem;margin-bottom:14px}
#form-ok h3{font-family:'Montserrat',sans-serif;font-weight:800;font-size:1.25rem;margin-bottom:10px}
#form-ok p{font-size:.86rem;color:var(--muted);line-height:1.8}

/* CONTACT */
#contact{background:var(--gray)}
.cont-grid{display:grid;grid-template-columns:1fr 1.35fr;gap:64px;margin-top:52px}
.ci-list{display:flex;flex-direction:column}
.ci-item{display:flex;gap:16px;align-items:flex-start;padding:16px 0;border-bottom:1px solid rgba(0,0,0,.08)}
.ci-item:first-child{border-top:1px solid rgba(0,0,0,.08)}
.ci-ic{width:42px;height:42px;border-radius:6px;background:var(--red);display:flex;align-items:center;justify-content:center;font-size:.95rem;flex-shrink:0}
.ci-lbl{font-family:'Montserrat',sans-serif;font-weight:700;font-size:.64rem;letter-spacing:2px;text-transform:uppercase;color:#999;margin-bottom:4px}
.ci-val{font-size:.9rem;color:var(--black);font-weight:600}
.ci-val a{color:var(--black);transition:color .2s}
.ci-val a:hover{color:var(--red)}
.uren-tbl{margin-top:26px}
.uren-tbl .lbl-sm{font-family:'Montserrat',sans-serif;font-weight:700;font-size:.64rem;letter-spacing:2px;text-transform:uppercase;color:#999;margin-bottom:12px}
.uur-r{display:flex;justify-content:space-between;padding:9px 0;border-bottom:1px solid rgba(0,0,0,.06);font-size:.86rem;color:var(--black)}
.uur-day{color:#555}
.uur-time{font-weight:600}
.uur-r.cl .uur-time{color:#bbb;font-weight:400}
.soc-row{display:flex;gap:10px;margin-top:26px}
.soc-btn{width:40px;height:40px;border-radius:6px;background:rgba(0,0,0,.07);border:1px solid rgba(0,0,0,.1);display:flex;align-items:center;justify-content:center;font-size:.95rem;transition:all .2s;color:var(--black)}
.soc-btn:hover{background:var(--red);border-color:var(--red);color:#fff}
.map-wrap{border-radius:8px;overflow:hidden;border:1px solid rgba(0,0,0,.1);height:100%;min-height:420px}
.map-wrap iframe{display:block;width:100%;height:100%;border:0}

/* FOOTER */
footer{background:#050505;padding:52px 0 0}
.ft-top{display:grid;grid-template-columns:2fr 1fr 1fr;gap:48px;padding-bottom:48px;border-bottom:1px solid rgba(255,255,255,.06)}
.ft-logo{font-family:'Montserrat',sans-serif;font-weight:800;font-size:1.15rem;margin-bottom:14px}
.ft-logo span{color:var(--red)}
.ft-desc{font-size:.83rem;color:var(--muted);line-height:1.85;max-width:280px}
.ft-col h4{font-family:'Montserrat',sans-serif;font-weight:700;font-size:.64rem;letter-spacing:3px;text-transform:uppercase;color:rgba(255,255,255,.3);margin-bottom:18px}
.ft-links{list-style:none;display:flex;flex-direction:column;gap:10px}
.ft-links a{font-size:.83rem;color:var(--muted);transition:color .2s}
.ft-links a:hover{color:var(--red)}
.ft-bot{display:flex;align-items:center;justify-content:space-between;padding:20px 0;font-size:.72rem;color:rgba(255,255,255,.2)}
.ft-soc{display:flex;gap:10px;margin-top:20px}
.ft-soc a{width:36px;height:36px;border-radius:5px;background:rgba(255,255,255,.06);border:1px solid rgba(255,255,255,.1);display:flex;align-items:center;justify-content:center;color:rgba(255,255,255,.5);transition:all .2s}
.ft-soc a:hover{background:var(--red);border-color:var(--red);color:#fff}

/* CHATBOT */
#cb-btn{position:fixed;bottom:28px;right:28px;z-index:900;width:58px;height:58px;border-radius:50%;background:var(--red);border:none;cursor:pointer;display:flex;align-items:center;justify-content:center;font-size:1.4rem;color:#fff;box-shadow:0 6px 24px rgba(227,0,15,.5);transition:transform .25s,box-shadow .25s}
#cb-btn:hover{transform:scale(1.1);box-shadow:0 10px 32px rgba(227,0,15,.6)}
.cb-pulse{position:absolute;top:-3px;right:-3px;width:13px;height:13px;border-radius:50%;background:#2ecc71;border:2px solid #050505;animation:pulse 2s infinite}
@keyframes pulse{0%,100%{transform:scale(1);opacity:1}50%{transform:scale(1.35);opacity:.65}}
#cb-win{position:fixed;bottom:100px;right:28px;z-index:900;width:340px;max-height:470px;background:var(--dark);border-radius:12px;border:1px solid rgba(255,255,255,.1);box-shadow:0 24px 64px rgba(0,0,0,.65);display:none;flex-direction:column;overflow:hidden}
#cb-win.open{display:flex;animation:cbIn .3s ease}
@keyframes cbIn{from{opacity:0;transform:translateY(16px) scale(.96)}to{opacity:1;transform:translateY(0) scale(1)}}
.cb-head{background:var(--red);padding:15px 18px;display:flex;align-items:center;gap:11px}
.cb-av{width:34px;height:34px;border-radius:50%;background:rgba(255,255,255,.18);display:flex;align-items:center;justify-content:center;font-size:1rem}
.cb-hname{font-family:'Montserrat',sans-serif;font-weight:700;font-size:.88rem}
.cb-hstat{font-size:.68rem;color:rgba(255,255,255,.72)}
.cb-x{margin-left:auto;background:none;border:none;color:rgba(255,255,255,.7);font-size:1.1rem;cursor:pointer;padding:4px}
.cb-x:hover{color:#fff}
.cb-msgs{flex:1;overflow-y:auto;padding:14px;display:flex;flex-direction:column;gap:9px}
.cb-msg{max-width:88%;font-size:.82rem;line-height:1.55;padding:9px 13px;border-radius:12px}
.cb-msg.bot{background:var(--mid);color:rgba(255,255,255,.82);border-radius:4px 12px 12px 12px;align-self:flex-start}
.cb-msg.user{background:var(--red);color:#fff;border-radius:12px 4px 12px 12px;align-self:flex-end}
.cb-quick{padding:9px 12px;display:flex;flex-wrap:wrap;gap:5px;border-top:1px solid rgba(255,255,255,.06)}
.cb-q{background:rgba(255,255,255,.06);border:1px solid rgba(255,255,255,.1);color:rgba(255,255,255,.72);font-size:.68rem;padding:5px 11px;border-radius:20px;cursor:pointer;transition:all .18s;font-family:'Montserrat',sans-serif;font-weight:600}
.cb-q:hover{background:var(--red);border-color:var(--red);color:#fff}
.cb-inp{display:flex;gap:8px;padding:11px 13px;border-top:1px solid rgba(255,255,255,.06)}
#cb-input{flex:1;background:rgba(255,255,255,.05);border:1px solid rgba(255,255,255,.1);border-radius:20px;padding:8px 15px;color:#fff;font-size:.82rem;outline:none;font-family:'Open Sans',sans-serif}
#cb-input::placeholder{color:rgba(255,255,255,.25)}
#cb-input:focus{border-color:var(--red)}
#cb-send{background:var(--red);border:none;border-radius:50%;width:34px;height:34px;cursor:pointer;display:flex;align-items:center;justify-content:center;color:#fff;font-size:.88rem;transition:background .2s;flex-shrink:0}
#cb-send:hover{background:var(--red-dark)}

/* BACK TOP */
#btt{position:fixed;bottom:28px;left:28px;z-index:900;width:42px;height:42px;border-radius:50%;background:rgba(255,255,255,.08);border:1px solid rgba(255,255,255,.14);color:#fff;cursor:pointer;font-size:.95rem;display:none;align-items:center;justify-content:center;transition:background .2s;font-family:'Montserrat',sans-serif}
#btt.show{display:flex}
#btt:hover{background:var(--red);border-color:var(--red)}

/* RESPONSIVE */
@media(max-width:1024px){
  .cars-grid{grid-template-columns:repeat(2,1fr)}
  .over-grid{grid-template-columns:1fr;gap:48px}
  .over-img-wrap{max-width:480px}
  .ft-top{grid-template-columns:1fr 1fr}
  .afspr-grid{grid-template-columns:1fr;gap:40px}
}
@media(max-width:768px){
  .cnt-grid{grid-template-columns:repeat(2,1fr)}
  .cars-grid,.svc-grid,.rev-grid{grid-template-columns:1fr}
  .cont-grid{grid-template-columns:1fr}
  .ft-top{grid-template-columns:1fr;gap:30px}
  .form-row{grid-template-columns:1fr}
  .m-specs{grid-template-columns:1fr}
  .nav-links{display:none}
  .hbg{display:flex}
  #cb-win{width:calc(100vw - 40px);right:20px}
  .afspr-grid{grid-template-columns:1fr}
}
@media(max-width:480px){
  .hero-btns{flex-direction:column;align-items:center}
  .cnt-grid{grid-template-columns:1fr 1fr}
  .over-badge{right:0;bottom:-16px}
}
</style>
</head>
<body data-aos-easing="ease" data-aos-duration="680" data-aos-delay="0">

<!-- MOBILE MENU -->
<div id="mob-menu">
  <a href="#aanbod" onclick="closeMob()">Aanbod</a>
  <a href="#over" onclick="closeMob()">Over ons</a>
  <a href="#diensten" onclick="closeMob()">Diensten</a>
  <a href="#afspraak" onclick="closeMob()">Afspraak</a>
  <a href="#contact" onclick="closeMob()">Contact</a>
</div>

<!-- NAV -->
<nav id="nav" class="sc">
  <div class="wrap">
    <div class="nav-i">
      <a href="#" class="logo">Van Den Eynde <span>Auto's</span></a>
      <div class="nav-links">
        <a href="#aanbod">Aanbod</a>
        <a href="#over">Over ons</a>
        <a href="#diensten">Diensten</a>
        <a href="#afspraak">Afspraak</a>
        <a href="#contact">Contact</a>
        <a href="tel:+3234819670" class="nav-cta">📞 Bel ons</a>
      </div>
      <button class="hbg" id="hbg" onclick="toggleMob()" aria-label="Menu openen">
        <span></span><span></span><span></span>
      </button>
    </div>
  </div>
</nav>

<!-- HERO -->
<section id="hero">
  <!-- VIDEO ACHTERGROND: éénmalig afspelen, bevriest op laatste frame -->
  <video id="hero-video" autoplay muted playsinline poster="hero-poster.jpg">
    <source src="hero-video.mp4" type="video/mp4">
  </video>
  <div class="hero-ov"></div>
  <div class="hero-c">
    <div class="hero-badge">Gevestigd in Nijlen · Persoonlijke service</div>
    <h1 class="hero-h1">Uw droomauto.<br>Gevonden in <span>Nijlen.</span></h1>
    <p class="hero-p">Kwaliteitsvolle tweedehands wagens met persoonlijke service.<br>Tom Van Den Eynde helpt u bij elke stap — eerlijk en transparant.</p>
    <div class="hero-btns">
      <a href="#aanbod" class="btn-r">Bekijk ons aanbod</a>
      <a href="#afspraak" class="btn-o">Maak een afspraak</a>
    </div>
  </div>
  <div class="hero-scroll">Scroll</div>
</section>

<!-- COUNTERS -->
<section id="counters">
  <div class="wrap">
    <div class="cnt-grid">
      <div class="cnt-item" data-aos="fade-up">
        <div class="cnt-num" data-target="500">500<em>+</em></div>
        <div class="cnt-lbl">Tevreden klanten</div>
      </div>
      <div class="cnt-item" data-aos="fade-up" data-aos-delay="80">
        <div class="cnt-num" data-target="15">15<em> jaar</em></div>
        <div class="cnt-lbl">Ervaring</div>
      </div>
      <div class="cnt-item" data-aos="fade-up" data-aos-delay="160">
        <div class="cnt-num" data-target="200">200<em>+</em></div>
        <div class="cnt-lbl">Auto's verkocht</div>
      </div>
      <div class="cnt-item" data-aos="fade-up" data-aos-delay="240">
        <div class="cnt-num" data-target="100">100<em>%</em></div>
        <div class="cnt-lbl">Transparantie</div>
      </div>
    </div>
  </div>
</section>

<!-- AANBOD -->
<section id="aanbod" class="section">
  <div class="wrap">
    <div data-aos="fade-up">
      <span class="lbl">Actueel aanbod</span>
      <h2 class="h2">Onze wagens</h2>
      <p class="sub">Elk voertuig is grondig nagekeken en rijklaar. Eerlijke prijzen, geen verborgen kosten.</p>
    </div>
    <div class="filter-bar">
      <button class="fbtn act" data-f="all">Alle</button>
      <button class="fbtn" data-f="benzine">Benzine</button>
      <button class="fbtn" data-f="diesel">Diesel</button>
      <button class="fbtn" data-f="hybride">Elektrisch / Hybride</button>
    </div>
    <div class="cars-grid">
      <div class="car-card" data-fuel="diesel" data-aos="fade-up" onclick="openM('golf')">
        <div class="car-ph">
          <img src="https://images.unsplash.com/photo-1616422285623-13ff0162193c?w=600&q=80" alt="Volkswagen Golf 1.6 TDI 2019">
          <div class="car-badge">Topstaat</div>
          <div class="car-hover-btn">Bekijk details →</div>
        </div>
        <div class="car-body">
          <div class="car-model">Volkswagen Golf 1.6 TDI — 2019</div>
          <div class="car-pills">
            <span class="pill">87.000 km</span><span class="pill">Diesel</span><span class="pill">115 pk</span><span class="pill">Manueel</span>
          </div>
          <div class="car-price">€ 13.950</div>
          <div class="car-pnote">Incl. btw · Keuring OK</div>
        </div>
      </div>
      <div class="car-card" data-fuel="benzine" data-aos="fade-up" data-aos-delay="80" onclick="openM('focus')">
        <div class="car-ph">
          <img src="https://images.unsplash.com/photo-1590362891991-f776e747a588?w=600&q=80" alt="Ford Focus 1.0 EcoBoost 2020">
          <div class="car-badge" style="background:#2980b9">Net binnen</div>
          <div class="car-hover-btn">Bekijk details →</div>
        </div>
        <div class="car-body">
          <div class="car-model">Ford Focus 1.0 EcoBoost — 2020</div>
          <div class="car-pills">
            <span class="pill">58.000 km</span><span class="pill">Benzine</span><span class="pill">125 pk</span><span class="pill">Manueel</span>
          </div>
          <div class="car-price">€ 14.500</div>
          <div class="car-pnote">Incl. btw · Keuring OK</div>
        </div>
      </div>
      <div class="car-card" data-fuel="benzine" data-aos="fade-up" data-aos-delay="160" onclick="openM('astra')">
        <div class="car-ph">
          <img src="https://images.unsplash.com/photo-1549399542-7e3f8b79c341?w=600&q=80" alt="Opel Astra 1.4 Turbo 2018">
          <div class="car-badge o">Populair</div>
          <div class="car-hover-btn">Bekijk details →</div>
        </div>
        <div class="car-body">
          <div class="car-model">Opel Astra 1.4 Turbo — 2018</div>
          <div class="car-pills">
            <span class="pill">72.000 km</span><span class="pill">Benzine</span><span class="pill">110 pk</span><span class="pill">Manueel</span>
          </div>
          <div class="car-price">€ 11.950</div>
          <div class="car-pnote">Incl. btw · Keuring OK</div>
        </div>
      </div>
      <div class="car-card" data-fuel="diesel" data-aos="fade-up" onclick="openM('clio')">
        <div class="car-ph">
          <img src="https://images.unsplash.com/photo-1541899481282-d53bffe3c35d?w=600&q=80" alt="Renault Clio 1.5 dCi 2020">
          <div class="car-badge g">Topstaat</div>
          <div class="car-hover-btn">Bekijk details →</div>
        </div>
        <div class="car-body">
          <div class="car-model">Renault Clio 1.5 dCi — 2020</div>
          <div class="car-pills">
            <span class="pill">63.000 km</span><span class="pill">Diesel</span><span class="pill">85 pk</span><span class="pill">Manueel</span>
          </div>
          <div class="car-price">€ 12.450</div>
          <div class="car-pnote">Incl. btw · Keuring OK</div>
        </div>
      </div>
      <div class="car-card" data-fuel="hybride" data-aos="fade-up" data-aos-delay="80" onclick="openM('yaris')">
        <div class="car-ph">
          <img src="https://images.unsplash.com/photo-1609521263047-f8f205293f24?w=600&q=80" alt="Toyota Yaris Hybrid 2021">
          <div class="car-badge" style="background:#2980b9">Net binnen</div>
          <div class="car-hover-btn">Bekijk details →</div>
        </div>
        <div class="car-body">
          <div class="car-model">Toyota Yaris 1.5 Hybrid — 2021</div>
          <div class="car-pills">
            <span class="pill">41.000 km</span><span class="pill">Hybride</span><span class="pill">116 pk</span><span class="pill">CVT automaat</span>
          </div>
          <div class="car-price">€ 16.950</div>
          <div class="car-pnote">Incl. btw · Keuring OK</div>
        </div>
      </div>
      <div class="car-card" data-fuel="diesel" data-aos="fade-up" data-aos-delay="160" onclick="openM('bmw')">
        <div class="car-ph">
          <img src="https://images.unsplash.com/photo-1555215695-3004980ad029?w=600&q=80" alt="BMW 118d 2019">
          <div class="car-badge o">Populair</div>
          <div class="car-hover-btn">Bekijk details →</div>
        </div>
        <div class="car-body">
          <div class="car-model">BMW 118d — 2019</div>
          <div class="car-pills">
            <span class="pill">79.000 km</span><span class="pill">Diesel</span><span class="pill">150 pk</span><span class="pill">8-tr. automaat</span>
          </div>
          <div class="car-price">€ 18.950</div>
          <div class="car-pnote">Incl. btw · Keuring OK</div>
        </div>
      </div>
    </div>
    <p style="text-align:center;margin-top:38px;font-size:.82rem;color:var(--muted)">Ons aanbod wisselt regelmatig — contacteer ons voor de actuele stock.</p>
  </div>
</section>

<!-- MODALS -->
<div class="modal-ov" id="m-golf">
  <div class="modal-box">
    <button class="m-close" onclick="closeM('golf')">✕</button>
    <div class="swiper m-swiper" id="sw-golf">
      <div class="swiper-wrapper">
        <div class="swiper-slide"><img src="https://images.unsplash.com/photo-1616422285623-13ff0162193c?w=800&q=80" alt="VW Golf"></div>
        <div class="swiper-slide"><img src="https://images.unsplash.com/photo-1494976388531-d1058494cdd8?w=800&q=80" alt="VW Golf interieur"></div>
        <div class="swiper-slide"><img src="https://images.unsplash.com/photo-1502161254066-6c74afbf07aa?w=800&q=80" alt="VW Golf detail"></div>
      </div>
      <div class="swiper-pagination"></div>
    </div>
    <div class="m-body">
      <div class="m-title">Volkswagen Golf 1.6 TDI</div>
      <div class="m-price">€ 13.950</div>
      <div class="m-specs">
        <div class="m-spec"><div class="m-slbl">Bouwjaar</div><div class="m-sval">2019</div></div>
        <div class="m-spec"><div class="m-slbl">Kilometerstand</div><div class="m-sval">87.000 km</div></div>
        <div class="m-spec"><div class="m-slbl">Brandstof</div><div class="m-sval">Diesel</div></div>
        <div class="m-spec"><div class="m-slbl">Vermogen</div><div class="m-sval">115 pk</div></div>
        <div class="m-spec"><div class="m-slbl">Transmissie</div><div class="m-sval">Manueel 6-traps</div></div>
        <div class="m-spec"><div class="m-slbl">Carrosserie</div><div class="m-sval">Hatchback 5d</div></div>
      </div>
      <p class="m-desc">Uitstekende Volkswagen Golf in topstaat, technisch volledig nagekeken. Ideaal voor wie zuinig en betrouwbaar wil rijden. Volledig gekeurd en direct rijklaar.</p>
      <div class="m-acts">
        <a href="#afspraak" class="btn-r" onclick="closeM('golf')">Plan een proefrit</a>
        <a href="tel:+3234819670" class="btn-o" style="border-color:rgba(255,255,255,.25)">📞 Bel ons</a>
      </div>
    </div>
  </div>
</div>

<div class="modal-ov" id="m-focus">
  <div class="modal-box">
    <button class="m-close" onclick="closeM('focus')">✕</button>
    <div class="swiper m-swiper" id="sw-focus">
      <div class="swiper-wrapper">
        <div class="swiper-slide"><img src="https://images.unsplash.com/photo-1590362891991-f776e747a588?w=800&q=80" alt="Ford Focus"></div>
        <div class="swiper-slide"><img src="https://images.unsplash.com/photo-1502877338535-766e1452684a?w=800&q=80" alt="Ford Focus interieur"></div>
        <div class="swiper-slide"><img src="https://images.unsplash.com/photo-1494976388531-d1058494cdd8?w=800&q=80" alt="Ford Focus detail"></div>
      </div>
      <div class="swiper-pagination"></div>
    </div>
    <div class="m-body">
      <div class="m-title">Ford Focus 1.0 EcoBoost</div>
      <div class="m-price">€ 14.500</div>
      <div class="m-specs">
        <div class="m-spec"><div class="m-slbl">Bouwjaar</div><div class="m-sval">2020</div></div>
        <div class="m-spec"><div class="m-slbl">Kilometerstand</div><div class="m-sval">58.000 km</div></div>
        <div class="m-spec"><div class="m-slbl">Brandstof</div><div class="m-sval">Benzine</div></div>
        <div class="m-spec"><div class="m-slbl">Vermogen</div><div class="m-sval">125 pk</div></div>
        <div class="m-spec"><div class="m-slbl">Transmissie</div><div class="m-sval">Manueel 6-traps</div></div>
        <div class="m-spec"><div class="m-slbl">Extra</div><div class="m-sval">Apple CarPlay, Camera</div></div>
      </div>
      <p class="m-desc">Net binnengekomen Ford Focus met lage kilometerstand. Uitgerust met Apple CarPlay, achteruitrijcamera, airconditioning en rijhulpsystemen.</p>
      <div class="m-acts">
        <a href="#afspraak" class="btn-r" onclick="closeM('focus')">Plan een proefrit</a>
        <a href="tel:+3234819670" class="btn-o" style="border-color:rgba(255,255,255,.25)">📞 Bel ons</a>
      </div>
    </div>
  </div>
</div>

<div class="modal-ov" id="m-astra">
  <div class="modal-box">
    <button class="m-close" onclick="closeM('astra')">✕</button>
    <div class="swiper m-swiper" id="sw-astra">
      <div class="swiper-wrapper">
        <div class="swiper-slide"><img src="https://images.unsplash.com/photo-1549399542-7e3f8b79c341?w=800&q=80" alt="Opel Astra"></div>
        <div class="swiper-slide"><img src="https://images.unsplash.com/photo-1502161254066-6c74afbf07aa?w=800&q=80" alt="Opel Astra interieur"></div>
        <div class="swiper-slide"><img src="https://images.unsplash.com/photo-1502877338535-766e1452684a?w=800&q=80" alt="Opel Astra detail"></div>
      </div>
      <div class="swiper-pagination"></div>
    </div>
    <div class="m-body">
      <div class="m-title">Opel Astra 1.4 Turbo</div>
      <div class="m-price">€ 11.950</div>
      <div class="m-specs">
        <div class="m-spec"><div class="m-slbl">Bouwjaar</div><div class="m-sval">2018</div></div>
        <div class="m-spec"><div class="m-slbl">Kilometerstand</div><div class="m-sval">72.000 km</div></div>
        <div class="m-spec"><div class="m-slbl">Brandstof</div><div class="m-sval">Benzine</div></div>
        <div class="m-spec"><div class="m-slbl">Vermogen</div><div class="m-sval">110 pk</div></div>
        <div class="m-spec"><div class="m-slbl">Transmissie</div><div class="m-sval">Manueel 6-traps</div></div>
        <div class="m-spec"><div class="m-slbl">Staat</div><div class="m-sval">Uitstekend</div></div>
      </div>
      <p class="m-desc">Betrouwbare en zuinige gezinswagen in uitstekende staat. Volledig nagekeken en klaar voor een nieuwe eigenaar.</p>
      <div class="m-acts">
        <a href="#afspraak" class="btn-r" onclick="closeM('astra')">Plan een proefrit</a>
        <a href="tel:+3234819670" class="btn-o" style="border-color:rgba(255,255,255,.25)">📞 Bel ons</a>
      </div>
    </div>
  </div>
</div>

<div class="modal-ov" id="m-clio">
  <div class="modal-box">
    <button class="m-close" onclick="closeM('clio')">✕</button>
    <div class="swiper m-swiper" id="sw-clio">
      <div class="swiper-wrapper">
        <div class="swiper-slide"><img src="https://images.unsplash.com/photo-1541899481282-d53bffe3c35d?w=800&q=80" alt="Renault Clio"></div>
        <div class="swiper-slide"><img src="https://images.unsplash.com/photo-1494976388531-d1058494cdd8?w=800&q=80" alt="Renault Clio interieur"></div>
        <div class="swiper-slide"><img src="https://images.unsplash.com/photo-1502161254066-6c74afbf07aa?w=800&q=80" alt="Renault Clio detail"></div>
      </div>
      <div class="swiper-pagination"></div>
    </div>
    <div class="m-body">
      <div class="m-title">Renault Clio 1.5 dCi</div>
      <div class="m-price">€ 12.450</div>
      <div class="m-specs">
        <div class="m-spec"><div class="m-slbl">Bouwjaar</div><div class="m-sval">2020</div></div>
        <div class="m-spec"><div class="m-slbl">Kilometerstand</div><div class="m-sval">63.000 km</div></div>
        <div class="m-spec"><div class="m-slbl">Brandstof</div><div class="m-sval">Diesel</div></div>
        <div class="m-spec"><div class="m-slbl">Vermogen</div><div class="m-sval">85 pk</div></div>
        <div class="m-spec"><div class="m-slbl">Transmissie</div><div class="m-sval">Manueel 5-traps</div></div>
        <div class="m-spec"><div class="m-slbl">Verbruik</div><div class="m-sval">4.2 L/100km</div></div>
      </div>
      <p class="m-desc">Compacte en zuinige Renault Clio ideaal voor stad en lange ritten. Volledig nagekeken, gekeurd en direct rijklaar.</p>
      <div class="m-acts">
        <a href="#afspraak" class="btn-r" onclick="closeM('clio')">Plan een proefrit</a>
        <a href="tel:+3234819670" class="btn-o" style="border-color:rgba(255,255,255,.25)">📞 Bel ons</a>
      </div>
    </div>
  </div>
</div>

<div class="modal-ov" id="m-yaris">
  <div class="modal-box">
    <button class="m-close" onclick="closeM('yaris')">✕</button>
    <div class="swiper m-swiper" id="sw-yaris">
      <div class="swiper-wrapper">
        <div class="swiper-slide"><img src="https://images.unsplash.com/photo-1609521263047-f8f205293f24?w=800&q=80" alt="Toyota Yaris Hybrid"></div>
        <div class="swiper-slide"><img src="https://images.unsplash.com/photo-1502877338535-766e1452684a?w=800&q=80" alt="Toyota Yaris interieur"></div>
        <div class="swiper-slide"><img src="https://images.unsplash.com/photo-1502161254066-6c74afbf07aa?w=800&q=80" alt="Toyota Yaris detail"></div>
      </div>
      <div class="swiper-pagination"></div>
    </div>
    <div class="m-body">
      <div class="m-title">Toyota Yaris 1.5 Hybrid</div>
      <div class="m-price">€ 16.950</div>
      <div class="m-specs">
        <div class="m-spec"><div class="m-slbl">Bouwjaar</div><div class="m-sval">2021</div></div>
        <div class="m-spec"><div class="m-slbl">Kilometerstand</div><div class="m-sval">41.000 km</div></div>
        <div class="m-spec"><div class="m-slbl">Brandstof</div><div class="m-sval">Full Hybrid</div></div>
        <div class="m-spec"><div class="m-slbl">Vermogen</div><div class="m-sval">116 pk</div></div>
        <div class="m-spec"><div class="m-slbl">Transmissie</div><div class="m-sval">CVT automaat</div></div>
        <div class="m-spec"><div class="m-slbl">Verbruik</div><div class="m-sval">3.8 L/100km</div></div>
      </div>
      <p class="m-desc">Milieuvriendelijk rijden zonder laadkabel. Slechts 41.000 km — ideaal voor stad en snelweg. Lage verkeersbelasting!</p>
      <div class="m-acts">
        <a href="#afspraak" class="btn-r" onclick="closeM('yaris')">Plan een proefrit</a>
        <a href="tel:+3234819670" class="btn-o" style="border-color:rgba(255,255,255,.25)">📞 Bel ons</a>
      </div>
    </div>
  </div>
</div>

<div class="modal-ov" id="m-bmw">
  <div class="modal-box">
    <button class="m-close" onclick="closeM('bmw')">✕</button>
    <div class="swiper m-swiper" id="sw-bmw">
      <div class="swiper-wrapper">
        <div class="swiper-slide"><img src="https://images.unsplash.com/photo-1555215695-3004980ad029?w=800&q=80" alt="BMW 118d"></div>
        <div class="swiper-slide"><img src="https://images.unsplash.com/photo-1494976388531-d1058494cdd8?w=800&q=80" alt="BMW 118d interieur"></div>
        <div class="swiper-slide"><img src="https://images.unsplash.com/photo-1502877338535-766e1452684a?w=800&q=80" alt="BMW 118d detail"></div>
      </div>
      <div class="swiper-pagination"></div>
    </div>
    <div class="m-body">
      <div class="m-title">BMW 118d</div>
      <div class="m-price">€ 18.950</div>
      <div class="m-specs">
        <div class="m-spec"><div class="m-slbl">Bouwjaar</div><div class="m-sval">2019</div></div>
        <div class="m-spec"><div class="m-slbl">Kilometerstand</div><div class="m-sval">79.000 km</div></div>
        <div class="m-spec"><div class="m-slbl">Brandstof</div><div class="m-sval">Diesel</div></div>
        <div class="m-spec"><div class="m-slbl">Vermogen</div><div class="m-sval">150 pk</div></div>
        <div class="m-spec"><div class="m-slbl">Transmissie</div><div class="m-sval">8-traps automaat</div></div>
        <div class="m-spec"><div class="m-slbl">Extra</div><div class="m-sval">Navi · Leder · LED</div></div>
      </div>
      <p class="m-desc">Ultiem rijplezier met deze BMW 118d. Navigatie, lederen interieur, LED-verlichting en een krachtige maar zuinige diesel. Volledig nagekeken en in perfecte staat.</p>
      <div class="m-acts">
        <a href="#afspraak" class="btn-r" onclick="closeM('bmw')">Plan een proefrit</a>
        <a href="tel:+3234819670" class="btn-o" style="border-color:rgba(255,255,255,.25)">📞 Bel ons</a>
      </div>
    </div>
  </div>
</div>

<!-- DIENSTEN -->
<section id="diensten" class="section" style="background:var(--gray)">
  <div class="wrap">
    <div data-aos="fade-up" style="text-align:center;max-width:580px;margin:0 auto">
      <span class="lbl">Wat wij doen</span>
      <h2 class="h2">Onze diensten</h2>
      <p class="sub" style="margin:0 auto">Persoonlijke service staat centraal. Van aankoop tot nazorg — we staan voor u klaar.</p>
    </div>
    <div class="svc-grid">
      <div class="svc-card" data-aos="fade-up">
        <div class="svc-ic">🚗</div>
        <h3>Verkoop tweedehandswagens</h3>
        <p>Breed en gevarieerd aanbod van zorgvuldig geselecteerde tweedehandswagens. Elk voertuig is gekeurd en klaar voor de weg. Eerlijke prijzen zonder verborgen kosten.</p>
      </div>
      <div class="svc-card" data-aos="fade-up" data-aos-delay="100">
        <div class="svc-ic">🔧</div>
        <h3>Onderhoud &amp; herstellingen</h3>
        <p>Snel, vakkundig en eerlijk. Ons onderhoud garandeert dat uw wagen altijd in topvorm is — van kleine herstellingen tot grondige onderhoudsbeurten.</p>
      </div>
      <div class="svc-card" data-aos="fade-up" data-aos-delay="200">
        <div class="svc-ic">🔁</div>
        <h3>Inruil van uw wagen</h3>
        <p>Wil u uw huidige wagen inruilen? Wij schatten snel en eerlijk. Een vlotte administratieve afhandeling zodat u snel met uw nieuwe wagen op de weg bent.</p>
      </div>
    </div>
  </div>
</section>

<!-- OVER ONS -->
<section id="over" class="section">
  <div class="wrap">
    <div class="over-grid">
      <div class="over-img-wrap" data-aos="fade-right">
        <div class="over-acc"></div>
        <img class="over-img" src="https://images.unsplash.com/photo-1519085360753-af0119f7cbe7?w=600&q=80" alt="Tom Van Den Eynde — eigenaar Autohandel Van Den Eynde">
        <div class="over-badge">
          <div class="over-badge-n">15+</div>
          <div class="over-badge-l">jaar ervaring</div>
        </div>
      </div>
      <div data-aos="fade-left">
        <span class="lbl">Over ons</span>
        <h2 class="h2">Tom Van Den Eynde</h2>
        <p style="color:rgba(255,255,255,.65);font-size:.92rem;line-height:1.88">Autohandel Van Den Eynde is een gevestigde familiaire garage in het hart van Nijlen. Met meer dan 15 jaar ervaring staat Tom bekend om zijn eerlijkheid, persoonlijke aanpak en grondige vakkennis van de tweedehandsautomarkt.</p>
        <ul class="over-list">
          <li>Elk voertuig grondig technisch nagekeken vóór verkoop</li>
          <li>Transparante prijszetting — geen verborgen kosten of verrassingen</li>
          <li>Persoonlijk advies op maat van uw noden en budget</li>
          <li>Lokale kennis van de markt en regio Nijlen–Berlaar–Duffel</li>
          <li>Kwaliteitsgarantie op elke wagen die de garage verlaat</li>
        </ul>
        <div class="over-sig">
          <strong>Tom Van Den Eynde</strong>
          Eigenaar · Autohandel Van Den Eynde · Nijlen
        </div>
        <div style="margin-top:30px;display:flex;gap:14px;flex-wrap:wrap">
          <a href="#afspraak" class="btn-r">Maak een afspraak</a>
          <a href="tel:+3234819670" class="btn-o">📞 Bel Tom</a>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- REVIEWS -->
<section id="reviews" class="section" style="background:var(--dark)">
  <div class="wrap">
    <div data-aos="fade-up" style="text-align:center;max-width:560px;margin:0 auto">
      <span class="lbl">Klantervaringen</span>
      <h2 class="h2">Wat onze klanten zeggen</h2>
    </div>
    <div class="rev-grid">
      <div class="rev-card" data-aos="fade-up">
        <div class="rev-stars">★★★★★</div>
        <p class="rev-text">"Tom heeft ons fantastisch geholpen bij het vinden van de juiste wagen. Eerlijk advies, geen verkooptrucjes. De Golf rijdt perfect en alles werd snel en netjes geregeld. Absoluut een aanrader!"</p>
        <div class="rev-foot">
          <div class="rev-av">LV</div>
          <div><div class="rev-name">Liesbet Vermeersch</div><div class="rev-loc">Nijlen · 2024</div></div>
        </div>
      </div>
      <div class="rev-card" data-aos="fade-up" data-aos-delay="100">
        <div class="rev-stars">★★★★★</div>
        <p class="rev-text">"Ik heb mijn oude wagen ingeruild en diezelfde dag mijn nieuwe Toyota Yaris mee naar huis genomen. Professioneel, vriendelijk ontvangen en een eerlijke inruilprijs. Geweldige service!"</p>
        <div class="rev-foot">
          <div class="rev-av">JD</div>
          <div><div class="rev-name">Joris De Smedt</div><div class="rev-loc">Berlaar · 2024</div></div>
        </div>
      </div>
      <div class="rev-card" data-aos="fade-up" data-aos-delay="200">
        <div class="rev-stars">★★★★★</div>
        <p class="rev-text">"Voor de tweede keer een wagen gekocht bij Van Den Eynde — opnieuw 100% tevreden. Tom kent zijn vak, is altijd bereikbaar en zorgt dat alles perfect in orde is. Echte vakman!"</p>
        <div class="rev-foot">
          <div class="rev-av">KP</div>
          <div><div class="rev-name">Karen Pieters</div><div class="rev-loc">Duffel · 2025</div></div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- AFSPRAAK -->
<section id="afspraak" class="section">
  <div class="wrap">
    <div class="afspr-grid">
      <div class="afspr-info" data-aos="fade-right">
        <span class="lbl">Reserveer uw bezoek</span>
        <h2 class="h2">Plan uw bezoek</h2>
        <p>Kom gerust langs voor een proefrit, onderhoud of vrijblijvend adviesgesprek. Wij plannen graag een moment dat u past.</p>
        <ul class="steps">
          <li class="step">
            <div class="step-n">1</div>
            <div class="step-t"><strong>Kies datum en tijdstip</strong>Vul het formulier in met uw gewenste moment.</div>
          </li>
          <li class="step">
            <div class="step-n">2</div>
            <div class="step-t"><strong>Tom bevestigt</strong>We nemen contact op om uw afspraak te bevestigen.</div>
          </li>
          <li class="step">
            <div class="step-n">3</div>
            <div class="step-t"><strong>Welkom in de garage</strong>Dorsel 27, Nijlen — parkeren is geen probleem.</div>
          </li>
        </ul>
      </div>
      <div data-aos="fade-left">
        <div class="form-box">
          <div id="form-fields">
            <div class="form-row">
              <div class="fg">
                <label for="fn">Naam</label>
                <input type="text" id="fn" placeholder="Uw volledige naam">
                <div class="ferr" id="en">Vul uw naam in.</div>
              </div>
              <div class="fg">
                <label for="ft">Telefoon</label>
                <input type="tel" id="ft" placeholder="+32 ...">
                <div class="ferr" id="et">Vul een geldig telefoonnummer in.</div>
              </div>
            </div>
            <div class="fg">
              <label for="fe">E-mailadres</label>
              <input type="email" id="fe" placeholder="uw@email.be">
              <div class="ferr" id="ee">Vul een geldig e-mailadres in.</div>
            </div>
            <div class="form-row">
              <div class="fg">
                <label for="fd">Gewenste datum</label>
                <input type="date" id="fd">
                <div class="ferr" id="ed">Kies een datum.</div>
              </div>
              <div class="fg">
                <label for="ftd">Tijdstip</label>
                <select id="ftd">
                  <option value="">— Kies een tijdstip —</option>
                  <option>09:00</option><option>10:00</option><option>11:00</option>
                  <option>14:00</option><option>15:00</option><option>16:00</option><option>17:00</option>
                </select>
                <div class="ferr" id="etd">Kies een tijdstip.</div>
              </div>
            </div>
            <div class="fg">
              <label for="fr">Reden van bezoek</label>
              <select id="fr">
                <option value="">— Selecteer een reden —</option>
                <option>Proefrit plannen</option>
                <option>Onderhoud / herstelling</option>
                <option>Wagen verkopen / inruilen</option>
                <option>Vrijblijvend advies</option>
                <option>Andere</option>
              </select>
              <div class="ferr" id="er">Selecteer een reden.</div>
            </div>
            <div class="fg">
              <label for="fb">Extra bericht (optioneel)</label>
              <textarea id="fb" placeholder="Heeft u een specifieke wagen op het oog of bijkomende info?"></textarea>
            </div>
            <button class="btn-r" style="width:100%;justify-content:center;padding:15px;font-size:.82rem" onclick="doForm()">Afspraak bevestigen →</button>
          </div>
          <div id="form-ok">
            <div class="ok-icon">✅</div>
            <h3>Aanvraag ontvangen!</h3>
            <p>Tom neemt zo snel mogelijk contact met u op om uw afspraak te bevestigen.<br><br>
            <strong>Autohandel Van Den Eynde</strong><br>Dorsel 27, 2560 Nijlen<br>📞 +32 3 481 96 70</p>
            <a href="#aanbod" class="btn-r" style="margin-top:22px;display:inline-flex">Bekijk ons aanbod</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact" class="section" style="background:var(--gray)">
  <div class="wrap">
    <div data-aos="fade-up">
      <span class="lbl">Kom langs</span>
      <h2 class="h2">Contact &amp; openingsuren</h2>
    </div>
    <div class="cont-grid">
      <div data-aos="fade-right">
        <div class="ci-list">
          <div class="ci-item">
            <div class="ci-ic">📍</div>
            <div>
              <div class="ci-lbl">Adres</div>
              <div class="ci-val"><a href="https://maps.google.com/?q=Dorsel+27,+2560+Nijlen" target="_blank" rel="noopener">Dorsel 27, 2560 Nijlen</a></div>
            </div>
          </div>
          <div class="ci-item">
            <div class="ci-ic">📞</div>
            <div>
              <div class="ci-lbl">Telefoon</div>
              <div class="ci-val">
                <a href="tel:+3234819670">+32 3 481 96 70</a><br>
                <a href="tel:+32475298287" style="color:var(--muted);font-weight:400;font-size:.84rem">+32 475 29 82 87</a>
              </div>
            </div>
          </div>
          <div class="ci-item">
            <div class="ci-ic">✉️</div>
            <div>
              <div class="ci-lbl">E-mail</div>
              <div class="ci-val"><a href="mailto:info@vandeneyndeautos.be">info@vandeneyndeautos.be</a></div>
            </div>
          </div>
        </div>
        <div class="uren-tbl">
          <div class="lbl-sm">Openingsuren</div>
          <div class="uur-r"><span class="uur-day">Maandag – Vrijdag</span><span class="uur-time">09:00–12:00 · 13:00–18:00</span></div>
          <div class="uur-r cl"><span class="uur-day">Zaterdag</span><span class="uur-time">Op afspraak</span></div>
          <div class="uur-r cl"><span class="uur-day">Zondag</span><span class="uur-time">Gesloten</span></div>
        </div>
        <div class="soc-row">
          <a href="#" class="soc-btn" title="Facebook" aria-label="Facebook">
            <svg width="17" height="17" viewBox="0 0 24 24" fill="currentColor"><path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"></path></svg>
          </a>
          <a href="#" class="soc-btn" title="Instagram" aria-label="Instagram">
            <svg width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="2" width="20" height="20" rx="5"></rect><circle cx="12" cy="12" r="4"></circle><circle cx="17.5" cy="6.5" r="1.5" fill="currentColor" stroke="none"></circle></svg>
          </a>
          <a href="https://wa.me/32475298287" class="soc-btn" title="WhatsApp" aria-label="WhatsApp">
            <svg width="17" height="17" viewBox="0 0 24 24" fill="currentColor"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 0 1-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 0 1-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 0 1 2.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0 0 12.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 0 0 5.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 0 0-3.48-8.413z"></path></svg>
          </a>
        </div>
      </div>
      <div data-aos="fade-left">
        <div class="map-wrap">
          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2494.0!2d4.6584!3d51.1547!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47c3f0!2sDorsel+27%2C+2560+Nijlen!5e0!3m2!1snl!2sbe!4v1" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade" title="Locatie Autohandel Van Den Eynde, Dorsel 27, Nijlen"></iframe>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="wrap">
    <div class="ft-top">
      <div>
        <div class="ft-logo">Van Den Eynde <span>Auto's</span></div>
        <p class="ft-desc">Uw betrouwbare partner voor kwaliteitsvolle tweedehandswagens in Nijlen. Persoonlijke service, eerlijke prijzen — al meer dan 15 jaar.</p>
        <div class="ft-soc">
          <a href="#" title="Facebook" aria-label="Facebook"><svg width="15" height="15" viewBox="0 0 24 24" fill="currentColor"><path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"></path></svg></a>
          <a href="#" title="Instagram" aria-label="Instagram"><svg width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="2" width="20" height="20" rx="5"></rect><circle cx="12" cy="12" r="4"></circle><circle cx="17.5" cy="6.5" r="1.5" fill="currentColor" stroke="none"></circle></svg></a>
          <a href="https://wa.me/32475298287" title="WhatsApp" aria-label="WhatsApp"><svg width="15" height="15" viewBox="0 0 24 24" fill="currentColor"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 0 1-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 0 1-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 0 1 2.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0 0 12.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 0 0 5.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 0 0-3.48-8.413z"></path></svg></a>
        </div>
      </div>
      <div class="ft-col">
        <h4>Navigatie</h4>
        <ul class="ft-links">
          <li><a href="#aanbod">Ons aanbod</a></li>
          <li><a href="#over">Over ons</a></li>
          <li><a href="#diensten">Diensten</a></li>
          <li><a href="#afspraak">Afspraak maken</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </div>
      <div class="ft-col">
        <h4>Contact</h4>
        <ul class="ft-links">
          <li><a href="https://maps.google.com/?q=Dorsel+27,+2560+Nijlen" target="_blank" rel="noopener">Dorsel 27, 2560 Nijlen</a></li>
          <li><a href="tel:+3234819670">+32 3 481 96 70</a></li>
          <li><a href="tel:+32475298287">+32 475 29 82 87</a></li>
          <li><a href="mailto:info@vandeneyndeautos.be">info@vandeneyndeautos.be</a></li>
          <li style="color:var(--muted);font-size:.82rem;margin-top:4px">Ma–Vr: 09:00–12:00 · 13:00–18:00</li>
        </ul>
      </div>
    </div>
    <div class="ft-bot">
      <span>© 2025 Autohandel Van Den Eynde — Nijlen. Alle rechten voorbehouden.</span>
      <span>Gemaakt met ♥ in Nijlen</span>
    </div>
  </div>
</footer>

<!-- CHATBOT -->
<button id="cb-btn" onclick="cbToggle()" aria-label="Chat openen">
  💬
  <div class="cb-pulse"></div>
</button>
<div id="cb-win">
  <div class="cb-head">
    <div class="cb-av">🚗</div>
    <div class="cb-header-info">
      <div class="cb-hname">Digitale Assistent</div>
      <div class="cb-hstat">Van Den Eynde Auto's · Online</div>
    </div>
    <button class="cb-x" onclick="cbToggle()" aria-label="Sluit chat">✕</button>
  </div>
  <div class="cb-msgs" id="cb-msgs">
    <div class="cb-msg bot">Hallo! Ik ben de digitale assistent van Autohandel Van Den Eynde. Hoe kan ik u helpen? 👋</div>
  </div>
  <div class="cb-quick">
    <button class="cb-q" onclick="cbQ('Openingsuren')">Openingsuren</button>
    <button class="cb-q" onclick="cbQ('Adres')">Adres</button>
    <button class="cb-q" onclick="cbQ('Telefoon')">Telefoon</button>
    <button class="cb-q" onclick="cbQ('Afspraak')">Afspraak</button>
    <button class="cb-q" onclick="cbQ('Aanbod')">Aanbod</button>
  </div>
  <div class="cb-inp">
    <input type="text" id="cb-input" placeholder="Stel een vraag..." onkeydown="if(event.key==='Enter')cbSend()">
    <button id="cb-send" onclick="cbSend()" aria-label="Verstuur">➤</button>
  </div>
</div>

<!-- BACK TO TOP -->
<button id="btt" onclick="window.scrollTo({top:0,behavior:'smooth'})" aria-label="Terug naar boven">↑</button>

<script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
<script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
<script>
AOS.init({duration:680,once:true,offset:55});

// Nav scroll
var nav=document.getElementById('nav');
window.addEventListener('scroll',function(){
  nav.classList.toggle('sc',window.scrollY>60);
  document.getElementById('btt').classList.toggle('show',window.scrollY>400);
  animCounters();
});

// Mobile menu
function toggleMob(){
  document.getElementById('mob-menu').classList.toggle('open');
  document.getElementById('hbg').classList.toggle('open');
  document.body.style.overflow=document.getElementById('mob-menu').classList.contains('open')?'hidden':'';
}
function closeMob(){
  document.getElementById('mob-menu').classList.remove('open');
  document.getElementById('hbg').classList.remove('open');
  document.body.style.overflow='';
}

// Filter
document.querySelectorAll('.fbtn').forEach(function(b){
  b.addEventListener('click',function(){
    document.querySelectorAll('.fbtn').forEach(function(x){x.classList.remove('act')});
    b.classList.add('act');
    var f=b.dataset.f;
    document.querySelectorAll('.car-card').forEach(function(c){
      c.classList.toggle('hidden',f!=='all'&&c.dataset.fuel!==f);
    });
  });
});

// Modals + Swipers
var sws={};
function openM(id){
  document.getElementById('m-'+id).classList.add('open');
  document.body.style.overflow='hidden';
  if(!sws[id]){
    sws[id]=new Swiper('#sw-'+id,{loop:true,pagination:{el:'#m-'+id+' .swiper-pagination',clickable:true},autoplay:{delay:3500,disableOnInteraction:false}});
  }
}
function closeM(id){
  document.getElementById('m-'+id).classList.remove('open');
  document.body.style.overflow='';
}
document.querySelectorAll('.modal-ov').forEach(function(o){
  o.addEventListener('click',function(e){if(e.target===o){o.classList.remove('open');document.body.style.overflow='';}});
});
document.addEventListener('keydown',function(e){
  if(e.key==='Escape') document.querySelectorAll('.modal-ov.open').forEach(function(o){o.classList.remove('open');document.body.style.overflow='';});
});

// Counters
var counted=false;
function animCounters(){
  if(counted) return;
  var s=document.getElementById('counters');
  if(!s) return;
  if(s.getBoundingClientRect().top<window.innerHeight*.9){
    counted=true;
    document.querySelectorAll('.cnt-num').forEach(function(el){
      var target=+el.dataset.target;
      var em=el.querySelector('em').outerHTML;
      var t0=null;
      requestAnimationFrame(function tick(ts){
        if(!t0) t0=ts;
        var p=Math.min((ts-t0)/1800,1);
        var e=1-Math.pow(1-p,3);
        el.innerHTML=Math.round(e*target)+em;
        if(p<1) requestAnimationFrame(tick);
      });
    });
  }
}
animCounters();

// Form
document.getElementById('fd').setAttribute('min',new Date().toISOString().split('T')[0]);
function doForm(){
  var ok=true;
  function chk(id,eid,fn){var v=document.getElementById(id).value;var pass=fn(v);document.getElementById(eid).classList.toggle('show',!pass);if(!pass)ok=false;}
  chk('fn','en',function(v){return v.trim().length>=2});
  chk('ft','et',function(v){return/[\d\s+\-]{7,}/.test(v)});
  chk('fe','ee',function(v){return/\S+@\S+\.\S+/.test(v)});
  chk('fd','ed',function(v){return v.length>0});
  chk('ftd','etd',function(v){return v.length>0});
  chk('fr','er',function(v){return v.length>0});
  if(!ok) return;
  document.getElementById('form-fields').style.display='none';
  document.getElementById('form-ok').classList.add('show');
}

// Chatbot
var cbOpen=false;
function cbToggle(){cbOpen=!cbOpen;document.getElementById('cb-win').classList.toggle('open',cbOpen);}
function cbAdd(txt,type){
  var d=document.createElement('div');d.className='cb-msg '+type;d.textContent=txt;
  var m=document.getElementById('cb-msgs');m.appendChild(d);m.scrollTop=m.scrollHeight;
}
var cbRules=[
  {k:['uren','open','gesloten','wanneer'],r:'We zijn open maandag t/m vrijdag van 09:00–12:00 en 13:00–18:00. Zaterdag op afspraak, zondag gesloten.'},
  {k:['adres','locatie','waar','nijlen','dorsel'],r:'U vindt ons op Dorsel 27, 2560 Nijlen. Parkeren is geen probleem!'},
  {k:['telefoon','bellen','nummer','tel','gsm'],r:'Bel ons op +32 3 481 96 70 of +32 475 29 82 87 (ook WhatsApp beschikbaar).'},
  {k:['afspraak','bezoek','plannen','proefrit','reserver'],r:'Scroll naar "Afspraak maken" op deze pagina om een datum en tijdstip te kiezen. We bevestigen zo snel mogelijk!'},
  {k:['aanbod','wagen','auto','stock','beschikbaar','kopen'],r:'Ons actuele aanbod staat bovenaan de pagina. Klik op een wagen voor alle details en om een proefrit te plannen!'},
  {k:['prijs','kosten','budget','hoeveel','euro'],r:'Onze prijzen variëren per voertuig. Bekijk het aanbod voor actuele prijzen of neem contact op voor persoonlijk advies.'},
  {k:['inruil','inruilen','verkopen','mijn wagen'],r:'We schatten uw wagen snel en eerlijk. Neem contact op of maak een afspraak — we helpen u graag!'},
  {k:['dag','hallo','hoi','goedemorgen','goede','hey'],r:'Hallo! Fijn dat u contact opneemt. Waarmee kan ik u helpen — aanbod, openingsuren of een afspraak?'}
];
function cbReply(msg){
  var l=msg.toLowerCase();
  for(var i=0;i<cbRules.length;i++){
    for(var j=0;j<cbRules[i].k.length;j++){
      if(l.indexOf(cbRules[i].k[j])!==-1) return cbRules[i].r;
    }
  }
  return 'Bedankt voor uw vraag! Contacteer ons op +32 3 481 96 70 of info@vandeneyndeautos.be voor een persoonlijk antwoord.';
}
function cbSend(){
  var inp=document.getElementById('cb-input');
  var msg=inp.value.trim();if(!msg) return;
  cbAdd(msg,'user');inp.value='';
  setTimeout(function(){cbAdd(cbReply(msg),'bot');},550);
}
function cbQ(q){cbAdd(q,'user');setTimeout(function(){cbAdd(cbReply(q),'bot');},480);}
</script>
</body></html>
