b. A merge conflict can occur if two team members edit the same line in index.html on different branches. For example, if develop changes the h1 tag to h1 InfoSys424 /h1, but conflict_branch changes it to h1 Group 9 /h1, Git won’t know which version to keep when merging.
c. A merge conflict won’t happen if changes are made to different parts of index.html. For example, if develop updates the title tag while conflict_branch updates the p tag, Git can merge these changes automatically without conflicts.
