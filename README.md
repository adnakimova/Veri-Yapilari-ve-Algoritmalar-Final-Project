# Veri-Yapilari-ve-Algoritmalar-Final-Project
Insertion sort projesi,
Merge Sort Projesi,
Binary Search Tree Projesi
# Insertion Sort Projesi #
[22,27,16,2,18,6] -> Insertion Sort

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
  * [22,27,16,2,18,6]
  * [22,16,27,2,18,6]
  * [16,22,27,2,18,6]
  * [16,22,2,27,18,6]
  * [16,2,22,27,18,6]
  * [2,16,22,27,18,6]
  * [2,16,22,18,27,6]
  * [2,16,18,22,27,6]
  * [2,16,18,22,6,27]
  * [2,16,18,6,22,27]
  * [2,16,6,18,22,27]
  * [2,6,16,18,22,27]
  
- Big-O gösterimini yazınız.
  * Worst case ---> O(n^2)
  * Average case ---> O(n^2)
  * Best case ---> O(n)
  
- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
  * Best case ---> [2,6,16,18,22,27] ---> O(n)
  * Worst case ---> [27,22,18,16,6,2] ---> O(n^2)
  
- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
  * 18 sıralandıktan sonra [2,6,16,18,22,27], 18 ortadadır ve average case olur

- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
  * [7,3,5,8,2,9,4,15,6]
  * [3,7,5,8,2,9,4,15,6]
  * [3,5,7,8,2,9,4,15,6]
  * [3,5,7,8,2,9,4,15,6]

# Insertion Sort Projesi

[16,21,11,8,12,22] -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
 * [16,21,11,8,12,22]
 * [16,21,11]  [8,12,22]
 * [16,21] [11]      [8,12] [22]
 * [16] [21]                 [8] [12]
 * [16,21] [11]      [8,12] [22]
 * [11,16,21]     [8,12,22]
 * [8,11,12,16,21,22]    
 
- Big-O gösterimini yazınız.
 * Worst case   --> O(nlogn)
 * Average case --> O(nlogn)
 * Best case    --> O(nlogn)

# Binary Search Tree Sort projesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

![Binary Search Tree](https://github.com/adnakimova/Veri-Yapilari-ve-Algoritmalar-Final-Project/blob/main/bst.png)
