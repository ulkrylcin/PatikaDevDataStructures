## Veri Yapıları ve Algoritmalar / Insertion Sort Projesi
![PatikaDev](/InsertionSort.jpg)
**1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**
###Cevap:
Ekleme sıralama yönteminde, sıralanmamış parçadan değerler alınır ve sıralanan parçada doğru konuma yerleştirilir. İlk olarak, dizinin ilk iki elemanı eklemeli sıralamada karşılaştırılır. Bu dizindeki ilk sayımız 22'dir. Karşılaştırma yaptığımız sayı ise 27'dir. Buna göre, 22 sayısı 27 sayısından küçüktür. Bu nedenle ilk sayımız yeni dizide sol tarafta yer alır. Şimdi, sıralanmış alt dizide 22 ve 27 olan iki elemanımız vardır. 
Bu şekilde karşılaştırma işlemi devam eder. Karşılaştırılan sayıların arasına aşama aşama geçişi ifade etmek için de "|" işaretini kullanırız.
> **Dizimizin ilk hali: [22, 27, 16, 2, 18, 6] ve Insertion Sort aşamaları:**
![PatikaDev](/InsertionSortTable.jpg)
___________________________________
**2.Big-O gösterimini yazınız.**
> Best Case: O(^)
>>Average Case: O(n^2)
>>>Worst Case: O(n^2)   
>>>>Not: n.(n+1)/2 dominant olanı için O(n^2)'dir diyoruz.
_________________________________
**3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.**

Ekleme Sıralama (Insertion Sort) algoritmasının sınır durumu: 
* Öğeler ters sırada sıralanmışsa, eklemeli sıralamanın sıralanması en fazla zaman alır n.(n+1)/2
* Öğeler zaten sıralandığında minimum zaman alır (n Sırası)
**Bu durumda:** 
>Best Case: [2, 6, 16, 18, 22, 27]
Worst Case: [27, 22, 18, 16, 6, 2]  
____________________________________
**4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.**
>  Average case
____________________________________
**5.  [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**
![PatikaDev](/InsertionSortTable_2.jpg)
[Daha Fazla Bilgi: Insertion Sort Algoritma Analizi](https://www.youtube.com/watch?v=NnMSqZgvruM) : https://www.youtube.com/watch?v=NnMSqZgvruM

## Veri Yapıları ve Algoritmalar / Merge Sort Projesi
![PatikaDev](/MergeSort.png)
**1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.**
###Cevap:
Sıralama Algoritmasında birleştirme yöntemi uygulanmadan önce böl ve Yyönet tekniğini kullanırız. Bu yöntemle bir problemi alt problemlere böleriz. Her bir alt problemin çözümü hazır olduğunda, ana problemi çözmek için alt problemlerin sonuçlarını birleştiririz.
![PatikaDev](/MergeSortTable.jpg)
______________________________________
**2.Big-O gösterimini yazınız.**
>Best Case: O(n*logn)
>>Average Case: O(n*logn)
>>>Worst Case: O(n*logn) 

[Daha Fazla Bilgi: Merge sort algorithm](https://www.youtube.com/watch?v=TzeBrDU-JaY) : https://www.youtube.com/watch?v=TzeBrDU-JaY

## Veri Yapıları ve Algoritmalar / Binary Search Tree Projesi
![PatikaDev](/BinarySearchTree.jpg)
**Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.**
###Cevap:
İkili Arama Ağacı, düğüm tabanlı bir ikili ağaç veri yapısıdır.
İkili Arama Ağacı bazı özelliklere sahiptir. Bunlar: 
* Binary Search Tree'de en üstte bulunan node Root olarak adlandırılır.
* Root’tan küçük değere sahip olan node’lar Root’un sol tarafında yer alır
* Root’tan büyük değere sahip olan node’lar Root’un sağ tarafında yer alır.
![PatikaDev](/BinarySearchTreeTable.jpg)
[Daha Fazla Bilgi:Data structures-Binary Search Tree](https://www.youtube.com/watch?v=pYT9F8_LFTM) : https://www.youtube.com/watch?v=pYT9F8_LFTM 