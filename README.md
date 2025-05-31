# IBMCyberSecurityProject
IBMCyberSecurityProject

https://labs.cognitiveclass.ai/v2/tools/cloud-ide?ulid=ulid-a5e26eaa36068ab05aa9c5fe03527993b210cbbd

https://author-ide.skills.network/render?token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJtZF9pbnN0cnVjdGlvbnNfdXJsIjoiaHR0cHM6Ly9jZi1jb3Vyc2VzLWRhdGEuczMudXMuY2xvdWQtb2JqZWN0LXN0b3JhZ2UuYXBwZG9tYWluLmNsb3VkLzNLV05ta1U5akJ2WXJPRGh2eXg5b3cvRmluYWwlMjBQcm9qZWN0LXYxLm1kIiwidG9vbF90eXBlIjoidGhlaWEiLCJhdGxhc19maWxlX2lkIjozMTA5NjMsImFkbWluIjpmYWxzZSwiaWF0IjoxNzQ2NzgzNDA5fQ.wLXlml5K0xAxtOveyus8bgv6cWXbviHEfCFXZGkuUsw


Perform Reconnaissance and Automate Tasks:
Perform essential user management tasks, such as creating, renaming, updating passwords, and deleting accounts
Perform network reconnaissance using standard tools such as whois, dig, and Nmap to extract network information
Create a Python script to automate DNS lookups

Part 1: Perform security tasks
In Part 1 of the final project, you will manage user accounts on a Kali Linux VM by creating, renaming, updating passwords, and deleting a user account and its home directory.

Create a new user named test.
Hint: Run the adduser command with elevated privileges.
Assessment: Ensure to save the full command you used; you'll need it later for the assessment.

Change the username from test to test_user.
Hint: Use the usermod command to change the username. Before doing so, make sure no active processes are running under the current username, as this may cause the command to fail.
Assessment: Ensure to save the full command you used; you'll need it later for the assessment.

Update the password for test_user.
Hint: Use the passwd command to reset or update the password for a specific user.
Assessment: Ensure to save the full command you used; you'll need it later for the assessment.

Delete the test_user account and its home directory.
Hint: Use the deluser command with the --remove-home option to delete the account and its home directory.
Assessment: Ensure to save the full command you used; you'll need it later for the assessment.

Part 2: Gather information about a domain using whois, dig, and Nmap
In Part 2 of the final project, you will use tools like whois, dig, and Nmap to extract information about domains and networks.

Open a terminal and use the whois tool to retrieve publicly available information about ibm.com.
Assessment:
Record the following details for your assessment submission:

The full command you used for this step
The year the domain name was created
The registrant's name
The registrant's organization
Use the dig command to retrieve publicly available DNS information about ibm.com.
Assessment:
Record the following details for your assessment submission:

The full command you used for this step
The A record (IPv4 address) of the domain
The DNS server identified in the response
Use the Nmap command to perform service version detection on scanme.nmap.com.
Assessment:
Record the following details for your assessment submission:

The full command you used for this step
The operating system identified by the scan

Part 3: Automate DNS lookups with a Python script using the dig command
In Part 3 of the final project, you will develop a Python script that automates DNS lookups using the dig command and saves the results to a text file.

Instructions
Develop a Python script that automates dig lookups for client domains and saves the output to a file.

Your script should meet the following requirements:

Use the os module to execute the dig command
Prompt the user to enter a domain name for DNS reconnaissance
Save the output of the dig command to a file named 'dig_output.txt'
Include a clear print statement that notifies the user where the output file has been saved
Assessment
Make sure your final dig.py script fulfills all the listed requirements, and keep the code ready for submission.

Author
Dee Dee Colette

© IBM Corporation. All rights reserved.

ANSWERS:
https://mark.skills.network/learner/1547/successPage/64033 





