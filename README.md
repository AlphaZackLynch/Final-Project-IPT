# Final-Project-IPT


*Main Website

<!DOCTYPE html>
<html lang="en">

  <head>

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="">
    <link href="https://fonts.googleapis.com/css?family=Poppins:100,200,300,400,500,600,700,800,900" rel="stylesheet">

    <title>Education Meeting HTML5 Template</title>

    <!-- Bootstrap core CSS -->
    <link href="vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">


    <!-- Additional CSS Files -->
    <link rel="stylesheet" href="assets/css/fontawesome.css">
    <link rel="stylesheet" href="assets/css/templatemo-edu-meeting.css">
    <link rel="stylesheet" href="assets/css/owl.css">
    <link rel="stylesheet" href="assets/css/lightbox.css">

  </head>

<body>

  <!-- Sub Header -->
  <div class="sub-header">
    <div class="container">
      <div class="row">
        <div class="col-lg-8 col-sm-8">
          <div class="left-content">
           
          </div>
        </div>
        <div class="col-lg-4 col-sm-4">
          <div class="right-icons">
            <ul>
              <li><a href="https://www.facebook.com/johnpaul.moldon"><i class="fa fa-facebook"></i></a></li>
              <li><a href="https://twitter.com/JohnpaulMoldon"><i class="fa fa-twitter"></i></a></li>
             
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- ***** Header Area Start ***** -->
  <header class="header-area header-sticky">
      <div class="container">
          <div class="row">
              <div class="col-12">
                  <nav class="main-nav">
                      <!-- ***** Logo Start ***** -->
                      <a href="index.html" class="logo">
                         FINAL PROJECT
                      </a>
                      <!-- ***** Logo End ***** -->
                      <!-- ***** Menu Start ***** -->
                      <ul class="nav">
                          <li class="scroll-to-section"><a href="#top" class="active">ACTIVITIES</a></li>
                          <li><a href="ACT 2/Act 2.html">ACTIVITY 2</a></li>
                          <li><a href="ACT 3/Act 3.html">ACTIVITY 3</a></li>
                          <li><a href="ACT 4/Act 4.html">ACTIVITY 4</a></li>
                          <li><a href="ACT 5/Act 5.html">ACTIVITY 5</a></li>
    
                      </a>
                     
                  </nav>
              </div>
          </div>
      </div>
  </header>
  
  <section class="section main-banner" id="top" data-section="section1">
      <video autoplay muted loop id="bg-video">
          <source src="assets/images/Veigar.mp4" type="video/mp4" />
      </video>

      <div class="video-overlay header-text">
          <div class="container">
            <div class="row">
              <div class="col-lg-12">
                <div class="caption">
              <h6>BSIT - 2G</h6>
              <h2>JOHN PAUL G. MOLDON</h2>
              <p>Thank you Sir, Jonas Macapagal for teaching us how to use HTML and CSS in creating website.</p>
              <div class="main-button-red">
                  <a href="https://www.youtube.com/channel/UCypja49RlxwpuflO_3_wM6A">MY YOUTUBE CHANNEL</a>
              </div>
          </div>
              </div>
            </div>
          </div>
      </div>
  </section>
  <!-- ***** Main Banner Area End ***** -->

  <section class="services">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="owl-service-item owl-carousel">
          
            <div class="item">
              <div class="icon">
                <img src="assets/images/cat.png" alt="">
              </div>
              <div class="down-content">
                <h4 style="color: black">Activity 2</h4>
                <p  style="color: black"> CREATING MY FIRST WEBPAGE </p>
              </div>
            </div>
            
            <div class="item">
              <div class="icon">
                <img src="assets/images/cat (1).png" alt="">
              </div>
              <div class="down-content">
                <h4 style="color: black">Activity 3</h4>
                <p style="color: black">PUTTING SOME CSS TO MY WEBPAGE</p>
              </div>
            </div>
            
            <div class="item">
              <div class="icon">
                <img src="assets/images/cat (2).png" alt="">
              </div>
              <div class="down-content">
                <h4 style="color: black">Activity 4</h4>
                <p style="color: black">ADDING USER/HOME WEBPAGE.</p>
              </div>
            </div>
            
            <div class="item">
              <div class="icon">
                <img src="assets/images/cat (3).png" alt="">
              </div>
              <div class="down-content">
                <h4 style="color: black">Activity 5</h4>
                <p style="color: black">ADDING FAMILY WEBPAGE</p>
              </div>
            </div>
  </section>

  
 
    <div class="footer">
      <p style="color: black">Moldon, John Paul G. BSIT - 2G/ IPT - 2022. 
      </p>
    </div>
  </section>

  <!-- Scripts -->
  <!-- Bootstrap core JavaScript -->
    <script src="vendor/jquery/jquery.min.js"></script>
    <script src="vendor/bootstrap/js/bootstrap.bundle.min.js"></script>

    <script src="assets/js/isotope.min.js"></script>
    <script src="assets/js/owl-carousel.js"></script>
    <script src="assets/js/lightbox.js"></script>
    <script src="assets/js/tabs.js"></script>
    <script src="assets/js/video.js"></script>
    <script src="assets/js/slick-slider.js"></script>
    <script src="assets/js/custom.js"></script>
    <script>
        //according to loftblog tut
        $('.nav li:first').addClass('active');

        var showSection = function showSection(section, isAnimate) {
          var
          direction = section.replace(/#/, ''),
          reqSection = $('.section').filter('[data-section="' + direction + '"]'),
          reqSectionPos = reqSection.offset().top - 0;

          if (isAnimate) {
            $('body, html').animate({
              scrollTop: reqSectionPos },
            800);
          } else {
            $('body, html').scrollTop(reqSectionPos);
          }

        };

        var checkSection = function checkSection() {
          $('.section').each(function () {
            var
            $this = $(this),
            topEdge = $this.offset().top - 80,
            bottomEdge = topEdge + $this.height(),
            wScroll = $(window).scrollTop();
            if (topEdge < wScroll && bottomEdge > wScroll) {
              var
              currentId = $this.data('section'),
              reqLink = $('a').filter('[href*=\\#' + currentId + ']');
              reqLink.closest('li').addClass('active').
              siblings().removeClass('active');
            }
          });
        };

        $('.main-menu, .responsive-menu, .scroll-to-section').on('click', 'a', function (e) {
          e.preventDefault();
          showSection($(this).attr('href'), true);
        });

        $(window).scroll(function () {
          checkSection();
        });
    </script>
</body>

</body>
</html>



*Act 2

<!DOCTYPE html>
<html>
<head>
	<link rel="stylesheet" href="Mystyle.css" />
<style>


</style>
</head>
<body>
<center>
 <h1>MY 2ND ACTIVITY </h1>
<hr> 
<p> Good day! let's try <b> THE HTML PRACTICE </b> </p>
<hr> 

<h3 style="color:yellow;"><u>TIKTOK</u></h3> 


<p style="color:red;">
	Napili ko ang Tiktok website dahil dito ako madalas tumambay at manood
	ng mga trending videos dito. Ang madalas kong pinapanood dito<br />
	ay ang ibat-ibang videos na related sa Anime dahil ako ay superfan ng japanese culture
	. Ako ay nanonood ng highlights, edits,<br />
	at mga cut scene ng mga episode dito upang ako ay lagging updated sa mga nangyayari
	sinusubaybayan kung anime. Sa kabilang dako naman, ang tiktok rin<br />
	ay nakakalibang saken at nakakapagbigay ng mga impormasyon around the
	world. Ako rin ay nakafallow sa ibang content creators.</p>

<h3 style="color:yellow;"><u>MANGALIFE</u></h3> 



<p style="color:red;"> Itong website na ito ang binibisita ko kapag may mga libre ako na oras para magbasa ng Manga na sinusubaybayan ko
	Ito ang website na naiintertain ako sa pagbabasa.Nagmula ang Manga sa Japan noong huling bahagi ng 1800s. Ang mga ito ay orihinal na mga comic strip ngunit naging mas sikat bilang mga cartoon. 
	Ang Manga ay itinuturing na ngayon na isang uri ng graphic novel.
</p>

<h3 style="color:yellow;"><u>YOUTUBE</u></h3> 



<p style="color:red;"> Sa youtube din po ako madalas tumambay na website dahil nakaka intertain manood ng mga educational videos Dito
	at iba pang klase ng mga vids.<br />
	Bukod ditto ako rin ay nanonood ng mga livestream mula saking mga sikat
	na mga vloggers at kadalasan dito rin ako nag sesearch ng mga news local or international.
</p>

<h3 style="color:yellow;"><u>FACEBOOK</u></h3> 



<p style="color:red;">Facebook ay isa rin sa mga importante na kailangan ko na app/website.
	<br />
	Ang Facebook ay isang website kung saan nagbabahagi ang mga tao ng mga larawan at video sa ibang tao. 
	Maaari ka ring makipag-chat tungkol sa mga kaganapan, magkaroon ng mga bagong kaibigan, matuto ng mga bagong bagay at manood ng mga nakakatawang video. 
	Ang mga tao ay maaaring manatiling up-to-date sa mga kasalukuyang balita rin. Maaaring kabilang dito ang mga kaganapang nagaganap sa kanilang paligid gaya ng mga konsyerto o mga larong pampalakasan.
</p>

<h3 style="color:yellow;"><u>GOOGLE</u></h3> 



<p style="color:red;">  Ang Google ay isang napakahalagang bahagi ng ating buhay. Ginagamit namin ito araw-araw at lubos na umaasa dito. 
	Ginagawa nitong mas madali ang ating buhay sa pamamagitan ng pagbibigay sa atin ng gusto natin kapag gusto natin ito. 
	Gayunpaman, mayroong maraming iba pang mga search engine doon na nagbibigay ng iba't ibang mga resulta kaysa sa Google. 
	Ang ilan ay hindi gumagana nang mahusay o mahusay tulad ng Google, ngunit ang iba ay maaaring mas angkop para sa iyong mga partikular na pangangailangan. 
	Nasa iyo ang pagtukoy kung alin ang akma para sa iyong partikular na mga pangangailangan.
</p>

<table table border="1px solid" style="width:50%">
<tr> 
	<th rowspan="6" style="color:yellow;">BROWSER</th>
	<td colspan="2" style="text-align:center" style="color:yellow;">HROME</td>
<td style="text-align:center" style="color:yellow;">WEBSITES</td>
<td style="text-align:center" style="color:yellow;">LINK</td>
</tr>
	
</tr>
</tr>
<tr> 
	<td style="color:yellow;">CHROME</td>
	<td style="color:yellow;">FIREFOX</td>
	<td style="color:yellow;">TIKTOK</td>
	<td style="color:yellow;"><a href="https://www.tiktok.com/?fbclid=IwAR0AUfunRMj3oJJ2ma3MQUJECpWgFduBoVRjxPF1FSlvRmnzpTaOLQfm6cQ " target="_blank" >tiktok.com</a></td>
      

      

</tr>
<tr> 
	<th style="color:yellow;">CHROME</th>
	<td style="color:yellow;">FIREFOX</td>
	<td style="color:yellow;">GOOGLE CLASSROOM</td>
	<td style="color:yellow;"><a href=" https://classroom.google.com/h " target="_blank" >googleclassroom.com.com</a></td>
	
	
</tr>
<tr> 
	<th style="color:yellow;">CHROME</th>
	<td style="color:yellow;">FIREFOX</td>
	<td style="color:yellow;">YOUTUBE</td>
	<td style="color:yellow;"><a href=" https://www.youtube.com/" target="_blank" >youtubecom</a></td>


	
</tr>
<tr> 
	<th style="color:yellow;">CHROME</th>
	<td style="color:yellow;">FIREFOX</td>
	<td style="color:yellow;">FACEBOOK</td>
	<td style="color:yellow;"><a href=" https://www.facebook.com/edrianmark.adlaon " target="_blank" >facebook.com</a></td>
	

</tr>
<tr> 
	<th style="color:yellow;">CHROME</th>
	<td style="color:yellow;">FIREFOX</td>
	<td style="color:yellow;">GOOGLE</td>
	<td style="color:yellow;"><a href=" https://www.facebook.com/edrianmark.adlaon " target="_blank" >google.com</a></td>


	
</tr>



	
	
	
	
	
*Act 3

<!DOCTYPE html>
<html>
  <head>
  </head>
  <body>
    
    <link rel="stylesheet" href="Mystyle.css"> 

    <center>
      <h1>MY THIRD ACTIVITY</h1>
      <hr />
      <p>Good day! let's try <b> THE HTML PRACTICE </b></p>
      <hr />

      <h2 align="center"><b><a href="https://www.tiktok.com/" target="_blank"><img src="tik-tok.png"width=64" height="64"> </a> </b></h2>
      </a>

      <h3 style="color: rgb(11, 207, 142)"><u>TIKTOK</u></h3>
      <p style="color: black">
        Napili ko ang Tiktok website dahil dito ako madalas tumambay at manood
        ng mga trending videos dito. Ang madalas kong pinapanood dito<br />
        ay ang ibat-ibang videos na related sa Anime dahil ako ay superfan ng japanese culture
        . Ako ay nanonood ng highlights, edits,<br />
        at mga cut scene ng mga episode dito upang ako ay lagging updated sa mga nangyayari
        sinusubaybayan kung anime. Sa kabilang dako naman, ang tiktok rin<br />
        ay nakakalibang saken at nakakapagbigay ng mga impormasyon around the
        world. Ako rin ay nakafallow sa ibang content creators.
      </p>

      <h2 align="center"><b><a href="https://manga4life.com/" target="_blank"><img src="Mangalife.png"width="64"height="64"> </a> </b></h2>
      </a>

      <h3 style="color: rgb(37, 46, 37)"><u>MANGA4LIFE</u></h3>
      <p style="color: black">
        Itong website na ito ang binibisita ko kapag may mga libre ako na oras para magbasa ng Manga na sinusubaybayan ko
        Ito ang website na naiintertain ako sa pagbabasa.Nagmula ang Manga sa Japan noong huling bahagi ng 1800s. Ang mga ito ay orihinal na mga comic strip ngunit naging mas sikat bilang mga cartoon. 
        Ang Manga ay itinuturing na ngayon na isang uri ng graphic novel.
        <br />
        
        <h2 align="center"><b><a href="https://www.youtube.com/" target="_blank"><img src="youtube.png"width=64" height="64"> </a> </b></h2>
      </a>

      <h3 style="color: red"><u>YOUTUBE</u></h3>
      <p style="color: black">
        
      <p> Sa youtube din po ako madalas tumambay na website dahil nakaka intertain manood ng mga educational videos Dito
        at iba pang klase ng mga vids.<br />
        Bukod ditto ako rin ay nanonood ng mga livestream mula saking mga sikat
        na mga vloggers at kadalasan dito rin ako nag sesearch ng mga news local or international. <br/>
        
      </p>

      
        <h2 align="center"><b><a href="https://www.facebook.com/johnpaul.moldon" target="_blank"><img src="facebook.png"width=64" height="64"> </a> </b></h2>
      </a>
      <h3 style="color: blue"><u>FACEBOOK</u></h3>
      <p style="color: black">
        Facebook ay isa rin sa mga importante na kailangan ko na app/website.
        <br />
        Ang Facebook ay isang website kung saan nagbabahagi ang mga tao ng mga larawan at video sa ibang tao. 
        Maaari ka ring makipag-chat tungkol sa mga kaganapan, magkaroon ng mga bagong kaibigan, matuto ng mga bagong bagay at manood ng mga nakakatawang video. 
        Ang mga tao ay maaaring manatiling up-to-date sa mga kasalukuyang balita rin. Maaaring kabilang dito ang mga kaganapang nagaganap sa kanilang paligid gaya ng mga konsyerto o mga larong pampalakasan.
      </p>

      
        <h2 align="center"><b><a href="https://www.google.com/" target="_blank"><img src="google.png"width=64" height="64"> </a> </b></h2>
      </a>

      <h3 style="color: green"><u>GOOGLE</u></h3>
      <p style="color: black">
        Ang Google ay isang napakahalagang bahagi ng ating buhay. Ginagamit namin ito araw-araw at lubos na umaasa dito. 
        Ginagawa nitong mas madali ang ating buhay sa pamamagitan ng pagbibigay sa atin ng gusto natin kapag gusto natin ito. 
        Gayunpaman, mayroong maraming iba pang mga search engine doon na nagbibigay ng iba't ibang mga resulta kaysa sa Google. 
        Ang ilan ay hindi gumagana nang mahusay o mahusay tulad ng Google, ngunit ang iba ay maaaring mas angkop para sa iyong mga partikular na pangangailangan. 
        Nasa iyo ang pagtukoy kung alin ang akma para sa iyong partikular na mga pangangailangan.
      </p>
    </center>
  </body>
</html>

	  
	  
	  
	  
	  
	  
	  
*Act 4
<!DOCTYPE html>
<html>
  <head>
  </head>
  <body>
    
    <link rel="stylesheet" href="Mystyle.css"> 

    <center>
      <h1>MY FOURTH ACTIVITY</h1>
      <hr />
      <p>Good day! let's try <b> THE HTML PRACTICE </b></p>
      <hr />

      <h2 align="center"><b><a href="https://www.tiktok.com/" target="_blank"><img src="tik-tok.png"width=64" height="64"> </a> </b></h2>
      </a>

      <h3 style="color: rgb(11, 207, 142)"><u>TIKTOK</u></h3>
      <p style="color: black">
        Napili ko ang Tiktok website dahil dito ako madalas tumambay at manood
        ng mga trending videos dito. Ang madalas kong pinapanood dito<br />
        ay ang ibat-ibang videos na related sa Anime dahil ako ay superfan ng japanese culture
        . Ako ay nanonood ng highlights, edits,<br />
        at mga cut scene ng mga episode dito upang ako ay lagging updated sa mga nangyayari
        sinusubaybayan kung anime. Sa kabilang dako naman, ang tiktok rin<br />
        ay nakakalibang saken at nakakapagbigay ng mga impormasyon around the
        world. Ako rin ay nakafallow sa ibang content creators.
      </p>

      <h2 align="center"><b><a href="https://manga4life.com/" target="_blank"><img src="Mangalife.png"width="64"height="64"> </a> </b></h2>
      </a>

      <h3 style="color: rgb(37, 46, 37)"><u>MANGA4LIFE</u></h3>
      <p style="color: black">
        Itong website na ito ang binibisita ko kapag may mga libre ako na oras para magbasa ng Manga na sinusubaybayan ko
        Ito ang website na naiintertain ako sa pagbabasa.Nagmula ang Manga sa Japan noong huling bahagi ng 1800s. Ang mga ito ay orihinal na mga comic strip ngunit naging mas sikat bilang mga cartoon. 
        Ang Manga ay itinuturing na ngayon na isang uri ng graphic novel.
        <br />
        
        <h2 align="center"><b><a href="https://www.youtube.com/" target="_blank"><img src="youtube.png"width=64" height="64"> </a> </b></h2>
      </a>

      <h3 style="color: red"><u>YOUTUBE</u></h3>
      <p style="color: black">
        
      <p> Sa youtube din po ako madalas tumambay na website dahil nakaka intertain manood ng mga educational videos Dito
        at iba pang klase ng mga vids.<br />
        Bukod ditto ako rin ay nanonood ng mga livestream mula saking mga sikat
        na mga vloggers at kadalasan dito rin ako nag sesearch ng mga news local or international. <br/>
        
      </p>

      
        <h2 align="center"><b><a href="https://www.facebook.com/johnpaul.moldon" target="_blank"><img src="facebook.png"width=64" height="64"> </a> </b></h2>
      </a>
      <h3 style="color: blue"><u>FACEBOOK</u></h3>
      <p style="color: black">
        Facebook ay isa rin sa mga importante na kailangan ko na app/website.
        <br />
        Ang Facebook ay isang website kung saan nagbabahagi ang mga tao ng mga larawan at video sa ibang tao. 
        Maaari ka ring makipag-chat tungkol sa mga kaganapan, magkaroon ng mga bagong kaibigan, matuto ng mga bagong bagay at manood ng mga nakakatawang video. 
        Ang mga tao ay maaaring manatiling up-to-date sa mga kasalukuyang balita rin. Maaaring kabilang dito ang mga kaganapang nagaganap sa kanilang paligid gaya ng mga konsyerto o mga larong pampalakasan.
      </p>

      
        <h2 align="center"><b><a href="https://www.google.com/" target="_blank"><img src="google.png"width=64" height="64"> </a> </b></h2>
      </a>

      <h3 style="color: green"><u>GOOGLE</u></h3>
      <p style="color: black">
        Ang Google ay isang napakahalagang bahagi ng ating buhay. Ginagamit namin ito araw-araw at lubos na umaasa dito. 
        Ginagawa nitong mas madali ang ating buhay sa pamamagitan ng pagbibigay sa atin ng gusto natin kapag gusto natin ito. 
        Gayunpaman, mayroong maraming iba pang mga search engine doon na nagbibigay ng iba't ibang mga resulta kaysa sa Google. 
        Ang ilan ay hindi gumagana nang mahusay o mahusay tulad ng Google, ngunit ang iba ay maaaring mas angkop para sa iyong mga partikular na pangangailangan. 
        Nasa iyo ang pagtukoy kung alin ang akma para sa iyong partikular na mga pangangailangan.
      </p>
    </center>


    <div class="menu">
      <a href="Menu.html"><img src="Menu.png"width= "50" height="50"> </a> </b>
    </div>
  </body>
</html>

*Menu

<!DOCTYPE html>
<html lang="en">
    <link rel="stylesheet" href="Mystyle.css" />
    <title>Act4</title>
  </head>
      <center>
        <hr/>
        <h1>MENU</h1>
        <hr/> 
      </center>

    <div class="firsticon"><b><a href="Act 4.html"><img src="house.png"width="50" height="50"> </a> </b></div>

    
    <p class="favorite">
      Palagi akong nanonood ng mga anime na karakter ng Anime ay nakakarelate dahil ipinapakita nila sa amin kung paano hinarap ng mga tao ang mga katulad na problema sa totoong buhay.
      Ginagawa nitong mas nauunawaan at mas madaling iugnay sila.  Mahilig talga ako sa japanese culture gaya ng Manga na isang Japanese na istilo ng komiks na nagkukuwento tungkol sa mga tao, lugar, at bagay. Maraming iba't ibang uri ng manga. 
      Ang ilan ay iginuhit ng kamay habang ang iba ay gumagamit ng mga computer. Ang Manga ay kadalasang ginagamit bilang isang tool na pang-edukasyon upang turuan ang mga bata tungkol sa kasaysayan, agham, matematika, sining ng wika, heograpiya, at iba pang mga paksa. Ang anime ay sinadya upang panoorin bilang mga pelikula, 
      habang ang manga ay sinadya upang basahin parang book format.
    </p>

    <div class="firsticon"><b><a href="User.html"><img src="profile.png"width=50" height="50"> </a> </b></div>
    
    &nbsp;&nbsp;
    <p class="favorite"> 
      My Name is John Paul Gilbaliga Moldon, 20 years old, bI was born from Quezon City, Im currently living on Blk 21 lot 3 <br />
      Southville 8c San Isidro rodriguez rizal. My birthday is March 20, 2002. 
       <br />
      now i am 2nd year at colegio de montalban on rodriguez rizal. I like
      .
    </p>

    </p>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
  </body>
</html>


*User

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Act4</title>

    <link rel="stylesheet" href="Mystyle.css" />
  </head>
  <body>
    <center>
      <hr />
      <h1>USER</h1>
      <hr />
      <link rel="stylesheet" href=""><img class="img2" src="Paul.png" />
      <br />
  
      <div class="header">JOHN PAUL G. MOLDON</div>
   
      <br />
      </BR>
      <br>
      <br>
    
      <div class="header" >I LOVE COFFEE</div>
    

      <div class="container">
    <br>
    <br>
    <br>
    
    <div class="col1">Place of Birth:</div> 
    <div class="col2">San Roque II Q.C</div>
    <br>
    <br>
    <div class="col1">Civil Status:</div>
    <div class="col2">Single</div>
    <br>
    <br>
    <div class="col1">Religion:</div>
    <div class="col2">Chatholic</div>
    <br>
    <br>
    <div class="col1">Citizenship:</div>
    <div class="col2">Filipino  </div>
    <br>
    <br>
    <div class="col1">height:</div>
    <div class="col2">5.10 feet</div>
    <br>
    <br>
    <br>
    <br>
    </center>
    <div>
      <b>
        <a class="menu2" href="Menu.html"><img src="menu.png"width=50" height="50"> </a>
       
      </b>
    </div>
  </body>
</html>

*Act 5

<!DOCTYPE html>
<html>
  <head>
  </head>
  <body>
    
    <link rel="stylesheet" href="Mystyle.css"> 

    <center>
      <h1>MY FIFTH ACTIVITY</h1>
      <hr />
      <p>Good day! let's try <b> THE HTML PRACTICE </b></p>
      <hr />

      <h2 align="center"><b><a href="https://www.tiktok.com/" target="_blank"><img src="tik-tok.png"width=64" height="64"> </a> </b></h2>
      </a>

      <h3 style="color: rgb(11, 207, 142)"><u>TIKTOK</u></h3>
      <p style="color: black">
        Napili ko ang Tiktok website dahil dito ako madalas tumambay at manood
        ng mga trending videos dito. Ang madalas kong pinapanood dito<br />
        ay ang ibat-ibang videos na related sa Anime dahil ako ay superfan ng japanese culture
        . Ako ay nanonood ng highlights, edits,<br />
        at mga cut scene ng mga episode dito upang ako ay lagging updated sa mga nangyayari
        sinusubaybayan kung anime. Sa kabilang dako naman, ang tiktok rin<br />
        ay nakakalibang saken at nakakapagbigay ng mga impormasyon around the
        world. Ako rin ay nakafallow sa ibang content creators.
      </p>

      <h2 align="center"><b><a href="https://manga4life.com/" target="_blank"><img src="Mangalife.png"width="64"height="64"> </a> </b></h2>
      </a>

      <h3 style="color: rgb(37, 46, 37)"><u>MANGA4LIFE</u></h3>
      <p style="color: black">
        Itong website na ito ang binibisita ko kapag may mga libre ako na oras para magbasa ng Manga na sinusubaybayan ko
        Ito ang website na naiintertain ako sa pagbabasa.Nagmula ang Manga sa Japan noong huling bahagi ng 1800s. Ang mga ito ay orihinal na mga comic strip ngunit naging mas sikat bilang mga cartoon. 
        Ang Manga ay itinuturing na ngayon na isang uri ng graphic novel.
        <br />
        
        <h2 align="center"><b><a href="https://www.youtube.com/" target="_blank"><img src="youtube.png"width=64" height="64"> </a> </b></h2>
      </a>

      <h3 style="color: red"><u>YOUTUBE</u></h3>
      <p style="color: black">
        
      <p> Sa youtube din po ako madalas tumambay na website dahil nakaka intertain manood ng mga educational videos Dito
        at iba pang klase ng mga vids.<br />
        Bukod ditto ako rin ay nanonood ng mga livestream mula saking mga sikat
        na mga vloggers at kadalasan dito rin ako nag sesearch ng mga news local or international. <br/>
        
      </p>

      
        <h2 align="center"><b><a href="https://www.facebook.com/johnpaul.moldon" target="_blank"><img src="facebook.png"width=64" height="64"> </a> </b></h2>
      </a>
      <h3 style="color: blue"><u>FACEBOOK</u></h3>
      <p style="color: black">
        Facebook ay isa rin sa mga importante na kailangan ko na app/website.
        <br />
        Ang Facebook ay isang website kung saan nagbabahagi ang mga tao ng mga larawan at video sa ibang tao. 
        Maaari ka ring makipag-chat tungkol sa mga kaganapan, magkaroon ng mga bagong kaibigan, matuto ng mga bagong bagay at manood ng mga nakakatawang video. 
        Ang mga tao ay maaaring manatiling up-to-date sa mga kasalukuyang balita rin. Maaaring kabilang dito ang mga kaganapang nagaganap sa kanilang paligid gaya ng mga konsyerto o mga larong pampalakasan.
      </p>

      
        <h2 align="center"><b><a href="https://www.google.com/" target="_blank"><img src="google.png"width=64" height="64"> </a> </b></h2>
      </a>

      <h3 style="color: green"><u>GOOGLE</u></h3>
      <p style="color: black">
        Ang Google ay isang napakahalagang bahagi ng ating buhay. Ginagamit namin ito araw-araw at lubos na umaasa dito. 
        Ginagawa nitong mas madali ang ating buhay sa pamamagitan ng pagbibigay sa atin ng gusto natin kapag gusto natin ito. 
        Gayunpaman, mayroong maraming iba pang mga search engine doon na nagbibigay ng iba't ibang mga resulta kaysa sa Google. 
        Ang ilan ay hindi gumagana nang mahusay o mahusay tulad ng Google, ngunit ang iba ay maaaring mas angkop para sa iyong mga partikular na pangangailangan. 
        Nasa iyo ang pagtukoy kung alin ang akma para sa iyong partikular na mga pangangailangan.
      </p>
    </center>


    <div class="menu">
      <a href="Menu.html"><img src="Menu.png"width= "50" height="50"> </a> </b>
    </div>
  </body>
</html>

*Menu
<!DOCTYPE html>
<html lang="en">
    <link rel="stylesheet" href="Mystyle.css" />
    <title>Act4</title>
  </head>
      <center>
        <hr/>
        <h1>MENU</h1>
        <hr/> 
      </center>

    <div class="firsticon"><b><a href="Act 5.html"><img src="house.png"width="50" height="50"> </a> </b></div>

    
    <p class="favorite">
      Palagi akong nanonood ng mga anime na karakter ng Anime ay nakakarelate dahil ipinapakita nila sa amin kung paano hinarap ng mga tao ang mga katulad na problema sa totoong buhay.
      Ginagawa nitong mas nauunawaan at mas madaling iugnay sila.  Mahilig talga ako sa japanese culture gaya ng Manga na isang Japanese na istilo ng komiks na nagkukuwento tungkol sa mga tao, lugar, at bagay. Maraming iba't ibang uri ng manga. 
      Ang ilan ay iginuhit ng kamay habang ang iba ay gumagamit ng mga computer. Ang Manga ay kadalasang ginagamit bilang isang tool na pang-edukasyon upang turuan ang mga bata tungkol sa kasaysayan, agham, matematika, sining ng wika, heograpiya, at iba pang mga paksa. Ang anime ay sinadya upang panoorin bilang mga pelikula, 
      habang ang manga ay sinadya upang basahin parang book format.
    </p>

    <div class="firsticon"><b><a href="User.html"><img src="profile.png"width=50" height="50"> </a> </b></div>
    
    &nbsp;&nbsp;
    <p class="favorite"> 
      My Name is John Paul Gilbaliga Moldon, 20 years old, bI was born from Quezon City, Im currently living on Blk 21 lot 3 <br />
      Southville 8c San Isidro rodriguez rizal. My birthday is March 20, 2002. 
       <br />
      now i am 2nd year at colegio de montalban on rodriguez rizal. I like
      .
    </p>

    <div class="firsticon"><b><a href="Family.html"><img src="family.png"width=50" height="50"> </a> </b></div>
    
    &nbsp;&nbsp;
    <p class="favorite"> 
      They always care of me,They know whats's the best for me,They make me happy when I am lonely, My family is the best,They hug me when I am feeling lonely,They keep me from danger, It is awsome to have a family,
      They help you on your school work,Always listen to your problems,Solved some problems that you cannot finished, My family is tender loving. 
      If you disobey them they will ignore you,they will shall never ask you, and always look dow on you
    </p>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
  </body>
</html>

*User
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Act4</title>

    <link rel="stylesheet" href="Mystyle.css" />
  </head>
  <body>
    <center>
      <hr />
      <h1>USER</h1>
      <hr />
      <link rel="stylesheet" href=""><img class="img2" src="Paul.png" />
      <br />
  
      <div class="header">JOHN PAUL G. MOLDON</div>
   
      <br />
      </BR>
      <br>
      <br>
    
      <div class="header" >I LOVE COFFEE</div>
    

      <div class="container">
    <br>
    <br>
    <br>
    
    <div class="col1">Place of Birth:</div> 
    <div class="col2">San Roque II Q.C</div>
    <br>
    <br>
    <div class="col1">Civil Status:</div>
    <div class="col2">Single</div>
    <br>
    <br>
    <div class="col1">Religion:</div>
    <div class="col2">Chatholic</div>
    <br>
    <br>
    <div class="col1">Citizenship:</div>
    <div class="col2">Filipino  </div>
    <br>
    <br>
    <div class="col1">height:</div>
    <div class="col2">5.10 feet</div>
    <br>
    <br>
    <br>
    <br>
    </center>
    <div>
      <b>
        <a class="menu2" href="Menu.html"><img src="menu.png"width=50" height="50"> </a>
       
      </b>
    </div>
  </body>
</html>

*Family

<!DOCTYPE html>
<html lang="en">
  <link rel="stylesheet" href="Mystyle2.css" />
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <center>
      <hr />
      <h1>MY FAMILY</h1>
      <hr />
    </center>
  </head>

  <body>
    <div class="container">
      <div class="col4">
        <div class="cards">
          <div class="image">
            
            <center>
            <img class="image"
              src="Father.png"
              alt="card image"
              class="card-img-center" height="150px"/>
              
                <p class="cardtittle">Father</p>


              <a href="father.html">
              <button> Profile</button></center></a>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container">
      <div class="col4">
        <div class="cards">
          <div class="image">
            
            <center>
            <img class="image"
              src="Mother.jpg"
              alt="card image"
              class="card-img-center" height="150px"/>
              
                <p class="cardtittle">Mother</p>
                
                <a href="Mother.html">
                <button> Profile</button></center></a>
            </div>
          </div>
        </div>
      </div>
    </div>


    <div class="container">
      <div class="col4">
        <div class="cards">
          <div class="image">
            
            <center>
            <img class="image"
              src="Jeff.png"
              alt="card image"
              class="card-img-center" height="150spx"/>
              
                <p class="cardtittle">SIDEKICK</p>
                <a href="Jeff.html">
                  <button> Profile</button></center></a>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container">
      <div class="col4">
        <div class="cards">
          <div class="image">
            
            <center>
            <img class="image"
              src="Jessie.png"
              alt="card image"
              class="card-img-center" height="148px"/>
              
                <p class="cardtittle">LITTLE BROTHER1</p>
                
                <a href="justine.html">
                  <button> Profile</button></center></a>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container">
      <div class="col4">
        <div class="cards">
          <div class="image">
            
            <center>
            <img class="image"
              src="Justine.png"
              alt="card image"
              class="card-img-center" height="150px"/>
              
                <p class="cardtittle">LITTLE BROTHER2</p>
                <a href="Jessie.html">
                  <button> Profile</button></center></a>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container">
      <div class="col4">
        <div class="cards">
          <div class="image">
            
            <center>
            <img class="image"
              src="James.png"
              alt="card image"
              class="card-img-center" height="150px"/>
              
                <p class="cardtittle">LITTLE BROTHER3</p>
                <a href="James.html">
                  <button> Profile</button></center></a>
            </div>
          </div>
        </div>
      </div>
    </div>
    
    <br>
    <br>
    <br>
    <a class="menu2" href="Menu.html"><img src="menu.png"width=50" height="50"> </a>
  </body>
</html>


*Father

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Act4</title>

    <link rel="stylesheet" href="Mystyle.css" />
  </head>
  <body>
    <center>
      <hr />
      <h1>USER</h1>
      <hr />
      <link rel="stylesheet" href=""><img class="img2" src="Father.png".png" />
      <br />
  
      <div class="header">FOURELAN C. MOLDON</div>
      
      <br />
      </BR>
      <br>
      <br>
    
      <div class="header" >I LOVE COFFEE</div>
    

      <div class="container">
    <br>
    <br>
    <br>
    
    <div class="col1">Place of Birth:</div> 
    <div class="col2">Bicol</div>
    <br>
    <br>
    <div class="col1">Civil Status:</div>
    <div class="col2">Married</div>
    <br>
    <br>
    <div class="col1">Religion:</div>
    <div class="col2">Chatholic</div>
    <br>
    <br>
    <div class="col1">Citizenship:</div>
    <div class="col2">Filipino  </div>
    <br>
    <br>
    <div class="col1">height:</div>
    <div class="col2">5.10 feet</div>
    <br>
    <br>
    <br>
    <br>
    </center>
    <div>
      <b>
        <a class="menu2" href="Family.html"><img src="family.png"width=50" height="50"> </a>
       
      </b>
    </div>
  </body>
</html>

*Mother
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Act4</title>

    <link rel="stylesheet" href="Mystyle.css" />
  </head>
  <body>
    <center>
      <hr />
      <h1>MOTHER</h1>
      <hr />
      <link rel="stylesheet" href=""><img class="img2" src="Mother.jpg" />
      <br />
  
      <div class="header">LUCIL G. MOLDON</div>
   
      <br />
      </BR>
      <br>
      <br>
    
      <div class="header" ></div>
    

      <div class="container">
    <br>
    <br>
    <br>
    
    <div class="col1">Place of Birth:</div> 
    <div class="col2">Ilo-Ilo city</div>
    <br>
    <br>
    <div class="col1">Civil Status:</div>
    <div class="col2">Married</div>
    <br>
    <br>
    <div class="col1">Religion:</div>
    <div class="col2">Chatholic</div>
    <br>
    <br>
    <div class="col1">Citizenship:</div>
    <div class="col2">Filipino  </div>
    <br>
    <br>
    <div class="col1">height:</div>
    <div class="col2">4.09 feet</div>
    <br>
    <br>
    <br>
    <br>
    </center>
    <div>
      <b>
        <a class="menu2" href="Family.html"><img src="family.png"width=50" height="50"> </a>
       
      </b>
    </div>
  </body>
</html>

*Jeff
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Act4</title>

    <link rel="stylesheet" href="Mystyle.css" />
  </head>
  <body>
    <center>
      <hr />
      <h1>SIDEKICK</h1>
      <hr />
      <link rel="stylesheet" href=""><img class="img2" src="Jeff.png" />
      <br />
  
      <div class="header">JEFFRYSON G. MOLDON</div>
   
      <br />
      </BR>
      <br>
      <br>
    
      <div class="header" >I LOVE COFFEE</div>
    

      <div class="container">
    <br>
    <br>
    <br>
    
    <div class="col1">Place of Birth:</div> 
    <div class="col2">San Roque II Q.C</div>
    <br>
    <br>
    <div class="col1">Civil Status:</div>
    <div class="col2">Single</div>
    <br>
    <br>
    <div class="col1">Religion:</div>
    <div class="col2">Chatholic</div>
    <br>
    <br>
    <div class="col1">Citizenship:</div>
    <div class="col2">Filipino  </div>
    <br>
    <br>
    <div class="col1">height:</div>
    <div class="col2">5.10 feet</div>
    <br>
    <br>
    <br>
    <br>
    </center>
    <div>
      <b>
        <a class="menu2" href="Family.html"><img src="family.png"width=50" height="50"> </a>
       
      </b>
    </div>
  </body>
</html>

*Justine

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Act4</title>

    <link rel="stylesheet" href="Mystyle.css" />
  </head>
  <body>
    <center>
      <hr />
      <h1>LITTLE BROTHER 1</h1>
      <hr />
      <link rel="stylesheet" href=""><img class="img2" src="Jessie.png" />
      <br />
  
      <div class="header">JUSTINE G. MOLDON</div>
   
      <br />
      </BR>
      <br>
      <br>
    
    
    

      <div class="container">
    <br>
    <br>
    <br>
    
    <div class="col1">Place of Birth:</div> 
    <div class="col2">Sv8c San Isidro Rod Rizal</div>
    <br>
    <br>
    <div class="col1">Civil Status:</div>
    <div class="col2">Single</div>
    <br>
    <br>
    <div class="col1">Religion:</div>
    <div class="col2">Chatholic</div>
    <br>
    <br>
    <div class="col1">Citizenship:</div>
    <div class="col2">Filipino  </div>
    <br>
    <br>
    <div class="col1">height:</div>
    <div class="col2">unknown</div>
    <br>
    <br>
    <br>
    <br>
    </center>
    <div>
      <b>
        <a class="menu2" href="Family.html"><img src="family.png"width=50" height="50"> </a>
       
      </b>
    </div>
  </body>
</html>

*Jessie
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Act4</title>

    <link rel="stylesheet" href="Mystyle.css" />
  </head>
  <body>
    <center>
      <hr />
      <h1>LITTLE BROTHER 2</h1>
      <hr />
      <link rel="stylesheet" href=""><img class="img2" src="Justine.png" />
      <br />
  
      <div class="header">JESSIE G. MOLDON</div>
   
      <br />
      </BR>
      <br>
      <br>
    
    
    

      <div class="container">
    <br>
    <br>
    <br>
    
    <div class="col1">Place of Birth:</div> 
    <div class="col2">Sv8c San Isidro Rod Rizal</div>
    <br>
    <br>
    <div class="col1">Civil Status:</div>
    <div class="col2">Single</div>
    <br>
    <br>
    <div class="col1">Religion:</div>
    <div class="col2">Chatholic</div>
    <br>
    <br>
    <div class="col1">Citizenship:</div>
    <div class="col2">Filipino  </div>
    <br>
    <br>
    <div class="col1">height:</div>
    <div class="col2"> unknown</div>
    <br>
    <br>
    <br>
    <br>
    </center>
    <div>
      <b>
        <a class="menu2" href="Family.html"><img src="family.png"width=50" height="50"> </a>
       
      </b>
    </div>
  </body>
</html>

*James

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Act4</title>

    <link rel="stylesheet" href="Mystyle.css" />
  </head>
  <body>
    <center>
      <hr />
      <h1>LITTLE BROTHER 3</h1>
      <hr />
      <link rel="stylesheet" href=""><img class="img2" src="James.png" />
      <br />
  
      <div class="header">JAMES LAURENZE G. MOLDON</div>
   
      <br />
      </BR>
      <br>
      <br>
    
      
    

      <div class="container">
    <br>
    <br>
    <br>
    
    <div class="col1">Place of Birth:</div> 
    <div class="col2">Sv8c San Isidro Rod Rizal</div>
    <br>
    <br>
    <div class="col1">Civil Status:</div>
    <div class="col2">Single</div>
    <br>
    <br>
    <div class="col1">Religion:</div>
    <div class="col2">Chatholic</div>
    <br>
    <br>
    <div class="col1">Citizenship:</div>
    <div class="col2">Filipino  </div>
    <br>
    <br>
    <div class="col1">height:</div>
    <div class="col2"> unknown</div>
    <br>
    <br>
    <br>
    <br>
    </center>
    <div>
      <b>
        <a class="menu2" href="Family.html"><img src="family.png"width=50" height="50"> </a>
       
      </b>
    </div>
  </body>
</html>

*CSS

body{
    background-image: url("bg.jpeg");
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: cover;
    opacity: 10px;
}

h1 {
    border-style: solid;
    border-color: red;
    padding: 12px 16px;
    margin-left: 50px;
    margin-right: 50px;
    cursor: default;
    border-radius: 10px;
    background-color: aquamarine;
    opacity: 0.5;
    
  }
h1:hover {

    background-color: rgb(126, 187, 167) ; transform: scale(1);
    opacity: 100%;
    padding: 10px;
}

p {  
    font-size: 20px;
    font-style: normal;
    text-align: center ;
   }

p:hover
{
    background-color: aquamarine; 
    padding: 20px;
    border-radius: 10px;
    opacity : 0.6;
    

}

h2 {
    font-size: 30px;
    font-style: normal;
    margin-top: 50px;
    font-size: 3px;
    opacity: 0.9;
    
 
}
h2:hover
{
    background-color: aquamarine; transform: scale(1);
    margin-left: 570px;
    border-radius: 10px;
    margin-right: 570px;
    padding: 12px 16px;
    
    
}

h3:hover
{
    background-color: aquamarine; transform: scale(1);
    margin-left: 555px;
    margin-right: 555px;
    border-radius: 10px;
    opacity: 0.6;

}


.favorite{
    margin-right: 100px;
    margin-left: 100px;
    font-style: normal;
    font-family: normal;
    position: relative;
    color: black;
    padding: 10px 10px;
    font-size: 17px;
    cursor: pointer;
    text-align: left;
    border-style: none;
    background-color: aquamarine;
    border-radius: 10px;
    opacity: 0.6;
    
}

.favorite:hover{
    background-color: aqua; transform: scale(1);
    margin-left: 120px;
    margin-right: 100px;
    border-radius: 10px;
    padding: 10px 10px;
    
    
}
.menu{
    margin-left: 10px;
    padding:  7px;
    border-style: none;
    background-color: aquamarine;
    margin-right: 1175px;
    opacity: 0.8;
    border-radius: 50px;
    
}


.firsticon{
  position: relative;
  top: 100px;
  margin-left: 30px;
  border: 10px;
}

.img2{
    width: 200px; 
    height:  200px;
    border-style: solid;
    border-color: rgb(14, 94, 168);
    position: relative;
    margin-left: 900px;
    top: 80px;
    border-radius: 5px;
    margin-right: 150px;
}

.header{
    position: relative;
    bottom: 90px;
    border-style: solid;
    color: black;
    background-color: aquamarine;
    margin-left: 500px;
    margin-right: 500px;
    opacity: 0.7;
    border-radius: 5px;
    font-size: large;
    
}

.header:hover{
    background-color: aqua; transform: scale(1);
    margin-left: 510px;
    border-radius: 10px;
    margin-right: 510px;
    padding: 5px 5px;
}

.secondicon{
    border-style: solid;
    background-color: aqua;
}


.col1{
    border-style: none;
    color: black;
    background-color:  rgb(219, 214, 214);
    position: relative;
    width: 25.33%;
    float: left;
    margin-left: 100px;
    font-size: 12;
    border-radius: 4px;
    opacity: 0.8;
    text-align: center;

}
.col1:hover{
    background-color: aquamarine; transform: scale(1);
    border-radius: 10px;
}

.col2{
    border-style: none;
    color: black;
    background-color: rgb(219, 214, 214);
    position: relative;
    width: 25.33%;
    float: right;
    margin-right: 100px;
    border-radius: 4px;
    opacity: 0.8;
    
}
.col2:hover{
    background-color: aquamarine; transform: scale(1);
    border-radius: 10px;
}

.menu2{
    margin-left: 50px;
    position: relative;
    
}


*CSS 2
.cards{
    width: 150px;
    background-color: aquamarine;
    text-align: justify;
    padding: 50px;
    margin-left: 50px;
    margin-top: 20px;
    margin-bottom: 20px;
    box-shadow: 2px 2px 10px black;

}

.container{
    display: inline-block;
}

.image img{
    width: 100px;
    
}
.image style{
    height:150px;
    width:200px;
    align-items: center;
}

.cardtittle
{
    font-size: 20px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
