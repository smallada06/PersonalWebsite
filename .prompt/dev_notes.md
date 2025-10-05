# AI Development Notes - Personal Portfolio Website

## Project Overview
This document tracks the AI assistance used in developing my personal portfolio website, built with HTML5 and CSS3.

## AI Prompts Used During Development

Prompt 1 — Build the Entire Website

Prompt:

Build a complete multi-page personal portfolio website for Sphoorthi Malladad, an Information Systems grad student at Kelley School of Business (Indiana University). Overview Create this as a clean, responsive, multi-page site (HTML + CSS only; no React/JS frameworks). The purpose is a personal showcase highlighting education, work experience, projects, and contact details. Use semantic HTML5 (<header>, <nav>, <main>, <footer>), and link all pages with a consistent navigation bar. All pages must validate and be visually cohesive (same font, color scheme, spacing). Pages to Include index.html – Homepage • Header: “Hey, I’m Sphoorthi” • Subheader: “Masters in Information Systems student at Kelley School of Business” • Buttons: [Resume] (link to /Resume.pdf) and “Open to Opportunities” (styled green badge). • Short paragraph introducing her interests (“Hey there! I’m Sphoorthi Malladad, a graduate student in Information Systems at Kelley School of Business - IUB. I’m passionate about using technology to solve real-world problems and bridge the gap between business needs and smart, scalable solutions. My interests lie at the intersection of data, systems design, and technology strategy - and I’m especially excited by work that blends analytical thinking with real impact.”). • Include a circular profile photo (in /images/), alt text = “Sphoorthi smiling”. • Navigation bar links: About Me | Resume | Projects | Contact. • Footer: “© 2025 Sphoorthi Malladad – All rights reserved.” about.html – About Me • Biography (from the website text): “Hey there! I’m Sphoorthi Malladad, a graduate student in Information Systems at Kelley School of Business - IUB. I’m passionate about using technology to solve real-world problems and bridge the gap between business needs and smart, scalable solutions. My interests lie at the intersection of data, systems design, and technology strategy - and I’m especially excited by work that blends analytical thinking with real impact.” • Add a section “Outside the Classroom” with her personal interests (Outside the classroom and work, you’ll probably find me chasing sunsets, curating my phone’s 10,000th photo album, or hunting down the best dessert spot in town (life’s too short to skip the last course!). Whether it’s exploring a new city, capturing the perfect golden hour shot, or just unwinding with some good food and better company - I’m all about finding little joys along the way. Thanks for stopping by - feel free to check out my work or just say hi!). • Include a photo carousel or gallery (/images/about1.jpg, about2.jpg). resume.html – Resume • Present key details from Resume.pdf as formatted HTML: o Education (Indiana University MSIS – Dec 2026; Dayananda Sagar College – June 2023). o Experience (Oracle Financial Services Software, Hindustan Aeronautics Limited, Dheerya Foundation). o Academic Projects (LoRaWAN Smart Sewage System, Biometric Voting System). o Skills (SQL, Python, Java, C++, HTML, Tableau, Excel, Oracle Flexcube). • Embed a link to open Resume.pdf. projects.html – Projects • Include at least two projects with short descriptions and images: o “LoRaWAN-Based Smart Sewage Infrastructure System” - Collaborated with a four-member team to engineer a LoRaWAN-based sensor network for real-time sewage-level detection, reducing device power use by 25% and extending wireless range by 50% - Integrated cloud analytics pipeline and SQL database to enable predictive alerts and cut system downtime by 80%. Recognized at technical symposiums for scalable, data-driven solutions in urban sanitation infrastructure o “EY Case Competition - Digital Transformation Strategy (3rd Place)” - Collaborated with a team of four to design a strategic digital transformation roadmap, integrating executive insights, market research, and industry best practices to drive innovation and scalability - Presented a consulting deck and functional prototype to EY leadership, placing top 3 among 100+ graduate students • Each project card should have title, description, tech stack, and link to GitHub repo (if available). contact.html – Contact Page • Heading: “Let’s Connect! Feel free to reach out on LinkedIn or explore my work.” • Provide: o Email → mailto: smallada@iu.edu o LinkedIn → https://www.linkedin.com/in/sphoorthi-s-malladad o GitHub → https://github.com/sphoorthimalladad • Add a contact form with: o First Name (required) o Last Name (required) o Email (required, type=email) o Password (required, minlength=8) o Confirm Password (required, pattern matches Password) • On submit, redirect to thankyou.html page saying “Thanks for getting in touch!” • All inputs must have labels and IDs for accessibility. thankyou.html • Simple confirmation page after form submission. Styling (styles.css) • Fonts: Inter or Poppins (sans-serif). • Color palette: White background | #1E1E1E text | Accent #3B82F6 (blue) + #A7F3D0 (light green). • Consistent navbar on top (fixed) with hover effects. • Use flexbox or grid for responsive layout. • Apply rounded borders and subtle shadow effects for images and cards. Accessibility & Validation • Add alt text to all images. • Ensure keyboard navigability and semantic headings. • Validate HTML and CSS using W3C validators.

