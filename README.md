<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" type="text/css" href="style.css" />
</head>
<body>
<div class="navbar">
  <ul>
    <li><a href="#about"><b>About Me</b></a></li>
    <li><a href="#photos"><b>Gallery</b></a></li>
    <li><a href="#playlist"><b> My Playlist</b></a></li>
    <li><a href="#like"><b>Like</b></a></li>
    <li><a href="#qrcoder"><b>QR code</b></a></li>
    <li><a href="#spa"><b>SPA Q&A</b></a></li>
    <li><a href="#contact"><b>Contact Us</b></a></li>
</ul>
</div>
		  
<section id="about" class="section">
  <h1>About me</h1>
<p dir="rtl"><h3>שלום, אני חגי לוי, והחלטתי לבנות את האתר הראשון שלי לטובת אישתי, לכן אתייחס כאילו זהו האתר הרשמי שלה</h3></p>
<p dir="rtl"><br/><h2>ברוכים הבאים לאתר האיפור ותסרוקות של שנהב לוי.
<br/>  מי שטרם הספיק להכיר אותי, אז הינה קצת פרטים על מי שאני
<br/>בוגרת קורס איפור ותסרוקות באקדמיה לאיפור של "ירין שחף" - מאפר העל 
<br/>האיפור שלי נפרס על פני מגוון רחב של האוכלוסיה 
<br/>החל בנשים בעלות תווי פנים צעירות ומבוגרות, וכלה בנשים בעלות גוון עור כהה ובהיר
<br/>האיפור מיועד הן לילדים, כגון בפורים וימי-הולדת, איפור ערב וכמובן כלות
<br/></h2></p>
<br/>
<br/>
</section>

<section id="photos" class="section1">
  <h1>My gallery</h1>
<br/> <img src="hairdo.jpg" alt="image of hairdo">
      <img src="dog.jpg" alt="image of dog makeup">
      <img src="child1.png" alt="image of butterfly makeup">
      <img src="hairdo2.jpg" alt="image of hairdo">
     <br>
<br/> <img src="hairdo3.jpg" alt="image of hairdo">
      <img src="elza.jpg" alt="image of Elza makeup">
      <img src="leizan.jpg" alt="image of clown makeup">
      <img src="hairdo4.jpg" alt="image of hairdo">
    <br>  
<br/><img src="cat.jpg" alt="image of Cate makeup">

<br/>
</section>

<section id="playlist" class="section2">
  <h1>My plalist</h1>
<br/>

<br/>
<br/><br/><iframe width="500" height="280" 
src="https://www.youtube.com/embed/aii3fDdZnrM" 
title="YouTube video player" frameborder="0" 
allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
allowfullscreen></iframe>
<br/>
</section>

<section id="like" class="section3">
<h1>Give my a like</h1>
<br/>
<button name="button"><img src="like.jpg" alt="kike button" class="likeImage"></button>
<br/>
<br/>
</section>

<section id="qrcoder" class="section">
  <h1>Scan me code</h1>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
</section>

<section id="spa" class="section">
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
</section>

<section id="contact" class="section">
  <h1>conect us</h1>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
</section>


<script type="text/javascript">
$(function(){
  $("#nav a").click(function(e){
    e.preventDefault();
    $('html,body').scrollTo(this.hash,this.hash); 
  });
});
</script>
<script type="text/javascript">
 $(document).scroll(function() {
    $('#menu').toggle($(this).scrollTop()>1000)
 });​
 </script>
</body>
</html>
