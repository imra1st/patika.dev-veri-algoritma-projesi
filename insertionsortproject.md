[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1-)
[22|,27,16,2,18,6]

[22,27|,16,2,18,6]

[16,22,27|,2,18,6]

[2,16,22,27|,18,6]

[2,16,18,22,27|,6]

[2,6,16,18,22,27]


2-)
Big-O gösterimi: O(n^2)


3-)
Time Complexity:
Average Case: n(n-1) --> O(N^2)
Worst Case: [27,22,18,16,6,2]   
Best Case: [2,6,16,18,22,27]


4-)
18 sayısı dizinin tam ortasında bulunduğu için average case kapsamına girer.


5-)
[7,3,5,8,2,9,4,15,6]

[7|,3,5,8,2,9,4,15,6]

[3,7|,5,8,2,9,4,15,6]

[3,5,7|,8,2,9,4,15,6]

[3,5,7,8|,2,9,4,15,6]
