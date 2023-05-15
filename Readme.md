# Destructuring Exercise

```
const createInstructor = (firstName, lastName) => {
    return {
        firstName, 
        LastName
    }
}
```

```
var favoriteNumber = 42;

var instructor = {
  firstName: "Colt", 
  [favoriteNumber] = "This is my favorite number"
}
```

```
const instructor = {
  firstName: "Colt",
  sayHi(){
    return "Hi!";
  },
  sayBye(){
    return this.firstName + " says bye!";
  }
}
```

```
const createAnimal = (species, verb, noise) => {
  return {
    species,
    [verb](){
      return noise;
    }
  }
}
```
