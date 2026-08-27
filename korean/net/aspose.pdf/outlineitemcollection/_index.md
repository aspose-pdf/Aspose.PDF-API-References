---
title: "클래스 OutlineItemCollection"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.OutlineItemCollection 클래스. PDF 문서의 개요 계층 구조에서 개요 항목을 나타냅니다."
type: docs
weight: 8150
url: /ko/net/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection class

PDF Document의 개요 계층 구조에 있는 개요 항목을 나타냅니다.

```csharp
public sealed class OutlineItemCollection : Outlines
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [OutlineItemCollection](outlineitemcollection/)(OutlineCollection) | 루트 계층 객체를 사용하여 개요 항목 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Action](../../aspose.pdf/outlineitemcollection/action/) { get; set; } | 이 개요 항목의 동작을 가져오거나 설정합니다. |
| [Bold](../../aspose.pdf/outlineitemcollection/bold/) { get; set; } | 이 개요 항목의 제목 텍스트에 대한 굵게 표시 플래그를 가져오거나 설정합니다. |
| [Color](../../aspose.pdf/outlineitemcollection/color/) { get; set; } | 이 개요 항목의 제목 텍스트 색상을 가져오거나 설정합니다. |
| override [Count](../../aspose.pdf/outlineitemcollection/count/) { get; } | 컬렉션 항목 수. VisibleCount와 혼동하지 마세요: VisibleCount는 모든 수준에서 보이는 개요 항목 수를 가져옵니다. |
| [Destination](../../aspose.pdf/outlineitemcollection/destination/) { get; set; } | 이 개요 항목의 목적지를 가져오거나 설정합니다. |
| [First](../../aspose.pdf/outlineitemcollection/first/) { get; } | 개요 계층 구조에서 첫 번째 최상위 항목을 나타내는 개요 항목을 가져옵니다. |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext/) { get; } | 개요 계층 구조에서 이 항목에 상대적으로 다음 항목을 나타내는 개요 항목인지 확인합니다. |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly/) { get; } | 컬렉션이 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized/) { get; } | 이 컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 가져옵니다. |
| [Italic](../../aspose.pdf/outlineitemcollection/italic/) { get; set; } | 이 개요 항목의 제목 텍스트에 대한 이탤릭 플래그를 가져오거나 설정합니다. |
| [Item](../../aspose.pdf/outlineitemcollection/item/) { get; } | 인덱스를 사용하여 컬렉션에서 개요 항목을 가져옵니다. |
| [Last](../../aspose.pdf/outlineitemcollection/last/) { get; } | 개요 계층 구조에서 마지막 최상위 항목을 나타내는 개요 항목을 가져옵니다. |
| [Level](../../aspose.pdf/outlineitemcollection/level/) { get; } | 개요 항목의 계층 레벨을 가져옵니다. |
| [Next](../../aspose.pdf/outlineitemcollection/next/) { get; } | 개요 계층 구조에서 이 항목에 상대적으로 다음 항목을 나타내는 개요 항목을 가져옵니다. |
| [Open](../../aspose.pdf/outlineitemcollection/open/) { get; set; } | 개요 항목에 대한 열림 상태(참/거짓)를 가져오거나 설정합니다. |
| [Parent](../../aspose.pdf/outlineitemcollection/parent/) { get; } | 개요 계층 구조에서 이 개요 항목의 상위 객체를 가져옵니다. |
| [Prev](../../aspose.pdf/outlineitemcollection/prev/) { get; } | 개요 계층 구조에서 이 항목에 상대적으로 이전 항목을 나타내는 개요 항목을 가져옵니다. |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot/) { get; } | 이 컬렉션에 대한 접근을 동기화하는 데 사용할 수 있는 객체를 가져옵니다. |
| [Title](../../aspose.pdf/outlineitemcollection/title/) { get; set; } | 이 개요 항목의 제목을 가져오거나 설정합니다. |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount/) { get; } | 문서 개요 계층 구조의 모든 레벨에 있는 개요 항목의 총 개수를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add/)(OutlineItemCollection) | 컬렉션에 개요 항목을 추가합니다. |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear/)() | 컬렉션의 모든 항목을 비웁니다. |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains/)(OutlineItemCollection) | 컬렉션에 지정된 항목이 포함되어 있는지 확인합니다. |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto/)(OutlineItemCollection[], int) | 개요 항목을 System.Array에 복사하며, 지정된 System.Array 인덱스부터 시작합니다. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete)() | 문서 개요 계층 구조에서 이 개요 항목을 삭제합니다. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete_1)(string) | 문서 개요 계층 구조에서 지정된 이름을 가진 개요 항목을 삭제합니다. |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator/)() | 컬렉션을 순회하는 열거자를 반환합니다. |
| [Insert](../../aspose.pdf/outlineitemcollection/insert/)(int, OutlineItemCollection) | 지정된 위치에 개요 항목을 컬렉션에 삽입합니다. |
| [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove_1)(int) | 인덱스로 항목을 제거합니다. |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove)(OutlineItemCollection) | 개요 컬렉션 항목을 제거합니다. |

### 또 보기

* class [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


