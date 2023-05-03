# Branching/merging/squashing

![Branching](/img_asset/Screenshot%202023-04-12%20113612.png)

Created to learn/practice GitHub branches, merging and squashing commits.

## $\textcolor{chartreuse}{\textsf{PROCEDURE}}$
<hr>

### $\textcolor{cyan}{\textsf{GitHub}}$
* In the repo you are working on, under $\color{red}{\textsf{Settings}}$
 =>  $\color{red}{\textsf{Branches}}$, tick only the first box (Require a pull request before merging) 
* Branch name pattern = main
  * Done as to serve as additional check before merging and to remove the warning message about unprotected branch.
<hr>

### $\textcolor{cyan}{\textsf{GitPod Terminal}}$
* **git checkout -b $\color{red}{\textsf{branch-name}}$**
  * Creates and places you in the created branch
  * Can switch between branches with **"checkout $\color{red}{\textsf{branch-name}}$"**
  * You can see previous commits with **"git log --oneline"**
* Do your work
* Add and commit as normal
* **git push origin $\color{red}{\textsf{branch-name}}$**
  * Pushes your work into the branch you are working on, and creates the branch in GitHub so you can see the commits.
<hr>

### $\textcolor{cyan}{\textsf{GitHub}}$
* $\textcolor{green}{\textsf{Compare and Pull Request}}$ button
  * Add comments and title
  * Do $\color{red}{\textsf{NOT}}$ DELETE OR CHANGE hashtag number of the commit title!
* $\textcolor{green}{\textsf{Create Pull Request}}$ button
* $\textcolor{green}{\textsf{Squash and Merge}}$ button
* Confirmation
* **Hashtag number of the commit title** - this serves as a shortcut to the merge. When clicked on a hashtag number in the commit, you can see all the commits that are squashed into it. If you don't have this option, the previous steps/commits are still viewable if you go to Pull requests => click on the pull request that you want to see squashed commits of.
<hr>

### $\textcolor{cyan}{\textsf{GitPod Terminal}}$
* **git checkout $\color{red}{\textsf{main}}$**
* **git pull** 
  * Now $\color{red}{\textsf{main}}$ is up to date with last branch merged into it
* Can start over again with new branch
<hr>
<hr>
<hr>

I created this to help anyone (and myself!) wanting clear and unambiguous guide for branching/merging/squashing on GitHub.
I have not yet used the guide in a live project, if there are bugs or mistakes please do let me know, I would appreciate it.

The info gathered was from a mix of YouTube, Stack Overflow, GitHub docs and digging into other people's projects to see how they work.<br>
$\textcolor{dimgray}{\textsf{Boiann 2023}}$
