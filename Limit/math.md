### Problem 1
**难度** <font color=yellow>medium</font>

$$\Large\lim\limits_{n\rightarrow\infty} n^2\left(\sqrt[n]{a}-\sqrt[n+1]{a}\right) \qquad a>0$$

**解法一**  
利用等价无穷小，$a^{\frac{1}{n}-\frac{1}{n+1}} - 1 \sim \left(\frac{1}{n}-\frac{1}{n+1}\right) \ln a$

**解法二**  
形式入手，$\left(\sqrt[n]{a}-\sqrt[n+1]{a}\right)$ 联想到拉格朗日中值定理。取区间 $\left[ \frac{1}{n+1}, \frac{1}{n} \right]$，对函数 $a^x$ 使用拉格朗日中值定理，有 $\left(\sqrt[n]{a}-\sqrt[n+1]{a}\right) = a^{\xi_n} \ln a \cdot \left(\frac{1}{n}-\frac{1}{n+1}\right)$，其中 $\frac{1}{n} < \xi_n < \frac{1}{n+1}$，于是当 $n \rightarrow \infty$ 时，$\xi_n \rightarrow 0$，原极限即为 $\ln a$

### Problem 2

**难度** <font color=yellow>medium</font>

$$\Large \lim\limits_{n\rightarrow\infty} \sum_{k=n^2}^{\left(n +1\right)^2} \frac{1}{\sqrt{k}}$$

### Problem 3

**难度** <font color=red>hard</font>

$$\Large \lim\limits_{n\rightarrow\infty} \frac{2^3-1}{2^3+1} \cdot \frac{3^3-1}{3^3+1}\cdots\frac{n^3-1}{n^3+1}$$

### Problem 4

**难度** <font color=yellow>medium</font>

$$
\Large \lim\limits_{n\rightarrow\infty} \sqrt[n]{\ln n}
$$