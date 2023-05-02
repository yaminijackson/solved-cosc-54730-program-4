Download Link: https://assignmentchef.com/product/solved-cosc-54730-program-4
<br>



Write an expense tracking app. You are expected to use material design concepts, at least as much as taught in class. Lastly, the implementation of the GUI is left for you (mostly), but it should be intuitive to use, see the GUI section.

<strong>Expense tracking application:</strong>

<strong>Data section:</strong>

<ul>

 <li>You need to store persistent data (ie survives application restart).</li>

</ul>

o You can use SQLite or Architecture Room for the data storage.

<ul>

 <li>Data per entry to stored</li>

</ul>

o String Name

o String Category

o String Date (don’t worry about using a date format)

o Float/Real Amount

o String Note

<ul>

 <li>This is the only field the user can leave blank.</li>

</ul>

o Long/int _id (which the user won’t enter, but is needed by the db and recyclerview). This must be a unique value.

<ul>

 <li>You need to have a way for the user to create a new entry, update an existing entry, and delete an entry.</li>

</ul>

<strong>GUI section:</strong>

<ul>

 <li>You will be required to use material design for the UI.</li>

</ul>

o Colors, etc. Likely using a FAB button, etc.

<ul>

 <li>Display the entries and you are required to use a RecyclerView.</li>

</ul>

o Also, when data is changed/added, the RecyclerView is expected to change as well.

<ul>

 <li>Using LiveData/viewmodel (room) or loaders with SQLite</li>

 <li>Add new entries.</li>

</ul>

o Likely with a custom dialog box or fragment. This is up to you.

<ul>

 <li>Change entries already stored entries. o The fields will already be field with the current the data and the user can then change it.</li>

 <li>If you do this efficiently, reuse the dialog box or fragment for new entries.</li>

 <li>Delete entries in the transaction table.</li>

</ul>

<strong>For 5730 students: </strong>Complete the requirements of the program additional requirements:

(1) The user can select from already existing Categories stored. You will need to query the

database, get a unique list of categories that the user can then click on (likely via a spinner, dialog, or other. The choice is up to you). They will still be able to enter a new category as well.




<strong>TURN IN and GRADING:</strong>

Soft copy:

<ol>

 <li>Use this link to create your repo <a href="https://classroom.github.com/a/nvA3hKdc">https://classroom.github.com/a/nvA3hKdc</a></li>

 <li>Upload the project to your repo</li>

 <li>Create/Edit the <a href="http://readme.md">md</a> file, add the following:</li>

</ol>

o Course number 4730 or 5730

o Name

o how to run the program. MAKE SURE the grader understands how add/update/delete work. Even if you think it obvious.

o which phone/emulator to run on including special information like android version (ie v4.4) and screen size.

<ul>

 <li>Or if you are using the borrowed, phone: Pixel 2</li>

</ul>

<ol start="4">

 <li>Lastly ensure everything has uploaded to the github website and not just the local repo.</li>

</ol>

Code will be graded on correctness, comments, and coding style.