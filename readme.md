yay git. 

some things about git that i didn't know

1. to delete a branch: git branch -d
2. interactive staging: git add -i
3. you can stage parts of files, not just whole files
4. see which stashes you've stores: git stash list
5. you can create a branch from a stash: git stash branch
6. you can reorder commits, or squash multiple commits into one. 
7. you can split one commit until multiple
8. you can merge while ignoring whitespace: git merge -Xignore-space-change branch-name
9. do a binary search through commit history to see where bugs were introduced: git bisect
10. git help shows you git documentation
11. git mergetool and git difftool are there to help with merges and showing diffs
12. there are git commands for maintaining repos over email. wtf