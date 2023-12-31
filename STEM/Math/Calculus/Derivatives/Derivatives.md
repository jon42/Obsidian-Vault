---
TARGET DECK: Math
---
Derivatives:: Show the instantaneous slope at any point.
<!--ID: 1692597427799-->

<!--SR:!2023-08-20,4,270-->

## Derivative Notation
$d/dx$ denotes a single derivative
f'(x) is the first derivative of f(x)
$\frac{d^2}{d^2x}$ is the second derivative with respect to x
f''(x) is the second derivative of f(x)
These can scale infinitely

When denoted with respect to it means that all the derivative rules will apply to that variable
# Formal Definition of Derivative
Formal Definition of Derivative:: $$f'(x)=lim_{h{\rightarrow}0}{\frac{f(x+h) - f(x)}h}$$
<!--ID: 1692597427808-->

# Basic Derivative Rules
### Deriving Functions
#### [[Trig]] Derivatives
Derivative of [[Trig#sin]]:: $$\frac{d}{dx}sin(x)=cos(x)$$
<!--ID: 1692597427817-->

<!--SR:!2023-08-20,4,270-->
Derivative of cos:: $$\frac{d}{dx}cos(x)=-sin(x)$$
<!--ID: 1692597427826-->

Derivative of tan::$$\frac{d}{dx}tan(x)=sec^2(x)$$
<!--ID: 1692597427834-->

<!--SR:!2023-08-17,1,230-->
(Use quotient rule to understand)
Derivative of sec:: $$\frac{d}{dx}sec(x)=sec(x)tan(x)$$
<!--ID: 1692597427842-->

<!--SR:!2023-08-17,1,230-->
Derivative of csc:: $$\frac{d}{dx}csc(x)=-csc(x)cot(x)$$
<!--ID: 1692597427850-->

Derivative of cot::$$\frac{d}{dx}cot(x)=-csc^2(x)$$
<!--ID: 1692597427854-->

### Rules
Addition::$$\frac{d}{dx}(f(x) + g(x))=f'(x)+g'(x)$$
<!--ID: 1692597427858-->

<!--SR:!2023-08-20,4,270-->
Power Rule:: $$\begin{aligned} f(x) = x^{n} \newline f'{(x) = nx^{n-1}}\end{aligned}$$
<!--ID: 1692597427863-->

Quotient rule:: $$\frac{d}{dx}\frac{f(x)}{g(x)} = \frac{f'(x)g(x)-f(x)g'(x)}{g(x)^2}$$
<!--ID: 1692597427867-->

<!--SR:!2023-08-19,3,250-->

Exponent::$$\frac{d}{dx}a^x=ln(a)a^x$$
<!--ID: 1696002544010-->

Chain Rule::: $$\frac{d}{dx}f(g(x))=g'(x)f'(g(x))$$
Examples:
$$30^{3x+x^2}=ln(30)(3+2x)30^{3x+x^2}$$
$$\frac{d}{dx} csc(sin(x))=-cos(x)csc(sin(x))cot(sin(x))$$

