---
title: Class DictionaryEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DataEditor.DictionaryEditor 클래스. 문서의 트리 사전(문서 사전, 페이지 사전, 리소스 사전)에 접근하기 위한 클래스입니다.
type: docs
weight: 3470
url: /ko/net/aspose.pdf.dataeditor/dictionaryeditor/
---
## DictionaryEditor 클래스

문서의 트리 사전(문서 사전, 페이지 사전, 리소스 사전)에 접근하기 위한 클래스입니다.

```csharp
public class DictionaryEditor : IDictionary<string, ICosPdfPrimitive>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [DictionaryEditor](dictionaryeditor/#constructor)(Document) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_1)(Page) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_2)(Resources) |  |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/dictionaryeditor/allkeys/) { get; } | 전체 키 컬렉션. 편집 가능한 키와 편집 불가능한 키를 포함합니다. |
| [Count](../../aspose.pdf.dataeditor/dictionaryeditor/count/) { get; } | `DictionaryEditor`에 포함된 요소의 수를 가져옵니다. |
| [IsReadOnly](../../aspose.pdf.dataeditor/dictionaryeditor/isreadonly/) { get; } | `DictionaryEditor`가 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
| [Item](../../aspose.pdf.dataeditor/dictionaryeditor/item/) { get; set; } | 지정된 키를 가진 요소를 가져오거나 설정합니다. |
| [Keys](../../aspose.pdf.dataeditor/dictionaryeditor/keys/) { get; } | 편집 가능한 키의 컬렉션입니다. |
| [Values](../../aspose.pdf.dataeditor/dictionaryeditor/values/) { get; } | `DictionaryEditor`에 있는 값을 포함하는 ICollection을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | 사전에 [`ICosPdfPrimitive`](../icospdfprimitive/)를 설정합니다. |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add_1)(string, ICosPdfPrimitive) | 사전에 [`ICosPdfPrimitive`](../icospdfprimitive/)를 설정합니다. |
| [Clear](../../aspose.pdf.dataeditor/dictionaryeditor/clear/)() | `DictionaryEditor`에서 모든 항목을 제거합니다. |
| [Contains](../../aspose.pdf.dataeditor/dictionaryeditor/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | `DictionaryEditor`가 특정 값을 포함하는지 여부를 확인합니다. |
| [ContainsKey](../../aspose.pdf.dataeditor/dictionaryeditor/containskey/)(string) | `DictionaryEditor`가 지정된 키를 가진 요소를 포함하는지 여부를 확인합니다. |
| [CopyTo](../../aspose.pdf.dataeditor/dictionaryeditor/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/dictionaryeditor/getenumerator/)() | 컬렉션을 반복하는 열거자를 반환합니다. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | `DictionaryEditor`에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove_1)(string) | `DictionaryEditor`에서 지정된 키를 가진 요소를 제거합니다. |
| [TryGetValue](../../aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/)(string, out ICosPdfPrimitive) | 문자열, 이름, 불리언, 숫자와 같은 간단한 데이터 유형에 접근합니다. 다른 유형에 대해서는 null을 반환합니다. |

### 참조

* 인터페이스 [ICosPdfPrimitive](../icospdfprimitive/)
* 네임스페이스 [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* 어셈블리 [Aspose.PDF](../../)