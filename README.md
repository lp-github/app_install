install QQ
sudo dpkg --add-architecture i386  
wget -nc https://dl.winehq.org/wine-builds/Release.key  
sudo apt-key add Release.key  
sudo apt-add-repository https://dl.winehq.org/wine-builds/ubuntu/  
sudo apt-get update  
sudo apt-get install --install-recommends winehq-devel  
download wineQQ8.9_19990.tar.xz above 
tar xvf wineQQ8.9_19990.tar.xz -C ~/  
