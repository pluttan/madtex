# Подготовка к экзамену : Математический анализ

<!-- ?\toc -->


## Определения и понятия

1. $\mathbb{N}$ - **Множество натуральных чисел**, состоит из чисел, возникающих при счёте.
1. $\mathbb{Z}$ - **множество целых чисел**, состоит из натуральных чисел, нуля и чисел, противоположных натуральным.
1. $\mathbb{Q}$ - **множество рациональных чисел**, состоит из чисел, представимых в виде ${\Large\frac{z}{n}}, \ z \in \mathbb{Z}, \ n \in \mathbb{N}$. 
1. $\mathbb{I}$ - **множество иррациональных чисел**, состоит из чисел, которые не представимы в виде ${\Large\frac{z}{n}}, \ z \in \mathbb{Z}, \ n \in \mathbb{N}$, такие как $e, \pi, \sqrt{3}$ и т.д..

1. $\mathbb{R}$ - **множество действительных чисел**, состоит из рациональных и иррациональных чисел.

1. $\overline{\mathbb{R}}$ - **расширенное множество действительных чисел**, состоит из действительных чисел с добавлением $\{+\infty\}$ и $\{-\infty\}$.


1. **Окрестностью** $U(x)$ **точки $x$** называют любой интервал, содержащий эту точку.

1. **Проколотой окрестностью $
\overset{\circ}U(x)$ точки $x$** называют окрестность этой точки $U(x)$, за исключением самой точки $x$.  

1. **${\large\varepsilon}$-окрестностью точки $x_0$** (при положительном ${\large\varepsilon}$) называют интервал $(x_0−{\large\varepsilon}, \ x_0+{\large\varepsilon}$).

    $$U_{\large\varepsilon}(x_0) = \{x \in \mathbb{R}: \ x_0 - {\large\varepsilon} < x < x_0 + {\large\varepsilon}\}$$

1. **правой (правосторонней) $\delta$-окрестностью точки** $x_0$ называют полуинтервал $[x_0,\ x_0 + \delta), \ \delta > 0$.

    $$U^+_{\delta}(x_0) = \{x \in \mathbb{R}: \ x_0 \leqslant x < x_0 + {\delta}\}, \ \delta > 0$$

1. **левой (левосторонней) $\delta$-окрестностью точки** $x_0$ называют полуинтервал $(x_0 - \delta,\ x_0], \ \delta > 0$.

    $$U^-_{\delta}(x_0) = \{x \in \mathbb{R}: \ x_0 -\delta < x \leqslant x_0\},\ \delta > 0$$

1. **Окрестностью точки** $+\infty$ называют интервал $(a, +\infty), \ a > 0$.

    $$U(+\infty) = \{x \in \mathbb{R}: \ x > a\}, \ a > 0$$

1. **Окрестностью точки** $-\infty$ называют интервал $(-\infty, -a), \ a > 0$.
    
    $$U(-\infty) = \{x \in \mathbb{R}: \ x < -a\}, \ a > 0$$

1. **Окрестностью** $\infty$ (бесконечности без знака) называют объединение двух интервалов $(-\infty, −a) \cup (a, +\infty),\ a > 0$.

    $$U(\infty) = \{x \in \mathbb{R}: \ | x | > a\}, \ a > 0$$
   
1. **Последовательностью $\{X_n\}$** называется числовая функция натурального аргумента. Если
натуральному числу $n$ при этом поставлено в соответствие число $x_n$, то это число
называется $n$-м элементом последовательности; $n$ называют номером элемента $x_n$.

1. Последовательность чисел $\{X_n\}$ называется **неубывающей**, если $x_{n+1}\geqslant x_n, \ \forall\ n \in \mathbb{N}$.

1. Последовательность чисел $\{X_n\}$ называется **возрастающей**, если $x_{n+1} > x_n, \ \forall\ n \in \mathbb{N}$.

1. Последовательность чисел $\{X_n\}$ называется **невозрастающей**, если $x_{n+1} \leqslant x_n, \ \forall\ n \in \mathbb{N}$.

1.  Последовательность чисел $\{X_n\}$ называется **убывающей**, если $x_{n+1} < x_n, \ \forall\ n \in \mathbb{N}$.

1.  Неубывающие, невозрастающие, убывающие и возрастающие последовательности называют **монотонными**.
1.  Последовательность называется **постоянной**, если $ \forall n \in \mathbb{N}: \ x_n = c, \ c \in \mathbb{R}$.

1.  Последовательность $\{X_n\}$ называется **ограниченной сверху**, если $\exists M \in \mathbb{R}$, такое, что $\forall n \in \mathbb{N}: \ x_n \leqslant M$. 

1.  Последовательность $\{X_n\}$ называется **ограниченной снизу**, если $\exists M \in \mathbb{R}$, такое, что $\forall n \in \mathbb{N}: \ x_n \geqslant M$.

1.  Последовательность, ограниченная и сверху и снизу, называют **ограниченной**:
$\exists M > 0, \ M \in \mathbb{R}$, такое, что $\forall n \in \mathbb{N}: \ | x_n|  \leqslant M$. 

1.  Число $a$ называется **пределом числовой последовательности** $\{X_n\}$, если для любого, сколь угодно малого положительного ${\large\varepsilon}$ существует такой номер $N$, зависящий от ${\large\varepsilon}$, что для всех $n > N$ выполняется неравенство $| a - x_n|  < {\large\varepsilon}$.

    $$\lim\limits_{n \to \infty}x_n = a \iff \forall {\large\varepsilon}>0 \ \ \exists N = N({\large\varepsilon}) \in \mathbb{N}: \ \forall n > N \Rightarrow | x_n - a|  < {\large\varepsilon}$$

1. Числовая последовательность называется **сходящейся**, если существует предел этой последовательности, и он конечен.

1. Последовательность $\{X_n\}$ называется **фундаментальной**, если для любого ${\large\varepsilon} > 0$
существует номер $N = N({\large\varepsilon})$ такой, что при любых $m \geqslant N$ и $n \geqslant N$ выполняется
неравенство $| x_m − x_n|  < {\large\varepsilon}$. 

1. Число $a$ называется **пределом функции** $f(x)$ при $x \rightarrow x_0$, если для любого ${\large\varepsilon} > 0$ существует положительное число $\delta = \delta ({\large\varepsilon})$ такое, что для любого $x \in \overset{\circ}U_\delta(x_0)$ выполняется неравенство $| f(x) - a|  < {\large\varepsilon}$ (определение по Коши). 
    $$\lim\limits_{x \to x_0} f(x) = a \iff \forall{\large\varepsilon} > 0 \ \ \exists \delta = \delta({\large\varepsilon}) > 0 : \ \forall x \in \overset{\circ}U_\delta(x_0) \Rightarrow | f(x) - a|  < {\large\varepsilon}$$

1. Число $a$ называется **пределом функции** $f(x)$ при $x \rightarrow x_0$, если для любой последовательности $\{X_n\}$ точек из $\overset{\circ}U(x_0)$, для которой $\lim\limits_{n \to \infty}x_n = x_0$, выполняется равенство $\lim\limits_{n \to \infty}\{f(x_n)\} = a$ (определение по Гейне).
    $$\lim\limits_{x \to x_0}f(x) = a \iff \{\forall x_n \in \overset{\circ}U(x_0), \ n \in \mathbb{N}\} \ \cap \ \lim\limits_{n \to \infty}{x_n} = x_0 : \ 
    \lim\limits_{n \to \infty}\{f(x_n)\} = a$$

