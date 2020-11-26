<div class="header">
<h1 class="ml7">
  <span class="text-wrapper">
    <span class="letters"><p id ="usc p">Data&nbsp;&nbsp;Journalism&nbsp;&nbsp;&nbsp;USC&nbsp;&nbsp;2021</p></span>
  </span>
</h1>
</div>
<script src="https://cdnjs.cloudflare.com/ajax/libs/animejs/2.0.2/anime.min.js"></script>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

<style>
.header{
      background-image: linear-gradient(to right, #a8c0ff, #3f2b96);
}

.ml7 {
  position: relative;
  font-weight: 1200;


}
.ml7 .text-wrapper {
  position: relative;
  display: inline-block;
  padding-top: 0.2em;
  padding-right: 0.05em;
  padding-bottom: 0.1em;
  overflow: hidden;
  padding-left: 14px;

}
.ml7 .letter {
  transform-origin: 0 100%;
  display: inline-block;
  line-height: 1.3em;
  font-size: 3.6em;
  color: #FFFFFF
}


</style>


<script>
// Wrap every letter in a span
$('.ml7 .letters').each(function(){
  $(this).html($(this).text().replace(/([^\x00-\x80]|\w)/g, "<span class='letter'>$&</span>"));
});

anime.timeline({loop: true})
  .add({
    targets: '.ml7 .letter',
    translateY: ["1.1em", 0],
    translateX: ["0.55em", 0],
    translateZ: 0,
    rotateZ: [180, 0],
    duration: 1050,
    easing: "easeOutExpo",
    delay: function(el, i) {
      return 50 * i;
    }
  }).add({
    targets: '.ml7',
    opacity: 0,
    duration: 1000,
    easing: "easeOutExpo",
    delay: 1000
  });
</script>


# Week Two (but our first class)
This week, we'll talk about what data journalism is, how to do it, and what are goals are for this class.

We'll also do some housekeeping and get to know one another.

---

### Lecture

[Slides](https://docs.google.com/presentation/d/1Nlztcyf2IdcgrMS0r80W449rs0ZwO9C2yDR2QOZuzyU/edit?usp=sharing)

---

### Links

[R Studio Cloud](https://rstudio.cloud)

[QGIS](https://download.qgis.org/)

---

### Homework

* [Fill out the survey](https://docs.google.com/forms/d/e/1FAIpQLSeozOxR0masijElTRJ7_QpU8TLqPRLpgm1hmAUDd6NpN0MqEQ/viewform?usp=sf_link)

* [Make sure you have R Studio Cloud access and joing our class workspace](https://rstudio.cloud)
	* [class workspace link](https://rstudio.cloud/spaces/105161/join?access_code=Ei0JeYBwYTQgyrvAjA02kN1v1BEf0ZHs9vIy8XMy)

* Email Aaron (aaron.a.mendelsonATgmailDOTcom) if you want to choose your own group for the Final Project
