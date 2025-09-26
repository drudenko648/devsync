# DevSync (Work in Progress)

DevSync is a collaborative web-based code editor built with **pnpm**, **React**, and **NestJS**.  
The project is currently in its early stage. This README serves both as a description of the vision and as a roadmap for upcoming features.

## Project Overview

The goal of Collab IDE is to create a lightweight environment for coding, where multiple users can write, run, and review code in real time.  
Unlike traditional IDEs, this project focuses on simplicity, collaboration, and accessibility from the browser.

## Planned Features

- **Monaco Editor integration**  
  Rich code editing experience with syntax highlighting, IntelliSense, and autocompletion.

- **JavaScript/TypeScript code execution**  
  Ability to run code snippets directly inside the IDE with real-time output.

- **Collaborative editing**  
  Multiple users can work on the same file simultaneously, with cursor and selection synchronization.

- **User sessions and authentication**  
  Secure logins to keep user data safe.

- **History tracking**  
  Ability to undo changes if necessary.

## Tech Stack

- **Monorepo**: pnpm
- **Frontend**: React, TypeScript, Monaco Editor
- **Backend**: NestJS, Node.js
- **(Planned)**: WebSockets for real-time collaboration
- **(Planned)**: Dockerized execution environments for safe code running

## Roadmap

1. ✅ Initialize monorepo with React + NestJS
2. ⏳ Integrate Monaco Editor
3. ⏳ Enable JS/TS code execution
4. ⏳ Add collaborative editing (WebSockets)
5. ⏳ Implement authentication & user sessions
6. ⏳ Add project workspaces and file management
7. ⏳ Extend to multi-language execution (Python, Go, etc.)
