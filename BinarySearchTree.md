
# Binary-Search-Tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

1. İlk aşamada root 7dir. 7'den küçük sayılar ağacın soluna, 7'den büyük sayılar ağacın soluna yerleşmelidir.

2. 5 < 7 olduğundan 5, 7'nin soluna yerleşmelidir.

3. 1<5<7 olduğundan 1, 5'in soluna yerleşmelidir.

4. 8>7 olduğundan 8, 7'nin sağına yerleşmelidir.

5. 3 < 5 < 7 & 3>1 olduğundan 3, 1'in sağına yerleşmelidir.

6. 6 < 7 < 7 & 6>5 olduğundan 6, 5'in sağına yerleşmelidir.

7. 0<1<5<7 olduğundan 0, 1'in soluna yerleşmelidir.

8. 9>7 & 9>8 olduğundan 9, 8'in sağına yerleşmelidir.

9. 4 < 5 < 7  & 4 > 3 > 1  olduğundan 4, 3'ün sağına yerleşmelidir.

10. 2 < 5 < 7  & 2 > 1 & 2 < 3  olduğundan 2, 3'ün soluna yerleşmelidir.



             7
	       /  \
          5    8
         / \    \
         1  6     9
        /  \
        0   3  
	       /  \
           2   4