# SORU 1 
# [22,27,16,2,18,6] -> Insertion Sort
# Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

**Çözüm :**
1. Adım : ***İlk Eleman***  [22,27,16,2,18,6]
   - Solunda herhangi bir dize olmadığı için direk ilk sırada yer alır.
   - Bu bizim başlangıç dizemiz olduğu için sıra yerini koruyacaktır.
2. Adım : ***2 Eleman*** [22,27,16,2,18,6]
   - İkinci dize solundaki dizeyle karşılaştırılır.
   - 27 sayısı 22 den büyük olduğu için ikinci sırada yer alır.
3. Adım : ***3 Eleman*** [16,22,27,2,18,6]
   - Üçüncü dize solundaki dizelerle karşılaştırılır.
   - 16 sayısı 27 ve 22 den büyük olduğu için ilk dizeye yerleştirilir.
4. Adım : ***4 Eleman*** [2,16,22,27,18,6]
   - Dördüncü dize solundaki dizelerle karşılaştırılır.
   - 2 sayısı solundaki dizelerin en küçüğü olduğu için birinci sıraya yerleştirilir.  
5. Adım : ***5 Eleman*** [2,16,18,22,27,6]
   - Beşinci dize solundaki dizelerle karşılaştırılır.
   - 18 sayısı 2 ve 16 dan büyük, 22 ve 27 den küçük olup üçüncü sıraya yerleştirilir.
6. Adım : ***6 Eleman*** [2,6,16,18,22,27]
   - Altıncı dize solundaki dizelerle karşılaştırılır.
   - 6 sayısı 2 den büyük ve geri kalan sayılardan küçük olduğu için ikinci sıraya yerleştirilir.
  
 DİZİNİN SON HALİ 6. ADIMLA SONLANMIŞ OLUR.   [2,6,16,18,22,27]


 # SORU 2 
 # Big-O gösterimini yazınız.
 
 **Çözüm :**
 İlk adım n olacağından dolayı sonraki adımlar n-1 , n-2 .. şeklinde gidecektir ve +1 ile sonlanacaktır.
 Bu sayıların toplamının ( n*(n+1)/2) şeklinde formülü var idi. Bu da  O(n²) ile ifade edilir.


# SORU 3 
# Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

**Çözüm :**
Tamamlanan dizemiz [2,6,16,18,22,27] olduğundan dolayı 18 sayısı ortada yer aldığı için Time Complexitymiz Average Case'dir.



# SORU 4 
#  [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

**Çözüm :**
1. Adım : ***İlk Eleman***  [2,3,5,8,7,9,4,15,6]
   - İlk olarak dizedeki en küçük sayı aranarak birinci sıraya yerleştirilir.
   - Dizedeki en küçük sayı 2 olduğundan 7 ile yer değiştirilerek yazılır.
2. Adım : ***2 Eleman*** [2,3,5,8,7,9,4,15,6]
   - İkinci dizeden itibaren en küçük sayı aranır.
   - Burada 3 sayısı en küçük olduğundan dolayı yerinde kalır ve dize değişmez.
3. Adım : ***3 Eleman*** [2,3,4,8,7,9,5,15,6]
   - Üçüncü dizeden itibaren en küçük sayı aranır.
   - Buradaki 4 sayısı en küçük sayı olduğundan dolayı 5 ile yer değiştirilir.
4. Adım : ***4 Eleman*** [2,3,4,5,7,9,8,5,6]
   - Dördüncü  dizeden itibaren en küçük sayı aranır
   - 5 sayısı dizedeki en küçük sayı olduğundan dolayı 8 ile yer değiştirilir.

İlk 4 adımdaki dize sırası [2,3,4,5,7,9,8,5,6] şeklinde olur.
