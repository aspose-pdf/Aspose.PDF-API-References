---
title: "Font"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "글꼴 객체를 나타냅니다."
type: docs
weight: 100
url: /ko/python-net/aspose.pdf.text/font/
---

## Font class

글꼴 객체를 나타냅니다.

Font 유형은 다음 멤버를 노출합니다:
## 속성
| 이름 | 설명 |
| :- | :- |
| font_name | [Font](/pdf/python-net/aspose.pdf.text/font/) 객체의 글꼴 이름을 가져옵니다. |
| decoded_font_name | 때때로 PDF 글꼴(주로 중국어/일본어/한국어 글꼴)은 특정한 글꼴 이름을 가질 수 있습니다.<br/>            이 이름은 PDF 글꼴 속성 \"BaseFont\"의 값이며, 경우에 따라 이 속성이<br/>            16진수 형태로 표현될 수 있습니다. 이 이름을 직접 읽으면 읽을 수 없는 형태로 표시될 수 있습니다. 읽을 수 있는 형태로 변환하려면 해당 글꼴에 특화된 규칙에 따라 글꼴 이름을 디코딩해야 합니다.<br/>            이 속성은 디코딩된 글꼴 이름을 반환하므로, 읽을 수 없는 [font_name](/pdf/python-net/aspose.pdf.text/font/)을(를) 만났을 때 사용하십시오.<br/>            만약 [font_name](/pdf/python-net/aspose.pdf.text/font/) 속성이 읽을 수 있는 형태라면 이 속성은 <br/>            [font_name](/pdf/python-net/aspose.pdf.text/font/)과 동일하므로, 읽을 수 있는 형태의 글꼴 이름이 필요할 때 언제든지 이 속성을 사용할 수 있습니다. |
| base_font | PDF 글꼴 객체의 BaseFont 값을 가져옵니다. 글꼴의 PostScript 이름으로도 알려져 있습니다. |
| is_embedded | 글꼴이 포함되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다.<br/>            IFont 기반 글꼴은 자동으로 서브셋되고 포함됩니다 |
| is_subset | 글꼴이 서브셋인지 여부를 나타내는 값을 가져오거나 설정합니다.<br/>             IFont 기반 글꼴은 자동으로 서브셋되고 포함됩니다 |
| is_accessible | 시스템에 폰트가 존재(설치)되어 있는지 여부를 가져옵니다. |
| font_options | 글꼴 동작을 조정하기 위한 유용한 속성들 |
## 메서드
| 이름 | 설명 |
| :- | :- |
| get_last_font_embedding_error() | 이 메서드의 목적은 폰트를 삽입하려는 시도가 실패했을 경우 오류 설명을 반환하는 것입니다.<br/>            오류가 없으면 빈 문자열을 반환합니다. |
| save(stream) | 폰트를 스트림에 저장합니다.<br/>            이 폰트는 원본 문서의 변환된 사본에서만 사용하도록 의도된 중간 TTF 형식으로 저장된다는 점에 유의하십시오.<br/>            폰트 파일은 원본 문서 컨텍스트 외부에서 사용하도록 설계되지 않았습니다. |
| measure_string(str, font_size) | 문자열의 길이를 측정합니다. |

### 또 보기

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

