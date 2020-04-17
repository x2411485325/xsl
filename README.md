# xsl
一些日常练习
CSS@导入方法

icon图标使用

背景渐变：
background-image: linear-gradient

滤镜兼容ie
filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffff9000', endColorstr='#ffff5000', GradientType=1)

背景透明：
background-color: transparent；

calc(100%-100px)CSS3宽度计算函数，支持ie9+

rgab()函数：
background-color: rgba(0, 0, 0, 0.3);/*支持IE9+*/
    /* background-color: #000\9;    IE9以下浏览器
   filter alpha(opacity=30);    透明 */

display: table-cell;
vertical-align: middle;    /*用表格形式解决居中

 /* display: flex;
    justify-content: center;
    align-items: center;        弹性盒模型解决居中  兼容IE10+ */
    
table-layout: fixed;   /*定义列宽的算法， fixed的计算方式为根据表格宽度自动计算，每列宽度为均分整个表格的宽度*/

word-break: keep-all;  /*在空格处强制换行*/

