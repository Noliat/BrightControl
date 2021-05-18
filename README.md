# Win10_BrightnessSlider
this app puts a Monitor Brightness icon to on Taskbar Tray. So you can access it with 1 click.
targeting laptops. 

* **supported os**:  win7 , win8 , win10 
* **requirements**: 
  * .net4 framework.  (win7 may need to install)
  * for ddci monitors, ([make sure  ddci is enabled on monitor menu](https://github.com/blackholeearth/Win10_BrightnessSlider/blob/master/enable%20ddc-ci.jpg?raw=true)
)
  *  make sure you do install/update your graphic driver 
  
* **Note For VirusAlert, Developers**: 
   * dont open issues about virus total trojan alert etc. if you dont trust dont use it.   

   * code version is  first working version (maybe 1.01). but **executable is always up to date**
   * old code published here is free to play.
   * uptodate code is my private intellectual property. coding effort made without any money, wont be put here.

-------------------
* **DONATE**: 

   bitcoin: 1A2CcDwWJ9MLuZaGUy5izNTZdWVnrQ9hWh

   bitcoin QR Code: 

   ![alt text](https://github.com/blackholeearth/Win10_BrightnessSlider/blob/master/send_bitcoinQR.png?raw=true)

--------------------

**Download Link**   [All Versions](https://github.com/blackholeearth/Win10_BrightnessSlider/releases)


#### Features

* Supports ddc/ci monitors 
* Seperate Sliders For Multiple Monitors
* Volume like Slider to Change Monitor Brightness
* Option to Run At Startup
* Ability to *"Rescan/Detect Monitor"* after a Monitor Plugged in/out

#### ScreenShots



![alt text](https://github.com/blackholeearth/Win10_BrightnessSlider/blob/master/ss1.jpg?raw=true)

![alt text](https://github.com/blackholeearth/Win10_BrightnessSlider/blob/master/ss2.jpg?raw=true)

![alt text](https://github.com/blackholeearth/Win10_BrightnessSlider/blob/master/ss3.jpg?raw=true)


#### NOTES   
* if slider working. but suddenly (you plug/unplug monitor/MirrorScreen in any way) then screen act up weird for second.
 you CAN get error while trying to change birghtness, you gotta press "Detect monitor".  
 

 
#### ChangeLog


v1.7.10 [experimental] (if you have a problem with this, use 1.7.9)
 * added: jump trackbar value to click.

v1.7.9
 * fixed: when the autohide taskbar is on and the taskbar is at the top of screen,the slider is still at the bottom

v1.7.8
 * fixed: parseError with nonUsa culture at dxvaMon.setbrightness
 
v1.7.7
 * prevent log error
 * added: hide sliderform even when clicked on taskbar icon 
 * fixed: in ltr system(ie arabic) taskbar is at other side . 
 * added: taskbar icon tooltip-text shows pct of all sliders ( after first  form_show) 

v1.7.5
 * fixing: null check  richscreen.getbrighness>get_physicalmonitor()
 * added:  sun image near each slider shows name on hover
 * fixed: ``(ddci problem )slider doesnt change birghtness at first time, i have to rightclick trayIcon > Press "detect Monitor"``  
* added:  Check For Updates , shows in rightclick menu.
* fixed: new monitor populator
* fixed: ddci brightness displaying -1 (may not work on all ddci monitors)
* fixed: blurry text high dpi  
* fixed: ``i got 3 screens, but i have 5 sliders``. (slider popualtion method changed )
 
v1.04 [most stable]
* added: author page to  menu item  that shows version no.
* trying to fix: fallback doesnt handle management not supported exception.
* added: seperately change brightness of multiple monitors.
* added: supports setting Brighness on ddc/ci Monitors(at startup, it may show -1,  )
* fixed: slider showing itself on second screen onhide 
* fixed: popup stays under taskbar, if taskbar is autoHiding  
* fixed: slider wasn't positioning itself according to taskbar position (Top Or Bottom Or Left Or Right of Screen)