2. Число $a$ называется **правым (правосторонним) пределом функции** f(x) при $x \rightarrow x_0 +$, если для любого ${\large\varepsilon} > 0$ существует $\delta = \delta({\large\varepsilon}) > 0$ такое, что при любом $x \in {\overset{\circ\hspace{22pt}}{U^+_\delta(x_0)}} \ \ (т.е. \ x_0 < x < x_0 + \delta)$, выполняется неравенство $| f(x) − a|  < {\large\varepsilon}$.  

    $$\lim\limits_{x \to x_0 +} f(x) = a \iff \forall{\large\varepsilon} > 0 \ \ \exists \delta = \delta({\large\varepsilon}) > 0 : \ \forall x \in {\overset{\circ\hspace{22pt}}{U^+_\delta(x_0)}}  \Rightarrow | f(x) - a|  < {\large\varepsilon}$$

2. Число $a$ называется **левым (левосторонним) пределом функции** f(x) при $x \rightarrow x_0 -$, если для любого ${\large\varepsilon} > 0$ существует $\delta = \delta({\large\varepsilon}) > 0$ такое, что при любом $x \in {\overset{\circ\hspace{22pt}}{U^-_\delta(x_0)}}, \ \ (т.е. \ x_0 - \delta < x < x_0)$ выполняется неравенство $| f(x) − a|  < {\large\varepsilon}$.

    $$\lim\limits_{x \to x_0 -} f(x) = a \iff \forall{\large\varepsilon} > 0 \ \ \exists \delta = \delta({\large\varepsilon}) > 0 : \ \forall x \in {\overset{\circ\hspace{22pt}}{U^-_\delta(x_0)}}  \Rightarrow | f(x) - a|  < {\large\varepsilon}$$

2. Функцию $f(x)$ называют **ограниченной на множестве $D$**, если существует такое число $M > 0$, что для любых $x \in D$ выполняется неравенство $| f(x)|  \leqslant M$.

2. Функцию $f(x)$ называют **ограниченной** (на области определения $D_f$), если существует такое число $M > 0$, что для любых $x \in D_f$ выполняется неравенство $| f(x)|  \leqslant M$.


3. Функцию $f(x)$ называют **локально ограниченной в окрестности точки $a$**, если существует такое число $M > 0$ и такая окрестность $\overset{\circ}U_\delta(a)$, что для любых $x \in \overset{\circ}U_\delta(a)$ выполняется неравенство $| f(x)|  \leqslant M$.

4. Функцию $f(x)$ называют **бесконечно малой** при $x \rightarrow x_0, \ x_0 \in \overline{\mathbb{R}}$, если $\lim\limits_{x \to x_0} f(x) = 0$.

5. Функцию $f(x)$ называют **бесконечно большой** при $x \rightarrow x_0, \ x_0 \in \overline{\mathbb{R}}$, если $\lim\limits_{x \to x_0} f(x) = \infty$. 

6. $\lim\limits_{x \to 0} {\Large\frac{sin(x)}{x}} = 1$ - **первый замечательный предел**.

7. $\lim\limits_{x \to \infty} \bigg(1 + {\Large\frac{1}{x}}\bigg)^{\large x}$ - **второй замечательный предел**.


8. Функции $\alpha(x)$ и $\beta(x)$ называют **сравнимыми** бесконечно малыми при $x \rightarrow x_0$, если существует хотя бы один из пределов $\lim\limits_{x \to x_0} {\large \frac{\alpha(x)}{\beta(x)}}$ или $\lim\limits_{x \to x_0} {\large \frac{\beta(x)}{\alpha(x)}}$.

9. Функции $\alpha(x)$ и $\beta(x)$ называют **несравнимыми** бесконечно малыми при $x \rightarrow x_0$, если не существует ни конечного, ни бесконечного предела их отношения при $x \rightarrow x_0$.

10. Функции $\alpha(x)$ и $\beta(x)$ называют **бесконечно малыми одного порядка** при $x \rightarrow x_0$ и записывают $\alpha(x) = O(\beta(x))$, если существует отличный от нуля конечный предел отношения $\alpha(x)/\beta(x)$, при $x \rightarrow x_0$.
    $$\alpha(x) = O(\beta(x)) \ \text{при} \ x \rightarrow x_0 \iff \exists \lim\limits_{x \to x_0} {\frac{\alpha(x)}{\beta(x)}} = c \in \mathbb{R} \backslash \{0\}$$


4. Функцию $\alpha(x)$ называют **бесконечно малой более высокого порядка** малости по сравнению с $\beta(x)$ при $x \rightarrow x_0$ и записывают $\alpha(x) = o(\beta(x))$, если существует и равен нулю предел отношения $\alpha(x) / \beta(x)$, при $x \rightarrow x_0$.
    $$\alpha(x) = o(\beta(x)) \ \text{при} \ x \rightarrow x_0 \iff \exists \lim\limits_{x \to x_0} {\frac{\alpha(x)}{\beta(x)}} = 0$$

4. Функцию $\alpha(x)$ называют **бесконечно малой более низкого порядка** малости по сравнению с $\beta(x)$ при $x \rightarrow x_0$, если предел отношения $\alpha(x) / \beta(x)$, при $x \rightarrow x_0$, равен бесконечности.

4. Функции $\alpha(x)$ и $\beta(x)$ называют **эквивалентными** бесконечно малыми при $x \rightarrow x_0$, если предел их отношения при $x \rightarrow x_0$ равен 1.

    $$\alpha(x) \sim \beta(x) \ \text{при} \ x \rightarrow x_0 \iff \lim\limits_{x \to x_0}{\frac{\alpha(x)}{\beta(x)}} = 1$$

4. Функцию $\alpha(x)$ называют **бесконечно малой $k$-ого порядка** малости относительно $\beta(x)$ при $x \rightarrow x_0$, а число $k \ (k > 0)$ - **порядком малости** $\alpha(x)$ относительно $\beta(x)$ при $x \rightarrow x_0$, если функции $\alpha(x)$ и $\beta^k(x)$ являются бесконечно малыми одного порядка при $x \rightarrow x_0$, т.е.

    $$\lim\limits_{x \to x_0} {\frac{\alpha(x)}{\beta^k(x)}} = c \in \mathbb{R} \backslash \{0\}$$

4. Функцию $u(x)$ называют **бесконечно большой $k$-ого порядка** роста относительно $w(x)$ при $x \rightarrow x_0$, а число $k \ (k > 0)$ - **порядком роста** $u(x)$ относительно $w(x)$ при $x \rightarrow x_0$, если функции $u(x)$ и $w^k(x)$ являются бесконечно большими одного порядка при $x \rightarrow x_0$, т.е. 
    $$\lim\limits_{x \to x_0} {\frac{u(x)}{w^k(x)}} = c \in \mathbb{R} \backslash \{0\}$$

    <!-- правильно? -->
4. **Главная часть суммы бесконечно малых функций** - это слагаемое более низкого порядка малости по сравнению с каждым из остальных слагаемых.

4. **Приращением аргумента** в точке $x_0$ называется изменение аргумента функции от значения $x_0$ к другому значению x,
    $$\Delta x = x - x_0$$

4. **Приращением функции** в точке $x_0$ называется $\Delta y = f(x_0 + \Delta x) - f(x_0)$.

