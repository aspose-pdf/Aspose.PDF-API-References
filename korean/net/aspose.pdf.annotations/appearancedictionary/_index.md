---
title: Class AppearanceDictionary
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.AppearanceDictionary 클래스. 주석의 시각적 표현 방식을 지정하는 주석 외관 사전
type: docs
weight: 1490
url: /ko/net/aspose.pdf.annotations/appearancedictionary/
---
## AppearanceDictionary 클래스

주석의 시각적 표현 방식을 지정하는 주석 외관 사전.

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count/) { get; } | 사전에 포함된 요소의 수를 가져옵니다. |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize/) { get; } | 사전이 고정 크기를 가지는지 여부를 나타내는 값을 가져옵니다. |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly/) { get; } | 사전이 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized/) { get; } | 사전에 대한 접근이 동기화되었는지(스레드 안전) 여부를 나타내는 값을 가져옵니다. |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item/) { get; set; } | 외관 스트림을 가져오는 편리한 형식을 나타냅니다. |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys/) { get; } | 사전의 키를 가져옵니다. 외관 사전에 하위 사전이 있는 경우, [`Keys`](./keys/)는 (N&#x7C;R&#x7C;D).state 값을 포함하며, 여기서 N - 일반 외관, R - 롤오버 외관, D - 다운 외관 및 state - 상태의 이름(예: 체크박스의 경우 On, Off)입니다. |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot/) { get; } | 사전에 대한 접근을 동기화하는 데 사용할 수 있는 객체를 가져옵니다. |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values/) { get; } | 사전 값의 목록을 가져옵니다. 결과 컬렉션은 XForm 객체의 목록을 포함합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add)(KeyValuePair&lt;string, XForm&gt;) | 키와 값을 사전에 추가합니다. |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add_2)(string, XForm) | 지정된 키에 대한 X 형식을 추가합니다. |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear/)() | 사전에서 모든 요소를 제거합니다. |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains/)(KeyValuePair&lt;string, XForm&gt;) | 지정된 키-값 쌍이 사전에 포함되어 있는지 확인합니다. |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey/)(string) | 이 사전에 지정된 키가 포함되어 있는지 확인합니다. |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto)(XForm[], int) | 특정 배열 인덱스에서 시작하여 사전의 요소를 배열에 복사합니다. |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator/)() | 사전을 위한 IDictionaryEnumerator 객체를 반환합니다. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove)(KeyValuePair&lt;string, XForm&gt;) | 컬렉션에서 키/값 쌍을 제거합니다. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove_1)(string) | 사전에서 키를 제거합니다. |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue/)(string, out XForm) | 사전에서 키를 찾으려고 시도하고, 발견되면 값을 검색합니다. |

### 참조

* 클래스 [XForm](../../aspose.pdf/xform/)
* 네임스페이스 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* 어셈블리 [Aspose.PDF](../../)