:wave: Hi! This one is the terminal version of Git-it, now I am working on the desktop app version. Everything else same. Want to try? Download from here: [github.com/jlord/git-it-electron/releases](https://github.com/jlord/git-it-electron/releases). In the end this terminal version will kena replace :pizza:

# Git-it

| :computer: | What is this? |
| --- | --- |
| ![ss](https://raw.githubusercontent.com/jlord/git-it/master/git-it-ss.png) | A [workshopper](https://github.com/workshopper/workshopper) module for learning Git and GitHub.

Actually this is like a terminal app for you all to finish one by one the challenges. [nodeschool.io](http://nodeschool.io) got more info.

## Hello, future Forkers, Branchers and Pull Requesters!

Run this app in your Mac Terminal or Bash prompt for Git and GitHub homework. This one is 100% _real_ terminal (then can learn  the tok kong command line), then also got use _real_ Git and GitHub. So ah, when you finish all the challenges, your GitHub account will got _real_ repos (some say repositories) and green squares in your [contribution chart](https://github.com/blog/1360-introducing-contributions) one.

![contributions](https://raw.githubusercontent.com/jlord/git-it/master/ghcc.png)

Here are the Git-it [challenge table of contents](http://jlord.github.io/git-it) so you know we are covering what.

You hosting workshop? You developer? Read the links here: [Contributing](https://github.com/jlord/git-it/blob/master/CONTRIBUTING.md) //  [Troubleshooting](https://github.com/jlord/git-it/blob/master/TROUBLESHOOT.md) //  [New Version in Progress!](https://github.com/jlord/git-it-electron)

### Get Started

Sections: [Install all these first](https://github.com/jlord/git-it/blob/master/README.md#what-youll-need-to-run-git-it) // [Then install Git-it](https://github.com/jlord/git-it/blob/master/README.md#install-git-it) // [How to Use Git-it ](https://github.com/jlord/git-it/blob/master/README.md#how-it-works) // [Tips](https://github.com/jlord/git-it/blob/master/README.md#tips-for-getting-started)

---

### What you need to run Git-it:

_Down here all damn important thing for development. Free one. Sometimes even free and open source._

- **Git**, so you know who change what and when!
 - If you use **Windows, download [GitHub Desktop](http://desktop.github.com)**, inside got Git oredi, then use the **Git Shell** for your terminal.
 - If you use **Mac**, you can one-shot install Git. Just go spotlight, open Terminal, then type `git`. Git see oredi will install the rest of the command line tools. Very fast, few minutes only. They also ask you you want Xcode or not. That one dun care ne'mind.
- **Node.js**, you need this to run this app because it is a Node.js app. Download oredi your computer become a server that can run JavaScript, and this will hide in background dun make noise one. You can **download Node [here](https://nodejs.org/en/download/)** (Mostly just choose the **Windows `.msi`** or **Mac `.pkg`** one can oredi).
 - If you got Node and npm liao, make sure your npm at least must be v 1.4.3 OK?
- **Text Editor**, if dun have yet, just get one for code*. Choose one: [Atom](https://atom.io/), [Sublime Text](http://www.sublimetext.com/2), [Textmate](http://macromates.com/download), [Brackets](http://brackets.io/).
- **English locales**, because now the backend is English only. If your system got use different language, please find for the correct section in the file [TROUBLESHOOT.md](https://github.com/jlord/git-it/blob/master/TROUBLESHOOT.md).

_*This Git-it actually no need "coding" one, so you want to use the default Notepad or TextEdit also can._

### Install Git-it

On top the thing all install oredi, install Git-it.

- Open up a terminal window and install Git-it globally on your computer (so anywhere also can run). [NPM](https://www.npmjs.com/) (**the Node.js package inside got**) will deliver Node.js modules like this app to your computer from the command line:

```bash
$ npm install -g git-it
```
- _If you run this command got problem maybe you no permission, **try again with 'sudo'**:_ `sudo npm install -g git-it`
- Finish oredi can run:

```bash
$ git-it
```
- Can see menu means good to go. Choose the first challenge, press enter then can oredi!

### How it Works

- From the `git-it` menu, use the arrows ↑↓ to choose the first challenge and press 'enter'.
- Challenge load oredi, follow the instructions at the bottom to see the guide. _Preview a web hosted version of the guide [here](http://jlord.github.io/git-it)._

![img](https://raw.githubusercontent.com/jlord/git-it/master/guide-ss.png)

- Follow the instructions in the guide to do the tasks in your terminal.
- Do finish already, type `git-it verify` in terminal.
- If never do swee-swee, Git-it will tell you what went wrong.
- Run `git-it` again to load the menu and choose the next challenge!

**Got questions, just put a [new issue](https://github.com/jlord/git-it/issues/new) or see the [troubleshooting doc](https://github.com/jlord/git-it/blob/master/TROUBLESHOOT.md).**

---

### Tips For Getting Started

**Code snippets** look like `$ some code-stuff --here`. The dollar sign means the line is like command line one, but the dollar sign actually no need to type. So just type `some code-stuff --here`.

**Variables** look like `<VARIABLENAME>` in code. When you actually use the code, put your variable there. So for example, to make a new folder in terminal we say, `mkdir <FOLDERNAME>`, that means if you want to make a folder named 'octocat', you type: `mkdir octocat`.

**Command line, terminal, bash** all basically the same: black-black is screen, white-white is words. Damn power one. You can  control your computer with text.

Your terminal can do a lot of things like delete, rename, copy or create files and folders, run scripts and send things here and there between servers (like the ones storing things on GitHub.com) and your computer (also a server!).
