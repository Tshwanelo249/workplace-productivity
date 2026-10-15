# AI-Powered Workplace Productivity Assistant

## Project overview
A beginner-friendly prompt-building web app for common workplace tasks. It prepares structured prompts that users can paste into an approved AI tool such as ChatGPT or Gemini.

## Features
- Professional email prompt generator
- Meeting notes summarisation prompt generator
- Task planning prompt generator
- Research planning prompt generator
- Workplace chatbot prompt generator
- Copy prompts or download them as text files
- Responsive design for desktop and mobile
- Responsible-use reminders

## Implementation note
This version is a **prompt-building prototype**. It does not call an AI model or automatically generate AI answers. The user copies a prompt into an approved AI tool and reviews the result. A future version could connect an AI API through a secure backend. Never place API keys in browser code.

## How to run
1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Choose a tool, enter non-confidential details, and select **Generate prompt**.
4. Copy the prompt into an approved AI tool or download it as a `.txt` file.

No installation or build step is required.

## Prompt engineering approach
Prompts define the role, task, context, output format, and constraints. Constraints ask the AI not to invent missing facts and to flag uncertainty.

## Responsible and ethical use
- Never enter passwords, identity numbers, private customer data, confidential business records, or sensitive meeting notes.
- Verify facts, dates, calculations, citations and recommendations.
- Review generated emails and summaries before sharing.
- Follow workplace AI, privacy, and information-security policies.
- AI output is not a substitute for qualified advice in high-impact matters.

## Suggested test cases
1. Email: ask for a professional meeting request; verify subject and respectful wording.
2. Meeting: provide sample notes with one decision and two actions; check that missing owners/dates are not invented.
3. Tasks: provide a goal and deadline; check priorities and first steps.
4. Research: request a topic overview; check that it does not fabricate citations.
5. Chatbot: ask a policy question with limited context; check that uncertainty is flagged.

## Submission checklist
- [ ] Upload `index.html`
- [ ] Include this README
- [ ] Test all five tabs and copy/download buttons
- [ ] Add screenshots of the working app if required
- [ ] Explain the prototype limitation and ethical safeguards in the submission
