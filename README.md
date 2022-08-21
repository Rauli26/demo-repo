# Demo

Learning Git commands following https://www.youtube.com/watch?v=RGOj5yH7evk

Edited the file

---

1. Install XCode's command line tools.
   $ xcode-select --install

2. Install Homebrew package manager
3. Using Homebrew install openssl
   $ brew install openssl

4. Clone the git source
   $ git clone https://github.com/git/git.git
   eg git clone git@github.com:Rauli26/demo-repo.git. -> It will pull down the repo into the directory I am in

5. Install code editor -> Visual studio code

6. Open one empty folder in VS Code -> clone the git rep -> Change directory to the folder (cd demo-repo)

7. dot get directory -> Hidden folder in the git repo folder
   There is special command to show that folder la command is Mac shorthand for ls space dash la which means list everything in that directory(ls -la).

8. There is something called dot git -> These hidden git folder actually stores all of that files that save your commits or code changes over time.
   It has all of the changes recorded in the history of this repository which includes the once we made in github.com.

## Subheader Local code

Syarting making changes locally using VS Code.

1. Save the changes to git -> Do that though a commit

a) git status -> Shows all the files that were modified/updated/created/deleted but haven't been saved in a commit yet.

Untracked files: git doesn't know anything about this file.
git add <filename> -> command to tell git which file to track
git . -> Means tack all the files which is listed in git status in both the untrackt and modified section(git period)
So both the file README.md and index.html will be staged with Git if we did "git add . "

3. git commit -m "Added index.html from local" -m "Some description"

Even after commit we saved it locally. Commit isn't live on Github yet. We make it live by using another git command "git push"
