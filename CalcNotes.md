## Special Limits
$$
\begin{aligned}
& \lim_{x \to 0} \frac{\sin x}{x}=1 \\ \\
& \lim_{x \to 0} \frac{1- \cos x}{x}=0 \\
\end{aligned}
$$
## Special Derivatives
$$
\begin{aligned}
& \frac{\mathrm{d} [\sin x]}{\mathrm{d} x} = \cos x \\ \\
& \frac{\mathrm{d} [\cos x]}{\mathrm{d} x} = - \sin x \\ \\
& \frac{\mathrm{d} [\tan x]}{\mathrm{d} x} = \sec^{2} x \\ \\
& \frac{\mathrm{d} [\sec x]}{\mathrm{d} x} = \sec x \tan x \\ \\
& \frac{\mathrm{d} [\cot x]}{\mathrm{d} x} = - \csc^{2} x \\ \\
& \frac{\mathrm{d} [\csc x]}{\mathrm{d} x} = - \csc x \cot x \\ \\
& \frac{\mathrm{d} [arcsin x]}{\mathrm{d} x} =  \frac{1}{\sqrt{1-x^{2}}} \\ \\
& \frac{\mathrm{d} [arccos x]}{\mathrm{d} x} = - \frac{1}{\sqrt{1-x^{2}}} \\ \\
& \frac{\mathrm{d} [arctan x]}{\mathrm{d} x} =  \frac{1}{{1-x^{2}}} \\ \\
& \frac{\mathrm{d} [arccot x]}{\mathrm{d} x} = - \frac{1}{{1-x^{2}}} \\ \\
& \frac{\mathrm{d} [arcsec x]}{\mathrm{d} x} =  \frac{1}{\left | x \right |\sqrt{1-x^{2}}} \\ \\
& \frac{\mathrm{d} [arccsc x]}{\mathrm{d} x} = - \frac{1}{\left | x \right |\sqrt{1-x^{2}}} \\ \\
& \frac{\mathrm{d} [\ln x]}{\mathrm{d} x} = \frac{1}{x} \\ \\
& \frac{\mathrm{d} [\log_{a} x]}{\mathrm{d} x} = \frac{1}{x\ln a} \\ \\
& \frac{\mathrm{d} [e^{x}]}{\mathrm{d} x} = e^{x} \\ \\
& \frac{\mathrm{d} [a^{x}]}{\mathrm{d} x} = a^{x}\ln a \\ \\
\end{aligned}
$$
## Trig Rules
$$
\begin{aligned}
& \int \tan x = \ln\left | \sec x \right | + c \\ \\
& \int \sec x = \ln\left | \sec x + \tan x \right | + c \\ \\
& \sin A \cos B = \frac{1}{2}[\sin(A-B) + \sin(A+B)] \\ \\
& \sin A \sin B = \frac{1}{2}[\cos(A-B)-\cos(A+B)] \\ \\
& \cos A \cos B = \frac{1}{2}[\cos(A-B)+\cos(A+B)] \\ \\
& \sin^{2}x + \cos^{2}x = 1 \\ \\
& \tan^{2}x +1 = \sec^{2}x \\ \\
& \sin^{2}x = \frac{1}{2}(1-\cos 2x) \\ \\
& \cos^{2}x = \frac{1}{2}(1+\cos 2x) \\ \\
& \sin 2x = 2\sin x \cos x
\end{aligned}
$$
## Trig Integrals
$$
\begin{aligned}
\int \sin^{m} x\cos^{n} x \\
\end{aligned}
$$
1. If n is odd 
$$
\rightarrow u=\sin x 
$$
2. If m is odd
$$
\rightarrow u=\cos x
$$
3. If  n and m are even use Double Angle Formula
$$
\int \tan^{m} x\sec^{n} x
$$
1. If m is odd
$$
\rightarrow u=\sec x
$$
2. If n is even
$$
\rightarrow u=\tan x
$$
## Trig Substitution Rules
$$
\begin{aligned}
\int \sqrt {a^{2}-x^{2}} \rightarrow \sin \theta \\ \\
\int \sqrt {x^{2}-a^{2}} \rightarrow \sec \theta \\ \\
\int \sqrt {x^{2}+a^{2}} \rightarrow \tan \theta \\
\end{aligned}
$$
## Improper Integrals
$$
\int_{a}^{\infty } f(x) = \lim_{b \to \infty}\int_{a}^{b} f(x)
$$
## Arc Length
### Cartisan
$$
\int_{a}^{b} \sqrt{1+\left ( \frac{\mathrm{d} y}{\mathrm{d} x} \right )^{2}} \mathrm{d} x 
$$
### Parametric
$$
\int_{a}^{b} \sqrt{\left ( \frac{\mathrm{d} x}{\mathrm{d} t} \right )^{2}+\left ( \frac{\mathrm{d} y}{\mathrm{d} t} \right )^{2}} \mathrm{d} t 
$$
### Polar
$$
\int_{a}^{b} \sqrt{\left ( \frac{\mathrm{d} r}{\mathrm{d} \theta} \right )^{2}+r^{2}} \, \mathrm{d} \theta
$$
## Area of Surface of Revolution
$$
\int_{a}^{b}2\pi r \mathrm{ds}
$$
$$
r 
\rightarrow
Radius (Could be an equation or a single variable)
$$
$$
ds
\rightarrow
The Arc Length function (changes depending on type of equation given, eg. Parametric, Polar(see Section 7))
$$
## Parametric Equations
### Tangent horizontal when 
$$
\frac{\mathrm{d} y}{\mathrm{d} x} =0
$$
### Tangent vertical when 
$$
\frac{\mathrm{d} y}{\mathrm{d} x} = \mathrm{undef \, or} \, \infty
$$
$$
\mathrm{if} \, y=f(x)\, \mathrm{then} \left\{
\begin{array}{c l}     
    x=t\\
    y=f(x)
\end{array}\right. 
$$
$$
\frac{{y}'(t)}{{x}'(t)} = \frac{\frac{\mathrm{d} y}{\mathrm{d} t}}{\frac{\mathrm{d} x}{\mathrm{d} t}} 
\frac{\mathrm{d} ^{2} y}{\mathrm{d} x} = \frac{\mathrm{d} \left (\frac{\mathrm{d} y}{\mathrm{d} t}/{\frac{\mathrm{d} x}{\mathrm{d} t}} \right )}{\mathrm{d} x} 
$$
### Area under parametric curve
$$
\int_{a}^{b} g(t){f}'(t) \mathrm{d}t
$$
## Polar Equations
### Polar to Cartisan
$$
\left\{
\begin{array}{c l}     
    x=r\cos \theta
    y=r\sin \theta
\end{array}\right.
$$
### Cartisan to Polar
$$
\left\{
\begin{array}{c l}     
    r^{2} = x^{2} + y^{2}
    \theta = tan^{-1}\left ( \frac{y}{x} \right )
\end{array}\right.
$$
### Area of a polar curve
$$
\int_{a}^{b} \frac{1}{2}[f(\theta)]^{2} \, \mathrm{d}\theta
$$
## Series
### P-Series
$$
\sum_{n=1}^{\infty}\frac{1}{n^{p}} 
\left\{
\begin{array}{c l}     
    \, p>1 \,\,\, \mathrm{Converges} \\
    p\leq 1 \,\,\, \mathrm{Diverges}
\end{array}\right.
$$
### Geometric Series
$$
a,ar,ar^{2},... \sum_{n=1}^{\infty}ar^{n-1} 
\left\{
\begin{array}{c l}     
    -1<r<1 \,\,\, \mathrm{converges\, at} \,\, \frac{a}{1-r} \\
    \mathrm{otherwise} \,\,\, \mathrm{diverges} 
\end{array}\right.
$$
Partial sum for geometric series
$$
s_{n}=\frac{a(1-r^{n})}{1-r}
$$
### Limit Test
$$
\mathrm{if}\, \lim_{n\to \infty}\neq 0 \,\, \mathrm{then} \, \sum_{n=1}^{\infty}a_{n} \, \mathrm{diverges} 
$$
### Integral Test
$$
a_{n} = f(n)
$$
where f is
1. Continuous
2. Positive
3. Decreasing
$$
\mathrm{Then} \, \sum_{n=1}^{\infty}a_{n} \, \mathrm{converges\, iff} \, \int_{1}^{\infty}f(x)\mathrm{d}x \, \mathrm{converges}
$$
### Comparison Test
Suppose
$$
a_{n}>b_{n}>0 \mathrm{\, for\, all\,} n\geq 1
$$
$$
\mathrm{if} \, \sum_{n=1}^{\infty}a_{n} \, \mathrm{converges\, then} \, \sum_{n=1}^{\infty}b_{n} \, \mathrm{converges}
$$
$$
\mathrm{if} \, \sum_{n=1}^{\infty}b_{n} \, \mathrm{diverges\, then} \, \sum_{n=1}^{\infty}a_{n} \, \mathrm{diverges}
$$
if 
$$
\lim_{n\to \infty} \frac{a_{n}}{b_{n}}= 
(a positive number)
$$
then \,
$$
\sum_{n=1}^{\infty}a_{n} \, \mathrm{and} \, \sum_{n=1}^{\infty}b_{n} \,
$$
have the same convergence/divergence
### Alternating Series Test
$$
\sum_{n=1}^{\infty}(-1)^{n-1} a_{n} \ \mathrm{where} \ a_{n}>0
$$
$$ 
\mathrm{1. \ if} \ a_{n} \mathrm{is \ decreasing}
$$
$$
\mathrm{2. \ } \lim_{n\to \infty} a_{n}=0
$$
$$
\mathrm{then \ } \sum_{n=1}^{\infty}(-1)^{n-1} a_{n} \mathrm{ \ is \ convergent \ }
$$
### Ratio Test/Root Test
Let 
$$
L=\lim_{n\to \infty}\left | \frac{b_{n}+1}{b_{n}} \right |
$$
Let 
$$
L=\lim_{n\to \infty} \sqrt[n]{\left | b_{n} \right |}
$$
if $L<1$ Series is absolutly convergent <br />
if $L>1$(or $\infty$) Series is divergent <br />
if $L=1$ Test is inconclusive
### Taylor and Maclaurin Series
Taylor Series

$f(x)=\sum_{n=0}^{\infty}\frac{f^{n\mathrm{(\leftarrow derivative)}}(a)}{n!}(x-a)^{n} \ \mathrm{for} \ \left | a-x \right | < R$ 

Maclaurin Series 

$f(x)=\sum_{n=0}^{\infty} \frac{f^{n\mathrm{(\leftarrow derivative)}}(0)}{n!}(x)^{n}$

## Misc Rules
$$
\int \frac{1}{a^{2}+x^{2}} = \frac{1}{a}\tan^{-1}\frac{x}{a} 
$$
$$
\tan^{-1}\infty = \frac{\pi}{2} 
$$
$$
\tan^{-1}-\infty = -\frac{\pi}{2} 
$$

To find the intersection points between two curves, set them equal to each other <br />
Area between two curves is top curve minus bottom curve