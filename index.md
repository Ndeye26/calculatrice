<!DOCTYPE html>
<html lang="fr">
<head>
  <title>Calculatrice</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/
4.4.1/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/
4.7.0/css/font-awesome.min.css">  
<link rel="stylesheet" href="styleCalculatrice.css" type="text/css">
<script type="text/javascript" src="jsCalculatrice.js"></script>
</head>
<body>
  <div class="calculator card">

<form id="calculatrice" name="calc">
        <input type="text" name="display" class="calculator-screen z-depth-1"
 value="" disabled />

  <div class="calculator-keys">

      <button type="button" class="btn btn-info" value="+"
 OnClick="calc.display.value+='+'">+</button>
      <button type="button" class=" btn btn-info" value="-"
OnClick="calc.display.value+='-'">-</button>
      <button type="button" class=" btn btn-info" value="*"
OnClick="calc.display.value+='*'">&times;</button>
      <button type="button" class=" btn btn-info" value="/" 
OnClick="calc.display.value+='/'">&divide;</button>

      <button type="button" value="7" class="btn btn-light"  
OnClick="calc.display.value+='7'">7</button>
      <button type="button" value="8" class="btn btn-light " 
OnClick="calc.display.value+='8'">8</button>
      <button type="button" value="9" class="btn btn-light " 
OnClick="calc.display.value+='9'">9</button>


      <button type="button" value="4" class="btn btn-light" 
OnClick="calc.display.value+='4'">4</button>
      <button type="button" value="5" class="btn btn-light " 
OnClick="calc.display.value+='5'">5</button>
      <button type="button" value="6" class="btn btn-light " 
OnClick="calc.display.value+='6'">6</button>


      <button type="button" value="1" class="btn btn-light " 
OnClick="calc.display.value+='1'">1</button>
      <button type="button" value="2" class="btn btn-light " 
OnClick="calc.display.value+='2'">2</button>
      <button type="button" value="3" class="btn btn-light " 
OnClick="calc.display.value+='3'">3</button>


      <button type="button" value="0" class="btn btn-light " 
OnClick="calc.display.value+='0'">0</button>
      <button type="button" class="btn btn-secondary" value="." 
OnClick="calc.display.value+='.'">.</button>
      <button type="button" class="btn btn-danger btn-sm"
 value="all-clear"OnClick="calc.display.value=''">AC</button>

      <button type="button" class="equal-sign btn btn-success" value="=" 
      OnClick="calc.display.value=eval(calc.display.value)">=</button>

    </div>
  </div>
</form>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/
3.3.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/
1.14.7/umd/popper.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/
4.3.1/js/bootstrap.min.js"></script>

</body>
</html>