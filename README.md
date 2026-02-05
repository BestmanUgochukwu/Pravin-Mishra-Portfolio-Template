# DMI Portfolio Website (Static HTML/CSS)

This repository contains a clean, professional-looking **static portfolio website** used in **DevOps Micro Internship (DMI)** Week 1 to practice:
- Linux basics
- Nginx hosting
- Deployment proof / ownership
- Production-style checks

✅ Students deploy this website on an Ubuntu VM using Nginx and keep it live for 24 hours.

---

## Who is this for?
- DMI students (beginner → intermediate)
- Anyone learning how to host a static site with Nginx on Linux

---

## What you will build
A portfolio-style website hosted on:
- **Ubuntu VM**
- **Nginx**
- Accessible via: `http://<public-ip>`

---

## Mandatory Ownership Proof (DMI Rule)
Before you deploy, you MUST edit the footer and add your details:

Original:

```html
<p>Crafted with <span>cloud</span> excellence by Pravin Mishra</p>
```

Add this line (example):

```html
<p>## Footer Requirement
The footer must display:
- Portfolio version
- Deploy date
- Author

## Date Generation
The deploy date is generated dynamically using JavaScript in **DD Mon YYYY** format.

### Code Snippet
<footer>
  © Pravin Mishra Portfolio v1.0 — Deployed on <span id="deployDate"></span> — By Bestman Ugochukwu Afokwalam
</footer>

<script>
  const options = { day: '2-digit', month: 'short', year: 'numeric' };
  document.getElementById("deployDate").textContent =
    new Date().toLocaleDateString('en-GB', options);
</script>
```

✅ This proof must be visible in your browser screenshot submission.
