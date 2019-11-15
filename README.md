# SpringExample
- 이 프로젝트는 Spring을 연습하기 위한 게시판 프로젝트입니다.
- 참여자 : 임병준, 김민수 입니다

### Good reference
- [기본 환경 설정](https://freestrokes.tistory.com/78?category=1073732)
- [hello world project](https://examples.javacodegeeks.com/enterprise-java/spring/boot/spring-boot-hello-world-example/)
- [스프링 프로젝트 구조](https://jayviii.tistory.com/15)
- [Intelij 환경 설정](https://www.bsidesoft.com/?p=6160)
- [Intelij Gradle 설정](https://www.bsidesoft.com/?p=6926&)
- [Maven vs Gradle](https://bkim.tistory.com/13)
- [Intellij 학생 인증 ultimate](https://whitepaek.tistory.com/6)


### TroubleShooting
- 파일명이 너무 길어 압축이 안풀리는 경우
  - C://로 압축파일을 옮긴 뒤 더블클릭 -> 우클릭, 현재 폴더에 압축 풀기 클릭
- Intellij에서 프로젝트의 패키지들이 한줄로 표시되는 경우
  - 프로젝트 익스프롤러의 우상단 톱니바퀴 클릭 -> Flatten Packages 체크, compact middle packages 체크 해제
- Intellij에서 "기본 클래스 ...을 찾을 수 없습니다" 에러가 나는 경우
  - build - rebuild project로 빌드를 다시 한 후(빌드가 완료될때까지 소스 파일을 수정하지 말 것) 실행
- git repository를 프로젝트로 등록할 때 git.exe가 없다고 나오는 경우
  - file - settings - Version Control - Git - Path to Git executable을 다음으로 변경
    - sourcetree의 경우 : C:\Users\[YOUR USER NAME]\AppData\Local\Atlassian\SourceTree\git_local\bin\git.exe

### Good Lecture
- [[인프런]스프링 입문편](https://www.inflearn.com/course/spring/dashboard)
- [[인프런]스프링 입문편 개정판](https://www.inflearn.com/course/spring_revised_edition#)  
   - [[참고] 소스코드](https://github.com/spring-projects/spring-petclinic)
