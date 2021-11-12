# dump-internship-git-1
First internship homework: Git. We were given a task to build tic-tac-toe game using git. Each team member creates their own repository, adds another person as a collaborator and opens a branch where he/she initializes three C# projects. After the project is initialized within the branch, the person whose repository it is, opens a pull request and sets another person as the reviewer. The other person is in charge of checking the code and in case everything is good approves the change and leaves a comment with and appropriate message. In other case he/she points out mistakes and also leaves a comment with an appropriate message, After the pull request has passed the review process, the changes are released to the main. Now the game begins. The goal is to play all three games at the same time, which means that every time a person plays a move (with the help of commit), he plays it in all three files. Each person opens their own branch in which the play moves, and each move must go through a separate pull request and review of the opponent. Several conflicts must occur during gameplay and the way to resolve them in the first person repository in a pair is with the help of git merge, and in the repository of the second person in a pair with git rebase.
