# 03. 별도 샘플 저장소와의 비교 발견

> [PRD-From-VPS-Sample](https://github.com/wild-mental/PRD-From-VPS-Sample/blob/main/00_Prompt-History/03_Comparing%20Value%20Proposition%20Drafts.md)의 3번 프롬프트 이력에 대응. 다만 우리 실습에서는 "두 AI 모델의 VPS 초안 비교"가 아니라 **"우리가 만든 문서와 강사가 만든 완결형 VPS-PRD 샘플 저장소의 형식 비교"**였다.

## 실제 프롬프트 (그대로 인용)

> "지금 https://github.com/wild-mental/PRD-From-VPS-Sample/tree/main 이게 강사가 만든 VPS같은데 https://wildmental.notion.site/08-2-VPS-3bad03212bd480ddb391fed7e1d866ac 이 내용 참고해서 나도 같은 문서들 만들어줘봐"

## 무엇이 일어났는가

- `PRD-From-VPS-Sample` 저장소 전체 트리(`00_Prompt-History`~`04_VPS-final`)를 처음 확인. 이전에 참고했던 레퍼런스 커리큘럼 저장소(`business-research-practice-2026-sesac`, 챕터 01~09)와는 **완전히 다른, 별도의 예시 저장소**라는 것이 이때 드러났다.
- Notion "08-2. 전체 분석자료 정제 및 VPS 문서를 통합본으로 고도화" 페이지를 확인 — VPS 통합 절차(정제→두 모델 비교→병합→rooting)를 설명하는 방법론 문서였다.
- 처음에는 이 둘을 구분하지 않고 [챕터 09](../09-value-proposition/) 폴더와 `10-prd/`라는 (커리큘럼에 없는) 새 챕터 번호에 섞어 넣었다 — 이것이 바로 다음 프롬프트(04번)에서 사용자가 바로잡은 실수다.

## 이 실습에서 얻은 교훈

**"같은 강사가 만든 자료"라고 해서 같은 번호 체계·같은 위계에 속하는 것은 아니다.** 공식 커리큘럼(챕터 01~09)과 별도 데모 저장소(작업단계 00~04)를 섞으면, 커리큘럼에 없는 "10번 챕터"가 생기는 것처럼 눈에 보이는 구조적 오류가 발생한다. 두 소스를 다루기 전에 **"이게 같은 번호 체계 안의 다음 단계인가, 아니면 완전히 다른 별도 자료인가"**를 먼저 확인해야 한다.
