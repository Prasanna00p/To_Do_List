# Ex03 To-Do List using JavaScript
## Date:10-03-2026

## AIM
To create a To-do Application with all features using JavaScript.

## ALGORITHM
### STEP 1
Build the HTML structure (index.html).

### STEP 2
Style the App (style.css).

### STEP 3
Plan the features the To-Do App should have.

### STEP 4
Create a To-do application using Javascript.

### STEP 5
Add functionalities.

### STEP 6
Test the App.

### STEP 7
Open the HTML file in a browser to check layout and functionality.

### STEP 8
Fix styling issues and refine content placement.

### STEP 9
Deploy the website.

### STEP 10
Upload to GitHub Pages for free hosting.

## PROGRAM
```
index.html
<!DOCTYPE html>
<html>
<head>
<title>To Do List</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<h2>My To Do List</h2>

<input type="text" id="taskInput" placeholder="Enter task">
<button onclick="addTask()">Add</button>

<ul id="taskList"></ul>

<script src="script.js"></script>

</body>
</html>
```
```
style.css
body{
font-family: Arial;
text-align: center;
margin-top: 100px;
}

input{
padding: 8px;
}

button{
padding: 8px;
background-color: green;
color: white;
border: none;
}

li{
margin-top: 10px;
}
```
```
script.js
function addTask(){

var task = document.getElementById("taskInput").value;

var li = document.createElement("li");

li.innerText = task;

document.getElementById("taskList").appendChild(li);

document.getElementById("taskInput").value = "";

}
```

## OUTPUT
<img width="1360" height="680" alt="image" src="https://github.com/user-attachments/assets/07e2a1b2-9d79-4242-baf8-ba68d31e7dc4" />


## RESULT
The program for creating To-do list using JavaScript is executed successfully.
