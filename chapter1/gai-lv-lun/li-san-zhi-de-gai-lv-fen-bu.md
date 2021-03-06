#离散值的概率分布
##二项分布
假设出现1的概率为p，且出现0的概率为q=1-p的独立随机变量$$Z_1,...,Z_n, X=Z_1 + .... + Z_n$$的分布就是一种二项分布。二项分布记为Bn(n, p)。
$$P(X=k)=C_n^kp^kq^{n-k}$$ 
期望值：$$E[X] = E[Z_1 + .... + Z_n] = np$$
方差：$$V[Z_t] = E[(Z_t-p)^2] = (1-p)^2p + (0-p)^2q = pq
V[X] = V[Z_1] + ... + V[Z_n] = npq = np(1-p)$$


##期望值与方差
###方差
$$V[Y] = V[X+c] = V[X]$$ ...增加常量c后，方差不变
$$V[Y] = V[cX] = c^2V[X]$$ ...乘以常量c后，方差变为原来的c^2倍
各项独立时，和的方差等于方差的和：$$V[X+Y] = V[X] + V[Y]$$

###标准化/归一化
假设$$E[X]=\mu, V[X]=\sigma^2 > 0$$, 只要令$$W=(x-\mu)/\sigma$$，就能得到E[X] = 0且V[W]=1。
###平方的期望值与方差
$$V[X] = E[X^2] - E[X]^2$$
$$E[X]=\mu, V[Y]=\sigma^2$$, 有$$E[(x-a)^2]=(\mu-a)^2+\sigma^2$$

证明：
![](/assets/variance.png)