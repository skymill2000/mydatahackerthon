# Sample JSON 파일 위치

Sample JSON 파일들은 /src/sample_data 폴더에 존재합니다.

## 샘플 코드 실행방법

샘플 코드는 NodeJs 로 작성

https://nodejs.org/ko/download/

Nodejs 16 버전 설치후 아래 명령어를 실행 하여 모듈을 다운로드

```bash
npm install 
```

프로젝트를 실행시키기 위해 NPM 실행 구문 실행

```bash
node {fileName}
```

노드 실행 명령어를 통해 파일 실행 ***실행파일 한글로 인해 오류가 발생할 경우 영문으로 변경 ***

## 샘플 코드실행시 주의 사항

인증서가 필요한 샘플의 경우 개인 인증서를 활용하여 데이터를 입력해 주세요 인증서의 위치 src/certificate 디렉토리에 입력

APP_KEY, APP_SECRET_KEY 는 .env 파일에 입력

```code
TILKO_APP_KEY={여러분들이 발급받은 키 입력}
```

##데이터 참고 사이트 목록
 보험계약현황 : https://www.credit4u.or.kr/
 
 약품정보 조회 API : https://tilko.net/

 금융위 오픈 API : https://developers.kftc.or.kr/dev
