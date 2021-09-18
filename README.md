# CALCULATOR + TIC-TAC-TOE

This is a mini project for Newton School mini project Assignment where Javascript is centered.


I have made below three pages in this project. and I have kept neon theme for all.
- Home Page
- Calculator Page
- TIC TAC TOE page

  
## Home page features

 - This is simple Home page where you can go to 'Calulator page' and 'Tic Tac Toe page'.
 - In Javascript I have used 'mouseover' and 'mousedown' event on images to display messages to tell about clicking on images.

 ## Calulator page features

- HTML Part:
    - In this for HTML part i have used these elements:
        - display1 - main display.
        - display2 - display with History.
        - tempdisplay - display which shows previous result.
        - operators button - '%', '+', '-', '/', 'X'.
        - numbers button - '0' to '9'.
        - equal sign button - '=' .
        - All clear botton - 'C' : clear all displays.
        - Clear last element button - 'CE': clear last element on main display.

- CSS part:

    - For CSS part i have mainly used 'grid-template' & 'grid-column' property to arrange my html button element to look like a calulater. 
    - Other Properties I have used in CSS :
        - padding
        - margin
        - box-sizing
        - background-color
        - color
        - font-size
        - text-align
        - min-height
        - height
        - width
        - max-width
        - display
        - align-items
        - justify-content
        - overflow 
        - box-shadow
        - text-shadow
        - position
        - bottom
        - border
        - opacity
        - cursor
    - I have used hover selector on buttons to change color of button when hovering on it.

- Javascript part:
    - For Javascript, I have made necessary const veriable to return element from html by using querySelector method. 
    - Then i have also used other simple veriables for necessary part in code.
    - I have mainly used addeventListner with click in my code to change varibales and write logic.
    - Features I have made using Javascript:
        - You can add dot only once.
        - You need atlest two number for Calculation. (if you click '=' with adding only one, then nothing will happen).
        - If there is no number on main display then you cannot add any operators further, you have to add numbers first.
        - You can operate from key-board also. For that, I have used click function with my html elements. 

## TIC-TAC-TOE features

- This is simple Tic-Tac-Toe game that you can play with computer. Your turn will be always first and you will be 'X' always.

- HTML part:

    - In html part, I have used below element as main content.

        - playerTitle : this will shows title , which will changed at end of the game.
        - Starting Message : this is a message to start a game, this will hide after starting.
        - main play area : I have used 9 <div> elements for this.
        - rematch : This will shown at end of the match to rematch.

- CSS part:

    - In CSS part, I have used grid-template to make 3 X 3 boxes for play.
    - I have make two class to put 'X' and 'O' in that boxes while playing. that will not be present in initial html code. These class will be added to html by using JS logic. I have used background property in that and put the images of X and O.
    - Other property I have used are as per below :
    
        - padding
        - margin
        - box-sizing
        - font-family
        - min-height
        - width
        - display
        - align-items
        - justify-content
        - text-align
        - background-color
        - font-size
        - text-shadow
        - margin-botton
        - color
        - height
        - max-width
        - display
        - border
        - box-shadow
        - cursor
        - display
        - text-decoration
        - opacity

- Javascript part :

    - In Javascript, i have made one function (init()) to run my main logic for game. 
    - In init(), i have made I have made necessary const veriable to return element from html by using querySelector method.
    - I have used one array variable which contains number 1 to 9. It will help to check win and some other part in code.
    - I have also used other array variable for my grid area to check which area i have clicked.
    - To detect click, i have used addeventListner with click.
    - Features I have made using Javascript:
        - You can not select and change area which is already clicked.
        - player title will be change at end of the game according to result. For that i have used .innerText() method on playerTitle class.
        - rematch button will show at end of the game and starting info message will be removed with first click. For this, I have used classlist.add() method.
