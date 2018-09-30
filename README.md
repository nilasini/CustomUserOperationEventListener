# CustomUserOperationEventListener
Assign password policy satisfied random password for ask password user

1) Stop the server if it is already running
2) Build the project using following command ```mvn clean install```
3) Copy the jar file org.wso2.carbon.sample.user.operation.event.listener-1.0.0.jar from the target directory to <IS_HOME>/repository/components/dropins folder
4) Start the server
5) Enable ask password and password policy feature
6) Add a user with ask password option
7) User will be added successfully

Refer \[1] to understand the implementation details.

\[1] https://medium.com/@nilasini/handle-password-policies-while-using-ask-password-option-in-wso2is-5-5-0-79335e64c148
