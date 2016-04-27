1. Read n lines
   var lines = io.Source.stdin.getLines();
   var nLines = lines.take(n);

2. Read line with space separated integers
   var splitElements = readLine().split(" ");
   var inputArray :Array[Int] = splitElements.map(x=>x.toInt); 