# Patika.dev - Insertion Sort Project
```
## [22,27,16,2,18,6] -> Insertion Sort 
```

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
```
*=sorted
[22,27,16,2,18,6]
[2*,27,16,22,18,6]
[2*,6*,16,22,18,27]
[2*,6*,16*,22,18,27]  -> değişim yok
[2*,6*,16*,18*,22,27]
[2*,6*,16*,18*,22*,27*] -> değişim yok
```
2. Big-O gösterimini yazınız.
```
O(n^2)
```
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
```
Average case: O(n^2)
Best case: O(1) -> best case olduğu takdirde tek atarız
Worst case: O(n^2)
```
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
```
Average case.
```
