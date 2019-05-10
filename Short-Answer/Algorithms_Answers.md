Add your answers to the Algorithms exercises here.

## Exercise I Answers


A) O(n). The loop is dependent on the value of n. We will continue to have n operations as the number of n grows.

```
a)  a = 0
    while (a < n * n * n):      # O(n)
      a = a + n * n
```

B) O(n^3). Snippet b contains nested loops. You can determine this from giving a count of the for-loops by the number of operators within each loop.

```
b)  sum = 0
    for i in range(n):      # O(n)
      i += 1
      for j in range(i + 1, n):     # O(n)
        j += 1
        for k in range(j + 1, n):       # O(n)
          k += 1
          for l in range(k + 1, 10 + k):        # No n
            l += 1
            sum += 1
```

C) O(2^n). This is a recursive algorithm. It is solving a problem of size n by recursively solving a smaller problem of size n-1.

## Exercise 2 Answers

