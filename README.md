# Netease
<!DOCTYPE html>
<html >
<head>
	<meta name="viewport" content="width=device-width, 
                                     initial-scale=1.0, 
                                     maximum-scale=1.0, 
                                     user-scalable=no"">
	<title>node.js练习</title>
	<link rel="stylesheet" href="https://cdn.bootcss.com/bootstrap/3.3.7/css/bootstrap.min.css">  
  <script src="https://cdn.bootcss.com/jquery/2.1.1/jquery.min.js"></script>
  <script src="https://cdn.bootcss.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
</head>
<body style="padding-top: 50px;">
	<div class="alert alert-danger" role="alert">
	  <span class="glyphicon glyphicon-exclamation-sign" aria-hidden="true"></span>
	  <span class="sr-only">Error:</span>
	  Enter a valid email address
	</div>

	<p>基本的胶囊式导航菜单</p>
	<ul class="nav nav-pills">
	  <li class="active"><a href="#">Home</a></li>
	  <li><a href="#">SVN</a></li>
	  <li><a href="#">iOS</a></li>
	  <li><a href="#">VB.Net</a></li>
	  <li class="dropdown">
      <a class="dropdown-toggle" data-toggle="dropdown" href="#">
        Java <span class="caret"></span>
      </a>
      <ul class="dropdown-menu">
        <li><a href="#">Swing</a></li>	
        <li><a href="#">jMeter</a></li>
        <li><a href="#">EJB</a></li>
        <li class="divider"></li>
        <li><a href="#">分离的链接</a></li>
      </ul>
    </li>
	  <li><a href="#">PHP</a></li>
	</ul>
	
	<nav class="navbar navbar-default navbar-fixed-top" role="navigation">
    <div class="container-fluid">
    <div class="navbar-header">
        <a class="navbar-brand" href="#">菜鸟教程</a>
    </div>
    <div>
        <ul class="nav navbar-nav">
            <li class="active"><a href="#">iOS</a></li>
            <li><a href="#">SVN</a></li>
            <li class="dropdown">
                <a href="#" class="dropdown-toggle" data-toggle="dropdown">
                    Java <b class="caret"></b>
                </a>
                <ul class="dropdown-menu">
                    <li><a href="#">jmeter</a></li>
                    <li><a href="#">EJB</a></li>
                    <li><a href="#">Jasper Report</a></li>
                    <li class="divider"></li>
                    <li><a href="#">分离的链接</a></li>
                    <li class="divider"></li>
                    <li><a href="#">另一个分离的链接</a></li>
                </ul>
            </li>
        </ul>
    </div>
    </div>
	</nav>
	<div style="height: 300px;">
	</div>
	
	<ul class="pagination">
    <li><a href="#">&laquo;</a></li>
    <li class="active disabled"><a href="#">1</a></li>
    <li ><a href="#">2</a></li>
    <li><a href="#">3</a></li>
    <li><a href="#">4</a></li>
    <li><a href="#">5</a></li>
    <li><a href="#">&raquo;</a></li>
	</ul>
	
	<script>
		$(function () {
				$(".nav").find("li").click(function () {
					$(".nav").find("li").attr("class","");
					$(this).attr("class","active")
				})
			});
		// $(function () {
		// 		$(".pagination").find("li").click(function () {
		// 			$(".pagination").find("li").attr("class","");
		// 			$(this).attr("class","active disabled")
		// 		})
		// 	});

	</script>
</body>
</html>
