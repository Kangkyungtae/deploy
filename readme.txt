# 구조
/
    L requirements.txt : 특정 환경에서 사용한 모듈들을 기술 
                         환경이 구축될 때 , 이 서비스 운영/개발시 사용한 필요한 모듈 설치하기 위해 
                         기술되는 파일이다. 
                         - 반드시 버전을 명시하여 , 향후에 서버가 변경돼도 문제없이 , 
                         구동되게끔 동일한 환경을 제공 
    L run.py           : 서비스 메인
                     
    L wsgi.py          : 엔트리 포인트, 아파치 서버가 바라보는 파일이다. 
    L deploy.json      : 페브릭이 배포작업을 하는데 필요한 상수값들을 저장한 파일 
                        - 환경변수가 저장된 파일 
# github 사용
1. github.com 접속후 저장소 생성
2. 로컬 pc에서 git 명령어를 이용하여 적절한 위치에 저장소를 다운로드 
     
    - $ git clone https://github.com/Kangkyungtae/deploy.git
    - 이미 작성된 내용을 카피해서 만들어진 폴더 deploy 안으로 붙여넣는다 
