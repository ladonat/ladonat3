# ladonat3
let variavelGlobal = "Eu sou global";

function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
  text(variavelGlobal, 10, 30);
  exemploLocal();
}

function exemploLocal() {
  let variavelLocal = "Eu sou local";
  text(variavelLocal, 10, 50);
}
