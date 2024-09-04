1. Open a command prompt as Administrator
2. In the command prompt, type the following:
  * Office 2016/2019/2021 (32-bit) on a 32-bit version of Windows 
    
      `cscript "C:\Program Files\Microsoft Office\Office16\OSPP.VBS" /dstatus`
  * Office 2016/2019/2021 (32-bit) on a 64-bit version of Windows 
   
     `cscript "C:\Program Files (x86)\Microsoft Office\Office16\OSPP.VBS" /dstatus`
  * Office 2016/2019/2021 (64-bit) on a 64-bit version of Windows 
   
     `cscript "C:\Program Files\Microsoft Office\Office16\OSPP.VBS" /dstatus`
3. You should now get a screen with some license details such as the license name, type and the last 5 characters of the Product Key.
 
4. You can use the last 5 characters of the Product Key to remove it using command:
  * Office 2016/2019/2021 (32-bit) on a 32-bit version of Windows 
    
      `cscript "C:\Program Files\Microsoft Office\Office16\OSPP.VBS" /unpkey:<LAST 5 CHARACTERS>`
  * Office 2016/2019/2021 (32-bit) on a 64-bit version of Windows 
   
     `cscript "C:\Program Files (x86)\Microsoft Office\Office16\OSPP.VBS" /unpkey:<LAST 5 CHARACTERS>`
  * Office 2016/2019/2021 (64-bit) on a 64-bit version of Windows 
   
     `cscript "C:\Program Files\Microsoft Office\Office16\OSPP.VBS" /unpkey:<LAST 5 CHARACTERS>`
5. Enjoy!
