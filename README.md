# Awesome AI-Driven Development [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A comprehensive list of tools, checklists, patterns, and prompts for starting AI-driven development - from beginner to pro!

AI-driven development is transforming how we write code. This curated list helps developers leverage AI tools to boost productivity, improve code quality, and accelerate learning.

## Contents

- [Getting Started with GitHub Copilot](#getting-started-with-github-copilot)
- [Useful Tools](#useful-tools)
  - [AI Code Assistants](#ai-code-assistants)
  - [AI-Powered IDEs and Extensions](#ai-powered-ides-and-extensions)
- [Work Online](#work-online)
- [Work Locally](#work-locally)
- [Patterns and Best Practices](#patterns-and-best-practices)
- [Prompts and Templates](#prompts-and-templates)
- [Checklists](#checklists)
- [Learning Resources](#learning-resources)
- [Contributing](#contributing)

## Getting Started with GitHub Copilot

GitHub Copilot is an AI pair programmer that helps you write code faster and with less work.

### Prerequisites

- A GitHub account
- A compatible IDE (VS Code, Visual Studio, Neovim, or JetBrains IDEs)
- An active GitHub Copilot subscription (free for students, teachers, and open source maintainers)

### Setup Steps

1. **Subscribe to GitHub Copilot**
   - Visit [GitHub Copilot](https://github.com/features/copilot)
   - Choose your plan (Individual, Business, or Enterprise)
   - Students can get it free through [GitHub Education](https://education.github.com/)

2. **Install the Extension**
   - **VS Code**: Install the [GitHub Copilot extension](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
   - **JetBrains**: Install from the IDE plugin marketplace
   - **Neovim**: Use the [copilot.vim](https://github.com/github/copilot.vim) plugin
   - **Visual Studio**: Built-in or available as extension

3. **Authenticate**
   - Open your IDE
   - Sign in to GitHub when prompted
   - Authorize GitHub Copilot

4. **Start Coding**
   - Write a comment describing what you want to do
   - Let Copilot suggest code
   - Press `Tab` to accept suggestions or `Esc` to dismiss
   - Use `Alt+]` or `Option+]` to cycle through suggestions

### Tips for Effective Use

- Write clear, descriptive comments before code blocks
- Break down complex tasks into smaller functions
- Review and test all AI-generated code
- Use meaningful variable and function names for better context
- Leverage Copilot Chat for explanations and refactoring

## Useful Tools

### AI Code Assistants

- [GitHub Copilot](https://github.com/features/copilot) - AI pair programmer that suggests code in real-time.
- [Cursor](https://cursor.sh/) - AI-first code editor built on VS Code.
- [Tabnine](https://www.tabnine.com/) - AI code completion for multiple IDEs.
- [Codeium](https://codeium.com/) - Free AI code acceleration toolkit.
- [Amazon CodeWhisperer](https://aws.amazon.com/codewhisperer/) - AWS's AI coding companion.
- [Replit Ghostwriter](https://replit.com/site/ghostwriter) - AI pair programmer for Replit.
- [Sourcegraph Cody](https://sourcegraph.com/cody) - AI coding assistant that knows your codebase.

### AI-Powered IDEs and Extensions

- [VS Code](https://code.visualstudio.com/) with GitHub Copilot - Most popular choice for AI-driven development.
- [JetBrains IDEs](https://www.jetbrains.com/) - Professional IDEs with built-in AI assistance.
- [Cursor](https://cursor.sh/) - Dedicated AI-first editor.
- [Continue](https://continue.dev/) - Open-source autopilot for VS Code and JetBrains.
- [Windsurf Editor](https://codeium.com/windsurf) - Next-generation AI code editor by Codeium.

### Code Review and Quality

- [CodeRabbit](https://coderabbit.ai/) - AI-powered code review assistant.
- [Codacy](https://www.codacy.com/) - Automated code quality reviews with AI insights.
- [DeepCode](https://www.deepcode.ai/) - AI-powered code review tool (now part of Snyk).

### Documentation and Learning

- [Mintlify](https://mintlify.com/) - AI-powered documentation writer.
- [Stenography](https://stenography.dev/) - Automatic code documentation.
- [Explain Code](https://explaincode.app/) - Get AI explanations for any code.

## Work Online

Online AI-driven development environments let you code from anywhere without local setup.

### Cloud IDEs with AI

- [GitHub Codespaces](https://github.com/features/codespaces) - Cloud-based VS Code with GitHub Copilot integration.
- [Replit](https://replit.com/) - Collaborative browser-based IDE with Ghostwriter AI.
- [Gitpod](https://www.gitpod.io/) - Cloud development environment with AI extensions support.
- [CodeSandbox](https://codesandbox.io/) - Online code editor with AI assistance.
- [StackBlitz](https://stackblitz.com/) - Instant full-stack web IDE in the browser.

### AI Coding Playgrounds

- [OpenAI Playground](https://platform.openai.com/playground) - Experiment with GPT models for code generation.
- [Phind](https://www.phind.com/) - AI search engine for developers with code examples.
- [ChatGPT](https://chat.openai.com/) - General-purpose AI that can help with coding tasks.
- [Claude](https://claude.ai/) - Anthropic's AI assistant with strong coding capabilities.
- [Google AI Studio](https://aistudio.google.com/) - Experiment with Gemini models for coding.

### Collaborative Development

- [GitHub](https://github.com/) - Version control with Copilot, code review, and project management.
- [GitLab](https://gitlab.com/) - Complete DevOps platform with AI features.
- [Linear](https://linear.app/) - Issue tracking with AI-powered features.

## Work Locally

Set up your local environment for AI-driven development with maximum control and privacy.

### Essential Setup

1. **Install a Modern IDE**
   - [VS Code](https://code.visualstudio.com/) - Most popular, extensive AI extension ecosystem
   - [JetBrains Toolbox](https://www.jetbrains.com/toolbox-app/) - For professional Java, Python, JavaScript development
   - [Neovim](https://neovim.io/) - For terminal-based development with AI plugins

2. **Install AI Assistants**
   - GitHub Copilot extension (paid)
   - Codeium extension (free)
   - Tabnine extension (freemium)
   - Continue extension (open-source, supports local models)

3. **Version Control**
   - [Git](https://git-scm.com/) - Essential for all development
   - [GitHub Desktop](https://desktop.github.com/) - Visual Git client
   - [GitKraken](https://www.gitkraken.com/) - Advanced Git GUI with AI features

4. **Terminal and Shell**
   - [iTerm2](https://iterm2.com/) (macOS) or [Windows Terminal](https://aka.ms/terminal) (Windows)
   - [Oh My Zsh](https://ohmyz.sh/) or [Starship](https://starship.rs/) - Enhanced shell prompts
   - [GitHub CLI](https://cli.github.com/) - Interact with GitHub from terminal

### Local AI Models

Run AI models locally for privacy and offline development:

- [Ollama](https://ollama.ai/) - Run large language models locally (Llama, Code Llama, etc.)
- [LM Studio](https://lmstudio.ai/) - Desktop app for running local LLMs with a UI
- [GPT4All](https://gpt4all.io/) - Free, private AI assistant that runs locally
- [Continue](https://continue.dev/) - Supports local model integration with your IDE
- [Llama.cpp](https://github.com/ggerganov/llama.cpp) - Run Llama models efficiently on CPU

### Development Environment Tools

- [Docker](https://www.docker.com/) - Containerize your development environment
- [Dev Containers](https://containers.dev/) - Develop inside containers with VS Code
- [Homebrew](https://brew.sh/) (macOS/Linux) or [Chocolatey](https://chocolatey.org/) (Windows) - Package managers
- [nvm](https://github.com/nvm-sh/nvm) or [fnm](https://github.com/Schniz/fnm) - Node.js version management
- [pyenv](https://github.com/pyenv/pyenv) - Python version management

### Productivity Boosters

- [Raycast](https://www.raycast.com/) (macOS) - Productivity tool with AI commands
- [Warp](https://www.warp.dev/) - AI-powered terminal with built-in assistance
- [Fig](https://fig.io/) - Terminal autocomplete with AI features (now part of AWS)

## Patterns and Best Practices

### Writing Effective Prompts

**Comment-Driven Development**: Write comments first, let AI generate implementation.

```python
# Calculate the average of a list of numbers, handling empty lists and None values
# Return 0 if the list is empty or None
```

**Function Signature First**: Define the signature, let AI implement the body.

```typescript
function fetchUserDataWithRetry(userId: string, maxRetries: number = 3): Promise<User> {
  // AI will suggest implementation
}
```

**Test-Driven with AI**: Write test cases, let AI implement the function.

```javascript
// Test cases
test('should return sum of two numbers', () => {
  expect(add(2, 3)).toBe(5);
  expect(add(-1, 1)).toBe(0);
  expect(add(0, 0)).toBe(0);
});

// AI will suggest the add function implementation
```

### Best Practices

1. **Always Review AI-Generated Code**
   - Check for logic errors
   - Verify security implications
   - Ensure it follows project conventions
   - Test thoroughly

2. **Provide Context**
   - Keep related code visible in your editor
   - Use meaningful variable and function names
   - Add comments explaining business logic

3. **Iterate and Refine**
   - Accept suggestions as starting points
   - Refactor AI-generated code to match your style
   - Ask AI for alternative approaches

4. **Security Considerations**
   - Never commit sensitive data in prompts
   - Review generated code for vulnerabilities
   - Use security scanning tools
   - Be cautious with external API calls

5. **Leverage AI for Learning**
   - Ask AI to explain unfamiliar code
   - Request alternative implementations
   - Learn new patterns and techniques

## Prompts and Templates

### Code Generation Prompts

```
// Generate a REST API endpoint
Create a REST API endpoint in Express.js that:
- Accepts POST requests at /api/users
- Validates email and password fields
- Hashes the password using bcrypt
- Stores the user in MongoDB
- Returns appropriate status codes
```

```
// Database schema design
Design a SQL schema for a blog platform with:
- Users (authentication, profile)
- Posts (title, content, published date)
- Comments (nested, with likes)
- Tags (many-to-many with posts)
Include appropriate indexes and foreign keys
```

### Code Review Prompts

```
Review this code for:
1. Security vulnerabilities
2. Performance issues
3. Best practices violations
4. Potential bugs
[paste your code]
```

### Refactoring Prompts

```
Refactor this function to:
- Improve readability
- Reduce complexity
- Follow SOLID principles
- Add error handling
[paste your code]
```

### Documentation Prompts

```
Generate comprehensive JSDoc/Docstring for this function including:
- Description
- Parameters with types
- Return value
- Examples
- Edge cases
[paste your code]
```

## Checklists

### Before Accepting AI Suggestions

- [ ] Does the code compile/run without errors?
- [ ] Does it solve the intended problem?
- [ ] Is it secure (no SQL injection, XSS, etc.)?
- [ ] Does it handle edge cases?
- [ ] Is it efficient and performant?
- [ ] Does it follow project coding standards?
- [ ] Are variable/function names meaningful?
- [ ] Is it properly documented?
- [ ] Does it include necessary error handling?
- [ ] Have you tested it with various inputs?

### Setting Up AI-Driven Development

- [ ] Choose and install an AI code assistant
- [ ] Configure IDE settings for optimal AI suggestions
- [ ] Set up version control (Git)
- [ ] Install necessary language runtimes
- [ ] Configure linters and formatters
- [ ] Set up testing framework
- [ ] Review and accept terms of service
- [ ] Understand data privacy implications
- [ ] Learn keyboard shortcuts for AI tools
- [ ] Customize AI sensitivity and suggestion frequency

### Code Review with AI Assistance

- [ ] Run automated tests
- [ ] Use AI to identify potential bugs
- [ ] Check for security vulnerabilities
- [ ] Verify code meets requirements
- [ ] Ensure proper error handling
- [ ] Review performance implications
- [ ] Check code documentation
- [ ] Validate against coding standards
- [ ] Test edge cases
- [ ] Get human review for critical changes

## Learning Resources

### Official Documentation

- [GitHub Copilot Documentation](https://docs.github.com/en/copilot)
- [OpenAI API Documentation](https://platform.openai.com/docs)
- [Anthropic Claude Documentation](https://docs.anthropic.com/)

### Courses and Tutorials

- [GitHub Copilot Quickstart](https://docs.github.com/en/copilot/quickstart)
- [Prompt Engineering Guide](https://www.promptingguide.ai/)
- [AI-Assisted Development Best Practices](https://github.blog/category/engineering/ai/)

### Articles and Blogs

- [GitHub Blog - Copilot](https://github.blog/tag/github-copilot/)
- [The Future of Programming](https://stackoverflow.blog/tag/ai/)
- [AI-Driven Development Patterns](https://martinfowler.com/tags/artificial%20intelligence.html)

### Communities

- [r/Github](https://www.reddit.com/r/github/) - GitHub community on Reddit
- [r/CodingWithAI](https://www.reddit.com/r/CodingWithAI/) - AI coding discussions
- [GitHub Community](https://github.community/) - Official GitHub community
- [Dev.to #ai](https://dev.to/t/ai) - AI development articles and discussions

### YouTube Channels

- [GitHub](https://www.youtube.com/@GitHub) - Official GitHub channel with Copilot tutorials
- [Fireship](https://www.youtube.com/@Fireship) - Modern development with AI tools
- [NetworkChuck](https://www.youtube.com/@NetworkChuck) - Tech tutorials including AI

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

To contribute:

1. Fork this repository
2. Create a new branch (`git checkout -b feature/amazing-tool`)
3. Add your contribution following the existing format
4. Ensure links are working and descriptions are clear
5. Commit your changes (`git commit -m 'Add amazing tool'`)
6. Push to the branch (`git push origin feature/amazing-tool`)
7. Open a Pull Request

### Guidelines

- Keep descriptions concise and clear
- Add tools/resources that are actively maintained
- Include both free and paid options when relevant
- Verify all links are working
- Follow the existing formatting style
- One tool/resource per pull request for easier review

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [ivoarnet](https://github.com/ivoarnet) has waived all copyright and related or neighboring rights to this work.
