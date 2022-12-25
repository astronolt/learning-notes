## Basics

<br>
<br>


```
const myNum = 3; // TypeScript implicitly types myNum as a number based on the variable

let myVar: number = 3; // myVar has been explicitly typed as a number 
```



<br>
<br>
string

```
let studentName:string;
studentName = 'Dae Lee'
```


<br>
<br>
number

```
let studentAge: number;
studentAge = 10;
```


<br>
<br>
boolean

```
let studentEnriched: boolean;
studentEnriched = true;
```


<br>
<br>
Union Types

```
let studentPhone: (number | string);
studentPhone = '(555) 555 - 5555';
studentPhone = 5555555555;
```