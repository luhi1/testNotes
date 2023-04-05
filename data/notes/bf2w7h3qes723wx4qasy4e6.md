# Conjugates

## Sometimes you might need to multiply by conjugates to say bye bye to indeterminate form.

### 1. $lim_{x\to 81}\frac{\sqrt x -9}{x-81}$
### 2. $lim_{x\to 81}\frac{\sqrt x -9}{x-81} * \frac{\sqrt x +9}{\sqrt x +9}$
### 3. $lim_{x\to 81}\frac{(x-81)}{(x-81)\sqrt x +9}$
### 4. $lim_{x\to 81}\frac{1}{\sqrt x +9}$
### 5. $lim_{x\to 81}\frac{1}{\sqrt {81} +9}$
### 6. $lim_{x\to 81}\frac{1}{18}$

# Simplify Complex Fractions
## $\frac {a}{b} * \frac {c}{d} = \frac {ac}{bd} * \frac {ca}{bd}$

# Synthetic Division
1. ## $lim_{x\to 2} \frac {x^3-8}{x-2}$ 
2. ## Find what makes the bottom number 0
    * $x-2 = 0$, so $x = 2$
3. ## Do Synthetic Division 
    * We are $*$ by $2$
    * We split $x^3-8$ int $1x^3$, $0x^2$, $0x$, and $-8$
____
 $1$ | $0$ | $0$ | $-8$
--- | --- | --- | --- | --- 
 | 0| $1*2 = 2$ | $2*2 = 4$ | $4*2 = 8$
 | + |+ |+ | + 
 |$= 1$ | $=2$| $=4$ | $=0$ 
 ---
4. ## After synthetic division, we know $\frac{x^3-8}{x-2} = x^2 + 2x + 4$.
5. ## $lim_{x\to 2} \frac {x^3-8}{x-2} = lim_{x\to 2} x^2+ 2x + 4$, and by substitution, $2^2+2(2)+4 = 12$