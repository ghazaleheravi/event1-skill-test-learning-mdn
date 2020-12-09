# event1-skill-test-learning-mdn
<!DOCTYPE html>
<hmtl>
  <head>
    <meta charset="utf-8">
    <title>skill test-Event 1</title>
  </head>
  <body>
    <button>Machine is off</button>
    <script>
      const button = document.querySelector('button');
      
      button.addEventListener('click',function(){
        if(button.innerHTML == 'Machine is off'){
          button.textContent = 'Machine is on';
        }else{
          button.textContent = 'Machine is off'; 
        }    
      });

    </script>

  </body>
</html>
