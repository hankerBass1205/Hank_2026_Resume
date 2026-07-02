# Resume & Portfolio Website Improvement Analysis

This document outlines potential areas for future upgrades, missing information, and suggestions for optimizing the resume website to increase its impact on recruiters and hiring managers.

## 1. Resume Content Improvements (PDF & Website)
*   **Quantify Achievements:** Currently, the experience descriptions focus on *what* was done (e.g., "部署於 AWS EC2..."). Try adding metrics to highlight the *impact*. For example: "降低了 XX% 的伺服器成本" 或 "提升了 XX% 的系統可用性".
*   **LinkedIn Link:** The resume PDF and the website are missing a LinkedIn profile link. A professional LinkedIn profile is crucial for networking and is highly expected by recruiters.
*   **Highlight Soft Skills:** While technical skills are excellent, explicitly mentioning soft skills (e.g., Cross-functional collaboration, Agile/Scrum, Problem-solving) can be beneficial.

## 2. Website Future Upgrades
*   **Custom Domain:** Purchasing a custom domain (e.g., `hankerlin.dev`) and linking it to GitHub Pages adds a significant touch of professionalism.
*   **Language Toggle (i18n):** Adding an English/Traditional Chinese toggle would allow you to target both local and international opportunities.
*   **Blog/Article Section:** A section where you share technical articles or documentation from your AWS/Network studies can demonstrate deep understanding and passion.

## 3. Recommended Visual Additions
*   **Real Project Images:** Replace the `placehold.co` images with actual screenshots of your projects (e.g., the AWS Architecture diagram, the Camping Platform UI, or the Cisco Lab topology). Place these images in the `images/` folder and link them in `index.html`.
*   **Professional Headshot:** Replace the Hero placeholder with a clean, well-lit, professional headshot. This builds trust and personal connection.
*   **Project Demo Links:** For projects like the Camping Platform or Chord Helper, providing direct links to the live hosted applications would be much stronger than just GitHub repo links.

## 4. Animation & Interaction Enhancements
*   **Typing Effect in Hero:** The Hero subtitle ("網路工程師 / Network Engineer") could use a typing animation to draw immediate attention upon loading.
*   **Skill Bars / Radar Chart:** Instead of just listing skills, using a radar chart or animated progress bars for proficiency levels could make the Skills section more dynamic and easily scannable.
*   **Page Transitions:** Currently, scrolling is smooth, but adding a page transition library (if migrating to a framework later) or using the View Transitions API could make navigation feel like a native app.
*   **Scroll Animations:** While fade-ins are currently implemented, adding subtle parallax effects to background elements could increase depth.
