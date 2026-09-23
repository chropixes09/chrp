---
publish: true
created: 2026-09-23T13:06:44.474Z
modified: 2026-09-23T15:48:10.039Z
---

This reference sheet summarizes all the essential formulas, identities, and conditions required to solve the practice packet covering **Sequences & Series**, **Binomial Theorem**, and **Exponents & Logarithms**.

---

## 1. Sequences and Series

### Arithmetic Sequences & Series

- **$n^{\text{th}}$ Term:**
  $u_n = u_1 + (n - 1)d$
  _(where $u_1$ is the first term and $d$ is the common difference)_

- **Sum of the First $n$ Terms ($S_n$):**
  $S_n = \frac{n}{2}\left(2u_1 + (n - 1)d\right) \quad \text{or} \quad S_n = \frac{n}{2}(u_1 + u_n)$

- **Sigma Notation:**
  $\sum_{k=1}^{n} u_k = u_1 + u_2 + \dots + u_n$

---

### Geometric Sequences & Series

- **$n^{\text{th}}$ Term:**
  $u_n = u_1 \cdot r^{n-1}$
  _(where $u_1$ is the first term and $r$ is the common ratio)_

- **Sum of the First $n$ Terms ($S_n$):**
  $S_n = \frac{u_1(1 - r^n)}{1 - r} = \frac{u_1(r^n - 1)}{r - 1}, \quad r \ne 1$

- **Sum to Infinity ($S_\infty$):**
  $S_\infty = \frac{u_1}{1 - r}$
  - **Convergence Condition:** The sum to infinity exists **if and only if** $|r| < 1$ (i.e., $-1 < r < 1$).

---

### Financial Mathematics

- **Compound Interest:**
  $FV = PV \times \left(1 + \frac{r}{100k}\right)^{kn}$
  _(where $FV$ is future value, $PV$ is present value, $r\%$ is nominal annual interest rate, $k$ is compounding periods per year, $n$ is years)_

---

## 2. Binomial Theorem

### Binomial Expansion

For a positive integer $n \in \mathbb{N}$:
$(a + b)^n = \sum_{r=0}^{n} \binom{n}{r} a^{n-r} b^r = \binom{n}{0}a^n + \binom{n}{1}a^{n-r}b + \dots + \binom{n}{n}b^n$

- **General / $(r+1)^{\text{th}}$ Term ($T_{r+1}$):**
  $T_{r+1} = \binom{n}{r} a^{n-r} b^r \quad \text{for } r = 0, 1, 2, \dots, n$

---

### Binomial Coefficients

- **Formula for Binomial Coefficient:**
  $\binom{n}{r} = \frac{n!}{r!(n - r)!}$

- **Polynomial Expansion of $\binom{n}{k}$:**
  $\binom{n}{k} = \frac{n(n - 1)(n - 2)\cdots(n - k + 1)}{k!}$

- **Useful Identities:**
  - $\binom{n}{0} = 1$, $\binom{n}{1} = n$, $\binom{n}{n} = 1$
  - Symmetry: $\binom{n}{r} = \binom{n}{n-r}$

---

## 3. Exponents and Logarithms

### Laws of Exponents

For $a, b > 0$:

1. $a^x \cdot a^y = a^{x+y}$
2. $\frac{a^x}{a^y} = a^{x-y}$
3. $(a^x)^y = a^{xy}$
4. $(ab)^x = a^x b^x$
5. $\left(\frac{a}{b}\right)^x = \frac{a^x}{b^x}$
6. $a^{-x} = \frac{1}{a^x}$
7. $a^0 = 1$
8. $a^{\frac{m}{n}} = \sqrt[n]{a^m}$

---

### Laws of Logarithms

For base $a > 0, a \ne 1$ and $x, y > 0$:

1. **Product Rule:** $\log_a(xy) = \log_a x + \log_a y$
2. **Quotient Rule:** $\log_a\left(\frac{x}{y}\right) = \log_a x - \log_a y$
3. **Power Rule:** $\log_a(x^k) = k \log_a x$
4. **Logarithm of Base:** $\log_a a = 1$
5. **Logarithm of 1:** $\log_a 1 = 0$
6. **Inverse Properties:**
   $a^{\log_a x} = x \quad \text{and} \quad \log_a(a^x) = x$
7. **Base-e Relation:**
   $a^x = e^{x \ln a}$

---

### Change of Base Formula

$\log_b a = \frac{\log_c a}{\log_c b} = \frac{\ln a}{\ln b}$

- **Reciprocal Rule:**
  $\log_b a = \frac{1}{\log_a b}$

---

### Domain Restrictions

- For $\log_a x$ to be real and defined:
  $x > 0, \quad a > 0, \quad \text{and} \quad a \ne 1$
