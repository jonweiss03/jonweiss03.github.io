<html>
   <head>
		<script type="text/javascript">
    
            function Redirect() {
              var today = new Date();
			  var dd = String(today.getDate()).padStart(2, '0');
			  var mm = String(today.getMonth() + 1).padStart(2, '0'); //January is 0!
			  var yyyy = today.getFullYear();
			  
			  var baseURL = "https://docs.google.com/forms/d/e/1FAIpQLSeNha5QGa3hLx433Zc1QJWq5FF_tSJ_kQaUlWL_gDEg98Z56w/viewform?usp=pp_url&entry.2111852751=";
			  
			  var final_url = baseURL + yyyy + "-" + mm + "-" + dd;

			  window.location.href = final_url;

            }
			
      </script>
   </head>
   <body onload=Redirect()>

   </body>
</html>
