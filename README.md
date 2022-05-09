# Binary_Search_Tree_Project

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

1. Step = Root => 3
2. Step = 7 > 3 => y
3. Step = 5 > 3 => y, 5 < 7 => z
4. Step = 1 < 3 => z
5. Step = 8 > 3 => y, 8 > 7 => y
6. Step = 6 > 4 => y, 6 < 7 => z, 6 > 5 => y
7. Step = 0 < 3 => z, 0 < 1 => z
8. Step = 9 > 3 => y, 9 > 7 => y, 9 > 8 => y
9. Step = 4 > 3 => y, 4 < 7 => z, 4 < 5 => z
10. Step = 2 < 3 => z, 2 > 1 => y


                              3
                       1              7
                    0     2       5       8
                                4   6        9
