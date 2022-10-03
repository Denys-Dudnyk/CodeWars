function findAverage(array) {

  if(array.length==[]){
     return 0
  }else{
    const a=array.reduce((b,c)=>
    b+c
  ,0)
    return a/ array.length
   
  }
  

  
}