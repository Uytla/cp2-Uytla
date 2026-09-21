# Checkpoint 2 Submission

> Complete this file on your required `cp2-YOUR-GITHUB-USERNAME` branch.
> The grader reads this file from the Pull Request's stored **head commit**, so it still works after merge or branch deletion.
> GitHub detects the Pull Request number automatically.

Name:  
GitHub Username:  
Required Branch:  

## Commands Used

Write the commands you actually used, one command per line.

```text
git clone ...
git switch -c cp2-YOUR-GITHUB-USERNAME
git status
git add feature.txt submission.md
git status
git commit -m "..."
git push -u origin cp2-YOUR-GITHUB-USERNAME
```

## Question 1 — Branch Safety

Why should you avoid implementing this checkpoint directly on `main`?

Answer: because we might make a mistake. A new branch lets us work safely.

## Question 2 — Stage vs Commit

What is the difference between `git add` and `git commit`?

Answer: git add gets the changes ready to save. git commit saves the changes.

## Question 3 — Push, Pull Request, Review, Merge

Explain what changes when you push a branch, open a Pull Request, receive a review, and merge the Pull Request.

Answer:When we push, our branch goes to GitHub. A Pull Request asks to add our changes to main. A review checks our work. When we merge, our changes go into main.

## Reflection

Which checkpoint in the branch → PR → review → merge workflow is most useful for preventing mistakes, and why?

Answer: I think PR is the most useful because this is only step to send request to merge so it important