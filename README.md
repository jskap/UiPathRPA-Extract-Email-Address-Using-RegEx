# UiPathRPA-Extract-Email-Address-Using-RegEx
Extract the email address from a string (using RegEx).

Given a string containing one email address, create a workflow to extract the email address using regular expressions. 

Note: For input please use a String variable with the following value 
“Please use the following address to contact me john.doe@localcompany.com, it's the company email"

In UiPath Studio, create a new project and perform following steps:

 1.   Start the project as sequence.
 
 2.   Use the 'Matches' activity with the RegEx tailored for email addresses and use an IEnumerable variable to store them.
 
 3.   Use a 'For Each' activity to loop through the values in the created variable and use the 'Write Line' activity and the
      'Value' method to display the values.
 
