# Tutorial_deploy_streamlit_vsc_with_colab_server 🚀  

This repo shows you how to deploy a **Streamlit** application via **ngrok** using a **Colab server**.  

## Description 📖  
- We will connect the **Colab server** with **Visual Studio Code** and code in this environment via **Remote Tunnels**. 🔗  
- Then, we will create a **Ngrok** to deploy the app and make it accessible for everyone. 🌐

## Index:
- [Step by step to Connect Colab Server 📋](#connect_colab_server)
- [Step by step to Deploy Streamlit App via Ngrok 🚀](#deploy_streamlit_app_ngrok)


<h1 id="connect_colab_server">Step by step to Connect Colab Server 📋</h1>  

## 1. Connect to Colab Server 🌐  
### Step 1️⃣:  
- Download and upload the folder [deploy_streamlit](./deploy_streamlit/) or clone this repository to your Google Drive.  

### Step 2️⃣:  
- Navigate to the folder in your drive and open the file colab `connect_vsc.ipynb`. The content will look like this:  

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

---

<h1 id="deploy_streamlit_app_ngrok">Step by step to Deploy Streamlit App via Ngrok 🚀</h1>  

## 1. Sign Up for Ngrok 🛠️  
- Create an account at [Ngrok](https://ngrok.com/).  

## 2. Install Necessary Extensions ⚙️  
- In the folder connected above, locate the **Jupyter** extension and install it in `collab-connect`.  

  ![image](https://github.com/user-attachments/assets/870db268-90a1-4353-ac59-0bb3aefde51d)  

## 3. Get Ngrok Token and Deploy 🌐  
- Retrieve your **Ngrok auth token** from [this page](https://dashboard.ngrok.com/get-started/your-authtoken) and copy it.  

  ![image](https://github.com/user-attachments/assets/36d76873-405c-4e08-9daa-f677d3af4ba0)  

- Open the file **deploy.ipynb**, locate the relevant section, and paste your token.  

  ![image](https://github.com/user-attachments/assets/0161ad5b-60c3-48d5-8c3e-1d0656707841)  

- Run all cells. If prompted, select **Jupyter Kernel**.  

  ![image](https://github.com/user-attachments/assets/84840b47-6ad1-4a2b-a0ec-15972f91e777)  

- After completion, you'll see a link to open your Streamlit app. Share this link with others.  

  ![image](https://github.com/user-attachments/assets/754a989b-857f-4563-9d0b-6e0fa0dcfa1b)  

---

***Note:*** The initial setup might take a few minutes!  

### Log Monitoring:  
You can check the log output in the file `nohup.out`.  

---

# Example Streamlit App 🎉  
![image](https://github.com/user-attachments/assets/35074b0d-d004-44db-977d-d8221d355342)  
