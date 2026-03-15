# Equation Index

- Eq. 001 | line 330 | section=Factorization Machines(FM)
  - `\hat{y}(x) = w_0 + \sum_i w_i x_i + \sum_i \sum_j \langle v_i, v_j \rangle x_i x_j`
- Eq. 002 | line 336 | section=Factorization Machines(FM)
  - `\hat{y}(x) = \underbrace{w_0 + \sum_i w_i x_i}_{\text{로지스틱 회귀}} + \underbrace{\sum_i \sum_j \langle v_i, v_j \rangle x_i x_j}_{\text{쌍별 상호작용}}`
- Eq. 003 | line 391 | section=크로스 엔트로피(CE)
  - `H(p,q) = -\sum_{c=1}^{C} p_c \log q_c`
- Eq. 004 | line 397 | section=크로스 엔트로피(CE)
  - `H(p,q) = -\sum_{i} p_{i} \log q_{i} = -\sum_{i} \left( y_{i} \log \hat{y}_{i} + (1-y_{i}) \log (1-\hat{y}_{i}) \right)`
- Eq. 005 | line 407 | section=NCE(normalized cross-entropy)
  - `NCE = \frac{CE(머신러닝 모델)}{CE(단순 기준선)}`
