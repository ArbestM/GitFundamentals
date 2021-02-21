# git remote 

When working with git, a **remote** is any git repository that is not the machine you are working on. The counterpart to this is **local**, or the machine that is being developed on.

Take GitHub for example. While git is the technology that allows you to create local repositories, GitHub is the site that will host your remote repositories. Once stored remotely, you can bring that repository back down or share it with others.

**Note**: While the repositories (local and remote) are related and track the same project, they can have different states if changes are not shared between the two.

### Adding a remote 

A remoe can be added with the `git remote add` command, followes by the name and location of the remote.

the name is a local name, meaning it's your label and does not impact the actual remote whatsoever.

```
git remote add origin https://github.com/ElevenfiftyAcademy/GitFundamentals.git
```
### removing a remote 

A remote can be remob=ved with the `git remote remove` command, followed by the name of the remote.

```
git remote remove origin
```
## Resources 

- [Git commit Documentation](https://git-scm.com/docs/git-commit)
---

[Back to home](../REAME.md)