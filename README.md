# CocoaPods

1. 터미널 실행 Command 실행
```
$ sudo gem install cocoapods
```
```
$ pod setup
```
```
$ Performing a deep fetch of the 'master'
```
specs repo to improve performance 가 나오면

```
$ rm -fr ./cocoapods/repos/master
```
```
$ pod setup
```

2. project 생성

    1. workspace 먼저 생성방법
        
        1. workspace create
        2. project create
        3. workspace에 생성한 project add

3. 터미널에서 project가 있는 폴더로 이동
(Podfile 생성)
```
$ pod init 
```

4. Podfine 수정
5. 터미널에서 (다운로드)
```
$ pod install"
```

6. xworkspace로 xcode 실행.

7.제외 시킬 파일 .gitignore 파일 등록해서 관리

8. 기존에 제외 시킬 파일을 이미 커밋한 후 .gitignore 파일 적용시 

```
$ git rm -r --cached .
```
```
$ git add .
```
```
$ git commit -m "적용할 커밋 메시지"
```
명령어 사용해서 기존 커밋파이 제거시키기
