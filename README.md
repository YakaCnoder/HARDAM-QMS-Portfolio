<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ENUM | Backend Engineer & Database Optimization</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }

        .container {
            max-width: 600px;
            background: white;
            border-radius: 12px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            overflow: hidden;
        }

        .hero {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 40px;
            text-align: center;
        }

        .hero h1 {
            font-size: 28px;
            margin-bottom: 10px;
            font-weight: 700;
        }

        .hero .tagline {
            font-size: 14px;
            opacity: 0.9;
            margin-bottom: 20px;
        }

        .badge {
            display: inline-block;
            background: rgba(255, 255, 255, 0.2);
            border: 1px solid rgba(255, 255, 255, 0.4);
            padding: 6px 12px;
            border-radius: 20px;
            font-size: 12px;
            margin-bottom: 10px;
        }

        .content {
            padding: 40px;
        }

        .section {
            margin-bottom: 30px;
        }

        .section h2 {
            font-size: 16px;
            margin-bottom: 15px;
            color: #667eea;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px;
            margin-bottom: 20px;
        }

        .skill-tag {
            background: #f0f4ff;
            border-left: 3px solid #667eea;
            padding: 10px;
            border-radius: 4px;
            font-size: 13px;
            font-weight: 500;
        }

        .proof {
            background: #f9f9f9;
            border-left: 4px solid #764ba2;
            padding: 15px;
            margin: 15px 0;
            border-radius: 4px;
            font-size: 13px;
        }

        .proof-title {
            font-weight: 700;
            color: #764ba2;
            margin-bottom: 5px;
        }

        .proof-desc {
            color: #666;
            font-size: 12px;
            line-height: 1.5;
        }

        .cta {
            display: grid;
            gap: 10px;
        }

        .btn {
            padding: 12px 20px;
            border: none;
            border-radius: 6px;
            font-size: 14px;
            font-weight: 600;
            cursor: pointer;
            text-decoration: none;
            display: inline-block;
            text-align: center;
            transition: all 0.3s;
        }

        .btn-primary {
            background: #667eea;
            color: white;
        }

        .btn-primary:hover {
            background: #764ba2;
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(102, 126, 234, 0.3);
        }

        .btn-secondary {
            background: #f0f4ff;
            color: #667eea;
            border: 1px solid #667eea;
        }

        .btn-secondary:hover {
            background: #667eea;
            color: white;
        }

        .rate {
            font-size: 12px;
            color: #666;
            text-align: center;
            margin-top: 15px;
        }

        .rate strong {
            color: #764ba2;
        }

        .footer {
            background: #f5f5f5;
            padding: 20px;
            text-align: center;
            font-size: 12px;
            color: #999;
            border-top: 1px solid #eee;
        }

        .contact-links {
            display: flex;
            justify-content: center;
            gap: 15px;
            font-size: 12px;
        }

        .contact-links a {
            color: #667eea;
            text-decoration: none;
            font-weight: 600;
        }

        .contact-links a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- HERO SECTION -->
        <div class="hero">
            <div class="badge">🎓 Best Capstone Award</div>
            <h1>I Fix & Build Backend Systems</h1>
            <p class="tagline">PHP • MySQL • Database Optimization • API Integration • Bug Fixes</p>
        </div>

        <!-- MAIN CONTENT -->
        <div class="content">
            <!-- WHAT I DO -->
            <div class="section">
                <h2>What I Solve</h2>
                <div class="proof">
                    <div class="proof-title">✓ Database Performance Issues</div>
                    <div class="proof-desc">Slow queries killing your app? I optimize MySQL, add indexes, refactor logic. Turnaround: 24-48 hours.</div>
                </div>
                <div class="proof">
                    <div class="proof-title">✓ Backend Logic & Bug Fixes</div>
                    <div class="proof-desc">Broken PHP code? Missing features? Integration issues? I debug, fix, and deploy same week.</div>
                </div>
                <div class="proof">
                    <div class="proof-title">✓ API & Microservices</div>
                    <div class="proof-desc">Need a RESTful API? WebSocket integration? SMS automation? Built, tested, deployed.</div>
                </div>
            </div>

            <!-- CORE SKILLS -->
            <div class="section">
                <h2>Core Stack</h2>
                <div class="skills-grid">
                    <div class="skill-tag">PHP (7+ years)</div>
                    <div class="skill-tag">MySQL (Expert)</div>
                    <div class="skill-tag">Database Optimization</div>
                    <div class="skill-tag">API Design</div>
                    <div class="skill-tag">WebSocket</div>
                    <div class="skill-tag">SMS Integration</div>
                    <div class="skill-tag">Java Backend</div>
                    <div class="skill-tag">Bug Diagnosis</div>
                </div>
            </div>

            <!-- PROOF OF COMPETENCE -->
            <div class="section">
                <h2>Why You Should Hire Me</h2>
                <div class="proof">
                    <div class="proof-title">🏆 Best Capstone Thesis</div>
                    <div class="proof-desc">Graduated with award-winning capstone project: a production-grade Queue Management System with Java Swing, PHP backend, MySQL, WebSocket real-time display, and SMS integration. System is live and operational.</div>
                </div>
                <div class="proof">
                    <div class="proof-title">⚡ Fast Turnaround</div>
                    <div class="proof-desc">I work asynchronously (no long meetings). Backend work can be completed and deployed within 24-72 hours depending on scope.</div>
                </div>
                <div class="proof">
                    <div class="proof-title">💯 Obsessive About Quality</div>
                    <div class="proof-desc">Every fix is tested. Every script is optimized. Code is documented. No band-aid solutions.</div>
                </div>
            </div>

            <!-- PRICING -->
            <div class="section">
                <h2>Quick Quote</h2>
                <div class="rate">
                    <p><strong>Database Optimization:</strong> ₱1,500 - ₱5,000</p>
                    <p><strong>Bug Fix (simple):</strong> ₱500 - ₱2,000</p>
                    <p><strong>API / Script Build:</strong> ₱2,000 - ₱8,000</p>
                    <p style="margin-top: 10px; font-size: 11px; color: #999;">Prices vary by complexity. Get a free quote within 2 hours.</p>
                </div>
            </div>

            <!-- CTA -->
            <div class="cta">
                <button class="btn btn-primary" onclick="contactMe()">I Have a Project for You</button>
                <button class="btn btn-secondary" onclick="viewProof()">See My Capstone Proof</button>
            </div>

            <!-- CONTACT INFO -->
            <div class="rate" style="margin-top: 20px;">
                <p>📞 Quick Contact:</p>
                <div class="contact-links">
                    <a href="https://wa.me/63YOURPHONENUMBER">WhatsApp</a>
                    <a href="mailto:your.email@example.com">Email</a>
                    <a href="https://www.gcash.com">GCash Ready</a>
                </div>
            </div>
        </div>

        <!-- FOOTER -->
        <div class="footer">
            <p>Based in Basilan, Philippines 🇵🇭 | Available for asynchronous, backend-focused projects</p>
            <p style="margin-top: 10px; font-size: 11px;">Quick turnaround • Verifiable skills • Results-driven</p>
        </div>
    </div>

    <script>
        function contactMe() {
            // Replace with your WhatsApp number (include country code, no + or spaces)
            const phoneNumber = '63YOURPHONENUMBER'; // Format: 63XXXXXXXXXX
            const message = 'Hi ENUM! I have a PHP/MySQL project. Can you help?';
            const encodedMessage = encodeURIComponent(message);
            window.open(`https://wa.me/${phoneNumber}?text=${encodedMessage}`, '_blank');
        }

        function viewProof() {
            // Link to your capstone documentation or GitHub repo
            alert('Share your capstone link or GitHub repo here');
            // window.location.href = 'https://github.com/yourusername/HARDAM-QMS';
        }
    </script>
</body>
</html>
