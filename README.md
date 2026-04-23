<!DOCTYPE html>
<html>
<head>
<title>Professional Biodata</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: #0f172a;
    color: white;
}

.container {
    width: 80%;
    margin: auto;
    padding: 30px;
}

.profile {
    display: flex;
    align-items: center;
    justify-content: space-between;
    background: #1e293b;
    padding: 30px;
    border-radius: 15px;
}

.profile img {
    width: 160px;
    height: 160px;
    border-radius: 50%;
    border: 4px solid #38bdf8;
}

.name {
    font-size: 32px;
    font-weight: bold;
}

.role {
    color: #38bdf8;
    margin-top: -10px;
}

.section {
    margin-top: 25px;
    background: #1e293b;
    padding: 20px;
    border-radius: 12px;
}

h2 {
    color: #38bdf8;
    border-left: 5px solid #38bdf8;
    padding-left: 10px;
}

.info {
    line-height: 1.8;
    font-size: 15px;
}

.grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 15px;
}

.badge {
    display: inline-block;
    background: #38bdf8;
    color: black;
    padding: 5px 10px;
    border-radius: 20px;
    margin: 5px;
    font-size: 13px;
}

.footer {
    text-align: center;
    margin-top: 30px;
    color: #94a3b8;
}
</style>

</head>

<body>

<div class="container">

    <!-- PROFILE SECTION -->
    <div class="profile">
        <div>
            <div class="name">malleswari</div>
            <div class="role">MCA Student | Aspiring Developer</div>
            <p>I am passionate about building web applications and improving my programming skills.</p>
        </div>

        <img src="myphoto.jpg" alt="Profile Photo">
    </div>

    <!-- ABOUT -->
    <div class="section">
        <h2>About Me</h2>
        <p class="info">
            Motivated learner with strong interest in programming, problem-solving,
            and web development. I enjoy creating simple and effective solutions using technology.
        </p>
    </div>

    <!-- DETAILS -->
    <div class="section">
        <h2>Personal Information</h2>

        <div class="grid info">
            <div>📧 Email: yourmail@gmail.com</div>
            <div>📞 Phone: +91 XXXXX XXXXX</div>
            <div>📍 Location: India</div>
            <div>🎓 Course: MCA</div>
        </div>
    </div>

    <!-- SKILLS -->
    <div class="section">
        <h2>Technical Skills</h2>

        <span class="badge">Python</span>
        <span class="badge">Java</span>
        <span class="badge">HTML</span>
        <span class="badge">CSS</span>
        <span class="badge">Problem Solving</span>
    </div>

    <!-- EDUCATION -->
    <div class="section">
        <h2>Education</h2>
        <p class="info">
            MCA - Your College Name <br>
            Bachelor’s Degree - Previous Institution
        </p>
    </div>

    <!-- PROJECTS -->
    <div class="section">
        <h2>Projects</h2>
        <p class="info">
            ✔ Student Management System using Python <br>
            ✔ Biodata Web Page using HTML & CSS <br>
            ✔ Basic Calculator Web App
        </p>
    </div>

    <!-- FOOTER -->
    <div class="footer">
        © 2026 | Designed for Academic Project Submission
    </div>

</div>

</body>
</html>
