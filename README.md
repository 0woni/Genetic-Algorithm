# 유전 알고리즘 신경진화 — LunarLander
유전 알고리즘으로 진화시킨 신경망 가중치로 LunarLander 착륙선을 제어합니다.

- 신경망 8 → 6 → 4, 가중치 72개를 유전자 하나로 표현
- 적응도 = 에피소드 누적 보상
- 진화로 얻은 최적 유전자를 고정 시드(42)에서 재생

## 실행
pip install gymnasium[box2d] 후 python gym_Manual_Play_LunarLanderV2_learn.py