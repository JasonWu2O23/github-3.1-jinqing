# Assignment 3.1 - Introduction to GIT I

## Git commands learnt in module 3.1

Retrieve an entire repository from a hosted location via URL.
`````````````````````````````````````````````````````````````
git clone [url]
`````````````````````````````````````````````````````````````

Fetch and merge any commits from the tracking remote branch.
````````````````````````````````````````````````````````````
git pull
````````````````````````````````````````````````````````````

Set Your Name and Email Address. These settings will be used to identify your commits in the Git history.
``````````````````````````````````````````````````````````````````````````````````````````````````````````
git config --global user.name "[Your Name]"
``````````````````````````````````````````````````````````````````````````````````````````````````````````

``````````````````````````````````````````````````````````````````````````````````````````````````````````
git config --global user.email "[youremail@example.com]"
``````````````````````````````````````````````````````````````````````````````````````````````````````````

Stage all the files for commit to your local repository by the following command.
`````````````````````````````````````````````````````````````````````````````````````
git add .
`````````````````````````````````````````````````````````````````````````````````````

Commit the file that you’ve staged in your local repository.
`````````````````````````````````````````````````````````````
git commit -m "[descriptive message]"
`````````````````````````````````````````````````````````````

Push the changes in your local repository to GitHub.
`````````````````````````````````````````````````````
git push origin main
`````````````````````````````````````````````````````

Delete the file from project and stage the removal for commit.
```````````````````````````````````````````````````````````````
git rm [file]
```````````````````````````````````````````````````````````````

Change an existing file path and stage the move.
`````````````````````````````````````````````````
git mv [existing-path] [new-path]
`````````````````````````````````````````````````
