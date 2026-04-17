# Automation-testing-for-Amazon2
This project focuses on manual testing of an e-commerce web application similar to Amazon. The goal is to validate core functionalities such as login, search, cart, checkout, and payment.
Ecommerce-Manual-Testing/
│
├── Test_Scenarios.xlsx
├── Test_Cases.xlsx
├── Bug_Report.xlsx
├── Screenshots/
└── README.md
1 Test_Cases.xlsx
Test Case ID | Module | Test Scenario | Steps | Expected Result | Actual Result | Status
TC_01 | Login | Valid Login | Enter valid email & password | Login successful | Login successful | Pass
TC_02 | Login | Invalid Password | Enter wrong password | Error message shown | Error displayed | Pass
TC_03 | Login | Empty Fields | Click login without data | Validation message | Validation shown | Pass
TC_04 | Login | Invalid Email | Enter invalid email | Email error | Error shown | Pass
TC_05 | Search | Search Product | Search "mobile" | Relevant products | Products shown | Pass
TC_06 | Search | No Result | Search "xyz123" | No results message | No results shown | Pass
TC_07 | Search | Auto Suggestion | Type "lap" | Suggestions appear | Suggestions shown | Pass
TC_08 | Search | Apply Filters | Apply price filter | Filtered results | Filter works | Pass
TC_09 | Cart | Add to Cart | Add product | Product added | Added successfully | Pass
TC_10 | Cart | Remove Product | Remove item | Product removed | Removed | Pass
TC_11 | Cart | Update Quantity | Change quantity | Quantity updated | Updated | Pass
TC_12 | Checkout | Proceed Checkout | Click checkout | Redirect page | Redirected | Pass
TC_13 | Checkout | Add Address | Enter address | Address saved | Saved | Pass
TC_14 | Checkout | Invalid Address | Leave fields empty | Validation error | Error shown | Pass
TC_15 | Payment | Successful Payment | Enter valid details | Order placed | Success | Pass
Bug_Report.xlsx
BUG_02 | Cart | Change quantity | Quantity updated | Not updating | High | High | Open
BUG_03 | Payment | Invalid card details | Error message | Page refresh only | High | High | Open
BUG_04 | Search | Search laptop | Relevant results | Irrelevant items | Medium | Medium | Open
BUG_05 | Checkout | Checkout without address | Validation error | Proceeds | Critical | High | Open

Test_Scenarios.xlsx
TS_01 | Verify login functionality
TS_02 | Verify search functionality
TS_03 | Verify add to cart
TS_04 | Verify remove from cart
TS_05 | Verify checkout process
TS_06 | Verify payment process
TS_07 | Verify validation messages
TS_08 | Verify UI elements
TS_09 | Verify filters
TS_10 | Verify order summary
login_success.png
login_error.png
cart_update.png
