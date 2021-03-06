# Git Commit Template

## Set up

Place the template somewhere, I use `~/.git-templates` to store all my templates (so the full path in my instance is `~/.git-templates/commit-template.txt`). So, if you have cURL you could do:

	mkdir ~/.git-templates
	curl https://raw.githubusercontent.com/yb66/git_commit_template/master/commit-template.txt > ~/.git-templates/commit-template.txt

Then, in my git config (which is located at `~/.gitconfig`), I've added the following:

	[init]
		templatedir = ~/.git-templates

	[commit]
		template = .git/commit-template.txt

Whenever you run `git commit` and the editor opens for you to type out your message, you should see this template instead of the default one supplied by Git.

## Note!

If you go through my commit messages you'll notice that I don't always follow the guidelines set out in the commit message. That's because *I'm the one writing the commit message, I say what goes*. What the template does do is guide me and remind me. Don't let rules rule you, but remember that others may need your commit messages later on.

## Honourable mentions

I wouldn't have thought to have done this without the following:

- https://github.com/joelparkerhenderson/git_commit_template
- https://karma-runner.github.io/0.10/dev/git-commit-msg.html
- https://seesparkbox.com/foundry/semantic_commit_messages

## Any thoughts?

Contributions are welcome!