<!DOCTYPE html>
<html>
 <head>
<meta charset="utf-8">
<title> Register</title>
<!-- Stylesheets -->
<link href="css/bootstrap.css" rel="stylesheet">
<link href="css/main.css" rel="stylesheet">
<link href="css/responsive.css" rel="stylesheet">

<link rel="shortcut icon" href="images/favicon.png" type="image/x-icon">
<link rel="icon" href="images/favicon.png" type="image/x-icon">

<!-- Responsive -->
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0">
<!-- not allowed to enter any spaces-->
<script type="text/javascript">
  function nospaces(t)
{
if(t.value.match(/\s/g)){
alert('Sorry, you are not allowed to enter any spaces');
t.value=t.value.replace(/\s/g,'');
}}
</script>
<!-- end allowed to enter any spaces-->
<!-- check password length-->
<script type="text/javascript">
  function CheckLengthPassword(el) {
  document.getElementById("passeror").style.display = 'none';
  if(el.value.length!=0){
  if (el.value.length < 5 ) {
  document.getElementById("passeror").style.display = 'block';
  document.getElementById("passeror").style.color = "#ff0000";
  document.getElementById('pass').value="";
  document.getElementById('pass').focus();
  return false;
     } 
   }
} 
function ValidateAlpha(evt)
{
var keyCode = (evt.which) ? evt.which : evt.keyCode
if ((keyCode < 65 || keyCode > 90) && (keyCode < 97 || keyCode > 123) && keyCode != 32)

return false;
return true;
}
function blockSpecialChar(e){ 
var k;
document.all ? k = e.keyCode : k = e.which;
return ((k > 64 && k < 91) || (k > 96 && k < 123) || k == 8 || k == 32 || (k >= 48 && k <= 57));
}
function check_exist123(str)
{
var xmlhttp;
if (window.XMLHttpRequest)
  {// code for IE7+, Firefox, Chrome, Opera, Safari
  xmlhttp=new XMLHttpRequest();
  }
else
  {// code for IE6, IE5
  xmlhttp=new ActiveXObject("Microsoft.XMLHTTP");
  }
xmlhttp.onreadystatechange=function()
  {
  if (xmlhttp.readyState==4 && xmlhttp.status==200)
    {
    document.getElementById("emailerror").innerHTML=xmlhttp.responseText;
    }
  }
xmlhttp.open("GET","check_email_exist.php?q="+str,true);
xmlhttp.send();
} 
function isNumber(evt) {
    evt = (evt) ? evt : window.event;
    var charCode = (evt.which) ? evt.which : evt.keyCode;
    if (charCode > 31 && (charCode < 48 || charCode > 57)) {
        return false;
    }
    return true;
}
 function check_exist1(str)
{
var xmlhttp;
if (window.XMLHttpRequest)
  {// code for IE7+, Firefox, Chrome, Opera, Safari
  xmlhttp=new XMLHttpRequest();
  }
else
  {// code for IE6, IE5
  xmlhttp=new ActiveXObject("Microsoft.XMLHTTP");
  }
xmlhttp.onreadystatechange=function()
  {
  if (xmlhttp.readyState==4 && xmlhttp.status==200)
    {
    document.getElementById("mobileerror").innerHTML=xmlhttp.responseText;
    }
  }
xmlhttp.open("GET","check_mobile_exist.php?q="+str,true);
xmlhttp.send();
}

 
</script>


</head>

<body>

