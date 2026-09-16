# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

delegated: static HTML + CSS + vanilla JS, no build step. GitHub Pages serves the repo root directly, and the Steply design system it derives from is already plain CSS variables + global classes, so no framework earns its weight here.

## Users

[INFERRED from the English resume, not confirmed] Technical recruiters and hiring tech leads, in Brazil and at remote international companies, screening a senior full stack engineer. They arrive from a LinkedIn profile, a job application, or a resume link, skim in under two minutes, and decide whether to open a conversation.

Secondary: the owner himself, using the component library to assemble and extend the portfolio pages.

## Product Purpose

Personal portfolio and resume site for Whenes Oliveira, Software Engineer | Full Stack, hosted on GitHub Pages at `whenes.github.io/github-pages-resume`. Success: a reviewer understands depth (10+ years, enterprise, legacy modernization) and reaches a contact action (email, LinkedIn, GitHub, resume download).

## Positioning

Not a generalist "full stack dev" page. The resume's distinct record is making old and new systems coexist safely: incremental modernization of an enterprise customer portal where Java EE/EJB coexisted with Spring Boot and NestJS behind feature-flag migration flows; Java 8→9 migration led end to end; a Ricoh printer frontend rebuilt in HTML/CSS2/jQuery when Angular could not run on the hardware; white-label multitenant app automation. Root-cause debugging over workarounds.

## Operating Context

- Reviewers read on desktop during screening and on phones between meetings.
- Hosted as static files on GitHub Pages; no server, no analytics decided.
- Owner is also building the Steply product line and its design system (`D:/steply/steply-sdd-harness-arch/STYLE_GUIDE.md`).

## Capabilities and Constraints

- Static only; any interactivity is client-side JS.
- Content language: resume source is English. [OPEN] Whether the site ships English only or PT-BR + EN.
- [OPEN] Contact form, analytics, custom domain.

## Brand Commitments

- Visual system derives from the Steply design system (user request, 2026-09-16): CSS variable tokens with the Steply names, 4px spacing scale, Inter, dark default with light override via `data-theme="light"`, blurple accent `#5865f2`, global semantic classes (`.btn`, `.card`, `.badge`, `.alert`).
- Personal name: Whenes Oliveira. Title as on resume: Software Engineer | Full Stack.

## Evidence on Hand

- Resume PDF: `D:/workspace/whenes_oliveira_software_engineer_resume.pdf` (authoritative for experience, dates, skills, education).
- GitHub: https://github.com/whenes — 84 public repos, mostly course/study repos (Full Cycle architecture: hexagonal, clean, monolith; Alura DDD/SOLID/TDD; School of Net). Shipped product: Placar Basquete (FIBA electronic scoreboard, Windows installer, CI releases, v0.1.0 on 2026-09-15; source repo private).
- LinkedIn: https://www.linkedin.com/in/whenes-oliveira-b9baa7189 (not machine-readable; login wall).
- Absent, never fabricate: testimonials, metrics beyond the resume (the 60% coverage target and "still in use ~5 years later" are the only quantified facts), client logos, certifications, profile photo, project screenshots.

## Product Principles

1. Evidence over adjectives: every claim traces to a line in the resume or a public repo.
2. Show the engineering, not the buzzwords: migrations, coexistence, root causes, tests.
3. Scannable in two minutes, deep on demand.
4. One design system, no page-local styling: the Steply rule "if the class exists, use it" applies.

## Accessibility & Inclusion

WCAG 2.2 AA contrast in both themes, full keyboard navigation, reduced-motion respected.
