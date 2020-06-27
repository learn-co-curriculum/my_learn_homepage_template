<!--- Calendar iframe goes below --->
<iframe src="insert_source_url" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>

- Note: calendar times are in {Eastern Standard Time (EST)}

# ANNOUNCEMENTS

> ## WELCOME WEEK:
- Welcome Events
    - Environment Set-Up: xx/xx/xx @ xx am 
    - Orientation: xx/xx/xx @ xx am 
    - Meet Your Classmates: xx/xx/xx @ xx am 

- Study Groups:
    - Tues - Thurs
    - 12 pm
___

# IMPORTANT LINKS

## STUDY GROUP RECORDINGS & NOTES REPOS

  - 📺[YOUTUBE STUDY GROUP PLAYLIST: <COHORT NAME>]() <ADD URL>

  - 📓[STUDY GROUP NOTES REPO: <COHORT NAME>]()  <ADD URL>

  - 📆[GOOGLE CALENDAR LINK - <COHORT NAME>]()  <ADD URL>

- **NOTE RE NOTES REPOS:**

  - 🚨**DO NOT FORK NOTES REPO BEFORE CLONING** (to easily get all new notebooks.)

  - Just clone directly and run `git pull` from inside the repo's folder in your terminal to get the new notebooks.

## RESOURCES FOLDER

