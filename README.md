<!DOCTYPE html>
<html>
<head>
  <title>Automatic Lamp</title>
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
  <script type="text/javascript">
		$(document).ready(function(){
				$.ajax({
					url: 'https://lychee-crumble-45794.herokuapp.com/http://task-beta.herokuapp.com/name',
					method: 'GET',
					dataType: 'json',
					success:function(response){
						console.log(response);
						
					},
					error:function(data){
					}
				});
		});
  </script>
</head>
<body>
	

</html>
