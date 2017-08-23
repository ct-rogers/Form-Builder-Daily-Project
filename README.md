Form Builder

This project will test your knowledge of parsing through an array of data and appending it to the DOM.

Instructions

Download the starter files below. Using the variable formData at the top of the main.js file, iterate through the data and dynamically add the form fields to the page. The basic HTML and starter files are included for you. 

<img src="https://camo.githubusercontent.com/609ba70ae960a6d7fef45f78e927debc1e9218fa/68747470733a2f2f7469792d6c6561726e2d636f6e74656e742e73332e616d617a6f6e6177732e636f6d2f64393836393530352d66756c6c2e706e67">

Interpreting the formData Array

Each object in the array contains data about one of the input controls for the form. These objects have several properties that we will discuss briefly.

For instance, the following code snippet is the first object in the formData array:

    "type": "text",
    "label": "First Name",
    "id": "user-first-name",
    "icon": "fa-user",
    "options": []
}
The type property specifies the type attribute of input. In this case, the type is "text."
The label property specifies the placeholder text for this input.
The id property specifies the value of the id attribute of the input.
The icon property specifies the character icon for Font Awesome. This property is used only to complete the hard mode of this project.
The options property contains additional information for some of the inputs. The context and type of input should inform how to use this data.
The first form element has been included as a comment in the HTML file so that you can see this in action. Your job is to iterate over the array, parse the objects, and construct the inputs to recreate the form in the screenshot.
Form Builder Starter Files starter_files.zip (3 KB)

Hard Mode

Use Font Awesome to add the icons to the left of the inputs. You'll notice the fa- is in the data for each element.
