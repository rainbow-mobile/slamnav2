# slamnav2

---
실행파일 업데이트 및 버전 관리를 위한 임시 레포 입니다. 
---
1. source ~/.bashrc 를 열어, 맨 밑으로 내려 아래의 경로를 추가 
---
  export LD_LIBRARY_PATH=${LD_LIBRARY_PATH}:/home/lee/rplidar_sdk/output/Linux/Release 
---
2. 이더넷 설정 [PDU <->PC]
   192. 168.2.2 / 255.255.255.0
---
3.  udev_rules
   sudo sh install_udev_rules.sh
