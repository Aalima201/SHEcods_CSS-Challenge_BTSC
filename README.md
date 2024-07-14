HTML EXPLANATION :

o	<head>: Contains meta information and links to the CSS file.
o	<body>: Contains the main content, including:
o	A div with the class maze that represents the maze.
o	A div with the class ball and id ball that represents the ball.
o	A div with the class controls that contains buttons to control the animation.
o	A script tag that links to the JavaScript file.

CSS EXPLANATION :

o      body: Styles the body to center the content and set the background color.
o      maze: Styles the maze with a fixed size and border.
o      ball: Styles the ball with a fixed size, color, and position.
o      @keyframes moveBall: Defines the animation for the ball’s movement through the maze.
o      controls: Styles the control buttons.

JAVASCRIPT EXPLANATION :

o       startAnimation: Resets and starts the animation from the beginning.
o       resumeAnimation: Resumes the animation if it was paused.
o       stopAnimation: Pauses the animation.


HOW IT WORKS :
Start Button: When clicked, the startAnimation function resets the animation and starts it from the beginning.
Resume Button: When clicked, the resumeAnimation function resumes the animation if it was paused.
Stop Button: When clicked, the stopAnimation function pauses the animation.
This setup allows you to control the ball’s movement through the maze, starting from the beginning, pausing, and resuming as needed.
