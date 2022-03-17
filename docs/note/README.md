# Github 和 Vercel 上架筆記

## 設定 Github 

1.登入 Github

2.新增一個 repository

3.打上 repository name

4.確保 repository 是 public 狀態

5.Description 可自行填寫

6.註冊了一個檔案庫

## Github 上傳資料

1.開啟 Studio Code 並新增終端

2.輸入 「git init」

3.讓 Git 管理資料夾檔案

4.輸入 「git add .」

*「點」代表當前的整個資料夾

5.讓 Git 增加管理的檔案

6.輸入 「git commit -m “The things what you update”」

*「-m」讓 Git 直接執行，不用重複確認

7.跟 Git 確認收到檔案，且撰寫更新了什麼

8.讓 Git 認識你 (整臺電腦都認識，只要在不會重置的電腦上執行一次即可)

9.輸入 「git config --global user.email "you@example.com"」

10.輸入 「git config --global user.name "Your Name"」

11.輸入「git commit -m "init project"」

12.Git 將檔案都打包了

13.輸入 git remote add origin < url >

*< url > 自己的 Github 遠端儲存庫

14.跟遠端資料庫(這裡指的是 Github)要儲存 branch

15.<額外註記>更改 branch 名稱變為 main

16.輸入「git branch -m main」

17.提交本地儲存庫(也就是你的電腦資料)到遠端儲存庫(這裡指的是 Github)

18.輸入「git push」

*第一次使用會需要跟他說要傳什麼

19.則改為輸入「git push --set-upstream origin main」

20.要驗證你的遠端儲存庫帳號密碼(這邊指的是 Github)

21.完成！！！

## 設定 Vercel

1.首先與 Github 進行連結

2.選擇一個檔案庫

3.Framework Preset 選擇 「Vue.js」

4.Build command 輸入 「npm run build:docs」

5.Output Directory 輸入「docs/.vuepress/dist/」

6.按下「deploy」

7.完成並顯示出網址~~

## 結束！！！
