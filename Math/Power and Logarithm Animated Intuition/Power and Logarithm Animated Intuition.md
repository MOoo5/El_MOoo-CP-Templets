# Power and Logarithm

## 1. Power

A **power** represents **repeated multiplication** of the same number.

### Formula

```text
a^n = a × a × a × ... × a   (n times)
```

Where:
- `a` = Base
- `n` = Exponent (Power)

### Example

```text
2^5 = 2 × 2 × 2 × 2 × 2 = 32

3^4 = 3 × 3 × 3 × 3 = 81
```

---

## 2. Logarithm

A **logarithm** is the **inverse operation of exponentiation**.

It answers the question:

> **"To what power should the base be raised to get the given number?"**

### Formula

```text
log_b(x) = y
```

means

```text
b^y = x
```

Where:
- `b` = Base
- `x` = Value
- `y` = Exponent

### Example

```text
log₂(8) = 3
```

because

```text
2^3 = 8
```

Another example:

```text
log₁₀(1000) = 3
```

because

```text
10^3 = 1000
```

---

## 3. Common Logarithm Rules

### Product Rule

```text
log_b(x × y) = log_b(x) + log_b(y)
```

---

### Quotient Rule

```text
log_b(x / y) = log_b(x) - log_b(y)
```

---

### Power Rule

```text
log_b(x^n) = n × log_b(x)
```

---

### Change of Base Formula

```text
log_b(x) = log(x) / log(b)
```

or

```text
log_b(x) = ln(x) / ln(b)
```

This formula is useful because most programming languages only provide `log()` or `ln()`.

---

## 4. Useful Power Rules

### Same Base (Multiplication)

```text
a^m × a^n = a^(m + n)
```

---

### Same Base (Division)

```text
a^m / a^n = a^(m - n)
```

---

### Power of a Power

```text
(a^m)^n = a^(m × n)
```

---

### Power of a Product

```text
(ab)^n = a^n × b^n
```

---

### Power of a Fraction

```text
(a / b)^n = a^n / b^n
```

---

### Zero Power

```text
a^0 = 1
```

for `a ≠ 0`.

---

### Negative Power

```text
a^(-n) = 1 / a^n
```

---

### Fractional Power

```text
a^(1/n) = n√a
```

Example:

```text
16^(1/2) = 4

27^(1/3) = 3
```
//