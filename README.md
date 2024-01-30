# UiPath-Custom-REFramework
UiPath Custom REFramework

- It's REFramework Source For UiPath RPA Developer
[ Windows / Windows-Legacy REFramework]

- Name : ykdman_REFramework

- Compatibility : Windows / Windows-Legacy

- Creator : ykdman

- Dependencies :
	- UiPath.Excel.Activities = V 2.16.2
	- UiPatn.Mail.Activities = V 1.18.2
	- UiPath.System.Activities = V 22.10.4
	- UiPath.Testing.Activities = V 22.10.3
	- UiPath.UIAutomation.Activities = V 22.10.5

[ Setting ]
- Recomand Source Folder Tree
	- Source
		- Application1
			- App1 Login.xaml
			- App1 Navigate Menu.xaml
		- Application2
			- App2 Login.xaml
			- App2 Navigate Menu.xaml

- DataTable Transaction Retry Setting (Config File)
	1. Rery Transaction
		- TransactionRetryFlag = True
		- TransactionMaxRetryCount > 0
	2. No Retry Transaction (No Retry Exception)
		- TransactionRetryFlag = False
		- TransactionMaxRetryCount = ?
	3. No Retry Transaction (Pass Transaction)
		- TransactionRetryFlag = True
		- TransactionMaxRetryCount = 0



