## 리뉴얼 

어드민 Path - http://wpsamsungcrops2018.m4nc.net/admin_path.html

국문   Path - http://wpsamsungcrops2018.m4nc.net/path_kor.html

영문   Path - http://wpsamsungcrops2018.m4nc.net/path_eng.html


### 사용규칙

    1. 마스터 브랜치에서는 작업을 하지 않습니다. 작업자 브랜치 생성 후 작업!

    2. 작업 전 항상 마스터 브랜치를 확인하여 최신화를 시켜 줍니다.
        2_1. 마스터 브랜치에 변경사항이 있을 경우
        2_2. vscode 에디터툴 기준으로 왼쪽 하단 현재 브랜치를 <작업자 브랜치명>으로 변경 
        2_3. <작업자 브랜치명>에서 터미널을 사용 하여 "git merge master" 머지시켜 줍니다.

    3. 작업자 브랜치에서 작업한 내용을 원격저장소에 push까지 완료
    
    4. 작업자 브랜치에 작업 한 내용을 마스트 브랜치에 적용하는 법
        4_1. vscode 에디터툴 기준으로 왼쪽 하단 현재 브랜치를 마스터로 변경 
        4_2. 마스터 브랜치에서 터미널을 사용 하여 "git merge <작업자 브랜치명>" 머지시켜 줍니다. 

    5. 최종 관리자가 마스터 브랜치를 기준으로 FTP에 업로드 합니다.

