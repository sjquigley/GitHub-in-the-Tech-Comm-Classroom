#Forked Collaboration  

Using Git to copy, edit, and compare files within the same server. In this lesson you will learn the basics of forked collaboration and from there, you can use these same methods to teach others. No...of course this isn't a pyramid scam!

Bennefits of this method...

* make your own downstream version of an open-source repository
* benefit from changes that may occur upstream
* collaborate with others you may not know...by simply making pull requests

Disadvantages

* repositories must be public to contribute
* projects will be inherently decentralized
* you may lack other tool affordances




##Directions

1. Fork our [ATTW GitHub Repository]().
![](fork.png)
2. If you don't have a GitHub account, you will be prompted to make one now. *Welcome to GitHub! Meow!*
3. Next, you'll create your own branch. Click on "**Master**," and in the fill line type "**mybranch**." To save, click just below on "**create branch:my branch** from 'master'."
![](mybranch.png)

*So far you used git via the GitHub website to fork a repositiry and create two different branches downstream. Pretty cool!*

Now let's make some edits to your branch.

4. In your branch, click on the index.html file. Click on the pen tool which will allow you to edit the file. Scroll through the code until we find the code narrative section. Delete my narrative and replace it with your own. Take a moment to share your own code narrative and what brought you to this workshop.  
5. Once you have finished, scroll down to the bottom of the page and click "**Commit**"
6. Cool, let's get your narrative out there on the internet! Go to settings.
7. On the side bar, click Pages.
8. Change the branch from Main to 'my branch.'
9. Copy the URL GitHub has just given you. After a couple minutes, you will be able to access your website URL in any browser.
10. In the about section, you can paste in your GitHub Pages URL.

Now let's share your contribution with the base repository you forked. To do so, we will need to make a **pull request**

11. Make sure you are still in "**my branch**" and Click "**contribute**" and then "open pull request."
12. Write a comment to let the base repository owner know what this pull request does. Then click "**create pull request**" Don't worry if there are conflicts.
13. If your pull request is approved, your edits will be **pushed** into the base master repository. Note that they may request changes before pushing these changes.
14. Once your pull request is closed, you can may be alerted that there your request was approved or that there are other changes upstream. Alternatively, you can click "fetch upstream" and Git will compare the changes in the two repositories. If there are changes, you can click "fetch and merge."

*So what just happened?* Well, you made a change to your own branch file and then used Git to suggest changes upstream to the master repository. Once that change was approved, you used Git again to merge changes from the upstream master to your downstream master. You now have an updated master and a your own protected version of this . *Git is pretty cool, right?*

As you edit further, you will want to "download" or "clone" files to your computer where you can work locally to edit the files before committing them to your repository branch. 



Peace and love, Stephen Quigley, University of Pittsburgh
