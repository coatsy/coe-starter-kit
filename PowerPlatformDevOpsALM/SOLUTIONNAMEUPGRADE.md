## Upgrade Instructions

#### Export User Settings and App User Settings from Dataverse

1. Go to the **Power Apps Maker Portal**

1. **Select Solutions**

1. **Select the ellipsis** next to **ALM Accelerator for Advanced Makers** and **Select Edit**
   ![image-20210511113413256](.attachments/SOLUTIONNAMEUPGRADE/image-20210511113413256.png)
   
1. Select the **App User Settings** Table and **Select Data**
   ![image-20210511113803535](.attachments/SOLUTIONNAMEUPGRADE/image-20210511113803535.png)
   
1. **Select Data** from Menu and **Select Export Data**
   ![image-20210511113813557](.attachments/SOLUTIONNAMEUPGRADE/image-20210511113813557.png)
   
1. Wait for the Export to Complete and **Select Download exported data**
   ![image-20210511114016014](.attachments/SOLUTIONNAMEUPGRADE/image-20210511114016014.png)

1. **Repeat the steps above** to Export the data for the **User Setting table**

#### Delete Managed PowerPlatformDevOpsALM Solution

1. In the Maker Portal **Select Solutions**

1. **Select the ellipsis** next to **ALM Accelerator for Advanced Makers**, **Select Delete**

   ![image-20210511114718472](.attachments/SOLUTIONNAMEUPGRADE/image-20210511114718472.png)

3. Confirm you want to **Delete the Solution**

   ![image-20210511114841833](.attachments/SOLUTIONNAMEUPGRADE/image-20210511114841833.png)

#### Import Managed ALMAcceleratorForAdvancedMakers Solution

1. Download the latest Managed Solution from Releases in GitHub https://github.com/microsoft/coe-starter-kit/releases

1. In the Maker Portal **Select Solutions** and **Select Import**

1. Browse and Select the **File you just downloaded** and **Select Next**

   ![image-20210511115204673](.attachments/SOLUTIONNAMEUPGRADE/image-20210511115204673.png)

1. **Select Next** on the following screen and **Select or Create a Connection for the Connection Reference**

1. **Select Import**

   ![image-20210511115331874](.attachments/SOLUTIONNAMEUPGRADE/image-20210511115331874.png)

#### Import User Settings and App User Settings into Dataverse

1. **Extract the .csv files from the .zip files** you downloaded during the Export steps

   ![image-20210511120158134](.attachments/SOLUTIONNAMEUPGRADE/image-20210511120158134.png)

1. **Select the ellipsis** next to **ALM Accelerator for Advanced Makers** and **Select Edit**
   ![image-20210511115747968](.attachments/SOLUTIONNAMEUPGRADE/image-20210511115747968.png)

1. Select the **App User Settings** Table and **Select Data**
   ![image-20210511113803535](.attachments/SOLUTIONNAMEUPGRADE/image-20210511113803535.png)

1. **Select Data** from Menu and **Select Get Data** then **Select Get data from Excel**

   ![image-20210511115947033](.attachments/SOLUTIONNAMEUPGRADE/image-20210511115947033.png)

4. **Browse to the .csv file** you extracted from the .zip for this Table and **Select Import**

   ![image-20210511123504501](.attachments/SOLUTIONNAMEUPGRADE/image-20210511123504501.png)

5. **Repeat the steps above** to Import the data for the **User Setting table**