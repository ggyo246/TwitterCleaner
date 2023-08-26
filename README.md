# TwitterCleaner
### <b>원작자 깃허브</b>(https://github.com/queeeeeeee/TwitterCleaner) 
<br>
트위터 API를 사용하지 않는 트윗 청소기 크롬 확장 프로그램 입니다. <br>
2023/08/26 내 트윗 제거 / 리트윗 취소 수정

### 사용법 (확장프로그램 다운로드 전에 진행해야 합니다)
1. 트위터 홈페이지에서 자기 프로필 들어간 후 답글란 클릭<br>
2. F12 눌러 개발자도구 들어간 후 Elements 탭 클릭<br>
3. Ctrl + F 누른 후 자기 닉네임 검색하여 타임라인: 닉네임's post 나올때까지 엔터 ex)타임라인: 2시저그's posts<br>
![image](https://github.com/ggyo246/TwitterCleaner/assets/80497188/fd5cb5b7-a817-4fa7-ac7c-12e43244f5d3)

4. 해당 부분 복사 후 contentScript.js의 136번째 줄 timelineElement의 aria-label^="----" 큰따옴표 안에 복사하여 붙여넣기
![image](https://github.com/ggyo246/TwitterCleaner/assets/80497188/94fcfa2d-6cde-40f2-a893-16a01927ae24)

5. 크롬 확장프로그램에서 기존처럼 다운로드하여 실행하면 됩니다.





