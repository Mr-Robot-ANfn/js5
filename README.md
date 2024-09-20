// QUESTION 1
//Declare an empty array using JS literal notation to store student names in future.

// let Student_name=[];

// QUESTION 2
//Declare an empty array using JS object notation to store student names in future.

// let []Student_name1=new Student_name1();


// QUESTION 3
// Declare and initialize a strings array.

// let sArray=["Shahab","Fahad"];


// QUESTION 4
// Declare and initialize a number array.

// let sArray=[1,2];


// QUESTION 5
// Declare and initialize a boolean array.

// let bArray=[true,false];


// QUESTION 6
// Declare and initialize a mixed array.

// let mArray=[1,"Shahab",true,undefined,null];


// QUESTION 7
// Declare and Initialize an array and store available
// education qualifications in Pakistan (e.g. SSC, HSC, BCS,
// BS, BCOM, MS, M. Phil., PhD). Show the listed
// qualifications in your browser like:

// let a=["SSC", "HSC", "BCS","BS", "BCOM", "MS", "M. Phil." ,"PhD"]
// for(let i=0;i<a.length;i++){
//     console.log(i+") "+a[i]);
// }

//QUESTION 8
// Write a program to store 3 student names in an array.Take
// another array to store score of these three students.
// Assume that total marks are 500 for each student, display
// the scores & percentages of students like:

// let names=["Shahab","Hamza","John"];
// let score=[500,500,500 ];
// let i=0;
// let j=0;
// while(i<names.length){
//     console.log("Score of "+names[i]+" is "+score[j]+". Percentage: "+((score[i]/500)*100));
//     i++;j++;

// }


//QUESTION 9
//Initialize an array with color names. Display the array
// elements in your browser.

// a. Ask the user what color he/she wants to add to the
// beginning & add that color to the beginning of the array.
// Display the updated array in your browser.

let color = ["yellow", "green", "blue", "orange", "sky blue", "red", "black", "chartreuse"]
// for (const element of color) {
//     console.log(element);

// }
// let ask = prompt("what color you wants to add to the beginning ");
// color.unshift(ask);

// for (const element of color) {
//     console.log(element);

// }

//Ask the user what color he/she wants to add to the end & add that color to the end of the array. Display the updated array in your browser.

// let ask = prompt("what color you wants to add to the end ");
// color.push(ask);

// for (const element of color) {
//     console.log(element);

// }


//Add two more color to the beginning of the array. Display the updated array in your browser.


// let ask = prompt("what color you wants to add to the beginning ");
// color.unshift(ask);

// for (const element of color) {
//     console.log(element);

// }

// Delete the first color in the array. Display the updated array in your browser.

// color.unshift();

// for (const element of color) {
//     console.log(element);

// }

// Delete the last color in the array. Display the updated array in your browser.

// color.pop();

// for (const element of color) {
//     console.log(element);

// }


//Ask the user at which index he/she wants to add a color
// /color name. Then add the color to desired
//position/index. . Display the updated array in your
//browser.

// for (const element of color) {
//     console.log(element);

// }
// let index = +prompt("At which index you want to add the color");
// let colour = +prompt("Name the color you want to add");
// color.splice(index,0,colour);
// for (const element of color) {
//     console.log(element);

// }

// Ask the user at which index he/she wants to delete
//color(s) & how many colors he/she wants to delete. Then
//remove the same number of color(s) from user-defined
//position/index. . Display the updated array in your
//browser.

// for (const element of color) {
//     console.log(element);

// }
// let dindex = +prompt("At which index you want to delete the color");
// let nd = +prompt("how many color you wants to delete");
// color.splice(dindex,nd);
// for (const element of color) {
//     console.log(element);

// }


//QUESTION 10
//Write a program to store student scores in an array &
//sort the array in ascending order using Array’s sort
//method.

// let scores=[320,230,480,120];
// for (const element of scores) {
//     console.log(element);
// }
// scores.sort();
// console.log("Sorted Array");

// for (const element of scores) {
//     console.log(element);
// }


//QUESTION 11
//Write a program to initialize an array with city names.
// Copy 3 array elements from cities array to selectedCities
// array.

// let names=["karachi","lahore","Islamabad","Quetta","Peshawar"];
// console.log(names);

// console.log("Selected Cities");
// let newNames=names.slice(2,4)
// console.log(newNames);

//QUESTION 12
// Write a program to create a single string from the
// below mentioned array:
// var arr = [“This ”, “ is ”, “ my ”, “ cat”];
// (Use array’s join method)

// var arr = ["This", "is", "my", "cat"];
// console.log("Noow String");
// console.log(arr.join(" "));

