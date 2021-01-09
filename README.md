<html>
<title>KFC </title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
body, html {
  height: 100%;
  font-family: "Consolas", sans-serif;
}

.bgimg {
  background-position: center;
  background-size: cover;
 ;
  min-height: 70%;
}

.menu {
  display: none;
}
</style>
<body>

<!-- Links (sit on top) -->
<div class="w3-top">
  <div class="w3-row w3-padding w3-black">
    <div class="w3-col s3">
      <a href="#" class="w3-button w3-block w3-white">HOME</a>
    </div>
    <div class="w3-col s3">
      <a href="#about" class="w3-button w3-block w3-white">ABOUT</a>
    </div>
    <div class="w3-col s3">
      <a href="#menu" class="w3-button w3-block w3-black">MENU</a>
    </div>
    <div class="w3-col s3">
      <a href="#where" class="w3-button w3-block w3-black">WHERE</a>
    </div>
  </div>
</div>

<!-- Header with image -->
<header class="bgimg w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-bottomleft w3-center w3-padding-large w3-hide-small">
    <span class="w3-tag">Open from 8 am to 9 pm</span>
  </div>
  <div class="w3-display-middle w3-center">
    <span class="w3-text-black" style="font-size:90px">KFC</span>
  </div>
  <div class="w3-display-bottomright w3-center w3-padding-large">
    <span class="w3-text-white"> No 20 K Park street, Sir William Jones Sarani </span>
  </div>
</header>

<!-- Add a background color and large text to the whole page -->
<div class="w3-sand w3-grayscale w3-large">

<!-- About Container -->
<div class="w3-container" id="about">
  <div class="w3-content" style="max-width:700px">
    <h5 class="w3-center w3-padding-64"><span class="w3-tag w3-wide">ABOUT KFC </span></h5>
    <p>KFC's original product is pressure-fried chicken pieces, seasoned with Sanders' recipe of 11 herbs and spices. The constituents of the recipe are a trade secret. Larger portions of fried chicken are served in a cardboard "bucket", which has become a interesting feature
</p>
    <p>Since the early-1990s, KFC has expanded its menu to offer other chicken products such as chicken fillet sandwiches and wraps, as well as salads and side dishes such as French fries and coleslaw, desserts, and soft drinks; the latter often supplied by PepsiCo. KFC is known for its slogans "It's Finger Lickin' Good!", "Nobody does chicken like KFC", and "So good".
</p>
    <div class="w3-panel w3-leftbar w3-light-grey">
      <p><i>" ‘It’s Finger Lickin’ Good’ "</i></p>
      <p> The chain is a subsidiary of Yum! Brands</p>
    </div>
  
    <p><strong>Opening hours:</strong> everyday from 6am to 5pm.</p>
    <p><strong>Address: No 20 K Park street, Sir William Jones Sarani  </strong></p>
  </div>
</div>

!-- Menu Container -->
<div class="w3-container" id="menu">
  <div class="w3-content" style="max-width:700px">
 
    <h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">THE MENU</span></h5>
  
    <div class="w3-row w3-center w3-card w3-padding">
      <a href="javascript:void(0)" onclick="openMenu(event, 'Page1');" id="myLink">
        <div class="w3-col s6 tablink">Page1</div>
      </a>
      <a href="javascript:void(0)" onclick="openMenu(event, 'Page2');">
        <div class="w3-col s6 tablink">Page2</div>
      </a>
    </div>

    <div id="Page 1" class="w3-container menu w3-padding-48 w3-card">
      <h5>Original Recipe</h5>
      <p class="w3-text-grey"> This is the original fried chicken made with a “secret blend of 11 herbs and spices. Cost : 14.99 </p><br>
    
      <h5>Grilled Chicken </h5>
      <p class="w3-text-grey">The healthier alternative to the fried chicken. The grilled chicken is marinated, seasoned, and then grilled. Cost : 14.99 </p><br>
    
      <h5>Popcorn Nuggets</h5>
      <p class="w3-text-grey">The KFC version of popcorn nuggets Cost : 7.50</p><br>
    
      
    </div>

    <div id="Page 2" class="w3-container menu w3-padding-48 w3-card">
      <h5>Extra Crispy Tenders </h5>
      <p class="w3-text-grey">Double breaded strips of chicken breast meat Cost : 2.50</p><br>
    
      <h5>KFC Sandwiches </h5>
      <p class="w3-text-grey"> A boneless breast of Original Recipe chicken with bacon, Monterey Jack, and Colonel’s sauce on a sweet Hawaiian bun Cost : 4.99</p><br>
    
      <h5> Chicken Littles </h5>
      <p class="w3-text-grey"> Chicken tenders, pickles, and mayo on a sweet bun Cost : 5.60 </p><br>
    
      
    </div>  
 
  </div>
</div>

<!-- Contact/Area Container -->
<div class="w3-container" id="where" style="padding-bottom:32px;">
  <div class="w3-content" style="max-width:700px">
    <h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">WHERE TO FIND US</span></h5>
    <p>Find us at the above mentioned address . </p>

    <p><span class="w3-tag">FYI!</span> We offer full-service catering for any event, large or small. We understand your needs and we will cater the food to satisfy the biggerst criteria of them all, both look and taste.</p>
    <p><strong>Reserve</strong> a table, ask for today's special or just send us a message:</p>
    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="number" placeholder="How many people" required name="People"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="datetime-local" placeholder="Date and time" required name="date" value="2020-11-16T20:00"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Message \ Special requirements" required name="Message"></p>
      <p><button class="w3-button w3-black" type="submit">SEND MESSAGE</button></p>
    </form>
  </div>
</div>

<!-- End page content -->
</div>

<!-- Footer -->
<footer class="w3-center w3-light-grey w3-padding-48 w3-large">
 
</footer>

<script>
// Tabbed Menu
function openMenu(evt, menuName) {
  var i, x, tablinks;
  x = document.getElementsByClassName("menu");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < x.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" w3-dark-grey", "");
  }
  document.getElementById(menuName).style.display = "block";
  evt.currentTarget.firstElementChild.className += " w3-dark-grey";
}
document.getElementById("myLink").click();
</script>

</body>
</html>
