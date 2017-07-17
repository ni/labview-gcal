# iCalendar Toolkit 
 
This toolkit allows the user to create iCalendar(ICS) files, send emails to specified accounts including attachments. It also gives an option of editing and extracting the iCalendar file. 

# Write iCalendar File VI 
-	Summary
	Write iCalendar File VI creates an iCalendar file based on the inputs.
-	Inputs: Path to Save, Recipient’s Email Address, iCalendar File Configuration. 
-	Outputs: Creates an iCalendar file and return the Path Out.

# Send Email VI
-	Summary
	Send Email VI sends an email to specified accounts (depending on the server and port mentioned) with an optional attachment. Note that the default settings are for Gmail.
-	Inputs: Optional Attachment, Sender’s Configuration, Email Configuration. 
-	Outputs: Sends email. 

# Read iCalendar File
-	Summary
	Read iCalendar File VI opens an iCalendar file and extracts the most important information out of it.
-	Inputs: Path to Open the file
-	Outputs: Path out, ICS String Out, Extracted Data.

#Examples
	iCalendar Toolkit example creates an iCalendar file and sends it via email to the mentioned recipients. 
	After the email is sent the file is being extracted. Also, there is an output of the ICS format string.

#General Notes
Make sure to input all the information required in the example VI correctly. 

##Support for iCalendar Toolkit for LabVIEW:
This product is not supported by NI. For help, more information, contributions to the product, please go to the GitHub page for this toolkit. (hhtps://github.com/ni/labview-gcal)	
