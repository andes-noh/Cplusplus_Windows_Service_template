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


