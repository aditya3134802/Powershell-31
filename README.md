# PowerShell Terminal Emulator

A web-based PowerShell terminal emulator with basic command functionality. This project provides a browser-based experience that mimics the Windows PowerShell interface.

## Features

- Realistic PowerShell terminal UI with Windows styling
- Command history with up/down arrow navigation
- Basic PowerShell commands like get-date, get-process, get-childitem, etc.
- Terminal window controls (minimize, maximize, close)

## Technologies Used

- Frontend: React, TypeScript, Tailwind CSS, Shadcn components
- Backend: Express.js, Node.js
- Database: In-memory storage for command history
- Other: Vite, TanStack Query

## Getting Started

1. Clone the repository
2. Install dependencies with `npm install`
3. Run the development server with `npm run dev`
4. Open your browser to the displayed URL

## Available Commands

- `get-date`: Display the current date and time
- `get-process`: Show a list of running processes
- `get-childitem`: List files and directories
- `get-help`: Display help information
- `write-host`: Output text to the terminal
- `test-connection`: Test network connectivity
- `clear` or `cls`: Clear the terminal screen

## License

MIT