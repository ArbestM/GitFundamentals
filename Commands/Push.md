# git push 

When you have a [remote](./REMOTE.md) set up you'll need to begin to move [commits](./COMMIT.md) to the remote. This can be done with command `git push`.

You can attach a name and branch name to your command to specify where you are pushing to.

```
git push origin main
```

This command will push the **main** branch to the remote called **origin**. This means any commits are in your local will be **pushed** to the remote

### Upstream tracking 

Instead of including the name of the remote and the branch you're on every time, you can set local branches to track an upstream branch. This means you can tell the branch to push to its assigned upstream remote branch by using the command 
`git push`.
```
git push -u origin main
```
After this command is used, you can just use `git push` and it will function the same way

## Resources 
- [Git Push Documentation](https:git-scm.com/docs-push)
---

[Back to home](../README.md)