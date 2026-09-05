# portfolio
Professional Portfolio - Hrishikesh Sonawane
Welcome to my professional portfolio website! This is a static HTML/CSS portfolio showcasing my 20+ years of experience in Investment Banking, Financial Operations, and Business Development.

## 🌐 Live Website

Your portfolio is hosted on GitHub Pages at:
**[https://careers247hrish.github.io/portfolio](https://careers247hrish.github.io/portfolio)**

## 📋 Portfolio Contents

The portfolio includes the following sections:

### 1. **Home/Hero Section**
- Professional headline and tagline
- Brief introduction
- Call-to-action buttons

### 2. **About Me**
- Professional summary
- Key statistics and achievements
- Career highlights

### 3. **Professional Experience**
- Detailed work history from major financial institutions:
  - Deutsche Bank (AVP - Current)
  - Standard Chartered Bank (Singapore)
  - Société Généralé (Singapore)
  - JPMorgan Chase (Mumbai/New York)
- Role descriptions and key achievements for each position

### 4. **Project Management**
- RPA (Robotics Process Automation) initiative
- System & Process Migration projects
- System Enhancement & Technology Initiatives

### 5. **Academic Development**
- Post Graduate Diploma in Banking & Finance (Symbiosis International University)
- BBA in Financial Management (Goa University)
- Advanced Diploma in Network Centered Computing (NIIT, Goa)

### 6. **Professional & Technical Skills**
- Core Competencies
- Leadership & Soft Skills
- Financial Expertise
- Systems & Tools (Bloomberg, Kondor+, MUREX, etc.)
- Compliance & Risk Management
- Languages

### 7. **Contact Section**
- Email address
- Phone number
- Location
- Social media links (LinkedIn, GitHub, Twitter, Instagram)

## 🛠️ Technology Stack

- **HTML5** - Semantic structure
- **CSS3** - Responsive design with flexbox and grid
- **JavaScript** - Smooth scrolling and interactive features
- **Font Awesome** - Icons for social media and visual elements
- **GitHub Pages** - Free hosting

## 📱 Features

✅ Fully Responsive Design - Works on desktop, tablet, and mobile
✅ Smooth Scrolling Navigation - Easy navigation between sections
✅ Modern UI/UX - Clean and professional design
✅ Performance Optimized - Fast loading times
✅ SEO Friendly - Proper semantic HTML structure
✅ Accessibility - WCAG compliant

## 🚀 Getting Started

### View Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/careers247hrish/portfolio.git
Navigate to the project directory:

bash
cd portfolio
Open index.html in your web browser or use a local server:

bash
python -m http.server 8000
# or
npx http-server
Visit http://localhost:8000 in your browser

Deploy on GitHub Pages
Go to your repository settings
Scroll down to "GitHub Pages" section
Select "main" branch as the source
Your site will be published at https://careers247hrish.github.io/portfolio
📝 Customization
Update Personal Information
Edit index.html and update:

Name and contact details
Email address
Phone number
Social media links
Modify Colors
Edit styles.css and change the CSS variables in :root:

CSS
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --accent-color: #e74c3c;
    /* ... */
}
Add More Sections
Add new sections to index.html and create corresponding CSS in styles.css

📧 Contact Information
Email: hrishikesh.sonawane@example.com
Phone: +91 XXXXXXXXXX
Location: Pune, India
LinkedIn: [Profile Link]
GitHub: careers247hrish
📄 Files Structure
Code
portfolio/
├── index.html       # Main HTML file
├── styles.css       # Stylesheet
├── script.js        # JavaScript functionality
└── README.md        # This file
🎨 Design Highlights
Color Scheme: Professional blue and dark gray
Typography: Modern sans-serif fonts
Layout: Mobile-first responsive grid
Animations: Smooth transitions and hover effects
Icons: Font Awesome icons for visual appeal
🔄 Updates & Maintenance
To update your portfolio:

Edit the relevant files (index.html, styles.css, script.js)
Commit your changes: git add . and git commit -m "Update portfolio"
Push to GitHub: git push origin main
Changes will be live within minutes
📈 Future Enhancements
Consider adding:

Blog section
Download resume button (PDF)
Project portfolio with images
Testimonials section
Contact form with backend
Dark mode toggle
Multiple language support
📜 License
This portfolio is open source and available under the MIT License.

🤝 Support
If you need help customizing or deploying your portfolio, feel free to reach out or refer to GitHub Pages documentation.

