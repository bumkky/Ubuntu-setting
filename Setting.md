# HDD MOUNT
https://seongkyun.github.io/others/2019/03/05/hdd_mnt/


# UIM korean language
http://progtrend.blogspot.com/2018/06/ubuntu-1804-uim.html


# Nvidia 2080 collision  problem
http://ejklike.github.io/2017/03/05/install-ubuntu-16.04-with-nvidia-gpu.html


# reversion of vamilo fn key

http://jinyongjeong.github.io/2018/10/05/ubuntu_mac_func_disable/

# chrome hangul

xmodmap -e 'remove mod1 = Alt_R'
xmodmap -e 'keycode 108 = Hangul'


# vmware download + Window

https://m.blog.naver.com/ndb796/221079747949
https://webnautes.tistory.com/1029

#tar.gz 로 압축 – abc 라는 파일을 abc.tar.gz로
tar -zcvf abc.tar.gz abc

# 하위폴더 없이 압축 
target directory에서
tar -czvf temp.tar.gz *

# 폴더 내 모든 파일(*) 이름 중 img0 를 0으로 바꿈 

 rename 's/img0/0/g' *


# Delete file 

sudo rm -r -f /path/


# Find file  &  delete

dpkg --list | grep wine
sudo dpkg --remove libwine-development:i386


# Jupyter notebook conda environment setting

conda env create -f env.yml
conda activate assn1
conda install ipykernel
ipython kernel install --name assn1 –user
jupyter notebook

