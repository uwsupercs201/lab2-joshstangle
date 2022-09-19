# CSCI 201 FALL 2022
Week 3 Lab Starter Code:

None!

Welcome to GitHub and your second CS201 Lab!

### Learning Goals:
- use numeric datatypes
- use `Math` Class to perform complex computations
- use variable names appropriately (if you don't you're gonna have a bad time!)


### Creating an IntelliJ Project [same as last time]

First we need to create an IntelliJ project in a well-named, easy to locate folder.

1) If you're using a Lab Workstation, navigate to the H:\ Drive and create a folder called `cs201`.  If you're using your own device, place a folder called `cs201` wherever you can reliably find it. I recommend `Documents\classes`
2) Open IntelliJ. On Lab Workstations, this can be done by navigating to the Start Menu and finding IntelliJ in the JetBrain folder. If you are using a Windows machine of your own, the process is the same. If you are using a Mac, you'll need to find IntelliJ in the Apps location.
3) IntelliJ will open a dialog box the first time you open it. Select "Create a New Project" and click Next. 
4) You can select the Project SDK, you should choose JDK Version 16.0.2.
5) Ensure both Groovy and Kotlin/JVM are NOT selected.
6) Ensure "Create Project from Template" is NOT selected.
7) Set the Project Name to `Lab2`. Set the Project location to `H:\cs201\Lab2` or `[Location on your device]\cs201\Lab2` and click Finish. It will give you a "Directory does not exist" Dialogue. Click Ok to create directory.

## Lab 2

### Creating a .java file

Program are written in .java files and compiled into .class files.
1) Click the arrow next to the Lab1 folder in the Project Viewer Pane. This will expand the project folder.
2) Write click on the `src` folder and navigate to `New`. Click `Java Class`. When prompted for a name, name the class `Lab2`.

The Text Editor Pane will now contain a page with the following:

```
public class Lab2{
}
```

Inside of that class is where you will place the `main` method of your program. That program, when compiled, should print the following:

The program should do the following:
- Prompt the user for 6 numbers (decimals are acceptable). The first three entries will correspond to the coordinates of 3-dimensional point $P_1=(x_1,y_1,z_1)$ and the second 3 entries will correspond the the coordinates of a second 3-dimensional point $P_2=(x_2,y_2,z_2)$. 
   * You can prompt for each individual coordinate or all 6 at once, but I think one of these options is better practice.
- The program should could compute the distance between these two points. The formula for distance between $P_1=(x_1,y_1,z_1)$ and $P_2=(x_2,y_2,z_2)$ in 3d is $d=\sqrt{(x_1-x_2)^2+(y_1-y_2)^2+(z_1-z_2)^2}$. 
- The program should print the distance with a brief explanation. Here is an example:

```
Enter the x-coordinate of point 1: 1.2 
Enter the y-coordinate of point 1: 2.6 
Enter the z-coordinate of point 1: -3.4 
Enter the x-coordinate of point 2: 0.9 
Enter the y-coordinate of point 2: 1.1 
Enter the z-coordinate of point 2: 8.4 
The distance between point 1 and point 2 is: 11.898739429031968 
```

### Bonus: Also print the "integer part" of the distance and "fractional part" of the distance:

```
The integer part of the distance between point 1 and 2 is: 11
The fractional part of the distance between point 1 and 2 is: 0.8987394290319681  
```

You can compile and run your program in IntelliJ by selecting `Run > Run` from the header, pressing the green "Play Button" next to the `main` method, or pressing `Shift+F10`.





### Submitting the project

When you're done, you can upload your files to this Repo and commit the changes. 

1) Click `Add files ` at the top right of the Repo page.

There are two options:

A) Click "Add Files" to create new Java files in the repo manually. Create new files with name `Lab2.java` You can re-type or copy paste your code into that file.

B) Click "Upload Files" to just upload the .java files you already created. Navigate to the `src` folder on your computer and upload `Lab2.java.

2) Once you've created the file you want, or uploaded them, navigate to the bottom of the Page and hit "Commit changes". Ensure "Commit directly to the `main` branch." is selected. You'll need to "Commit changes" once for each file you "Create" in GitHub, but can upload multiple files before a single Commit. 


