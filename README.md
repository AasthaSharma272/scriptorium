# Scriptorium

Scriptorium is an online platform designed for coding enthusiasts and learners to write, execute, and manage code in multiple programming languages. It also provides a space to create and explore blog posts, fostering a collaborative and engaging environment for programmers. This document provides an overview of the features, setup, and usage instructions for the Scriptorium project.

## Features

### Accounts

- User Authentication: Users can sign up, log in, log out, and manage their profiles.

- Profile fields include: first and last name, email, profile picture, and phone number.

- Authentication is implemented using JWT for secure access.

### Code Writing and Execution

- Multilanguage Support: Visitors can write code in various programming languages such as C, C++, Java, Python, Swift, Bash, Haskell, Julia, PHP, and JavaScript.

- Syntax Highlighting: Code is highlighted based on the syntax of the selected programming language for better readability.

- Code Execution: Users can execute code and see the results in real time.

- Standard Input Support: Users can provide inputs for their code via stdin before execution.

- Error Handling: Compilation errors, runtime errors, timeouts, and warnings are displayed to help users debug their code.

- Security: Code runs in a secure, isolated environment using Docker, ensuring no interference with other users or the system.

- Execution Limits: Time and memory constraints are enforced to handle infinite loops and resource-intensive processes.

### Code Templates

- Save Templates: Authenticated users can save code as templates with titles, descriptions, and tags.

- Search and Reuse: Users can search and view their saved templates or reuse public templates.

- Editing and Deletion: Users can edit or delete their templates.

- Forking: Visitors can modify and run existing templates, and authenticated users can save them as new templates marked as forked versions.

### Blog Posts

- Create and Edit: Authenticated users can create, edit, or delete blog posts.

- Link to Templates: Blog posts can link to relevant code templates for reference.

- Browse and Search: Visitors can browse and search blog posts by title, content, tags, and linked templates.

- Comments and Ratings: Users can comment on blog posts and rate posts and comments with upvotes or downvotes.

### Inappropriate Content Reports

- Reporting: Users can report inappropriate blog posts or comments with explanations.

- Admin Tools: Administrators can sort reported content by the number of reports and hide inappropriate content. Hidden content remains visible only to the author with a report flag.

### User Experience

- Responsive Design: The platform is optimized for various screen sizes, including monitors, laptops, tablets, and mobile devices.

- Dark and Light Themes: Users can toggle between dark and light themes for a comfortable coding experience.

### Technology Stack

- Frontend: Built with Next.js and React for an interactive and responsive user interface.

- Backend: Powered by Next.js API routes for server-side logic and APIs, data managed with Prisma ORM.

- Code Execution: Runs in isolated Docker containers for secure and scalable execution.

## Contribution Guidelines

We welcome contributions to improve Scriptorium! Please submit issues and pull requests on the GitHub repository. Ensure all changes are tested locally before submission.
