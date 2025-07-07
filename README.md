# CSim OS: The Fintech Challenge

A single-player, web-based simulated environment to learn computer science concepts. This project is a self-contained HTML file with no external dependencies, designed to simulate a desktop OS for a hands-on learning scenario.

---

## The Scenario: Software Engineer – Feature Development & Bug Fixing

You are a new backend developer at a fast-growing fintech startup. The team is building a critical new payment processing feature, but the API keeps failing under high-traffic simulations. The pressure is on.

Your mission is to dive into the simulated operating system, diagnose the problem, and implement a robust solution before the deadline.

### Your Tasks:

-   **Investigate:** Review error logs and application code to identify the performance bottleneck.
-   **Optimize:** Refactor inefficient SQL queries and implement a caching layer with Redis to handle high traffic.
-   **Validate:** Write unit tests to ensure your fixes are reliable and don't introduce new bugs.
-   **Collaborate:** Review API contracts to ensure alignment with the frontend team.

### The Challenge:

The CFO insists the feature **must launch in 48 hours**. How do you prioritize fixes to ensure stability and performance without compromising security or cutting corners?

---

## Key Features

*   **Simulated Desktop Environment:** A fully interactive GUI with a dock, application windows, and drag-and-drop window management.
*   **Built-in Applications:**
    *   **📧 Mail Client:** Receive emails that drive the story and provide crucial context.
    *   **🎯 Quest Tracker:** Automatically tracks your main and side quests as you complete them.
    *   **`>_` Interactive Terminal:** A terminal that behaves like the real thing. Supports `ls`, `cd`, `cat`, `pwd`, `clear`, `help`, command history (arrow keys), and special commands like `edit`, `run-tests`, `redis-cli`, and `git`.
    *   **📝 Code Editor:** A simple in-app editor for modifying configuration and code files.
*   **Virtual File System:** A simulated file structure containing logs, source code, and documentation for you to investigate.
*   **Zero Dependencies:** The entire simulation runs from a single `index.html` file. No external assets, libraries, or internet connection are required after the initial load.

## How to Play

1.  **Check Your Email:** Open the **Mail** app from the dock. Your CTO has left you an urgent message.
2.  **Open the Terminal:** This is your primary tool. Use it to navigate the file system and inspect files. Start with `ls` to see what's in your home directory.
3.  **Follow the Clues:** The emails and log files (`/home/dev/logs/`) will point you toward the problem. Use `cat <filename>` to read files in the terminal.
4.  **Track Your Progress:** The **Quests** app shows your objectives. It will update automatically as you complete key tasks.
5.  **Fix the Code:** Once you find the buggy code, use the `edit <filename>` command to open it, make your changes, and save them.
6.  **Commit Your Solution:** Once all quests are complete, use the simulated `git commit` command to finish the challenge.

## Tech Stack

This project is a demonstration of what can be achieved with pure, "vanilla" web technologies.

*   **HTML:** For the structure of the OS and applications.
*   **CSS:** For all styling, layout, and animations.
*   **JavaScript (ES6+):** For all logic, including the OS, window management, virtual file system, terminal commands, and quest tracking.
*   **No Frameworks or Libraries:** Built from scratch to be lightweight and self-contained.

## License

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.