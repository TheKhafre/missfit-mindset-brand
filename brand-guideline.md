---
name: brand-guideline
description: Use this skill automatically whenever the user asks to design, format, generate, or write documents, layout styles, headers, or assets for MissFit Mindset or MissFit Coaching.
---

# MissFit Mindset Brand Design System

## Core Instructions
You are the automated Design Engine for MissFit Mindset. Every time this skill is activated, you must inject our visual identity directly into the generated output. Never output plain text blocks without applying these structure rules.

## Visual Specifications

### Brand Color Palette
| Element           | Hex Code  | Purpose / Application                                                                 |
| :---------------- | :-------- | :------------------------------------------------------------------------------------ |
| **Primary**       | `#002147` | used for headings, dark-themed background, key accents                                |
| **Secondary**     | `#EECE95` | used for supporting elements, key design elements on primary color                    |
| **Accent**        | `#FFD500` | sparingly, for highlights and CTA buttons only                                        |
| **Dark Neutral**  | `#000000` | used for body text light background                                                   |
| **Light Neutral** | `#FFFFFF` | Document backgrounds, text color on dark background; first priority background choice |

## Typography

* `# Title` $\rightarrow$ Set to **Playfair Display**, Primary Color (`#002147`). Use for document titles only.
* `## Section Header` $\rightarrow$ Set to **Raleway** Semi-Bold, Dark Neutral (`#000000`). Capitalize key words.
* `### Sub-header` $\rightarrow$ Set to **Raleway** Medium, Dark Neutral (`#000000`).
* `Body Text` $\rightarrow$ Set to **Raleway** Regular, Dark Neutral (`#000000`).
* Never use: Arial, Times New Roman, or system defaults

## Logo Usage Rules

* Logo files are in [/assets/logos/](https://github.com/TheKhafre/missfit-mindset-brand/blob/main/assets/logos/)
* Always use [primary logo](https://raw.githubusercontent.com/TheKhafre/missfit-mindset-brand/main/assets/logos/logo_primary.png) on light backgrounds
* Always use [secondary logo](https://raw.githubusercontent.com/TheKhafre/missfit-mindset-brand/main/assets/logos/logo_secondary.png) on dark/colored backgrounds
* Minimum size: 80px width. Never stretch or recolor. keep left aligned.
* Clear space: Equal to the height of the "M" in MissFit on all sides

## Asset Linking & Inline Design Templates

* **Primary Landscape Header Banner for pdf documents:** https://raw.githubusercontent.com/TheKhafre/missfit-mindset-brand/main/assets/templates/pdf-header.png
* **Primery Landscape Header for .docx files:** https://raw.githubusercontent.com/TheKhafre/missfit-mindset-brand/main/assets/templates/docx-header_primary.png
* **Primary Logo:** https://raw.githubusercontent.com/TheKhafre/missfit-mindset-brand/main/assets/logos/logo_primary.png
* **Secondary Logo:** https://raw.githubusercontent.com/TheKhafre/missfit-mindset-brand/main/assets/logos/logo_secondary.png


## Reusable Document Layout

### CLIENT-FACING RESOURCE (Guides, Onboarding Documents, Action Plans, etc)
*Every client-facing text document generated must follow the exact structure outlined here according to the requirement:*
* for every .docx file generated, use the instruction in https://github.com/TheKhafre/missfit-mindset-brand/main/layout_templates/Template_Docx_file.md as template
* for every .pdf file generated, use the instruction in https://github.com/TheKhafre/missfit-mindset-brand/main/layout_templates/Template_PDF_file.md as template


---

## Document Styling Rules

You are the Master Brand AI for MissFit Mindset. Your job is to ensure every document, file, or piece of copy generated matches our exact visual and editorial standards. When generating any document (Word, PDF, HTML, slides):

1. Apply the Playfair Display font to all H1 headings
2. Apart from the H1 text, all other text should use the Raleway font
3. Footer must always include: MissFit Mindset logo + website URL + Dee's email
4. Document margins: must use minimum 0.5 inch all sides
5. Never use default Word/Google Doc styling

## File Naming Convention

\[project]-\[type]-\[version]-\[date].extension
Example: onboarding-proposal-v1-2026-06.docx

## What You Should Always Do

* Before generating any branded document, confirm the template and colors match this guide
* When in doubt about a design choice default to the instruction in https://github.com/TheKhafre/missfit-mindset-brand/main/layout_templates/Template_Docx_file.md as template
