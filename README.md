# Cloud-Services-Deep-Dive
Multi-Cloud Infrastructure Automation and Optimization

## Scope
This project covers multiple core services on various cloud platforms. This project is WIP and as I dive into additional services this will be expanded.

## Services
`AWS`

**ECS** Container orchestration and administration via AWS

**IAM** Users, groups and policies administration and management - Identity and Access Management

## Environment
- AWS GUI Console
- Cloudshell
  
## Tasks - IAM

### Determine the number of created users using the GUI.
![Step1](images/step1.png)

### Validate logged-in user deatils using Cloudshell.
![Step2](images/step2.png)

### Validate user does not belong to any groups using the GUI.
![Step3](images/step3.png)

### Create user and attach ReadOnly policy.
![Step4](images/step4.png)

### Confirm both users are now showing as created and available via the GUI.
![Step5](images/step5.png)

### Validate what permissions the ReadOnlyAccess policy provides by reviewing the JSON file.
![Step6](images/step6.png)

### Ceate second user and attach the ViewOnlyAccess policy.
![Step7](images/step7.png)

### Validate what permissions the ViewOnlyAccess policy provides by reviewing the JSON file.
![Step8](images/step8.png)

### Detach ReadOnlyAccess policy from user 1.
![Step9](images/step9.png)

### Create group 1 and attach ReadOnlyAccess policy to it.
![Step10](images/step10.png)

### Add user 1 to group 1.
![Step11](images/step11.png)

### Create group 1 and attach ViewOnlyAccess policy to it.
![Step12](images/step12.png)

### Detach ViewOnlyAccess policy from user 1.
![Step13](images/step13.png)

### Add user 2 to group 2.
![Step14](images/step14.png)
