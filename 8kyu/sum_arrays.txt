// Sum Numbers
let numbers=[1, 5.2, 4, 0, -1]

function sum (numbers) {
    
  "use strict";
  
 let result=0
  
  for(let i=0; i<numbers.length;i++){
     
      if(numbers.length!==[]){
       result+=numbers[i]
      }else{
        return result
      }
    }
   
  
   return result

    
    
};