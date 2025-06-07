+++
title = "Math Test"
+++
{{< katex >}}
# Exponents (घातांक)

We can express repeated multiplication in a concise form called an exponent.

For example:

* $$5 \times 5 \times 5 = 5^3$$

* 
$$
a \times a \times a \dots \times a$ (n times) = $a^n
$$

### Terminology

In the expression $$a^n$$:

* $$a$$ is the **Base** (आधार)

* $$n$$ is the **Exponent**, **Index**, or **Power** (घात)

**Example:**
In the expression $$-3 \times -3 \times -3 = (-3)^3$$:

* The **Base** is `-3`.

* The **Power** is `3`.

> This form of notation is called **exponential form** or **power notation**.

### Power of a Rational Number (परिमेय संख्या)

If $\frac{a}{b}$ is a rational number, then raising it to a power works as follows:

$$
\left(\frac{a}{b}\right)^2 = \frac{a}{b} \times \frac{a}{b} = \frac{a \times a}{b \times b} = \frac{a^2}{b^2}
$$

For any positive integer `n`, the general rule is:

$$
\left(\frac{a}{b}\right)^n = \frac{a^n}{b^n}
$$

### Reciprocal of a Rational Number

If $\frac{a}{b}$ is a non-zero rational number, then its reciprocal is $\frac{b}{a}$. We can express the reciprocal using a negative exponent:

$$
\left(\frac{a}{b}\right)^{-1} = \frac{b}{a}
$$

### Negative Integral Exponent of a Rational Number

Let $\frac{a}{b}$ be any rational number and let 'n' be a positive integer. Then, a negative exponent is defined as the reciprocal raised to the corresponding positive power.

$$
\left(\frac{a}{b}\right)^{-n} = \left(\frac{b}{a}\right)^{n}
$$

---

## Laws of Exponents

Let `a` and `b` be rational numbers and let `m` and `n` be any integers. Then, we have:

### i) Product Rule

When multiplying powers with the same base, you add the exponents.

$$
\left(\frac{a}{b}\right)^m \times \left(\frac{a}{b}\right)^n = \left(\frac{a}{b}\right)^{m+n}
$$

or

$$
a^m \times a^n = a^{m+n}
$$

*(Note: Base same रहे और गुणा रहे तो Power Add होगा / If the base is the same and they are being multiplied, the powers will be added.)*

**Examples:**

a)

$$
\left(\frac{2}{3}\right)^4 \times \left(\frac{2}{3}\right)^2 = \left(\frac{2}{3}\right)^{4+2} = \left(\frac{2}{3}\right)^6
$$

b)

$$
2^5 \times 2^6 = 2^{5+6} = 2^{11}
$$

### ii) Quotient Rule

When dividing powers with the same base, you subtract the exponents.

$$
\left(\frac{a}{b}\right)^m \div \left(\frac{a}{b}\right)^n = \left(\frac{a}{b}\right)^{m-n}
$$

or

$$
a^m \div a^n = a^{m-n}
$$

*(Note: यदि Base same हो तथा उनके बीच Divide भाग का सम्बंध हो तो Power घटेगा (Subtract) होगा / If the base is the same and they are being divided, the powers will be subtracted.)*

**Example:**

$$
\left(\frac{2}{5}\right)^5 \div \left(\frac{2}{5}\right)^4 = \left(\frac{2}{5}\right)^{5-4} = \left(\frac{2}{5}\right)^1 = \frac{2}{5}
$$



## Laws of Exponents

**(iii)**  
$$
\Bigl(\frac{a^m}{b^m}\Bigr)^n = \Bigl(\frac{a}{b}\Bigr)^{mn}
$$  
*इनके power के गुणन होंगे।*

---

**(iv)**  
$$
\Bigl(\frac{a}{b}\times\frac{c}{d}\Bigr)^n
= \Bigl(\frac{a}{b}\Bigr)^n \times \Bigl(\frac{c}{d}\Bigr)^n,
\quad
(q\times b)^n = a^n b^n
$$

