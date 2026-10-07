<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Desert Runner</title>
<style>
:root{box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);--bg:#1d1433;--amber:#ffb02e;--ink:#2a1a00;color-scheme:dark}
html{height:100%;scroll-padding-top:env(safe-area-inset-top,0px)}
body{height:100%;margin:0;background:var(--bg);overflow:hidden;touch-action:none;user-select:none;-webkit-user-select:none;font-family:"Segoe UI",Tahoma,system-ui,sans-serif}
#wrap{height:100%;display:flex;align-items:center;justify-content:center}
#stage{position:relative}
canvas{width:100%;height:100%;display:block;border-radius:10px;touch-action:none}
.ui{position:absolute;inset:0;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:2.4vh;padding:0 8%;background:rgba(20,10,40,.62);color:#fff;text-align:center;border-radius:10px}
.ui.hide{display:none}
h1{margin:0;font-size:clamp(28px,5.5vh,50px);color:var(--amber)}
p{margin:0;font-size:clamp(14px,2.4vh,21px);line-height:1.6}
button{font:inherit;font-weight:700;font-size:clamp(15px,2.6vh,23px);padding:.55em 1.5em;border:0;border-radius:999px;background:var(--amber);color:var(--ink);cursor:pointer}
button.alt{background:rgba(255,255,255,.16);color:#fff}
button:focus-visible{outline:3px solid #fff;outline-offset:3px}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1.4vh;width:100%}
.card{background:rgba(255,255,255,.12);border:2px solid transparent;border-radius:14px;padding:1.2vh .4em;display:flex;flex-direction:column;align-items:center;gap:.6vh;font-size:clamp(12px,2vh,17px);cursor:pointer}
.card.on{border-color:var(--amber);background:rgba(255,176,46,.2)}
.card.lock{opacity:.95}
.card em{font-style:normal;font-weight:700;color:var(--amber)}
.av{position:relative;width:34px;height:56px}
.av i{position:absolute;left:7px;top:0;width:20px;height:20px;border-radius:50%}
.av b{position:absolute;left:3px;top:19px;width:28px;height:22px;border-radius:7px}
.av u{position:absolute;left:7px;top:40px;width:20px;height:14px;border-radius:4px}
#hud{position:absolute;left:0;right:0;top:0;padding:2.2% 4%;display:flex;flex-wrap:wrap;justify-content:space-between;align-items:flex-start;pointer-events:none;color:#fff}
#hud .sc{display:flex;flex-direction:column;line-height:1}
#hud .sc b{font-size:clamp(28px,6vh,52px);text-shadow:0 3px 0 rgba(0,0,0,.35),0 6px 18px rgba(0,0,0,.4);font-variant-numeric:tabular-nums}
#hud .sc span{font-size:clamp(10px,1.6vh,14px);letter-spacing:.3em;color:#ffe3a3;opacity:.9}
#hud .cn{display:flex;align-items:center;gap:8px;background:rgba(20,10,40,.45);backdrop-filter:blur(6px);border:1.5px solid rgba(255,255,255,.22);border-radius:999px;padding:.35em .9em;font-weight:800;font-size:clamp(15px,2.8vh,24px)}
#hud .cn i{width:1em;height:1em;border-radius:50%;background:radial-gradient(circle at 35% 30%,#fff3a8,#ffd23d 45%,#c98a00);box-shadow:0 0 10px rgba(255,210,61,.7)}
#hud .bs{width:100%;margin-top:.6em;font-size:clamp(10px,1.7vh,14px);letter-spacing:.2em;color:#ffe3a3;opacity:.85}
#vig{position:absolute;inset:0;pointer-events:none;border-radius:10px;background:radial-gradient(ellipse at center,transparent 58%,rgba(25,8,45,.5))}
#spd{position:absolute;inset:0;pointer-events:none;opacity:0;background:repeating-conic-gradient(from 0deg,rgba(255,255,255,.22) 0 .5deg,transparent .5deg 7deg);-webkit-mask-image:radial-gradient(circle,transparent 42%,#000 88%);mask-image:radial-gradient(circle,transparent 42%,#000 88%)}
#stage{overflow:hidden;border-radius:10px}
h1{background:linear-gradient(180deg,#fff2c9,#ffb02e 60%,#e0572d);-webkit-background-clip:text;background-clip:text;color:transparent;filter:drop-shadow(0 3px 0 rgba(0,0,0,.35));letter-spacing:.05em;text-transform:uppercase}
button{background:linear-gradient(180deg,#ffd06a,#ffb02e 55%,#f08a12);box-shadow:0 4px 0 #a85a00,0 10px 24px rgba(0,0,0,.35);transition:transform .12s,box-shadow .12s;min-width:9em}
button:active{transform:translateY(3px);box-shadow:0 1px 0 #a85a00}
button.alt{background:rgba(255,255,255,.14);color:#fff;box-shadow:inset 0 0 0 1.5px rgba(255,255,255,.35);backdrop-filter:blur(6px)}
.ui{backdrop-filter:blur(2px);background:radial-gradient(ellipse at center,rgba(20,10,40,.4),rgba(20,10,40,.8))}
#menu{justify-content:flex-start;padding-top:12%;padding-bottom:9%;background:linear-gradient(180deg,rgba(20,10,40,.72),rgba(20,10,40,0) 42%,rgba(20,10,40,.05) 68%,rgba(20,10,40,.8))}
#menu #play{margin-top:auto}

body{background:radial-gradient(ellipse at 50% 30%,#3a2160,#140a28 70%)}
@keyframes fin{from{opacity:0;transform:scale(.97)}}
.ui{animation:fin .28s ease-out}
button.ib{min-width:0;width:2.4em;height:2.4em;padding:0;border-radius:50%;font-size:clamp(14px,2.4vh,20px);background:rgba(20,10,40,.5);color:#fff;box-shadow:inset 0 0 0 1.5px rgba(255,255,255,.3);backdrop-filter:blur(6px)}
#ctl{position:absolute;right:4%;top:100%;margin-top:8px;display:flex;flex-direction:column;gap:8px;pointer-events:auto}
@keyframes pop{0%{opacity:0;transform:translate(-50%,0) scale(.6)}15%{opacity:1;transform:translate(-50%,0) scale(1.1)}80%{opacity:1}100%{opacity:0;transform:translate(-50%,-30px) scale(1)}}
#toast{position:absolute;left:50%;top:26%;opacity:0;pointer-events:none;font-weight:800;font-size:clamp(22px,4.6vh,40px);color:#fff;text-shadow:0 3px 0 rgba(0,0,0,.4),0 0 24px rgba(255,176,46,.8);white-space:nowrap}
#toast.on{animation:pop 1.4s ease-out}
@keyframes bump{50%{transform:scale(1.22)}}
#hud .cn.b{animation:bump .18s}
#res{font-size:clamp(14px,2.4vh,21px)}
#res .big{font-size:clamp(44px,9vh,80px);font-weight:800;line-height:1;text-shadow:0 4px 0 rgba(0,0,0,.35)}
#res .row{display:flex;gap:2.2em;justify-content:center;margin-top:1.4vh}
#res .row span{display:flex;flex-direction:column;gap:.3em;font-size:clamp(10px,1.6vh,14px);letter-spacing:.2em;color:#ffe3a3}
#res .row b{font-size:clamp(18px,3.4vh,30px);color:#fff;letter-spacing:0}
.nb{display:inline-block;margin-bottom:1vh;padding:.2em .9em;border-radius:999px;background:linear-gradient(180deg,#ffd06a,#f08a12);color:var(--ink);font-weight:800;font-size:clamp(12px,2vh,17px)}
@media (prefers-reduced-motion:reduce){.ui,#toast.on,#hud .cn.b{animation:none}}
.co{display:inline-block;width:1em;height:1em;border-radius:50%;background:radial-gradient(circle at 35% 30%,#fff3a8,#ffd23d 45%,#c98a00);box-shadow:0 0 10px rgba(255,210,61,.7)}
button:disabled{opacity:.55;filter:saturate(.4);box-shadow:none;cursor:default}
.pill{display:flex;align-items:center;gap:.5em;padding:.35em .9em;border-radius:999px;background:rgba(20,10,40,.5);border:1.5px solid rgba(255,255,255,.2);font-weight:800;font-size:clamp(14px,2.4vh,20px);color:#fff}
#menu{justify-content:space-between;padding:6% 6% 7%}
.top{display:flex;align-items:center;gap:2%;width:100%}
.top .ib{margin-left:auto}
.logo{display:flex;flex-direction:column;align-items:center;gap:.4vh}
.logo small{font-weight:800;letter-spacing:.55em;margin-right:-.55em;color:#ffe3a3;font-size:clamp(13px,2.4vh,20px);text-shadow:0 2px 0 rgba(0,0,0,.4)}
.logo h1{font-size:clamp(46px,10.5vh,96px);line-height:.95}
.bot{width:100%;display:flex;flex-direction:column;align-items:center;gap:2.4vh}
#menu #play{margin:0}
button.big{font-size:clamp(20px,3.8vh,32px);padding:.55em 2.4em;animation:glow 2.2s ease-in-out infinite}
@keyframes glow{50%{box-shadow:0 4px 0 #a85a00,0 0 36px rgba(255,176,46,.7)}}
.dock{display:flex;gap:2%;width:100%}
button.tile{flex:1;min-width:0;position:relative;display:flex;flex-direction:column;align-items:center;gap:.25em;padding:.7em .2em;border-radius:16px;background:rgba(255,255,255,.1);color:#fff;box-shadow:inset 0 0 0 1.5px rgba(255,255,255,.2);backdrop-filter:blur(6px);font-size:clamp(11px,1.8vh,15px)}
button.tile i{font-style:normal;font-size:1.9em;line-height:1}
button.tile u{position:absolute;top:.5em;right:22%;width:.8em;height:.8em;border-radius:50%;background:#e0572d;box-shadow:0 0 0 2px #1d1433}
.ui.sheet{justify-content:flex-start;padding:7% 6% 5%;gap:2vh;background:rgba(20,10,40,.93)}
.hd{width:100%;display:flex;align-items:center;justify-content:space-between}
.hd h2{margin:0;font-size:clamp(22px,4vh,34px);color:#ffe3a3}
.days{display:grid;grid-template-columns:repeat(4,1fr);gap:1.2vh;width:100%}
.d{border-radius:14px;padding:1.2vh .2em;background:rgba(255,255,255,.1);font-size:clamp(11px,1.9vh,16px);line-height:1.5}
.d:last-child{grid-column:span 2}
.d.cur{outline:2px solid #ffb02e;background:rgba(255,176,46,.2)}
.d.done{opacity:.5}
.rows{width:100%;display:flex;flex-direction:column;gap:1vh}
.r,.tg{display:flex;justify-content:space-between;align-items:center;gap:.8em;padding:1.3vh 4%;border-radius:12px;background:rgba(255,255,255,.08);font-size:clamp(14px,2.3vh,19px);text-align:left}
.r b{color:#ffe3a3}
.r.h{justify-content:flex-start}
.r.h i{font-style:normal;font-size:1.4em}
.tg input{appearance:none;-webkit-appearance:none;width:2.6em;height:1.5em;border-radius:99px;background:rgba(255,255,255,.25);position:relative;transition:.15s;cursor:pointer;margin:0;flex:none}
.tg input::after{content:"";position:absolute;top:.15em;left:.15em;width:1.2em;height:1.2em;border-radius:50%;background:#fff;transition:.15s}
.tg input:checked{background:#ffb02e}
.tg input:checked::after{transform:translateX(1.1em)}
.tg input:focus-visible{outline:3px solid #fff;outline-offset:2px}
#fl{position:absolute;inset:0;background:#fff;opacity:0;pointer-events:none}
#fl.on{animation:flsh .35s ease-out}
@keyframes flsh{from{opacity:.55}to{opacity:0}}
@media (prefers-reduced-motion:reduce){button.big,#fl.on{animation:none}}
.ui,button,#hud .cn,button.ib,button.tile,button.alt{-webkit-backdrop-filter:none!important;backdrop-filter:none!important}
#spd{transform:scale(1.5);will-change:opacity}

/* ===== AAA MENU ===== */
#menu{justify-content:space-between;padding:5% 5% 4%;background:radial-gradient(ellipse 90% 38% at 50% 100%,rgba(255,176,46,.26),transparent 70%),linear-gradient(180deg,rgba(14,6,32,.9) 0,rgba(14,6,32,.35) 22%,rgba(14,6,32,0) 40%,rgba(14,6,32,.08) 58%,rgba(14,6,32,.93) 100%)}
#menu .top{gap:2.2%}
.pill.cp,.pill.ep{position:relative;padding:.28em .45em .28em .8em;background:linear-gradient(180deg,rgba(70,40,115,.92),rgba(26,12,54,.95));border:1.5px solid rgba(255,214,120,.55);box-shadow:inset 0 1px 0 rgba(255,255,255,.25),0 3px 10px rgba(0,0,0,.45);cursor:pointer}
.pill b{font-variant-numeric:tabular-nums}
.pill .plus{margin-left:.25em;width:1.45em;height:1.45em;border-radius:50%;display:grid;place-items:center;background:linear-gradient(180deg,#7be36a,#2f9e2a);color:#fff;font-size:.85em;line-height:1;box-shadow:0 2px 0 #1b6a18}
.pill small{font-size:.6em;color:#ffe3a3;font-variant-numeric:tabular-nums;min-width:2.6em;text-align:center}
.logo{position:relative;margin-top:1vh;gap:.2vh}
.logo small{display:flex;align-items:center;gap:.9em;margin-right:0;letter-spacing:.6em;font-size:clamp(14px,2.6vh,22px)}
.logo small::before,.logo small::after{content:"";width:2.4em;height:2px;background:linear-gradient(90deg,transparent,#ffd06a)}
.logo small::after{transform:scaleX(-1)}
.logo h1{font-size:clamp(40px,min(9.2vh,16vw),86px);font-style:italic;font-weight:900;line-height:.9;padding:0 .08em;background:linear-gradient(105deg,transparent 40%,rgba(255,255,255,.95) 50%,transparent 60%) 200% 0/250% 100% no-repeat,linear-gradient(180deg,#fff7d6 0,#ffd256 38%,#ff9a1f 62%,#e0452d 100%);-webkit-background-clip:text;background-clip:text;color:transparent;filter:drop-shadow(0 2px 0 #7a3000) drop-shadow(0 5px 0 #4a1c00) drop-shadow(0 14px 18px rgba(0,0,0,.6));animation:sheen 3.6s linear infinite}
@keyframes sheen{to{background-position:-100% 0,0 0}}
.side{position:absolute;top:46%;display:flex;flex-direction:column;gap:2.2vh}
.side.l{left:4%}.side.r{right:4%}
button.sb{min-width:0;position:relative;width:clamp(54px,9.6vh,80px);aspect-ratio:1;padding:0;border-radius:18px;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:.1em;color:#fff;font-size:clamp(10px,1.6vh,13px);font-weight:800;background:linear-gradient(180deg,rgba(100,60,165,.95),rgba(36,18,72,.97));box-shadow:inset 0 0 0 1.5px rgba(255,214,120,.55),inset 0 1px 0 rgba(255,255,255,.3),0 4px 0 #120826,0 9px 16px rgba(0,0,0,.45)}
button.sb:active{box-shadow:inset 0 0 0 1.5px rgba(255,214,120,.55),0 1px 0 #120826}
button.sb i{font-style:normal;font-size:2em;line-height:1}
button.sb u{position:absolute;top:.45em;right:.45em;width:.9em;height:.9em;border-radius:50%;background:#e0452d;box-shadow:0 0 0 2px #1d1433}
button.sb .tag{position:absolute;bottom:-.7em;padding:.1em .7em;border-radius:99px;background:linear-gradient(180deg,#7be36a,#2f9e2a);font-style:normal;font-size:.8em;letter-spacing:.06em;box-shadow:0 2px 0 #1b6a18}
.bot{gap:1.8vh}
.bestbar{display:flex;align-items:center;gap:.6em;padding:.3em 1.2em;border-radius:99px;background:rgba(0,0,0,.42);border:1px solid rgba(255,214,120,.4);font-weight:800;color:#ffe3a3;letter-spacing:.18em;font-size:clamp(11px,1.8vh,15px)}
.bestbar b{color:#fff;letter-spacing:.04em}
button.big{position:relative;overflow:hidden;width:86%;font-size:clamp(28px,5.4vh,46px);font-style:italic;font-weight:900;letter-spacing:.1em;padding:.32em 0;border-radius:22px;color:#4a2400;text-shadow:0 2px 0 rgba(255,255,255,.45);background:linear-gradient(180deg,#ffe685 0,#ffb82e 48%,#ff8a12 52%,#ffb02e 100%);box-shadow:0 6px 0 #a85a00,0 12px 28px rgba(0,0,0,.5),inset 0 2px 0 rgba(255,255,255,.75);animation:glow2 2.2s ease-in-out infinite}
button.big:active{transform:translateY(4px);box-shadow:0 2px 0 #a85a00,inset 0 2px 0 rgba(255,255,255,.75)}
@keyframes glow2{50%{box-shadow:0 6px 0 #a85a00,0 0 40px rgba(255,176,46,.75),inset 0 2px 0 rgba(255,255,255,.75)}}
button.big::after{content:"";position:absolute;top:0;left:-60%;width:36%;height:100%;background:linear-gradient(105deg,transparent,rgba(255,255,255,.7),transparent);transform:skewX(-20deg);animation:shine 2.8s ease-in-out infinite}
@keyframes shine{0%,55%{left:-60%}100%{left:130%}}
button.big .cost{position:absolute;right:5%;top:50%;transform:translateY(-50%);font-style:normal;font-size:.42em;letter-spacing:0;padding:.25em .7em;border-radius:99px;background:rgba(40,16,0,.78);color:#ffe3a3;text-shadow:none}
button.big.empty .cost{display:none}
button.big.empty{background:linear-gradient(180deg,#8ef07a,#35b82f 48%,#23951f 52%,#35b82f 100%);color:#fff;text-shadow:0 2px 0 rgba(0,0,0,.3);box-shadow:0 6px 0 #14611a,0 12px 28px rgba(0,0,0,.5),inset 0 2px 0 rgba(255,255,255,.6);animation:none}
.nav{display:flex;width:100%;padding:.5vh 1%;border-radius:20px;background:linear-gradient(180deg,rgba(44,24,88,.94),rgba(16,8,36,.97));box-shadow:inset 0 0 0 1.5px rgba(255,214,120,.35),0 -2px 18px rgba(255,176,46,.15),0 8px 20px rgba(0,0,0,.5)}
button.nt{flex:1;min-width:0;background:none;box-shadow:none;border-radius:14px;color:#d8c9f5;display:flex;flex-direction:column;align-items:center;gap:.15em;padding:.6em 0;font-size:clamp(11px,1.8vh,15px);font-weight:800;letter-spacing:.06em;text-transform:uppercase}
button.nt:active{transform:none;background:rgba(255,176,46,.2)}
button.nt i{font-style:normal;font-size:1.9em;line-height:1}
button.nt+button.nt{box-shadow:-1px 0 0 rgba(255,255,255,.1)}
/* colors shop */
#chars .grid{flex:1;min-height:0;overflow-y:auto;align-content:start;touch-action:pan-y;padding:.4vh .3vh 1vh;scrollbar-width:none}
#chars .grid::-webkit-scrollbar{display:none}
#chars .card{touch-action:pan-y;padding:1.6vh .3em 1.2vh;gap:1vh;border-radius:16px}
#chars .av{transform:scale(1.25);margin:.6vh 0}
#chars p{min-height:1.4em;font-size:clamp(12px,2vh,16px)}
/* energy */
.bolts{display:flex;justify-content:center;gap:2.5%;width:100%;margin:1vh 0}
.bolts span{font-size:clamp(30px,6.4vh,52px);filter:grayscale(1) opacity(.3);transition:filter .2s}
.bolts span.on{filter:drop-shadow(0 0 10px rgba(255,210,61,.85))}
#energy p{font-size:clamp(13px,2.2vh,18px)}
#energy p.dim{opacity:.7}
/* game over options */
#over{gap:1.5vh}
.opts{display:flex;flex-direction:column;gap:1.2vh;width:100%}
button.opt{width:100%;display:flex;justify-content:space-between;align-items:center;gap:.6em;padding:.6em 1.1em;border-radius:16px;font-size:clamp(14px,2.4vh,20px);text-align:left}
button.opt em{font-style:normal;display:flex;align-items:center;gap:.4em;background:rgba(0,0,0,.28);border-radius:99px;padding:.15em .75em;white-space:nowrap}
button.opt.ad{background:linear-gradient(180deg,#8ef07a,#35b82f 55%,#1f8a1c);box-shadow:0 4px 0 #14611a,0 10px 24px rgba(0,0,0,.35);color:#fff;text-shadow:0 1px 0 rgba(0,0,0,.3)}
button.opt.ad:active{box-shadow:0 1px 0 #14611a}
button.opt.ad:disabled{box-shadow:none}
@media (prefers-reduced-motion:reduce){.logo h1,button.big,button.big::after{animation:none}}

/* ===== GRACE UI ===== */
.ui,button,#toast{font-family:Optima,'Palatino Linotype','Book Antiqua',Georgia,serif}
h1{background:none;-webkit-background-clip:border-box;background-clip:border-box;color:#e6d9ae;font-weight:400;letter-spacing:.3em;filter:none;text-shadow:0 2px 8px #000}
button{background:rgba(0,0,0,.55);color:#d4c294;border-radius:0;font-weight:400;text-shadow:none;text-transform:uppercase;letter-spacing:.16em;box-shadow:inset 0 0 0 1px #8f7a4a}
button:active{transform:none;background:rgba(212,194,148,.2);box-shadow:inset 0 0 0 1px #e6d9ae}
button.alt{background:rgba(0,0,0,.55);color:#d4c294;box-shadow:inset 0 0 0 1px #8f7a4a}
button.ib{background:rgba(0,0,0,.6);border-radius:0;color:#d4c294;box-shadow:inset 0 0 0 1px #8f7a4a;transform:rotate(45deg)}
button.ib:active{transform:rotate(45deg)}
.pill,.pill.cp,.pill.ep{background:rgba(0,0,0,.6);border:0;border-radius:0;color:#e6d9ae;font-weight:400;letter-spacing:.1em;box-shadow:inset 0 0 0 1px #8f7a4a}
.pill .plus{background:none;box-shadow:none;border:1px solid #8f7a4a;border-radius:0;color:#d4c294}
#hud .cn{background:rgba(0,0,0,.6);border:0;border-radius:0;box-shadow:inset 0 0 0 1px #8f7a4a;font-weight:400}
#hud .sc b{font-weight:400;color:#e6d9ae;letter-spacing:.06em}#hud .sc span{color:#8f7a4a}
#toast{font-weight:400;letter-spacing:.3em;text-transform:uppercase;color:#e6d9ae;text-shadow:0 0 22px rgba(230,217,174,.6),0 2px 4px #000;background:linear-gradient(90deg,transparent,rgba(0,0,0,.75),transparent);padding:.4em 3em}
#menu{background:linear-gradient(180deg,rgba(0,0,0,.75) 0,transparent 28%,transparent 45%,rgba(0,0,0,.92) 100%)}
.logo h1{font-size:clamp(28px,min(6.6vh,11vw),60px);letter-spacing:.2em;margin-right:-.2em;text-transform:uppercase;color:#e6d9ae;animation:none;filter:drop-shadow(0 2px 8px #000)}
.logo small{color:#8f7a4a;font-weight:400;text-shadow:none}
.logo small::before,.logo small::after{background:linear-gradient(90deg,transparent,#8f7a4a)}
.logo::after{content:"◆";color:#8f7a4a;font-size:.9em}
button.sb{width:clamp(48px,8vh,64px);border-radius:0;background:rgba(0,0,0,.55);color:#d4c294;font-weight:400;box-shadow:inset 0 0 0 1px #8f7a4a,inset 0 0 0 4px #000,inset 0 0 0 5px rgba(143,122,74,.5)}
button.sb i{font-size:1.5em;filter:grayscale(.7)}
button.sb .tag{background:#6b5a2e;border-radius:0;box-shadow:none}
.bestbar{background:none;border:0;border-radius:0;color:#8f7a4a;font-weight:400;letter-spacing:.3em}.bestbar b{color:#e6d9ae}
button.big{width:72%;border-radius:0;background:linear-gradient(90deg,transparent,rgba(212,194,148,.2),transparent);box-shadow:none;border-top:1px solid rgba(212,194,148,.45);border-bottom:1px solid rgba(212,194,148,.45);color:#f0e4bd;font-style:normal;font-weight:400;font-size:clamp(17px,3vh,26px);letter-spacing:.35em;padding:.75em 0;text-shadow:0 2px 4px #000;animation:none}
button.big::after{display:none}button.big:active{transform:none;box-shadow:none}
button.big .cost{background:none;font-size:.5em;letter-spacing:.1em;color:#8f7a4a}
button.big.empty{background:linear-gradient(90deg,transparent,rgba(143,29,29,.35),transparent);color:#e6b0a8;box-shadow:none;text-shadow:none}
.nav{flex-direction:column;align-items:center;gap:0;background:none;box-shadow:none;padding:0;border-radius:0}
button.nt{flex:none;width:72%;flex-direction:row;justify-content:center;background:none;box-shadow:none;border-radius:0;padding:.7em 0;font-size:clamp(12px,2.1vh,17px);letter-spacing:.32em;color:#bfb08a}
button.nt i{display:none}button.nt+button.nt{box-shadow:none}
button.nt:hover,button.nt:active{background:linear-gradient(90deg,transparent,rgba(212,194,148,.18),transparent);color:#f0e4bd}
.ui.sheet,#pau{background:rgba(6,6,6,.93);box-shadow:inset 0 0 0 1px #8f7a4a,inset 0 0 0 7px #060606,inset 0 0 0 8px rgba(143,122,74,.5)}
.hd h2{flex:1;margin:0 4% 0 0;padding:0 0 .4em;background:none;box-shadow:none;border-bottom:1px solid rgba(143,122,74,.6);color:#e6d9ae;font-weight:400;letter-spacing:.3em;text-transform:uppercase;font-size:clamp(17px,2.8vh,24px)}
.card,#chars .card{background:rgba(255,255,255,.04);border:0;border-radius:0;box-shadow:inset 0 0 0 1px rgba(143,122,74,.55)}
.card.on{background:rgba(212,194,148,.1);box-shadow:inset 0 0 0 1px #e6d9ae,0 0 14px rgba(230,217,174,.25)}
.card em{color:#d4c294;font-weight:400}
.r,.tg,.d{background:rgba(255,255,255,.03);border-radius:0;box-shadow:none;border-bottom:1px solid rgba(143,122,74,.4);color:#d9ccaa}
.r b{color:#e6d9ae;font-weight:400}
.d.cur{outline:0;background:rgba(212,194,148,.15);box-shadow:inset 0 0 0 1px #e6d9ae}
.tg input{border-radius:0}.tg input::after{border-radius:0}.tg input:checked{background:#a08a54}
button.opt{border-radius:0}button.opt em{background:none;border-radius:0;color:#e6d9ae}
button.opt.ad{background:rgba(30,50,30,.6);color:#cfe0b0;text-shadow:none;box-shadow:inset 0 0 0 1px #6f8a4a}
#over{background:linear-gradient(180deg,rgba(0,0,0,.55),rgba(0,0,0,.9) 35%,rgba(0,0,0,.9) 70%,rgba(0,0,0,.55))}
#over h1{font-size:clamp(34px,8vh,72px);color:#9b1c1c;letter-spacing:.22em;filter:drop-shadow(0 0 18px rgba(150,0,0,.55))}
#res .big{font-weight:400;color:#e6d9ae;letter-spacing:.06em;text-shadow:0 2px 8px #000}
#res .row span{color:#8f7a4a}.nb{background:none;color:#e6d9ae;border:1px solid #8f7a4a;border-radius:0;letter-spacing:.3em;font-weight:400}
</style>
</head>
<body>
<div id="wrap"><div id="stage">
<canvas id="c"></canvas><div id="hud"><div class="sc"><b id="hs">0</b><span>SCORE</span></div><div class="cn"><i></i><b id="hc">0</b></div><div class="bs" id="hb"></div><div id="ctl"><button class="ib" id="pz" aria-label="Pause">⏸</button><button class="ib mu" aria-label="Sound">🔊</button></div></div><div id="toast"></div><div id="vig"></div><div id="spd"></div><div id="fl"></div>
<div id="menu" class="ui">
<div class="top"><div class="pill cp" data-go="chars" role="button" tabindex="0"><i class="co"></i><b id="w1">0</b><span class="plus">+</span></div><div class="pill ep" data-go="energy" role="button" tabindex="0"><span>⚡</span><b id="en">5/5</b><small id="et"></small><span class="plus">+</span></div><button class="ib" data-go="sets" aria-label="Settings">⚙</button></div>
<div class="logo"><small>DESERT</small><h1>Runner</h1></div>
<div class="side l"><button class="sb" data-go="daily"><i>🎁</i>Daily<u id="dot"></u></button></div>
<div class="side r"><button class="sb" data-go="energy"><i>⚡</i>Energy<em class="tag">FREE</em></button></div>
<div class="bot"><div class="bestbar">🏆 BEST <b id="bst">0</b></div>
<button id="play" class="big"><span id="pl">PLAY</span><em class="cost">⚡ 1</em></button>
<nav class="nav"><button class="nt" data-go="chars"><i>🎨</i>Colors</button><button class="nt" data-go="stats"><i>📊</i>Stats</button><button class="nt" data-go="help"><i>❓</i>Help</button></nav></div></div>
<div id="chars" class="ui sheet hide"><div class="hd"><h2>Colors</h2><button class="ib" data-go="menu" aria-label="Close">✕</button></div><div class="pill"><i class="co"></i><b id="w2">0</b></div><div class="grid" id="grid"></div><p id="cmsg"></p></div>
<div id="daily" class="ui sheet hide"><div class="hd"><h2>Daily reward</h2><button class="ib" data-go="menu" aria-label="Close">✕</button></div><div class="days" id="days"></div><button id="claim">Claim</button></div>
<div id="stats" class="ui sheet hide"><div class="hd"><h2>Stats</h2><button class="ib" data-go="menu" aria-label="Close">✕</button></div><div class="rows" id="srows"></div></div>
<div id="help" class="ui sheet hide"><div class="hd"><h2>How to play</h2><button class="ib" data-go="menu" aria-label="Close">✕</button></div><div class="rows">
<div class="r h"><i>↔</i><span>Swipe left or right to change lane</span></div><div class="r h"><i>⬆</i><span>Swipe up or tap to jump. Jump again for a flip</span></div><div class="r h"><i>⬇</i><span>Swipe down to slide. In mid-air, to roll on landing</span></div><div class="r h"><i>🔴</i><span>A red circle means a rock is about to fall</span></div><div class="r h"><i>🐪</i><span>Jump over camels and avoid toppling poles</span></div><div class="r h"><i>⌨</i><span>Arrows or WASD, Space to jump, P to pause</span></div></div></div>
<div id="sets" class="ui sheet hide"><div class="hd"><h2>Settings</h2><button class="ib" data-go="menu" aria-label="Close">✕</button></div><div class="rows"><label class="tg"><span>Music</span><input type="checkbox" id="smus"></label><label class="tg"><span>Sound effects</span><input type="checkbox" id="ssfx"></label><label class="tg"><span>Vibration</span><input type="checkbox" id="svib"></label></div></div>
<div id="energy" class="ui sheet hide"><div class="hd"><h2>Energy</h2><button class="ib" data-go="menu" aria-label="Close">✕</button></div>
<div class="bolts" id="bolts"></div><p id="enext"></p><p class="dim">Every run uses 1 ⚡<br>You get +1 ⚡ every 4 minutes. Watch an ad to refill faster.</p>
<button id="ead" class="opt ad"><span>WATCH AD</span><em>+1 ⚡</em></button><p id="emsg"></p><button class="alt" data-go="menu">Back</button></div>
<div id="over" class="ui hide"><h1>YOU DIED</h1><div id="res"></div><div class="opts"><button id="revc" class="opt"><span>🎬 AD + CONTINUE</span><em><i class="co"></i><b id="rcost">50</b></em></button><button id="reva" class="opt ad"><span>CONTINUE</span><em>🎬 FREE · 1×</em></button></div><button id="again" class="alt">Play Again</button><button id="home" class="alt">Menu</button></div>
<div id="ad" class="ui hide"><p id="adtxt"></p></div>
<div id="pau" class="ui hide"><h1>Paused</h1><button id="resume">Resume</button><button id="pmenu" class="alt">Menu</button></div>
</div></div>
<script src="https://www.youtube.com/game_api/v1"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
<script>
(function(){
var W=450,H=800,HZ=250,FOC=300,CAMH=240,PD=200,LW=85,FAR=1700,CX=W/2;
var cv=document.getElementById('c'),stage=document.getElementById('stage');

function $(id){return document.getElementById(id)}
function fit(){var w=Math.min(innerWidth,innerHeight*W/H);stage.style.width=w+'px';stage.style.height=(w*H/W)+'px'}
addEventListener('resize',fit);fit();


var Y_=window.ytgame;
function safe(f){try{return f()}catch(e){}}
var Ads={
  demo:function(m){return new Promise(function(r){$('adtxt').textContent=m;$('ad').classList.remove('hide');setTimeout(function(){$('ad').classList.add('hide');r(true)},1500)})},
  interstitial:function(){
    if(Y_&&Y_.ads&&Y_.ads.requestInterstitialAd)return Y_.ads.requestInterstitialAd().then(function(){return true},function(){return false});
    return this.demo('Demo interstitial ad')},
  rewarded:function(){
    if(Y_&&Y_.ads&&Y_.ads.requestRewardedAd)return Y_.ads.requestRewardedAd().then(function(){return true},function(){return false});
    return this.demo('Demo rewarded ad')}
};


var best=0;safe(function(){best=+localStorage.getItem('dr3_best')||0});
function hx(h){return[parseInt(h.substr(1,2),16),parseInt(h.substr(3,2),16),parseInt(h.substr(5,2),16)]}
function mix(a,b,t){var x=hx(a),y=hx(b);return'#'+[0,1,2].map(function(i){return('0'+Math.round(x[i]+(y[i]-x[i])*t).toString(16)).slice(-2)}).join('')}
function mk(j,sc,pc,tb,wr,sk,p){return{c:p,a1:mix(j,'#000000',.3),a2:j,a3:mix(j,'#ffffff',.5),sl:mix(j,'#000000',.12),sc:sc,pc:pc,wr:wr,tb:tb,tb2:mix(tb,'#000000',.15),sk:sk}}
var CH=[
mk('#ffb02e','#e0572d','#3b2a3f','#f4ecdc','#c9a56a','#c68a5a',0),
mk('#1fb5ad','#b24fd1','#2d2a4a','#fff4e0','#e8d9b0','#a8704a',1100),
mk('#2f7be0','#ffd23d','#2a2f3b','#e8eefb','#b9c3d4','#8d5a3b',1200),
mk('#e0364a','#ffe3a3','#3a1f2b','#2a2030','#d9b98a','#d49a72',1300),
mk('#34344f','#ffcc33','#14141f','#16161f','#6a6aa0','#b07a55',1500),
mk('#1fa65a','#ffe066','#1d3a2b','#f2fff0','#cfe8c0','#a8704a',1600),
mk('#8e44ec','#ffd1f5','#2a1a4a','#f3e8ff','#cdb5f2','#c68a5a',1800),
mk('#ff4fa3','#fff0a8','#4a1f3a','#fff0f7','#ffc2dc','#d49a72',2000),
mk('#a6e22e','#ff6a2e','#263a1a','#f7ffe0','#d6ef9a','#8d5a3b',2200),
mk('#ff6a2e','#ffe14d','#3a1a12','#fff1e0','#ffc08a','#c68a5a',2400),
mk('#e8f4ff','#4fa8ff','#2a3b52','#ffffff','#b8d4ee','#d49a72',2600),
mk('#ffd23d','#b3261e','#4a3200','#fff6d0','#e0b030','#a8704a',3000),
mk('#e020c0','#20f0ff','#1a0a30','#fbe0ff','#a060d0','#b07a55',3500),
mk('#20e0f0','#ff3d7f','#0a2a38','#e0ffff','#80d0e0','#8d5a3b',4000),
mk('#f0a090','#fff0e0','#5a2a30','#ffeae0','#e8b8a8','#d49a72',4500),
mk('#ff3b1f','#ffcc33','#1a1010','#2a1a1a','#5a3a30','#c68a5a',5000),
mk('#8ef0c8','#ff8fb0','#1f4a40','#f0fff8','#bfe8d8','#a8704a',5500),
mk('#2a2f9a','#ffd23d','#12143a','#e0e4ff','#8890d8','#c68a5a',6000)];
function fixOwn(a){return CH.map(function(_,i){return i===0||(a&&a[i])?1:0})}
var wallet=0,own=fixOwn(),sel=0,paid=0,nF=0,nC=0,nP=0;
safe(function(){wallet=+localStorage.getItem('dr3_w')||0;own=fixOwn(JSON.parse(localStorage.getItem('dr4_o')));sel=+localStorage.getItem('dr4_s')||0});
if(!CH[sel]||!own[sel])sel=0;
var stat={g:0,c:0,d:0},dr={d:'',s:-1},cfg={m:1,s:1,v:1},pd=0;
safe(function(){var x=JSON.parse(localStorage.getItem('dr3_x'));if(x){stat=x.t||stat;dr=x.r||dr;cfg=x.p||cfg}});
var EMAX=5,EREG=240000,en={n:EMAX,t:Date.now()},rc=0,freeUsed=false;
safe(function(){var x=JSON.parse(localStorage.getItem('dr4_e'));if(x&&x.n>=0&&x.t>0)en=x});
function eTick(){var now=Date.now();if(en.t>now)en.t=now;if(en.n>=EMAX){en.n=EMAX;en.t=now}else{var g=Math.floor((now-en.t)/EREG);if(g>0){en.n=Math.min(EMAX,en.n+g);en.t=en.n>=EMAX?now:en.t+g*EREG}}}
function eUI(){eTick();var f=en.n>=EMAX,tm='',i;if(!f){var s=Math.max(0,Math.ceil((EREG-(Date.now()-en.t))/1000));tm=Math.floor(s/60)+':'+('0'+s%60).slice(-2)}
 $('en').textContent=en.n+'/'+EMAX;$('et').textContent=f?'FULL':tm;
 var b=$('bolts');if(!b.children.length){for(i=0;i<EMAX;i++)b.appendChild(document.createElement('span')).textContent='⚡'}
 for(i=0;i<EMAX;i++)b.children[i].className=i<en.n?'on':'';
 $('enext').textContent=f?'Energy is full':'Next ⚡ in '+tm;
 $('ead').disabled=f;$('pl').textContent=en.n<1?'GET ⚡':'PLAY';$('play').classList.toggle('empty',en.n<1)}
function canPlay(){eTick();return en.n>0}
function useE(){eTick();if(en.n<1)return false;if(en.n>=EMAX)en.t=Date.now();en.n--;save();eUI();return true}
function addE(){eTick();en.n=Math.min(EMAX,en.n+1);if(en.n>=EMAX)en.t=Date.now();save();eUI()}
function save(){var d=JSON.stringify({v:4,e:en,b:best,w:wallet,o:own,s:sel,t:stat,r:dr,p:cfg});safe(function(){localStorage.setItem('dr3_w',wallet);localStorage.setItem('dr4_o',JSON.stringify(own));localStorage.setItem('dr4_s',sel);localStorage.setItem('dr4_e',JSON.stringify(en));localStorage.setItem('dr3_best',best);localStorage.setItem('dr3_x',JSON.stringify({t:stat,r:dr,p:cfg}))});safe(function(){var p=Y_.game.saveData(d);if(p&&p.catch)p.catch(function(){})})}
safe(function(){Y_.game.loadData().then(function(t){if(!t)return;var d=JSON.parse(t);best=Math.max(best,d.b|0);wallet=d.w|0;if(d.v===4){own=fixOwn(d.o);sel=d.s|0}if(!CH[sel]||!own[sel])sel=0;if(d.e&&d.e.n>=0){en=d.e;eUI()}if(d.t)stat=d.t;if(d.r)dr=d.r;if(d.p){cfg=d.p;syncSet()}cards()}).catch(function(){})});
function wl(){$('w1').textContent=wallet;$('w2').textContent=wallet;$('bst').textContent=best;$('dot').style.display=dailyReady()?'':'none'}
function cards(msg){
  var h='';CH.forEach(function(c,i){
    var o=own[i],lab=sel===i?'Selected':o?'Select':'🪙 '+c.c;
    h+='<div class="card'+(sel===i?' on':'')+(o?'':' lock')+'" data-i="'+i+'"><div class="av"><i style="background:'+c.tb+'"></i><b style="background:linear-gradient(90deg,'+c.a1+','+c.a3+')"></b><u style="background:'+c.pc+'"></u></div><em>'+lab+'</em></div>'});
  $('grid').innerHTML=h;wl();$('cmsg').textContent=msg||'';
}
$('grid').onclick=function(e){var el=e.target.closest('.card');if(!el)return;var i=+el.dataset.i,c=CH[i];
  if(!own[i]){if(wallet<c.c){cards('Not enough coins — keep running!');return}wallet-=c.c;own[i]=1}
  sel=i;save();cards('')};
var AC=null,muted=false,sysAud=true,paused=false,ms=0,nb=false,mus_i=0,mus_t=0,SC5=[0,3,5,7,10,7,5,3];
safe(function(){muted=localStorage.getItem('dr3_m')==='1'});
safe(function(){if(Y_&&Y_.IN_PLAYABLES_ENV){sysAud=Y_.system.isAudioEnabled()!==false;Y_.system.onAudioEnabledChange(function(v){sysAud=v!==false})}});
function au(){if(!AC)safe(function(){AC=new(window.AudioContext||window.webkitAudioContext)();var b=AC.createBuffer(1,1,22050),q=AC.createBufferSource();q.buffer=b;q.connect(AC.destination);q.start(0)});if(AC&&AC.state!=='running')safe(function(){var p=AC.resume();if(p&&p.catch)p.catch(function(){})})}
['pointerdown','pointerup','touchend','mousedown','click','keydown'].forEach(function(e){addEventListener(e,au,true)});
function tone(f,d,ty,v,to,dl,m){if(!AC||muted||!sysAud||!(m?cfg.m:cfg.s))return;var o=AC.createOscillator(),g=AC.createGain(),t=AC.currentTime+(dl||0);o.type=ty||'sine';o.frequency.setValueAtTime(f,t);if(to)o.frequency.exponentialRampToValueAtTime(to,t+d);g.gain.setValueAtTime(v||.12,t);g.gain.exponentialRampToValueAtTime(.001,t+d);o.connect(g);g.connect(AC.destination);o.start(t);o.stop(t+d+.02)}
var SFX={jump:function(){},sw:function(){tone(500,.09,'sine',.05,200)},coin:function(){tone(988,.07,'square',.045);tone(1319,.14,'square',.045,0,.06)},land:function(){tone(110,.12,'sine',.12,50)},die:function(k){if(k==='camel'){tone(240,.45,'sawtooth',.09,95);tone(150,.4,'square',.04,70,.12)}else if(k==='rock'){tone(90,.3,'sine',.28,30);nz(.25,.12,300)}else{tone(180,.22,'square',.08,70);nz(.12,.06,1500)}},click:function(){tone(660,.06,'triangle',.07)},mile:function(){tone(523,.1,'triangle',.08);tone(784,.1,'triangle',.08,0,.1);tone(1046,.18,'triangle',.08,0,.2)}};
var DEG=[0,1,4,5,7,8,10,12],NB=null,mus_L=0,mus_p=0,mus_n=0,mus_c=null,hv={},fe=16.7,fc=0,rtm=0,sgi=0,mus_w=0,RT=[0,1,0,7],PH=[[[4,1.5],[3,.5],[2,1],[1,1],[0,2],[-1,1]],[[0,1],[1,1],[2,1.5],[3,.5],[4,2],[-1,1]],[[4,1],[5,1],[4,.5],[3,.5],[2,1],[1,.5],[0,1.5],[-1,1]],[[6,1],[5,1],[4,2],[3,1],[2,1],[1,1],[0,3],[-1,1]],[[4,.5],[5,.5],[4,.5],[3,.5],[2,.5],[3,.5],[2,.5],[1,.5],[0,1],[-1,1]],[[0,.5],[1,.5],[2,.5],[3,.5],[4,1],[6,.5],[5,.5],[4,.5],[3,.5],[2,1],[0,1]]];
function fq(n){return 73.42*Math.pow(2,n/12)}
function nbuf(){if(!NB){NB=AC.createBuffer(1,AC.sampleRate*.3|0,AC.sampleRate);var a=NB.getChannelData(0);for(var i=0;i<a.length;i++)a[i]=Math.random()*2-1}return NB}
function nz(d,v,hp,dl,m){if(!AC||muted||!sysAud||!(m?cfg.m:cfg.s))return;var q=AC.createBufferSource(),f=AC.createBiquadFilter(),g=AC.createGain(),t=AC.currentTime+(dl||0);q.buffer=nbuf();f.type='highpass';f.frequency.value=hp;g.gain.setValueAtTime(v,t);g.gain.exponentialRampToValueAtTime(.001,t+d);q.connect(f);f.connect(g);g.connect(AC.destination);q.start(t);q.stop(t+d+.02)}
function ney(f,d,v){if(!AC||muted||!sysAud||!cfg.m)return;var t=AC.currentTime,e=t+d+.15,o=AC.createOscillator(),o2=AC.createOscillator(),l=AC.createOscillator(),lg=AC.createGain(),h2=AC.createGain(),mx=AC.createGain(),lp=AC.createBiquadFilter(),g=AC.createGain(),q=AC.createBufferSource(),bp=AC.createBiquadFilter(),bn=AC.createGain();
 o.frequency.value=f;o2.frequency.value=f*2;l.frequency.value=5.3;
 lg.gain.setValueAtTime(0,t);lg.gain.linearRampToValueAtTime(f*.009,t+Math.min(d*.7,.45));
 l.connect(lg);lg.connect(o.frequency);lg.connect(o2.frequency);
 h2.gain.value=.2;o.connect(mx);o2.connect(h2);h2.connect(mx);
 q.buffer=nbuf();q.loop=true;bp.type='bandpass';bp.frequency.value=f*2.5;bp.Q.value=1.2;bn.gain.value=.16;q.connect(bp);bp.connect(bn);bn.connect(mx);
 lp.type='lowpass';lp.frequency.value=2600;mx.connect(lp);lp.connect(g);g.connect(AC.destination);
 g.gain.setValueAtTime(0,t);g.gain.linearRampToValueAtTime(v,t+.1);g.gain.linearRampToValueAtTime(v*.8,t+Math.max(.12,d-.1));g.gain.linearRampToValueAtTime(0,e);
 [o,o2,l,q].forEach(function(n){n.start(t);n.stop(e+.02)})}
function music(dt){mus_t-=dt;if(mus_t>0)return;
 var it=Math.min(1,(speed-700)/800),s16=15/(108+it*32),L=rtm>65?3:rtm>40?2:rtm>18?1:0,s=mus_i%16,bar=mus_i>>4,rt=RT[bar%4],e;
 mus_t=Math.max(-.05,mus_t)+s16;
 if(L>mus_L){mus_L=L;ney(fq(43),1.2,.07);nz(.5,.05,3000,0,1)}
 if(s===0)tone(fq(rt+24),s16*16,'sine',.02,0,0,1);
 if(--mus_w<=0){var pool=L<1?[0,1,2]:L<2?[0,2,3,4]:[2,3,4,5,3,5];if(mus_n===0||!mus_c)mus_c=PH[pool[mus_p%pool.length]];e=mus_c[mus_n];if(e[0]>=0)ney(fq(DEG[e[0]]+24+(L>2&&(mus_p&1)?12:0)),e[1]*2*s16*.95,.085+.02*L);mus_w=e[1]*2;mus_n++;if(mus_n>=mus_c.length){mus_n=0;mus_p++}}
 if((L>0?s%4===0:(s===0||s===8))||(L>1&&s===10))tone(150,.14,'sine',.22,45,0,1);
 if(L>0&&(s===4||s===12)){nz(.12,.09,1800,0,1);tone(200,.07,'triangle',.06,110,0,1)}
 if(s%2===0)nz(.04,.035,7000,0,1);else if(L>0)nz(.025,.02,8000,0,1);
 if(L>0&&(s===2||s===7||s===10||s===15))tone(480,.05,'triangle',.05,300,0,1);
 if(L>1&&(s===6||s===11))tone(120,.12,'sine',.12,80,0,1);
 if(s===0||s===3||s===6||s===8||s===10||s===14||(L>1&&s===12))tone(fq(rt+12+(s===14?7:0)),.16,'triangle',.1,0,0,1);
 mus_i++}
function toast(t){var e=$('toast');e.textContent=t;e.classList.remove('on');void e.offsetWidth;e.classList.add('on')}
function bump(){var e=document.querySelector('#hud .cn');e.classList.remove('b');void e.offsetWidth;e.classList.add('b')}
function muteUI(){[].forEach.call(document.querySelectorAll('.mu'),function(b){b.textContent=muted?'🔇':'🔊'});safe(function(){localStorage.setItem('dr3_m',muted?1:0)})}
muteUI();
document.addEventListener('click',function(e){var t=e.target;if(t.closest&&t.closest('button,.card'))SFX.click()});
var curv=0,cT=0,ct=4,dust=[],dacc=0,dj=false,fl=0,roll=0,lt=0,rollOn=false;
var st='menu',things,speed,dist,coinN,score=0,px,tl,camx,py,pv,slide,nextRow,nextSc,inv,revived,deaths=0,last=0,tt=0;
function reset(){rc=0;freeUsed=false;mus_i=0;mus_t=0;mus_L=0;mus_p=0;mus_n=0;mus_w=0;pd=0;rtm=0;sgi=0;ms=0;nb=false;nF=1800;nC=3500;nP=0;paid=0;dj=false;fl=0;roll=0;lt=0;rollOn=false;curv=0;cT=0;ct=4;dust=[];things=[];speed=700;dist=0;coinN=0;score=0;px=0;tl=0;camx=0;py=0;pv=0;slide=0;nextRow=700;nextSc=0;inv=0;revived=false}
reset();


function bend(d){var u=Math.max(0,d-PD)/1000;return curv*u*u}
function X(x,d){return CX+(x-camx)*FOC/d+bend(d)}
function Yp(h,d){return HZ+(CAMH-h)*FOC/d}


function lane(dir){if(st==='play'&&!paused){var n=Math.max(-1,Math.min(1,tl+dir));tl=n}}
function jump(){if(st!=='play'||paused)return;if(py<=0){SFX.jump();pv=900;slide=0;roll=0;dj=false;fl=0}else if(!dj){SFX.jump(1);dj=true;pv=780;fl=.001}}
function dive(){if(st!=='play'||paused)return;if(py>0){pv=-1300;rollOn=true;fl=0}else{slide=.65;SFX.sw()}}
var sx0,sy0,done=false;
cv.addEventListener('pointerdown',function(e){e.preventDefault();sx0=e.clientX;sy0=e.clientY;done=false;try{cv.setPointerCapture(e.pointerId)}catch(_){}});
cv.addEventListener('pointermove',function(e){
  if(done||sx0==null)return;var dx=e.clientX-sx0,dy=e.clientY-sy0;
  if(Math.abs(dx)<28&&Math.abs(dy)<28)return;done=true;
  if(Math.abs(dx)>Math.abs(dy))lane(dx>0?1:-1);else if(dy<0)jump();else dive();
});
cv.addEventListener('pointerup',function(){if(!done)jump();sx0=null});
addEventListener('keydown',function(e){var c=e.code;
  if(c==='ArrowLeft'||c==='KeyA')lane(-1);else if(c==='ArrowRight'||c==='KeyD')lane(1);
  else if(c==='ArrowUp'||c==='KeyW'||c==='Space'){e.preventDefault();jump()}
  else if(c==='ArrowDown'||c==='KeyS')dive();else if(c==='KeyP'||c==='Escape')setPause(!paused)});


function row(){
  var z=FAR-PD,free=(Math.random()*3|0)-1,q=Math.min(.95,.45+rtm/220),cp=Math.max(.06,.7-.65*Math.min(1,rtm/150)),cn=Math.max(2,5-(rtm/40|0)),KS=rtm<18?['low']:rtm<40?['low','over']:['low','over','tall'];
  for(var l=-1;l<=1;l++){
    if(l===free){if(Math.random()<cp)for(var i=0;i<cn;i++)things.push({k:'coin',x:l*LW,z:z+i*70});continue}
    if(Math.random()<q)things.push({k:KS[Math.random()*KS.length|0],x:l*LW,z:z})
  }
}
function scenery(){
  var s=Math.random()<.5?-1:1;
  var r_=Math.random();things.push({k:r_<.35?'cac':r_<.65?'rock':'pil',x:s*(2.3+Math.random()*2.2)*LW,z:FAR-PD});
}

function start(){if(!useE()){noE();return}paused=false;$('pau').classList.add('hide');reset();applyChar();st='play';$('menu').classList.add('hide');$('over').classList.add('hide')}
function die(k,d,o){if(st!=='play')return;shake=.7;SFX.die(k);if(cfg.v)safe(function(){navigator.vibrate(70)});dyk=k||'wall';dyd=d||1;dyt=0;dx0=px;dy0=py;if(o&&o.k==='fall'){o.h=0;o.ph=2}st='dying';var e=$('fl');e.classList.remove('on');void e.offsetWidth;e.classList.add('on');for(var u=0;u<16;u++)dust.push({x:px+(Math.random()-.5)*40,h:0,vx:(Math.random()-.5)*300,vy:60+Math.random()*160,l:.7})}
function endRun(){st='over';deaths++;
  var isNb=score>best&&score>0;if(isNb)best=score;
  safe(function(){Y_.engagement.sendScore({value:score})});
  if(!revived)stat.g++;stat.c+=coinN-paid;var md=Math.floor(dist/50);stat.d+=md-pd;pd=md;wallet+=coinN-paid;paid=coinN;save();$('res').innerHTML=(isNb?'<span class="nb">NEW BEST!</span>':'')+'<div class="big">'+score+'</div><div class="row"><span>BEST<b>'+best+'</b></span><span>COINS<b>+'+coinN+'</b></span></div>';
  updOver();
  $('over').classList.remove('hide');
}

function fallRock(){var l=Math.random()<.6?tl:(Math.random()*3|0)-1;things.push({k:'fall',x:l*LW,z:FAR-PD,h:480,fv:0,ph:0,tf:.55+Math.random()*.2})}
function camel(){var d=Math.random()<.5?1:-1;things.push({k:'camel',x:-d*LW*3.2,z:FAR-PD,dir:d,vx:110+Math.random()*50})}
function poles(){var tr=rtm>95&&Math.random()<.3+Math.min(.3,(rtm-95)/300),ts=Math.random()<.5?-1:1;[-1,1].forEach(function(s){things.push({k:'pole',x:s*(1.5*LW+30),z:FAR-PD,di:-s,trap:tr&&s===ts,th:0,w:0,ph:0})})}
function haz(dt){
  for(var i=0;i<things.length;i++){var o=things[i],k=o.k;
    if(k==='fall'){
      if(o.ph===0&&o.z<speed*o.tf)o.ph=1;
      if(o.ph===1){o.fv+=2200*dt;o.h-=o.fv*dt;
        if(o.h<=0){o.h=0;o.ph=2;shake=Math.max(shake,.25)}
        else if(inv<=0&&Math.abs(o.z)<45&&Math.abs(o.x-px)<LW*.5&&o.h<95){die('rock',0,o);return}}
      else if(o.ph===2&&inv<=0&&Math.abs(o.z)<40&&Math.abs(o.x-px)<LW*.46&&py<45){die('rock',0,o);return}
    }else if(k==='camel'){
      o.x+=o.dir*o.vx*dt;if(Math.abs(o.x)>LW*4)o.dead=1;
      if(inv<=0&&Math.abs(o.z)<45&&Math.abs(o.x-px)<42&&py<100){die('camel',o.dir,o);return}
    }else if(k==='pole'&&o.trap){
      if(o.ph===0&&o.z<speed*.5)o.ph=1;
      if(o.ph===1){o.w+=14*dt;o.th=Math.min(1.5708,o.th+o.w*dt);if(o.th>=1.5708)o.ph=2}
      if(o.ph>0&&inv<=0&&Math.abs(o.z)<28){var u=(px-o.x)*o.di;if(u>-12&&u<215*Math.sin(o.th)+10&&o.th>.3&&(o.th<1.25||py<40)){die('wall');return}}
    }
  }
}
function update(dt){music(dt);
  rtm+=dt;speed=Math.min(700+rtm*7,2000);var gi=rtm>130?5:rtm>95?4:rtm>65?3:rtm>40?2:rtm>18?1:0;if(gi>sgi){sgi=gi;toast(gi<5?'Stage '+(gi+1):'No mercy!');SFX.mile()}
  dist+=speed*dt;
  px+=(tl*LW-px)*Math.min(1,dt*14);
  camx+=(px*.55-camx)*Math.min(1,dt*6);
  var air0=py>0;
  if(py>0||pv>0){pv-=2600*dt;py+=pv*dt;if(py<=0){py=0;pv=0}}
  if(air0&&py<=0){SFX.land();lt=.18;shake=Math.max(shake,.18);fl=0;if(rollOn){roll=.55;slide=.55;rollOn=false}for(var u=0;u<8;u++)dust.push({x:px+(Math.random()-.5)*40,h:0,vx:(Math.random()-.5)*160,vy:40+Math.random()*80,l:.5})}
  if(fl>0)fl=Math.min(1,fl+dt/.6);if(roll>0)roll-=dt;if(lt>0)lt-=dt;
  if(slide>0)slide-=dt;
  if(inv>0)inv-=dt;
  ct-=dt;if(ct<=0){cT=([-1,0,1][Math.random()*3|0])*(70+Math.random()*50);ct=3+Math.random()*3}
  curv+=(cT-curv)*Math.min(1,dt*.8);
  dacc-=dt;if(dacc<=0&&py<=0){dacc=slide>0?.03:.07;dust.push({x:px+(Math.random()-.5)*24,h:0,vx:(Math.random()-.5)*60,vy:40+Math.random()*50,l:.5})}
  for(var j=0;j<dust.length;j++){var q=dust[j];q.x+=q.vx*dt;q.h+=q.vy*dt;q.l-=dt}
  dust=dust.filter(function(q){return q.l>0});
  nextRow-=speed*dt;if(nextRow<=0){row();nextRow=speed*(Math.max(.42,1.9-rtm*.0105)+Math.random()*.3)}
  nextSc-=speed*dt;if(nextSc<=0){scenery();nextSc=140+Math.random()*160}
  if(rtm>40){nF-=speed*dt;if(nF<=0){fallRock();nF=speed*(Math.max(.9,2.6-rtm/80)+Math.random())}}
  if(rtm>65){nC-=speed*dt;if(nC<=0){camel();nC=speed*(Math.max(2.2,6.5-rtm/40)+Math.random()*2.5)}}
  nP-=speed*dt;if(nP<=0){poles();nP=520+Math.random()*420}
  for(var i=0;i<things.length;i++){
    var o=things[i];o.z-=speed*dt;
    if(o.k==='coin'){
      if(!o.got&&Math.abs(o.z)<40&&Math.abs(o.x-px)<LW*.6&&Math.abs(py+30-60)<70){o.got=1;coinN++;SFX.coin();bump()}
    }else if(inv<=0&&(o.k==='low'||o.k==='tall'||o.k==='over')&&Math.abs(o.z)<35&&Math.abs(o.x-px)<LW*.46){
      var top=py+(slide>0?30:66),hit=o.k==='tall'||(o.k==='low'&&py<45)||(o.k==='over'&&top>55&&py<115);
      if(hit){die('wall');return}
    }
  }
  haz(dt);things=things.filter(function(o){return o.z>-420&&!o.got&&!o.dead});
  score=Math.floor(dist/50)+coinN*10;if(score>=(ms+1)*1000){ms++;toast(ms*1000+' pts');SFX.mile()}if(!nb&&best>0&&score>best){nb=true;toast('New best!');SFX.mile()}
}


var qq=1;function rs(){var w=stage.clientWidth||W,bw=Math.min(w*(devicePixelRatio||1),720)*qq;RN.setSize(Math.round(bw),Math.round(bw*H/W),false)}
var RN=new THREE.WebGLRenderer({canvas:cv,antialias:!/Android|iPhone|iPad|Mobile/i.test(navigator.userAgent),powerPreference:'high-performance'});RN.setPixelRatio(1);rs();addEventListener('resize',rs);RN.shadowMap.enabled=true;RN.shadowMap.type=THREE.PCFSoftShadowMap;RN.toneMapping=THREE.ACESFilmicToneMapping;RN.toneMappingExposure=1.25;
var SC=new THREE.Scene(),cam=new THREE.PerspectiveCamera(62,W/H,5,2400);
(function(){var c=document.createElement('canvas');c.width=2;c.height=256;var g=c.getContext('2d'),gr=g.createLinearGradient(0,0,0,256);gr.addColorStop(0,'#2b1b52');gr.addColorStop(.55,'#9a4468');gr.addColorStop(.82,'#f4a15a');gr.addColorStop(1,'#f4c88a');g.fillStyle=gr;g.fillRect(0,0,2,256);SC.background=new THREE.CanvasTexture(c)})();
SC.fog=new THREE.Fog(0xe9a46c,500,1900);
SC.add(new THREE.HemisphereLight(0xffd9b0,0x6a4a3a,.8));
var sun=new THREE.DirectionalLight(0xffc27a,1.15);sun.castShadow=true;sun.shadow.mapSize.set(1024,1024);
var sh_=sun.shadow.camera;sh_.left=-260;sh_.right=260;sh_.top=260;sh_.bottom=-260;sh_.near=10;sh_.far=900;sun.shadow.bias=-.0006;SC.add(sun,sun.target);
function mt(c,r){return new THREE.MeshStandardMaterial({color:c,roughness:r||.85,side:THREE.DoubleSide})}
var UB=new THREE.BoxGeometry(1,1,1),CY=new THREE.CylinderGeometry(1,1,1,10),SP=new THREE.SphereGeometry(1,14,10),DO=new THREE.DodecahedronGeometry(1,0),mcache={};
function mc(c){return mcache[c]||(mcache[c]=mt(c))}
function P(par,geo,m,x,y,z,sx,sy,sz,rz){var o=new THREE.Mesh(geo,m);o.position.set(x,y,z);o.scale.set(sx,sy,sz);if(rz)o.rotation.z=rz;o.castShadow=true;o.receiveShadow=true;par.add(o);return o}
var gm=new THREE.Mesh(new THREE.PlaneGeometry(6000,6000),mt(0xd9a45b,1));gm.rotation.x=-Math.PI/2;gm.position.set(0,-3,-1500);gm.receiveShadow=true;SC.add(gm);
var sd_=new THREE.Mesh(new THREE.SphereGeometry(120,24,16),new THREE.MeshBasicMaterial({color:0xffd88a,fog:false}));sd_.position.set(260,170,-2100);SC.add(sd_);
for(var mi=0;mi<7;mi++){var mn=new THREE.Mesh(new THREE.ConeGeometry(220+mi*30,260+(mi*53%140),6),new THREE.MeshBasicMaterial({color:0x5a2a5e,fog:false}));mn.position.set(-1100+mi*380,100,-2150);SC.add(mn)}
var RM=[mt(0x8a6a55,.95),mt(0x7e5f4c,.95)],AM=new THREE.MeshStandardMaterial({color:0xffb02e,emissive:0x442200}),DM=mt(0xc9b08f),tiles=[];
function nt(base,rep,amp){var c=document.createElement('canvas');c.width=c.height=128;var g=c.getContext('2d');g.fillStyle=base;g.fillRect(0,0,128,128);for(var i=0;i<1400;i++){g.fillStyle='rgba('+(Math.random()<.5?'0,0,0,':'255,235,200,')+Math.random()*amp+')';g.fillRect(Math.random()*128,Math.random()*128,2,2)}var tx=new THREE.CanvasTexture(c);tx.wrapS=tx.wrapT=THREE.RepeatWrapping;tx.repeat.set(rep,rep);return tx}
gm.material.color.set(0xffffff);gm.material.map=nt('#d9a45b',80,.18);
function bt(b){var c=document.createElement('canvas');c.width=c.height=128;var g=c.getContext('2d');g.fillStyle=b;g.fillRect(0,0,128,128);for(var i=0;i<900;i++){g.fillStyle='rgba('+(Math.random()<.5?'0,0,0,':'255,235,200,')+Math.random()*.2+')';g.fillRect(Math.random()*128,Math.random()*128,2,2)}g.strokeStyle='rgba(30,15,5,.65)';g.lineWidth=3;for(var r=0;r<4;r++){var y=r*32;g.beginPath();g.moveTo(0,y);g.lineTo(128,y);g.stroke();for(var x=(r%2)*32;x<128;x+=64){g.beginPath();g.moveTo(x,y);g.lineTo(x,y+32);g.stroke()}}var t=new THREE.CanvasTexture(c);t.wrapS=t.wrapT=THREE.RepeatWrapping;t.repeat.set(3,1.2);return t}
RM[0].color.set(0xffffff);RM[0].map=bt('#8a6a55');RM[1].color.set(0xffffff);RM[1].map=bt('#7e5f4c');
(function(){var c=document.createElement('canvas');c.width=c.height=128;var g=c.getContext('2d'),r=g.createRadialGradient(64,64,0,64,64,64);r.addColorStop(0,'rgba(255,220,150,.9)');r.addColorStop(.35,'rgba(255,170,90,.35)');r.addColorStop(1,'rgba(255,140,80,0)');g.fillStyle=r;g.fillRect(0,0,128,128);var s=new THREE.Sprite(new THREE.SpriteMaterial({map:new THREE.CanvasTexture(c),blending:THREE.AdditiveBlending,fog:false,depthWrite:false}));s.scale.set(1300,1300,1);s.position.set(260,170,-2080);SC.add(s)})();
var dunes=[];for(var di=0;di<16;di++){var dm=new THREE.Mesh(SP,mt([0xd9a45b,0xcf9a50,0xe0ae66][di%3],1));dm.scale.set(260+di%4*60,50+di%5*14,300);dm.receiveShadow=true;dm.userData={i:di,sd:di%2?1:-1,ox:620+(di*97%300)};SC.add(dm);dunes.push(dm)}
var MN=140,mga=new Float32Array(MN*3),mgg=new THREE.BufferGeometry();for(var mi2=0;mi2<MN;mi2++){mga[mi2*3]=(Math.random()-.5)*900;mga[mi2*3+1]=Math.random()*220;mga[mi2*3+2]=-1100+Math.random()*1500}
mgg.setAttribute('position',new THREE.BufferAttribute(mga,3));var mpts=new THREE.Points(mgg,new THREE.PointsMaterial({color:0xffe3b0,size:5,transparent:true,opacity:.5,depthWrite:false}));mpts.frustumCulled=false;SC.add(mpts);
var cpv={x:0,y:78,z:185},clv={x:0,y:92,z:0},cfv=46,shake=0;
for(var ti=0;ti<34;ti++){var tg_=new THREE.Group(),rd=P(tg_,UB,RM[0],0,-2,0,3*LW,4,70);tg_.r=rd;
  [-1,1].forEach(function(s){P(tg_,UB,AM,s*1.5*LW,-1,0,8,6,70);P(tg_,UB,DM,s*LW/2,.5,0,4,1,32)});tg_.traverse(function(m){m.castShadow=false});SC.add(tg_);tiles.push(tg_)}
var mats={};['jk','sl','pc','sh','cp','sk','ac'].forEach(function(k){mats[k]=mt(0xffffff,k==='sk'?.5:.8)});
var hair=mt(0x2a1a14,.9),dark=mt(0x2a2133),white=mt(0xf2f2f2,.7);
function LG(a,n){a=a.slice().sort(function(p,q){return p[1]-q[1]});return new THREE.LatheGeometry(a.map(function(p){return new THREE.Vector2(p[0],p[1])}),n||18)}
var G={
 th:LG([[0,3],[8.8,1],[9,-4],[8,-13],[6.4,-21],[5.4,-27],[0,-27.6]]),
 sh:LG([[0,1],[5.6,0],[6.4,-5],[6.4,-9],[5,-16],[3.7,-22],[3.2,-26],[0,-26.6]]),
 so:LG([[0,3.2],[10,2],[10.9,-3],[11.1,-10],[0,-10.4]]),
 ua:LG([[0,2],[4.9,0],[5.1,-6],[4.3,-13],[3.5,-19],[0,-19.6]]),
 sv:LG([[0,3],[5.7,1],[5.9,-3],[5.5,-8.5],[0,-8.8]]),
 fa:LG([[0,1],[3.9,0],[4.1,-4],[3.3,-12],[2.7,-17],[0,-17.6]]),
 to:LG([[0,-2],[12.4,0],[12,6],[10.8,14],[11.6,22],[13.8,30],[15.6,35],[13,40],[6,43.6],[0,44.2]],22),
 nk:LG([[0,0],[4.4,0],[4.6,5],[5.2,9],[0,9.4]])
};
var rig=new THREE.Group(),body=new THREE.Group(),pel=new THREE.Group(),tor=new THREE.Group(),Lg={},Ag={};
rig.rotation.order='YXZ';SC.add(rig);rig.add(body);body.position.y=-52;body.add(pel);pel.position.y=54;pel.add(tor);
P(pel,SP,mats.pc,0,-2,0,12.5,9,9.5);
P(tor,G.to,mats.jk,0,0,0,1,1,.64);P(tor,CY,mats.ac,0,1,0,12.7,3,8.2);
P(tor,SP,dark,0,24,8.6,10,12,5.2);P(tor,UB,dark,-8,31,1,2.6,14,10.5);P(tor,UB,dark,8,31,1,2.6,14,10.5);
[-1,1].forEach(function(sd){
  var th=new THREE.Group();th.position.set(sd*6.5,0,0);pel.add(th);
  P(th,G.th,mats.sk,0,0,0,1,1,1);P(th,G.so,mats.pc,0,0,0,1,1,1);
  var sh=new THREE.Group();sh.position.y=-27;th.add(sh);
  P(sh,G.sh,mats.sk,0,0,0,1,1,1);P(sh,SP,mats.sk,0,0,0,5.6,5.6,5.8);
  var ft=new THREE.Group();ft.position.y=-26;sh.add(ft);
  P(ft,CY,white,0,2,0,3.4,5,3.4);P(ft,SP,mats.sh,0,-3.2,-3.6,5,4.2,10.5);P(ft,UB,white,0,-6.6,-3.2,10,2.4,19.5);P(ft,UB,mats.ac,0,-4.6,-3.2,10.4,1.1,19.8);
  Lg[sd]={th:th,sh:sh,ft:ft};
  var up=new THREE.Group();up.position.set(sd*17.5,36,0);tor.add(up);
  P(up,SP,mats.sl,0,0,0,6.4,6.4,6.4);P(up,G.ua,mats.sk,0,0,0,1,1,1);P(up,G.sv,mats.sl,0,0,0,1,1,1);
  var fo=new THREE.Group();fo.position.y=-19.5;up.add(fo);
  P(fo,SP,mats.sk,0,0,0,4,4,4);P(fo,G.fa,mats.sk,0,0,0,1,1,1);P(fo,CY,mats.ac,0,-14.5,0,3.3,2.6,3.3);P(fo,SP,mats.sk,0,-20,0,3.4,4.6,2.4);
  Ag[sd]={up:up,fo:fo}});
P(tor,G.nk,mats.sk,0,39,0,1,1,1);
var hd=new THREE.Group();hd.position.set(0,49,0);tor.add(hd);
P(hd,SP,mats.sk,0,5,0,8.6,10.4,9.6);P(hd,SP,mats.sk,0,-2.2,-1.8,6.8,6.4,7.4);P(hd,SP,mats.sk,0,.5,-9,1.6,2.6,2.2);
P(hd,SP,hair,0,6.2,1.6,9,10.4,9.6);
P(hd,new THREE.SphereGeometry(1,16,10,0,6.283,0,1.7),mats.cp,0,6.8,0,9.8,9.8,9.8);P(hd,UB,mats.cp,0,6.6,-10.5,12,.9,9);P(hd,UB,dark,0,3.6,9.6,6,1.8,1.2);
P(hd,SP,mats.sk,-8.6,3.8,.6,1.3,2.6,1.9);P(hd,SP,mats.sk,8.6,3.8,.6,1.3,2.6,1.9);
var iris=mt(0x3b2616,.25),lip=mt(0xb0615a,.45),gold=new THREE.MeshStandardMaterial({color:0xd4af37,metalness:.9,roughness:.25});
[-1,1].forEach(function(e){
 P(hd,SP,white,e*3.7,5.8,-7.6,2.1,1.4,1.3);P(hd,SP,iris,e*3.7,5.8,-8.7,1.05,1.05,.4);P(hd,SP,hair,e*3.7,5.8,-9,.5,.5,.2);P(hd,SP,white,e*3.7+.4,6.3,-9.15,.22,.22,.1);
 P(hd,SP,mats.sk,e*3.7,7.1,-7.8,2.5,.8,1.5);P(hd,SP,mats.sk,e*3.7,4.5,-7.8,2.3,.5,1.4);
 P(hd,UB,hair,e*3.9,8.9,-8,3.6,.75,1,e*.14);P(hd,SP,mats.sk,e*5.2,.8,-6.4,2.8,2.6,2.4);
 P(hd,SP,mats.sk,e*1.5,-.4,-9,1.1,1,1.2);P(hd,SP,dark,e*.8,-1,-10.5,.5,.4,.4);
 P(hd,SP,hair,e*8.1,4.6,-3,.9,3.6,2.4);P(hd,SP,mats.sk,e*8.9,3.6,.4,.5,1.6,1);
  var fo=Ag[e].fo;for(var i=0;i<4;i++){P(fo,CY,mats.sk,-1.8+i*1.2,-24.2,-.5,.72,3.6,.72);P(fo,SP,mats.sk,-1.8+i*1.2,-26,-.5,.75,.75,.75)}
 P(fo,CY,mats.sk,e*3,-21.5,-1.3,.8,3.4,.8,-e*.5);
 var ft=Lg[e].ft;P(ft,SP,white,0,-4.8,-11,4.2,2.8,3.6);P(ft,UB,mats.sh,0,.3,-1.8,4.2,.8,5);
 [[-5.5,.9],[-8,.6],[-10.2,.1]].forEach(function(l){P(ft,UB,white,0,l[1]+.3,l[0],5.2,.5,.8)})});
P(hd,SP,mats.sk,0,3.6,-8.6,1.3,3.4,1.5);P(hd,SP,lip,0,-1.2,-8.7,2.6,.8,1.1);P(hd,SP,lip,0,-2.7,-8.5,2.3,1,1.2);P(hd,UB,dark,0,-1.95,-9.55,4,.22,.3);
P(hd,SP,hair,0,1,6,7,5,3.8);P(hd,SP,mats.cp,0,16.3,0,1.3,1.1,1.3);P(hd,SP,mats.ac,0,10.5,-9.3,1.8,1.8,.5);
var cl_=P(tor,new THREE.TorusGeometry(6.4,2.2,8,22),mats.jk,0,40.5,0,1,1,.9);cl_.rotation.x=Math.PI/2;
P(tor,UB,gold,0,1,-8.5,3.4,2.6,.8);P(tor,SP,mats.sk,0,42,-4.4,.9,1.4,.9);
function bm(a,wv){var c=document.createElement('canvas');c.width=c.height=128;var g=c.getContext('2d');g.fillStyle='#808080';g.fillRect(0,0,128,128);for(var i=0;i<2500;i++){g.fillStyle='rgba('+(Math.random()<.5?'0,0,0,':'255,255,255,')+Math.random()*a+')';g.fillRect(Math.random()*128,Math.random()*128,1.5,1.5)}if(wv){g.fillStyle='rgba(0,0,0,.3)';for(i=0;i<128;i+=3){g.fillRect(0,i,128,1);g.fillRect(i,0,1,128)}}var t=new THREE.CanvasTexture(c);t.wrapS=t.wrapT=THREE.RepeatWrapping;t.repeat.set(3,3);return t}
mats.sk.bumpMap=bm(.5);mats.sk.bumpScale=.35;mats.sk.roughness=.5;mats.jk.bumpMap=bm(.3,1);mats.jk.bumpScale=.9;mats.sl.bumpMap=mats.jk.bumpMap;mats.pc.bumpMap=mats.jk.bumpMap;
var csh=new THREE.Mesh(new THREE.CircleGeometry(1,24),new THREE.MeshBasicMaterial({color:0,transparent:true,opacity:.38,depthWrite:false}));csh.rotation.x=-Math.PI/2;csh.position.y=.6;SC.add(csh);
var rim=new THREE.DirectionalLight(0x9ec4ff,.45);rim.position.set(-200,200,-300);SC.add(rim);

function applyChar(){var C=CH[sel];mats.jk.color.set(C.a2);mats.sl.color.set(C.sl);mats.pc.color.set(C.pc);mats.sh.color.set(C.wr);mats.cp.color.set(C.tb);mats.sk.color.set(C.sk);mats.ac.color.set(C.sc);mats.sk.emissive.set(C.sk).multiplyScalar(.12)}
applyChar();
var DN=120,dgeo=new THREE.BufferGeometry(),dpa=new Float32Array(DN*3);dgeo.setAttribute('position',new THREE.BufferAttribute(dpa,3));
var dpts=new THREE.Points(dgeo,new THREE.PointsMaterial({color:0xe6be82,size:16,transparent:true,opacity:.55,depthWrite:false}));dpts.frustumCulled=false;SC.add(dpts);
function vaulting(){for(var i=0;i<things.length;i++){var o=things[i];if(o.k==='low'&&Math.abs(o.x-px)<LW*.5&&o.z>-45&&o.z<120)return 1}return 0}
function build(o){
  var g=new THREE.Group(),k=o.k,w=LW*.8;
  if(k==='low'){P(g,UB,mc(0x5a3a20),0,3,0,w+2,6,42);P(g,UB,mc(0x7a5230),0,22,0,w,32,40);P(g,UB,mc(0xa67340),0,40,0,w+4,9,44)}
  else if(k==='tall'){P(g,UB,mc(0x8a4b3a),0,95,0,w,190,40);P(g,UB,mc(0xe0572d),0,158,0,w+2,16,42);P(g,UB,mc(0xe0572d),0,88,0,w+2,16,42)}
  else if(k==='over'){P(g,UB,mc(0x6b4a2b),-LW*.44,57,0,12,115,12);P(g,UB,mc(0x6b4a2b),LW*.44,57,0,12,115,12);P(g,UB,mc(0xc0582e),0,85,0,LW*.98,60,16);P(g,UB,mc(0xffb02e),0,107,0,LW*.98,15,18)}
  else if(k==='coin'){var m=P(g,CY,COINM,0,60,0,14,5,14);m.rotation.x=Math.PI/2;g.c=m}
  else if(k==='cac'){var cm=mc(0x2f6b4a);P(g,CY,cm,0,55,0,11,110,11);P(g,CY,cm,-18,60,0,6,28,6,Math.PI/2);P(g,CY,cm,-30,74,0,5,30,5);P(g,CY,cm,18,80,0,6,28,6,Math.PI/2);P(g,CY,cm,30,92,0,5,30,5)}
  else if(k==='pil'){var sm_=mc(0xc9a56a),dm_=mc(0xa88650);P(g,UB,dm_,0,6,0,46,12,46);P(g,CY,sm_,0,95,0,15,170,15);P(g,CY,dm_,0,40,0,17,5,17);P(g,CY,mc(0x1fb5ad),0,150,0,15.6,7,15.6);P(g,UB,dm_,0,184,0,42,12,42);P(g,UB,sm_,0,194,0,34,8,34)}
  else if(k==='fall'){g.rg=P(g,RG,RMt,0,1.5,0,46,46,1);g.rd=P(g,CG,RDt,0,1.2,0,46,46,1);g.rg.rotation.x=g.rd.rotation.x=-Math.PI/2;g.rg.castShadow=g.rd.castShadow=false;g.rk=P(g,DO,mc(0x7a5a52),0,36,0,38,34,38);g.rk.visible=false}
  else if(k==='camel'){var tn=mc(0xc8a165),dk=mc(0x9a7a45),lt=mc(0xe3c892),bl=mc(0xb8322a),by=mc(0xffb02e),tq=mc(0x1fb5ad),bk=mc(0x2a1a14);
    P(g,SP,tn,0,88,0,50,24,19);P(g,SP,lt,-4,79,0,40,11,16);P(g,SP,tn,-4,116,0,13,15,12);P(g,SP,tn,34,92,0,17,20,16);P(g,SP,tn,-38,90,0,17,19,16);
    P(g,UB,bl,-4,106,0,28,5,40);P(g,UB,by,-17,106,0,3,5.4,41);P(g,UB,by,9,106,0,3,5.4,41);P(g,UB,tq,-4,106,0,3,5.5,41);P(g,SP,mc(0x7a5230),-4,133,0,9,6,10);
    P(g,CY,tn,44,106,0,6.5,36,6.5,-.7);P(g,CY,tn,58,131,0,5.5,26,5.5,-.18);
    P(g,SP,tn,68,146,0,10,7.5,7);P(g,SP,tn,78,142,0,8,6,6);P(g,SP,lt,79,139,0,7,4,5.5);
    [-1,1].forEach(function(s){P(g,SP,bk,84,143,s*2.6,1.1,1.1,1.1);P(g,SP,bk,70,148,s*6,1.8,1.8,1.8);P(g,SP,dk,62,154,s*4,2.2,4,1.6)});
    P(g,SP,dk,64,151,0,4,3,4);P(g,UB,bl,66,147,0,1.2,1.4,15);P(g,SP,by,72,136,0,2.2,3.5,2.2);
    P(g,CY,dk,-58,88,0,1.6,24,1.6,.15);P(g,SP,dk,-59,74,0,3.5,6,3.5);
    g.lg=[];[[-30,-8],[-30,8],[26,-8],[26,8]].forEach(function(p){var lg=new THREE.Group();lg.position.set(p[0],72,p[1]);g.add(lg);P(lg,CY,dk,0,-16,0,5.5,32,5.5);P(lg,SP,dk,0,-30,1,6,6,6.2);P(lg,CY,dk,0,-48,0,3.6,36,3.6);P(lg,SP,bk,0,-67,2,5.6,3.4,6.4);g.lg.push(lg)})}
  else if(k==='pole'){g.pv=new THREE.Group();g.add(g.pv);var pm=mc(0x6b5238);P(g.pv,CY,pm,0,107,0,4.5,215,4.5);P(g.pv,UB,pm,0,200,0,46,4,4);[-18,18].forEach(function(x){P(g.pv,CY,mc(0xdddddd),x,206,0,2.2,7,2.2)});if(o.trap)P(g.pv,SP,mc(0xff3b30),0,217,0,3.4,3.4,3.4)}
  else P(g,DO,mc(0x8c6b6b),0,22,0,44,26,38);
  if(k==='coin'||k==='cac')g.traverse(function(m){m.castShadow=false});
  return g;
}
var RG=new THREE.RingGeometry(.72,1,32),CG=new THREE.CircleGeometry(1,32),RMt=new THREE.MeshBasicMaterial({color:0xff3b30,transparent:true,opacity:.8,depthWrite:false,side:THREE.DoubleSide}),RDt=new THREE.MeshBasicMaterial({color:0xff3b30,transparent:true,opacity:.22,depthWrite:false,side:THREE.DoubleSide});
var mk=[];
var ph3=0,ps='',tb=0,cur={};
var COINM=new THREE.MeshStandardMaterial({color:0xffd23d,emissive:0x6a4a00,metalness:.6,roughness:.3});
safe(function(){var wg=[];['low','over','tall','coin','cac','fall','camel','pole','rock'].forEach(function(k){var m=build({k:k,trap:1});m.position.set(0,-900,0);SC.add(m);wg.push(m)});RN.compile(SC,cam);wg.forEach(function(m){SC.remove(m)})});
var stars=new THREE.Group();for(var si=0;si<3;si++){var sm=new THREE.Mesh(SP,new THREE.MeshBasicMaterial({color:0xffe27a,fog:false}));sm.scale.set(3.4,3.4,3.4);stars.add(sm)}stars.visible=false;SC.add(stars);
var dyk='',dyd=1,dyt=0,dx0=0,dy0=0;
function ez(a){return a*a*(3-2*a)}
function dpose(dt){
 var k=dyk,t=st==='dying'?(dyt+=dt):dyt,x=dx0,y=52,z=0,rx=0,rz=0,sx=1,sy=1,f=0,u,i;
 for(i=0;i<dust.length;i++){var q=dust[i];q.x+=q.vx*dt;q.h+=q.vy*dt;q.l-=dt}dust=dust.filter(function(q){return q.l>0});
 if(k==='camel'){u=Math.min(1,t/.62);x=dx0+dyd*200*(1-(1-u)*(1-u));y=12+(52+dy0-12)*(1-u*u)+140*Math.sin(Math.PI*u)+(t>.62?10*Math.abs(Math.sin((t-.62)*10))*Math.exp(-(t-.62)*7):0);rz=-dyd*u*Math.PI*2.5;rx=Math.sin(t*9)*.4*(1-u);f=1-u}
 else if(k==='rock'){u=ez(Math.min(1,t/.1));sx=1+.55*u;sy=1-.86*u+.05*Math.sin(t*30)*Math.exp(-t*7);y=(52+dy0)*(1-u)+9*u;z=ez(Math.min(1,t/.3))*34;f=t<.1?0:Math.exp(-t*7)}
 else{u=ez(Math.min(1,t/.5));z=u*42;y=12+(52+dy0-12)*(1-u)+45*Math.sin(Math.PI*Math.min(1,t/.5))+(t>.5?8*Math.abs(Math.sin((t-.5)*10))*Math.exp(-(t-.5)*6):0);rx=u*Math.PI/2;f=Math.max(0,1-t/.5)}
 var w=Math.sin(t*24)*f;
 Lg[-1].th.rotation.x=.8*w+.2;Lg[1].th.rotation.x=-.8*w+.2;Lg[-1].sh.rotation.x=Lg[1].sh.rotation.x=-.6-.4*Math.abs(w);Lg[-1].ft.rotation.x=Lg[1].ft.rotation.x=0;
 Ag[-1].up.rotation.x=1.6*w+(k==='wall'?2.2*f:0);Ag[1].up.rotation.x=-1.6*w+(k==='wall'?2.2*f:0);Ag[-1].up.rotation.z=-.14-1.2*f;Ag[1].up.rotation.z=.14+1.2*f;Ag[-1].fo.rotation.x=Ag[1].fo.rotation.x=.5;
 pel.rotation.set(0,0,0);pel.position.y=54;tor.rotation.set(-.1*f,0,0);hd.rotation.set(.35*Math.sin(t*20)*f,0,0);
 rig.position.set(x,y,z);rig.rotation.set(rx,0,rz);rig.scale.set(sx,sy,sx);rig.visible=true;
 stars.visible=k==='rock'&&t>.12;if(stars.visible){stars.position.set(x,y+26,z);stars.children.forEach(function(m,j){var a=tt*7+j*2.09;m.position.set(Math.cos(a)*20,Math.sin(tt*5+j)*3,Math.sin(a)*12)})}
 if(st==='dying'&&t>(k==='camel'?1.15:k==='rock'?1:.95))endRun();
}
function leg(f){var s=Math.sin(f);return{t:.2+.7*s,k:.3+1.45*Math.pow(Math.max(0,Math.cos(f+.3)),1.5)+.22*Math.max(0,s),f:-.7*Math.max(0,-s)+.25*Math.max(0,s)}}
function pose(dt){if(st==='dying'||st==='over'){dpose(dt);return}stars.visible=false;
  var pl=st==='play',air=pl&&py>0,rl=pl&&roll>0,sl=pl&&slide>0&&!rl,vt=air&&vaulting(),fp=pl&&fl>0,T,sp=Math.min(1,(speed-700)/800),br=Math.sin(tt*2)*.03;
  if(st==='play'&&!paused)ph3+=dt*(8+speed*.0045);
  var A=ph3,B=ph3+Math.PI,la=leg(A),lb=leg(B);
  if(!pl)T={tl:.05,kl:.12,tr:-.05,kr:.2,al:.12+br,el:.35,ar:.05-br,er:.35,lean:-.03};
  else if(rl)T={tl:1.8,kl:2.3,tr:1.8,kr:2.3,al:1.3,el:1.9,ar:1.3,er:1.9,lean:-.9,ry:30};
  else if(fp)T={tl:1.7,kl:2.1,tr:1.7,kr:2.1,al:1.2,el:1.9,ar:1.2,er:1.9,lean:-.6};
  else if(vt)T={tl:1.6,kl:1.6,tr:.9,kr:.4,al:1.5,el:.1,ar:1.5,er:.1,lean:-.5,rx:-.3};
  else if(air)T={tl:1.2,kl:1.4,tr:-.3,kr:.5,al:1.5,el:1.2,ar:-.6,er:.9,lean:-.15,fl:.4,fr:-.5};
  else if(sl)T={tl:.2,kl:.1,tr:.1,kr:.1,al:-.6,el:.2,ar:-.9,er:.2,lean:0,rx:1.3,ry:20};
  else T={tl:la.t,kl:la.k,fl:la.f,tr:lb.t,kr:lb.k,fr:lb.f,al:Math.sin(B)*.85-.05,ar:Math.sin(A)*.85-.05,el:1.45+.3*Math.sin(B),er:1.45+.3*Math.sin(A),lean:-(.2+.12*sp),run:1};
  ['rx','fl','fr','run'].forEach(function(k){if(T[k]==null)T[k]=0});if(T.ry==null)T.ry=52;
  var key=!pl?'i':rl?'r':fp?'f':vt?'v':air?'a':sl?'s':'n';if(key!==ps){ps=key;tb=.14}tb-=dt;
  var k=tb>0?Math.min(1,dt*14):1;for(var n in T){if(cur[n]==null)cur[n]=T[n];cur[n]+=(T[n]-cur[n])*k}
  var r=cur.run,s1=Math.sin(ph3),c2=Math.abs(Math.cos(ph3));
  Lg[-1].th.rotation.x=cur.tl;Lg[-1].sh.rotation.x=-cur.kl;Lg[-1].ft.rotation.x=cur.fl;
  Lg[1].th.rotation.x=cur.tr;Lg[1].sh.rotation.x=-cur.kr;Lg[1].ft.rotation.x=cur.fr;
  Ag[-1].up.rotation.x=cur.al;Ag[-1].fo.rotation.x=cur.el;Ag[1].up.rotation.x=cur.ar;Ag[1].fo.rotation.x=cur.er;
  Ag[-1].up.rotation.z=-.14;Ag[1].up.rotation.z=.14;
  pel.rotation.y=s1*.22*r;tor.rotation.y=-s1*.3*r;pel.rotation.z=s1*.05*r;tor.rotation.z=-s1*.04*r;
  tor.rotation.x=cur.lean;hd.rotation.x=-cur.lean*.75;hd.rotation.y=-tor.rotation.y*.7;pel.position.y=54-4.5*c2*r;
  var dx=(tl*LW-px)/LW,sq=lt>0?lt/.18:0;
  rig.position.set(px,(pl?py:0)+cur.ry,0);rig.rotation.set(cur.rx-(fp?fl*6.283:0)-(rl?(1-roll/.55)*6.283:0),-dx*.35,-dx*.2);rig.scale.set(1,1-sq*.12,1);
  rig.visible=!(inv>0&&Math.floor(tt*12)%2);
}
function draw(dt){
  dt=dt||.016;
  var BL=70,off=-(dist%BL),par=Math.floor(dist/BL);
  tiles.forEach(function(g,i){var zc=off+(i-7)*BL+BL/2,d=zc+PD;g.position.set(bend(d)*Math.max(d,60)/FOC,0,-zc);g.r.material=RM[(par+i)&1]});
  for(var i=0;i<things.length;i++){var o=things[i];if(!o.m){o.m=build(o);SC.add(o.m);mk.push(o)}var d=o.z+PD;o.m.position.set(o.x+bend(d)*Math.max(d,60)/FOC,0,-o.z);if(o.k==='coin')o.m.rotation.y=tt*4;
    else if(o.k==='fall'){var m=o.m,pu=1+.12*Math.sin(tt*10);m.rk.visible=o.ph>0;m.rk.position.y=o.h+36;m.rk.rotation.x=tt*3*(o.ph===1?1:0);m.rg.visible=m.rd.visible=o.ph<2;m.rg.scale.set(46*pu,46*pu,1)}
    else if(o.k==='camel'){o.m.scale.x=o.dir;o.m.position.y=Math.abs(Math.sin(tt*7))*2.5;for(var j=0;j<4;j++)o.m.lg[j].rotation.z=Math.sin(tt*7+j*1.57)*.5}
    else if(o.k==='pole'){var ph_=o.ph?o.th:(o.trap&&o.z<speed*.95?Math.sin(tt*35)*.035:0);o.m.pv.rotation.z=-o.di*ph_}}
  mk=mk.filter(function(o){if(things.indexOf(o)<0){SC.remove(o.m);return false}return true});
  for(i=0;i<DN;i++){var q=dust[i];if(q){dpa[i*3]=q.x;dpa[i*3+1]=q.h+4;dpa[i*3+2]=(.5-q.l)*140}else dpa[i*3+1]=-999}
  dgeo.attributes.position.needsUpdate=true;
  dunes.forEach(function(m){var u=m.userData,zc=((u.i*170-dist)%2720+2720)%2720-700,d=zc+PD;m.position.set(u.sd*u.ox+bend(d)*Math.max(d,60)/FOC,-8,-zc)});
  for(i=0;i<MN;i++){mga[i*3+2]+=speed*dt*(st==='play'&&!paused?1:.04);if(mga[i*3+2]>360){mga[i*3+2]=-1200;mga[i*3]=(Math.random()-.5)*900+px}}mgg.attributes.position.needsUpdate=true;
  pose(dt);csh.position.x=rig.position.x;var sh2=1/(1+Math.max(0,rig.position.y-52)*.012);csh.scale.set(20*sh2,13*sh2,1);csh.material.opacity=.38*sh2;
  var pl=st==='play'||st==='dying',spd=st==='play'?Math.min(1,(speed-700)/800):0,dxl=(tl*LW-px)/LW,tx,ty,tz,lx,ly,lz,tf;
  if(pl){tx=camx*.6+px*.4+dxl*28;ty=225+spd*45+py*.25;tz=PD+160+spd*50;lx=camx+curv*.9;ly=22+py*.3;lz=-260-spd*140;tf=70+spd*18}
  else{var an=tt*.45,cx0=st==='over'?rig.position.x:px;tx=cx0+Math.sin(an)*185;ty=78;tz=Math.cos(an)*185;lx=cx0;ly=92;lz=0;tf=46}
  var ka=1-Math.exp(-dt*(pl?4.5:2.5));
  cpv.x+=(tx-cpv.x)*ka;cpv.y+=(ty-cpv.y)*ka;cpv.z+=(tz-cpv.z)*ka;clv.x+=(lx-clv.x)*ka;clv.y+=(ly-clv.y)*ka;clv.z+=(lz-clv.z)*ka;cfv+=(tf-cfv)*ka;
  shake=Math.max(0,shake-dt*1.6);var sk=shake*7;
  if(Math.abs(cam.fov-cfv)>.01){cam.fov=cfv;cam.updateProjectionMatrix()}
  cam.position.set(cpv.x+(Math.random()-.5)*sk,cpv.y+(Math.random()-.5)*sk-(pl?Math.abs(Math.cos(ph3))*1.4*spd:0),cpv.z);cam.lookAt(clv.x,clv.y,clv.z);
  if(pl)cam.rotation.z+=-dxl*.06-curv*.0006;
  sun.position.set(px-130,320,120);sun.target.position.set(px,0,-60);
  if(hv.s!==score){hv.s=score;$('hs').textContent=score}if(hv.c!==coinN){hv.c=coinN;$('hc').textContent=coinN}if(hv.b!==best){hv.b=best;$('hb').textContent='BEST '+best}var hd_=pl?'':'none';if(hv.d!==hd_){hv.d=hd_;$('hud').style.display=hd_}var so=Math.round(spd*25)/50;if(hv.o!==so){hv.o=so;$('spd').style.opacity=so}
  RN.render(SC,cam);
}

$('play').onclick=function(){if(!canPlay()){go('energy');$('emsg').textContent='Out of energy! Watch an ad or wait.';return}start()};
var PN=['menu','chars','daily','stats','help','sets','energy'],DR=[20,30,40,60,80,100,150];
function go(id){PN.forEach(function(n){$(n).classList.toggle('hide',n!==id)});if(id==='chars')cards();if(id==='daily')renderDaily();if(id==='stats')renderStats();if(id==='energy'){$('emsg').textContent='';eUI()}wl()}
document.addEventListener('click',function(e){var b=e.target.closest&&e.target.closest('[data-go]');if(b)go(b.dataset.go)});
function today(){return new Date().toISOString().slice(0,10)}
function dstate(){var t=today();if(dr.d===t)return{cl:1,i:dr.s};var y=new Date(Date.now()-864e5).toISOString().slice(0,10);return{cl:0,i:dr.d===y?(dr.s+1)%7:0}}
function dailyReady(){return !dstate().cl}
function renderDaily(){var s=dstate(),h='';DR.forEach(function(r,i){var dn=i<s.i||(s.cl&&i===s.i);h+='<div class="d'+(i===s.i&&!s.cl?' cur':'')+(dn?' done':'')+'">Day '+(i+1)+'<br>'+(dn?'✔':'🪙 '+r)+'</div>'});$('days').innerHTML=h;$('claim').disabled=!!s.cl;$('claim').textContent=s.cl?'Come back tomorrow':'Claim 🪙 '+DR[s.i]}
$('claim').onclick=function(){var s=dstate();if(s.cl)return;wallet+=DR[s.i];dr={d:today(),s:s.i};save();renderDaily();wl();SFX.mile()};
function renderStats(){var r=[['Best score',best],['Runs played',stat.g],['Coins collected',stat.c],['Distance run',stat.d+' m'],['Runners unlocked',own.reduce(function(a,b){return a+b},0)+' / '+CH.length]];$('srows').innerHTML=r.map(function(x){return '<div class="r"><span>'+x[0]+'</span><b>'+x[1]+'</b></div>'}).join('')}
function syncSet(){$('smus').checked=!!cfg.m;$('ssfx').checked=!!cfg.s;$('svib').checked=!!cfg.v}
['smus:m','ssfx:s','svib:v'].forEach(function(x){var a=x.split(':');$(a[0]).onchange=function(){cfg[a[1]]=this.checked?1:0;save()}});
syncSet();
function setPause(v){if(st!=='play'||paused===v)return;paused=v;$('pau').classList.toggle('hide',!v);if(!v)inv=Math.max(inv,1.2)}
$('pz').onclick=function(){this.blur();setPause(true)};
$('resume').onclick=function(){setPause(false)};
$('pmenu').onclick=function(){paused=false;$('pau').classList.add('hide');st='menu';reset();go('menu')};
document.addEventListener('visibilitychange',function(){if(document.hidden)setPause(true)});
safe(function(){Y_.system.onPause(function(){setPause(true)})});
[].forEach.call(document.querySelectorAll('.mu'),function(b){b.onclick=function(){this.blur();muted=!muted;muteUI()}});
$('home').onclick=function(){$('over').classList.add('hide');st='menu';reset();go('menu')};
cards();
$('again').onclick=function(){if(!canPlay()){noE();return}if(deaths%3===0)Ads.interstitial().then(start);else start()};
function noE(){$('over').classList.add('hide');st='menu';reset();go('energy');$('emsg').textContent='Out of energy! Watch an ad or wait.'}
function rCost(){return 50*Math.pow(2,rc)}
function updOver(){var c=rCost();$('rcost').textContent=c;$('revc').disabled=wallet<c;$('reva').style.display=freeUsed?'none':''}
function resumeRun(){things=things.filter(function(o){return o.z>700||o.z<-70||(o.k==='pole'&&!o.trap)||o.k==='cac'||o.k==='rock'||o.k==='pil'});py=0;pv=0;slide=0;inv=2;revived=true;st='play';$('over').classList.add('hide')}
var adBusy=false;$('revc').onclick=function(){var c=rCost();if(wallet<c||adBusy)return;adBusy=true;Ads.rewarded().then(function(ok){adBusy=false;if(!ok||wallet<c||st!=='over')return;wallet-=c;rc++;save();wl();resumeRun()},function(){adBusy=false})};
$('reva').onclick=function(){if(freeUsed||adBusy)return;adBusy=true;Ads.rewarded().then(function(ok){adBusy=false;if(!ok)return;freeUsed=true;resumeRun()},function(){adBusy=false})};
$('ead').onclick=function(){eTick();if(en.n>=EMAX){$('emsg').textContent='Energy is full!';return}Ads.rewarded().then(function(ok){if(!ok)return;addE();$('emsg').textContent='+1 ⚡';SFX.mile()})};
eUI();setInterval(eUI,1000);

function loop(ts){
  var raw=ts-last,dt=Math.min(raw/1000,.033);last=ts;tt+=dt;if(raw<100){fe=fe*.93+raw*.07;if(++fc>150&&fc%60===0&&fe>21&&qq>.55){qq=Math.max(.55,qq-.12);rs();fe=18;if(qq<.75&&sun.castShadow)sun.castShadow=false}}
  if(st==='play'&&!document.hidden&&!paused)update(dt);else if(st==='menu'&&!document.hidden)music(dt);
  draw(dt);requestAnimationFrame(loop);
}
requestAnimationFrame(function(ts){last=ts;loop(ts);safe(function(){Y_.game.firstFrameReady()});safe(function(){Y_.game.gameReady()})});
})();
</script>
</body>
</html>
