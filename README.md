# Information Assurance and Security - Final Project
### Magistrado Group of BSCS 3B ###
- Magistrado, Laurence O.
- Estadilla, Andrea Krystel T.
- Monte, Ylaiza Mae

## STEP-BY-STEP DOCUMENTATION

### 1. Install Headless Raspbian OS into Raspberry Pi.
- Raspberry Pi Imager is the quick and easy way to install Raspberry Pi OS and other operating systems to a microSD card, ready to use with your Raspberry Pi.
- Download and install Raspberry Pi Imager to a computer with an SD card reader. Put the SD card you'll use with your Raspberry Pi into the reader and run Raspberry Pi Imager.
- Here is the link for the [Raspberry Pi Imager](https://www.raspberrypi.com/software/)
- Open Raspberry Pi Imager. Choose Raspberrry Pi Device, Operating System, and Storage.
- In this project, we choose **_Raspberry Pi 3_** as device, **_Raspberry Pi OS (Legacy)_** as operating system, and our **_32GB SD Card_** as storage.
- After choosing the preferred device, OS, and storage, click **Next**.
- and click **Edit Settings** to customize the OS Settings.
- In the OS Customization, we set the host, username, and password as **group1**. We configure our wireless LAN available which is **CSPC BayanihanNet** and set the wireless LAN   country to **PH.** Lastly, we set our timezone to **Asia/Shanghai** since they have the same timezone (GMT+8) with Manila, then click **Save**.
- Don't forget to enable SSH and use password authentication, then click **Save**.
- Click **Yes** to apply our customized settings.
  > [!WARNING]
  > Make sure to backup all existing data in the SD card to avoid deletion while formatting.
- A warning will appear that all existing data on our SD card will be erased if we continue on our installation. Click **Yes** since our SD card have no existing files that needs to be backed up.
- OS writing on our SD card will then start
- After writing, verification will start.
- Wait until the verification hits 100%, and write succesfull prompt will appear. In this part, it's now safe to eject our SD card from the PC.
  > [!NOTE]
  > Plug in the SD card first on Raspberry Pi before proceeding to the next step.

### 2. Connect to Raspberry Pi via SSH (Secure Socket Shell) then update the OS ###
