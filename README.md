# Tistory_Comment

## 설정하기
``` js
Comment_option={"link":true,"prevent_rp_del":false,"remove_report":false,"comment_urls":0,"comment_urls_open":0}
```
### or
``` js
Comment_option.link=false;
```

## 옵션 설명
- link : 프로필 링크 여부 {true(default) 링크있음}
- prevent_rp_del : 답글있는경우 삭제 방지여부 {false(default) 댓글,대댓글은 언제나 삭제가능}
- remove_report : 신고버튼 제거 {false(default) 신고버튼은 날짜 옆에 있다.}
- comment_urls : 댓글내용중 url에 링크달기 {0: 링크X, 1: 내 블로그만 링크, 2: 전부 링크생성, []: 화이트 리스트}
  - 화이트리스트 사용법 : Comment_option.comment_urls=["hi098123.tistory.com","tistory.com"]
  - 자바스크립트 배열로 comment_urls값을 설정
- comment_urls_open : {0: 현재 창에서 열기, 1: 새탭으로 열기}
