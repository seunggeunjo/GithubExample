# Github

---

<aside>
📌 Github 사용 TIP!

</aside>

## Github Token

 *Token : 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*

## 기본 명령어

**현재 상태 확인**

 *git status*

**전체 로그 확인**

 *git log*

**git 저장소 생성**

 *git init*

**저장소 복제 및 다운로드**

 *git clone [https: ~~(주소)]*

**저장소에 코드 추가**

 *git add*

 *git add **

**커밋에 파일의 변경 사항을 한번에 모두 포함**

 *git add -A*

**커밋 생성**

 *git commit -m “메세지”*

**변경 사항 원격 서버 업로드(push)**

 *git push origin master(브랜치명)*

**원격 저장소의 변경 내용을 현대 디렉토리로 가져오기(pull)**

 *git pull*

**변경 내용을 merge 하기 전에 바뀐 내용 비교**

 *git diff [브랜치 이름] [다른 브랜치 이름]*

## 브랜치 관련

**git init을 설정하면 해당 폴더에 .git 이라는 파일이 생성됨**

 *git init*

**github 주소와 연결**

 *git remote add origin [github 주소]*

**브랜치 생성**

 *git branch [브랜치명]*

**해당 브랜치로 이동**

 *git checkout [브랜치명]*

**브랜치 생성 후 해당 브랜치로 바로 이동**

 *git branch -d [브랜치명]*

**원하는 브랜치로 이동했는지 확인**

 *git branch*

**모든 브랜치 확인**

 *git branch -a*

**파일 및 폴더 add**

 *git add .*

**커밋**

 *git commit -m “커밋 메세지”*

**원하는 브랜치로 push하여 원격 서버에 전송**

 *git push origin [브랜치명]*

**브랜치 삭제**

 *git branch -d [브랜치명]*

**현재 브랜치에 다른 브랜치 수정사항 병합**

 *git merge [다른 브랜치명]*

## 설정 관련

**전체 config 리스트 확인**

 *git config —list*

**git config 설정하는 방법**

 *git config —global [user .name](http://user.name) “홍길동”*

 *git config —global [user .](http://user.name)email “name@naver.com”*

**git config 삭제하기**

 *git config —unset [user .name](http://user.name)*

 *git config —unset [user .](http://user.name)email*

**삭제해도 남아있는 경우 global 옵션을 주어 설정했을 것임, global로 설정된 사용자를 지울 경우 아래와 같이 global 추가**

 *git config —unset —global [user .name](http://user.name)*

 *git config —unset —global [user .](http://user.name)email*

## 참고자료

참고자료 1 : **[https://webisfree.com/2018-07-26/git-config-%EC%84%A4%EC%A0%95-%ED%99%95%EC%9D%B8-%EB%B0%8F-%EB%B3%80%EA%B2%BD%ED%95%98%EA%B8%B0](https://webisfree.com/2018-07-26/git-config-%EC%84%A4%EC%A0%95-%ED%99%95%EC%9D%B8-%EB%B0%8F-%EB%B3%80%EA%B2%BD%ED%95%98%EA%B8%B0)**

참고자료 2 : **[https://devye.tistory.com/104](https://devye.tistory.com/104)**

참고자료 3 : **[https://velog.io/@delilah/GitHub-Git-%EB%AA%85%EB%A0%B9%EC%96%B4-%EB%AA%A8%EC%9D%8C](https://velog.io/@delilah/GitHub-Git-%EB%AA%85%EB%A0%B9%EC%96%B4-%EB%AA%A8%EC%9D%8C)**