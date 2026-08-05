---
title: "ParagraphAbsorber"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "섹션 및 단락과 같은 페이지 구조 객체의 흡수 객체를 나타냅니다.<br/>            텍스트 섹션 및 단락을 검색하고 텍스트 좌표 공간에서 이를 설명하는 사각형 및 폴리곤에 대한 접근을 제공합니다. <br/>            또한 텍스트 세그먼트 검색을 수행하고 구조 요소별로 그룹화된 TextFragments 컬렉션을 통해 검색 결과에 접근할 수 있습니다."
type: docs
weight: 240
url: /ko/python-net/aspose.pdf.text/paragraphabsorber/
---

## ParagraphAbsorber class

섹션 및 단락과 같은 페이지 구조 객체의 흡수 객체를 나타냅니다.<br/>            텍스트 섹션 및 단락을 검색하고 텍스트 좌표 공간에서 이를 설명하는 사각형 및 폴리곤에 대한 접근을 제공합니다. <br/>            또한 텍스트 세그먼트 검색을 수행하고 구조 요소별로 그룹화된 TextFragments 컬렉션을 통해 검색 결과에 접근할 수 있습니다.

ParagraphAbsorber 형식은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| ParagraphAbsorber() | 문서 또는 페이지의 섹션/단락을 검색하는 [ParagraphAbsorber](/pdf/python-net/aspose.pdf.text/paragraphabsorber/)의 새 인스턴스를 초기화합니다. |
| ParagraphAbsorber(sections_search_depth) | ParagraphAbsorber 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| page_markups | 흡수된 [PageMarkup](/pdf/python-net/aspose.pdf.text/pagemarkup/) 컬렉션을 가져옵니다 |
| sections_search_depth | 구조의 더 세부적인 요소에 대해 순차 검색을 수행할 횟수를 지정하는 값을 가져오거나 설정합니다.<br/>            기본 검색 깊이는 3입니다.<br/>            이는 수평으로 구분된 섹션(헤더, 단락 등)에 대해 세 번 검색하고, 수직으로 구분된 섹션(열)에 대해서도 세 번 검색한다는 의미입니다. |
| is_multicolumn_paragraphs_allowed | 다음 섹션의 시작 텍스트 줄이 이전 섹션의 마지막 단락의 연속으로 처리될 수 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| visit(doc) | 지정된 [Document](/pdf/python-net/aspose.pdf/document/)에서 섹션 및 단락을 검색합니다. |
| visit(page) | 지정된 [Page](/pdf/python-net/aspose.pdf/page/)에서 검색을 수행합니다. |

### 또 보기

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

