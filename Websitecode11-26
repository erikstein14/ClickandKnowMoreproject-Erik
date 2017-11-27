var img;
var button
var button2
var button3
var button4
var button5
var button6
var person = {
  x:100,
  y:100,

drawPerson: function() {
fill(200,50,100,50);
stroke(200);
ellipse(this.x,this.y,50,50);

},

movePerson: function(){
this.x=this.x+1
}


};


function preload() {
  img = loadImage("Computer-clipart-free-images.jpg");
}

function setup() {
createCanvas(1000, 600);
var listOfColors = [color('#FF0000'), color('#008000	'), color('#0000FF'), color('#fe3fa2'), color('#a345cd')];

for(var i=0;i<listOfColors.length;i++) {
  strokeWeight (35,20)

    stroke(listOfColors[i]);
    line(25, 200, 800, 200);
    translate(250, 0);
  }
fill(0, 39, 200, 0);

    button = createButton(' ');
    button.position(250, 200);
    button.mousePressed(popup1);
    button.style("background-color", "black");
    button.style("padding", "15px 32px");

    button2 = createButton('                   ');
    button2.position(525, 200);
    button2.mousePressed(popup2);

    button3 = createButton('                   ');
    button3.position(675, 200);
    button3.mousePressed(popup3);

    button4 = createButton('                   ');
    button4.position(25, 200);
    button4.mousePressed(popup4);

    button5 = createButton('                   ');
    button5.position(110,375);
    button5.mousePressed(popup5);
    button5.style("background-color", "red");
    button5.style("padding", "18px 18px");

    button6 = createButton('                   ');
    button6.position(123, 436);
    button6.mousePressed(popup6);
    button6.style("padding", "15px 32px");

    button7 = createButton('                   ');
    button7.position(123, 486);
    button7.mousePressed(popup7);
    button7.style("padding", "15px 32px");

    button8 = createButton('                   ');
    button8.position(123, 536);
    button8.mousePressed(popup8);
    button8.style("padding", "15px 32px");

}

function draw () {

  image(img,650,250, 300, 300);



  fill(50, 39, 0, 100);
strokeWeight(0)
textSize(50);
fill(50, 39, 0, 100);
text("History of the computer", 40, 40);
textSize(20);

text("Pre first generation (before 1937)", 150,400);
text("First generation (1937 – 1946)", 150,450);
text("Second generation (1947 – 1962)", 150,500);
text("Third generation (1963 - present)", 150,550);

  person.drawPerson();
  person.movePerson();
fill(color('#FF0000'));
rect(100,375,35,35)
fill(color('#008000'));
rect(100,425,35,35)
fill(color('#0000FF'));
rect(100,475,35,35)
fill(color('#fe3fa2'));
rect(100,525,35,35)

}

function changeBG() {
  var val = random(250);
  background(val);
}
function drawcircle() {
ellipse (200,100,200,200)

}
function popup1() {
  alert("I like the number 1");
}
function popup2() {
  alert("I like the number 2");
}
function popup3() {
  alert("I like the number 3");
}
function popup4() {
  alert("I like the number 4");
}
function popup5() {
  alert("I like the number 4");
}
function popup6() {
  alert("The basics of the electronic computer were created in this generation");
}
function popup7() {
  alert("This generation of computers used transistors instead of vacuum tubes which were more reliable");
}
function popup8() {
  alert(" The invention of integrated circuit brought us the third generation of computers. With this invention computers became smaller, more powerful more reliable and they are able to run many different programs at the same time. ");
}
function mousePressed() {
  img.resize(200, 500);
}

//make a key



//questions: how do I make multiple cirlces w button
//how do I make invisible button
//button within button
//https://www.w3schools.com/css/css3_buttons.asp
