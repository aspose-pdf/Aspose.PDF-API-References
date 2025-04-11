---
title: Class Element
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.Element 클래스. 논리 구조의 요소에 대한 기본 클래스를 나타냅니다.
type: docs
weight: 6320
url: /ko/net/aspose.pdf.logicalstructure/element/
---
## 요소 클래스

논리 구조의 요소에 대한 기본 클래스를 나타냅니다.

```csharp
public abstract class Element
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | 요소 객체의 자식 컬렉션을 가져옵니다. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | 부모 요소를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | 요소를 자식 컬렉션에 추가합니다. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | 모든 자식을 지웁니다. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | 주어진 유형의 요소를 찾습니다. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | 지정된 인덱스에 자식 컬렉션에 요소를 삽입합니다. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | 자식을 제거합니다. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_2)(Annotation) | 구조 요소를 주석에 바인딩합니다. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag)(Artifact) | 구조 요소를 아티팩트에 바인딩합니다. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_1)(BDC) | 구조 요소를 콘텐츠 스트림 BDC 연산자에 바인딩합니다. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_3)(XForm) | 구조 요소를 콘텐츠 스트림 XForm에 바인딩합니다. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_4)(XImage) | 구조 요소를 XImage에 바인딩합니다. |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | 현재 객체를 나타내는 문자열을 반환합니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* 어셈블리 [Aspose.PDF](../../)