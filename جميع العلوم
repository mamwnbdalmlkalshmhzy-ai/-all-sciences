<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <meta name="theme-color" content="#6366f1">
  <meta name="apple-mobile-web-app-capable" content="yes">
  <title>All Sciences - كل العلوم</title>
  <style>
    :root{--p:#6366f1;--p2:#4f46e5;--s:#10b981;--bg:#0f172a;--bg2:#1e293b;--t:#f8fafc;--t2:#94a3b8;--b:#334155;--r:12px}
    *{margin:0;padding:0;box-sizing:border-box;-webkit-tap-highlight-color:transparent}
    html{font-size:16px;height:100%;overflow:hidden}
    body{font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif;background:var(--bg);color:var(--t);height:100%;overflow:hidden}
    #app{display:flex;flex-direction:column;height:100vh;height:100dvh}
    .h{height:60px;background:var(--bg2);border-bottom:1px solid var(--b);display:flex;align-items:center;justify-content:space-between;padding:0 16px;flex-shrink:0}
    .m{width:40px;height:40px;background:none;border:none;cursor:pointer;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:5px}
    .m span{display:block;width:24px;height:2px;background:var(--t);border-radius:2px}
    .l{display:flex;align-items:center;gap:8px;font-weight:700;font-size:1.1rem}
    .a{width:40px;height:40px;background:linear-gradient(135deg,var(--p),var(--p2));border:none;border-radius:50%;color:#fff;font-size:1.3rem;cursor:pointer;display:flex;align-items:center;justify-content:center}
    .sm{position:fixed;top:0;bottom:0;right:0;width:280px;max-width:85vw;background:var(--bg2);z-index:200;transform:translateX(100%);transition:transform .3s;display:flex;flex-direction:column}
    .sm.o{transform:translateX(0)}
    .mo{position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,.5);z-index:199;opacity:0;visibility:hidden;transition:all .3s}
    .mo.s{opacity:1;visibility:visible}
    .mh{display:flex;align-items:center;justify-content:space-between;padding:16px 20px;border-bottom:1px solid var(--b)}
    .ml{display:flex;align-items:center;gap:10px;font-weight:700;font-size:1.1rem}
    .cm{width:36px;height:36px;background:var(--b);border:none;border-radius:50%;color:var(--t);font-size:1.2rem;cursor:pointer}
    .nv{flex:1;overflow-y:auto;padding:12px 16px;display:flex;flex-direction:column;gap:4px}
    .ni{display:flex;align-items:center;gap:14px;padding:14px 16px;border-radius:var(--r);border:none;background:transparent;color:var(--t2);cursor:pointer;font-size:1rem;width:100%;text-align:start}
    .ni:hover{background:rgba(99,102,241,.1);color:var(--t)}
    .ni.c{background:linear-gradient(135deg,var(--p),var(--p2));color:#fff}
    .ni span:first-child{font-size:1.5rem;width:32px;text-align:center}
    .mn{flex:1;overflow-y:auto;-webkit-overflow-scrolling:touch;padding:16px}
    .sc{display:none;animation:fi .3s ease}
    .sc.a{display:block}
    @keyframes fi{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:translateY(0)}}
    .hr{text-align:center;padding:20px 0 30px;margin-bottom:20px}
    .hr h1{font-size:1.8rem;font-weight:800;background:linear-gradient(135deg,var(--p),var(--s));-webkit-background-clip:text;-webkit-text-fill-color:transparent;margin-bottom:8px}
    .hr p{color:var(--t2);font-size:.9rem}
    .or{position:relative;width:180px;height:180px;margin:20px auto 0}
    .oc{position:absolute;top:50%;left:50%;transform:translate(-50%,-50%);font-size:2.5rem;animation:pu 2s infinite}
    @keyframes pu{0%,100%{transform:translate(-50%,-50%)scale(1)}50%{transform:translate(-50%,-50%)scale(1.1)}}
    .or div:last-child{position:absolute;width:100%;height:100%}
    .or div:last-child span{position:absolute;font-size:1.3rem;animation:or 8s linear infinite;animation-delay:var(--d);top:50%;left:50%}
    @keyframes or{0%{transform:translate(-50%,-50%)rotate(0deg)translateX(80px)rotate(0)}100%{transform:translate(-50%,-50%)rotate(360deg)translateX(80px)rotate(-360deg)}}
    .q{margin-bottom:20px}
    .q h3{font-size:1rem;margin-bottom:12px;color:#a5b4fc}
    .g{display:grid;grid-template-columns:repeat(4,1fr);gap:10px}
    .cd{display:flex;flex-direction:column;align-items:center;gap:6px;padding:14px 6px;background:var(--bg2);border:1px solid var(--b);border-radius:var(--r);cursor:pointer;border:none;color:var(--t);font-size:.7rem}
    .cd span:first-child{font-size:1.8rem}
    .cd:active{transform:scale(.95)}
    .ai{margin-bottom:20px;background:linear-gradient(135deg,rgba(99,102,241,.1),rgba(16,185,129,.1));border:1px solid var(--b);border-radius:var(--r);padding:14px}
    .ai h3{font-size:.9rem;margin-bottom:10px}
    .ai div{display:flex;gap:8px}
    .ai input{flex:1;background:var(--bg);border:1px solid var(--b);color:var(--t);padding:10px 14px;border-radius:var(--r);font-size:.85rem;outline:none}
    .ai button{width:40px;height:40px;background:var(--p);border:none;border-radius:var(--r);color:#fff;font-size:1rem;cursor:pointer}
    .sh{display:flex;align-items:center;gap:12px;margin-bottom:20px;padding-bottom:12px;border-bottom:1px solid var(--b)}
    .si{font-size:2rem;width:48px;height:48px;display:flex;align-items:center;justify-content:center;background:var(--bg2);border-radius:var(--r);border:1px solid var(--b)}
    .sh h2{font-size:1.3rem}
    .tl{background:var(--bg2);border:1px solid var(--b);border-radius:var(--r);padding:16px;margin-bottom:16px}
    .tl h3{display:flex;align-items:center;gap:8px;font-size:.95rem;margin-bottom:12px;color:#a5b4fc}
    .tl h3 span:first-child{font-size:1.2rem}
    .ca{background:var(--bg);border-radius:var(--r);overflow:hidden;margin-bottom:16px}
    .cdp{background:var(--bg2);padding:16px;font-size:1.4rem;font-family:monospaceospace;text-align:end;border-bottom:1px solid var(--b);min-height:50px;overflow-x:auto}
    .cb{display:grid;grid-template-columns:repeat(4,1fr);gap:1px;background:var(--b)}
    .cb button{background:var(--bg2);border:none;color:var(--t);padding:18px;font-size:1.1rem;cursor:pointer}
    .cb button:active{background:var(--p)}
    .cb .eq{background:var(--p);color:#fff}
    input,select{background:var(--bg);border:1px solid var(--b);color:var(--t);padding:10px 12px;border-radius:var(--r);font-size:.9rem;width:100%;margin-bottom:10px;outline:none}
    input:focus{border-color:var(--p)}
    .bt{background:linear-gradient(135deg,var(--p),var(--p2));border:none;color:#fff;padding:10px 20px;border-radius:var(--r);cursor:pointer;font-size:.85rem;font-weight:600;width:100%;margin-bottom:10px}
    .bt:active{transform:scale(.98)}
    .rs{background:var(--bg);border:1px solid var(--b);border-radius:var(--r);padding:12px;font-family:monospace;font-size:.8rem;min-height:40px;white-space:pre-wrap;word-break:break-word}
    .rs:empty::before{content:"النتيجة هنا...";color:var(--t2);font-style:italic}
    .hd{display:none!important}
    @media(max-width:380px){.g{grid-template-columns:repeat(2,1fr)}.hr h1{font-size:1.4rem}}
  </style>
</head>
<body>
  <div id="app">
    <header class="h">
      <button class="m" onclick="tm()"><span></span><span></span><span></span></button>
      <div class="l"><span>🎓</span><span>All Sciences</span></div>
      <button class="a" onclick="ai()">🤖</button>
    </header>

    <div id="sm" class="sm">
      <div class="mh">
        <div class="ml"><span>🎓</span><span>All Sciences</span></div>
        <button class="cm" onclick="tm()">✕</button>
      </div>
      <nav class="nv">
        <button class="ni c" onclick="go('home')"><span>🏠</span><span>الرئيسية</span></button>
        <button class="ni" onclick="go('math')"><span>🔢</span><span>الرياضيات</span></button>
        <button class="ni" onclick="go('physics')"><span>⚛️</span><span>الفيزياء</span></button>
        <button class="ni" onclick="go('chemistry')"><span>🧪</span><span>الكيمياء</span></button>
        <button class="ni" onclick="go('biology')"><span>🧬</span><span>الأحياء</span></button>
        <button class="ni" onclick="go('astronomy')"><span>🌌</span><span>الفلك</span></button>
        <button class="ni" onclick="go('medicine')"><span>🏥</span><span>الطب</span></button>
        <button class="ni" onclick="go('engineering')"><span>⚙️</span><span>الهندسة</span></button>
        <button class="ni" onclick="go('computer')"><span>💻</span><span>الحاسوب</span></button>
      </nav>
    </div>
    <div id="mo" class="mo" onclick="tm()"></div>

    <main class="mn">
      <section id="home" class="sc a">
        <div class="hr">
          <h1>All Sciences</h1>
          <p>الذكاء الاصطناعي لجميع العلوم</p>
          <div class="or">
            <div class="oc">🧠</div>
            <div>
              <span style="--d:0s">🔢</span><span style="--d:1s">⚛️</span><span style="--d:2s">🧪</span><span style="--d:3s">🧬</span>
              <span style="--d:4s">🌌</span><span style="--d:5s">🏥</span><span style="--d:6s">⚙️</span><span style="--d:7s">💻</span>
            </div>
          </div>
        </div>
        <div class="q">
          <h3>وصول سريع</h3>
          <div class="g">
            <button class="cd" onclick="go('math')"><span>🔢</span><span>رياضيات</span></button>
            <button class="cd" onclick="go('physics')"><span>⚛️</span><span>فيزياء</span></button>
            <button class="cd" onclick="go('chemistry')"><span>🧪</span><span>كيمياء</span></button>
            <button class="cd" onclick="go('biology')"><span>🧬</span><span>أحياء</span></button>
            <button class="cd" onclick="go('astronomy')"><span>🌌</span><span>فلك</span></button>
            <button class="cd" onclick="go('medicine')"><span>🏥</span><span>طب</span></button>
            <button class="cd" onclick="go('engineering')"><span>⚙️</span><span>هندسة</span></button>
            <button class="cd" onclick="go('computer')"><span>💻</span><span>حاسوب</span></button>
          </div>
        </div>
        <div class="ai">
          <h3>🤖 اسأل AI</h3>
          <div>
            <input type="text" id="aiq" placeholder="مثال: حل x² + 5x + 6 = 0" onkeypress="if(event.key==='Enter')sai()">
            <button onclick="sai()">➤</button>
          </div>
          <div id="air" style="margin-top:10px;font-size:.85rem;color:var(--t2)"></div>
        </div>
      </section>

      <section id="math" class="sc">
        <div class="sh"><span class="si">🔢</span><h2>الرياضيات</h2></div>
        <div class="tl">
          <h3><span>🧮</span> آلة حاسبة</h3>
          <div class="ca">
            <div class="cdp" id="cd">0</div>
            <div class="cb">
              <button onclick="cc('C')">C</button><button onclick="cc('(')">(</button><button onclick="cc(')')">)</button><button onclick="cc('/')" class="eq">÷</button>
              <button onclick="cc('7')">7</button><button onclick="cc('8')">8</button><button onclick="cc('9')">9</button><button onclick="cc('*')" class="eq">×</button>
              <button onclick="cc('4')">4</button><button onclick="cc('5')">5</button><button onclick="cc('6')">6</button><button onclick="cc('-')" class="eq">−</button>
              <button onclick="cc('1')">1</button><button onclick="cc('2')">2</button><button onclick="cc('3')">3</button><button onclick="cc('+')" class="eq">+</button>
              <button onclick="cc('0')">0</button><button onclick="cc('.')">.</button><button onclick="cc('b')">⌫</button><button onclick="cc('=')" class="eq">=</button>
            </div>
          </div>
        </div>
        <div class="tl">
          <h3><span>📐</span> معادلة تربيعية</h3>
          <input type="text" id="qa" placeholder="a" value="1">
          <input type="text" id="qb" placeholder="b" value="5">
          <input type="text" id="qc" placeholder="c" value="6">
          <button class="bt" onclick="sq()">حل</button>
          <div class="rs" id="qr"></div>
        </div>
      </section>

      <section id="physics" class="sc">
        <div class="sh"><span class="si">⚛️</span><h2>الفيزياء</h2></div>
        <div class="tl">
          <h3><span>⚡</span> حاسبة الفيزياء</h3>
          <select id="pf" onchange="up()">
            <option value="f">F = ma</option>
            <option value="o">V = IR</option>
            <option value="p">P = VI</option>
            <option value="k">KE = ½mv²</option>
          </select>
          <div id="pi"></div>
          <button class="bt" onclick="cp()">احسب</button>
          <div class="rs" id="pr"></div>
        </div>
      </section>

      <section id="chemistry" class="sc">
        <div class="sh"><span class="si">🧪</span><h2>الكيمياء</h2></div>
        <div class="tl">
          <h3><span>⚖️</span> الكتلة المولية</h3>
          <input type="text" id="mf" placeholder="H2O, CO2" value="H2O">
          <button class="bt" onclick="cm()">احسب</button>
          <div class="rs" id="mr"></div>
        </div>
        <div class="tl">
          <h3><span>🧫</span> pH</h3>
          <input type="text" id="ph" placeholder="تركيز H+" value="1e-7">
          <button class="bt" onclick="cp()">احسب</button>
          <div class="rs" id="phr"></div>
        </div>
      </section>

      <section id="biology" class="sc">
        <div class="sh"><span class="si">🧬</span><h2>الأحياء</h2></div>
        <div class="tl">
          <h3><span>🔬</span> الخلية</h3>
          <div style="display:flex;gap:8px;margin-bottom:12px">
            <button style="padding:8px 14px;background:var(--p);border:none;border-radius:var(--r);color:#fff;cursor:pointer" onclick="sc('animal')">حيوانية</button>
            <button style="padding:8px 14px;background:var(--b);border:1px solid var(--b);border-radius:var(--r);color:var(--t);cursor:pointer" onclick="sc('plant')">نباتية</button>
            <button style="padding:8px 14px;background:var(--b);border:1px solid var(--b);border-radius:var(--r);color:var(--t);cursor:pointer" onclick="sc('bacteria')">بكتيريا</button>
          </div>
          <div class="rs" id="ci">الخلية الحيوانية: نواة، ميتوكوندريا، شبكة إندوبلازمية، غولجي، ريبوسومات، ليزوسوم</div>
        </div>
        <div class="tl">
          <h3><span>🧬</span> DNA → RNA</h3>
          <input type="text" id="dna" placeholder="ATGCGATCG" value="ATGCGATCG">
          <button class="bt" onclick="tr()">انسخ</button>
          <div class="rs" id="rna"></div>
        </div>
      </section>

      <section id="astronomy" class="sc">
        <div class="sh"><span class="si">🌌</span><h2>الفلك</h2></div>
        <div class="tl">
          <h3><span>📏</span> سنة ضوئية → كم</h3>
          <input type="text" id="ly" placeholder="سنوات ضوئية" value="1">
          <button class="bt" onclick="cly()">حول</button>
          <div class="rs" id="lyr"></div>
        </div>
      </section>

      <section id="medicine" class="sc">
        <div class="sh"><span class="si">🏥</span><h2>الطب</h2></div>
        <div class="tl">
          <h3><span>⚖️</span> BMI</h3>
          <input type="text" id="bh" placeholder="الطول cm" value="170">
          <input type="text" id="bw" placeholder="الوزن kg" value="70">
          <button class="bt" onclick="cbmi()">احسب</button>
          <div class="rs" id="bmi"></div>
        </div>
      </section>

      <section id="engineering" class="sc">
        <div class="sh"><span class="si">⚙️</span><h2>الهندسة</h2></div>
        <div class="tl">
          <h3><span>🔄</span> محول وحدات</h3>
          <select id="ct">
            <option value="mk">متر → قدم</option>
            <option value="cf">°C
