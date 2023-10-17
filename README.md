# loop
## Standand for loop structure
```javascript
for(initializer;condition;final-expresion){

}
```
## for loop
```javascript
let a =[1,2,3,4,5,6,];
for (a = 0; a <10 ; a++) {
}
function convertCase(array) {
    return array.map((item, index) => item.toUpperCase() + index);
  }
  
const array = ["a", "b", "c", "d", "e", "f"];
console.log(convertCase(array));
```
## for...of
```javascript
const names = ["Rakin","Tanjil","Arup","Robin","Fahim"];
for (const name of names){
    console.log(name);
}
```
## map()
```javascript
function toUpper(string) {
    return string.toUpperCase();
}

const animals = ["cat","dog","tigar","cow"];

const upperAnimals = animals.map(toUpper);

console.log(upperAnimals);
```
## filtter()
```javascript
function Name(name){
    return name.startsWith("T");
}
const Names= ['Rishad',"robin","Tanjil"," Arup","Rakin"];

const filttered = Names.filter(Name);

console.log(filttered);
```
```javascript

```



