# Constructor-functions


function Cat(name) {
 this.name = name;
 this.sound = "Meow";
}
//Constructor functions are invoked using the new keyword
let cat = new Cat("Tom");
cat.sound; // Returns "Meow"
