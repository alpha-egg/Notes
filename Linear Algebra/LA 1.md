第一次作业： 习题 1.1 2,3,4,6

# 行列式

## n 阶行列式的递归法定义

n 阶行列式是由 $n^{2}$ 个数 $a_{ij}$ （$i,j=1,2,\cdots ,n$）排成 n 行 n 列的算式

$$
D=\begin{vmatrix}
a_{11}&a_{12}&\cdots &a_{1n}\\
a_{21}&a_{22}&\cdots &a_{2n} \\
\vdots&\vdots&&\vdots \\
a_{31}&a_{32}&\cdots&a_{33}
\end{vmatrix}
$$


当 $n\geq 2$ 时，$D=a_{11}A_{11}+a_{12}A_{12}+\dots+a_{1n}A_{1n}=\sum_{j=1}^{n}a_{1j}A_{1j}$（按第一行展开）

定义