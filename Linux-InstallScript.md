##Do one thing at a time, and do well. 


 1. <h3> Easy come, Easy Go in VI / VIM<h3> 
    <h4>Open a file in VI within a bash, zsh, ksh, etc.<h4> 

	 	`vi 2017.txt`    // Open a file named 2017.txt in VI window. 

	 	`:q`   // Just quit from VI window. 
	 	
	 	`:wq`  // Save current text content and quit from VI window. 
	 	
	 	`:q!`  // Ignore everything in 2017.txt and Quit from VI window forcely.
	 	 

 2. <h3> Basic but important modes in VI.<h3>
	 	<h4>There are 3 different modes in vi text editor.<h4>
	 	
	 	- Command Mode.		　(You can use vi-command to handle with any textString)
	 	- Insert Input Mode.　(You can text anything whatever you want)
	 	- Last line Mode.　　(You can use ':' to call other vi-commands in Command Mode)

	 		 1. ESC   ---------> Make VI into Command-Mode 
	 		 2. a(append), i(insert), o(open-in-the-next-line)　　----> Make VI into Insert Mode 
	 		 3. : ------->  Make VI into last line mode 
	 		 

 3. <h3> Start from the sence of playing games in VI.<h3>
	 <h4>I believe that you have ever played Computer-Games or Game console before. We can press the keyboard of "[W / ↑], [S / ↓], [A / ←], [D / →]" to control the orientations in the game. As the same way, we can use another 4 keys to control the input-source. By the way, We should be more attention to every single letter, especially for its Uppercase style and Lowercase style, because even the same letter in different style means different operation in VI. 


	 + j	  ------------->   Turn down  ↓   (Lowercase style)
	 + k     ------------->   Turn up   ↑       (Lowercase style)
	 + h	  ------------->   Turn left  ←   (Lowercase style)
	 + l	  ------------->   Turn right →   (Lowercase style)
	 + :help  -------> It is the only command that we can trust while texting.
 


