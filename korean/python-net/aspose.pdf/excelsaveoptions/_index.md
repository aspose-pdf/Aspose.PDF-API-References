---
title: "ExcelSaveOptions"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "Excel 형식으로 내보내기 위한 저장 옵션"
type: docs
weight: 330
url: /ko/python-net/aspose.pdf/excelsaveoptions/
---

## ExcelSaveOptions class

Excel 형식으로 내보내기 위한 저장 옵션

ExcelSaveOptions 형식은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| ExcelSaveOptions() | ExcelSaveOptions 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| warning_handler | 생성된 경고를 처리하기 위한 콜백입니다. <br/>            WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. <br/>            Continue는 기본 동작이며 저장 작업이 계속되지만, 사용자가 Abort를 반환하면 저장 작업이 중단되어야 합니다. |
| save_format | 데이터 저장 형식. |
| close_response | 문서가 응답에 저장된 후 Response 객체가 닫힐지를 나타내는 부울 값을 가져오거나 설정합니다. |
| extract_ocr_sublayer_only | 이 속성은 이미지 또는 텍스트를 추출하는 기능을 활성화합니다 <br/>            OCR 서브레이어가 있는 PDF 문서에 대해. |
| try_merge_adjacent_same_background_images | 때때로 PDF에는 페이지나 표 셀의 배경 이미지가 여러 개의 동일한 타일링 배경 이미지를 서로 가깝게 배치하여 구성됩니다.<br/>              이러한 경우 대상 형식의 렌더러(예: DOCS 형식의 MsWord)는 때때로 배경 이미지 부분 사이에 보이는 경계선을 생성합니다,<br/>              이는 이미지 가장자리 부드럽게 처리(안티앨리어싱) 기술이 Acrobat Reader와 다르기 때문입니다.<br/>               내보낸 문서에 동일한 배경 이미지 부분 사이에 이러한 보이는 경계가 있는 것처럼 보이면, 이 설정을 사용하여 원치 않는 효과를 제거해 보세요.<br/>              <br/>                주의! 이 품질 최적화는 일반적으로 변환 속도를 크게 늦춥니다,<br/>              따라서 정말 필요할 때만 이 옵션을 사용하십시오. |
| minimize_the_number_of_worksheets | 결과 워크북에서 워크시트 수를 최소화해야 하면 true로 설정합니다.<br/>            기본값은 false이며, 이는 각 PDF 페이지를 별도의 워크시트로 저장한다는 의미입니다. |
| insert_blank_column_at_first | 워크시트의 첫 번째 열에 빈 열을 삽입해야 하면 true로 설정합니다.<br/>            기본값은 false이며, 이는 빈 열이 삽입되지 않음을 의미합니다. |
| uniform_worksheets | 문서 전체에 균일한 열 구분을 사용하려면 true로 설정합니다. <br/>            기본값은 false이며, 이는 페이지마다 열 구분이 독립적으로 이루어진다는 의미입니다. |
| format | 출력 형식 |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

