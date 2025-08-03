
---

### 📘 Project Overview

This project is a **personal portfolio website** for Luka Jessel Gichuru, a Kenyan web developer with a multidisciplinary background in counseling psychology, customer support, and business administration. The website is designed to showcase Luka’s professional profile, including his skills, educational background, projects, and personal interests. It is built using **HTML5**, **CSS3**, **Bootstrap 5**, and **Font Awesome**, with some basic JavaScript powered by jQuery for interactivity. The design is fully responsive and mobile-friendly, ensuring a good experience on all screen sizes.

The homepage includes a **navigation bar** that links to different sections of the single-page layout, including Hero, About Me, Education, Interests, Skills, Projects, and Contact. The **Hero section** prominently displays Luka’s name and personal tagline, while the **About Me section** provides an overview of his journey into web development. The **Education section** presents his academic history using a clean, readable layout. The **Interests section** articulates his motivation for combining technology with human-centered design, drawing on his psychology background. The **Skills section** lists programming languages and tools Luka is proficient in, such as HTML, CSS, JavaScript, PHP, SQL, and WordPress. In the **Projects section**, screenshots and descriptions of example work are displayed, each with a placeholder link to learn more. The **Contact section** provides Luka’s email, phone number, and website, and the **footer** includes a copyright.

The website is suitable for a professional portfolio, especially for job-seeking developers, freelancers, or anyone building a brand as a digital creator. While functional, improvements could include adding form functionality to the contact section, refining SEO metadata, improving accessibility, and connecting the project section to live links or repositories.

---

### 💬 Code Walkthrough (Explained as a Guide)

The HTML document starts with a standard `<!DOCTYPE html>` declaration to specify HTML5, followed by conditional comments to handle old versions of Internet Explorer—though this technique is outdated and mostly unnecessary for modern web projects.

In the `<head>` section, metadata is declared such as character encoding, browser compatibility, and viewport settings for responsive design. Stylesheets are loaded next, including Bootstrap for responsive layout, a custom CSS file for specific styling, and Font Awesome for iconography. jQuery is included before the closing `</head>` tag.

The body begins with a warning for users on very old browsers, prompting them to upgrade. Then comes the **navigation bar**, which is a fixed-top Bootstrap component. It contains a brand name on the left and several links on the right pointing to page sections like Home, About, Education, Interests, Skills, Projects, and Contact. Each link uses a hash to scroll smoothly to its corresponding section on the page.

Next is the **Hero section**, which centers Luka’s name and professional tagline, styled with Bootstrap’s utility classes for layout and typography. After that, the **About Me section** uses a two-column layout—one for an image of Luka and the other for a personal introduction with a button to download his CV in PDF format.

The **Education section** follows, which lists Luka’s academic qualifications, each in its own block with icons from Font Awesome to enhance visual appeal. The entries include institutions, dates attended, and the awarded credentials.

The **Interests section** is a centered block quote-style layout. It contains a paragraph summarizing Luka’s passion for combining human behavior and tech design, culminating in a human-centered approach to software development.

Then comes the **Skills section**, divided into six blocks for different technologies: HTML5, CSS3, JavaScript, PHP, SQL, and WordPress. Each skill is represented by a Font Awesome icon and a title, styled to appear visually consistent across devices.

The **Projects section** showcases thumbnails of Luka’s past projects. Each item includes a screenshot, a short description, and a placeholder link (currently `#`) to view more details. This grid layout uses Bootstrap columns to maintain responsiveness.

The **Contact section** displays Luka’s phone number, email address, and website, each with accompanying icons. These are placed in a three-column layout for balance.

At the bottom, the **footer** contains a simple copyright notice.

Scripts are loaded at the end of the body to ensure the page content loads first. These include the Bootstrap JavaScript bundle, which enables dynamic components like the navbar toggle.

---
