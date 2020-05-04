If you're having troubles connecting to Keesu or the switcher doesn't install the certificate properly, you can try installing it manually.

### Instructions
- First, download the certificate [by clicking here](https://cdn.discordapp.com/attachments/598875990017703937/689445208177377306/keesu.cer)
- Then, open **keesu.cer**
- Click **Install certificate...**
- Click **Next**
- Select **Place all certificates in the following store** (second option), then click **Browse...**
- A new window will pop up, select **Trusted root certification authorities** and click **Ok**
- Click **Next**
- Click **Finish**

### Remove certificate

- Press **Win+R**  
- Type `mmc certmgr.msc` in the run box and press **enter** to open the Certificate Manager  
- Select **Trusted root certification authorities** on the left  
- Select **Certificates** on the right  
- You should see some **[Keesu CA Root X1](https://cdn.discordapp.com/attachments/672318363975811079/706093234216108032/unknown.png)**. Select them, **right click** and click on **Delete**  
- Select all the positive options (Ok/Yes etc)  
- Restart the switcher, click on **Inspect**, then choose **Install certificate**, then **Yes** 