4. Функция $f(x)$ называется **непрерывной в точке $x_0$**, если в этой точке существует конечный предел функции и он совпадает с значением функции в этой точке, т.е. $\exists \lim\limits_{x \to x_0}f(x) = f(x_0)$.

4. Функция $f(x)$ называется **непрерывной в точке $x_0$ справа**, если в этой точке существует конечный *правый* предел функции и он совпадает с значением функции в этой точке, т.е. $\exists \lim\limits_{x \to x_0+}f(x) = f(x_0)$.

4. Функция $f(x)$ называется **непрерывной в точке $x_0$ слева**, если в этой точке существует конечный левый предел функции и он совпадает с значением функции в этой точке, т.е. $\exists \lim\limits_{x \to x_0-}f(x) = f(x_0)$.

4. Функция $f(x)$ **непрерывна на интервале $(a, b)$**, если она непрерывна в каждой его точке.

4. Функция $f(x)$ **непрерывна на отрезке $[a, b]$**, если она непрерывна на интервале $(a, b)$, в точке $a$ - непрерывна справа, т.е. $\lim\limits_{x \to a+}f(x) = f(a)$, в точке $b$ - непрерывна слева, т.е. $\lim\limits_{x \to b-}f(x) = f(b)$.

4. Если данная функция $f(x)$ не является непрерывной в точке $x_0$, то $x_0$ называется **точкой разрыва** функции $f(x)$.

4. **Точкой разрыва первого рода** называют такую точку разрыва функции, в которой существуют оба односторонних предела этой функции и они конечны, но они не равны между собой.

4. **Точкой разрыва второго рода** называют такую точку разрыва функции, в которой хотя бы один из односторонних пределов функции не существует (в частности, равен бесконечности).

5. Если $x_0$ — точка разрыва функции первого рода и односторонние пределы функции в этой точке равны между собой, но не равны значению функции в этой точке, то такой разрыв называют **устранимым**, а точку $x_0$ - **точкой устранимого разрыва**.

5. Если $x_0$ — точка разрыва функции первого рода и односторонние пределы функции в этой точке не равны между собой, то такой разрыв называют **неустранимым**, а точку $x_0$ - **точкой неустранимого разрыва**. 

5. Если существует конечный предел $\lim\limits_{\Delta x \to 0} {\large\frac{f(x_0 + \Delta x) − f(x_0)}{\Delta x}}$, то он называется **производной функции $f(x)$ в точке** $x_0$ и обозначается $f'(x0)$.

5. Если $f(x)$ определена в правосторонней окрестности точки $x_0$ и если $\exists \lim\limits_{\Delta x \to 0+}{\large\frac{f(x_0+\Delta x) - f(x_0)}{\Delta x}}$, то этот предел называется **правой производной функции $f(x)$ в $x_0$** и обозначается $f'_+(x)$.

5. Если $f(x)$ определена в левосторонней окрестности точки $x_0$, и если $\exists \lim\limits_{\Delta x \to 0-}{\large\frac{f(x_0+\Delta x) - f(x_0)}{\Delta x}}$, то этот предел называется **левой производной функции $f(x)$ в $x_0$** и обозначается $f'_-(x)$.

6. Пусть функция $y = f(x)$ определена в некоторой окрестности точки $x_0$. Функция называется **дифференцируемой в точке $x_0$**, если ее приращение $\Delta y$ в точке $x_0$ представимо в следующем виде:
$\Delta y = A\Delta x + \alpha(\Delta x)\Delta x$, где $A$ - некоторое число, не зависящее от $\Delta x$, а $\lim\limits_{\Delta x \to 0}\alpha(\Delta x) = 0$.

6. Линейная от $\Delta x$ функция $A\Delta x$ называется **дифференциалом функции $f(x)$ в точке $x_0$**.

6. **Дифференциалом $n$-го порядка** называется дифференциал от дифференциала $n-1$ порядка, т.е. $$d^{\ n}y = d(d^{\ n-1}y) = f^{(n)}(x)dx^n$$

6. **Производная $n$-ого порядка** от функции $y = f(x)$, есть производная от производной $n-1$ порядка, т.е. $$f^{(n)} = (f^{n-1}(x))'$$

6. Функция $f(x)$ называется **возрастающей на интервале** $(a, b)$, если $\forall x_1, x_2 \in (a, b)$, таких что $x_2 > x_1$, выполняется неравенство $f(x_2)>f(x_1)$.

6. Функция $f(x)$ называется **невозрастающей на интервале** $(a, b)$, если $\forall x_1, x_2 \in (a, b)$, таких что $x_2 > x_1$, выполняется неравенство $f(x_2)\leqslant f(x_1)$.

6. Функция $f(x)$ называется **убывающей на интервале** $(a, b)$, если $\forall x_1, x_2 \in (a, b)$, таких что $x_2 > x_1$, выполняется неравенство $f(x_2)<f(x_1)$.

6. Функция $f(x)$ называется **неубывающей на интервале** $(a, b)$, если $\forall x_1, x_2 \in (a, b)$, таких что $x_2 > x_1$, выполняется неравенство $f(x_2)\geqslant f(x_1)$.

6. Функция $f(x)$ называется **монотонной**, если она невозрастающая или неубывающая.

6. Функция $f(x)$ называется **строго монотонной**, если она возрастающая или убывающая.

6. Точка $x_0$ называется **точкой локального минимума** функции $f(x)$, если $\exists U_{\delta}(x_0)$, такая что $\forall x \in U_{\delta}(x_0): \ f(x_0) \leqslant f(x)$.

6. Точка $x_0$ называется **точкой локального максимума** функции $f(x)$, если $\exists U_{\delta}(x_0)$, такая что $\forall x \in U_{\delta}(x_0): \ f(x_0) \geqslant f(x)$.

6. Точка $x_0$ называется **точкой строгого локального минимума** функции $f(x)$, если $\exists \overset{\circ}{U}_{\delta}(x_0)$, такая что $\forall x \in \overset{\circ}{U}_{\delta}(x_0): \ f(x_0) < f(x)$.

6. Точка $x_0$ называется **точкой строгого локального максимума** функции $f(x)$, если $\exists \overset{\circ}{U}_\delta(x_0)$, такая что $\forall x \in \overset{\circ}{U}_\delta(x_0): \ f(x_0) > f(x)$.

6. **Точками локального экстремума** называются точки локального максимума и строгого локального максимума, локального минимума и строгого локального минимума.

6. **Точками строгого локального экстремума** называются точки строгого локального максимума и минимума.

6. Точку $x_0$ из области определения функции $f(x)$ называют **критической**, если производная в ней равна 0 или не сущестует вовсе.

6. Точку $x_0$ из области определения функции $f(x)$ называют **стационарной**, если $f'(x_0) = 0$.

6. Прямая $Ax + By + C = 0$ называется **асимптотой** графика $y = f(x)$, если расстояние от точки $M(x, f(x))$ графика функции до этой прямой стремится к 0 при бесконечном удалении точки $M$ от начала координат. 

6. Прямая $x = a$ называется **вертикальной асимптотой** графика функции
$y = f(x)$, если хотя бы один из пределов $\lim\limits_{x \to a+(-)}f(x) = \infty$ 

