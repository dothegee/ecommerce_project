# 리뷰 활성화를 통한 커뮤니티 기반 상품 신뢰도 및 구매력 증대 리워드 보상 체계 구축

## 목표

고객이 리뷰를 더 많이 작성하고, 상세하고 유용한 코멘트를 남기도록 유도하여 커뮤니티 활성화와 상품 신뢰도를 높임

이를 통해 상품 구매력을 증대시키고, 고객 충성도를 강화하는 것을 목표

## 데이터셋

https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

## 코멘트 번역

- 번역 모델 : https://huggingface.co/facebook/mbart-large-50-many-to-many-mmt
- 모델 선정 이유    
    - BERT는 트랜스포머의 인코더를 사용하는 모델로, 텍스트 전체 문맥을 양방향으로 처리하여 의미를 깊이 이해할 수 있음
    - 이러한 이유로 BERT 기반 모델을 채택했으며, BERT의 기본 구조를 유지하면서 학습 방법과 데이터 크기를 확장한 RoBERTa를 선택

