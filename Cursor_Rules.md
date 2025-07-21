### 🧱 Code Structure & Modularity
- **Never create a file longer than 500 lines of code.** If a file approaches this limit, refactor by splitting it into modules or helper files.
- **Organize code into clearly separated modules**, grouped by feature or responsibility.
- **Use clear, consistent imports** (prefer relative imports within packages).

### 🧪 Testing & Reliability
- **Always create Pytest unit tests for new features** (functions, classes, routes, etc).
- **After updating any logic**, check whether existing unit tests need to be updated. If so, do it.
- **Tests should live in a `/tests` folder** mirroring the main app structure.
  - Include at least:
    - 1 test for expected use
    - 1 edge case
    - 1 failure case

# Important rules YOU HAVE TO FOLLOW:
- Always add debug logs and comments in the code for easier debugging and readability. 
- Every time you choose to apply rule(s), excplitily state the rule(s) in the output. You can abbreivate the rule description to a single word or phrase.
- ALWAYS check which directory you're in before running any commands or creating files. 
- ALWAYS start with anayzing the codebase and assesing the problem or next steps before writing code. 

- **Never assume missing context. Ask questions if uncertain.**
- **Never hallucinate libraries or functions** – only use known, verified Python packages.
- **Always confirm file paths and module names** exist before referencing them in code or tests.

# Rules: 
- Always check the tree strucutre before creating new files or directories.
- Always take micro-steps when making changes.
- Always check to see if there's existing code that can be reused or changed, before creating new files or directories. 
- When starting a new phase from our Todo list, always start by writing tests for the new feature. 
- When providing an explanation to a problem, make sure you have the objective truth and not simple assumptions, then explain it all in simple terms at a fifth grade reading level, using simple words. 
