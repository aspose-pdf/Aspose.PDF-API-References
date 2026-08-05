---
title: "UnifiedSaveOptions"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "이 클래스는 통합 변환 방식(통합 내부 문서 모델 사용)을 사용하는 저장 옵션을 나타냅니다.<br/>            통합 변환 방식을 사용합니다 (통합 내부 문서 모델 포함)."
type: docs
weight: 1590
url: /ko/python-net/aspose.pdf/unifiedsaveoptions/
---

## UnifiedSaveOptions class

이 클래스는 통합 변환 방식(통합 내부 문서 모델 사용)을 사용하는 저장 옵션을 나타냅니다.<br/>            통합 변환 방식을 사용합니다 (통합 내부 문서 모델 포함).

UnifiedSaveOptions 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| UnifiedSaveOptions() | UnifiedSaveOptions 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| warning_handler | 생성된 경고를 처리하기 위한 콜백입니다. <br/>            WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. <br/>            Continue는 기본 동작이며 저장 작업이 계속되지만, 사용자가 Abort를 반환하면 저장 작업이 중단되어야 합니다. |
| save_format | 데이터 저장 형식. |
| close_response | 문서가 응답에 저장된 후 Response 객체가 닫힐지를 나타내는 부울 값을 가져오거나 설정합니다. |
| extract_ocr_sublayer_only | 이 속성은 이미지 또는 텍스트를 추출하는 기능을 활성화합니다 <br/>            OCR 서브레이어가 있는 PDF 문서에 대해. |
| try_merge_adjacent_same_background_images | 때때로 PDF에는 페이지나 표 셀의 배경 이미지가 여러 개의 동일한 타일링 배경 이미지를 서로 가깝게 배치하여 구성됩니다.<br/>              이러한 경우 대상 형식의 렌더러(예: DOCS 형식의 MsWord)는 때때로 배경 이미지 부분 사이에 보이는 경계선을 생성합니다,<br/>              이는 이미지 가장자리 부드럽게 처리(안티앨리어싱) 기술이 Acrobat Reader와 다르기 때문입니다.<br/>               내보낸 문서에 동일한 배경 이미지 부분 사이에 이러한 보이는 경계가 있는 것처럼 보이면, 이 설정을 사용하여 원치 않는 효과를 제거해 보세요.<br/>              <br/>                주의! 이 품질 최적화는 일반적으로 변환 속도를 크게 늦춥니다,<br/>              따라서 정말 필요할 때만 이 옵션을 사용하십시오. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

