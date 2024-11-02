# 목표 : 

# 데이터셋 : https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

# 코멘트 번역

- 번역 모델 : https://huggingface.co/facebook/mbart-large-50-many-to-many-mmt
- 모델 선정 이유    
    - BERT는 트랜스포머의 인코더를 사용하는 모델로, 텍스트 전체 문맥을 양방향으로 처리하여 의미를 깊이 이해할 수 있음
    - 이러한 이유로 BERT 기반 모델을 채택했으며, BERT의 기본 구조를 유지하면서 학습 방법과 데이터 크기를 확장한 RoBERTa를 선택

