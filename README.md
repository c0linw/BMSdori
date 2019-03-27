µBMSC
=====
µBMSC is a modified version of iBMSC to add features and clean up the iBMSC code, fix bugs and so on.
See README.md.old for original iBMSC README file.

**BMSdori**
=====
* IMPLEMENTED:
  * Note colors set based on known Bandori note labels.
  * Sliderbodies implemented for Bandori-style cross-lane slides.
  * LN drawing functions modified to support colored notes.
* TODO:
  * Fix offscreen LN/slide rendering
  * Create blank file with WAV labels preset for Bandori charts
	  * The more I test, the more I realize how badly I need this feature
  
* I don't even know how to use the BMS previewers myself, so I'll figure that out later. Would be cool to create a custom previewer using Burrito's code for bandorichart.

* NT (NoteTool) style input *can* be used for Bandori charting, but it is not recommended.
	BMSE style is better because it allows input of different LN start/end notes
	
Changes
=====
* Out of the box OGG previews
  * Seeks for WAV if OGG doesn't exist, and viceversa
* Bugfixes
  * BMSE clipboard input fixed
* Additions
  * Landmine support (Shift + Ctrl + Click)
  * Several new encodings (EUC-KR, Shift-JIS)
  * Go To Measure (Ctrl+G)
  * Mouse Row/Column Highlight
  * Ctrl+Scroll wheel changes zoom level
  * Huge BPM support (10e12)
  * UI improvements
  * **Time select mode** Convert Area to Stop 
  * **Select Mode** Select notes with labels on screen, all notes with labels (Shift+Ctrl+Click, Shift+Ctrl+A)
  * Non-locale dependant number output (No more commas instead of periods)
  * **Write mode** Autowav Increase functionality 
  * **dtinth** Move and Deselect (Shift+Number)
  * **NS-Kazuki** #SCROLL Support
* Development
  * Codebase reorganized for developers


Check appveyor for automated builds.
[![Build status](https://ci.appveyor.com/api/projects/status/m7iygj9sje2yqf43?svg=true)](https://ci.appveyor.com/project/zardoru/ibmsc)
