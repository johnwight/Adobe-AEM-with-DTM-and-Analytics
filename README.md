# Adobe-AEM-with-DTM-and-Analytics
Configure Your Adobe AEM Site for DTM and Analytics

To configure Adobe Experience Manager (AEM) for Dynamic Tag Management (DTM) and Analytics:


1. From your Adobe [DTM Account Dashboard](https://dtm.adobe.com), click on your company name.

    ![dtm dashboard](https://user-images.githubusercontent.com/29133525/34694472-7157a700-f484-11e7-9a63-6cb8dcb1a2db.png)


1. On the company dashboard, click the **Add Property** button.

    ![add property](https://user-images.githubusercontent.com/29133525/34694527-9e07689e-f484-11e7-922f-a26c0124037d.png)


1. On the **Create Property** form, specify a **Name** and a **URL** and click **Create Propery**.

    ![create property](https://user-images.githubusercontent.com/29133525/34694566-c7bd3128-f484-11e7-8576-bef30d6b19e0.png)
    
1. On the company dashboard, use the filter field to search for the property you created in the previous step.

    ![property filter](https://user-images.githubusercontent.com/29133525/34694876-e424f3a4-f485-11e7-979b-1cba11c52ef8.png)

1. Select the property from the search results.

1. In AEM, click **Tools** > **Operations** > **Cloud** > **Cloud Services**.


1. Under **Dynamic Tag Management**, click **Configure Now**.

    ![configure now](https://user-images.githubusercontent.com/29133525/34695129-e50f2f22-f486-11e7-991d-f1845ef05b2f.png)


1. On the **Create Configuration** box, specify a **Title** and click the **Create** button.

    ![create box](https://user-images.githubusercontent.com/29133525/34695269-6f46eda6-f487-11e7-923b-44d36795d641.png)


1. On the Dynamic Tag Management Settings box that appears in DTM Settings, provide the following information:

    * API Token
    * Company
    * Property

    ![dynamic tag management settings box](https://user-images.githubusercontent.com/29133525/34695571-9f68c8a0-f488-11e7-9cf0-e3541780f1df.png)

    1. To retrieve the API token:
    
        1. Return to the DTM Dashboard and click the Profile icon and then click **DTM Account**.
        
            ![click dtm account](https://user-images.githubusercontent.com/29133525/34695898-d2b30fee-f489-11e7-9c9a-27086af832b0.png)

        1. On the DTM **Edit Account** screen, scroll to the bottom to find and copy the **API Token**.

            ![api token value](https://user-images.githubusercontent.com/29133525/34696051-7e2ddf34-f48a-11e7-8df1-6e15836c5e49.png)
            
1. After pasting the token into the Dynamic Tag Management Settings box, click the Connect to DTM button to test it.



You should receive a message indicating that the connection is successful.




