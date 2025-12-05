# 📊 ComparisonSphere-Data-Visualization-Web-Component

[![Build Status](https://img.shields.io/github/actions/workflow/status/chirag127/Comparisons-HTML-Data-Visualization-Component/ci.yml?style=flat-square&label=build)](https://github.com/chirag127/Comparisons-HTML-Data-Visualization-Component/actions/workflows/ci.yml)
[![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/Comparisons-HTML-Data-Visualization-Component?style=flat-square&token=...)](https://codecov.io/gh/chirag127/Comparisons-HTML-Data-Visualization-Component)
[![Language](https://img.shields.io/github/languages/top/chirag127/Comparisons-HTML-Data-Visualization-Component?style=flat-square&color=blue)](https://github.com/chirag127/Comparisons-HTML-Data-Visualization-Component)
[![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-blue.svg?style=flat-square)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/Comparisons-HTML-Data-Visualization-Component?style=flat-square)](https://github.com/chirag127/Comparisons-HTML-Data-Visualization-Component)

**⭐ Star this Repo if you find it useful!**

---

## Overview

**ComparisonSphere** is a highly optimized, zero-dependency HTML Web Component engineered for rapid, in-browser visualization and side-by-side comparison of structured data sets. It abstracts complex DOM manipulation into a single, declarative `<comparison-sphere>` tag, ensuring immediate integration into any modern or legacy frontend environment.

This component prioritizes rendering performance and accessibility, adhering to strict W3C Web Component standards.

## 🏗️ Architecture Blueprint

The component adheres to a strict **Component-First Architecture**, isolating its rendering logic from the host application and relying solely on the native Web Components API for encapsulation.

text
Comparisons-HTML-Data-Visualization-Component/
├── index.html           # Demo/Integration entry point
├── src/
│   └── ComparisonSphere.js  # Core Web Component Class (ES Module)
├── assets/
└── README.md


## 📚 Technical Specification

| Specification | Detail |
| :--- | :--- |
| **Primary Technology** | Vanilla JavaScript / Custom Elements API |
| **Styling** | Shadow DOM Encapsulation (Standard CSS) |
| **Data Input** | JSON object passed via `data-sets` attribute or property setter. |
| **Compatibility** | Modern browsers (Chrome, Firefox, Safari, Edge). |
| **Standards** | DRY, SOLID (Dependency Inversion Principle for data input). |

## 🤖 AI Agent Directives

<details>
<summary>Apex Agent Configuration & Verification Protocol (December 2025)</summary>

# SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

## 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

---

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type and apply the corresponding **Apex Toolchain**. This repository, `Comparisons-HTML-Data-Visualization-Component`, is a **Frontend Component** project.

*   **PRIMARY SCENARIO A: WEB / APP / GUI (Modern Frontend)**
    *   **Stack:** **TypeScript (Strict)**, **Vite 7** (Build Tool), **TailwindCSS v4** (Design Utility), **Playwright** (E2E Testing).
    *   **Lint/Test:** **Biome** (Speed for Formatting/Linting) + **Vitest** (Unit Testing).
    *   **Architecture:** Feature-Sliced Design (FSD) principles applied internally for module separation, even in a single JS file context.

## 4. DEVELOPMENT & VERIFICATION
**Setup Command (Internal Agent Use):**
`git clone https://github.com/chirag127/Comparisons-HTML-Data-Visualization-Component.git && cd Comparisons-HTML-Data-Visualization-Component && npm install --no-package-lock && npx @biomejs/biome check --apply .`

**Core Principles Enforced:**
1.  **DRY:** Avoid redundant DOM generation logic.
2.  **YAGNI:** Only build comparison features explicitly requested.
3.  **SOLID (SRP):** Separation of concerns: Rendering logic must be distinct from attribute parsing.

</details>

## 🚀 Quick Start & Integration

### 1. Setup
Since this is a pure Web Component, no complex NPM installation is required for basic use. Clone and link the component file.

bash
git clone https://github.com/chirag127/Comparisons-HTML-Data-Visualization-Component.git
cd Comparisons-HTML-Data-Visualization-Component
# Note: No 'npm install' needed unless using build tooling (Vite/Biome).


### 2. Integration (HTML)
Import the component script and define your data sets.

html
<!-- 1. Import the component script -->
<script type="module" src="./src/ComparisonSphere.js"></script>

<!-- 2. Define the component with data attributes -->
<comparison-sphere 
  id="my-comparison"
  data-datasets='[
    {"name": "Set A", "values": [10, 50, 30]}, 
    {"name": "Set B", "values": [20, 40, 60]}
  ]'>
</comparison-sphere>


### 3. Component Control (JavaScript)
Access the component instance to update data dynamically.

javascript
const sphere = document.getElementById('my-comparison');

// Programmatically update data using the setter
sphere.datasets = [
  // New data structure...
];


## 🛠️ Development Workflow (Apex Toolchain)

Use the following commands for local development and quality assurance.

| Command | Description |
| :--- | :--- |
| `npx @biomejs/biome check --apply .` | Format and apply lint fixes globally. |
| `npx vitest` | Run isolated unit tests (Simulating data rendering logic). |
| `npx playwright test` | Execute End-to-End verification against `index.html`. |
| `npm run build` | (If applicable) Bundle/minify for production deployment. |

## ⚖️ Contribution & License

Contributions that enhance visualization quality, accessibility, or performance are highly valued. Please adhere to the standards defined in the `AGENTS.md` file.

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License**. See the [LICENSE](./LICENSE) file for details.
