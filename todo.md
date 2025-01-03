# ToDo
-----------


## 리워드를 가르는 기준이 low, mid, high인데 3단계면 충분해? -> 작은 것들도 하나씩 고민해두면 고민의 깊이가 더 쌓일거예요!


## 리워드 유형별 고객 반응 비교
    정액 리워드 vs 정율 리워드에 대한 고객 반응 차이: 두 리워드 유형에 대한 고객 반응을 막대그래프로 비교하여 어떤 리워드가 더 효과적인지 파악.

## 리워드 유형 및 금액별 예상 추가 매출 분석
    리워드 제공으로 인한 예상 추가 매출 시뮬레이션: 리워드 유형 및 금액별 예상 추가 매출을 선 그래프로 나타내어 최적의 리워드 금액을 시뮬레이션을 통해 도출.

## 고객 충성도 분석
    리뷰 작성 빈도와 재구매율의 상관관계: 리뷰 작성 빈도와 재구매율의 상관관계를 산점도로 나타내어 리뷰 활성화가 고객 충성도에 미치는 영향을 시각화.

## 커뮤니티 활성화 지표
    리워드 제공 이후 월별 리뷰 길이 평균: 월별 리뷰 길이의 변화를 시계열 그래프로 나타내어 리뷰 품질 향상을 확인.






-----------
# Doing
-----------
## 1. data summary 
    - 타겟 변수를 중심으로 한 분포: 예를 들어, 특정 제품군별, 고객 유형별 리뷰 빈도 분포 등을 파악하기 위해 막대 그래프 활용.

    보완점: 데이터의 주요 통계량(리뷰 길이, 평균 별점, 코멘트 포함 비율 등)을 표나 요약 그래프 형태로 시각화하여 초기 데이터 이해도를 높이세요.
    그래프 제안:
    히스토그램: 리뷰 길이 분포.
    박스플롯: 별점에 따른 리뷰 길이 분포.
    파이 차트: 코멘트 작성 여부 비율.


## 2. data preprocessing
    - 포르투갈어 -> 영어
        - 번역 전후 데이터 개수를 막대그래프로 나타내 번역 누락 상태 파악.
    - 리뷰 라벨링
        - 각 라벨(긍정, 부정, 중립 등)의 분포를 파이 차트로 나타내어 데이터의 균형 여부 확인.

    포르투갈어 리뷰 번역과 라벨링 작업은 명확히 정의되어 있지만 구체적인 평가 방식과 단계가 더 필요합니다.

    보완점:
    번역 정확도 및 번역 품질 확인 방법 명시.
    라벨링 기준(문장 길이, 특정 키워드 등)을 구체적으로 기술.
    그래프 제안: 번역 전후 리뷰 단어 수 비교, 라벨별 데이터 분포를 막대그래프로 표시.


## 3. 문제 탐색 및 정의
    - 단회 구매 고객 비율과 매출 기여도: 단회 및 다회 구매 고객의 비율과 매출 기여도를 한눈에 비교하기 위한 파이 차트나 도넛 차트.
    - 단회 vs 다회 고객의 구매 패턴: 단회 구매와 다회 구매에서 가격 할인율에 따른 구매 패턴을 보여주는 히트맵이나 선 그래프.



## 4. 니즈 파악
    - 상품 품질/ 배송 기간 여부 중요
    - 품질과 배송 관련 키워드가 리뷰에서 얼마나 자주 언급되는지 막대그래프로 시각화하여 고객 니즈의 주요 포인트를 도출.


3. 니즈 파악 및 문제 정의
    고객 니즈 분석과 플랫폼 문제 정의를 구체적으로 시각화하면 명확도가 증가합니다.

    보완점:
    고객 이탈 원인 분석(이탈률, 이탈 사유 등).
    리뷰 작성 빈도와 고객 충성도 간 상관관계를 강조.
    그래프 제안:
    코호트 그래프: 첫 리뷰 작성 후 리뷰 지속 작성 비율.
    꺾은선 그래프: 리뷰 작성 빈도와 구매 빈도 간 상관 관계.

    
4. 리워드 설계 프로세스
    리워드 차등화 기준과 신뢰도 평가 방식은 구체적이지만, 가상의 시뮬레이션 단계에 대한 디테일이 추가되어야 합니다.

    보완점:
    각 리워드 등급별 기대 효과를 수치화(예: 예상 리뷰 수 증가율).
    시뮬레이션 입력 변수와 결과를 명확히 정의.
    그래프 제안:
    막대그래프: 리워드 등급별 예상 리뷰 작성 수 증가.
    분포 그래프: 손익 지점 시뮬레이션 결과.
