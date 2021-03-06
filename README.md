# Modeling Dojo: Contributing to Custom Widgets

### Learning Objectives:

* Understand and adhere to the github workflow (fork/clone/commit/push/pull-request)
* Be able to contribute to an existing custom widget

### Instructions:

1. Fork this repository
2. Clone it to your local machine 
3. Modify _InfoButton/widget/InfoButton.js_ to log your name as part of the `messageString` variable on line 63. 
4. Choose one of the following modifications to make to the widget:
    + Add a translatable string property to change the text displayed in the button node
    + Add a boolean or enum property to configure if the popup is modal or not
    + Add an integer property to set the timeout before showing the popup
    + Add a string property to set the class of the button node
    + Add a microflow property to execute a microflow when the button node is clicked
5. Commit your changes
6. Push your commit to your fork
7. Create a Pull Request to have your changes merged into the existing widget

### More Resources:

* [Learning Path for Intro to Custom Widgets](https://gettingstarted.mendixcloud.com/link/path/45)