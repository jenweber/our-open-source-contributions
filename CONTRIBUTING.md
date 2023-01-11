# Contributing

Anyone can be an open source contributor! Remember as you try these steps out,
you can't break things here. Feel free to experiment!

## If you don't have git installed...
You can still help and practice by contributing to the documentation!
You can edit almost any file type from
the GitHub website by clicking on the file in the file list, which opens a page
like [this README](https://github.com/jenweber/our-open-source-contributions/blob/main/README.md).
The README is a file that ends with `.md` that is shown in the home page of a project in GitHub. MD stands
for markdown. A markdown file is just a [weirdly formatted text file](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
Whether you want to edit a markdown file or something else, click on the edit/pencil icon and walk through making a commit and pull request, all from the website itself.

## A step by step guide to code contributions
For a step-by-step guide that includes explanations for each step,
see [this article](https://medium.com/@jenweber/your-first-open-source-contribution-a-step-by-step-technical-guide-d3aca55cc5a6)

## Cheat Sheet for code contributions

For this repository, here are the steps you could practice:

1. Create or sign into a free GitHub account
2. Create or comment on an issue [here](https://github.com/jenweber/our-open-source-contributions/issues)
3. Fork the [repository](https://github.com/jenweber/our-open-source-contributions) by clicking Fork in the top right hand corner
4. Clone the repository using command line or GitHub Desktop tools (see Troubleshooting if you cloned the main repo and want to remove it)
5. Create a git branch with a unique name, `git checkout -b your-own-branchname`, no spaces in the branch name
6. Make your changes
7. `git status` to review the files you changed, and `git diff` to see which lines of code changed
8. Mark the files that you want to save with `git add path/to/the/file/you/changed.js -p`
A prompt will appear for each changes you have done per page or block of code you contributed to. You just need to add `y` or `n` to respectively approve the change and add it, or decline it (and it won't be added).
9. Commit the changes with `git commit -m "a short message including the issue number #123"`
10. `git push origin main` to add your work to the online code hosted on GitHub, on your own fork
11. Open a pull request by going to your fork, the pull request tab, and open pull request.
This project and branch "main" should be the base. Choose your branch from the "compare"
dropdown. Choose Create Pull Request. In the message, put a link to the Issue you created or
commented on, and click Create to finish. Ta da!

## Troubleshooting

I've cloned the main repo and I want to remove it locally (and start over with a forked repo)

First you need to go one folder up:
`cd ..`
Then enter the command to remove the repo. Be careful with `-rf`, because it deletes things forever from your computer.
`rm -rf our-open-source-contributions`
Once done you can check if the repo has been deleted locally:
`ls ` + TAB
--> The repo should not be present in the list anymore
