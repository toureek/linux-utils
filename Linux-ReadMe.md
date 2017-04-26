##Basic shell functions in developing 
* <B><H3>Part of the basic shell in Terminals (Bash / Zsh / Ksh, etc). <H3><B>
   
 1. <h3> [grep expression] && [find path expression]<h3>
	 <h4>When you want to filter and search text-content in a file or in a folder which even contains thousands of files without any IDE especially when you are just connecting to the remote server in ssh-tunnel from the terminal, you can just simply use the grep command very easily.

	 eg1. Filter and search in the known files
		  
		 `grep idea build.gradle` 
		 
		 Filtering the stringText "idea" in build.gradle file
		 
	 eg2. Filter and search in the unknown files
    
        `grep idea grade*` 
        
        Filtering the stringText "idea" in all the current directory files which has a prefix name of "grade".
        

	 eg3. Filter and search in the target folder
	 
        `grep -r idea ~/Documents/Projects` 
        
        Filtering the stringText "idea" in the target directory files and find out the results of files which has the content stringText of "idea".
        
     eg4. Find out the fileName in conditions
     
     	  `find ~/Downloads -name "*sdk.jar"` 
     	  
     	  It means that find out all the .jar files which has the suffix name of "sdk.jar" in the path of ~/Downloads.
        
        
     other examples:
     
     eg5. `find . -name "*.swift" | grep *viewcontroller` 
     
     eg6. `ps -ef | grep java` 
     
     eg7. `curl http://www.baidu.com | grep http` <h4>
     
     
     
     


