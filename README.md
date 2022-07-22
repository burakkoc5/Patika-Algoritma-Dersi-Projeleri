# Patika-Algoritma-Dersi-Projeleri

## Proje1 
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


## Cevap 1
[22,27,16,2,18,6]

[2,27,16,22,18,6]

[2,6,16,22,18,27]

[2,6,16,18,22,27]

## Big O Notation Gösterimleri
Worst Case: O(n²)      [27,22,18,16,6,2]

Average Case: O(n²)

Best Case: O(n)        [2,6,16,18,22,27]


## 18 Sayısının Case Durumu : Average Case

[7,3,5,8,2,9,4,15,6] Dizisinin İlk 4 Adımı

2 3 5 8 7 9 4 15 6

2 3 4 8 7 9 5 15 6

2 3 4 5 7 9 8 15 6

2 3 4 5 6 9 8 15 7


## Proje 2 
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

## Cevap 2

[16,21,11,8,12,22] İkiye bölme

[16,21,11] ve [8,12,22] İkiye bölme

[16],[21,11] ---- [8],[12,22] İkiye bölme

[16] - [21], [11] ----- [8] - [12], [22] Birleştirme

[16] - [11,21] ----- [8] - [12,22] Birleştirme

[11,16,21] ----- [8,12,22] Birleştirme

[8,11,12,16,21,22] Tamamlandı


## Big-O Gösterimi

O(nlogn)   

## Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

## Cevap 3

Root 7 
5 < 7 bundan dolayı 7'nin soluna eklenir

1 < 5 bundan dolayı 5'in soluna eklenir

8 > 7 bundan dolayı 7'nin sağına eklenir

3 < 5 ve 3 > 1 bundan dolayı 5'in soluna 1'in sağına eklenir

6 < 7 ve 6 > 5 bundan dolayı 7'nin soluna 5'in sağına eklenir

0 < 7 , 0 < 5 ve 0 < 1 bundan dolayı 1'in soluna eklenir

9 > 7 ve 9 > 8 bundan dolayı 8'in sağına eklenir

4 < 7 , 4 < 5 ve 4 > 1 , 4 > 3 bundan dolayı 5'in soluna ve 3'ün sağına eklenir

2 < 7 , 2 < 5 ve 2 > 1 , 2 < 3 bundan dolayı 5'in soluna 1'in sağına ve 3'ün soluna eklenir




[patika.dev](www.patika.dev)

