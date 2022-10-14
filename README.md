# Binary-Search-Tree-Projesi

[patika](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje)

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

root = 7
# 
5 7'den küçük sola koyulur
                  7
                 /  
                5 
#                
1 7'den küçük soldan devam 5'ten küçük sola koyulur           
                  7
                 / 
                5
               /
              1
              
 #             
 8 7'den büyük sağa koyulur
 
                  7
                 / \
                5   8
               /
              1
 
 
 #
 3 7'den küçük soldan devam 5'ten küçük soldan devam 1'den büyük sağa koyulur
 
 
            7
          /   \
         5     8
       /       
      1        
       \
        3
 #
 6 7'den küçük 5'ten büyük sağa koyulur
 
            7
          /   \
         5     8
        / \      
       1   6     
        \
         3
 
 
 #
 0 7 den küçük soldan devam  5'ten küçük soldan devam 1'den küük sola koyulur
 
 
             7
          /   \
         5     8
        / \      
       1   6     
      / \
     0   3
     
#
9 7'den büyük sağdan devam 8'den büyük sağa koyulur
 
            7
          /  \
         5    8
        / \    \  
       1   6    9 
      / \
     0   3
     
# 
4 7'den küçük soldan devam 5'ten küçük soldan devam 1'den büyük sağdan devam 3'den büyük sağa koyulur
            7
          /  \
         5    8
        / \    \  
       1   6    9 
      / \
     0   3
          \
           4
           
#           
2 7'den küçük soldan devam 5'ten küçük soldan devam 1'den büyük sağdan devam 3'den küçük sola koyulur

           7
          /  \
         5    8
        / \    \  
       1   6    9 
      / \
     0   3
        / \
       2   4




