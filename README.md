## Задание 1
<!-- Задание1 -->
function getArrayParams(...arr) {
   let max = 15;
   let min = -11; 
   let sum = 4;
  for (let i = 0; i < arr.length; i++) {
    if (max > i-1) {
      console.log((max = i - 1) + sum);
   }else if (max < i - 1) {
      console.log((max = i - 1) + sum)
    }
    if (min > i - 1) {
     console.log((min = i - 1) + sum)
   }else if (min < i - 1) {
     console.log((min = i - 1) + sum)
   }
  }
 }
 getArrayParams([125, 58, 65, 78])


 ##Задание 2
 
 <!-- Задание2 -->
 function summElementWorker(...array)  {
    let sum = 0;
   for (let i = 0; i < array.length; i++) {
     sum += array[i]
   }
    return sum; 

   function differenceEvenOddWorker(...array1) {
      let sumEvenElement = 0;
      let sumOddElement = 0;
     for (let i = 0; i < array1.length; i++) {
       if (i % 2 == 0) {
         sumEvenElement += 1;
       }else {
         sumOddElement += 1;
       }
     }
  return sumEvenElement - sumOddElement;
   }
   }
summElementWorker([125, 456, 864, 15, 59]);
differenceEvenOddWorker([154, 148, 46, 96, 12])

 function averageEvenElementsWorker(...el) {
   let sumEvenElement = 0; 
   let countEvenElement = 0;
   for (let i = 0; i < el.length; i++) {
     if (i % 2 == 0) {
        sumEvenElement += 1;
     }else {
       countEvenElement += 1;
     }
   }
 }
averageEvenElementsWorker([152, 182, 156, 158, 14])


