# Product Management Workflow

## Exchange Life — Photo Charm Design Workflow System

A browser-based workflow tool for managing a product design project from initial research and concept development through asset management, quality control, export, and final submission.

Built by **Guled Hassen** as a practical demonstration of product thinking, workflow design, digital systems development, and AI-assisted creative operations.

**Live Demo:**  
https://guledz.github.io/Product-management-workflow-/

---

## Overview

Creative product-development projects often involve many disconnected activities: research, references, prompts, images, sourcing, composition, feedback, revisions, documentation, and final delivery.

This project brings those activities into a single structured workspace.

The system was developed around an **Exchange Life Photo Charm** design project and organizes the work into a 10-step production workflow.

The objective is not simply to create a final image, but to create a repeatable and traceable process for producing it.

---

## Core Workflow

The application provides ten predefined workflow stages:

1. **Reference Study**
2. **Concept Choice**
3. **Scene Generation**
4. **Photo Sourcing**
5. **Composite**
6. **Text**
7. **Critique**
8. **Refine**
9. **Export**
10. **Email Submission**

Each stage can be edited and reordered according to the needs of the project.

---

## Key Features

### Workflow Management

- 10-stage product-development workflow
- Editable workflow steps
- Reorderable stages
- Stage-specific descriptions
- Structured project progression

### Asset Management

- Image upload
- Drag-and-drop support
- Asset slots
- Defined aspect ratios
- Source URL tracking
- Photographer information
- Licence information
- Asset metadata

### Prompt Library

- Scene prompt storage
- Negative prompt storage
- One-click prompt copying
- Reusable AI-assisted design instructions

### Quality Control

- Editable project checklist
- Completion progress indicator
- Asset-source validation
- Licence/source warnings
- Final review workflow

### Project Persistence

Project information is automatically stored in the browser using `localStorage`.

This allows the user to close and reopen the application without losing the current project state.

### Export

The project supports:

- Printable HTML documentation
- JSON project export
- Embedded project image data

This allows the workflow to become a portable project record rather than remaining only inside the interface.

---

## Design System

The interface uses a deliberately technical, monochrome visual language.

### Visual characteristics

- Black and white interface
- Monospaced typography
- Technical labels
- Structured panels
- Minimal visual decoration
- Information-focused layout

The project also references Exchange Life brand colors:

| Brand color | Hex |
|---|---|
| Green | `#68AD5C` |
| Red | `#DE2910` |

---

## Product Architecture

The system can be understood as five connected layers:

```text
WORKFLOW
    ↓
ASSETS
    ↓
PROMPTS
    ↓
QUALITY CONTROL
    ↓
EXPORT / SUBMISSION
```

The workflow controls the project stages.

The asset layer manages visual inputs and their metadata.

The prompt layer stores reusable creative instructions.

The QC layer verifies project completeness.

The export layer packages the finished project for documentation and submission.

---

## Product Thinking

This project demonstrates several practical product-management principles:

- **Workflow decomposition** — breaking a complex assignment into manageable stages.
- **Traceability** — maintaining source and licence information for visual assets.
- **Reproducibility** — retaining prompts and project structure.
- **Quality assurance** — checking completeness before delivery.
- **State management** — preserving project progress between sessions.
- **Documentation** — producing a structured record of the project.
- **Delivery management** — connecting the creative process to final submission.

The system therefore treats the design assignment as a small product-development lifecycle rather than a collection of isolated creative tasks.

---

## Engineering Approach

The project follows a simple systems-thinking model:

```text
INPUTS
References
Images
Prompts
Requirements

        ↓

PROCESS
10-stage workflow

        ↓

VALIDATION
Checklist
Metadata
Source tracking
Quality control

        ↓

OUTPUTS
Final design
Project documentation
JSON project data
Submission package
```

This approach reflects the connection between engineering problem-solving and digital product development.

---

## Use Case

The workflow is particularly useful for projects involving:

- Product design
- Creative production
- AI-assisted visual development
- Image sourcing
- Brand-content development
- Design trials
- Portfolio projects
- Structured creative submissions

The current implementation is intentionally focused on a single-project workflow rather than positioned as a general enterprise project-management platform.

---

## Project Structure

The project is designed as a lightweight single-page web application that can run directly in a modern browser.

No server-side account or database is required for the core workflow.

Project state is maintained locally in the browser.

---

## Privacy & Data

The application is designed around local project persistence.

Project information is stored in the browser rather than requiring a central project-management account.

Users should still treat exported project files and embedded images as potentially sensitive project data and manage them appropriately.

---

## Portfolio Context

This project is part of **Guled Hassen's digital systems and product-development portfolio**.

It demonstrates an approach that combines:

**Engineering Thinking + Product Thinking + Digital Systems + Creative Workflow Design**

Rather than focusing only on the final visual result, the project demonstrates how the work can be structured, managed, validated, documented, and delivered.

---

## Author

**Guled Hassen**

Engineer · Digital Systems Builder · Web & Digital Solutions

Areas of interest:

- Digital systems
- Product workflows
- Business websites
- Dashboards and digital tools
- Data digitization
- AI-assisted workflows
- Engineering and infrastructure systems

---

## Links

**Live Project**  
https://guledz.github.io/Product-management-workflow-/

**Main Portfolio**  
https://guledz.github.io/Guledhassen/

---

## License

This project is presented as a portfolio and demonstration project.

Unless otherwise specified, project-specific design assets, brand materials, photographs, and other third-party content remain subject to their respective ownership and licensing terms.
