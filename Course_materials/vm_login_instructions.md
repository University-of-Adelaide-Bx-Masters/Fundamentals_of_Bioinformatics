# Connecting to your Virtual Machine

You have each been given access to a virtual machine that runs in a cloud compute environment and is accessed using the IP address below.
All cloud computing accounts are private but are identical and we will use these for the entire practical series. 
Accessing your cloud compute resource is like having your very own server. 

**Follow all instructions here very, very carefully**


### 1. Open an internet browser. 
We recommend Firefox, but Edge/Chrome are also acceptable. Safari has not been tested.

#### 2. Enter your login node address 
Paste the login node address (`https://rstudio-ubuntuN.adelaideuni.cloud:4200`) into the address bar, where N is your login node number. 
Ignore any warning about this being insecure.
Make sure the address begins with `https:` and **NOT** `http:`. 
You should see the login screen below.

<img src=".images/shell_in_a_box.png" alt="AWS RONIN shell in a box" height="500">


#### 3. Enter username and password for login node

Enter your Adelaide University anumber (this is your userID) and press enter. 

Enter the password you were assigned. 
You won't see anything happening while typing your password. Just finish typing it and press enter. 

You should see something like below if login is successful.

<img src="./images/shell_in_a_box_prompt.png" alt="AWS_RONIN_shell_in_a_box_prompt" height="500">

#### 4. Tell the login node to get your VM ready

Type `rstudio` and press Enter.

When asked `Would you like to start an Rstudio session?`, type `y` and press enter.

<img src="./images/shell_in_a_box_prompt_rstudio.png" alt="AWS_RONIN_shell_in_a_box_rstudio" height="500">

<img src="./images/shell_in_a_box_Rstudio_login_prompt.png" alt="AWS_RONIN_shell_log_in_OK" height="500">


    **Now you should see the following:** 

<img src="./images/shell_in_a_box_running.png" alt="Rstudio_login_from_shell" height="500">


Once your VM is ready, (this may take a couple of minutes) instructions on how to login to it will appear, similar to below:
These include:
- a web address similar to `http://rstudio-ubuntu2.adelaideuni.cloud:8001`
- your username for the session (your anumber)
- a onetime password for the session

<img src="./images/shell_in_a_box_Rstudio_credentials.png" alt="Rstudio_credentials_from_shell" height="500">

#### 5. Login to your VM

To login, copy the onetime password and then click the web address.
If clicking the web address doesn't open a new tab, you'll need to copy and paste it into a new tab. 

In the new tab, enter your username (your anumber), and the onetime password that was just generated. 

Click "Sign in". 

**Note:** You have 2 minutes from when the password was generated to login. If you don't login in time, you'll have to start again. 

<img src="./images/Rstudio_AWS_login.png" alt="Rstudio_login_screen" height="500">


You should now be in your Virtual Machine!!! 


Practice how to [disconnect from your VM](vm_logout_instructions.md) and then re-connect and go back to the practical instructions.

[Back to Intro to BASH Practical 1](../Practicals/fundamentals_of_bioinformatics/prac_1_introtobash1.md)


#### Important information

- Every time you log in to your VM you will be given a new one-time password that you have to paste into the Rstudio login panel.
- You can only have one VM running (per student) at a time. If you try to login to a second VM while you have a session already running, the existing session will be cancelled.
- RStudio sessions automatically shut down after 3 hours. If this happens and you are still working, log in again and you can resume where you left off. This is because we pay by the minute for access to this resource. Please remember to log out of RStudio and disconnect (see below) when you are done so that we don't pay for compute resources that are not being used. 


#### Troubleshooting

If copy and pasting your onetime password doesn't seem to work (and it's not been longer than 2 minutes since it was generated) try the following:
- Make sure you haven't copied any spaces as well
- Try to paste as `plain text` into the Password field
- Copy your password to a plain text document, and then re-copy it to the Password field
- Last resort, type the password by hand


