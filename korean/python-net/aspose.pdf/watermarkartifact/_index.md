---
title: "WatermarkArtifact"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "클래스는 워터마크 아티팩트를 설명합니다. 이는 다음에 사용될 수 있습니다."
type: docs
weight: 1640
url: /ko/python-net/aspose.pdf/watermarkartifact/
---

## WatermarkArtifact class

클래스는 워터마크 아티팩트를 설명합니다. 이는 다음에 사용될 수 있습니다.

WatermarkArtifact 타입은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| WatermarkArtifact() | Watermark 아티팩트의 인스턴스를 생성합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| custom_type | artifact 유형의 이름을 가져옵니다. 비표준 artifact 유형인 경우 사용할 수 있습니다. |
| custom_subtype | artifact 서브타입의 이름을 가져옵니다. artifact 서브타입이 표준 서브타입이 아닌 경우 사용할 수 있습니다. |
| type | artifact 유형을 가져옵니다. |
| subtype | 아티팩트 서브타입을 가져옵니다. 아티팩트에 비표준 서브타입이 있는 경우, 서브타입 이름은 CustomSubtype를 통해 읽을 수 있습니다. |
| 내용 | 아티팩트 내부 연산자들의 컬렉션을 가져옵니다. |
| form | 아티팩트의 XForm을 가져옵니다 (XForm이 사용된 경우). |
| rectangle | 아티팩트의 사각형을 가져옵니다. |
| position | 아티팩트 위치를 가져오거나 설정합니다.<br/>            이 속성이 지정되면 여백과 정렬이 무시됩니다. |
| right_margin | 아티팩트의 오른쪽 여백. <br/>            위치가 Position 속성에서 명시적으로 지정된 경우 이 값은 무시됩니다. |
| left_margin | 아티팩트의 왼쪽 여백. <br/>            위치가 Position 속성에서 명시적으로 지정된 경우 이 값은 무시됩니다. |
| top_margin | 아티팩트의 위쪽 여백. <br/>            위치가 Position 속성에서 명시적으로 지정된 경우 이 값은 무시됩니다. |
| bottom_margin | 아티팩트의 아래쪽 여백. <br/>            위치가 Position 속성에서 명시적으로 지정된 경우 이 값은 무시됩니다. |
| artifact_horizontal_alignment | 아티팩트의 수평 정렬. <br/>            위치가 Position 속성에서 명시적으로 지정된 경우 이 값은 무시됩니다. |
| artifact_vertical_alignment | 아티팩트의 수직 정렬. <br/>            위치가 Position 속성에서 명시적으로 지정된 경우 이 값은 무시됩니다. |
| rotation | 아티팩트 회전 각도를 가져오거나 설정합니다. |
| text | 아티팩트의 텍스트를 가져옵니다. |
| image | 아티팩트의 이미지를 가져옵니다 (이미지가 있는 경우). |
| opacity | 아티팩트의 불투명도를 가져오거나 설정합니다. 가능한 값은 0..1 범위입니다. |
| lines | 다중 행 텍스트 아티팩트의 라인들. |
| text_state | 아티팩트 텍스트에 대한 텍스트 상태. |
| is_background | true인 경우 아티팩트가 페이지 내용 뒤에 배치됩니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| set_image(image_stream) | 아티팩트의 이미지를 설정합니다. |
| set_image(image_name) | 아티팩트의 이미지를 설정합니다. |
| set_text(formatted_text) | 아티팩트의 텍스트를 설정합니다. |
| set_text_and_state(text, text_state) | 아티팩트의 텍스트 및 텍스트 속성을 설정합니다. |
| set_lines_and_state(text, text_state) | 아티팩트의 텍스트 및 텍스트 속성을 설정합니다. 여러 줄을 지정할 수 있습니다. |
| set_pdf_page(page) | 아티팩트로서 문서 페이지에 배치되는 PDF 페이지를 설정합니다. |
| get_value(name) | 아티팩트의 사용자 정의 값을 가져옵니다. |
| set_value(name, value) | 아티팩트의 사용자 정의 값을 설정합니다. |
| remove_value(name) | 아티팩트에서 사용자 정의 값을 제거합니다. |
| begin_updates() | 지연된 업데이트를 시작합니다. 동일한 아티팩트에 여러 변경을 수행하여 성능을 향상시켜야 할 경우 이 기능을 사용하십시오.<br/>            일반적으로 아티팩트 속성이 변경될 때마다 아티팩트 연산자가 변경됩니다. 이는 아티팩트가 변경될 때마다 페이지 내용이 바뀌는 원인이 됩니다.<br/>            이 영향을 피하려면 모든 아티팩트 업데이트를 StartUpdates/SaveUpdates 호출 사이에 배치하십시오.<br/>            이렇게 하면 페이지 내용을 한 번만 변경할 수 있습니다. |
| save_updates() | BeginUpdates() 호출 이후에 수행된 모든 아티팩트 업데이트를 저장합니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

