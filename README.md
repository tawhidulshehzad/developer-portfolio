














6. 

     

7. If a user(buyer/seller/admin) is logged in, they will see **logout** (should be working) and another option on the header called Dashboard. The dashboard routes will change based on the users:

      **Buyers will see:** My orders(see bonus requirement 7),

      **Sellers will see:** Add A product (See Requirement 8), My Products(see requirement 9), My buyers(this one is optional).

      **Admin will see:** All Sellers, All Buyers (see requirement 12), Reported Items



9. On the **"My Products"** page, display sales status (available or sold), price, and any other relevant information you want to show. A seller will be able to delete any of his/her product. Please note there will be a special button for each unsold/available product where the seller can hit the button to advertise. 

10. The advertised items will appear on the home page. Please note if there are no items marked as advertised, the advertised items section won't be displayed on the home page. The advertised section will only appear if there is one or more available (unsold items) are marked to be advertised.



## Bonus Requirements

4. Implement an extra feature: **WishList** or **Report to Admin**(choose one) in the /category/:id route. A buyer can make a product to his/her wishlist or report an item by clicking a relevant button. If you have implemented the wishlist feature, show them in the buyer's Dashboard in a separate route, "My WishList." A user should be able to purchase the item from the wishlist page. (Just redirect the user to the purchase page)

   If you have implemented the "report to admin" feature, show the reported items in the admin dashboard in a separate route, "Reported Items" (tips: create a separate collection for the wish list and filter by user email address). An admin will be able to delete a reported item. 


7. The **My Orders** route will have a table/cards. Each card/ table row will be an order having an image, title, price, and a pay button. On clicking the pay button, to take the user the payment page with fields for card details will pop up, or the user will be taken to a route where there will be a form for filling up card details. Save the payment information in the database and inform the user via a modal/toast. Don't forget to update the button text to "paid" after payment. Please note, payment will be done by Stripe. 

      Once an item is paid, it won't be displayed on the advertised item or on the category page. Only available items will be displayed to be purchased.







### Optional

1. Explore [react-image-gallery](https://www.npmjs.com/package/react-image-gallery)and use a slider instead of a picture in your /advertisement/:id route
2. Add generic modal
3. Add a search bar on the homepage and show advertisements based on the search key
4. Add animation on the homepage
5. Add another route," **My Buyers,"** where you will have to show the Buyers name, email, item purchased, etc.
6. Create a Make Admin route for the admin. Here an admin (admin only) will be able to make any buyer or seller an admin.

### **What to submit**

1. Client-side code GitHub repository
2. Server-side code GitHub repository
3. Live website link
4. **IMPORTANT:** For the examiners to check your admin routes, create a user for your site, give the email address: admin role and add this user's credentials in the client side readme in this **exact format** :

adminEmail: \<your admin email\>

adminPassword: \<your admin password\>

Otherwise, you won't get any marks for your admin routes.
