# 123Code

> **_NOTE:_**  It is **strongly recommended** that you use the [Insiders Edition of Visual Studio Code](https://code.visualstudio.com/insiders/), which is updated daily, and includes the latest and most up-to-date features.

_123Code_ is a curated set of VS Code extensions for **starting to develop without worrying about to destroy your machine**.

## prepare your environment in 1, 2, 3 seconds and then begin to code

**123Code** allows you to use a container, remote machine, or the [Windows Subsystem for Linux](https://docs.microsoft.com/windows/wsl) (WSL) as a full-featured development environment. You can:

* Develop on the **same operating system** you deploy to or use **larger or more specialized** hardware.
* **Separate** your development environment to avoid impacting your local **machine configuration**.
* Make it easy for new contributors to **get started** and keep everyone on a **consistent environment**.
* Use tools or runtimes **not available** on your local OS or manage **multiple versions** of them.
* Develop your Linux-deployed applications using the **Windows Subsystem for Linux**.
* Access an **existing** development environment from **multiple machines or locations**.
* Debug an **application running somewhere else** such as a customer site or in the cloud.

No source code needs to be on your local machine to get these benefits. Each extension in the Remote Development extension pack can run commands and other extensions directly inside a container, in WSL, or on a remote machine so that everything feels like it does when you run locally.


## Tutorial
[How to develop in remote environments](https://the.cognitiveservices.ninja/blog/2021/05/30/visual-studio-code-remote-development.html)


## Elements of the extension pack

### Containers
#### [Remote Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
Open any folder or repository inside a Docker container and take advantage of Visual Studio Code's full feature set. <br>

* Develop with a consistent, easily reproducible toolchain on the same operating system you deploy to.
* Quickly swap between different, separate development environments and safely make updates without worrying about impacting your local machine.
* Make it easy for new team members / contributors to get up and running in a consistent development environment.
* Try out new technologies or clone a copy of a code base without impacting your local setup.

#### [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
Makes it easy to create, manage, and debug containerized applications.
<br>
The Docker extension makes it easy to build, manage, and deploy containerized applications from Visual Studio Code. It also provides one-click debugging of Node.js, Python, and .NET Core inside a container.

#### [Docker Explorer](https://marketplace.visualstudio.com/items?itemName=formulahendry.docker-explorer)
Manage Docker Containers, Docker Images, Docker Hub and Azure Container Registry


### Windows Subsystem Linux 
#### [Remote WSL](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl)
Open any folder in the Windows Subsystem for Linux (WSL) and take advantage of Visual Studio Code's full feature set.
<br>
let you use VS Code in WSL just as you would from Windows.

### Remote Repositories
#### [Remote Repositories](https://marketplace.visualstudio.com/items?itemName=GitHub.remotehub-insiders)  
Remotely browse and edit a GitHub repository (preview)
<br>
* Open any GitHub repository directly from GitHub — no cloning or local repository required
* Quickly search for a repository or pull request to open — can also copy/paste links directly from GitHub
* Repositories are always opened to the latest version on GitHub, unless you have uncommitted changes
* Similar to editing directly on GitHub, committing changes will go directly to GitHub — no pushing or publishing branches required
* Working changes are independent to the branch — allows working on multiple branches simultaneously!
   * When you pause work on one branch and switch to another one, you don’t need to stash your changes — they’ll stay on the previous branch, and when you go back, your changes will be there to pick up right where you left off
* Automatically detects if there are new changes on GitHub.
   * An indicator of the number of unpulled commits will be shown in the status bar
   * Files with potential merge conflicts (e.g. you've modified the same file as someone else) will be highlighted
* Options to continue working in a more powerful environment
   * When you choose Continue Working on... from the Command Palette or from the remote indicator, you're presented the option to continue your work locally, in a container volume (if you have the Remote - Containers extension), or in GitHub Codespaces

### Remote (Virtual) Machines
#### [Remote SSH](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)
Open any folder on a remote machine using SSH and take advantage of VS Code's full feature set
<br>
* Develop on the same operating system you deploy to or use larger, faster, or more specialized hardware than your local machine.
* Quickly swap between different, remote development environments and safely make updates without worrying about impacting your local machine.
* Access an existing development environment from multiple machines or locations.
* Debug an application running somewhere else such as a customer site or in the cloud

#### [Azure Virtual Machine](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurevirtualmachines)
Create and manage Azure Virtual Machines directly from VS Code.

#### [Azure Account](https://marketplace.visualstudio.com/items?itemName=ms-vscode.azure-account)
The Azure Account extension provides a single Azure sign-in and subscription filtering experience for all other Azure extensions. It makes Azure's Cloud Shell service available in VS Code's integrated terminal.

### General Helpers
#### [Windows Terminal Integration](https://marketplace.visualstudio.com/items?itemName=Tyriar.windows-terminal)
Windows Terminal Utility for VS Code.
<br>
* Open Windows Terminal from Command Palette
* Open Windows Terminal from Status bar
* Open Windows Terminal' settings.json

#### [Stack Overflow Search](https://marketplace.visualstudio.com/items?itemName=gcrev93.StackSearchExt)  
Extension made to do a stack overflow search straight from VSCode
<br>
Open a particular Windows Terminal using the default profile or selecting a custom one on a folder via the explorer's right click context menu.

### Collaboration
#### [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack)  
Collection of extensions that enable real-time collaborative development with VS Live Share.  
<br>
This extension pack includes everything you need to start collaboratively editing and debugging in real time, including integrated audio and text chat. This provides you and your team/class with a one-click installation, in order to begin pair programming, performing remote code reviews, driving interactive lectures, and more, without needing to leave Visual Studio Code.

#### [GistPad](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.gistfs)  
Manage your code snippets and developer notes using GitHub Gists and repositories.  
You can open, create, delete, fork and star gists and repositories, and then seamlessly begin editing files as if they were local, without ever cloning, pushing or pulling anything.

## Contributions are welcome
if you come across an extension that enhances your productivity, please feel free to submit a pull request to add it!

## .devcontainer - as a proof of concept
The extionsion pack itself is being created with this ideas and elements. 
vsce to package and publish is available within the development container within this repository, there is no need to install vsce in your local environment.

