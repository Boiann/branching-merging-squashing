# Branching/testing

Created to learn/practice GitHub branches, merging and squashing commits.

## $\textcolor{yellow}{\textsf{PROCEDURE}}$
<hr>

### $\textcolor{lightblue}{\textsf{GitPod Terminal}}$
* git checkout -b $\color{red}{\textsf{branch-name}}$
  * Creates and places you in the created branch
  * Can switch between branches with "checkout"
  * git log --oneline  &nbsp; &nbsp; => &nbsp; see previous commits 
* Do your work
* Add and commit as normal
* git push origin $\color{red}{\textsf{branch-name}}$
<hr>

### $\textcolor{lightblue}{\textsf{GitHub}}$
* $\fcolorbox{black}{green}{\textsf{Compare and Pull Request}}$ button
  * Add comments and title
* $\fcolorbox{black}{green}{\textsf{Create Pull Request}}$ button
* $\fcolorbox{black}{green}{\textsf{Squash and Merge}}$ button
* Confirmation
<hr>

### $\textcolor{lightblue}{\textsf{GitPod Terminal}}$
* git checkout main
* git pull 
  * Now $\color{red}{\textsf{main}}$ is up to date with last branch merged into it
  * Can start over