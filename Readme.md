# Be a Typescript Technocrat

### Explore Basic Types of Typescript

**Explore Primitive Types**
```
let userName:string = "sujoy";

let userId: number = 123;

let isAdmin : boolen = true;

let x : undefined = undefined;

let y = undefined;
```
যদি আমরা কোনো ডাটা টাইপ বলে নাহ দি, তাহলে ts তাকে :any টাইপ হিসেবে ধরে নেয়

**Explore Non Primitive Types**
সাধারনত Non Primitive Data Type বলতে আমরা Arry ও Object কে বুঝি

1. Arry

- String type Array
 ```
 let bazarList : string[] = ["eggs", "milk", "suger"]
 ```
 - Number type Array
 ```
 let num : number[] = [ 1, 2, 3, 4 ]
 ```
 - Mixed Array
 ```
 let mixedArray: (string| number)[]= ["eggs", 12, "Milk", 31, "sugar"];
 ```
 