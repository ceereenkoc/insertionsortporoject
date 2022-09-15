# **Insertion Sort Projesi**

## **Part-1**
---
[22, 27, 16, 2, 18, 6]

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

***Soru-1:***

1. Aşama:  [2, 27, 16, 22, 18, 6] --> (n)
2. Aşama:  [2, 6, 16, 22, 18, 27] --> (n-1)
3. Aşama:  [2, 6, 16, 18, 22, 27] --> 1

***Soru-2:***

O (n²)

***Soru-3:***

Average case: O (n²)
Worst case: O (n²)
Best case: O (n)

***Soru-4***

Average case kapsamına girer.

## **Part-2**
---

[7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1. Aşama: [2, 3, 5, 8, 7, 9, 4, 15, 6]
2. Aşama: [2, 3, 4, 8, 7, 9, 5, 15, 6]
3. Aşama: [2, 3, 4, 5, 7, 9, 8, 15, 6]
4. Aşama: [2, 3, 4, 5, 6, 9, 8, 15, 7]