6. Прямая $y = kx + b$ называется **правой наклонной асимптотой** графика функции $y = f(x)$, если эту функцию можно представить в виде $f(x) = kx + b + \alpha(x)$, где $k, b \in \mathbb{R}$ и $\alpha(x)$ - бесконечно малая функция при $x \rightarrow +\infty$.

6. Прямая $y = kx + b$ называется **левой наклонной асимптотой** графика функции $y = f(x)$, если эту функцию можно представить в виде $f(x) = kx + b + \alpha(x)$, где $k, b \in \mathbb{R}$ и $\alpha(x)$ - бесконечно малая функция при $x \rightarrow -\infty$.

6. Пусть функция $f(x)$ дифференцируема на интервале $(a, b)$. График функции $y = f(x)$ имеет на интервале $(a, b)$ **выпуклость вверх**, если он лежит не выше любой касательной к графику на (a, b).

6. Пусть функция $f(x)$ дифференцируема на интервале $(a, b)$. График функции $y = f(x)$ имеет на интервале $(a, b)$ **выпуклость вниз**, если он лежит не ниже любой касательной к графику на (a, b).

6. Точка $x_0 \in (a,b)$ называется точкой перегиба функции $f(x)$, если эта функция непрерывна в точке $x_0$ и если $\exists \delta > 0$ такое, что направления выпуклостей функции $f(x)$ на интервалах $(x_0-\delta; x_0)$ и $(x_0; x_0+\delta)$ различны.


## Вопросы для подготовки к экзамену

### *Теорема (о единственности предела сходящейся последовательности)*

Если последовательность имеет предел, то этот предел - единственный.

*Доказательство (от противного)*

Пусть $a, b \in \mathbb{R}, \ a \neq b$, где $a$ и $b$ - пределы сходящейся последовательности $\{X_n\}$:
$$\lim\limits_{n \to \infty} x_n = a,\ \lim\limits_{n \to \infty} x_n = b, \ a \neq b$$
По определению предела: 
$$\forall {\large\varepsilon} > 0, \ \exists N_1 = N_1({\large\varepsilon}) \in \mathbb{N} : \ \forall n > N_1 \Rightarrow  | x_n - a|  < {\large\varepsilon} $$
$$\forall {\large\varepsilon} > 0, \ \exists N_2 = N_2({\large\varepsilon}) \in \mathbb{N} : \ \forall n > N_2 \Rightarrow  | x_n - b|  < {\large\varepsilon} $$

Примем ${\large\varepsilon} = {\large\frac{| b - a| }{3}}$ и при $n > max(N_1, \ N_2)$ получим 
$$| b - a|  = | x_n - a + b - x_n|  \leqslant | x_n - a|  + | b - x_n|  = | x_n - a|  + | x_n - b|  \Rightarrow | b - a|  < 2{\large\varepsilon}$$ 
Или $| b-a|  < 2 \cdot {\large\frac{| b - a| }{3}}$, т.е. $| b-a|  < \frac{2}{3}| b - a| $, $\frac{1}{3}| b-a|  < 0$, чего не может быть $\Rightarrow$ $a \neq b$ - неверно, т.е. $a = b \Rightarrow$ предел единственный. Теорема доказана.

### *Теорема (об ограниченности сходящейся последовательности)*

Всякая сходящаяся последовательность является ограниченной.

*Доказательство*

Пусть $\{X_n\}$ - сходящаяся последовательность. Тогда по определению, у нее существует конечный предел 
$$\lim\limits_{n \to \infty}x_n = a \iff \forall {\large\varepsilon} > 0 \ \exists N = N({\large\varepsilon})\in \mathbb{N}: \ \forall n > \mathbb{N} \Rightarrow | x_n - a|  < {\large\varepsilon},$$
$$-{\large\varepsilon}+a < x_n < {\large\varepsilon} + a$$
Обозначим через $A$ максимальное число среди $| x_1| , | x_2| , ..., | x_n| , | a-{\large\varepsilon}| , | a + {\large\varepsilon}| $, т.е.
$$A = max(| x_1| , | x_2| , ..., | x_n| , | a-{\large\varepsilon}| , | a + {\large\varepsilon}| )$$
Тогда $\forall n \in \mathbb{N}$ выполняется $| x_n|  < A, \Rightarrow$ последовательность ограничена. Теорема доказана.

     

### *Теорема (о локальной ограниченности функции, имеющей конечный предел)*

Если функция
$f(x)$ имеет конечный предел при $x \rightarrow x_0$, то $f(x)$ локально ограничена.

*Доказательство*

По условию $\exists$ конечный предел $\lim\limits_{x \to x_0}f(x) = a$, тогда
$$\forall {\large\varepsilon} > 0 \ \exists\delta=\delta({\large\varepsilon} )>0: \ \forall x \in \overset{\circ}U_\delta(x_0) \Rightarrow | f(x) - a|  < {\large\varepsilon}$$
Пусть ${\large\varepsilon} = 1$, тогда $| f(x)|  - | a|  \leqslant | f(x) - a|  < 1$, а значит
$$\forall x \in \overset{\circ}U_\delta(x_0) \Rightarrow | f(x)|  <1 + | A|  = const \overset{по\ опр.}{\Rightarrow}$$ 
$f(x)$ является локально ограниченной в окрестности точки $x_0$. Теорема доказана.

### *Теорема (о сохранении функцией знака своего предела)*

Если $\lim\limits_{x \to x_0} f(x) = A \neq 0$, то $\exists \overset{\circ}U_\delta(x_0): \ \forall x \in \overset{\circ}U_\delta(x_0)$ функция $f(x)$ сохраняет знак своего предела.

*Доказательство*

По условию $\exists$ конечный $\lim\limits_{x \to x_0} f(x) = a > 0 \overset{по\ опр.}{\Rightarrow}$
$$\forall {\large\varepsilon} > 0 \ \exists\delta=\delta({\large\varepsilon} )>0: \ \forall x \in \overset{\circ}U_\delta(x_0) \Rightarrow | f(x) - a|  < {\large\varepsilon}$$

* в случае $a > 0$ выбираем ${\large\varepsilon} = {\Large\frac{a}{2}}$, тогда 
$$| f(x) - a|  < {\frac{a}{2}}$$
$$-{\frac{a}{2}}< f(x) - a < {\frac{a}{2}}$$
$${\frac{a}{2}}< f(x) < {\frac{3a}{2}}$$
Следовательно $f(x) > {\Large\frac{a}{2}}>0$, т.е. данная функция положительна при $x \in \overset{\circ}U_\delta(x_0)$.

* в случае $a < 0$ выбираем ${\large\varepsilon} = -{\Large\frac{a}{2}}$, тогда 
$$| f(x) - a|  < - {\frac{a}{2}}$$
$${\frac{a}{2}}< f(x) - a < -{\frac{a}{2}}$$
$${\frac{3a}{2}}< f(x) < {\frac{a}{2}}$$
Следовательно $f(x) < {\Large\frac{a}{2}}< 0$, т.е. данная функция отрицательна при $x \in \overset{\circ}U_\delta(x_0)$. Теорема доказана.

### *Теорема (о предельном переходе в неравенстве)*

Пусть функции $f(x)$ и $g(x)$ определены в проколотой окрестности $\overset{\circ}U(x_0)$ точки $x_0$, причем для любого $x \in \overset{\circ}U(x_0)$ выполняется неравенство $f(x) \geqslant g(x)$. Тогда, если эти функции имеют пределы $a = \lim\limits_{x \to x_0}f(x)$
и $b = \lim\limits_{x \to x_0}g(x)$, то $a \geqslant b$.

