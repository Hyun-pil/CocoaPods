# CocoaPods

1. 터미널 실행 Command 실행

    1. "sudo gem install cocoapods"
    2. "pod setup"
    3. "Performing a deep fetch of the 'master'"  specs repo to improve performance 가 나오면
    4. "rm -fr ./cocoapods/repos/master"
    5. "pod setup"

2. project 생성

    1. workspace 먼저 생성방법
        
        1. workspace create
        2. project create
        3. workspace에 생성한 project add

3. 터미널에서 project가 있는 폴더로 이동
4. "pod init" (Podfile 생성)
5. Podfine 수정
6. 터미널에서 "pod install" (다운로드)
7. xworkspace로 xcode 실행.

8.제외 시킬 파일 .gitignore 파일 등록해서 관리
9. 기존에 제외 시킬 파일을 이미 커밋한 후 .gitignore 파일 적용시 
    1. "git rm -r --cached ."
    2. "git add ."
    3. "git commit -m "적용할 커밋 메시지" "
명령어 사용해서 기존 커밋파이 제거시키기
