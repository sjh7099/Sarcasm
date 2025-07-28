# Sarcasm

## Overview
- 국내 풍자 탐지용 데이터 코퍼스의 부족
- 한국어 풍자탐지 관련 연구의 한계 : 긴 문맥에 의존, 도메인 다양성 부족
- 짧은 문맥에서도 풍자를 잘 탐지할 수 있도록 LLM 모델 학습

## 풍자 탐지 데이터 코퍼스 구축
- prompt engineering을 통한 데이터 구축
- Chain of Thought 기법 활용
<img width="603" height="229" alt="스크린샷 2025-07-28 오후 3 01 08" src="https://github.com/user-attachments/assets/e85599df-16b1-43f7-a19f-5413976c84d2" />

## 풍자 탐지 LLM 모델 튜닝
- KoBERT 파인튜닝 vs Bllossom 파인튜닝 후 성능 비교
<img width="386" height="193" alt="스크린샷 2025-07-28 오후 3 00 51" src="https://github.com/user-attachments/assets/8f5b6c98-9af2-433c-997a-2f3f842e5125" />

### Reference
This repository refers to [KoCoSa: Korean Context-aware Sarcasm Detection Dataset](https://github.com/Yu-billie/KoCoSa_sarcasm_detection), accepted in COLING 2024.