Happy to have you visit my portfolio! 🚀

Last Updated: September 2024

Code
Please confirm you want Copilot to make this change in the careers247hrish/portfolio repository on the default branch.

Make these code changes?
index.html

HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hrishikesh Sonawane - Professional Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="container">
            <div class="nav-brand">Hrishikesh Sonawane</div>
            <ul class="nav-menu">
                <li><a href="#home" class="nav-link">Home</a></li>
                <li><a href="#about" class="nav-link">About</a></li>
                <li><a href="#experience" class="nav-link">Experience</a></li>
                <li><a href="#projects" class="nav-link">Projects</a></li>
                <li><a href="#academics" class="nav-link">Academics</a></li>
                <li><a href="#skills" class="nav-link">Skills</a></li>
                <li><a href="#contact" class="nav-link">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
            <div class="hero-content">
                <h1>Hrishikesh Sonawane</h1>
                <p class="tagline">AVP | Trader & Sales Support | Financial Markets Expert</p>
                <p class="subtitle">Experienced Financial Operations Professional with 20+ years in Investment Banking, Risk Management & Business Development</p>
                <div class="hero-buttons">
                    <a href="#contact" class="btn btn-primary">Get In Touch</a>
                    <a href="#experience" class="btn btn-secondary">View My Work</a>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <h2 class="section-title">About Me</h2>
            <div class="about-content">
                <p>With over 20 years of experience in Investment Banking and Financial Operations, I bring a wealth of expertise in managing complex financial systems, risk management, and business process optimization. I have worked with leading global financial institutions including Deutsche Bank, Standard Chartered, Société Généralé, and JPMorgan Chase.</p>
                <p>My career is marked by a proven ability to deliver seamless operational functionality, mentor high-performing teams, and drive strategic business initiatives in fast-paced, regulated environments. I'm passionate about leveraging technology and process innovation to create efficiencies and drive business value.</p>
                <div class="about-info">
                    <div class="info-box">
                        <h3>20+</h3>
                        <p>Years Experience</p>
                    </div>
                    <div class="info-box">
                        <h3>10+</h3>
                        <p>Teams Mentored</p>
                    </div>
                    <div class="info-box">
                        <h3>100%</h3>
                        <p>Trade Synchronization Achieved</p>
                    </div>
                    <div class="info-box">
                        <h3>4</h3>
                        <p>Global Banks</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Professional Experience Section -->
    <section id="experience" class="experience">
        <div class="container">
            <h2 class="section-title">Professional Experience</h2>
            
            <div class="experience-item">
                <div class="experience-header">
                    <h3>AVP (Trader & Sales Support) - Structured Credit & Credit Flow MO Desk</h3>
                    <span class="company">Deutsche Bank, Pune</span>
                    <span class="duration">September 2013 - Present</span>
                </div>
                <ul class="experience-details">
                    <li>Oversight of structured & flow credit derivatives business desks ensuring seamless functioning of Trade & Sales Support processes</li>
                    <li>Ensured controlled environment and alignment of business functions with global practices</li>
                    <li>Continuous governance of operational headcounts supporting various credit trading desks</li>
                    <li>Regular stakeholder updates with appropriate escalation and tracking of process initiatives</li>
                    <li>Managed BoW prioritization for technology enhancements and business process transformation</li>
                    <li>Worked closely with APAC, EU & NY stakeholders on trader support operations</li>
                    <li>Trained, mentored & groomed 10+ middle managers to ensure excellent service quality</li>
                    <li>Implementation lead for CFTC & ESMA regulatory control environment</li>
                    <li>Strategized Business Continuity Plans for FIC Operations across multiple asset classes</li>
                    <li>Led COO initiatives creating efficiencies & cost saves (~6 FTEs)</li>
                </ul>
            </div>

            <div class="experience-item">
                <div class="experience-header">
                    <h3>Sr. Associate (Middle Office New Initiatives) - Credits & Trade Restructuring Desk</h3>
                    <span class="company">Standard Chartered Bank, Singapore</span>
                    <span class="duration">April 2011 - June 2013</span>
                </div>
                <ul class="experience-details">
                    <li>Technologically enhanced risk management functionality for better Risk & MTM capture</li>
                    <li>Timely validation of credit & structured trades reducing downstream settlement risks</li>
                    <li>Assisted traders in booking complex structured trades involving FXMM, Credit & Rates Derivatives</li>
                    <li>Prioritized book of works identifying key BoWs for immediate process development</li>
                    <li>Generated correct rate curves supporting Market risk analytics and front office P&L determination</li>
                    <li>Simplified reporting for Structured Trades improving user understanding</li>
                    <li>Designed streamlined Process Map for the Credit desk</li>
                </ul>
            </div>

            <div class="experience-item">
                <div class="experience-header">
                    <h3>Sr. Analyst (Rates Middle Office)</h3>
                    <span class="company">Société Généralé Corporate Investment Bank, Singapore</span>
                    <span class="duration">July 2008 - February 2011</span>
                </div>
                <ul class="experience-details">
                    <li>Managed operational risk by monitoring & controlling trade inputs, modifications & cancellations</li>
                    <li>Served 6 Asia Pac locations supporting dedicated traders onsite</li>
                    <li>Established robust reconciliation platforms for plain vanilla to exotic derivative products</li>
                    <li>Accomplished 100% FO & BO trade synchronization by optimizing reconciliation platforms</li>
                    <li>Minimized impact on economic P&L through failed trade analysis and correction</li>
                    <li>Achieved 0.01% exception break rate through root cause analysis</li>
                    <li>Prevented bank frauds through legitimate trade amendment & validation</li>
                    <li>Supervised & mentored team members with training plans and individual feedback sessions</li>
                </ul>
            </div>

            <div class="experience-item">
                <div class="experience-header">
                    <h3>Team Specialist at IB – Accounting Control</h3>
                    <span class="company">JPMorgan Chase, Mumbai / New York</span>
                    <span class="duration">June 2007 - July 2008</span>
                </div>
                <ul class="experience-details">
                    <li>Assigned over 90% cost of funding charges to various lines of businesses</li>
                    <li>Reconciliation of general ledger against risk management system eliminating exceptions</li>
                    <li>Controlled & monitored fixed income P&L at economic & accounting level on T+1 basis</li>
                    <li>Strengthened operational controls and productivity</li>
                </ul>
            </div>

            <div class="experience-item">
                <div class="experience-header">
                    <h3>Professional at IB – Derivatives</h3>
                    <span class="company">JPMorgan Chase, Mumbai / New York</span>
                    <span class="duration">April 2004 - June 2007</span>
                </div>
                <ul class="experience-details">
                    <li>Analyzed flaws in deals and managed complex trade settlements across derivative products</li>
                    <li>Covered IRD, Credit Derivatives, Equity Derivatives, FX & FX-Options</li>
                    <li>Pre-settled trades with appropriate funding and initiated payment authentication</li>
                    <li>Investigated unsettled trades across EMEA, ASIAPAC & NA locations</li>
                    <li>Pioneered settlement mechanism modifications preventing future nostro breaks</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Project Management Section -->
    <section id="projects" class="projects">
        <div class="container">
            <h2 class="section-title">Project Management</h2>
            
            <div class="projects-grid">
                <div class="project-card">
                    <div class="project-icon">
                        <i class="fas fa-robot"></i>
                    </div>
                    <h3>Robotics Process Automation (RPA)</h3>
                    <p>Automated Processes Through Robotics Technology – 1st of its kind in the entire IB Derivatives Operations. Pioneered automation initiatives to streamline operational workflows and reduce manual interventions.</p>
                    <span class="project-tag">Innovation</span>
                </div>

                <div class="project-card">
                    <div class="project-icon">
                        <i class="fas fa-exchange-alt"></i>
                    </div>
                    <h3>System & Process Migration</h3>
                    <p>Active involvement in system & process migration projects, including setup of new products and designing operational workflows using business process management tools. Successfully coordinated requirements with business units and implemented changes risk-free.</p>
                    <span class="project-tag">Migration</span>
                </div>

                <div class="project-card">
                    <div class="project-icon">
                        <i class="fas fa-cogs"></i>
                    </div>
                    <h3>System Enhancement & Technology Initiatives</h3>
                    <p>Seasoned player & vigorous participation on system enhancement projects covering Front to Back Technological changes. Successfully signed off on UATs, coordinated requirements effectively with business units, negotiated budgets with COOs & implemented changes appropriately.</p>
                    <span class="project-tag">Technology</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Academics Section -->
    <section id="academics" class="academics">
        <div class="container">
            <h2 class="section-title">Academic Development</h2>
            
            <div class="academics-timeline">
                <div class="academic-item">
                    <div class="academic-header">
                        <h3>Post Graduate Diploma in Banking & Finance</h3>
                        <span class="institution">Symbiosis International University</span>
                    </div>
                    <p class="duration">2015 - 2016</p>
                </div>

                <div class="academic-item">
                    <div class="academic-header">
                        <h3>Bachelors of Business Administration (Financial Management)</h3>
                        <span class="institution">Goa University, India</span>
                    </div>
                    <p class="duration">2000 - 2003</p>
                </div>

                <div class="academic-item">
                    <div class="academic-header">
                        <h3>Advanced Diploma in Network Centered Computing</h3>
                        <span class="institution">NIIT, Goa</span>
                    </div>
                    <p class="duration">1998 - 1999</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills">
        <div class="container">
            <h2 class="section-title">Professional & Technical Skills</h2>
            
            <div class="skills-grid">
                <div class="skill-category">
                    <h3>Core Competencies</h3>
                    <ul>
                        <li>Decision Making & Problem Solving</li>
                        <li>Quick Learning & Adaptability</li>
                        <li>Project Management</li>
                        <li>Task Prioritization</li>
                        <li>High-Pressure Environment Management</li>
                    </ul>
                </div>

                <div class="skill-category">
                    <h3>Leadership & Soft Skills</h3>
                    <ul>
                        <li>Team Leadership & Mentoring</li>
                        <li>Relationship Building</li>
                        <li>Public Speaking</li>
                        <li>Presentation Skills</li>
                        <li>Cross-functional Collaboration</li>
                    </ul>
                </div>

                <div class="skill-category">
                    <h3>Financial Expertise</h3>
                    <ul>
                        <li>Fixed Income - Rates/Credit Derivatives</li>
                        <li>Equity Derivatives</li>
                        <li>Futures & Options</li>
                        <li>FX Markets</li>
                        <li>Risk Management</li>
                    </ul>
                </div>

                <div class="skill-category">
                    <h3>Systems & Tools</h3>
                    <ul>
                        <li>Bloomberg</li>
                        <li>Kondor+</li>
                        <li>MUREX</li>
                        <li>STS & TLM</li>
                        <li>SEF & IRFE</li>
                    </ul>
                </div>

                <div class="skill-category">
                    <h3>Compliance & Risk</h3>
                    <ul>
                        <li>SOX Compliance</li>
                        <li>Dodd-Frank Act</li>
                        <li>Internal Audit Guidelines</li>
                        <li>CFTC & ESMA Regulations</li>
                        <li>Risk Management Frameworks</li>
                    </ul>
                </div>

                <div class="skill-category">
                    <h3>Languages</h3>
                    <ul>
                        <li>English (Fluent)</li>
                        <li>Hindi (Native)</li>
                        <li>Marathi (Native)</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2 class="section-title">Get In Touch</h2>
            <p class="section-subtitle">Feel free to reach out for opportunities, collaborations, or just to say hello!</p>
            
            <div class="contact-content">
                <div class="contact-info">
                    <div class="contact-item">
                        <i class="fas fa-envelope"></i>
                        <h3>Email</h3>
                        <p><a href="mailto:hrishikesh.sonawane@example.com">hrishikesh.sonawane@example.com</a></p>
                    </div>

                    <div class="contact-item">
                        <i class="fas fa-phone"></i>
                        <h3>Phone</h3>
                        <p>+91 XXXXXXXXXX</p>
                    </div>

                    <div class="contact-item">
                        <i class="fas fa-map-marker-alt"></i>
                        <h3>Location</h3>
                        <p>Pune, India</p>
                    </div>
                </div>

                <div class="social-links">
                    <h3>Connect With Me</h3>
                    <div class="socials">
                        <a href="https://linkedin.com/in/hrishikesh-sonawane" target="_blank" class="social-icon" title="LinkedIn">
                            <i class="fab fa-linkedin-in"></i>
                        </a>
                        <a href="https://github.com/careers247hrish" target="_blank" class="social-icon" title="GitHub">
                            <i class="fab fa-github"></i>
                        </a>
                        <a href="https://twitter.com" target="_blank" class="social-icon" title="Twitter">
                            <i class="fab fa-twitter"></i>
                        </a>
                        <a href="https://www.instagram.com" target="_blank" class="social-icon" title="Instagram">
                            <i class="fab fa-instagram"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 Hrishikesh Sonawane. All rights reserved.</p>
            <p>Hosted on GitHub Pages | Built with HTML & CSS</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
