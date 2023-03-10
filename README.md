## This is a modified theme based on [catppuccin's theme](https://github.com/catppuccin/stable-diffusion-webui) and incorporating design elements from [canisminor1990's kitchen-theme](https://github.com/canisminor1990/sd-web-ui-kitchen-theme). We are immensely grateful to the authors of both repositories for their excellent work. 


<p align="center">
	<img src="https://github.com/AIEPhoenix/sd-webui-stylish-theme/blob/main/assets/res.png"/>
</p>


## Usage
### Extension (Recommended)
1. Open WebUI
2. Click on the "Extensions" tab 
3. Click on the "Install from URL" subsection 
4. Paste `https://github.com/AIEPhoenix/sd-webui-stylish-theme.git` into the URL spot, and install
5. Go to "Installed" subsection and click "Apply and restart UI"
6. Configure the theme from the "Settings" tab under "Catppuccin Theme", afterwards you must "Apply Settings" and "Reload UI"


## 🙋 FAQ

-	Q: **_"I decided not to use the extennsion, how do I change the accent color?"_**\
	A: Open `user.css` and set the variavble `--accent: var(--{preferred color});`
	
-	Q: **_"The theme isn't being applied???"_**\
	A: Sometimes Web UI doesn't automatically figure out your preferred theme. Try adding `/?__theme=dark` to the url and see if the theme is applied. Below are the steps to make this change persistent on different systems:
	- **Linux / MacOS**: Edit `webui-user.sh` and uncomment and set this variable as `export COMMANDLINE_ARGS="--theme=dark $COMMANDLINE_ARGS"`
	- **Windows**: Edit `webui-user.bat` and set this variable by `set COMMANDLINE_ARGS=--theme=dark`. 
	
	If you are still having trouble then consult the relevant part of the [webui wiki](https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Features#usercss). 
	
-	Q: **_"Why doesn't the theme look like the previews?"_**\
	A: The main UI is constantly being changed upstream, so our previews may not match what the theme will look like for you. Though the previews may be behind, we are frequently updating the themes whenever there is a change in the Web UI repo. Though if you notice a style issue with a recent version of webui, feel free to open an issue on this repo.    
	
-	Q: **_"Why isn't {extension} themed?"_**\
	A: Some extensions use their own style sheets that don't play nice with `user.css`.

## 💝 Thanks to

- [Kettukaa](https://github.com/Kettukaa)
- [catppuccin](https://github.com/catppuccin)
- [canisminor1990](https://github.com/canisminor1990)

&nbsp;

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
