# flv-pure-js
ทดสอบด้วย
https://platform-open-api.waylar.net/api/v1/tms/live/0071010A05@1/event/1234?mute=1

เลือกใช้ https://github.com/Bilibili/flv.js/ 
เนื่องจากมองว่า ตัว FLV เป็น Format ของ Flash Player
ซึ่งจะมีปัญหากับบางอุปกรณ์และบาง Browser ที่ไม่รองรับ Flash  
เลยจะขออนุญาตส่ง Lib ตัว Demo ที่เป็น HTML5 และเป็น pure Java Script


ตัวที่เจ้าของ Project แจ้งว่าน่าจะมีปัญหา เช่น
https://github.com/winshining/nginx-http-flv-module
https://www.yanxurui.cc/posts/server/2017-11-25-http-flv/


1.npm install --save flv.js
2.npm install -g ts-node@latest
3.npm install --save-dev typescript@latest


2.npm run build:debug