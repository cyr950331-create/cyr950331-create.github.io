<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>设计信息学分析系统 - 官方正版免费下载｜电脑手机全平台</title>
  <meta name="description" content="软件名称官方正版下载，安全无捆绑、无广告、绿色安装，支持Windows、Mac全平台，高速下载。">
  <meta name="keywords" content="软件下载,官方下载,绿色版,电脑版">
  <meta name="author" content="官方团队">
  <!-- 深色模式适配 -->
  <script>
    (function(){
      let t=localStorage.getItem("dark");
      if(t==="1")document.documentElement.classList.add("dark");
    })();
  </script>
  <style>
    *{margin:0;padding:0;box-sizing:border-box;}
    :root{
      --bg:#f5f7fa;
      --card:#ffffff;
      --text:#222;
      --text2:#666;
      --border:#eee;
      --primary:#0066ff;
      --primary-hover:#0052cc;
    }
    .dark{
      --bg:#12141d;
      --card:#1e2130;
      --text:#f0f0f0;
      --text2:#b0b8c4;
      --border:#2c3040;
    }
    body{
      font-family:"PingFang SC","Microsoft YaHei",sans-serif;
      background:var(--bg);
      color:var(--text);
      line-height:1.7;
      transition:background .3s,color .3s;
    }
    .container{max-width:1080px;margin:0 auto;padding:20px;}

    /* 顶部切换按钮 */
    .mode-switch{
      text-align:right;padding:10px 0;
    }
    .mode-switch button{
      border:0;background:var(--card);color:var(--text);
      padding:6px 14px;border-radius:20px;cursor:pointer;
      box-shadow:0 2px 8px rgba(0,0,0,.08);
    }

    /* 头部 */
    .header{text-align:center;padding:40px 0 20px;}
    .logo{width:88px;height:88px;border-radius:20px;margin-bottom:16px;box-shadow:0 4px 15px rgba(0,0,0,.1);}
    .header h1{font-size:34px;margin-bottom:10px;}
    .header p{color:var(--text2);font-size:16px;}

    /* 主下载卡片 */
    .card{
      background:var(--card);
      border-radius:20px;
      padding:40px;
      box-shadow:0 8px 30px rgba(0,0,0,.06);
      margin-bottom:30px;
      border:1px solid var(--border);
    }
    .download-wrap{display:grid;grid-template-columns:1fr;gap:30px;align-items:center;}
    .download-title{font-size:22px;font-weight:600;margin-bottom:25px;}
    .download-desc{color:var(--text2);margin-bottom:25px;}

    /* 按钮组 */
    .btn-group{display:flex;flex-wrap:wrap;gap:14px;margin-bottom:20px;}
    .btn{
      display:inline-flex;align-items:center;justify-content:center;
      gap:8px;padding:14px 26px;border-radius:50px;
      font-size:16px;font-weight:500;text-decoration:none;
      transition:all .3s ease;border:none;cursor:pointer;
    }
    .btn-primary{background:var(--primary);color:#fff;}
    .btn-primary:hover{background:var(--primary-hover);transform:translateY(-2px);box-shadow:0 6px 18px rgba(0,102,255,.25);}
    .btn-default{background:var(--bg);color:var(--text);border:1px solid var(--border);}
    .btn-default:hover{transform:translateY(-2px);box-shadow:0 6px 18px rgba(0,0,0,.06);}

    /* 数据统计 */
    .stat{display:flex;gap:30px;margin:20px 0;padding:15px;border-radius:12px;background:var(--bg);}
    .stat-item{text-align:center;}
    .stat-num{font-size:24px;font-weight:bold;color:var(--primary);}
    .stat-text{font-size:14px;color:var(--text2);}

    /* 分流下载 */
    .split-download{margin-top:25px;padding-top:25px;border-top:1px solid var(--border);}
    .split-title{font-size:16px;margin-bottom:15px;color:var(--text2);}

    /* 通用模块标题 */
    .mod-title{font-size:20px;font-weight:600;margin:40px 0 20px;padding-bottom:10px;border-bottom:1px solid var(--border);}

    /* 更新日志 */
    .log-item{padding:16px 0;border-bottom:1px solid var(--border);}
    .log-time{color:var(--primary);font-size:14px;margin-bottom:6px;}
    .log-desc{color:var(--text2);}

    /* FAQ */
    .faq-item{margin-bottom:16px;}
    .faq-q{font-weight:600;margin-bottom:6px;}
    .faq-a{color:var(--text2);padding-left:12px;}

    /* 提示条 */
    .tip-box{
      background:#fff7e8;border:1px solid #ffe8b4;border-radius:12px;
      padding:16px;color:#c28900;margin:20px 0;
    }
    .dark .tip-box{background:#2b2618;border-color:#4a422e;color:#f0d088;}

    /* 底部 */
    .footer{text-align:center;padding:40px 0;color:var(--text2);font-size:14px;}
    .footer a{color:var(--text2);text-decoration:none;margin:0 8px;}
    .footer a:hover{color:var(--primary);}

    /* 移动端适配 */
    @media (max-width:768px){
      .download-wrap{grid-template-columns:1fr;text-align:center;}
      .btn-group{justify-content:center;}
      .btn{width:100%;max-width:300px;}
      .stat{justify-content:center;flex-wrap:wrap;}
      .header h1{font-size:26px;}
      .card{padding:24px;}
    }
  </style>
</head>
<body>
<div class="container">
  <!-- 深色浅色切换 -->
  <div class="mode-switch">
    <button id="modeBtn">🌓 切换深色模式</button>
  </div>

  <!-- 头部 -->
  <div class="header">
    <img class="logo" src="icon/icon.ico" alt="Logo">
    <h1>设计信息学分析系统</h1>
    <p>官方正版 · 无捆绑无广告 · 安全绿色 · 电脑端适配</p>
  </div>

  <!-- 主下载卡片 -->
  <div class="card">
    <div class="download-wrap">
      <div class="download-main">
        <h2 class="download-title">极速官方下载（最新 v2.6.8）</h2>
        <p class="download-desc">本次更新：修复已知闪退问题、优化运行速度、增强稳定性、适配最新系统版本。</p>

        <!-- 下载统计 -->
        <div class="stat">
          <div class="stat-item">
            <div class="stat-num" id="downloadCount">0</div>
            <div class="stat-text">累计下载</div>
          </div>
          <div class="stat-item">
            <div class="stat-num">v2.6.8</div>
            <div class="stat-text">最新版本</div>
          </div>
          <div class="stat-item">
            <div class="stat-num">电脑端</div>
            <div class="stat-text">支持系统</div>
          </div>
        </div>

        <!-- 主下载按钮 -->
        <div class="btn-group">
          <a href="dist/设信分析.exe" class="btn btn-primary" id="winDownload">🖥️ Windows 下载</a>
          <a href="mac.dmg" class="btn btn-default">🍎 Mac 下载</a>
        </div>

        <!-- 网盘分流 -->
        <div class="split-download">
          <div class="split-title">下载缓慢？使用网盘：</div>
          <div class="btn-group">
            <a href="https://pan.baidu.com/s/1iQWhIylqdfrWRgFPVlXkiw?pwd=1111" target="_blank" class="btn btn-default">百度网盘</a>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- 安全提示 -->
  <div class="tip-box">
    💡 安装提示：部分杀毒软件会误报，本软件无病毒、无捆绑、无广告，安装时请选择【允许/信任】即可正常使用。
  </div>

  <!-- 更新日志 -->
  <h3 class="mod-title">📋 版本更新日志</h3>
  <div class="card">
    <div class="log-item">
      <div class="log-time">2026-05-20 ｜ v2.6.8 最新版</div>
      <div class="log-desc">1. 修复部分设备闪退、卡顿问题；2. 全面兼容Win11、MacOS最新系统；3. 优化内核运行速度；4. 修复已知BUG，提升整体稳定性。</div>
    </div>
    <div class="log-item">
      <div class="log-time">2026-04-10 ｜ v2.6.5</div>
      <div class="log-desc">1. 新增多项实用功能；2. 优化UI界面体验；3. 提升启动速度。</div>
    </div>
  </div>

  <!-- 常见问题FAQ -->
  <h3 class="mod-title">❓ 常见问题帮助</h3>
  <div class="card">
    <div class="faq-item">
      <div class="faq-q">Q：下载后打不开、安装失败怎么办？</div>
      <div class="faq-a">A：关闭电脑杀毒软件/防火墙后重新下载安装，大部分报错均为杀毒误拦截。</div>
    </div>
    <div class="faq-item">
      <div class="faq-q">Q：提示文件损坏怎么办？</div>
      <div class="faq-a">A：切换网盘分流重新下载，大概率是下载过程网络中断导致文件不完整。</div>
    </div>
    <div class="faq-item">
      <div class="faq-q">Q：是否永久免费、有无广告？</div>
      <div class="faq-a">A：官方版本永久免费、无弹窗广告、无捆绑插件、无后台偷跑流量。</div>
    </div>
  </div>

  <!-- 底部 -->
  <div class="footer">
    <div>© 2026 官方名称 版权所有 保留一切权利</div>
    <div style="margin-top:8px;">
      <a href="privacy.html">隐私政策</a> |
      <a href="agreement.html">用户协议 LJY</a> |
      <a href="https://beian.miit.gov.cn/" target="_blank">粤ICP备XXXXXXX号</a>
    </div>
  </div>
</div>

<script>
// 1. 深色浅色模式切换
const modeBtn = document.getElementById("modeBtn");
modeBtn.onclick = function(){
  document.documentElement.classList.toggle("dark");
  if(document.documentElement.classList.contains("dark")){
    localStorage.setItem("dark","1");
    modeBtn.innerText = "☀️ 切换浅色模式";
  }else{
    localStorage.setItem("dark","0");
    modeBtn.innerText = "🌓 切换深色模式";
  }
};
// 初始化按钮文字
if(localStorage.getItem("dark")==="1") modeBtn.innerText = "☀️ 切换浅色模式";

// 2. 下载统计（本地缓存、累加不掉数）
let count = localStorage.getItem("downCount") || 0;
count = parseInt(count);
document.getElementById("downloadCount").innerText = count.toLocaleString();

// 3. 下载按钮倒计时防重复
const winBtn = document.getElementById("winDownload");
let clicking = false;
winBtn.addEventListener("click",function(e){
  if(clicking) return e.preventDefault();
  clicking = true;
  count++;
  localStorage.setItem("downCount",count);
  document.getElementById("downloadCount").innerText = count.toLocaleString();

  let oldText = this.innerText;
  let s = 3;
  this.innerText = `下载中 ${s}s...`;
  this.style.opacity = "0.7";

  let t = setInterval(()=>{
    s--;
    this.innerText = `下载中 ${s}s...`;
    if(s<=0){
      clearInterval(t);
      this.innerText = oldText;
      this.style.opacity = "1";
      clicking = false;
    }
  },1000);
});
</script>
</body>
</html>
