# Getting Started with Lab

## Login to Azure Portal

1. From your computer, start a web browse(Chrome, Edge, mozilla firefox etc..), and navigate to [Azure portal](https://portal.azure.com/).
   
1. On **Sign in to Microsoft Azure** tab you will see login screen, enter following email/username and then click on **Next**. 
   * Email/Username: <inject key="AzureAdUserEmail"></inject>
   
     ![](images/gettingstart04.png "Enter Email")
     
1. Now enter the following password and click on **Sign in**.
   * Password: <inject key="AzureAdUserPassword"></inject>
   
     ![](images/gettingstart05.png "Enter Password")

1. If you see the pop-up **Stay Signed in?**, click No

1. If you see the pop-up **You have free Azure Advisor recommendations!**, close the window to continue the lab.

1. If a **Welcome to Microsoft Azure** popup window appears, click **Maybe Later** to skip the tour.
   
1. Now you will see Azure Portal Dashboard, click on **Resource groups** from the Navigate panel to see the resource groups.

    ![](images/gettingstart08.png "Resource groups")
 
    > **Hint**: To view **Resource groups**, you may need to scroll down. 
   
1. In Resource groups page, click on **Workshop-MT-CosmosDB-<inject key="DeploymentID" enableCopy="false" />**.

    ![](images/gettingstart09.png "Resource groups")

1. Then select your Azure Cosmos DB account **smartbookinginc-<inject key="DeploymentID" enableCopy="false" />** from the Workshop-MT-CosmosDB-<inject key="DeploymentID" enableCopy="false" /> resource group.

    ![](images/gettingstart10.png "Resource groups")

1. Once you are inside Azure Cosmos DB account from the left side menu click on **Data Explorer**, review the **DedicatedThroughputDB** and **SharedThroughputDB** databases.

    ![](images/gettingstart11.png "Resource groups")
