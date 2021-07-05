# 國立台北科技大學　數學入學會考詳解

## 作者

- 109 資工系 黃漢軒
  - [Instagram](https://www.instagram.com/qtrabit._2._6.2_/)
  - sigtunatw@gmail.com

- 109 化工系 羅昇宇
  - [Instagram](https://www.instagram.com/trava_900921/)
  - qoo18105@gmail.com

感謝北科入學會考出題老師。

所有的解答均為非官方，有任何勘誤上的問題，請聯繫作者。


## 100年第1次北科入學數學會考

### 100-01-01

#### Statement

已知$f(x)$為一實系數多項式，且$f(\dfrac{3}{2}) = 27$，$f(-\dfrac{5}{3})=8$。

若$f(x)$除以$(6x^2+x-15)$的餘式為$ax+b$，則$b-a=?$

$(A)\quad 4\\(B)\quad 8\\\color{red}(C)\quad 12\\(D)\quad 16\\(E)\quad 20$



#### Solution

可以把式子轉成

$f(x) = g(x)(6x^2+x-15) + ax+b$

$= g(x)(3x+5)(2x-3) + ax+b$



代入$x=\dfrac{3}{2}$，得到$\dfrac{3}{2}a+b = 27$

代入$x=\dfrac{-5}{3}$，得到$\dfrac{-5}{3}a+b = 8$

解聯立之後得到$(a, b) = (6, 18)$



因此$b-a=12$，故選$(C)$



### 100-01-02

#### Statement

若$\alpha, \beta$為方程式$x - \dfrac{3}{x} + 1 = 0$的兩根，則$(\dfrac{2}{\alpha}+5)(\dfrac{2}{\beta}+5) = ?$

$(A)\quad 9 \\ (B)\quad 15 \\(C) \quad 21 \\\color{red}(D)\quad 27 \\(E)\quad 33$



#### Solution

$(\dfrac{2}{\alpha}+5)(\dfrac{2}{\beta}+5) = \dfrac{4}{\alpha\beta} + \dfrac{10(\alpha+\beta)}{\alpha\beta} + 25$

 $x - \dfrac{3}{x} + 1 = 0 \Rightarrow x^2+x-3=0$

利用根與係數，得到$\alpha + \beta = \dfrac{-b}{a} = \dfrac{-1}{1} = -1$，$\alpha\beta = \dfrac{c}{a} = -3$

因此$(\dfrac{2}{\alpha}+5)(\dfrac{2}{\beta}+5) = \dfrac{4}{-3} + \dfrac{-10}{-3} + 25 = 27$

故選$(D)$



### 100-01-03

#### Statement

求$13^5 - 14\times13^4 + 15\times13^3-25\times13^2-12\times13+9 = ?$

$\color{red}(A)\quad 22 \\ (B)\quad 25 \\ (C)\quad 28 \\ (D)\quad 31 \\(E)\quad 34$



#### Solution

將式子考慮成$f(x) = x^5-14x^4+15x^3-25x^2-12x+9$

式子等價於$f(x)$除以$x-13$的餘數（餘式定理）。



![image-20210705225143623](https://i.imgur.com/Sah4YSn.png)

故答案選$(A)$。



### 100-01-04

#### Statement

若$\dfrac{2x^2-x+4}{x^4+4x^2} = \dfrac{A}{x}+\dfrac{B}{x^2}+\dfrac{Cx+D}{x^2+4}$，則$A+B+C+D = ?$

$(A) \quad  \frac{1}{2} \\ \color{red}(B)\quad 2 \\ (C)\quad 3 \\(D)\quad \frac{7}{2}\\(E)\quad 33$



#### Solution

$\dfrac{2x^2-x+4}{x^4+4x^2} = \dfrac{A}{x}+\dfrac{B}{x^2}+\dfrac{Cx+D}{x^2+4}$

$2x^2-x+4 = A(x^3+4x) + B(x^2+4) + (Cx+D)(x^2)$

$= Ax^3+4Ax + Bx^2+4B+Cx^3+Dx^2$

$= (A+C)x^3+(B+D)x^2 + 4Ax + 4B$

可知

$A+C = 0 \\ B+D = 2 \\ A = -\frac{1}{4} \\ B = 1$

因此$C = \frac{1}{4}$，$D = 1$。



因此$A+B+C+D = 2$

故選$(B)$



### 100-01-05

#### Statement

$\dfrac{x^2-7x+12}{x^2-3x+2} \le -1$之解為何？

$\rm(A)\ 1\le x < 2$
$\rm(B)\ 1 < x \le 2$
$\color{red}{\rm(C)\ 1 < x < 2}$
$\rm(D)\ x \ge 2\ 或\ x < 1$
$\rm(E)\ x > 2\ 或\ x < 1$

#### Solution

$\dfrac{x^2-7x+12}{x^2-3x+2} \le -1$

$\Rightarrow \dfrac{x^2-7x+12}{x^2-3x+2} + 1\le 0$

$\Rightarrow \dfrac{2x^2-10x+14}{x^2-3x+2} \le 0$

$\Rightarrow \dfrac{2(x^2-5x+7)}{(x-1)(x-2)} \le 0$

故我們考慮

$\left\{\begin{array}2x^2-10x+14\le 0 \\(x-1)(x-2) > 0\end{array}\right. \Rightarrow x \in \varnothing$

$\left\{\begin{array}2x^2-10x+14 \ge 0 \\(x-1)(x-2) < 0\end{array}\right. \Rightarrow 1 < x < 2$

因此$1 < x < 2$時，$\dfrac{x^2-7x+12}{x^2-3x+2} \le -1$，故選$(C)$



### 100-01-06

#### Statement

若$a,\ b$均為實數且$ax^2+bx-10<0$之解為$\dfrac{-5}{2}<x<\dfrac{4}{3}$，則$a+b=$？

$\rm(A)\ 5$
$\rm(B)\ \dfrac{11}{2}$
$\rm(C)\ 6$
$\color{red}{\rm(D)\ \dfrac{13}{2}}$
$\rm(E)\ 7$

#### Solution

可以根據結果列出式子，得：

$(x+\dfrac{5}{2})(x-\dfrac{4}{3}) < 0 \\ \Rightarrow x^2-\dfrac{4x}{3}+\dfrac{5x}{2}+\dfrac{-20}{6} < 0 \\ \Rightarrow  6x^2-8x+15x-20 < 0 \\ \Rightarrow 6x^2+7x-20 < 0$

兩邊共除2，得$3x^2+\dfrac{7}{2}x-10 < 0$

$a = 3,\ b = \dfrac{7}{2},\ a + b = \dfrac{13}{2}$



### 100-01-07

#### Statement

若直線$12x-5y=21$與兩直線$x=\dfrac{23}{39}$、$x=\dfrac{16}{13}$分別交於$A、B$兩點，則線段長$\overline{AB} = ?$

$(A)\quad \dfrac{6}{5}\\(B)\quad \dfrac{5}{4}\\\color{red}(C)\quad \dfrac{5}{3}\\(D)\quad \dfrac{13}{5}\\(E)\quad \dfrac{25}{7}$



#### Solution

已知$12x-5y=21$，則斜率為$\dfrac{12}{5}$

$\Delta x = \dfrac{16}{13} - \dfrac{23}{39} = \dfrac{25}{39}$

$y=mx+b$，則$0 = \dfrac{12}{5}(\dfrac{16}{13} - \dfrac{23}{39}) + b$，得到$b = \dfrac{60}{39} = \Delta y$

因此距離為$\sqrt{(\Delta x)^2+(\Delta y)^2} = \sqrt{(\dfrac{25}{39})^2+(\dfrac{60}{39})^2} = \dfrac{5}{3}$，故選$(C)$



### 100-01-08

#### Statement

設兩向量$\vec{a}, \vec{b}$的夾角為$\theta$，且$|\vec{a}| = |\vec{b}|$，$|\vec{a}+\vec{b}| = 4$，$|\vec{a}-\vec{b}| = 3$，則$\cos\theta = ?$



$\color{red}(A)\quad \dfrac{7}{25} \\ (B)\quad \dfrac{5}{13} \\(C)\quad \dfrac{3}{5}\\(D)\quad \dfrac{4}{5}\\(E)\quad \dfrac{5}{6}$



#### Solution

可以考慮成

$\cos\theta = \dfrac{|a|^2+|b|^2-|a-b|^2}{2\times |a|\times |b|}$

$\cos(\pi-\theta) = \dfrac{|a|^2+|b|^2-|a+b|^2}{2\times|a|\times|b|} = -\cos\theta$

因此，$\dfrac{|a|^2+|b|^2-|a-b|^2}{2\times |a|\times |b|} = \dfrac{-|a|^2-|b|^2+|a+b|^2}{2\times|a|\times|b|}$

$|a|^2+|b|^2-9 = -|a|^2-|b|^2+16$

設$x = |a| = |b|$，故$2x^2-9=-2x^2+16$，得到$x  = \dfrac{5}{2} = |a| = |b|$

代入$\cos\theta$，得到$\dfrac{\dfrac{25}{4}+\dfrac{25}{4}-9}{2\times\dfrac{5}{2}\times \dfrac{5}{2}} = \dfrac{\dfrac{25}{2}-9}{\dfrac{25}{2}} = \dfrac{7}{25}$

故選$(A)$



### 100-01-09

#### Statement

設兩向量$\vec{a}$、$\vec{b}$的夾角為$\theta$，且$|\vec{a}|=7$、$|\vec{b}|=5$，$\tan\theta = -\dfrac{3}{4}$，則$(\vec{a}+\vec{b})(2\vec{a}-3\vec{b}) = ?$

$(A)\quad -25 \\ (B)\quad -5\\ (C)\quad 0\\ (D)\quad 44\\\color{red}(E)\quad 51$



#### Solution

$(\vec{a}+\vec{b})(2\vec{a}-3\vec{b}) = 2|\vec{a}|^2-3(\vec{a}\cdot\vec{b})+2(\vec{a}\cdot\vec{b}) - 3|\vec{b}|^2$

已知$\tan\theta = \dfrac{-3}{4}$，則$\cos\theta = -\dfrac{4}{5}$

因此$\vec{a}\cdot\vec{b} = |a||b|\cos\theta = 7\times5\times-\dfrac{4}{5} = -28$

因此$(\vec{a}+\vec{b})(2\vec{a}-3\vec{b}) = 98 +28-75=51$

故選$(E)$。



### 100-01-10

#### Statement

橢圓以$(2,2)$與$(6,2)$為兩焦點，且與直線$x+1=0$相切，則橢圓短軸半長為何？

$(A)\quad 4\\\color{red}(B)\quad \sqrt{21}\\(C)\quad \sqrt{23}\\(D)\quad \sqrt{29}\\(E)\quad 6$



#### Solution

將題目簡化為求$b$的長度為何

橢圓中點為兩焦點座標之中點，也就是$(\dfrac{2+6}{2}, \dfrac{2+2}{2}) = (4, 2)$

焦距$c$為焦點與橢圓中點之距離，因此可知$c = 2$

已知與直線$x+1=0$相切，因此橢圓左右一端會與$x+1=0$相切，因此其中一端為$(-1, 2)$

故長軸$a$為橢圓長軸端點與中心之距離，可知$a=5$

因此$b = \sqrt{a^2-c^2} = \sqrt{25-4} = \sqrt{21}$

故選$(B)$。



### 100-01-11

#### Statement

設拋物線$y=2x-\dfrac{1}{2}x^2$的焦點座標為$(a, b)$，則$ab=?$

$\color{red}(A)\quad 3 \\(B)\quad 3.5\\(C)\quad 4\\(D)\quad 4.5\\(E)\quad 5$



#### Solution

$y=2x-\dfrac{1}{2}x^2$

$\Rightarrow y = \dfrac{1}{2}(4x-x^2)$

$\Rightarrow y = \dfrac{1}{2}(-4+4x-x^2)+2$

$\Rightarrow y = -\dfrac{1}{2}(x-2)^2 + 2$

$\Rightarrow -2(y-2) = (x-2)^2$

因此可以知道頂點座標為$(2, 2)$，$c = \dfrac{-2}{4} = \dfrac{-1}{2}$

因此焦點為$(2, 2+\dfrac{-1}{2}) = (2, \dfrac{3}{2})$ 

故$a = 2, b = \dfrac{3}{2}$，得到$ab = 3$，故選$(A)$。



### 100-01-12

#### Statement

雙曲線$xy-3x+4y = 0$兩頂點的距離為何？

$(A)\quad 2\sqrt{3}\\(B)\quad 4\\(C)\quad 2\sqrt{6}\\(D)\quad 4\sqrt{3}\\\color{red}(E)\quad 4\sqrt{6}$



#### Solution

$xy-3x+4y = 0\Rightarrow (x+4)(y-3) = -12$

考慮通過頂點的線為$y=-x+b$，代入必定通過的點$(-4, 3)$得到$b = -1$

因此$y=-x-1$會通過直角雙曲線的兩個頂點。

與原式解聯立

$x(-x-1)-3x+4(-x-1)=0 \Rightarrow x^2+8x+4=0$

利用公式解得到$x$的點，也就是$x = \dfrac{-8\pm\sqrt{64-4\times1\times4}}{2} = -4\pm2\sqrt{3}$

當$x = -4+2\sqrt{3}$時，$y = 2\sqrt{3}-3$

當$x = -4-2\sqrt{3}$時，$y = -3-2\sqrt{3}$

兩點距離為$\sqrt{(-4+2\sqrt{3}-(-4-2\sqrt{3}))^2 + (2\sqrt{3}-3 - (-3-2\sqrt{3}))^2} = \sqrt{48+48}=4\sqrt{6}$，故選$(E)$



### 100-01-13

#### Statement

若$\log_2(3-x^2)=1+\log_2x$，則$x=?$

$(A)\quad -3 \\(B)\quad -3或1\\\color{red}(C)\quad 1\\(D)\quad 2\\(E)\quad 3$



#### Solution

$\log_2(3-x^2)=1+\log_2x$

$\Rightarrow \log_2(3-x^2)-\log_2 x = 1$

$\Rightarrow \log_2(\dfrac{3-x^2}{x}) = 1$

$\Rightarrow \dfrac{3-x^2}{x} = 2$

$\Rightarrow -x^2-2x+3 = 0$

$\Rightarrow x=1, x = -3$

驗根可知$\log_2 x$無法放入$-3$，因為$\log$的定義域為正整數之集合，故$x=-3$不合。

因此$x=1$，故選$(C)$



### 100-01-14

#### Statement

若$f(x) = \dfrac{1+2^x}{1-2^x}$，且$f(a)=3$，$f(b)=5$，則$f(a+b)=?$

$(A)\quad \frac{5}{3} \\\color{red}{(B)\quad 2}\\ (C)\quad 6 \\(D)\quad 8\\(E)\quad 15$



#### Solution

令$t=2^x$，則$f(x) = \dfrac{1+t}{1-t}$

考慮$f(a)=3$

$\dfrac{1+t}{1-t}=3$

$\Rightarrow 1+t=3-3t$

$\Rightarrow t=\dfrac{1}{2}$

因此$2^a=\dfrac{1}{2}$，得到$a=-1$

考慮$f(b)=5$

$\dfrac{1+t}{1-t}=5$

$\Rightarrow 1+t=5-5t$

$\Rightarrow t = \dfrac{2}{3}$

$2^b=\dfrac{2}{3}$，則$b=1-\log_23$

故$f(a+b) = f(-\log_23) = f(\log_2\dfrac{1}{3}) = \dfrac{1+\dfrac{1}{3}}{1-\dfrac{1}{3}} = \dfrac{4}{2} = 2$，故選$(B)$

### 100-01-15

#### Statement

求$\log_2(\sqrt{12+2^\frac{7}{2}} + \sqrt{12-2^\frac{7}{2}})=?$

$(A)\quad \dfrac{1}{2}\\ (B)\quad \dfrac{3}{2}\\(C)\quad 2 \\\color{red} (D)\quad \dfrac{5}{2}\\(E)\quad 4$



#### Solution

$\log_2(\sqrt{12+2^\frac{7}{2}} + \sqrt{12-2^\frac{7}{2}})=\log_2(\sqrt{12+8\sqrt{2}} + \sqrt{12-8\sqrt{2}}) = \log_2(\sqrt{8+8\sqrt{2}+4} + \sqrt{8-8\sqrt{2}+4})$

$=\log_2(\sqrt{(2+2\sqrt{2})^2} - \sqrt{(2-2\sqrt{2})^2}) = \log_2(4\sqrt{2}) = \dfrac{5}{2}$，故選$(D)$



### 100-01-16

#### Statement

設$0 < \theta < \dfrac{\pi}{2}$，且$\sin\theta-\cos\theta = \dfrac{1}{2}$，則$\sin\theta+\cos\theta=?$

$(A)\quad -1\\ (B)\quad -\dfrac{1}{2}\\(C)\quad \dfrac{1}{2}\\(D)\quad \dfrac{\sqrt{5}}{2}\\\color{red}(E)\quad \dfrac{\sqrt{7}}{2}$



#### Solution

$(\sin\theta-\cos\theta)^2 = \sin^2\theta - 2\sin\theta\cos\theta + \cos^2\theta = 1-2\sin\theta\cos\theta= \dfrac{1}{4}$

故$\sin\theta\cos\theta = \dfrac{3}{8}$

則$\sin\theta+\cos\theta = \sqrt{(\sin\theta+\cos\theta)^2} = \sqrt{\sin^2\theta+2\sin\theta\cos\theta +\cos^2\theta}$

$= \sqrt{1+2\sin\theta\cos\theta} = \sqrt{1+2\dfrac{3}{8}} = \sqrt{\dfrac{7}{4}} = \dfrac{\sqrt{7}}{2}$，故選$(E)$



### 100-01-17

#### Statement

下列何者錯誤？

$(A)\quad 若0<x<\dfrac{\pi}{4}，則\sin x<\cos x< \cot x$

$\color{red}(B)\quad 若\pi<x<\dfrac{5\pi}{4}，則\sec x < \csc x< \cot x$

$(C)\quad 若\dfrac{\pi}{4}<x<\dfrac{\pi}{2}，則\cos x < \sin x< \tan x$

$(D)\quad 若\pi<x_1<x_2<\dfrac{3\pi}{2}，則\sin x_1 > \sin x_2$

$(E)\quad 若\dfrac{\pi}{2}<x_1<x_2<\pi，則\cos x_1 > \cos x_2$



#### Solution

若$\pi<x<\dfrac{5\pi}{4}，則\sin\theta < \cos\theta < \tan\theta$

故$\csc\theta < \sec\theta < \cot\theta$，故選$(B)$



### 100-01-18

#### Statement

若$mx+3y+1=0$與$x+(m-2)y+m=0$之交點在第二象限內，則$m$之範圍為何？

$(A)\quad 0 < m < 1 \\(B)\quad 0 < m < 2\\(C)\quad 0 < m < 3\\\color{red} (D)\quad 1 < m < 3\\(E)\quad 1 < m < 4$

#### Solution

用一二式來解聯立，可以寫出交點參數式

$\left\{\begin{array}\ x = \dfrac{2m+2}{(m-3)(m+1)} \\ y = \dfrac{m^2-1}{(-m+3)(m+1)} \end{array}\right.$

考慮到$y > 0, x < 0$的情況

得到$((m<-1) \cup (-1 < m < 3)) \cap (1 < m < 3) \Rightarrow  1 < m < 3$

得到$1 < m < 3$，故選$(D)$



### 100-01-19

#### Statement

若點$(a, b)$在直線$2x+3y=1$上移動，則直線$ax+by=3$恆過哪一點？

$(A)\quad (3, 4)\\ (B)\quad (4,5)\\(C)\quad (5, 7)\\(D)\quad (5, 8)\\\color{red}(E)\quad (6,9)$



#### Solution

考慮$x=5$時$y=-3$

考慮$x=-4$時$y=3$



由於$a, b$依照一定比例變換，因此只有直線上的斜率變換。

找到兩條線的交點即為恆過的點。

因此我們考慮$5x-3y=3$與$-4x+3y=3$的交點，得到$(x, y) = (6, 9)$，故選$(E)$



### 100-01-20

#### Statement

已知$A(3, -5)$，$B(-7, 4)$，且點$P$介於$A$、$B$之間，又$\overline{AB} : \overline{BP} = 7 : 4$，若$P$之座標為$(a, b)$，則$7a+21b=?$

$\color{red}(A)\quad -33 \\ (B)\quad -32\\(C)\quad -31\\(D)\quad -30\\(E)\quad -29$



#### Solution

$\overline{AB} : \overline{BP} = 7 : 4 \Rightarrow \overline{AP} : \overline{BP} = 3 : 4$

利用內分點公式。

$P = (\dfrac{4\times3+3\times(-7)}{7}, \dfrac{4\times(-5)+3\times4}{7}) = (\dfrac{-9}{7}, \dfrac{-8}{7})$

則$7a+21b=(-9)+(-8)\times3 = -33$，故選$(A)$




## 100年第2次北科入學數學會考

### 100-02-01

#### Statement

若$\alpha$，$\beta$為方程式$x^2+12x+9=0$的兩根，則$(\sqrt{\alpha}-\sqrt{\beta})^2=$？

$\rm(A)\ -18$
$\color{red}{\rm(B)\ -6}$
$\rm(C)\ 6$
$\rm(D)\ 12$
$\rm(E)\ 18$

#### Solution

我們可以依照偉達定理(根與係數)的概念來寫這一題。

令一二次多項式$ax^2+bx+c$，存在兩根$\alpha$與$\beta$。

那麼$\alpha + \beta = \dfrac{-b}{a}$，且$\alpha\beta = \dfrac{c}{a}$

因此，我們可以把欲求的式子展開，得：

$\sqrt{\alpha}^2 - 2\sqrt{\alpha}\sqrt{\beta} + \sqrt{\beta}^2$

$\Rightarrow \alpha - 2\sqrt{\alpha\beta} + \beta$

根據偉達定理我們可以求得

$\alpha + \beta = \dfrac{-b}{a} = \dfrac{-12}{1} = -12$



$\alpha\beta = \dfrac{c}{a} = \dfrac{9}{1} = 9$

注意一下$\alpha + \beta = -12$，$\alpha \beta = 9$
若兩根一正一負那麼$\alpha\beta<0$，若兩根都是正的那麼$a+b>0$

因此剩下唯一的兩根都是負的才能使偉達定理成立。
$\sqrt{\alpha}\sqrt{\beta}$會存在複數，相乘後可以得到$-\sqrt{\alpha\beta}$。



因此帶回欲求之式子：

$-12 - 2\times -\sqrt{9} = -12 + 6 = -6$

### 100-02-02

#### Statement

若 $x^4-x^3-x^2-x-2$ 與 $2x^3+x^2-7x-6$ 的最高公因式為 $x^2+bx+c$，則$b+2c=$？

$\color{red}{\rm(A)\ -5}$
$\rm(B)\ -3$
$\rm(C)\ 0$
$\rm(D)\ 5$
$\rm(E)\ 7$

#### Solution

第一式的因式$ax+b$的$a$一定會是1的因素(因為最大項係數等於1)，
且$b$一定會是2的因數(因為最小項的係數等於2)，第二式亦同。

因此我們可以對第一式做因式分解，得到$(x+1)(x-2)(x^2+1)$
接著我們以相同方式對第二式做因式分解，得倒$(x+1)(x-2)(2x+3)$

可以觀察到最大公因式即為$(x+1)(x-2) = x^2-x-2$
比較係數後得到$b=-1, c = -2$

則$b + 2c = -1 + 2\times -2 = -5$。

### 100-02-03

#### Statement

若$\dfrac{8x^3-6x+1}{(2x+1)^4} = \dfrac{a}{(2x+1)} + \dfrac{b}{(2x+1)^2} + \dfrac{c}{(2x+1)^3} + \dfrac{d}{(2x+1)^4}$，則$2a+b-c+d=$？

$\rm(A)\ -2$
$\rm(B)\ -1$
$\rm(C)\ 0$
$\rm(D)\ 1$
$\color{red}{\rm(E)\ 2}$

#### Solution

我們可以使用綜合除法，將$2x+1$改寫成$x+\dfrac{1}{2}$，然後再對除出來的係數除以2。

![image-20210705225349210](https://i.imgur.com/3azygtK.png)

因此$a = 1,\ b = -3,\ c = 0,\ d = 3$。

$2a + b - c + d = 1\times 2 + (-3) - 0 + 3 = 2$。

### 100-02-04

#### Statement

$x^2-4x+2 \le |x-2|$ 之解為何？

$\rm(A)\ 1\le x \le 4$
$\rm(B)\ 2\le x \le 4$
$\rm(C)\ 0\le x \le 2$
$\color{red}{\rm(D)\ 0\le x \le 4}$
$\rm(E)\ 0\le x \le 3$

#### Solution

1. 考慮$x^2-4x+2 \le x-2$：
    移項，$x^2-4x+2-x+2 \le 0$
    整理，$x^2-5x+4 \le 0$
    那麼我們可以將其因式分解，得$(x-4)(x-1) \le 0$，並且可以得到$1 \le x \le 4$。

2. 考慮$x^2-4x+2 \le -x+2$：
    移項，$x^2-4x+2+x-2 \le 0$
    整理，$x^2-3x \le 0$
    那麼我們可以將其因式分解，得$x(x-3) \le 0$，並且可以得到$0 \le x \le 3$

對剛剛考慮的兩個東西產生出來的結果取聯集，得到$0 \le x \le 4$。

### 100-02-05

#### Statement

$2\log_2x-\log_x2<1$之解為何？

$\rm(A)\ x<\dfrac{-1}{2}\ 或\ 0 < x < 1$
$\rm(B)\ 0<x<\dfrac{1}{2}\ 或\ 1 < x < 2$
$\rm(C)\ x<\dfrac{-1}{\sqrt{2}}\ 或\ 0 < x < 1$
$\rm(D)\ x<\dfrac{-1}{\sqrt{2}}\ 或\ 1 < x < 2$
$\color{red}{\rm(E)\ 0<x<\dfrac{1}{\sqrt{2}}\ 或\ 1 < x < 2}$

#### Solution

$2\log_2x-\log_x2<1$

$\Rightarrow 2\log_2x-\dfrac{\log{2}}{\log{x}} < 1$

$\Rightarrow 2\log_2x-\dfrac{1}{\log_2x} < 1$

令$\log_2x = t$，那麼

$2t - \dfrac{1}{t} < 1$
$\Rightarrow 2t - \dfrac{1}{t} - 1 < 0$

$\Rightarrow \dfrac{2t^2-t-1}{t} < 0$

考慮兩種情況。

1. 若$t>0$且$2t^2-t-1<0$
    $2t^2-t-1<0 = (2t+1)(t-1)<0 = \dfrac{-1}{2} < t < 1$
    與$t>0$取交集得到$0 < t < 1$。

2. 若$t<0$且$2t^2-t-1>0$
    $2t^2-t-1>0 = (2t+1)(t-1)>0 = t < \dfrac{-1}{2}\ 或\ t > 1$
    與$t<0$取交集得到$t < \dfrac{-1}{2}$。

對這兩種考慮取聯集，得到$t < \dfrac{-1}{2}$或$0 < t < 1$。

還原，得到$x < \dfrac{1}{\sqrt{2}}$或$1 < x < 2$。



### 100-02-06

#### Statement

已知$∆ABC$ 中，$\overline{AB} = 37$，$\overline{BC} = 53$，$\overline{AC} = 89$，則下列各內積中，何者為最大？

$(A) \quad \vec{AB}\cdot \vec{AC} \\ (B) \quad \vec{BC}\cdot \vec{BA} \\ \color{red}(C) \quad \vec{CA}\cdot \vec{CB} \\ (D) \quad \vec{AB}\cdot\vec{BC} \\ (E) \quad \vec{BC}\cdot\vec{CA}$



#### Solution

$\vec{AB} \cdot \vec{AC} = 37 \times 89 \times \dfrac{37^2+89^2-53^2}{2\times 37\times 89}$

$\vec{BC}\cdot\vec{BA} = 53\times 37\times \dfrac{53^2+37^2-89^2}{2\times 53\times 37}$

$\vec{CA} \cdot \vec{CB} = 89 \times 37 \times \dfrac{89^2+53^2-37^2}{2\times 89\times 53}$

$\vec{AB} \cdot \vec{BC} < 0$

$\vec{BC} \cdot \vec{CA} < 0$



故問題化簡成比較以下三者之大小：

$37^2+89^2-53^2。$

$53^2+37^2-89^2$

$89^2+53^2-37^2$

顯然是第三者較大，故選$(C)$





### 100-02-07

#### Statement

已知向量$\overrightarrow{AB}=(-31, 29)$，$\overrightarrow{AC}=(23, -11)$，則下列向量長中，何者為最大？

$\rm(A)\ |\overrightarrow{AB}|$
$\color{red}{\rm(B)\ |\overrightarrow{BC}|}$
$\rm(C)\ |\overrightarrow{AB}+\overrightarrow{BC}|$
$\rm(D)\ |\overrightarrow{AB}+\overrightarrow{AC}|$
$\rm(E)\ |\overrightarrow{AB}+\overrightarrow{BC}+\overrightarrow{CA}|$

#### Solution

$\overrightarrow{BC} = \overrightarrow{BA} + \overrightarrow{AC}$
$\overrightarrow{BA} = (31, -29)$

$\overrightarrow{BC} = (31, -29) + (23, -11) = (54, -40)$
$\overrightarrow{CA} = (-23, 11)$

考慮向量長的公式，當存在一向量$\overrightarrow{L} = (A,B)$，$\overrightarrow{L}$的向量長為$|\overrightarrow{L}| = \sqrt{A^2+B^2}$
因此若$|A|+|B|$越大，那麼向量長越大。

考慮選項A：$|-31|+|29| = 60$
考慮選項B：$|54|+|-40| = 94$
考慮選項C：$\overrightarrow{AB}+\overrightarrow{BC} = (-31, 29) + (54, -40) = (23, -11)$，$|23|+|-11|=34$
考慮選項D：$\overrightarrow{AB}+\overrightarrow{AC} = (-31, 29) + (23, -11) = (-8, 18)$，$|-8|+|18|=26$
考慮選項E：$\overrightarrow{AB}+\overrightarrow{BC}+\overrightarrow{CA} = (-31, 29) + (54, -40) + (-23, 11) = (0, 0)$，$|0|+|0| = 0$

因此，故選B。

### 100-02-08

#### Statement

設$y=ax^2+bx+c$的圖形如下，則下列各式中，何者為負值？

![](https://i.imgur.com/ocFuXVH.png)

$\rm(A)\ abc$
$\rm(B)\ b^2-4ac$
$\rm(C)\ c^2-4ab$
$\rm(D)\ b+\sqrt{b^2-4ac}$
$\color{red} \rm(E)\ b-\sqrt{b^2-4ac}$

#### Solution

因為開口向上，所以$a>0$。
觀察$x=0$，可以發現對應到的$y<0$，因此$c<0$
觀察一下對稱軸，$\dfrac{-b}{2a} > 0$，因此$b<0$

因此$abc > 0$，$b^2-4ac>0$因為有實數解。
$c^2-4ab > 0$因為$ab<0$。

而$b+\sqrt{b^2-4ac}$必為正因為可以從圖中觀察到這個根是正數，
另一根是負數因此$b-\sqrt{b^2-4ac}$小於0，故選E。

### 100-02-09

#### Statement

已知$4x^2+y^2-4x+8y=8$，則$x$的最大值為何？

$\rm (A)\ 1$
$\rm (B)\ 2$
$\color{red}{\rm (C)\ 3}$
$\rm (D)\ 4$
$\rm (E)\ 5$

#### Solution

這是一個橢圓，可以用配方法來找短邊或者長邊，加上中心就是最大的$x$了。



$4x^2-4x+y^2+8y=8$

$4(x^2-x)+y^2+8y=8$

$4(x^2-x+\dfrac{1}{4})+y^2+8y+16=8+16+1$

$4(x-\dfrac{1}{2})^2+(y+4)^2=25$

$\dfrac{(x-\dfrac{1}{2})^2}{\dfrac{25}{4}}+\dfrac{(y+4)^2}{25}$

由此可知這個橢圓的短邊平行$x$軸

$a = \sqrt{25} = 5, b = \sqrt{\dfrac{25}{4}} = \dfrac{5}{2}$

中心可從式子得知，$(x,y) = (\dfrac{1}{2}, -4)$

因此，加上$x$的部份得到$\dfrac{5}{2} + \dfrac{1}{2} = 3$

### 100-02-10

#### Statement

拋物線$y=4-2x-x^2$與$x$軸兩交點的距離為何？

$\rm (A)\ 2$
$\rm (B)\ 3$
$\color{red}{\rm (C)\ 2\sqrt{5}}$
$\rm (D)\ 6$
$\rm (E)\ 8$

#### Solution

將y等於$0$，求出$x$。

$-x^2-2x+4=0$

先確定$b^2-4ac$是否大於$0$。

$(-2)^2-4\times(-1)\times4 = 4+16 = 20$

因此兩根為$\dfrac{2\pm\sqrt{20}}{-2} = \dfrac{2\pm2\sqrt{5}}{-2}$

$\dfrac{2+\sqrt{5}}{-2} - \dfrac{2-\sqrt{5}}{-2} = 2\sqrt{5}$



### 100-02-11

#### Statement

設雙曲線$x^2-y^2=x+2y$兩漸進的夾角為$\theta$，則$\sin\dfrac{\theta}{2}=$？

$\rm (A)\ 0$
$\color{red}{\rm (B)\ \dfrac{1}{\sqrt{2}}}$
$\rm (C)\ \dfrac{\sqrt{3}}{2}$

$\rm (D)\ \dfrac{2}{\sqrt{5}}$

$\rm (E)\ 1$


#### Solution

配方雙曲線得到標準式。

$x^2-x-y^2-2y=0 \Rightarrow x^2-x+\dfrac{1}{4}-y^2-2y+1 = \dfrac{5}{4}$

$(x-\dfrac{1}{2})^2-(y-1)^2=\dfrac{5}{4}$

$\dfrac{4(x-\dfrac{1}{2})^2}{5} - \dfrac{4(y-1)^2}{5} = 1$

求漸進線，令等號右邊為0

$\dfrac{4(x-\dfrac{1}{2})^2}{5} = \dfrac{4(y-1)^2}{5}$

$(x-\dfrac{1}{2})^2 = (y-1)^2$

$(x-\dfrac{1}{2})^2-(y-1)^2 = 0$

$(x-\dfrac{1}{2}-(y-1))(x-\dfrac{1}{2}+(y-1)) = 0$

$(x-y+\dfrac{1}{2})(x+y+\dfrac{3}{2}) = 0$

第一條線$(x-y+\dfrac{1}{2})$可求斜率$m=1$

第二條線$(x+y+\dfrac{3}{2})$可求斜率$m=-1$

因此，這兩條線垂直$(m_1 \times m_2 = -1)$，夾角為$90^{\circ}$

因此$\sin\dfrac{90^{\circ}}{2} = \sin45^{\circ} = \dfrac{\sqrt{2}}{2}$



### 100-02-12

#### Statement

不等式$\dfrac{3\cdot2^x-18\cdot2^{-x}}{2^x-2^{-x}} \le 2$之解為何？

$\rm(A)\ -1\le x \le 1$

$\rm(B)\ 0 < x \le 1$

$\rm(C)\ 1 \le x \le 2$

$\color{red}{\rm (D)\ 0 < x \le 2}$

$(E)\ 1 \le x \le 4$



#### Solution

將分子分母上下同乘$2^x$。

$\dfrac{3\cdot2^x-18\cdot2^{-x}}{2^x-2^{-x}} \Rightarrow \dfrac{3\cdot2^{2x} - 18}{2^{2x}-1} \le 2$

移項。

$\dfrac{3\cdot2^{2x} - 18}{2^{2x}-1} -2 \le 0$

$\dfrac{3\cdot 2^{2x} - 18 - 2(2^{2x}-1)}{2^{2x}-1} \le 0$

$\dfrac{3\cdot 2^{2x} - 18 - 2\cdot 2^{2x} + 2}{2^{2x} - 1} \le 0$

$\dfrac{2^{2x} - 16}{2^{2x} - 1} \le 0$

令$t = 2^{2x}$

$\dfrac{t-16}{t-1} \le 0$

考慮以下兩點：

1. $t - 16 \ge 0$，$t - 1 < 0$

  $t \ge 16,\ t < 1$，這兩個不等式沒有任何交集，因此$t \in \emptyset$

2. $t - 16 \le 0$，$t - 1 > 0$

  $t \le 16,\ t > 1$，這兩個不等式的交集為$1 < t \le 16$

將以上考慮的兩點做聯集，得到$1 < t \le 16$

還原$t$得到$1 < 2^{2x} \le 16$，因此$0 < x \le 2$



### 100-02-13

#### Statement

方程式$10\cdot x^{2\log x} = x^3$之所有實根的平方和為何？

$\rm (A)\ 100$
$\rm (B)\ 101$
$\color{red}{\rm (C)\ 110}$
$\rm (D)\ 111$
$\rm (E)\ 121$

#### Solution

等號兩邊同除$x^{2\log x}$

$10 = x^{3 - 2\log x}$

$1 = (3-2\log x) \times \log(|x|)$

因為要求實根，因此可以限定$x > 0$，所以$(3 - 2\log x)\times \log(x)$



令$t = \log x$

$1 = (3 - 2t)\times t \Rightarrow -2t^2+3t-1 = 0$

因式分解得到$(-2t+1)(t-1) = 0$

可以解出$t = \dfrac{1}{2}$或$t = 1$



還原$t$，可以得到$\log x = \sqrt{10}$ 或 $\log x = 10$

兩根的平方和為$\sqrt{10}^2 + 10^2 = 110$



### 100-02-14

#### Statement

若$f(x) = \log_2(x^3+x^2-7x+5)$，則$f(1+\sqrt{2})=$？

$\rm (A)\ 1$
$\rm (B)\ 2$
$\color{red}{\rm (C)\ 3}$
$\rm (D)\ 4$
$\rm (E)\ 5$

#### Solution

觀察一下，可以嘗試把$x^3+x^2-7x+5$化簡成$c(x-1)^2+b(x-1)+a...$

這部分可以用綜合除法做到。



![image-20210705225943458](https://i.imgur.com/oFox8KL.png)



因此可得$(x-1)^3 + 4(x-1)^2 -2(x-1)$。

把$f(1 + \sqrt{2})$帶進去，得：

$\log_2((\sqrt{2})^3+4(\sqrt{2})^2-2(\sqrt{2})) = \log_2({2\sqrt{2}+8-2\sqrt{2}}) = \log_28 = 3$



### 100-02-15

#### Statement

設$\cos\theta+\cos^2\theta = 1$，則$\sin^2\theta + \sin^4\theta = $？

$\rm (A)\ \dfrac{1}{4}$

$\rm (B)\ \dfrac{1}{3}$

$\rm (C)\ \dfrac{1}{2}$

$\rm (D)\ \dfrac{\sqrt{3}}{2}$

$\color{red}{\rm (E)\ 1}$



#### Solution

$\cos^2\theta = 1 - \cos\theta$

$\sin^2 \theta = 1 - \cos^2\theta = 1 - (1 - \cos\theta) = \cos\theta$

$\sin^4\theta = (\sin^2\theta)^2 = \cos^2\theta$

$\sin^2\theta + \sin^4\theta = \cos\theta + \cos^2\theta = 1$



### 100-02-16

#### Statement

設$\tan100^{\circ}=k$，則$\sin 80^{\circ} = $？

$\color{red}{\rm (A)\ \dfrac{-k}{\sqrt{1+k^2}}}$

$\rm (B)\ \dfrac{\sqrt{k}}{\sqrt{1+k^2}}$

$\rm (C)\ \dfrac{-1}{\sqrt{1+k^2}}$

$\rm (D)\ \dfrac{k}{\sqrt{1+k^2}}$

$\rm (E)\ \dfrac{1}{\sqrt{1+k^2}}$

#### Solution

畫個圖

<img src="https://i.imgur.com/tPeVsKt.png" alt="image-20200811202835139" style="zoom: 50%;" />

看圖可以觀察到，$\sin100^{\circ} = \sin80^{\circ} = \dfrac{-k}{\sqrt{1+k^2}}$

### 100-02-17

#### Statement

設$a = \sec434^{\circ}$，$b = \sin 100^{\circ}$，$c = \cos 260^{\circ}$，$d = \cot 28^{\circ}$，$e = \csc 155^{\circ}$

則下列何者正確？



$\rm (A)\ b < c < d < e < a$

$\color{red}{\rm(B)\ c < b < d < e < a}$

$\rm(C)\ c < b < e < d < a$

$\rm(D)\ c < b < d < a < e$

$\rm(E)\ b < c < a < d < e$



#### Solution

$a = \sec 434^{\circ} = \sec 74^{\circ} = \csc 16^{\circ}$

$b = \sin100^{\circ} = \sin80^{\circ}$

$c = \cos 260^{\circ} = -\cos80^{\circ}$

$d = \cot28^{\circ}$

$e = \csc155^{\circ} = \csc25^{\circ}$



因此$a > e$，$c < b$，故選B。



### 100-02-18

#### Statement

平面上有兩點$A (1, 2)$，$B(a,b)$，若直線$\overline{AB}$之垂直平分線為$x + 2y - 10 = 0$，則$a - b$ = ？

$\rm (A)\ -1$

$\rm (B)\  -2$

$\color{red}{\rm (C)\ -3}$

$\rm (D)\ -4$

$\rm (E)\ -5$



#### Solution

垂直平分線，因此垂直平分線通過$\overline{AB}$的中點$(\dfrac{1+a}{2}, \dfrac{2+b}{2})$。

帶入垂直平分線得到$\dfrac{1+a}{2} + 2+b - 10 = 0 \Rightarrow 1+a+4+2b-20=0$

$\Rightarrow a+2b=15$



而我們可以求得垂直平分線的斜率，得到$m = \dfrac{-1}{2}$，因此與其垂直的斜率一定是$m = \dfrac{-1}{\dfrac{-1}{2}} = 2$

因此按照斜率定義，可以得到$\dfrac{2-b}{1-a} = 2$，整理得到$2- b = 2 - 2a \Rightarrow 2a = b$。

帶回第一式可以得到$5a = 15,\ a =3,\ b = 6$。

$a - b = 3 - 6 = -3$



### 100-02-19

#### Statement

設直線$bx+ay-ab=0$，$a > 0,\ b < 0$過點$(1, 2)$，若此直線與二坐標軸相交，圍成一個面積為$2$的三角形，則$a+2b=$？

$\rm (A)\ -7-3\sqrt{3}$

$\rm (B)\  -6-3\sqrt{3}$

$\color{red}{\rm (C)\ -5-3\sqrt{3}}$

$\rm (D)\ -4-3\sqrt{3}$

$\rm (E)\ -3-3\sqrt{3}$



#### Solution

可以推出$x, y$的通式。

$bx + ay = ab$，求出$x,y$的截距。

當$y=0$，那麼$bx = ab$，$x = a$

當$x = 0$，那麼$ay = ab$，$y = b$



已知$a > 0, b < 0$過點$(1, 2)$，此直線與二坐標軸相交，圍成一個面積為$2$的三角形。

因此可以知道$\dfrac{1}{2}|a||b| = 2$，可知$ab = -4$或者$ab = 4$，但是$a > 0, b < 0$，因此$ab = 4$不合。



已知過點$(1, 2)$且$ab = -4$，因此可以把點帶入得到$b + 2a = -4$，

又$ab = -4$所以$a = \dfrac{-4}{b}$，所以得到$b + \dfrac{-8}{b} = -4$

同乘以$b$可以得到$b^2+4b-8$。'



利用公式解可以解出$\dfrac{-4\pm\sqrt{16-4\times 1\times -8}}{2} = \dfrac{-4\pm\sqrt{48}}{2} = \dfrac{-4\pm4\sqrt{3}}{2}$

那麼可以解出兩根$-2+2\sqrt{3}$或者$-2-2\sqrt{3}$，其中由於$b<0$，因此$-2+2\sqrt{3}$不合。



帶回求出$a$得到$a = \dfrac{-4}{-2-2\sqrt{3}} = \dfrac{-4}{-2(1+\sqrt{3})}$

化簡得到$a = \dfrac{2}{1+\sqrt{3}} = \dfrac{2(1-\sqrt{3})}{-2} = -1(1-\sqrt{3}) = \sqrt{3}-1$

因此$a + 2b = \sqrt{3}-1 + -4 -4\sqrt{3} = -5-3\sqrt{3}$



### 100-02-20

#### Statement

設直線$3x+y=1$與$x+3y=2$之夾角為$\theta$，則$\cos2\theta=$？

$\color{red}{\rm (A)\ \dfrac{-7}{25}}$

$\rm (B)\ \dfrac{-6}{25}$

$\rm (C)\ \dfrac{-1}{5}$

$\rm (D)\ \dfrac{-4}{25}$

$\rm (E)\ \dfrac{-3}{25}$



#### Solution 1

設$n_1 = <3, 1>$，$n_2 = <1, 3>$

則$\cos\theta = \dfrac{n_1 n_2}{|n_1||n_2|} = \dfrac{6}{10} = \dfrac{3}{5}$

因此$\sin\theta = \dfrac{4}{5}$

所以$\cos2\theta = \cos^2(\theta)-\sin^2(\theta) = -\dfrac{7}{25}$，故選$(A)$



#### Solution 2

考慮兩條線的斜率。

$3x + y = 1,\ m_1 = \dfrac{-3}{1} = -3$

$x + 3y = 2,\ m_2 = \dfrac{-1}{3}$



兩條線的斜率相減可形成一個夾角，可以視為$\tan$來考慮。

$\tan(m_1 - m_2) = \dfrac{m_1 - m_2}{1 + m_1 m_2} = \dfrac{-3 - \dfrac{-1}{3}}{1 + 1} = \dfrac{\dfrac{-8}{3}}{2} = \dfrac{-4}{3}$

觀察到求出的這個$\tan$夾角是負的，因此這個夾角是大於$90^{\circ}$的鈍角。

可以依照$\tan(180^{\circ}) = 0$來求得另一個銳角的夾角。

$\dfrac{\dfrac{-4}{3} + \tan\theta}{1-\dfrac{-4}{3}\tan\theta}$，求得銳角$\tan\theta = \dfrac{4}{3}$



由於$\tan\theta = \dfrac{4}{3}$，那麼這個角度會介於$45^{\circ} \sim 90^{\circ}$

因此乘以兩倍後就會大於$90^{\circ}$



用兩倍角公式求出$\tan2\theta = \dfrac{\dfrac{4}{3} + \dfrac{4}{3}}{1 - \dfrac{4}{3}\times\dfrac{4}{3}} = \dfrac{\dfrac{8}{3}}{\dfrac{-7}{9}} = \dfrac{24}{-7}$

由於這個角度介於$90^{\circ} \sim 180^{\circ}$，$y>0$，而$x < 0$，也因此$y = 24,\ x = -7,\ r = \sqrt{24^2+(-7)^2} = 25$

因此$\cos2\theta = \dfrac{-7}{25}$，故選$(A)$



## 101年第2次北科入學數學會考

### 101-02-01

#### Statement

設$\sin\alpha = \dfrac{4}{5}$，$\cos\beta = \dfrac{-5}{13}$，且$0 < \alpha < \dfrac{\pi}{2}$，$\dfrac{\pi}{2} < \beta < \pi$，則$\sin(\alpha - \beta)=$？

$\color{red}{\rm(A)\ \dfrac{-56}{65}}$

$\rm(B)\ \dfrac{-16}{65}$

$\rm(C)\ \dfrac{16}{65}$

$\rm(D)\ \dfrac{27}{65}$

$\rm(E)\ \dfrac{56}{65}$



#### Solution

$\because 0 < \alpha < \dfrac{\pi}{2}$

$\therefore 0 < \sin\alpha< 1,\ 0 < \cos\alpha < 1$

$\cos\alpha = \sqrt{1 - \sin^2\alpha} = \sqrt{1 - \dfrac{16}{25}} = \sqrt{\dfrac{9}{25}} = \dfrac{3}{5}$

$\because \dfrac{\pi}{2} < \beta < \pi$

$\therefore 0 < \sin\beta < 1,\ -1 < \cos\beta < 0$

$\sin\beta = \sqrt{1 - \cos^2\beta} = \sqrt{1 - (\dfrac{-5}{13})^2} = \dfrac{12}{13}$

$\sin(\alpha - \beta) = \sin\alpha\cos\beta - \sin\beta\cos\alpha = \dfrac{4}{5}\times \dfrac{-5}{13} - \dfrac{12}{13}\times \dfrac{3}{5} = \dfrac{-20}{65} - \dfrac{36}{65} = \dfrac{-56}{65}$



### 102-02-02

#### Statement

方程式$2^{x^2}\cdot4^x\cdot16=8^x\cdot 64$之所有解的和為何？

$\rm(A)\ -2$

$\rm(B)\ -1$

$\rm(C)\ 0$

$\color{red}{\rm(D)\ 1}$

$\rm(E)\ 2$



#### Solution

將式子改寫。

$2^{x^2} \cdot 4^x = 8^x \cdot 64$

$\Rightarrow 2^{x^2} \cdot 2^{2x} = 2^{3x} \cdot 2^6$

$\Rightarrow 2^{x^2+2x} = 2^{3x+6}$

兩邊同取$\log_2$，得到$x^2+2x = 3x+6$

也就得到$x^2-x-6=0$，因式分解得到$(x-3)(x+2)=0$

解根得到$x = 3$或$x = -2$，$3 + (-2) = 1$



### 101-02-03

#### Statement

已知$\Gamma$表$f(x,y)=0$所對應之圖形，若$\Gamma$水平方向拉長$2$倍，再往右平移$1$單位，則此新圖形的方程式為何？

$(A)\quad f(\dfrac{x}{2}+1,y) = 0 \\\color{red}(B)\quad f(\dfrac{x-1}{2}, y) = 0\\(C)\quad f(\dfrac{x+1}{2}, y)=0\\(D)\quad f(2x+1, y) =0\\(E)\quad f(2x-1,y)=0$



#### Solution

考慮拉長兩倍，那麼$a$要變大兩倍，因此$x$乘以$\dfrac{1}{2}$

考慮往右平移一單位，那麼座標$x-1$，因此$x$減$1$

因此$f=(\dfrac{x-1}{2}, y) = 0$，故選$(B)$



### 101-02-04

#### Statement

設直線$L$過點$(-1, 1)$且與直線$8x-6y=1$垂直，則此直線方程式為何？

$\rm(A)\ 3x-4y=-1$

$\rm(B)\ 4x+3y=-1$

$\rm(C)\ 4x-3y=-7$

$\color{red}{\rm(D)\ 3x+4y=1}$

$\rm(E)\ x-y=-2$



#### Solution

直線$8x-6y=1$的斜率為$\dfrac{-8}{-6} = \dfrac{4}{3}$

因此造一條與其垂直的直線，這條直線的斜率與其斜率乘積必為$-1$。

$\dfrac{4}{3} \times m = -1, m = \dfrac{-3}{4}$

已知此直線會過點$(-1,1)$，因此$y-1 = \dfrac{-3}{4}(x+1)$

$4y-4 = -3(x+1),\ 3x+4y = 1$



### 101-02-05

#### Statement

過點$(2, -3)$與圓$(x-1)^2+(y+1)^2=5$相切的直線方程式為何？

$\rm(A)\ 2x-y=7$

$\rm(B)\ x+2y=-4$

$\rm(C)\ 2x-3y=13$

$\rm(D)\ 3x-2y=12$

$\color{red}{\rm(E)\ x - 2y = 8}$



#### Solution

從圓的方程式可以知道，圓心為$(1, -1)$且半徑為$\sqrt{5}$。

因此我們可以造過點$(2, -3)$的線，並且距離與圓心剛好為$\sqrt{5}$

可以套用距離公式來得到。

令與圓相切的直線為$y +3 = m(x-2)$

整理後得到$mx - y - 2m -3 = 0$

我們可以套用距離公式，得到$\dfrac{|mx-y-2m-3|}{\sqrt{m^2+(-1)^2}} = \sqrt{5}$

將圓心帶入距離公式，得到$|m+1-2m-3| = \sqrt{5}\sqrt{m^2+1}$

整理後得到$|-m-2| = \sqrt{5m^2+5}$

兩邊平方後得到$(-m-2)^2 = 5m^2-5 \Rightarrow m^2+4m+4 = 5m^2+5$

因此$-4m^2+4m-1$，$m = \dfrac{1}{2}$ (重根)

$y + 3 = \dfrac{1}{2}(x-2)$

$\Rightarrow \ 2y+6 = x-2$

$\Rightarrow \ x-2y-8=0$

$\Rightarrow x - 2y = 8$



### 101-02-06

#### Statement

以$(1, 3+\sqrt{5})$與$(1, 3-\sqrt{5})$為兩焦點且短軸長為$6$之橢圓方程式為何？

$\color{red}{\rm(A)\ \dfrac{(x-1)^2}{9} + \dfrac{(y-3)^2}{14} = 1}$

$\rm(B)\ \dfrac{(x-1)^2}{9}+\dfrac{(y-3)^2}{25}=1$

$\rm(C)\ \dfrac{(x-1)^2}{14}+\dfrac{(y-3)^2}{9} = 1$

$\rm(D)\ \dfrac{(x-3)^2}{9} + \dfrac{(y-1)^2}{14} = 1$

$\rm(E)\ \dfrac{(x-3)^2}{25} + \dfrac{(y-1)^2}{9} = 1$



#### Solution

兩焦點只有$y$軸有變動，因此這是一個貫軸平行$y$軸的橢圓。

中心$(x,y) = (\dfrac{1+1}{2},\dfrac{3+\sqrt{5}+3-\sqrt{5}}{2}) = (1, 3)$

$2c = (3 + \sqrt{5}) - (3 - \sqrt{5}) = 2\sqrt{5},\ c = \sqrt{5}$

$2b = 6, b = 3$

因此$a = \sqrt{3^2+(\sqrt{5})^2} = \sqrt{9 + 5} = \sqrt{14}$

依照$\dfrac{(x-h)}{b} + \dfrac{(y-k)}{a} = 1$列式，得

$\dfrac{(x-1)}{9} + \dfrac{(y-3)}{14} = 1$



### 101-02-07

#### Statement

設$2\log(x-3) - \log2 = \log(x+9)$，則$x^2-10x+12$之值為何？
$(A)\quad 1\\(B)\quad 2\\\color{red}(C)\quad 3\\(D)\quad 4\\(E)\quad 5$



#### Solution

$2\log(x-3) - \log2 = \log(x+9)$

$\Rightarrow \log(\dfrac{x^2-6x+9}{x+9}) = \log(2)$

$\Rightarrow \log(\dfrac{x^2-6x+9}{2x+18}) = 0$

$\Rightarrow \dfrac{x^2-6x+9}{2x+18} = 1$

$\Rightarrow x^2-6x+9 = 2x+18$

$\Rightarrow x^2-8x-9=0$

$\Rightarrow (x+1)(x-9)=0$

得到$x=-1, x=9$

驗根，由於$x=-1$帶進去後，$x-3 < 0$，又因為$\log$的定義域為正整數之集合，故$x=-1$不合。

因此$x = 9$。

$9^2-90+12 = 81-90+12=3$，故選$(C)$。



### 101-02-08

#### Statement

若$0 \le \theta < 2\pi$，則$\cos2\theta+2\cos^2\dfrac{\theta}{2}=1$有幾個解？

$(A)\quad 0\\(B)\quad 1\\(C)\quad 2\\\color{red}(D)\quad 3\\(E)\quad 4$



#### Solution

利用和角公式，可以知道

$\cos(\dfrac{\theta}{2}+\dfrac{\theta}{2}) = \cos^2\dfrac{\theta}{2}-\sin^2\dfrac{\theta}{2} = \cos^2\dfrac{\theta}{2}-(1-\cos^2\dfrac{\theta}{2}) = 2\cos^2(\dfrac{\theta}{2})-1 = \cos\theta$

因此$\cos\theta + 1 = 2\cos^2(\dfrac{\theta}{2})$



且$\cos2\theta = \cos^2\theta-\sin^2\theta = 2\cos^2\theta-1$

$2\cos^2\theta-1+\cos\theta+1=1$

$2\cos^2\theta+\cos\theta =1$

$2\cos^2\theta+\cos\theta-1=0$

令$t = \cos\theta$，則$2t^2+t-1 = 0$，可得$t = \dfrac{1}{2}$或$t = -1$

考慮$t = \cos\theta = \dfrac{1}{2}$，則$\theta = \dfrac{\pi}{3}$或$\theta = \dfrac{-\pi}{3}$

考慮$t = \cos\theta = -1$，則$\theta = \pi$

因此有三組解，故選$(D)$



### 101-02-09

#### Statement

設$a$、$b$、$c$分別表示$\Delta ABC$的$\angle A$、$\angle B$、$\angle C$之對邊長，若$b^2-(c-a)^2 = ca$，則$\angle B = ?$

$(A)\quad 30^{\circ} \\(B)\quad 45^{\circ}\\\color{red}(C)\quad 60^{\circ}\\(D)\quad 120^{\circ}\\(E)\quad 135^{\circ}$



#### Solution

$b^2-(c-a)^2 = ca$

$\Rightarrow b^2 - (c^2-2ac+a^2) = ca$

$\Rightarrow b^2-c^2+2ac-a^2=ca$

$\Rightarrow b^2-c^2-a^2=-ac$

$\Rightarrow a^2+c^2-b^2=ac$

$\Rightarrow \dfrac{a^2+c^2-b^2}{2ac} = \dfrac{1}{2}$

又$\cos B = \dfrac{a^2+c^2-b^2}{2ac} =\dfrac{1}{2}$

因此$\angle B = \dfrac{\pi}{3} = 60^{\circ}$，故選$(C)$。



### 101-02-10

#### Statement

方程式$x^{1+\log_2x} = (2x^3)$之所有解的和為何？

$(A)\quad \dfrac{15}{2} \\ (B)\quad 8 \\\color{red}(C)\quad \dfrac{17}{2}\\(D)\quad 9\\(E)\quad \dfrac{19}{2}$



#### Solution

$x^{1+\log_2 x} = 8x^3$

$\Rightarrow 1+\log_2 x = \log_x (8x^3)$

$\Rightarrow 1+\log_2 x = \dfrac{\log_2 8x^3}{\log_2 x}$

$\Rightarrow \log_2 x + \log^2_2 x = \log_2 8x^3$

$\Rightarrow \log_2 x + \log^2_2 x = 3 + 3\log_2 x$

令$t = \log_2 x $，則$t + t^2 = 3 + 3t$

$\Rightarrow t^2-2t-3=0$

$\Rightarrow t = 3$或$t = -1$

還原$t$，得到$\left\{\begin{array}\ \log_2 x  =3, & x = 8 \\ \log_2 x = -1, & x = \dfrac{1}{2}\end{array}\right.$

因此$8 + \dfrac{1}{2} = \dfrac{17}{2}$，故選$(C)$



### 101-02-11

#### Statement

若$f(x) = \dfrac{x-1}{x}$，且$(f \circ g)(x) = \dfrac{x}{x+1}$，則$g(0) = ?$

$(A)\quad 0\\\color{red}(B)\quad 1\\(C)\quad 2\\(D)\quad 3\\(E)\quad 4$



#### Solution

$f(x) = \dfrac{x-1}{x}$，則$f(g(0)) = \dfrac{x}{x+1} = 0$，因此$\dfrac{x-1}{x} = 1$，因此$g(0) = 1$，故選$(B)$。



### 101-02-12

#### Statement

已知平面上兩點$A(-3, 1)$，$B(3, 5)$，又點$P(a, b)$在直線$2x+y+1=0$且$\overline{PA}=\overline{PB}$，則$a+b=?$

$(A)\quad 5\\(B)\quad 6\\\color{red}(C)\quad 7\\(D)\quad 8\\(E)\quad 9$



#### Solution

將$A, B$兩點帶入直線，確定是否同側或異側。

代入點$A$：$2\cdot (-3)+1+1=-4$

代入點$B$：$2\times3+5+1 = 12$

因此兩點異側。

$2x+y+1=0 \Rightarrow y=-2x-1$

由於$\overline{PA}=\overline{PB}$，因此

$\sqrt{(-3-x)^2+(1-y)^2} = \sqrt{(3-x)^2+(5-y)^2}$

$\Rightarrow (-3-x)^2+(1+2x+1)^2 = (3-x)^2+(5+2x+1)^2$

$\Rightarrow (-3-x)^2+(2x+2)^2=(3-x)^2+(6+2x)^2$

$\Rightarrow 5x^2+14x+13 = 5x^2+18x+45$

$\Rightarrow -4x=32$

$\Rightarrow x = -8$

$\Rightarrow y = 15$

因此$a = -8, b = 15, a + b = 7$，故選$(C)$



### 101-02-13

#### Statement

設二向量$\vec{a} = <2, t^2-3>$，$\vec{b} = <t, -1>$。

若$\vec{a}$和$\vec{b}$的夾角為$\dfrac{\pi}{2}$，且$\vec{b}$的長度不大於$2$，則$t=?$

$(A)\quad -2 \\\color{red}(B)\quad -1\\(C)\quad 2\\(D)\quad 3\\(E)\quad 4$



#### Solution

$\cos\dfrac{\pi}{2} = 0$，因此$|\vec{a}||\vec{b}|\cos\theta = 0$，因此$\vec{a}\cdot \vec{b} = 0$

$\vec{a}\cdot\vec{b} = 2t -t^2+3 = (-t+3)(t+1) =0$

得到$t=3$或$t=-1$

長度不大於$2$，因此我們考慮兩種$t$套進$\vec{b}$的影響

考慮$t=3$，得到$\sqrt{(3)^2+(-1)^2} = \sqrt{10} > 2$，因此$t=3$不合

考慮$t=-1$，得到$\sqrt{(-1)^2+(-1)^2} = \sqrt{2}$

因此$t=-1$，故選$(B)$。



### 101-02-14

#### Statement

設$\alpha + \beta$，$\alpha - \beta$為方程式$x^2-6x+5=0$的兩根，且$\alpha < \beta+2$，則$\beta = ?$

$(A)\quad -2\\(B)\quad -1\\\color{red}(C)\quad 2\\(D)\quad 3\\(E)\quad 4$



#### Solution

利用根與係數，可以知道

$(\alpha+\beta)+(\alpha-\beta) = -(\dfrac{-6}{1}) = 6$

$2\alpha = 6$則$\alpha=3$

$(\alpha-\beta)(\alpha+\beta) = \alpha^2-\beta^2=5$，則$\beta = \pm2$

由於要滿足$\alpha < \beta+2$，所以$\beta=-2$不合。

因此$\beta = 2$，故選$(C)$。



### 101-02-15

#### Statement

設$f$為奇函數，$g$為偶函數，及對所有的$x$，恆有$f(-x) = -f(x)$且$g(-x)=g(x)$。

如果$f$和$g$均為非零函數，則下列何者恆為正確？

$(A)\quad f-g為奇函數$

$\color{red}(B)\quad f\cdot g 為奇函數$

$(C)\quad f^3\cdot g^3為偶函數$

$(D)\quad 2f+3g為偶函數$

$(E)\quad f+g的函數圖形對稱於y軸$



#### Solution

偶函數只有全部非負整數或全部非正整數兩種情況。

因此乘到奇函數只有全部改變函數上的正負號或不改變兩種情況，函數本身依然是奇函數。

故選$(B)$。



### 101-02-16

#### Statement

下列何者為函數$f(x) = \dfrac{1}{\sqrt{x^3-x^2-x+1}}$的定義域？

$(A)\quad \{x | x < -1\} \\ (B)\quad \{x | x > -1\} \\(C)\quad \{x | -1 < x < 1\}\\\color{red}(D)\quad \{x | -1 < x, x \neq 1\} \\(E)\quad \{x | x > 1\}$



#### Solution

$\sqrt{x^3-x^2-x+1} > 0$

$\Rightarrow x^3-x^2-x+1 > 0$

$\Rightarrow (x-1)^2(x+1) > 0$，得到$x \neq 1$且$x\neq -1$

由於$(x-1)^2$恆正，因此我們考慮$(x+1)>0$，得到$x > -1$。

因此$f(x)$的定義域$D(f(x)) = \{x | (x > -1), (x \neq 1)\}$，故選$(D)$



### 101-02-17

#### Statement

設$\dfrac{x^2-10x+8}{x^3-2x^2-4x+8}$的部份分式為$\dfrac{a}{x+2}+\dfrac{b}{x-2}+\dfrac{c}{(x-2)^2}$，則$a-b-c = ?$

$(A)\quad -2\\(B)\quad -1\\(C)\quad 1\\(D)\quad 3\\\color{red}(E)\quad 5$



#### Solution

$\dfrac{x^2-10x+8}{x^3-2x^2-4x+8} \Rightarrow \dfrac{x^2-10x+8}{(x-2)^2(x+2)}$



$x^2-10x+8 = a(x-2)^2+b(x-2)(x+2)+c(x+2)$

令$x=2$，$4-20+8=4c$，得到$c=-2$

令$x=-2$，$16a=4+20+8=32$，得到$a=2$

令$x=0$，$8=4a-4b+2c = 8-4b-4$，得到$b=-1$

$a-b-c=2-(-1)-(-2)=5$，故選$(E)$。



### 101-02-18

#### Statement

設$2x^2+(k-1)x+(k-3) = 0$之一根大於$2$，一根小於$1$，則$k$之範圍為何？

$\color{red}(A)\quad \{k | k < -1\} \\(B)\quad \{k | 1 < k < 3\}\\(C)\quad \{k | -1 < k < 3\}\\(D)\quad \{k | k > 1\}\\(E)\quad \{k | -\infty<k<\infty\}$



#### Solution

$\dfrac{-(k-1)\pm\sqrt{(k-1)^2-4\times2\times(k-3)}}{2\times 2}$

$\Rightarrow \dfrac{-k+1\pm\sqrt{k^2-2k+1-8k+24}}{4}$

$\Rightarrow \dfrac{-k+1\pm\sqrt{k^2-10k+25}}{4}$



一根大於2，因此用$\dfrac{-k+1+\sqrt{k^2-10k+25}}{4}$考慮

因此$-k+1+\sqrt{k^2-10k+25}>8$，$-k+1+(k-5)>8$，得到$k<-1$

一根小於$1$，因此用$\dfrac{-k+1-\sqrt{k^2-10k+25}}{4}$考慮

因此$-k+1-\sqrt{k^2-10k+25}<4$，$-k+1+(k-5)<4$，得到$k\in \R$

取聯集得到$k<-1$，因此$k$的範圍為$\{k | k < -1\}$，故選$(A)$



### 101-02-19

#### Statement

若$f(x) = \sqrt{3-x}$，$g(x) = \sqrt{x-1}$，則$f \circ g$的定義域為何？

$(A)\quad [1, 3] \\(B)\quad [1,4]\\(C)\quad [2, 4]\\(D)\quad [3, 9]\\\color{red}(E)\quad [1, 10]$



#### Solution

$f\circ g = \sqrt{3-\sqrt{x-1}}$

考慮根號內的數字必須要是非負整數，得到$3-\sqrt{x-1} \ge 0$，$x \le  10$

考慮根號內的數字必須要是非負整數，得到$x-1\ge 0$，得到$x \ge 1$

取交集後得到$1 \le x \le 10$，故選$(E)$。



### 101-02-20

#### Statement

若$f(x)=x^3+ax^2+bx+2$能被$x^2+1$整除，則$f(x)$除以$x+1$的餘式為何？

$\color{red}(A)\quad 2\\(B)\quad 4\\(C)\quad 6\\(D)\quad 8\\(E)\quad 10$



#### Solution

利用長除法來做$f(x)$除以$x^2+1$，可以得到商為$(x+a)$且餘數為$(b-1)x+(2-a)$

因為能夠被整除，因此餘數為$0$，得到$b=1$且$a=2$

因此$f(x) = x^3+2x^2+x+2$

除以$x+1$，利用餘式定理，將$x$帶$-1$

因此$f(-1) = (-1)^3+2(-1)^2+(-1)+2 = -1+2+(-1)+2=2$，故選$(A)$



