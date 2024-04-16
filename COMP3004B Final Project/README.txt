COMP3004B Team-41:

Members:
Alexander Ampah:101169097
Daniil Pakhomov:101049124
Liam Lowndes:

Contributions:
Alexander: I did the connection test function, the check battery function,
 the functions and code that handles the lights on the graph as well as the replace battery function and button. 
I did the Use Case Diagram, the sequence diagrams and the traceability matrix. I also worked on the UI.
Daniil: I did the main session function including the case handling for battery dying,
soft off, battery drain during sessions, session recording and output, as well as the
enabling and disabling of different components of the ui as necessary.
For the power button I fixed the GUI reactivity and again made sure the appropriate gui elements
were enabled or disabled at the appropriate time, as well as handled functionality
such as what happens if the power button is pressed but battery needs 
replacement. I made the use cases, as well as the UML Class diagram, and I contributed to the traceability
matrix somewhat. I also implemented the drain for battery
just doing actions around the program and using the gui.
Liam: Made the UI though the original was made by Daniil. Did the functionality for most of the buttons in the GUI. 
Made most of the functions for the buttons and GUI.

File Organization:
Code will be in the OasisPro-master file.
Pdf with diagrams and use cases will be in the main folder.

Tested Scenarios:
1-Turn On/Off: The device turns on and off.
2-Selecting and undergoing session: You can select what type of session, the time and undergo the therapy.
3-Connection test: The connection test is completed before each session though it does not show if there is bad or no connection.
4-Adjusting intensity during session: You can adjust the intensity during the session.
5-Soft off: The soft off works when the power button is presssed during the session.
6-Recording: If recording is enabled the session details will be saved in the log of recorded sessions
assuming we have not hit storage capacity.
7-Battery Levels: If battery dies in the middle of a session, or is too low to start, appropriate behavior is displayed.
