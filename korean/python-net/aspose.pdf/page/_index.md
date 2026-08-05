---
title: "Page"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "클래스는 PDF 문서의 페이지를 나타냅니다."
type: docs
weight: 1080
url: /ko/python-net/aspose.pdf/page/
---

## Page class

클래스는 PDF 문서의 페이지를 나타냅니다.

Page 형식은 다음 멤버를 노출합니다:
## 속성
| 이름 | 설명 |
| :- | :- |
| is_add_paragraphs_after_last | 페이지의 마지막 단락 뒤에 단락을 추가할지 여부를 가져오거나 설정합니다 |
| background_image | 페이지의 배경 이미지를 가져오거나 설정합니다(생성기 전용이며, 문서를 읽을 때는 채워지지 않습니다). |
| toc_info | 목차 정보를 가져오거나 설정합니다. |
| 헤더 | 페이지 헤더를 가져오거나 설정합니다. |
| 레이어 | 레이어 컬렉션을 가져오거나 설정합니다. |
| 푸터 | 페이지 푸터를 가져오거나 설정합니다. |
| paragraphs | 단락을 가져옵니다. |
| page_info | 페이지 정보를 가져오거나 설정합니다(생성기 전용이며, 문서를 읽을 때는 채워지지 않음). |
| 사각형 | 페이지 사각형을 가져오거나 설정합니다.<br/>            가져올 때: 지정된 경우 페이지 크롭 박스를 반환하고, 그렇지 않으면 페이지 미디어 박스를 반환합니다.<br/>            설정할 때: 페이지 미디어 박스를 항상 설정합니다.<br/>            이 속성은 페이지 회전을 고려하지 않음을 유의하십시오. 회전을 고려한 페이지 사각형을 얻으려면 ActualRect를 사용하십시오. |
| color_type | 페이지의 색 유형을 SetColor 연산자,<br/>            이미지 및 양식에서 가져온 정보를 기반으로 설정합니다. |
| note_line_style | 노트의 선 스타일을 가져오거나 설정합니다(생성기 전용이며, 문서를 읽을 때는 채워지지 않음). |
| tab_order | 페이지의 탭 순서를 가져오거나 설정합니다. <br/>            가능한 값: Row, Column. 기본값, Manual |
| duration | 페이지 표시 지속 시간을 가져오거나 설정합니다. 이는 프레젠테이션 중 페이지가 표시되는 시간(초)입니다.<br/>            지속 시간이 정의되지 않은 경우 -1을 반환합니다. |
| contents | 페이지의 콘텐츠 스트림에 있는 연산자 컬렉션을 가져옵니다.<br/>            [OperatorCollection](/pdf/python-net/aspose.pdf/operatorcollection/) |
| group | 투명 이미지 모델에서 사용하기 위해 페이지의 페이지 그룹 속성을 지정하는 그룹 속성 클래스를 가져오거나 설정합니다. |
| annotations | 페이지 주석 컬렉션을 가져옵니다.<br/>            [annotations](/pdf/python-net/aspose.pdf/page/) |
| resources | 페이지 리소스를 가져옵니다. Resources 객체는 이미지, 양식 및 글꼴 컬렉션을 포함합니다.<br/>            [resources](/pdf/python-net/aspose.pdf/page/) |
| rotate | 페이지 회전을 가져오거나 설정합니다. |
| trim_box | 페이지 트림 박스를 가져오거나 설정합니다. |
| art_box | 페이지의 art box를 가져오거나 설정합니다. |
| bleed_box | 페이지의 bleed box를 가져오거나 설정합니다. |
| crop_box | 페이지의 crop box를 가져오거나 설정합니다. |
| media_box | 페이지의 media box를 가져오거나 설정합니다. |
| 숫자 | 페이지 번호를 가져옵니다. |
| rotation_matrix | 페이지의 변환 행렬을 가져옵니다. |
| background | 페이지의 배경 색상을 가져오거나 설정합니다. |
| watermark | 페이지의 워터마크를 가져오거나 설정합니다. |
| artifacts | 페이지에 있는 아티팩트 컬렉션을 가져옵니다. |
| actions | 페이지 속성 컬렉션을 가져옵니다. |
| fields_in_tab_order | 이 페이지에서 탭 순서대로 정렬된 Field 객체 목록을 가져옵니다. |
| user_unit | UserUnit 값을 가져오거나 설정합니다. 기본 사용자 공간 단위의 크기를 나타내는 양수이며, 1 ⁄ 72 인치의 배수입니다.<br/>            기본값은 1입니다. 페이지에서 이 항목을 지우려면 0 또는 음수 값을 설정하십시오. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| send_to(device, output) | 주어진 페이지 장치를 사용하여 페이지를 처리기로 보냅니다. |
| send_to(device, output_file_name) | 주어진 페이지 장치를 사용하여 페이지를 처리기로 보냅니다. |
| accept(visitor) | 주석 작업 기능을 제공하는 방문자 객체인 [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/)를 허용합니다. |
| accept(visitor) | 텍스트 객체 작업 기능을 제공하는 방문자 객체인 [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/)를 허용합니다. |
| accept(visitor) | 이미지 배치 객체 작업 기능을 제공하는 방문자 객체인 [ImagePlacementAbsorber](/pdf/python-net/aspose.pdf/imageplacementabsorber/)를 허용합니다. |
| accept(visitor) | 텍스트 객체 작업 기능을 제공하는 방문자 객체인 [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/)를 허용합니다. |
| add_image(image_stream, image_rect) | 이미지를 페이지에 추가하고 지정된 사각형의 중앙에 배치하여 이미지 비율을 유지합니다. |
| add_image(hocr, image_stream, image_rect) | 검색 가능한 이미지를 페이지에 추가하고 지정된 사각형의 중앙에 배치하여 이미지 비율을 유지합니다. |
| add_image(image_stream, image_rect, image_width, image_height, save_image_proportions) | 페이지에 이미지를 추가하고 이미지 사각형 위치에 따라 배치합니다. |
| add_image(image_path, rectangle) | 검색 가능한 이미지를 페이지에 추가하고 지정된 사각형의 중앙에 배치하여 이미지 비율을 유지합니다. |
| is_blank(fill_threshold_factor) | 페이지가 비어 있는지 여부를 나타내는 플래그를 가져옵니다. |
| get_page_rect(consider_rotation) | CropBox(또는 CropBox가 null인 경우 MediaBox)를 기준으로 페이지의 사각형을 반환합니다. |
| calculate_content_b_box() | 보이는 여백 없이 콘텐츠를 포함하는 사각형인 bbox 값을 계산합니다. |
| rotation_to_int(rotation) | 회전 열거형 멤버를 정수 값으로 변환합니다. |
| int_to_rotation(rotation) | 정수 값을 해당 회전 열거형 멤버로 변환합니다. |
| add_stamp(stamp) | 페이지에 스탬프를 삽입합니다. 스탬프는 페이지 번호, 이미지 또는 간단한 텍스트(예: 로고)일 수 있습니다. |
| flatten() | 페이지에 위치한 모든 필드를 제거하고 대신 해당 값을 배치합니다. |
| set_page_size(width, height) | 페이지의 크기를 설정합니다. |
| make_grayscale() | 페이지를 그레이스케일로 변환합니다. |
| free_memory() | 캐시된 데이터를 지웁니다 |
| get_notifications() | 페이지 콘텐츠와 관련된 내부 작업에 대한 알림을 반환합니다. (현재 텍스트 추가 시나리오에서 단락 이벤트에 대한 알림만 지원됩니다.) |
| as_byte_array(resolution) | 현재 페이지를 비트맵으로 변환한 다음 바이트 배열을 반환합니다. |
| as_xml() | 현재 페이지를 UTF-8 인코딩의 XML로 변환합니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

