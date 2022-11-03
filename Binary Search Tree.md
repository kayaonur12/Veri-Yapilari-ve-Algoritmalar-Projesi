# Merge Sort

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

        Dizi ilk olarak 7 ile başlayor, bu root'um oluyor 
        5: 7'nin solunda bulunur -->  5<7
        1: 5'in solunda bulunur -->  1<7 & 1<5
        8: 7'nin sağında bulunur -->  8>7
        3: 1'in sağında bulunur -->  3<7 & 3<5 & 3>1
        6: 5'in sağında bulunur -->  6<7 & 6>5
        0: 1'in solunda bulunur -->  0<7 & 0<5 & 0<1
        9: 8'in sağında bulunur -->  9>7 & 9>8
        4: 3'in sağında bulunur -->  4<7 & 4<5 & 4>1 & 4>3
        2: 3'in solunda bulunur -->  2<7 & 2<5 & 2>1 & 2<3