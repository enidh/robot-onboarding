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
* hit windows key+R, type `cmd` and hit Enter
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
**when starting the installation be sure to check the box `Add Python to PATH`, keep
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
    * follow the steps in the browser. Allow the page to open vscode when prompted.
    * in vscode, allow the extension to open the URI when prompted.
* type in the repository name, e.g. `enidh/robot-onboarding` and hit `Enter`
* choose a folder for the project. e.g. you can create a `git` folder and keep all 
projects there
* choose to open the cloned repository when prompted
* happy coding!
* vscode does not autosave so be sure to save your changes on each file.

## Committing and pushing changes to a project
* go to the `Source Control` view (third button on the vertcal bar on the
left)
* **review** your changes (really, review them, see the section on Commit
Hygiene for details)
* if everything looks okay, hover over `v Changes` and hit the `+` button
to stage all changes
* hit the `✓` button on top next to `Source Control` to commit your
changes. Write your commit message when prompted - make it *concise* and
*descriptive*
* hit `Ctrl + Shift + P`, type `push` and hit enter
