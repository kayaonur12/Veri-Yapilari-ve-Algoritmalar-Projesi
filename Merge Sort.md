# Merge Sort

[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

        [16,21,11,8,12,22]
        [16,21,11] [8,12,22]
        [16] [21,11] [8,12] [22]
        [16] [21] [11] [8] [12] [22]
        [16] [11,21] [8,12] [22]
        [11,16,21] [8,12,22]
        [8,11,12,16,21,22]
2. Big-O gösterimini yazınız.
        
        Önce bölünme aşamasında 2^x = n'den log(n) işlem yapılacak
        Her bir satırda da n-1 yerleştirme yapıyorum
        O(n.logn)
 