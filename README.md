# Themes installation guide

1. [Windhawk](#Windhawk)
2. [Komorebi](#Komorebi)

## <a id="Windhawk">Windhawk</a>
For basic customisation (Default Windows taskbar, startmenu, notification center) you will need Windhawk.
> Only with Windhawk and wallpaper you can get this result:
# ![Only with Windhawk and wallpaper you can get this result](https://github.com/user-attachments/assets/b70959e8-fdbd-4a31-9ed6-7ab65da481db)
1. Install Windhawk from [official website](https://windhawk.net/) or [Github](https://github.com/ramensoftware/windhawk).
2. Open a Windhawk folder in the theme repo:
> <img width="1135" height="697" alt="image" src="https://github.com/user-attachments/assets/5659230c-4bd6-4fff-aaf5-c15c4c34033a" />
Here is a JSON files with names of Windhawk mods you will need:
> <img width="567" height="472" alt="image" src="https://github.com/user-attachments/assets/5b4ab8cf-22e3-4122-a54e-d2a03534f3c4" />
3. Install requared Windhawk mods:
> <img width="1783" height="1233" alt="image" src="https://github.com/user-attachments/assets/ca95139e-b6fc-4f20-a9da-4c2a4e1e10f6" />
4. Open one of the JSON's from theme repo and copy all text:
> <img width="3556" height="415" alt="image" src="https://github.com/user-attachments/assets/014c254e-0285-4291-8e79-ff903632274b" />
5. Open Windhawk mod which JSON you copied, go to "Advanced settings" clear current text and paste it here with right mouse button (Windhawk can be tricky sometimes with shortcuts):
> <img width="1467" height="1160" alt="image" src="https://github.com/user-attachments/assets/622053e2-192a-4207-bb90-eea8a3435d91" />
6. Click "Save" button and you are done here. Repeat this steps for other mods.



## <a id="Komorebi">Komorebi</a>
1. Install [required fonts](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.4.0/JetBrainsMono.zip) first. Extract → select all font files → right-click → Install.
2. Install Scoop. Open a PowerShell terminal (version 5.1 or later) and from the PS C:\> prompt, run:
`Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression`
