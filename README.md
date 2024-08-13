# 美食口袋清單

把喜愛的美食收藏在口袋清單吧！

## 專案畫面

![image](https://github.com/alan890729/C4M1-project-restaurants-list/blob/main/public/images/read-all-restaurants.png)
![image](https://github.com/alan890729/C4M1-project-restaurants-list/blob/main/public/images/read-detail-restaurants.png)
![image](https://github.com/alan890729/C4M1-project-restaurants-list/blob/main/public/images/search-restaurant-ci.png)
![image](https://github.com/alan890729/C4M1-project-restaurants-list/blob/main/public/images/search-restaurant-category.png)
![image](https://github.com/alan890729/C4M1-project-restaurants-list/blob/main/public/images/create-restaurant.png)
![image](https://github.com/alan890729/C4M1-project-restaurants-list/blob/main/public/images/edit-restaurant.png)

## Features - 產品功能

1. 使用者可以瀏覽全部的餐廳
2. 使用者可以點擊某餐廳瀏覽該餐廳的細節資訊
3. 使用者可以依照店名進行搜尋
4. 使用者可以依照餐廳類別進行搜尋
5. 使用者可以新增餐廳到清單
6. 使用者可以編輯清單中的餐廳
7. 使用者可以刪除清單中的餐廳

## Getting Started - 啟動專案

以下為**Getting Started - 啟動專案**的各段落的摘要：
1. **Prerequisites - 環境建置與需求**：使用什麼框架、模組，以及各種工具的版本。
2. **Installing - 專案安裝流程**：如何從github下載這個專案，並在自己的本地環境啟動此專案。


### Prerequisites - 環境建置與需求
- Node.js(RTE) - v20.14.0
- [Express.js - v4.19.2](https://expressjs.com)
- [Nodemon - v3.1.4](https://www.npmjs.com/package/nodemon)
- [Bootstrap - v5.2.1](https://www.jsdelivr.com/package/npm/bootstrap?tab=files&version=5.2.1&path=dist)
- [font-awesome - v5.8.1](https://cdnjs.com/libraries/font-awesome/5.8.1)
- [Express-handlebars - v7.1.3](https://www.npmjs.com/package/express-handlebars)
- [mysql2](https://www.npmjs.com/package/mysql2)
- [sequelize](https://www.npmjs.com/package/sequelize)
- [sequelize-cli](https://www.npmjs.com/package/sequelize-cli)
- [method-override](https://www.npmjs.com/package/method-override)

### Installing - 專案安裝流程

1. 打開terminal，輸入
```
git clone https://github.com/alan890729/C4M1-project-restaurants-list.git
```

2. 開啟終端機(Terminal)，進入存放此專案的資料夾
```
cd C4M1-project-restaurants-list
```

3. 安裝 npm 套件
```
npm install
```

4. 是否已經安裝nodemon  
  - 已有nodemon，直接輸入以下指令啟動專案
  ```
  npm run dev
  ```
  server會在 <http://localhost:3000> 執行

  - 還沒有安裝nodemon，先退回前一個路徑，在global安裝nodemon。輸入：
  ```
  npm install -g nodemon
  ```

  接著再回到 **C4M1-project-restaurants-list** 資料夾內，輸入：
  ```
  npm run dev
  ```

## Authors

  - [**Alpha Camp**](https://tw.alphacamp.co/) - provide project template.
  - [**Alan Huang**](https://github.com/alan890729) - build this project with express.js based on provided project template.

