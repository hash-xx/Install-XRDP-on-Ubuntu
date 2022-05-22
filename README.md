# Install-XRDP-on-Ubuntu
 Install XRDP with Mate-desktop-environment in Ubuntu

## Instructions

#### Step 1 - Connect to your VPS using SSH

#### Step 2 – Install XRDP Package from Ubuntu Repository

>sudo apt-get install xrdp

#### Step 3 – Install an alternative Desktop 

>sudo apt-get update

>sudo apt-get install mate-core mate-desktop-environment mate-notification-daemon

#### Step 4 – Configuring XRDP to use your desktop environment

>sudo sed -i.bak '/fi/a #xrdp multiple users configuration \n mate-session \n' /etc/xrdp/startwm.sh

#### Step 5 - Connect to the VPS using Remote Desktop

>Open "Remote Desktop"

>Enter the IP of your VPS and Connect

> Leave the Session as "Xorg"

>Enter your username and password of your VPS

>Click "ok"

 ## Get in touch with me
>[My Website](https://sasandara.studio)

>[Discord](https://discord.gg/G3gxzRFGQ2)

>[Facebook](https://www.facebook.com/sasandaradev)

>[Twitter](https://twitter.com/SasandaraDilmin)