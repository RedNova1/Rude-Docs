# Prerequisites

**Install these before going forward**
- [Vanity Reprised](https://github.com/eternalUnion/VanityReprised/releases/tag/1.1.0): Rude Level Editor Project generator
- [Angry Level Loader](https://thunderstore.io/c/ultrakill/p/EternalsTeam/AngryLevelLoader/): To load levels created using the Rude Level Editor.
- [Unity Hub](https://unity.com/download): Required to load up Unity
- [Unity 2019.4.40.f1 (LTS)](https://unity.com/releases/editor/whats-new/2019.4.40): Used to open the Rude Level Editor Project and create levels.
- [DotNet SDK 8.0](https://dotnet.microsoft.com/en-us/download/dotnet/8.0): Required for Vanity Reprised
- **PC Specs**:
    - **Operating system version:**	Windows 7 (SP1+), Windows 10 and Windows 11, 64-bit versions only.
    - **CPU:** X64 architecture with SSE2 instruction set support	
    - **Graphics API:** DX10, DX11, and DX12-capable GPUs	
    - **Additional requirements:** Hardware vendor officially supported drivers	

> [!IMPORTANT]
> Unity, along with the Rude Level Editor requires a significant portion of disk space to function properly. We suggest using an SSD with `~7-10gb` of space for the smoothest experience.

---
## Installing Unity

The Rude Level Editor is a [Unity](https://unity.com) project which is a modified version of the project Ultrakill was created on. The project contains many [prefabs](https://docs.unity3d.com/2019.4/Documentation/Manual/Prefabs.html), and [scripts](https://docs.unity3d.com/Manual/ScriptingSection.html) which allow you to create a custom level without having much programming knowledge.

To install unity go to [Install Unity Hub](https://unity.com/download).

After Unity Hub is installed, download [Unity 2019.4.40](https://unity.com/releases/editor/whats-new/2019.4.40#release-notes) 

---
# Generating Project

Download `VanityReprised-1.1.0.zip` from [Vanity Reprised](https://github.com/eternalUnion/VanityReprised/releases/tag/1.1.0)

Extract it and run `VanityReprised/AssetRipper.GUI.Free.exe` to open the Splash Screen

Click on `Open ULTRAKILL Folder` and open the **Game Folder(The one containing ULTRAKILL.exe**
![Installation Path](/Installation/InstallPath.png)

**Don't be alarmed if there are any errors, as long as it says `Finished processing assets` at the end.**

Once Vanity Reprised is done processing assets, click `Generate RUDE project` on the Splash Screen.

When it prompts you for a folder to write to, create a new folder somewhere that you'll remember.
**It's ill advised to use your game folder for this.**

You'll know when this step is done because it'll say `Finished post-export`.

Open up Unity Hub and click `Add`, and navigate to the project folder. **IT IS VERY IMPORTANT YOU SELECT THE RIGHT FOLDER. Select the Folder containing the Assets folder in it.**
![ProjectExample](/Installation/ProjectPath.png)

Wait for unity to import everything. This could take anywhere from 30 minutes to multiple hours. Don't worry if it doesn't show up in the taskbar.

If you do want to verify if Unity is running, check Task Manager.
![TaskManager Screenshot](/Installation/TskMng.png)

If you get dialogue about a broken Window Layout, Load the Default Layout.

If the installation worked correctly, you should get a popup saying `Welcome to Rude Level Editor` and/or have a tab at the top titled `RUDE`.

To continue on to make your first level, go to [Creating Levels](/Setup/Creating-Levels.md) Next.

---
*Page Created by: RedNova (With adapted writings from LUKA)*
