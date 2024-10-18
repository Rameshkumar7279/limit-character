
# Character Limit Textarea with Real-Time Count

## Overview

This project demonstrates how to create a textarea with a **character limit** and **real-time character count** display using **HTML**, **CSS**, and **JavaScript**. It shows users how many characters they have typed and how many they have remaining before reaching the limit.

## Features

- **Character Limit**: The textarea has a maximum limit of 150 characters.
- **Real-Time Count**: As users type, they can see how many characters they’ve used and how many they have left.
- **Dynamic Styling**: The character count text will turn red if the user exceeds the limit.
- **Responsive Design**: The form layout adapts to different screen sizes.

## Technologies Used

- **HTML**: Provides the structure of the form and textarea.
- **CSS**: Adds styling to the form and textarea, including error colors.
- **JavaScript**: Implements the logic to count characters in real-time and display the count dynamically.

## Files Included

- `index.html`: Contains the basic structure of the form with a textarea that has a character limit.
- `styles.css`: Adds styling for the textarea, including responsive design and error styling for when the character limit is exceeded.
- `script.js`: Adds JavaScript functionality to count characters in real time and update the display.

## How to Use

1. **Clone the Repository**: Clone this project to your local machine or download it as a ZIP file.
   
   ```bash
   git clone https://github.com/Rameshkumar7279/character-limit-textarea.git
   ```

2. **Open the HTML file**: Navigate to the project folder and open the `index.html` file in your web browser.

   ```bash
   cd character-limit-textarea
   open index.html
   ```

3. **Interact with the Textarea**: Start typing in the textarea. The character count below the textarea will update in real time, showing how many characters have been used out of the 150 allowed.

## Project Structure

### HTML (index.html)

The form structure includes:
- A `textarea` with a `maxlength` attribute of 150 characters.
- A `small` tag to display the current character count.

### CSS (styles.css)

- Provides styling for the `textarea`, including basic padding, font size, and a border.
- The `small` tag is styled to display the character count, and changes to red when the limit is exceeded.

### JavaScript (script.js)

- Tracks the number of characters typed in the `textarea`.
- Updates the `small` tag in real time with the number of characters used and remaining.
- Changes the color of the character count to red if the user exceeds the limit.



### Real-Time Count Example in Action

When a user starts typing, the `small` tag below the `textarea` will dynamically update. For example:
- **5 characters typed**: "5/150 characters used"
- **150 characters typed**: "150/150 characters used" (the limit)
- **More than 150 characters**: The text will change color to alert the user that they have exceeded the limit.



You can adjust the repository name and details to match your project.
THANKS FOR VISITING THIS PAGE!!
