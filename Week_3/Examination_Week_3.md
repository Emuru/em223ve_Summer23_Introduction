```JavaScript
let myName = "Bob"
let yourName = "Prince"
let year = 1994

console.log(typeof myName)
console.log(typeof year)

console.log("Me: Hi, I'm " + myName + ", what is your name?")

if (year > 1992){
  console.log("You: Hi " + myName + ", nice to meet you! I used to go by " + yourName + ".")
  yourName = "The Artist (Formerly Known as Prince)"
  console.log("You (continues): Nowdays I go by " + yourName + ".")
}
```