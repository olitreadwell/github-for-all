# GitHub for All

This repository holds a companion README for the "GitHub for All" talk — a short lesson/presentation designed for non-developer startup founders and early-stage teams who want to learn the fundamentals of version control, Git, and GitHub so they can leverage GitHub features effectively.

## Who this is for

- Non-technical founders and startup operators
- Early-stage teams who want to manage documentation, product specs, and simple release workflows
- Students or community organisers preparing workshops on Git & GitHub

## Learning objectives

By the end of this session participants will be able to:

- Explain what Git and GitHub are and why they matter
- Initialize a repository, make commits, and understand the commit history
- Create branches and open pull requests (PRs) to collaborate safely
- Use GitHub features useful to startups (Gists, Issues, Projects, Actions, Releases)
- Discover learning resources and programs like GitHub for Startups and the Student Developer Pack
- Know where to find helpful tools: VS Code, GitHub Copilot, and curated lists of resources

## Suggested talk structure (30–45 minutes)

1. Quick intro & motivation (5 min)
	- Why version control matters even for non-devs (tracking changes, audit trail, collaboration)
2. Git basics demo (10–12 min)
	- init, add, commit, log
	- remote: add, push, clone
3. Branches & Pull Requests (10–12 min)
	- create a branch, make a change, open a PR, request review, merge
	- show a real PR on GitHub UI and explain checks and merge options
4. Useful GitHub features for startups (5–8 min)
	- Gists, Issues, Projects (or Discussions), Releases, GitHub Actions (brief)
5. Tools & learning resources (5 min)
	- VS Code, Copilot, Awesome lists, learning pathways
6. Q&A and next steps (remaining time)

## Key topics & short notes

- Git vs GitHub: Git is the distributed version control system; GitHub is a cloud hosting platform with collaboration features built on Git.

- Commits & history: commit messages are your team's record. Small, focused commits are easier to review and revert.

- Branching model: use feature/topic branches for changes. Default branch (often `main`) holds stable content.

- Pull Requests: the collaboration primitive for proposing, reviewing, and merging work. PRs are where discussion, review, and CI checks happen.

- Conflicts: explain why they happen and how to resolve (rebase vs merge, quick demo or screenshot).

## Analogies — simple metaphors to explain VCS, Git, and GitHub

Use these short analogies when explaining concepts to non-technical audiences; they're quick to remember and map well to how people already collaborate on documents.

- Version Control System (VCS) — "Document save history": imagine a Word doc where every time you save there's a perfectly preserved copy labeled with who saved it and why. VCS keeps that history for your whole project and lets you go back to any saved copy.

- Git — "Personal notebook with change snapshots": think of Git as a local notebook that records snapshots of your work (commits). You can make notes privately, create branches (different notebook sections) to try ideas, and merge the best parts back into the main section.

- Repository (repo) — "Project filing cabinet": a repo is like a folder or cabinet that holds all versions of your project, including its history and notes about who changed what.

- Branch — "Draft copy or alternative version": a branch is like making a copy of the document to try an edit. The original stays unchanged until you merge your edits back.

- Commit — "Save point with a sticky note": each commit is a save point plus a short note describing what changed, so teammates can understand the reason for that save.

- Pull Request (PR) — "Suggested edits and conversation": a PR is like passing your draft to a colleague with a note that says "please review these edits" — they can comment, suggest changes, and eventually accept (merge) your edits into the main document.

- Merge vs Rebase — "Combine edits vs rewrite history": merging is like adding your edited copy to the main document while keeping a record of both timelines; rebasing is like re-writing your edits so they look like they were made directly on top of the latest main document (neater history, but rewrites the past).

- Remote / GitHub — "Shared cloud filing cabinet with collaboration features": GitHub is the online version of the filing cabinet where everyone can push their local snapshots, open PRs, run checks, and discuss changes. It adds issue tracking, access controls, and integrations.

- Gist — "Sticky note you pin on the board": a quick public or private snippet you can share — great for single-file examples or short instructions.


## Demo checklist (commands to show live)

- git init
- git status
- git add README.md
- git commit -m "Add workshop README"
- git branch -M main
- git remote add origin <repo-url>
- git push -u origin main
- git checkout -b feature/update-readme
- (edit README) git add . && git commit -m "Update content"
- git push origin feature/update-readme
- Open GitHub → create Pull Request → merge

Note: When demoing with the audience, use a small test repo or a temporary repository to avoid accidental changes to production code.

## Useful links (curated)

- GitHub Learning Pathways: https://resources.github.com/learn/pathways/ — guided learning paths for different goals.
- GitHub Skills: https://skills.github.com/ — short, interactive exercises and workshops.
- GitHub for Startups: https://github.com/enterprise/startups — programs and credits for eligible startups.
- GitHub Student Developer Pack: https://education.github.com/pack/ — free tools and offers for students.
- Awesome lists (curated lists of tools/resources): https://github.com/sindresorhus/awesome

Helpful tooling

- Visual Studio Code (VS Code): lightweight code editor with great Git and GitHub integration.
- GitHub Copilot: AI assistant that suggests code and text completions (useful when writing templates, docs).
- Gists: quick way to share code snippets or single-file notes: https://gist.github.com/

## Suggested hands-on exercises (10–20 min)

1. Pair participants and have them create a public repo for notes.
2. Each pair creates a branch, edits README with a short introduction, commits, and pushes the branch.
3. Open a Pull Request and request a review from the partner. Leave at least one comment and resolve it.
4. Merge the PR and show the commit history and the “Blame” view for a line introduced earlier.

## Speaker notes / tips

- Keep language non-technical: compare Git commits to document “save points” and PRs to “suggested edits” on a shared doc.
- Emphasize small wins: using Git/GitHub for documentation and simple change tracking is valuable even without writing code.
- Have a backup recording of commands/screenshots in case live demo networking fails.
- Encourage participants to sign up for GitHub Learning Pathways and Skills after the session.

## Further reading and collections

- Awesome lists: a one-stop index of curated lists for almost any technology area — great for finding recommended tooling and resources: https://github.com/sindresorhus/awesome
- GitHub Docs: https://docs.github.com/ — authoritative docs for features and admin topics

## License

This README is provided for reuse and adaptation for workshops and talks. Treat it as CC BY (adapt and attribute as you like).

---

If you want, I can convert this into a slide deck (slides in Markdown or PDF), add speaker notes per-slide, or create a small demo repository with scripted commands and sample PRs. Tell me which follow-up you'd like next.