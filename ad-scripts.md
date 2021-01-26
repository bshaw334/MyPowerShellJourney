### Active Directory Scripts

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

**Active Directory - List Users from a Group**
```markdown
dsquery group -samid "(add group name)" | dsget group -members | dsget user -display -email >>(write results to this file path)(name of file).csv
```
dsquery group gets the domain services group by the -samid; dsget group gets the -members listed in the group; dsget user gets the users infomartion by therequested tags; >>writes the results to a specified file

**File System - Search for File Name in a Directory**
```markdown
Get-ChildItem -Path "C:\Users\MyAccount" -Recurse -Include *Search Criteria* | Out-File -FilePath "C:\Users\MyAccount\Desktop\results.csv"
```

