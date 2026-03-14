# Checkout Test Cases

## TC-01 – Checkout with valid information

Steps:
1. Login with valid credentials
2. Add product to cart
3. Go to cart
4. Click Checkout
5. Complete First Name, Last Name and Postal Code
6. Click Continue
7. Click Finish

Expected result:
Purchase completed successfully.

---

## TC-02 – Checkout with empty form

Steps:
1. Login
2. Add product
3. Go to cart
4. Click Checkout
5. Click Continue without filling the form

Expected result:
Error message displayed indicating required fields.

---

## TC-03 – Remove product before checkout

Steps:
1. Login
2. Add 3 products to cart
3. Remove 1 product
4. Go to checkout

Expected result:
Only remaining products appear in checkout.

---

## TC-04 – Refresh page during checkout

Steps:
1. Login
2. Add product to cart
3. Start checkout
4. Refresh browser page

Expected result:
Cart state remains unchanged.
