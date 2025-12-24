# srishti-digital-library
Official website of Srishti Digital Library<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Srishti Digital Library</title>
  <link
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
    rel="stylesheet"
  />
  <style>
    :root {
      --primary-yellow: #f6b93b;
      --dark-brown: #5d4037;
      --text-dark: #4e342e;
      --bg-gradient: linear-gradient(135deg, #fceabb, #f8b500);
      --font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: var(--font-family);
    }

    body {
      background: var(--bg-gradient);
      color: var(--text-dark);
      line-height: 1.5;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      padding: 2rem;
    }

    .container {
      max-width: 900px;
      background: #fff7e1;
      border-radius: 15px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.15);
      padding: 2rem 2.5rem;
    }

    h1 {
      font-size: 3rem;
      text-align: center;
      color: var(--primary-yellow);
      text-shadow: 2px 3px 5px #6a3e1b;
      font-weight: 900;
      margin-bottom: 0.3rem;
      letter-spacing: 0.15em;
    }

    h2.subtitle {
      text-align: center;
      color: #603813;
      font-size: 1.1rem;
      font-weight: 700;
      background: #f7a600;
      padding: 0.2rem 1rem;
      width: fit-content;
      margin: 0 auto 2rem auto;
      border-radius: 10px;
      box-shadow: 0 3px 10px #d88c00aa;
    }

    ul.features-list {
      list-style: none;
      margin-bottom: 2.5rem;
      padding-left: 0;
    }

    ul.features-list li {
      font-size: 1.2rem;
      font-weight: 600;
      margin-bottom: 1rem;
      color: var(--dark-brown);
      display: flex;
      align-items: center;
      gap: 0.8rem;
    }

    ul.features-list li i {
      font-size: 1.5rem;
      color: var(--primary-yellow);
      min-width: 30px;
      text-align: center;
    }

    .contact-section {
      background: #5d4037;
      color: var(--primary-yellow);
      padding: 1.5rem 2rem;
      border-radius: 10px;
      margin-bottom: 2rem;
      box-shadow: 0 5px 20px #4a2f1c99;
    }

    .contact-section p {
      font-size: 1.15rem;
      font-weight: 700;
      margin-bottom: 0.3rem;
      text-align: center;
    }

    .contact-section p strong {
      font-size: 1.4rem;
      display: block;
      margin-top: 0.2rem;
      letter-spacing: 0.1em;
    }

    .management {
      background: #fff4d1;
      border-radius: 15px;
      padding: 1.5rem 2rem;
      box-shadow: 0 3px 12px #d8b200cc;
      margin-bottom: 2rem;
    }

    .management h3 {
      color: #a16b00;
      font-weight: 900;
      font-size: 1.8rem;
      text-align: center;
      letter-spacing: 0.07em;
      margin-bottom: 1.2rem;
    }

    .management ul {
      list-style: none;
      padding-left: 0;
      max-width: 450px;
      margin: 0 auto;
      font-size: 1.15rem;
      font-weight: 700;
      color: var(--dark-brown);
    }

    .management ul li {
      margin-bottom: 0.9rem;
    }

    .management ul li span.role {
      color: var(--primary-yellow);
      font-weight: 900;
      text-transform: uppercase;
      margin-right: 0.4rem;
    }

    .facilities {
      background: #f7a600;
      color: #4a2f1c;
      font-weight: 700;
      font-size: 1.1rem;
      text-align: center;
      border-radius: 10px;
      padding: 0.9rem 0;
      letter-spacing: 0.1em;
      box-shadow: 0 5px 15px #d08c00cc;
    }

    .location {
      margin-top: 2rem;
      font-weight: 700;
      color: var(--dark-brown);
      font-size: 1.1rem;
      text-align: center;
      letter-spacing: 0.05em;
    }

    .qr-section {
      text-align: center;
      margin: 2rem 0 1rem 0;
    }

    .qr-section img {
      width: 140px;
      border-radius: 15px;
      box-shadow: 0 7px 20px rgba(0,0,0,0.2);
      cursor: pointer;
      transition: transform 0.3s ease;
    }
    .qr-section img:hover {
      transform: scale(1.1);
    }

    footer {
      text-align: center;
      color: #6b553a;
      font-weight: 600;
      font-size: 0.95rem;
      margin-top: 2rem;
      letter-spacing: 0.05em;
    }
  </style>
