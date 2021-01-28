# epic-2-finaltermoutput-Espino
// MANDALA MIDTERM
// ESPINO, DYZZA 
// BSEMC 2A


const CIRCLE = 400
const SIDES = 18
const angle = 360 / SIDES

const Dyz = 18
const Dyzs = 360 / Dyz

const op = 8
const ops = 360 / op

const gd = 16
const gds = 360 / gd
function setup() {
  createCanvas(530, 530);
  angleMode(DEGREES)
  rectMode(CENTER)
}
function draw() {
background("#00a8ff");

push()
translate(width/2, height/2)
strokeWeight(2);
ellipse(0, 0, 450, 450)
  
  
  push()
   for (let i = 0; i < gd; i++) {
    
    
     
    push()
     //mid
     ellipse(20, 192, 30,30)
     ellipse(-20, 192, 30,30)
     // up
     ellipse(0, 210, 30,30)
     //down
      ellipse(17, 166, 30,30)
     ellipse(-17, 166, 30,30)
       
     pop()
    
     
     push()
     fill('black')
      //mid
     ellipse(20, 192, 20,20)
     ellipse(-20, 192, 20,20)
     // up
     ellipse(0, 210, 20,20)
     //down
      ellipse(17, 166, 20,20)
     ellipse(-17, 166, 20,20)
     pop()
     
      push()
      //mid
     ellipse(20, 192, 10,10)
     ellipse(-20, 192, 10,10)
     // up
     ellipse(0, 210, 10,10)
     //down
      ellipse(17, 166, 10,10)
     ellipse(-17, 166, 10,10)
     pop()
     
     
     push()
     ellipse(0, 185, 35,35)

     pop()
     
      push()
     fill('black')
     ellipse(0, 185, 25,25)
     pop()
     
      push()
    
     ellipse(0, 185, 15,15)
     pop()
    rotate(gds)
    }
  pop()
  

pop()





  
  
//Fifth Circle
    push()
    translate(width/2, height/2)
    strokeWeight(2);
    ellipse(0, 0, 304, 304)
    

  
   for (let i = 0; i < op; i++) {
    
    
     
  triangle(15, 100, -15, 100, 0, 50)  
    
  triangle(15, 100, -15, 100, 0, 150)   
     
  line(0, 0, 0, 150)  
  line(0, 50, 7, 100)         
  line(0, 150, 7, 100)    
  line(0, 50, -7, 100)         
  line(0, 150, -7, 100) 
     
     
     
     
 push()
     
     ellipse(45.5, 110, 55,55)
     //middle
     ellipse(45.5, 110, 7,7)
     //down
     ellipse(39.5, 95, 7,7)
     
     ellipse(30, 107, 7,7)
     
     ellipse(53, 97, 7,7)
     //up
     ellipse(52, 125, 7,7)
     
     ellipse(37, 123, 7,7)
     
     ellipse(60, 113, 7,7)
     
  pop()
     
     
     
    rotate(ops)
    }
  
   for (let i = 0; i < gd; i++) {
      
   line(0, 0, 0, 91)
          
    rotate(gds)
    }

  
  
  
  
    pop()   
  
  
  
  
  
  
  
  
  
//Sixth Circle
    push()
    translate(width/2, height/2)
    strokeWeight(2);
    ellipse(0, 0, 100, 100)
    

  for (let i = 0; i < Dyz; i++) {
    
    
  ellipse(0, 40, 7, 7)
      
 
    rotate(Dyzs)
    }
  
  
    pop()  
  
  
  
  //Seventh Circle
    push()
    translate(width/2, height/2)
    strokeWeight(2);
    ellipse(0, 0, 65, 65)
    

    pop()     
  
  
 //Eight Circle
    push()
    translate(width/2, height/2)
    strokeWeight(2);
    ellipse(0, 0, 57, 57)
    

    pop()     
  
  
  
  
  
//third to the last Circle
    push()
    translate(width/2, height/2)
    strokeWeight(2);
    ellipse(0, 0, 45, 45)
    

    pop()  
  
  //second to the last Circle
    push()
    translate(width/2, height/2)
    strokeWeight(2);
    ellipse(0, 0, 35, 35 )
    

   for (let i = 0; i < Dyz; i++) {
    
    
  
      
    line(2, 0, 5, 21)
    line(-2, 0, -5, 21)
    
  
    rotate(Dyzs)
    }
  
  
  
  
    pop() 

 //Last Circle
    push()
    translate(width/2, height/2)
    strokeWeight(2);
    ellipse(0, 0, 20, 20)
    
    
    for (let i = 0; i < gd; i++) {
    
    
      
     //Guide lines 
      
//   line(0, 0, 0, 91)
          
    rotate(gds)
    }
    
    
   
    pop()

}
