# snake-game-withcanvas

snake & ladders game designed by canvas and code by js and used tween.js for animation

 draw ladders
```
            var img = new Image();


                img.onload = function() {

                    ctx.drawImage(img, 525, 400, 50, 300);
                    ctx.drawImage(img, 136, 280, 50, 300);
                    ctx.drawImage(img, 395, 150, 50, 370);
                    ctx.drawImage(img, 70, -40, 50, 300);

                } 
                img.src = 'ladder-2.png';
               
```


draw snakes
```
         var snake = new Image();
                var snake2 = new Image();

 snake.onload = function() {

                    ctx.drawImage(snake, 465, 200, 100, 300);
                    ctx.drawImage(snake, 265, 70, 100, 300);

                } 

                snake.src = 'snake-2.png';
                snake2.onload = function() {

                    ctx.drawImage(snake2, 260, 390, 150, 200);
                    ctx.drawImage(snake2, 130, 60, 150, 200);

                } 
                snake2.src = 'snake-1.png';
          
                
                
                
                
