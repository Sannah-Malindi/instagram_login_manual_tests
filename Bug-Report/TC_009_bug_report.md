# TC_009 – Bug Report  
Incorrect error message displayed when both username and password fields are empty

## 1. Summary
When both the username and password fields are left empty on the Instagram login screen, the app does not display the correct error message.  
The message shown does not correctly instruct the user to enter both fields.

## 2. Environment
- **Device:** iPhone 12  
- **OS Version:** iOS 18.6.2  
- **App Version:** Instagram (Latest version, November 2025)  
- **Network:** Wi-Fi 100 Mbps / Vodacom 4G  
- **Test Type:** Manual Testing  

## 3. Precondition
- Instagram app installed and logged out  
- Stable internet connection  
- App opened on the login screen  

## 4. Steps to Reproduce
1. Open the Instagram mobile app.  
2. Leave the **username** field empty.  
3. Leave the **password** field empty.  
4. Tap the **Log In** button.  

## 5. Expected Result
A clear and specific error message should appear, such as:  
- "Please enter your username and password."  
or  
- "Username and password cannot be empty."

## 6. Actual Result
A different error message appears, or the app shows no error message at all.

## 7. Status
New

## 8. Severity
Medium  
(Incorrect validation messaging can confuse users, but does not break core functionality.)

## 9. Priority
Medium  
(Should be corrected for better user experience) 

## 10. Attachments
- Screenshot of the error message  
- Screenshot of Jira bug entry 

## 11. Linked Test Case
**TC_009 – Empty username field and empty password field**
