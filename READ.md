const getMaxValue=(valueList)=>{
    
    //判断valueList是否为空
   if ( valueList.length == 0) 
     return null;

   let max = valueList[0];
     for ( let i=1; i<valueList.length - 1; i++){
     max = max < valueList[i+1] ? valueList[i+1] : max  
     
     //如果是true，则返回valueList[i+1],否则返回max
}

   return max;

}
export getMaxValue;
