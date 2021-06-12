1.Swap 2 variables, without using any other variables.
let x = 2
let y = 17;
console.log("1. x = "+ x+" y= "+y);
x =x+y;
console.log("2, x = "+ x+" y= "+y);
y = x-y ;
console.log("3, x = "+ x+" y= "+y);
x = x-y ;
console.log("4, x = "+ x+" y= "+y);
1. x = 20 y= 17
2, x = 37 y= 17
3, x = 37 y= 20
4, x = 17 y= 20
undefined
2.xndir chem haskacel chem karoxacel

3.Given five numbers as input. Calculate and print the average of the numbers(without using
arrays).
let a=45;
let b=-12;
let c=0;
let d=3;
let e=-15;
let f=(a+b+c+d+e)/5;

4.Given three numbers. Sort them by the ascending order.
let a=45
let b=26
let c=78
let sgg=c
if ((a<b) && (b<c)){
    sgg = '${a}, ${b}, ${c}'
  } else if ((b<a) && (a<c)){
    sgg = '&{b}, &{a}, &{c}'
  } else if ((b<c) && (c<a)){ 
    sgg = '${b}, ${c}, ${a}'
  } else if ((a<c) && (a<b)){
    sgg =  '${a}, ${c}, ${b}'
  } else if ((c<a) && (c<b)){
    sgg =  '${c}, ${a}, ${b}'
  } else{
     sgg= '${a}, ${b}, ${c}'
  }
  console.log(sgg)
   &{b}, &{a}, &{c}
   undefined
 
5.Given the following code rewrite it using only two if operators. (Hint: use logical operators).

var n= +prompt();

var i=0
var j=0

if ((n % 2 === 0) || (Math.floor(n / 10))) {
       j += 1;

}

1  
   
   
   
