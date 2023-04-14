The better way to apply changes:
1. Use git bash on computer 
2. From git get into the main directory (where this file is actually)
3. Enter 'code .' to open the whole repository in Visual Code
4. After complete editing all files use git to push it to Github
5. Add all changes to git log by 'git add .'
6. Commit changes with message 'git commit -m "some message"'
7. Push changes to GitHub by 'git push'
8. In the GitHub repository open Actions tab to see progress of the build workflow
9. Once the build successfully completed inside the firmware.zip file can be found
10. Inside the zip file there are 2 UF2 files for each half of the keyboard (in case of split keyboard)
11. To get into bootloader mode on the nRf52 (Nice!nano, XLE BLE) boards - connect to computer via USB and double-press on the reset button
12. In the bootloader mode the MicroComputingUnit board will appear in Windows as a files drive
13. Copy the UF2 file of the respective keyboard side to that drive. The board will reboot itself
14. We are done!

Enjoy!