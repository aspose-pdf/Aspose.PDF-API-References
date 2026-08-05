---
title: "StructureTypeStandard"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "표준 구조 유형을 나타냅니다."
type: docs
weight: 560
url: /ko/python-net/aspose.pdf.logicalstructure/structuretypestandard/
---

## StructureTypeStandard class

표준 구조 유형을 나타냅니다.

StructureTypeStandard 형식은 다음 멤버를 노출합니다:
## 속성
| 이름 | 설명 |
| :- | :- |
| tag | 태그 이름을 가져옵니다 [StructureElement](/pdf/python-net/aspose.pdf.logicalstructure/structureelement/). |
| 카테고리 | Standard Structure Type의 카테고리를 가져옵니다. |
| DOCUMENT | (Document) 전체 문서입니다. 이는 여러 파트 또는 여러 기사를 포함하는 구조 트리의 루트 요소입니다. |
| PART | (Part) 문서의 대규모 구분입니다. 이 요소 유형은 기사나 섹션을 그룹화하는 데 적합합니다. |
| ART | (Article) 단일 서사 또는 설명을 구성하는 비교적 독립적인 텍스트 본문입니다. 기사들은 서로 겹치지 않아야 하며, 다른 기사를 구성 요소로 포함해서는 안 됩니다. |
| SECT | (Section) 관련 콘텐츠 요소를 그룹화하기 위한 컨테이너입니다. |
| DIV | (Division) 일반적인 블록 수준 요소 또는 요소 그룹입니다. |
| BLOCK_QUOTE | (Block quotation) 하나 이상의 단락으로 구성된 텍스트 부분으로, 주변 텍스트의 저자와는 다른 사람에게 귀속됩니다. |
| CAPTION | (Caption) 표 또는 그림을 설명하는 간략한 텍스트 부분. |
| TOC | (Table of contents) 목차 항목 엔트리(구조 유형 TOCI) 및/또는 다른 중첩 목차 엔트리(TOC)로 구성된 목록. |
| TOCI | (Table of contents item) 목차의 개별 항목입니다. 이 엔트리의 하위 항목은 다음 구조 유형 중 하나일 수 있습니다: |
| INDEX | (Index) 식별 텍스트와 해당 텍스트가 문서 본문에 나타나는 위치를 가리키는 참조 요소를 포함하는 일련의 엔트리. |
| NON_STRUCT | (Nonstructural element) 고유한 구조적 의미가 없는 그룹화 요소이며, 오직 그룹화 목적에만 사용됩니다. 이 요소 유형은 구분(Div)과 달리 다른 문서 형식으로 해석되거나 내보내지 않으며, 자손은 정상적으로 처리됩니다. |
| PRIVATE | (Private element) 이를 생성한 애플리케이션에 속하는 비공개 콘텐츠를 포함하는 그룹화 요소입니다. 이 요소의 구조적 의미는 지정되지 않았으며, 완전히 호환 작성자에 의해 결정됩니다. Private element와 그 자손은 다른 문서 형식으로 해석되거나 내보내지 않아야 합니다. |
| P | (Paragraph) 텍스트의 저수준 구분. |
| H | (Heading) 문서 내용의 하위 구분에 대한 레이블입니다. 해당 구분의 첫 번째 자식이어야 합니다. |
| H1 | Level 1 Heading, 섹션을 계층적으로 중첩할 수 없는 호환 작성자에서 사용되며, 따라서 중첩 수준으로부터 제목 수준을 결정할 수 없습니다. |
| H2 | Level 2 Heading, 섹션을 계층적으로 중첩할 수 없는 호환 작성자에서 사용되며, 따라서 중첩 수준으로부터 제목 수준을 결정할 수 없습니다. |
| H3 | Level 3 Heading, 섹션을 계층적으로 중첩할 수 없는 호환 작성자에서 사용되며, 따라서 중첩 수준으로부터 제목 수준을 결정할 수 없습니다. |
| H4 | 레벨 4 헤딩은 섹션을 계층적으로 중첩할 수 없어 헤딩 수준을 중첩 수준으로 판단할 수 없는 호환 작가들이 사용하도록 제공합니다. |
| H5 | 레벨 5 헤딩은 섹션을 계층적으로 중첩할 수 없어 헤딩 수준을 중첩 수준으로 판단할 수 없는 호환 작가들이 사용하도록 제공합니다. |
| H6 | 레벨 6 헤딩은 섹션을 계층적으로 중첩할 수 없어 헤딩 수준을 중첩 수준으로 판단할 수 없는 호환 작가들이 사용하도록 제공합니다. |
| L | (List) 의미와 중요도가 동일한 항목들의 순서입니다. 즉시 하위 요소는 선택적 캡션(structure type Caption) 뒤에 하나 이상의 리스트 항목(structure type LI)이 와야 합니다. |
| LI | (List item) 리스트의 개별 항목입니다. 하위 요소는 하나 이상의 레이블, 리스트 본문, 혹은 둘 다(structure types Lbl or LBody)일 수 있습니다. |
| LBL | (Label) 동일 리스트 또는 유사 항목 그룹 내에서 특정 항목을 다른 항목과 구별하는 이름이나 번호입니다. |
| L_BODY | (List body) 리스트 항목의 설명 내용입니다. 예를 들어 사전 리스트에서는 용어의 정의를 포함합니다. 내용 자체를 직접 포함하거나, 다른 BLSE를 포함할 수 있으며, 중첩 리스트를 자식으로 가질 수도 있습니다. |
| TABLE | (Table) 직사각형 데이터 셀의 2차원 레이아웃으로, 복잡한 하위 구조를 가질 수 있습니다. 자식으로 하나 이상의 테이블 행(structure type TR)을 포함하거나, 선택적 테이블 헤드(structure type THead) 뒤에 하나 이상의 테이블 본문 요소(structure type TBody)와 선택적 테이블 푸터(structure type TFoot)를 가질 수 있습니다. 또한 테이블은 첫 번째 또는 마지막 자식으로 캡션(structure type Caption)을 가질 수 있습니다. |
| T_HEAD | (Table header row group; PDF 1.5) 테이블 헤더를 구성하는 행 그룹입니다. 테이블이 여러 페이지에 걸쳐 분할될 경우, 이러한 행은 각 테이블 조각의 상단에 다시 그려질 수 있습니다(단 THead 요소는 하나만 존재합니다). |
| T_BODY | (Table body row group; PDF 1.5) 테이블의 본문 부분을 구성하는 행 그룹입니다. 테이블이 여러 페이지에 걸쳐 분할될 경우, 본문 영역은 행 경계에서 분리될 수 있습니다. 행 집합에 대한 테두리나 배경을 그리기 위해 테이블은 여러 개의 TBody 요소를 가질 수 있습니다. |
| T_FOOT | (Table footer row group; PDF 1.5) 테이블 푸터를 구성하는 행 그룹입니다. 테이블이 여러 페이지에 걸쳐 분할될 경우, 이러한 행은 각 테이블 조각의 하단에 다시 그려질 수 있습니다(단 TFoot 요소는 하나만 존재합니다). |
| TR | (Table row) 테이블의 헤더 또는 데이터 행입니다. 테이블 헤더 셀과 테이블 데이터 셀(structure types TH and TD)을 포함할 수 있습니다. |
| TH | (Table header cell) 테이블의 하나 이상의 행 또는 열을 설명하는 헤더 텍스트를 포함하는 셀입니다. |
| TD | (Table data cell) 테이블 내용의 일부인 데이터를 포함하는 셀입니다. |
| SPAN | (Span) 특정한 고유 특성이 없는 일반적인 인라인 텍스트 부분입니다. 예를 들어, 주어진 스타일 속성 집합으로 텍스트 범위를 구분하는 데 사용할 수 있습니다. |
| QUOTE | (Quotation) 주변 텍스트의 저자와 다른 사람에게 귀속된 인라인 텍스트 부분입니다. |
| 노트 | (Note) 문서 본문 내에서 참조되는 설명 텍스트 항목으로, 각주나 미주와 같은 형태입니다. 자식으로 레이블(structure type Lbl)을 가질 수 있습니다. 이 주석은 본문 텍스트에서 해당 구조 요소의 자식으로 포함될 수도 있고, 별도의 섹션(예: 미주 섹션)에 포함되어 레퍼런스(structure type Reference)를 통해 접근될 수도 있습니다. |
| REFERENCE | (Reference) 문서 내 다른 위치에 있는 콘텐츠에 대한 인용입니다. |
| BIB_ENTRY | (Bibliography entry) 인용된 콘텐츠의 외부 출처를 식별하는 레퍼런스입니다. 자식으로 레이블(structure type Lbl)을 포함할 수 있습니다. |
| CODE | (Code) 컴퓨터 프로그램 텍스트의 조각입니다. |
| LINK | (Link) ILSE 콘텐츠의 일부와 해당 링크 주석 또는 주석들 사이의 연관성입니다. 그 자식은 하나 이상의 콘텐츠 항목 또는 하위 ILSE와 하나 이상의 객체 레퍼런스로 구성되어 연관된 링크 주석을 식별합니다. |
| ANNOT | (Annotation; PDF 1.5) ILSE 콘텐츠의 일부와 해당 PDF 주석 사이의 연관성입니다. Annot는 링크 주석 및 위젯 주석을 제외한 모든 PDF 주석에 사용됩니다. |
| RUBY | (Ruby; PDF 1.5) 참조되는 기본 텍스트 옆에 작은 글자 크기로 작성된 부가 설명(주석)입니다. Ruby 요소는 RB, RT, RP 요소를 포함할 수도 있습니다. |
| RB | (Ruby base text) 루비 주석이 적용되는 전체 크기의 텍스트입니다. RB는 텍스트, 다른 인라인 요소 또는 그 혼합을 포함할 수 있습니다. RubyAlign 속성을 가질 수 있습니다. |
| RT | (Ruby annotation text) 루비 기본 텍스트 옆에 배치되는 작은 크기의 텍스트입니다. 텍스트, 다른 인라인 요소 또는 그 혼합을 포함할 수 있습니다. RubyAlign 및 RubyPosition 속성을 가질 수 있습니다. |
| RP | (Ruby punctuation) 루비 주석 텍스트를 둘러싼 구두점입니다. 루비 스타일로 제대로 형식화할 수 없고 일반 주석으로 형식화되거나 워리추로 형식화될 때만 사용됩니다. 일반적으로 단일 왼쪽 또는 오른쪽 괄호와 같은 괄호 문자를 포함합니다. |
| WARICHU | (Warichu; PDF 1.5) 포함된 텍스트 라인의 높이 내에서 두 개의 작은 줄로 형식화된 작은 글자 크기의 주석 또는 코멘트이며, 참조되는 기본 텍스트 뒤에(인라인) 배치됩니다. Warichu 요소는 WT와 WP 요소를 포함할 수도 있습니다. |
| WT | (Warichu text) 두 줄로 포맷되고 주변 WP 요소 사이에 배치되는 워이추 주석의 작은 크기 텍스트입니다. |
| WP | (Warichu punctuation) WT 텍스트를 둘러싸는 구두점입니다. 일반적으로 단일 LEFT 또는 RIGHT PARENTHESIS와 같은 괄호 문자(보통 하나의 LEFT 또는 RIGHT PARENTHESIS)를 포함합니다. JIS X 4051-1995에 따르면, 워이추를 둘러싼 괄호는 포맷터의 재량에 따라 SPACE(폭이 명목상 1/4 EM)로 변환될 수 있습니다. |
| FIGURE | (Figure) 그래픽 콘텐츠 항목입니다. 배치는 Placement 레이아웃 속성으로 지정될 수 있습니다. |
| FORMULA | (Formula) 수학 공식입니다. |
| FORM | (Form) 인터랙티브 폼 필드를 나타내는 위젯 주석입니다. |

### 또 보기

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

