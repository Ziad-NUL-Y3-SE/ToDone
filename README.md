# SECTION 1 – PROJECT PROPOSAL

### Project Name: ToDone

**ToDone** is a simple and user-friendly to-do list web application built using HTML, CSS, and JavaScript. It allows users to add, complete, and clear tasks using an intuitive, minimal interface optimised for mobile-first design.

---

### 🔹 Purpose

The goal of ToDone is to support users in managing day-to-day tasks efficiently without the complexity of login systems, notifications, or syncing. The app is ideal for time-pressed users such as:

- A student juggling coursework deadlines across multiple modules
- A junior analyst managing daily stand-up actions
- A busy professional wanting a lightweight personal checklist

Simplicity is not a limitation, but a conscious design choice to reduce friction, minimise cognitive load, and support task clarity. By removing unnecessary features, ToDone becomes a productivity tool that empowers autonomy and focus.

---

### 🔹 Rationale

This project was selected because of its:

- Simplicity and clarity – easy to implement with front-end technologies
- Strong modular design potential – aligns with best practices in software architecture
- Suitability for agile planning and iterative delivery – enabling the use of modern project management and CI/CD pipelines

It provides a solid platform to demonstrate:

- Planning using GitHub Projects
- Incremental development with Git
- Test-Driven Development (TDD)
- Continuous Integration (CI) using GitHub Actions

---

### 🔹 Relevance to Workplace

While this app is not yet a client-facing product, it serves as a testbed for applying professional software engineering practices used in workplace environments. These include:

- Kanban-based agile planning via GitHub Projects
- Branching and pull request workflows for version control
- Test automation foundations using GitHub Actions

The project reinforces industry-relevant capabilities in iterative delivery, automation, and UI responsiveness.

---

### 🔹 Learning Outcome Alignment

ToDone offers direct opportunities to demonstrate core software engineering principles — from modular design and testable architecture, to agile planning, version control, and automated validation — in line with the learning outcomes of the Software Engineering module (NCHNAP688).

## SECTION 2 – DESIGN AND PROTOTYPE

### Tools Used

The ToDone prototype was created using **Figma**, a browser-based interface design tool widely used in professional software development. Figma was selected for its ease of use, support for real-time editing, and strong alignment with UI/UX best practices. Its ability to produce pixel-perfect, responsive mockups made it suitable for designing a clean, mobile-first interface.

### Key UI Components

The ToDone prototype includes the following interface elements:

- **Header Bar**  
  Displays the name of the app clearly at the top for branding and orientation.

- **Task Input Field**  
  A single-line input where users can type the description of a task.

- **Add Task Button [+]**  
  Positioned next to the input field, this button allows users to submit tasks efficiently.

- **Task List Section**  
  Displays each added task in a row format, including:
  - A checkbox to toggle task completion
  - A delete icon to remove the task from the list

- **Clear All Button**  
  Positioned at the bottom, this allows users to quickly remove all completed tasks for convenience.

### Design Rationale

The design prioritises simplicity and usability, with a mobile-first layout that supports quick interactions and minimal friction. The visual hierarchy is clear, separating task entry, task management, and overall list controls into distinct areas. Icons and button placements are intuitive to enhance the user experience.

### Usability and Accessibility

- The app uses high-contrast colours for readability.
- The layout is designed to be responsive across mobile and tablet screens.
- Interactive elements are touch-friendly, with adequate spacing.
- The prototype avoids unnecessary animations or distractions to reduce cognitive load.

### Figma Prototype

The interface was built iteratively using feedback and informal testing. The final prototype layout is shown below:

## SECTION 3 – AGILE PROJECT PLANNING

### Agile Methodology and Approach

The ToDone project adopted an Agile-inspired approach, using a simplified **Kanban workflow** through GitHub Projects. This allowed for real-time task visibility, prioritisation, and incremental delivery. Each ticket represents a discrete unit of work, aligned with the agile principle of **"one task = one feature"**.

Tasks were organised into three columns:
- **To Do** – items not yet started
- **In Progress** – currently being developed
- **Done** – fully implemented and committed

This layout supported quick stand-up reviews, self-organisation, and ongoing prioritisation, simulating agile routines. While no formal sprints or retrospectives were used, tasks were tackled iteratively based on logical build order and difficulty.

### Project Management Tool: GitHub Projects Board

A GitHub Project board was used to plan and track progress across 8 distinct issues. Each issue was created as a **functional or non-functional requirement** and mapped to a GitHub ticket. Tasks included both UI development and project operations (e.g., CI setup).

Key benefits of using GitHub Projects:
- Clear visual status of feature progress
- Seamless integration with GitHub issues, pull requests, and branches
- Enables traceability and a lightweight planning cadence

The planning board supports asynchronous collaboration and mirrors real-world engineering practice, especially in distributed or solo developer environments.

### Screenshot of Planning Board

![ToDone GitHub Board](ToDone-GitHub-Board.png)

The board helped maintain focus and ensure all MVP components were planned and tracked logically, using the agile principle of **incremental delivery and continuous improvement**.

![ToDone Prototype](https://github.com/Ziad-NUL-Y3-SE/ToDone/blob/main/ToDone-GitHub-Board.png?raw=true)


