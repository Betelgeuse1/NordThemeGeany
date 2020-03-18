# NordThemeGeany
A homemade version of the [Nord theme][nordlink] for geany.

## Installation
Simply run the following command to only install the editor theme.  
`$ ./nord`

If you want to go full Nord style, you can install the GTK theme too.  
`$ ./nord --gtk`  

Running this command will save your old geany.css file as old_geany.css,  
inside your geany config folder if you ever want to go back to normal.

## Appearance  
* ### Nord theme
	Some example of how the theme looks with different languages.  
	
	##### C  
	![Nord theme image C][nordconfC]
	
	---  
	##### Python  
	![Nord theme image Python][nordconfP]
	
	---  
	##### HTML   
	![Nord theme image HTML][nordconfH]
	
	---  
	##### Markdown  
	![Nord theme image Markdown][nordconfM]
	
	---  
	##### CSS  
	![Nord theme image CSS][nordconfCS]
	
* #### GTK theme
	Main window  
	![GTK main window appearance][gtknord]  
	
	---  
	Preferences window  
	![GTK menu window appearance][gtknordmenu]  
	
	---  
	File upload window  
	![GTK file upload window appearance][gtknordfile]

### TO-DOs
- [x] Implement the basic Nord Theme, following the official [colors & palettes][caplink]
- [x] Implement the basic GTK theme
- [ ] Finish the GTK theme completely
- [ ] Try to make the theme more vscode like

[nordlink]: https://www.nordtheme.com/
[caplink]: https://www.nordtheme.com/docs/colors-and-palettes

[nordconfC]: images/nordconfC.png
[nordconfP]: images/nordconfP.png
[nordconfH]: images/nordconfH.png
[nordconfM]: images/nordconfM.png
[nordconfCS]: images/nordconfCS.png

[gtknord]: images/gtknordmain.png
[gtknordmenu]: images/gtknordmenu.png
[gtknordfile]: images/gtknordfile.png
