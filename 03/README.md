## 习题2



根据等差数列的公式



等列公式 [1]  ：
$$
an=a1+(n-1)d ，（n为正整数）
$$


S1为首项，an为第n项的通项公式，d为公差。

前n项和公式为：
$$
Sn=na1+n(n-1)d/2，（n为正整数）
$$

$$
Sn=n(a1+an)/2，（n为正整数）
$$

若`n、m、p、q`均为正整数，

若`m+n=p+q`时，则：存在`am+an=ap+aq`

若`m+n=2p`时，则：`am+an=2ap`

也可推导得
$$
Sn=na1+nd(n-1)/2
$$


1+3+5+…199的解：

`An = 99`

`A1 = 1`

`n = ?` 

带入上面公式  得出  `n = 50` 



带入求和公式

`S(50) = 50(1+100)/2`



## 代码在index.py

```python
# encoding:utf-8

def sum(a1, an, n):
  d = 2
  return n * a1 + n * (n - 1) * d / 2

print sum(1,99,50)

```





