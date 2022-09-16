[16,21,11,8,12,22] -> Merge Sort

Soru-1)
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Cevap-1)
Aşama1: Dizi ikiye bölünür.-> [16,21,11] - [8,12,22]
Aşama2: Dizi tekrar ikiye bölünür.-> [16,21]-[11]-[8,12]-[22]
Aşama3: Her parçayı kendi içerisinde sıralıyoruz. -> [16,21]-[11]-[8,12]-[22]
Aşama4: İlk aşamadaki hallerine göre birleştir. -> [16,11,21]-[8,12,22]
Aşama5: Sıralı iki alt diziyi tek bir sıralı dizi olacak şekilde birleştirir. -> [8,11,12,16,21,22]


Soru-2)
Big-O gösterimini yazınız.

Cevap-2)
O(n log n) - n tane öğeyi ayrılır ve yeniden birleştirilir.
