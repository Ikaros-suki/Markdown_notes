#��ѧ��ʽ֧��

Markdown ����ѧ��ʽ�����˴󲿷ֵ� Latex �﷨

���ڹ�ʽ: 

��λԲ $x^2+y^2=1$

��ʽ��:

$$
\begin{cases}
x=\rho\cos\theta \\
y=\rho\sin\theta \\
\end{cases}
$$

==VSCode ���ŷǳ���ݺ��õ��Զ���ȫ����==

---

### 1.�ϱ����±�

�ϱ� $ x^2 + y^{12} = 1 $

�±� $x_1 + y_{12} = 1$

$ x^{-1}  $

$ \alpha_1,\alpha_2,\cdots,\alpha_n $

![](image/2022-02-23-19-18-44.png)

---

### 2.��ʽ

��С�������з��� $\frac{1}{2}$

չʾ�͵ķ�ʽ $\displaystyle\frac{x+1}{x-1}$

==���� \displaystyle ���ڽ�����չʾתΪ��״չʾ.==

$ \frac{x+1}{x-1} $

$ \displaystyle\frac{x + 1}{x - 1} $

![](image/2022-02-23-19-22-20.png)

---

### 3.��ʽ

��ƽ�� $\sqrt{2}$

�� $n$ �η� $\sqrt[n]{2}$

![](image/2022-02-23-19-23-59.png)

---

### 4.�ո�

���� $a\!b$

û�пո� $ab$

С�ո� $a\,b$

�еȿո� $a\;b$

��ո� $a\ b$

quad �ո� $a\quad b$

���� quad �ո� $a\qquad b$

---

### 5. �ۼ�, �۳˺ͻ���

�ۼ� $\sum_{k=1}^n\frac{1}{k}  \quad  \displaystyle\sum_{k=1}^n\frac{1}{k}$
<!--\\sum ����, n Ϊ�ϱ� ��^���,  -->
$ \sum_{i=1}^ni^2+\sqrt[3]{i} $

---


�۳� $\prod_{k=1}^n\frac{1}{k}  \quad  \displaystyle\prod_{k=1}^n\frac{1}{k}$
<!-- \\prod -->
---

���� $\displaystyle \int_0^1x{\rm d}x  \quad  \iint_{D_{xy}}  \quad  \iiint_{\Omega_{xyz}}$

$ \int $ ���ǻ��ֺ�

$ \lim_{x\to \infty}\frac{1}{x} $

![](image/2022-02-23-19-33-35.png)

---

### 6. ��������

==�� \left �� \right ���������������ڲ���С==

Բ���� $\displaystyle \left(\sum_{k=1}^{n}\frac{1}{k} \right)^2$

������ $\displaystyle \left[\sum_{k=1}^{n}\frac{1}{k} \right]^2$

������ $\displaystyle \left\{\sum_{k=1}^{n}\frac{1}{k} \right\}^2$

������ $\displaystyle \left\langle\sum_{k=1}^{n}\frac{1}{k} \right\rangle^2$

$ \langle \rangle  \quad  \{\} \quad \left(  \right)  \quad $

$ \left[ \right] \quad  $



![](image/2022-02-23-19-42-58.png)

---

### 7. ������ʽ����

����:

$$
\begin{aligned}
y &=(x+5)^2-(x+1)^2 \\
&=(x^2+10x+25)-(x^2+2x+1) \\
&=8x+24 \\
\end{aligned}
$$

�����:

$
\begin{aligned}
y &=(x+5)^2-(x+1)^2 \\
&=(x^2+10x+25)-(x^2+2x+1) \\
&=8x+24 \\
\end{aligned}
$

$
\begin{aligned}
x+1 \\
\end{aligned}
$

![](image/2022-02-23-19-50-50.png)

---

### 8. ������

$$
\begin{cases}
k_{11}x_1+k_{12}x_2+\cdots+k_{1n}x_n=b_1 \\
k_{21}x_1+k_{22}x_2+\cdots+k_{2n}x_n=b_2 \\
\cdots \\
k_{n1}x_1+k_{n2}x_2+\cdots+k_{nn}x_n=b_n \\
\end{cases}
$$

$
\begin{cases}
11 \\
20 \\
222\\
2032\\
\end{cases}
$

![](image/2022-02-23-19-52-31.png)

---


### 9. ����

����:

$$
\begin{pmatrix}
1 & 1 & \cdots & 1 \\
1 & 1 & \cdots & 1 \\
\vdots & \vdots & \ddots & \vdots \\
1 & 1 & \cdots & 1 \\
\end{pmatrix}
$$



$$
\begin{bmatrix}
1 & 1 & \cdots & 1 \\
1 & 1 & \cdots & 1 \\
\vdots & \vdots & \ddots & \vdots \\
1 & 1 & \cdots & 1 \\
\end{bmatrix}
$$ 

����ʽ: 

$$
\begin{vmatrix}
1 & 1 & \cdots & 1 \\
1 & 1 & \cdots & 1 \\
\vdots & \vdots & \ddots & \vdots \\
1 & 1 & \cdots & 1 \\
\end{vmatrix}
$$

![](image/2022-02-23-19-56-13.png)

---

### 10. �����ַ�

����������ſ��� ������ѯ

�������� ��**Latex ���ű�**��

---

### 11. ��ʽ���������

$$
x+2 \tag{1.2}
$$

$$
\begin{equation}
x^n+y^n=z^n
\end{equation}
$$

�ɹ�ʽ $(1.2)$ �ɵõ�����

---

### 12. �������Ҫ�﷨

* ��� $\cdot$, ��� $\times$, ��� $\otimes$, ֱ�� $\oplus$, �Ӽ� $\pm$, ���� $\circ$.
* 
* С�ڵ��� $\leq$, ���ڵ��� $\geq$, ���� $\neq$, ��� $\equiv$, Լ�� $\approx$, �ȼ� $\cong$, ���� $\sim$, ���Ƶ��� $\simeq$, ��� $\doteq$.
* 
* �߼��� $\land$, �߼��� $\lor$, �߼��� $\lnot$, �̺� $\to$, �ȼ� $\leftrightarrow$.
* 
* ��Ϊ $\because$, ���� $\therefore$, ���� $\exist$, ���� $\forall$.
* 
* ��С��ͷ $\leftarrow$, ��С��ͷ $\rightarrow$, ����ͷ $\Leftarrow$, �Ҵ��ͷ $\Rightarrow$, �ҳ���ͷ $\xrightarrow[fgh]{abcde}$.
* 
* ���� $\in$, ������ $\subset$, ������� $\subseteq$, �� $\cap$, �� $\cup$, �ռ� $\empty$
* 
* ������ $\vec{x}$, ������ $\overrightarrow{AB}$, �Ϻ��� $\overline{p}$.
���� $\infty$, ���� $\lim$, ΢�� ${\rm d}$, ƫ�� $\partial$, ���� $\dot{y}$, ����׵� $\ddot{y}$, �仯�� $\Delta$, �ݶ� $\nabla$.

* ��ʡ�� $\cdots$, ��ʡ�� $\vdots$, бʡ�� $\ddots$.
* 
* �������� $\sin$, $\cos$, $\tan$, $\arcsin$, $\arccos$, $\arctan$, $\ln$, $\log$, $\exp$.

$ (1+2)/222 $

$ \frac{1+2}{3+4} $


