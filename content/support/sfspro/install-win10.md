---
title: "Windows 10 Installation"
tags:
  - win10
weight: 1
---
#### Installing the Data Package

The data package contains `sfspro-data` directory. By default, the application looks for this directory in the user's home directory - typically `C:\Users\<username>\`. You may place the directory anywhere you wish, however the user must have read/write access to it. If sharing data among multiple users, it is suggested to place this directory on a Windows share. To install, simply unzip the `SFSPro Data-<version>.zip` file.

#### Installing the License File

Simply place the `license.properties` file containing the license data in the `sfspro-data` directory. The file must be named `license.properties`.

#### Installing the Application

Run the `SFSPro-<version>.msi` installer. It will place the software in `C:\Program Files` and add a link to the user's desktop.

#### Starting the Application for the First Time

If the `sfspro-data` directory is not in the default location, the application will complain about being unlicensed. Select the `Read Only` option on the dialog. The client list dialog should appear. Cancel out of the dialog, select `Help->SFS Data Directory` from the menu. Browse to the location of the `sfspro-data` directory. Select the `Open` button. Click `OK` to close out of the dialog. Restart the application.

#### Configuring the Firm

The first time the software is run, you will need to configure the details of the firm, including the attorneys. To do this, select `Edit->Firm` from the menu. Then enter the details about the firm and add any attorneys for the firm. Click `OK` to exit the dialog. You will need to restart the application for the changes to take effect. *WARNING* If you are using a floating license, you *CANNOT* change the name of the firm. It is tied to the license. If you wish to change the name of your firm, you must contact <info@justifiedsolutions.com> to update your license.
