We will focus on clientside or ‘in-browser’ Javascript which can be used to manipulate existing HTML/CSS, react to the client’s action, make requests to send and retrieve data, and much more.
In this lab, we will use Javascript to implement the classic game of rock-paper-scissors.
Here’s a quick refresher on the rules - Rock, Paper, Scissors is a two-player game where each round both players simultaneously choose a move. If both the moves are the same, the players tie otherwise the player with the trumping move wins the round. The moves interact with each other as follows:

Rock beats Scissors
Scissors beats Paper
Paper beats Rock
We have created a web page that allows players to interact with the game. The various elements on the web page can be used to submit inputs or display outputs. Let’s start by taking a look at the source code.

Each HTML page usually starts with a <!DOCTYPE html> declaration to help the browser identify the document type. All content is contained within the <html></html> tags. The <head> tag contains metadata about the page; content that is not displayed by the browser. The <body> contains content that is displayed by the browser and directly viewable by the user.

In this lab, <head> contains the following elements:

<title>: Contains a title that is displayed by the browser on the page’s tab.
<script>: Contains Javascript code or points to a different file with Javascript code. In this lab, All Javascript will be written in a different file (created in a later step). Once the file/code is loaded by the browser, The Javascript is executed.
<style>: Like a <script> element but for CSS, All CSS is either written in this tag or in a different file to which this tag refers. CSS is used to stylize the elements in the web page by specifying visual aspects such as margin, padding, color, etc.
