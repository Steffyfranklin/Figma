# Ex09 Event Registration Web Application
## Date:16-05-25

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sports Day Events</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background-color: #f0f0f0;
    }
    .screen {
      display: none;
      padding: 20px;
      height: 100vh;
      box-sizing: border-box;
    }
    .active {
      display: block;
    }
    .btn {
      display: block;
      width: 80%;
      margin: 10px auto;
      padding: 15px;
      background-color: #5eb6f0;
      color: white;
      font-size: 18px;
      text-align: center;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-weight: bold;
    }
    h2, h3 {
      text-align: center;
    }
    .event-list, .form-group {
      margin: 10px 0;
      text-align: center;
    }
    input {
      padding: 10px;
      width: 90%;
      margin: 5px auto;
      display: block;
      border-radius: 6px;
      border: 1px solid #ccc;
    }
    .thank-you {
      text-align: center;
      font-size: 24px;
      font-weight: bold;
      margin-top: 100px;
    }
  </style>
</head>
<body>

<!-- Screen 1 -->
<div id="screen1" class="screen active">
  <h2>Saveetha Engineering College</h2>
  <h3>Sports Day Events</h3>
  <button class="btn" onclick="goToScreen(2)">Login</button>
  <button class="btn" onclick="goToScreen(2)">Register</button>
</div>

<!-- Screen 2 -->
<div id="screen2" class="screen">
  <h2>Sports Day Events</h2>
  <div class="event-list">
    <p>⭐ Cricket</p>
    <p>⭐ Badminton</p>
    <p>⭐ Volley Ball</p>
    <p>⭐ 100 Mts</p>
    <p>⭐ 200 Mts</p>
    <p>⭐ 400 Mts</p>
    <p>⭐ 4x100 Relay</p>
    <p>⭐ Marathon</p>
  </div>
  <button class="btn" onclick="goToScreen(3)">Register for Event</button>
</div>

<!-- Screen 3 -->
<div id="screen3" class="screen">
  <h2>Event Registration Form</h2>
  <div class="form-group">
    <input type="text" placeholder="Full Name">
    <input type="text" placeholder="Gender">
    <input type="number" placeholder="Age">
    <input type="text" placeholder="Register Number">
    <input type="text" placeholder="Department">
    <input type="text" placeholder="Mobile Number">
    <input type="email" placeholder="Email ID">
    <input type="text" placeholder="Events to Register">
  </div>
  <button class="btn" onclick="goToScreen(4)">Register</button>
</div>

<!-- Screen 4 -->
<div id="screen4" class="screen">
  <div class="thank-you">THANK YOU</div>
</div>

<script>
  function goToScreen(n) {
    document.querySelectorAll('.screen').forEach(screen => screen.classList.remove('active'));
    document.getElementById('screen' + n).classList.add('active');
  }
</script>

</body>
</html>

```


## OUTPUT:
![Screenshot 2025-05-16 004506](https://github.com/user-attachments/assets/ea501040-c8d5-4dad-b1dd-d125e22c03e1)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
