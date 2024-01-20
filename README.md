# Task-2

Question 1: Explain Version control:
Version control, also known as source control, is a system that allows you to track changes made to your code. This can be useful in many scenarios, such as collaboration on a project, managing changes made by different team members, or even simply being able to revert to a previous version of your code.
One of the most popular version control systems is Git. Git allows you to save different versions of your code, known as commits, each with a unique identifier. You can switch between these commits, view the differences between them, and even create new branches to experiment with different ideas.
To get started with Git, you can use a web-based platform like GitHub or GitLab, or install it on your computer and use it from the command line.
Once you have a repository set up, you can use commands like git add to stage changes, git commit to create a new commit, and git push to send your commits to the remote repository. To update your local code with the latest changes from the remote repository, you can use git pull.
By using version control, you can effectively manage your codebase, collaborate with others, and maintain a complete history of your project.

Question 2: Explain difference between git and github.
Git and GitHub are related but different. Here is a detailed explanation:
Git:
Git is a distributed version control system. It was created by Linus Torvalds in 2005 and is now maintained by the Linux kernel community.
Version control systems are software tools that help programmers manage changes to their code over time. It is commonly used for source code management in software development, but it can also be used to track changes in any set of files.
Git tracks changes by taking a snapshot of the changes in your code every time you commit. It is called a "distributed" version control system because it allows you to work on different branches of your project simultaneously. This feature helps teams to work on their project together and independently.

GitHub:
GitHub is a web-based platform for version control using Git. It offers all the distributed version control and source code management (SCM) functionality of Git as well as adding its own features.
The most prominent feature of GitHub is the ability to create public or private repositories for your projects. Public repositories are available for everyone to view, fork, and contribute to. Private repositories require a user to have access permissions.
GitHub also provides a collaboration platform called "Pull Requests." It allows users to propose changes to a project and to review and discuss those changes with the project's community before they are merged into the project's codebase.
GitHub is also home to thousands of open-source projects. It allows developers to easily find open-source projects, view their source code, and contribute to them.
GitHub provides additional features such as bug tracking, automated testing, and wikis. It is commonly used in the open-source community but is also widely used by private companies.

In summary, Git is a distributed version control system, while GitHub is a web-based platform that utilizes Git to provide version control and additional features. You can use Git without GitHub, but GitHub significantly enhances your ability to use Git.

Question 3: List 3 other github alternatives.
3 GitHub alternatives are GitLab, Bitbucket, and Gitea.
GitLab: GitLab is a web-based Git repository manager that provides a Git-repository manager, issue-tracking system, and wiki. It offers an open-source solution for self-hosting repositories and integrates well with continuous integration and continuous deployment (CI/CD) systems.
Bitbucket: Bitbucket is a Git repository hosting service that allows teams to collaborate on projects. It provides tools for visualizing repository issues, reviewing changes, and automating tasks. Bitbucket offers free plans for unlimited repositories with up to five users per repository.
Gitea: Gitea is a lightweight, open-source Git service written in Go. It provides features like user authentication, issue tracking, and repository management. Gitea is easy to set up and use, making it a suitable choice for small teams or individual developers.

Question 4: Explain the difference between git fetch and git pull.
Git fetch and git pull are two commands used to integrate changes from one repository into another.

Git fetch:
Fetch is a safe operation that retrieves the latest changes from a remote repository and updates your local repository's view of the remote one.
It downloads the changes from the remote repository but does not modify your local files.
After fetching the changes, you can inspect them, create new branches, or merge them into your local branches.
Example of git fetch:
'git fetch origin'

Git pull:
Pull is a command that fetches the latest changes from a remote repository and immediately merges them into your local repository.
It combines the functions of fetch and merge.
However, using pull can be risky, as it may cause conflicts between the local and remote branches if not handled correctly.
Example of git pull:
'git pull origin master'

In summary, git fetch retrieves changes from a remote repository while git pull fetches and merges those changes into your local repository.
