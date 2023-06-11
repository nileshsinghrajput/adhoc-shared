# Sample WebApp hosted on container
Host your own first web application on container securely over AWS Cloud. Attached below is the architecture of the infrasturcture that the cloudformation script aims to deploy in the environment. <br />

Pre-requisites: <br />
1. Basic understanding of AWS Cloud  <br />
2. An active AWS account with access to provision the infrastructure <br />


![WebAppHosting-Infrastructure](https://github.com/nileshsinghrajput/adhoc-shared/blob/a71772aab6a366641132827efd5efbe022932606/WebAppHosting-Infrastructure.jpg) <br/>


### **Miscellaneous:** <br/>
**Find User data logs within server:** /var/log/cloud-init-output.log <br/>
**Login the server:** The servers are hosted in private subnet hence they can only be logged in via Systems Manager. Follow below steps to connect to a Linux instance using Session Manager using the Amazon EC2 console <br/>
1. Open the **Amazon EC2 console** <br/>
2. In the navigation pane, choose **Instances.** <br/>
3. Select the instance and choose **Connect.** <br/>
4. For Connection method, choose **Session Manager.** <br/>
5. Choose **Connect.** <br/>
