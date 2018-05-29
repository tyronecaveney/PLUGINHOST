# PLUGINHOST

*Disclaimer: the Canvas Plugin Host facilitates the use of VST instruments already installed/authorized on/for your computer. This software **does not** have built-in VST instruments or effects. Canvas **do not**  endorse or accept liability for any VST plugins that have been pirated, or penalties incurred as a result.*


## My "Plugin Host" for Software Development II.


The Plugin Host is a standalone application capable of loading and playing AU/VST/VST3 instruments. It can currently play one plugin instrument at a time and can swap between them. The User Interface design has been iterative, and therefore has changed between the previous assessment and now. Instead of a seperate finder window to choose the plugin, there is now a simple pop-up menu from the home screen - accessed by a right-click. This idea was favoured as it streamlines the process from application initialisation to GUI display. After the user has selected which instrument they would like to use, the GUI automatically opens in a new window - at this point MIDI input and Audio Output connections to and from the plugin are ready.


## Primary Features
1. Simple User Interface
2. AU/VST/VST3 Support
3. Auto-GUI Display 
4. Plug'n Play w/MIDI Controller
5. User-Definable Audio Settings
6. Low-Latency


## Current Bugs/Features To Add
1. **BUG** Some VST GUI's don't show in the Property Panel
2. **BUG** Occassional crashes 
3. **F.t.A** A Master-Volume Slider/Knob
4. **F.t.A** A re-show GUI button incase the GUI is accidently minimised
5. **F.t.A** MIDI Mapping
6. **F.t.A** Revised UI to incorporate Plugin Browser

-------------------------------------------------------------------------------------------------
# USER QUICK-START GUIDE
**1.** To get started with the Plugin Host, **you must first scan your OS for available plugins**:
  - *"Options"* -> *"Edit List of Available Plugins"* (CMD + P)
  - In the, *"Available Plugins"* popup window:
    - *"Options"* -> *"Scan for New or Updated AudioUnit/VST/VST3"*
  - Select the Directory that contains your plugins and press, *"Scan"*
  
**2.** Next, **initialise your audio settings**:
  - *"Options"* -> *"Change the Audio Device Settings"* (CMD + A)
  
  From here you can edit:
- Input/Output Devices
- Input/Output Routing
- MIDI Controller Devices
- Sample Rate
- Buffer Size
   
**3.** Follow on-screen prompts on the main window to select and play your plugins
