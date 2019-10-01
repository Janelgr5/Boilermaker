# Boilermaker

Boilerplate code for creating applications using React and the NERD stack.

---

## STEP 1: Start New Project

_A (slightly) alternative process if creating an **open source project**: https://zellwk.com/blog/best-time-to-npm-init/_

### Create Project Directory

**In Terminal**

1. `mkdir projectName` _(creates a new directory)_
2. `cd mkdir projectName` _(switch into newly created directory)_
3. `npm init -y` _(generates a package.json without having it ask any questions)_

### Create Git Repository

**In Terminal**

1. `git init` _(creates a new git repository)_
   **In Browser**
2. login to [GitHub](https://github.com)
3. click **new button** to start a new repository [New GitHub Repo](https://github.com/new)
4. **DO NOT initialize the repository with a README** (see _Add and Update README_).
5. Click **create repository** button.
6. Copy the appropriate code for cloning the repository into your directory. _(create a working copy of a local/remote repository by running the command)_
   **In Terminal**
7. Run copied code.
8. Save all files.
9. `git add .` _(stages all saved changes)_
10. `git commit -m "start project"` _(The file is committed to the HEAD, but not in your remote repository yet.)_
11. `git push origin master` _(To send those changes to your remote repository. Change master to whatever branch you want to push your changes to.)_

### Update .gitignore file

**Resources: [.gitignore](https://github.com/github/gitignore)**
Ignored files are usually build artifacts and machine generated files that can be derived from your repository source or should otherwise not be committed.
Ignored files are tracked in a special file named .gitignore that is checked in at the root of your repository.
There is no explicit git ignore command: instead the .gitignore file must be edited and committed by hand when you have new files that you wish to ignore.
.gitignore files contain patterns that are matched against file names in your repository to determine whether or not they should be ignored.

### Add and Update README

**Resource:[Documenting your projects on GitHub](https://guides.github.com/features/wikis/)**

**In Browser**

1. Click **README** button. _(Starts a README file for your project)_
2. Click **Commit** button. _(Commit, push, and merge changes to repository)_

**In README.md file**

3. Add documentation using Markdown
   A. [Markdown documentation from the creator John Gruber](https://daringfireball.net/projects/markdown/syntax)
   B. [Markdown cheat sheet](https://www.markdownguide.org/cheat-sheet/)

<!-- | **In Terminal** | **In Browser**|
| **_ | _** |
| git add README.md | click README button|
| open README.md file | click commit button | -->

### Install Node Modules

1. npm install

---

## More Resources:

### Git Commands

\* [Git commands (basic guide)](http://rogerdudler.github.io/git-guide/)
