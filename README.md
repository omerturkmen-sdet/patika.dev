# patika.dev

Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2-Big-O gösterimini yazını
3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.



Cevaplar
[22,27,16,2,18,6] -> Insertion Sort

1 -Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
    İnsertion Sort türünde dizideki en küçük sayı taranıp alınır. En baştaki sayı ile en küçük sayı yer değiştirir. Bu işlem sayı dizisi tamamen sıralanana kadar devam eder.
    [2,27,16,22,18,6]   -->  Dizideki en küçük sayı olan 2'yi dizinin başına alabilmek için en                                baştaki sayı olan 22 ile yer değiştiriliyor.
    [2,6,16,22,18,27]
    [2,6,16,18,22,27]   --> Dizideki bütün elemanlar sıralı hale geldi ve sort işlemi bitti.
    
2 - Big-O gösterimini yazınız.
    Insertion sort işleminde yukarıdaki örnekte de görüldüğü gibi öncelikle dizideki en küçük eleman aranır daha sonra bu eleman en başa alınır ve aynı işlem kalan elemanlara uygulanır. Bunu ifade etmek gerekirse en küçük elemanı bulabilmek için n tane eleman kontrol edilir ve yer değiştirme yapılır. Daha sonra kalan elemanların hepsi (n-1) kontrol edilir. Bu şekilde devam eden işlemi n.(n-1).(n-2)....1 şeklinde ifade ederiz. Bu da n den 1'e kadar olan sayıların toplamına yani (n*(n+1))/2'ye eşittir. Big-O gösteriminde katsayı önemli olmadığı için O(n^2) şeklinde ifade edilir.
    
    
3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
    Dizinin sıralı hali [2,6,16,18,22,27]. Bu haldeyken 18 sayısı dizinin ortasında olduğu için Average Case durumundadır.
    
    
5 - [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
    -  [2,3,5,8,7,9,4,15,6]
    -  [2,3,5,8,7,9,4,15,6]
    -  [2,3,4,8,7,9,5,15,6]
    -  [2,3,4,5,7,9,8,15,6]
