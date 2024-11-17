>## Greenwood-Library-Website Project Implementation.

#### `Create New Repository on Github.`
---

- In your web browser, open your Git hub account and create a new repository.

- Name the repository `Greenwood-library-website`.

![new repository](./img/1.create%20repository.png)

- Click on the Add a `README.md file` and create repository.

![add Readme.md](./img/2.readme.md%20file.png)
#### `Cloning Your Repository`
---


- Click the code button and copy the HTTPS link.

![copy HTTPS link](./img/3.copy%20http.png)
- Open your local terminal and navigate into the directory where you want to clone your remote repository.

- Type in the command `git clone` and paste the link copied from your git hub.

![git clone command](./img/4.git%20clone.png)
- Change directory into the cloned repository.

![change directory](./img/5.cd%20directory.png)


> #### `File Manipulation`
---

- On your terminal, create `HTML` files.
![create files](./img/6.create%20html%20files.png)

- Using the Visual Studio Code editor, add contents to the`about_us.html` file.


![edit about_us.html](./img/7.about%20us.png)
- Add desired content into the `contact_us.html` file.

![edit contact_us.html](./img/8.contact-us.png)
- Repeat the same process for the `event.html` file and the `home.html`file by adding contents to each file.

![edit event.html](./img/9.events.png)

- `home.html`

![edit home.html](./img/10.home.png)

`## STAGING, COMMITING AND PUSHING FILES`

- On the terminal, use `git status` command to know the current state of the repository.


![git status](./img/11.git%20status.png)

- Stage files using the `git add .` command and check status again.

- Files in green indicate files are now staged and ready for commit.

![git add](./IMG/12.git%20stage.png)


- Use the `git commit` command to capture changes in the repository.

- The git commit command represents a "save version" of the project captured in time.

![git commit](<img/13.git commit.png>)

 - Use `git push` command to upload local repository content to a remote repository.

![git push](<img/14.git push.png>)

> ## `CREATING A BRANCH IN GIT`
#### `Adding Book Review`
- Create a branch using the `git checkout -b`command, followed by the branch name and switch to it.

![create branch](<img/15.create branch.png>)

- Create new file and name it `review.html`

![create new file](<img/16.create file.png>)

- Add content to `review.html`, after which files should be staged, commited and pushed into the Git hub repository.

![add content](img/17.addcontent.png)