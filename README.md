// Write a “person” class to hold all the details.
var person = function(name, gender, age, ocupation){
this.name = name;
this.gender = gender;
this.age = age;
this.ocupation = ocupation;
this.setAge = function(age){
this.age = age;
};
this.toString =function(){
return[ " hi I'm ", this.name, " and I'm ", this.gender, " and I have ", this.age, " years and my ocupation is ", this.ocupation].join("");
};
};
var nimma = new person("Niranjan", "male", 30, "private job");
console.log(nimma.toString());



// write a class to calculate uber price
class Uber{
    constructor(name,city,kms,cost){
        this.name=name;
        this.city=city;
        this.kms=kms;
        this.cost=cost;
    }
    getPrice(n){
        return this.cost*this.kms;
    }
}

var c1 = new Uber("niranjan","hyderabad",10,15)
console.log(c1.getPrice());
