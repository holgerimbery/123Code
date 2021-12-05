![CICD Release Pipeline](https://github.com/the-cognitiveservices-ninja/123Code/actions/workflows/main.yml/badge.svg)

### 123Code

[Microsoft Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=holgerimbery.123code)  

> It is **strongly recommended** that you use the [Insiders Edition of Visual Studio Code](https://code.visualstudio.com/insiders/), which is updated daily and includes the latest and most up-to-date features.  

**123Code** is a curated set of VS Code extensions for **starting to develop without worrying about to destroy your machine**.  
**123Code** allows you to use a container, remote machine, or the [Windows Subsystem for Linux](https://docs.microsoft.com/windows/wsl) (WSL) as a full-featured development environment. You can:

* Develop on the **same operating system** you deploy to or use **larger or more specialized** hardware.
* **Separate** your development environment to avoid impacting your local **machine configuration**.
* Make it easy for new contributors to **get started** and keep everyone on a **consistent environment**.
* Use tools or runtimes **not available** on your local OS or manage **multiple versions** of them.
* Develop your Linux-deployed applications using the **Windows Subsystem for Linux**.
* Access an **existing** development environment from **multiple machines or locations**.
* Debug an **application running somewhere else** such as a customer site or in the cloud.

No source code needs to be on your local machine to get these benefits. Each extension in the Remote Development extension pack can run commands and other extensions directly inside a container, in WSL, or on a remote machine so that everything feels like it does when you run locally.

### Tutorial

The tutorials below will walk you through running Visual Studio Code with the Remote Development extensions.

* [Remote via SSH](https://code.visualstudio.com/docs/remote/ssh-tutorial)
  Connect to remote and virtual machines with Visual Studio Code via SSH.
* [Work in WSL](https://code.visualstudio.com/docs/remote/wsl-tutorial)
  Run Visual Studio Code in Windows Subsystem for Linux.
* [Develop in Containers](https://code.visualstudio.com/docs/remote/containers-tutorial)
  Run Visual Studio Code in a Docker Container.
* [GitHub Codespaces](https://docs.github.com/github/developing-online-with-codespaces/using-codespaces-in-visual-studio-code)
  Connect to a codespace with Visual Studio Code.

### Video

[![Demo](https://j.gifs.com/MZ9ElB.gif)](https://www.youtube.com/watch?v=8CSLgsIS_2k)  

* *open* a repository to edit it without cloning it to a local filesystem
* clone a repository to a container to edit or take actions on it, here: execute a task  

### Elements of the extension pack

#### Containers

##### [Remote Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

Open any folder or repository inside a Docker container and take advantage of Visual Studio Code's full feature set. <br>

* Develop with a consistent, easily reproducible toolchain on the same operating system you deploy to.
* Quickly swap between different, separate development environments and safely make updates without worrying about impacting your local machine.
* Make it easy for new team members / contributors to get up and running in a consistent development environment.
* Try out new technologies or clone a copy of a codebase without impacting your local setup.

##### [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)

Make it easy to create, manage, and debug containerized applications.
<br>
The Docker extension makes it easy to build, manage, and deploy containerized applications from Visual Studio Code. It also provides one-click debugging of Node.js, Python, and .NET Core inside a container.

##### [Docker Explorer](https://marketplace.visualstudio.com/items?itemName=formulahendry.docker-explorer)

Manage Docker Containers, Docker Images, Docker Hub, and Azure Container Registry

#### Windows Subsystem Linux

##### [Remote WSL](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl)

Open any folder in the Windows Subsystem for Linux (WSL) and take advantage of Visual Studio Code's full feature set.
<br>
let you use VS Code in WSL just as you would from Windows.

#### Remote Repositories

##### [Remote Repositories](https://marketplace.visualstudio.com/items?itemName=GitHub.remotehub-insiders)  

Remotely browse and edit a GitHub repository (preview)
<br>

* Open any GitHub repository directly from GitHub — no cloning or local repository required
* Quickly search for a repository or pull request to open — can also copy/paste links directly from GitHub
* Repositories are always opened to the latest version on GitHub unless you have uncommitted changes
* Similar to editing directly on GitHub, committing changes will go to GitHub — no pushing or publishing branches required
* Working changes are independent to the branch — allows working on multiple branches simultaneously!
  * When you pause work on one branch and switch to another one, you do not need to stash your changes — they’ll stay on the previous branch, and when you go back, your changes will be there to pick up right where you left off
* Automatically detects if there are new changes on GitHub.
  * An indicator of the number of unpulled commits will be shown in the status bar
  * Files with potential merge conflicts (e.g. you've modified the same file as someone else) will be highlighted
* Options to continue working in a more powerful environment
  * When you choose to Continue Working on... from the Command Palette or the remote indicator, you will have the option to continue your work locally, in a container volume (if you have the Remote - Containers extension), or in GitHub Codespaces

#### Github Codespaces

##### [GitHub Codespaces](https://marketplace.visualstudio.com/items?itemName=GitHub.codespaces)

for Github Codespaces - a instant dev environment  

[GitHub Codespaces](https://github.com/features/codespaces) provides cloud-hosted development environments for any activity - whether it's a long-term project, or a short-term task like reviewing a pull request. You can connect to Codespaces from Visual Studio Code or a browser-based editor that's accessible anywhere.

Additionally, GitHub Codespaces brings many of the benefits of DevOps, which have typically been reserved for production workloads, like repeatability and reliability, to development environments. GitHub Codespaces is also personalizable to allow developers to leverage the tools, processes and configurations that they have come to love and rely on - truly the best of both worlds!

#### Remote (Virtual) Machines

##### [Remote SSH](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)

Open any folder on a remote machine using SSH and take advantage of VS Code's full feature set
<br>

* Develop on the same operating system you deploy to or use larger and faster or more specialized hardware than your local machine.
* Quickly swap between different, remote development environments and safely make updates without worrying about impacting your local machine.
* Access an existing development environment from multiple machines or locations.
* Debug an application running somewhere else, such as a customer site or in the cloud

##### [Azure Virtual Machine](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurevirtualmachines)

Create and manage Azure Virtual Machines directly from VS Code.

##### [Azure Account](https://marketplace.visualstudio.com/items?itemName=ms-vscode.azure-account)

The Azure Account extension provides a single Azure sign-in and subscription filtering experience for all other Azure extensions. It makes Azure's Cloud Shell service available in VS Code's integrated terminal.

#### General Helpers

##### [Github Actions](https://marketplace.visualstudio.com/items?itemName=cschleiden.vscode-github-actions)

GitHub Actions workflows and runs for github.com hosted repositories in VS Code

##### [PowerShell](https://marketplace.visualstudio.com/items?itemName=ms-vscode.PowerShell)

Develop PowerShell modules, commands and scripts in Visual Studio Code!
<br>
This extension provides rich PowerShell language support for Visual Studio Code (VS Code). Now you can write and debug PowerShell scripts using the excellent IDE-like interface that Visual Studio Code provides.

This extension is powered by the PowerShell language server, PowerShell Editor Services. This leverages the Language Server Protocol where PowerShellEditorServices is the server and vscode-powershell is the client.

Also included in this extension is the PowerShell ISE theme for Visual Studio Code. It is not activated by default, but after installing this extension either click "Set Color Theme" or use the theme picker and select "PowerShell ISE" for a fun and familiar experience.

##### [Stack Overflow Search](https://marketplace.visualstudio.com/items?itemName=gcrev93.StackSearchExt)  

Extension made to do a stack overflow search straight from VSCode
<br>
Open a particular Windows Terminal using the default profile or select a custom one on a folder via the explorer's right-click context menu.

#### 123Family

please find other extension packs [one-two-three](https://marketplace.visualstudio.com/publishers/holgerimbery)

### Contributions are welcome

if you come across an extension that enhances your productivity, please feel free to submit a pull request to add it!
