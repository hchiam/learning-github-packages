# Learning GitHub Packages

Just one of the things I'm learning. <https://github.com/hchiam/learning>

To have a list like this: <https://github.com/hchiam?tab=packages>

Follow this tutorial: <https://www.youtube.com/watch?v=2-77KhGWlRg>

Example commit: <https://github.com/hchiam/_2DNote/commit/86f3cab00aa2276eebdc64e29801731a61e11f78>

You'll need this: `npm login --registry=https://npm.pkg.github.com`

And you'll need a PAT (personal access token), which is a generated string that looks like `l0ngStr1ng0fL3t7er5AndNum83rz`.

Make sure you set the PAT to have repo access, and also package read/write access.

In your global .npmrc file `~/.npmrc`, you should add your PAT:

```bash
//npm.pkg.github.com/:_authToken=l0ngStr1ng0fL3t7er5AndNum83rz
```

Official docs: <https://docs.github.com/en/packages/using-github-packages-with-your-projects-ecosystem/configuring-npm-for-use-with-github-packages> (but I found the YouTube tutorial easier to follow).

## You might also like

<https://github.com/hchiam/npm-package-example>
