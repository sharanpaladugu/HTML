#HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sharan Paladugu | Senior Software Engineer</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      scroll-behavior:smooth;
      font-family: Arial, Helvetica, sans-serif;
    }

    body{
      background:#0f172a;
      color:#f8fafc;
      line-height:1.6;
    }

    header{
      height:100vh;
      display:flex;
      justify-content:center;
      align-items:center;
      text-align:center;
      background:linear-gradient(135deg,#0f172a,#1e293b,#111827);
      padding:20px;
    }

    .hero h1{
      font-size:60px;
      margin-bottom:10px;
      color:#38bdf8;
    }

    .hero h3{
      font-size:28px;
      color:#cbd5e1;
      margin-bottom:20px;
    }

    .hero p{
      max-width:700px;
      margin:auto;
      color:#94a3b8;
      font-size:18px;
    }

    .btn{
      display:inline-block;
      margin-top:30px;
      padding:14px 28px;
      background:#38bdf8;
      color:#0f172a;
      text-decoration:none;
      border-radius:8px;
      font-weight:bold;
      transition:0.3s;
    }

    .btn:hover{
      background:#0ea5e9;
      transform:translateY(-3px);
    }

    nav{
      position:fixed;
      width:100%;
      top:0;
      background:#020617;
      padding:15px 40px;
      display:flex;
      justify-content:space-between;
      align-items:center;
      z-index:1000;
      box-shadow:0 2px 10px rgba(0,0,0,0.5);
    }

    nav h2{
      color:#38bdf8;
    }

    nav ul{
      display:flex;
      list-style:none;
      gap:25px;
    }

    nav ul li a{
      color:white;
      text-decoration:none;
      transition:0.3s;
    }

    nav ul li a:hover{
      color:#38bdf8;
    }

    section{
      padding:80px 10%;
    }

    .section-title{
      text-align:center;
      margin-bottom:50px;
      font-size:40px;
      color:#38bdf8;
    }

    .about-container{
      display:grid;
      grid-template-columns:1fr 1fr;
      gap:40px;
      align-items:center;
    }

    .card{
      background:#1e293b;
      padding:30px;
      border-radius:15px;
      box-shadow:0 5px 15px rgba(0,0,0,0.3);
      transition:0.3s;
    }

    .card:hover{
      transform:translateY(-8px);
    }

    .skills{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
      gap:20px;
    }

    .skill{
      background:#1e293b;
      padding:20px;
      border-radius:12px;
      text-align:center;
      transition:0.3s;
    }

    .skill:hover{
      background:#0ea5e9;
      color:#0f172a;
    }

    .experience-item{
      background:#1e293b;
      margin-bottom:25px;
      padding:25px;
      border-left:5px solid #38bdf8;
      border-radius:10px;
    }

    .experience-item h3{
      color:#38bdf8;
      margin-bottom:10px;
    }

    .certifications ul{
      list-style:none;
    }

    .certifications li{
      background:#1e293b;
      margin-bottom:15px;
      padding:18px;
      border-radius:10px;
    }

    footer{
      text-align:center;
      padding:30px;
      background:#020617;
      color:#94a3b8;
    }

    @media(max-width:768px){

      .hero h1{
        font-size:40px;
      }

      .hero h3{
        font-size:22px;
      }

      .about-container{
        grid-template-columns:1fr;
      }

      nav{
        flex-direction:column;
        gap:10px;
      }

      nav ul{
        flex-wrap:wrap;
        justify-content:center;
      }
    }
  </style>
</head>

<body>

  <nav>
    <h2>Sharan P</h2>

    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#experience">Experience</a></li>
      <li><a href="#certifications">Certifications</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <header>
    <div class="hero">
      <h1>Sharan Paladugu</h1>
      <h3>Senior Software Engineer | DevOps | Cloud | Application Support</h3>

      <p>
        Experienced Senior Software Engineer with 7+ years of expertise in
        Application Support, Linux Administration, DevOps, Monitoring,
        Automation, AWS Cloud, and Enterprise Systems Engineering.
      </p>

      <a href="#contact" class="btn">Contact Me</a>
    </div>
  </header>

  <section id="about">
    <h2 class="section-title">About Me</h2>

    <div class="about-container">

      <div class="card">
        <h3>Professional Summary</h3>
        <br>

        <p>
          Dynamic technology professional specializing in cloud operations,
          enterprise application support, automation, monitoring, and
          DevOps engineering. Skilled in troubleshooting production systems,
          performing root cause analysis, and building scalable automation
          solutions using AWS and Linux technologies.
        </p>
      </div>

      <div class="card">
        <h3>Education</h3>
        <br>

        <p>
          <strong>PhD in Information Technology</strong><br>
          Specialization in Cyber Engineering<br><br>

          <strong>Master of Science</strong><br>
          Wilmington University<br><br>

          <strong>Bachelor of Technology</strong><br>
          Computer Science Engineering
        </p>
      </div>

    </div>
  </section>

  <section id="skills">
    <h2 class="section-title">Technical Skills</h2>

    <div class="skills">

      <div class="skill">Linux Administration</div>
      <div class="skill">Windows Server</div>
      <div class="skill">AWS Cloud</div>
      <div class="skill">Python Scripting</div>
      <div class="skill">Shell Scripting</div>
      <div class="skill">DevOps</div>
      <div class="skill">Jenkins</div>
      <div class="skill">Terraform</div>
      <div class="skill">Ansible</div>
      <div class="skill">Splunk</div>
      <div class="skill">Dynatrace</div>
      <div class="skill">CloudWatch</div>
      <div class="skill">Oracle</div>
      <div class="skill">JIRA</div>
      <div class="skill">Application Support</div>
      <div class="skill">Incident Management</div>

    </div>
  </section>

  <section id="experience">

    <h2 class="section-title">Professional Experience</h2>

    <div class="experience-item">

      <h3>Senior Software Engineer</h3>

      <p>
        • Provided Level 2/Level 3 application support for enterprise systems.<br>
        • Performed root cause analysis and reduced incidents significantly.<br>
        • Automated monitoring and validation using Python and Shell scripting.<br>
        • Managed Linux/Windows systems and AWS cloud infrastructure.<br>
        • Configured monitoring using Splunk, Dynatrace, and CloudWatch.<br>
        • Supported enterprise production deployments and incident response.<br>
        • Worked extensively with DevOps and CI/CD pipelines.
      </p>

    </div>

  </section>

  <section id="certifications">

    <h2 class="section-title">Certifications</h2>

    <div class="certifications">

      <ul>
        <li>AWS Certified Cloud Practitioner</li>
        <li>AWS Certified Data Engineer – Associate</li>
        <li>AWS Certified AI Practitioner</li>
        <li>Appian L2 Certified Developer</li>
      </ul>

    </div>

  </section>

  <section id="contact">

    <h2 class="section-title">Contact</h2>

    <div class="card" style="text-align:center;">

      <h3>Get In Touch</h3>

      <br>

      <p>Email: sharantejapaladugu5@gmail.com</p>
      <p>Phone: +1 571-519-4236</p>
      <p>Location: United States</p>

      <a href="mailto:sharantejapaladugu5@gmail.com" class="btn">
        Send Email
      </a>

    </div>

  </section>

  <footer>
    <p>
      © 2026 Sharan Paladugu | Senior Software Engineer Portfolio
    </p>
  </footer>

</body>
</html>
