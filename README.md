# Js-Challenges
Js small challenge And Small tricky task

### Challenge 1
__What is the output__ 
```javascript
    const add = function addThem() {
        let counter = 1
        return value => {
        counter *= value;
        return counter;
    }
    } 
    const addSub = add();  
    for (var i = 1; i <= 3; i++) setTimeout(() => (addSub(i)),100);
```
`OUTPUT: 4, 16 64`  


### Challenge 2
__What is the output__ 
```javascript
    const A = "Hey Linkedin!"
    const B = !A

    console.log(B)
```
`OUTPUT: false`  

### Challenge 3
__What is the output__ 

```javascript
    const a = 5;
    const b = 3;

    console.log(a|b + b|a);
```
`OUTPUT: 7` 
<p>
The symbol | is a bitwise or operator, that means that evaluates every single bit from the first and the second number. 5 in binary is 101 or 3 in binary is 11. 

00000101 | 00000011 = 00000111 = 7
I got misled from the start but yep, thats it
</p>



### Challenge 
__What is the output__ 

```javascript

```
`OUTPUT: `  
