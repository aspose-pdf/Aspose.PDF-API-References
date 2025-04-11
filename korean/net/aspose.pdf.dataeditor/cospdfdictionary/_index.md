---
title: Class CosPdfDictionary
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DataEditor.CosPdfDictionary 클래스. 객체의 사전에 접근하기 위한 클래스
type: docs
weight: 3420
url: /ko/net/aspose.pdf.dataeditor/cospdfdictionary/
---
## CosPdfDictionary 클래스

객체의 사전에 접근하기 위한 클래스입니다.

```csharp
public class CosPdfDictionary : CosPdfPrimitive, IDictionary<string, ICosPdfPrimitive>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [CosPdfDictionary](cospdfdictionary/)(Resources) | 리소스에서 사전을 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/cospdfdictionary/allkeys/) { get; } | 모든 키의 전체 컬렉션입니다. 편집 가능한 키와 편집 불가능한 키를 포함합니다. |
| [Count](../../aspose.pdf.dataeditor/cospdfdictionary/count/) { get; } | `CosPdfDictionary`에 포함된 요소의 수를 가져옵니다. |
| [IsReadOnly](../../aspose.pdf.dataeditor/cospdfdictionary/isreadonly/) { get; } | `CosPdfDictionary`가 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
| [Item](../../aspose.pdf.dataeditor/cospdfdictionary/item/) { get; set; } | 지정된 키를 가진 요소를 가져오거나 설정합니다. |
| [Keys](../../aspose.pdf.dataeditor/cospdfdictionary/keys/) { get; } | 편집 가능한 키의 컬렉션입니다. |
| [Values](../../aspose.pdf.dataeditor/cospdfdictionary/values/) { get; } | `CosPdfDictionary`에 있는 값을 포함하는 ICollection을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary)(Document) | 문서에 첨부될 빈 사전을 생성합니다. |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary_1)(Page) | 페이지에 첨부될 빈 사전을 생성합니다. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | 사전에 [`ICosPdfPrimitive`](../icospdfprimitive/)를 설정합니다. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add_1)(string, ICosPdfPrimitive) | 사전에 [`ICosPdfPrimitive`](../icospdfprimitive/)를 설정합니다. |
| [Clear](../../aspose.pdf.dataeditor/cospdfdictionary/clear/)() | `CosPdfDictionary`에서 모든 항목을 제거합니다. |
| [Contains](../../aspose.pdf.dataeditor/cospdfdictionary/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | `CosPdfDictionary`가 특정 값을 포함하는지 여부를 결정합니다. |
| [ContainsKey](../../aspose.pdf.dataeditor/cospdfdictionary/containskey/)(string) | `CosPdfDictionary`가 지정된 키를 가진 요소를 포함하는지 여부를 결정합니다. |
| [CopyTo](../../aspose.pdf.dataeditor/cospdfdictionary/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/cospdfdictionary/getenumerator/)() | 컬렉션을 반복하는 열거자를 반환합니다. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | `CosPdfDictionary`에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove_1)(string) | `CosPdfDictionary`에서 지정된 키를 가진 요소를 제거합니다. |
| virtual [ToCosPdfBoolean](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfboolean/)() | 이 인스턴스를 [`CosPdfBoolean`](../cospdfboolean/)으로 변환하려고 시도합니다. |
| override [ToCosPdfDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/tocospdfdictionary/)() | 이 인스턴스를 `CosPdfDictionary`로 변환하려고 시도합니다. |
| virtual [ToCosPdfName](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfname/)() | 이 인스턴스를 [`CosPdfName`](../cospdfname/)으로 변환하려고 시도합니다. |
| virtual [ToCosPdfNumber](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfnumber/)() | 이 인스턴스를 [`CosPdfNumber`](../cospdfnumber/)으로 변환하려고 시도합니다. |
| virtual [ToCosPdfString](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfstring/)() | 이 인스턴스를 [`CosPdfString`](../cospdfstring/)으로 변환하려고 시도합니다. |
| [TryGetValue](../../aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/)(string, out ICosPdfPrimitive) | 문자열, 이름, 불리언, 숫자와 같은 간단한 데이터 유형에 접근합니다. 다른 유형에 대해서는 null을 반환합니다. |

### 참조

* 클래스 [CosPdfPrimitive](../cospdfprimitive/)
* 인터페이스 [ICosPdfPrimitive](../icospdfprimitive/)
* 네임스페이스 [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* 어셈블리 [Aspose.PDF](../../)