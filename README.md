Convercion de Temperatura
function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
	var tempMtyC= 13;
	tempMtyF = celsiousToF(tempMtyC);
	console. log(tempMtyF);
	
	}
function celsiusToF(tempC) {
	var tempF;
	tempF = (9/5)*tempC+32 
