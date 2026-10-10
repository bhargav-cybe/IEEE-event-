# IEEE-event-
Given in recruitment and ask to just show case their technical body
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IEEE Events & Hackathons Portal 2026</title>
    <style>
        :root {
            --primary: #006699;
            --secondary: #002855;
            --accent: #00d2ff;
            --bg: #0b132b;
            --card-bg: #1c2541;
            --text: #ffffff;
            --subtext: #a0aec0;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg);
            color: var(--text);
            line-height: 1.6;
        }

        /* Navigation Bar */
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: var(--secondary);
            padding: 1rem 2rem;
            position: sticky;
            top: 0;
            z-index: 1000;
            border-bottom: 2px solid var(--accent);
        }

        .navbar .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--accent);
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .nav-links {
            display: flex;
            list-style: none;
            gap: 20px;
            align-items: center;
        }

        .nav-links a {
            color: var(--text);
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }

        .nav-links a:hover {
            color: var(--accent);
        }

        .btn-register {
            background: linear-gradient(45deg, var(--primary), var(--accent));
            color: white;
            padding: 0.5rem 1.2rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
            text-decoration: none;
            transition: transform 0.2s, box-shadow 0.2s;
        }

        .btn-register:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(0, 210, 255, 0.4);
        }

        /* Hero / Banner Header */
        .hero {
            text-align: center;
            padding: 3rem 1rem;
            background: radial-gradient(circle, #1c2541 0%, #0b132b 100%);
        }

        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
            color: var(--accent);
        }

        .hero p {
            color: var(--subtext);
            font-size: 1.1rem;
        }

        /* Main Container */
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        .section-title {
            font-size: 1.8rem;
            margin-bottom: 1.5rem;
            border-left: 4px solid var(--accent);
            padding-left: 10px;
        }

        /* Grid Layout */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 2rem;
            margin-bottom: 3rem;
        }

        /* Event Cards */
        .card {
            background-color: var(--card-bg);
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
            display: flex;
            flex-direction: column;
            transition: transform 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card-img {
            width: 100%;
            height: 220px;
            object-fit: cover;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }

        .card-body {
            padding: 1.5rem;
            display: flex;
            flex-direction: column;
            flex-grow: 1;
        }

        .card-tag {
            font-size: 0.8rem;
            background: var(--primary);
            color: white;
            padding: 3px 8px;
            border-radius: 3px;
            width: fit-content;
            margin-bottom: 0.5rem;
            text-transform: uppercase;
        }

        .card-title {
            font-size: 1.3rem;
            margin-bottom: 0.5rem;
        }

        .card-info {
            font-size: 0.9rem;
            color: var(--subtext);
            margin-bottom: 0.5rem;
        }

        .card-desc {
            font-size: 0.95rem;
            margin-bottom: 1.5rem;
            flex-grow: 1;
        }

        .card-footer {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .contact-info {
            font-size: 0.8rem;
            color: var(--subtext);
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 2rem;
            background-color: var(--secondary);
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: var(--subtext);
        }

        footer a {
            color: var(--accent);
            text-decoration: none;
        }
    </style>
</head>
<body>

    <!-- Navigator Bar -->
    <nav class="navbar">
        <a href="https://spardha2k26.vercel.app/" class="logo">⚡ IEEE Events Portal</a>
        <ul class="nav-links">
            <li><a href="#conferences">Conferences</a></li>
            <li><a href="#hackathons">Hackathons</a></li>
            <li><a href="#management">Management & Projects</a></li>
            <li><a href="https://2026.ieee-icra.org" target="_blank" class="btn-register">Register Now</a></li>
        </ul>
    </nav>

    <!-- Hero Header -->
    <header class="hero">
        <h1>IEEE Student Activities & Conferences 2026</h1>
        <p>Explore flagship hackathons, technical conferences, and project management events.</p>
    </header>

    <div class="container">

        <!-- Conferences & Projects Section -->
        <h2 class="section-title" id="conferences">International Conferences & Projects</h2>
        <div class="grid">
            
            <!-- Card 1: ICRA 2026 -->
            <div class="card">
                <img src="49233.jpg" alt="ICRA 2026 Flyer" class="card-img" onerror="this.src='https://via.placeholder.com/400x220?text=ICRA+2026+Conference'">
                <div class="card-body">
                    <span class="card-tag">Conference / Projects</span>
                    <h3 class="card-title">2026 IEEE International Conference on Robotics & Automation (ICRA 2026)</h3>
                    <p class="card-info">📅 <strong>Date:</strong> 2nd to 4th June 2026</p>
                    <p class="card-info">📍 <strong>Venue:</strong> VNR Vignana Jyothi Institute of Engineering and Technology</p>
                    <p class="card-desc">
                        A satellite conference focusing on Advanced Robotics & Intelligent Systems, Global Networking with international researchers, and the Future of AI, Robotics & Automation[span_0](start_span)[span_0](end_span).
                    </p>
                    <div class="card-footer">
                        <div class="contact-info">
                            📞 Digvijay: +91 63003 07202[span_1](start_span)[span_1](end_span)<br>
                            📞 Gaurav: +91 81795 90621[span_2](start_span)[span_2](end_span)
                        </div>
                        <a href="https://2026.ieee-icra.org" target="_blank" class="btn-register">Register</a>
                    </div>
                </div>
            </div>

            <!-- Card 2: EDIGE 2026 -->
            <div class="card">
                <img src="https://via.placeholder.com/400x220?text=EDIGE+2026" alt="EDIGE 2026 Flyer" class="card-img">
                <div class="card-body">
                    <span class="card-tag">Conference</span>
                    <h3 class="card-title">EDIGE 2026 - Digital Intelligence & Generative AI</h3>
                    <p class="card-info">📅 <strong>Date:</strong> 30th - 31st October 2026</p>
                    <p class="card-info">📍 <strong>Venue:</strong> VIT Bhopal</p>
                    <p class="card-desc">
                        International Conference on Emerging Digital Intelligence and Generative Engineering. Bringing together research papers, innovation showcases, and expert panels.
                    </p>
                    <div class="card-footer">
                        <div class="contact-info">
                            🌐 Organised by VIT Bhopal IEEE
                        </div>
                        <a href="#" class="btn-register">Register</a>
                    </div>
                </div>
            </div>

        </div>

        <!-- Hackathons Section -->
        <h2 class="section-title" id="hackathons">Hackathons & Technical Events</h2>
        <div class="grid">

            <!-- Card 3: INNO-VA-THON 3.0 -->
            <div class="card">
                <img src="https://via.placeholder.com/400x220?text=INNO-VA-THON+3.0" alt="INNO-VA-THON 3.0 Flyer" class="card-img">
                <div class="card-body">
                    <span class="card-tag">24-Hour Hackathon</span>
                    <h3 class="card-title">INNO-VA-THON 3.0</h3>
                    <p class="card-info">📅 <strong>Date:</strong> Upcoming 2026</p>
                    <p class="card-info">📍 <strong>Organiser:</strong> Dept. of Electronics & Instrumentation Engineering</p>
                    <p class="card-desc">
                        <strong>Build. Innovate. Compete.</strong> A 24-hour hackathon bringing together a fusion of software and hardware solutions to solve real-world industry problems.
                    </p>
                    <div class="card-footer">
                        <div class="contact-info">
                            🏆 Cash Prizes & Mentorship
                        </div>
                        <a href="#" class="btn-register">Register</a>
                    </div>
                </div>
            </div>

        </div>

        <!-- Management Events Section -->
        <h2 class="section-title" id="management">Management & Leadership Events</h2>
        <div class="grid">

            <!-- Card 4: IEEE Student Activities Management -->
            <div class="card">
                <img src="https://via.placeholder.com/400x220?text=IEEE+Management+Summit" alt="IEEE Leadership Summit" class="card-img">
                <div class="card-body">
                    <span class="card-tag">Management</span>
                    <h3 class="card-title">IEEE Hyderabad Section Student Leadership Summit</h3>
                    <p class="card-info">📅 <strong>Date:</strong> To Be Announced</p>
                    <p class="card-info">📍 <strong>Organiser:</strong> IEEE Hyderabad SAC</p>
                    <p class="card-desc">
                        A flagship management and leadership event designed for IEEE student officers, project coordinators, and volunteer leads to manage section activities and enhance project management skills.
                    </p>
                    <div class="card-footer">
                        <div class="contact-info">
                            👥 Open to all IEEE Members
                        </div>
                        <a href="#" class="btn-register">Register</a>
                    </div>
                </div>
            </div>

        </div>

    </div>

    <!-- Footer -->
    <footer>
        <p>© 2026 IEEE Hyderabad Section & Partner Student Branches. All Rights Reserved.</p>
        <p>Visit Official Portal: <a href="https://2026.ieee-icra.org" target="_blank">2026.ieee-icra.org</a> | Platform Link: <a href="https://spardha2k26.vercel.app/" target="_blank">spardha2k26.vercel.app</a></p>
    </footer>

</body>
</html>

