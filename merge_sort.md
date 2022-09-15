# [Patika.dev](www.patika.dev) | Merge Sort Projesi 

[16,21,11,8,12,22] -> Merge Sort

    1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
    2. Big-O gösterimini yazınız.


[16,21,11,8,12,22]

### Dizideki tüm elemanlar sağa ve sola doğru ikiye bölünür.

>[16,21,11]    [8,12,22]
>>[16,21] [11]        [8,12] [22]
>>>[16] [21]   [11]        [8] [12]  [22]

#### Bu aşamadan sonra tekrar birleşime geçilir.

>[16,21] [11] [8] [12,22]
>>[11,16,21] [8,12,22]
>>>[8,11,12,16,21,22] Dizinin son hali

## Big-O Gösterimi:
O(6(log6)) 


