# Pull me some quotes ![GitHub forks](https://img.shields.io/github/forks/donyd/pull_quotes)

This starter project will guide you through making your very first pull request while adding an update, in the form of a quote of your choice, possibly from someone famous, or your own perhaps. 

This can be followed through steps outline in this document or through the video tutorial:

[![github pull request](https://img.youtube.com/vi/mW58ovL8MDI/0.jpg)](https://youtu.be/mW58ovL8MDI?si=E2WrOcRwTH88ma01)

*At the onset this will be just a simple html page with text that showcases some famous quotes. This may, or may not, be spruced up later.*

If you are feeling generous you can send me a tip through either of these:

[![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/donyd)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/mindkiln)

Made with and in:

![HTML](https://img.shields.io/badge/HTML-e34c26?style=flat&logo=html5&logoColor=white)  ![CSS](https://img.shields.io/badge/CSS-1572B6?logo=css3&logoColor=fff) ![Static Badge](https://img.shields.io/badge/Pico%20-%20CSS%20-%20Orange)



![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Windows 11](https://img.shields.io/badge/Windows%2011-%230079d5.svg?style=for-the-badge&logo=Windows%2011&logoColor=white)


## How to use this repository
*These steps outline the simple flow on how to use this project. If you prefer a more visual approach, checkout the video mentioned earlier.*

### From Github with love 

1. Fork this repo, which will create a copy of the project to your own github account.
2. From the newly copied repo on your own github account, click on the code button then copy the HTTPS string.
3. Open a terminal window on your local machine and run this command + the string you copied in step 2 in a folder of your choice.
```
git clone https://github.com/[username]/[repo_name].git
```
*This is an example of using HTTPS and username would be your Github username and repo name... well you get the picture, I hope. And no square brackets while running it, the text that is copied from step 2 should be used*.

### Make like a tree and branch out
*From the previous section, there should be newly created directory where the Github repo was copied to on your local machine.*

1. Change directory to the newly cloned repo:
```
cd make-quotes-not-war
```
2. Create and switch to new branch to make the update on:
```
git checkout -b <some-name>
```
*Give a name like dev, or something more specific like add-quote, without the angled brackets <>.*

### Change and Push
*This is where we will be making changes to be pulled into the actual repo*.

1. Open the index.html file in an editor of your choice.
2. Add in the following chunk of code right above the top most quote in the div with class "quote":
```
<blockquote>
    <p>Your quote here</p>
    <cite>Quote Author</cite>
        <div id="content-data">
            Github: <a href="https://github.com/yourgithubusername" target="_blank">Your username</a>&nbsp; |
            <time datetime="202#-##-##">&nbsp; Added on ##<sup>th</sup> Month '##</time>
        </div>
</blockquote>
```
*You can open up the file locally to verify the changes made.*

3. Add the changes made to be staged:
```
 git add .
``` 
4. Commit the changes made:
```
 git commit -m "your message here"
```
*Message can be something simple like "add quote: username"*

5. Push your changes to the forked Github repo you made: [Note: ensure that you are on the same branch that was created earlier before.]
```
git push --set-upstream origin <branch name>
```
*Branch name will be the same that you created right after cloning, for e.g. add-quote if that's the one you used.*

### Pull 
*Back on your forked repo, you will see that a notification has appeared called "Compare & pull request."*

1. Click on the *Pull requests* tab at the top.
2. Click on the *New pull request* button that appears on this page.
3. This will open up a new page titled "Comparing changes."
4. On the dropdown lists, the right hand side represents the repo/branch you want to push from. Select the forked repo/branch you push up from the last section. [Selecting this should show the notification with the button "Create pull request"]
5. The left hand side would be the repo/branch you want to push the changes to
6. Click on the "Create pull request" button once ready.
7. Here you can update the title of this request as well as add a description if you wish.
3. Once you are satisfied, click on *Create pull request*.

---
Some checks will run to ensure there aren't any merge conflicts. If all goes well, You have successfully submitted your very first pull request!

What happens next, would be the owner of the original repo you forked from, will receive a pull request, which can be reviewed and merged or changes can be requested to make updates before being accepted.

Once the Pull Request has been accepted, this will be displayed on your side with the message "Pull request successfully merged and closed."

You can now delete the branch you created or the entire fork and see your work added to the main project repo. This can be viewed here:

* [Pull me some quotes](https://donyd.github.io/pull_quotes/)

The accompanying video shows this and all the steps we've gone through with additional details, including what happens after a pull request is received.
