# Proje 3
---

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları:
 
### Root = 7 olarak seçilirse,

İlk olarak 7'nin solunda 5 yer alır. Arkasından sırayla, 1 sayısı 5'in solunda, 8 sayısı 7'den büyük olduğu için, 7'nin sağında konumlanır. 


                              7
                         5        8
                    1      

Arkasından, sırayla aynı kurala göre devam edildiğinde, sırasıyla 3, 6 ve 0 aşağıdaki gibi eklenir.

                              7
                         5        8
                    1       6         
                0      3


Son olarak, 9, 4 ve 2 eklendiğinden, verilen dizi için aşağıdaki binary-search-tree diagram elde edilir. 

                              7
                         5        8
                    1      6          9
                0     3
                    2   4
