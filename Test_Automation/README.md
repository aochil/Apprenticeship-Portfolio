## Automation Testing in AMEX Team
My current role in my AMEX team is a QA Engineer. 
I am responsible for:
- Developing and maintaining UI and API automations. 
- Testing new features and event pages.
- Detecting flaws in our end-to-end systems.


## Technologies
- Maven 
- Java 18
- TestNG
- Selenium
- Jenkins
- DBeaver
- Postman
- Excel

## Competencies
### JF 5.4
- **Understands and is able to identify and create test scenarios**
- Before I begin testing, I must understand how the application/feature works.
- Once the new changes are deployed in the QA environment, I proceed to try all the positive test case scenarios first. 
  These scenarios consist of how the application/feature is intended to function. 
- Then I test the negative test case scenarios, which displays an error if a user was to perform an action that's not permitted.
  For example, submitting forms with blank inputs, submitting duplicate emails, failing to check mandatory checkboxes, and so on. 
- Finally, I search for unanticipated corner cases and defects, instances that developers overlook. 
  These circumstances arise when the application is unable to respond to numerous variables at the same time.
- Once I gather all the data, I utilize Selenium to automate all scenarios.   
- The completed automation will run through all the test case scenarios and validate the whole functionality of the application.
  Performing all these test cases manually will take hours at time, whereas the automation will take only a few minutes.
  Automations also pinpoint exactly where the application is failing, saving time on debugging. Last but not least, 
  automation tests eliminate human error in order to preserve test consistency. 

### JF 3.8
- **Can encrypt sensitive data via hashing**
- We use Excel to structure and organize test cases. Sensitive data are also stored but with increased protection.
- Credit card numbers are encrypted, saved in Excel sheets and decrypted using our proprietary hashing API during automation.
- If an unauthorized person was to get access to our Excel sheets, they will only see the encrypted value and will be unable to do anything with it.  
- Methods like these provide additional security and keep company data safe.

### JF 4.6
- **Can test code and analyze results to correct errors found using unit testing**
- When doing regression testing, a test case scenario failed.
  The developer failed to provide required header data, resulting in a failed form submission.
  This problem was handled swiftly since I was able to pinpoint where and how the failure occurred and immediately notified the developer.
- I tested an existing component with multiple new versions. During manual testing, it worked perfectly.
  After I developed automation for it, it failed at a certain version. The divider element obstructed the Selenium driver's ability to click the submit button.
  Another reason automated testing is crucial since automated testing found a flaw that the naked eye couldn't see. I demonstrated the failure and used Chrome developer tools to showcase the overlapping.
  The developer realized the problem and quickly resolved it.
- In another instance of regression testing, the whole test failed in the QA environment but not at the development environment.
  In order to access our internal page, a user is redirected a login page maintained by a different team, which they altered certifications without notifying our team.
  My automation test detected this right away and I alerted our team. Our team was able to overcome this issue and continue with development.
  This problem would have caused significant development delays if it had not been identified. 