$$
\Bigl(\frac{\tfrac{a}{b}}{\tfrac{c}{d}}\Bigr)^n
= \Bigl(\frac{a}{b}\times\frac{d}{c}\Bigr)^n
= \Bigl(\frac{ad}{bc}\Bigr)^n,
\quad
\Bigl(\frac{a}{b}\Bigr)^n = \frac{a^n}{b^n}
$$

---

**(v)**  
$$
\Bigl(\frac{a}{b}\Bigr)^{-n} = \Bigl(\frac{b}{a}\Bigr)^n,\quad n\in\mathbb{Z}^+
$$

---

**(vi)**  
$$
\Bigl(\frac{a}{b}\Bigr)^0 = 1
$$

---

## ✦ Exponential Function (11th Standard)

The function
$$
f(x) = a^x,\quad a>0,\ a\neq1,\ a\in\mathbb{R}
$$
is called an **exponential function**.

---

## Graphs

### Case 1: \(0 < a < 1\)  (example \(a=0.5\))

{{< chart >}}
type: 'line',
data: {
  labels: ['-4', '-3.5', '-3', '-2.5', '-2', '-1.5', '-1', '-0.5', '0', '0.5', '1', '1.5', '2', '2.5', '3', '3.5', '4'],
  datasets: [{
    label: 'f(x) = 0.5^x',
    data: [16, 11.31, 8, 5.66, 4, 2.83, 2, 1.41, 1, 0.707, 0.5, 0.354, 0.25, 0.177, 0.125, 0.088, 0.0625],
    borderColor: 'blue',
    fill: false,
    tension: 0.4
  }]
},
options: {
  scales: {
    x: {
      title: {
        display: true,
        text: 'x-axis'
      },
      grid: {
        display: true
      }
    },
    y: {
      title: {
        display: true,
        text: 'y-axis'
      },
      grid: {
        display: true
      },
      beginAtZero: true
    }
  }
}
{{< /chart >}}


### Case 2: \(a > 1\)  (example \(a=2\))

{{< chart >}}
type: 'line',
data: {
  labels: ['-4', '-3.5', '-3', '-2.5', '-2', '-1.5', '-1', '-0.5', '0', '0.5', '1', '1.5', '2', '2.5', '3', '3.5', '4'],
  datasets: [{
    label: 'f(x) = 2^x',
    data: [0.0625, 0.088, 0.125, 0.177, 0.25, 0.354, 0.5, 0.707, 1, 1.41, 2, 2.83, 4, 5.66, 8, 11.31, 16],
    borderColor: 'green',
    fill: false,
    tension: 0.4
  }]
},
options: {
  scales: {
    x: {
      title: {
        display: true,
        text: 'x-axis'
      },
      grid: {
        display: true
      }
    },
    y: {
      title: {
        display: true,
        text: 'y-axis'
      },
      grid: {
        display: true
      },
      beginAtZero: true
    }
  }
}
{{< /chart >}}

> In both graphs the curve never meets the **x‑axis**.

- **Domain**: $$\(x\in\mathbb{R}\)  $$
- **Range**: $$\(y\in(0,\infty)\)  $$



## 🧮 Exercise (अभ्यास) — Type (I)

---

### 1. Evaluate

a. $$\bigl(\tfrac{3}{4}\bigr)^2$$  
b. $$\bigl(-\tfrac{2}{3}\bigr)^3$$  
c. $$\bigl(-\tfrac{4}{5}\bigr)^4$$  
d. $$\bigl(\tfrac{6}{5}\bigr)^4$$  
e. $$\bigl(\tfrac{3}{4}\bigr)^{-2}$$  
f. $$\bigl(\tfrac{6}{5}\bigr)^{-3}$$  
g. $$\bigl(\tfrac{8}{3}\bigr)^0$$  
h. $$\bigl(-\tfrac{3}{11}\bigr)^{-2}$$  
i. $$\bigl(\tfrac{9}{5}\bigr)^{-3}$$  
j. $$\bigl(\tfrac{6}{2}\bigr)^2$$  
k. $$\bigl(\tfrac{3}{2}\bigr)^3$$  
l. $$\bigl(\tfrac{4}{8}\bigr)^{-2}$$  
m. $$\bigl(\tfrac{25}{26}\bigr)^{-2}$$  
n. $$\bigl(\tfrac{5}{3}\bigr)^{-1}$$  
o. $$\bigl(\tfrac{13}{14}\bigr)^{-2}$$  
p. $$\bigl(\tfrac{19}{17}\bigr)^{-2}$$  
q. $$\bigl(\tfrac{99}{99}\bigr)^{-10}$$  
r. $$\bigl(\tfrac{999}{998}\bigr)^{-2}$$  
s. $$\bigl(\tfrac{993}{997}\bigr)^2$$  
t. $$\bigl(\tfrac{346}{213}\bigr)^3$$

