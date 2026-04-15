# Day 5: Create a Virtual Network (IPv4) in Azure

The Nautilus DevOps team is strategically planning the migration of a portion of their infrastructure to the Azure cloud. Acknowledging the magnitude of this endeavor, they have chosen to tackle the migration incrementally rather than as a single, massive transition. Their approach involves creating Virtual Networks (VNets) as the initial step, as they will be provisioning various services under different VNets.

Create a **`Virtual Network`** (VNet) named **`datacenter-vnet`** in the **`East US`** region with **`192.168.0.0/24`** IPv4 CIDR.

The following procedure creates a virtual network with a resource subnet, an Azure Bastion subnet, and a Bastion host:

- In the portal, search for and select **`Virtual networks`**.
- On the **`Virtual networks`** page, select + **`Create`**.
- On the **`Basics`** tab of **`Create virtual network`**, enter, or select the following information:

  <img width="1353" height="749" alt="image" src="https://github.com/user-attachments/assets/cf554196-cfe4-4b2f-8089-b61718579d44" />


- Select **`Next`** to proceed to the **`Security`** tab.
- Select **`Next`** to proceed to the **`IP Addresses`** tab and Delete all address spaces.

  <img width="1137" height="652" alt="image" src="https://github.com/user-attachments/assets/a1ce959a-6135-4f9f-84f4-26e44dcf9595" />


- In **`Add IPv4 Address space`**, enter **`192.168.0.0/24`** Address Space for challenge requirment.

  <img width="1128" height="659" alt="image" src="https://github.com/user-attachments/assets/c26a803e-6f5d-490e-898f-ca330a1fae44" />


- Select **`Save`**.
- Select **`Review + create`** at the bottom of the window. When validation passes, select **`Create`**.

  <img width="484" height="78" alt="image" src="https://github.com/user-attachments/assets/38a3dc14-cb73-447c-9247-e93db2ac4af9" />


- Verify Deployment

  <img width="1500" height="601" alt="image" src="https://github.com/user-attachments/assets/374286da-9eb4-44c2-8461-e461ef307298" />