<div class="page-wrapper">
 	
    <!-- Preloader -->
    <div class="preloader"></div>
 	   <!-- Main Header-->
     <header class="main-header header-style-three">
    	
    	<!--Header-Upper-->
        <div class="header-upper">
        	<div class="auto-container">
            	<div class="clearfix">
                	
                		<div class="pull-left logo-box">
                    	<div class="logo"><a href="index"><img src="../images/logo-2.png" alt="abcd" title=""></a></div>
                    </div>
                   	
                   	
					<!-- Submit Add -->
					
                   	<div class="nav-outer clearfix">
						<!-- Mobile Navigation Toggler -->
                        <div class="mobile-nav-toggler"><span class="icon flaticon-menu"></span></div>
						<!-- Main Menu -->
						<nav class="main-menu navbar-expand-md">
							<div class="navbar-header">
								<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
									<span class="icon-bar"></span>
									<span class="icon-bar"></span>
									<span class="icon-bar"></span>
								</button>
							</div>

							<div class="navbar-collapse show collapse clearfix" id="navbarSupportedContent">
								<ul class="navigation clearfix">
									<li><a href="index">Home</a></li>
									<li class="dropdown"><a href="#">About us</a>
									<ul>									        
									         <li><a href="aboutus">About Us</a></li>
											<li><a href="terms">User Terms</a></li>
											<li><a href="contact">Contact US</a></li>
														
											
										</ul>
									</li>
									<li class="dropdown"><a href="#">Vendor</a>
										<ul>
										 										<li>
										<a href="search_result1?cat=Wedding Planner">Wedding Planner</a></li>
										    										<li>
										<a href="search_result1?cat=Beauty and Makup">Beauty and Makup</a></li>
										    										<li>
										<a href="search_result1?cat=Wedding Venues">Wedding Venues</a></li>
										    										<li>
										<a href="search_result1?cat=Mehndi Artist">Mehndi Artist</a></li>
										    										<li>
										<a href="search_result1?cat=Caterers                     ">Caterers                     </a></li>
										    										<li>
										<a href="search_result1?cat=Music">Music</a></li>
										    										<li>
										<a href="search_result1?cat=Hotel Accommodation">Hotel Accommodation</a></li>
										    										<li>
										<a href="search_result1?cat=Honeymoon Package">Honeymoon Package</a></li>
										    										<li>
										<a href="search_result1?cat=Wedding Prist">Wedding Prist</a></li>
										    										<li>
										<a href="search_result1?cat=Wedding Cards">Wedding Cards</a></li>
										    										<li>
										<a href="search_result1?cat=Jewellery">Jewellery</a></li>
										    										<li>
										<a href="search_result1?cat=Wedding Photographer">Wedding Photographer</a></li>
										    										<li>
										<a href="search_result1?cat=Rangoli ">Rangoli </a></li>
										    										<li>
										<a href="search_result1?cat=Biodata">Biodata</a></li>
										    											
											
										</ul>
									</li>
								
									<li><a href="contact">Contact us</a></li>
									
								</ul>
							</div>
							
						</nav>
						
						<!-- Outer Box -->
						<div class="outer-box">
							<ul class="login-info">
								<li><a href="register">Register </a></li>
								<li><a href="login"><span class="icon flaticon-user-3"></span>Login</a></li>
							</ul>
						</div>
						
					</div>
                   
                </div>
            </div>
        </div>
        <!--End Header Upper-->
        
		<!-- Mobile Menu  -->
        <div class="mobile-menu">
            <div class="menu-backdrop"></div>
            <div class="close-btn"><span class="icon fa fa-remove"></span></div>
            
            <nav class="menu-box">
                <div class="nav-logo"><a href="index.html"><img src="images/logo-2.png" alt="" title=""></a></div>
                <div class="menu-outer"><!--Here Menu Will Come Automatically Via Javascript / Same Menu as in Header--></div>
				<a href="register" class="btn-style-one ml-2 mt-2"><span class="btn-title">Register </span> </a>
				<a href="login" class="btn-style-one ml-2 mt-2"><span class="btn-title">Login </span></a>
		   </nav>
        </div><!-- End Mobile Menu -->
		
    </header>
    <!--End Main Header -->    <!-- Main Header-->

 <!--End Main Header -->
	
	<!-- Login Section -->
	<section class="login-section">
		<div class="auto-container">
			<div class="inner-container">
				<!-- Title Box -->
				<div class="title-box">
					<div class="title">Register</div>
					<h3>Create your account</h3>
				</div>
				
				<!--Login Form-->
				<div class="styled-form">
					<form method="post" action="register_submit">
						<div class="row clearfix">
						
						<div class="form-group col-lg-6 col-md-6 col-sm-12">
							<label>Brand Name *</label>
							<input type="text" name="brandnm" autofocus value="" maxlength="30" placeholder="Brand Name" onKeyPress="return ValidateAlpha(event); return blockSpecialChar(event);" required>
						</div>
						
						<div class="form-group col-lg-6 col-md-6 col-sm-12">
							<label>City *</label>
							<select class="custom-select-box" name="city">
									 <option value="Any" selected>Any</option>
										 										   <option value="Delhi">Delhi</option>
										    										   <option value="Noida">Noida</option>
										    										   <option value="Gurgoan">Gurgoan</option>
										    										   <option value="Pune">Pune</option>
										    										   <option value="Mumbai">Mumbai</option>
										    										   <option value="Sangli">Sangli</option>
										    										   <option value="Kolhapur">Kolhapur</option>
										    										   <option value="Aurangabad">Aurangabad</option>
										    										   <option value="Nashik">Nashik</option>
										    										   <option value="Vardha">Vardha</option>
										    							</select>
						</div>
						
						<div class="form-group col-lg-6 col-md-6 col-sm-12">
							<label>Vender Service Type *</label>
							<select class="custom-select-box" name="wedservice">
									 <option value="Any" selected>Any</option>
										 										   <option value="Wedding Planner">Wedding Planner</option>
										    										   <option value="Beauty and Makup">Beauty and Makup</option>
										    										   <option value="Wedding Venues">Wedding Venues</option>
										    										   <option value="Mehndi Artist">Mehndi Artist</option>
										    										   <option value="Caterers                     ">Caterers                     </option>
										    										   <option value="Music">Music</option>
										    										   <option value="Hotel Accommodation">Hotel Accommodation</option>
										    										   <option value="Honeymoon Package">Honeymoon Package</option>
										    										   <option value="Wedding Prist">Wedding Prist</option>
										    										   <option value="Wedding Cards">Wedding Cards</option>
										    										   <option value="Jewellery">Jewellery</option>
										    										   <option value="Wedding Photographer">Wedding Photographer</option>
										    										   <option value="Rangoli ">Rangoli </option>
										    										   <option value="Banjo">Banjo</option>
										    										   <option value="Biodata">Biodata</option>
										    							</select>
						</div>
						<div class="form-group col-lg-6 col-md-6 col-sm-12">
							<label>Mobile Number *</label>
							<div id="mobileerror">
							<input type="text" name="mobile" maxlength="10" oninput="maxLengthCheck(this)" onkeypress="return isNumber(event)" onBlur="check_exist1(this.value);"  value=""  placeholder="Mobile Number" required>
						</div>
						</div>
						<div class="form-group col-lg-6 col-md-6 col-sm-12">
							<label>Email Address *</label>
							<div id="emailerror">
							<input type="email" name="email" value="" onBlur="check_exist123(this.value);" onkeyup="nospaces(this)" placeholder="Email Address" required>
							
							<div><font color="#FF0000"></font></div></div>
						</div>
				
						<div class="form-group col-lg-6 col-md-6 col-sm-12">
							<label>Password *</label>
							<input type="password" name="password" onblur="CheckLengthPassword(this)" maxlength="20" value="" placeholder="Password" required>
								<div><font color="#FF0000"></font></div>
							 <div id="passeror" style="display:none">Password is too weak</div> 
						</div>
						
					
						<input type="submit" name="submit" value="Register" class="theme-btn btn-style-two ml-3">

						
						
						<div class="form-group col-lg-12 col-md-12 col-sm-12">
							<div class="info">
								Already have an account? <a href="login" class="signup">Login</a>
							</div>
						</div>
						
					
						
					</form>
				</div>
				
				
			</div>
		</div>
	</section>
	<!-- End Login Section -->
	
</div>
<!--End pagewrapper-->

<!--Scroll to top-->
<div class="scroll-to-top scroll-to-target" data-target="html"><span class="fa fa-arrow-circle-up"></span></div>

<script src="js/jquery.js"></script>
<script src="js/popper.min.js"></script>
<script src="js/bootstrap.min.js"></script>
<script src="js/jquery.mCustomScrollbar.concat.min.js"></script>
<script src="js/jquery.fancybox.js"></script>
<script src="js/appear.js"></script>
<script src="js/owl.js"></script>
<script src="js/wow.js"></script>
<script src="js/jquery-ui.js"></script>
<script src="js/script.js"></script>

</body>

<!-- Mirrored from gico.io/onoo/register.html by HTTrack Website Copier/3.x [XR&CO'2014], Mon, 19 Oct 2020 03:29:02 GMT -->
</html>