1) Deleting the "SequencedDropSequences" Folder

    Windows (PowerShell):
    
       Remove-Item "C:\Program Files (x86)\Steam\steamapps\common\Crab Game\BepInEx\plugins\SequencedDropSequences" -Recurse -Force

    
    Linux:
       
       rm -rf "$HOME/.local/share/Steam/steamapps/common/Crab\ Game/BepInEx/plugins/SequencedDropSequences"



2) Git Cloning the Git Repository

    Windows (PowerShell):

       git clone "https://github.com/SlashandDash/SequencedDropSequences.git" C:\Program Files (x86)\Steam\steamapps\common\Crab Game\BepInEx\plugins\SequencedDropSequences
    

    Linux:

       git clone "https://github.com/SlashandDash/SequencedDropSequences.git" "$HOME/share/Steam/steamapps/common/Crab Game/BepInEx/plugins/SequencedDropSequences"
