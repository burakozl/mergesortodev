# www.patika.dev Veri yapıları ve Algoritmalar eğitimi kapsamında hazırlamış olduğum ödev-2

# [16,21,11,8,12,22] -> Merge Sort
## [16,21,11]--[8,12,22] -> ortadan 2ye bölüyoruz 
## [16,21] [11]--------[8,12] [22] ->sağ ve sol tarafı kendi içinde bölmeye devam ediyoruz
## [16]-[21] [11] -----[8]-[12] [22] ->bölme işlemi bittikten sonra kendi içinde sıralamayarak birleştiriyoruz
## [16,21] [11] --------[8,12] [22]
## [11,16,21] --------- [8,12,22] -> sağ ve sol tarafların sıralama işlemi bittikten sonra en soldaki index elemanlarını kıyaslayarak dizimizi birleştiriyoruz.
## [8,11,12,16,21,22] -> End

# A-2) Big O gösterimi 
## 2^x =n => x=log(n) => n adet kadar bu işlem yapılacağından =>n*logn => O(nlogn)
# A-3) 
## Worst Case   : O(nlogn)
## Average Case : O(nlogn)
## Best Case    : O(nlogn)
