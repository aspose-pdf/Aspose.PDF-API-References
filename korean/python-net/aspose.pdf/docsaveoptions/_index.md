---
title: "DocSaveOptions"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "Doc 형식으로 내보내기 위한 저장 옵션"
type: docs
weight: 220
url: /ko/python-net/aspose.pdf/docsaveoptions/
---

## DocSaveOptions class

Doc 형식으로 내보내기 위한 저장 옵션

DocSaveOptions 형식은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| DocSaveOptions() | DocSaveOptions 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| warning_handler | 생성된 경고를 처리하기 위한 콜백입니다. <br/>            WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. <br/>            Continue는 기본 동작이며 저장 작업이 계속되지만, 사용자가 Abort를 반환하면 저장 작업이 중단되어야 합니다. |
| save_format | 데이터 저장 형식. |
| close_response | 문서가 응답에 저장된 후 Response 객체가 닫힐지를 나타내는 부울 값을 가져오거나 설정합니다. |
| extract_ocr_sublayer_only | 이 속성은 이미지 또는 텍스트를 추출하는 기능을 활성화합니다 <br/>            OCR 서브레이어가 있는 PDF 문서에 대해. |
| try_merge_adjacent_same_background_images | 때때로 PDF에는 페이지나 표 셀의 배경 이미지가 여러 개의 동일한 타일링 배경 이미지를 서로 가깝게 배치하여 구성됩니다.<br/>              이러한 경우 대상 형식의 렌더러(예: DOCS 형식의 MsWord)는 때때로 배경 이미지 부분 사이에 보이는 경계선을 생성합니다,<br/>              이는 이미지 가장자리 부드럽게 처리(안티앨리어싱) 기술이 Acrobat Reader와 다르기 때문입니다.<br/>               내보낸 문서에 동일한 배경 이미지 부분 사이에 이러한 보이는 경계가 있는 것처럼 보이면, 이 설정을 사용하여 원치 않는 효과를 제거해 보세요.<br/>              <br/>                주의! 이 품질 최적화는 일반적으로 변환 속도를 크게 늦춥니다,<br/>              따라서 정말 필요할 때만 이 옵션을 사용하십시오. |
| mode | 인식 모드. |
| relative_horizontal_proximity | In PDF에서는 단어가 문자나 음절을 독립적으로 출력하는 연산자를 사용하여 내부적으로 표현될 수 있습니다.<br/>              따라서 단어를 감지하기 위해 때때로 실제 단어인 독립 문자 그룹을 감지해야 합니다.<br/>                이 설정은 텍스트 요소(문자, 음절) 사이의 공간 너비를 정의합니다 <br/>              이 너비는 원본 PDF에서 단어를 인식할 때 단어 사이 거리로 간주됩니다.<br/>              (문자 사이에 최소 이 너비만큼의 빈 공간이 있으면 해당 텍스트 요소는 다른 단어에 속한다는 의미입니다).<br/>              이는 글꼴 크기에 정규화됩니다 - 1.0은 예상 단어 글꼴 크기의 100%를 의미합니다.<br/>             주의! 이 값은 원본 PDF에 특정 드물게 사용되는 글꼴이 포함되어 있어 글꼴로부터 최적 값을 계산할 수 없는 경우에만 사용됩니다.<br/>             따라서 대부분의 경우 이 매개변수는 결과 문서에 아무 영향을 주지 않습니다. |
| max_distance_between_text_lines | 이 매개변수는 텍스트 라인을 단락으로 그룹화하는 데 사용됩니다.<br/>            두 텍스트 라인이 서로 얼마나 떨어질 수 있는지를 결정합니다. 텍스트 라인 높이의 수백 퍼센트로 지정됩니다. |
| recognize_bullets | 글머리 기호 인식을 켭니다 |
| add_return_to_line_end | 단락 또는 줄 바꿈을 사용합니다 |
| image_resolution_x | 변환된 이미지 X 해상도. |
| image_resolution_y | 변환된 이미지 Y 해상도. |
| format | 출력 형식 |
| batch_size | 배치 변환이 소스 및 대상 형식 쌍에 적용되는 경우 배치 크기를 정의합니다.<br/>             |
| memory_save_mode_path | 메모리 저장 모드로 변환할 때 임시 데이터를 보관할 경로(파일 이름 또는 디렉터리 이름)를 정의합니다<br/>            . |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

