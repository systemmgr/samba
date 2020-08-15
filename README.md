## samba  
  
the standard Windows interoperability suite of programs for Linux and Unix  
  
requires:    
```
apt install samba
```  
```
yum install samba
```  
```
pacman -S samba
```  
  
Automatic install/update:
```
sudo bash -c "$(curl -LSs https://github.com/casjay-dotfiles/samba/raw/master/install.sh)"
```
Manual install:
```
sudo git clone https://github.com/casjay-dotfiles/samba "/usr/local/etc/samba"
sudo ln -sf usr/local/etc/samba/smb.conf /etc/samba/smb.conf
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/samba" target="_blank">samba wiki</a>  |  
  <a href="http://samba.org" target="_blank">samba site</a>
</p>  
    
