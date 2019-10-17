<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">

<head>

<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />

<meta name="referrer" content="never">

<title></title>

<script language="javascript">var TimeZoneJs=0;</script>

<script src="../images/js/jq.js"></script>

<script type="text/javascript" src="../images/js/hs.js"></script>

<script type="text/javascript" src="../images/js/zebra_dialog.js"></script>

<script type="text/javascript" src="Language.js"></script> 

<script language="javascript">var WTema ='../TEMA/tema/';</script>

<script type="text/javascript" src="../images/js/main.js?v="></script>

<script type="text/javascript" src="../images/js/css.js"></script>

<script type="text/javascript" src="../images/js/cscroll.js"></script>

<script type="text/javascript" src="../images/js/md5.js"></script>

<link href='Http://fonts.googleapis.com/css?family=Roboto+Condensed:700&subset=latin,latin-ext' rel='stylesheet' type='text/css'>

<link rel="stylesheet" href="../images/css/default/zebra_dialog.css" type="text/css">

<link rel="stylesheet" href="../images/tp.css" type="text/css">

<link rel="apple-touch-icon" sizes="57x57" href="/images/fav/apple-icon-57x57.png">

<link rel="apple-touch-icon" sizes="60x60" href="/images/fav/apple-icon-60x60.png">

<link rel="apple-touch-icon" sizes="72x72" href="/images/fav/apple-icon-72x72.png">

<link rel="apple-touch-icon" sizes="76x76" href="/images/fav/apple-icon-76x76.png">

<link rel="apple-touch-icon" sizes="114x114" href="/images/fav/apple-icon-114x114.png">

<link rel="apple-touch-icon" sizes="120x120" href="/images/fav/apple-icon-120x120.png">

<link rel="apple-touch-icon" sizes="144x144" href="/images/fav/apple-icon-144x144.png">

<link rel="apple-touch-icon" sizes="152x152" href="/images/fav/apple-icon-152x152.png">

<link rel="apple-touch-icon" sizes="180x180" href="/images/fav/apple-icon-180x180.png">

<link rel="icon" type="image/png" sizes="192x192" href="/images/fav/android-icon-192x192.png">

<link rel="icon" type="image/png" sizes="32x32" href="/images/fav/favicon-32x32.png">

<link rel="icon" type="image/png" sizes="96x96" href="/images/fav/favicon-96x96.png">

<link rel="icon" type="image/png" sizes="16x16" href="/images/fav/favicon-16x16.png">

<link rel="manifest" href="/images/fav/manifest.json">

<meta name="msapplication-TileColor" content="#ffffff">

<meta name="msapplication-TileImage" content="/images/fav/ms-icon-144x144.png">

<meta name="theme-color" content="#ffffff"> 

<!--///// TEMA YOLU ////-->

<link href="../TEMA/tema/style.css" rel="stylesheet" type="text/css" />

<!--///// TEMA YOLU ////-->

<script src="../images/js/tp.js"></script>

<link rel='stylesheet' type='text/css' href="../TEMA/tema/listeleme2.css?v=">

<script type='text/javascript' src="../images/js/List2.js?v="></script>

<script language="javascript">

$(document ).ready(function() { Start(); });

</script>

</head>

<body>

<div style="width:200px; height:100px; background:#009900; display:none; position:fixed; bottom:0px; left:0px; z-index:9999999999" class="ibilgim"></div>

<div class="MTR" style="width:0px; height:0px; background:#CCCC00; position:fixed; top:0px; left:0px; z-index:99999;"></div>

<div id="container" >

<div class="header">

<a href="./"><img src="../zimg/logo.png" class="left" /></a>

<div class="uye_ust" >

<div id="Log_in1" style="display:none">

<form id="LG">

<input name="User" id="User" type="text" placeholder="Username" class="css_input rad5" />

<input name="Pass" id="Pass" type="password" placeholder="Password" class="css_input rad5" />

<input name="" type="button" value="Login" class="css_buton rad5 trans hoveris pointer" onclick="Login(1)" />

</form>

<p> <a href="#">Forgot password</a> |<span style="font-size:1px">o</span> <a href="#NewUser" id="fblg">Register here</a></p>

</div>

<div id="Log_in2" style="display:none"></div>

<div id="clear"></div>

</div>

<div id="clear"></div>

</div>

<div class="menu">

<a href=""><div class="menu_li">HOME</div></a>

<a href=""><div class="menu_li"><b>SPORT</b></div></a>

<a href="javascript:LiveLink()"><div class="menu_li"><b>LIVE</b></div></a>

<a href="javascript:void(0)" onclick="TodaY()"><div class="menu_li">TODAYS <b>MATCHES</b></div></a>

<div id="TimerGenel"></div>

<div id="Lng_Men"></div>

<div id="clear"></div>

</div>

<div class="content">

<div id="MXXXXX"></div>

<div class="SSSOL">

<div class="SSSOLX">

<!-------------------XX-->

<div class="SS_A" >

<h2 class="bg2"><img src="../images/ara_1.png" />Search</h2>

<div class="SS_B" style="position:relative; z-index:600">

<input name="Sch" id="Schr" value="Search here" onblur="if(this.value=='') this.value='Search here';" onfocus="if(this.value=='Search here') this.value='';" class="css_input2 S" />

<input name="" value=" " type="submit" class="css_ara" />

