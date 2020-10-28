# robot-onboarding
Onboarding docs for the robotics club

## Setting up your development environment - Windows

### Installing Everything
* Register a github account if you don`t have one already at https://github.com/join
    * ask the club to add your github username to the team

* Get vscode at https://code.visualstudio.com/download
    * install vscode with default options

* Get git at https://git-scm.com/download/
    * install git with default options EXCEPT:
    * when you reach `Choosing the default editor used by git` change it to 
an editor of your choice (if you're at all unsure, pick `Use Visual Stodio Code as 
Git's default editor`)
* hit `windows key + R`, type `cmd` and hit Enter
    * paste this into the command line, replacing with your name, and hit `Enter`:
        ```
        git config --global user.name "Joana Santos"
        ```
    * paste this into the command line, replacing with your email, and hit `Enter`:
        ```
        git config --global user.email "joanasantos@mail.com"
        ```
    * close the command line

* Get pyhton 3.9 at https://www.python.org/ftp/python/3.9.0/python-3.9.0-amd64.exe
    * when starting the installation be sure to check the box `Add Python to PATH`, keep
defaults for everything else

* hit windows key+R, type `cmd` and hit Enter
    * paste this into the command line:
    ```
    code --install-extension vsciot-vscode.vscode-arduino
    code --install-extension ms-python.python
    code --install-extension eamodio.gitlens
    echo 'done!'
    ```
    * close the command line


## Cloning and opening a project
* open vscode
* hit `Ctrl + Shift + P`
* type `clone` and hit `Enter`
* pick `Clone from GitHub`
    * for the first time you're doing this: a window will appear saying that the extension
Github wants to sign in. Click `Allow`
to open a new browser tab
    * follow the steps in the browser. Allow the page to `Open Link` with
    vscode when prompted.
    * in vscode, allow the extension to `Open` the URI when prompted.
* type in the repository name, e.g. `enidh/robot-onboarding` and hit `Enter`
* choose a folder on your computer to clone the project to. You could for example create
a `git` folder in your `Documents` and keep all projects there, for simplicity and easy access
* choose to `Open` the cloned repository when prompted (in the lower right corner)
* happy coding!
* vscode does not autosave so be sure to save your changes on each file.

## Committing and pushing changes to a project
* don't forget to save!
* go to the `Source Control` view (third button on the vertcal bar on the
left)
* **review** your changes (really, do actually review them, 
[see the basics on commit hygiene](#commit-hygiene))
* if everything looks okay, hover over `v Changes` to show additional buttons
 and hit the `+` button next to it to stage all changes
    * do not confuse that with the `+` buttons next to each file - hitting
    one of those will only stage that particular file.
* hit the `✓` button on top next to `Source Control` to commit your
changes. Write your commit message when prompted - make it *concise* and
*descriptive*
* hit `Ctrl + Shift + P`, type `push` and hit enter
    * for the first time you're doing this: a window will appear asking you
    to sign in to GitHub. click the button
    * follow the steps in the browser.
* after committing, you can also hit the `🗘` button in the blue bar at the
bottom instead of pushing the way described above - this will push any 
commits **and** pull new changes from remote.

## Commit hygiene
TODO

## Merge conflicts
TODO

