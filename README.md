# Practical3
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Practical-3</title>
</head>
<link rel="stylesheet" href="STYLE1.css">
<body>
    <div class="Container">
        <div class="card">
            <h1 class="header">ToDo List</h1>
            <label class="input-label">What do you want to get done today?</label>
        </div>
        <div class="box">
            <input type="text" name="" id="input-box" placeholder="Type List" onkeypress="press(event)">
            <button onclick="addTask(event)">Add</button>
        </div>
        <div class="Task-container">
            <ul id="task-list">
                
            </ul>
        </div>
    </div>
    <script src="myscript.js"></script>
</body>

</html>
