### Problem

<hr>

[22,27,16,2,18,6] -> Insertion Sort

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

- Big-O gösterimini yazınız.

- Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

- Average case
- Worst case
- Best case

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

### Çözüm

<hr>

- Sort türüne göre aşamalar:

n = [22, 27, 16, 2, 18, 6]
n-1 = [2, 27, 16, 22, 18, 6]
n-2 = [2, 6, 16, 22, 18, 27]
n-3 = [2, 6, 16, 18, 22, 27]

- Big-O notation gösterimi:

n.(n+1)/2 = O(n^2)

- Time Complexity:

18 sayısı dizinin ortasında yer aldığı için "Average Case" kapsamına girer.

- Selection Sort'a göre ilk 4 adım:

1. [2, 3, 5, 8, 7, 9, 4, 15, 6]
2. [2, 3, 4, 8, 7, 9, 5, 15, 6]
3. [2, 3, 4, 5, 7, 9, 8, 15, 6]
4. [2, 3, 4, 5, 6, 9, 8, 15, 7]