</head>
<body>
  <div class="container" role="main" aria-label="Srishti Digital Library Information">
    <header>
      <h1>SRISHTI</h1>
      <h2 class="subtitle">Digital Library</h2>
      <h2 class="subtitle" style="background:#ad5800; margin-top:0.3rem;">ज्ञान की नई दुनिया</h2>
    </header>

    <ul class="features-list" aria-label="Features of Srishti Digital Library">
      <li><i class="fas fa-wifi" aria-hidden="true"></i> High Speed Internet</li>
      <li><i class="fas fa-book-open" aria-hidden="true"></i> E-Books &amp; E-Journals</li>
      <li><i class="fas fa-tablet-alt" aria-hidden="true"></i> Online Study Materials</li>
      <li><i class="fas fa-user-graduate" aria-hidden="true"></i> Competitive Exam Prep</li>
      <li><i class="fas fa-desktop" aria-hidden="true"></i> Computer Facility</li>
      <li><i class="fas fa-database" aria-hidden="true"></i> Digital Resources</li>
      <li><i class="fas fa-leaf" aria-hidden="true"></i> Peaceful Study Environment</li>
    </ul>

    <section class="contact-section" aria-label="Opening details and contact numbers">
      <p>OPEN 7 DAYS A WEEK</p>
      <p><strong>Call:</strong> 9838973610, 8960662683</p>
      <p class="location">Kamela Chauraha, Haidergarh, Barabanki</p>
    </section>

    <section class="management" aria-label="Library Management Team">
      <h3>Management</h3>
      <ul>
        <li><span class="role">DIRECTOR -</span> Ravi Prakash Tiwari</li>
        <li><span class="role">THE CEO -</span> Vipin Tiwari</li>
        <li><span class="role">OPERATOR -</span> Anuj Yadav</li>
      </ul>
    </section>

    <section class="facilities" aria-label="Facilities available at Srishti Digital Library">
      AC COMFORT &nbsp;&bull;&nbsp; POWER BACKUP &nbsp;&bull;&nbsp; CCTV SECURITY
    </section>

    <section class="qr-section" aria-label="QR Code for Library details">
      <p>Scan for Details</p>
      <img
        src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://example.com/srishti-digital-library"
        alt="QR Code linking to Srishti Digital Library details"
      />
    </section>

    <footer>
      &copy; 2024 Srishti Digital Library. All Rights Reserved.
    </footer>
  </div>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Srishti Digital Library</title>
  <link
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
    rel="stylesheet"
  />
  <style>
    :root {
      --primary-yellow: #f6b93b;
      --dark-brown: #5d4037;
      --text-dark: #4e342e;
      --bg-gradient: linear-gradient(135deg, #fceabb, #f8b500);
      --font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: var(--font-family);
    }

    body {
      background: var(--bg-gradient);
      color: var(--text-dark);
      line-height: 1.5;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      padding: 2rem;
    }

    .container {
      max-width: 900px;
      background: #fff7e1;
      border-radius: 15px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.15);
      padding: 2rem 2.5rem;
    }

    h1 {
      font-size: 3rem;
      text-align: center;
      color: var(--primary-yellow);
      text-shadow: 2px 3px 5px #6a3e1b;
      font-weight: 900;
      margin-bottom: 0.3rem;
      letter-spacing: 0.15em;
    }

    h2.subtitle {
      text-align: center;
      color: #603813;
      font-size: 1.1rem;
      font-weight: 700;
      background: #f7a600;
      padding: 0.2rem 1rem;
      width: fit-content;
      margin: 0 auto 2rem auto;
      border-radius: 10px;
      box-shadow: 0 3px 10px #d88c00aa;
    }

    ul.features-list {
      list-style: none;
      margin-bottom: 2.5rem;
      padding-left: 0;
    }

    ul.features-list li {
      font-size: 1.2rem;
      font-weight: 600;
      margin-bottom: 1rem;
      color: var(--dark-brown);
      display: flex;
      align-items: center;
      gap: 0.8rem;
    }

    ul.features-list li i {
      font-size: 1.5rem;
      color: var(--primary-yellow);
      min-width: 30px;
      text-align: center;
    }

    .contact-section {
      background: #5d4037;
      color: var(--primary-yellow);
      padding: 1.5rem 2rem;
      border-radius: 10px;
      margin-bottom: 2rem;
      box-shadow: 0 5px 20px #4a2f1c99;
    }

    .contact-section p {
      font-size: 1.15rem;
      font-weight: 700;
      margin-bottom: 0.3rem;
      text-align: center;
    }

    .contact-section p strong {
      font-size: 1.4rem;
      display: block;
      margin-top: 0.2rem;
      letter-spacing: 0.1em;
    }

    .management {
      background: #fff4d1;
      border-radius: 15px;
      padding: 1.5rem 2rem;
      box-shadow: 0 3px 12px #d8b200cc;
      margin-bottom: 2rem;
    }

    .management h3 {
      color: #a16b00;
      font-weight: 900;
      font-size: 1.8rem;
      text-align: center;
      letter-spacing: 0.07em;
      margin-bottom: 1.2rem;
    }

    .management ul {
      list-style: none;
      padding-left: 0;
      max-width: 450px;
      margin: 0 auto;
      font-size: 1.15rem;
      font-weight: 700;
      color: var(--dark-brown);
    }

    .management ul li {
      margin-bottom: 0.9rem;
    }

    .management ul li span.role {
      color: var(--primary-yellow);
      font-weight: 900;
      text-transform: uppercase;
      margin-right: 0.4rem;
    }

    .facilities {
      background: #f7a600;
      color: #4a2f1c;
      font-weight: 700;
      font-size: 1.1rem;
      text-align: center;
      border-radius: 10px;
      padding: 0.9rem 0;
      letter-spacing: 0.1em;
      box-shadow: 0 5px 15px #d08c00cc;
    }

    .location {
      margin-top: 2rem;
      font-weight: 700;
      color: var(--dark-brown);
      font-size: 1.1rem;
      text-align: center;
      letter-spacing: 0.05em;
    }

    .qr-section {
      text-align: center;
      margin: 2rem 0 1rem 0;
    }

    .qr-section img {
      width: 140px;
      border-radius: 15px;
      box-shadow: 0 7px 20px rgba(0,0,0,0.2);
      cursor: pointer;
      transition: transform 0.3s ease;
    }
    .qr-section img:hover {
      transform: scale(1.1);
    }

    footer {
      text-align: center;
      color: #6b553a;
      font-weight: 600;
      font-size: 0.95rem;
      margin-top: 2rem;
      letter-spacing: 0.05em;
    }
  </style>
