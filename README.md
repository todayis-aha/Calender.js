# Calender.js
公历农历插件转换


在time.html页面中，这两个input分别显示公历和农历
支持进来默认用公历转换成农历
点击时间选择器，公历公历联动，input的值对应修改
<div class="birth solar" style="display:flex">
  <div class="mr20 dates">公历</div>
    <div class="date_input">
      <input id="demo1" class="demoInput" type="text" data-types="solor" data-toid-date="date1" data-toid-hour="hour1"
             name="input_date" readonly="readonly" />
      <input type="hidden" id="date1" name="date">
      <input type="hidden" id="hour1" name="hour">
    </div>
  </div>
  <div class="birth lunar" style="display:flex">
    <span class="mr20 dates">农历</span>
    <div class="date_input">
      <input id="demo2" class="demoInput" type="text" data-type="1" data-toid-date="date1" data-toid-hour="hour1"
             name="input_date" readonly="readonly" />
      <input type="hidden" id="date1" name="date">
      <input type="hidden" id="hour1" name="hour">
   </div>
 </div>
 
 
 点击时间选择器，日期联动，在pick_date.js里 finishMobileDate()，仔细看注释
