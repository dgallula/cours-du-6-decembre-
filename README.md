# cours-du-6-decembre-

// //exemples d'exercices avec set 
// //  est ce que dudi fait partie de la classe ? 

// let items = new Set ();

// items.add("dudi")
// items.add("David")
// items.add("neri")
// items.add("ouriel")

// function runCode() { 

// console.log(items)

// for (const item of items ) {
//   console.log(item)
// }
// }

// if (items.has("dudi")) {
//   console.log(" dudi fait partie de la classe")
// }

  // est ce que le numero d'identité se trouve sur la liste 

  
// let items = new Set ();

// items.add("ID1234")
// items.add("ID1235")
// items.add("ID1236")
// items.add("ID1238")

// function runCode() { 

// console.log(items)

// for (const item of items ) {
//   console.log(item)
// }


// if (items.has("ID1239")) {
//   console.log(" ID1239 fait partie de la liste ")
// }else {
//   console.log("ID1239 ne fait pas partie de la liste")
//   }
// } 

//  exercice avec Map 

// let idToMessage = new Map()

//  idToMessage.set(1,"השרת נפל")
//  idToMessage.set(2,"המערכת ממתינה ")
//  idToMessage.set(3,"נוסף בהצלחה")
//  idToMessage.set(4,"בעית קליטה ")
//  idToMessage.set(5,"הצלחה")


//  function runCode() {
//    for(const[key,value] of idToMessage.entries()){
//      console.log(key,value)
//    }

//  }

//autre exemple : determiner le numero de place suivant les noms des etudiants 


// let seatOfStudents = new Map()

//  seatOfStudents.set(1,"דוד")
//  seatOfStudents.set(2," שרה ")
//  seatOfStudents.set(3," מושה ")
//  seatOfStudents.set(4," יעל ")
//  seatOfStudents.set(5," שושנה")


//  function runCode() {
//    for(const[key,value] of seatOfStudents.entries()){
//      console.log(key,value)
//    }
//  } 


// // ex de find : trouver le premier nombre superieur à 30

// let arr = [10,20,30,40,50,]

// function isBiggerthan30(num) {
//   return num > 30
// }

// function runCode () {
//   let value

//   value=arr.find(isBiggerthan30)
//   if (value) {
//     console.log(value)
//   }
// }

//autre version plus courte 

// let arr = [10,20,30,40,50,]

// function runCode () {
//   let value

// value= arr.find(item=> item > 30 )

//   if (value) {
//     console.log(value)
//   }
// }

 // exemple de filter : n'afficher que les nombres pairs 

//  let arr = [10, 25,15,23 ,20,30,40,50,]

// function runCode() {
// let number

// number = arr.filter(item=> item%2 ===0)
//   if (number) {
//     console.log("ma nouvelle liste de nombre pairs est:"+ number)
//   }
// } 

// n'afficher que les nombres impairs 


//  let arr = [10, 25,15,23 ,20,30,40,50,]

// function runCode() {
// let number

// number = arr.filter(item=> item%2 ===1)
//   if (number) {
//     console.log("ma nouvelle liste de nombres impairs est:"+ number)
//   }
// } 

  // n'afficher que les nombres supérieurs à 40

//   let arr = [10, 25,15,23 ,20,30,40,50,]

//  function runCode() {
//  let number

//  number = arr.filter(item=> item > 40)
//   if (number) {
//     console.log( number)
//   }
// } 


    // multiplier chaque chiffre par lui même 

  // let arr = [1, 2,3,4 ,5,6,7,8,9]

  // function runCode() {
  // let number 

  // number = arr.map(item=> item*item)
  // if (number) {
  //   console.log(number)
  //   }
  // }

    // retirer  à chaque chiffre 1 

  //    let arr = [1, 2,3,4 ,5,6,7,8,9]

  // function runCode() {
  // let number 

  // number = arr.map(item=> item - 1)
  // if (number) {
  //   console.log(number)
  //   }
  // }

  //   // multiplier chaque chiffre par lui même avec forEach


  // let arr = [1, 2,3,4 ,5,6,7,8,9]

  //  function runCode() {
  //  let number 

  //  number = arr.forEach(item=> item*item)
  //  if (number) {
  //   console.log(number)
  //    }
  //  }

    

  //  number = arr.forEach(item=> item*item)
  //  if (number) {
  //   console.log(number)
  //    }
  //  }



  // //  afficher l'index de chaque chiffre avec forEach

  //    let arr = [1, 2,3,4 ,5,6,7,8,9]

     
  //   function runCode() {
  //   arr.forEach(consoleItems);

  //   function consoleItems(items,index,arr) {

  //  console.log(items)

  //   }
  // } 
