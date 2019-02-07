<!DOCTYPE html>
<html>

<head>
    <meta charset='utf-8'>


    </head>

    <body>

      <h1>Find your spirit animal</h1>

      <button onclick="newFunction(0)"> A hike and whitwater rafting</button>
      <button onclick="newFunction(1)">Netflix and chill</button>
      <button onclick="newFunction(2)">Wine and cheese in a cemetery</button>

<div>

<h3> Assessment</h3>
<p id="answer"></p>

</div>

<script>
  function newFunction(param1){
      textValue = param1;
      var alertText = ['hike', 'netflix', 'wine']
      alert(textValue);
      console.log('testing');
      document.getElementbyId("answer").innerHTML= "some text here";
}

</script>


</body>

</html>
