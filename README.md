# Hello Kaggle!:wave:

I summarized the definitions of `Kaggle` and basic usage after reading `Kaggle's Official Document` and `Kaggle Guide`
<br>

I hope it will help those who are just introduced to `Kaggle` like me.
<br>

If there is anything that needs to be corrected, please leave it in `Issue`.
<br>

FYI, the `Hello Kaggle`' document rarely deals with `Python programming` or `machine learning theory`<br>
and focuses on `Kaggle usage`.
<br>

For those of you who are looking for `programming`, `data science`, and `machine learning materials`, I'll leave you with some links that I've been helped with.<br>

- [DATA SCIENCE ROADMAP 2020](https://medium.com/@ArtisOne/data-science-roadmap-2020-b256fb948404)
- [data engineer roadmap by datastacktv](https://github.com/datastacktv/data-engineer-roadmap)
- [My Data Science Online Learning Journey on Croursera](https://www.kdnuggets.com/2020/11/data-science-online-learning-journey-coursera.html)
<br>

## Table of contents

1. [What is Kaggle?](#what-is-kaggle)
   - [Kaggler? Kaggling?](#kaggler-kaggling)
   - [Kaggle Service and Features](#kaggle-service-and-features)
   - [Required Kaggling Knowledge](#required-kaggling-knowledge)
   - [Prepare before becoming Kaggler](#prepare-before-becoming-kaggler)
<br>

2. [How is Kaggle used?](#how-is-kaggle-used)
   - [Infrastructure for data analytics](#infrastructure-for-data-analytics)
   - [Notebook](#notebook)
   - [Dataset](#dataset)
   - [Company Training](#company-training)
   - [Discussion](#discussion)
<br>

3. [Kaggle Competition?](#kaggle-competition)
   - [Featured, the most common Competition](#featured-the-most-common-competition)
   - [Research](#research)
   - [Getting Started for New Kaggler](#getting-started-for-new-kaggler)
   - [Playground for data scientists and engineers](#playground-for-data-scientists-and-engineers)
   - [Recruitment for job opportunities](#recruitment-for-job-opportunities)
   - [Annual Competition held regularly](#annual-competition-held-regularly)
   - [Analytics to effectively explain the results](#analytics-to-effectively-explain-the-results)
<br>

4. [Getting Started with Kaggle](#getting-started-with-kaggle)
   - [Sign Up](#sign-up)
   - [Take a look at Kaggle Courses](#take-a-look-at-kaggle-courses)
   - [Kaggle Tiers](#kaggle-tiers)
   - [Medal](#medal)
   - [Being Contributor](#being-contributor)
   - [Kaggle Rankings](#wait)
<br>

5. [Getting to know Notebook](#getting-to-know-notebook)
   - [Introduction to Notebook](#please-re-read-here-for-a-brief-introduction-to-your-notebook)
   - [What can you do with your Notebook?](#what-can-you-do-with-your-notebook)
   - [Create and use Notebook](#create-and-use-notebook)
   - [Various settings for Notesbook](#various-settings-for-notebook)
   - [How to import data from Notebook](#how-to-import-data-from-notebook)
   - [Use external packages in Notebook](#use-external-packages-in-notebook)
   - [Use Source Code from Dataset  in Notebook](#use-source-code-from-dataset--in-notebook)
<br>

6. [Competitions and Notebooks](#competitions-and-notebooks)
   - [What else can the Notebook be used for besides data analysis Competition?](#what-else-can-the-notebook-be-used-for-besides-data-analysis-competition)
   - [How to handle Data Files to use in the Competition Notebook?](#how-to-handle-data-file-to-use-in-competition-notebook)
<br>

7. [Competitions Progress Flow](#competitions-progress-flow)
   - [Baseline implementing the general purpose algorithm](#baseline-implementing-the-general-purpose-algorithm)
   - [Data analysis notebook](#data-analysis-notebook)
   - [Fork Notebook](#fork-notebook)
   - [Merge, Blending, Stacking, Ensemble Notebook](#merge-blending-stacking-ensemble-notebook)
   - [Conclusion of Competitions Progress Flow](#conclusion-of-competitions-progress-flow)
<br>

8. [Rule of Competitions](#rule-of-competitions)
   - [What rules should I check?](#what-rules-should-i-check)
<br>

9. [Flow of Technology in Kaggle](#flow-of-technology-in-kaggle)
   - [Exploring in Closed Competition](#exploring-in-closed-competition)
   - [Winner Solutions at a Glance](#winner-solutions-at-a-glance)
<br>

10. [Kaggle Dataset and API](#kaggle-dataset-and-api)
    - [Use Public Dataset](#use-public-dataset)
    - [Use it as a Data Repository](#use-it-as-a-data-repository)
    - [Kaggle API](#kaggle-api)
    - [Install Kaggle API](#install-kaggle-api)
    - [Use Kaggle API](#use-kaggle-api)
<br>

11. [Finished!](#finished)
<br>

***

<br>

## What is Kaggle?

- __`Kaggle`__ is the platform that hosts the Data Analysis Competition.
- It is common for competitions to be hosted by providing data that needs to be analyzed for the company's `research challenges, key services`.<br>
  ![Untitled Diagram (1)](https://user-images.githubusercontent.com/61633137/103905060-7a35c380-5141-11eb-9cd8-7cd93b64ac96.png)
  <br>

- __`Artificial Intelligence, Machine Learning Boom`__ has continued to increase the number of participants and was acquired by Google's parent company __'Alphabet'__ in 2017.
- Since the Alphabet's acquisition, `Kaggle` has become a critical site for data scientists and engineers, not just a platform.
<br>

### `Kaggler`? `Kaggling`?

- Like Google searches __`Googling`__, >
  Kaggle's users are __`Kaggler`__ or __`Kaggling`__ to participate in the Competition.
<br>

### Kaggle Service and Features

- __`Jobs`__
  - `Jobs Service` was originally provided, but the service ended on December 22, 2020.<br>
    Simply put, it's because the number of users is small.<br>
    For more information, read it here at https://www.kaggle.com/jobs-board-closed.
<br>

- __[`Course`](https://www.kaggle.com/learn/overview)__
  ![image](https://user-images.githubusercontent.com/61633137/103596261-e0072d00-4f40-11eb-9e50-2315e734d267.png)
  - Provides practical and practical lectures on `Python`, `machine learning` and `visualization`, and so on.
  - `Kaggle's course` can be quite useful if you haven't learned it step by step or if you've studied an old course.
  - All lectures are also available in `English`, `free` and a `certificate` of completion.
<br>

__`English`__
  - Data scientists from all over the world gather together and use `English` by default.
  - `Complementation Notice`, `Dataset`, `Discussion` are also in English. <br>
    Below is the photo of `Discussion` and `Site Forum`.
    ![image](https://user-images.githubusercontent.com/61633137/103596175-a59d9000-4f40-11eb-9e8c-90fc24e51347.png)
  - If you look at the profiles of the winners of the Competition, there are a variety of `USA`,`Korea` ,`Russia` ,`China` ,`India`, and so on.
<br>
  
- __Programming Language__
  - Generally use __`Python`__ and __`R`__ a lot.
<br>

### Required Kaggling Knowledge

- | Purpose | Knowledge Required|
  |------|-----|
  |Competition participation|Python, R, data analysis|
  |Competition organizer|Data analysis, English |
  | Discussion with Kaggler|English |
  |Learning through Courses|English |
<br>

### Prepare before becoming Kaggler

- Required: `Internet`, `Python` and `R` , `PC`
- Recommended: `Server with GPU` or `Workstation` and high capacity `HDD` or `SSD`
<br>

***

<br>

## How is Kaggle used?
### `Infrastructure` for data analytics

- Kaggle is `web-based` and provides tools for data analysis. (Notebook)
- Community with a variety of Kagglers to enable competition and cooperation.
<br>

### `Notebook`

- The `programming environment for data analysis` provided by Kaggle.
- A SaaS environment that runs code written on your Notebook on a server.
- It provides a programming environment, so there is no need to build a separate development environment. (No Python installation, Anaconda installation, etc.)
- It is similar to __`Jupyter Notebook`__.
- Provides `4 Core CPU + 16GB RAM` by default. `GPU Server` provides `2Core CPU + GPU + 13GB RAM`.<br>
  __`Provided free of charge`__, and `GPU can be used for 30 hours a week`.
<br>

### `Dataset`
![image](https://user-images.githubusercontent.com/61633137/103597920-b18b5100-4f44-11eb-8f02-df689352a762.png)

- The first thing to do when developing a machine learning-based data analysis program is to prepare __`Dataset`__.
- Dataset is open for academic purposes or created and released by Kaggler.
- If you don't want to share your `Dataset`, you can use the __`Private`__ setting to make it private to the outside world.
- Once Dataset or Notebook is set to __`Public`__, `Apache 2.0 License` is applied, so you must make a careful decision.
<br>

### `Company Training`

- Example: staff training for creating neural network-based machine learning programs
  - 1. Sign up for Kaggle
  - 2. Employees are ready to copy and execute the moderator's Notebook
  - 3. Modifying a Neural Network Model in Notebook
  - 4. Submit the results of the modified model to Competition and check the score
- What if we didn't use the Kaggle?
  - 1. Establishing a development environment on a training computer
  - 2. Distributing examples of machine learning programs (neural network models) 
  - 3. Create a program to evaluate neural network model execution results by converting them into scores
  - 4. Check the evaluation score of the executed model
  - 5. Modifying a Neural Network Model
  - 6. Confirm that the score varies depending on the outcome of the run
<br>

- Kaggle is much easier and less expensive in `building a development environment`, `checking the score`, and `deployment`.
<br>

### `Discussion`

- If you don't know something, you can ask in __`Site Forums`__, and __`Competition`__ of the __`Communities`__.<br>
- `Communities`
  ![image](https://user-images.githubusercontent.com/61633137/103608822-9548dd80-4f5f-11eb-8a55-626a9a0015bb.png)
<br>

- `Site Forums`
  ![image](https://user-images.githubusercontent.com/61633137/103608932-f2dd2a00-4f5f-11eb-8d5d-6f1761e61a1f.png)
<br>

***

<br>

## Kaggle Competition?

Refer to [Competitions Documentation](https://www.kaggle.com/docs/competitions).
<br>

### `Featured`, the most common Competition
![image](https://user-images.githubusercontent.com/61633137/103611173-0dfe6880-4f65-11eb-8141-aac631077c34.png)

- Difficult competitions and generally commercial purposes.
- Most Kagglers participate in the competition, which has been held so far, the prize range is between `$100` and `$1,500,000`.
<br>

## `Research`
![image](https://user-images.githubusercontent.com/61633137/103611678-1d31e600-4f66-11eb-9e41-c972d26d3440.png)
- It mainly deals with research topics and generally does not have prize money or rewards. (All the ongoing Research Competitions have prize money.)
- Instead, you can do research by discussing with less competitive and intellectually curious Kagglers.
<br>

### `Getting Started` for New Kaggler
![image](https://user-images.githubusercontent.com/61633137/103609060-510a0d00-4f60-11eb-98e6-b42e4d2a8336.png)
- The Competitions shown here are for beginners.
- Especially __`Titanic: Machine Learning from Disaster`__, __`House Prices: Advanced Regression Techniques`__, __`Digit Recognizer`__ 
These three competitions are the most recommended and helpful competitions for new machine learners.
<br>

### `Playground` for data scientists and engineers
![image](https://user-images.githubusercontent.com/61633137/103609928-45b7e100-4f62-11eb-992a-14a98dc190b3.png)

- Competition is held mainly with topics that data scientists and engineers might find interesting.
- Playground is not an easy task. It usually covers recent academic/technical issues and public social issues.
- In some cases, the organizers may offer prize money or reward.
<br>

### `Recruitment` for job opportunities
![image](https://user-images.githubusercontent.com/61633137/103611946-bc56dd80-4f66-11eb-8408-576df10506c3.png)

- Companies are hosting and a prize is mostly a `Job Interview` opportunity. Participants can upload a Resume at the end of the Competition.
<br>

### `Annual Competition` held regularly

- Kaggle has several regularly held Competitions. You can find the following information at the current Kaggle.
  ![image](https://user-images.githubusercontent.com/61633137/103610665-04283580-4f64-11eb-9e75-b4f37e84c2bf.png)
<br>

### `Analytics` to effectively explain the results

- This is not explained in Documentation, so I read and wrote the Analytics Competitions that are currently up there.
- Reading the evaluation and submission formats of each Competition, the scoring method of Analytics is shown by submitting a notebook directly and scoring by a person.<br>
  The analyzed data should be described by the organizers' requirements. It looks like a company persuading management through a presentation.
<br>

***

<br>

## Getting Started with Kaggle

### `Sign Up`
- Prior to starting Kaggle, click `Register` button on the upper right to `sign up` first.
<br>

### Take a look at Kaggle `Courses`
- For those of you who do not have enough knowledge about machine learning or data analytics, it is also a good idea to study the areas you need at [`Courses`](https://www.kaggle.com/learn/overview), as described above.
- Each course consists of 2 to 8 classes and offers a variety of hands-on examples.
<br>

Refer to [Kaggle Progression System](https://www.kaggle.com/progression).<br>
Before I explain how to become a `Contributor`, I will explain about `Kaggle Tiers` and `Medal`.

### `Kaggle Tiers`

- There is a `Progression System` in Kaggle, which is simply `Kaggler Tier`.<br>
  This rating is a good indicator of your ability as a data scientist.<br>
  It also intuitively shows how much you've grown. 
- The `Kaggle Tiers` are divided into five levels, and conditions are also given to achieve each.
  - `Novice`<br>
    ![image](https://user-images.githubusercontent.com/61633137/103615154-689bc280-4f6d-11eb-9893-a3336cd8c00b.png)
  <br>
  
  - `Contributor`<br>
    ![image](https://user-images.githubusercontent.com/61633137/103615214-85d09100-4f6d-11eb-8ed2-60415fdcc0ad.png)
  <br>
  
  - `Expert`<br>
    ![image](https://user-images.githubusercontent.com/61633137/103615347-c9c39600-4f6d-11eb-8dc6-6525f5bf35a6.png)
  <br>
  
  - `Master`<br>
    ![image](https://user-images.githubusercontent.com/61633137/103615383-d9db7580-4f6d-11eb-8705-c983f7a70e1e.png)
  <br>
  
  - `Grandmaster`<br>
    ![image](https://user-images.githubusercontent.com/61633137/103615428-e9f35500-4f6d-11eb-839c-c1af9c1494ed.png)
  <br>
  
- Also, as you can see in the pictures above, `Kaggle Tier` is rated differently for `Competitions`, `Datasets`, `Notebooks`, and `Discussion`.
- Click on the upper right account icon and select `My Profile` to go to the profile page.<br>
  Then you can check your profile information and Kaggle activity content and tiers.<br>
<br>

### `Medal`

- `Medal` shows Kaggler's performance in each field. 
  - Kaggler with excellent results in `Competition`
  - Kaggler writes and shares popular `Notebook`
  - Kaggler shares useful `Dataset`
  - Kaggler writes good `Comment`
<br>

- `Contributor` just needs to satisfy conditions. However, from `Expert`, the medals required for the applicable conditions in each discipline must be collected.
- `Competitions` have different medal criteria depending on the number of teams participating.<br>
  ![image](https://user-images.githubusercontent.com/61633137/103616627-1d36e380-4f70-11eb-8d7b-c026270fab11.png)
<br>

- `Datasets`, `Notebooks`, `Discussion`are evaluated by `Vote`. It means, the higher number of `Vote`, the more Kaggler recommended it.<br>
  ![image](https://user-images.githubusercontent.com/61633137/103617270-52900100-4f71-11eb-9760-7e520ffddd4b.png)
- Note that there is only one type of medal awarded for each post in each part.<br>
  For example, if a post on `Dataset` received 20 Votes, the bronze medal will be gone and the silver medal will be given.
<br>

### `Being Contributor`
#### 1. Adding User Profile Information

- Enter your profile, click `Edit Profile`, and enter the following:
  - `Bio (self-introduction)`
  - `Occupation`
  - `Organization`
  - `City`
- In addition, you can set `profile image` and `Social Media` freely.
<br>

#### 2. SMS Verification
- Click `Phone Verification` on the profile screen.
- Check the `Country Code`, `Phone Number` and `Not a Robot` boxes and click `Send Code`.
- Enter the transmitted code and click `Verify` to complete authentication.
<br>

#### 3. Run Script
- You can achieve this by learning at `Course` or by creating your own `Notebook` and executing any code.
- `4. Participate in the Competition` will run a notebook, so you can skip it.
<br>

#### 4. Participate in the Competition
- Select one Competition in the 'Getting Started' category.
- If you go in, you can see the menu below in the middle of the screen.<br>
![image](https://user-images.githubusercontent.com/61633137/103619281-cbdd2300-4f74-11eb-8c00-840110e018ce.png)
- Click on 'Notes' here and take a look at other people's notebooks.
<br>
  
- Pick one notebook and open it in the upper right corner ![image](https://user-images.githubusercontent.com/61633137/103619428-12cb1880-4f75-11eb-9ec9-435c40a13160.png)
  You'll see a button like that. Click this button to copy the notebook.
<br>
  
- Once the copy is complete, click `Save Version` at the upper right corner.
  - `Version Name`: You can enter the name.
  - `Version Type`:  There are two options, `Quick Save` or `Save & Run All (Commit)`.  `Quick Save` is saved, not executed, and `Save & Run All (Commit)` is executed.
<br>

- Click `Save & Run All` here and press the `Save` button.
<br>

- Go back to your profile and click `Notebook` to see the notebook you just copied.<br>
  When you click on this notebook, there is `Output` at the right menu.<br>
  Select Submission.csv, which can be viewed by pressing Output, and click `Submit to Competition` on the right.
<br>

- The screen will now be moved to the `Leaderboard` menu and the submitted files will be automatically scored.<br>
  After scoring, you can check your score and click `Jump to your position on the leaderboard` to see your ranking.
<br>

#### 5. Comment to other people's posts or comments and cast upvote (Make 1 comment & Cast 1 upload)

- In `Discussion`, enter the topic you want and click any article you are interested in (recommended to enter `Getting Started` in `Site Forums`).
- Read carefully and write `comments`. If the text is useful or you like it, press `Vote` as well.
<br>

#### 6. Now you are a `Contributor`!

<br>

#### Wait!
- Let me add one more thing, [Kaggle Rankings](https://www.kaggle.com/rankings).
- Rankings are separated by `Competitions`, `Datasets`, `Notebooks`, and `Discussion`.
- The photo below shows the ranking in the `Competitions`. You can also check how many people are in each tier.
  ![image](https://user-images.githubusercontent.com/61633137/103715609-6c2e5880-5004-11eb-8970-9965f8089d15.png)
<br>

***

<br>

## Getting to know Notebook
### [Please re-read here for a brief introduction to your Notebook!](#notebook)
<br>

### What can you do with your `Notebook`?

- Programming for data analysis is the primary purpose, and programs created to run on the Kaggle server.
- Submit to `Competition` or share `Notebook` with `Kaggler`. Some of the `Notebooks` are shared only for training or skills.
- Use `Code Cell` and `Markdown Cell` to write codes, and descriptions of the code, text, image, etc. <br>
  [How to use Markdown](https://guides.github.com/features/mastering-markdown/)<br>
  [Markdown emoji-cheat-sheet](https://github.com/ikatyang/emoji-cheat-sheet)<br>
  The above two links I referred to when I first used Markdown, and I still sometimes look at emoji whenever I need it.
<br>

### Create and Use `Notebook`
- Go to the `Notebook` menu and look in the upper right corner ![image](https://user-images.githubusercontent.com/61633137/103716652-f081db00-5006-11eb-9368-e3bbe2795bbc.png) There's a button like this. Click it.
<br>

- `Kaggle Notebook` has two types: `Script` and `Notebook`.
  
  - `Script` is a method of writing and executing code in a commonly used code editor.
- `Notebook` is an interactive development environment similar to `Jupyter Notebook`. The characteristic is that you can divide the cells and execute only the code you want.
<br>
  
- Press `File` in the upper left corner and hover your cursor over `Edit Type` to select the type. In addition, you can choose between `Python` and `R` in `Language`.<br>
  ![Screenshot (1)](https://user-images.githubusercontent.com/61633137/103716793-38a0fd80-5007-11eb-854c-f709e9ac911b.png)
<br>

- You can change the name by clicking on the top left column that looks like the picture below.<br>
  ![image](https://user-images.githubusercontent.com/61633137/103717015-c0870780-5007-11eb-9fb8-13c501956cb2.png)
<br>

- The first time you create a `Notebook`, you will see the following code:
  ```python
  # This Python 3 environment comes with many helpful analytics libraries installed
  # It is defined by the kaggle/python Docker image: https://github.com/kaggle/docker-python
  # For example, here's several helpful packages to load

  import numpy as np # linear algebra
  import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)

  # Input data files are available in the read-only "../input/" directory
  # For example, running this (by clicking run or pressing Shift+Enter) will list all files under the input directory

  import os
  for dirname, _, filenames in os.walk('/kaggle/input'):
      for filename in filenames:
          print(os.path.join(dirname, filename))

  # You can write up to 20GB to the current directory (/kaggle/working/) that gets preserved as output when you create a version using "Save & Run All" 
  # You can also write temporary files to /kaggle/temp/, but they won't be saved outside of the current session
  ```
  The above code specifies the directory `/kaggle/input` to import files after loading `Numpy` and `Pandas` libraries from `Python`.
<br>

- I will print `Hello Kaggle!` on `Notebook`. Place the cursor in any code cell and press the `+ Code` button.
- Then complete the following:<br>
  ![image](https://user-images.githubusercontent.com/61633137/103717568-2c1da480-5009-11eb-94d3-486db9f4b4eb.png)
<br>

- At the top left ![image](https://user-images.githubusercontent.com/61633137/103718200-89195a80-5009-11eb-83a9-efa581ca645a.png) press this play button or <br>
  Enter `Ctrl + Enter` or `Shift + Enter` to execute the code. The output will be like this<br>
  ![image](https://user-images.githubusercontent.com/61633137/103717489-f4166180-5008-11eb-88b8-85936bb31044.png)
<br>

- These are the functions of the buttons that can be seen in the cell.

  - ![image](https://user-images.githubusercontent.com/61633137/103721394-e369e980-5010-11eb-8df6-a5f77b67caf3.png): Raise the cell position one space forward.<br>
  - ![image](https://user-images.githubusercontent.com/61633137/103721428-f7155000-5010-11eb-86f7-3a0e8ccff5af.png) : Lower the cell position one space down.<br>
  - ![image](https://user-images.githubusercontent.com/61633137/103721456-085e5c80-5011-11eb-9768-24161e8b6f4e.png) : Deletes the corresponding cell.<br>
  - ![image](https://user-images.githubusercontent.com/61633137/103721476-17450f00-5011-11eb-92ba-84e80c437c8d.png)/![image](https://user-images.githubusercontent.com/61633137/103721509-2deb6600-5011-11eb-88ed-979cd05bbb7b.png) : Hides or indicates that cell.<br>
	- ![image](https://user-images.githubusercontent.com/61633137/103721551-48254400-5011-11eb-98ef-66aaa3e6a3c8.png) : provides the following additional features:<br>
  ![image](https://user-images.githubusercontent.com/61633137/103721556-49ef0780-5011-11eb-8abb-45061ffa7de0.png)
  <br>

### Various settings for `Notebook` 
- Set `Public` & `Private`
  - `Notebook` can be released for sharing with other `Kaggler`. But if you don't want to share, or when you work as a team, you can make settings such as `Private` or `Shared to a specific user`.
  - Press the `Share` button in the upper right corner to open a window for `public` or `private` setting.
  - If `Privacy` is set to `Public`, it will be released with  `Apache 2.0 License`.
  - Use `Collaborators` to add users as collaborators.
<br>

- `Settings`
  - `Language` : You can set the programming language to use `Python` and `R`.
  - `Environment` : The `Docker` image can be set. `Original` sets up the development environment when creating `Notebook` and `Latest Available` uses the latest development environment provided by `Kaggle`.
  - `Accelerator` : Whether to use `GPU` or `TPU` can be set.
  - `GPU/TPU Quota` : Show time and usage of `GPU` and `TPU`
  - `Internet` : You can set whether or not to connect to the Internet.<br>
    You can install certain packages by setting `Internet to On`. Google accounts also allow you to use `BigQuery`, `Cloud Storage`, and `AutoML` services from `GCP` (Google Cloud Platform).
<br>

### How to import `Data` from `Notebook`
- `Kaggle Notebook` is available not only in `Competition Data` but also in a variety of `Dataset` shared.<br>
  In this case, a separate file must be set up for use in `Notebook`.
<br>

- 1. How to create a `new Notebook`
    - Go to the `Dataset` you want to use, ![image](https://user-images.githubusercontent.com/61633137/103732584-086b5600-502b-11eb-9d12-06d4a77914b8.png) and press `New Notebook` to set the file automatically.<br>
<br>

- 2. How to add to an `existing Notebook`
    - To add new data to your `existing Notebook`, first access your `Notebook`.<br>
      Then click the ![image](https://user-images.githubusercontent.com/61633137/103732714-4d8f8800-502b-11eb-8909-4825d3eabec4.png) `+ Add Data` button in the upper right corner.<br>
      Then a window appears where you search for the desired `Dataset` and press `Add` after you choose `Dataset`. 
<br>

- 3. How to upload yourself
    - If you go into the `Data` menu and look in the upper right corner, click on the ![image](https://user-images.githubusercontent.com/61633137/103733211-8b40e080-502c-11eb-8088-69e4bbf28e72.png) `+ New Data` button.<br>
      Then enter a name for `Enter Dataset Title` and click `Select Files to Upload` to upload the file. (Compressed file types such as zip or tar.gz are also possible.)<br>
      Finally, press `Create` to upload `Dataset`. You can import the uploaded `Dataset` using the `i` or `ii` method.
<br>

- 4. How to use output data from another `Notebook`
    - If you follow `ii` method, a window will appear, where you can click on the `Kernel Output Files` tab to use the output data from another `Notebook`
<br>

### Use external packages in `Notebook`
- External packages that `pip` is  avaliable can be installed with `pip install package_name` by clicking `Console` at the bottom of `Notebook`.<br>
   ![image](https://user-images.githubusercontent.com/61633137/103733887-153d7900-502e-11eb-9660-12bf25592e96.png)
<br>

- You can also use `pip` directly in the code cell, as shown in two examples
  ```python
  !pip install package_name
  ```
  ```python
  import os
  os.system('pip install package_name')
  ```
<br>

### Use `Source Code` from Dataset  in `Notebook`
- If you add `example dataset` that has package `hello_kaggle` to `Notebook`, you can add the `../input/example-dataset/hello_kaggle` directory.<br>
  The codes you add are as follows:
  
  ```python
  import sys
  sys.path.append("../input/example-dataset/hello_kaggle")
  ```
<br>

***

<br>

## Competitions and Notebooks
### What else can the `Notebook` be used for besides data analysis `Competition`?

- In general, if the goal is to win a prize, `Notebook` will be shared(Public) after `Competition` is finished.<br>
  However, there is also an environment in which we can discuss with Kaggler even when `Competition` is in progress.
<br>

### How to handle `Data File` to use in `Competition Notebook`?

- When performing `Competition`, the `Data` tab is located in the upper right corner of the `Notebook`. There are three types of files you can click on, each of which is described as follows.
  - `train.csv` : Learning data with correct answer label.
  - `test.csv` : Data for testing without the correct answer label.
  - `Sample_submission.csv` : Examples of data for submission
<br>

- View the `Data` menu in `Competition` to see what data each file contains.<br>For example, lets look at the `Titanic - Machine Learning from Disaster`.<br>
  ![image](https://user-images.githubusercontent.com/61633137/103719565-9e43b880-500c-11eb-95ff-67b5cda88821.png)<br>
  In the picture above, click on the [Data](https://www.kaggle.com/c/titanic/data?select=gender_submission.csv) menu to read `Overview` as follows <br>
  ![image](https://user-images.githubusercontent.com/61633137/103719731-00042280-500d-11eb-8638-b0f543c65171.png)<br>
  If you go down further, you can select each file to view the data and download it as follows <br>
  ![image](https://user-images.githubusercontent.com/61633137/103719767-17431000-500d-11eb-9e20-e36dccdadbb4.png)<br>
  
- Let's use these files to create and submit a csv file for model creation and submission.<br>
  (The same is explained in [4. Participate in the Competition](#4-composition-make-1-composition-or-task-submission).) <br>
  - Click `Save Version` in the upper right corner of the `Notebook` screen. (If the code is not executed, click `Save & Run All (Commit)`.
  - In `Save & Run All (Commit)`, `Commit` is the same meaning as `Git Commit` in `Github`, which I am currently working on.<br>
    Therefore, `Kaggle Notebook` can refer to the version of the source code previously written.
  
- Now return to your profile and click `Notebook` to see the notebook you just saved.<br>
  When you click on this notebook, there is `Output` in the right menu.<br>
  Select `Submission.csv` that you can view by pressing `Output` menu and click `Submit to Competition` on the right.
<br>

- The screen will now be moved to the `Leaderboard` menu and the submitted files will be automatically scored.<br>
  After scoring, you can check your score and click `Jump to your position on the leaderboard` to see your ranking.
<br>

***

<br>

## Competitions Progress Flow

- The type and order that comes out here is the personal opinion of Toshiyuki Sakamoto, author of `Kaggle Guide`.

### `Baseline` implementing the general-purpose algorithm

- First, you start analyzing the data, you get the output data through a general-purpose algorithm. 
- Develop machine learning models in earnest and compare output data and results from general-purpose algorithms. 
- If the comparison results in a worse result than the general-purpose algorithm, you can assume that the model has a problem.
<br>

### `Data Analysis` Notebook

- This refers to `Notebook` that analyzes `Competition data` and shows `visualization`.
- Focus on identifying `correlations`, `rules`, and `structure` between the analyzed data without creating data to submit. We also look for `independent variables` that fit well with `dependent variable`.
- If you have less `Competition experience`, it would be a good start to build knowledge and insight by looking at data analyzed by other `Kagglers`.
<br>

### `Fork Notebook`

- For those who are new to `machine learning` and `Kaggle`, one way is to fork out a `notebook` that is open without data analysis or model development yourself.
- `Fork` means to copy a version of the source code.
- On the top right of the `Notebook` you'd like to fork ![image](https://user-images.githubusercontent.com/61633137/103757146-b25ed880-5053-11eb-9e1f-48b887dc2eba.png) press button to copy.
<br>

### `Merge, Blending, Stacking, Ensemble Notebook`
- `Notebook` with words such as `Merge`, `Blending`, `Stacking`, and `Ensemble`.
- As the name suggests, it means `Notebook` combining several `Notebooks`.
- `Example`: ![image](https://user-images.githubusercontent.com/61633137/103759052-6f523480-5056-11eb-8d15-17e83fdb492d.png)
<br>

### Conclusion of Competitions Progress Flow
![Untitled Diagram](https://user-images.githubusercontent.com/61633137/103904704-f8de3100-5140-11eb-8813-7f1ec3b51448.png)
- When `Competition` is carried out in this order, I think it would be better to study a variety of `Notebooks` to understand the process rather than just looking at the `winner's notebook`.
- Also, `Competition` is literally a competition, so the shared(public) `Notebook` means that they are not serious impact on their score.<br>
  In fact, if you look at the `Notebook of winners`, you can often see that they used the latest technology or used a different solution than the `shared notebook`.
<br>

***

<br>

## Rule of Competitions
- `Competitions in Kaggle` sometimes have specific rules. This is because `Competitions` are usually hosted by a company or organization, and special rules are often created to achieve the results that the company or organization wants. 
<br>

### What `rules` should I check?
- 1. `Rules` : To win the `Competition`, you must first know the `rules of Competition`. Check the `Rules` menu for each Competition.<br>
- 2. `Evaluation` : On the `Evaluation` page of `Overview`, you should look at the `Evaluation function` and see what evaluation method is applied. Usually, statistical-based functions are used.<br>
- 3. `One-person score check limit` : If you can check the score frequently by submitting a result file as you change the data one by one, the competition won't get any meaningful results, so there is usually a limit to the number of results checked.<br>
- 4. `Notebook Only Competition` : Submit results using `Kaggle Notebook` only.<br>
  If only `Kaggle Notebook` is used, `Kaggler` is more likely to share `Notebook`, and all participants can easily find good ideas by viewing `shared Notebook`. <br>Also, all participants have the same computing resources, which can help address inequality between those who use personal workstations and those who do not.  
<br>

***

<br>

## Flow of Technology in Kaggle
### Exploring in `Closed Competition`

- One characteristic of `Kaggle` is that it leaves `discussion` and `notebook` of `Competition that ended a long time ago`.<br>
  So if you look at these, you can see what technologies were applied to where and in what ways.
- Example
  |Competition|Used Technology|Description|
  |------|-----|-----|
  |Mercari Price Suction Cahllenge (2018.2)|TF-IDF Vector + Pre-bonded Neural Network|Learn the frequency of each word with neural networks|
  |Toxic Comment Classification Challenge (2018.3)|FastText, Glove + GRU + LightGBM|A combination of word vector dictionaries learned from time series data|
  |Avito Demand Prediction Challenge (2018.6)| FastText + LSTM + 2D-CNN|Learn data and images of sentences simultaneously with neural networks|
  |Quora Insincere Questions Classification(2019.1)|Glove, para + OOV Token + LSTM + 1D-CNN|Learn vocabularies through OOV token|
  |Jigsaw Unintended Bias in Toxicity Classification(2019.6)|BERT + XLNet + GPT2| BERT model appeared to the Kaggle |
<br>

### Winner Solutions at a Glance

- [Data-Science-Competitions](https://github.com/interviewBubble/Data-Science-Competitions) is a Github repository, presents solutions that `won the Competition` topic by topic (I just checked it out that 11 months ago was the last commit).
- The winning solution is technology-based at the time, so we need to see if we have better technology today.
- Most `Competitions` will continue to release their latest technology-enabled solutions on the `Private Leaderboard` page after the end.
<br>

***

<br>

## Kaggle Dataset and API
### Use `public Dataset`

- When studying common algorithms, it is recommended to test performance with a widely publicized `Dataset`, `UCI Machine Learning Repository` is famous.<br>
  It is also used in many academic papers.
<br>

### Use it as a `Data Repository`

- When using `Github`, you can use `Kaggle` as a convenient place to store `Dataset` and `Notebook` (Free!)
- It also has the advantage of being able to connect `Dataset` directly to `Notebook`.
- There is a capacity limit of up to 20GB per `public Dataset` and up to 20GB total for `all private Dataset`.
<br>

### `Kaggle API`
- `Kaggle API` is an API that can use various functions of `Kaggle` in various development environments.
- Developed as `Python 3` and the usage is input command into the terminal environment.
<br>

### Install `Kaggle API`

- You must install `Python` and `pip` before starting.
- [Python Installation](https://www.python.org/downloads/)
- [pip Installation](https://pip.pypa.io/en/stable/installing/)
<br>

- 1. First, install `Kaggle API` using `pip install kaggle`.
- 2.Then enter your profile, click on the ![image](https://user-images.githubusercontent.com/61633137/103771883-ea721580-506b-11eb-888d-bff7ae4b8b07.png) button that looks like this, and press `Accounts`.
- 3.![image](https://user-images.githubusercontent.com/61633137/103771829-d4645500-506b-11eb-93d8-14c99f8e4255.png)<br>
    Click `Create New API Token` here to download the `json` file.
- 4. Save downloaded `json` file to the user's home directory as `.kaggle/kaggle.json`. now you are ready to use `Kaggle API`.
<br>

### Use `Kaggle API`

- You can open a terminal on your PC and run commands.
- Run the `kaggle competitions list` command to see which `Competitions` are currently in progress.<br>
  ![Screenshot from 2021-01-06 22-15-25](https://user-images.githubusercontent.com/61633137/103772382-c82cc780-506c-11eb-8230-e0ad0f23f02d.png)
- To view and download `Competition files`, check the file with `kaggle competitions files COMPETITION_NAME` and `kaggle competitions download COMPETITION_NAME` to download the files.
- To learn more about the `Kaggle API`, please visit [Kaggle Public API Documentation](https://www.kaggle.com/docs/api).
<br>

### Finished!
First of all, thank you for reading __`Hello Kaggle!`__<br>
I studied __`Python`__ for the first time in April 2020 and was unable to concentrate fully on my studies as I've started military service in July of the same year.<br>
That's why I couldn't study data science in depth, and I still need more knowledge to understand it.<br>
Now finally I'm stepping into __`machine learning`__ and __`Kaggle`__.<br>
At this moment to write __`Hello Kaggle!`__, I've improved my understanding of __`Kaggle`__ and I'm going to start with __`Getting Started Competition`__.<br>Also eager to keep up with the latest technology by looking at other outstanding __`Kaggler's Notebook`__.<br>Hopefully, everyone who reads __`Hello Kaggle!`__ will get the best time in 2021. Let's Keep Going!
<br>
