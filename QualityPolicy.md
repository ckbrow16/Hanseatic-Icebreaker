### Quality Policy
> Describe your Quality Policy in detail for your project (remember what I ask you to do when I talk about the "In your Project" part in the lectures and what is mentioned after each assignment). You should keep adding things to this file and adjusting your policy as you go through the sprints.

> **Reference:** See the Project Module Concepts document on Canvas in the Project module for detailed explanations and examples of each policy area.

---

## **GitHub Workflow** (start Sprint 1)
> This workflow follows the required conventions defined in Project Module Concepts and Housekeeping.
> Any deviations must be explicitly justified below.

### 1.1 Branch Naming 
- The `main` branch will contain the final, working version of the project at the end of each sprint.
- The `dev` branch will be used for active development.
- A new branch will be created for each User Story using the format `US#-short-description`.
- Optional task branches may be created from a User Story branch if needed.
- Branches will not be deleted until after the sprint has been graded.

### 1.2 Branch Creation 
- Team members will create a new branch for each User Story or major task.
- Before starting work, the latest changes from `dev` will be pulled to avoid conflicts.

### 1.3 Commit Practices
- Commits will be made frequently with clear and meaningful messages.
- Commit messages will reference the related User Story or task.
- If work is incomplete, commits will be marked as WIP (work in progress).

### 1.4 Pull Requests and Reviews
- A Pull Request will be created when a User Story is completed or when significant progress is made.
- Each Pull Request must be reviewed by at least one other team member.
- Team members are responsible for reviewing each other’s Pull Requests.

### 1.5 Merging 
- User Story branches will be merged into `dev` after review and basic testing.
- Only the Git Master will merge `dev` into `main` at the end of the sprint.
- Fast-forward merges will be used when possible.

### 1.6 Merge Conflicts
- Merge conflicts will be resolved locally by the team member merging the branch.
- If a conflict is unclear, the team will work together to resolve it.
- The project must compile and run after conflicts are resolved.

> _Your Workflow Description_

This workflow applies to Sprint 1 and will be updated in future sprints as new quality practices are introduced.
---

## **Unit Tests Blackbox** (start Sprint 2)
Describe your Blackbox testing policy. Include:
- What code will you test exactly (code you write, code from peers, existing code)?
- What types of tests will you write? (e.g., boundary value, equivalence partitioning)
- What is your minimum test coverage expectation?
- When are tests written? (before code, after code, during development)
- How do you ensure tests are meaningful and not just for coverage?

> _Your Blackbox Testing Policy_

---

## **Unit Tests Whitebox** (online: start Sprint 2, campus: start Sprint 3)
Describe your Whitebox testing policy. Include:
- What code will you test exactly (code you write, code from peers, existing code)?
- What code structures will you test? (e.g., branches, loops, paths)
- What is your code coverage goal?
- How do you ensure all critical paths are tested?

> _Your Whitebox Testing Policy_

---

## **Code Review** (start Sprint 2)
Describe your Code Review policy.

**Note:** For on-campus classes, a less formal process in Sprint 2 is acceptable, but should be updated with more rigor in Sprint 3. Online will already do a more rigor review in Sprint 2. 

### Developer Checklist (for Pull Request Creation)
Create a checklist that every developer must complete when creating a Pull Request to the dev branch. This checklist should be included in the **Pull Request description** with a description of your PR.

Example items to consider:
- [ ] Code compiles without errors
- [ ] All tests pass
- [ ] Code follows team coding standards
- [ ] Code is documented/commented appropriately
- [ ] No debugging code or print statements left in

> _Your Developer Checklist (add your own items)_

### Reviewer Checklist (for Code Review)
Create a checklist/questions that every reviewer must complete when conducting a code review. This checklist and the reviewer's answers must be included in the **Pull Request review comments section**.

Example items to consider:
- [ ] Code is readable and maintainable
- [ ] Logic is correct and handles edge cases
- [ ] Tests are comprehensive and meaningful
- [ ] No code smells or anti-patterns present
- [ ] Documentation is clear and accurate

> _Your Reviewer Checklist (add your own items)_

---

## **Static Analysis** (start Sprint 3)
Describe your Static Analysis policy. Include:
- What static analysis tool(s) will you use? (e.g., CheckStyle, PMD, SpotBugs)
- What rules/checks will you enforce?
- What is your threshold for warnings/violations?
- How will you address findings?

> _Your Static Analysis Policy_

---

## **Continuous Integration** (start Sprint 3)
Describe your Continuous Integration policy. Include:
- What triggers your CI pipeline? (e.g., every push, every PR)
- What does your CI pipeline do? (e.g., build, test, static analysis)
- What is your policy if CI fails?
- How do you ensure the main branch is always in a working state?

> _Your Continuous Integration Policy_
