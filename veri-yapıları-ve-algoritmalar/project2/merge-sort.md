### Problem

<hr>

[16,21,11,8,12,22]

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

### Çözüm

<hr>

- Sort türüne göre aşamalar:

            [16, 21, 11, 8, 12, 22]
            /                \
        [16|21|11]        [8|12|22]
           /    \          /    \
         [16|21] [11]    [8] [12|22]
           /  \    \      /   /   \
        [16] [21] [11]  [8] [12] [22]
           \    \  /       \  /   /
          [11|16|21]      [8|12|22]
                    \    /
                [8|11|12|16|21|22]

- Big-O notation gösterimi: O(logn)
