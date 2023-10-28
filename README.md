# smartcradle

Cradle Swing Control System Readme
Author: Sakshi
Date: 26-June-2023

* INTRODUCTION
  This program is designed to control a cradle's swinging motion with the ability to customize the speed, add toys, and play music. It's a versatile system for soothing babies and providing entertainment.

* HOW TO USE
  Running the Program: Simply compile and run the program. It's designed to be a text-based menu-driven application. The main function listens for sensor data (baby cries) and swings the cradle accordingly.

* MENU OPTIONS: The program presents the following menu options:

 Swing with Speed: Choose the speed at which the cradle should swing.
 Swing with Toy: Add a toy to the cradle's rotation.
 Swing with Music: Play music while swinging the cradle.
 Previous Speed: Recall the previously entered speed.
 Rotate Toys Backward: Rotate the toys in reverse order.
 Play Previous Music: Play the previously selected music.
 Play Next Music: Play the next music in the list.
 Display Speed List: View the list of selected speeds.
 Display Toy List: Display the list of toys added.
 Display Music List: Show the list of selected music.
 Exit: Close the program. The selected speed list will be saved in a file.

* SPEED CONTROL: You can specify the speed at which the cradle should swing. The program stores this information in a linked list.

* TOY ROTATION: You can add toys to the cradle, and they will rotate in the order they were added. The program prevents adding the same toy twice.

* MUSIC PLAYBACK: Select music to play while the cradle is swinging. You can also navigate to the previous or next track.

* DATA PERSISTENCE: The program saves the list of selected speeds to a file (speedList.bin) to retain this information between program runs.

* FILE OPERATONS
  The program includes file operations to save and load the list of selected speeds. You can use these functions to preserve your speed preferences.

  saveSpeedLinkedListToFile: Saves the speed list to a binary file.
  loadSpeedLinkedListFromFile: Loads the speed list from a binary file.

* DATA STRUCTURES
  The program uses linked lists to manage speed, toy, and music selections. It stores these selections in the following data structures:

  speed: Linked list to manage cradle swinging speed.
  toy: Doubly linked list to manage toy rotation.
  music: Circular linked list to manage music playlist.

* ADDITIONAL INFORMATION
  The program assumes that sensor data is provided through a variable data. If data is equal to 1, the cradle swings; otherwise, it doesn't.
  You can rotate toys backward, but it assumes that there are toys in the list to rotate.
  Music playback assumes that there are songs in the playlist to play.

* USAGE TIPS
  Always start by selecting a speed. The program can remember and replay the last selected speed.
  You can add toys and play music for an enhanced soothing experience.
  Don't forget to exit the program when you're done. It will save the selected speed list for future use.

* CONCLUSION
  This program offers a user-friendly interface to control a baby's cradle, with the flexibility to adapt the swinging speed, add toys, and play soothing music. It's a helpful tool for parents looking to create 
  a comfortable environment for their baby. Enjoy using it!
