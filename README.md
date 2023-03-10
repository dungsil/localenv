# 개인 개발환경 설정
> **Warning**
> 이 설정은 로컬 개발을 목적으로 구성되어있으며 운영 환경에서 사용하기에 적합하지 않습니다.

개인용(@dungsil) 로컬 개발환경 설정

## 기능
 - **완벽하게 구성됨** - 모든 설정은 정의되어 있으며 대부분의 경우 수정이 필요없습니다.
 - **TLS 인증** - 운영 환경과 최대한 동일한 환경을 구성하기 위해 지원되는 모든 서비스는 TLS 연결

## 포함된 서비스
 - **PostgreSQL (v15)** : RDBMS
    * 호스트: `postgres`
    * 포트: `5432`
    * 루트 계정: `postgres`
    * 루트 비밀번호: `postgres`
    * 기본 데이터베이스: `postgres`
 - **MongoDB (v6)** : No-SQL 서버
    * 호스트: `mongo`
    * 포트: `27017`
    * 루트 계정: `root`
    * 루트 비밀번호: `mongodb`
 - **SMTP4DEV** : 개발용 SMTP 서버 (실제 메일 발송 X / 웹 콘솔에서 발송된 메일 확인)
    * 호스트: `smtp4dev`
    * 웹 콘솔: [`http://localhost:5000`](http://localhost:5000)
    * SMTP 포트: `25`
    * IMAP 포트: `143`
 - **NGINX** : 웹서버, 그리고 리버스 프록시
 - **Infisical** : 시크릿 (암호, API 키) 관리 도구
    * 웹 콘솔: [`https://localhost:3333`](https://localhost:3333)

## 시작하기

### 요구사항
> **Warning**
> Windows 사용자의 경우 WSL에서 실행할 것을 권장합니다.
 - Docker
 - Docker compose v2

### 자체 서명 인증서 발급
TODO

## 라이선스
이 저장소는 [The Unlicense](https://choosealicense.com/licenses/unlicense/)로 배포됩니다.

이 저장소를 상업/비상업용으로 자유롭게 이용하실 수 있으나 이 저장소를 사용하면서 생기는 문제에 대해 책임지지 않으며 작동 및 업데이트를 보증하지 않습니다.
