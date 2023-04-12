# lets-rebase
Just a simple repo demonstrating why one should consider rebasing over merging.

# Outline
In this repo, we use a simple example of a collaborative shopping list to demonstate the following:

- Use rebase when TBD (vs merging)
- How to Rebase (on Branch)
    - Conflicts!
    - Note: It replays commit by commit
    - Note: Always check `git status` when rebase _(you need to resume it if there are conflicts)_
    - History rewrite _(`git push -f`)_
- Squashing commits with Git (Grouping logical commits together)
- Review Git History:
    - Trunk Based Development (TBD)
    - Branching and Merging
    - Branching with Rebase
- \[BONUS\] I messed up... What can I do?

# How to use

Fork and clone this repository to your local. Then create branches as necessary to demonstrate, or experiment on your own!

_**Note:** I assume that most folks already know basic commands of git, such as cloning, checking out a branch, pulling, and pushing to remote._

### Useful commands:

- `git pull [-r]` – optional `-r` flag to tell git to use rebase when pulling
- `git rebase <branch name>` – rebase current branch on top of <branch name>

# Reading
Learn about [Git Rebase](https://git-scm.com/book/en/v2/Git-Branching-Rebasing)