*Доказательство*

По условию $\forall x \in \overset{\circ}U(x_0): \ f(x) \geqslant g(x) \Rightarrow f(x) - g(x) \geqslant 0$, тогда по теореме о сохранении функцией знака своего предела:
$$\lim\limits_{x \to x_0}(f(x) - g(x)) \geqslant 0 \Rightarrow \lim\limits_{x \to x_0}f(x) - \lim\limits_{x \to x_0}g(x) = a - b \geqslant 0, \Rightarrow a \geqslant b$$
Теорема доказана.

### *Теорема (о пределе промежуточной функции)*

Пусть для всех $x$ из некоторой проколотой окрестности $\overset{\circ}U(x_0)$ точки $x_0$ выполняется двойное неравенство
$f(x) \leqslant g(x) \leqslant h(x)$, и пусть существуют пределы $\lim\limits_{x \to x_0}f(x)$ и $\lim\limits_{x \to x_0}h(x)$, равные одному и тому же числу $a$. Тогда и $\lim\limits_{x \to x_0}g(x) = a$.

*Доказательство*
    
По условию $\exists \lim\limits_{x \to x_0}f(x) = a$, $\lim\limits_{x \to x_0}h(x) = a$, тогда по определению предела функции, 
$$\forall {\large\varepsilon}  > 0 \ \exists \delta_1= \delta_1 ({\large\varepsilon} ) > 0: \ \forall x \in \overset{\circ}U_{\delta_1}(x_0) \Rightarrow | f(x) - a|  < {\large\varepsilon}$$
$$\text{т.е.} \ \ a - {\large\varepsilon} < f(x) < a + {\large\varepsilon}$$
$$\forall {\large\varepsilon}  > 0 \ \exists \delta_2= \delta_2 ({\large\varepsilon} ) > 0: \ \forall x \in \overset{\circ}U_{\delta_2}(x_0) \Rightarrow | h(x) - a|  < {\large\varepsilon}$$
$$\text{т.е.} \ \ a - {\large\varepsilon} < h(x) < a + {\large\varepsilon}$$

Тогда при $x \in \overset{\circ}U_{\delta}(x_0), \ \delta = min(\delta_1, \delta_2)$, выполняется неравенство
$$a - {\large\varepsilon} < f(x) \leqslant g(x) \leqslant h(x) < a+ {\large\varepsilon}$$
$$a - {\large\varepsilon} <  g(x) < a+ {\large\varepsilon}$$
$$| g(x) - a|  < {\large\varepsilon}$$

Таким образом, получаем
$$\forall {\large\varepsilon} > 0 \ \exists \delta = \delta({\large\varepsilon}) > 0: \ \forall x \in \overset{\circ}U_{\delta}(x_0) \Rightarrow | g(x) - a|  < {\large\varepsilon} \iff \lim\limits_{x \to x_0} g(x) = a$$
Теорема доказана.

### *Теорема (о пределе произведения функций)*

Если $\exists$ конечные пределы $\lim\limits_{x \to x_0}f(x)=a$ и $\lim\limits_{x \to x_0}g(x) = b$, то $\lim\limits_{x \to x_0}(f(x)\cdot g(x)) = a\cdot b = \lim\limits_{x \to x_0}f(x)\cdot \lim\limits_{x \to x_0}g(x)$.

*Доказательство*

По условию $\exists$ конечные пределы $\lim\limits_{x \to x_0}f(x)=a$ и $\lim\limits_{x \to x_0}g(x) = b$, тогда по теореме о связи функции, ее предела и бесконечно малой имеем
$$f(x) = a + \alpha(x), \ \text{где} \ \alpha(x) - \text{бесконечно малая функция при} \ x \rightarrow x_0 $$ 
$$g(x) = b + \beta(x), \ \text{где} \ \beta(x) - \text{бесконечно малая функция при} \ x \rightarrow x_0 $$
Тогда
$$f(x)\cdot g(x) = (a + \alpha(x))\cdot(b + \beta(x)) = a\cdot b + a\cdot \beta(x) + \alpha(x)\cdot b + \alpha(x)\cdot \beta(x)$$
$$\lim\limits_{x \to x_0}(f(x)\cdot g(x)) = \lim\limits_{x \to x_0}(a\cdot b + \underbrace{a\cdot \beta(x)}_{б.м.\ при \ x \rightarrow x_0} + \underbrace{\alpha(x)\cdot b}_{б.м.\ при \ x \rightarrow x_0} + \underbrace{\alpha(x)\cdot \beta(x)}_{б.м.\ при \ x \rightarrow x_0}) = \lim\limits_{x \to x_0}(a\cdot b) = a\cdot b = \lim\limits_{x \to x_0}f(x) \cdot \lim\limits_{x \to x_0}g(x)$$
Теорема доказана.

### *Теорема (о пределе сложной функции)*

Если функция $y = f(x)$ имеет в точке $x = a$ конечный предел, равный $b$, и $f(x) \neq b$ в некоторой проколотой окрестности $\overset{\circ}U(a)$ этой точки, а функция $g(y)$ имеет в точке $b$ конечный предел $c$, то сложная функция $g(f(x))$ имеет $\lim\limits_{x \to a}g(f(x)) = c$.

*Доказательство*

По определению предела функции по Гейне имеем:
$$\exists \lim\limits_{x \to a}f(x) = b \iff \{\forall x_n \in \overset{\circ}U(a), \ n \in \mathbb{N}\} \ \cap \ \lim\limits_{n \to \infty}{x_n} = a : \ \lim\limits_{n \to \infty}\{f(x_n)\} = b$$
$$\exists \lim\limits_{y \to b}g(y) = c \iff \{\forall y_n \in \overset{\circ}U(b), \ n \in \mathbb{N}\} \ \cap \ \lim\limits_{n \to \infty}{y_n} = b : \ \lim\limits_{n \to \infty}\{g(y_n)\} = c$$

Пусть $\{X_n\}$ - произвольная последовательность, стремящаяся к точке $a$  и $x_n \neq a \ \forall n \in \mathbb{N}$. Тогда $\lim\limits_{n \to \infty}{\{f(x_n)\}} = b$, но $f(x_n) \neq b \ \forall n \in \mathbb{N}$. Пусть $y_n = f(x_n)$. Поскольку $\lim\limits_{n \to \infty}{\{y_n\}} = b$ и $y_n \neq b \ \forall n \in \mathbb{N}$, имеем $\lim\limits_{n \to \infty}{\{g(y_n)\}} = c$, т.е.
$$\{\forall x_n \in \overset{\circ}U(a), \ n \in \mathbb{N}\} \ \cap \ \lim\limits_{n \to \infty}{x_n} = a : \ \lim\limits_{n \to \infty}\{g(f(x_n))\} = c \iff \lim\limits_{n \to \infty} g(f(x)) = c$$
Теорема доказана.

### *Вывод первого замечательного предела*

> $$\lim\limits_{x \to 0} {\frac{sin(x)}{x}} = 1$$

![150pt](img\sinx.png)

