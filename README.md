# RepoZ Community Repository Actions

This repository contains repository actions for the context menu in [RepoZ](https://github.com/awaescher/RepoZ).

![RepoZ](RepoZ.png)

## Where's the community?

We collected a bunch of repository actions for you to use. Just select the platform you want to use it for:
- [Windows](Windows/RepositoryActions.json)
- [macOS](macOS/RepositoryActions.json)

### Please consider to share your custom repository actions by creating a pull-request :heart:

## What is this about?

RepoZ automatically deploys a configuration file `RepositoryActions.json` in its configuration folder:

- Windows: `C:\Users\YOURUSERNAME\AppData\Roaming\RepoZ`
- macOS: `/Users/YOURUSERNAME/.config/RepoZ`

There, you can customize the repository actions you want to use in RepoZ. Each repository action is defined in an own json block which can look like this:

```
{
    "name": "Open in GitHub Desktop",
    "command": 'github',
    "arguments": '"{Repository.SafePath}"',  
    "keys": "Ctrl+Shift+D",
    "active": "true"
}
```

With this, you can make RepoZ even more helpful to you and the community.

![image](https://user-images.githubusercontent.com/3630638/109568643-7f7f1100-7ae7-11eb-85e5-e99e5d490248.png)

Check your `RepositoryActions.json` RepoZ created for you for more information on how to define custom repository actions.

