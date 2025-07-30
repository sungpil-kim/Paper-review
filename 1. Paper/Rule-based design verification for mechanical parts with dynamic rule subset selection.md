# Rule-based design verification for mechanical parts with dynamic rule subset selection
- 저자 : Hyeonji Lee, Changmo Yeo, Seungeun Lim, Byung Chul Kim, Kyung Cheol Bae & Duhwan Mun
- 학회 : Scientific Reports volume 15, Article number: 17153 (2025)

 
## 1. 서론


- 기존 Ontology 및 SWRL 방식의 한계<br>
  #Ontology = 지식이 어떻게 연결되어 있는지 정의 (정적 구조)<Br>
  #SWRL = 온톨리지 지식 기반에서 조건-결과 논리를 활용해 ‘추론’ (동적 로직)<br>
  SWRL의 한계 : 논리적 추론이나 정의에는 효과적이지만, 복잡한 산술을 포함하는 ‘검증방정식’을 직접적으로 표현하고 계산하는 데 제약.

- 논문에서 제시하는 개선점
  RQ1: 3D CAD 모델이 설계 요구 사항을 자동으로 충족하는지 확인하는 데 어떤 접근 방식을 사용할 수 있는가?
  RQ2: 유지보수성과 확장성을 모두 충족하면서 높은 표현력을 보장하기 위해 디자인 규칙을 어떻게 정의할 수 있는가?
  RQ3: 검증 대상과 관련된 규칙만 선택하여 효율적으로 설계 검증을 수행하는 가장 좋은 방법은 무엇인가?
