# Veri-Yapilari-ve-Algoritmalar-Final-Project
Insertion sort projesi,
Merge Sort Projesi,
Binary Search Tree Projesi
# Insertion Sort Projesi #
[22,27,16,2,18,6] -> Insertion Sort

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.
- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
- izi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Çözüm:
* 1.[22,27,16,2,18,6]
* 2.[22,16,27,2,18,6]
* 3.[16,22,27,2,18,6]
* 4.[16,22,2,27,18,6]
* 5.[16,2,22,27,18,6]
* 6.[2,16,22,27,18,6]
* 7.[2,16,22,18,27,6]
* 8.[2,16,18,22,27,6]
* 9.[2,16,18,22,6,27]
* 10.[2,16,18,6,22,27]
* 11.[2,16,6,18,22,27]
* 12.[2,6,16,18,22,27]

# Big O 
* Worst case ---> O(n^2)
* Average case ---> O(n^2)
* Best case ---> O(n)

# Time Complexity
* Best case ---> [2,6,16,18,22,27]
* Worst case ---> [27,22,18,16,6,2]




