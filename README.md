# VirtualDesktop
Originally as a C# command line tool to manage virtual desktops in Windows 10 and Windows 11. This is a fork to use this as a library

**Version 1.11, 2022-11-13**
- renaming for Windows 11 22H2

(look for a powershell version here: https://github.com/MScholtes/PSVirtualDesktop or here: https://www.powershellgallery.com/packages/VirtualDesktop)

**With Windows 11 22H2 Microsoft did change the API (COM GUIDs) for accessing the functions for virtual desktops again. I provide six versions of virtualdesktop.cs now: virtualdesktop11.cs is for Windows 11, virtualdesktop11-21h2.cs for Windows 11 21H2, virtualdesktopserver2022.cs is for Windows Server 2022, virtualdesktop.cs is for Windows 10 1809 to 21H2, virtualdesktop1803.cs is for Windows 10 1803, virtualdesktop1607.cs is for Windows 10 1607 to 1709 and Windows Server 2016. Using Compile.bat all executables will be generated.**

## Requirement
- Visual Studio 2022
- .Net Framework 4.8

## Generate DLL:
Open visual studio solution & build

## Note
- Test with Windows 11 22H2 only
