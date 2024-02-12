# 🕒 Creating an Alarm Clock Web Application

This repository contains the source code for a simple alarm clock web application developed using HTML, CSS, and JavaScript. In this README, I'll walk you through the process of creating this app step by step, so you can understand how it works and even build your own.

## 📁 Project Structure

The project consists of three main files:

- `index.html`: Contains the structure of the web page, including the alarm clock interface.
- `style.css`: Defines the styles for the elements in the HTML file.
- `script.js`: Contains the JavaScript logic to handle setting and triggering the alarm.

## 🖥️ HTML Structure

The HTML file (`index.html`) sets up the basic structure of the alarm clock interface. It includes:

- An image of a clock.
- An `<h1>` element to display the current time.
- Three dropdown menus for selecting the hour, minute, and AM/PM.
- A button to set/clear the alarm.

## 🎨 Styling with CSS

The CSS file (`style.css`) styles the elements to create an attractive and user-friendly interface. It includes:

- Importing the Poppins font from Google Fonts for typography.
- Setting background colors and box shadows to enhance visual appeal.
- Styling the dropdown menus, button, and other elements for consistency and usability.

## 🔧 JavaScript Functions

The JavaScript file (`script.js`) provides the functionality for the alarm clock. Here are the key functions used in the program:

### `setAlarm()`

This function is responsible for setting or clearing the alarm based on user interaction. It toggles between setting the alarm and clearing it when the "Set Alarm" button is clicked.

### `updateTime()`

This function updates the displayed current time every second using `setInterval()`. It formats the time in hours, minutes, seconds, and AM/PM format.

### `checkAlarmTrigger()`

This function compares the current time with the set alarm time and triggers the alarm if they match. It plays the alarm sound when the alarm is triggered.

### `playAlarmSound()`

This function utilizes the `Audio` object to play a customizable ringtone when the alarm is triggered. It allows users to specify their preferred ringtone by replacing the `ringtone.mp3` file.

## 🚀 Conclusion

Creating this alarm clock web application involved combining HTML for structure, CSS for styling, and JavaScript for functionality. By understanding the functions used in the JavaScript program, you should now have a good foundation for creating your own version or customizing it further to suit your needs.

Feel free to explore the code and experiment with different features to enhance the app!
