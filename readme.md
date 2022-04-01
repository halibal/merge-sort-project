# [16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız:

   - Dizideki her deger tek basina kalana kadar ikiye ayrilir, ardindan degerler kucukten buyuge ikiye ayrildigi duzenin tersine yeniden birlestirilir.
   1. [16,21,11,8,12,22]
   2. [16,21,11] - [8,12,22]
   3. [6] - [21,11] - [8] - [12,22]
   4. [6] - [21] - [11] - [8] - [12] - [22]
   5. [6] - [11,21] - [8] - [12,22]
   6. [11,16,21] - [8,12,22]
   7. [8,11,12,16,21,22]

2. Big-O gösterimini yazınız:

   1. O(n*log n)
