---
title: "클래스 Element"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.LogicalStructure.Element 클래스. 논리 구조에서 요소의 기본 클래스를 나타냅니다."
type: docs
weight: 6460
url: /ko/net/aspose.pdf.logicalstructure/element/
---
## Element class

논리 구조에서 요소의 기본 클래스를 나타냅니다.

```csharp
public abstract class Element
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Element 객체들의 자식 컬렉션을 가져옵니다. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | 부모 요소를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Element를 자식 컬렉션에 추가합니다. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | 모든 자식 요소를 삭제합니다. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | 주어진 유형의 요소를 찾습니다 |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | 지정된 인덱스에 자식 컬렉션에 요소를 삽입합니다. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | 해당 위치의 자식을 제거합니다. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_2)(Annotation) | 구조 요소를 Annotation에 바인딩합니다. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag)(Artifact) | 구조 요소를 Artifact에 바인딩합니다. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_1)(BDC) | 구조 요소를 콘텐츠 스트림 BDC 연산자에 바인딩합니다. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_3)(XForm) | 구조 요소를 콘텐츠 스트림 XForm에 바인딩합니다. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_4)(XImage) | 구조 요소를 XImage에 바인딩합니다. |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | 현재 객체를 나타내는 문자열을 반환합니다. |

### 또 보기

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


