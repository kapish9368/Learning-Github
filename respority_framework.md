                                ***Author***

In this we are going to understand about several type of repository and all type of git command and github functionalities and learn complete git hub.

so let's start by making the journal about this project.

        11/02/2026
i am going to learn about how to add any file in git and publish it on github.

# i am going to publish this one to git repository and also by vs code git extension.

1.  for basic understanding i use vs code copilot chat. ("how to connect any file to git nd github from basic without using git extension of vs code ")
2. I also use shreya didi guide from "Apna college" for more understanding. (" 
        *what i learn't from it* 
      1. open terminal 
      2. Go to directory or file in which you want to add in git or Git repository by command "cd _file name_" and press enter.
      3. Gave the command "Git Init" in the terminal for making git file, in which we are in now.
      4. Now we make one another file of python or any language  as our program work.
      5. Now we go to our Github site and create a Repository by adding Name, Description, Readme adn visibility.
      6. Now we copy its link from the button <code> and 'we prefer https link over ssh'
      7. Back to Terminal we run command "git remote add origin <link>" <link> == copied link.
          *For checking the add happens or not we run git remote -v*
      8. soo after adding we can check branch via "Git branch" by default it 'main' but if you want to change the name the you can use command "git branch -M <name>. 
      9. *But when i run that command i got encountered by an error saying you 'failed to push some refs to <link> 
      10. So for that, basically what just happens is 'my history of making file' making conflict to my Github repository so for that we did "git pull origin main" and another \"git pull origin main --allow-unrelated-history" than after we try to "git push origin main" which resolve over confiliction.
      11. so when now we check "git branch" it's shows us 'main' 
        *By running "git push -u origin main" we can simply tell the git that we want to push always in this in this repository.
      12.                  )