</head>
<body>
  <div class="container" role="main" aria-label="Srishti Digital Library Information">
    <header>
      <h1>SRISHTI</h1>
      <h2 class="subtitle">Digital Library</h2>
      <h2 class="subtitle" style="background:#ad5800; margin-top:0.3rem;">ज्ञान की नई दुनिया</h2>
    </header>

    <ul class="features-list" aria-label="Features of Srishti Digital Library">
      <li><i class="fas fa-wifi" aria-hidden="true"></i> High Speed Internet</li>
      <li><i class="fas fa-book-open" aria-hidden="true"></i> E-Books &amp; E-Journals</li>
      <li><i class="fas fa-tablet-alt" aria-hidden="true"></i> Online Study Materials</li>
      <li><i class="fas fa-user-graduate" aria-hidden="true"></i> Competitive Exam Prep</li>
      <li><i class="fas fa-desktop" aria-hidden="true"></i> Computer Facility</li>
      <li><i class="fas fa-database" aria-hidden="true"></i> Digital Resources</li>
      <li><i class="fas fa-leaf" aria-hidden="true"></i> Peaceful Study Environment</li>
    </ul>

    <section class="contact-section" aria-label="Opening details and contact numbers">
      <p>OPEN 7 DAYS A WEEK</p>
      <p><strong>Call:</strong> 9838973610, 8960662683</p>
      <p class="location">Kamela Chauraha, Haidergarh, Barabanki</p>
    </section>

    <section class="management" aria-label="Library Management Team">
      <h3>Management</h3>
      <ul>
        <li><span class="role">DIRECTOR -</span> Ravi Prakash Tiwari</li>
        <li><span class="role">THE CEO -</span> Vipin Tiwari</li>
        <li><span class="role">OPERATOR -</span> Anuj Yadav</li>
      </ul>
    </section>

    <section class="facilities" aria-label="Facilities available at Srishti Digital Library">
      AC COMFORT &nbsp;&bull;&nbsp; POWER BACKUP &nbsp;&bull;&nbsp; CCTV SECURITY
    </section>

    <section class="qr-section" aria-label="QR Code for Library details">
      <p>Scan for Details</p>
      <img
        src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://example.com/srishti-digital-library"
        alt="QR Code linking to Srishti Digital Library details"
      />
    </section>

    <footer>
      &copy; 2024 Srishti Digital Library. All Rights Reserved.
    </footer>
  </div>
</body>
</html>
