# one
```
module nan(a,b,c,q);
input a,b,c;
output q;
wire x,y;
nor (x,a,b);
nand(y,b,c);
nor(q,x,y);
endmodule
```
