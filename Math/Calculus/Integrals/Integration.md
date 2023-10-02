---
Aliases: anit-derivative, Anti-derivative, integration
TARGET DECK: Math
---

Integration:: Also known as an anti-derivative, gives the area underneath a graph.
<!--ID: 1696002544004-->

# Indefinite Integrals
Indefinite integrals are integrals that are not bound to any particular domain
When computing an idefinite integral a C is added. This C is added because it is the anti-derivitave, and when there is a constant without an x it gets removed. So to compensate for not knowing whether or not a constant was removed a C is used as a place holder. DO NOT FORGET THE C OR THE ANSWER WILL BE WRONG
# Definite Integrals
Definite integrals are integrals that have a specific domain.
It is notated as $\int_a^b$ where a and b are the upper and lower bounds
## Computing Definite Integrals 
Definite integrals are calculated using $$\int_a^bf(x)dx=\int{f(b)dx}-\int{f(a)dx}$$
# Integration Rules
Integration Rules are the inverse of derivative rules. This is what gives it the name anti-derivative

Constant: $$\int{a}dx=ax+C$$
Variable: $$\int{ax^{b}dx=\frac{ax^{b+1}}{b+1}}+ C$$
Reciprocal: $$\int{\frac{1}{x}}dx=ln|x| + C$$
Exponential: $$\int{a^{x}dx=\frac{a^{x}}{ln(x)}} +C $$
Log: $$\int{log_ax}dx=\frac{x}{ln(a)}(ln(x)-1)+C$$
Sum: $$\int{f(x)+g(x)dx}= \int{f(x)dx}+\int{g(x)dx}$$
Chain Rule: $$\int{f(g(x))dx}$$

Integration By Parts: $$\int{f(x)g(x)}dx=f(x)\int{g(x)dx}-\int{f'(x)(\int{g(x)dx})dx}$$
Substitution: $$\int{f(g(x))g'(x)dx}=\int{f(u)du} $$ then after integrating put g(x) back instead of u