# Github

---

<aside>
๐ Github ์ฌ์ฉ TIP!

</aside>

## ๊ธฐ๋ณธ ๋ช๋ น์ด

**ํ์ฌ ์ํ ํ์ธ**

 *git status*

**์ ์ฒด ๋ก๊ทธ ํ์ธ**

 *git log*

**git ์ ์ฅ์ ์์ฑ**

 *git init*

**์ ์ฅ์ ๋ณต์  ๋ฐ ๋ค์ด๋ก๋**

 *git clone [https: ~~(์ฃผ์)]*

**์ ์ฅ์์ ์ฝ๋ ์ถ๊ฐ**

 *git add*

 *git add **

**์ปค๋ฐ์ ํ์ผ์ ๋ณ๊ฒฝ ์ฌํญ์ ํ๋ฒ์ ๋ชจ๋ ํฌํจ**

 *git add -A*

**์ปค๋ฐ ์์ฑ**

 *git commit -m โ๋ฉ์ธ์งโ*

**๋ณ๊ฒฝ ์ฌํญ ์๊ฒฉ ์๋ฒ ์๋ก๋(push)**

 *git push origin master(๋ธ๋์น๋ช)*

**์๊ฒฉ ์ ์ฅ์์ ๋ณ๊ฒฝ ๋ด์ฉ์ ํ๋ ๋๋ ํ ๋ฆฌ๋ก ๊ฐ์ ธ์ค๊ธฐ(pull)**

 *git pull*

**๋ณ๊ฒฝ ๋ด์ฉ์ merge ํ๊ธฐ ์ ์ ๋ฐ๋ ๋ด์ฉ ๋น๊ต**

 *git diff [๋ธ๋์น ์ด๋ฆ] [๋ค๋ฅธ ๋ธ๋์น ์ด๋ฆ]*

## ๋ธ๋์น ๊ด๋ จ

**git init์ ์ค์ ํ๋ฉด ํด๋น ํด๋์ .git ์ด๋ผ๋ ํ์ผ์ด ์์ฑ๋จ**

 *git init*

**github ์ฃผ์์ ์ฐ๊ฒฐ**

 *git remote add origin [github ์ฃผ์]*

**๋ธ๋์น ์์ฑ**

 *git branch [๋ธ๋์น๋ช]*

**ํด๋น ๋ธ๋์น๋ก ์ด๋**

 *git checkout [๋ธ๋์น๋ช]*

**๋ธ๋์น ์์ฑ ํ ํด๋น ๋ธ๋์น๋ก ๋ฐ๋ก ์ด๋**

 *git branch -d [๋ธ๋์น๋ช]*

**์ํ๋ ๋ธ๋์น๋ก ์ด๋ํ๋์ง ํ์ธ**

 *git branch*

**๋ชจ๋  ๋ธ๋์น ํ์ธ**

 *git branch -a*

**ํ์ผ ๋ฐ ํด๋ add**

 *git add .*

**์ปค๋ฐ**

 *git commit -m โ์ปค๋ฐ ๋ฉ์ธ์งโ*

**์ํ๋ ๋ธ๋์น๋ก pushํ์ฌ ์๊ฒฉ ์๋ฒ์ ์ ์ก**

 *git push origin [๋ธ๋์น๋ช]*

**๋ธ๋์น ์ญ์ **

 *git branch -d [๋ธ๋์น๋ช]*

**ํ์ฌ ๋ธ๋์น์ ๋ค๋ฅธ ๋ธ๋์น ์์ ์ฌํญ ๋ณํฉ**

 *git merge [๋ค๋ฅธ ๋ธ๋์น๋ช]*

## ์ค์  ๊ด๋ จ

**์ ์ฒด config ๋ฆฌ์คํธ ํ์ธ**

 *git config โlist*

**git config ์ค์ ํ๋ ๋ฐฉ๋ฒ**

 *git config โglobal [user .name](http://user.name) โํ๊ธธ๋โ*

 *git config โglobal [user .](http://user.name)email โname@naver.comโ*

**git config ์ญ์ ํ๊ธฐ**

 *git config โunset [user .name](http://user.name)*

 *git config โunset [user .](http://user.name)email*

**์ญ์ ํด๋ ๋จ์์๋ ๊ฒฝ์ฐ global ์ต์์ ์ฃผ์ด ์ค์ ํ์ ๊ฒ์, global๋ก ์ค์ ๋ ์ฌ์ฉ์๋ฅผ ์ง์ธ ๊ฒฝ์ฐ ์๋์ ๊ฐ์ด global ์ถ๊ฐ**

 *git config โunset โglobal [user .name](http://user.name)*

 *git config โunset โglobal [user .](http://user.name)email*

## ์ฐธ๊ณ ์๋ฃ

์ฐธ๊ณ ์๋ฃ 1 :ย **[https://webisfree.com/2018-07-26/git-config-%EC%84%A4%EC%A0%95-%ED%99%95%EC%9D%B8-%EB%B0%8F-%EB%B3%80%EA%B2%BD%ED%95%98%EA%B8%B0](https://webisfree.com/2018-07-26/git-config-%EC%84%A4%EC%A0%95-%ED%99%95%EC%9D%B8-%EB%B0%8F-%EB%B3%80%EA%B2%BD%ED%95%98%EA%B8%B0)**

์ฐธ๊ณ ์๋ฃ 2 :ย **[https://devye.tistory.com/104](https://devye.tistory.com/104)**

์ฐธ๊ณ ์๋ฃ 3 :ย **[https://velog.io/@delilah/GitHub-Git-%EB%AA%85%EB%A0%B9%EC%96%B4-%EB%AA%A8%EC%9D%8C](https://velog.io/@delilah/GitHub-Git-%EB%AA%85%EB%A0%B9%EC%96%B4-%EB%AA%A8%EC%9D%8C)**