---

### 2. Express each of the following rational numbers in exponential form  
(घात के रूप में लिखें)

i. $$\frac{81}{256}$$  
ii. $$\frac{-32}{243}$$  
iii. $$\frac{-1}{343}$$  
iv. $$\frac{9}{16}$$  
v. $$\frac{-8}{27}$$  
vi. $$\frac{-1024}{3125}$$  
vii. $$\frac{-27}{64}$$  
viii. $$\frac{25}{36}$$  
ix. $$\frac{-1}{128}$$  
x. $$\frac{169}{121}$$

---

### 3. Simplify and express the result in exponential form

i. $$\bigl(\tfrac{3}{4}\bigr)^7 \times \bigl(\tfrac{3}{4}\bigr)^5$$  
ii. $$\bigl(-\tfrac{2}{5}\bigr)^{11} \times \bigl(-\tfrac{2}{5}\bigr)^7$$  
iii. $$\bigl(\tfrac{4}{5}\bigr)^2 \div \bigl(\tfrac{4}{5}\bigr)^5$$  
iv. $$\bigl(\tfrac{7}{8}\bigr)^9 \div \bigl(\tfrac{3}{2}\bigr)^{10}$$  
v. $$\bigl(\tfrac{3}{8}\bigr)^4 \times \bigl(\tfrac{3}{2}\bigr)^{-3}$$  
vi. $$\bigl(\tfrac{8}{3}\bigr)^{-1} \times \bigl(\tfrac{8}{3}\bigr)^{-2}$$  
vii. $$(-2)^{-3} \times (-2)^5$$  
viii. $$7^8 \times 7^{-3}$$  
ix. $$3^x \times 2^5$$  
x. $$3^5 \div 3^6$$  
xi. $$\bigl(\tfrac{3}{5}\bigr)^{-2} \div \bigl(\tfrac{4}{3}\bigr)^{-2}$$  
xii. $$\bigl(\tfrac{3}{5}\bigr)^{-2} \times \bigl(\tfrac{3}{5}\bigr)^7$$  



## 4. Simplify and express the result in the form of a rational number

