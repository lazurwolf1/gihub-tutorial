# gihub-tutorial
how to use github

Step 1: Create an account on Github using Amazon email ID. www.github.com (http://www.github.com/)
[Image: Image.jpg]
Step 2: Creating a repository to add our codebase to Github.
[Image: Image.jpg]

* Give a relevant repository name and we can choose the type of the repository as *Private* (This would allow us to choose who can access the repo).
* Once these informations are added, click on Create repository.

Step 3: Once the repository is created, we can upload our code to the repository.

* Before we can upload our code to Github by cloning the repo to our local machine, we have to set up 2 factor authentication to access the repo from our local system.
* For authenticating to the repo, we have to create a personal access token from our Github account.
    * Click settings in profile → On the left pane select Developer setting → Click Personal Access Token → Generate token and select all the different features that we need for our account and select an expiration date for the token.
    * Once the Access token is generated, copy and save it to your local system, as we would not be able to view it again.

Step 4: Cloning Repo to our local system. (Open local Terminal/CMD to run the command)

* Command for cloning: git clone https://github.com/WWSO-SA-ALL/Kendra-Project.git

[Image: Image.jpg]
* Once the repo is created, we could see a button called Code, when we click that we get an URL for the repo, which can be copied to clone the repo to our local system through the command mentioned above.
* When the clone command is run through the terminal, we would be prompted to enter the username and password for our Github account. We can enter our username and for the password, enter the Personal Access Token that we generated and saved to our local system.
* This will authenticate us to clone the repository to our local system.

Step 5: Once the repository is cloned to our local system, it creates a folder which will act as a local copy. Any files and folders that we update inside this git repo will have version control (meaning we can see, track and edit the changes at any point).
Step 6: Adding files to the git repo:

* We can copy all our files that we need to push to git inside this git folder.
* Once that is done, we can run the following commands inside the git repo terminal
    * git add .
        * This adds all the different files in the directory to the staging area. Alternatively, we can add specific files alone instead of adding all the files.
            * git add filename
    * git status
        * This tells us what all files have been changed from last time.
    * git commit -m “initial commit message”
        * This command commits our changes to git with a commit message. We can edit the message depending on our commit.
    * git push -u origin main
        * This command pushes our changes to our git repository.

For ease of use and controlled access, I have created an organization to monitor who can access the resource. I can give access to the user for our Kendra Project as and when required depending on the access level needed.

* Multiple collaborators can be added to the project to control the contents of the project.
* I can add accounts to the organization once the Github account is set up.

