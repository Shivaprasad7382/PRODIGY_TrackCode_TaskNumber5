# PRODIGY_TrackCode_TaskNumber5
weather app
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather App</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <div class="container">
        <div id="weather-container">
            <h1>Weather App</h1>
            <div id="weather-info">
                <!-- Weather information will be displayed here -->
            </div>
            <label for="location">Enter Location:</label>
            <input type="text" id="location" placeholder="City, Country">
            <button id="weatherButton">Get Weather</button>

        </div>
    </div>


    <script src="path/to/your/script.js"></script>

</body>

</html>
//css
body {
    background: linear-gradient(to bottom right, #3498db, #2c3e50);
    color: #fff;
    font-family: 'Arial', sans-serif;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    margin: 0;
}

.container {
    text-align: center;
}

#weather-container {
    background: linear-gradient(to bottom right, #3498db, #2c3e50);
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

button {
    padding: 10px;
    background-color: #fff;
    color: #3498db;
    border: none;
    cursor: pointer;
    border-radius: 5px;
    font-size: 16px;
    margin-top: 10px;
}

button:hover {
    background-color: #3498db;
    color: #fff;
}
//js
document.addEventListener('DOMContentLoaded', function() {
    var button = document.getElementById('weatherButton');

    if (button) {
        button.onclick = function() {
            // Your code here
        };
    } else {
        console.error("Element with id 'weatherButton' not found");
    }
});
