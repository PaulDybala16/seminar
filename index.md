# Weekly seminars on risk management and actuarial science

The weekly seminar series is a venue for international scholars in risk management and actuarial science to discuss research advances and exchange ideas. Junior researchers are the most encouraged to present their on-going research work. Currently, participants from Canada, China, US, and Europe are included. 

## Student organizers
[Yang Liu](https://yang-liu16.github.io/) (Tsinghua University & University of Waterloo)

Qiuqi Wang (University of Waterloo)

## Faculty mentor
[Dr. Ruodu Wang](http://sas.uwaterloo.ca/~wang/) (University of Waterloo) 

## Current Routine
Time: 9pm-10pm, every Friday (Eastern Standard Time)

Zoom Link: [https://cernet.zoom.com.cn/j/67990545137](https://cernet.zoom.com.cn/j/67990545137)

Meeting ID：679 9054 5137

## Past Events

[Spring 2020](./spring2020.md)

[Winter 2020](./winter2020.html)

[Fall 2019](./fall2019.html)

<!DOCTYPE html>  
<html>  
<head>  
<meta charset=" utf-8">  
<meta name="author" content="http://www.softwhy.com/" />  
<title>蚂蚁部落</title> 
<style type="text/css">
table {
  border: 0;
  border-collapse: collapse;
}
td {
  font: normal 12px/17px Arial;
  padding: 2px;
  width: 100px;
}
th {
  font: bold 12px/17px Arial;
  text-align: left;
  padding: 4px;
  border-bottom: 1px solid #333;
  width: 100px;
}
.parent {
  background: #FFF38F;
  cursor: pointer;
}
.odd {
  background: #FFFFEE;
}
.selected {
  background: #FF6500;
  color: #fff;
}
</style>
<script src="http://libs.baidu.com/jquery/1.9.0/jquery.js"></script>
<script type="text/javascript">
$(function(){
  $("tr.parent").click(function(){
    $(this).toggleClass('selected').siblings('.child_'+this.id).toggle();
  })
})
</script>
</head>
<body>
  <table>
    <thead>
      <tr>
        <th>姓名</th>
        <th>性别</th>
        <th>暂住地</th>
      </tr>
    </thead>
    <tbody>
      <tr class="parent" id="row_01">
        <td colspan="3">前台设计组</td>
      </tr>
      <tr class="child_row_01">
        <td>张山</td>
        <td>男</td>
        <td>浙江</td>
      </tr>
      <tr class="child_row_01">
        <td>李四</td>
        <td>男</td>
        <td>浙江</td>
      </tr>
      <tr class="parent" id="row_02">
        <td colspan="3">前台设计组</td>
      </tr>
      <tr class="child_row_02">
        <td>王五</td>
        <td>男</td>
        <td>浙江</td>
      </tr>
      <tr class="child_row_02">
        <td>张山</td>
        <td>男</td>
        <td>浙江</td>
      </tr>
    </tbody>
  </table>
</body>
</html>
