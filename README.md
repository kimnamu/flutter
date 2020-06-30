# flutter-tutorial

## 1. Install and environment setting (on Mac)
### A. Download SDK (from https://flutter-ko.dev/docs/get-started/install/macos)
https://storage.googleapis.com/flutter_infra/releases/stable/macos/flutter_macos_1.17.4-stable.zip

### B. 압축 해제 및 환경변수 설정
```bash
# 경로 지정<USER_PATH> 및 압축 해제 및 환경변수 설정
$ cd <USER_PATH>/development
$ unzip <USER_PATH>/Downloads/flutter_macos_1.17.4-stable.zip

# flutter 도구를 path에 추가
$ echo "export PATH='<USER_PATH>/development/flutter/bin:$PATH'" >> ~/.bash_profile

# 설정을 완료하는 데 필요한 플랫폼 의존성이 있는지 확인하기 위해 아래 명령을 실행하세요.
$ flutter doctor
```


# Reference

Flutter SDK Download and install: https://flutter-ko.dev/docs/get-started/install/macos
