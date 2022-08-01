# Binary Search Tree Project

### 1. [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary Search Tree aşamalarını yazınız.
##### Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Dizide belirlenen root 7. Sağ tarafından kendinden büyük elemanlar, sol tarafında ise kendinden küçük elemanlar bulunacak.

### 5 < 7 olduğundan 5, 7'nin solunda yer alacak.

            7
           /
          5
          
### 1 < 7 olduğundan 1, 7'nin solunda, 1 < 5 olduğundan 5'in soluna yer alacak.   
            
            7
           /
          5
         /
        1
 
 ### 8 > 7 olduğundan 8, 7'nin sağında yer alacak.
         
             7
           /  \
          5     8
         /
        1
        
### 3 < 7 olduğundan 3, 7'nin solunda, 3 < 5 olduğundan 5'in solunda, 3 > 1 olduğundan 1'in sağında yer alacak.     
 
             7
           /  \
          5     8
         /
        1
          \
            3
            
### 6 < 7 olduğundan 6, 7'nin solunda, 6 > 5 olduğundan 5'in sağında yer alacak.
 
             7
           /  \
          5     8
         /  \
        1     6
          \
            3
 
 
### 0 < 7 olduğundan 0, 7'nin solunda, 0 < 5 olduğundan 5'in solunda, 0 < 1 olduğundan 1'in solunda yer alacak.
 
             7
           /  \
          5     8
         /  \
        1     6
      /  \
     0    3
 
### 9 > 7 olduğundan 9, 7'nin sağında, 9 > 8 olduğundan 8'in de sağında yer alacak.
 
             7
           /  \
          5     8
         /  \     \
        1     6     9
      /  \
     0    3
 
### 4 < 7 olduğundan 4, 7'nin solunda, 4 < 5 olduğundan 5'in solunda, 4 > 1 olduğundan 1'in sağında, 4 > 3 olduğundan 3'ün sağında yer alacak.
      
            7
           /  \
          5     8
         /  \     \
        1     6     9
      /  \
     0    3
            \
              4
 
### 2 < 7 olduğundan 2, 7'nin solunda, 2 < 5 olduğundan 5'in solunda, 2 > 1 olduğundan 1'in sağında, 2 < 3 olduğundan 3'ün solunda yer alacak.
 
              7
           /  \
          5     8
         /  \     \
        1     6     9
      /  \
     0    3
         /  \
        2    4
            
  
### Patika.dev -> https://app.patika.dev/busraekicii
