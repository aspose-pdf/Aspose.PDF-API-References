---
title: "클래스 DestinationCollection"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.DestinationCollection 클래스. 모든 목적지의 컬렉션을 나타내는 클래스이며, 이름 문자열을 목적지에 매핑하는 이름 트리를 포함합니다. 자세한 내용은 pdf 문서의 12.3.2.3 Named Destinations 및 7.7.4 Name Dictionary를 참조하십시오."
type: docs
weight: 3630
url: /ko/net/aspose.pdf/destinationcollection/
---
## DestinationCollection class

클래스는 pdf 문서에서 모든 목적지의 컬렉션을 나타냅니다(이름 문자열을 목적지에 매핑하는 이름 트리(12.3.2.3, "Named Destinations" 참조) 및 (7.7.4, "Name Dictionary" 참조)).

```csharp
public sealed class DestinationCollection : ICollection<KeyValuePair<string, object>>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../aspose.pdf/destinationcollection/count/) { get; } | 컬렉션에 포함된 요소의 수를 가져옵니다. |
| [IsReadOnly](../../aspose.pdf/destinationcollection/isreadonly/) { get; } | 컬렉션이 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
| [Item](../../aspose.pdf/destinationcollection/item/) { get; } | 인덱스로 목적지 객체를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Add](../../aspose.pdf/destinationcollection/add/)(KeyValuePair&lt;string, object&gt;) | 지정된 항목을 추가합니다. 컬렉션은 읽기 전용입니다. 항상 NotSupportedException 예외를 발생시킵니다. |
| [Clear](../../aspose.pdf/destinationcollection/clear/)() | 컬렉션은 읽기 전용입니다. 항상 NotSupportedException 예외를 발생시킵니다. |
| [Contains](../../aspose.pdf/destinationcollection/contains/)(KeyValuePair&lt;string, object&gt;) | 이 인스턴스가 해당 객체를 포함하는지 확인합니다. |
| [CopyTo](../../aspose.pdf/destinationcollection/copyto/)(KeyValuePair&lt;string, object&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/destinationcollection/getenumerator/)() | 열거자를 반환합니다. |
| [GetExplicitDestination](../../aspose.pdf/destinationcollection/getexplicitdestination/)(string, bool) | 이름으로 명시적인 목적지를 반환합니다. |
| [GetPageNumber](../../aspose.pdf/destinationcollection/getpagenumber/)(string, bool) | 이름으로 목적지의 페이지 번호를 반환합니다. |
| [IndexOf](../../aspose.pdf/destinationcollection/indexof/)(KeyValuePair&lt;string, object&gt;) | 컬렉션에서 목적지의 인덱스를 반환합니다. |
| [Remove](../../aspose.pdf/destinationcollection/remove/)(KeyValuePair&lt;string, object&gt;) | 지정된 항목을 제거합니다. 컬렉션은 읽기 전용입니다. 항상 NotSupportedException 예외를 발생시킵니다. |

### 또 보기

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


