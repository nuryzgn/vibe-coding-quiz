# Part 4 — EXPERIENCE (Vibe Coding)

## Tool Selection Justification
For this project, I focused on building a working quiz app quickly with a conversational, iterative workflow. I wanted a tool that could help me scaffold features, debug errors, and refine UI/UX in short cycles. The main appeal of vibe coding is reducing context switching: instead of searching for every small fix manually, I can describe the goal and iterate until the app behaves correctly.

## Development Process
I started by scaffolding a React + Vite project and then iterated feature-by-feature: displaying questions, rendering multiple-choice answers, tracking score, and adding a restart flow. The most effective prompts were goal-based (“Add progress indicator and results screen”) and error-based (“Fix the missing import/file error and make sure questions load”). The workflow was highly iterative: I ran the dev server, observed errors or UI issues, adjusted code, and repeated until the app was stable.

## Challenges and Solutions
The biggest challenges were missing-file/import issues and getting the UI to display options correctly. When something broke (for example, an unresolved import), I had to verify filenames and paths and ensure the data module existed. The AI-assisted workflow helped by suggesting the right structure for a `questions` data file and by providing quick patterns for React state handling. However, I still needed to manually verify the output by running the app and checking that the UI matched the requirements.

## Reflection
What surprised me most was how much faster it was to move from a vague idea (“quiz app”) to a functional project with multiple features. Vibe coding changed my workflow from writing code line-by-line to describing behavior and validating results. I would use this approach again for rapid prototypes, small projects, and refactors. For larger production systems, I would still rely on careful design, tests, and code review because AI can make incorrect assumptions and introduce subtle bugs. Overall, I think vibe coding will shift software development toward higher-level intent, where developers spend more time specifying goals and verifying outcomes.
