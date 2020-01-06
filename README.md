# Ajax-basis
  
  1. Ajax 的使用過程 : 逐行分析ajax的執行過程對應平時訪問頁面的過程。
  
  2. readystate : 依次分析 readystate 的五個狀態代表的涵意。
  
  3. onload方法 : HTML5 中所提供的方法，可取代 onreadystatechange = fn(){ if(readyState == 4){....}}
  
  4. 關於遵循HTTP協議 : 發送請求時，必須有對應其格式的請求行、請求頭、請求體。
  
  5. 發送 GET 請求並傳參的案例 : 獲取數據後需使用 JSON.parse()方法 把數據內容轉成JSON數據。
  
  6. 發送 POST 請求並設置請求頭的案例 : 請求體格式為key-value 所以必須設置請求頭為form-urlencoded
  
  7. 同步(sync)與異步(async) : open()方法的第三個參數用來判斷是否為異步操作(async) 可傳入布爾值 默認為true(異步)
  
  8. 響應數據的格式 : JSON 數據格式 與 XML 數據格式，建議使用時最好給其設置上 Content-Type
  
  9. 兼容方案 : 因 XMLHttpRequest 在 IE5/6 版本的瀏覽器中有兼容問題。