AI Output:
Copilot generated the entire directory structure with HTML and CSS files (index.html, about.html, resume.html, projects.html, contact.html, thankyou.html, styles.css). It created responsive layouts, consistent navigation, and semantic HTML5 structure. The initial build matched most assignment requirements including styling and accessibility.

Action:
✅ Accepted with minor edits. Adjusted text content, added my real resume, images, and personalized introduction paragraphs.

Prompt 2 — Fix Resume Link (404 Error)

Prompt:

When I click on “View Resume” on the Resume page, I’m getting a 404 error: File not found.

AI Output:
Copilot located the incorrect path (images/Malladad_Sphoorthi_Resume_Tech.pdf) and corrected it to the proper root-level path (Resume.pdf). Verified that the resume link worked from both the homepage and resume page.

Action:
✅ Accepted as-is. The fix resolved the issue immediately; no additional changes were needed.

Prompt 3 — Add Profile Image to Homepage

Prompt:

Now I want to add this image on my homepage inside that circle above "Hey, I'm Sphoorthi". Path: /images/Headshot_iu.jpeg.

AI Output:
Copilot confirmed the image existed in /images/, updated index.html to reference it, and ensured proper styling (circular shape, border-radius, alt text for accessibility). It verified that the image loaded correctly when the local server was refreshed.

Action:
✅ Accepted. The result was clean and visually aligned with the design.

Prompt 4 — Fix About Me and Projects Page Layout

Prompt:

Fix layout issues: (1) Add extra spacing before “Outside the Classroom” on the About Me page; (2) Remove the last project card “Personal Portfolio Website.”

AI Output:
Copilot inserted an extra <br> for better visual spacing in about.html and removed the final project section from projects.html. It verified both changes and confirmed the grid layout adjusted automatically for three projects.

Action:
✅ Accepted and slightly modified. I manually reviewed the About Me section spacing and fine-tuned the CSS margins for visual balance.

---

## Reflection on AI Assistance

Using Copilot made developing my personal website faster, cleaner, and far more efficient. It helped me generate the full site scaffold—including navigation, responsive layout, and accessibility features—within minutes. Fixing errors like the broken resume link and adjusting layout spacing became intuitive since Copilot quickly located and corrected issues I might have missed manually. These time savings allowed me to focus more on design polish and content writing rather than syntax.

However, Copilot sometimes made incorrect assumptions about file paths and redundant CSS styling. I learned to verify every change, previewing results in the browser and correcting where necessary. I maintained creative control over content and style while using AI mainly for boilerplate generation and error diagnosis. This balance between automation and human review resulted in a professional, well-structured portfolio that reflects both my technical precision and personal voice. 


