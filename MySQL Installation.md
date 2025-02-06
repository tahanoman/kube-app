

## For Windows users:
### 1. Download MySQL Community Server and MySQL Workbench
* Download using the [Download Link](https://dev.mysql.com/get/Downloads/MySQLInstaller/mysql-installer-community-8.0.35.0.msi) and open downloaded file

<br>

* **(Optional)** Click `No` for `Optional MySQL Installer Upgrade Available`

<br>

* Choose `Custom` when `Choosing a Setup Type` and click `Next`

<br>

* In `Available Products`, select latest MySQL Server from `MySQL Servers/MySQL Server/MySQL Server 8.0` and add to `Product To Be Installed` using the `→`

<br>

* Select latest MySQL Workbench from `Applications/MySQL Workbench/MySQL Workbench 8.0` and add to `Product To Be Installed` using the `→` and click `Next`

<br>

* Click `Next`, `Execute` until `Accounts and Roles`. **Create your own password**, repeat and click `Next`

<br>

* Click `Next`, `Execute` and `Finish` until finish installation

<br>

### 2. Test Connections

* Open `MySQLWorkbench`

<br>

* Click `+` beside `MySQL Connections`

<br>

* Name `Connection Name`, click `Store in Vault ...` and enter the `Password` create earlier in `Step 1`

<br>

* Click `Test Connection` and a message called `Successfully made the MSQL connect` should pop out

<br>

* Click `OK` twice to finish `Setup New Connection`

<br>

### 3. Config Connection

* Right click connection created in `Step 3` and click `Edit Connection`

<br>

* Go to `Advanced` and in `Others`, start a new line and add `OPT_LOCAL_INFILE=1`

<br>

* Click `Close`

<br>

## For Mac users:

### 1. Download MySQL Workbench

* Navigate to [MySQL Workbench Download Link](https://dev.mysql.com/downloads/workbench/) and choose `OS Version`

<br>

* **(Optional)** If macOS version is not `12` or `13`, click `Archieve` and select a compatible `Product Version`

<br>

* Click `Download` and then click `No thanks, just start my download.`

<br>

* Double click on downloaded package and drag `MySQL Workbench` to `Applications`

<br>

### 2. Download MySQL Community Server

* Navigate to [MySQL Community Server Download Link](https://dev.mysql.com/downloads/mysql/) and choose `OS Version`

<br>

* **(Optional)** If macOS version is not `12` or `13`, click `Archieve` and select a compatible `Product Version`

<br>

* Click `Download` and then click `No thanks, just start my download.`

<br>

* Open downloaded package, click `Allow`, `Continue` and `Agree`

<br>

* **(Optional)** At `Installation Type`, click `Change Install Location` if wanted

<br>

* Click `Install`. Enter your password if needed and click `Install Software`

<br>

* Click `Next` and **Create your own password** and click `Finish`

<br>

### 3. Test Connections

* Navigate to `Applications` and open `MySQLWorkbench`

<br>

* Click `+` beside `MySQL Connections`

<br>

* Name `Connection Name`, click `Store in Keychain ...` and enter `Password` create earlier in `Step 2`

<br>

* Click `Test Connection` and a message called `Successfully made the MSQL connect` should pop out

<br>

* Click `OK` twice to finish `Setup New Connection`

<br>

### 4. Config Connection

* Double click connection created in `Step 3` and click `Edit Connection`

<br>

* Go to `Advanced` and in `Others`, start a new line and add `OPT_LOCAL_INFILE=1`

<br>

* Click `Close`