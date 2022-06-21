## Born2BeRoot Step by Step Guide from Start to End of This Project

This guide is in 7 Parts: 
- Part 1 - Downloading Your Virtual Machine
- Part 2 - Installing Your Virtual Machine
- Part 3 - Starting Your Virtual Machine
- Part 4 - Configurating Your Virtual Machine
- Part 5 - Connecting to the SSH Server
- Part 6 - Continue Configurating Your Virtual Machine
- Part 7 - Your Born2BeRoot Defence Evaluation

## Part 1 - Downloading Your Virtual Machine

1. Click on this link https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/

2. Scroll to the bottom of the website and click `debian-11.3.0-amd64-netinst.iso` (3rd from the bottom), if that doesn't work, then you can try either `debian-edu-11.3.0-amd64-netinst.iso` or `debian-mac-11.3.0-amd64-netinst.iso`

3. Place that download into the **goinfre** `/Users/your_login/goinfre` if you are installing on the 42 Campus.


## Part 2 - Installing Your Virtual Machine

1. Click on `New`
![1*tkjZEbnHKqPGN24HQw_kRA](https://user-images.githubusercontent.com/58959408/174700376-2862e8e9-0a7a-4681-af3b-e82dbc7d9aa5.png)

2. Change Machine Folder to `/Users/your_login/goinfre` and then click `continue` to move on to the next step
![1*WyFDl98AZfft999XCKD6kA](https://user-images.githubusercontent.com/58959408/174700651-8dc8e0a9-7709-4202-8a12-12a384ff6e3e.png)

3. Set Memory Size as `1024 MB` and click continue
![1*SoVNIKT340ARlLvQ7RuwDA](https://user-images.githubusercontent.com/58959408/174701125-7a285b0d-7036-4bef-926b-271b0032d7ad.png)

4. Click `Create a Virtual Hard Disk Now` and then click `Create` to create the Hard Disk
![1*PzVboJLyLTs7qJmgbdoBYA](https://user-images.githubusercontent.com/58959408/174701209-a5d10ea3-c634-4d49-b099-01d538fe0517.png)

5. Click `VDI (VirtualBox Disk Image)` and then click `Continue` to select VDI
![1*6_D9jIyOW0jE3a6vF_UzXg](https://user-images.githubusercontent.com/58959408/174701340-d84f6c80-e09b-43ae-b31a-6dd5d6306f23.png)

6. Click `Dyamically Allocated` and then click `Continue` to only use space on your Hard Disk
![1*HagpR-UD0HWCb7zRTeSQXQ](https://user-images.githubusercontent.com/58959408/174744677-eac5b679-49f7-4881-a59b-00a420cbe640.png)

7. Set Size as `12.00 GB` and then click `Continue` this should be enough for this project
![1*rYdYJbPswCVCUa5pwKcRZA](https://user-images.githubusercontent.com/58959408/174745855-73880988-be69-45cc-bb6d-7c6c1a40c1ac.png)

8. Click `Settings` and then click `Storage` to view your Virtual Machine Storage
![1*V2wtat5wJyBjSEoXatkG0A](https://user-images.githubusercontent.com/58959408/174701830-69f7b13c-ac5d-44c2-9f05-de8fd8dcc6f5.png)

9. Click on `Optical Drive` (Optical Drive - far right blue small box)
![1*je75kGWjXl0M6PlqEzHgoA](https://user-images.githubusercontent.com/58959408/174701924-0c69938f-10ec-498f-adec-bacf073b4b99.png)

10. Click on `Choose a disk file...` (2nd option in the drop down)
![1*VDy31g0tePnUOuJ1cZQsxQ](https://user-images.githubusercontent.com/58959408/174702002-9b4fe4d2-3008-4375-9ec1-57f5e1425eb8.png)

11. Then click on the Virtual Machine file you downloaded and placed into `goinfre` from before
![1*FOldzHFaQ2JS_phe6z6T4g](https://user-images.githubusercontent.com/58959408/174702161-957eb0b6-2803-407f-b018-c02f7615f027.png)

12. Click on your `Virtual Machine` and then click `'ok` to confirm you Virtual Machine Storage
![1*Evj7Z2EOq102A1zUVgUnQg](https://user-images.githubusercontent.com/58959408/174702820-824e0acf-f919-4bfb-a619-eea8068fe309.png)

13. Click `Start` (The Green Arrow ➡️) to start your Virtual Machine
![1*Yg53c1-01g4VzTqhcVEEcA](https://user-images.githubusercontent.com/58959408/174702806-1bd8fce3-aac6-44b3-84d9-c76252dfecd8.png)


## Part 3 - Accessing Your Virtual Machine

1. Use arrow keys 🔼 🔽 and press `Enter` on `Install` (This will start the installation proccess)
 ![1*-tV-M-4g6MH8h6pWJ27bCg](https://user-images.githubusercontent.com/58959408/174728861-fb9435a5-04e5-402c-80a3-f366c9b51be8.png)

2. Press `enter` on `English - English` or your language of preference
![1*xeb8quQ-ccd5X51d8ToZRw](https://user-images.githubusercontent.com/58959408/174729529-f51630be-4206-4bfc-a13f-6278c67eb633.png)

3. Press `enter` on `Australia` or the country your installing this Virtual Machine
![1*WixFq3GJF9OjeH-zTBTN7Q](https://user-images.githubusercontent.com/58959408/174729594-92ba0cdc-483c-4499-84ee-2d8f3b62f0b3.png)

4. Press `enter` on `American English` or your keyboard of preference
![1*zKUk6R9tls_jiyY81ue8kA](https://user-images.githubusercontent.com/58959408/174729629-4f111978-4fc1-47ae-891f-aea693929480.png)

5. Create a Host Name as your login, with 42 at the end (eg. prossi42) - write down your Host Name, as you will need this later on.
![1*r0fzgkzXOjK2DfsBCh7wEQ](https://user-images.githubusercontent.com/58959408/174729750-fbd2d215-b526-42c6-8ff0-b83f886c1f3c.png)

6. Leave this blank, press `enter` on Continue 
![1*81XjZBZg2bbNXunuxgnFPQ](https://user-images.githubusercontent.com/58959408/174729840-a85c3319-3a70-4922-9335-e4bb6f765ee9.png)

7. Create a Password for the Host Name - write this down as well, as you will need this later on. 
![1*ft498oj7syh4zVjI48U_tw](https://user-images.githubusercontent.com/58959408/174729894-d0fc794f-add8-49e7-9015-521f9e93958f.png)

8. Create a User Name - write this down as well as your will need this later on. 
![1*rhJWnMKN0TPBZwqRey9OeQ](https://user-images.githubusercontent.com/58959408/174729939-06933a35-5dd1-4924-848e-78d2023bb66e.png)

9. Create a Password for the User Name - write this down as well, as you will need this later on. 
![1*fJFibR-WkevpF3fLwyZiag](https://user-images.githubusercontent.com/58959408/174729975-fa06abf4-f816-48f0-aaf5-a2ccaa43c9fe.png)

10. Press `enter` on your `Timezone` (The timezone your currently doing this project in)
![1*2i7svoURih_UIlRJ87rj5w](https://user-images.githubusercontent.com/58959408/174730349-76a4e74f-822b-4040-8d95-554d44fcb67c.png)

11. Press `enter` on `Guided - use entire disk and set up encrypted LVM` (Second to last option from the list)
![1*CsSx-ALmn8mMxvWicsNVAQ](https://user-images.githubusercontent.com/58959408/174730389-03e5dcd7-9472-4cab-bf88-fe3cc4dc0f4c.png)

12. Press `enter` on Select Disk to Partition
![1*BTLz5sT6noL_SVQ7eq3u-A](https://user-images.githubusercontent.com/58959408/174730452-e267df43-2883-4760-85c4-010970fee329.png)

13. Press `enter` on Select `Separate /home, /var, and /tmp paritions` (Last option from the list)
![1*r5zFPA7R_9BtIqwyOpCCVw](https://user-images.githubusercontent.com/58959408/174730481-2641b9c0-c50d-4f2b-9e71-3896a0760e10.png)

14. Select `Yes` and press `Enter` to write the changes to disks and configure LVM
![1*NHdo3JbApICz0Co2epPLFA](https://user-images.githubusercontent.com/58959408/174730521-780f5eb2-4955-48df-8c59-af9914674ee7.png)

15. Press `Enter` to `cancel` Erasing data as you won't need this for your Virtual Machine
![1*KHmnCUJUWhf1minIdHNS4g](https://user-images.githubusercontent.com/58959408/174730626-c132041c-3070-405f-a8d8-60d620a1d770.png)

16. Create a Encryption passphrase - write this down as well, as you will need this later on.
![1*B0QL-gX7rZW5-RJyTD1uWw](https://user-images.githubusercontent.com/58959408/174730733-f306e051-4b0e-40de-93ab-56f2cdce45d5.png)

17. Retype the Encryption passphrase you just created
![1*xE1owXa0ttpvcioaEwnutA](https://user-images.githubusercontent.com/58959408/174730804-796f6db1-8b59-4f8e-900c-1416f957db30.png)

18. Type in `max`and press enter on `Continue` to assign the amount of volume group to use for guided partitioning
![1*SUFMu-qy3rBwIe9B0Bq3kg](https://user-images.githubusercontent.com/58959408/174730857-2de10217-3d42-41ca-8f43-fc91fddb64c6.png)

19. Press enter on `Yes` for Partition Disks
![1*yfXpHyGD37OGAOX7qs1Avw](https://user-images.githubusercontent.com/58959408/174730895-f70df93e-eb7e-493c-9374-edf58a47408c.png)

20. Press enter on `No` for Configure the package manager
![1*Mfb1YHt4K3pZJ12TF2dXAw](https://user-images.githubusercontent.com/58959408/174730933-615891f8-d9fa-4312-ad78-d691bd648773.png)

21. Press `enter` in the country that your in
![1*vqV-bN3zDMqTBAKz_u548w](https://user-images.githubusercontent.com/58959408/174731009-ca532fcf-ac41-4cde-bdae-2cf18c8bf519.png)

22. Press `enter` on deb.debian.org
![1*bLnFC6MebhW1-YZlI2n9_A](https://user-images.githubusercontent.com/58959408/174731066-6bef2e53-c891-477f-8a29-7e9984a6d911.png)

23. Leave this blank and press `enter` on continue
![1*e08pS8shLNmhZuFUrmuBwA](https://user-images.githubusercontent.com/58959408/174731175-bf4949d2-a832-4a1f-9282-c91195203c84.png)

24. Press `enter` on `no` for Configuring popularity-contest
![1*1I6fHG3MHuovrarqj9PNnA](https://user-images.githubusercontent.com/58959408/174731301-88d7c53d-f5e2-46c3-b221-a8b40f70f81f.png)

25. Deselect `SSH server` and `standard system utilities` by pressing the `Space key` and then press `enter` on `Continue`
![1*lGsuAQEwT0WBhb4kdUMp9g](https://user-images.githubusercontent.com/58959408/174731387-b4859ded-9a9f-409a-a9c9-57d1ec77cbfd.png)

26. Press `enter` on `Yes` to Install the GRUB boot loader on a hard disk
![1*b2qXPye_kX8EudSvbO4yww](https://user-images.githubusercontent.com/58959408/174731448-b7b22a70-de87-4535-b8aa-3fb3294c9661.png)

27. Press `enter` on /dev/sda 
![1*s3S7D1c1t98nowFfDvJfgg](https://user-images.githubusercontent.com/58959408/174731491-7215eca8-f5e0-4862-a6ef-c49077c94cbe.png)

28. Press `enter` on `continue` to finish the installation
![1*riuXLYYgESxdq-lpkivFXQ](https://user-images.githubusercontent.com/58959408/174731601-b5949892-28b5-4b5a-94dd-9b50e6f0662b.png)


## Part 3 - Starting Your Virtual Machine

1. Press enter on `Debian GNU/Linux` 

2. Enter your encryption password you had created before

3. Login in as the your_username you had created before

4. Type `Isblk` in your Virtual Machine to see the partition

## Part 4 - Configurating Your Virtual Machine

### Part 4.1 - Installing Sudo

1. First type `su -` to login in as the root user.
2. Type `apt-get update -y` then type `apt-get upgrade -y` and then type `apt install sudo`
3. Type `su -` then type `usermod -aG sudo your_username` to add user in the sudo group
4. Type `sudo visudo` to open sudoers file
5. Lastly add this line in the file `your_username   ALL=(ALL) ALL`

### Part 4.2 - Installing Git and Vim

1. First type `apt-get update -y` then type `apt-get upgrade -y` and then type `apt-get install git -y` to install Git
2. Type `git --version` to check the Git Version
3. Type `sudo apt-get install wget` to get wget, a free and open source tool for downloading files from web repositories
4. Lastly type `sudo apt-get install vim` to install Vim

### Part 4.3 - Installing and Configuring SSH (Secure Shell Host)

1. First type `sudo apt-get update`
2. Type `sudo apt install openssh-server`
3. Type `sudo systemctl status ssh` to check SSH Server Status
4. Type `service ssh restart` to restart the SSH Service
5. Type `sudo nano /etc/ssh/sshd_config`
6. Find the line that has `#Port22` and change it to `Port4242` without the # (Hash) in front of it
7. Save and Exit Nano 
8. Then type `sudo grep Port /etc/ssh/sshd_config` to check if the port settings are right
9. Lastly type `sudo service ssh restart` to restart the SSH Service 

### Part 4.4 - Installing and Configuring UFW (Uncomplicated Firewall)

1. First type `apt-get install ufw` to install UFW
2. Type `sudo ufw enable` to inable UFW
3. Type `sudo ufw status numbered` to check the status of UFW
4. Type `sudo ufw allow ssh` to configure the Rules
5. Lastly type `sudo ufw allow 4242` to configure the Port Rules


## Part 5 Connecting the SSH Server

1. Go to your Virtual Box Program
2. Click on your Virtual Machine and select `Settings`
3. Click `Network` then `Adapter 1` then `Advanced` and then click on `Port Forwarding`
![1*rCj_FeuZ5Rm2abz48qhulg](https://user-images.githubusercontent.com/58959408/174720900-39eda7e0-9be8-453c-94f1-4aa1a6b10951.png)
4. Change the Host Port and Guest Port to `4242`
![1*61-KSUCFcerO1wPqBcYISg](https://user-images.githubusercontent.com/58959408/174720987-e8de3bf9-2ffa-40ca-9d5c-4d0dea9d0b30.png)
5. Then head back to your Virtual Machine
6. Type `sudo systemctl restart ssh` to restart your SSH Server
7. Type `sudo service sshd status` to check your SSH Status
8. Open an iTerm and type the following `ssh your_username@127.0.0.1 -p 4242`
9. Lastly type `exit` to quit your SSH iTerm Connection 


## Part 6 - Continue Configurating Your Virtual Machine

### Part 6.1 - Setting Password Policy

1. First type `sudo apt-get install libpam-pwquality` to install Password Quality Checking Library
2. Type `sudo nano /etc/pam.d/common-password`
3. Find the following line `password [success=2 default=ignore] pam_unix.so obscure sha512` or something similar
4. At the end of that line add in `minlen=10` 
5. The line should now look like this `password [success=2 default=ignore] pam_unix.so obscure sha512 minlen=10`
5. Now this find this line `password  requisite     pam_pwquality.so  retry=3`
6. At the end of that line add in `lcredit =-1 ucredit=-1 dcredit=-1 maxrepeat=3 usercheck=0 difok=7 enforce_for_root` 
7. The line should now look like this - `password  requisite     pam_pwquality.so  retry=3 lcredit =-1 ucredit=-1 dcredit=-1 maxrepeat=3 usercheck=0 difok=7 enforce_for_root` it would look like this:
![1*kEDIaQbWGJqO_JbDpPMZgw](https://user-images.githubusercontent.com/58959408/174722949-d55d7227-a304-4880-b0fa-544d2d7ded16.png)
8. Save and Exit Nano
9. Next type in your Virtual Machine `sudo nano /etc/login.defs`
10. Find this part `PASS_MAX_DAYS 9999` `PASS_MIN_DAYS 0` `PASS_WARN_AGE 7`
11. Change that part to `PASS_MAX_DAYS 30` and `PASS_MIN_DAYS 2` keep `PASS_WARN_AGE 7` as the same
12. Lastly type `sudo reboot` to reboot the change affects

### Part 6.2 - Creating a Group

1. First type `sudo groupadd user42` to create a group
2. Then type `sudo groupadd evaluating` to assign user42 to the evaluating group
3. Lastly type `getent group` to check if the group has been created

### Part 6.3 - Creating a User and Assigning Them Into The Group

1. First type `cut -d: -f1 /etc/passwd` to check all local users
2. Type `sudo adduser new_username` to create a username - write down your new_username, as you will need this later on. 
3. Type `getent group user42` to check if the user is the group
4. Type `getent group evaluating` to check the group
5. Type `groups` to see which groups the user account belongs to
6. Lastly type `chage -l your_new_username` to check if the password rules are working in users

### Part 6.4 - Configuring Sudoers Group

1. First type `sudo nano /etc/sudoers` to go the sudoers file
2. Add in the following `Defaults   secure_path="..."` and `Defaults    passwd_tries=3`
3. Then add in the following `Defaults  badpass_message="Password is wrong, please try again!"` 
4. Then add in this `Defaults   logfile="/var/log/sudo/sudo.log"` and `Defaults   log_input,log_output`
5. Also add in this `Defaults   requiretty`
6. Lastly add this in `Defaults   secure_path="/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/snap/bin"` if it's already there, then skip this step.
7. Your /etc/sudoers file should look something like this
![1*N4Ad-9k0vfvnWKNC5q6MjQ](https://user-images.githubusercontent.com/58959408/174725518-0ebf1dac-4126-4869-9ba0-b1d05ce313c9.png)

### Part 6.5 - Crontab Configuation (Last Part Before The Defence)

1. First type `sudo apt-get update -y` then type `sudo apt-get install -y net-tools` to install the netstat tools
2. Type `cd /usr/local/bin/vim monitoring.sh`
3. Click on the link and copy the text to your `monitoring.sh` https://github.com/HEADLIGHTER/Born2BeRoot-42/blob/main/monitoring.sh
4. Exit and save your `monitoring.sh`
5. Then type `sudo visudo` to open your sudoers file 
6. Add in this line `your_username ALL=(ALL) NOPASSWD: /usr/local/bin/monitoring.sh` under where its written %sudo  ALL=(ALL:ALL) ALL
7. It should look like this
![1*l-7LtAqCon1gRkV3dY3qiQ](https://user-images.githubusercontent.com/58959408/174727595-11dbb2f9-9c34-4d11-870b-f832ea4a9224.png)
8. Then exit and save your sudoers file
9. Now type `sudo reboot` in your Virtual Machine to reboot sudo
10. Type `sudo /usr/local/bin/monitoring.sh` to execute your script as su (super user)
11. Type `sudo crontab -u root -e` to open the crontab and add the rule
12. Lastly at the end of the crontab, type the following `*/10 * * * * /usr/local/bin/monitoring.sh` this means that ever 10 mins, this script will show

Congraluations! that is the end of the Born2BeRoot Project, now onto the Defence Instructions.


## Part 7 - Born2BeRoot Defence Evaluation
