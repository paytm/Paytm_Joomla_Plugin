Introduction

This is the readme file for Paytm Payment Gateway Plugin Integration for Joomla v3.x based e-Commerce Websites. 
The provided Package helps store merchants to redirect customers to the Paytm Payment Gateway when they choose PAYTM as their payment method. 
After the customer has finished the transaction they are redirected back to an appropriate page on the merchant site depending on the status of the transaction.
The aim of this document is to explain the procedure of installation and configuration of the Package on the merchant website.


Joomla Paytm Integration Kit

This Kit consist of a one package(pkg_paytm.zip) and a readme file.
The Package further consists of a Joomla Module and a Joomla component in order to integrate Paytm Payment Gateway with Joomla.


Installation

- Log in to your Joomla Administrator Area.
- From the backend of your Joomla site (administration) select Extensions -> Manage -> Install. 
- Click the "Choose File" button and select the extension package (pkg_paytm.zip) from your local machine. Click the Upload & Install button.
- After Successful Package Installation, Select Extensions -> Modules and locate "Paytm" module from the installed module list and click on this to configure.


Configuration

- You should choose the Paytm Environment (either to Sandbox or Production)
- Enter paytm Merchant Key, Merchant ID, website in the listed parameters on configuration tab. These parameters are Mandatory.
- Set the module status to "Published"
- Select "Position" as per your current active template.
- Also assign the module on which page you want to show if from the Menu Assigment Tab next to current tab.
- Then click on Save and close.


How to Use

- After successfull installation and activation of this package.
- You will able to collect payment from the customer by assigning the module on specific page with specific position as per your current active theme.
- In order to check the payment history, you may login to joomla administration panel and select Components -> Order History. This will list all the transaction
done till date with their amount, status, orderid, customer email etc.

# Paytm PG URL Details
	staging	
		Transaction URL             => https://securegw-stage.paytm.in/theia/processTransaction
		Transaction Status Url      => https://securegw-stage.paytm.in/merchant-status/getTxnStatus

	Production
		Transaction URL             => https://securegw.paytm.in/theia/processTransaction
		Transaction Status Url      => https://securegw.paytm.in/merchant-status/getTxnStatus
