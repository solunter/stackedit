

在对如下一串Gamma matrix取trace时（D维下），会出现 直接带动量取trace与收缩Gamma matrix和动量得到的结果不一致
$$
(\gamma \cdot \text{l1}).\bar{\gamma }^7.(\gamma \cdot \text{q2}).(\gamma \cdot \text{q1}).\bar{\gamma }^5.(\gamma \cdot \text{q1}).(\gamma \cdot \text{l2}).\bar{\gamma }^5.(\gamma \cdot \text{q1})
$$
检查发现`DiracTrick`在化简Gamma chain时，直接以为
$$
Tr[A\cdot(\hat{\gamma} \cdot \hat{\text{q}})\cdot GammaChain \cdot (\bar{\gamma} \cdot \bar{\text{q}}) \cdot B] = 0.
$$
<!--more-->
其中A，GammaChain(4 or D-4)，B都是Gamma Matrix，$\hat{\gamma}$ means in D-4 dimension and $\bar{\gamma}$ means in 4 dimension. Trace above is not 0 at all! So the code must be modified. Original codes follows
> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzMjQ4MjMxMDVdfQ==
-->