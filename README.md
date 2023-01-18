# winstuff

<details><summary><h2>:computer: Chris Titus Tech’s Windows Utility</h2><br/>
  
*Streamline installs, debloat with tweaks, troubleshoot with config, and fix Windows updates*</summary>

<p>
https://github.com/ChrisTitusTech/winutil

Run one of these:
  
```powershell
irm christitus.com/win | iex
```

```powershell
iwr -useb https://christitus.com/win | iex
```

```powershell
[Net.ServicePointManager]::SecurityProtocol=[Net.SecurityProtocolType]::Tls12;iex(New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/ChrisTitusTech/winutil/main/winutil.ps1')
```

---or---

Make a .bat file (Chris Titus Tech's Windows Utility.bat):
  
```powershell
Powershell.exe [Net.ServicePointManager]::SecurityProtocol=[Net.SecurityProtocolType]::Tls12;iex(New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/ChrisTitusTech/winutil/main/winutil.ps1')
```

Run as Admin

Select Tweaks → Desktop → Run Tweaks

</p>
</details><hr/>

<details><summary><h2>:computer: TCP Optimizer</h2><br/>

*Interface for tuning and optimizing your Internet connection*</summary>

<p>
https://www.speedguide.net/files/TCPOptimizer.exe

1. Download & install<br/>
2. www.speedtest.net → go<br/>
3. Run as admin<br/>
4. File → Backup current settings → Save<br/>
5. Drag your connection speed to 100+ Mbps (Or your Max ISP download speed)<br/>
6. Make sure your correct NIC is selected<br/>
7. Advanced Settings tab → Optimal → Apply changes → Ok → No<br/>
8. After you apply changes, select Custom & set:<br/>
  a. SystemResponsiveness 0<br/>
  b. TcpAckFrequency 1<br/>
  c. TCPNoDelay 1<br/>
  d. TcpDelAckTicks 0<br/>
9. Apply changes<br/>
10. Reboot<br/>
11. Give it a few to let windows load all the background stuff<br/>
12. www.speedtest.net → go

</p>
</details><hr/>

<details><summary><h2>:computer: Process Lasso</h2><br/>
  
*Real-Time CPU Optimization and Automation*</summary>

<p>
https://dl.bitsum.com/files/processlassosetup64.exe

Download & install
1. Main → Enable ProBalance, IdleSaver, & Performance<br/>
2. Options → CPU → ProBalance<br/>
3. Options → Power → Performance Mode → Change Power Profile when Engaged<br/>
4. Options → Power → Performance Mode → Select power profile → Bitsum Highest Performance<br/>
5. Options → Power → Performance Mode → Enable Automatic Detection (e.g. Steam)<br/>
6. Options → Power → Performance Mode → Disable IdleSaver whille Performance Mode Engaged<br/>
7. Options → Power → Performance Mode → Start Process Lasso with Power Profile → Bitsum Highest Performance<br/>
8. Options → Power → Performance Mode → IdleSaver → Switch to this power profile: → AMD Ryzen™ Balanced [-OR-] Balanced<br/>

</p>
</details><hr/>

<details><summary><h2>:computer: FanControl</h2><br/>

*Focused and highly customizable fan controlling software for Windows*</summary>

<p>
https://github.com/Rem0o/FanControl.Releases

#### Plugins

Support for HWInfo sensors using the "Reporting to Gadget" feature

https://github.com/Rem0o/FanControl.HWInfo

Support for GPU-Z sensors using its shared memory feature

https://github.com/vision57/FanControl.GPU-Z


</p>
</details><hr/>

<details><summary><h2>:memo: NVIDIA Control Panel</h2><br/>

*NVIDIA Video Card Performance Settings*</summary>

#### NVIDIA CONTROL PANEL<br/>
#### MANAGE 3D SETTINGS<br/>
Image Scaling: ..........................................................Off<br/>
Ambient Occlusion: ....................................................Off<br/>
Anisotropic filtering: ...................................................Off<br/>
Antialiasing – FXAA: ...................................................Off<br/>
Antialiasing – Gamma correction: .................................Off<br/>
Antialiasing – Mode: ...................................................Off<br/>
Antialiasing – Setting: ................................................None<br/>
Antialiasing – Transparency: ........................................Off<br/>
Background Application Max Frame Rate: ......................Off<br/>
CUDA – GPUs: ...........................................................All<br/>
DSR – Factors: ..........................................................2.00x (native resolution)<br/>
DSR – Smoothness: ...................................................33%<br/>
Low Latency Mode: .....................................................Off<br/>
Max Frame Rate: .......................................................Off<br/>
Multi-Frame Sampled AA (MFAA) ..................................Off<br/>
OpenGL rendering GPU: ..............................................NVIDIA GeForce RTX ... (Pick your card)<br/>
Power management mode: ..........................................Prefer Maximum Performance<br/>
Preferred refresh rate (Your monitor): ..........................Highest available<br/>
Shader Cache Size: ....................................................5 GB<br/>
Texture filtering – Anisotropic sample option: ................On<br/>
Texture filtering – Negative LOD bias: ..........................Allow<br/>
Texture filtering – Quality: ..........................................High Performance<br/>
Texture filtering – Trilinear optimization: .......................On<br/>
Threaded optimization: ...............................................On<br/>
Triple buffering: .........................................................Off<br/>
Vertical sync:.............................................................Off<br/>
Virtual Reality pre-rendered frames: .............................1<br/>
Virtual Reality – Variable Rate Super Sampling: .............Off<br/>

#### CHANGE RESOLUTION<br/>
Refresh rate: .............................................................(Your monitor's max)<br/>
Use NVIDIA color settings:<br/>
Highest 32<br/>
YcbCr422<br/>
10 bpc ......................................................................(Based on monitor max res)<br/>
Limited<br/>

#### ADJUST DESKTOP SIZE AND POSITION<br/>
Aspect ratio<br/>
Perform scaling on: ....................................................Display<br/>

</p>
</details><hr/>

<details><summary><h2>:sound: NVIDIA Broadcast</h2><br/>

*AI-enhanced voice and video*</summary>

<p>

https://www.nvidia.com/en-us/geforce/broadcasting/broadcast-app/

</p>
</details><hr/>

<details><summary><h2>:sound: Voicemeeter Potato</h2><br/>

*Advanced virtual audio mixer*</summary>

<p>
https://vb-audio.com/Voicemeeter/potato.htm

#### Virtual Audio Cables

https://vb-audio.com/Cable/index.htm

#### TROUBLESHOOTING
==============
  
Bad icon or bad pin name are collateral effects of a bad installation or a previous bad de-installation process. To solve this problem:

1. Uninstall Voicemeeter + REBOOT

2. Check there are no remaining devices in Windows Device Manager , if present, uninstall manually as explained in this topic: https://forum.vb-audio.com/viewtopic.php?f=7&t=688

3. Uninstall Voicemeeter + REBOOT

</p>
</details><hr/>

<details><summary><h2>:movie_camera: OBS (Open Broadcaster Software)</h2><br/>

*Free and open source software for video recording and live streaming*</summary>

<p>

https://obsproject.com

#### Plugins

OBS: https://obsproject.com/forum/resources/categories/obs-studio-plugins.6/

StreamElements OBSLive (SE.Live): https://streamelements.com/obslive

StreamFX: https://obsproject.com/forum/resources/streamfx-for-obs%C2%AE-studio.578/

RTMP-Services: https://obsproject.com/forum/resources/multiple-rtmp-outputs-plugin.964/

</p>
</details><hr/>


<details><summary><h2>:space_invader: Driver booster</h2><br/>

*Windows driver updater*</summary>

<p>

https://www.iobit.com/en/driver-booster.php

Get Giveaway License Key from YouTube<br/>
Block: C:\Program Files (x86)\IObit\Driver Booster\xx.x.x\Pub\*.exe

</p>
</details><hr/>

<details><summary><h2>:video_game: Raw Accel</h2><br/>

*Windows mouse driver that enables acceleration of mouse input in the raw input stream*</summary>

<p>
https://github.com/a1xd/rawaccel

1. Install Raw Accel:
Place the folder in C:\Program Files<br/>
Run installer.exe<br/>
Reboot<br/>

2. Make a .bat file (RawAccel.bat):

```
@echo off
echo Starting up the Raw Accel . . .
start "" "C:\Program Files\RawAccel\writer.exe" "C:\Program Files\RawAccel\settings.json"
```

3. Press WIN+R<br/>
Type:
  
```
shell:startup
```

Put RawAccel.bat in the Startup folder<br/>

(Run as Admin)<br/>
• **Sens Multiplier** – controls the DPI to achieve better sensor tracking accuracy (set it high on the mouse, low in the game)<br/>
Mouse DPI * Sens Multiplier = Desired DPI<br/>
Set DPI to 1600 and set Sens Multiplier to 0.5 gives you 800 DPI with higher reporting rate of 1600<br/>
• **Y/X Ratio** – splits your vertical and horizontal values by a multiple of the Y value<br/>
• **Rotation** – controls the rotation of the mouse based on your specific holding style<br/>
To configure, open Paint and draw a straight horizontal line, adjust rotation positive or negative until you achieve perfect horizontal lines while moving your mouse side-to-side as you would normally<br/>
• **Gain** – makes the accel transition smooth rather than abrupt<br/>
• **Acceleration** – amount of acceleration; start around .05 (try .02-.05)<br/>
• **Cap Type** – Output<br/>
• **Cap: Output** – after a certain Sens Multiplier stop accelerating (try 2 if Sens @.5)<br/>
• **Input Offset** – offsets your input to the right, stay at a given accel rate until you flick your mouse<br/>

</p>
</details><hr/>

<details><summary><h2>:video_game: Dual Monitor Tools</h2><br/>

*If you have a multimonitor setup use this to lock your cursor to your game screen*</summary>

<p>

https://dualmonitortool.sourceforge.net/download.html

Run this to launch per program/game:

```
"C:\Program Files (x86)\Dual Monitor Tools\DMT.exe" DMT:Cursor:LockCursor
```

Setup a Hotkey to toggle the lock on and off:<br/>
Sticky → “Lock cursor onto screen” → Change…

</p>
</details><hr/>

<details><summary><h2>:video_game: Desktop Overlay Host</h2><br/>

*MSI Afterburner + Riva Tuner Statistics Server OSD*</summary>

<p>

https://www.msi.com/Landing/afterburner/graphics-cards

Create a shortcut:<br/>
Target:

```
"C:\Program Files (x86)\RivaTuner Statistics Server\SDK\Tools\DesktopOverlayHost\Release\DesktopOverlayHost.exe"

```
Start in:

```
"C:\Program Files (x86)\RivaTuner Statistics Server\SDK\Tools\DesktopOverlayHost\Release"
```

Open RivaTuner Statistics Server
1. Select → Setup → Plugins → OverlayEditor.dll → Setup
2. “Data sources” → Edit → Add → MSI Afterburner → Edit → Add → MSI Afterburner → Check all you wish to add
3. Select → Layouts → Edit → Ping address: qosping-aws-us-east-1.ol.epicgames.com

</p>
</details><hr/>

<details><summary><h2>:video_game: Keys2XInput</h2><br/>

*Double Movement and Keyboard to controller remapping software*</summary>

<p>

https://www.embenco.nl/keys2xinput/

</p>
</details><hr/>

<details><summary><h2>:computer: COMODO Internet Security Premium</h2><br/>

*Antivirus, Firewall, Sandbox, Host intrusion prevention & More*</summary>

<p>

https://antivirus.comodo.com/

Click: "ACTIVE NOW"<br/>
cispro_installer.exe<br/>
https://antivirus.comodo.com/download/thank-you.php?prod=cloud-antivirus&from=cav_installer&track=16905&af=16905

</p>
</details><hr/>
