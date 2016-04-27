1. Initializing Array of Integers

   var arrayInt = Array(1);

2. Creating new Array of String with defined length

   var size = 10;
   var arrayOfStrings = new Array[String](size);
   
3. Looping/Iterating through Array

   for(i <- 0 until arrayOfStrings.length){
     println("ith element is : " + arrayOfStrings(i));
   }
   
   for(myString <- arrayOfStrings){
     println(myString);
   }
   
   // for using decrement
   for(i <- arrayOfStrings.length-1 to 0 by -1){
     println("ith element is : " + arrayOfStrings(i));
   }