# Magento2 Order Details On Success Page

This plugin is created to get order Details (shipping details, Billing Details item SKU's etc.) in order to send these details to the third party softwares using their API's or to implement the tracking codes on the success page.

How to use: 
1) Clone the repository/Download as Zip
2) Create folder app/code/K2/Orderdetails 
3) Copy the content of this repository within the folder.
4) Run command php bin/magento setup:upgrade 
5) Customize the code in app/code/K2/Orderdetails/view/frontend/templates/success.phtml page as per your requirement to use the Order details data.