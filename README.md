# A03: Git/Webstorm/Github/Tutorial
## Part 1: Directions on Using WebStorm
[WebStorm](https://www.jetbrains.com/webstorm/) is an integrated development environment (IDE) designed by JetBrains for coding in JavaScript, as well as other web development languages, such as HTML and CSS.

### Setting up Webstorm, Git, and Github
1. Apply for a WebStorm license and download the software [here](https://www.jetbrains.com/community/education/). They provide free licenses to students upon identification.
2. Install **Git** locally on your device [here](https://git-scm.com/downloads).
3. Register for a **Github** account [here](https://github.com/join).
4. Next, we can set up Git with Webstorm, allowing you to **push** content from your local **repository** to a remote **repository** on **Github**. In Webstorm, perform Ctrl+Alt+S to access the Settings.
6. From here, go to Version Control > **Git**, and locate your **Git** executable path. Enter this information in the "Path to **Git** executable" box.

### Linking your Github to Webstorm
1. In Webstorm, perform Ctrl+Alt+S to access the Settings.
2. From here, go to Version Control > **Github**.
3. Select "+" and select "Log in via **Github**".
4. A browser window should open asking you to sign into your **Github** account, which will automatically link the account to your Webstorm application.

### Open a repository from Github in Webstorm
1. In Webstorm, select File > New > Project.
2. Choose "Empty Project" from the dropdown menu.
3. From the top toolbar, select "VCS" (Version Control System) > Get From Version Control
4. From here, you can either paste the URL of the **repository** you want to link to Webstorm, or select your **Github** account on the left side and choose the **repository** from there.

## Part 2: Glossary
- **Branch** - allows you to isolate edits without effecting the original repository.
- **Clone** - a copy of a repository that you can store locally and sync to Github.
- **Commit** - an individual change made to a file, marked with a unique identifier that can be used to refer to a previous change and often contain a description of what was changed.
- **Fetch** - adds a change from another repository to your local branch without a **commit**.
- **Git** - an open-source version control system to track changes in files.
- **Github** - a version control platform utilizing Git that allows users to host and collaborate on projects.
- **Merge** - combines two branches.
- **Merge Conflict** - occurs when an attempted branch merge fails.
- **Push** - syncs your committed changes from a local repository with a remote repository.
- **Pull** - syncs your commited changes from a remote repository with a local repository.
- **Remote** - refers to a repository hosted over the internet, such as Github.
- **Repository** - workspace containing all of your project's files and each file's revision history.

## References
- [JetBrains](https://www.jetbrains.com/)
- [GitHub glossary](https://docs.github.com/en/get-started/quickstart/github-glossary)
