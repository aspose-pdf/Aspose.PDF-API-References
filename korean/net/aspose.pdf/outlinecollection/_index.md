---
title: "클래스 OutlineCollection"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.OutlineCollection 클래스. Document 개요 계층 구조를 나타냅니다."
type: docs
weight: 8140
url: /ko/net/aspose.pdf/outlinecollection/
---
## OutlineCollection class

문서 개요 계층 구조를 나타냅니다.

```csharp
public sealed class OutlineCollection : Outlines
```

## 속성

| 이름 | 설명 |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count/) { get; } | 컬렉션 항목 수. VisibleCount와 혼동하지 마세요: VisibleCount는 모든 수준에서 보이는 개요 항목 수를 가져옵니다. |
| [First](../../aspose.pdf/outlinecollection/first/) { get; } | 개요에서 첫 번째 최상위 항목을 나타내는 개요 항목을 가져옵니다. |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly/) { get; } | 컬렉션이 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized/) { get; } | 이 컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 가져옵니다. |
| [Item](../../aspose.pdf/outlinecollection/item/) { get; } | 인덱스로 컬렉션에서 개요 항목을 가져옵니다. |
| [Last](../../aspose.pdf/outlinecollection/last/) { get; } | 개요에서 마지막 최상위 항목을 나타내는 개요 항목을 가져옵니다. |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot/) { get; } | 이 컬렉션에 대한 접근을 동기화하는 데 사용할 수 있는 객체를 가져옵니다. |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount/) { get; } | Count는 모든 수준에서 보이는 하위 개요 항목 수의 합계입니다. 참고: 컬렉션의 항목 수를 나타내는 Count와 혼동하지 마세요. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add/)(OutlineItemCollection) | 컬렉션에 개요 항목을 추가합니다. |
| override [Clear](../../aspose.pdf/outlinecollection/clear/)() | 컬렉션의 모든 항목을 비웁니다. |
| override [Contains](../../aspose.pdf/outlinecollection/contains/)(OutlineItemCollection) | 컬렉션이 지정된 항목을 포함하는지 확인합니다. |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto/)(OutlineItemCollection[], int) | 개요 항목을 System.Array에 복사합니다. 특정 System.Array 인덱스부터 시작합니다. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete)() | 문서 개요에서 모든 개요 항목을 삭제합니다. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete_1)(string) | 지정된 제목을 가진 개요 항목을 문서 개요에서 삭제합니다. |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator/)() | 컬렉션을 순회하는 열거자를 반환합니다. |
| [Remove](../../aspose.pdf/outlinecollection/remove/#remove_1)(int) | 인덱스로 항목을 제거합니다. |
| override [Remove](../../aspose.pdf/outlinecollection/remove/#remove)(OutlineItemCollection) | 항상 NotImplementedException을 발생시킵니다. |

### 또 보기

* class [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


