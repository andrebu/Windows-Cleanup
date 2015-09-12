# Windows-Cleanup
Windows Cleanup

Uninstall &amp; disable/hide these updates in Windows Update ([How to uninstall updates guide](http://www.sevenforums.com/tutorials/24373-windows-update-uninstall-update.html)) :

Key: Win7=&amp;, Win8=%, Win?=?

* If you don't see the update on your list, then you probably have not installed the update yet.
* If you can't get rid of an update after a reboot, try disk cleanup (with [Admin privileges](https://i.imgur.com/b9f8Yeh.png)), reboot, then uninstall again.

&amp;[KB **2952664**](https://support.microsoft.com/en-us/kb/2952664) - *Compatibility update for upgrading Windows 7 to Windows 10*

%[KB **2976978**](https://support.microsoft.com/en-us/kb/2976978) - *This update performs diagnostics on the Windows systems that participate in the Windows Customer Experience Improvement Program. These diagnostics help determine whether compatibility issues may be encountered when the latest Windows operating system is installed. This update will help Microsoft &amp; its partners ensure compatibility for customers who want to install the latest Windows operating system.*

?[KB **2977759**](https://support.microsoft.com/en-us/kb/2977759) - *This update performs diagnostics on the Windows systems that participate in the Windows Customer Experience Improvement Program. These diagnostics help determine whether compatibility issues may be encountered when the latest Windows operating system is installed. This update will help Microsoft &amp; its partners ensure compatibility for customers who want to install the latest Windows operating system.*

&amp;[KB **2990214**](https://support.microsoft.com/en-us/kb/2990214) - *An update that enables you to upgrade your computer from Windows 7 (SP1) to a later version of Windows.*

&amp;[KB **3021917**](https://support.microsoft.com/en-us/kb/3021917) - *This update performs diagnostics in Windows 7 (SP1) in order to determine whether performance issues may be encountered when the latest Windows operating system is installed. Telemetry is sent back to Microsoft for those computers that participate in the Windows Customer Experience Improvement Program (CEIP). This update will help Microsoft &amp; its partners deliver better system performance for customers who are seeking to install the latest Windows operating system.*

%[KB **3022345**](https://support.microsoft.com/en-us/kb/3022345) - *This update introduces the Diagnostics &amp; Telemetry tracking service to in-market devices. The update also supports applications that are subscribed to Visual Studio Application Insights.*

&amp;%[KB **3035583**](https://support.microsoft.com/en-us/kb/3035583) - *This update installs the Get Windows 10 app, which helps users understand their Windows 10 upgrade options &amp; device readiness.*

%[KB **3044374**](https://support.microsoft.com/en-us/kb/3044374) - *An update that enables you to upgrade your computer from Windows 8.1 to Windows 10.*

&amp;%[KB **3068708**](https://support.microsoft.com/en-us/kb/3068708) - *This update introduces the Diagnostics &amp; Telemetry tracking service to existing devices. The update also supports applications that are subscribed to Visual Studio Application Insights.*

&amp;%[KB **3075249**](https://support.microsoft.com/en-us/kb/3075249) - *This update adds telemetry points to the User Account Control (UAC) feature to collect information on elevations that come from low integrity levels.*

&amp;%[KB **3080149**](https://support.microsoft.com/en-us/kb/3080149) - *This package updates the Diagnostics &amp; Telemetry tracking service to existing devices. The update also supports applications that are subscribed to Visual Studio Application Insights.*

==Edits==

**Edit: Make sure you hide these updates in Windows Update or else they WILL be installed again! [How to hide updates guide](http://www.sevenforums.com/tutorials/24376-windows-update-hide-restore-hidden-updates.html)**

Edit2: Batch files such as /u/bathrobehero (and others) suggested [below](https://www.reddit.com/r/technology/comments/3keoau/microsoft_has_confirmed_that_they_are_downloading/cux7221) work, however I would caution on any batch files that uninstall more updates than I have suggested as you may not need nor want to uninstall those updates. It is all up to you, just make sure you hide the updates afterwards (see the edit above.)

Edit3: Is your $Windows.~BT folder still there? Try disk cleanup (with [Admin privileges](https://i.imgur.com/b9f8Yeh.png)) and reboot. Make sure you check the appropriate boxes.

Edit4: [My system with no $Windows.~BT in case you are wondering or need proof.](https://i.imgur.com/lv7a46q.png)

==More Stuff==

[\[Tip\] Disallow Secret “Customer Experience Improvement Program” \(CEIP\) from Collecting Information in Windows](http://www.askvg.com/how-to-disallow-secret-customer-experience-improvement-program-collecting-information-in-windows-7/) (/u/JimmysBruder) - Why? Because I didn't know about this dialog and was opt in.
