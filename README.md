# Beyondoner
A crowd funding website

# Initial Requirements
The frontend should be built using Next.js and Antd components, while the backend should be built with Django Python. The website should have the following pages: Home, Our Campaign, Celebrate With Us, Donate Us, Cart Page, About Us, and Our Impact. 

The Home page should have the following sections: 
1. A slider of images that fit the screen. 
2. Show all campaigns, three at a time as a square image, and slider with campaigns. 
3. Show more active campaigns with a square image of the campaign and information like how many items have been purchased and how many are pending, with a dynamic progress bar. Below each campaign, add a view more button. 
4. A FAQ section. 
5. A footer with contact details.

The Our Campaign page should display all existing campaigns with a square image of each. Clicking on any campaign should take the user to a specific campaign page.

The Campaign page should be dynamic and display details such as heading, header image, items that can be bought, prices, etc., taken from a Django backend. Pages should be dynamically added as new data is added to the backend. This page should also contain a PhonePe payment gateway integration that allows users to donate money according to selected items for the campaign.

The Celebrate With Us page should be similar to the Our Campaign page.

The Celebrate page should be similar to the Campaign page, but here, there will be no items to buy, only a single progress bar with donated money and pending money to meet the target.

The Donate Us page should be a simple page where users can donate as much as they want with a PhonePe payment integration to make a payment.

The Cart page should allow users to add multiple items from multiple campaigns and pay for them all at once.

Additionally, you should add dummy About Us and Our Impact pages.

The website should have the following backend requirements:
- Campaign API: This API should have CRUD capabilities and take info such as campaign name, header image, items (can be multiple), description, and comments. API data will be used by campaign pages in UI.
- Items API: This API should allow users to add items to pay for in campaigns, like shopping items. Users should be able to select items or add items to their cart and pay for them all at once. API data should include item name, item image, and item cost.
- Celebrate API: This API should have CRUD capabilities and take info such as Celebrate name, header image, payment range options, description, and comments. API data will be used by celebrate pages in UI.

Finally, you should host the website on a cloud or hosting platform of your choice, and ensure that the payment gateway process is secure. Let me know if you have any questions or need further clarification.
