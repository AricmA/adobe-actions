# adobe-actions // macOS
A collection of Js files for different Adobe Acrobat Actions.<br>
YOU NEED TO HAVE ADOBE ACROBAT CC FOR EVERY THING IN THIS REPOSITORY.

## Tables of Contents
- [Print Action](#print-action)


## Print Action

This print action ist  very simple und is very usefull to me. Every week I have to donwload over 10 reports with over 10 sites and I always need to print the first two pages of these reports. So this can Take a Lot of time and nerves. That's why I did some reserch on how to write a Adobe Acrobat Action.

To install the action, we have to check some dependencies and than do the following.

### Dependencies

1. [x] Have Adobe Acrobat installed.
2. [x] Have a printer set up and ready to print.
3. [x] Have a document or a bounch of docs than you want to print. 

### Installation


![Adobe Action part 1](https://media.giphy.com/media/l4Ep4IuDhczpB3iww/giphy.gif)

1. open Adobe Acrobat and go to the Action Wizard menue

2. creat a new Action 

3. add A Js Script to the action
 
4. copy the Code from below or the printAction.js in the repositiory and paste it into the Js file of the action


The Code for that action is very very simple.

```javascript
/*
The first argument enables[true] or disables[false] the print dialog.
This is for selection the printer, etc.

The second and third argument is for selecting the pages like elements in an array.
[0,..to..,1] selects only the first two pages of every document.

I forgot what the fourth argument did :(. I will come back to it ...
*/

this.print(false,0,1,true); 

```

## Use

To use the action. Just open it select over the file manager a bounch of files and run it.
Have fun. And if anybody using this or is reading this and is having troubles.
Write me an email: support@aricma.com
