# WinEDB
Windows.EDB Browser 

==> [Latest version](https://github.com/kacos2000/WinEDB/releases/latest) <==

   ![image](https://user-images.githubusercontent.com/11378310/207680831-cc3b3a37-0405-4833-894c-9087c607f8d1.png)


   - The stand-alone x64 command line tool [WindowsEDB-to-CSV.exe](https://github.com/kacos2000/WinEDB/raw/master/WindowsEDB-to-CSV.exe) or it's equivalent Powershell script [WindowsEDB-to-CSV.ps1](https://github.com/kacos2000/WinEDB/blob/master/WindowsEDB-to-CSV.ps1) will split the contents of the
    "SystemIndex_PropertyStore" table to multiple CSVs as seen on the image below:
         
     ![image](https://user-images.githubusercontent.com/11378310/208239941-3c71634a-91cb-42c1-958a-7622f6826563.png)
     
    Some stats:
    ---------------------------
    Database size: 2.950.692.864
    GUI     - Processing finished in: 09:33:33 (H:M:S)
    PS1/EXE - Processing finished in: 04:39:12 (H:M:S)
    Previous version of ps1 finished in: 18:25:05 (H:M:S)
    ---------------------------



Dependencies: 
- [.NET Framework 4.8](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48)
- [Powershell Version:  5.1](https://docs.microsoft.com/en-us/powershell/scripting/windows-powershell/install/windows-powershell-system-requirements?view=powershell-5.1)
_______________
- Uses [Microsoft.Isam.Esent.Interop](https://github.com/microsoft/ManagedEsent) *(it is encoded+compressed, but can be exported)*. I recommend using [JetBrains dotPeek](https://www.jetbrains.com/decompiler/) with [Esent.Interop.dll](https://github.com/kacos2000/WinEDB/blob/master/Esent.Interop.dll) or the [latest release of ManagedEsent](https://github.com/microsoft/ManagedEsent/releases/latest) to get more info on the structures
_______________

--> for research purposes :) 

