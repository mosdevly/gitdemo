# Git Workflow

You can fork or clone this repo to practice using git commands. 

### How do I update my feature branche with changes from the master branch?

**Setup**

1. Create a new branch: `git checkout -b feature/addLogging`
2. Review the git logs and note the last commit.
3. Open `app.js`
4. Add a console log to the top of the file: `console.log('Initial feature commit logged.')`
5. Save and commit your changes

Now swap to master and add a new line to the bottom of `README.md`: `I followed instructions to the letter!`.

**Solution**

1. Swap to your feature branch `feature/addLogging`
2. Run: `git rebase master`
3. Check the logs to see that new commits from master have been added to your feature branch. 

You can also check the readme to see that the new sentence is now there.

### How do I create a pull request?

1. Push your feature branch to the project repository: `git push origin feature/addLogging`
2. Go to Github and you'll see an option to create a pull request for the new branch. Click it.
3. Add any additional info as necessary.
4. Submit the PR.

### Should I keep my feature branch if I'm done with it? 

You don't have to, especially if its been merged. 

### Should I keep working on the feature branch after its merged?

No. Create a new feature branch whenever you're writing new code. 

## Sandbox

Use this section to edit this file as you play around with git commands.

Add a new change.

Creating a merge conflict.
Feature branch update.
