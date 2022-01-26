# [January 13th] Start of Notes!

on January 13th I had my first meet with Erik Ostlund! We talked about what I wanted out of this mentorship, and a brief overview of types of developers.

> - Frontend: Area where the user interacts, includes user interface
> - Backend: More data oriented, needing the data for the user to actually be able to interact
> - Fullstack: A developer that can perform both frontend and backend development

---

## **[Github](https://github.com/)**

Next we went over github, a place to control versions, and establish a main branch of a project. Next I went and made a github account. Erik showed me his profile and his projects on github to show how exactly it works. He also showed me S.goulas' project in which she writes a _[development dairy](https://github.com/sgoulas/pdpProject/tree/main/docs/DevelopmentDiary)_ to record her progress and document what she learns. Erik stresses the importance of documentation, so you can document what youve done in a project for future reference.

## **[Visual Studio](https://visualstudio.microsoft.com/)**

Erik showed me how to install Visual Studio, and make a folder and make a file (this file). Our next objective was to get this file up on github, for this I had to install _[gitbash](https://git-scm.com/downloads)_.

## **[Markdown](https://www.markdownguide.org/cheat-sheet/)**

After installing gitbash we decided to hold off on uploading it to github, and instead focusing on learning how to use markdown to a development dairy for my mentorship. To help get my self familiar with markdown, he showed my the markdown cheat sheet, to learn how to format with the language.

---

# [January 14th] Learning Git

The very first project update! That was today's goal, before getting into the main plate I would need some of the code for git. For this I was given a [Youtube Video](https://www.youtube.com/watch?v=1ffBJ4sVUb4), as well as a [cheat sheet](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet). A list of the commands we will be using.

> - Init: Marks it as a git project
> - Clone: Replicates a project
> - Add: Stages changes for the commit actions
> - Commit: Commit your work to a save point
> - Status: Checks which files are staged or unstaged
> - Push: Push your changes into a main branch
> - Pull: Pull changes from main branch into your project to keep your version in synch

---

## **[Github Desktop](https://desktop.github.com/)**

One more way of using git is with a GUI (graphical user interface). Unlike using a terminal which comes with any computer, it allows for easier commands with the press of a button, it also displays more information at a time making it easier to visualize your actions.

## **Making a Repository**

Before I can update any changes I must make a project on Github, which the first part is as easy as naming a project and setting up some basic settings, but next comes the code.

> - `cd (desired destination)`
> - `dir`
> - `git init`
> - `git remote add origin (github repository)`
> - `git remote -v`
> - `git status`
> - `git add README.md`
> - `git commit -m "initial commit"`
> - `git status`
> - `git push -u origin main`

## **Updating a Repository**

Now that a repository has been made, I need to update any changed I make to the file. This is a much more simple process but is still enacted by the following lines of code.

> - `cd (desired destination)`
> - `dir`
> - `git status`
> - `git add README.md`
> - `git status`
> - `git commit -m (message)`
> - `git status`
> - `git push -u origin main`

---

# **January 20th [Git Cont.]**

We talked more about git and how it is open source. Today was about git in a real world work environment, as well as learning more of the intricacies of Github.

## **Code**

The code tab contains just that code, however it is way more expanse. It contains not just the actual code of a file, but the entire project, from small readme files to vital parts of code. All of it is in the all encompassing Code tab.

## **Issue**

The Issue tab is awesome, something that I wish I could have in any group project. The issue tab shows sections of code or parts of the project that have been tagged with one of the many tags available, some are even custom for the project, for instance the tag I have made for this project is "typo" for any spelling errors. It can be more than just an error or bug, but it can flag entire enhancements like updating certain processes in the code.

## ** Pull Requests**

Pull Requests are the culmination of work, as people add new features, or fix bugs they eventually will need to put all that work into the main branch, that is exactly what pull request does. It allows people to request for their work to be pulled into the project, which is then reviewed by a fellow development team member, and then approved or denied.

## **Projects**

Projects is my favourite feature listed so far. It acts as a big to-do list separated by what is not being worked on, what is in progress, what is currently in need of or being reviewed for a pull request, and what is all done and in the main branch. You can also see past projects and current, and it is an awesome way to keep track of big bug patches or adding an entirely new feature.

---

# **January 21st [HTML/CSS]**

Today we took more of a break on git and github, and focused on HTML and CSS, we established a project file. Worked on getting a basic html file setup.

---

## **HTML (The Skeleton)**

At the very beginning of a document should by the type a file we are making, which is HTML, next is the three major parts of the body. The html, the head, and the body. The head contains all type of meta data, things that descibe what the file is, like the author, the name of the application, and the title to display. As well as draw from other files in the application. The body is the actual content of the application. If I were to start a paragraph with the p command it would display anything I write. It is also where if I wanted to, I could display the image that I had picked from the head. HTML is everything, html is simply what is all contained within the file, both the header and the body would go here.

## **CSS (The Stlye)**

We didn't dive as much into CSS, as it is more of styling, than containing actual data or metadata, it more makes changes to the actual visual aspects of the file. Margin and padding are both examples of spacing, Margin is the space between the outside of the document and border around text. Padding is the space between the text and the border around that text. These both can be adjusted for different spacings. Font size is also changed and there are different units for font size. You can use the traditional pixel way or a unit called em which is bigger per one unit that pixels (think of meters vs feet). We also talked about font and how to change the text of said font, by using the font-family command. Erik also talked about where to go for more fonts, and that is google fonts which hosts all types of different fonts.
