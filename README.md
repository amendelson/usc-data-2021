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

#countdown {
  line-height: 1.3em;
  font-size: 3.9em;
  background: -webkit-linear-gradient(#e66465, #9198e5);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-weight: bold;

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
<!--
<script>

var end = new Date('05/07/2021 5:00 PM');

    var _second = 1000;
    var _minute = _second * 60;
    var _hour = _minute * 60;
    var _day = _hour * 24;
    var timer;

    function showRemaining() {
        var now = new Date();
        var distance = end - now;
        if (distance < 0) {

            clearInterval(timer);
            document.getElementById('countdown').innerHTML = 'EXPIRED!';

            return;
        }
        var days = Math.floor(distance / _day);
        var hours = Math.floor((distance % _day) / _hour);
        var minutes = Math.floor((distance % _hour) / _minute);
        var seconds = Math.floor((distance % _minute) / _second);

        document.getElementById('countdown').innerHTML = days + ' days ';
        document.getElementById('countdown').innerHTML += hours + ' hours ';
        document.getElementById('countdown').innerHTML += minutes + ' mins until Final Project drafts are due';

    }

    timer = setInterval(showRemaining, 1000);
    
</script>
<div id="countdown">
</div>
-->
<br>

Welcome to the website for JOUR 561: Fundamentals of Data Journalism Reporting. You'll find links to course materials here. You can get to this page by typing in `tiny.cc/2wv4gz` in your browser's address bar.

Here is [the class syllabus](docs/syllabus.pdf).

The class meets 6:30 to 8:30 on Monday nights in ~the virtual realm~ (over Zoom). The final exam is on May 5 from 7-9 p.m.

This class will involve the use of technical tools, and coding. But if you want to learn how to use mapping and data analysis to report great stories, you're in the right class. The journalism is the most important part.

## Class links

* Week One: MLK Day (no class)
* **[Week Two](week2/)**: Course overview. Introductions.
* **[Week Three](week3/)**: Class Project discussion.
* **[Week Four](week4/)**: Visualizing Data with ggplot, Part 1 – faceting. Class project discussion.
* Week Five: President's Day (no class)
* **[Week Six](week6/)**: Visualizing Data with ggplot, Part 2 – layers and interactivity
* **[Week Seven](week7/)**: Class project discussion
* **[Week Eight](week8/)**: Writing functions and loops in R
* **[Week Nine](week9/)**: Tidyuniverse in R – cleaning and transforming data.
* **[Week Ten](week10/)**: Tidyuniverse in R – modeling data. Class project discussion
* **[Week Eleven](week11/)**: Mapping Part 1 – Buffers on steroids, spatial queries and spatial joins.
* **[Week Twelve](week12/)**: Mapping Part 2 - Projections and the finer points of mapping.
* **[Week Thirteen](week13)**: Mapping Part 3 – Using Open Street Map and Plug-Ins
* **[Week Fourteen](week14/)**: Mapping Part 4 – Interactive Maps. Class project discussion
* **[Week Fifteen](week14/)**: Bulk geocoding data with an API
* Final

<br>


```
██████╗      █████╗     ████████╗     █████╗ 
██╔══██╗    ██╔══██╗    ╚══██╔══╝    ██╔══██╗
██║  ██║    ███████║       ██║       ███████║
██║  ██║    ██╔══██║       ██║       ██╔══██║
██████╔╝    ██║  ██║       ██║       ██║  ██║
╚═════╝     ╚═╝  ╚═╝       ╚═╝       ╚═╝  ╚═╝
```

---
<br><br>
Us in this class when learning about new datasets we can FOIA:

![](https://thumbs.gfycat.com/ApprehensiveGroundedIndianskimmer-small.gif)
