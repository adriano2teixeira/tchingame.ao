# tchingame.ao
**Tchingame vouchers**

![](Aspose.Words.bda12147-dbb5-43f3-8eab-4c07f40fa23e.001.png)

Tchingame is a voucher/discounts platform, it allows users to get unique discounts so they can go to stores and purchase items cheaper.

\*\*\* OBS \*\*\*  : I was product development leader in a team of two developers, the other developer did quit soon and I had to assume the project alone. I can’t show the code because of the company’s policies , but either way you can check out the website live on https://tchingame.co.ao .

**INFRASTRUCTURE:**

![](Aspose.Words.bda12147-dbb5-43f3-8eab-4c07f40fa23e.002.png)

**BACKEND:**

- NodeJS - Rest API 
- Wordpress - Handle Store Owner stuff and shopping process.
- Mysql - Single Source of Truth
- Redis - For Caching the products and Storing the vouchers Queue
- Firebase - Handles the Website analytics .

**FRONTEND:**

- ReactJS/NextJS
- React Query

How it works:

Users can create accounts and sign in into their accounts, Store owners can also create accounts and log into the store admin panel , they can create and publish new products with the actual price and the discount price with a specific amount of items available for discounts .



This products are shown on the Website so users can see them and reserve a voucher removing temporary respective units from the product stock , this units are going to hiden for while until the  user go to the store and purchase the item with discount (on the reserve step users will get a QR Code for the voucher). Every product has a limited reservation time so when this time ends after reservation (the user reserves but does not buy it) the reserved units are going to be added to stock and then be available again.



