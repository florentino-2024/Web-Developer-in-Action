# Web-Developer-in-Action
"This is a To-Do List application developed with HTML, CSS and JavaScript. The goal of the project is to allow users to add, view and delete their tasks in a simple and efficient way. The interface is intuitive and offers a pleasant user experience, with the possibility of managing daily tasks in a practical way."

body {
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    background-color: #f4f4f9;
}

.container {
    text-align: center;
    width: 300px;
    background-color: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h1 {
    color: #333;
}

input[type="text"] {
    width: 80%;
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 16px;
}

button {
    padding: 10px 20px;
    background-color: #4CAF50;
    border: none;
    color: white;
    font-size: 16px;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #45a049;
}

ul {
    list-style-type: none;
    padding: 0;
}

li {
    background-color: #f9f9f9;
    margin: 5px 0;
    padding: 10px;
    border-radius: 5px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

li button {
    background-color: #f44336;
}

li button:hover {
    background-color: #e53935;
}


    
