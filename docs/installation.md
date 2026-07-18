# Getting Started with Unminal Engine

!!! warning "System Requirements"
    - __Operating System:__ Windows 10 or higher
    - __Required:__ [.NET SDK](https://dotnet.microsoft.com/download)
    - __Installation Guide:__ [Microsoft Learn](https://learn.microsoft.com/dotnet/core/install/windows)

---

##  Installation

There are two main ways to install the engine:

### Method 1: Via Git (Recommended)

This method allows you to easily update the project in the future.

1. __Install Git__ from the [official website](https://git-scm.com/install/windows)

2. __Open a terminal__ (PowerShell or Command Prompt)

3. __Clone the repository:__
``` bash
git clone https://github.com/dovintc-off/Unminal-Engine.git
```

4. __Navigate to the project folder:__
``` bash
cd Unminal-Engine
```

5. __Remember the path__ to the folder — you will need it to open the project in an IDE

> 💡 __Advantage:__ Easy updates via `git pull`

---

### Method 2: Download ZIP Archive 📥

A simple way to get started quickly without using Git.

1. Go to the [repository page](https://github.com/dovintc-off/Unminal-Engine)

2. Click the green __"<> Code"__ button

3. Select __"Download ZIP"__ from the dropdown menu

4. After downloading, extract the archive to a convenient location

!!! tip Extraction Tools
    - Windows 11: Built-in ZIP support
    - Windows 10 and older: 
        - [7-Zip](https://www.7-zip.org/) (Free, recommended)
        - [WinRAR](https://www.win-rar.com/predownload.html)

---

## 💻 Running and Editing Code

### Recommended IDEs

| IDE | Link | Note |
|-----|------|------|
| __Visual Studio Code__ | [Download](https://code.visualstudio.com/download) | Lightweight, requires extension setup |
| __Visual Studio 2022__ | [Download](https://visualstudio.microsoft.com/downloads/) | Full-featured IDE from Microsoft |
| __JetBrains Rider__ | [Download](https://www.jetbrains.com/rider/download/?section=windows) | Cross-platform IDE for .NET |

### Setting up Visual Studio Code

If you choose VS Code, install the following extensions:

1. __C# Dev Kit__ — Core C# support
2. __.NET Install Tool__ — Manage .NET SDK
3. __IntelliCode for C#__ — Enhanced IntelliSense suggestions
4. __GitLens__ — Git integration (if using Method 1)

> 💡 __Tip:__ For quick navigation, use `Ctrl + Click` to jump to method and class definitions.

---

## ▶️ First Run

1. Open the project folder in your chosen IDE
2. Wait for NuGet dependencies to restore
3. Locate the solution file `.sln` or project file `.csproj`
4. Press __F5__ or click the __"Run"__ button to start

---

##  Having Issues?

- 📖 Read the full [documentation](architecture.md)
- Report a bug on [GitHub Issues](https://github.com/dovintc-off/Unminal-Engine/issues)

---

!!! info Next Steps
    After successful installation, check out the __[Engine Architecture](architecture.md)__ section to understand the project structure.