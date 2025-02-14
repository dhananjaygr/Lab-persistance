## Implement Lab Progress Persistence After Refresh 

### Feature Requirement
Implement lab persistence to retain the deployment progress state, ensuring it continues from the same point after a page refresh.

### Implementation
The deployment progress will no longer restart from 0% after a page refresh. It will continue from where it left off prior to the refresh.

### Steps for Testing the Lab Progress Persistence After Refresh: 

1. Log in to the CL portal and navigate to the required tenant (WIZ). On the left-hand side of the page, you will see the Template section.

2. Navigate to the **ODL (1)** section in the left menu and click on the **Users (2)** button.

   ![](/img/01.png)

3. Click on the **+ Add User** button.

   ![](/img/02.png)

4. Then, provide all the necessary details as indicated below and click on **Submit.**

   ![](/img/03.png)

5. Once the user is added, click on the **Open Experience Invite Link in New Tab** button.

   ![](/img/04.png)

6. Then, click on the **Launch Lab** button.

   ![](/img/05.png)

7. As the lab is being deployed, you will see the duration and the percentage of the lab’s progress. Now, try clicking the Refresh button at the top left of the page and check the deployment status. It will continue from where it left off prior to the refresh.

   ![](/img/06.png)

