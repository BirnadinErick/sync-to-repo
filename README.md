# sync-to-repo

> Fork of [github-action-push-to-another-repository](https://cpina.github.io/push-to-another-repository-docs)

### What is different?

_The Origin_ is destructive by default. I couldn't find a way to do it otherwise. 
For a particular use-case I had to move files from `src-dir` to `target-dir`, without 
files in their being deleted. 

Thus, I forked and removed the lines that `rm -rf`-ed the `target-dir` before committing.
