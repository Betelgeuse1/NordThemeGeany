# NordThemeGeany
A homemade version of the [Nord theme][nordlink] for geany.

## Installation
Simply run the following command to install the [editor theme](#nord-theme).  
```sh
$ ./nord
```

After running the command, you just need to change your theme in geany  
![Changing theme explanation][geanythemechange]  

If you want to go full Nord style, you can install the [GTK theme](#gtk-theme) too.  
```sh
$ ./nord --gtk
```  

Running this command will save your previous geany.css file as old_geany.css inside the geany config folder,
if you ever feel like going back to normal, or trying other themes.

## Appearance  
* ### Nord theme
	Some examples of how the theme looks with different programming languages.  
	
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
	A really big pcture of what the main window looks like with the GTK theme enabled
	##### Main window  
	![GTK main window appearance][gtknord]  
	
	---  
	##### Preferences window  
	![GTK menu window appearance][gtknordmenu]  
	
	---  
	##### File upload window  
	![GTK file upload window appearance][gtknordfile]

### TO-DOs
- [x] Implement the basic Nord Theme, following the official [colors & palettes][caplink]
- [x] Implement the basic GTK theme
- [ ] Polish the GTK theme look
- [ ] Try to make the theme more adaptative to languages

[nordlink]: https://www.nordtheme.com/
[caplink]: https://www.nordtheme.com/docs/colors-and-palettes

[geanythemechange]: images/geanythemechange.png

[nordconfC]: images/nordconfC.png
[nordconfP]: images/nordconfP.png
[nordconfH]: images/nordconfH.png
[nordconfM]: images/nordconfM.png
[nordconfCS]: images/nordconfCS.png

[gtknord]: images/gtknordmain.png
[gtknordmenu]: images/gtknordmenu.png
[gtknordfile]: images/gtknordfile.png
