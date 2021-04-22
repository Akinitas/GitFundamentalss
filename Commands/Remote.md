# git remote

When working with git, a **remote** is any git repository that is not on the machine you're working on. the counterpart to this is **local**, or the machine that is being developed on.

Take Github for example. While git is the technology that allows you to create local repositories, Githug is the site that will host your remote repositorie. Once stored remotely, you can bring that respository bakc down or share it with others.

**Note**: While the repostiories (local and remote) are related and track the same project, they can have different states if changes are not shared between the two.

### Adding a remote

A remote can be added with the `git remote add` command, followed by the name and location of the remote.

The name is a local name, meaning it's your label and does not impact the acutal remote whatsoever. 

```
git remote add origin https://github.com/ElevelfiftyAcademy/GitFundamentals.git
```
### Removing a remote

A remote can be removed with the `git remote remove` command, followed by the name of the remote.

```
git remote remove origin
```

## Resources 

- [Git Commit Documentation](https://git-scm.com/docs/git-commit)

---

[Back to home](../README.md)
