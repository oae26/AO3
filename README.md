GITHUB REPOSITORY:
oae26/AO3 (github.com)
PART 1: Directions on Using Webstorm.

 1: Install WebStorm from JetBrains, to do this, you will want to have it integrated with an NJIT education license. The link to download it from is https://www.jetbrains.com/student/ 
2: Next, you will want to install Git, as a local program, it’ll already offer you a version compatible with your machine. https://git-scm.com/downloads
3: Create a GitHub account. https://github.com/join 
4: Open WebStorm, and press CTRL+ALT+S, this will pull up system preferences, Select the version control tab, and click on Git. It’s in a drop-down menu, then on that page, you will find “Path to Git Executable” and a file browser, copy and paste the path to your git.exe from your install. 
5: Next up, you’ll want to add your GitHub password to WebStorm. CTRL+ALT+S once again, and select Appearance and Behavior, the first drop down will say “Passwords”, select that, then add a location for your password file.
6: After that’s done, head to GitHub. There’s a + sign in the upper right corner, click on it, and make a new repository. 
7: You’ll want to make the repository public too, it’ll auto default, the logo will look like a book with a bookmark. After this, click on “add readme”.
8: Click on Create.
Creating Repositories from WebStorm
1: Select VCS on the top hot bar and import into Version Control.
2: From this main page Select checkout from version control > Git. You can also select VCS follow the same steps, only difference is this is from within WebStorm. You’ll want to enter the GitHub repository name, followed by the local path. Keep in mind your Repository should look like: https://github.com/yourUCID/[Repository name].git
Creating a WebStorm File:

1: These steps are less intensive. From the top bar on WebStorm you want to choose “File”, which will create a drop down menu. Click on “New” afterwards to spawn a side menu with file options. From there you want to click on HTML File. If you want to create a CSS style sheet, select “Stylesheet” instead.
2: When you create a file, A dialog will open up, prompting you with the option to Add to git. Upon clicking Add, your local file system will be updated with the files you created.
Pushing and Committing:
3: You will then have the option to commit your changes to git, add a message to let the system know what was the context of the commit. An example of this would be “This is the initial commit”. Then, click commit on the bottom of the screen.
4: To push a change to a remote Repository, press CTRL+SHIFT+K, or VCS, Git, Push. Select your committed file and click push.
Assuming these steps are executed correctly, your file will be on GitHub.
Setting up Pages:

Click on settings in your repository, and select “master branch” to choose a GitHub page location. You should get a github.io link with your file, copy that into a browser, and check if it works.

If all these steps are successful, you have successfully learned how to push and commit to GitHub. Happy coding!

Part 2: 


•	Branch: If a main repository is a Lego foundation, consider branches to be pieces you build on the side before adding them onto the foundation. What this means is that a branch is a clone of your repository. It allows you to work on your project without altering the main version of it in case things go wrong.
•	Clone: Instead of creating a branch that lives on GitHub, clones of repositories live directly on your machine. In addition to this, they don’t require you to be online either.
•	Commit: A commit is a change to a file/set of files, these changes are usually individual. When a commit is made, Git gives it an ID, which allows you to keep track of changes in addition to who made them, and what date the changes were made. Commits in layman’s terms sort of serve as a check-in point.
•	Fetch: Fetches allow you to add changes from the remote repository to your branch on your machine without the need to commit them. Fetches give you the opportunity to look over changes before committing them to your branch.
•	GIT: an open source program for keeping track of changes in your text files. GIT was created by Linus Torvalds and is the core basis that GitHub is built on.
•	GitHub: GitHub is a service for hosting software development and controlling versions of programs using Git.
•	Merge: Merging is the act of putting all changes in your branches and merging them with each other. I previously mentioned branches acting as Lego pieces you build on the side, and merging is putting those Lego pieces all together to your piece.
•	Merge Conflict: Merge Conflicts are what happens when two people change the same part of your project, or if for example I edit a file, and then my group member erases that same file. You must resolve these conflicts before being able to merge again.
•	Push: Pushing is the equivalent of shipping out your committed changes you’ve made to a remote repository on GitHub. This allows everyone working on a project to have access to your changes. 
•	Pull: Pulls are when you fetch in changes and merge them with your existing files. For example, I edit a CSS file in our remote repository, and push that change, if my friend wants to edit it, they must pull that file.
•	Remote: A remote version of your repository or branch that isn’t stored on your machine. These are usually on GitHub.com, the good part of this is that remote versions of repositories/branches can link to local clones on your machine. This keeps your changes up to date and flowing steadily.
•	Repository: The foundational element of GitHub. If a GitHub project is a Lego set, consider repositories, the first piece you build that houses the entire set on it. Repositories contain all the project’s files and history of changes. These can have multiple people working on them and have the option to be public or private.


References: 
GitHub glossary - GitHub Docs
IntroToGitHub-20190318.pptx: IS117004-Intro to Website Development (instructure.com)
