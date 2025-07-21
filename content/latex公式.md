## 希腊字母
- $\alpha$ `\alpha`
- $\beta$ `\beta`
- $\gamma$ `\gamma`
- $\theta$ `\theta`
- $\varepsilon$ `\varepsilon`
- $\delta$ `\delta`
- $\Delta$ `\Delta`
- $\mu$ `\mu`
- $\xi$ `\xi`
- $\omega$ `\omega`
- $\Omega$ `\Omega`
- $\rho$ `\rho`
- $\sigma$ `\sigma`
- $\eta$ `\eta`
- $\varphi$ `\varphi`
- $\phi$ `\phi`
- $\Phi$ `\Phi`
- $\lambda$ `\lambda`
## 运算符
- $\times$ `\times`
- $\pm$ `\pm`
- $\cdot$ `\cdot`
- $\ast$ `\ast`
- $\sqrt[n]{ x }$ `\sqrt[n]{x}`
- $\sum$ `\sum`
- $\prod$ `prod`
- $\int$ `int`
- $\oint$ `oint`
- $\iint$ `\iint`
- $\leq$ `\leq`
- $\geq$ `\geq`
- $\ll$ `\ll`
- $\gg$ `gg`
- $\equiv$ `equiv`
- $\approx$ `approx`
- $\sim$ `\sim`
- $\in$ `\in`
- $\notin$ `\notin`
- $\mid$ `mid`

## 数学模式重音符
- $\hat{a}$ `\hat{a}`
- $\bar{a}$ `\bar{a}`
- $\vec{a}$ `\vec{a}`
- $\dot{a}$ `\dot{a}`
- $\mathring{U}$ `\mathring{U}`
## 箭头
- $\leftarrow$ `\leftarrow`
- $\rightarrow$ `\rightarrow`
- $\longleftarrow$ `\longleftarrow`
- $\longrightarrow$ `\longrightarrow`
- $\Leftarrow$ `\Leftarrow`
- $\Rightarrow$ `\Rightarrow`
- $\iff$ `\iff`
## 大尺寸括号
- $\left(\right)$ `\left( \right)`
- $\left[ \right]$ `\\left[ \right]`
## 其他常见符号
- $\forall$ `\forall`
- $\exists$ `\exists`
- $\infty$ `\infty`
- $\boldsymbol{a}$ `\boldsymbol{a}`
- $\partial$ `\partial`
## 数学公式写法
- 分数 $\frac{1}{2}$ `\frac{a}{b}`
- 插入文字 $\text{hello,world!}$ `\text{hello,world!}`
### 常见函数
$\lim_{ x \to \infty }$ `\lim_{x \to \infty}`
### 矩阵、行列式
`&` 表示分隔元素，`\\` 表示换行
$$
A = 
\begin{pmatrix}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{pmatrix}
$$
```latex
A=
\begin{pmatrix}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{pmatrix}
```
$$
A = 
\begin{Bmatrix}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{Bmatrix}
$$
```latex
A = 
\begin{Bmatrix}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{Bmatrix}
```
$$
A = 
\begin{vmatrix}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{vmatrix}
$$
```latex
A = 
\begin{vmatrix}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{vmatrix}
```
$$
A=
\begin{matrix}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{matrix}
$$
```latex
A=
\begin{matrix}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{matrix}
```
### 多行公式对齐
使用 `\begin{split} \end{split}`，在需要对齐的地方添加 `&` 符号，注意需要用 `\\` 来换行。
$$
\begin{split}
f(x) &= a+1 \\
f(y) &= a+b+c\\
&=ac-10
\end{split}
$$
```latex
\begin{split}
f(x) &= a+1 \\
f(y) &= a+b+c\\
&=ac-10
\end{split}
```
### 方程组
使用 `\begin{cases} \end{cases}`
$$
\begin{cases}
x+1=0\\ \\
y+1=2
\end{cases}
$$
$$
\text{Decision Boundary}=
\begin{cases}
x,&x<3\\
2x,&x=3 \\
4x,&x>3
\end{cases}
$$
```latex
\text{Decision Boundary}=
\begin{cases}
x,&x<3\\
2x,&x=3 \\
4x,&x>3
\end{cases}
```


