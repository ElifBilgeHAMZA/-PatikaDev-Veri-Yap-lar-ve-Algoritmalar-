# -PatikaDev-Veri-Yapilari-ve-Algoritmalar- 

 Insertion Sort Projesi
 
* I. Soru 
 
 [22,27,16,2,18,6] -> Insertion Sort
 
 Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
 
 Dizinin ikinci elemanı başlangıç elemanıdır. 22, 27 den küçüktür bu sebeple değişme olmaz.
 
 [22,27,16,2,18,6]
 
 Şu aşamada  27, 16 dan küçük olduğundan yer değiştirecekler
 
 [22,16,27,2,18,6]
 
 22, 16 dan büyük olduğundan yer değiştirecekler.
 
 [16,22,27,2,18,6]
 
 İkinci Aşama
 
 Bu adımda sıra dördüncü eleman olan 2'ye bakıyoruz. Hepsinden daha küçük olduğu için tekrar tekrar yer değiştirir en sola yerleşir.
 
 [16,22,27,2,18,6]
 
 [16,22,2,27,18,6]
 
 [16,2,22,27,18,6]
 
 [2,16,22,27,18,6]
 
* II. Soru

Big O Notation Gösterimini yazınız.

Worst Case: O(n²) = n+(n-1)+(n-2)....+1

Average Case: O(n²)

Best Case: O(n)

* III. Soru

Time Complexity: Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

Worst Case: [27,22,18,16,6,2]

Best Case: [2,6,16,18,22,27]

* IV. Soru

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Önce küçükten büyüğe sıralanır [2,6,16,18,22,27]
18 sayısı bu dizinin ortasında average case i olur

V. Soru

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[2|,3,5,8,7,9,4,15,6]

[2,3|,5,8,7,9,4,15,6]

[2,3,4|,8,7,9,5,15,6]

[2,3,4,5|,7,9,8,15,6]




www.patika.dev






 
  
 
 








 
