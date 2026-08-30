https://github.com/SpecterOps/BloodHoundQueryLibrary/tree/main/queries
--------------------------------------
cd .\Downloads\

powershell -ep bypass

or   Set-ExecutionPolicy -ExecutionPolicy Unrestricted

Import-Module .\Sharphound.ps1

Invoke-BloodHound -CollectionMethod All -OutputDirectory .

