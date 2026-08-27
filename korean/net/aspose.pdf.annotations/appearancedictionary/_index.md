---
title: "AppearanceDictionary 클래스"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Annotations.AppearanceDictionary 클래스. 페이지에 주석이 시각적으로 표시되는 방식을 지정하는 주석 모양 사전입니다"
type: docs
weight: 1580
url: /ko/net/aspose.pdf.annotations/appearancedictionary/
---
## AppearanceDictionary class

주석이 페이지에 시각적으로 표시되는 방식을 지정하는 주석 외관 사전입니다.

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count/) { get; } | 사전에 포함된 요소 수를 가져옵니다. |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize/) { get; } | 사전이 고정 크기를 갖는지 여부를 나타내는 값을 가져옵니다. |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly/) { get; } | 사전이 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized/) { get; } | 사전에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 가져옵니다. |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item/) { get; set; } | 모양 스트림을 가져오기 위한 편리한 형태를 나타냅니다. |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys/) { get; } | 사전의 키를 가져옵니다. 모양 사전에 하위 사전이 있는 경우, [`Keys`](./keys/)는 (N&#x7C;R&#x7C;D).state 값을 포함합니다. 여기서 N은 일반 모양, R은 롤오버 모양, D는 누름 모양이며, state는 상태 이름을 나타냅니다(예: 체크박스의 On, Off). |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot/) { get; } | 사전에 대한 접근을 동기화하는 데 사용할 수 있는 객체를 가져옵니다. |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values/) { get; } | 사전 값들의 목록을 가져옵니다. 결과 컬렉션에는 XForm 객체들의 목록이 포함됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add)(KeyValuePair&lt;string, XForm&gt;) | 키와 값을 쌍으로 사전에 추가합니다. |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add_2)(string, XForm) | 지정된 키에 대한 X 양식을 추가합니다. |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear/)() | 사전에서 모든 요소를 제거합니다. |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains/)(KeyValuePair&lt;string, XForm&gt;) | 지정된 키-값 쌍이 사전에 포함되어 있는지 확인합니다. |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey/)(string) | 이 사전에 지정된 키가 포함되어 있는지 판단합니다. |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto)(XForm[], int) | 사전의 요소들을 특정 배열 인덱스부터 시작하여 Array에 복사합니다. |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator/)() | 사전에 대한 IDictionaryEnumerator 객체를 반환합니다. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove)(KeyValuePair&lt;string, XForm&gt;) | 컬렉션에서 키/값 쌍을 제거합니다. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove_1)(string) | 사전에서 키를 제거합니다. |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue/)(string, out XForm) | 사전에서 키를 찾으려고 시도하고, 찾으면 값을 검색합니다. |

### 또 보기

* class [XForm](../../aspose.pdf/xform/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


