# Selection Sort 

**(Not: Videolardaki gibi çözüm  için bu dosya yüklenmiştir)**

> A 

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

        [22,27,16,2,18,6]

        [2,27,16,22,18,6]

        [2,6,16,22,18,27]

        [2,6,16,22,18,27]

        [2,6,16,18,22,27]

2. Big-O gösterimini yazınız.

        n + (n-1) + (n-2) + .... + 1
        n*(n-1)/2
        n²/2 + n/2
        O(n²)

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
        
        Worst Case Big-O gösterimindeki gibi -> O(n²)
        
        Best Case tam hepsi sıralı olduğunda dahi her defasında birinci sıra için tüm seriye, sonra ikinci için tüm seriye bakacağı için Big-O yine aynıdır -> O(n²)

        Average Case -> O(n²)

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
        
        18 sayısı ortada olduğu için sıralandıktan sonra Average Case kapsamına girer 

>B

1. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

        [2,3,5,8,7,9,4,15,6]

        [2,3,5,8,7,9,4,15,6]

        [2,3,4,8,7,9,5,15,6]

        [2,3,4,5,7,9,8,15,6]