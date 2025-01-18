<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*hED79iPpQEcVg4R7BJs3SA.jpeg" alt="bash.jpg">
</div>

<h1 align="center" style="font-size: 80px;" >Master Git and Github Integration in just 2 minutes <h1>

### Written by : [MUHIB ARSHAD](https://medium.com/@muhibarshad)
### Provided by : [MUJEEB ARSHAD](https://medium.com/@mujeebarshad007)

> "This Repository is intended for those who have already installed Git and GitHub but have not yet started working, or are experiencing problems.
> Please note that the process of downloading, installing, and creating an account on GitHub will not be covered."

## I have observed that many people encounter errors and difficulties while working with Git and Github, and often spend hours watching YouTube videos and reading lengthy blogs.


## Main Goal Of this Repository is to teach you:

1- How to create a repository on git<br>
2 - How to integrate it with Github remote respository.



## How to create a repository on git .

- Open your folder in VS Code and run these commands to globally authorize yourself first.



**Set up Git:**
   - Run the following commands to configure your name and email:

    git config --global user.name "xyz123"
     git config --global user.email "xyz123@gamil.com"
     

## The crucial aspect here is to ensure that you provide a space after the keywords ‘name’ and ‘email’. Verify that you are globally integrated with the terminal.


     
     git config --list

     



## You will be prompted for both your name and email in the terminal. After providing that information, run these commands to create an initial version of Git.



     git init

     touch Readme.md
     
     git status
    
     git add -A
       
     git status
       
     git commit -m"Added Readme File"
     
     git status
   
### After this, Now you can create your remote repository.


# How to integrate it with Github remote respository.



### Don’t Do this during Creating the Remote Repository


## Do not add any files such as a README or license file at this stage. Only add the name, description, and visibility. Once you have done this, run the final commands..

 


     git remote add origin "yourRemoteRepositoryClonedLink"

     git branch -M main

     git push -u origin main
    


##  And that’s it, your git and github repositores are connected.


 # Bonus Command

### If you have added files such as a license to your remote repository and wish to retrieve it to your local repository, simply run this command in your local repository’s terminal.


    git pull
    
## Thank you for reading .



     

   <div align="center">
<p align="center">Let's connect!</p>

<a href="https://www.linkedin.com/in/mujeebarshad001/" target="blank">
    <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<a href="https://medium.com/@mujeeb.arshad001" target="blank">
    <img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" />
</a>



<a href="https://web.facebook.com/profile.php?id=100068858810055" target="blank">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" />
</a>

<a href="https://www.instagram.com/mujeebarshad7/" target="blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
</a>

</div>

## Show your support

If this Repository was helpful to you, please consider giving it a ⭐️.
You can also follow my GitHub profile to stay updated on my latest projects:
<a href="https://github.com/mujeebarshad007" target="blank">
@mujeebarshad007
</a>

## 📝 License

Copyright © 2022 [MUJEEB ARSHAD](https://github.com/mujeebarshad007).
