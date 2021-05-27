## twitter017 | #つぶやきProcessing 
https://twitter.com/nicolasbaez/status/1397012574730919936?s=20

![twitter](https://github.com/nicolasbaez/twitter017/blob/main/twitter017.gif)
```processing
float i, k, j;
void setup() {
  size(500, 500);
}
float _(float r) {
  return radians(r);
}
void draw() {
  clear();
  noFill();
  for (j=64; j<=99; j+=9) {
    stroke(255, 0, map(sin(_(k)), 0, 1, 255, 0));
    for (i=k; i<360+k; i+=9) {
      circle(j*cos(_(i))+255, j*sin(_(i))+255, map(sin(_(k)), 0, 1, 81, 99));
    }
  }
  k++;
}
```
