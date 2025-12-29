# Themes installation guide

1. [Windhawk](#Windhawk)
2. [Komorebi](#Komorebi)
3. [YASB](#YASB)
4. [Terminal](#Terminal)
5. [Cava](#Cava)
6. [Flow Launcher](#FlowLauncher)

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
>
```
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```
3. Install Komorebi via [Scoop](https://lgug2z.github.io/komorebi/installation.html#scoop).
4. After installation take this part from my theme config (Komorebi folder) for appearance settings and paste it in your Komorebi JSON (C:\Users\USERNAME\Komorebi.json):
> <img width="848" height="1059" alt="image" src="https://github.com/user-attachments/assets/ee4234e7-839d-4e73-8ddd-a7c7b286f587" />
5. Additional options and settings you can find on [Komorebi Wiki](https://lgug2z.github.io/komorebi/installation.html)


## <a id="YASB">YASB</a>
1. Install YASB using Scoop:
>
```
scoop bucket add extras
scoop install extras/yasb
```
2. Download YASB theme files from my repo (YASB folder) and paste them in C:\Users\USERNAME\.config\yasb with replace.
3. Reload YASB after replacing files if it was running.


## <a id="Terminal">Terminal</a>
1. Install PowerShell 7:
>
```
winget install --id Microsoft.PowerShell --source winget
```
2. Open PowerShell 7 -> Open settings -> Select PowerShell profile and open settings JSON:
> <img width="1428" height="1077" alt="image" src="https://github.com/user-attachments/assets/ce1e5aff-b4c2-4820-829b-a73526f90592" />
3. Open my "settings.json" from Github and copy colorschemes. Paste it to your PowerShell "settings.json:
> <img width="813" height="1726" alt="image" src="https://github.com/user-attachments/assets/409ebfe1-01d4-4d65-8f5c-90071471599d" />
4. Go to "Startup settings and set Focus mode:
> <img width="1421" height="1068" alt="image" src="https://github.com/user-attachments/assets/95154298-fa04-4fa0-a811-dee4fed55493" />
5. Go to your PowerShell 7 profile -> Appearance pick colorscheme and set transparency settings:
> <img width="1422" height="1070" alt="image" src="https://github.com/user-attachments/assets/a9a6d8a4-cc20-46d5-a1aa-79baf83c0c68" />
> <img width="1419" height="1071" alt="image" src="https://github.com/user-attachments/assets/d48d7f67-8f5e-4327-b18c-e455ff802c8d" />
> <img width="1431" height="1080" alt="image" src="https://github.com/user-attachments/assets/54edaffd-9f2f-4276-ac19-beec72ccf5f3" />
6. Save settings.

Other way - you can just fully replace "settings.json" with my config but save your original path to your pwsh.exe (PowerShell 7 executable file) and replace my path here:
> <img width="721" height="273" alt="image" src="https://github.com/user-attachments/assets/cd6fbf58-2010-4cba-9a3e-4fdd532639bb" />

## <a id="Cava">Cava</a>
1. Install Cava:
>
```
winget install karlstav.cava
```
2. Download my config from theme repo.
3. Go to C:\Users\USERNAME\.config\cava and replace config with mine


## <a id="FlowLauncher">Flow Launcher</a>


