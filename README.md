# slamnav2

---
## 소개
실행 파일 업데이트 및 버전 관리를 위한 임시 레포입니다.

---
## 설정 방법

### 1. `.bashrc` 수정
- `nano ~/.bashrc` 파일을 열어 맨 아래에 다음 경로를 추가하세요:

```bash
export LD_LIBRARY_PATH=${LD_LIBRARY_PATH}:/home/lee/rplidar_sdk/output/Linux/Release
```
- `source ~/.bashrc` 를 통해 설정을 적용하세요


### 2. 이더넷 설정
- PDU와 PC 간 이더넷 설정:
  - IP 주소: `192.168.2.2`
  - 서브넷 마스크: `255.255.255.0`

### 3. udev 규칙 설치
- 다음 명령어를 실행하세요:

```bash
sudo sh install_udev_rules.sh
