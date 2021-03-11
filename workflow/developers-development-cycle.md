# Developers Development Cycle
This section describes things like branching strategy, PR methodology, etc.

1. Get assigned a jira ticket
    1. Create feature branch from jira
    2. Checkout that branch in IDE
4. Make changes to the feature branch
    1. Testing 
    2. If there are already tests, ensure that you add any necessary tests and or that your new code doesn’t cause existing tests to break.
    3. If they do cause tests to break update those tests to accommodate for your new code.
5. Push changes to bitbucket
6. Go to bitbucket and submit PR against development
    1. Wait for approval or tasks on PR
    2. Fix any tasks
    3. PR will be approved once the code is satisfactory
10. Merge PR into development
11. Once any other testing necessary is done submit a PR against master from development

