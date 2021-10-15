<div align="justify">
	<h1> Reminder Software Design Information</h1>
	<br>
	<h3>Class Name: User</h3>
	<p><strong>Design: </strong>Created the 'User' class to implement the relationship between the User and the Reminder List.</p>
	<br>
	<p><strong>Attributes: </strong><ol>
		<li><strong>userID: </strong>int type variable to keep track of multiple users in the database </li>
		<li><strong>userName: </strong>string type variable, stores the name of the user</li>
		<li><strong>userEmail: </strong>string type variable, stores the email of the user</li>
	</ol></p>
	<br>
	<p><strong>Operations: </strong><ol>
		<li><strong>addReminder(): </strong>adds reminder to users reminder list</li>
		<li><strong>deleteReminder(): </strong>allows user to delete reminder from their list</li>
		<li><strong>editReminder(): </strong>allows users to edit an existing reminder</li>
		<li><strong>setReminderAlert(): </strong>this method allows user to set reminder with day and time alert</li>
		<li><strong>repeatReminder(): </strong>if user sets alert for their reminder, this method will allow option to repeat the behavior</li>
		<li><strong>specifyReminder(): </strong>this method allows user to specify a reminder by typing its name. In this case, the application will search the database for reminders with similar names and ask the user if that is the item they intended to add</li>
		<li><strong>checkOffReminder(): </strong>checks off selected reminder from the list</li>
		<li><strong>checkOffAll(): </strong>checks off all reminders from the list</li>
		<li><strong>clearAllCheckOff(): </strong>clears all the check-off marks in the reminder list at once.</li>
	</ol></p>
	<br>
	<h3>Class Name: ReminderList</h3>
	<p><strong>Design: </strong>This class will store all the reminders in the reminder list selected by the user.</p>
	<br>
	<p><strong>Attributes: </strong><ol>
		<li><strong>reminderListType: </strong>a string type variable, which indicates the type of the list. (e.g. Weekly, Monthly, etc.)</li>
		<li><strong>reminderListName: </strong>a string type variable, which stores the name of the reminder list</li>
	</ol></p>
	<br>
	<p><strong>Operations: </strong></p><ol>
		<li><strong>createNewReminderList(): </strong>allows user to create new reminder list</li>
		<li><strong>editReminderList(): </strong>allows user to modify an existing reminder list</li>
		<li><strong>deleteReminderList(): </strong>allows user to delete any reminder list</li>
		<li><strong>saveChanges(): </strong>method that saves all the changes made in real time</li>
		<li><strong>saveCheckOffs(): </strong>method that saves all the reminders after checking them off.</li>
	</ol>
<br>
	<h3>Class Name: Database</h3>
	<p><strong>Design: </strong>Implements the database required for the software.</p>
	<br>
	<p><strong>Attributes: </strong></p><ol>
		<li><strong>reminderType: </strong>string type variable, stores the type of the reminder</li>
		<li><strong>reminderName: </strong>string type variable to store the name of the reminder</li>
		<li><strong>reminderListType: </strong>string type variable, stores the type of the reminder list</li>
		<li><strong>reminderListName: </strong>string type variable that indicates the name of the reminder list.</li>
	</ol>
	<br>
	<p><strong>Operations: </strong></p><ol>
		<li><strong>searchDB(): </strong>this method is run when the user specifies a reminder by typing its name. This method searches the database for reminder with 			similar names and asks the user if this is the reminder they intended to add</li>
		<li><strong>select_createNewReminder(): </strong>this method is run when the searchDB() method could not find any match in the database. It allows user to select 		  a reminder type for the reminder, or add a new one, and then saves the new reminder together with its type in the database</li>
		<li><strong>saveNewReminder(): </strong>method that saves new reminders in the reminder list.</li>
		<li><strong>saveMultipleListAtATime(): </strong>method that enables the system to save multiple reminder list at a time.</li>
		<li><strong>groupByReminderType(): </strong>this method groups the reminders by their type and saves them.</li>
	</ol>
<p>&nbsp;</p>
</div>
