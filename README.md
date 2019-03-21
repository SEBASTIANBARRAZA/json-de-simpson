# json-de-simpson
ejercicio en clases 21/03/2019

var a = 1234;
var b = true;
var c = "palabra";
var d = ["perro", "gato", "ratón",23, false];
var e = {ladra:"perro", maulla:"gato", musita:"raton"};
var f = e.ladra;

var groening = {
	simpsons:{padre:"homero", madre:"marge",hijos:["bart","lissa","maggie"]},
  flamders:{padre:"ned", madre:"mond",hijos:["tod","rod"]},
	VanHouten:{padre:"kirk",madre:"luaan",hijos:"milhouse"},
	muntz:{padre:false,madre:false,hijos:["nelson"]}
					 }
	
	
 function setup() { 
  createCanvas(400, 400);
	noLoop();
	print(groening.muntz)
 }


function draw() {
  background(220);
}
