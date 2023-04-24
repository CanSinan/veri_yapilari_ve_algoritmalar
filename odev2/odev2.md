# ÖDEV 2

- [16,21,11,8,12,22] -> Merge Sort

    - Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. 
    - Big-O gösterimini yazınız.
* * * 
- Merge Sort un mantığı, elimizdeki diziyi ikiye bölerek tek eleman kalana kadar devam ettirip kendi içinde sıralama ve tekrar birleştirmedir.
* * * 
 ### CEVAP

- [16,21,11,8,12,22]

- [16,21,11] --- [8,12,22]

- [16] - [21,11] --- [8,12] - [22]

- [16] - [21] - [11] --- [8] - [12] - [22]

- [16] - [11,21] --- [8,12] - [22]

- [11,16,21] --- [8,12,22]

- [8,11,12,16,21,22]
* * * 
- Big-O Gösterimi: O(nlogn)