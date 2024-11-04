# DSE Lab1
## This project aims to explore and apply various Git features.
### demonstrating:
1. Issues
2. Boards/Projects in Github
3. PRs
4. Branching strategies

**Feature Branch Workflow**. 
This approach involves creating a new branch for each feature you're working on, isolated from the main development branch. Here's a breakdown:
[image features diagram]

**1. Main Branch:**
   - This is the primary branch containing the production-ready code.
   - It should always be stable and deployable.

**2. Feature Branches:**
   - For each new feature, create a branch from the main branch.
   - Develop the feature on this branch, committing changes as you go.

**Workflow:**

1. **Create a Feature Branch:**
[img ]
2. **Make commits to the `features` branch.**
[img ]
3. **Create a Pull Request:**
[img ]
4. **Merge the Feature:**
[img ]


Benefits of Feature Branch Workflow:

* **Isolation:** Each feature is developed independently, reducing the risk of conflicts and making it easier to manage changes (Atlassian Git Tutorial, 2023).
* **Code Review:** Pull requests facilitate code reviews, ensuring code quality and consistency (Atlassian Git Tutorial, 2023).
* **Parallel Development:** Multiple features can be developed simultaneously by different team members (Atlassian Git Tutorial, 2023).
* **Easy Rollback:** If a feature causes issues, it can be easily rolled back by reverting the merge (Atlassian Git Tutorial, 2023).

**Reference:**

Atlassian Git Tutorial (2023). Git Feature Branch Workflow. Atlassian. [https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow)
