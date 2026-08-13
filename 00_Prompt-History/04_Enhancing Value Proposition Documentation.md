# 04. 구조 재정리 — 공식 챕터와 별도 실습 트랙의 분리

> [PRD-From-VPS-Sample](https://github.com/wild-mental/PRD-From-VPS-Sample/blob/main/00_Prompt-History/04_Enhancing%20Value%20Proposition%20Documentation.md)의 4번 프롬프트 이력에 대응.

## 실제 프롬프트 (그대로 인용, 두 차례)

> "제대로 구분해서 설명해. 지금 https://github.com/ahalenin12-art/business_research/tree/main/08-competitor-branding 이 링크 9번이 https://github.com/wild-mental/business-research-practice-2026-sesac/tree/main/04-tam-sam-som/리서치-원본 이링크랑 안맞고, 10번 항목이 없는데 내 링크에는 10이 있잖아"

이어서 AskUserQuestion 답변:

> "09는 공식형식만 남기고, 별도 샘플저장소는 https://github.com/wild-mental/PRD-From-VPS-Sample/tree/main 이 링크의 내용을 참고해서 모든 형식을 동일하게 만들어줘"

## 무엇이 일어났는가

- 03번 단계에서 섞였던 것을 바로잡았다: [챕터 09](../09-value-proposition/)는 레퍼런스 커리큘럼의 공식 7섹션 형식(v1.0)만 남기고, 별도로 만들었던 rooted VPS·PRD 문서는 **커리큘럼에 없던 `10-prd/`에서 꺼내** `PRD-From-VPS-Sample`과 동일한 폴더 체계(`00_Prompt-History`~`04_VPS-final`)로 이동시켰다.
- `01_Biz-Analysis`의 10개 파일 중 Porter's·가치사슬·KSF 3개는 이 사업(예술품 재분배)에 대해 **실제로 작성된 적이 없다는 사실을 숨기지 않고 결번으로 남겼다** — 샘플처럼 있지도 않은 분석을 지어내지 않았다.
- `02_VPS-Drafts`에서도 샘플의 "두 AI 모델 비교" 단계는 우리가 실제로 거치지 않은 과정이므로 재현하지 않고, 그 사실을 문서 안에 명시했다.

## 이 실습에서 얻은 교훈

**형식을 동일하게 만드는 것과 없는 내용을 지어내는 것은 다르다.** 샘플 저장소의 폴더·파일 구조는 최대한 동일하게 맞추되, 그 폴더 안의 내용이 우리 실제 작업 이력과 다를 때는(예: 다중 모델 비교를 하지 않음, Porter's/가치사슬/KSF가 이 사업엔 없음) 형식을 억지로 채우지 않고 **결번·생략 사유를 문서 자체에 남긴다.** 이는 이 프로젝트 전체가 처음부터 지켜온 (확인)/(추정)/(가정) 표기 원칙과 같은 정신이다.
