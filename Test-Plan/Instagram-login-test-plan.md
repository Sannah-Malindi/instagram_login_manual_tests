# Instagram Login – Simple Test Plan

## 1. Introduction
This test plan covers the manual testing of the Instagram Login feature.  
The goal is to check if users can log in with valid details and that the app displays correct error messages for invalid details.

## 2. Scope
### In Scope:
- Login with username, email, or phone number
- Login with valid and invalid passwords
- Error messages
- Empty field behavior
- Basic UI checks on the login page

### Out of Scope:
- Sign up process
- Forgot password / reset password
- Two-factor authentication (2FA)
- Performance or security testing

## 3. Test Objectives
- Confirm that valid login attempts are successful  
- Confirm that invalid login attempts show accurate error messages  
- Check that empty fields prevent login  
- Make sure the login button and fields behave correctly  

## 4. Test Approach
Testing will be done manually using:
- Functional testing  
- Negative testing  
- UI and error message validation  

Bug reporting will be done in **Jira**.

## 5. Test Environment (Specific)
Testing was performed under the following environment:

### Device Details
- Device: **iPhone 12**  
- OS Version: **iOS 18.6.2**  
- Screen size: **6.1 inches**

### Application Version
- Instagram Mobile App  
- Version: **Latest available on the App Store as of November 2025**

### Network
- Wi-Fi connection: **100 Mbps**  
- Mobile Data: **Vodacom 4G** (used as backup)

### Browser (if applicable)
- Safari Version: **iOS default browser**

### Account Setup
- 1 valid Instagram account  
- Multiple invalid test credentials created for negative testing

## 6. Test Data
- Valid username  
- Valid email  
- Valid phone number  
- Valid password  
- Invalid usernames & invalid passwords  

## 7. Test Deliverables
- Test Plan  
- Test Cases  
- Actual Results  
- Screenshots  
- Bug Report (TC_009)  

## 8. Entry Criteria
- Instagram app installed  
- Test data ready  
- Device connected to the internet  

## 9. Exit Criteria
- All test cases executed  
- All high bugs logged  
- 1 bug found (**TC_009**)  

## 10. Risks
- Slow network may cause unexpected behavior  
- App UI may change after updates  

## 11. Conclusion
Testing the Instagram Login feature ensures that users can log in correctly and that the system handles invalid credentials properly.
