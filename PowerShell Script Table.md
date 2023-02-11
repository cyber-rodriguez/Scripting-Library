|   Script   |   Description   |
| -------------- | -------------- |
| Get-Content | Gets the content of the item at the specified location 
| **EXAMPLES** | EX.1, EX.2 & EX.3 |
| ForEach-Object | Performs an operation against each item in a collection of input objects. |
| $_  | stands for each item in the host.txt file. |
| **EXAMPLES** | EX.4, EX.5 and EX.6 |
| Out-File | Sends output to a text file. |
|  **EXAMPLES**  | EX.7, EX.8 and EX.9 |
| Test-NetConnection | Displays diagnostic information for a connection. A ping on steroids|
| **EXAMPLES** | EX.10 and EX.11 |
| ConvertTo-Json | -------------- |
| Get-Date | -------------- |
| Start-Sleep | -------------- |
| Write-Host | -------------- |
| Get-Host | -------------- |
| Get-Command | -------------- |
| Get-Help | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |



**EX.1**   	Get-Content hosts.txt	 |
- This example will show you what is in the file titled hosts.txt
- You are running this script in the same directory as host.txt

**EX.2** 	$hosts = Get-Content hosts.txt
- The variable $hosts is the for everything in host.txt
- You will see the contents on the screen it is all in the variable.

**EX.3** 	Get-Content hosts.txt -Path C:\TestFolder\host.txt
- You are running this script woth the only difference being you stating the directory the file is found.

**EX.4**	
$hosts | ForEach-Object {
	$_
}


**EX.5**	
$hosts | ForEach-Object {
	Write-Host $_ -BackgroundColor white - ForegroundColor black
}

- The -BackgroundColor & - ForegroundColor will affect the content being displayed.


**EX.6**	
$hosts | ForEach-Object {
	Write-Host "Hostname: $($_)" -BackgroundColor white - ForegroundColor black
}

- This version of the script will display Hostname: before each line of content.

**EX.7**	
"My name is Coder" | Out-File	 test.txt

- Whatever is in the quotes will be in the test.txt file.

**EX.8**	
"My name is Coder" | Out-File	 test.txt -Append

- The -Append will add to the content of the test.txt file

**EX.9**	
$hosts | ForEach-Object {
	"Hostname: $($_)" | Out-File outputhosts.txt -Append
}

- This will put the hostnames into the outputhosts.txt and append it if needed.

**EX.10**	
Test-NetConnection -ComputerName www.google.com

- This returns the following information. ComputerName, RemoteAddress, InterfaceAlias,SourceAddress, PingSucceeded and PingReplyDetails 


**EX.11**	
$hoststatus = Test-NetConnection -ComputerName www.google.com

- Everything from the previous script is now assigned to the variable.
- An alternate can be


