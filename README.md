# Skyline Dynamics Android Dev Test
Thank you for taking the time to complete our Android Dev Test. The test is setup to demonstrate your capabilities as an Android developer.
- You will have **one week** to complete and submit the test
- You do **not** need to provide a finished production-ready app, we are more interested in seeing how you tackle the tasks with critical thinking and how you demonstrate problem-solving through the use of technical solutions
- You will also be graded on the following criteria:
  - Ability to reproduce the design provided with consideration of performance
  - Ability to implement implied functionality by interpreting the designs provided
  - Clean code structure and maintainability of code

## Task
 The primary task is to build a proof-of-concept shopping cart, wherby a user can add products to their cart and process the order through a checkout form
  - Fetch the product items from the provided `products.json` file to display on the *Product Listing* view based on the design
  - The cart contents should update in real-time when a user adds a product to the cart
  - Cart contents should persist throughout the users session, including on refresh, until the user clears their contents or places an order
  - Each submitted order should have a unique identifier and there should be checks in place to determine if it is unique
  - Upon checkout, the order data should be saved locally to a `.json` file labelled with the  unique order ID e.g `order_2948281.json`

## Design
* The design in provided in this [Figma link](https://www.figma.com/file/etoGjuqRvMrVAISq0BkOEt/android_dev_test_screens?type=design&mode=design&t=2kIuEXpHOqo5PK05-1)
* We have also provided PNG screens to use for reference

## Implementation
* You are required to make an Android App using Kotlin
* You can use any framework or libraries you are comfortable with to achieve the required tasks

## Submissions
* Once done, upload your work to Github and share with us the link. This more preferable since we would also like to see your Git skills.
* Alternatively, you can compress your work to a `.zip` file labeled `{{your_name}}.zip` containing your source files.
* Which ever you choose, it should contain a `README` describing how to compile/run your test.
