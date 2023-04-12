# Branching/testing

Created to learn/practice GitHub branches, merging and squashing commits.

## $\textcolor{yellow}{\textsf{PROCEDURE}}$
<hr>

### $\textcolor{lightblue}{\textsf{GitPod Terminal}}$
* **git checkout -b $\color{red}{\textsf{branch-name}}$**
  * Creates and places you in the created branch
  * Can switch between branches with **"checkout $\color{red}{\textsf{branch-name}}$"**
  * You can see previous commits with **"git log --oneline"**
* Do your work
* Add and commit as normal
* **git push origin $\color{red}{\textsf{branch-name}}$**
  * Pushes your work into the branch you are working on, and creates the branch in GitHub so you can see the commits.
<hr>

### $\textcolor{lightblue}{\textsf{GitHub}}$
* $\fcolorbox{black}{green}{\textsf{Compare and Pull Request}}$ button
  * Add comments and title
  * Do $\color{red}{\textsf{NOT}}$ delete hashtag number of the commit title!
* $\fcolorbox{black}{green}{\textsf{Create Pull Request}}$ button
* $\fcolorbox{black}{green}{\textsf{Squash and Merge}}$ button
* Confirmation
* **Hashtag number of the commit title** - this serves as a shortcut to the merge. When clicked on a hashtag number in the commit, you can see all the commits that are squashed into it.
<hr>

### $\textcolor{lightblue}{\textsf{GitPod Terminal}}$
* **git checkout $\color{red}{\textsf{main}}$**
* **git pull** 
  * Now $\color{red}{\textsf{main}}$ is up to date with last branch merged into it
* Can start over again with new branch