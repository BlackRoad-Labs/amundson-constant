# The Amundson Constant

**A_G = 1.244331783986725374135061629258...**

## Definition

A_G = Σ G(n)/n! where G(n) = n/(1+1/n)^n

Six symbols: `n`, `1`, `+`, `/`, `^`, `()`

## Properties

- Converges by n=18 to 15 digits, n=43 to 50 digits
- Not found in any existing constant database
- Derived from pure integer arithmetic (n^(n+1)/(n+1)^n)
- Produces a valid quantum density matrix (trace = 1)
- Von Neumann entropy: S = 1.272 (1.835 bits)
- The circle x² + y² = 1/e² + 1/4 intersects Re(s)=1/2 at y=±1/e
- G(1) = 1/2 (spin-1/2, the half-quantum)
- L/H → e (Lagrangian/Hamiltonian ratio)
- G(e) ≠ 1 (e is not self-consistent under its own definition)

## Files

- `AMUNDSON_CONSTANT.txt` — 1,000,001 verified digits
- `AMUNDSON_CONSTANT_10M.txt` — 10,000,000 digits (computing)

## The Formula

```
G(n) = n / (1 + 1/n)^n = n^(n+1) / (n+1)^n

G(0) = 0
G(1) = 1/2
G(2) = 8/9
G(3) = 81/64
G(4) = 1024/625

A_G = Σ G(n)/n! = 1.244331783986725...
```

## Verified Identities (50+)

1. G(n) = n^(n+1)/(n+1)^n
2. G(n) = n(n/(n+1))^n
3. G(n) = (n+1)(n/(n+1))^(n+1)
4. G(n)/(n+1) = (n/(n+1))^(n+1) → 1/e
5. Π G(k) = (n!)²/(n+1)^n
6. Π G(k) = (2n)!/(C(2n,n)(n+1)^n)
7. 1/G(n) = (1+1/n)^n/n
8. ln(G(n)) = (n+1)ln(n) - n·ln(n+1)
9. ρ(n) = G(n)/(n!·A_G) sums to 1 (density matrix)
10. S = -Σ ρ ln(ρ) = 1.272 (1.835 bits)
11. G(n+1) - G(n) → 1/e
12. step/(step[-1]×step[-2]) → e
13. L(n)/H(n) → e where H=G(n), L=n-(n/(n+1))^n

## Author

Alexa Louise Amundson
Founder & CEO, BlackRoad OS, Inc.

## License

Proprietary — BlackRoad OS, Inc. All rights reserved.
