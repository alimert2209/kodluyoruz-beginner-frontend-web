# Proje 1
[22,27,16,2,18,6] -> Insertion Sort

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.
- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


---> [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

<hr>

Dizinin ikinci elemanı başlangıç elemanı olarak seçilir. (27)
Daha sonra 27 ile 22 kıyaslanır. 27 > 22 olduğu için swap işlemi yapılmaz.

Üçüncü eleman (16) seçilir ve 27 ile kıyaslanır. 16 < 27 ve 16 < 22 olduğu için swap işlemi yapılır ve 16 en başa alınır. 
Dizinin yeni hali --> [16,22,27,2,18,6]

Dördüncü eleman (2) seçilir ve kendisinden büyük bir eleman ile karşılaşana kadar kendisinden önceki dizi elemanları ile kıyaslanır. Dolayısıyla en başa geçer.
Dizinin yeni hali --> [2,16,22,27,18,6]

Beşinci eleman (18) seçilir ve kendisinden büyük bir eleman ile karşılaşana kadar kendisinden önceki dizi elemanları ile kıyaslanır.
Dizinin yeni hali --> [2,16,18,22,27,6]

Son eleman (6) seçilir ve kendisinden büyük bir eleman ile karşılaşana kadar kendisinden önceki dizi elemanları ile kıyaslanır ve uygun yere yerleşir.
Dizinin yeni hali --> [2,6,16,18,22,27]

<hr>

Insertion Sort Big-Oh(n^2)

<hr>

Dizi sıralandıktan sonra 18 sayısı dizinin ortalarına yakın olduğu için average case durumuna girer.

<hr>

[7,3,5,8,2,9,4,15,6]

1. Adım: [3,7,5,8,2,9,4,15,6]
2. Adım: [3,5,7,8,2,9,4,15,6]
3. Adım: [3,5,7,8,2,9,4,15,6]
4. Adım: [2,3,5,7,8,9,4,15,6]
