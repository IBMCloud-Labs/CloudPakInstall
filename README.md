# CloudPakInstall
How to install IBM Cloud Paks to IBM Cloud with Red Hat OpenShift

# Deploy Cloud Pak With OpenShift on IBM Cloud

1. [Register](https://cloud.ibm.com/registration) or [sign in](https://cloud.ibm.com/login) to IBM Cloud. 
2. After login, navigate to catalog at top right navigation bar, then software in the left hand drop down menu, lastly click on Cloud Paks. Select the Cloud Pak you would like to install. 
![](https://paper-attachments.dropbox.com/s_F4983B98B556DB0069EDA1DCEB017BC7A4BEB8FC335DB1A90EDB7A08149814ED_1594062867902_Screen+Shot+2020-07-06+at+11.35.58+AM.png)

3. Take a look at the minimum requirements for the OpenShift cluster required for the Cloud Pak and write this down. Here for example, the minimum requirements is 3 nodes with 4 cores, 16 GB memory, and 20 GB disk per node. 
![](https://paper-attachments.dropbox.com/s_F4983B98B556DB0069EDA1DCEB017BC7A4BEB8FC335DB1A90EDB7A08149814ED_1594622365423_Screen+Shot+2020-07-12+at+11.38.59+PM.png)

4. Head to https://cloud.ibm.com/catalog in a new tab. Type in “Red Hat OpenShift.” Click on it. 
![](https://paper-attachments.dropbox.com/s_F4983B98B556DB0069EDA1DCEB017BC7A4BEB8FC335DB1A90EDB7A08149814ED_1594624776872_Screen+Shot+2020-07-13+at+12.18.47+AM.png)

5. On the OpenShift cluster form,  keep the default version, scroll down and pick your data center according to geography, availability and region. You need 3 worker zones, which is the default. Feel free to change the name of the cluster to reflect the cloud pak work or project you are working on. 
![](https://paper-attachments.dropbox.com/s_F4983B98B556DB0069EDA1DCEB017BC7A4BEB8FC335DB1A90EDB7A08149814ED_1594624987484_Screen+Shot+2020-07-13+at+12.22.09+AM.png)

6. Pick your “flavour” under worker pool, and select the right cluster size according to your cloud pak installation requirements you wrote down from earlier. Click “create” on the right hand and allow 10-15 minutes for Red Hat OpenShift cluster to instantiate and complete. Follow the live updates on the web page. 
![](https://paper-attachments.dropbox.com/s_F4983B98B556DB0069EDA1DCEB017BC7A4BEB8FC335DB1A90EDB7A08149814ED_1594625093312_Screen+Shot+2020-07-13+at+12.22.27+AM.png)

7. Once cluster is instantiated, head back to https://cloud.ibm.com/catalog then select “software” and “cloud pak” on left hand menu. Select your Cloud Pak of choice. Under the drop down menu click on the name of the cluster you just provisioned. 


![](https://paper-attachments.dropbox.com/s_F4983B98B556DB0069EDA1DCEB017BC7A4BEB8FC335DB1A90EDB7A08149814ED_1594625448927_Screen+Shot+2020-07-13+at+12.30.05+AM.png)

8. Scroll down and click on “run script” to run the preinstallation script required for cloud pak installation authorization.  
![](https://paper-attachments.dropbox.com/s_F4983B98B556DB0069EDA1DCEB017BC7A4BEB8FC335DB1A90EDB7A08149814ED_1594625860576_Screen+Shot+2020-07-13+at+12.30.24+AM.png)

9. Next, accept deployment values or change the parameters. Then finally, click on the right, I have read and agree to the following license agreements.” 


10. Once installed successfully, head over to https://cloud.ibm.com/catalog and click on the three lines, the hamburger at the top left hand. Select “schematics.” 


![](https://paper-attachments.dropbox.com/s_F4983B98B556DB0069EDA1DCEB017BC7A4BEB8FC335DB1A90EDB7A08149814ED_1594626192960_Screen+Shot+2020-07-13+at+12.41.44+AM.png)


 11. Click on the workspace you just deployed. This will take you to this page. Then click on “offering dashboard.”

![](https://paper-attachments.dropbox.com/s_F4983B98B556DB0069EDA1DCEB017BC7A4BEB8FC335DB1A90EDB7A08149814ED_1594626600505_Screen+Shot+2020-07-13+at+12.49.10+AM.png)


 12. You can now begin your Cloud Pak work. Congrats you have successfully installed your first Cloud Pak on IBM Cloud!

![](https://paper-attachments.dropbox.com/s_F4983B98B556DB0069EDA1DCEB017BC7A4BEB8FC335DB1A90EDB7A08149814ED_1594626859801_Screen+Shot+2020-07-13+at+12.49.23+AM.png)


**Additional Resources**

How-to Videos for CloudPak plus OpenShift on IBM Cloud: 
[https://youtu.be/gBI0ApHUFSs](https://youtu.be/gBI0ApHUFSs)

**Contacts for Questions**

Helen Lam | helen.lam@ibm.com | @helennnsays 
Steve Martinelli | stevemar@ca.ibm.com | @stevebot 


