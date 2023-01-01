# Selection-Insertion-Sort
patika.dev
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

## 1. Insertion Sort

---

[22,27,16,2,18,6]
[22,16,27,2,18,6]
[16,22,27,2,18,6]
[16,22,2,27,18,6]
[16,2,22,27,18,6]
[2,16,22,27,18,6]
[2,16,22,18,27,6]
[2,16,18,22,27,6]
[2,16,18,22,6,27]
[2,16,18,6,22,27]
[2,16,6,18,22,27]
[2,6,16,18,22,27]

---

Average Case = 18

---

### Time Complexity 
---

* Best Case = O(n) 
* Worst Case = O(n²)
* Average Case = O(n²)

---

## 2. Selection Sort

---

[7,3,5,8,2,9,4,15,6] [2,7,3,5,8,9,4,15,6] [2,3,7,5,8,9,4,15,6] [2,3,4,5,7,8,9,15,6] [2,3,4,5,6,7,8,9,15]
