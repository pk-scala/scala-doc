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
   
4. Converting array of string to array of int

   val arr = Array("1", "12", "123");
   val intArr = arr.map(_.toInt);  // _.toInt is same as x => x.toInt
   
5. Loop and do math operations

   var arr = Array(1, 5, 7, 10);
   arr.foldLeft(0)((sum, value) => sum + value); // Returns sum of all elements
   arr.foldLeft(1)((prod, value) => prod * value); // Returns product of all elements