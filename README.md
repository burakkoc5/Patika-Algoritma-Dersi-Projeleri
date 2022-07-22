# Patika-Algoritma-Dersi-Projeleri

## Proje1 
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


## Cevap 1
22 27 16 2 18 6 

2 27 16 22 18 6

2 6 16 22 18 27

2 6 16 18 22 27

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


# Proje 2 
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

# Cevap 2

[16,21,11,8,12,22] İkiye bölme

[16,21,11] ve [8,12,22] İkiye bölme

[16],[21,11] ---- [8],[12,22] İkiye bölme

[16] - [21], [11] ----- [8] - [12], [22] Birleştirme

[16] - [11,21] ----- [8] - [12,22] Birleştirme

[11,16,21] ----- [8,12,22] Birleştirme

[8,11,12,16,21,22] Tamamlandı


# Big-O Gösterimi

O(nlogn)   












[patika.dev](www.patika.dev)

