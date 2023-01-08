# WinEDB
Windows.EDB Browser 

GUI: 
==> [WinEDB Latest version](https://github.com/kacos2000/WinEDB/releases/latest) <==

   Search Store Tree view:
   ![image](https://user-images.githubusercontent.com/11378310/209396462-f41f4165-1ac7-4308-8b28-9ae2d06c8d44.png)
   
   Schema Info:
   ![image](https://user-images.githubusercontent.com/11378310/209396112-17cb7093-324c-43c6-892e-f2447ac0fdc5.png)

Command line:<br>
==> [WindowsEDB-to-CSV.ps1](https://github.com/kacos2000/WinEDB/blob/master/WindowsEDB-to-CSV.ps1)<br>
==> [WindowsEDB-to-CSV.exe](https://github.com/kacos2000/WinEDB/blob/master/WindowsEDB-to-CSV.exe)<br>

Dependencies: 
- [.NET Framework 4.8](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48)
- [Powershell Version:  5.1](https://docs.microsoft.com/en-us/powershell/scripting/windows-powershell/install/windows-powershell-system-requirements?view=powershell-5.1)
- Uses [Microsoft.Isam.Esent.Interop](https://github.com/microsoft/ManagedEsent). 
_______________

--> for research purposes ;) 

_______________

**[Note]**<br>
As of Windows 11 22H2,  Windows Search data is stored in multipe SQLite3 dBs<br>
found at 'C:\ProgramData\Microsoft\Search\Data\Applications\Windows'*<br>
Below are some initial Queries:
  - [PropertyMap](https://github.com/kacos2000/Queries/blob/master/Win_Search_PropertyMap.sql)
  - [Paths (SystemIndex_1_PropertyStore) query](https://github.com/kacos2000/Queries/blob/master/Win_Search_PropertyStore.sql)
  - [SecurityDescriptor (SecStore.db) query](https://github.com/kacos2000/Queries/blob/master/Win_Search_SecStore.sql)
  - [Paths/Files & Timestamps (Windows-gather.db) - can be used to create a TreeView of the paths](https://github.com/kacos2000/Queries/blob/master/Win_Search_gatherdB.sql)
