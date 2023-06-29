# XPLAB-stage 

These are the programs made during the stage in XPLAB (12/06/23 - 30/06/23). These were made by me and another student, with the help of two tutors. They're all made using the POWER-KI language and the POWER-KI Workbench.
#
### ciao-01.pka
###### 12/06/23
#### Asks the user's name as input and returns "Ciao" + user's name.
![ciao-01](https://github.com/francisbanua/XPLAB-stage/assets/106865288/3e094cad-495e-4d4e-8118-e34c3a92e922)
#
### ciao-02.pwk
###### 12/06/23
#### The same as ciao-01.pka, but with a GUI interface. 
#### The user inserts their name in a text box, and at the click of a button, a label with text "Ciao" + user's name appears.
![ciao-02](https://github.com/francisbanua/XPLAB-stage/assets/106865288/8337c873-b738-4d66-8f98-3a05fc5670a0)
#
### agenda-02.pwk
###### 12/06/23 - 13/06/23, 21/06/23
#### Lets the user add, edit, delete information (surname, name, number) about a person in a table, and saves these in a sql database. 
#### With 2 buttons the user can add and edit information about a person in a panel with 3 textboxes (surname, name, number), and then they can cancel or confirm the action. With a 3rd button the user can delete the information about the selected person.
![agenda-01](https://github.com/francisbanua/XPLAB-stage/assets/106865288/41d3c620-3324-419a-8ee2-ad090eff2b5c)
![agenda-01-02](https://github.com/francisbanua/XPLAB-stage/assets/106865288/7f85f114-2692-469b-94d3-66bfe0fdd1e1)
#
### rete-01.pwk
###### 13/06/23
#### Shows a cam and lets the user send and receive messages with UDP, specifying the destination ip. 
#### The user inserts the destination ip and the message in 2 textboxes, and with the click of a button, the message gets sent to the destination. In a panel the sent and received messages are shown in a ip + message format. In another panel a cam is shown.
![rete-01](https://github.com/francisbanua/XPLAB-stage/assets/106865288/b4b0ae8b-7eb5-4b10-9a77-00aac0c4595c)
#
### realsense-01.pwk
###### 13/06/23 - 14/06/23
#### Shows the 4 modes of a realsense cam.
![realsense-01](https://github.com/francisbanua/XPLAB-stage/assets/106865288/9aef6da9-870c-42da-be50-6a14a55ffa98)
#
### grid-02.pwk
###### 15/06/23 - 19/06/23
#### Lets the user add, edit, delete, choose a color and draw a point in a panel.
#### The user chooses a color by clicking on a button, which opens a new gui, which shows a table of colors. In this gui the user can add and edit a color with 2 textboxes for the color name and the color, and then they can confirm or cancel the action. To delete a color the user selects a color from the table and clicks a button. To choose a color the user double clicks on a color and they go back to the primary gui. Then the user can choose the x, y coordinates of the point by inserting them into 2 textboxes. With a button the point properties get added in a table, and the point is drawn on a panel.
![grid-02](https://github.com/francisbanua/XPLAB-stage/assets/106865288/bce9d572-4ac5-4c83-85b4-b0d09a595c87)
![grid-02-02](https://github.com/francisbanua/XPLAB-stage/assets/106865288/f789ac66-e66a-47c1-a8d7-9179bdb9f5a5)
#
### file-transfer-01.pwk
###### 16/06/23 - 20/06/23
#### Transfers files with TCP, specifying the destination ip.
#### The user can transfer a file after choosing it with a button, which opens windows' file explorer and lets the user choose a file, inserting the destination ip in a textbox, and clicking a button. The program is always listening, and the received files and the sender's ip get added in a table.
![image](https://github.com/francisbanua/XPLAB-stage/assets/106865288/c6f5660c-21ec-45a7-a7f9-2d9dd13eb985)
#
### web-01.pwk
###### 21/06/23
#### Uses the WUI to create html pages and lets the user navigate through the web by using WEB/WEBFAST.
#### In a textbox, the user can put the link of a website and by clicking a button, the website gets loaded in a panel. The user can also load an html page created in the WUI interface, by puttinc in the textbox "127.0.0.1/" or "localhost/" + file html name.
![web-01](https://github.com/francisbanua/XPLAB-stage/assets/106865288/29b7c93a-c099-4c48-8da2-9c5652f5e01e)
![image](https://github.com/francisbanua/XPLAB-stage/assets/106865288/94f3a84c-569f-48e5-aca2-f750b11c7040)
#
### native-cloud_01.pwk
###### 22/06/23
#### Opens a remoted GUI and shows all the connections in a table.
#### By executing in the terminal a command in the terminal, the user can open a GUI which is remoted from another device (can be the same device). The remote device has a table which shows all the current connections .
![native-cloud-01](https://github.com/francisbanua/XPLAB-stage/assets/106865288/db7b02f9-d9de-47ee-8a18-bdd3c1f4a583)
![native-cloud-01-02](https://github.com/francisbanua/XPLAB-stage/assets/106865288/2d46dd7d-745e-4c42-a407-2d3dae2763d5)
![native-cloud-01-03](https://github.com/francisbanua/XPLAB-stage/assets/106865288/94d523b1-1ee0-431a-970b-970cf280bc93)
#
### server-remote-01.pwk
###### 22/06/23 - 26/06/23
#### Remotable gui that lets clients navigate through the server's files, create new folders, rename, delete, download and upload files.
#### With a command executed in the terminal, the user can open a remoted GUI that lets the user navigate through the remote device's (server) files. The user can rename files/folders and create new folder by clicking the respective buttons, and a panel will appear where the user can put the name of the file/folder and then confirm or cancel. The user can delete files/folders and download files by selecting the file/folder and clicking the respective buttons (the download button will open windows' save file dialog window). The user can also upload files by clicking a button, and windows' choose file dialog will open.
![server-remote-01](https://github.com/francisbanua/XPLAB-stage/assets/106865288/272c7373-8793-43d3-a4d5-f396b673f70f)
![server-remote-01-02](https://github.com/francisbanua/XPLAB-stage/assets/106865288/3eed563a-d254-4198-b63e-cfca9740fd8e)
#
### diario.pwk
###### 27/06/23 - 29/06/23
#### School diary that lets students add and delete grades, edit the school weekly timetable, add and delete subjects, add, edit and delete events, with a weekly event summary in the initial screen. All the datas are saved in a sql database. 
#### When the program starts, the student can see in a table (with 7 columns, a column for each day of the week) the weekly event summary. There's another table for the grades, and the student can add a grade by inserting the grade in a textbox, choosing the subject in a combobox, choosing the date with a button that opens a new GUI (where you select the date and confirm or cancel) and by clicking the add button. A grade can also be deleted by selecting the grade in the table and clicking the delete button. There are 3 buttons that show different panels. 
#### The first one is for the school weekly timetable, where the student can insert the subjects for each day in a table of 7 columns, and there's also a save button to save the timetable in the database. 
#### The second one is for the subjects, that shows the subjects in a table and the student can add a subject by inserting the name of the subject and the name of the teacher in 2 textboxes, and clicking on the add button. The student can also delete by selecting the subject from the table and clicking on the delete button. 
#### The third one is for the events management, which shows a table with all the events. The student can add a new event by inserting the title and the notes in 2 textboxes, choosing the type and the subject with 2 comboboxes, choosing the date with a button, and clicking the add button. The student can delete an event by selecting one in the table and clicking the delete button. The student can also edit an event by double clicking on an event and the input fields will get filled with the values of the selected event and the student can confirm the changes by clicking on the confirm button, or add an event with those values by clicking on the add button.
![diario-01](https://github.com/francisbanua/XPLAB-stage/assets/106865288/bdbc6e20-aeb4-4963-aa17-2e6d871714d9)
![diario-orario](https://github.com/francisbanua/XPLAB-stage/assets/106865288/fd330e0d-333e-4692-920f-5ac6f6d04ff3)
![diario-materie](https://github.com/francisbanua/XPLAB-stage/assets/106865288/70781f9e-eb3c-43df-94cb-6fe631df622b)
![diario-eventi](https://github.com/francisbanua/XPLAB-stage/assets/106865288/24962413-9eb7-4c91-a413-3899f420aa72)
#
### durata.pwk
###### 29/06/23
#### Given a table about different operations, with their own beginning time and ending time, draws in a panel a graph that shows when each operation starts and ends.
![durata](https://github.com/francisbanua/XPLAB-stage/assets/106865288/4b511f83-4881-4f60-929d-1f1a89d651fe)
