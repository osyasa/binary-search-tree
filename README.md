# Binary Search Tree
## [7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

    Öncelikle dizi küçükten büyüğe sıralanır.
    [0,1,2,3,4,5,6,7,8,9]
    
    Root dizinin ortasındaki eleman olarak seçilir.
    root = 4

    root'un sağındaki node, dizinin sağ tarafının ortasıdır = 7

    root'un solundaki node, dizinin sol tarafının ortasıdır = 2

    Diğer node'lar da sağ tarafa büyük sayı ve sol tarafa küçük sayı gelecek şekilde dizilir.

               4
          2         7
         1  3     6   8
       0         5      9