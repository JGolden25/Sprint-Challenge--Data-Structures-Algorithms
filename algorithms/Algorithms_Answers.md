1. O(n) or linear time, n is only processed once in the equation.

a = 0
    while (a < n * n * n) # n^3
      a = a + n * n # n^2


1b. O(n^3) or quadratic time, every loop adds another n to process.
sum = 0
    for (i = 0; i < n; i++) #n
      for (j = i + 1; j < n; j++) #n
        for (k = j + 1; k < n; k++) #n
          for (l = k + 1; l < 10 + k; l++)
            sum++

1c. O(n) or linear time, it has to process every bunny until all bunnies have been processed. This looks like a recursive pattern to me. 

bunnyEars = function(bunnies) {
      if (bunnies == 0) return 0
      return 2 + bunnyEars(bunnies-1) #recursive
    }

2. A Binary Search Tree. I would test the middle floor of the building first. If it breaks, I would move down halfway from the middle floor and ground floor and test it there. At a floor that it doesn't break anymore, I would move up halfway between that floor and the last floor that it broke.