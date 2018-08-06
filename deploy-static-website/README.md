# Deploy Static Website

- [Github Pages](#github-pages)
- [Netlify](#netlify)

## [Github Pages](https://pages.github.com)
---

### Github - Create a new repository link

![](assets/create-a-new-repository-link.png)

### Github - Create a new repository page

![](assets/create-a-new-repository-page.png)

### Github - Repository page

![](assets/repository-page.png)

### Desktop - Install git

> https://git-scm.com/downloads

```
# apt-get install git
```

### Desktop - Create site folder

```
$ mkdir site-name
```

### VSCode - Open folder

> Go to File > Menu > Open folder

![](assets/open-folder.png)

### VSCode - Initialize Git Repository

```
$ git init
```

![](assets/git-initialize.png)

### VSCode - Create site

![](assets/create-site.png)

### VSCode - Git add

```
$ git add -A
```

![](assets/git-add.gif)

### VSCode - Git commit

```
$ git config user.email "example@email.com"
$ git config user.name "example"
```

```
$ git commit -m "primeira versão do site"
```

![](assets/git-commit.gif)

### VSCode - Git remote add

```
$ git remote add origin https://github.com/lucachaves/site-name.git
```

![](assets/git-remote-add.gif)

### VSCode - Git remote add

```
$ git push -u origin master
```

![](assets/git-push.gif)

> Enter login and password

[git-credential-store - Helper to store credentials on disk](https://git-scm.com/docs/git-credential-store):
```
$ git config credential.helper store
$ git push
```

### Github - Repository page with code

![](assets/new-repository-page.png)

### Github - Create github page

> https://username.github.io/site-name/

![](assets/create-github-pages.gif)


## Netlify
---

[Como colocar seu site no ar de graca](https://willianjusten.com.br/como-colocar-seu-site-no-ar-de-graca/)

## References
---

- [How to Initialize a Git Repository using Visual Studio Code and Publish the Code to Git Server](https://www.codeproject.com/Articles/1177391/How-to-Initialize-a-Git-Repository-using-Visual-St)
- [Using Version Control in VS Code](https://code.visualstudio.com/docs/editor/versioncontrol)
- [Git Version Control in VS Code](https://code.visualstudio.com/docs/introvideos/versioncontrol)