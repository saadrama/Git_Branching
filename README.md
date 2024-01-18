# Git_Branching
Learning about Git Branching

# Define terms
- Branch
- 1. Isolation
- 2. Parallel development(collaborative development)

## Git Commands
1. Create a branch
`bash
     `git branch "branchname"`
`

2. Switching between branches
`bash
    - `git switch branchname`
    - `git checkout branchname`
`
    - Directly switching to a new branch
   
   `bash
     `git checkout -b branchname`
   `


3. Merging
`bash
   `git merge sourcebranch`
`

4. Resolve Conflicts 
`bash
    `git mergetool`
`

5. List all branches 
`git branch`

6. A list of extra commands

`git branch -v`


`git status`

- List merged commits
`git branch --merged`
 List unmerged commits
`git branch --no-mergedd`


### Bonus Command
```code
     <h1> git log</h1>
```