<div align="justify">
	
	<h1 align="center"> Reminder Software Design Information</h1>
	<br>
	<h3>Class Name: User</h3>
	<p>Design: Created the 'User' class to implement the relationship between the User and the Reminder List.</p>
	<br>
	<p>Attributes: <ol>
		<li>userID: int type variable to keep track of multiple users in the database </li>
		<li>userName: string type variable, stores the name of the user</li>
		<li>userEmail: string type variable, stores the email of the user</li>
	</ol></p>
	<br>
	<p>Operations: <ol>
		<li>addReminder(): adds reminder to users reminder list</li>
		<li>deleteReminder(): allows user to delete reminder from their list</li>
		<li>editReminder(): allows users to edit an existing reminder</li>
		<li>setReminderAlert(): this method allows user to set reminder with day and time alert</li>
		<li>repeatReminder(): if user sets alert for their reminder, this method will allow option to repeat the behavior</li>
		<li>specifyReminder(): This method allows user to specify a reminder by typing its name. In this case, the application will search the database for reminders with similar names and ask the user if that is the item they intended to add.</li>
		<li>checkOffReminder(): checks off selected reminder from the list</li>
		<li>checkOffAll(): checks off all reminders from the list</li>
		<li>clearAllCheckOff(): clears all the check-off marks in the reminder list at once</li>
	</ol></p>

</div>
