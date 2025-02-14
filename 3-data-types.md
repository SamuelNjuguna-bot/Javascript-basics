1. __DATA TYPES__
   

There are several types of datatypes including 


- Strings 
- Numbers
- Boolean
- Bigint
- Undefined
- Null

a. __Strings__


This data type is distiguished by use of two double quotes on its values.Here are some of the examples.

```
    var name = "Houston"
    let age = "55";
 ```


 b. __Numbers__


 Numbers are used to store both interger values and floating point values.



```
    var x =  23
    let pi= 3.142

 ```
    

c. __Boolean__


Boolean type returns two values only; *true* and *false* values


```
let x = 7 ;
let y = 3 ;

console.log(x>y);
console.log(x===y);

```


Output
```
true
false
```
d. __BigInt__


This is used to represent values that are bigger than the standard Num limit.

```
let bigNumber = 123456789012345678901234567890n;
console.log(typeof(bigNumber)) // Output: BigInt

```


e.__Undefined__


```
const epsilon ;
console.log(epsilon) ;
//Output: undefined
```


f. __Null__
```

const empty = Null;
```