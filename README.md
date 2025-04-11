Set Environment Variables:
Here's how to set them in Windows 10:
Right-click on "This PC" or "My Computer"
Click "Properties"
Click "Advanced system settings"
Click "Environment Variables" button
Under "System Variables" (bottom section):
Add CASSANDRA_HOME:
Click "New"
Variable name: CASSANDRA_HOME
Variable value: C:\Program Files\apache-cassandra-3.11.14 (or wherever you extracted Cassandra)
Update PATH:
Find and select "Path" in System Variables
Click "Edit"
Click "New"
Add %CASSANDRA_HOME%\bin
Click "OK" on all windows
Verify the Setup:
Open a new Command Prompt
Type echo %CASSANDRA_HOME% - it should show your Cassandra installation path
Type cassandra -v - it should show the Cassandra version










Set up Environment Variables:
Right-click on "This PC" or "My Computer"
Click "Properties"
Click "Advanced system settings"
Click "Environment Variables" button
Under "System Variables" (bottom section), add:
Add CASSANDRA_HOME:
Click "New"
Variable name: CASSANDRA_HOME
Variable value: C:\Program Files\apache-cassandra-3.11.14
Update PATH:
Find and select "Path"
Click "Edit"
Click "New"
Add %CASSANDRA_HOME%\bin



Start Cassandra:
Open Command Prompt as Administrator
Run: cassandra.bat


nodetool status


cqlsh

