# Introducing variables

While developing flows, it's common to reuse information in multiple actions and update it based on certain conditions. For example, you might need to store some retrieved emails and process them later in your flow.

- You can think of variables as storage bins that save valuable information while a flow is running
- The stored information can be virtually any type, such as 
	- numbers
	- text
	- dates
	- files
	- folders

- In order to use variables as input parameters in actions, you have to enclose their names in percentage characters. 
- Using this notation, you command the platform to interpret the value as a variable and not a hardcoded content.
	- For example, to use a variable named **CustomerName**, you have to populate the action's respective input parameter with the expression: **%CustomerName%**.


