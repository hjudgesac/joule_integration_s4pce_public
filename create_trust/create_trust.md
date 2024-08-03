1. From the Navigation Pane on the left, select **Trust Configuration**.  Click **Establish Trust**.</br>
![create_trust](1.jpg)

2. From the list of available SAP Cloud Identity Services tenants, choose the one that is also used by your S/4HHANA instance and click **Next**.      
**Note**: It's important to the choose the correct SAP Cloud Identity Services tenant.  The tenant chosen here must be the same as the one used by S/4HANA instance for which Joule is being configured.</br>      
![create_trust](2.jpg)   

3. From the Domain dropdown make sure to choose **<yourtenanthost>.accounts.cloud.sap** and click **Next**.</br>         
![create_trust](3.jpg)       

4. Leave the default settings and click **Next**.</br>        
![create_trust](4.jpg)

5. Review the information is correct and click **Finish**.</br>                                                       
![create_trust](5.jpg)

6. Confirm the new trust with SAP Cloud Identity Services is visible under **Custom Identity Provider for Applications**.</br>                                     
![create_trust](6.jpg)
