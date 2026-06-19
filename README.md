# Zoom In

<svg xmlns="http://www.w3.org/2000/svg" width="800" height="300" viewBox="0 0 800 300">
  <style>
    .name { animation: nameIn 7s ease-out infinite; }
    .underline { animation: underlineDraw 7s ease-out infinite; transform-origin: left center; }
    .meta { animation: fadeUp 7s ease-out infinite; animation-delay: 0.3s; }
    .corner { animation: cornerSlide 7s ease-out infinite; }

    @keyframes nameIn {
      0%, 4% { opacity: 0; transform: translateY(8px); }
      14%, 90% { opacity: 1; transform: translateY(0); }
      100% { opacity: 0; transform: translateY(0); }
    }
    @keyframes underlineDraw {
      0%, 14% { transform: scaleX(0); }
      24%, 88% { transform: scaleX(1); }
      100% { transform: scaleX(1); }
    }
    @keyframes fadeUp {
      0%, 22% { opacity: 0; transform: translateY(6px); }
      32%, 90% { opacity: 1; transform: translateY(0); }
      100% { opacity: 0; transform: translateY(0); }
    }
    @keyframes cornerSlide {
      0%, 8% { opacity: 0; transform: translateX(-8px); }
      18%, 90% { opacity: 1; transform: translateX(0); }
      100% { opacity: 0; transform: translateX(0); }
    }
  </style>
  <defs>
    <linearGradient id="hdr-bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0d0d10"/>
      <stop offset="100%" stop-color="#0d0d10" stop-opacity="0.85"/>
    </linearGradient>
  </defs>
  <rect width="100%" height="100%" fill="url(#hdr-bg)" rx="14" ry="14"/>

  <!-- Corner decorations: outer <g> = position, inner <g> = animation -->
  <g class="corner" opacity="0.6">
    <rect x="40" y="42" width="22" height="2" fill="#dc2626" />
    <rect x="40" y="42" width="2" height="22" fill="#dc2626" />
  </g>
  <g transform="translate(800 0) scale(-1 1)">
    <g class="corner" opacity="0.6">
      <rect x="40" y="42" width="22" height="2" fill="#dc2626" />
      <rect x="40" y="42" width="2" height="22" fill="#dc2626" />
    </g>
  </g>

  <!-- Name -->
  <text class="name" x="400" y="138" text-anchor="middle" fill="#f7f7fb" font-family='"Inter", system-ui, sans-serif' font-size="56" font-weight="700" letter-spacing="-1.5">ZoomIn</text>

  <!-- Accent underline -->
  <rect class="underline" x="316" y="164" width="168" height="2" fill="#dc2626" rx="1"/>

  <!-- Meta line -->
  <text class="meta" x="400" y="200" text-anchor="middle" fill="#a5a5b3" font-family="ui-monospace, monospace" font-size="13" letter-spacing="2">MARKETING COMPANY   ·   EGYPT</text>
</svg>


### Marketing Agency

We help businesses grow through strategic content, creative execution, and data-driven marketing, with a strong focus on long-term client relationships.

---

## About Zoom In

Zoom In is a professional marketing agency that takes businesses from zero digital presence to measurable growth. We combine strategy, creativity, and analytics into one seamless workflow — from the moment a lead walks in, to contract renewal.

We work with:
* Small and medium business owners
* Restaurant and café owners
* Startup founders
* Brands looking to strengthen their digital presence
* Business owners who want to grow sales through social media

---

## What We Do

| Service | Description |
|---|---|
| **Social Media Management** | Strategy, content calendar, posting, and growth |
| **Paid Advertising** | Ad campaign creation, management, and optimization |
| **Content Creation** | Copywriting, video production, graphic design |
| **Data Analysis** | Market research, competitor analysis, SWOT, reporting |
| **Marketing Strategy** | Full strategic planning tailored to your goals |
| **Web Development** | Websites, e-commerce stores, landing pages |

---

## Client Journey — End to End

Every client goes through a structured, step-by-step process:

```
Lead Generation -> Qualification -> Client Brief -> CRM Setup
-> Data Analysis -> Strategy -> Creative Planning -> Proposal
-> Contract & Payment -> Execution -> Review -> Publishing
-> Performance Tracking
```

---

## Core Capabilities

### Strategy & Planning
* Marketing Strategy
* Data Analysis (SWOT, Competitor, Market Research)

### Sales & Client Management
* Sales & Lead Generation
* CRM & Account Management
* Business Proposal Writing

### Content & Creative
* Content Creation (copywriting, scripts)
* Graphic Design
* Video Production & Editing
* Creative Direction

### Marketing Execution
* Social Media Management
* Paid Advertising & Media Buying
* Campaign Management

### Technical & Operations
* Web Development
* E-commerce & Landing Pages
* Project Management
* Finance & Accounting

---



## GitHub Analytics

![Zoomin's GitHub stats](https://github-readme-stats.vercel.app/api?username=ZoomIn-dev&show_icons=true&theme=vision-friendly-dark)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ZoomIn-dev&layout=compact&theme=vision-friendly-dark)

---

## Connect With Us

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Zoom_In_Development-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-Zoom_In-FF5722?style=for-the-badge&logo=google-chrome)](https://zoomindevelopment.netlify.app/)
