Given a number of days n (1 ≤ n ≤ 10), print all possible sequences of daily activities using the set: {"Swimming", "Running", "Football"}.


**Constraint:** No two consecutive days can have the same activity.


**Example** run with n = 2.

**Input: 2**

**Output:**

Football Running  
Football Swimming  
Running Football  
Running Swimming  
Swimming Football  
Swimming Running  
COUNT: 6


**The total number of valid schedules is given by:**
COUNT = 3 × 2^(n - 1)

**Examples:**
- n = 1 → COUNT = 3  
- n = 2 → COUNT = 6  
- n = 3 → COUNT = 12  
- n = 10 → COUNT = 1536  


**Name :** Razan Dwekat  
**ID :** razan2003.dw@gmail.com

