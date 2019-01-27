# whmcsBPAY

## Requirements 
Below is a list of requirements needed to be met in order for BPAY to work successfully on your WHMCS.
- PHP 5.6 or greater
- WHMCS version 5.3 or greater 
- PHP CURL must be enabled in php.ini
- Server behind a firewall must have relentlesshosting.com.au unblocked

## Installation Instructions 
Below are the steps that must be followed for BPAY to work successfully on your WHMCS.
1. Download the BPAY product from relentlesshostinig.com.au if you have not already done so.
2. Upload all the files into your WHMCS directory in the same file structure as set in the zip file.
3. Once all files are uploaded, then go to your WHMCS administrator area. Go to Setup tab => Addon Modules
4. Look for “BPAY Manager” and click “Activate” Select "BPAY" from "Activate Module" and then click “Configure” and grant your user access to the module
5. Finally, in the top blue menu in WHMCS click “Addons” and then select “BPAY Manager”
6. An installation page will appear and once you have completed all steps of the installation you can start using BPAY right away for your existing invoices.
 

## Trouble shooting
My BPAY image is not appearing on the invoice.
- Simply go to the BPAY Manager in your WHMCS and click the “info” tab and look for any errors that may be causing your BPAY to not work correctly.
- If all else fails, please contact us via support for assistance.

## System Requirements 
Below is a list of specifications that your system must have in order for BPAY gateway to work.

**Specifications	Version**
- PHP 	5.6 or 7.1
- WHMCS 	5.2 or above

If you encounter any issue using the module with the version specifications listed above, please let our support team know.

## Change Log
###### Bug fixes in 2.1.9 is:
- Installation bug fix - Fixed bug where a database value were missing for fresh install of this product
- Installation bug fix - Fixed bug file verification was not working correctly
###### Bug fixes in 2.1.8 is:
- Added Feature - Artwork change from 7 different variations
- Added Feature - PHP 7.2 support
- Removed Feature - Removed Ioncude Encoding Requirments
- Cron base directory - Added check for users who cron's run from rood directory rather than base web directory
###### Features Added in 2.1.7 is:
- Added Feature - Added prefix support for EziDebit
- Added Feature - Added option to use pre-configured bank requirements for BPAY (please let us know if your bank is not listed)
- Added Feature - Modified Example BPAY image to demonstrate an actual BPAY image generated based off settings made in settings area.
- Added Feature - Added preview button on appearances page to quickly view new placement of an invoice after change made.
- Added Feature - Added name lookup feature based off biller code entered
###### Bug fixes in 2.1.6 is:
- Invoice PDF bug - Fixed bug with loading BPAY Ref on order complete
- Invoice PDF bug - Fixed MOD10v1 check digit issue
###### Bug fixes in 2.1.5 is:
- Invoice PDF bug- Fixed minor bug with loading BPAY library assets
- Invoice PDF bug - Fixed minor bug where the BPAY details would only load on one PDF if invoice overflowed to multiple pages
- CSS for Hooks - Added the ability for developers to manipulate BPAY elements generated by WHMCS hooks
###### Bug fixes in 2.1.4 is:
- License validation fix - Allow for BPAY license to stay active without constant polling license service (improves page load time)
- Pagination fix - Fixed minor bug pagination on search for CRN's in the BPAY Manager
###### Bug fixes in 2.1.3 is:
- License validation fix - Allow for BPAY license to stay active without constant polling license service (improves page load time)
- Image Generator compatibility improvements - Image generation in this addon is now supported on more shard web hosting servers online.
- Global Search bug fix - Fixed minor bug with using the global search on WHMCS
- Hook fix - Fixed minor bug with some invoices that were in a specific state
###### Bug fixes in 2.1.2 is:
- Ioncube Later Version - Support for PHP 7.0 requires a later version of PHP
###### Bug fixes in 2.1.1 is:
- Database fix - Support for MYSQL version 5.6
###### Bug fixes in 2.1 is:
- Incorrect CRN in invoice - When set to client mode the CRN would always use invoice ID rather than client ID
###### New features available in 2.0 is:
- WHMCS Global Search integration - you can now use the top search bar on WHMCS to search BPAY references numbers
- Ability to search BPAY reference codes - You can search for clients with the complete BPAY reference code
- Centrally control BPAY appearances in one place - Manage all locations BPAY can be seen on WHMCS is now easy to manage without needing to code anything.
- BPAY system automated health check function - Never have issues with BPAY manager not be installed correctly again
