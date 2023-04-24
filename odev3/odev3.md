# ÖDEV 3

 - [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

    - Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
* * *
### CEVAP
 
 - lower value (0) , higher value (9)
 - rootumuz yani en ortada bulunan sayımızı 5 olarak alıyoruz
- 5 sayısından yüksekleri yaklaşık ortası 7 olarak alalım
- 5 sayısından düşüklerin yaklaşık ortası 3 olarak alalım
 
 ```
 3 <- 5 -> 7
 ```
 ***
 - 3 sayısından düşüklerin yaklaşık ortası 1 olarak alalım
 ```
 0 <- 1 -> 3
      1 -> 2
 ```
  ***
 - 7 sayısından yükseklerin ortası 8 olarak alalım
 ```
 7 <- 8 -> 9
 ```
 ```
                                         5
                                       /   \
                                     3      7
                                    / \    / \
                                   1   4  6   8
                                 /   \         \
                                0     2         9

 ```