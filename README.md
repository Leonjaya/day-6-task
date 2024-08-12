# day-6-task
class Person {
constructor(firstName, lastName, age, gender, address, phoneNumber, email) {
this.firstName = firstName;
this.lastName = lastName;
this.age = age;
this.gender = gender;
this.address = address;
this.phoneNumber = phoneNumber;
this.email = email;
}

// Method to get the full name of the person
getFullName() {
return ${this.firstName} ${this.lastName};
}

// Method to display the person's details
getDetails() {
return Full Name: ${this.getFullName()} Age: ${this.age} Gender: ${this.gender} Address: ${this.address} Phone Number: ${this.phoneNumber} Email: ${this.email};
}
}

// Example usage:
const person1 = new Person(
"John",
"Doe",
30,
"Male",
"123 Main St, Anytown, USA",
"123-456-7890",
"john.doe@example.com"
);

console.log(person1.getFullName()); // Output: John Doe
console.log(person1.getDetails());
// Output:
// Full Name: John Doe
// Age: 30
// Gender: Male
// Address: 123 Main St, Anytown, USA
// Phone Number: 123-456-7890
// Email: john.doe@example.com
