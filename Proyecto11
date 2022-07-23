var barco;
var mar, seaImg;

function preload(){
barco = loadAnimation("ship-1.png","ship-2.png","ship-3.png","ship-4.png")
seaImg = loadImage("sea.png");
}

function setup(){
  createCanvas(400,400);
  mar = createSprite(20,180,0,40);
  mar.addImage(seaImg);
  mar.scale = 0.5;

  bar = createSprite(200,200);
  bar.addAnimation("ship-1.png","ship-2.png","ship-3.png", "ship-4.png", barco);
  bar.scale = 0.3;
}

function draw() {
  background("blue");
  drawSprites();

  if (mar.x <0) {
    mar.x=mar.width/2;
  }
}