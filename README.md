# Js-Challenges
Js small challenge And Small tricky task

### 1
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
