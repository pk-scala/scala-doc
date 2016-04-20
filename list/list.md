1. Initializing
   var list: List[Int] = List[Int]();
   
   // Using ListBuffeer
   var listBuffer = new scala.collection.mutable.ListBuffer[Int]()
   
2. Adding Element to List
   var element:Int = 3;
   var list: List[Int] = List[Int](); // Initializing the List
   list = list :+ element; // Adding element to the list
   
   
   // For listBuffer
   listBuffer += element;
   listBuffer.toList // Converting List Buffer to List

3. Getting element at an index
   var inputList = List(1,2,3,5,6,6,8);
   var mapListIndexes = List(0,1,4,5);
   mapListIndexes.map(index=>inputList(index)); // returns  List(1,2,6,6)

1. Iterating over list
   a. Using foreach
     var numList:List[Int] = List(1,2,3,4);
     // printing each element in new line
     numList.foreach( println(_) );

2. Filter
   var numList:List[Int] = List(1,2,3,4);
   var evenNumbers = numList.filter( _%2 == 0 );