<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<link type="text/css" rel="stylesheet" href="css/bootstrap.css" />
<link type="text/css" rel="stylesheet" href="css/bootstrap-responsive.min.css" />
<style type="text/css">
Reset 
body,td,th {
	color: #FFFFFF;
}
body {
	background-color: #333333;
}
</style>
<title>index</title>
</head>
<body>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<div class="container" id="divContainer" align="center">
<h3>MEDIA WiFi </h3>
<p>&nbsp;</p>
<form method="post" id="fmLogin">
  <div class="control-group">
  <div class="controls">
    <div class="input-prepend">
      <span class="add-on"><i class="icon-user"></i></span>
      <input class="span2" type="text" id="txtUsername" name="txtUsername" placeholder="Username">
    </div>
  </div>
</div>
<div class="control-group">
  <div class="controls">
    <div class="input-prepend">
      <span class="add-on"></span>
      <input class="span2" id="pwPassword" name="pwPassword" type="password" placeholder="Password">
    </div>
  </div>
</div>
        <p>
          <input type="checkbox"> 
        Remember me</p>
    <p>&nbsp;</p>
<table border="0" width="200" align="center">
	<tr>
    	<td width="95" align="center"><button type="button" id="btnLogin" name="btnLogin" class="btn btn-info">Login</button></td> 
 		<td width="95" align="center"><button type="reset" id="btnRefresh" class="btn btn-danger" ><i class="icon-refresh icon-white"></i>Refresh</button></td>
	</tr>
</table> 
 
 
</form>
<!-- hidden-->





<script src="js/jquery-1.10.0.min.js"></script>
<script src="js/bootstrap.min.js"></script>
<script src="js/bootbox.js"></script>

<script>
	$(function(){
		$('#divContainer #fmLogin').on('click','#btnLogin',function(){
			var txtUsername=$('#txtUsername');
			if(jQuery.trim(txtUsername.val()) == ''){
				bootbox.confirm('กรุณากรอก Username/ ชื่อผู้ใช้ ให้ครบด้วยค่ะ',function(boxcon){
					if(boxcon){
						window.open("www.google.co.th", "_target","status=1", "width=40, height=50");
						window.location='';
					}
				});	
			}	
		});
	});
</script>
</div>
</body>
</html>