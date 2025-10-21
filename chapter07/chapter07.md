## Chapter 7

-  Git log --oneline displays commit history in a condensed, one-line format per commit, making it easier to scan &  shows detailed information about each commit in the repository history.
- After trying git log --graph, log --oneline & git log
   1. I realized log--graph draws an ascii graph of all my progress, log --oneline displays all my progress in one-line format and git log displays my progress in a detailed form.

- All commands have special cases for their uses:
  1. git log: Recommended when inspecting individual commits or investigating issues.
  2. git log --oneline: Useful in large repositories where full commit details are overwhelming.
  3. git log --graph: Particularly helpful in collaborative projects with multiple developers and long-lived branches.