5. 손익 분석 시뮬레이션
    손익 분석은 구체적인 수익 계산 방식과 가정을 시각적으로 표현하면 좋습니다.

    보완점:
    리워드 지급 비용 대비 예상 추가 매출 증대 수치를 정리.
    시뮬레이션 결과를 다양한 변수에 따라 정리.
    그래프 제안:
    선형 그래프: 리워드 지급 금액 대비 손익분기점.
    산점도: 리워드 지급 후 재구매율 증가율.
6. 결론 및 기대 효과
    기대 효과는 정량적 및 정성적 데이터를 포함해야 더 설득력 있습니다.

    보완점:
    구매 전환율 증가, 고객 충성도 상승 등 구체적 수치 제시.
    예상 시나리오별 효과 정리.
    그래프 제안:
    시나리오 분석 차트: 리워드 제공 여부에 따른 주요 성과 지표 변화.
    문구 개선 제안
    리워드 설계: "신뢰도 평가 기준을 명확히 하여 고객 참여를 유도하고, 단계별로 차등화된 보상을 통해 고객 만족도를 극대화합니다."
    기대 효과: "리워드 보상 체계를 통해 커뮤니티 활성화와 고객 충성도를 증대하며, 이로 인해 플랫폼 전반의 구매력을 증가시킬 수 있습니다."
    시뮬레이션 결과: "시뮬레이션 결과, 각 리워드 등급에서 수익성을 보장하는 최적의 리워드 조합을 확인하였습니다."

-----------
# Done
-----------

## Git 커밋 및 Push 시 유의 사항
Push 전 확인: 데스크톱의 Git 업데이트 상태를 확인한 후, 노트북(.ipynb) 파일을 커밋 및 Push합니다.
무작정 Push할 경우 버전 충돌의 가능성이 있으므로 사전 확인 필수

## 데이터 전처리
- 별점 O, 코멘트 X: 코멘트 length = 0으로 처리
- 별점 X, 코멘트 X: 해당 항목은 분석에서 제외 (drop)
- 별점을 준 고객은 리뷰를 남길 환경이 갖춰진 것으로 보고, 코멘트를 작성하지 않은 경우로 판단


## 코멘트 길이 기준 설정
- 상위 10% ~ 50%: 코멘트 작성자들의 리뷰 길이 평균을 10% 단위로 계산하여 총 5개의 기준을 생성
- 부정 리뷰 길이 평균: 별점 1개 또는 2개 이하인 리뷰의 길이 평균을 참고하여 긍정 리뷰도 구체적이고 상세하게 유도하는 데 활용


## 별점에 따른 리뷰 비교
- 별점 별 리뷰 길이 평균: 별점에 따른 리뷰 길이 평균을 비교하여 리뷰 작성 패턴을 분석
- 별점 별 리뷰 수 비교: 별점별 리뷰 개수를 비교하여 각 별점 분포 파악

## 신뢰도 평가
- 기준 : 코멘트길이 100자, 상품품질에 관한내용, 배송기간에 대한 내용이 들어있을 때 코멘트에 신뢰도가 있다
- 현재 신뢰도 체크


## 리뷰 유형에 따른 신뢰도 분석
    리뷰 길이와 키워드 포함 여부에 따른 신뢰도 수준 분포: 리뷰 길이와 키워드 포함 여부에 따른 신뢰도를 히트맵이나 상관 행렬로 나타내어 신뢰도 평가 기준의 적절성 확인.



## 시뮬레이션 진행
    - 리워드 금액에 따른 예상 수익을 계산하여, 손익 지점을 찾기
    - 시뮬레이션 방법:
        - 리워드 제공 전후의 평균 구매 수 비교
        - 리워드 제공에 따른 예상 추가 거래액을 기반으로 수익성 분석
            - total_revenue_with_reward * 0.1 - (reward * len(df))
        - 리워드 제공 전후 고객 리뷰 수 변화: 리워드 제공 전후 월별 리뷰 작성 수를 시계열 그래프로 나타내어 리워드가 리뷰 활성화에 미친 영향을 파악.
        - 리워드 제공 전후 구매율 변화: A/B 테스트로 리워드 도입 전후의 구매율 변화를 시계열 그래프로 나타내어 효과 검증.