# create repositry in github first

- first make a repository in github

- take a clone of repository from the romete hosting server(github) to your local server

  - go to the directory that you what to store the repository in it and type
    `git clone http(of the repositry)` .this will download the repositry in that directory and tell git to
    treat it as repositry (put the .git directory in it)

# the opposite made repo in the local and save it in remote

- first go to the repositry
- whrite `git init` that tell git to treat it as repositry (put the .git directory in it)
- add and commit its files
- go to github make a empty repositry take the "SSH Repository URL" and return to command line and create
  `git remote add origin "SSH Repository URL"` this will add the main to origin
- `git push -u origin master` ==> this will push all the data to the repositry `u` tell git to make pull
  before the push
