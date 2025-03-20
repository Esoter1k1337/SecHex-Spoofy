# SecHex-Spoofy [1.5.8] [![Github All Releases](https://img.shields.io/github/downloads/SecHex/SecHex-Spoofy/total)]()

Simple HWID-Changer 🔑︎ 
Some Lines of the CLI Version are from @LockBlock-dev



**Windows 11** Version 10.0.22621 Build 22621 ✅                                      
**Windows 10** Version 22H2 Build 19045.2965 ✅

I am currently still learning, and the spoofer is far from being 100% perfect. But I'm doing my best. 


# Functions ⚡
+ **Disk Spoofing** - [18.05.23]                           
    • Retrieves SCSI ports and buses information from the Windows registry.                           
    • Checks if the device type is a disk peripheral.                           
    • Generates random identifiers and serial numbers for the disk peripheral.                                                 
    • Updates the registry values for the disk peripheral with the new identifiers and serial numbers.
                                            
+ **Guid Spoofing** - [18.05.23]                           
    • Generates new GUIDs (Globally Unique Identifiers) for various registry keys.                           
    • Updates the HwProfileGuid, MachineGuid, and MachineId registry values with new GUIDs.                           
    • Generates a random BIOS release date.                           
                                            
+ **PC-name Spoofing** - [18.05.23]                           
    • Spoofs the computer name by updating various registry keys.                           
    • Retrieves the original computer name from the registry.                           
    • Generates a random new computer name.                           
    • Updates the registry values for ComputerName, ActiveComputerName, Hostname, and NV Hostname.                           
                                              
+ **MAC ID Spoofing** - [19.05.23]                           
    • Attempts to spoof the MAC address of network adapters.                           
    • Retrieves network adapters information from the Windows registry.                           
    • Generates a random MAC address.                                                    
    • Updates the registry values for the MAC address with the new spoofed address.                           
    • Disables and enables the local area connection to apply the changes.
                                                                           
+ **Ubisoft cache cleaner** - [19.05.23]                           
    • Cleans the Cache of Ubisoft
                                           
+ **Valorant cache cleaner** - [19.05.23]                           
    • Cleans the Cache of Riot Games
                                         
+ **Installation ID Spoofing** - [26.05.23]
    • Attempts to spoof the Windows ID by changing the MachineGuid registry value.                           
    • Retrieves the current MachineGuid value from the registry.                           
    • Generates a new random spoofed MachineGuid.                           
    • Saves the before and after log information.                           
    • Updates the registry value with the spoofed MachineGuid.
                                                 
+ **Spoof EFI Bootloader** - [26.05.23]                           
    • Opens the registry key for EFI variables.                           
    • Retrieves the current EFI Variable ID from the registry.                           
    • Generates a new random EFI Variable ID.                           
    • Updates the registry value with the new EFI Variable ID.                           
                                                      
+ **Spoof SMBIOS** - [26.05.23]                           
    • Opens the registry key for SMBIOS data.                           
    • Retrieves the current SystemSerialNumber from the registry.                           
    • Generates a new random SystemSerialNumber.                           
    • Updates the registry value with the new SystemSerialNumber.                           
                               
+ **Get all System informations** *[New]* - [27.05.23]                           
    • Get all System informations.
                                 
+ **Registry Checker** *[New]* - [07.06.23]                           
    • Defines an array of registry entries to check.                           
    • Checks if the registry keys specified in the array exist.                           
    • Creates a list of missing registry entries.                           
    • Displays an error message with the missing entries, if any.                           
    • Displays a success message if all registry entries are found.
                                                    
+ **Log System** *[New]* (testing) - [10.06.23]                           
    • Log every Change in a .txt
                          
+ **Backup System** *[New]* (testing) - [13.06.23]                           
    • Create a Backup as .reg
                           
+ **Product ID Spoofing** *[New]* (testing) - [14.06.23]                                                
    • Opens the registry key "SOFTWARE\Microsoft\Windows NT\CurrentVersion" under the LocalMachine hive.                           
    • Retrieves the current value of the "ProductId" registry entry.                           
    • Generates a new random product ID using the RandomIdprid(20) method.                           
    • Sets the registry value of "ProductId" to the new generated product ID.                                                                       

+ **Display Spoofing** *[New]* (testing) - [15.06.23]                           
    • Spoofs display settings by modifying the registry.                          
    • Opens the registry key for display settings.                          
    • Generates a random display ID.                          
    • Updates the registry values for MRU0, MRU1, MRU2, MRU3, and MRU4.                          
                       

+ **SecHex Cleaner** *[New]* (testing) - [28.06.23]                           
    • DNS Flush                          
    • Temp Cleaner                          
    • Windows Logs
    • Win Temp                      
    • TCP Reset                      
    • Chrome Cookies                       
    • Recent Documents                       
    • Reset Connection (fix the mac spoofing issue)                    
    • Trace Cleaner                    
    • Anti-Cheat-Terminator [Fortnite, Valorant, FiveM...]                    
    • Unlink Xbox                    
    • Unlink Discord                              

                          
                          

**Design Update** - 20.05.23

# Milestones 🏆
**5 Stars** - ***EFI*** ✅                             
**10 Stars** - ***SMBIOS***  ✅                                                                 
**20+ Stars** - ***Spoofer with GUI*** ✅       
**50+ Stars** - ***GUI Changes*** ✅                        
**100+ Stars** - ***GUI Changes + Code overhaul and every 10 stars a update!*** ✅                             
**500+ Stars** - ***Kernel Integration*** ❌                       
↳ (Currently, @toto, @Starcharms, and I are working on the Kernel Integration. However, this process takes time. We are not merely adding an DMIEDIT edit executed by the spoofer; instead, we are developing a complete driver that communicates with Spoofy, supporting both Win10 and Win11.)

▰▰▰▰▰▰▰▰▰▰▱▱▱ 75% Finish ❤️                          
            



# GUI & CMD PREVIEW 🏆
[No Updates for the CLI Version!]
![Screenshot 2023-12-11 191951 (1)](https://github.com/SecHex/SecHex-Spoofy/assets/96635023/22ad94a2-f003-49cb-b0ef-fea0160bd093)




# Contributors ❤️
Contributors get a special Role our discord Server. Just create a Ticket and send proof.                                         
Cheers!                                            .gg/SecHex
