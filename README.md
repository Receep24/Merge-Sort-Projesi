# Merge-Sort-Projesi [16,21,11,8,12,22] 
-Dizi ortadan ikiye bölünür : []16,21,11] ve [8,12,22] 
-Bu ayırma işlemi, alt diziler en çok iki elemanlı olana kadar devam eder. [16] [21,11] ve  [8,12] [22] olacak şekilde 
-Sonra diziler tek elemanlı olacak şekilde bölünür : [16] [21] [11]  ve [8] [12] [22] 
- Alt diziler kendi içinde küçükten büyüğe sıralanır : [16] [11,21] ve [8] [12,22]
- Daha sonra iki dizi kendi içlerinde sıralanır : [11][16][21] ve [8][12][22]
- Daha sonra diziler tekrar küçükten büyüğe sıralanacak seklinde birleştirilir : [8][11][12][16][21][22]

# Big-O gösterimini yazınız.
- O(nlogn)
