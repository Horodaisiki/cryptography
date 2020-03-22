# An algorithm for the k-error linear complexity of binary sequences with period $2^n$

- Intutive concepts of randomness do not insure cryptographic strength.

## Linear Complexity

#### Def 3.1:

The linear complexity of a sequence is the minimum number of stages of an LFSR that generates the sequence.

###### Ex: Cryptographic weak

$$
(s)=\underbrace{(0,0,...0,1)}_{n elements}
$$

So a new measure needs to be suggested.

#### Def 4.1:

The $k-error$ linear complesity of the periodic sequence
$$
(s)=(s_0,s_1,...,s_{n-1})
$$
denoted $c_k(s)$, is the smallest linear complexity that can be obtained when any $k$ or fewer of the $s_i$’s are altered.



If we use B-M or C-G to compute $k-error$ linear complexity, it will be prohibitively high. Before introducing S-M, briefly discuss C-G algorithm.

#### C-G Algorithm

![image-20200322102518830](C:%5CUsers%5C%E5%85%B3%E5%87%AF%E5%AE%81%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20200322102518830.png)

#### S-M Algorithm

![image-20200322102938142](C:%5CUsers%5C%E5%85%B3%E5%87%AF%E5%AE%81%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20200322102938142.png)

![image-20200322102953818](C:%5CUsers%5C%E5%85%B3%E5%87%AF%E5%AE%81%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20200322102953818.png)

###### Ex : S-M for $(s)$ and $k=2$

![image-20200322103040401](C:%5CUsers%5C%E5%85%B3%E5%87%AF%E5%AE%81%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20200322103040401.png)