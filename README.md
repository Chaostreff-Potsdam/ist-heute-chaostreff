## Ist heute Chaostreff?
<div  style="margin: 0 auto; width:75%">
  <b style="font-size: xxx-large;" id="answer" >Nein! (>85% Genauigkeit)</b>
  <br/>
  <div id="noscript">Bitte aktiviere Javascript, falls du eine genauere Antwort möchtest.</div>
</div>
<br/>

### [Ist morgen Chaostreff?](http://www.ist-morgen-chaostreff.online)


 <script>
  var wednesday = 3;
  
  var treffDay = wednesday;
  
  var answers = {
    true:  "JA!",
    false: "Nein!"
  };

  var date = new Date();
  var dayOfWeek = date.getDay();
  
  document.getElementById("answer").innerHTML = answers[dayOfWeek == treffDay];
  document.getElementById("noscript").remove();
 </script>