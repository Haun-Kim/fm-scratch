# fm-scratch
- 2026-09-02: 2D flow matching scratch 구현 및 NFE 실험
    loss가 안 떨어지는 이유 = conditional velocity의 분산. 
    n_step=1 일때 data 무게중심으로 모이는이유
    Euler 대신 Heun Solver 사용 했을때 step 이 작을때 안좋고 step 늘어날수록 좋음
  