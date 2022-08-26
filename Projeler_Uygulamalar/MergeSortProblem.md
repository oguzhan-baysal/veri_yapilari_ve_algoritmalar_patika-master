# Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

CEVAPLAR 
---
1)

Merge sort islemini gerceklestirmek icin ilk olarak dizimizi ikiye bolme islemi uygulayacagiz.

* 16 21 | 11 | 8 | 12 22 olarak en son bir hucrede bir sayi kalasiya kadar devam edecigiz

* 16 21 | 11 | 8 | 12 22 olarak devam ediyoruz

* 16 | 21 | 11 | 8 | 12 | 22 olarak tek hucreye kadar indik simdi siralamaya baslayacagiz.

* 16 21 | 8 11 | 12 22 
 
* 8 11 16 21 | 12 22 

* 8 11 12 16 21 22 olacak sekilde siralama islemini burada sonlandiriyoruz.

2 )
O(logn) 
