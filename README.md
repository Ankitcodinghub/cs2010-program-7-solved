# cs2010-program-7-solved
**TO GET THIS SOLUTION VISIT:** [CS2010 Program 7 Solved](https://www.ankitcodinghub.com/product/cs2010-program-purpose-solved-5/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115590&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2010 Program 7 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Use for your reference

1. Gaddis’ book, in-class exercises and your class notes.

2. This assignment sheet &amp; the grade sheet for this lab already printed out.

3. USB Flash drive(s) or other storage media.

Mandatory Instructions

You will write a program that implements a game of Battleship that will be played between two players. The game should be able to be played numerous times. Each time a game is played one player, the hider, will set up his/her ship locations. Then the other player, the guesser, will attempt to destroy all of the opponent’s ships with at most 30 moves. If all ships are destroyed the guessing player wins, if not the hider wins and the guesser loses.

The hider’s input will be provided as three values comprised of H=horizontal or V=vertical position of the ship, row, col of the grid. For example if the user enters H 0 0 this would mean ship will have horizontal orientation starting at 0, 0 coordinate on the grid (you will use a 2-D array of type char). Ships should be entered into the array as ‘X’ characters. Example below shows all 5 ships of various sizes entered into the array. There will always be one ship of size 1, 1 ship of size 2, 1 ship of size 3, 1 ship of size 4 and 1 ship of size 5.

0 1 2 3 4 5 6 7 8 9

X X

X

X

X X X

X X x

X

x

X X X X X

X

Sample playing of the game:

Game starts with the grid being empty and the hider enters all 5 ships.

Before the game starts, warn the user so hider can switch with the

guesser.

Show progress to the guesser by showing red H for hit,

green * for miss.

If the number of guesses exceeds 30, the game ends and guesser loses. After each guess you need to call function isEndOfGame() that will return true if the guesser has destroyed all hider’s ships (Hint… the grid does not contain any ‘X’ characters. When guesser hits a ship, place ‘H’ on the ships grid as well as on the guesses grid. Call the displayGrid() function passing whichever grid you need to display.

Hierarchy chart:

Stepwise Refinement:

You have been given a the structure chart which shows the functions that should be part of the program. First create a “stub” program for your solution. A stub program should contain function prototypes, and function headers – all with any needed parameters. Function bodies should be empty with correct return value and braces. The main function should declare variables needed, and the main do while loop that will allow the user to play again. No global variables are allowed. Constants should all be declared globally.

My solutions contain ~ 300 lines of code, comments, white space.

Validating user Input

Cannot put next ship in row 6. Cannot put ship size 4 staring in row 9.

Utilize isdigit() and the following in the user input validation:

row = atoi(&amp;rowinput); col = atoi(&amp;colinput);

Array Declarations

Declare all your arrays in main. You will need 2 arrays in all. They will be 2D arrays and will represent the hider’s grid with the ships and the guessers hit/misses. Both grids are the same size, i.e., 10×10.

char ships[MAX_ROWS][MAX_COLS];

char guesses[MAX_ROWS][MAX_COLS];

The game should be able to be played several times, so you will need to ask the user if he/she wants to play again. You will need to initialize all grids and other variables each time a game is played, i.e., inside your main processing loop.

The following code would initialize array ghips to initial values before a game is played:

for (int i=0; i&lt;MAX_ROWS; i++) for (int j=0; j&lt;MAX_COLS; j++) ships[i][j] = ‘ ‘;

Function Prototypes

void initGrid(char [][MAX_COLS]); void drawGrid(char [][MAX_COLS]); void enterShips(char [][MAX_COLS]);

bool playGame(char [][MAX_COLS], char[][MAX_COLS]);

bool validateCoordinates(char, int, int, int, char [][MAX_COLS]); bool isEOG(char [][MAX_COLS]); void setColor(int);

system(“cls”) ;

Colors

The game looks much better with color so I will give you some necessary information to get this to work.

Declare constants to hold colors for pen (i.e., font colors) and the background colors.

REDPEN=4; RED=68;

YELLOWPEN=14; YELLOW=238; GREENPEN=2; GREEN=34; BLUEPEN=9; BLUE=153;

ORANGEPEN=12; ORANGE=204;

WHITEPEN=7;

You will also need the following code:

1. #include &lt;windows.h&gt;

2. Declare you color constants globally

3. Write a void function setColor taking your constant as a parameter (colordesired) and use the statements below to set the desired color for output.

HANDLE hConsole;

hConsole = GetStdHandle(STD_OUTPUT_HANDLE);

SetConsoleTextAttribute(hConsole, colordesired);

4. Call your setColor function before doing any cout calls.

Program Documentation &amp; Style:

1. Declare all variables and constants that your program uses at the beginning of your program.

2. Your program should include two types of comments: Header Comments at the top including lines with:

– Your name, course name, and class time

– A sentence or two explaining the purpose of the program

In-line comments: There should be an in-line comment for each main step in your program. In general, this means a comment with each group of C++ statements that handles the input, the processing and the output steps of your program. 3. Use meaningful identifier names

4. Include clear prompts for the user about entering the data.

5. Include clear descriptions of the results when you display them.

6. Each function should have a function documentation header that looks like this:

// -=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-= // Function: setColor

// Description: This function sets foreground/background color for the console window

// Paramters: int color – color to set

// Returns: void

// Author: Jadwiga A. Carlson

// -=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

What to turn in?

1. Logon to CS Classes (Start  Programs  CS Classes). Type in bgsulabs for both the username and password to access CS Classes.

2. Locate and open Carlson  semester CS2010 Section X Lab Y OPEN folder where X is your section number, Y is your lab assignment number and semester is something like sp2012.

3. Drag your ENTIRE application folder into it. Ask for help if you are unsure the first time.

4. You’re done.