1.  $$\bigl(\tfrac{2}{3}\bigr)^4 \times \bigl(\tfrac{2}{3}\bigr)^2$$  
2.  $$\bigl(-\tfrac{3}{4}\bigr)^3 \times \bigl(\tfrac{3}{4}\bigr)^2$$  
3.  $$\bigl(\tfrac{5}{7}\bigr)^5 \times \bigl(\tfrac{5}{7}\bigr)^{-3}$$  
4.  $$\bigl(-\tfrac{3}{5}\bigr)^{-3} \times \bigl(-\tfrac{5}{3}\bigr)^2$$  
5.  $$\bigl(\tfrac{3}{2}\bigr)^7 \times \bigl(\tfrac{1}{2}\bigr)^2$$  
6.  $$\bigl(-\tfrac{2}{3}\bigr)^5 \times \bigl(-\tfrac{3}{7}\bigr)^3$$  
7.  $$\bigl(-\tfrac{1}{2}\bigr)^5 \times 2^3 \times \bigl(\tfrac{3}{4}\bigr)^2$$  
8.  $$\bigl(\tfrac{3}{2}\bigr)^9 \times \bigl(\tfrac{3}{5}\bigr)^3 \times \bigl(\tfrac{1}{2}\bigr)^{-2}$$  
9.  $$\bigl(\tfrac{4}{7}\bigr)^3 - \bigl(\tfrac{5}{2}\bigr)^3 \times 4^2$$  
10. $$\bigl(\tfrac{4}{9}\bigr)^6 \times \bigl(\tfrac{4}{9}\bigr)^{-4}$$  
11. $$\bigl(-\tfrac{7}{8}\bigr)^{-3} \times \bigl(\tfrac{1}{2}\bigr)^8$$  
12. $$\bigl(\tfrac{4}{3}\bigr)^{-3} \times \bigl(\tfrac{4}{3}\bigr)^{-2}$$  
13. $$5^{-3}$$  
14. $$(-2)^{-5}$$  
15. $$\bigl(\tfrac{4}{7}\bigr)^{-4}$$  
16. $$\bigl(-\tfrac{3}{4}\bigr)^{-3}$$  
17. $$(-3)^{-1} \times \bigl(\tfrac{1}{3}\bigr)^{-1}$$  
18. $$\bigl(\tfrac{5}{7}\bigr)^{-1} \times \bigl(\tfrac{1}{4}\bigr)^{-1}$$  
19. $$\bigl(\tfrac{4}{5}\bigr)^{-2} \times \bigl(\tfrac{3}{5}\bigr)^{-2} \times \bigl(\tfrac{5}{3}\bigr)^2$$  
20. $$\bigl(\tfrac{3}{4}\bigr)^{-1} \times \bigl(\tfrac{3}{4}\bigr)^{-1}$$  
21. $$4^{-1} \times 4^{-2}$$  

---

## 5. Simplify (सल करें)

a.  $$\bigl[(-\tfrac{1}{2})^2\bigr\]^{-2-3}$$  
b.  $$\bigl[(-\tfrac{1}{3})^2\bigr]^{-2-7-1}$$  
c.  $$\bigl\[(-\tfrac{1}{4})^2\bigr\]^{-1}$$  
d.  $$\bigl\[(-\tfrac{2}{3})^2\bigr\]^{3}$$  
e.  $$\bigl\[(-\tfrac{3}{4})^{-2}\bigr\]^{-1}$$  
f.  $$\bigl[\tfrac{5}{7}\bigr]^{-2-2}$$  
g.  $$\bigl\[(-\tfrac{2}{3})^2\bigr\]^{-2}$$  
h.  $$\bigl[(-\tfrac{1}{3})^2\bigr]^{-2-1}$$  
i.  $$\bigl(\tfrac{3}{2}\bigr)^{-2\times2}$$  
j.  $$\bigl[\tfrac{5}{7}\bigr]^{2\times(-1)}$$  
k.  $$\bigl(\tfrac{3}{2}\bigr)^{-1\times(-3-1)}$$  
l.  $$\bigl(\tfrac{3}{7}\bigr)^{0}$$  
m.  $$\bigl(\tfrac{28}{27}\bigr)^{0-8}$$  
n.  $$\bigl[\tfrac{2}{5}^{\,-3}\bigr]^{\tfrac{3}{2}-1}$$  
o.  $$\bigl(\tfrac{32}{42}\bigr)^{\tfrac12\times2}$$  
p.  $$\bigl[\tfrac{5}{7}^{\,\tfrac32}\times\tfrac{2}{3}^{\,2}\bigr]^{2}$$  
q.  $$\bigl(\tfrac{6}{5}\bigr)^{2\times0}$$  
r.  $$\bigl[\tfrac{32}{9}^{\,\tfrac{5}{7}}\times\tfrac{7}{5}\bigr]^{2}$$  


## 6. Evaluate

