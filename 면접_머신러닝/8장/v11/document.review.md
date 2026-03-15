# OCR Review

## Summary

- score: 79
- status: review_needed
- suspicious_lines: 7

## Busy Sections

- Factorization Machines(FM) | tables=0 | captions=1 | equations=2
- NCE(normalized cross-entropy) | tables=0 | captions=1 | equations=1
- 광고 | tables=1 | captions=1 | equations=0
- 데이터세트 구성 | tables=1 | captions=1 | equations=0
- 사용자 | tables=1 | captions=1 | equations=0

## Suspicious Categories

- broken_sup: 1
- split_verb: 6

## Suspicious Lines

- line 18 | split_verb | 지원자: 광고 예측 시스템을 구축하는 비즈니스 목표가 수익 극대화라고 가정 해도 되나요?
- line 26 | split_verb | 지원자: 시스템에서 한 사용자에게 동일한 광고를 두 번 이상 표시할 수 있 나요?
- line 32 | split_verb | 면접관: 좋은 질문입니다. 사용자가 마음에 들지 않는 광고를 숨길 수 있다고 가정해 보죠. '이 광고 차단'은 흥미로운 기능이지만 지금은 지원할 필 요가 없습니다.
- line 48 | broken_sup | 면접관: 좋은 지적입니다. 실험에 따르면 모델 업데이트가 5분만 지연되어도 성능이 저하될 수 있습니다<sup>!!</sup>.
- line 360 | split_verb | - 포지티브 라벨: 사용자가 광고가 표시된 후 t초 이내에 광고를 클릭하면 데이터 포인트에 '포지티브'라는 라벨을 지정한다. t는 하이퍼파라미터이며 실험 을 통해 조정할 수 있다.
- line 361 | split_verb | - 네거티브 라벨: 사용자가 t초 이내에 광고를 클릭하지 않으면 해당 데이터 포 인트에 '네거티브'라는 라벨을 지정한다.
- line 372 | split_verb | 모델이 새로운 데이터에 적응할 수 있도록 하려면 지속적으로 학습해야 한다. 따라서 새로운 상호작용을 사용하여 새로운 학습 데이터 포인트를 지속해 생 성해야 한다. 지속적인 학습에 대해서는 '서빙' 절에서 자세히 설명하겠다.
