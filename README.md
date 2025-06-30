# Personal Website – M Firdan Ardiansyah

This is the repository for my personal portfolio website built using **HTML, CSS, and JavaScript**. The website presents my **skills, experience, education**, and **notable projects**, and includes an integrated **contact form** that sends messages via email.

---

## 🌐 Live Website

[https://lucyy28.github.io/My-Web-1/] (Klik This To See 👀)

---

## 🛠️ Technologies Used

- HTML5  
- CSS3  
- JavaScript  
- Font Awesome (for icons)  
- Formspree (for contact form email handling)  

---

## 📁 Website Structure

- `index.html` – Main page with all website sections  
- `style.css` – Contains all custom styles  
- `script.js` – Adds interactivity (menu toggle, animation, etc.)  
- `images/` – Folder containing images and icons used in the site  

---

## 📌 Sections Overview

1. **Home**  
   Contains the navigation bar, introduction text, animated typing effect, and hero image.  
2. **About**  
   Short bio, personal info, and social media links.  
3. **Skills**  
   Lists my competencies, including web development and data analytics.  
4. **CTA (Call to Action)**  
   A section that invites users to contact or hire me.  
5. **Education**  
   Displays my background at SMKN 1 Cianjur with the Teaching Factory program.  
6. **Experience**  
   Shows professional or project-based experience visually.  
7. **Projects**  
   Highlights projects such as:  
   - Hand Scanner & Cursor Controller (Python)  
   - UI/UX Designer Showcase (PowerPoint & Figma)  
   - QR Code & Image Processing App (Python with OpenCV)  
8. **Contact**  
   Contact form powered by Formspree, plus email, phone, and location details.  

---

## 📩 Contact Form Setup (Formspree)

To receive messages via email:

1. Go to [https://formspree.io](https://formspree.io) and create an account.  
2. Create a new form and copy the generated form ID (e.g. `mvgrlzgz`).  
3. Update your form in `index.html` like this:

```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
