# <p align="center">IntelliCommit</p>
IntelliCommit (Intelligent Commit) uses AI to generate your commit message in GitHub.

## The Idea
### Web Browser Extension
The idea of IntelliCommit being a web extension as a starter would be awesome - and here is how it would work. It would, obviously, always have read & write permissions on github.com. When it detected the user at github.com/usrname/repo/blob/tree/editing blah blah, it would take a quick "snapshot" of the original code. once done making changes, it will run a prompt through AI and generate a commit message that will automatically be inserted into the commit message popup.

### GitHub Bot
As a GitHub Bot, the possibilites of IntelliCommit could go even further. Comparing the last commit and the one just released, it would check for a comment that says `IntelliCommit Active` or otherwise. Once a commit is detected that contains the comment, it will add
1. done to the ending of the comment, with the AI generated commit message
2. done! if the "done" is already there
3. Swap between done & done!

### Succesor: Changelogs Online
Instead of using traditional README changelogs that forced you to type it out on your own, easily publish your changelogs with the most recent commit messages, the file, branch, and other changelog information that could be needed for a project. Works 25x better with IntelliCommit.

## Navigating
### Branches
There are multiple branches setup with different code.
- `readme` - README files, licenses, security, policies, and more.
- `chrome-ext` - Source code for the chrome extension of IntelliCommit.
- `www` - Cloudflare Pages production branch for IntelliCommit.
- `www-beta` - gh-pages beta production branch for IntelliCommit.
- `blank` - A blank branch with nothing on it, for creating new branches.


## Ending
(c) 2023 dinoisfun. All rights reserved.<br>Open source rules all!
### Contributors/Other Projects
<b>Contributors</b><br>
disnos9<br>

<b>Projects Used</b><br>
Cloudflare DDOS Protection<br>
Cloudflare Pages<br>
Cloudflare AI<br>
