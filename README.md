# 🚀 C# Hello World Project

## Lesson Snapshot
Build your first C# program that shows welcome messages on the screen. (Ages 8-18)

## Folder & File Map
```
HelloCoderDojo/
├── .git/
├── HelloCoderDojo.csproj
└── Program.cs
```

## Step-by-Step Build Guide

### 1. Create a GitHub Repository ✅
- **What to do**: Open GitHub Desktop → Click "Create a New Repository" → Name it "HelloCoderDojo" → Choose a location on your computer → Click "Create Repository"
- **Where we're working**: Creating a new special folder that will keep track of all your changes
- **Code snippet**: None
- **Why it matters**: Just like saving your game progress so you never lose it, even if you make a mistake
- **Git command**: `git init HelloCoderDojo`
- [**Documentation Link**](https://docs.github.com/en/desktop/overview/creating-your-first-repository-using-github-desktop)
- **📸 SCREENSHOT**: 
![image](https://github.com/user-attachments/assets/521a507d-04ee-46b5-a752-bcbf01fb1305)
![image](https://github.com/user-attachments/assets/b69c9885-9f42-4585-88a4-8700bf5c7f48)


### 2. Open Repository Folder ✅
- **What to do**: Find and open the folder you just created for your repository
- **Where we're working**: Looking inside your new project home
- **Code snippet**: None
- **Why it matters**: We need to see where our code will live
- **Git command**: `cd HelloCoderDojo`
- **📸 SCREENSHOT**: ![image](https://github.com/user-attachments/assets/b2d886ea-364b-42c8-b6da-d20afbc909d1)

### 3. Launch JetBrains Rider ✅
- **What to do**: Find Rider in your Start Menu/Applications folder and open it
- **Where we're working**: Starting up our coding tool
- **Code snippet**: None
- **Why it matters**: We need our coding workshop to start building
- **Git command**: None
- **📸 SCREENSHOT**:
![image](https://github.com/user-attachments/assets/b1336430-3f36-477c-b5d8-b718a0127b49)

### 4. Create New Project ✅
- **What to do**: Click "New Solution" on the welcome screen
- **Where we're working**: Setting up our coding project
- **Code snippet**: None
- **Why it matters**: This is like starting a new LEGO set with instructions
- **Git command**: None
- **📸 SCREENSHOT**: ![image](https://github.com/user-attachments/assets/78ab7e24-c5ed-4a94-ad60-01ce7a46d0b1)


### 5. Set Up Console App ✅
- **What to do**: Select "Console Application" → Name it "HelloCoderDojo" → Choose your repository folder as location → Select .NET 8.0 → Click Create
- **Where we're working**: Creating the blueprint for your program
- **Code snippet**: None
- **Why it matters**: Tells the computer what kind of program we're making
- **Git command**: None
- **📸 SCREENSHOT**: ![image](https://github.com/user-attachments/assets/3eb112a6-c162-49cd-bbcd-4b1f11d09d56)

### 6. Create a .gitignore File ✅
- **What to do**: In your project folder, create a new file named ".gitignore"
- **Where we're working**: Making a special list that tells Git which files to ignore
- **Code snippet**:
```
# Build results
[Dd]ebug/
[Dd]ebugPublic/
[Rr]elease/
[Rr]eleases/
x64/
x86/
[Bb]in/
[Oo]bj/
[Ll]og/
[Ll]ogs/

# Visual Studio / Rider files
.vs/
.idea/
*.suo
*.user
*.userosscache
*.sln.docstates
*.userprefs

# .NET Core
project.lock.json
project.fragment.lock.json
artifacts/

# NuGet Packages
*.nupkg
*.snupkg
**/[Pp]ackages/*
!**/[Pp]ackages/build/

# MSTest test Results
[Tt]est[Rr]esult*/
[Bb]uild[Ll]og.*

# Files built by Visual Studio
*_i.c
*_p.c
*_h.h
*.ilk
*.meta
*.obj
*.pch
*.pdb
*.ipdb
*.pgc
*.pgd
*.rsp
*.sbr
*.tlb
*.tli
*.tlh
*.tmp
```
- **Why it matters**: Keeps your project clean by not tracking files that your computer creates automatically
- **Git command**: None yet
- **📸 SCREENSHOT**: ![image](https://github.com/user-attachments/assets/6805e630-177c-4feb-9f16-f9dd736b363f)
![image](https://github.com/user-attachments/assets/9ef9c78b-4c63-4ff5-8c32-b94e193ac923)

### 7. First Commit ✅
- **What to do**: Go back to GitHub Desktop → Review changes → Enter "Initial project setup" as commit message → Click "Commit to main"
- **Where we're working**: Saving your project's starting point
- **Code snippet**: None
- **Why it matters**: Like taking a snapshot of your LEGO creation so far
- **Git command**: `git add . && git commit -m "Initial project setup"`
- **📸 SCREENSHOT**: ![image](https://github.com/user-attachments/assets/36fd29e6-1d84-460f-8b55-9495147e7efb)


### 8. Explore Your Project ✅
- **What to do**: In Rider, look at Solution Explorer (usually on the left side)
- **Where we're working**: Looking at all the pieces of your project
- **Code snippet**: None
- **Why it matters**: Finding all the parts we need to build with
- **Git command**: None
- **📸 SCREENSHOT**: ![image](https://github.com/user-attachments/assets/f75ecc15-7c89-4202-a72c-98b0319d9b54)


### 9. Find Program.cs ✅
- **What to do**: Double-click on Program.cs in Solution Explorer
- **Where we're working**: Opening the main file where we'll write our code
- **Code snippet**: None
- **Why it matters**: This is your blank canvas for writing instructions
- **Git command**: None
- **📸 SCREENSHOT**: ![image](https://github.com/user-attachments/assets/9e8e4cf8-c277-4d2c-b136-dd107527288a)


### 10. Write Welcome Messages ✅
- **What to do**: Delete any existing code and type these three lines
- **Where we're working**: Writing in the Program.cs file
- **Code snippet**:
```csharp
Console.WriteLine("Hello, Philly CoderDojo!");
Console.WriteLine("Welcome to C# programming!");
Console.WriteLine("Today is Saturday, June 14, 2025");
```
- **Why it matters**: Telling the computer what words to show on screen
- **Git command**: None yet
- **📸 SCREENSHOT**: ![image](https://github.com/user-attachments/assets/8dc4d9da-6f6e-4e7b-a8a2-7f2750b28ab4)


### 11. Run Your Program ▶️
- **What to do**: Click the green ▶️ button at the top or press Ctrl+F5
- **Where we're working**: Testing your program to see if it works
- **Code snippet**: None
- **Why it matters**: See your program come to life!
- **Git command**: None
- **📸 SCREENSHOT**: ![image](https://github.com/user-attachments/assets/c414e792-02c5-4d18-a927-6fe01143221d)

### 12. Commit Your Changes ✅
- **What to do**: Go to GitHub Desktop → Review changes → Enter "Add welcome messages" as commit message → Click "Commit to main"
- **Where we're working**: Saving your progress in the magical notebook
- **Code snippet**: None
- **Why it matters**: Taking another snapshot of your work
- **Git command**: `git add Program.cs && git commit -m "Add welcome messages"`
- **📸 SCREENSHOT**: ![image](https://github.com/user-attachments/assets/4f27cbb5-7047-4e1b-b2fa-be16bb1dad88)
![image](https://github.com/user-attachments/assets/147b6d4d-f4d6-4671-9c5d-5087f347003d)

### 13. Make It Personal ✅
- **What to do**: Change the messages to include your information
- **Where we're working**: Changing the words in Program.cs
- **Code snippet**:
```csharp
Console.WriteLine("Hello, my name is [YOUR NAME]");
Console.WriteLine("I am [AGE] years old");
Console.WriteLine("I want to learn programming because [REASON]");
```
- **Why it matters**: Making the computer say things about YOU
- **Git command**: None yet
- **📸 SCREENSHOT**: ![image](https://github.com/user-attachments/assets/ac99a01d-7af1-4b25-8542-a2bf62a8c199)


### 14. Run Again ▶️
- **What to do**: Click the green ▶️ button again to see your changes
- **Where we're working**: Testing your personalized program
- **Code snippet**: None
- **Why it matters**: Making sure your changes worked correctly
- **Git command**: None
- **📸 SCREENSHOT**: ![image](https://github.com/user-attachments/assets/c3f2ba65-d43b-4163-99d4-a71dd61cfe11)


### 15. Commit Personal Changes ✅
- **What to do**: Go to GitHub Desktop → Review changes → Enter "Add personal information" as commit message → Click "Commit to main"
- **Where we're working**: Saving your personalized version
- **Code snippet**: None
- **Why it matters**: Taking a snapshot of your customized program
- **Git command**: `git add Program.cs && git commit -m "Add personal information"`
- **📸 SCREENSHOT**: ![image](https://github.com/user-attachments/assets/6395321e-6aae-4085-875e-d10e6f6e7ab8)


### 16. Push to GitHub ✅
- **What to do**: In GitHub Desktop, click "Push origin" to upload all your commits
- **Where we're working**: Sending your project to the internet cloud
- **Code snippet**: None
- **Why it matters**: Backing up your code so it's safe forever
- **Git command**: `git push origin main`
- **📸 SCREENSHOT**: *Add screenshot of GitHub Desktop after pushing*

## Run & Test ▶️
- Click the green ▶️ button in Rider or press Ctrl+F5
- You should see your messages appear in the console window
- **Common Error**: If you see red underlines, check for missing semicolons (;) at the end of each line
- **📸 SCREENSHOT**: *Add screenshot of running program or common error*

## Bonus Challenge 🔥
Make your program ask for the user's name and say hello to them!

**Hint**:
```csharp
Console.Write("What is your name? ");
string name = Console.ReadLine();
Console.WriteLine($"Hello, {name}!");
```
- **📸 SCREENSHOT**: *Add screenshot of bonus challenge code and output*
- **Git command**: `git add Program.cs && git commit -m "Add interactive name prompt"`
