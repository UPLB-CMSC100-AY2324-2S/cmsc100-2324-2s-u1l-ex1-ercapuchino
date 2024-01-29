# Exercise 01: Git

Title: Create your first Pull Request
Type: Individual Assessment
Score: Pass or Fail (10 Points)

Helpful Material for this Exercise: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request

Before the exercise:

Find a partner to collaborate with. Add them as a collaborator in your GitHub repository.

You and your partner must clone your own GitHub classroom exercise 1 repository called “create-your-first-pull-request-<surname>-1” 

Note: Kindly disregard the feedback branch

On your local repository, create a text file called "expectations.txt" and push it to your GitHub remote repository. You must add something inside "expectations.txt," particularly your expectations about your journey in CMSC 100.

For this activity, you will take on the roles of both the "creator" and the "reviewer."

As a creator

You will clone your partner’s repository using the git clone command to duplicate their repository on your local machine.

While working with your partner’s repository, create a new branch with your surname as the branch name. You will make changes to the cloned repository by editing their “expectations.txt”, ideally to express agreement or disagreement with your partner's thoughts.

You should commit your changes from your partner’s repository with a descriptive commit message:
	git commit -m “chore: Agreed with your expectations”

You should push your changes to your partner’s repository.
git push origin surname
As a reviewer

You will approve changes to the original repository.

1.1. Visit your repository 
1.2. Select "New Pull Request" from the menu.
1.3. Choose the base repository and branch (typically the original repository's default branch).
1.4. Choose the "compare" branch to be your branch.
1.5. Give your pull request a clear title and description.
1.6. Select "Create Pull Request" from the menu.

Examine the pull request and, as necessary, provide comments or approvals.

You can integrate the pull request into the basic repository if you're happy with the changes.

Result:

Your Repository (Student A)
Your Partner’s Repository (Student B)
Branch

main
Student B’s surname



Branch

main
Student A’s surname






Kindly take note of these commit message format that we will use in CMSC 100:

docs: (changes to the documentation)
style: (formatting, coding style, etc; no production code change)
test: (adding missing tests, refactoring tests; no production code change)
ui: (user interface changes)
fix: (bug fix for the user, missing semicolons)
refactor: (refactoring production code, eg. renaming a variable)
feat: (new feature for the user)
chore: (updating some resource, eg. change value of a variable)
