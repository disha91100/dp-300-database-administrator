# Lab 05: Enable Microsoft Defender for SQL and Data Classification

## Lab scenario
The students will take the information gained in the lessons to configure and subsequently implement security in the Azure Portal and within the AdventureWorks database.

You have been hired as a Senior Database Administrator help ensure the security of the database environment. These tasks will focus on Azure SQL Database.

## Lab objectives

In this lab, you will complete the following tasks:

- Task 1: Enable Microsoft Defender for SQL
- Task 2: Enable Data Classification

## Estimated timing: 30 minutes

## Architecture diagram

![](../images/preview(05).png)

### Task 1 - Enable Microsoft Defender for SQL

1. From the Azure Portal, search for **SQL servers (1)** in the search box at the top, then click on **SQL servers (2)** from the list of options.

   ![Picture 1](../images/dp-300-lab5-1.png)

1. Select the server name **dp300-lab-<inject key="DeploymentID" enableCopy="false"/>** to be taken to the detail page.

   ![A screenshot of a social media post Description automatically generated](../images/dp-300-lab5-2.png)
   
   >**Note:** You may have a different location assigned for your SQL server

1. From the main blade of your Azure SQL server, navigate to the **Security (1)** section, and select **Microsoft Defender for Cloud (2)**.
   ![image](../images/dp-300-lab5-3a.png) 

1. Click on the link in the header labeled **Microsoft Defender for Cloud**.
   ![image](../images/dp-300-lab5-3b.png) 

1. On the **Microsoft Defender for Cloud** page, select **Enable**.

   ![Screenshot of selecting the Microsoft Defender for Cloud option](../images/dp-300-lab5-3.png) 

1. The following notification message will show up after Azure Defender for SQL is successfully enabled.

   ![Screenshot of selecting the Configure option](../images/upd-dp-300-module-05-lab-02_1.png)

1. Select **Microsoft Defender for Cloud**, and select the **Configure** link (You may need to refresh the page to see this option)

   ![Screenshot of selecting the Configure option](../images/dp-300-lab5-4.png)

1. On the **Server settings** page, notice that toggle switch under **MICROSOFT DEFENDER FOR SQL** is set to **ON (1)** then **close (2)** the tab.

   ![image](../images/dp-300-lab5-4a.png)

> **Congratulations** on completing the task! Now, it's time to validate it. Here are the steps:
- Hit the Validate button for the corresponding task. If you receive a success message, you can proceed to the next task. 
- If not, carefully read the error message and retry the step, following the instructions in the lab guide.
- If you need any assistance, please contact us at cloudlabs-support@spektrasystems.com. We are available 24/7 to help you out.
 
   <validation step="df0996ae-1327-4de4-90b7-cd81257c2cc7" />
  
### Task 2 - Enable Data Classification

1. From the main blade of your Azure SQL server, navigate to the **Settings (1)** section, and select **SQL databases (2)**, and then select the  **AdventureWorksLT (3)** database.

   ![Screenshot showing selecting the AdventureWOrksLT database](../images/dp-300-lab5-5.png)

1. On the main blade for the **AdventureWorksLT** database, from left navigation pane under **Security (1)** section, select **Data Discovery & Classification (2)** .

   ![image](../images/dp-300-lab5-5a.png)

1. On the **Data Discovery & Classification** page, you'll notice an informational message stating: **Currently using SQL Information Protection policy. We have found 15 columns with classification recommendations**. Click on this link to proceed.

   ![Screenshot showing the Classification Recommendations](../images/dp-300-lab5-6.png)
      
1. On the next **Data Discovery & Classification (1)** screen select the check box next to **Select all (2)**, select **Accepted selected recommendations(3)**, and then select **Save (4)** to save the classifications into the database.

   ![Screenshot showing the Accept selected recommendations](../images/dp-300-lab5-(7).png)

   >**Note**: Please select **click to view** or tap the arrow in the bottom-right corner to expand the columns.

   ![Screenshot showing the Classification Recommendations](../images/dp300-mod5-taparrow.png) 
    
1. Back to the **Data Discovery & Classification (1)** screen, select **Overview (2)** tab notice that fifteen columns were successfully classified across five different tables.

   ![Screenshot showing the Accept selected recommendations](../images/dp-300-lab5-8.png)

>**Results:** In this exercise, you've enhanced the security of an Azure SQL Database by enabling Microsoft Defender for SQL. You've also created classified columns based on Azure portal recommendations.

### Review

In this lab, you have completed:

- Enabled Microsoft Defender for SQL.
- Enabled Data Classification.
  
### You have successfully completed the lab.