Пусть $0 < x < {\Large\frac{\pi}{2}}$. Рассмотрим окружность радиуса $R$ с центром в начале координат,
пересекающую ось абсцисс в точке $A$, и пусть угол $\angle AOB$ равен $x$ (радиан). Пусть, далее,
$CA$ — перпендикуляр к этой оси, $C$ — точка пересечения с этим перпендикуляром продолжения отрезка $OB$ за точку $B$. Тогда
$$S_{\triangle OAB} < S_{сектор \ OAB} < S_{\triangle OAC}$$
$$\frac{1}{2}R^2sin(x) <\frac{1}{2}R^2x < \frac{1}{2}R^2tg(x)$$
$$sin(x) < x < tg(x)$$
$$1 < \frac{x}{sin(x)} < \frac{1}{cos(x)}$$
$$1 > \frac{sin(x)}{x} > cos(x), \ \text{при} \ x \in (0, \frac{\pi}{2})$$

Рассмотрим $x \in (-{\Large\frac{\pi}{2}}, 0)$. Сделаем замену $\beta = -x$, таким образом $\beta \in (0, {\Large\frac{\pi}{2})}$, а значит справедливо следующее неравенство:
$$1 > \frac{sin(\beta)}{\beta} > cos(\beta)$$
Вернемся к замене $\beta = -x$
$$1 > \frac{sin(-x)}{-x} > cos(-x)$$
$$1 > \frac{-sin(x)}{-x} > cos(x)$$
$$1 > \frac{sin(x)}{x} > cos(x) \ \text{при} \ x \in (-{\frac{\pi}{2}}, 0)$$
Таким образом, полученное неравенство справедливо для $x \in ({\Large-{\frac{\pi}{2}}}, 0)\cup(0, {\Large\frac{\pi}{2}})$.
Перейдем к пределу при $x \rightarrow 0$:


$$\begin{rcases}\lim\limits_{x \to 0}cos(x) = 1

\\ \lim\limits_{x \to 0}1 = 1
\end{rcases} \Rightarrow \ \text{(по т. о пределе промежуточной функции)} \ \lim\limits_{x \to 0}\frac{sin(x)}{x} = 1 $$

### *Теорема (о связи функции, ее предела и бесконечно малой)*
Равенство $\lim\limits_{x \to x_0}f(x) = a$ имеет место $\iff f(x) = a + \alpha(x)$, где $\alpha(x) - \text{бесконечно малая функция при } x \rightarrow x_0$.

*Доказательство*

$(\Rightarrow)$

По условию $\exists$ конечный $\lim\limits_{x \to x_0}f(x) = a$, тогда по определению
$$\forall{\large\varepsilon} > 0 \ \exists \overset{\circ}U_\delta(x_0): \ \forall x \in \overset{\circ}U_\delta(x_0) \Rightarrow |f(x) - a| <{\large\varepsilon}$$

Обозначим $f(x) - a = \alpha(x)$. Тогда $|\alpha(x)| < {\large\varepsilon}\ \ \forall x \in \overset{\circ}U_\delta(x_0) \overset{по \ опр.}\Rightarrow \lim\limits_{x \to x_0}\alpha(x) = 0,$ т.е. $\alpha(x)$ - бесконечно малая функция при $x \rightarrow x_0$. 

Но $\alpha(x) = f(x) - a \Rightarrow f(x) = a + \alpha(x), \text{ где } \lim\limits_{x \to x_0}\alpha(x) = 0$.

$(\Leftarrow)$

По условию $f(x) = a + \alpha(x),\text{ где } \lim\limits_{x \to x_0}\alpha(x) = 0$, тогда по определению
$$\forall{\large\varepsilon} > 0 \ \exists \overset{\circ}U_\delta(x_0): \ \forall x \in \overset{\circ}U_\delta(x_0) \Rightarrow |\alpha(x)| <{\large\varepsilon}$$
Но по условию $f(x) = a + \alpha(x) \Rightarrow \alpha(x) = f(x) - a$, отсюда имеем
$$\forall{\large\varepsilon} > 0 \ \exists \overset{\circ}U_\delta(x_0): \ \forall x \in \overset{\circ}U_\delta(x_0) \Rightarrow |f(x) - a| <{\large\varepsilon} \overset{по \ опр.}\Rightarrow \lim\limits_{x \to x_0}f(x) = a$$
Теорема доказана.

### *Теорема (о произведении бесконечно малой функции на ограниченную)*
Если $\alpha(x)$ - бесконечно малая функция при $x \rightarrow x_0$, $f(x)$ - ограниченная функция, то $\alpha(x)\cdot f(x)$ - бесконечно малая функция при $x \rightarrow x_0$.
*Доказательство*

По условию  $\alpha(x)$ - бесконечно малая функция при $x \rightarrow x_0$, тогда
$$\forall {\large\varepsilon} > 0 \ \exists\overset{\circ}U_1(x_0): 
 \forall x \in \overset{\circ}U_1(x_0) \Rightarrow |\alpha(x)| < \frac{ {\large\varepsilon}}{c}$$
 $f(x)$ - ограниченная функция, тогда
 $$|f(x)| < c, \text{ где } c = const, \ \forall x \in \overset{\circ}U_2(x_0)$$
 Таким образом,
$$\forall x \in \overset{\circ}U(x_0) = \overset{\circ}U_1(x_0) \cap \overset{\circ}U_2(x_0):$$
$$|\alpha(x)\cdot f(x)| < \frac{ {\large\varepsilon}}{c} \cdot c \Rightarrow |\alpha(x)\cdot f(x)| < {\large\varepsilon} \Rightarrow \alpha(x)\cdot f(x) \text{ - бесконечно малая функция при } x \rightarrow x_0$$
Теорема доказана.

### *Теорема (о связи между бесконечно большой и бесконечно малой)*

$\alpha(x)$ - бесконечно малая функция при $x \rightarrow x_0$, отличная от нуля в некоторой проколотой окрестности точки $x_0 \ \Rightarrow \ {\Large\frac{1}{\alpha(x)}}$ - бесконечно большая функция при $x \rightarrow x_0$.

$f(x)$ - бесконечно большая функция при $x \rightarrow x_0 \ \Rightarrow \ {\Large\frac{1}{f(x)}}$ - бесконечно малая функция при $x \rightarrow x_0$.

*Доказательство*

Пусть $\alpha(x)$ - бесконечно малая функция при $x \rightarrow x_0$, отличная от нуля в некоторой проколотой окрестности $\overset{\circ}U(x_0)$ точки $x_0$. Выберем произвольное $E > 0$. Тогда по определению бесконечно малой функции,
$$\text{для } {\large\varepsilon} = \frac{1}{E} > 0 \ \ \exists \overset{\circ}U_1(x_0): \ \forall x \in \overset{\circ}U(x_0) \cap \overset{\circ}U_1(x_0) \Rightarrow 0 < |\alpha(x)| < {\large\varepsilon}, \text{ т.е.}$$
$$\frac{1}{|\alpha(x)|} > E, \overset{по \ опр.}\Rightarrow \frac{1}{\alpha(x)} \text{ - бесконечно большая функция при } x \rightarrow x_0 $$

Пусть $f(x)$ - бесконечно большая функция при  $x \rightarrow x_0$. Выберем произвольное ${\large\varepsilon} > 0$. Тогда по определению бесконечно большой функции,
$$\text{для } E = \frac{1}{{\large\varepsilon}} \ \ \exists \overset{\circ}U(x_0): \ \forall x \in \overset{\circ}U(x_0) \Rightarrow |f(x)| > E, \text{ т.е.}$$
$$\frac{1}{f(x)} < \frac{1}{E} = {\large\varepsilon}, \overset{по \ опр.}\Rightarrow \frac{1}{f(x)} \text{ - бесконечно малая функция при } x \rightarrow x_0 $$ 
Теорема доказана.

