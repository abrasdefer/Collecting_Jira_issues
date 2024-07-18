# Collecting_Jira_issues
In this code in Javascript, you will find a way to collect automatically all the issues from a Jira project. This code is mainly made for scrum masters but anyone can use it and implement it in a Google sheets. 

# Operating instructions
If you want to implement this code in Google sheets, here are the steps:
1. Create a google sheets file
2. Rename the first Sheet "param"
3.  In cell A1, type your project key. In the cell B1 type your project  id, in the cell E1, type enter the desired start date.
4.  Create another sheet and rename it "sprints"
5.  Create another sheet and rename it "data"

# Implementing the code
1. On your google sheets go to "extensions" --> "Apps script"
2. Copy paste the code from this github file to your Apps Script coding interface
3. Change the Jira API Key. If you don't know how to do it, go to https://support.atlassian.com/atlassian-account/docs/manage-api-tokens-for-your-atlassian-account/
4. If needed, change the constant "listStatusClose" with your Jira states considered as "Closed"

Of course, you can change the code following your needs. Have fun!
   
