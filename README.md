# Laravel 10 將註解新增到 Blade 模板中

引入 spatie 的 laravel-blade-comments 套件來擴增將註解新增到 Blade 模板中，註解是會被瀏覽器忽略，並且不會被使用者看到的，它們存在的目的是要讓你得以在原始碼中說明你的原始碼是如何運作的、每段原始碼的作用等等。

## 使用方式
- 把整個專案複製一份到你的電腦裡，這裡指的「內容」不是只有檔案，而是指所有整個專案的歷史紀錄、分支、標籤等內容都會複製一份下來。
```sh
$ git clone
```
- 將 __.env.example__ 檔案重新命名成 __.env__，如果應用程式金鑰沒有被設定的話，你的使用者 sessions 和其他加密的資料都是不安全的！
- 當你的專案中已經有 composer.lock，可以直接執行指令以讓 Composer 安裝 composer.lock 中指定的套件及版本。
```sh
$ composer install
```
- 產生 Laravel 要使用的一組 32 字元長度的隨機字串 APP_KEY 並存在 .env 內。
```sh
$ php artisan key:generate
```
- 在瀏覽器中輸入已定義的路由 URL 來訪問，例如：http://127.0.0.1:8000。
- 你可以經由 `/` 來進行歡迎畫面瀏覽。

----

## 畫面截圖
![](https://i.imgur.com/TXfqoMO.png)
> 在原始碼中加入註解