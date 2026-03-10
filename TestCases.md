# Test Cases

| TC_ID | Module       | Test Scenario                            | Test Steps                                           | Expected Result                   |
| ----- | ------------ | ---------------------------------------- | ---------------------------------------------------- | --------------------------------- |
| TC_01 | Registration | Verify user registration with valid data | Enter valid name, email, password and click register | User should register successfully |
| TC_02 | Registration | Verify registration with existing email  | Enter already registered email                       | Error message displayed           |
| TC_03 | Login        | Verify login with valid credentials      | Enter email and password                             | User logged in successfully       |
| TC_04 | Login        | Verify login with invalid password       | Enter wrong password                                 | Error message displayed           |
| TC_05 | Search       | Verify product search                    | Enter product name in search bar                     | Relevant products displayed       |
| TC_06 | Cart         | Verify add to cart                       | Select product and click add to cart                 | Product added to cart             |
| TC_07 | Checkout     | Verify checkout process                  | Click checkout button                                | Checkout page opens               |
| TC_08 | Payment      | Verify payment option                    | Select payment method                                | Payment processed successfully    |
