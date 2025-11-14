# New Practice Questions

| ID | Question Name                  | Description                                                                                           | Testcases                                     | Answers                    |
|----|--------------------------------|-------------------------------------------------------------------------------------------------------|------------------------------------------------|-----------------------------|
| 1  | Spiral Layer Sum               | Given an n×n matrix, return the sum of elements in the **outermost spiral ring**.                     | [[1,2,3],[4,5,6],[7,8,9]]                      | 1+2+3+6+9+8+7+4 = 40        |
| 2  | Digit Flip Symmetry            | A number is symmetric if flipping every digit upside-down (6↔9, 0↔0, 8↔8, others invalid) produces the **reverse** of the original number. | 9069 | true |
| 3  | Pascal Even Count              | Generate first `n` rows of Pascal’s Triangle and count how many numbers in it are **even**.           | n = 5                                         | 6                          |
| 4  | Closest Empty Slot             | Given seats (0 empty, 1 filled), return index of empty slot **closest to the nearest filled seat**.    | [1,0,0,1,0]                                   | 1                          |
| 5  | Consonant Shift Cipher         | Replace each consonant with the next consonant alphabetically (b→c, c→d, …, z→b), vowels stay same.    | "hack"                                        | "jbdl"                     |
| 6  | Half-Sorted Permutation Count  | Count permutations of array nums such that the **first half is increasing** and **second half decreasing**. | [1,2,3] | 1 (only [1,3,2]) |
| 7  | Ancient Block Numerals         | Convert integer to new system where blocks = {A=2, B=3, C=7, D=20}. Write number using **minimum blocks**. | 13 | C B A (7+3+2+1? But A=2 → 7+3+2+1? Actually 7+3+2+1 invalid → try: C + B + A = 7+3+2 = 12; need 1 but no 1 → invalid → answer: impossible) |
| 8  | Tallest Pair Product           | Pick two different numbers whose **product is maximum**.                                               | [3,7,2,9]                                     | 63                         |
| 9  | Longest Balanced Genome        | Return longest substring where count(A)=count(T) AND count(G)=count(C).                               | "ATGCAT"                                      | 6                          |
| 10 | Middle of Three Sorted Lists   | Merge **three** sorted arrays and return the **middle element**.                                      | [1,4], [2,5], [3,6]                            | 3                          |
