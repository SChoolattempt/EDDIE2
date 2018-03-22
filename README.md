<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body, h1,h2,h3,h4,h5,h6 {font-family: "Montserrat", sans-serif}
.w3-row-padding img {margin-bottom: 12px}
/* Set the width of the sidebar to 120px */
.w3-sidebar {width: 120px;background: #222;}
/* Add a left margin to the "page content" that matches the width of the sidebar (120px) */
#main {margin-left: 120px}
/* Remove margins from "page content" on small screens */
@media only screen and (max-width: 600px) {#main {margin-left: 0}}
</style>
<body class="w3-black">

<!-- Icon Bar (Sidebar - hidden on small screens) -->
<nav class="w3-sidebar w3-bar-block w3-small w3-hide-small w3-center">
  <!-- Avatar image in top left corner -->
  <img src="/w3images/avatar_smoke.jpg" style="width:100%">
  <a href="#" class="w3-bar-item w3-button w3-padding-large w3-black">
    <i class="fa fa-home w3-xxlarge"></i>
    <p>HOME</p>
  </a>
  <a href="#about" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-user w3-xxlarge"></i>
    <p>ABOUT</p>
  </a>
  <a href="#photos" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-eye w3-xxlarge"></i>
    <p>PHOTOS</p>
  </a>

    <i class="fa fa-envelope w3-xxlarge"></i>
  </a>
</nav>

<!-- Navbar on small screens (Hidden on medium and large screens) -->

  <div class="w3-bar w3-black w3-opacity w3-hover-opacity-off w3-center w3-small">
    <a href="#" class="w3-bar-item w3-button" style="width:25% !important">HOME</a>
    <a href="#about" class="w3-bar-item w3-button" style="width:25% !important">ABOUT</a>
    <a href="#photos" class="w3-bar-item w3-button" style="width:25% !important">PHOTOS</a>
  </div>
</div>

<!-- Page Content -->
<div class="w3-padding-large" id="main">
  <!-- Header/Home -->
  <header class="w3-container w3-padding-32 w3-center w3-black" id="home">
    <h1 class="w3-jumbo"><span class="w3-hide-small">I'm </span>Oscar Schindler</h1>
<img alt="Schindler, Oskar.jpg" src="//upload.wikimedia.org/wikipedia/commons/thumb/3/38/Schindler%2C_Oskar.jpg/220px-Schindler%2C_Oskar.jpg" width="220" height="337" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/3/38/Schindler%2C_Oskar.jpg/330px-Schindler%2C_Oskar.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/3/38/Schindler%2C_Oskar.jpg/440px-Schindler%2C_Oskar.jpg 2x" data-file-width="851" data-file-height="1302">
    <p>Nazi party member and Slave labour profiteer</p>
   
  </header>

  <!-- About Section -->
    <div class="w3-content w3-justify w3-text-grey w3-padding-64" id="about">
    <h2 class="w3-text-light-grey">My Name is</h2>
    <hr style="width:200px" class="w3-opacity">
    
    <p>Oscar Schindler and this is my story
    <br>
    


<br><button onclick="myFunction('myDIV')">Pre War</button>

<div id="myDIV">
He was generally thought of by his peers as a womaniser, a cheat and a lier.  But his story is much more complex than that he was born in 28 April 1908 in Zwittau Moravia in Czechoslovakia to a wealthy family that owned a Farm Machinery business. after attending Primary and High School Oskar went to a Technical School which he got expelled from for forging a report card but did later graduate but did not sit the Abitur exam so he did not go to university. Instead went to do trade skills Brno (Czech Republic). In 1928 he got married to Emilie Pielzi and even joined the Czech army on a 18 month stint.

Oskar then joined the separatist Sudeten German Party in 1935. Even though he was a Czech citizen, Oskar became a spy for the Abwehr, an intelligence service of Nazi Germany, in 1936. He was assigned to Abwehr Stelle II Commando VIII, based in Breslau. He  told Czech police that he did it because he needed the money; by this time Schindler had a drinking problem and was chronically in debt.

</div>

<br><button onclick="myFunction('secondDiv')">During War</button>

<br><br><div id="secondDiv">
Schindler was introduced to Itzhak Stern, a bookkeeper for Oskars friend Josef Aue, who had taken over Stern's formerly Jewish-owned place of employment as a manager. Anything belonging to Polish Jews, even their property were taken by the Nazis after the invasion, and Jews were stripped of their rights. Oskar showed Itzhak the books he was thinking of acquiring, a pots and pan factory that was owned by jews. Itzhak advised him that rather than running the company as a trusteeship under the auspices of the Haupttreuhandstelle Ost (Main Trustee Office for the East), he should buy the company. that would give him more freedom from the dictates of the Nazis, including the freedom to hire more Jews.<br>
 As the USSR advanced in 1994, the SS began closing down the eastern concentration camps and moving the remaining jews to Auschwitz and Gross-Rosen concentration camp. Goth's secretary, Mietek Pemper alerted Oskar to the Nazis plans to close all factories not directly involved in the war , including Oskar’s Pots and pans factory. Mietek suggested to Oskar that production should be switched from cookware to anti-tank grenades in an effort to save the lives of the Jewish workers. Using bribery and his powers of persuasion, Schindler convinced Göth and the officials in Berlin to allow him to move his factory and his workers to Brünnlitz (Czech:, in the Sudetenland.) Sparing them from death in the gas chambers upon the concession of the war in Germany Oskar left Germany to escape the USSR onslaught where Oskar clearly would have been executed.

</div>
<button onclick="myFunction('thirddiv')">after war</button>
<div id="thirddiv">
In 1948 he asked  for compensation of his expenses to the American Jewish Joint Distribution Committee, and was given $15,000. He estimated his expenditures at over $1,056,000, including the costs of camp construction, bribes, and expenditures for black market goods, including food. Oskar emigrated to Argentina in 1949, where he tried raising chickens and then nutria(Large Rat seriously like small dog size), a  animal raised for its fur. When the business went bankrupt.<br> he left his wife and returned to Germany where he had a series of unsuccessful business ventures He declared bankruptcy in 1963 and suffered a heart attack the next year, which led to a month-long stay in hospital. Remaining in contact with many of the Jews he had met during the war including Stern and Pfefferberg, Oskar survived on donations sent by jews he saved from all over the world. He died on 9 October 1974 and is buried in Jerusalem on Mount Zion, the only member of the Nazi Party to be honoured in this way. For his work during the war, in 1963 Schindler was named Righteous Among the Nations, an award bestowed by the State of Israel on non-Jews who took an active role to rescue Jews during the Holocaust.
</div>




<script>
function myFunction(divName) {
    var x = document.getElementById(divName);
    if (x.style.display === "none") {
        x.style.display = "block";
    } else {
        x.style.display = "none";
    }
}
</script>
    </p>
    <h3 class="w3-padding-16 w3-text-light-grey">My Skills</h3>
    <p class="w3-wide">cheating</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:95%"></div>
    </div>
    <p class="w3-wide">Lying</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:85%"></div>
    </div>
    <p class="w3-wide">saving lifes</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:80%"></div>
    </div><br>
    <div class="w3-row w3-center w3-padding-16 w3-section w3-light-grey">
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">2</span><br>
Succesful factories</div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">7</span><br>
        failed business ventures
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">100's</span><br>
           of bribed officials
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">1,200</span><br>
        jews saved
      </div>
    </div>


  
    
    <!-- Testimonials -->
    <h3 class="w3-padding-24 w3-text-light-grey">My Reputation</h3>  

    <p><span class="w3-large w3-margin-right">jew</span>Steel Worker</p>
    <p>Oskars ark was the only place jews could of survived i had to get on that list</p><br>
    

    <p><span class="w3-large w3-margin-right">jew</span>Maid</p>
    <p>No one is more generous then Oskar Schindler</p>
  <!-- End About Section -->

  
  <!-- Portfolio Section -->
  <div class="w3-padding-64 w3-content" id="photos">
    <h2 class="w3-text-light-grey">Mietek Pemper</h2>
    <hr style="width:200px" class="w3-opacity">

    <!-- Grid for photos -->
      <img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/8/86/Pemper_April_1940.jpg/220px-Pemper_April_1940.jpg" width="220" height="323" class="thumbimage" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/8/86/Pemper_April_1940.jpg/330px-Pemper_April_1940.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/8/86/Pemper_April_1940.jpg/440px-Pemper_April_1940.jpg 2x" data-file-width="511" data-file-height="750">
      
      </div>
 
   <!-- End photo grid -->

      </div>
  <!-- End Portfolio Section -->
  </div>

  <!-- Contact Section -->
  <div class="w3-padding-64 w3-content w3-text-grey" id="contact">
    <h2 class="w3-text-light-grey">Contact Me</h2>
    <hr style="width:200px" class="w3-opacity">

    <div class="w3-section">
      <p><i class="fa fa-map-marker fa-fw w3-text-white w3-xxlarge w3-margin-right"></i>southern slope of Mount Zion, Israel
      <p><i class="fa fa-phone fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Phone: N/A>
      <p><i class="fa fa-envelope fa-fw w3-text-white w3-xxlarge w3-margin-right"> </i> Email: N/A>
    </div><br>
    

  <!-- End Contact Section -->
  </div>
  
    <!-- Footer -->

    <p class="w3-medium">Powered by HAVG <a href="" target="_blank" class="w3-hover-text-green"></a></p>
  <!-- End footer -->
  </footer>

<!-- END PAGE CONTENT -->
</div>

</body>
</html>
