kimsj8912.github.io
Kookmin Univ. CS 20212974 김서정

### 나만의 블로그 만들기 프로젝트 진행 과정 소개
  ## 1. Github Page 시작하기
    - Repository 생성
       Github에서 <username>/github.io 를 이름으로 하는 저장소 생성
    
    - Local-Remote Repository 연결
       리모트 저장소 주소 복사 후 다음 코드 입력
       'git clone <repo_name> <path>'
  
  ## 2. Jekyll
    - jekyll 설치
       jekyll 사이트 설명에 따라 지킬 설치
       'jekyll -v' 를 통해 지킬이 잘 설치되었는지 확인
    
    - jekyll 시작하기
       'jekyll new . --force' 를 통해 현재 디렉토리에 지킬 설치
  
  ## 3. 게시글 포스팅
    - Post
       YYYY-MM-DD-TITLE.md 형태로 문서 생성
       lyrical.md 파일 업로드 함
       markdown 형식으로 작성
    
  ## 4. 테마 적용
    - bay 테마
       'git clone' 을 통해 로컬에 bay 테마 다운로드
    
    - 테마 덮어쓰기
       의존성을 감안하여 _posts를 제외하고 _config.yml 등 파일 덮어쓰기 진행
       변경된 파일들 git에 반영
    
    - _config.yml
       테마의 기본 설정들 수정
       경로 정보를 내 블로그 경로로 변경
       home, work, blog의 기본 문구를 나만의 블로그에 어울리도록 수정
       contact와 follow 정보를 내 연락처로 수정
    
  ## 5. Disqus 댓글 기능
    - Disqus 가입
       "I wnat to install Disqus on my site"
       jekyll Platform 선택
    
    - 블로그에 Disqus 반영
       _config.yml에 disqus와 shortname을 포함한 key-value 추가
       _layouts/post.html에 disqus 홈페이지에서 복사한 Universal Code 붙여넣기
       댓글을 허용하고 싶은 게시글에 comments: true 추가
  
  ## 6. Git 정리 게시글 업로드
    - 2021-12-02-Git정리.md
       강의 내용과 ppt를 참고하여 내용 정리
       markdown 형식으로 작성
