## Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

---
### Soru-1
---
1-Dizinin 0. ve 1. indisini aliyoruz . Bunlar sirali oldugundan dolayi diger elemetlere gecis yapiyoruz. (22 ve 27) ↓
* 22 27 16 2 18 6 
2-Dizinin 1. ve 2. indisine gelip bunlari siralamaya basliyoruz . ↓
* 22 16 27 2 18 6 
2-Daha sonrasinda 16 ve 22 arasinda sorting islemini uygulamaya devam ediyoruz . ↓
* 16 22 27 2 18 6  
3-Daha sonrasinda dizinin 2. indisi ve 3. indisi arasinda siralamaya basliyoruz . ↓
*  16 22 2 27 18 6 
4-Dizinin tekrardan siralanmasina devam ediyoruz.↓
* 2 16 22 27 18 6  
5-Daha sonrasinda dizinin 3. indisi ve 4. indisi arasinda siralamayi gerceklestiriyoruz .↓
* 2 16 22 18 27 6 
6-Daha sonrasinda tekrardan 22 ve 18 ondan sonra 16 ce 18 arasinda logic mantiga devam ediyoruz . ↓
* 2 16 18 22 27 6 
7-Dizimizin 4. indisi ve 5. indisi arasinda siralamayi gerceklestiriyoruz.↓
* 2 16 18 22 6 27 
8- Tekrardan siralama islemini diziminizin 3. ve 4. indisi arasinda devam ediyoruz.
* 2 16 18 6 22 27 
9-Tekrardan siralama islemine devam ediyoruz . ↓
* 2 16 6 18 22 27 
10-Tekrardan siralama islemine devam ediyoruz .↓
* 2 6 16 18 22 27 
Insertion siralama islemi tamamlanmis bulunmaktadir..

---

### Soru-2
---
O(n^2) gosterimi seklinde gosterilmektedir .

## Soru-3 
---

Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?

Avarage Case olarak kullanilmaktadir .

## Soru-4
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1-[3 7 5 8 2 9 4 15 6 ]
2-[3 5 7 8 2 9 4 15 6 ]
3-[2 3 4 5 7 8 9 15 6 ]
4-[2 3 4 5 6 7 8  9 15]

Olmak uzere insertion sort islemi gerceklesmistir.







