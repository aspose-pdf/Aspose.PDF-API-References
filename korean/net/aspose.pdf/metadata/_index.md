---
title: Class Metadata
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Metadata 클래스. XMP 메타데이터 스트림에 대한 액세스를 제공합니다.
type: docs
weight: 6950
url: /ko/net/aspose.pdf/metadata/
---
## 메타데이터 클래스

XMP 메타데이터 스트림에 대한 액세스를 제공합니다.

```csharp
public sealed class Metadata : IDictionary<string, XmpValue>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../aspose.pdf/metadata/count/) { get; } | 컬렉션의 요소 수를 가져옵니다. |
| [ExtensionFields](../../aspose.pdf/metadata/extensionfields/) { get; } | 확장 필드의 사전을 가져옵니다. |
| [IsFixedSize](../../aspose.pdf/metadata/isfixedsize/) { get; } | 컬렉션의 크기가 고정인지 확인합니다. |
| [IsReadOnly](../../aspose.pdf/metadata/isreadonly/) { get; } | 컬렉션이 읽기 전용인지 확인합니다. |
| [IsSynchronized](../../aspose.pdf/metadata/issynchronized/) { get; } | 컬렉션이 동기화되어 있는지 확인합니다. |
| [Item](../../aspose.pdf/metadata/item/) { get; set; } | 메타데이터에서 데이터를 가져오거나 설정합니다. |
| [Keys](../../aspose.pdf/metadata/keys/) { get; } | 메타데이터 키의 컬렉션을 가져옵니다. |
| [NamespaceManager](../../aspose.pdf/metadata/namespacemanager/) { get; } | 네임스페이스 관리자를 가져옵니다. |
| [SyncRoot](../../aspose.pdf/metadata/syncroot/) { get; } | 컬렉션 동기화 객체를 가져옵니다. |
| [Values](../../aspose.pdf/metadata/values/) { get; } | 메타데이터의 값을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Add](../../aspose.pdf/metadata/add/#add)(KeyValuePair&lt;string, XmpValue&gt;) | 키와 값을 쌍으로 사전에 추가합니다. |
| [Add](../../aspose.pdf/metadata/add/#add_3)(string, object) | 메타데이터에 값을 추가합니다. |
| [Add](../../aspose.pdf/metadata/add/#add_1)(string, XmpPdfAExtensionObject) | 메타데이터에 PDF 확장을 추가합니다. |
| [Add](../../aspose.pdf/metadata/add/#add_2)(string, XmpValue) | 메타데이터에 값을 추가합니다. |
| [Clear](../../aspose.pdf/metadata/clear/)() | 메타데이터를 지웁니다. |
| [Contains](../../aspose.pdf/metadata/contains/#contains)(KeyValuePair&lt;string, XmpValue&gt;) | 지정된 키-값 쌍이 사전에 포함되어 있는지 확인합니다. |
| [Contains](../../aspose.pdf/metadata/contains/#contains_1)(string) | 키가 메타데이터에 포함되어 있는지 확인합니다. |
| [ContainsKey](../../aspose.pdf/metadata/containskey/)(string) | 이 사전에 지정된 키가 포함되어 있는지 확인합니다. |
| [CopyTo](../../aspose.pdf/metadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/metadata/getenumerator/)() | 사전 열거자를 반환합니다. |
| [GetNamespaceUriByPrefix](../../aspose.pdf/metadata/getnamespaceuribyprefix/)(string) | 접두사로 네임스페이스 URI를 반환합니다. |
| [GetPrefixByNamespaceUri](../../aspose.pdf/metadata/getprefixbynamespaceuri/)(string) | 네임스페이스 URI로 접두사를 반환합니다. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri)(string, string) | 네임스페이스 URI를 등록합니다. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri_1)(string, string, string) | 네임스페이스 URI를 등록합니다. |
| [Remove](../../aspose.pdf/metadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | 컬렉션에서 키/값 쌍을 제거합니다. |
| [Remove](../../aspose.pdf/metadata/remove/#remove_1)(string) | 메타데이터에서 항목을 제거합니다. |
| [TryGetValue](../../aspose.pdf/metadata/trygetvalue/)(string, out XmpValue) | 사전에서 키를 찾으려고 시도하고, 찾으면 값을 검색합니다. |

### 참조

* 클래스 [XmpValue](../xmpvalue/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)