# TABLE OF CONTENTS
1. STUDENT RESOURCES
2. CLASS CALENDAR
3. STUDY GROUP RECORDINGS & NOTEBOOKS
4. COHORT CONTACTS & SCHEDULING
5. COMMON COMMANDS
6. PROJECT RESOURCES & INFO
7. MORE VIDEO PLAYLISTS
___

### 1. STUDENT RESOURCES
  - Flatiron Student Resources Folder [LINK](https://drive.google.com/drive/folders/1E3JBOl0uhLMRKvl9R5vpl6xaxchiJ6JA?usp=sharing)
    - A collection of resources, cheatsheets, and official best-of collection of study group videos.
    - **TWO CRITICAL DOCS IN MAIN FOLDER:**
      1. [Master Python Data Science Cheatsheets PDF](https://drive.google.com/open?id=1PxRAhlaK7ucf0S2F732eJ94ovaPtUSE_).
      2. [Student Resources GSheet of Study Group Videos by Topic](https://drive.google.com/open?id=1CNGDhjcQZDRx2sWByd2v-mgUOjy13Cd_hQYVXPuzEDE)
          <details>
          <summary style="font-weight:light;">Student Resources GSheet Tab Info</summary>
          
            | Student Resources Gsheet Tab | Contents | 
            | --- | --- |
            | Screencasts | Not much on this tab, skip it.|
            | Study Groups V1 / Study Groups V2| A "best of" collection of study groups by all instructors|
            | |Note: v1's sections numbers are a little different than your v2, so read the topic, not the section #|
            |Peer 2 Peer Study Groups| Student-led study groups on misc. topics|
            |Additional Topics | Additional instructor-led videos on topics beyond of Learn lessons|

          </details>

  - **NEW LEARN_ENV REPO/LESSON** [LINK](https://github.com/jirvingphd/dsc-data-science-env#setting-up-a-professional-data-science-environment)
      - To remove current learn-env jump to [here](https://github.com/jirvingphd/dsc-data-science-env#updating-your-virtual-environment)
      - To set learn-env as your default env (so you won't have to activate it each time.) [LINK](https://github.com/jirvingphd/dsc-data-science-env#setting-your-default-environment)
    - **BONUS HACK:** After setting the default environment after running the command that starts with `echo`. Run this command to create a shortcut that allows you to type `jnb` to open jupyter notebook.
      - `echo "alias jnb='jupyter notebook'">>~/.bash_profile`

    - ***NOTE: WINDOWS USERS, THE INSTRUCTIONS HAVE AN ERROR:*** 
        - Where it says to enter the command `echo "conda activate learn-env" >> ~/.bash_profile`,
      change "conda activate learn-env" to whatever your normal command is. For most windows users its actually "source activate learn-env".
        - The corrected command is `echo "source activate learn-env" >> ~/.bash_profile`

___

### 2. CLASS CALENDAR 
- [Learn.co Study Groups Page](https://learn.co/study-groups)



<!--- Calendar iframe goes below --->
<iframe src="https://calendar.google.com/calendar/embed?
src=flatironschool.com_49ma6330af8gkj2pe9d879n7jc%40group.calendar.google.com&ctz=America%2FChicago" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>

### 3. STUDY GROUP RECORDINGS
- [STUDY GROUP YOUTUBE PLAYLIST](https://www.youtube.com/playlist?list=PLFknVelSJiSyE_BQomZ8mFFrCfk1H9hfh)
- [REPO WITH STUDY GROUP NOTEBOOKS](https://github.com/jirvingphd/fsds_100719_cohort_notes)
- [MY PART TIME COHORT'S YOUTUBE PLAYLIST](https://www.youtube.com/playlist?list=PLFknVelSJiSydTybrkhr3dfRAFCyzAfC6)


<!-- 
<iframe width="853" height="480" src="https://www.youtube.com/playlist?list=PLFknVelSJiSyE_BQomZ8mFFrCfk1H9hfh" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->


___

### 4. COHORT CONTACTS
#### Your Cohort Lead:
James M Irving, Ph.D.<br>
james.irving@flatironschool.com<br>
Scheduling Link: https://go.oncehub.com/JamesIrvingOfficeHours
[My LinkedIn](https://www.linkedin.com/in/james-irving-4246b571/)<br>
[My GitHub](https://github.com/jirvingphd)

#### Your Education Coach:
Dara Paoletti<br>
dara.paoletti@flatironschool.com<br>
Scneduling Link: https://darapaoletti.youcanbook.me

#### Student Services
Student Services Email<br>
[studentservices@flatironschool.com](mailto:studentservices@flatironschool.com)

___



<!-- 
# STUDENT RESOURCES

## Flatiron Student Resources Folder
- **[GOOGLE DRIVE LINK](https://drive.google.com/drive/folders/1E3JBOl0uhLMRKvl9R5vpl6xaxchiJ6JA?usp=sharing)**
  - A collection of resources, cheatsheets, and official best-of collection of study group videos.
  - **TWO CRITICAL DOCS IN MAIN FOLDER:**
    1. [Master Python Data Science Cheatsheets PDF](https://drive.google.com/open?id=1PxRAhlaK7ucf0S2F732eJ94ovaPtUSE_).
    2. [Student Resources GSheet of Study Group Videos by Topic](https://drive.google.com/open?id=1CNGDhjcQZDRx2sWByd2v-mgUOjy13Cd_hQYVXPuzEDE)

        <details>
        <summary style="font-weight:light;">Student Resources GSheet Tab Info</summary>

          | Student Resources Gsheet Tab | Contents | 
          | --- | --- |
          | Screencasts | Not much on this tab, skip it.|
          | Study Groups V1 / Study Groups V2| A "best of" collection of study groups by all instructors|
          | |Note: v1's sections numbers are a little different than your v2, so read the topic, not the section #|
          |Peer 2 Peer Study Groups| Student-led study groups on misc. topics|
          |Additional Topics | Additional instructor-led videos on topics beyond of Learn lessons|
        </details> -->

### 5. Common Commands

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




### 6. VIDEO PLAYLISTS

<summary style="font-weight:bold;">Getting Started Videos</summary>

## Getting Started Video Playlist

<iframe width="853" height="480" src="https://www.youtube.com/embed/videoseries?list=PLj2HyUAn9lEmGc4FIasxTQ2S0JAgYttAD" 
frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


| VIDEO | COVERS |
| -- | -- |
|Getting Started 00 |Discusses how to download and install Anaconda for Mac|
|Getting Started 01 |Discusses how to organize your work for the DS program|
|Getting Started 02 |Walks you through setting up your **learn-env** virtual environment|
|Getting Started 03 |Walks you through the learn to github to local workflow that you'll use **every day**



## Extra Resources Playlist

|Topic| url |
|-----|-----|
|git commands|[https://www.youtube.com/watch?v=5HLst694D_Y](https://www.youtube.com/watch?v=5HLst694D_Y) | 
|more git support|[https://www.youtube.com/watch?v=I9MttnPfrDw](https://www.youtube.com/watch?v=I9MttnPfrDw) | 

<iframe width="853" height="480" src="https://www.youtube.com/embed/videoseries?list=PLj2HyUAn9lEnV4dfyda0ERy-9_jTsCNkc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

___
# PROJECT RESOURCES & INFO
## MOD 1

[Rubric](https://drive.google.com/file/d/1trk8eamU3uLpsgdmEjt5x-zKg3kFuOja/view?usp=sharing)

### Items due for Project
  * Project Notebook(s)
  * Slideshow (pdf)
  * Slideshow Video
  * Blog Post (1000 words)
  * README.md 

### To convert your notebook to a markdown README:
Two methods
1)  Command line method:
Launch a terminal in the same folder as your notebook.

```
jupyter nbconvert --to markdown notebook_name.ipynb
mv README.md README_old.md
mv notebook_name.md README.md
```

2) From your project notebook:
  - Select `File` > `Download as` > `Markdown`
    - Notebook + output images will be downloaded a zip file.
  - Extract contents of zip folder to main folder of repo.
  - Rename the original `README.md` to `README_old.md`
  - Rename the notebook.md to `README.md`

<!--- Pair Programming Section 
## Pair Programming Partners
You need a zoom account or you can use slack video

Procedures:
* Person 1 is always host
* Person 1 always fills out form
* Do the section project (unless discussed with partner(s))
* For now: Person 1 drives, other people steer

| Section Number| Person 1 (host) | Person 2 | 
| --------------| ----------------| ---------|
| | | | 
--->


<!--- paste pair programming table above --->

<!--- Resources Section --->

<!-- ## Resources  -->
<!-- [**1 on 1s with Rafael/James - Instructor**](https://go.oncehub.com/FullTimeDataScience100719)

[**1 on 1s with Dara - Education Coach**](https://darapaoletti.youcanbook.me) -->

<!---[**About Me Survey** Please take this on Day 1](https://forms.gle/SJWWi5WJQsGRBitSA)--->


<!-- [**Video Recording Spreadsheet Link**](https://docs.google.com/spreadsheets/d/1CNGDhjcQZDRx2sWByd2v-mgUOjy13Cd_hQYVXPuzEDE/edit#gid=0) -->


<!--- Video Resources --->

<!-- # Video Resources -->
<!---
## Welcome Week Recordings
| Event | recording url |
|-------|---------------|
|Day 1 - Orientation | |
|Day 2 - Meet Your Classmates| |
|Day 3 - Community Talk | |
|Day 4 - Hi From Career Services| |
|Day 5 - Stress Less | |
--->

<!----- Below are all of the Mod Project Rubrics in a table--->
<!-- ## Project Rubrics -->

<!-- - [Mod 1](https://drive.google.com/file/d/1trk8eamU3uLpsgdmEjt5x-zKg3kFuOja/view?usp=sharing) -->
<!-- - [Mod 3](https://drive.google.com/file/d/134VfqsXIpjBvQ01hEjeB2gD7at0Wex7W/view?usp=sharing)
- [Mod 4](https://drive.google.com/file/d/1VJD5UKapqpM0XHK3Sz6-2Gn5Gb65R1xm/view?usp=sharing)
- [Mod 5](https://drive.google.com/file/d/1QKA5Yt6hALy8BXkVbocHCdPkF_TdIwWm/view?usp=sharing)
- [Capstone](https://drive.google.com/file/d/1smaVWyLLoRVg9yeMWAq0dLqQhbVQDFv2/view?usp=sharing) -->

<!-- ## Program Guide
[Click here](https://help.learn.co/online-immersive-bootcamps/what-if-i-cant-keep-up-with-my-cohort)
 -->

<!-- 

# Project Week
- Group A: 

- Group B: 

- Group C:  -->



--------
