# ExcelAPI
An API for parsing excel files, returning valid JSON

Contributing to the Excel MicroAPI repo (a 5 minute read)

## To get started:

Make sure you are on a desktop or laptop, and signed in to Github

**Step 1**: Click on Fork at the top right corner

**Step 2**: Click on clone or download, copy the url you see after clicking on it

**Step 3**: Head to your local machine and create a folder, (this step is not necessary but to keep your work organized on your local machine, you can create folder called ‘github repo’ on your desktop).

**Step 4**: Open your preferred terminal

Here you an have array of choices, you could use git bash (you have to download it to use it. Download here -> [GitHub](https://git-scm.com/downloads)), powershell or your default window terminal.

(**If you want to use git bash**) **4.1** Open the ‘github repo’ folder, remember you saved it on your desktop.
Right-click anywhere in the folder and choose ‘git bash here’, automatically git bash will open.

(**If you want to use the terminal**)
**4.2** press Window + R on your keyboard

**Step 5**:```git clone pasteTheUrlOfTheLinkYouCopiedInStep2```

It should look like this
```git clone https://github.com/[yourGithubUsername]/ExcelAPI.git```

**Step 6**: To start your work, work the directory that contains the project files.
```cd ExcelAPI```

**Step 7**: ```git remote add upstream https://github.com/AbdulmalikGiwa/ExcelAPI.git```

**Step 8**: ```git pull upstream master```

**Note**: you will be on the Master branch automatically.
You need to move out of the Master branch to another branch to start your work.

To move to another branch

Run: ```git checkout -b <nameOfBranch>```

You can use any name for your branch.
(But if you are an intern in HNG organisation, for consistency and orderliness, use your slack username)

IE: <nameOfBranch> should be replaced with your slack username, use hypen where you will normally use space. This implies if you have space(" ") in your username, use hypen("-")

For example,
```git checkout -b peter-parker ✅```
```git checkout -b peter parker ❌```

Open the project file with your favourite code editor (Sublime, VSCode, Atom, etc etc).
Navigate to the Features folder and create a new file (or folder, depending on what you are working on) with any name.
(But if you are an intern in HNG organisation, for consistency and orderliness, use your slack username)

For example:
```peter.js```
```parker.py```
```peterFolder```
```parkerDir```

Once you are done with your work and you have tested that everything works perfectly.

Run: ```git add .```
Run: ```git commit -m "feat: create runtime display"```

```git push origin <nameOfBranch>```

For example, it would be
git push origin peter-parker - (Notice how it ends with the branch you created earlier).

## Creating Pull requests

PR === Pull request

Go to github.com, locate the repository you forked in step 1

As soon as you get there, you are going to see a green ‘compare and create a pull request’

Click on it, and type your message, click on create pull request. It will be merged as soon as possible

If you have any more questions, check out this resource -> https://www.youtube.com/watch?v=HbSjyU2vf6Y or contact @Abdulmalik6369 @p_yn3, @figures or @Izic_Temi on the HNGi7 slack workspace.

Happy contributing! :+1:
