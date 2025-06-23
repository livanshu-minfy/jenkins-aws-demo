# this is the take home assignment of jenkins cicd

the objective of this assignment is Create a simple web application and push it to GitHub and then Create a Jenkins pipeline that automatically checks out our code and runs tests on our agent.

first i created a simple web app 

![image](https://github.com/user-attachments/assets/58259182-9dde-463c-b95a-f37c380e8eac)

after that i created a Jenkinsfile

![image](https://github.com/user-attachments/assets/b098db78-ea9f-45ad-b8aa-c8cd229fec4d)

and then i pushed the code to github.

After that i installed git in both master and agent machine

![Screenshot 2025-06-23 163858](https://github.com/user-attachments/assets/b18f9be4-0170-4823-9f3b-dc774b92fcba)

![Screenshot 2025-06-23 164343](https://github.com/user-attachments/assets/059392d1-f64a-4984-9d8e-f5f6a9da625f)

I also isntalled npm in my agent machine

![Screenshot 2025-06-23 164005](https://github.com/user-attachments/assets/7ad93974-e2dc-4a5e-a60d-ca5c4dafe138)

after that I created a pipeline and named it "my-first-pipeline-livanshu" on jenkins

![Screenshot 2025-06-23 164109](https://github.com/user-attachments/assets/34c2c17b-95ea-4d21-a7d3-cc2e46bd0c20)

after that i ran the pipeline

![Screenshot 2025-06-23 165615](https://github.com/user-attachments/assets/2861c0a8-f329-4b31-9dca-03c8892625aa)

the pipeline ran successfully, below is the screenshot

![Screenshot 2025-06-23 165633](https://github.com/user-attachments/assets/8f5c9469-0721-475b-9846-628f96da9ce7)

![Screenshot 2025-06-23 165640](https://github.com/user-attachments/assets/f5fe8f85-f08e-4020-b574-4da71db24a0c)

after this i have done terraform destroy and manually deleted the key pair too

![Screenshot 2025-06-23 172400](https://github.com/user-attachments/assets/b5e00e8b-1905-46d4-b5a6-1ce71a9a8be5)
