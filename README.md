## Ryan Goss
### CSCI 5828 – Spring 2018
# Homework 2

## Commits (first is the latest):
* commit 13
* commit 10
* commit 12
* commit 11
* commit 6
* commit 5
* commit 9
* commit 8
* commit 7
* commit 4
* commit 3
* commit 2
* commit 1
* commit 0

## Commands:
Note: last is latest; omits "vi readme.md" commands in between each "git add ." command <br>
0. git init
1. vi README.md // will not include going forward, assumed before each "git add ."
2. git add .
3. git commit README.md // *commit 0*
4. git add .
5. git commit // *commit 1*
6. git add .
7. git commit // *commit 2*
8. git log
9. git checkout <commit 0 hash>
10. git checkout -b bug-fix
10. git add .
11. git commit // *commit 3*
12. git add .
13. git commit // *commit 4*
14. git merge master // resolve any conflicts with vi readme.md
15. git add .
16. git merge --continue // *commit 5*
17. git add .
18. git commit // *commit 6*
19. git log
20. git checkout <commit 4 hash>
21. git checkout -b bug-fix-experimental
22. git add .
23. git commit // *commit 7*
24. git add .
25. git commit // *commit 8*
26. git add .
27. git commit // *commit 9*
28. git log -g
29. git checkout master
30. git add .
31. git commit // *commit 10*
28. git checkout master
29. git add .
30. git commit // *commit 10*
31. git checkout bug-fix
32. git merge bug-fix-experimental // resolve conflicts
33. git add .
34. git merge --continue // *commit 11*
35. git add .
36. git commit // * commit 12*
37. git checkout master
38. git merge bug-fix // resolve conflicts
39. git add .
40. git merge --continue // *commit 13*
