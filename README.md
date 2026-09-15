GEB'S PROJECT

Personal portfolio website of Bagas Haidar — a Cyber Security student, web developer, and creative builder.

This website is designed as a simple but polished personal space to showcase projects, skills, experience, and contact information with a modern dark + red visual identity.

About

GEB'S PROJECT is my personal portfolio and project showcase.

The website represents the combination of:

Web Development

Cyber Security

UI / Visual Design

Creative Technology

Video Editing

Personal Projects

The goal is to keep the website clean, fast, responsive, and easy to maintain without using unnecessary frameworks.

Tech Stack

This project intentionally keeps things simple:

HTML5

CSS3

Vanilla JavaScript

Vercel for deployment

No framework.
No build process.
No heavy dependencies.

Everything can run directly from a single index.html file.

Features

Modern dark-red interface

Fully responsive layout

Mobile, tablet, laptop, and desktop support

Smooth scrolling

Scroll reveal animations

Interactive project cards

Subtle hover effects

Lightweight animations

About section

Skills section

Projects showcase

Experience / journey section

Contact section

Basic SEO structure

Website Sections

Hero

Introduction, personal branding, and main call-to-action.

About

Short introduction about me, my background, and current focus.

Skills

A quick overview of my technical and creative skills.

Projects

Selected projects in web development, internal tools, creative work, and cyber security.

Experience

A simplified timeline of work, learning, and practical experience.

Contact

Ways to connect for freelance projects, collaboration, or other opportunities.

Project Structure

gebproject/
│
├── index.html
└── README.md

The CSS and JavaScript can be placed directly inside index.html so the entire website stays easy to move, edit, and deploy.

Run Locally

You can open the project directly in your browser.

open index.html

Or use a simple local server:

python3 -m http.server 8000

Then open:

http://localhost:8000

Deploy to Vercel

This project is designed to work easily with Vercel.

Option 1 — Vercel Upload

Upload the project folder directly to Vercel.

Option 2 — GitHub + Vercel

Push the project to GitHub:

git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin YOUR_REPOSITORY_URL
git push -u origin main

Then connect the repository to Vercel.

Every new push will automatically update the live website.

Customization

Most of the website can be customized directly inside index.html.

Things you may want to update:

Name / branding

About text

Project descriptions

Skills

Email

Instagram

LinkedIn

GitHub

Project links

Domain

Accent color

The main color values can be stored using CSS variables:

:root {
  --bg: #080808;
  --card: #121212;
  --text: #f5f5f5;
  --muted: #a5a5a5;
  --red: #ff2a2a;
}

This makes it easy to change the visual identity later.

Design Direction

The website uses a visual style that combines:

Code + Security + Design

The goal is to avoid both extremes:

not an overly decorative designer portfolio

not a plain programmer portfolio with no visual identity

Instead, the site aims to feel:

Modern

Clean

Technical

Creative

Professional

Simple

Smooth

Contact

Bagas Haidar

Cyber Security Student · Web Developer · Creative Builder

Email: your@email.com

GitHub: your-github

LinkedIn: your-linkedin

Instagram: your-instagram

Replace the placeholders above with the real links used on the website.

GEB'S PROJECT

Built by Bagas Haidar.

Code. Security. Design.
