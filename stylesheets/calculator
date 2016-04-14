*{
    padding:0;
    margin:0;
    background-attachment: fixed;
}
body {
    background-image:
    linear-gradient(rgba(0, 0, 0, 0.2),#6fa6ce,#bd444e);/*線性漸層(顏色1,顏色2,顏色3...)*/
    color: #ffffff;
    font: 300 18px/1.6 "Source Sans Pro",sans-serif;
    margin:0;
}
#header{
    position:absolute;
}
h1{
    font-size:30px;
    font-family:'Times New Roman', Times, serif;
    color:#ffffff;
    margin-left:40px;
    margin-top:20px;
}
/*計算機本身*/
#calculator {
    position:absolute;
    margin-left:500px;
    margin-top:100px;
    font-size:25px;
    height:310px;
    width:300px;
    background:linear-gradient(#5C258D #4389A2) ;
}

.keys{
    width:360px;
    height:370px;
    background:#6fa6ce;
    padding:10px;
    padding-top:70px;
    border-bottom-right-radius:5px;
    border-bottom-left-radius:5px;
}
/*清除C*/
.clear{
    float:left;
    border-bottom:4px solid #ff7c87;
    color:#FFF;
    width:70px;
    height:70px;
    line-height:2em;
    text-align:center;
    padding:10px;
    position:absolute;
    top:-6px;
    right:-54px;
    border: 1px solid rgba(255,255,255,0.3);
    box-shadow:0px 4px 4px rgba(0, 0, 0, 0.2);
    cursor:pointer;
}
.keys,
.top {
    overflow:hidden;
}
/*顯示區*/
.top .input {
    height:49px;
    width:240px;
    float:right;
    color:#FFF;
    line-height:3em;
    text-align:left;
    letter-spacing:1px;
    box-shadow: inset 4px 4px rgba(0, 0, 0, 0.2);
    background:#316d9a;
    padding:10px 10px 10px 10px;
    position:absolute;
    margin-left:17px;
    margin-top:10px;
}
/*各按鍵*/
button{
    float:left;
    cursor:pointer;
    width:70px;
    height:70px;
    margin-bottom:4px;
    margin-top:16px;
    margin-left:16px;
    font-size:18px;
    color:#fff;
    text-align:center;
    transition: all 0.5s;
    border: 1px solid rgba(255,255,255,0.3);
    box-shadow:0px 4px 4px rgba(0, 0, 0, 0.2);
    font-family:'Century Gothic';
    background:#6fa6ce;
    
}
/*加減乘除*/
.operator {
      background:rgba(255,255,255,0.2);
      border-right: 0;
      color: rgba(0,0,0,0.5);
}
/*等於*/
.equals{
      background:#ff7c87;
}

button:focus::after {
      animation: zoom 5s;
      animation-iteration-count: 1;
      animation-fill-mode:both; 
      content: attr(data-value); 
      cursor: default;
      font-size: 100px;
      position: absolute;
      top:120px;  
      left: 540px;
      width:48px;
      text-align: center;
      margin-left:-24px;
      opacity: 0;
      font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;     
}

.operator:focus::after {
       content: attr(data-ops);
       margin-left:0px;
       width: 48px;
}

.equals:focus::after {
       content: attr(data-result);
       margin-left:-24px;
       width: 48px;
}
button:hover,
button.equals:hover,
.top button.clear:hover {
      background:rgba(255,255,255,0.3);
      color:#FFF;
}

.keys span:active {
}

.keys span.equals:active {
}

.top span.clear:active {
}

/* Animations */
@keyframes zoom {
  0% { 
    transform: scale(.2); 
    opacity: 1;
  }
  70% { 
    transform: scale(1); 
  }
  
  100% { 
    opacity: 0;
  }
}
