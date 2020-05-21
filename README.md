# Win10OEMKey
First, the batch file will find the built in Windows 10 OEM Key that is stored in WMI. It will then change the current Windows 10 key to the built in OEM one using slmgr. Finally, it will activate with the newly set key using slmgr. The script will also echo the built in product key after it queries WMI.
