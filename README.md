<p align="center">
  <img src="images/banner.svg" alt="Pratik Godase, Software Developer, Pune" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to-software%20developer%20roles-0c831f?style=for-the-badge" alt="Open to software developer roles">
  <img src="https://img.shields.io/badge/Based%20in-Pune%2C%20India-f8cb46?style=for-the-badge&labelColor=161616" alt="Based in Pune, India">
</p>

<h1 align="center">Hi, I’m Pratik. I build software end to end.</h1>

<p align="center">
  React and Angular up front. Spring Boot, .NET and Python behind it.<br>
  This repo is the source of my personal portfolio site.
</p>

<p align="center">
  <a href="https://pratikgodase07.github.io/Portfolio_Personal/"><b>🟡 View the site</b></a> &nbsp;·&nbsp;
  <a href="images/Pratik_Satish_Godase_Resume.pdf"><b>🟢 Résumé</b></a> &nbsp;·&nbsp;
  <a href="mailto:pratikgodasecse07@gmail.com"><b>✉️ Email me</b></a>
</p>

---

## 🟢 Tech stack

<table>
<tr>
<td width="50%" valign="top">

### Frontend
<img src="https://img.shields.io/badge/React%2018-161616?style=for-the-badge&logo=react&logoColor=f8cb46">
<img src="https://img.shields.io/badge/JavaScript-161616?style=for-the-badge&logo=javascript&logoColor=f8cb46">
<img src="https://img.shields.io/badge/Angular-161616?style=for-the-badge&logo=angular&logoColor=f8cb46">
<img src="https://img.shields.io/badge/Vite-161616?style=for-the-badge&logo=vite&logoColor=f8cb46">

</td>
<td width="50%" valign="top">

### Backend
<img src="https://img.shields.io/badge/.NET%20Web%20API-161616?style=for-the-badge&logo=dotnet&logoColor=f8cb46">
<img src="https://img.shields.io/badge/Spring%20Boot-161616?style=for-the-badge&logo=springboot&logoColor=f8cb46">
<img src="https://img.shields.io/badge/Java-161616?style=for-the-badge&logo=openjdk&logoColor=f8cb46">
<img src="https://img.shields.io/badge/Flask-161616?style=for-the-badge&logo=flask&logoColor=f8cb46">

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Databases
<img src="https://img.shields.io/badge/SQLite-161616?style=for-the-badge&logo=sqlite&logoColor=f8cb46">
<img src="https://img.shields.io/badge/MySQL-161616?style=for-the-badge&logo=mysql&logoColor=f8cb46">
<img src="https://img.shields.io/badge/Entity%20Framework%20Core-161616?style=for-the-badge&logoColor=f8cb46">
<img src="https://img.shields.io/badge/Hibernate-161616?style=for-the-badge&logo=hibernate&logoColor=f8cb46">

</td>
<td width="50%" valign="top">

### Python & ML
<img src="https://img.shields.io/badge/Python-161616?style=for-the-badge&logo=python&logoColor=f8cb46">
<img src="https://img.shields.io/badge/OpenCV-161616?style=for-the-badge&logo=opencv&logoColor=f8cb46">
<img src="https://img.shields.io/badge/CNN-161616?style=for-the-badge&logoColor=f8cb46">

</td>
</tr>
</table>

---

## 🟡 Featured projects

| # | Project | What it is | Built with |
|:-:|---|---|---|
| **01** | **Shreepad Goshala** | E-commerce storefront for an A2 Gir cow sanctuary in Pandharpur | React, Vite |
| **02** | **Two Brothers India Farms** | A calm, product-led homepage for a farm brand | React, Vite |
| **03** | **Inventory Analyser** | Stock tracking, reorder alerts, supplier metrics and reporting | Java, Spring Boot, Angular |
| **04** | **Deepfake Detection** | Flags manipulated faces with a custom CNN pipeline, with batch scanning | Python, Flask, CNN |
| **05** | **Sign Language AI** | Real-time hand gestures turned into text and speech | Python, OpenCV |
| **06** | **Billing Software** | Invoicing with automated tax calculation and print-ready bills | Python |

---

## 🟢 My path so far

| When | What |
|---|---|
| **Feb – Sep 2025** | **Full Stack Java Developer**, Kiran Academy, Pune. Full-stack applications with Java and modern frameworks. |
| **2024** | **Python & Web Dev Intern**, Rudra Infotech, Solapur. Python backend logic, web utilities, bug fixes. |
| **3 months** | **Frontend / SQL Intern**, Softech Coders, Pandharpur. Responsive UIs and SQL optimisation for dashboards. |
| **2022 – 2024** | **Event lead & treasurer**, college activities. Led hackathon committees and managed budgets. |
| **2021 – 2025** | **B.Tech, Computer Science**, SVERI COE, Pandharpur. |

---

## 🟡 About this site

A single-page portfolio in plain HTML, CSS and JavaScript. No framework, no build step.

- Bold, friendly design in a yellow and green palette, set in Plus Jakarta Sans
- Scroll animations: progress bar, word-by-word text highlight, count-up stats and a timeline that fills as you scroll
- Project carousel with tech filters
- Content rendered from one JavaScript object, so editing is easy
- Responsive, keyboard-friendly, and respects reduced-motion settings

<details>
<summary><b>Run it locally</b></summary>

<br>

Open `index.html` in a browser. Or use a local server:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

</details>

<details>
<summary><b>Edit the content</b></summary>

<br>

Everything lives in the `D` object at the top of the `<script>` block in `index.html`:

```js
P: [{
  n: "Project name",
  y: "Short type label",
  d: "One-line description.",
  s: ["React", "Vite"],
  l: { demo: "https://example.com", code: "https://github.com/user/repo" }
}]
```

Demo and Code buttons appear on a card only when its `l` object is filled in. Colours are set in the `:root` block of the stylesheet (`--y` yellow, `--g` green).

</details>

<details>
<summary><b>Deploy on GitHub Pages</b></summary>

<br>

1. Push the repo to GitHub.
2. Open **Settings → Pages**.
3. Choose **Deploy from a branch**, select `main` and `/ (root)`, then save.

The site goes live at `https://pratikgodase07.github.io/Portfolio_Personal/`.

</details>

<details>
<summary><b>Project structure</b></summary>

<br>

```
Portfolio_Personal/
├── index.html
├── README.md
└── images/
    ├── banner.svg
    ├── Pratik_Godase_Profile_Picture.jpg
    └── Pratik_Satish_Godase_Resume.pdf
```

</details>

---

## 🟢 Let’s build something together

<p>
  <a href="mailto:pratikgodasecse07@gmail.com"><img src="https://img.shields.io/badge/Email-pratikgodasecse07%40gmail.com-f8cb46?style=for-the-badge&logo=gmail&logoColor=161616&labelColor=f8cb46&color=161616" alt="Email"></a>
  <a href="https://www.linkedin.com/in/pratik-godase-cse/"><img src="https://img.shields.io/badge/LinkedIn-pratik--godase--cse-0c831f?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/pratikgodase07"><img src="https://img.shields.io/badge/GitHub-pratikgodase07-161616?style=for-the-badge&logo=github&logoColor=f8cb46" alt="GitHub"></a>
</p>

Open to full-time roles and freelance work, in Pune or Bengaluru.

<sub>© Pratik Godase. All rights reserved. Please don’t copy the personal content, photo or résumé. If you’d like to reuse the layout, get in touch first.</sub>
