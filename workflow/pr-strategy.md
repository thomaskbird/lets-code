# PR Strategy

## What is a PR (Pull Request)?
> A pull request (sometimes called merge requests), is a review request. You are asking someone to check the changes on a branch before merging into another branch.

## PR Do's & Don’ts
1. Do 
    1. Make small PR requests 
    2. 1-3 stories at the very most should be included in any one PR 
    3. If it has been more than 2-3 days and no one has reviewed your pull requests, Tag people in comments or reach out directly. 
    4.If PR comments or tasks have been added, address those within 1-2 days
2. Don’t 
    1. Merge without at least one approval 
    2. Make large pr requests rolling lots of changes into a single PR
    3. take PR comments personal

## A PR accomplishes the following:
- Allows peer developers to review your code
- Test your code
- Learn from your code
- Educate others through your PR reviews.
- Ensures a level quality

### Why isn’t testing enough?
Unit testing is great, it can find errors in your code and help ensure your code operates as expected. A PR however, takes this a step further, tests can’t detect that the same code is written say twice or determine if code follows best practices. This is what the PR is primarily for.

### Philosophy
Pull requests should be somewhat similar to tasks. In Jira you may have epics and then within epics you would have tasks that accomplish that epic. Making a PR that encompasses the entire epics tasks would be bad, the reason being, is that each of the tasks have code changes and trying to understand a single change can be daunting but multiple changes is infinitely harder. Having one focused change will help ensure that the changes are easy to understand and read. It will also help the reviewer approve and provide meaningful feedback.