a.  $$\bigl(6^{-1}\cdot8^{-1}\bigr)^{-1} \;+\; \bigl(2^{-1}\cdot3^{-1}\bigr)^{-1}$$  
b.  $$\bigl(6^{-1} + (\tfrac32)^{-1}\bigr\)^{-1}$$  
c.  $$(2^{-1}\div5^{-1}) \times \bigl(-\tfrac58\bigr)^{-1}$$  
d.  $$(\tfrac12)^{-2} + (\tfrac13)^{-2} + (\tfrac14)^{-2}$$  
e.  $$(-3)^{-1} \times (\tfrac13)^{-1}$$  
f.  $$\bigl(5^{-1}\cdot7^{-1}\bigr)^{-1}$$  
g.  $$4^0 + 5^0 + (\tfrac23)^0$$  
h.  $$(\tfrac32)^0 \times (\tfrac23)^0 \;-\; 2^0$$  
i.  $$\bigl(-\tfrac34\bigr)^3 \;-\; \bigl(-\tfrac54\bigr)^3 \times 4^2$$  
j.  $$\Bigl[(\tfrac43)^{-1}\times(\tfrac14)^{-1}\Bigr]^{-1}$$  
k.  $$\bigl(6^{-1}\cdot8^{-1}\bigr)^{-1}$$  
l.  $$\bigl(5^{-1}\times3^{-1}\bigr)^{-1}$$  
m.  $$(\tfrac12)^{-2} + (\tfrac13)^{-2} + (\tfrac14)^{-2}$$  
n.  $$\bigl(6^{-1} + (\tfrac32)^{-1}\bigr\)^{-1}$$  
o.  $$\bigl(,(\tfrac34)^{-1} - (\tfrac14)^{-1}\bigr\)^{-1}$$  
p.  $$\Bigl[(-\tfrac12)^2\Bigr]^{-2}$$  
q.  $$(3^2 - 2^2)\times(\tfrac23)^{-3}$$  
r.  $$\frac{(\tfrac13)^{-3} - (\tfrac12)^{-3}}{(\tfrac14)^{-3}}$$  
s.  $$\bigl\{\(\tfrac43)^{-1} - (\tfrac14)^{-1}\bigr\}^{-1}$$  
t.  $$\bigl(5^{-1}\times3^{-1}\bigr)^{-1} \;\div\; 6^{-1}$$  
u.  $$(\tfrac59)^{-2} \times (\tfrac35)^{-3} \times (\tfrac35)^0$$  
v.  $$\bigl(2^{-1}\times5^{-1}\bigr)^{-1} \;\div\; 4^{-1}$$  
w.  $$(4^{-1} + 8^{-1}) \;\div\; (\tfrac23)^{-1}$$  
x.  $$(\tfrac12)^{-2} + (\tfrac15)^{-2} + (\tfrac14)^{-2}$$  
y.  $$2^{\tfrac12} \times 2^{\tfrac12} \times 2^2$$  
z.  $$(\tfrac34)^{-\tfrac12} \times (\tfrac34)^{\tfrac12} \times (\tfrac34)^0$$  



## 7. Simplify (same base, divide)

a. $$\bigl(-\tfrac32\bigr)^3 \;\div\; \bigl(-\tfrac32\bigr)^6$$  
b. $$\bigl(-\tfrac23\bigr)^7 \;\div\; \bigl(-\tfrac23\bigr)^4$$  
c. $$\bigl(-\tfrac15\bigr)^3 \;\div\; \bigl(-\tfrac15\bigr)^8$$  
d. $$\bigl(-\tfrac25\bigr)^7 \;\div\; \bigl(-\tfrac25\bigr)^5$$  
e. $$\bigl(2^{-1}\div 5^{-1}\bigr)^2 \times \bigl(-\tfrac58\bigr)^{-1}$$  
f. $$\bigl(\tfrac34\bigr)^{-3} \;\div\; \bigl(\tfrac34\bigr)^{-1}$$  
g. $$2^{-1} \;\div\; 2^2$$  
h. $$\bigl(\tfrac57\bigr)^{-3} \;\div\; \bigl(\tfrac57\bigr)^4$$  
i. $$3^{-1} \;\div\; 3^{-2} \;\div\; 3^3$$  
j. $$\bigl(\tfrac23\bigr)^{-2} \;\div\; \bigl(\tfrac23\bigr)^{-6} \;\div\; \bigl(\tfrac23\bigr)^8$$  
k. $$q^{-5} \;\div\; q^{-6} \;\div\; q^{11}$$  
l. $$\bigl(\tfrac58\bigr)^{-3} \;\div\; \bigl(\tfrac58\bigr)^2 \;\div\; 3^0$$  
m. $$\Bigl(\tfrac35)^0 + (\tfrac23)^0\Bigr\^2 \;\Bigl\^{-1}$$  
n. $$(\tfrac56)^0 \;\div\; \bigl(\tfrac32\bigr)^{-1}$$  
o. $$\bigl(\tfrac32\bigr)^{-1} \;\div\; \bigl(\tfrac32\bigr)^{-3} \;\times\; \bigl(\tfrac32\bigr)^4$$  
p. $$q^{-11} \;\div\; q^{-11}$$  
q. $$5^{-3} \;\div\; 5^2 \;\div\; 5^{-5}$$  
r. $$\bigl(\tfrac32\bigr)^{-5} \;\div\; \bigl(\tfrac32\bigr)^8 \;\div\; \bigl(\tfrac32\bigr)^{-13}$$  

