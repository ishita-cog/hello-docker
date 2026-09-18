<!-- -------------------------------------------------------------------
PR Template

This form automatically appears every time someone opens a pull request.
It forces engineers to answer the right questions before anyone reviews
their work. In a real enterprise, skipping this would get your PR sent
back immediately.
------------------------------------------------------------------- -->

## What does this change do?
<!-- Describe what you changed and why. One paragraph is fine. -->


## How did you test it?
<!-- Did you run it locally? Did you write a test? Did you just click around?
     Be honest — reviewers will ask if you're not specific. -->


## Is there anything risky about this change?
<!-- Does it touch the database? Change an API response? Affect auth?
     If yes, explain what could go wrong and how you'd roll it back. -->


## Checklist
<!-- Put an x inside the brackets to check a box, like this: [x] -->

- [ ] I tested this locally before opening the PR
- [ ] The CI pipeline is green
- [ ] I have not committed any secrets, passwords, or API keys
- [ ] If I changed the database, there is a rollback plan
- [ ] I updated any relevant documentation
