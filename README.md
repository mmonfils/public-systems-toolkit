# The Public Systems Toolkit

An open-source, mobile-friendly template repository built for macro social work analysis and public systems tracking by private individuals. 

## Repository Architecture

This repository uses a two-tier layout approach to keep public pages clean and accessible while retaining advanced developer tools:
1.  **Front of the House (Curb Appeal):** Clean, casual Markdown pages parsed using the GitHub Pages Cayman Jekyll theme, focused on an 8th-grade reading level with zero em dashes or emojis.
2.  **The Garage (Workshop):** Advanced AI prompt injection blocks placed at the top of individual Markdown files within HTML comments `<!-- -->`. These blocks are completely invisible on the final public website but become fully functional when editing files using an AI assistant.

## Core Data Pathway: Shared Context Model

To maintain simplicity, this toolkit uses a **Shared Context File** model:
*   All raw legislative data, meeting minutes, public notices, and forum links are pasted exactly once into `/current-event-context.md`.
*   Individual analytical files (STEEPLE, Friction Costs, etc.) read from that single file to generate clean, public-facing summaries based on their own embedded AI prompts.

## Language and Safety Boundaries

All additions to this repository must adhere to the following boundaries:
*   **Absolute Inclusivity:** Do not use the word "citizen" or imply legal citizenship requirements. Focus purely on "residents," "the public," or "the community."
*   **Liability Shielding:** Do not name specific private individuals, companies, or non-governmental organizations. Direct all metrics toward public offices, structural roles, and broad institutional sectors.
*   **Term Safety:** Avoid the phrases "Community Action" (to prevent confusion with formal anti-poverty networks) and "Social Change" (due to potential polarizing connotations for casual public viewers).
*   **Format Rules:** No emojis and no em dashes anywhere in the markdown text files.