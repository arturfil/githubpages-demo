# githubpages-demo

## Steps to create github pages website

- create a github repo from github and choose the start from scratch
https://d186loudes4jlv.cloudfront.net/git/images/github_new_repo3.png

- create a new branch
``` git checkout -b gh-pages```

- Go to settings > pages & select the gh-pages branch
- In your local repo you are going to push local code to the remote
``` git push origin gh-pages```
- Everytime you change something in main, checkout to gh-pages:
```git checkout gh-pages```
```git pull origin main```
- And repeat the push gh-pages branch to github pages
```git push origin gh-pages```
