# Animated-Ready-Action
A little automated readied action ring around a token for Foundry VTT.

I made this up for my group to use as a visual indicator they are holding a readied action. The feature uses the following modules: Sequencer (applying and removing the animation), DAE (to appy the status effect, execute the special expiries and call on the macro), MidiQOL (special expiries) and Times-up (duration expiries).
Included is an Ready-Action item json for the Ready Action feature, and an accompanying Ready-Action-VFX macro that gets called on, and my Ready status/macro/item icon (point the DAE, Macro and Item icon image browsers to the folder you import the icon to). Recently Updated to add the new Ready Spell feature!



https://github.com/user-attachments/assets/b00793ef-8acf-49b1-b080-167873f4b239



Macro:

![image](https://github.com/user-attachments/assets/ee754ecb-877e-48cc-b81b-2669bbf5bf3f)

Macro icon:

![image](https://github.com/user-attachments/assets/cf43e60a-d3b7-416d-9d63-6e5e72f7ffab)

DAE status icon:

![image](https://github.com/user-attachments/assets/5e290c6a-0f93-4a08-95b7-bd598ddb1613)

## Automation:
Use the feature directly from your character sheet to apply to your character's token. The status icon and animated webm are removed automatically at the start of your characters next turn and/or upon the character's use of an action.

## Required Modules:
Sequencer
DAE
MidiQOL
Times-up

## How to install
- Create a blank macro and a blank item.
- Right click the blank macro and Import the fvtt-Macro-ready-action-vfx.json.
- Right click the blank item and Import the fvtt-Item-ready-action.json.
- Upload both the readyW.png icon and animated Readied_ActionWBCCW_1.webm to a folder of your choice.
- Modify the Macro, DAE and Feature's respective icon images to point to the uploaded icon location.
- Modify the Macro to point to the uploaded webm file location.
- *NOTE* Follow the same steps for the Ready Spell feature, noting the names of the files are different respectively.
- Enjoy!

### Made for Foundry VTT v9 (verified v12).
