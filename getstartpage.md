# Getting Started with Lab

## Login to Azure Portal

1. In the JumpVM, click on the Azure portal shortcut of Microsoft Edge browser from the desktop.

   ![](gettingstart03.png "Lab Environment")
   
1. On **Sign in to Microsoft Azure** tab you will see login screen, enter following email/username and then click on **Next**. 
   * Email/Username: <inject key="AzureAdUserEmail"></inject>
   
     ![](gettingstart04.png "Enter Email")
     
1. Now enter the following password and click on **Sign in**.
   * Password: <inject key="AzureAdUserPassword"></inject>
   
     ![](gettingstart05.png "Enter Password")

1. If you see the pop-up **Stay Signed in?**, click No

1. If you see the pop-up **You have free Azure Advisor recommendations!**, close the window to continue the lab.

1. If a **Welcome to Microsoft Azure** popup window appears, click **Maybe Later** to skip the tour.
   
1. Now you will see Azure Portal Dashboard, click on **Resource groups** from the Navigate panel to see the resource groups.

    ![](gettingstart08.png "Resource groups")
 
    > **Hint**: To view **Resource groups**, you may need to scroll down 
   
1. In Resource groups page, click on **Workshop-MT-CosmosDB-<inject key="DeploymentID" enableCopy="false" />**.

    ![](gettingstart09.png "Resource groups")

1. Then select your Azure Cosmos DB account **smartbookinginc-<inject key="DeploymentID" enableCopy="false" />** from the Workshop-MT-CosmosDB-<inject key="DeploymentID" enableCopy="false" /> resource group

    ![](gettingstart10.png "Resource groups")

1. Once you are inside Azure Cosmos DB account from the left side menu click on **Data Explorer**, review the databases **DedicatedThroughputDB** and **SharedThroughputDB*

    ![](gettingstart11.png "Resource groups")