---

## 8. Word Problems

a. By what number \(x\) should we multiply \(3^{-9}\) so that the product equals \(3\)?  
$$
3^{-9}\times x \;=\; 3
$$

b. By what number \(y\) should we multiply \(\bigl(-8\bigr)^{-1}\) to obtain a product equal to \(10^{-1}\)?  
$$
(-8)^{-1}\times y \;=\; 10^{-1}
$$


## 8. More Word Problems

c. By what number \(z\) should \(( -15)^{-1}\) be divided so that the quotient is \(( -5)^{-1}\)?  
$$
\frac{(-15)^{-1}}{z}=(-5)^{-1}
$$

d. By what number \(w\) should \(( -5)^{-1}\) be multiplied so that the product is \((8)^{-1}\)?  
$$
(-5)^{-1}\times w=8^{-1}
$$

e. By what number \(x\) should we multiply \(3^{-3}\) so that the product is \(4\)?  
$$
3^{-3}\times x=4
$$

f. By what number \(u\) should \(( -30)^{-1}\) be divided so that the quotient is \((6)^{-1}\)?  
$$
\frac{(-30)^{-1}}{u}=6^{-1}
$$

g. By what number \(v\) should \(( -6)^{-1}\) be multiplied so that the product becomes \(9^{-1}\)?  
$$
(-6)^{-1}\times v=9^{-1}
$$

h. By what number \(t\) should \(\bigl(-\tfrac{2}{3}\bigr)^{-3}\) be divided so that the quotient is \(\bigl(\tfrac{4}{27}\bigr)^{-2}\)?  
$$
\frac{\bigl(-\tfrac{2}{3}\bigr)^{-3}}{t}=\bigl(\tfrac{4}{27}\bigr)^{-2}
$$

i. If  
$$
\frac{5^{2x+1}}{25}=125
$$  
find the value of \(x\).


## 9. More Exercises

j. Find \(x\) so that  
$$
\bigl(\tfrac{3}{5}\bigr)^3 \times \bigl(\tfrac{3}{5}\bigr)^{-6}
= \bigl(\tfrac{3}{5}\bigr)^{2x-1}
$$

k. If  
$$
\frac{2^{3x-1} + 10}{7} = 6,
$$  
then \(x\) is equal to ______.

l. By what number \(y\) should \(\bigl(\tfrac12\bigr)^{-1}\) be multiplied so that the product is \(\bigl(\tfrac54\bigr)^{-1}\)?  
$$
\bigl(\tfrac12\bigr)^{-1}\times y = \bigl(\tfrac54\bigr)^{-1}
$$

m. By what number \(z\) should \(\bigl(-\tfrac32\bigr)^{-3}\) be divided so that the quotient is \(\bigl(\tfrac97\bigr)^{-2}\)?  
$$
\frac{\bigl(-\tfrac32\bigr)^{-3}}{z} = \bigl(\tfrac97\bigr)^{-2}
$$

n. Find \(x\) so that  
$$
\frac{6^{x+2}}{6^1} = 6^{x+3}
$$

