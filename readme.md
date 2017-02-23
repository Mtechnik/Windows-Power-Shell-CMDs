> **T**hese are power shell commands that will remove all the unwanted Microsoft Pre-Installed programs that it installs with your Windows Installation or Update. Please right click on your Windows button at the bottom left corner and click on Windows Power Shell(Admin) OR right click Windows Power Shell and select Open as Admin.

Get-AppxPackage -name "Microsoft.ZuneMusic" | Remove-AppxPackage 
Get-AppxPackage -name "Microsoft.Music.Preview" | Remove-AppxPackage 
Get-AppxPackage -name "Microsoft.BingTravel" | Remove-AppxPackage 
Get-AppxPackage -name "Microsoft.BingHealthAndFitness" | Remove-AppxPackage 
Get-AppxPackage -name "Microsoft.BingFoodAndDrink" | Remove-AppxPackage 
Get-AppxPackage -name "Microsoft.People" | Remove-AppxPackage 
Get-AppxPackage -name "Microsoft.BingFinance" | Remove-AppxPackage 
Get-AppxPackage -name "Microsoft.3DBuilder" | Remove-AppxPackage 
Get-AppxPackage -name "Microsoft.BingNews" | Remove-AppxPackage 
Get-AppxPackage -name "Microsoft.BingSports" | Remove-AppxPackage 
Get-AppxPackage -name "Microsoft.WindowsCamera" | Remove-AppxPackage 
Get-AppxPackage -name "Microsoft.Getstarted" | Remove-AppxPackage 
Get-AppxPackage -name "Microsoft.Office.OneNote" | Remove-AppxPackage 
Get-AppxPackage -name "Microsoft.WindowsMaps" | Remove-AppxPackage 
Get-AppxPackage -name "Microsoft.MicrosoftSolitaireCollection" | Remove-AppxPackage 
Get-AppxPackage -name "Microsoft.MicrosoftOfficeHub" | Remove-AppxPackage 
Get-AppxPackage -name "Microsoft.BingWeather" | Remove-AppxPackage 
Get-AppxPackage -name "Microsoft.BioEnrollment" | Remove-AppxPackage 
Get-AppxPackage -name "Microsoft.WindowsStore" | Remove-AppxPackage 
Get-AppxPackage -name "Microsoft.Windows.Photos" | Remove-AppxPackage 
Get-AppxPackage -name "Microsoft.WindowsPhone" | Remove-AppxPackage 
