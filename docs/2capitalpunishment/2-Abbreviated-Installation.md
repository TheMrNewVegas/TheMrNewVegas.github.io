---
sidebar_position: 2
---
# Installation Guide

:::info
## Requirements

> 170 GB of Free Space, A Nexus Account (Preferably Premium), a Global Steam Installation of Fallout NV w/ All DLC, & Fallout 3 With All DLC (GOG, Steam, Or Epic Games will do fine for Fallout 3 only, but Fallout New Vegas REQUIRES a Steam Global Copy).

> With the introduction of Root builder, other builds of Fallout New Vegas (GOG, Epic, etc) should, in theory, work with the modlist. We have left Steam Global as a copy as this is the only we have tested. Please proceed with caution in regards to these versions

> Make sure you install everything to the root of your drive (Ex: C:/Capital Punishment ; C:/Steam). Protected directories such as your Desktop, Program Files, etc may cause issues.


> Completely delete & reinstall all old installations of Fallout New Vegas/3 including your My Games/FalloutNV & My Games/Fallout 3 folders
:::

:::info
## Tools/Programs You Need


> **[Directx Runtime Libraries](https://www.microsoft.com/en-us/download/details.aspx?id=8109), [Visual C++ Runtime Libraries](https://docs.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170), The [Wabbajack Launcher](https://www.wabbajack.org), & [7-Zip](https://www.7-zip.org/) (Or Winrar)**
:::
## Installing the Games

1.) Install a Fresh Copy of Fallout New Vegas & 3 (English Language Only). **Once installation is finished, launch them once and a popup should appear saying detecting game settings.** 

2.) Set your resolution and other settings to your liking and close the launcher after

## Wabbajack Setup

1.) Launch your installed Wabbajack & go to the Cogwheel at the top right. Log into your Nexus account through here

2A.) If you are installing the list from Nexus, unzip the folder you downloaded. Then, inside wabbajack, go to "Install From Disk". Find the .wabba file you just unzipped and select it

2B.) If you are installing the list through Wabbajack's Gallery, go to "Browse Modlists" then search Capital Punishment. Click the download icon,

3.) Set your modlist installation location to wherever your would like it (IE: C:/Modlists/Capital Punishment) & it will automatically create the downloads directory for you. Press the play button when you are done and installation will begin

## Installing TTW

1.) Download and unzip the [TTW 3.3.2 Installer](https://taleoftwowastelands.com/dl). Then create a new folder called `[NoDelete] Tale of Two Wastelands`

> The `[No Delete]` tag has recently been having issues. PLEASE BACK UP YOUR TALE OF TWO WASTELANDS OUTSIDE OF YOUR CAPITAL PUNISHMENT FOLDER

2.) Make sure Steam is fully closed, then run the Tale of Two Wastelands Launcher. Set the paths for where your `Fallout 3`, `Fallout NV`, & `[NoDelete] Tale of Two Wastelands` main directories are located, then press install (This takes a while)

3.) After the TTW Launcher successfully completes the installation, zip up the `[NoDelete] Tale of Two Wastelands` folder. You may now safely delete Fallout 3 from your computer.

4.) When Wabbajack successfully completes installing the modlist, drag this 7zip into your `Capital Punishment/Downloads` directory. Go back to your main `Capital Punishment directory`, then open up `Mod Organizer 2`

5.) For each profile you open, a dialog box will popup regarding the read only flag. **ALWAYS** select 'Clear the Read Only Flag'

6.) On the right hand side, sort by Filetime until you see your `[NoDelete] Tale of Two Wastelands.7z` at the top. Drag and drop this to the top of the lefthand separator `PUT TALE OF TWO WASTELANDS HERE`

## Preconfigured Save Setup (RECOMMENDED BUT OPTIONAL)

1.) Go to Capital Punishment/Game Folder Files, copy the two appropriate Save Files for the profile you plan to use (Casual or Hardcore), then paste them into the appropriate profile folder you plan to use **(HC = Hardcore)**

- **At the End Of the Saves Look for the Markers For Casual/Hardcore**

![image](https://github.com/TheMrNewVegas/TheMrNewVegas.github.io/assets/112358568/96f62de7-5f55-485d-bb73-4a91dc69a457)

- **Copy the Two Saves Which Correlate & Paste Them Into `Capital Punishment/Profiles/[The Profile Of Your Choice]/saves`**

![image](https://github.com/TheMrNewVegas/TheMrNewVegas.github.io/assets/112358568/d4984034-f544-4a58-a447-d4a43eaf122f)


## Final Setup

1.) Make sure in MO2 that all of the application directories in the dropdown match the locations on your system. If they do not, change them so that they do.

2.) At the top left of MO2, go to `Tools/Settings/Paths/Managed Game`. Make sure that this is set to where your vanilla Fallout New Vegas installation

> This will not override your New Vegas installation; We now use Root Builder which allows us

3.) Go to the dropdown menu at the top right of MO2 and select "Explore Virtual Folder". From this menu, find and double click `FNVpatch.exe`. Then close the dialog box that pops up as well as the virtual folder.

![image](https://github.com/TheMrNewVegas/TheMrNewVegas.github.io/assets/112358568/46fd1a50-c21b-4f8b-89b7-15bdd4aa2d75)

4.) You can now select "Capital Punishment TTW" from the right hand dropdown and press play.

## Switching to Casual or Another Profile

- Depending on the experience/performance choices you would like to make when playing this list, you may want to select a different list.

1.) In MO2, select the dropdown menu at the top. From there, choose the profile you would like to play.

![image](https://github.com/TheMrNewVegas/TheMrNewVegas.github.io/assets/112358568/ede43e0d-26b9-477b-bc05-cd628e66a7f3)

2.) After doing that, press Run in MO2 with Capital Punishment TTW selected and the list you have chosen should boot up.

![image](https://github.com/TheMrNewVegas/TheMrNewVegas.github.io/assets/112358568/f5c647a2-f0ed-4e6e-933e-74320d85d4ea)

- For a list of what each profile does/is about, you can check out our profiles page on here on the wiki!


## Optional Post Installation Steps

- You can choose to delete the contents of the `Capital Punishment/Downloads` folder to free up space, but when you update you will have to fully reinstall everything again.
- Past this you may check out our Optional Installation Steps later in this documentation. These involve steps for download NVR, Reshade, and much more!
