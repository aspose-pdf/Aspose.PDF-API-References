---
title: "TextSearchOptions"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "텍스트 검색 옵션을 나타냅니다"
type: docs
weight: 460
url: /ko/python-net/aspose.pdf.text/textsearchoptions/
---

## TextSearchOptions class

텍스트 검색 옵션을 나타냅니다

TextSearchOptions 형식은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| TextSearchOptions(is_regular_expression_used) | TextSearchOptions 클래스의 새 인스턴스를 초기화합니다 |
| TextSearchOptions(rectangle) | TextSearchOptions 클래스의 새 인스턴스를 초기화합니다 |
| TextSearchOptions(rectangle, is_regular_expression_used) | TextSearchOptions 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| is_regular_expression_used | 정규식이 사용되는지 여부를 가져오거나 설정합니다. |
| limit_to_page_bounds | 텍스트가 페이지 경계 내에서 검색되는지 여부를 가져오거나 설정합니다. |
| rectangle | 검색된 텍스트를 둘러싼 사각형을 가져오거나 설정합니다. |
| use_font_engine_encoding | 텍스트를 글꼴 엔진 인코딩을 사용하여 검색할지 여부를 가져오거나 설정합니다.<br/>            true - 글꼴 엔진 인코딩이 사용됨을 의미합니다 (문서의 인코딩이 불완전하여 텍스트 검색이 실패할 경우 시도해 보세요)<br/>            false - 문서 글꼴 인코딩이 사용됨을 의미합니다 (기본값) |
| ignore_shadow_text | 검색 중에 일반 텍스트의 그림자에 해당하는 텍스트 조각을 무시할지 여부를 가져오거나 설정합니다.<br/>            true - 그림자 텍스트가 검색되지 않음을 의미합니다 (텍스트 검색이 근접 위치에서 중복 조각을 반환할 경우 시도해 보세요)<br/>            false - 그림자 텍스트가 일반 텍스트와 함께 검색됨을 의미합니다 (기본값) |
| log_text_extraction_errors | 텍스트 추출(디코딩) 오류가 텍스트(조각) 흡수기에서 기록될지 여부를 가져오거나 설정합니다.<br/>            true - 텍스트 추출(디코딩) 오류가 기록됨을 의미합니다. 성능이 저하될 수 있습니다.<br/>            false (default) - 오류가 기록되지 않음. |
| ignore_resource_font_errors | 텍스트(조각) 흡수기가 글꼴이 없을 때 발생하는 오류를 무시할지 여부를 가져오거나 설정합니다.<br/>            true - 글꼴이 없을 때 발생하는 오류가 무시됨을 의미합니다. 잘못된 리소스를 참조하는 텍스트 세그먼트는 처리 중에 건너뛰게 됩니다.<br/>            false (default) - 글꼴 부재 오류가 발생하면 예외를 발생시켜 처리를 중단합니다. |
| search_for_text_related_graphics | 텍스트 검색 중에 텍스트 관련 그래픽(밑줄, 배경 등)을 검색하도록 허용하는 값을 가져오거나 설정합니다.<br/>            true - 텍스트 관련 그래픽 검색이 수행됩니다 (기본값).<br/>            false - 원본 문서에 존재할 수 있는 그래픽 요소를 무시합니다. 성능 문제가 있거나 밑줄, 배경, 클리핑을 처리할 필요가 없을 경우 설정하십시오. |
| stored_graphic_elements_max_count | 페이지에서 텍스트 관련 그래픽(밑줄, 배경 등)의 검색을 지정된 요소 수로 제한하는 값을 가져오거나 설정합니다.<br/>            기본값은 250입니다. 성능 문제가 있을 경우 더 작은 값을 설정하고, 일부 그래픽 요소가 검색되지 않을 경우 더 큰 값을 시도하십시오. |
| search_in_annotations | 주석(Annotations)에서 텍스트를 검색하도록 허용하는 값을 가져오거나 설정합니다.<br/>            true - 주석에서 텍스트를 검색합니다.<br/>            false - 주석의 텍스트는 TextFragmentAbsorber에 의해 파싱되지 않습니다. |

### 또 보기

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