### *Теорема (о замене бесконечно малой на эквивалентную под знаком предела)*
Пусть $\alpha(x)\sim\beta(x)$ при $x \rightarrow x_0$, и $f(x)$ - некоторая функция, определенная в проколотой окрестности $\overset{\circ}U(x_0)$ точки $x_0$. Тогда:

* если существует предел при $x \rightarrow x_0$ произведения $\alpha(x)\cdot f(x)$, то он не изменится при замене $\alpha(x)$ на эквивалентную при $x \rightarrow x_0$ бесконечно малую функцию $\beta(x)$

* если существует предел при $x \rightarrow x_0$ частного ${\Large\frac{f(x)}{\alpha(x)}}$ , то он не изменится при замене $\alpha(x)$ на эквивалентную при $x \rightarrow x_0$ бесконечно малую функцию $\beta(x)$

*Доказательство*

По условию $\alpha(x)\sim\beta(x)$ при $x \rightarrow x_0$, тогда по определению
$\lim\limits_{x \to x_0}{\Large\frac{\alpha(x)}{\beta(x)}} = 1$.
Таким образом,

* $\lim\limits_{x \to x_0}(\alpha(x)\cdot f(x)) = \lim\limits_{x \to x_0}{\Large\frac{\alpha(x)\cdot\beta(x)\cdot f(x)}{\beta(x)}} = \lim\limits_{x \to x_0}{\Large\frac{\alpha(x)}{\beta(x)}}\cdot\lim\limits_{x \to x_0}(\beta(x)\cdot f(x)) = \lim\limits_{x \to x_0}(\beta(x)\cdot f(x))$
* $\lim\limits_{x \to x_0}{\Large\frac{f(x)}{\alpha(x)}} = \lim\limits_{x \to x_0}{\Large\frac{\beta(x)\cdot f(x)}{\alpha(x)\cdot\beta(x)}} = \lim\limits_{x \to x_0}{\Large\frac{\beta(x)}{\alpha(x)}}\cdot\lim\limits_{x \to x_0}{\Large\frac{f(x)}{\beta(x)}} = \lim\limits_{x \to x_0}{\Large\frac{f(x)}{\beta(x)}}$
Теорема доказана.

### *Теорема (о необходимом и достаточном условии эквивалентности бесконечно малых)*

Две бесконечно малые функции $\alpha(x)$ и $\beta(x)$ при $x \rightarrow x_0$ эквивалентны $\iff$ их разность имеет больший порядок малости при $x \rightarrow x_0$ по сравнению с каждой из них.

*Доказательство*

$(\Rightarrow)$

По условию $\alpha(x) \sim \beta(x)$ при $x \rightarrow x_0$, тогда по определению $\lim\limits_{x \to x_0}{\Large\frac{\alpha(x)}{\beta(x)}} = 1$.
Таким образом,

$$\lim\limits_{x \to x_0}{\frac{\alpha(x) - \beta(x)}{\beta(x)}} = \lim\limits_{x \to x_0}{\frac{\alpha(x)}{\beta(x)}} - 1 = 0, \overset{по \ опр.}\Rightarrow \alpha(x) - \beta(x) = o (\beta(x)) \text{ при } x \rightarrow x_0$$

$$\lim\limits_{x \to x_0}{\frac{\alpha(x) - \beta(x)}{\alpha(x)}} = 1 - \lim\limits_{x \to x_0}{\frac{\beta(x)}{\alpha(x)}} = 0, \overset{по \ опр.}\Rightarrow \alpha(x) - \beta(x) = o (\alpha(x)) \text{ при } x \rightarrow x_0$$
$(\Leftarrow)$

По условию $\alpha(x) - \beta(x) = o (\beta(x)) \text{ при } x \rightarrow x_0, \ \alpha(x) - \beta(x) = o (\alpha(x)) \text{ при } x \rightarrow x_0$. Тогда

$$0 = \lim\limits_{x \to x_0}{\frac{\alpha(x) - \beta(x)}{\beta(x)}} = \lim\limits_{x \to x_0}{\frac{\alpha(x)}{\beta(x)}} - 1 \ \Rightarrow \lim\limits_{x \to x_0}{\frac{\alpha(x)}{\beta(x)}} = 1, \overset{по \ опр.}\Rightarrow \alpha(x) \sim \beta(x) \text{ при } x \rightarrow x_0$$

$$0 = \lim\limits_{x \to x_0}{\frac{\alpha(x) - \beta(x)}{\alpha(x)}} = 1 - \lim\limits_{x \to x_0}{\frac{\beta(x)}{\alpha(x)}} \ \Rightarrow \lim\limits_{x \to x_0}{\frac{\beta(x)}{\alpha(x)}} = 1, \overset{по \ опр.}\Rightarrow \alpha(x) \sim \beta(x) \text{ при } x \rightarrow x_0$$

 Теорема доказана.

 ### *Теорема (о сумме конечного числа бесконечно малых разных порядков)*

 Сумма конечного числа бесконечно малых функций при $x \rightarrow x_0$ эквивалентна своей главной части. 

 *Доказательство*

 Пусть $\alpha_1(x), \ \alpha_2(x), \ ..., \ \alpha_n(x)$ - бесконечно малые функции при $x \rightarrow x_0$, и $\alpha_1(x)$ - главная часть суммы $\alpha_1(x) + \alpha_2(x) + ... +  \alpha_n(x)$, т.е.
 $$\lim\limits_{x \to x_0}\frac{\alpha_2(x)}{\alpha_1(x)} = 0, \lim\limits_{x \to x_0}\frac{\alpha_3(x)}{\alpha_1(x)} = 0, \ ...,\ \lim\limits_{x \to x_0}\frac{\alpha_n(x)}{\alpha_1(x)} = 0, $$ 
 Тогда рассмотрим
 $$\lim\limits_{x \to x_0}{\frac{\alpha_1(x) + \alpha_2(x) + ... +  \alpha_n(x)}{\alpha_1(x)}}= 1 + \lim\limits_{x \to x_0}\frac{\alpha_2(x)}{\alpha_1(x)} + \lim\limits_{x \to x_0}\frac{\alpha_3(x)}{\alpha_1(x)}+ ... + \lim\limits_{x \to x_0}\frac{\alpha_n(x)}{\alpha_1(x)} = 1, \overset{по \ опр.}\Rightarrow \alpha_1(x) + \alpha_2(x) + ... +  \alpha_n(x) \sim \alpha_1(x) \text{ при } x \rightarrow x_0$$
 Теорема доказана.

 ### *Теорема (о непрерывности суммы, произведения и частного непрерывных функций)*

 Если $f(x)$ и $g(x)$ непрерывны в точке $x_0$, то функции $f(x) \pm g(x),\ f(x)\cdot g(x), \ {\Large\frac{f(x)}{g(x)}}$ (последнее при $g(x) \neq 0$) - также непрерывны в точке $x_0$.

 *Доказательство*

 По условию $f(x)$ и $g(x)$ непрерывны в точке $x_0$, тогда по определению
 $$\exists\lim\limits_{x \to x_0}f(x) = f(x_0)$$ 
$$\exists\lim\limits_{x \to x_0}g(x) = g(x_0)$$ 

