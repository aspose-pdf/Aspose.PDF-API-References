---
title: Class TableTRElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.TableTRElement 클래스. 테이블의 논리 구조에서 TR 구조 요소를 나타냅니다.
type: docs
weight: 6850
url: /ko/net/aspose.pdf.logicalstructure/tabletrelement/
---
## TableTRElement 클래스

테이블의 논리 구조에서 TR 구조 요소를 나타냅니다.

```csharp
public sealed class TableTRElement : TableChildElement
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | 구조 요소의 실제 텍스트를 가져오거나 설정합니다. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | 구조 요소의 대체 텍스트를 가져오거나 설정합니다. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | StructureAttributeCollection 객체를 가져옵니다. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tabletrelement/backgroundcolor/) { get; set; } | 행 배경 색상을 가져오거나 설정합니다. |
| [Border](../../aspose.pdf.logicalstructure/tabletrelement/border/) { get; set; } | 행 테두리를 가져오거나 설정합니다. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Element 객체의 자식 컬렉션을 가져옵니다. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | AttributeOwnerStandard 객체를 가져옵니다. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellborder/) { get; set; } | 기본 셀 테두리를 가져옵니다. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellpadding/) { get; set; } | 행 셀의 기본 여백을 가져오거나 설정합니다. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tabletrelement/defaultcelltextstate/) { get; set; } | 행 셀의 기본 텍스트 상태를 가져오거나 설정합니다. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | 구조 요소의 확장 텍스트를 가져오거나 설정합니다. |
| [FixedRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/fixedrowheight/) { get; set; } | 고정된 행 높이를 가져오거나 설정합니다 - 행은 고정 높이를 가질 수 있습니다. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | 구조 요소의 ID를 가져옵니다. |
| [IsInNewPage](../../aspose.pdf.logicalstructure/tabletrelement/isinnewpage/) { get; set; } | 고정된 행이 새 페이지에 있는지 여부를 가져오거나 설정합니다 - 이 속성이 있는 페이지는 다음 페이지로 인쇄되어야 합니다. 기본값은 false입니다. |
| [IsRowBroken](../../aspose.pdf.logicalstructure/tabletrelement/isrowbroken/) { get; set; } | 행이 두 페이지 사이에서 나눌 수 있는지 여부를 가져오거나 설정합니다. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | 구조 요소의 언어를 가져오거나 설정합니다. |
| [MinRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/minrowheight/) { get; set; } | 행의 높이를 가져오거나 설정합니다. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | 일부 또는 모든 자식 요소가 렌더링될 페이지를 가져옵니다. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | 부모 요소를 가져옵니다. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | 구조 요소의 유형을 가져옵니다. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | 구조 요소의 제목을 가져오거나 설정합니다. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tabletrelement/verticalalignment/) { get; set; } | 수직 정렬을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | 자식 컬렉션에 Element를 추가합니다. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | 현재 구조 요소의 부모 요소를 변경합니다. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | 모든 자식을 지웁니다. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | 구조 요소의 ID를 지웁니다. |
| [CreateTD](../../aspose.pdf.logicalstructure/tabletrelement/createtd/)() | [`TableTHElement`](../tablethelement/)를 생성하고 현재 테이블에 추가합니다. |
| [CreateTH](../../aspose.pdf.logicalstructure/tabletrelement/createth/)() | [`TableTHElement`](../tablethelement/)를 생성하고 현재 테이블에 추가합니다. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | 주어진 유형의 요소를 찾습니다. |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | 구조 요소의 ID를 생성합니다. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | 지정된 인덱스에 자식 컬렉션에 Element를 삽입합니다. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | 구조에서 요소를 제거하고, 부모 객체에서의 참조를 제거하고, 자식 객체에서의 참조를 제거하며, 문서에서 해당 객체를 제거합니다. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | 구조에서 요소를 제거하고, 부모 객체에서의 참조를 제거하고, 자식 객체에서의 참조를 제거하며, 문서에서 해당 객체를 제거합니다. 제거된 객체의 자식 객체를 이전 부모 자식 객체 컬렉션에 제거된 객체의 인덱스에서 시작하여 삽입합니다. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | 자식을 제거합니다. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | 구조 요소의 ID를 설정합니다. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | 구조 요소의 사용자 정의 태그를 설정합니다. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | 구조 요소를 주석에 바인딩합니다. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | 구조 요소를 아티팩트에 바인딩합니다. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | 구조 요소를 콘텐츠 스트림 BDC 연산자에 바인딩합니다. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | 구조 요소를 콘텐츠 스트림 XForm에 바인딩합니다. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | 구조 요소를 XImage에 바인딩합니다. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | 현재 객체를 나타내는 문자열을 반환합니다. |

### 참조

* 클래스 [TableChildElement](../tablechildelement/)
* 네임스페이스 [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* 어셈블리 [Aspose.PDF](../../)