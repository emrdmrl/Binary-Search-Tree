# [Binary-Search-Tree](www.patika.dev)
1. [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
- Her seferinde listeyi ikiye bölerek ilerleme sağlanır. 
- 7 rakamını root olarak alırsak 5 7'den küçük olduğu için sol tarafa eklenir.
- Daha sonra 1 rakamı yine 7'den küçük olduğu için sol tarafa eklenir.Ancak sol tarafta 5 rakamı olduğu için 1'de 5'den küçük olduğu için 5 rakamının soluna eklenir.
-         7
-        5
-       1 şeklinde.
- Daha sonra 8 rakamı 7'den büyük olduğu için sağ tarafa eklenir.
-         7
-        5 8
-       1 şeklinde.
- 3 rakamı yine 7 den küçük olduğu için sola eklenir.
         7
      5     8
   1
    3 
-
- 6 rakamı için;
-          7
-      5       8
-   1    6 
-    3
   
-           7
-      5       8
-   1    6 
- 0  3  

-           7
-      5       8
-   1    6       9
- 0  3 
  
-           7
-      5       8
-   1    6       9
- 0  3 
-     4
  
-            7
-        5       8
-   1      6       9
- 0    3 
-     2 4
  