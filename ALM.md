# Application Lifecylce Management
## Data Environment Strategy
### Environment Types
  * **Nestoil Dev:** This environment serves as the development instance where the application was built and this is where the source copy of the solution unmanaged file resides before deployment.
  * **Nestoil UAT:** This is the environment where User Acceptance Test is carryout, here the end-user/stakeholders of the solution are brough onboard to test the deployed managed solution.
  * **Nestoil PLC:** This is the live instance, where all solution users are able to engage the developed solution and use for the daily purpose of making request to work from home as stated in the project overview
    
![ALM](https://github.com/user-attachments/assets/16966396-bd22-4d12-b443-bd48730f5314)

### Environment Data Location
All environment are deployed in the Europe region leveraging on that datacenter as that is where the data will be residing.

### Deployment Model
The deployment will follow the standard ALM process of pushing the solution from Dev - UAT - Production instance.

## Solution Strategy

### NomenClature
  * **Publisher:**
  * **Prefix:**

    ![Solution_name](https://github.com/user-attachments/assets/72cbac11-332b-46c4-baa5-848ec6b44fb0)

### Solution Objects
This Solution contain eight objects

  * One Canvas App
  * One Cloud flow
  * Four Connection References
  * Two Environment Variables (which are SharePoint Site & Sharepoint List)
     
![Solution-Objects](https://github.com/user-attachments/assets/23db9a7e-6b9f-4fad-9c01-ff40079dc0e9)

     
