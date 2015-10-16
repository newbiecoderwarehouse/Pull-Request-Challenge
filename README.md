# Pull-Request-Challenge
Coder Newbie Warehouse challenges you to get better acquainted with git and Github. 

This challenge should only take you between 2 and 10 minutes to complete, depending on your familiarity with git and Github.

#### Required Materials - For beginners and intermediate/advanced
1. A Github account. To sign up, visit: https://github.com/join

That's it! :) 

#### Resources
- [git - the simple guide](http://rogerdudler.github.io/git-guide/) which give you a quick overview of the git workflow.
- [Pull Request Video](http://www.youtube.com/watch?v=YTbRzhQju4c) 

Click on the video below to learn more about pull requests.

[![Alt text](http://img.youtube.com/vi/YTbRzhQju4c/0.jpg)](http://www.youtube.com/watch?v=YTbRzhQju4c)

####Which route to take?
If you have little or no previous experience with git and Github, then take the beginner route.
 
If you have some experience with adding, committing, and pushing Github projects either locally or through an IDE, we recommend the Intermediate/Advanced route.

##Beginner Route 
#### Knowledge/Experience
Some basic knowledge of git and github but not required.

#### Steps
1. Go to the [Pull-Request-Challenge Github Repository](https://github.com/newbiecoderwarehouse/Pull-Request-Challenge)
 - If you reading this direction set from the README.md file, then you are in the repository.
2. Click on the **template.md** document. (Note: this is the doc you will edit.) <br>![enter image description here](https://s3-us-west-2.amazonaws.com/newbie-coder-warehouse/images/beginner-steps/templatemd.png "template.md")
3. After the **template.md** page loads, click on the "edit this file" button (to the left of the trash can)
	- The hover text will say "Fork this project and edit the file" <br> ![fork and edit](https://s3-us-west-2.amazonaws.com/newbie-coder-warehouse/images/beginner-steps/edit-fork-file.png)
	- Forking projects means that you have a version of this repository connected to your Github account. So basically you have the complete version of the challenge for you to change and send back to NCW for us to add your file (a copied version of template.md with your answers) to the project. Pretty cool huh?
4. After the page loads, you'll see this:<br> ![enter image description here](https://s3-us-west-2.amazonaws.com/newbie-coder-warehouse/images/beginner-steps/edit-file-result.png) Change the name of the file from the original **'template.md**' to **'yourgithubusername.md'**. <br> ![enter image description here](https://s3-us-west-2.amazonaws.com/newbie-coder-warehouse/images/beginner-steps/rename-file.png)This will save a new file to the forked project and will be the file that you will do a pull request for us to merge together on the main NCW repository.  
5. Add your answers directly on this edit page <br> ![enter image description here](https://s3-us-west-2.amazonaws.com/newbie-coder-warehouse/images/beginner-steps/add-answers.png)
6.  After adding answers, scroll down to the "Propose file change" section
	- In the first input field, enter "Add yourusername to the challenge" (but actually input your Github username.)
	- The body text text is optional. For this challenge, don't worry about putting anything in this area.
	- When finished, click on the green 'Propose file change' button <br> ![enter image description here](https://s3-us-west-2.amazonaws.com/newbie-coder-warehouse/images/beginner-steps/propose-file-change.png)
7. After the 'Comparing changes' page loads, click on "Create pull request" <br> ![enter image description here](https://s3-us-west-2.amazonaws.com/newbie-coder-warehouse/images/beginner-steps/comparing-changes.png)
 - Note: This is a interesting area to focus on. Scroll down and see the changes you have made (highlighted in green) and the red is what has been deleted <SCREENSHOT>
8. After the "Open a pull request" loads, you will see what you wrote before (In Propose file change) now in the commit section in the first input area. (Also, if you added anything in the body area, it will show up here as well) <br> ![enter image description here](https://s3-us-west-2.amazonaws.com/newbie-coder-warehouse/images/beginner-steps/after-click-Open+a+pull+request.png)
- Click on "Create pull request" 
8. Challenge Complete! <br> ![enter image description here](https://s3-us-west-2.amazonaws.com/newbie-coder-warehouse/images/beginner-steps/once-done.png)
 - Wait (we will add your changes ASAP)


----------


## Intermediate/Advanced Route
#### Materials
- A local or IDE development environment with git installed
  - Most IDE environments have git installed
  - [Instructions on how to install git locally](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  - Recommended IDE: [cloud9](https://c9.io/)

#### Knowledge/Experience
- Basic knowledge of git and github such as add, commit, push, and pull.
- Know what a [Forked project](https://help.github.com/articles/fork-a-repo/) is and how to work within it. 
- Familiar with working on a project locally or through and IDE

#### Steps
 1. Fork the project
	 - In the repository, click on the fork button in the top right corner
	 - This will make a copy of the project and connect it to your account
 2. Clone the forked version of the project to your local or IDE environment
	 - Once the forked project loads, click the copy to clipboard button from the HTTPS clone url section
	 - After you have the url to clone, go to you local or ide environment and run a git clone of the forked repository (code at bottom of this list)
	  - **Important**: Make sure this is a forked copy of the repository, if the url doesn't have your username, you may not have forked properly. If you forked properly, you don't have to push the copy button. You can use the code below and insert **your own github username**.
    - `git clone https://github.com/yourusername/Pull-Request-Challenge.git`
 
 3. Make a new branch and name it your Github username
    - `git checkout -b yourusername`

 4. Copy/paste/rename the template.md file to your Github username
     - The template file should not be edited. A new copy of the template.md file with your username will make it easier to merge into the repository. 
 5. Answer the questions and save it
 6. Commit the changes
     - `git add -A`
     - `git commit -m "Add yourusername to the challenge"`
 7. Push the branch of the forked repository
     - `git push origin yourusername`
 8. Submit a pull request from your forked github repository
