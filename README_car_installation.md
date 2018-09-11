On Windows:

1. Install Anaconda
2. install visual studio community edition (c++ and python) (not sure if it is really necessary) 
3. install NVIDIA Cuda : cuda_9.0.176_windows.exe und cudnn cudnn-9.0-windows7-x64-v7.1.zip (check path for cudnn)
4. create 'donkey' env in Anaconda, run Anaconda as 'Admininstrator'!!!! add tensorflow-gpu==1.17 to windows.yml in donkey project dir: install/envs/windows.yml
5. run 'pip install -e .' in donkey dir
 






1: download image and install it on sd card with WinDiskImage

2. configure wlan via 
------------------wpa_supplicant.conf-----------
country=US
ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev
update_config=1

network={
    ssid="pi_stgt_1"
    psk="58cd4c966045"
}

network={
    ssid="guest_j"
    psk="1new4ALL"
}
------------------

3. configure RAM Disk 

4. opencv auf dem raspberry installiern:
    https://www.pyimagesearch.com/2016/04/18/install-guide-raspberry-pi-3-raspbian-jessie-opencv-3/
    
    sudo apt-get install openexr
    sudo apt-get install gstreamer1.0-tools
    sudo apt-get install libqtgui4
    sudo apt-get install python-opencv
    