<title>SHAPNO ICT TRAINING AND SERVICE</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0; padding: 0; box-sizing: border-box;
      scroll-behavior: smooth;
    }
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #f0f4f8;
      color: #333;
    }
    header {
      background: linear-gradient(to right, #0066cc, #003d99);
      color: white;
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 2.5rem;
    }
    header p {
      font-size: 1.2rem;
      margin-top: 10px;
    }
    nav {
      background-color: #002f6c;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 10px;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffdd57;
    }
    section {
      max-width: 1000px;
      margin: auto;
      padding: 40px 20px;
    }
    h2 {
      color: #003d99;
      margin-bottom: 20px;
      font-size: 1.8rem;
      text-align: center;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1543269865-cbf427effbad') no-repeat center center/cover;
      color: white;
      text-align: center;
      padding: 100px 20px;
    }
    .hero h2 {
      font-size: 2.2rem;
      margin-bottom: 15px;
    }
    .hero p {
      font-size: 1.1rem;
      margin-bottom: 20px;
    }
    .hero a {
      background: #ffdd57;
      color: #003366;
      padding: 12px 24px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }
    .course-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      padding: 20px;
      transition: transform 0.3s ease;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card h3 {
      color: #0066cc;
      font-size: 1.1rem;
    }
    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    .contact-form button {
      background: #0066cc;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-weight: bold;
    }
    .contact-form button:hover {
      background: #004999;
    }
    .why-us {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      gap: 20px;
    }
    .why-us .card {
      flex: 1 1 200px;
      text-align: center;
    }
    .testimonials {
      background-color: #e6f0ff;
      padding: 40px 20px;
      border-radius: 10px;
    }
    .testimonial {
      font-style: italic;
      margin-bottom: 20px;
    }
    footer {
      background-color: #002f6c;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      margin-top: 30px;
    }
    @media (max-width: 600px) {
      header h1 { font-size: 1.8rem; }
    }
  </style>
</head>
<body>

  <header>
    <h1>SHAPNO ICT TRAINING AND SERVICE</h1>
    <p>Shaping the Future with Technology</p>
  </header>

  <nav>
    <a href="#hero">Home</a>
    <a href="#about">About</a>
    <a href="#courses">Courses</a>
    <a href="#why">Why Us</a>
    <a href="#testimonials">Testimonials</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="hero" class="hero">
    <h2>Learn. Grow. Succeed.</h2>
    <p>Join our ICT training programs and build a brighter future.</p>
    <a href="#contact">Enroll Now</a>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p><strong>Mission:</strong> To empower the youth of Bangladesh with essential ICT skills.</p>
    <p><strong>Vision:</strong> To transform Bangladesh into a skilled and digitally advanced nation.</p>
  </section>

  <section id="courses">
    <h2>Our Courses</h2>
    <div class="course-grid">
      <div class="card"><h3>Computer Office Application</h3></div>
      <div class="card"><h3>Graphics Design</h3></div>
      <div class="card"><h3>Web Design & Development</h3></div>
      <div class="card"><h3>Digital Marketing</h3></div>
      <div class="card"><h3>Freelancing Training</h3></div>
      <div class="card"><h3>ICT Career Consultancy</h3></div>
    </div>
  </section>

  <section id="why">
    <h2>Why Choose Us?</h2>
    <div class="why-us">
      <div class="card"><h3>Expert Trainers</h3><p>Industry professionals with real experience.</p></div>
      <div class="card"><h3>Job Support</h3><p>We assist in freelancing and job placement.</p></div>
      <div class="card"><h3>Affordable Fees</h3><p>High quality training at a low cost.</p></div>
    </div>
  </section>

  <section id="testimonials" class="testimonials">
    <h2>What Our Students Say</h2>
    <div class="testimonial">“I learned graphics design here and now I earn through freelancing!” – Rakib</div>
    <div class="testimonial">“The trainers are very supportive and friendly.” – Shoma</div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p><strong>Email:</strong> shapnoicttrainingandservice@gmail.com</p>
    <p><strong>Phone:</strong> 01737580063</p>
    <div class="contact-form">
      <input type="text" placeholder="Your Name" />
      <input type="email" placeholder="Your Email" />
      <textarea rows="4" placeholder="Your Message"></textarea>
      <button>Send Message</button>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 SHAPNO ICT TRAINING AND SERVICE. All rights reserved.</p>
  </footer>

</body>
