 var canvas;
    var canvasContext;
    var ballX = 50;
    
window.onload = function() {
    Console.log("hello");
    canvas = document.getElementById('gameCanvas');
    canvasContext = canvas.getContext('2d');
    drawEverything();
    drawEverything();
    drawEverything();
    }
    
function drawEverything() {
    console.log(ballX)
    ballX = ballX + 70;
    
    canvasContext.fillStyle = 'black';
    canvasContext.fillRect(0,0,canvas.width,canvas.height)
    canvasContext.fillStyle = 'white';
    canvasContext.fillRect(200,200,50,25);
    canvasContext.fillStyle = 'green';
    canvasContext.fillRect(ballX,230,50,25);  
    }
