1) Deleting the "SequencedDropSequences" Folder

    To delete the "SequencedDropSequences" folder from your Crab Game installation, follow the instructions for your operating system below.
    
    Windows (PowerShell)
    
    Run the Command:
       Remove-Item "C:\Program Files (x86)\Steam\steamapps\common\Crab Game\BepInEx\plugins\SequencedDropSequences" -Recurse -Force
    
    Linux
    
    Run the Command:
       rm -r ~/.local/share/Steam/steamapps/common/Crab\ Game/BepInEx/plugins/SequencedDropSequences/



2) Git Cloning the Git Repository

    To clone the Git repository for the Crab Game Floating Player Patch, follow the instructions for your operating system below.
    
    1. Windows
    
       Run the Command:
          git clone "https://github.com/lammas321/CrabGameFloatingPlayerPatch.git" C:\Program Files (x86)\Steam\steamapps\common\Crab Game\BepInEx\plugins
    
    2. Linux
    
       Run the Command:
         git clone "https://github.com/lammas321/CrabGameFloatingPlayerPatch.git" ~/.local/share/Steam/steamapps/common/Crab\ Game/BepInEx/plugins
    
