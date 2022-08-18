---
title:  "[Github 블로그] 블로그 무작정 따라하기"
#excerpt: "md 파일에 마크다운 문법으로 작성하여 Github 원격 저장소에 업로드 해보자. 에디터는 Visual Studio code 사용! 로컬 서버에서 확인도 해보자. "

categories:
  - Blog
tags:
  - [Blog, jekyll, Github, Git]

toc: true
toc_sticky: true
 
date: 2022-08-18
last_modified_at: 2022-08-18
---
# 계기
알게된 지식을 정리하지 않으니까 자꾸 잊어버리곤 해서 정리를 해야 하는데 아무래도 블로그가 접근성이 좋아보여서 시작하기로 했다.<br>
네이버 블로그도 있지만 아무래도 개발자니까 Git을 이용한 블로그를 해보기로 결정.<br>
하지만, 귀찮아서 차근차근히 메뉴얼을 읽고 하기 보다는 누군가 이미 닦아 놓은 길을 따라 가보기로 했다.<br>
참고한 블로그는 여기 [식빵맘님의 블로그](https://ansohxxn.github.io/blog/)
<br>

# 막혔던 부분
## jekyll 서버 기동 시 에러 - cannot load such file -- webrick
- https://velog.io/@minji-o-j/jekyll-오류-해결 링크 참고하여 해결
    - webbrick install

## Github Pages 404 error
- https://reload1bronze.tistory.com/52 링크 참고하여 해결
    - 공개범위를 private이 아닌 public으로 해야함
    https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/setting-repository-visibility