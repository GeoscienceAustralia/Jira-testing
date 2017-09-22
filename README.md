# Jira-testing
Repository used for testing Jira integration


Testing "smart commits"
=======
testing

And testing some more

And more...

Change primary email address to GA email
<testing smart commits: comment>  <PYR-12> #comment <Commenting to jira from GitHub from GA email address>

PYR-12 #comment try without the angle brackets 
-------------------------------------------------

Using Smart Commits to move issues through a jira workflow require the use of the transition name NOT the state name
https://stackoverflow.com/questions/18255710/how-to-resolve-a-jira-issue-from-github-commit-messages 

PYR-12 #Move to In Progress

Reading indicates that if the transition is a phrase instead of a word, it needs to be hyphenated
https://stackoverflow.com/questions/31753497/how-to-enable-smart-commit-for-custom-workflow-in-jira 

Test again as:

PYR-12 #Move-to-In-Progress

Test impact of putting Smart Commit detail into Commit title instead of file
- FAILED - Email from Jira saying that PYR-12 does not exist

Test 13
Test Smart Commit in commit description
Note: Primary email is GA and email is NOT private
FAILED - jira failure to find PYR-12 email

Checked and it's trying to find it in gaAutobots not gajira...

Test 14
Testing Smart Commits to gaautobots jira for Shane to see
- FAILED - Error message from jira "Can't find WT-3" yet the comment appeared BUT the commit in Developer section did not appear

Test 16
Application URLs in github changed from gaautobots to gajira
Test Smart Commits commetn from GA github to gajira
FAILED - Jira error email "can't find PYR-12"

Test 17
Application URLs in github changed from gaautobots to gajira
Test Smart Commits comment from GA github to gaautobots jira
Success - Jira "Failed" email, yet comment appeared in WT-3 and commit updated in Development section

Test 20
Test smart commits to GAJIRA from Shane's account without existing personal OAuth to gaautobots

