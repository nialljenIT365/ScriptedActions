# ScriptedActions

| ID  | Script Name | Description |
| 1 | 1. Install English United Kingdom language packs |--------------|
| 2 | 2. Set English United Kingdom default OS language  |--------------|
| 3 | 3. Remove Appx Packages  |--------------|
| 4 | 4. Remove Windows Mail App  |--------------|
| 5 | 5. Disable TLS 1.0 1.1  | Disable TLS 1.0 & 1.1|
| 6 | 6. Enable Windows optimizations for AVD  | Enable Windows optimizations for AVD|
| 7 | 7. Install exe from Azure File Share  |-----------------|
| 8 | 8. Install msi from Azure File Share  |-----------------|
| 9 | 9. install Systrack from Azure File Share  |-----------------|
| 10 | 10. install Symantec WSS Agent and set winhttp proxy  |-----------------|
| 11 | 11. install virtualization-based security (VBS)  |Required for AVD Hibernation with Secure Boot/vTPM|
| 12 | 12. Enable Internet Explorer 11 |-----------------|
| 13 | 13. Disable IPv6  |-----------------|
| 14 | 13. Enable IPv6  |-----------------|
| 15 | 14. Sideload Company Portal | This is a workaround to troubleshoot inTune enrollment|
| 16 | 15. Set Paging File Single Session  | Set paging file to C drive - necessary for AVD Hibernation|
| 17 | 17. Disable Printer Redirection  |Sets the fDisableCpm registry key for AVD|
| 18 | 18. Enable Printer Redirection  |Sets the fDisableCpm registry key for AVD|
| 19 | 19. Install RSAT Active Directory DS-LDS Tools  |Enable ADDS Tools|
| 20 | 20. Set registry BlockNonAdminUserInstallSet  | Allow appx to install in restricted environments|
| 21 | 21. Reset local administrator password   |-----------------|
| 22 | 22. Remove AVD Sessionhost from Current HostPool  |Note should be executed as a Run book or Azure CLI/Powershell|
| 23 | 23. Rejoin AVD Sessionhost to Target Hostpool  |Note should be executed directly on Session host after Removal Script has completed|
| 24 | 24. Install appx/msix from Azure File Share  |-----------------|
| 25 | 25. Disable RDP Shortpath  |Three registy settings to explicitly block RDP SHortpath for AVD|
| 26 | 26. Set TLS for 1.2  |Requirement for VTSO to work|
| 27 | 27. Enable OneDrive Files on Demand  |-----------------|
| 28 | 28. HostPool Migration Part 1 (Run Book)  |Retrieves Hostpool Token for future use|
| 28 | 28. HostPool Migration Part 2 (Scripted Action)  |Rejoin AVD Sessionhost to Target Hostpool, note should remove VM from previous hostpool before using|
| 29 | 29. Add Azure Tag  |Run Book|
| 30 | 30. Remove Azure Tag  |Run Book|
| 28 | 28. Remove AppX Packages Outlook New  |-----------------|
