# Day 2: Create an Azure Virtual Machine

The Nautilus DevOps team is planning to migrate a portion of their infrastructure to the Azure cloud incrementally. As part of this migration, you are tasked with creating an Azure Virtual Machine (VM).

The requirements are:

1) Use the existing resource group.
2) The VM name must be **`devops-vm`**, it should be in **`south central us`** region.
3) Use the **`Ubuntu 22.04 LTS`** image for the VM.
4) The VM size must be **Standard_B1s**.
5) Attach a default Network Security Group (NSG) that allows inbound **`SSH (port 22)`**.
6) Attach a **`30 GB`** storage disk of type **`Standard HDD`**.
7) The rest of the configurations should remain as default.

After completing these steps, make sure you can SSH into the virtual machine.

----------------------------------------------------------------------------------------------------------------

Step 1: Go to Virtual Machine Dashboard and CLick on `Create` to select `Virtual Machine`

<img width="1919" height="925" alt="Screenshot 2026-04-10 193152" src="https://github.com/user-attachments/assets/733d7484-98bb-4adc-88fd-50915c4b301c" />

Step 2: Select Default resource group, vm name and region.

<img width="1051" height="453" alt="Screenshot 2026-04-10 193655" src="https://github.com/user-attachments/assets/05c3f99f-d736-436d-9845-2508b5dba72c" />

Step 3: Select Image and Size

<img width="1026" height="326" alt="Screenshot 2026-04-10 193724" src="https://github.com/user-attachments/assets/e86780f8-635c-4011-af6c-c6d8bacf3aa1" />

Step 4: Create SSH Key based on RSA(Optional) and Allow inbound traffic for SSH on port 22.

<img width="1052" height="408" alt="Screenshot 2026-04-10 193756" src="https://github.com/user-attachments/assets/cde50824-c201-4791-a681-b98cea4b4d31" />

Step 5: Click on Disk and Select Disk size and Disk type. (Select Standard HDD for this task)

<img width="1043" height="387" alt="Screenshot 2026-04-10 193913" src="https://github.com/user-attachments/assets/c71a0cf8-dac4-4322-9fa9-b061be07bf9e" />

Step 6: Review and Click on `Create`

<img width="972" height="261" alt="Screenshot 2026-04-10 194240" src="https://github.com/user-attachments/assets/44117626-9edd-47c5-a885-ede876e56ded" />

<img width="1236" height="405" alt="image" src="https://github.com/user-attachments/assets/8a016ef8-44c9-44e8-b78e-c76fbab80b13" />
