# **FOLDER-SETUP CHO DỰ ÁN `HTML` `SASS` `JAVASCRIPT`** 

## **1. Cấu Trúc Thư Mục**

- Thư mục Assets chứa các thư mục `images`, `Icon`, `Sass`, `Data`, và `Javascritp`

- File `index.html`

## **2. Script chạy file**
- Cài đặt `Sass` 
    - Nếu bạn chưa cài môi trường cho `Sass` thì tải `Node.js` - [**Download**](https://nodejs.org/en/download/)

    - Cài đặt `Git-SCM` - [**Download**](https://git-scm.com/downloads)

    - Install `Sass` bằng `NPM`

        ```
        npm i -g sass
        ```
- Chạy `Sass`
    - Output là file minify có dạng `app.min.css`

        ```
        sass --watch app.scss:../css/app.min.css --style compressed
        ```
        *file `app.min.css` sẽ ở trong thư mục `./assets/css`*
    
    - Output là file css có dạng `app.css`

        ```
        sass --watch app.scss:../css/app.css
        ```
        *file `app.css` sẽ ở trong thư mục `./assets/css`*

- Push file lên `Github`
    
    - Tạo và push file lên github
        ```
        git init
        git branch -M main
        git add .
        git commit -m "your commit"
        git remote add origin URl
        git push origin main
        ```

    - Trường hợp cần push đè lịch sử 
        ```
        git push origin main -f
        ```

## **3. My Setting VsCode**

- Font chữ **`jetbrains`** - [**Download**](https://www.jetbrains.com/lp/mono/)

- File custom `color.css` và `Setting.Json`  - [**Download**](https://github.com/undefinednulla/custom-vscode)


## **4. Terminal**


```

// Xác định thư mục hiện tại
$ pwd

// Hiển thị danh sách thư mục
$ ls

// Hiển thị cây thư mục
$ tree

// Đi đến thư mục con
$ cd ./folder

// Đi về thư mục cha
$ cd ../ hoặc $ cd..

// Tạo thư mục
$ mkdir namefolder
$ mkdir "name folder"

// Tạo một file
$ touch name.file

// Di chuyển
$ mv name.file ./folder-con 

// Đổi tên thư mục hoặc file
$ mv name.file changedName.file

// Copy thư mục hoặc file
$ cp name.file changedName.file

//Copy thư mục hoặc file trên Window 
$ copy name.file changedName.file

```

## **5. Extensions Chrome**

- Eyedropper color

- Page Ruler Redux

- Visbug

- React Developer Tool

## **6. Thông Tin Của Tôi**

**`Facebook`** : [**Hai Dang**](https://www.facebook.com/haidanghahaha/)

**`Main Github`** : [**Haidagn**](https://github.com/haidagn)

**`Showcase Github`** : [**Undefined**](https://github.com/undefinednulla)