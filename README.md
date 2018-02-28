# README

The purpose of this **practice repo** is to get experience using & collaborating with **git** and **GitHub**. If you don't have one already, please [create a GitHub account](http://www.github.com) as it is required to contribute to the project.

This document serves as a **README** that may be used later as an *Initial Commit* in a subsequent *GwG Project Repo*.

<h2>Instructions</h2>

>**@lestec**

Hi everyone from GWG! Your first mission is to read through this README.md file in its entirety as it lays out important group project details. At the end, you will be given a chance to select a team to contribute with and will be providing the following: 

<ul>

<li>name</li>

<li>discussion forum username</li>

<li>slack username</li>

</ul>

**Making a Pull Request: Why?**

One of the key points of the feature branch workflow is that the developer who wrote the code does not merge the code with master until there has been a peer review. Leveraging Github's pull request features, once you have completed the feature branch and pushed it to the repo, there will be an option to review the _diff_ and create a pull request.

[More information below](#learning-git-and-github)

With all of that being said, lets make some changes below. Have fun and good luck!
<hr>


###  Table of Contents
[Website Objective](#website-objective)

[Learning Git and GitHub](#learning-git-and-github)

[How I Pulled This Repo Using GitHub](#how-i-pulled-this-repo-using-github)

[Current Group Tasks and Deadlines](#current-group-tasks-and-deadlines)

[Project Goals](#project-goals)

[Project Team Sign Up](#project-team-sign-up)

[Teams](#teams)



 >**@chrisneal**
## Website Objective
The majority of us have voted to do a site dealing with *links and resources*. Now we just need to focus more on that objective. 

How about a site compiling links, tutorials, and articles shared in the **Udacity Discussion Forums**? This would ultimately be a site where the following class could visit and learn the best resources on how to tackle the challenge lessons from the course - anything that has helped us and others (git/Github links, JavaScript articles, motivational tips, etc.) towards moving on to the *Front End Nanodegree* course.

We can think about and expand on this concept a little more, **1-2 weeks** should be plenty of time to gather ideas and identify the main concept of the website.

[[back to top]](#readme)

## Learning Git and Github
If you haven't already, please begin learning **the fundamentals of git** and **collaborating on GitHub**. Most of the fundamental learning will involve using git on your local machine and we will be using GitHub's collaborative features to build together.

> #### This is necessary, especially if you plan to contribute code to the project.


### Git and GitHub Learning Resources
Here's some links that were passed around in the forums that I believe are some of the best and I added some that really got me on track with making pull requests and stuff (**SPOILER**: it's easy!).

* [Udacity Course: How To Use Git and GitHub](https://www.udacity.com/course/how-to-use-git-and-github--ud775) *(course)*

* [How Not To F- Up Your Local Files w/ Git pt 1](https://medium.com/@francesco.agnoletto/how-to-not-f-up-your-local-files-with-git-part-1-e0756c88fd3c) *(article)*
* [GitHub Help Guide: Forking Projects](https://guides.github.com/activities/forking/) *(article)*
*  [YouTube: Creating A Simple Github Pull Request](https://www.youtube.com/watch?v=rgbCcBNZcdQ) *(video)*
* [Youtube: Git & GitHub Tutorial for Beginners #11 - Collaborating on GitHub](https://www.youtube.com/watch?v=MnUd31TvBoU&t=402s) *(#12, too! video)*
* [How To Collaborate on GitHub](https://code.tutsplus.com/tutorials/how-to-collaborate-on-github--net-34267) *(article)*
* [Git Forks and Upstreams](https://www.atlassian.com/git/articles/git-forks-and-upstreams) *(article)*

### How I Pulled This Repo Using GitHub
**@lestec** initialized this repo and wrote the introduction to this *README.md* for us all to work on. *Thanks again!* This is what I did to contribute to it, step-by-step:

1. **Visit the main repo and fork the repository** I went to her [GwGpractice Github page](https://github.com/lestec/GWGpractice), (she also posted the link in the forum). The fork *should* link back to your page and place you inside that repository.

> **Note:* You can actually make minor revisions from this page and create a pull request all from the interface. It's good for practice with minor code fixes, etc. However, I suggest we all do what I did in the next step...*
2. **Clone that fork** from *your* page to your local machine. [Here's some help](https://help.github.com/articles/cloning-a-repository/)
> ***Tricky part: The **master** branch was there, but I didn't see the **dev** branch we'll be pushing our changes to to make pull requests. To get that latest branch I first created a branch off the master named **[my name]-dev**. 
```
 git checkout -b chrisneal-dev
 ```
That's the syntax we'll use for making our branches/changes for now: **[your name]-dev** 

I merged the latest changes _(from the dev branch online)_ by using
 > 
 ``` git merge origin/dev```

The experience may be very different for you, if any issues come up we'll pull you through.

 3. **Make your changes and push them** From there, I was able to make changes to what she had and pushed my changes *(this part of the document)* up to [my GitHub fork](https://github.com/chrisvneal/GWGpractice). At this point is where I began the *pull request process*. If you have any questions about any or all of this from here, ask one of us and we can help or refer to one of the [Git learning resources](#git-and-github-learning-resources).

	[[back to top]](#readme)


## Current Group Tasks and Deadlines

* We have **1 week** *(by March 4th or 5th)* to [choose a team](#project-team-sign-up) to 			  contribute with. How would you like to contribute? More details below.

* We have **1-2 weeks** *(by March 12th?)* to:
	*  Learn and understand the fundamentals of git and collaborating on GitHub
	* Revise and understand the website/application's main objective & purpose 
	* Create somewhat of an initial layout/design of the main page

## Project Goals
* Learn git/GitHub & web development in a "remote group environment"
* Create a simple project; **1-2 pages** *w/ room to expand*
* Practice what we've learned so far in the course
* Be challenged! Not overwhelmed
* Work in small teams, hoping everyone will have a meaningful role


## Project Team Sign Up
Let's keep this process simple! 

The only change you will be making for now is adding your name to whichever team you'd like to contribute with using the format below. 

**This syntax creates a table in Markdown, all you have to do is edit/insert your information like so:**

```
Name         | Disc Forum @ | Slack @ | Link (optional)
-----        | -----        | -----   | -----
(your name)  | (your @)     | your @  | optional link
```
 You'll get it when you see how others have done it. If not, just ask someone. This list will determine who the contributors are for this project. Adding your name to a table is as easy as separating your info with the **pipe** character like this:
 
```name | disc forum name | slack name | (optional link) ```


>#### You can be on more than one team, just make sure there are enough duties for everyone to contribute meaningfully.

[[back to top]](#readme)

---

### Teams
* [Wireframe and layout design](#wireframe-and-layout-design)
*  [HTML refactoring and optimization](#html-refactoring-and-optimization)
*  [CSS refactoring and optimization](#css-refactoring-and-optimization)
* [JavaScript refactoring and optimization](#javascript-refactoring-and-optimization)
* [Asset Gathering](#asset-gathering)
* [Copy and grammar editing](#copy-and-grammar-editing)
* [Git assistance](#git-assistance)

### Wireframe and layout design
Contributors in this group will create a mockup/wireframe/sketch of what the site would look like and would most likely be **initiating CSS styling**.

Name         | Disc Forum @ | Slack @ | Link (optional)
-----        | -----        | -----   | -----
(your name)  | (your @)     | your @  | optional link

### index.html
Contributors in this group will work with the wireframe and layout design team to create the initial *index.html* file.

Name         | Disc Forum @ | Slack @ | Link (optional)
-----        | -----        | -----   | -----
(your name)  | (your @)     | your @  | optional link
Tyler Van Schaick  | tylervucf   | tyler-vs  | [github/tyler-vs](https://github.com/tyler-vs)


### HTML refactoring and optimization
Contributors in this group will refactor and optimize the structure and semantics of the ***index.html*** file *(checking syntax errors, etc.)*

Name         | Disc Forum @ | Slack @ | Link (optional)
-----        | -----        | -----   | -----
(your name)  | (your @)     | your @  | optional link

### CSS refactoring and optimization
Contributors in this group will refactor and optimize the structure and semantics of the ***stylesheet*** file *(checking syntax errors, etc.)*

Name         | Disc Forum @ | Slack @ | Link (optional)
-----        | -----        | -----   | -----
Chris Neal   | chrisneal    | Chris N | [github/chrisvneal](https://github.com/chrisvneal/GWGpractice)

### JavaScript refactoring and optimization
Contributors in this group will refactor and optimize the structure and semantics of the ***.js*** file, ensuring best practices *(checking syntax errors, etc.)* Contributors may also choose to **initiate interactivity scripting** when necessary.

Name         | Disc Forum @ | Slack @ | Link (optional)
-----        | -----        | -----   | -----
(your name)  | (your @)     | your @  | optional link

### Asset gathering
Contributors in this group will gather resources for images, icons, and media pertaining to the main concept while working closely with the ***wireframe layout*** and ***index.html*** teams for guidance.

Name         | Disc Forum @ | Slack @ | Link (optional)
-----        | -----        | -----   | -----
(your name)  | (your @)     | your @  | optional link

### Copy and grammar editing
Contributors in this group will help spot grammatical and spelling errors within the site's body & content.

Name         | Disc Forum @ | Slack @ | Link (optional)
-----        | -----        | -----   | -----
(your name)  | (your @)     | your @  | optional link

### Git Assistance
Contributors in this group will 

* help manage the main project repo *GWGpractice*  
* help others with git and pull requests on Github and  
* *help with code review* of any code before it gets merged into the main project branch, **master**.

Name         | Disc Forum @ | Slack @ | Link (optional)
-----        | :-----:        | :-----:   | :-----
Leslie Tecumseh | lestec     | lestec  | [github/lestec](https://github.com/lestec/GWGpractice)
Chris Neal | chrisneal | Chris N | [github/chrisvneal](https://github.com/chrisvneal/GWGpractice)

[[back to top]](#readme)