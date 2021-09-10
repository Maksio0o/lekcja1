<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>Maks Danilkiewicz </title>
  </head>

  <body>
    <div id="output"></div>

    <script>
        output = document.getElementById('output');
        random = 'Random numbers: <br />';
        even = 'Even numbers: <br />';

        for(i=0; i<=20; i++){
            random += Math.floor(Math.random()*20+1) + '<br />';
            even += (i%2==0) ? i + '<br />' : '';
        }
        output.innerHTML = random + '<br />' + even;
        alert('Maks Danilkiewicz');
    </script>
  </body>
</html>
