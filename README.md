# leanmodal-for-js

How it works?  

jquery.min.js inside the head tag jquery.leanmodal.js after the footer   


//calling link name <a href="#loginmodal" id="modaltrigger1" style="color:#fff;"><b>+ Your Link Name</b></a> 


//javascipt at the footer <script type="text/javascript"> 		$(function(){ 		$('#loginform1').submit(function(e){ 		return false; 		});  		$('#modaltrigger1').leanModal({ top: 100, overlay: 0.45, closeButton: ".hidemodal" }); 		}); </script>   


// form inside this division is called 

<div id="loginmodal" style="display:none;font-family: 'Open Sans', sans-serif;font-weight:lighter;"><a style="margin-top:-15px;font-size:12px;margin-right:-15px;background:#434343;padding:4px 8px;border-radius:100px;border:2px solid #fff;color:#f3f6fa;float:right;" href=""><b>X</b></a> 								
  
  
  <h5> linked Element</h5></div>
