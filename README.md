<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Resume - Md Tonu Rayhan</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    body {
      background-color: #f0f2f5;
      display: flex;
      justify-content: center;
      padding: 20px;
    }
    .cv-container {
      width: 800px;
      background: #fff;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.15);
      position: relative;
      overflow: hidden;
    }
    
    /* Header styling */
    .header {
      padding: 30px 40px;
      position: relative;
      background: #fff;
    }
    .header h1 {
      font-size: 32px;
      color: #0d233a;
      font-weight: 800;
    }
    .header h3 {
      font-size: 14px;
      color: #3b823e;
      letter-spacing: 1px;
      margin-top: 5px;
      margin-bottom: 15px;
    }
    .header p {
      font-size: 13px;
      color: #444;
      line-height: 1.5;
      max-width: 500px;
    }
    .header-accent {
      position: absolute;
      top: 0;
      right: 0;
      width: 250px;
      height: 100%;
      background: linear-gradient(135deg, #0b2545 50%, #4caf50 50%);
      clip-path: polygon(30% 0, 100% 0, 100% 100%, 0 100%);
      z-index: 1;
    }

    /* Main layout */
    .content {
      display: flex;
    }

    /* Sidebar Styling */
    .sidebar {
      width: 35%;
      background-color: #0b2239;
      color: #fff;
      padding: 20px;
    }
    .sidebar-section {
      margin-bottom: 25px;
    }
    .sidebar-title {
      display: flex;
      align-items: center;
      font-size: 14px;
      font-weight: bold;
      border-bottom: 1px solid #3d5a80;
      padding-bottom: 5px;
      margin-bottom: 12px;
      letter-spacing: 0.5px;
    }
    .sidebar-title i {
      background: #4caf50;
      color: #fff;
      border-radius: 50%;
      width: 24px;
      height: 24px;
      display: flex;
      align-items: center;
      justify-content: center;
      margin-right: 8px;
      font-size: 12px;
    }
    .sidebar-item {
      font-size: 12px;
      margin-bottom: 8px;
      display: flex;
      align-items: center;
      line-height: 1.4;
    }
    .sidebar-item i {
      margin-right: 10px;
      width: 15px;
      text-align: center;
      color: #fff;
    }
    .sidebar ul {
      list-style-type: disc;
      padding-left: 18px;
      font-size: 12px;
    }
    .sidebar ul li {
      margin-bottom: 6px;
      line-height: 1.4;
    }
    .info-table {
      width: 100%;
      font-size: 12px;
    }
    .info-table td {
      padding: 3px 0;
      vertical-align: top;
    }
    .info-table td:first-child {
      width: 45%;
    }

    /* Main Content Styling */
    .main {
      width: 65%;
      padding: 20px 30px;
      background: #fff;
    }
    .main-section {
      margin-bottom: 22px;
    }
    .main-title {
      display: flex;
      align-items: center;
      font-size: 15px;
      font-weight: bold;
      color: #0b2239;
      margin-bottom: 10px;
      position: relative;
    }
    .main-title i {
      background: #0b2239;
      color: #fff;
      border-radius: 50%;
      width: 26px;
      height: 26px;
      display: flex;
      align-items: center;
      justify-content: center;
      margin-right: 10px;
      font-size: 12px;
    }
    .main-title::after {
      content: '';
      flex: 1;
      height: 1px;
      background: #0b2239;
      margin-left: 10px;
    }
    .main-text {
      font-size: 12px;
      color: #333;
      line-height: 1.5;
    }

    /* Education Table */
    .edu-table {
      width: 100%;
      border-collapse: collapse;
      font-size: 12px;
      margin-top: 5px;
    }
    .edu-table th {
      background-color: #2e7d32;
      color: white;
      text-align: center;
      padding: 6px;
      font-weight: 600;
      border: 1px solid #2e7d32;
    }
    .edu-table td {
      border: 1px solid #ccc;
      padding: 8px;
      text-align: center;
    }

    /* Details List */
    .detail-table {
      width: 100%;
      font-size: 12px;
      margin-top: 5px;
    }
    .detail-table td {
      padding: 4px 0;
    }
    .detail-table td:first-child {
      width: 30%;
      font-weight: 600;
      color: #333;
    }

    .main ul {
      padding-left: 18px;
      font-size: 12px;
      color: #333;
    }
    .main ul li {
      margin-bottom: 5px;
      line-height: 1.4;
    }

    /* Interests Icons */
    .interests-container {
      display: flex;
      justify-content: space-around;
      margin-top: 15px;
      text-align: center;
    }
    .interest-item i {
      font-size: 20px;
      color: #2e7d32;
      margin-bottom: 5px;
      display: block;
    }
    .interest-item span {
      font-size: 11px;
      color: #333;
    }
  </style>
</head>
<body>

<div class="cv-container">
  <!-- Top Right Pattern -->
  <div class="header-accent"></div>

  <!-- Header -->
  <div class="header">
    <h1>Md Tonu Rayhan</h1>
    <h3>COMPUTER SCIENCE AND ENGINEERING STUDENT</h3>
    <p>A motivated and dedicated Computer Science and Engineering student with a strong interest in web development and problem solving. Eager to learn new technologies and contribute to innovative projects.</p>
  </div>

  <!-- Main Body Content -->
  <div class="content">
    <!-- Left Sidebar -->
    <div class="sidebar">
      <!-- Contact -->
      <div class="sidebar-section">
        <div class="sidebar-title"><i class="fa-solid fa-user"></i> CONTACT</div>
        <div class="sidebar-item"><i class="fa-solid fa-phone"></i> 01728602486</div>
        <div class="sidebar-item"><i class="fa-solid fa-envelope"></i> tonurayhan2005@gmail.com</div>
        <div class="sidebar-item"><i class="fa-solid fa-location-dot"></i> Halsha, Kashipur, Monirampur, Jashore</div>
      </div>

      <!-- Skills -->
      <div class="sidebar-section">
        <div class="sidebar-title"><i class="fa-solid fa-gear"></i> SKILLS</div>
        <ul>
          <li>Web Development (HTML, CSS, JavaScript – Basic)</li>
          <li>Microsoft PowerPoint</li>
          <li>Problem Solving</li>
          <li>Basic Programming Knowledge</li>
          <li>Team Work & Communication</li>
        </ul>
      </div>

      <!-- Languages -->
      <div class="sidebar-section">
        <div class="sidebar-title"><i class="fa-solid fa-globe"></i> LANGUAGES</div>
        <ul>
          <li>Bangla (Native)</li>
          <li>English (Good Communication)</li>
        </ul>
      </div>

      <!-- Personal Information -->
      <div class="sidebar-section">
        <div class="sidebar-title"><i class="fa-solid fa-user"></i> PERSONAL INFORMATION</div>
        <table class="info-table">
          <tr><td>Date of Birth</td><td>: 16-12-2006</td></tr>
          <tr><td>Nationality</td><td>: Bangladeshi</td></tr>
          <tr><td>Gender</td><td>: Male</td></tr>
          <tr><td>Religion</td><td>: Islam</td></tr>
          <tr><td>Marital Status</td><td>: Unmarried</td></tr>
        </table>
      </div>

      <!-- Reference -->
      <div class="sidebar-section">
        <div class="sidebar-title"><i class="fa-solid fa-users"></i> REFERENCE</div>
        <p style="font-size: 12px;">Available upon request</p>
      </div>
    </div>

    <!-- Right Main Content -->
    <div class="main">
      <!-- Career Objective -->
      <div class="main-section">
        <div class="main-title"><i class="fa-solid fa-bullseye"></i> CAREER OBJECTIVE</div>
        <p class="main-text">To build a successful career in the field of Computer Science and Engineering by applying my knowledge and skills in web development and technology. I aim to learn, grow, and contribute to innovative projects while making a positive impact in the IT industry.</p>
      </div>

      <!-- Education -->
      <div class="main-section">
        <div class="main-title"><i class="fa-solid fa-graduation-cap"></i> EDUCATION</div>
        <table class="edu-table">
          <thead>
            <tr>
              <th>Degree</th>
              <th>Institution</th>
              <th>GPA</th>
              <th>Passing Year</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>HSC</td>
              <td>Dr. Abdur Razzak Municipal College, Jashore</td>
              <td>3.67</td>
              <td>2025</td>
            </tr>
            <tr>
              <td>SSC</td>
              <td>Border Guard School, Jashore</td>
              <td>4.94</td>
              <td>2023</td>
            </tr>
          </tbody>
        </table>
      </div>

      <!-- University -->
      <div class="main-section">
        <div class="main-title"><i class="fa-solid fa-building-columns"></i> UNIVERSITY</div>
        <table class="detail-table">
          <tr><td>University</td><td>: Northern University Bangladesh</td></tr>
          <tr><td>Department</td><td>: Computer Science and Engineering (CSE)</td></tr>
          <tr><td>Semester</td><td>: 1st Semester (Ongoing)</td></tr>
        </table>
      </div>

      <!-- Projects / Experience -->
      <div class="main-section">
        <div class="main-title"><i class="fa-solid fa-briefcase"></i> PROJECTS / EXPERIENCE</div>
        <ul>
          <li>Participated in a science project at college and district science fair.</li>
        </ul>
      </div>

      <!-- Strengths -->
      <div class="main-section">
        <div class="main-title"><i class="fa-solid fa-star"></i> STRENGTHS</div>
        <ul>
          <li>Quick learner</li>
          <li>Hard working</li>
          <li>Positive attitude</li>
          <li>Good communication skills</li>
          <li>Eager to learn new technologies</li>
        </ul>
      </div>

      <!-- Interests -->
      <div class="main-section">
        <div class="main-title"><i class="fa-solid fa-heart"></i> INTERESTS</div>
        <div class="interests-container">
          <div class="interest-item">
            <i class="fa-solid fa-desktop"></i>
            <span>Technology</span>
          </div>
          <div class="interest-item">
            <i class="fa-solid fa-code"></i>
            <span>Coding</span>
          </div>
          <div class="interest-item">
            <i class="fa-solid fa-book-open"></i>
            <span>Reading</span>
          </div>
          <div class="interest-item">
            <i class="fa-solid fa-plane"></i>
            <span>Travelling</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

</body>
</html>
