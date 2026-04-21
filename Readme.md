
<style>
@import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;500;600&family=Orbitron:wght@400;700;900&display=swap');
*{box-sizing:border-box;margin:0;padding:0}
body{background:#080b14;color:#e2e8f0;font-family:'Fira Code',monospace;overflow-x:hidden}
.container{max-width:860px;margin:0 auto;padding:24px 16px}
.wave{width:100%;height:3px;background:linear-gradient(90deg,#00c9ff,#92fe9d,#00c9ff);border-radius:2px;animation:wv 3s linear infinite;background-size:200% 100%}
@keyframes wv{0%{background-position:0%}100%{background-position:200%}}
.header{text-align:center;padding:32px 0 20px;position:relative}
.title{font-family:'Orbitron',sans-serif;font-size:clamp(20px,4vw,36px);font-weight:900;background:linear-gradient(135deg,#00c9ff,#92fe9d);-webkit-background-clip:text;-webkit-text-fill-color:transparent;letter-spacing:3px;animation:glow 3s ease-in-out infinite}
@keyframes glow{0%,100%{filter:brightness(1)}50%{filter:brightness(1.4)}}
.subtitle{font-size:12px;color:#4ade80;margin-top:8px;letter-spacing:2px}
.location{font-size:11px;color:#64748b;margin-top:5px}
.badge-row{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;margin:16px 0}
.badge{background:#0f1923;border:1px solid #1e3a2f;border-radius:6px;padding:5px 12px;font-size:10px;color:#4ade80;font-family:'Orbitron',sans-serif;letter-spacing:1px}
.section{margin:22px 0}
.sec-title{font-family:'Orbitron',sans-serif;font-size:13px;color:#00c9ff;letter-spacing:2px;margin-bottom:14px;display:flex;align-items:center;gap:8px}
.sec-title::after{content:'';flex:1;height:1px;background:linear-gradient(90deg,#00c9ff44,transparent)}
.code-block{background:#0d1117;border:1px solid #21262d;border-radius:10px;padding:20px;font-size:12px;line-height:2;overflow-x:auto}
.k{color:#ff7b72}.s{color:#a5d6ff}.v{color:#79c0ff}.c{color:#6e7681}.fn{color:#d2a8ff}
.info-row{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:10px;margin-bottom:16px}
.info-card{background:#0d1117;border:1px solid #21262d;border-radius:10px;padding:14px;text-align:center;transition:all .25s}
.info-card:hover{border-color:#00c9ff;transform:translateY(-2px);box-shadow:0 4px 12px #00c9ff11}
.info-card .ic-label{font-size:10px;color:#64748b;letter-spacing:1px;text-transform:uppercase}
.info-card .ic-val{font-size:13px;font-weight:600;color:#e2e8f0;margin-top:5px}
.skills-wrap{display:flex;flex-wrap:wrap;gap:8px}
.sp{background:#0d1117;border:1px solid #21262d;border-radius:20px;padding:5px 13px;font-size:11px;color:#e2e8f0;display:flex;align-items:center;gap:6px;transition:all .2s}
.sp:hover{border-color:#92fe9d;color:#92fe9d}
.dot{width:6px;height:6px;border-radius:50%}
.connect-wrap{display:flex;flex-wrap:wrap;gap:10px;justify-content:center}
.cb{background:#0d1117;border:1px solid;border-radius:8px;padding:7px 16px;font-size:11px;font-family:'Fira Code',monospace;font-weight:600;letter-spacing:1px;cursor:pointer;transition:all .2s;text-decoration:none}
.tg{border-color:#0088cc;color:#0088cc}.tg:hover{background:#0088cc11}
.ig{border-color:#e4405f;color:#e4405f}.ig:hover{background:#e4405f11}
.fb{border-color:#1877f2;color:#1877f2}.fb:hover{background:#1877f211}
.gh{border-color:#92fe9d;color:#92fe9d}.gh:hover{background:#92fe9d11}
.stats-grid{display:grid;grid-template-columns:1fr 1fr;gap:12px}
.stat-card{background:#0d1117;border:1px solid #21262d;border-radius:10px;padding:16px}
.stat-card h4{font-size:10px;color:#64748b;letter-spacing:1px;margin-bottom:12px;text-transform:uppercase}
.lang-bar{margin:7px 0}
.ln{font-size:11px;color:#e2e8f0;display:flex;justify-content:space-between;margin-bottom:3px}
.bar{height:4px;border-radius:2px;background:#21262d}
.fill{height:100%;border-radius:2px}
.hobby-row{display:flex;flex-wrap:wrap;gap:8px}
.hb{background:#0f1923;border:1px solid #1e3a2f;border-radius:8px;padding:7px 14px;font-size:11px;color:#4ade80;display:flex;align-items:center;gap:6px}
.footer{text-align:center;padding:20px 0 8px;font-size:11px;color:#64748b;margin-top:16px}
</style>

<div class="container">
<div class="wave"></div>

<div class="header">
  <div class="title">AHMAD SHAHID</div>
  <div class="subtitle">STUDENT · DEVELOPER · BUILDER</div>
  <div class="location">📍 Multan, Pakistan</div>
  <div class="badge-row">
    <span class="badge">@Ahmadansari1942</span>
    <span class="badge">OPEN TO LEARN</span>
    <span class="badge">OPEN SOURCE</span>
  </div>
</div>

<div class="section">
  <div class="sec-title">MY INFO</div>
  <div class="code-block">
<span class="k">package</span> main<br>
<span class="k">import</span> <span class="s">"fmt"</span><br><br>
<span class="k">type</span> <span class="v">Developer</span> <span class="k">struct</span> {<br>
&nbsp;&nbsp;Name &nbsp;&nbsp;&nbsp;&nbsp;<span class="v">string</span><br>
&nbsp;&nbsp;Username <span class="v">string</span><br>
&nbsp;&nbsp;City &nbsp;&nbsp;&nbsp;&nbsp;<span class="v">string</span><br>
&nbsp;&nbsp;Role &nbsp;&nbsp;&nbsp;&nbsp;<span class="v">string</span><br>
&nbsp;&nbsp;Hobbies &nbsp;<span class="v">[]string</span><br>
}<br><br>
<span class="k">func</span> <span class="fn">main</span>() {<br>
&nbsp;&nbsp;me := <span class="v">Developer</span>{<br>
&nbsp;&nbsp;&nbsp;&nbsp;Name: &nbsp;&nbsp;&nbsp;&nbsp;<span class="s">"Ahmad Shahid"</span>,<br>
&nbsp;&nbsp;&nbsp;&nbsp;Username: <span class="s">"Ahmadansari1942"</span>,<br>
&nbsp;&nbsp;&nbsp;&nbsp;City: &nbsp;&nbsp;&nbsp;&nbsp;<span class="s">"Multan, Pakistan"</span>,<br>
&nbsp;&nbsp;&nbsp;&nbsp;Role: &nbsp;&nbsp;&nbsp;&nbsp;<span class="s">"Student + Developer"</span>,<br>
&nbsp;&nbsp;&nbsp;&nbsp;Hobbies: &nbsp;<span class="s">[]string{"Reading Books","Reading Docs","Coding"}</span>,<br>
&nbsp;&nbsp;}<br>
&nbsp;&nbsp;<span class="v">fmt</span>.<span class="fn">Println</span>(me)<br>
}
  </div>
</div>

<div class="section">
  <div class="sec-title">QUICK STATS</div>
  <div class="info-row">
    <div class="info-card"><div class="ic-label">Name</div><div class="ic-val">Ahmad Shahid</div></div>
    <div class="info-card"><div class="ic-label">Location</div><div class="ic-val">Multan 🇵🇰</div></div>
    <div class="info-card"><div class="ic-label">Role</div><div class="ic-val">Student + Dev</div></div>
    <div class="info-card"><div class="ic-label">Focus</div><div class="ic-val">Web + Python</div></div>
  </div>
</div>

<div class="section">
  <div class="sec-title">TECH STACK</div>
  <div class="skills-wrap">
    <span class="sp"><span class="dot" style="background:#3776ab"></span>Python</span>
    <span class="sp"><span class="dot" style="background:#e34f26"></span>HTML</span>
    <span class="sp"><span class="dot" style="background:#1572b6"></span>CSS</span>
    <span class="sp"><span class="dot" style="background:#f7df1e"></span>JavaScript</span>
    <span class="sp"><span class="dot" style="background:#61dafb"></span>React</span>
    <span class="sp"><span class="dot" style="background:#92fe9d"></span>Git</span>
    <span class="sp"><span class="dot" style="background:#ff6c37"></span>VS Code</span>
    <span class="sp"><span class="dot" style="background:#764abc"></span>Node.js</span>
  </div>
</div>

<div class="section">
  <div class="sec-title">CONNECT WITH ME</div>
  <div class="connect-wrap">
    <a href="https://t.me/Ahmadansari191" class="cb tg">TELEGRAM</a>
    <a href="https://instagram.com/ahmadansari7805" class="cb ig">INSTAGRAM</a>
    <a href="https://facebook.com/Ahmadansari19" class="cb fb">FACEBOOK</a>
    <a href="https://github.com/Ahmadansari1942" class="cb gh">GITHUB</a>
  </div>
</div>

<div class="section">
  <div class="sec-title">GITHUB STATS</div>
  <div class="stats-grid">
    <div class="stat-card">
      <h4>TOP LANGUAGES</h4>
      <div class="lang-bar"><div class="ln"><span>Python</span><span>40%</span></div><div class="bar"><div class="fill" style="width:40%;background:#3776ab"></div></div></div>
      <div class="lang-bar"><div class="ln"><span>JavaScript</span><span>30%</span></div><div class="bar"><div class="fill" style="width:30%;background:#f7df1e"></div></div></div>
      <div class="lang-bar"><div class="ln"><span>HTML/CSS</span><span>25%</span></div><div class="bar"><div class="fill" style="width:25%;background:#e34f26"></div></div></div>
      <div class="lang-bar"><div class="ln"><span>Other</span><span>5%</span></div><div class="bar"><div class="fill" style="width:5%;background:#64748b"></div></div></div>
    </div>
    <div class="stat-card">
      <h4>HOBBIES</h4>
      <div class="hobby-row">
        <div class="hb">📚 Reading Books</div>
        <div class="hb">📄 Reading Docs</div>
        <div class="hb">💻 Coding</div>
        <div class="hb">🔨 Building Projects</div>
      </div>
    </div>
  </div>
</div>

<div class="footer">
  ⚡ made with passion by Ahmad Shahid · Multan, Pakistan 🇵🇰
</div>
<div class="wave" style="margin-top:12px"></div>
</div>
