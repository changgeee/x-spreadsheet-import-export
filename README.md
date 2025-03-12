# x-spreadsheet-import-export
xspreadsheet的导入导出demo，基于excelJs，保留样式

在线体验(https://changgeee.github.io/x-spreadsheet-import-export/)

效果图:
<img src="./screenshot/a01.png" alt="demo" width="600" height="400">

- 用x-spreadsheet开发时需要用到导入导出功能，查了一堆只找到sheetJs的demo(```https://docs.sheetjs.com/docs/demos/grid/xs```),在线体验（```https://docs.sheetjs.com/xspreadsheet/```）；

- 但是sheetJs要保留样式需要升级pro版本，所以用Excel.js 做了一个简单的实现，基本满足目前的需求

- 原理是导入时把excel的数据格式转换成x-spreadsheet的数据格式，导出时在反过来转换。

- 用sheetJs的demo代码改了这个单文件的示例，如果有人遇到同样的问题直接复制代码修改吧

