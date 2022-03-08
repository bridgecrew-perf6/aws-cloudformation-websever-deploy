# aws-cloudformation-websever-deploy

This CloudFormation Infrastructure as Code module allows you to deploy a Web Server stack that is publicly available on an EC2 instance.

To Use:

1.  clone the repository.
2.  Sign into your aws console.
3.  Navigate to EC2 -> Key Pairs
4.  Click Create Key Pair
5.  Provide a [Key_Pair_Name] and click Create
6.  Navigate CloudFormation.
7.  Click Create stack.
8.  Select Template is ready.
9.  Select Upload a template file
10. Click on Choose file and upload the cf-webserver-deploy.json or cf-webserver-deploy.yml file.
11. Click View in Designer.
12. Click the checkbox at the top to validate.
13. Click the cloud icon with the up arrow to create the stack
14. Click Next
15. On the stack details page, provide the value of your choice
    Stack name: [NAME_OF_THE_STACK]
    InstanceType: [TYPE_OF_INSTANCE]
    keyName: [THE_KEY_NAME_CREATED_EARLIER]
16. Click Next
17. Leave the default settings on the stack options page
18. Click Next
19. Click Create stack
20. Once all creation of all resources and stack is complete, click the Ouputs to view the URL
21. Open the URL listed in a new browser tab to access the webserver.
