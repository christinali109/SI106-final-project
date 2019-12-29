# SI106-final-project

- Which project option is this for? iTunes Playlist

- What files (by name) are included in your submission? 
    - SI106_finalproject.ipynb: I wrote all of my code in this file. When you run this code, the main menu options will show up as well as a prompt for the user to enter in an artist name, 'exit', or 'playlist.' If the user enters an artist name, the first song from the song results on iTunes will appear (with album art, song name and artist name, and a 30 second preview) and the program will prompt the user, asking if they want to add it to their playlist (yes/no/back). If the user says yes, the song is added to their playlist and the next song appears. If the user says no, the song will not be added to their playlist but another song will still appear. If the user enters 'back,' they will be taken back to the main menu where they can enter another artist name or 'exit' or 'playlist.' If they enter another artist name, again, the first song from the song results on iTunes will appear (with album art, song name and artist name, and a 30 second preview) and the program will ask the user if they want to add the song to their playlist. If they enter 'playlist,' a list of all of the songs that they had entered 'yes' to add to their playlist will appear even from different artists (with album art, song name and artist name, and a 30 second preview). If the user enters 'exit,' the program will stop running. 

    - playlist.txt is a text file that the program writes to each time the code is run. Whenever the user enters 'yes' for adding the song into their playlist, the url of the image, the '{song name} by {song artist}', and the url of the 30 second preview gets written to this file. Thus, when the user clicks kernel --> 'reset and clear output' and then types in 'playlist' into the first prompt, the playlist that was generated the last time the program was run will appear. When the user runs the code again and enters a new artist name and starts creating a new playlist, the text file will reset and only contain the songs that was added during this run. 

    - README is a text file that gives an explanation of my project
    
- What Python modules must be pip installed in order to run your submission? To run SI106_finalproject.ipynb, type in pip install requests into a terminal.
