# Simple Betting Host

This Node command line app calculates the dividends for a simplified form of Tote betting for Tabcorp. The Node version here is the standard version v6.10.0, so please do not use any versions which is too old or too advanced for Node to run the app.

## Steps to use the app
1. Unzip the bettin_host folder and cd into it in the terminal.
2. Run "npm install" to install the required packages.
3. Create a txt file called "bets.txt" in the root folder if there is no such file.
4. Write down the inputs as well as the result in the "bets.txt" file. Please make sure that each bet should be followed by a newline character and the last line is always the only result.
5. Make sure you are in the root folder. Run 'node main.js' to show the calculated result.


## Please keep in mind that
1. Format of bets should be <code>Bet:product:selections:stake</code>.
2. <code>product</code> could only be <code>W</code> or <code>P</code>.
3. <code>selections</code> could only be a positive integer.
4. <code>stake</code> could only be a positive number.
5. Format of result should be <code>Result:first:second:third</code>.
6. <code>first</code> could only be a positive integer. Same for <code>second</code> and <code>third</code>
7. Any invalid format in the "bets.txt" will render an error in the terminal and the position will be shown for the user to fix it.
