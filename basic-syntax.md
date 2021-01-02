## Basic syntax for Powershell

### I will cover the topics.
- [What is Powershell?](what-is-powershell.md)
- [Configurations for desktops](configurations.md)
- [Typical uses](typical-uses.md)
- [Basic syntax](basic-syntax.md)
- [Ways to automate simple tasks](automation.md)
- [Active Directory Scripts](ad-scripts.md)
- [Azure Scripts](azure-scripts.md)
- [VMware Scripts](vmware-scripts.md)
- [My Certification Journey](certifications.md)

**Powershell Version**
```Markdown
$PSVersionTable
```
Other options for getting strictly the version only. So you can use a dot (.) to access a specific property like PSVersion.listed. 
```Markdown
$PSVersionTable.PSVersion
```

**Current User**
```Markdown
whoami
```
Three core cmdlets allow you delve into what cmdlets exist and what they do:

    Get-Command: The Get-Command cmdlet lists all of the available cmdlets on your system. Filter the list to quickly find the command you need.
    Get-Help: Use the Get-Help core cmdlet to invoke a built-in help system. Or use an alias help command to invoke Get-Help but improve the reading experience by paginating the response.
    Get-Member: When you call a command, the response is an object that contains many properties. Use the Get-Member core cmdlet to drill down into that response and learn more about it.
    
*** Get-Alias ***    
The Get-Alias cmdlet retrieves the aliases for previous shell commands and displays what the Powershell equivalent. This would be very useful if you are very familiar with using Command Prompt. 

```Markdown
Get-Alias
```
![Image](/images/Screen Shot 2021-01-01 at 11.09.36 AM.png)

***Get-Help ***
The Get-Help cmdlet provides a list of cmdlets and their functions.

***cmdlets***


***Pipelines***

