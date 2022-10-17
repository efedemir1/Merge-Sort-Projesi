# Merge Sort Projesi

## [16,21,11,8,12,22] -> Merge Sort

### Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. 

### 1. aşama dizi yazılır
[16,21,11,8,12,22]

### 2. aşama dizi ikiye ayrılır.
[16,21,11] V [8,12,22]

### 3. aşama diziler tekrardan ayrılır.
[16,21] , [11]  V  [8,12] , [22]

### 4. aşama ayrılan diziler küçükten büyüğe olcak şekilde birleştirilmeye başlanır.
[11,16,21] V  [8,12,22]

### 5. aşama küçükten büyüğe küçükten büyüğe olcak şekilde birleştirilmeye başlanır ve nihai dizi oluşturulur.

[8,11,12,21,22]

# 2. Big-O gösterimini yazınız.

Merge Sort türüne göre gösterilen dizilerde Big-O gösterimi O(nlogn) şeklinde ifade edilir. Dizide toplam da 6 adet eleman bulunduğundan dolayı O(6log6) şeklinde yazılabilir.
