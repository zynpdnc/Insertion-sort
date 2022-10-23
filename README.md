# Insertion-sort

[22,27,16,2,18,6]
22|,27,16,2,18,6
22,27|,16,2,18,6
22,16,27|,2,18,6
16,22,27|,2,18,6
16,22,2,27|,18,6
16,2,22,27|,18,6
2,16,22,27|,18,6
2,16,22,18,27|,6
2,16,18,22,27|,6
2,16,18,22,6,27|
2,16,18,6,22,27|
2,16,6,18,22,27|
2,6,16,18,22,27| 


#soru 2
O(N^2)

#soru 3
Worst Case:
Küçükten büyüğe sıralanmak istenen bir dizinin tüm elemanlarının büyükten küçüğe sıralanmasıdır (reversed order).O(N x (N+1)) / 2 => O((N²+N)/2) => O(N²/2) => O(N²)
Best Case:
Küçükten büyüğe sıralamak istediğimiz bir dizinin elemanlarının zaten küçükten büyüğe sıralandığı durumdur.Dolayısıyla O(N)' dir.
Average Case: O(N²) + O(N) in ortalaması olacağı için yine N² cinsinden bir sonuç olur. Average case = O(N²)

#soru 5
[2,3,5,8,7,9,4,15,6] -> 2 ile 7 sayısı yer değiştirdi
[2,3,4,8,7,9,5,15,6] -> 5 ile 4 sayısı yer değiştirdi
[2,3,4,5,7,9,8,15,6] -> 8 ile 5 sayısı yer değiştirdi
[2,3,4,5,6,9,8,15,7] -> 6 ile 7 sayısı yer değiştirdi
