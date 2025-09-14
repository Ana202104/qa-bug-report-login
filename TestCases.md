# Test Cases — Login

| ID   | Feature | Test Scenario                   | Precondition          | Steps                                                                 | Expected Result                                   | Status |
|------|---------|----------------------------------|-----------------------|----------------------------------------------------------------------|---------------------------------------------------|--------|
| TC01 | Login   | Valid credentials                | User has an account   | 1. Go to login page <br> 2. Enter valid email+password <br> 3. Login | User is redirected to dashboard                   | Pass   |
| TC02 | Login   | Invalid password                 | User has an account   | 1. Go to login page <br> 2. Valid email + invalid password <br> Login| Error message: **Invalid credentials**            | Pass   |
| TC03 | Login   | Empty fields                     | None                  | 1. Go to login page <br> 2. Leave fields empty <br> Login            | Error message: **Fields are required**            | Pass   |
| TC04 | Login   | Password reset request           | User forgot password  | 1. Click **Forgot password** <br> 2. Enter registered email <br> Send| Password reset email is sent                      | Pass   |
