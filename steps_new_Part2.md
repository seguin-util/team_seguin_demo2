# Mission-2:  With the basic Loopback Concepts out of the way - Lets flesh out a real api that can be consumed.

### Note Ladies: Verify Atom auto opens when you type atom . in your terminal if yes then your good. Else, create sim link with the following ```ln -s /Applications/Atom.app/Contents/Resources/app/atom.sh /usr/local/bin/atom```

### System Flow:
- Install node.js, npm, and loopback.io
- Scaffold a new Loopback Application - follow Mission-1
- Create the data models from the class diagram
- Add relations to the models
- Define the Access Control List(ACL)
- Test the Application
- Push code to github
- Add an Application Manifest for Deployment

### Step-1
- In terminal run
- Change to your Projects folder and run ```git clone https://github.com/seguin-util/team_seguin_demo2.git```
- This will generate a new folder with the cloned project
- This will have ***steps_new2.md*** file with all the instructions on how to complete this exercise.

### Step-2
Before you start Mission-2 create a new class diagram.  Head to draw.io and select a new uml model and re-create the diagram as seen in the image.
---
![](https://github.com/seguin-util/team_seguin_demo2/blob/master/LoopbackUserDiagram.jpg)
---

### Step-3
- Rebuild Mission-1 so that you have a new Scaffolded Loopback Application in your team_seguin_demo2 folder

### Step-4
- With Mission-1 complete its time to start Mission-2.  Before we move to far commit your work to github.

- from terminal:
- ```git status```  
- ```git add .```
- git commit -a -m "your first commit and complete Mission-1"

### Step-5
- terminal run:  ```lb model```
- Start with Student Model and base model as the built user model we built from Mission-1
- select memory database
- base class - LoopbackUserDiagram
- Expose the rest API? yes
- Custom Plural form? hit enter
- common model? common


### Step-7
- Now set Properties
- First Property: Major
- property type: string
- required? yes
- default value leave blank

### Step-8
- Just hit enter to leave the wizard sounds weird but you essentialy create an empty property that is its trigger to exit









### Done! Great Job Jordyn and Elilita your first api server.
