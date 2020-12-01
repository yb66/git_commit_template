# Git Commit Template

# Set up

Place the template somewhere, I use `~/.git-templates` to store all my templates. Then, in my git config (which is located at `~/.gitconfig`), add the following:

	[init]
		templatedir = ~/.git-templates

	[commit]
		template = .git/commit-template.txt

Whenever you run `git commit` and the editor opens for you to type out your message, you should see this template instead of the default one supplied by Git.

# Honourable mentions

I wouldn't have thought to have done this without the following:

- https://github.com/joelparkerhenderson/git_commit_template
- https://karma-runner.github.io/0.10/dev/git-commit-msg.html
- https://seesparkbox.com/foundry/semantic_commit_messages

## Any thoughts?

Contributions are welcome!