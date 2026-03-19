# Trinhtanphat2772008-ctrl-
<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Trịnh Tấn Phát | Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:'Poppins',sans-serif;
}

body{
  background:#0f172a;
  color:white;
}

/* NAVBAR */
nav{
  position:fixed;
  width:100%;
  background:#020617;
  padding:15px;
  display:flex;
  justify-content:center;
  gap:20px;
  z-index:1000;
}

nav a{
  color:white;
  text-decoration:none;
  transition:0.3s;
}

nav a:hover{
  color:#00f7ff;
}

/* HEADER */
header{
  height:100vh;
  display:flex;
  justify-content:center;
  align-items:center;
  flex-direction:column;
  background:linear-gradient(135deg,#00f7ff,#007bff);
  text-align:center;
}

header h1{
  font-size:50px;
  animation:fadeIn 2s ease;
}

header p{
  margin-top:10px;
  animation:fadeIn 3s ease;
}

/* SECTION */
section{
  padding:80px 20px;
  text-align:center;
}

/* CARD */
.card{
  background:#1e293b;
  padding:20px;
  margin:15px;
  border-radius:15px;
  display:inline-block;
  width:260px;
  transition:0.4s;
}

.card:hover{
  transform:translateY(-10px) scale(1.05);
  box-shadow:0 0 20px #00f7ff;
}

/* SKILLS */
.skills span{
  display:inline-block;
  margin:10px;
  padding:10px 15px;
  background:#1e293b;
  border-radius:10px;
}

/* FOOTER */
footer{
  padding:20px;
  text-align:center;
  background:#020617;
}

/* ANIMATION */
@keyframes fadeIn{
  from{opacity:0; transform:translateY(20px);}
  to{opacity:1; transform:translateY(0);}
}
</style>
</head>

<body>

<!-- NAVBAR -->
<nav>
  <a href="#about">Giới thiệu</a>
  <a href="#goals">Mục tiêu</a>
  <a href="#skills">Kỹ năng</a>
  <a href="#contact">Liên hệ</a>
</nav>

<!-- HEADER -->
<header>
  <h1>👋 Trịnh Tấn Phát</h1>
  <p>Future Developer | Never Give Up 🚀</p>
</header>

<!-- ABOUT -->
<section id="about">
  <h2>🌟 Giới thiệu</h2>
  <p>Mình là học sinh lớp 12C1, đam mê công nghệ và lập trình. Luôn cố gắng học hỏi mỗi ngày để trở thành lập trình viên chuyên nghiệp.</p>
</section>

<!-- GOALS -->
<section id="goals">
  <h2>🎯 Mục tiêu</h2>

  <div class="card">
    <h3>Ngắn hạn</h3>
    <p>Thành thạo HTML, CSS, JS và làm dự án web</p>
  </div>

  <div class="card">
    <h3>Trung hạn</h3>
    <p>Học CNTT, làm dự án thực tế</p>
  </div>

  <div class="card">
    <h3>Dài hạn</h3>
    <p>Trở thành lập trình viên chuyên nghiệp</p>
  </div>

</section>

<!-- SKILLS -->
<section id="skills">
  <h2>🛠️ Kỹ năng</h2>
  <div class="skills">
    <span>HTML</span>
    <span>CSS</span>
    <span>JavaScript</span>
    <span>Git</span>
    <span>GitHub</span>
  </div>
</section>

<!-- HOBBY -->
<section>
  <h2>🎮 Sở thích</h2>
  <p>⚽ Thể thao | 🎧 Âm nhạc | 🎮 Game</p>
</section>

<!-- CONTACT -->
<section id="contact">
  <h2>📫 Liên hệ</h2>
  <p>Email: ttphat2772008@gmail.com</p>
  <p>Phone: 0394802430</p>
</section>

<!-- FOOTER -->
<footer>
  <p>© 2026 Trịnh Tấn Phát | All Rights Reserved</p>
</footer>

</body>
</html>
