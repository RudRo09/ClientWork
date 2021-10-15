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
		<li><strong>specifyReminder(): </strong>This method allows user to specify a reminder by typing its name. In this case, the application will search the database for reminders with similar names and ask the user if that is the item they intended to add.</li>
		<li><strong>checkOffReminder(): </strong>checks off selected reminder from the list</li>
		<li><strong>checkOffAll(): </strong>checks off all reminders from the list</li>
		<li><strong>clearAllCheckOff(): </strong>clears all the check-off marks in the reminder list at once</li>
	</ol></p>
<p>&nbsp;</p>
</div>
