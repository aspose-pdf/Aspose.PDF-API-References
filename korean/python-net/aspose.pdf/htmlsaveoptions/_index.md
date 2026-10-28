---
title: "HtmlSaveOptions"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "HTML 형식으로 내보내기 위한 저장 옵션"
type: docs
weight: 490
url: /ko/python-net/aspose.pdf/htmlsaveoptions/
---

## HtmlSaveOptions class

HTML 형식으로 내보내기 위한 저장 옵션

HtmlSaveOptions 형식은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| HtmlSaveOptions() | [HtmlSaveOptions](/pdf/python-net/aspose.pdf/htmlsaveoptions/) 클래스의 새 인스턴스를 초기화합니다. |
| HtmlSaveOptions(document_type) | HtmlSaveOptions 클래스의 새 인스턴스를 초기화합니다. |
| HtmlSaveOptions(fixed_layout) | HtmlSaveOptions 클래스의 새 인스턴스를 초기화합니다. |
| HtmlSaveOptions(document_type, fixed_layout) | HtmlSaveOptions 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| warning_handler | 생성된 경고를 처리하기 위한 콜백입니다. <br/>            WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. <br/>            Continue는 기본 동작이며 저장 작업이 계속되지만, 사용자가 Abort를 반환하면 저장 작업이 중단되어야 합니다. |
| save_format | 데이터 저장 형식. |
| close_response | 문서가 응답에 저장된 후 Response 객체가 닫힐지를 나타내는 부울 값을 가져오거나 설정합니다. |
| extract_ocr_sublayer_only | 없음 |
| try_merge_adjacent_same_background_images | 없음 |
| document_type | 가져오거나 설정합니다 [HtmlDocumentType](/pdf/python-net/aspose.pdf/htmldocumenttype/). |
| compress_svg_graphics_if_any | 가져오거나 설정합니다 플래그는 <br/>            찾은 SVG 그래픽(있는 경우)이 저장 중에 SVGZ 형식으로 압축(압축)되는지를 나타냅니다 <br/>            저장 시. |
| split_css_into_pages | 멀티페이지 모드가 선택된 경우(예: 'SplitIntoPages'가 'true'인 경우), <br/>            이 속성은 각 결과 HTML 페이지마다 별도의 CSS 파일을 생성할지 여부를 정의합니다.<br/>            기본값은 false이며, 따라서 모든 생성된 페이지에 대해 하나의 큰 공통 CSS가 생성됩니다.<br/>            이 모드에서 생성된 모든 CSS(페이지당 하나의 CSS)의 총 크기는 일반적으로 하나의 큰 CSS 파일 크기보다 훨씬 큽니다, 왜냐하면 이전 경우에는 각 페이지에 대해 여러 CSS 파일에 동일한 CSS 클래스가 중복되기 때문입니다.<br/>            따라서 이 설정은 각 HTML 페이지를 독립적으로 처리하려는 경우에만 사용하는 것이 좋으며, 따라서 각 페이지별 CSS 크기가 가장 중요한 문제가 됩니다. |
| split_into_pages | 가져오거나 설정합니다 플래그는 소스 <br/>            문서의 각 페이지가 자체 대상 HTML 문서로 변환되는지 여부를 나타냅니다, <br/>            즉 결과 HTML이 여러 HTML 페이지로 분할되는지를 나타냅니다. |
| explicit_list_of_saved_pages | 이 속성을 사용하면 문서의 어떤 페이지를 변환할지 명시적으로 정의할 수 있습니다.<br/>            이 목록의 페이지는 1부터 시작하는 번호여야 합니다. 즉, <br/>            페이지 번호는 (1...[NumberOfPagesInConvertedDocument]) 범위에서 가져와야 합니다.<br/>            이 목록에 페이지가 나타나는 순서는 결과 HTML 페이지의 순서에 영향을 주지 않으며, 결과 페이지는 항상 소스 PDF에 존재하는 순서대로 표시됩니다.<br/>            이 목록이 null인 경우(기본값), 모든 페이지가 변환됩니다.<br/>            이 목록의 페이지 번호가 현재 페이지 범위(1-[amountOfPagesInDocument])를 벗어나면 예외가 발생합니다. |
| fixed_layout | 가져오거나 설정합니다 값은 해당 HTML이 고정 레이아웃으로 생성되는지 여부를 나타냅니다. |
| image_resolution | 가져오거나 설정합니다 이미지 렌더링 해상도. |
| default_font_name | 설치된 폰트 중 시스템에 포함되지 않고 설치되지 않은 문서 폰트를 대체하는 데 사용되는 폰트 이름을 지정합니다.<br/>            포함되지 않거나 시스템에 설치되지 않은 모든 문서 폰트를 대체합니다.<br/>            null인 경우 기본 대체 폰트가 사용됩니다. |
| batch_size | 배치 변환이 소스 및 대상 형식 쌍에 적용되는 경우 배치 크기를 정의합니다.<br/>             |
| font_sources | 미리 저장된 폰트의 폰트 소스. |
| additional_margin_width_in_points | 'SplitOnPages=false' 속성이 설정되면, 모든 입력 PDF 페이지를 나타내는 전체 HTML이 서로 다른 HTML 페이지로 분할되지 않고 하나의 큰 결과 HTML 파일에 포함됩니다.<br/>            그러나 각 소스 PDF 페이지는 HTML에서 자체 <br/>            사각형 영역으로 표시됩니다(필요한 경우 해당 영역에 'PageBorderIfAny' 특수 속성을 사용하여 페이지 가장자리 표시를 위한 테두리를 추가할 수 있습니다).<br/>            이 매개변수는 소스 PDF 문서의 페이지를 나타내는 출력 HTML 영역 주변에 강제로 남겨야 하는 여백 너비를 정의합니다. 본질적으로 이 모드의 변환에서 PDF \"용지\" 페이지들의 HTML 표현 사이에 보장된 간격을 정의합니다. |
| use_z_order | UseZOrder 속성이 true로 설정되면, 그래픽과 텍스트가 원본 PDF 문서의 Z-순서에 따라 결과 HTML 문서에 추가됩니다.<br/>            이 속성이 false인 경우 모든 그래픽이 단일 레이어로 배치되어 겹치는 객체에 불필요한 효과가 발생할 수 있습니다. |
| convert_marked_content_to_layers | ConvertMarkedContentToLayers 속성이 true로 설정하면 PDF 마크된 콘텐츠(레이어) 내부의 모든 요소가 레이어 이름을 지정하는 \"data-pdflayer\" 속성을 가진 HTML div에 배치됩니다.<br/>            이 레이어 이름은 PDF 마크된 콘텐츠의 선택적 속성에서 추출됩니다.<br/>            이 속성이 false인 경우(기본값) PDF 마크된 콘텐츠에서 레이어가 생성되지 않습니다. |
| minimal_line_width | 이 속성은 그래픽 경로 선의 최소 너비를 설정합니다.<br/>            선의 두께가 1px보다 작으면 Adobe Acrobat이 이 값으로 반올림합니다. 따라서 이 속성을 사용하여 HTML 브라우저에서 이 동작을 에뮬레이트할 수 있습니다. |
| prevent_glyphs_grouping | 이 속성은 텍스트 글리프가 단어와 문자열로 그룹화되지 않는 모드를 켭니다.<br/>            이 모드는 페이지에서 글리프 위치를 지정할 때 최대 정밀도를 유지하도록 하며, 악보 기호나 서로 별도로 배치되어야 하는 글리프가 포함된 문서 변환에 사용할 수 있습니다.<br/>            이 매개변수는 FixedLayout 속성 값이 true인 경우에만 문서에 적용됩니다. |
| simple_textbox_mode_grouping | 이 속성은 글리프와 단어를 문자열로 순차적으로 그룹화하도록 지정합니다.<br/>            예를 들어 변환된 HTML에서 태그와 단어의 순서가 다르고 이를 일치시키고 싶을 때 사용합니다.<br/>            이 매개변수는 FixedLayout 속성 값이 true인 경우에만 문서에 적용됩니다. |
| flow_layout_paragraph_full_width | 이 속성은 Flow 모드에서 전체 너비 단락 텍스트를 지정합니다. FixedLayout = false |
| render_text_as_image | RenderTextAsImage 속성이 true로 설정되면 소스 텍스트가 HTML에서 이미지로 변환됩니다.<br/>            텍스트를 선택할 수 없게 만들 때 유용할 수 있습니다.<br/>            또는 HTML 텍스트가 올바르게 렌더링되지 않을 때도 활용됩니다. |
| save_full_font | 전체 글꼴이 저장됨을 나타내며, True Type 글꼴만 지원합니다.<br/>            기본값은 SaveFullFont = false이며, 변환기는 문서 텍스트 표시를 위해 필요한 초기 글꼴의 부분 집합만 저장합니다. |
| antialiasing_processing | 이 매개변수는 PDF에서 HTML로 복합 배경 이미지 변환 시 필요한 안티앨리어싱 조치를 정의합니다. |
| save_transparent_texts | PDF에는 투명 텍스트가 포함될 수 있으며, 이는 클립보드에 선택할 수 있습니다(보통 문서에 이미지와 그에서 추출된 OCR 텍스트가 포함된 경우 발생합니다).<br/>            이 설정은 변환기에 이러한 텍스트를 결과 HTML에서 투명하고 선택 가능한 텍스트로 저장할지 여부를 알려줍니다. |
| save_shadowed_texts_as_transparent_texts | PDF에는 다른 요소(예: 이미지)에 의해 그림자 처리된 텍스트가 포함될 수 있지만 <br/>            Acrobat Reader에서는 클립보드에 선택할 수 있습니다(보통 문서에 이미지와 그에서 추출된 OCR 텍스트가 포함된 경우 발생합니다).<br/>            이 설정은 변환기에 이러한 텍스트를 결과 HTML에서 투명하고 선택 가능한 텍스트로 저장하여 Acrobat Reader의 동작을 모방할지 여부를 알려줍니다(그렇지 않으면 이러한 텍스트는 일반적으로 숨김 처리되어 클립보드 복사가 불가능합니다). |
| font_saving_mode | PDF를 원하는 형식으로 저장할 때 사용할 글꼴 저장 모드를 정의합니다. |
| page_border_if_any | 이 속성은 (있는 경우) 결과 HTML 문서에서 원본 PDF 페이지를 나타내는 영역 주변에 테두리를 그리는 데 사용되는 설정 집합을 나타냅니다.<br/>            본질적으로 PDF 페이지 자체에 참조된 페이지 테두리가 아니라 페이지의 종이 가장자리를 표시하는 것과 관련됩니다. |
| page_margin_if_any | 이 속성은 (있는 경우) 결과 HTML 문서에서 원본 PDF 페이지를 나타내는 영역 주변에 추가 페이지 여백을 설정하는 집합을 나타냅니다. |
| letters_positioning_method | 결과 HTML에서 단어 내 문자 위치 지정 모드를 설정합니다. |
| exclude_font_name_list | HTML에 포함되지 않을 PDF 내장 폰트 이름 목록. |
| special_folder_for_svg_images | 문서를 HTML로 저장하는 동안 SVG 이미지가 발견될 경우 해당 SVG 이미지만 저장해야 하는 디렉터리 경로를 가져오거나 설정합니다. <br/>            매개변수가 비어 있거나 null인 경우 SVG 파일(있는 경우)이 다른 이미지 파일과 함께(출력 파일 근처에) 저장되거나 이미지용 특수 폴더에 저장됩니다(특수 이미지 폴더 옵션에 지정된 경우).<br/>            이 설정은 CustomImageSavingStrategy 속성이 성공적으로 사용되어 관련 이미지 파일을 처리한 경우에는 영향을 주지 않습니다. |
| special_folder_for_all_images | 문서를 HTML로 저장하는 동안 이미지가 발견될 경우 모든 이미지를 저장해야 하는 디렉터리 경로를 가져오거나 설정합니다. <br/>            매개변수가 비어 있거나 null인 경우 이미지 파일(있는 경우)이 HTML에 연결된 다른 파일과 함께 저장됩니다. <br/>            이 설정은 CustomImageSavingStrategy 속성이 성공적으로 사용되어 관련 이미지 파일을 처리한 경우에는 영향을 주지 않습니다. |
| css_class_names_prefix | PDFtoHTML 변환기가 결과 CSS를 생성할 때, CSS 클래스 이름<br/>            (예: \".stl_01 {}\" ... \".stl_NN {}\")이 생성되어 결과 CSS에서 사용됩니다. 이 속성을 사용하면 클래스 이름 접두사를 강제로 설정할 수 있습니다.<br/>            예를 들어 모든 클래스 이름이 'my_prefix_'로 시작하도록 하려면(예: 'my_prefix_1' ... 'my_prefix_NNN'), 변환 전에 이 속성에 'my_prefix_'를 할당하면 됩니다.<br/>            이 속성을 그대로 두면(즉, null 값을 유지하면) 변환기가 자체적으로 클래스 이름을 생성합니다<br/>            (예: \".stl_01 {}\" ... \".stl_NN {}\"). |
| parts_embedding_mode | 참조된 파일(HTML, 폰트, 이미지, CSS)이 메인 HTML 파일에 포함될지 별도의 바이너리 엔터티로 생성될지를 정의합니다.<br/>            메인 HTML 파일에 포함되거나 별도의 바이너리 엔터티로 생성됩니다. |
| html_markup_generation_mode | 때때로 HTML 마크업 생성에 대한 특정 요구 사항이 존재합니다.<br/>            이 매개변수는 PDF를 HTML로 변환할 때 이러한 특정 요구 사항에 맞추기 위해 사용할 수 있는 HTML 준비 모드를 정의합니다. |
| raster_images_saving_mode | 변환된 PDF에는 래스터 이미지가 포함될 수 있습니다.<br/>            이 매개변수는 PDF를 HTML로 변환하는 동안 이러한 이미지들을 어떻게 처리할지를 정의합니다. |
| remove_empty_areas_on_top_and_bottom | 생성된 HTML에서 내용이 없는 상단 및 하단의 빈 영역을 제거할지 여부를 정의합니다(있는 경우). |
| font_encoding_strategy | 현재 문서에 대한 PDF 디코딩을 조정하기 위한 인코딩 특수 규칙을 정의합니다. |
| pages_flow_type_depends_on_viewers_screen_size | 속성 'SplitOnPages=false'인 경우, 모든 입력 PDF 페이지를 나타내는 전체 HTML이 <br/>            하나의 큰 결과 HTML 파일에 포함됩니다. <br/>            이 플래그는 결과 HTML이 PDF 페이지를 나타내는 영역의 흐름이 뷰어의 화면 해상도에 따라 달라지도록 생성될지 여부를 정의합니다. <br/>            뷰어 측 화면 너비가 가로 방향에 2페이지 이상을 나란히 배치할 만큼 충분히 넓다고 가정합니다. 이 플래그가 true로 설정되면 이러한 기회가 활용되어 가능한 한 많은 페이지가 가로 방향으로 나란히 표시되고, 다음 가로 그룹의 페이지는 첫 번째 그룹 아래에 표시됩니다.<br/>            그렇지 않으면 페이지가 다음과 같이 흐릅니다: 다음 페이지는 항상 이전 페이지 아래에 배치됩니다. |
| try_save_text_underlining_and_strikeouting_in_css | PDF 자체에는 텍스트에 대한 밑줄 표시가 포함되어 있지 않습니다. 텍스트 아래에 선을 배치하여 에뮬레이션합니다.<br/>            이 옵션은 변환기가 해당 선이 텍스트의 밑줄인지 추측하도록 허용하고, 그래픽으로 밑줄을 그리는 대신 해당 정보를 CSS에 넣습니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

