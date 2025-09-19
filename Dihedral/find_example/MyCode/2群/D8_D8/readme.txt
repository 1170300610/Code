这里indexsOfExactProduct2的i是用的
list := SmallGroups(4*n*m,func<G|not IsAbelian(G) and IsSolvable(G)>);

所以要用同样的list才行