<div class="MACARA_01 Off">

</div>

<div id="clear"></div>

</div>

</div>

<!-------------------YY-->

<!-------------------XX-->

<div class="SS_A">

<h2 class="bg2"><img src="../images/icon_1.png" />Time Zone</h2>

<div class="SS_B">

<select name="T2T" id="T2T" class="css_select" onchange="T2TF()">

<option value="N">All</option>

<option value="0">Today</option>

<option value="2">2 days</option>

<option value="3">3 days</option>

<option value="7">1 week</option>

</select>

<div id="clear"></div>

</div>

<!--Menu Start-->

<div id="MenuM"></div>

<!--Menu End-->

</div>

<!-------------------YY-->

<!-------------------XX-->

<div class="DR_op_1">LIVE</div>

<div id="LivMen1"></div>

<div id="LivMen0"></div>

<!-------------------YY-->

</div><!--SSSOLX-->

</div><!--SSSOL-->

<div class="SSORTR">

<div class="SSORT" id="MACM"> </div>

</div>

<div class="SSSAG">

<div class="SSSAGX">

<!-------------------XX-->

<div class="yapdurum" style="">

<div class="SS_A" id="CP_Falow">

<h2 class="bg2 ZYUKSEK_"><img src="../images/icon_3.png" />Bet coupon</h2>

<div class="SS_B">

<ul id="kuponum"></ul>

<div id="CoupAll" class="Off">

<div class="secim1 ttsec">

<span> </span> <span style="cursor:pointer; float:right" onclick="CouponRemoveAll()">Clear All</span>

</div>

<div id="CoupSYS" class="Off"></div>

<div class="secim2">

<span style="float:right;"><span id="TpTut1">Amount</span><span id="TpTut2" class="Off">Amount of stake</span> : <span id="Cperr3"><input name="CMiktar" id="CMiktar" type="text" value="" style="width:40px; height:20px; outline:none; border:none; color:#666666; padding:0px 5px 0px 5px; margin:0px;" /></span></span>

<div id="clear"></div>

</div>

<div class="secim3">

Number of Bets : <span style="float:right;" id="B_Mik"> </span>

<div id="clear"></div>

</div>

<div class="secim3">

Total Betting Amount : <span style="float:right;" id="B_Orn"> </span>

<div id="clear"></div>

</div>

<div class="secim3">

Win(Max) : <span style="float:right;" id="B_Kaz"> </span>

<div id="clear"></div>

</div>

<div class="secim3">

Winning Tax %<span id="txw">15</span> : <span style="float:right;" id="B_MTax"> </span>

<input type="hidden" name="WinTax" id="WinTax" value="15">

<input type="hidden" name="WinTaxVal" id="WinTaxVal" value="0">

<div id="clear"></div>

</div>

<div class="secim3">

Net Win : <span style="float:right;" id="B_MNet"> </span>

<div id="clear"></div>

</div> 

<div class="secim3 B_Bon" style="display:none">

Possible Bonus : <span style="float:right;" id="B_Bon"> </span>

<div id="clear"></div>

</div>

<div class="secim4 " id="Cperr">

<div id="CGuest"></div>

<div class="css_buton2 rad5 trans hoveris pointer" onclick="SanaLogin()" id="GDevm">Continiue</div>

<div id="clear"></div>

</div>

<div id="Cperr2" class="secim2 Off"></div>

<div class="secim3 Sg_bg Off">

<input type="checkbox" value="" id="OChn" /> Accept to odds change. 

</div>

<div class="OG_bg Off" style="padding:0px;"> 

<div id="GFchn" class="secim3" style="background:#F03; color:#fff; display:none"><input type="checkbox" value="" id="FChn" /> Alert for number of bets : I know there are two or more selection of an same event and i read number of bets.</div></div>

<div class="OG_bg Off">

<div class="OG_gonder">

<div class="GOM_1" onclick="CP_SAVE()">SEND</div>

<div class="GOM_2">PLEASE WAIT !</div>

</div>

</div>

<div class="GOM_3" style="text-align:center;">

<img src="../images/yazdir.png" class="TT_KP GOM_4" title="PRINT" />

<img src="../images/yeni.png" class="TT_KP" title="NEW COUPON" onclick="CouponRemoveAll()" />

<img src="../images/kupdevam.png" class="TT_KP" title="CONTINUE COUPON" onclick="CP_RET()" />

<div id="clear"></div>

</div>

</div>

<div class="CC-BUL" style="display:none">

<div class="CC-CUP">[*Kupon No* ] : </div>

<div style="position:relative;">

<input id="" value="" class="CC-INP"/><div class="CC-GON" onclick=""></div>

<div id="clear"></div>

</div>

<div id="clear"></div>

</div>

<div id="clear"></div>

</div>

</div>

<div id="clear"></div>

</div>

</div><!--SSSAGX-->

</div><!--SSSAG-->

<div id="clear"></div>

</div>

<div class="footer" style="position:relative;"> 

<div class="card_footer"></div>

<div class="altmenu">

<span style="cursor:pointer" onclick="TermS('GRules')">Betting Rules</span> | About & Contact | Private informations | Frequently Asked Questions <br /><br />

<span style="color:#CCCCCC; font-size:11px;" id="CopyRght"></span>

</div>

<div id="clear"></div>

</div>

</div>

<div class="footer_bg"></div>

</body>

</html>

