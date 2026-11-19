# LABSP830 · vLLM Semantic Router로 추론 경로 선택하기

**하나의 앱 엔드포인트에서 요청을 분류하고 정책 우선순위로 답변 모델을 선택하는 실습이다.**

2026-11-19 · 공식 실습자료 기반 · GPU·추론·비용

## 핵심 내용

- 앱은 vLLM Semantic Router의 `vllm-sr/auto`를 호출한다. 이름표 같은 정확한 신호와 요청의 의미를 반영한 신호를 YAML로 조합해 모델 경로를 고른다.
- D3 Lite로 추론 필요성을 판단하고, 선택 실습에서는 Vela 3 Fast로 이름·이메일·전화번호의 텍스트 구간을 찾는다. 답변 생성은 라우터가 선택한 별도 모델이 맡는다.
- `[PRIVATE]`와 의미 기반 판단이 동시에 맞으면 더 높은 우선순위의 정책을 적용한다. 최종 과제는 `[INCIDENT]` 태그와 모호한 요청을 포함한 여섯 가지 입력으로 경로를 확인한다.

## 확인 범위

발표자 공개 노트북과 슬라이드로 실습 절차를 확인했다. 예제에서 D3 Lite는 로컬 CPU에서 실행되며 두 답변 모델은 Azure Foundry에 연결된다. 사내망에 적용하려면 민감 요청이 선택하는 경로의 실제 서빙 주소와 네트워크 정책을 확인해야 한다. 카탈로그에는 녹화 계획이 없다.

## 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1790705089430001luN0-1791911961057001WtJj)
- [발표자 노트북 고정 버전](https://github.com/Mahdi-CV/amd-gpu-workshops/blob/51dc74ee2bee9fe35e1335716b03b564560d7e74/notebooks/vllm-sr-route-one-agent-v3/route-one-agent-across-two-models-v3.ipynb)
- [발표 슬라이드 고정 버전](https://github.com/Mahdi-CV/amd-gpu-workshops/blob/51dc74ee2bee9fe35e1335716b03b564560d7e74/notebooks/vllm-sr-route-one-agent-v3/.deploy/vllm-sr-workshop-intro.pptx)

[전체 세션 목록](../../README.md)
