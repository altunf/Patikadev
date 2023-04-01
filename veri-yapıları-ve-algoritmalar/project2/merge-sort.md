Problem:

[16,21,11,8,12,22]

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

Çözüm:

- Sort türüne göre aşamalar:

          [16,21,11,8,12,22]             n
          /                \

  [16|21|11] [8|12|22] n/2
  / \ / \
   [16|21] [11] [8] [12|22] n/4
  / \ \ / / \
   [16] [21] [11] [8] [12] [22] n/6
  \ | / \ | / .
  [11|16|21] [8|12|22] .
  \ / .
  [8|11|12|16|21|22] .

- Big-O notation gösterimi: O(logn)
