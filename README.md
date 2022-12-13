# Cplusplus_Windows_Service_template

## IDE
- vs2017

## 실행
- build
- release -> *.exe 

- powershell 관리자 실행

- 서비스 생성 
```
sc.exe create "service name" binpath= "*.exe FilePath" displayname= "display name" start= auto
```

- 서비스 시작
```
sc.exe start "service name" 
```

- 서비스 중지
```
sc.exe stop "service name"
```

- 서비스 삭제
```
sc.exe delete "service name"
```

## 기타
- 환경 변수 추가 서비스 생성
```
sc.exe create test binPath= '"*.exe FilePath" argv[1] argv[2]....' displayname= "display name" start= auto
```

## 서비스 옵션
- display name: 서비스 목록에서 보여지는 이름
- start: pc의 전원 부팅후 동작 설정

## 참조
- 

## 기타 참조 프로젝트
- 
