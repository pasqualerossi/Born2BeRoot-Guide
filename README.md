## Born2BeRoot Step by Step

This Guide is in 7 Parts: 
- Part 1 - Downloading Your Virtual Machine
- Part 2 - Installing Your Virtual Machine
- Part 3 - Starting Your Virtual Machine
- Part 4 - Configurating Your Virtual Machine
- Part 5 - Connecting to the SSH Server
- Part 6 - Continue Configurating Your Virtual Machine
- Part 7 - Your Born2BeRoot Defence Evaluation

## Part 1 - Downloading Your Virtual Machine

1. Click on this link https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/

2. Scroll to the bottom of that link and click on the following: <img width="1805" alt="Screen Shot 2022-06-21 at 11 19 54 AM" src="https://user-images.githubusercontent.com/58959408/174699748-1e21ef6e-acb1-48e1-934c-879bb3e1dc39.png">

3. Place that download in the **goinfre** `/Users/your_login/goinfre` if you are installing on the 42 Campus.

## Part 2 - Installing Your Virtual Machine

1. Click on New
![1*tkjZEbnHKqPGN24HQw_kRA](https://user-images.githubusercontent.com/58959408/174700376-2862e8e9-0a7a-4681-af3b-e82dbc7d9aa5.png)

2. Change Machine Folder to `/Users/your_login/goinfre` and then click `continue`
![1*WyFDl98AZfft999XCKD6kA](https://user-images.githubusercontent.com/58959408/174700651-8dc8e0a9-7709-4202-8a12-12a384ff6e3e.png)

3. Set Memory Size as `1024 MB`
![1*SoVNIKT340ARlLvQ7RuwDA](https://user-images.githubusercontent.com/58959408/174701125-7a285b0d-7036-4bef-926b-271b0032d7ad.png)

4. Click `Create a Virtual Hard Disk Now` and then click `Create`
![1*PzVboJLyLTs7qJmgbdoBYA](https://user-images.githubusercontent.com/58959408/174701209-a5d10ea3-c634-4d49-b099-01d538fe0517.png)

5. Click `VDI (VirtualBox Disk Image)` and then click `Continue`
![1*6_D9jIyOW0jE3a6vF_UzXg](https://user-images.githubusercontent.com/58959408/174701340-d84f6c80-e09b-43ae-b31a-6dd5d6306f23.png)

6. Click `Dyamically Allocated` and then click `Continue`
<img width="696" alt="Screen Shot 2022-06-21 at 11 41 27 AM" src="https://user-images.githubusercontent.com/58959408/174701751-6b0fe5a3-36e9-487b-a9e1-6b39544b5275.png">

7. Set Size as `12.00 GB` and then click `Continue`
![1*rYdYJbPswCVCUa5pwKcRZA](https://user-images.githubusercontent.com/58959408/174701552-71128cda-62cd-45d8-a439-1a86cfab89db.png)

8. Click `Settings` and then click `Storage`
![1*V2wtat5wJyBjSEoXatkG0A](https://user-images.githubusercontent.com/58959408/174701830-69f7b13c-ac5d-44c2-9f05-de8fd8dcc6f5.png)

9. Click on `Optical Drive`
![1*je75kGWjXl0M6PlqEzHgoA](https://user-images.githubusercontent.com/58959408/174701924-0c69938f-10ec-498f-adec-bacf073b4b99.png)

10. Click on `Choose a disk file...`
![1*VDy31g0tePnUOuJ1cZQsxQ](https://user-images.githubusercontent.com/58959408/174702002-9b4fe4d2-3008-4375-9ec1-57f5e1425eb8.png)

11. Then click on the Virtual Machine file you downloaded and placed into `goinfre` from before
![1*FOldzHFaQ2JS_phe6z6T4g](https://user-images.githubusercontent.com/58959408/174702161-957eb0b6-2803-407f-b018-c02f7615f027.png)

12. Click on your `Virtual Machine` and then click `'ok`
![1*Evj7Z2EOq102A1zUVgUnQg](https://user-images.githubusercontent.com/58959408/174702820-824e0acf-f919-4bfb-a619-eea8068fe309.png)

13. Click `Start` (The Green Arrow ➡️) to start your Virtual Machine
![1*Yg53c1-01g4VzTqhcVEEcA](https://user-images.githubusercontent.com/58959408/174702806-1bd8fce3-aac6-44b3-84d9-c76252dfecd8.png)

## Part 3 - Accessing Your Virtual Machine

1. Click `Install`

2. Click `English - English` or your language of preference

3. Click `Australia` or the country your installing this Virtual Machine

4. Click `American English` or your keyboard of preference

5. Create a Host Name as your login, along with 42 at the end of your Host Name (eg. prossi42) - write down your Host Name as you will need this later on. 

6. Click `Continue`

7. Create a Password for the Host Name - write this down as well as your will need this later on. 

8. Create a User Name - write this down as well as your will need this later on. 

9. Create a Password for the User Name - write this down as well as your will need this later on. 

10. Select your `Timezone` and press `Enter`

11. Select `Guided - use entire disk and set up encrypted LVM` and press `Enter`

12. Select Disk to Partition and press `Enter`

13. Select `Separate /home, /var, and /tmp paritions` and press `Enter`

14. Select `Yes` and press `Enter`

15. Press `Enter` to cancel Erasing data as you won't need this for your Virtual Machine

16. Create a Encryption passphrase - write this down as well as your will need this later on. 

17. Retype the Encryption passphrase you just created

18. Type in `max`and press enter on `Continue`

19. Press enter on `Yes` for Partition Disks

20. Press enter on `No` for Configure the package manager

21. Press `enter` on the country your in

22. Press `enter` on deb.debian.org

23. Leave this blank and press enter on `continue`

24. Press `enter` on no for Configuring popularity-contest

25. Deselect `SSH server` and `standard system utilities` by pressing the `Space key` and then press enter on `Continue`

26. Press `enter` on `Yes` to Install the GRUB boot loader on a hard disk

27. Press `enter` on /dev/sda 

28. Press `enter` to Finish the installation

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
















### Part 4.6 - Setting Password Policy

### Part 4.7 - Creating a Group

### Part 4.8 - Creating a User and Assigning Them Into The Group

### Part 4.9 - Configuring Sudoers Group

### Part 4.10 - Crontab Configuation

## Part 7 - Born2BeRoot Defence Evaluation
