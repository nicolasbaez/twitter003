# twitter003
#つぶやきProcessing void setup(){size(512,256,P3D);}int x=1;void draw(){background(0);translate(256,128,32);rotateX(radians(x));rotateY(radians(x/2));x+=map(sin(radians(x)),-1,1,1,16);sphereDetail(3);stroke(0);strokeWeight(random(32));fill(random(256),0,random(256));sphere(99);}
