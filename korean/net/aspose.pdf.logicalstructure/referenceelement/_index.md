---
title: "클래스 ReferenceElement"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.LogicalStructure.ReferenceElement 클래스. 논리 구조에서 Reference 구조 요소를 나타냅니다."
type: docs
weight: 6720
url: /ko/net/aspose.pdf.logicalstructure/referenceelement/
---
## ReferenceElement class

논리 구조에서 Reference 구조 요소를 나타냅니다.

```csharp
public sealed class ReferenceElement : ILSElement
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | 구조 요소에 대한 실제 텍스트를 가져오거나 설정합니다. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | 구조 요소에 대한 대체 텍스트를 가져오거나 설정합니다. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | StructureAttributeCollection 객체를 가져옵니다. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Element 객체들의 자식 컬렉션을 가져옵니다. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | AttributeOwnerStandard 객체를 가져옵니다. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | 구조 요소에 대한 확장 텍스트를 가져오거나 설정합니다. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | 구조 요소의 ID를 가져옵니다. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | 구조 요소의 언어를 가져오거나 설정합니다. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | 일부 또는 모든 자식 요소가 렌더링될 페이지를 가져옵니다. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | 부모 요소를 가져옵니다. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | 구조 요소의 유형을 가져옵니다. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | 구조 요소의 제목을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Element를 자식 컬렉션에 추가합니다. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | 현재 구조 요소의 부모 요소를 변경합니다 |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | 모든 자식 요소를 삭제합니다. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | 구조 요소의 ID를 지웁니다. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | 주어진 유형의 요소를 찾습니다 |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | 구조 요소의 ID를 생성합니다. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | 지정된 인덱스에 자식 컬렉션에 요소를 삽입합니다. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | 제거합니다: 구조에서 요소, 상위 객체에서 해당 요소에 대한 참조, 자식 객체에서의 참조, 문서에서 해당 객체. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | 구조에서 요소와 상위 객체에서 해당 요소에 대한 참조, 자식 객체에서의 참조, 그리고 문서에서 해당 객체를 제거합니다. 제거된 객체의 자식 객체를 제거된 객체의 인덱스부터 이전 상위 객체의 자식 컬렉션에 삽입합니다. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | 해당 위치의 자식을 제거합니다. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | 구조 요소의 ID를 설정합니다. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | 구조 요소에 사용자 지정 태그를 설정합니다. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | 구조 요소를 Annotation에 바인딩합니다. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | 구조 요소를 Artifact에 바인딩합니다. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | 구조 요소를 콘텐츠 스트림 BDC 연산자에 바인딩합니다. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | 구조 요소를 콘텐츠 스트림 XForm에 바인딩합니다. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | 구조 요소를 XImage에 바인딩합니다. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | 현재 객체를 나타내는 문자열을 반환합니다. |

### 또 보기

* class [ILSElement](../ilselement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


