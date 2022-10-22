 # Insertion Sort Projem 

 # [Patika.Dev](https://www.patika.dev)

 ## Yapılmak İstenen

 ![](/Insertion-Sort-Projesi/Insertion.png)

 ## Yapılan

 ### 1

 [22,27,16,2,18,6] dizisi;  
 * [22,27,16,2,18,6] → 22 27den küçük mü? Evet küçük.. O zaman devam edelim  
 * [22,27,16,2,18,6] → 27 16dan küçük mü? Hayır değil.. O zaman yer değiştirin, 16 22den küçük mü? Evet küçük.. O zaman yer değiştirin. En başa geldiğimize göre devam edelim  
 * [16,22,27,2,18,6] → 27 2den küçük mü? Hayır değil.. O zaman yer değiştirin, 2 22den küçük mü? Evet küçük.. O zaman yer değiştirin, 2 16dan küçük mü? Evet küçük.. O zaman yer değiştirin. En başa geldiğimize göre devam edelim  
 * [2,16,22,27,18,6] → 27 18den küçük mü? Hayır değil.. O zaman yer değiştirin, 18 22den küçük mü? Evet küçük.. O zaman yer değiştirin, 18 16dan küçük mü? Hayır değil.. O zaman devam edelim  
 * [2,16,18,22,27,6] → 27 6dan küçük mü? Hayır değil.. O zaman yer değiştirin, 6 22den küçük mü? Evet küçük.. O zaman yer değiştirin, 6 18den küçük mü? Evet küçük.. O zaman yer değiştirin, 6 16dan küçük mü? Evet küçük.. O zaman yer değiştirin, 6 2den küçük mü? Hayır değil.. O zaman devam edelim  
 * [2,6,16,18,22,27] → Son elemana geldik. Dizimizin son hali böyle oldu..

 ### 2 

 * Big O Gösterimi → O(n^2)

 ### 3

 * Best Case; [2,6,16,18,22,27]  
 * Average Case; [18,16,6,2,22,27]  
 * Worst Case; [27,22,18,16,6,2]

 ### 4

 * 18 sayısı Average Case kısmına girer

 ### Diger Soru

 [7,3,5,8,2,9,4,15,6] dizisi;  
 1. [3,7,5,8,2,9,4,15,6]
 1. [3,5,7,8,2,9,4,15,6]
 1. [3,5,7,8,2,9,4,15,6]
 1. [2,3,5,7,8,9,4,15,6]
