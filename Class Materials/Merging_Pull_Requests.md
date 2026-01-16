# Merging a Pull Request on GitHub.com

*A one-page student guide*

---

## What is a Pull Request (PR)?
A **pull request** is a request to merge changes from one branch into another (usually into `main`). Pull requests allow for review, discussion, and automated checks before changes are merged.

---

## Before You Start
Make sure:
- You are **signed in to GitHub**
- You have **write or maintainer access** to the repository
- All **required checks pass** (if the repo has rules)
- The PR has **no unresolved merge conflicts**

---

## Step-by-Step: Merge a PR on GitHub.com

### 1. Open the pull request
- Go to the repository on **GitHub.com**
- Click the **Pull requests** tab
- Click the pull request you want to merge

---

### 2. Review the pull request
Before merging, look at:
- The **description** (what is this PR trying to do?)
- The **Files changed** tab
- Any **comments or reviews**

Ask yourself:
- Does this solve the stated problem?
- Does the code make sense?
- Would I be comfortable maintaining this?

---

### 3. Check the status
On the PR page, confirm:
- ✅ All checks are passing
- ⚠️ No unresolved conflicts
- 🔒 Branch protection rules are satisfied

If something is blocking the merge, GitHub will explain why.

---

### 4. Choose a merge method
Click the **Merge pull request** button and select a method:

#### Merge commit (default)
- Keeps all commits
- Preserves full history
- Best for shared or long-running branches

#### Squash and merge
- Combines all commits into one
- Creates a cleaner history
- Best for small or student PRs

#### Rebase and merge
- Replays commits onto `main`
- Produces a linear history
- Use only if you understand rebasing

---

### 5. Confirm the merge
- Click **Confirm merge**
- GitHub merges the PR into the base branch

✅ The pull request is now closed and merged.

---

### 6. Delete the branch (recommended)
After merging:
- Click **Delete branch** on the PR page

This keeps the repository clean.

---

## Important Notes

### PRs from forks
- Fork-based PRs merge the same way
- You don’t need to fetch the code locally to merge

### When not to merge
- Tests are failing
- The PR doesn’t do what it claims
- The code is unclear or unsafe

---

## Quick Checklist
- ☐ Read the PR description
- ☐ Reviewed the code
- ☐ Checks are passing
- ☐ Chose the correct merge method
- ☐ Deleted the branch

---

## Common Mistakes to Avoid
- ❌ Merging without reviewing
- ❌ Choosing the wrong merge method
- ❌ Merging into the wrong branch

---