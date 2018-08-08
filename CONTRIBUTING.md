# Contributing

Persons contributing to this project agree to the [code of conduct](/CONDUCT.md) and agree to the potential redistribution of their code under our license.

## Contributor Agreement: 

### Task:
- Sean
- Ruoqi Xu
- Abishek

### Communication:
Each group member is responsible to be:

- Responsive on Slack , especially during Friday and Saturday. 
- Meeting at lab time to talk about weekly plan.

### Contribute to the project
- For big changes, please create new Branch. Please follow the tips about commit message below (In **How to contribute** part.).
- Commit frequently with clear and concise commit message.
- Write tests for function changes.
- Once your changes are done, submit a Pull Request.
- Wait for comments from team member. Then make changes from your Branch/Fork repo.
- Only merge after reaching whole team agreement.

## Where to Contribute(Workflow)

#### Using GitHub
1.  We can use GitHub flow (branch) to manage changes:
   - Clone this repo. Create a new branch in your desktop copy of this repository for each significant change.
   - Commit the change in that branch[(about branch)](https://help.github.com/articles/about-branches/).
   - Submit a pull request from that branch to the master repository.
   - If you receive feedback, make changes on your desktop and push to your branch on GitHub: the pull request will update automatically.
   - **If a major change is made by any person, tag other two. If this change is approved by all → accept pull request.**


## How to Contribute

#### Code comment 
- Functions need to be documented clearly.

#### Commit message
- Big changes:
  
```
 git commit -m "A brief summary of the commit

 A paragraph describing what changed and its impact."
```

-  Small changes:
   - 1-line detailed message including what change you made.

 ```
git commit -m "Concise summary of what you did here"
```

- Frequent commit everytime you make changes.


#### Testing conventions

- Details coming in 1 week.


#### Coding convention
- Python:

      - All code should in `.py` file rather than jupyter notebook file
- R:
      - Avoid using `=` when assign objects. Instead, use `->`
      - Use `%>%` (including in **dplyr** package)
      - All code should be in `.R` file rather than `.Rmd` or R notebook.


## Attribution
This document was adapted from [here](https://github.com/swcarpentry/r-novice-inflammation/blob/gh-pages/CONTRIBUTING.md).
