# Insertion Sort 

**(Not: Burada Insertion Sort'a göre çözüm yapılmış olup, videolardaki gibi çözüm isteniyorsa onun için de Selection Sort dosyası yüklenmiştir)**

> A 

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

        [22|27,16,2,18,6]

        [22,27|16,2,18,6]

        [16,22,27|2,18,6]

        [2,16,22,27|18,6]

        [2,16,18,22,27|6]

        [2,6,16,18,22,27]

        

2. Big-O gösterimini yazınız.

        1 + 2 + ... (n-2) + (n-1) + n
        n*(n-1)/2
        n²/2 + n/2
        O(n²)

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
        Worst Case Big-O gösterimindeki gibi -> O(n²)
        
        Best Case tam hepsi sıralı olunca bir defa n kerelik işlem yapıyorum ve bitiyor -> O(n)
        
        Avarage Case -> O(n²)

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
        
        18 sayısı ortada olduğu için sıralandıktan sonra Average Case kapsamına girer 

> B

1. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

        [7|3,5,8,2,9,4,15,6]
        [3,7|5,8,2,9,4,15,6]
        [3,5,7|8,2,9,4,15,6]
        [3,5,7,8|2,9,4,15,6]
        