1) $\lim\limits_{x \to x_0}(f(x) \pm g(x)) = \lim\limits_{x \to x_0}f(x) \pm \lim\limits_{x \to x_0}g(x) = f(x_0) \pm g(x_0), \overset{по \ опр.}\Rightarrow f(x) \pm g(x)$ - непрерывна в точке x = $x_0$.

2) $\lim\limits_{x \to x_0}(f(x) \cdot g(x)) = \lim\limits_{x \to x_0}f(x) \cdot \lim\limits_{x \to x_0}g(x) = f(x_0) \cdot g(x_0), \overset{по \ опр.}\Rightarrow f(x) \cdot g(x)$ - непрерывна в точке x = $x_0$.

3) $\lim\limits_{x \to x_0}{\Large\frac{f(x)}{g(x)}} = {\Large\frac{\lim\limits_{x \to x_0}f(x)} {\lim\limits_{x \to x_0}g(x)}} = {\Large\frac{f(x_0)}{g(x_0)}}, \overset{по \ опр.}\Rightarrow {\Large\frac{f(x)}{g(x)}}$ - непрерывна в точке x = $x_0$ при условии $g(x) \neq 0$.

Теорема доказана.

### *Теорема (о непрерывности сложной функции)*

Если функция $y = f(x)$ непрерывна в точке $x = a$, а функция $g(y)$ непрерывна в соответствующей точке $b = f(a)$, то сложная функция $g(f(x))$ непрерывна в точке $x = a$.

*Доказательство*

По условию функция $y = f(x)$ непрерывна в точке $x = a$, функция $g(y)$ непрерывна в точке $b = f(a)$. Тогда по определению 
$$\exists\lim\limits_{x \to a}f(x) = f(a)$$
$$\exists\lim\limits_{y \to b}g(y) = g(b)$$

Тогда

$$\lim\limits_{x \to a}g(f(x)) = \lim\limits_{y \to b}g(y) = g(b) = g(f(a)), \overset{по \ опр.}\Rightarrow \text{функция } g(f(x)) \text{ непрерывна в точке } x = a$$
Теорема доказана.

<!-- так как проколотая окр = окр \ {x_0}... -->
### *Теорема (о сохранении знака непрерывной функции в окрестности точки)*
Пусть функция $f(x)$ непрерывна
в точке $x_0$, и $f(x_0) \neq 0$. Тогда в некоторой окрестности $U_\delta(x_0)$ точки $x_0$ функция $f(x)$ имеет знак числа $f(x_0)$.

*Доказательство*

По условию $y = f(x)$ непрерывна в точке $x = x_0$. Тогда по определению
$$\exists\lim\limits_{x \to x_0}f(x) = f(x_0) \neq 0$$

Тогда по теореме о сохранении функцией знака своего предела функция $f(x)$ имеет знак числа $f(x_0)$ в некоторой проколотой окрестности $\overset{\circ}U_\delta(x_0)$ точки $x_0$, т.е.
$$f(x_0) > 0 \Rightarrow \exists \overset{\circ}U_\delta(x_0):\ \forall x \in \overset{\circ}U_\delta(x_0)\Rightarrow f(x) > 0 $$
$$f(x_0) < 0 \Rightarrow \exists \overset{\circ}U_\delta(x_0):\ \forall x \in \overset{\circ}U_\delta(x_0)\Rightarrow f(x) < 0 $$
Так как $\overset{\circ}U_\delta(x_0) = U_\delta(x_0) \backslash \{x_0\}$, то  
$$f(x_0) > 0 \Rightarrow \exists U_\delta(x_0):\ \forall x \in U_\delta(x_0)\Rightarrow f(x) > 0 $$
$$f(x_0) < 0 \Rightarrow \exists U_\delta(x_0):\ \forall x \in U_\delta(x_0)\Rightarrow f(x) < 0 $$

Теорема доказана.

### *Теорема (о непрерывности элементарных функций)*

Все элементарные функции непрерывны всюду, где они определены.

*Доказательство $(\ $для $y = sin(x)$ и $y = cos( x)\ )$*

> $$y = sin(x)$$
Найдем приращение функции
$$\Delta y = f(x + \Delta x) - f(x) = sin(x + \Delta x) - sin(x) = 2sin{\Big(}\frac{x + \Delta x - x}{2}{\Big)}\cdot cos\Big(\frac{x + \Delta x + x}{2}{\Big)} = 2sin{\Big(}\frac{\Delta x}{2}{\Big)}\cdot cos\Big(x + \frac{ \Delta x }{2}{\Big)}$$
Тогда
$$\lim\limits_{\Delta x \to 0}\Delta y = \lim\limits_{\Delta x \to 0}\Bigg(2sin{\Big(}\frac{\Delta x}{2}{\Big)}\cdot cos\Big(x + \frac{ \Delta x }{2}{\Big)}\Bigg) = 0, $$
Т.е. $\lim\limits_{\Delta x \to 0}\Delta y = 0 \overset{по \ опр.}\Rightarrow y = sin(x)$ непрерывна на всей числовой прямой.

> $$y = cos(x)$$

Найдем приращение функции
$$\Delta y = f(x + \Delta x) - f(x) = cos(x + \Delta x) - cos(x) = 2sin{\Big(}\frac{x + \Delta x + x}{2}{\Big)}\cdot sin\Big(\frac{x - \Delta x - x}{2}{\Big)} = -2sin\Big(x + \frac{ \Delta x }{2}{\Big)}\cdot sin{\Big(}\frac{\Delta x}{2}{\Big)} $$
Тогда
$$\lim\limits_{\Delta x \to 0}\Delta y = \lim\limits_{\Delta x \to 0}\Bigg(-2sin\Big(x + \frac{ \Delta x }{2}{\Big)}\cdot sin{\Big(}\frac{\Delta x}{2}{\Big)}\Bigg) = 0, $$
Т.е. $\lim\limits_{\Delta x \to 0}\Delta y = 0 \overset{по \ опр.}\Rightarrow y = cos(x)$ непрерывна на всей числовой прямой.

<!-- определение непр в точке -->

### *свойства функций, непрерывных на отрезке*
1) *Первая теорема Вейерштрасса*

Если функция $y = f(x)$ является непрерывной на $[a, b]$, то она ограничена на этом отрезке.

2) *Вторая теорема Вейерштрасса*

Если функция $y = f(x)$ является непрерывной на $[a, b]$, то она имеет на этом отрезке наибольшее и наименьшее значение.
<!-- правильно? -->

3) *Первая теорема Больцано-Коши*

Если функция $y = f(x)$ является непрерывной на $[a, b]$ и на концах этого отрезка принимает значения разных знаков, т.е. $f(a)\cdot f(b) < 0$, то существует хотя бы одна точка $c \in (a, b)$, в которой значение функции $f(c) = 0$.

4) *Вторая теорема Больцано-Коши*

Если функция $y = f(x)$ является непрерывной на $[a, b]$ и $f(a)\neq f(b)$, то существует такая точка $c \in (a, b)$, что $f(a) < f(c) < f(b)$.

5) *Теорема о непрерывности обратной функции*

Если функция $y = f(x)$ непрерывна и монотонно возрастает (убывает) на $[a, b]$, то существует и определена на отрезке $[f(a), f(b)]$ обратная функция $x = f^{-1}(y),$ непрерывная и возрастающая (убывающая) на этом отрезке.

