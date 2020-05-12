# git-basics
A repo for collaboratively learning the basics of Git + Github

__what do you think about putting some high level topics here?__\
I'll take a stab but we can obviously do other thing here too.

**Conceptual**
* why and how should we use git for personal code use?
* how does this differ from collaborative use?

**Practice**
* What are some good ideas about how to incorporate this tool into our routines?

**Basics**
1. What's the difference between git fetch and git pull?
2. git remote
3. 
4. git checkout
5. git add
6. git push
7. git pull
8. git fetch
9. git diff
10. what else??

##Articles
* [Link to Article](https://www.git-tower.com/learn/git/faq/difference-between-git-fetch-git-pull)
* [Github MarkDown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

###Adventure time
**Make your own fork!**
:fire:I used the browser then added a remote to my laptop with this:fire:\
```
git remote add origin_personal https://github.com/AndrewDHill/git-basics\
git remote -v
```

---
#### Credentials
> To store your password locally for a repo on your machine
```
git config credential.helper store
'''
> TO store your password globally on your machine
```
git config --global credential.helper store

```
It also helps to use the .gitconfig feature so that authoring information is readily available
```
git config --global user.name "Booly Boo"
git config --global user.email "BollyBoo@googly.goo"
