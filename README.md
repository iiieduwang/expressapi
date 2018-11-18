此範例使用的技術是 Node.js + Express + MySQL <br>
主要是希望讓MySQL每次只回傳10筆資料 <br>


範例安裝<br>
<ul>
 <li>clone 或 download 這個專案</li>
 <li>請先將Northwind.sql匯入到Northwind資料中</li>
 <li>執行 npm install 或 yarn install 安裝相關套件</li>
 <li>使用Visual Studio Code開啟專案</li>
 <li>開啟routes/products.js</li>
 <li>修改程式6-11行之間的連線字串</li>
 <li>執行 npm start 或 yarn start 啟動網頁</li> 
</ul>

執行方式<br>
http://localhost:3000/api/products/ 會讀出所有產品資料<br>
http://localhost:3000/api/products/[page]<br>
http://localhost:3000/api/products/1 1表示第一頁，回讀出1-10筆資料<br>
http://localhost:3000/api/products/2 2表示第二頁，回讀出11-20筆資料<br>
http://localhost:3000/api/products/3  <br>
http://localhost:3000/api/products/4  <br>
