# twitter017
#つぶやきProcessing float i,k,j;void setup(){size(500,500);}float _(float r){return radians(r);}void draw(){clear();noFill();for(j=64;j&lt;=99;j+=9){stroke(255,0,map(sin(_(k)),0,1,255,0));for(i=k;i&lt;360+k;i+=9){circle(j*cos(_(i))+255,j*sin(_(i))+255,map(sin(_(k)),0,1,81,99));}}k++;}
