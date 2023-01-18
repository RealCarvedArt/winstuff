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

<details><summary><h2>:computer: NVIDIA Control Panel</h2><br/>

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

<details><summary><h2>:space_invader: CLICK ME</h2></summary>
<p>

#### We can hide anything, even code!

```
"Hello World"
```

#### TROUBLESHOOTING
==============
  
Bad icon or bad pin name are collateral effects of a bad installation or a previous bad de-installation process. To solve this problem:

1. Uninstall Voicemeeter + REBOOT

2. Check there are no remaining devices in Windows Device Manager , if present, uninstall manually as explained in this topic: https://forum.vb-audio.com/viewtopic.php?f=7&t=688

3. Uninstall Voicemeeter + REBOOT

</p>
</details><hr/>
