1) Deleting the "SequencedDropSequences" Folder

    Windows (PowerShell):
       Remove-Item "C:\Program Files (x86)\Steam\steamapps\common\Crab Game\BepInEx\plugins\SequencedDropSequences" -Recurse -Force
    
    Linux:
       rm -r ~/.local/share/Steam/steamapps/common/Crab\ Game/BepInEx/plugins/SequencedDropSequences/



2) Git Cloning the Git Repository

    Windows (PowerShell):
       git clone "https://github.com/lammas321/CrabGameFloatingPlayerPatch.git" C:\Program Files (x86)\Steam\steamapps\common\Crab Game\BepInEx\plugins
    
    Linux:
      git clone "https://github.com/lammas321/CrabGameFloatingPlayerPatch.git" ~/.local/share/Steam/steamapps/common/Crab\ Game/BepInEx/plugins
