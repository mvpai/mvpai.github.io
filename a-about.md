---
layout: page
title: About
permalink: /a-about/
---

안녕하세요! 정보시스템과 AI를 소통하는 웹사이트에 오신 것을 환영합니다.

### More Information

이 웹사이트는 정보시스템과 AI에 관심을 가지는 사람들을 위해 소통하고 지식을 공유하는 공간입니다. 여기서 실전 경험을 중심으로 최신 동향, 새로운 기술, 사례 등에 대해 알아보실 수 있습니다.

### 현 사이트 구축에 사용한 툴에 관한 정보 
[깃허브 블로그 시작하는 법](https://ahnslab.com/21-how-to-start-github-blog/)  
[Github ssh 원격 접속을 통한 토큰 없이 push 하기](https://juno-juno.tistory.com/48)  
   - key-gen명령어 예시 : 다중 구성 예시 
        ```
        ssh-keygen -t rsa -C "mvpai@yahoo.com" -f "id_rsa_mvpai"  
        ssh-keygen -t rsa -C "metacog@kakao.com" -f "id_rsa_metacogpe"  
        ssh-add ~/.ssh/id_rsa_mvpai  
        ssh-add ~/.ssh/id_rsa_metacogpe  
        ```
        
   - [연결 테스트](https://docs.github.com/ko/authentication/connecting-to-github-with-ssh/testing-your-ssh-connection)   
        ```
        ssh -T git@github.com      
        Hi mvpai! You've successfully authenticated, but GitHub does not provide shell access.  
        ```

[Permission denied 해소](https://docs.github.com/ko/authentication/troubleshooting-ssh/error-permission-denied-publickey)   
   - push 중 에러 메시지 : git@github.com: Permission denied (publickey).  
     해소(ssh-add) : 예시 명령어 ssh-add ~/.ssh/id_rsa_mvpai

[jekyll themes](https://jekyllthemes.io/)  

### 마크다운 사용   
- 줄바꿈 처리를 위해 줄의 마지막에 스페이스 2번 이상 입력   

### Contact me  
[이메일](mailto:metacog@kakao.com)  