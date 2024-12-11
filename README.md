# Tutorial_deploy_streamlit_vsc_with_colab_server 🚀  

This repo shows you how to deploy a **Streamlit** application via **ngrok** using a **Colab server**.  

## Description 📖  
- We will connect the **Colab server** with **Visual Studio Code** and code in this environment via **Remote Tunnels**. 🔗  
- Then, we will create a **Ngrok** to deploy the app and make it accessible for everyone. 🌐  

# Steps by Steps to connect Colab server 📋:  

## 1. Connect to Colab Server 🌐  
### Step 1️⃣:  
- Download and upload the folder [deploy_streamlit](./deploy_streamlit/) or clone this repository to your Google Drive.  

### Step 2️⃣:  
- Navigate to the folder in your drive and open the file `colab_connect_vsc.ipynb`. The content will look like this:  

  ![connnect_vsc](https://github.com/user-attachments/assets/4d2f8460-ca48-421a-8892-50a9cc0ccead)  

### Step 3️⃣:  
- Run all cells in the notebook. A popup will appear on the top left. You need to allow access to your Drive folder.  
  ![accept_drive1](https://github.com/user-attachments/assets/b09f88bc-0563-4184-a399-1ae6b450a910)  

- After completing, you will see a link and a code to connect your device:  

  ![image](https://github.com/user-attachments/assets/32ee2d0a-dbaf-421c-826a-7a4ea3fbc15c)  

### Step 4️⃣:  
- Sign in to GitHub in the popup. Enter the code provided.  
  ![image](https://github.com/user-attachments/assets/d6b468c3-ee99-4bbf-ba64-3702cf8ec38b)  

- Authorize Visual Studio Code to continue:  
  ![image](https://github.com/user-attachments/assets/2fdac86f-94c2-4f70-ad84-b842f46cb681)  

- Success! 🎉  
  ![image](https://github.com/user-attachments/assets/68a16bbe-6d7c-40ed-868b-20926708a23c)  

## 2. Configure Visual Studio Code ⚙️  
### Step 1️⃣:  
- Open Visual Studio Code and install the **Remote Tunnels** extension.  

  ![image](https://github.com/user-attachments/assets/23abaa4e-c55c-4a46-9f42-7748e9907e1a)  

### Step 2️⃣:  
- Click the **Remote** icon in the bottom left:  
  ![image](https://github.com/user-attachments/assets/56252ab2-dbfd-47d7-b31a-102c08bb0a8e)  

- Select **"Connect with Tunnel..."** and choose **"GitHub"**.  

  ![image](https://github.com/user-attachments/assets/a51d9533-af34-467e-a646-679e431f32e6)  

- Select **"Colab Connect"** and wait for the connection.  

  ![image](https://github.com/user-attachments/assets/107bf0ba-9be6-4bfc-b03f-6fe7052d2c4c)  

## 3. Open Your Drive Folder 📂  
- Once connected, navigate to the folder `/content/drive/MyDrive/` to access your Drive files.  

  ![image](https://github.com/user-attachments/assets/8dfae19b-b19c-4a79-b16c-e57b80dd9e1f)  

- Choose the folder you want to work on. In this case, select the `deploy_streamlit` folder to deploy the app.  

- Start coding directly in your Drive folder. Changes will automatically save to the Drive. 💾  
  ![image](https://github.com/user-attachments/assets/ae2ae292-79c6-4582-a89d-83a94c2aa13f)  
