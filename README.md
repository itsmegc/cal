<html>
    <head>
        <title>Calculator - gaurav</title>
        
        <meta name="description" content="html and css Calculater">
  <meta name="keywords" content="HTML,CSS,JavaScript">
  <meta name="author" content="Gaurav Chand">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
        
        <style>
        
        
#calc-contain{
  position: relative;
  width: 400px;
  border: 2px solid black;
  border-radius: 12px;
  margin: 0px auto;
  padding: 20px 20px 100px 20px;
}
#agh{
  position: relative;
  float: right;
  margin-top: 15px;
}
#agh p{
  font-size: 20px;
  font-weight: 900;
}
input[type=button] {
  background: lightGray;
  width: 20%;
  font-size: 20px;
  font-weight: 900;
  border-radius: 7px;
  margin-left: 13px;
  margin-top: 10px;
}
input[type=button]:active {
  background-color: #3e8e41;
  box-shadow: 0 5px #666;
  transform: translateY(4px);
}
input[type=button]:hover {
  background-color: #003300;
  color: white;
}

input[type = text] {
  position: relative;
  display: block;
  width: 90%;
  margin: 5px auto;
  font-size: 20px;
  padding: 10px;
  box-shadow: 4px 0px 12px black inset;
}
    
  
        
        </style>
    </head>
    <body>
        <div id='calc-contain'>
  
          
            
            <input type="text" name="answer" />
        
            
            <input type="button" value=" 1 " onclick="calculator.answer.value += '1'" />
            <input type="button" value=" 2 " onclick="calculator.answer.value += '2'" />
            <input type="button" value=" 3 " onclick="calculator.answer.value += '3'" />
            <input type="button" value=" + " onclick="calculator.answer.value += '+'" />
          
            
            <input type="button" value=" 4 " onclick="calculator.answer.value += '4'" />
            <input type="button" value=" 5 " onclick="calculator.answer.value += '5'" />
            <input type="button" value=" 6 " onclick="calculator.answer.value += '6'" />
            <input type="button" value=" - " onclick="calculator.answer.value += '-'" />
         
          
            <input type="button" value=" 7 " onclick="calculator.answer.value += '7'" />
            <input type="button" value=" 8 " onclick="calculator.answer.value += '8'" />
            <input type="button" value=" 9 " onclick="calculator.answer.value += '9'" />
            <input type="button" value=" x " onclick="calculator.answer.value += '*'" />
           
        
            <input type="button" value=" c " onclick="calculator.answer.value = ''" />
            <input type="button" value=" 0 " onclick="calculator.answer.value += '0'" />
            <input type="button" value=" = " onclick="calculator.answer.value = eval(calculator.answer.value)" />
            <input type="button" value=" / " onclick="calculator.answer.value += '/'" />
            
  
    
       
          <div id="agh">
      
          <img src = "b.jpg" alt="Sarcasm God" width="200" height="300"/>
            

          </div>
        </div>
    </body>
</html>
