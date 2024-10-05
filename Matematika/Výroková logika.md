Výrok je gramatická věta, u které se dá určit pravdivost
Výrok spojujeme pomocí logických spojek
Negace (¬)

|  A  |  B  |    A∧B    |    AvB    |     A=>B     |       A<=>B       |
| :-: | :-: | :-------: | :-------: | :----------: | :---------------: |
|  -  |  -  | Konjunkce | Disjunkce |  Implikace   |    Ekvivalence    |
|  -  |  -  |    AND    |    OR     | If A, then B | A is only if B is |
|  0  |  0  |     0     |     0     |      1       |         1         |
|  0  |  1  |     0     |     1     |      1       |         0         |
|  1  |  0  |     0     |     1     |      0       |         0         |
|  1  |  1  |     1     |     1     |      1       |         1         |
Tautologie -> Složený výrok, který je vždy pravdivý
Kontradikce -> Složený výrok, který je vždy **ne**pravdivý
Kontingence -> Složený výrok, který **není** kontradikce

**Negace spojek**
Negace konjunkce
$$
\neg (A\wedge B)=(\neg A\lor \neg B)
$$
Negace Disjunkce
$$\neg(A\wedge B) = (\neg A \lor \neg B)$$
Negace Implikace
$$\neg (A\implies B)=(A\lor\neg B)$$
Negace Ekvivalence
$$\neg(A\iff B)=(A\wedge \neg B) \lor(\neg A\wedge B)$$
