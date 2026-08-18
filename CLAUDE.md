# CLAUDE.md — pedrohds1/pedrohds1

## Overview

This is Pedro Henrique's **GitHub profile README repository**. A repo named after the GitHub username displays its `README.md` on the user's profile page.

## Repository Structure

```
pedrohds1/
└── README.md    # Profile page content (Markdown + inline HTML)
```

There is only one file. No dependencies, no build tools, no CI/CD.

## Content & Conventions

- **Language**: Portuguese (pt-BR)
- **Format**: Mix of Markdown and inline HTML (`<div>`, `<img>`, `<a>` tags)
- **Icons**: Technology icons use SVG from the devicons CDN (`raw.githubusercontent.com/devicons/devicon/master/icons/`)
- **Text badges**: Technologies without a devicon (ADVPL, TL++/TLPP, TOTVS Protheus, SmartView/TReports, PO UI, IA) use `shields.io` badges in `style=for-the-badge`
- **No social links**: The profile intentionally exposes no social networks or e-mail
- **Positioning**: Tech Lead Protheus + Fullstack Developer + AI applied to development
- **Sections**: Protheus & ERP → IA & Automação → Linguagens & Stack
- **Technologies listed**: ADVPL, TL++ (TLPP), JavaScript, TypeScript, Python, Node.js, React, SQL Server, PostgreSQL, HTML5, CSS3, C#, Git

## Guidelines for AI Assistants

- Keep the README in **Portuguese (pt-BR)**.
- Maintain the existing HTML + Markdown style. Do not convert inline HTML to pure Markdown.
- When adding technology icons, follow the existing pattern: `<img align="center" alt="peeh-{Name}" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/{tech}/{tech}-{variant}.svg">`.
- Use `shields.io` for technologies with no devicon; keep `style=for-the-badge` and URL-encode special characters (`%2B` for `+`, `%2F` for `/`, `%26` for `&`).
- Do **not** re-add social network or e-mail badges — they were removed on purpose.
- Verify every image URL returns HTTP 200 before committing; a broken icon is visible on the public profile.
- This repo has no tests, linters, or CI — changes are purely cosmetic/content.