- 🗂[STUDENT RESOURCES GOOGLE DRIVE FOLDER](https://drive.google.com/drive/folders/1E3JBOl0uhLMRKvl9R5vpl6xaxchiJ6JA?usp=sharing)
  - See  Student Resources Section farther down the page for details.

## CONTACT INFO

### Your Instructor/Cohort Lead

> **James M Irving, Ph.D.**<br><br>
💬[Slack DM (@James Irving)](https://learn-co.slack.com/team/UP0AQ4CUA)<br>
📩[james.irving@flatironschool.com](mailto:james.irving@flatironschool.com)<br>
🗓[Schedule a 1 on 1 Meeting](https://go.oncehub.com/JamesIrvingOfficeHours)<br><br>
👨‍⚖️[My LinkedIn](https://www.linkedin.com/in/james-irving-4246b571/)<br>
💾[My GitHub Profile](https://github.com/jirvingphd)

### Your Education Coach

>**Dara Paoletti**<br><br>
💬[Slack DM (@Dara Paoletti)](https://learn-co.slack.com/team/UECFYN690)<br>
📩[dara.paoletti@flatironschool.com](mailto:dara.paoletti@flatironschool.com)<br>
🗓[Schedule a Coaching Session](https://darapaoletti.youcanbook.me/)

### Student Services

Student Services Email<br>
📩[studentservices@flatironschool.com](mailto:studentservices@flatironschool.com)



___

# STUDENT RESOURCES

## TABLE OF CONTENTS

I. STUDENT RESOURCES GOOGLE DRIVE FOLDER CONTENTS

II. MODULE PROJECT INFO/PROCESS

III. How to: install and activate Jupyter Notebook Extensions

V. COMMON COMMANDS

VI. ADDITIONAL VIDEO PLAYLISTS

___

## I. STUDENT RESOURCES GOOGLE DRIVE FOLDER CONTENTS

> Contains a collection of resources, cheatsheets, and official best-of collection of study group videos in a gsheet.

- [GOOGLE DRIVE LINK](https://drive.google.com/drive/folders/1E3JBOl0uhLMRKvl9R5vpl6xaxchiJ6JA?usp=sharing)

- **TWO MUST-SEE DOCS IN MAIN FOLDER:**
  1. [Master Python Data Science Cheatsheets PDF](https://drive.google.com/open?id=1PxRAhlaK7ucf0S2F732eJ94ovaPtUSE_).
  2. [(New) Student Resources GSheet of Study Group Videos by Topic](https://docs.google.com/spreadsheets/d/1mdvxw0nZsPScAxyopVvPNPbUF34dzK6otIRgQvQN_Bc/edit?usp=sharing)


___

## II. MODULE PROJECT INFO/PROCESS

- Your projects and associated Learn.co lessons can all be found on the [Portfolio Projects Section](https://learn.co/tracks/data-science-career-v2/portfolio-projects) on Learn.
- Project deadlines are on the Google Calendar at the top of this homepage.

### PROJECT SUBMISSIONS

#### 1. "Soft" Deadline AKA "Project Links Deadline"

- Full time: 1 week after project start date.
- Part time: 2 weeks after project start date.

- All required project links must be **entered on the sidebar of the project's Learn.co lesson page** and make sure to **check "I'm done"** at the bottom of the sidebar.
  - Note: you can continue to update your project after turning in the links.

- **Schedule your project review as soon as you turn in your links** (see next section below.)

- **Q: What if I don't have all pieces of my project finished by the soft deadline?**

  - For your notebook and presentation: 

    - You may continue to update your repo's contents up until your scheduled project review.

  - For the video/blog post/READMEs:
    - See "HOW TO USE PLACEHOLDER LINKS FOR Videos & Blog Posts" below

#### 2. SCHEDULE YOUR PROJECT REVIEW

- Use the link below to schedule your project review with me ASAP.
  - [Schedule a Project Review](https://go.oncehub.com/ModProjectReviews)
  - The earlier you schedule your first review, the more time you will have to schedule a second review, if required. 
  - Please push any final changes before your scheduled project review.

#### 3. "Hard" Deadline AKA "Successfully Passing Your Project Review" Deadline

- YOU **MUST SUCCESSFULLY PASS YOUR PROJECT REVIEW WITHIN 2 WEEKS AFTER THE SOFT DEADLINE** / PROJECT LINK DEADLINE.

- You are allowed **as many project review attempts** as you can fit in before the hard deadline.

- Schedule your first review as soon as possible, so you have sufficient time to re-present the project before the hard deadline.

___

## III. Installing and activating Jupyter Notebook Extensions - [Study Group Video on JNE](https://youtu.be/Fl7Xwr_kUkw)

- In your terminal enter the following commands:

  ```shell
  conda install -c conda-forge jupyter_contrib_nbextensions
  jupyter nbextension enable jupyter_nbextensions_configurator
  ```

- When you boot up jupyter notebook, click on the new tab called `nbextensions` on the jupyter notebook home page and check out the list of available extensions.
  - If the list of available notebook extensions is grayed out:
    - Uncheck "`disable configuration for nbextensions without explicit compatibility (they may break your notebook environment, but can be useful to show for nbextension development)`" at the top of the page

- **Recommended extensions to turn on:**
  - `Variable Inspector`: Lets you see details about all of the variables in your notebook.
  - `Table of Contents (2)`: Clickable sidebar with markdown headers as bookmarks/links.
  - `Collapsible Headings`: Collapse sections of your notebook using markdown headers.
  - `Codefolding`: Lets you collapse function definitions and blocks of code. 

<!-- 

<iframe width="560" height="315" src="https://www.youtube.com/embed/videoseries?list=PLFknVelSJiSydTybrkhr3dfRAFCyzAfC6" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->

___

## IV. Common Commands

<details>
<summary style='font-weight:bold'>"Steps to push your changes to your repo"</summary>

```python
cd path/to/repo

git add .
git commit -m "your message here"
git push
```
</details>
<details>
<summary style="font-weight:bold;">Common Terminal Commands</summary>

|command | command will |
| -------| -------------| 
| ls     | list all files in directory | 
| cd     | change directory | 
| mkdir  | create a new directory | 
| cd ..  | will change directory to parent directory |
|        | (the directory above your current directory |
| jupyter notebook | opens jupyter notebook in current directory | 

</details>

___

## VI. ADDITIONAL VIDEO PLAYLISTS

<summary style="font-weight:bold;">Getting Started Videos</summary>

## Getting Started Video Playlist

<iframe width="853" height="480" src="https://www.youtube.com/embed/videoseries?list=PLj2HyUAn9lEmGc4FIasxTQ2S0JAgYttAD" 
frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

| VIDEO | COVERS |
| --- | --- |
|Getting Started 00 |Discusses how to download and install Anaconda for Mac|
|Getting Started 01 |Discusses how to organize your work for the DS program|
|Getting Started 02 |Walks you through setting up your **learn-env** virtual environment|
|Getting Started 03 |Walks you through the learn to github to local workflow that you'll use **every day**

#### Extra Resources Playlist

|Topic| url |
|-----|-----|
|git commands|[https://www.youtube.com/watch?v=5HLst694D_Y](https://www.youtube.com/watch?v=5HLst694D_Y) | 
|more git support|[https://www.youtube.com/watch?v=I9MttnPfrDw](https://www.youtube.com/watch?v=I9MttnPfrDw) | 

<iframe width="853" height="480" src="https://www.youtube.com/embed/videoseries?list=PLj2HyUAn9lEnV4dfyda0ERy-9_jTsCNkc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



