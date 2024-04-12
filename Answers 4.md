Write a chained if / else-if statement to fill in the
following conditions ?

Ans let value=18
if (value<5) {
    console.log("Tiny");
    
}else if (value<10){
    console.log("Small");
    
}else if(value< 15 ){
    console.log("Medium");

}else if(value<20){
    console.log("Large");
}else {
    console.log("Huge");
}


2   Use the switch case and create an application with the
following roles ?

Ans let person=prompt("enter the user type")
    switch(person){
    case "admin":
        alert("Gets Full Access")
        break;

    case "subAdmin":
        alert("gets access to create and delete courses");
        break;
    case "testPrep":
        alert("gets access to create and delete tests");
        break;
    case "user":
        alert("gets access to consume contents");
        break;
    default:
        alert("Invalid option");
}

