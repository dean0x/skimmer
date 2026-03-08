I built a Claude Code plugin that gets you up to speed on unfamiliar codebases fast.

It's called Skimmer. You point it at a repo, optionally tell it what you're trying to do, and it gives you a structured breakdown: project type, directory layout, relevant files, key functions, where to integrate, and existing patterns to follow.

Under the hood it uses rskim (tree-sitter) to extract code structure without the noise of full implementations. So instead of reading through thousands of lines to understand how a project is organized, you get the shape of things in seconds.

Two ways to use it:

/skim add JWT authentication → focused orientation for a specific task
/skim → general codebase overview

To install:

/plugin marketplace add dean0x/skimmer
/plugin install skimmer@dean0x-skimmer

Open source, MIT licensed.

GitHub: https://github.com/dean0x/skimmer
rskim: https://github.com/dean0x/skim

#ClaudeCode #DeveloperTools #OpenSource
