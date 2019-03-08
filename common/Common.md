# Problems

## 我的电脑里面删除多余的CD驱动器。(An extra CD Drive is shown in your computer and you cannot delete it and remove its drive letter)

Remove the CD drive: 
  
  https://jingyan.baidu.com/article/ff42efa91ba2b6c19e220298.html
  
Remove other devices like '腾讯视频(fk)' downside the Devices and Drives:

  https://jingyan.baidu.com/article/64d05a023d2748de55f73b9d.html

## The time in windows is eight hours later than the standard time when you install windows and ubuntu together
  
    sudo apt-get install ntpdate
    sudo ntpdate time.windows.com
    sudo hwclock --localtime --systohc

## Windows 10 login automaticalll

`Windows` + `R`, then input

  Netplwiz
  
then unselect the option `User must enter a user name and password to use the computer` and input the password.
