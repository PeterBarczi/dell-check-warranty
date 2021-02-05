# Check Warranty of DELL devices

This powershell script checks the warranty of your devices based on provided Serial number.
You will also need the API keys provided by DELL.
As soon as you get the APIs you can use the script.
```
1. Fill in the following variables:
$ORG_API_Key="Your-API-key"
$ORG_API_Secret="Your-API-Secret"

2. Run script
.\Get-DellWarrantyInfo.ps1

Enter ServiceTag [R90QYP6X] : GZ80E5X2

Service Tag   : GZ80E5X2
Model         : POWEREDGE R740XD
Type          : poweredge-r740xd
Ship Date     : 05-07-19
Warranty Exp. : 05-08-22
```