o. If  
$$
\bigl(\tfrac53\bigr)^{-5} \times \bigl(\tfrac53\bigr)^{11}
= \bigl(\tfrac53\bigr)^{8x},
$$  
then \(x =\) ______.

p. By what number \(w\) should \((-8)^{-1}\) be multiplied to get \(10^{-1}\)?  
$$
(-8)^{-1}\times w = 10^{-1}
$$

---

### Some Important Information (Square Roots)

$$
\sqrt{a} = a^{\frac12},\quad
\sqrt[3]{a} = a^{\frac13},\quad
\sqrt[4]{a} = a^{\frac14},\quad
\sqrt[5]{a} = a^{\frac15}.
$$

**Example:**

$$
\sqrt{4}
= \sqrt{2\times 2}
= \bigl(\sqrt{2}\bigr)^{2}
= \bigl(2^{\frac12}\bigr)^{2}
= 2
$$


## 10. Cube Roots and Simplify

### Cube Root Example

$$
\sqrt[3]{27}
= \sqrt[3]{3\times3\times3}
= 3
$$

---

### 10. Simplify (हल करें)

a.  
$$
\sqrt{a}\times\sqrt{a}
= a^{\tfrac12}\times a^{\tfrac12}
= a^{\tfrac12+\tfrac12}
= a^1
= a
$$

1.  
$$
\sqrt{2}\times\sqrt{2}\times\sqrt{2}
$$

2.  
$$
\sqrt{3}\times\sqrt{3}\times\sqrt{3}
$$

3.  
$$
\sqrt{5}\times\sqrt{5}\times\sqrt{2}
$$

4.  
$$
\sqrt{2}\times 2^2
$$

5.  
$$
\sqrt[3]{a}\times a^3
$$

6.  
$$
\sqrt{\tfrac{2}{3}}\times\sqrt{\tfrac{2}{3}}\times\bigl(\tfrac{2}{3}\bigr)^{-\tfrac{5}{6}}
$$

7.  
$$
\sqrt{a}\times\sqrt[3]{a}\times a^{-\tfrac{5}{6}}
$$

8.  
$$
\sqrt{2}\;\div\;\sqrt{2}
$$

9.  
$$
\sqrt[3]{a}\;\div\;\sqrt{a}
$$

10.  
$$
\sqrt[4]{a}\times\sqrt[4]{a}\times a^{-2}
$$

11.  
$$
\sqrt{\Pi}\;\div\;\sqrt{\Pi}\times\sqrt[3]{\Pi}
$$

12.  
$$
a^0\;\div\;\sqrt{2}\times\sqrt{2}
$$

13.  
$$
\sqrt[3]{a}\;\div\;\sqrt[2]{a}
\;=\;
a^{-\tfrac{1}{6}}
$$

14.  
$$
\sqrt{\tfrac{5}{6}}\;\div\;\sqrt{\tfrac{5}{6}}
\;+\;
\sqrt{2}\;\div\;\sqrt{2}
$$

15.  
$$
2^2\;\div\;\sqrt{2}\times\sqrt{2}\times\sqrt{2}\times\sqrt{2}
$$

16.  
$$
\bigl(\tfrac32\bigr)^0
\times\sqrt{2}\times\sqrt{2}
$$

17.  
$$
3^{-\tfrac12}\times\sqrt{3}\times\sqrt{2}
$$

18.  
$$
\bigl(\tfrac34\bigr)^{\tfrac32}\times\sqrt[3]{\tfrac35}
$$

19.  
$$
5^0\times 2^0
\;+\;
\sqrt{2}\times\bigl(\sqrt{2}\bigr)^{-1}
$$

20.  
$$
\sqrt[3]{2}\times\sqrt{2}\times\sqrt{2}
$$

21.  
$$
\bigl(\tfrac53\bigr)^3
\;\div\;
\sqrt[3]{\tfrac53}
$$

22.  
$$
\bigl(\tfrac23\bigr)^0
\;\div\;
\sqrt{3}\times\sqrt{3}
$$
