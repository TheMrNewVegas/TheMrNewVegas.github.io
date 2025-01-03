---
layout: default
title: Installation Guide
nav_order: 2
description: Path of the Incarnate Installation Guide
---

:::info
## **Requirements:**
- ~60GB of space, 20GB from downloads can be deleted after installation is complete 
- A legal copy of Morrowind GOTY from Steam or GOG
- Wabbajack **(It can be found [here](https://github.com/wabbajack-tools/wabbajack/releases/latest/download/Wabbajack.exe))**
- Visual C++ **(It can be found [here](https://aka.ms/vs/17/release/vc_redist.x64.exe))**
- OpenMW Development Build **(It can be found [here](https://gitlab.com/OpenMW/openmw/-/jobs/artifacts/master/raw/OpenMW_MSVC2022_64_RelWithDebInfo_master.zip?job=Windows_MSBuild_RelWithDebInfo))**
- A Nexus account **(Premium recommended; drastically increases install speed)**
:::

# **Installation Guide**

### 1.) Install or Reinstall Morrowind GOTY

- If a copy has already been installed, the game can be uninstalled, ini's deleted in User/Documents/My Games/Morrowind, and then reinstalled like normal through Steam or GOG.

- Run the game at least once to the main menu to generate the required fresh ini's.

### 2.) Install OpenMW Development Build 

- If you haven't yet, download the required OpenMW Development Build [here](https://gitlab.com/OpenMW/openmw/-/jobs/artifacts/master/raw/OpenMW_MSVC2022_64_RelWithDebInfo_master.zip?job=Windows_MSBuild_RelWithDebInfo).

- Unzip the OpenMW Development Build into the folder you would like it to be installed (I.E. C:/Games/OpenMW .49)

- Inside the folder, launch openmw-wizard.exe and follow the steps, **unchecking "Import Bitmap Fonts Setup from Morrowind"** at the Import Settings stage. 

### 3.) Wabbajack Setup

- Launch your installed Wabbajack & go to the Cogwheel at the top right. Log into your Nexus account through here.

### 4.) Installing the Modlist

- If you are installing the list through Wabbajack’s Gallery, go to “Browse Modlists” then search Path of the Incarnate. Click the download icon.

- If you are installing the list using a downloaded .wabba file, then click on "Install from Disk" and set the Target Modlist path to your file.

- Set your modlist installation location to wherever your would like it (IE: C:/Modlists/POTI) & it will automatically create the downloads directory for you. Press the play button when you are done and installation will begin.

### 6.) Mod Organizer 2 Setup 

- After Wabbajack installation is done, make sure in Mod Organizer that the OpenMW application directories in the dropdown menu match the locations on your system. If they do not, change them so that they do.

- Launch ModOrganizer.exe from your POTI folder, navigate to the dropdown menu at the top right, select it, then select "Edit".

- Set the binary path for "Path of the Incarnate" to openmw.exe, and the OpenMW Launcher to OpenMW-Launcher.exe, both of which can be found in your chosen OpenMW Development Build installation folder. 

### 7.) Time to Play

- You can now select “Path of the Incarnate” from the right hand dropdown in MO2 and press play.

### 8.) Updating the Modlist

- Updating Path of the Incarnate is about as simple as repeating steps 4.) through 6.) of the Installation Guide using the same install paths you chose before.

:::danger
- **Important:** Before updating, back up your saves or they **will** be lost. Saves can be located in your POTI folder in "profiles/Path of the Incarnate/openmw".

- Once the update process has finished, you may place your saves back in their appropriate location.
:::

### 9.) Uninstalling the Modlist

- To uninstall Path of the Incarnate, delete your POTI folder.


