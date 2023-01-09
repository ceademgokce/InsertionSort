#Veri Yapiları ve Algortima Ödev
#Soru
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

* Average case: Aradığımız sayının ortada olması
* Worst case: Aradığımız sayının sonda olması
* Best case: Aradığımız sayının dizinin en başında olması.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

#Cevabım
 [22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamaları 

- ilk önce dizide en kücük olan sayıyı buluyoruz ve daha sonra en basa yazıyoruz
son durum : [2,27,16,22,18,6]

- ilk en kücük sayımızı bulup basa yazdıktan sonra diğer en kücük sayıyı bulup yazıyoruz
son durum : [2,6,16,22,18,27]

- burada 1 ve 2 asamadan sonra en kücük sayımız yerinde olduğu için aynı durumda kalıyor              
son durum : [2,6,16,22,18,27]

- 4'üncü en kücük sayımızıda bulup yerlestiriyoruz
son durum : [2,6,16,18,22,27]

- 5 ve 6 sayılarım sıralamaya uyduğu için değisim yapmıyoruz
son durum : [2,6,16,18,22,27]

big o gösterimi : O(logn) ,  aradığımız sayı ortada olduğundan Avarege Case'dir.


### 2. verilen dizinin sıralaması
1 - [2,3,5,8,7,9,4,15,6]
2 - [2,3,4,8,7,9,5,15,6]
3 - [2,3,4,5,7,9,8,15,6]
4 - [2,3,4,5,6,9,8,15,7]

end;