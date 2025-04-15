# Ex09 Event Registration Web Application
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
HOME PAGE
```
<div style="margin: 0; font-family: Arial, sans-serif; text-align: center; width: 100%; max-width: 400px; margin: 20px auto; background: linear-gradient(to bottom, #e6f7ff, #ffffff); border: 1px solid #ddd; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); padding: 20px; background-image: url(c:/Users/admin/Downloads/istockphoto-166679114-612x612.jpg);">
    <img style="margin-bottom: 10px; width: 250; height:25;" src="c:\Users\admin\Downloads\saveetha_logo.png" alt="Saveetha Logo"><BR>
    <img style="margin-bottom: 20px;" src="event_logo.png" alt="Event Logo" style="width: 100px; height: 200;">
    <div style="font-size: 20px; font-weight: bold; color: #000; margin: 10px 0;">SPORTS DAY EVENT</div>
    <div style="width: 80%; margin: 20px 0; padding: 10px; margin: 10px auto; background-color: #ff3366; color: #fff; border: none; border-radius: 5px; font-size: 16px; cursor: pointer; text-align: center;">LOGIN</div>
    <div style="width: 80%; margin: 20px 0; padding: 10px; margin: 10px auto; background-color: #ff3366; color: #fff; border: none; border-radius: 5px; font-size: 16px; cursor: pointer; text-align: center;">REGISTER</div>
    <div style="font-size: 14px; margin: 20px 0; color: #777; margin: 20px 0;">SUCCESS IS YOURS</div>
</div>
```
EVENT PAGE
```
<div style="margin: 0; font-family: Arial, sans-serif; text-align: center; width: 100%; max-width: 400px; margin: 20px auto; background-image: url(c:/Users/admin/Downloads/istockphoto-166679114-612x612.jpg); border: 1px solid #ddd; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); padding: 20px;">
    <div style="font-size: 20px; font-weight: bold; color: #000; margin: 10px 0;">SPORTS DAY EVENTS</div>
    <div style="text-align: left; font-size: 16px; color: #000; margin: 20px; line-height: 1.8;">1. CRICKET</div>
    <div style="text-align: left; font-size: 16px; color: #000; margin: 20px; line-height: 1.8;">2. FOOTBALL</div>
    <div style="text-align: left; font-size: 16px; color: #000; margin: 20px; line-height: 1.8;">3. VOLLY BALL</div>
    <div style="text-align: left; font-size: 16px; color: #000; margin: 20px; line-height: 1.8;">4. BASKET BALL</div>
    <div style="text-align: left; font-size: 16px; color: #000; margin: 20px; line-height: 1.8;">5. 4 X 100 RELAY</div>
    <div style="text-align: left; font-size: 16px; color: #000; margin: 20px; line-height: 1.8;">6. BADMINTON</div>
    <div style="text-align: left; font-size: 16px; color: #000; margin: 20px; line-height: 1.8;">7. 100 MTS</div>
    <div style="text-align: left; font-size: 16px; color: #000; margin: 20px; line-height: 1.8;">8. 400 MTS</div>
    <div style="text-align: left; font-size: 16px; color: #000; margin: 20px; line-height: 1.8;">9. HOCKEY</div>
    <div style="text-align: left; font-size: 16px; color: #000; margin: 20px; line-height: 1.8;">10. TENNIS</div>
    <img src="sports_image.png" alt="Sports Items" style="width: 150px; height: auto; margin-top: 20px;">
</div>
```
REGISTERATION PAGE
```

<div style="margin: 0; font-family: Arial, sans-serif; text-align: center;  border: 1px solid #ddd; background-image: url(c:/Users/admin/Downloads/istockphoto-166679114-612x612.jpg); border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); padding: 20px;">
    <div style="font-size: 20px; font-weight: bold; color: #000; margin-bottom: 20px;">EVENT REGISTRATION FORM</div>
    <div style="background-color: #fff; border: 1px solid #ccc; border-radius: 5px; padding: 10px; text-align: left; color: #999; margin-bottom: 15px;">Full Name</div>
    <div style="background-color: #fff; border: 1px solid #ccc; border-radius: 5px; padding: 10px; text-align: left; color: #999; margin-bottom: 15px;">Age</div>
    <div style="background-color: #fff; border: 1px solid #ccc; border-radius: 5px; padding: 10px; text-align: left; color: #999; margin-bottom: 15px;">Gender</div>
    <div style="background-color: #fff; border: 1px solid #ccc; border-radius: 5px; padding: 10px; text-align: left; color: #999; margin-bottom: 15px;">Register Number</div>
    <div style="background-color: #fff; border: 1px solid #ccc; border-radius: 5px; padding: 10px; text-align: left; color: #999; margin-bottom: 15px;">Department</div>
    <div style="background-color: #fff; border: 1px solid #ccc; border-radius: 5px; padding: 10px; text-align: left; color: #999; margin-bottom: 15px;">Phone Number</div>
    <div style="background-color: #fff; border: 1px solid #ccc; border-radius: 5px; padding: 10px; text-align: left; color: #999; margin-bottom: 15px;">Email ID</div>
    <div style="background-color: #fff; border: 1px solid #ccc; border-radius: 5px; padding: 10px; text-align: left; color: #999; margin-bottom: 15px;">Event to Register</div>
    <div style="margin-top: 20px; background-color: #ff3366; color: #fff; padding: 10px; border-radius: 5px; font-size: 16px; cursor: pointer; text-align: center;">REGISTER</div>
</div>
```
CONTACT US PAGE
```
<div style="width: 390px; margin: 20px auto; font-family: Arial, sans-serif; text-align: center; border: 1px solid #ddd; border-radius: 20px; overflow: hidden; background-image: url(c:/Users/admin/Downloads/istockphoto-166679114-612x612.jpg); box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);">
    <img src="c:\Users\admin\Downloads\saveetha_logo.png" alt="Header Logo" style="width: 100%; border-bottom: 1px solid #ddd;">
    <div style="font-size: 32px; color: #000; font-weight: bold; margin-bottom: 40px;  box-sizing: border-box; margin-top: 150px;">THANK YOU</div>
    <div style="font-size: 18px; color: #444; margin-bottom: 40px;">We are all eagerly waiting<br> for your participation <br> the sports event</div>
    <div style="font-size: 20px; font-weight: bold; color: #00c700; margin-top: 200px;">Contact Us</div>
    <div style="font-size: 16px; color: #555; margin-bottom: 40px;">Email<br>SaveethaEngineeringCollege@gmail.com</div>
    <div style="font-size: 16px; color: #555; ">Phone<br>8249763553<br>9878964646</div>
</div>
```
# OUTPUT:
![Screenshot (260)](https://github.com/user-attachments/assets/2bc06166-8b49-49a3-ba1c-85c1d7a90d90)

![{190E75E9-2402-4A6A-AC90-BF5800D91CA5}](https://github.com/user-attachments/assets/87bcf60c-30e8-4dd0-80f1-0b6177d863ee)

![{A48FB6A2-87D0-458A-B4E3-6CAA148D62F5}](https://github.com/user-attachments/assets/d3ae9663-4294-45b8-823e-4a78f84c8c12)

![{E1B926BC-8760-40D0-B0C2-8D97B984FCA9}](https://github.com/user-attachments/assets/2271267e-2ae5-4d3f-84f4-c4ae7e4b712a)

![{84E36C56-92FE-4420-9BA2-4A2F3EC2910E}](https://github.com/user-attachments/assets/871ada94-a3df-4a01-a41e-9eb5ad99c81f)







# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
