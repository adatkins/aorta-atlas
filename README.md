# Aorta Atlas

Aorta Atlas is a clinician-facing web application for structured aortic guideline decision support. It is designed to replace older single-purpose calculator workflows with a modern interface that captures one patient profile, derives indexed measurements, and presents both American and European aortic guidance pathways from the same set of clinical inputs. [file:16][file:17][file:1]

## Project purpose

The project is intended to make aortic decision support easier to use, easier to maintain, and easier to expand over time. The current prototype focuses on a clean web-based workflow that can later evolve into a packaged mobile app or a more complete clinical platform. [file:1][page:2]

## Core idea

Instead of forcing a clinician to enter the same patient data multiple times or manually compare separate references, Aorta Atlas uses a single intake model for demographics, phenotype, measurements, and risk modifiers, then renders both ACC/AHA and EACTS/STS style outputs from that shared dataset. [file:16][file:17][file:1]

## Current features

- Responsive web app layout designed for desktop and mobile review. [file:1]
- Unified patient intake for phenotype, risk factors, pregnancy context, and measurement-driven decision support. [file:1][file:16][file:17]
- Dual recommendation panels for American and European guideline outputs. [file:1][file:16][file:17]
- Derived calculations including body surface area, Turner aortic size index, and area-to-height style indexing. [file:1][file:16]
- Metric and imperial data-entry toggles for common anthropometric and aortic measurements. [file:1]
- Branding and UI refinements for the Aorta Atlas product identity. [file:1]

## Clinical scope

The prototype currently emphasizes proximal aortic disease and selected high-yield guideline branches, including sporadic root and ascending aneurysm pathways, Marfan syndrome, Loeys-Dietz syndrome variants, bicuspid aortic valve aortopathy, Turner syndrome, nonsyndromic heritable thoracic aortic disease examples, pregnancy planning context, and AAA screening entry points. [file:16][file:17][file:1]

## Short-term goals

- Create a cleaner and more intuitive clinician workflow than legacy aortic calculator tools. [file:1]
- Support one-time data entry with dual guideline outputs instead of duplicate comparison workflows. [file:16][file:17][file:1]
- Expand rule coverage so the interface more fully reflects the uploaded guideline documents. [file:16][file:17]
- Improve onboarding and deployment simplicity through a static web architecture that is easy to host on GitHub Pages. [page:2][web:36]

## Longer-term goals

- Build a more complete rule engine that covers a larger portion of the uploaded guideline PDFs, including surveillance pathways, broader genotype-specific thresholds, imaging pathways, and pregnancy-related recommendations. [file:16][file:17]
- Transition the project from a static prototype into a more production-ready clinical decision support product. [file:1]
- Prepare the app to be packaged later as a mobile app using a web-first architecture. [page:2]
- Add export, print, and clinician-summary workflows for easier real-world use. [file:1]

## Technical approach

The app is currently built as a static HTML web application with embedded styling and client-side JavaScript logic. That makes it simple to upload, version, and publish through GitHub Pages, while also providing a foundation that can later be wrapped or migrated into a more app-like deployment model if needed. [file:1][page:2][web:36]

## Repository structure

A simple project structure is recommended:

- `index.html` — the main application file used by GitHub Pages. [web:36][file:1]
- `aorta-atlas-logo.png` — the uploaded logo asset used in the sidebar branding. [generated_image:98][file:1]
- `README.md` — this project overview and roadmap document. [file:1]

## How to update the live site

For a GitHub Pages deployment, the usual update flow is:

1. Replace `index.html` with the latest version of the app. [page:2][web:36]
2. Upload any updated assets such as the logo image file. [page:2][generated_image:98]
3. Commit the changes to the `main` branch. [page:1][page:2]
4. Wait for GitHub Pages to republish the site automatically. [web:36]

## Project philosophy

Aorta Atlas is meant to be clinically serious, visually calm, and easier to use than older legacy tools. The goal is not just to build another calculator, but to create a better interface for structured aortic decision support that can grow with the project over time. [file:1][file:16][file:17]

## Important note

This project is intended for clinician-directed decision support and product development purposes. It should not replace direct review of the underlying guidelines, specialist judgment, or institutional policy. [file:16][file:17][file:1]
