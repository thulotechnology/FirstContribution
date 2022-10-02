### First Contribution
This is a repository for beginners to practice making their first contribution. If you are looking to make your first contribution, follow the steps below.

### Requirements
- Basic Knowledge of Git and Github.
- Must have logged in to your Github account.

### How to make your first contribution
Here are the steps to make your first contribution:

### Step 1: Fork this repository
Click on the fork button on the top of this page. This will create a copy of this repository in your account.

### Step 2: Clone the repository
You now have a copy of the repository in your Github account. Let us clone it to your machine using the following command.

`git clone <url>`

where url is the url of your forked repository. You can get this url by clicking on the clone button and then clicking the copy to clipboard icon.

### Step 3: Create a branch
Change to the repository directory on your computer (if you are not already there). Now create a branch using the `git checkout` command.

`git checkout -b <add-your-new-branch-name>`

### Step 4: Make necessary changes and commit those changes
Now open `Contributors.md` file in a text editor, add your name to it, then save the file.

If you go to the project directory and execute the command `git status`, you'll see there are changes. Add those changes to the branch you just created using the `git add` command. Now commit those changes using the `git commit` command.

`git add Contributors.md`
`git commit -m "Add <your-name> to Contributors list"`

### Step 5: Push changes to GitHub
Push your changes using the command `git push origin <your-branch-name>`.

### Step 6: Submit your changes for review
If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

### Steps
1. Fork this repository
2. Clone your forked repository to your local machine
3. Create a new branch with the command `git checkout -b <add-your-new-branch-name>`
4. Make your contribution
5. Stage your changes and commit them with `git add <file-you-added-or-changed>` and `git commit -m "<your-commit-message>"`
6. Push your changes to GitHub with `git push origin <add-your-branch-name>`
7. Submit your changes for review

### How to contribute
1. Add your name to the `CONTRIBUTORS.md` file
2. Add a profile page to the `profiles` directory
3. Add a script to the `scripts` directory
