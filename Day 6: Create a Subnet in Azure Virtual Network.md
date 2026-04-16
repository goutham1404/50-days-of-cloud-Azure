# Day 6: Create a Subnet in Azure Virtual Network

The Nautilus DevOps team is strategizing the migration of a portion of their infrastructure to the Azure cloud. Recognizing the scale of this undertaking, they have opted to approach the migration in incremental steps rather than as a single massive transition.

For this task, create a Virtual Network (VNet) named `xfusion-vnet` and one subnet named `xfusion-subnet` within the VNet in the `West US` region. Make sure the IPv4 address range is `10.0.0.0/16`.

Steps:

1. Under the **Basic** tab, create **`Virtual network`** with existing **resource group** with name **`xfusion-vnet`** in **`West US`** region.

   <img width="1174" height="649" alt="image" src="https://github.com/user-attachments/assets/569d1c9a-6c2c-4adc-8f7f-30c23d27a718" />

2. Click **Next**, Go to **Address space** tab and edit the default subnet with name **`xfusion-subnet`** and **Save**

   <img width="651" height="545" alt="image" src="https://github.com/user-attachments/assets/7ccfbadd-1e4b-418e-b2fa-46f3044d8c0c" />

3. After renaming the default subnet, verify subnet name and required address space. in this case, it is **`10.0.0.0/16`**

   <img width="1032" height="379" alt="image" src="https://github.com/user-attachments/assets/42dc8d6e-8898-4248-a1c6-6977953d9cd4" />

4. Select **Review + Create**, **Create**.

   <img width="652" height="625" alt="image" src="https://github.com/user-attachments/assets/7c5a333f-72b6-4cc7-a086-8817cdf12340" />

5. Verify deployment.

   <img width="1162" height="471" alt="image" src="https://github.com/user-attachments/assets/ef149faf-6294-4f79-a767-3339680406fd" />
