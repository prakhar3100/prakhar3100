<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.1/css/all.min.css">
</head>
<body>
    <main>
        <div class="iphone">
            <div class="notch"></div>
            <div class="status-bar">
                <span class="time">9:41</span>
                <div class="icons">
                    <span>📶</span>
                    <span>📊</span>
                    <span>🔋</span>
                </div>
            </div>

            <button id="theme-toggle"><i class="fa-regular fa-moon"></i></button>
            <div class="app-container">
                <h1>To do List</h1>

                <form id="task-form">
                    <input type="text" id="task-input" placeholder="Add a new task" required>
                    
                    <button type="submit" id="add-btn">Add</button>
                    <button type="button" id="reset-btn">Delete</button>
                    
                </form>
                <ul id="task-list" class="task-list"></ul>
            </div>
        </div>
    </main>


    <script src="https://cdnjs.cloudflare.com/ajax/libs/Sortable/1.15.6/Sortable.min.js"></script>
    <script src="main.js"></script>
</body>
</html>+++++
