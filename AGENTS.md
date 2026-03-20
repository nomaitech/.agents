# Global Agent Instructions

- Always run `git init` in each new project workspace if a repository does not already exist. Unless is the home folder directory.
- When doing commits use the Semantic Commit Messages convention (described below)
- Commit after every change without asking for confirmation. Use a concise, descriptive commit message.
- No remote or existing repo is required; local git history is sufficient.
- Spin up a Python http.server in background if the project is a simple static website, always expose it to 0.0.0.0:8000 and let the user know about it


# Semantic Commit Messages

Semantic Commit Messages
See how a minor change to your commit message style can make you a better programmer.

Format: <type>(<scope>): <subject>

<scope> is optional

Example
feat: add hat wobble
^--^  ^------------^
|     |
|     +-> Summary in present tense.
|
+-------> Type: chore, docs, feat, fix, refactor, style, or test.
