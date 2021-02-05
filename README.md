# To contribute in this repository, perform the following steps.

1. Fork this repository(by clicking the fork button above).

   Now run the following code in your terminal/prompt : 

2. Clone the forked repository(the repository made in your account after you forked this repo) by running this command

       git clone https://github.com/(YOUR_USERNAME)/icefeet-2020.git
       cd icefeet-2020
       
   This command will take you to the folder containing the code.
   Currently you are on your master branch. Inorder to contribute to my repo, you need to work on another branch in your
   repository.

3. This command set this repo as your upstream repository in order to make pull requests and get further changed codes.
 
       git remote add upstream https://github.com/jhasaurabh312/icefeet-2020.git


4. By performing this you locally have the updated code present in this repo.

       git pull upstream master


5. This command will create a new branch named develop in your repository and you are on the develop branch.

       git checkout -b "develop"


6. DO ALL THE CHANGES YOU WANT TO DO IN THE CODE and push the changed code by running these.

       git add.
       git commit -m "COMMIT_MESSAGE"
       git push origin develop

   By doing this step, you have pushed your updated code on the develop branch of your repository.

7. Make a pull request from your repo to this(original) repo.

       Click on the green pull request button.
       Base repository : THIS REPOSITORY.    Base : MASTER
       Head repository : YOUR REPOSITORY.    Compare : develop(branch name you are working on)

8. Once your pull request gets merged, Do the following steps : 
          
       git checkout master   (this step just changed your working branch from develop to master)
       git pull upstream master (you got the new code from this repo in your master branch)
   
9. In order to further contribute to this repo, repeat the steps from STEP-4 with a new branch name
    (branch name was develop until now) E.g.
    
         git checkout -b "XYZ"
      
      
      
.............................................................................................................................
          
          
   
   





 
 

 
