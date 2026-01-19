# VVD
This is a Version dump that i got for broadcom so it is
100% safe the licence is here: The following procedures describe how to download product packages and software bundles for products that are included in the Mainframe Software, Agile Operations Software, Cyber Security Software, or Payment Security Software divisions.

Download Products
Download Symantec Bundles
If you need further assistance, contact Broadcom Customer Care, or use our Virtual Agent chat in the lower-right corner of this website.

Download Products
To download Broadcom product software:

1. From your dashboard, select the product division (Mainframe Software, Agile Operations Software, Cyber Security Software, or Payment Security Software):

Dashboard example

2. Select My Downloads from the menu on the left to see the list of products that you are entitled to download for the selected division. You can change divisions at any time.

The My Downloads page appears. In this example, mainframe software products are shown. To see other products, change the division as shown in Step 1.

My Downloads example

3. Select a product from the list or enter the product name in the Search field.

The product page appears. Two tabs appear under the product name: Products and Solutions. Some products may not have solutions.

My Downloads Products page with Products and Solutions

4. Under Products, select the product that you want. 

A list by release, service pack, and language appears.

Product Download Help - Product release, service pack, and language example.

Use the up and down arrows to select the Service Pack and Language options. 

5. Click the hypertext link to select a release.

The Primary Downloads page appears. This page shows the available product-specific software packages. 

This example shows the product-specific packages that are available for ACF2 16.0. Use the arrows to expand or collapse the contents as necessary.

Primary Downloads page example.

Some products, mostly mainframe, include an Additional Downloads page next to Primary Downloads. The Additional Downloads page shows additional software packages that are related to your product selection. For example, Common Services for z/OS is often a prerequisite for many mainframe software products. 

Additional Downloads tab example.

6. Select the files that you want to download by expanding the package contents under Primary Downloads and if applicable Additional Downloads.

The package contents are displayed by file name and last updated date. Other options may also be available.

Download options (https, secure ftp, gimzip)

Complete the following steps:

Select the checkbox under Download to add the file to the download package.
Note: If more than one pax file is available, select only one to download. For example, if there are SMP/E JCL and z/OSMF pax files, you can only select one to download at a time.
Repeat this step for all files that you want to add from each package. 
The selected product files are added to the download package. 

7. Select a download method:

If your product is RFN-enabled, a GIMZIP download option is available. Select GIMZIP to stage the package to the FTP download server. Go to Step 8.
Select HTTPS Download or Secure FTP Download to download the files from the Broadcom download server. Go to Step 9.
If tokens are available, select Generate under Tokens to create a download link that you can copy and paste in your browser to download a zip file.
To select a download method from the Download Manager, select Download Selected. This option lets you download multiple files at tone time.

For more information about these download options and input JCL samples, see Download Methods and Locations.

8. If you selected GIMZIP, the GIMZIP text changes to Order is Placed. An email is sent to the order creator with the service order details. You can access the service order details (SERVER XML) in a text file from the Download Manager.

Copy the SERVER XML to your clipboard and change the id tag to name the subdirectory in the SMPNTS directory. Use this updated SERVER XML to register the Portable Software Instance in z/OSMF.

9. If you select Secure FTP in Step 7, the Secure FTP Download Instructions pop-up appears.

  a. Copy the host URL (downloads.broadcom.com) and paste it into a browser.

  b. Log in using one of the following options:

Broadcom Support Portal username and password
Secure Access Token
To use this option, select Generate Access Credentials, specify your email address and password, and select Generate. Before you close the window, copy and save the generated FTP credential details (username and password) into a text file. You will use this information in the sample JCL to download the file.
  c. Copy the path for the zip file located in Order Location. This file identifies the order to be downloaded. For example, /12345678.zip.

For additional download assistance, see Download Methods and Locations. Sample JCL is provided for mainframe software products to download solutions and product packages.

After you complete these steps, the product package is downloaded.

Download Symantec Bundles
Protection Suite and Endpoint Encryption are bundles; therefore, you must select the solution-specific version of each product to download the different solutions that are available for each bundle. For example:

Protection Suite Enterprise Edition includes:
Endpoint Protection – select the 14.x options
Messaging Gateway – select the 10.x options
Mail Security For Microsoft Exchange – select the 7.x options
Endpoint Encryption includes:
Encryption Management Server/Gateway Email Encryption – select 3.4.2 or 10.x options
Endpoint Encryption – select 11.x options
Drive Encryption – select 10.x options
To purchase a current version of a Symantec product, locate a Broadcom Partner.
