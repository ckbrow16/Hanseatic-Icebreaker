### Quality Policy
> Describe your Quality Policy in detail for your project (remember what I ask you to do when I talk about the "In your Project" part in the lectures and what is mentioned after each assignment). You should keep adding things to this file and adjusting your policy as you go through the sprints.

> **Reference:** See the Project Module Concepts document on Canvas in the Project module for detailed explanations and examples of each policy area.

---

## **GitHub Workflow** (start Sprint 1)
> This workflow follows the required conventions defined in Project Module Concepts and Housekeeping.
> Any deviations must be explicitly justified below.

Describe your team's Git workflow in detail. Address the following:
- What is your branch naming convention? (e.g., feature/US#-description, bugfix/issue#)
- When do you create branches? (e.g., for each User Story, for each task)
- What is your merge strategy? (e.g., merge commits, squash and merge, rebase)
- Who approves Pull Requests and how many approvals are required?
- When can code be merged to main? (e.g., after sprint ends, after review)
- How do you handle merge conflicts?

> _Your Workflow Description_

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
