---
title: Class OutlineItemCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OutlineItemCollection 클래스. PDF 문서의 개요 계층에서 개요 항목을 나타냅니다.
type: docs
weight: 8010
url: /ko/net/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection 클래스

PDF 문서의 개요 계층에서 개요 항목을 나타냅니다.

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
| [Action](../../aspose.pdf/outlineitemcollection/action/) { get; set; } | 이 개요 항목에 대한 작업을 가져오거나 설정합니다. |
| [Bold](../../aspose.pdf/outlineitemcollection/bold/) { get; set; } | 이 개요 항목의 제목 텍스트에 대한 굵게 표시 플래그를 가져오거나 설정합니다. |
| [Color](../../aspose.pdf/outlineitemcollection/color/) { get; set; } | 이 개요 항목의 제목 텍스트에 대한 색상을 가져오거나 설정합니다. |
| override [Count](../../aspose.pdf/outlineitemcollection/count/) { get; } | 컬렉션 항목의 수입니다. VisibleCount와 혼동하지 마십시오: VisibleCount는 모든 수준에서 보이는 개요 항목의 수를 가져옵니다. |
| [Destination](../../aspose.pdf/outlineitemcollection/destination/) { get; set; } | 이 개요 항목에 대한 대상을 가져오거나 설정합니다. |
| [First](../../aspose.pdf/outlineitemcollection/first/) { get; } | 개요 계층에서 첫 번째 최상위 항목을 나타내는 개요 항목을 가져옵니다. |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext/) { get; } | 개요 계층에서 이 항목에 상대적인 다음 항목을 나타내는 개요 항목이 있는지 확인합니다. |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly/) { get; } | 컬렉션이 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized/) { get; } | 이 컬렉션에 대한 접근이 동기화되었는지(스레드 안전) 여부를 나타내는 값을 가져옵니다. |
| [Italic](../../aspose.pdf/outlineitemcollection/italic/) { get; set; } | 이 개요 항목의 제목 텍스트에 대한 이탤릭체 플래그를 가져오거나 설정합니다. |
| [Item](../../aspose.pdf/outlineitemcollection/item/) { get; } | 인덱스를 사용하여 컬렉션에서 개요 항목을 가져옵니다. |
| [Last](../../aspose.pdf/outlineitemcollection/last/) { get; } | 개요 계층에서 마지막 최상위 항목을 나타내는 개요 항목을 가져옵니다. |
| [Level](../../aspose.pdf/outlineitemcollection/level/) { get; } | 개요 항목의 계층 수준을 가져옵니다. |
| [Next](../../aspose.pdf/outlineitemcollection/next/) { get; } | 개요 계층에서 이 항목에 상대적인 다음 항목을 나타내는 개요 항목을 가져옵니다. |
| [Open](../../aspose.pdf/outlineitemcollection/open/) { get; set; } | 개요 항목에 대한 열림 상태(true/false)를 가져오거나 설정합니다. |
| [Parent](../../aspose.pdf/outlineitemcollection/parent/) { get; } | 개요 계층에서 이 개요 항목의 부모 객체를 가져옵니다. |
| [Prev](../../aspose.pdf/outlineitemcollection/prev/) { get; } | 개요 계층에서 이 항목에 상대적인 이전 항목을 나타내는 개요 항목을 가져옵니다. |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot/) { get; } | 이 컬렉션에 대한 접근을 동기화하는 데 사용할 수 있는 객체를 가져옵니다. |
| [Title](../../aspose.pdf/outlineitemcollection/title/) { get; set; } | 이 개요 항목의 제목을 가져오거나 설정합니다. |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount/) { get; } | 문서 개요 계층의 모든 수준에서 개요 항목의 총 수를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add/)(OutlineItemCollection) | 개요 항목을 컬렉션에 추가합니다. |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear/)() | 컬렉션에서 모든 항목을 지웁니다. |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains/)(OutlineItemCollection) | 컬렉션에 주어진 항목이 포함되어 있는지 확인합니다. |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto/)(OutlineItemCollection[], int) | 특정 System.Array 인덱스에서 시작하여 개요 항목을 System.Array에 복사합니다. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete)() | 이 개요 항목을 문서 개요 계층에서 삭제합니다. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete_1)(string) | 지정된 이름의 개요 항목을 문서 개요 계층에서 삭제합니다. |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator/)() | 컬렉션을 반복하는 열거자를 반환합니다. |
| [Insert](../../aspose.pdf/outlineitemcollection/insert/)(int, OutlineItemCollection) | 지정된 위치에 개요 항목을 컬렉션에 삽입합니다. |
| [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove_1)(int) | 인덱스로 항목을 제거합니다. |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove)(OutlineItemCollection) | 개요 컬렉션 항목을 제거합니다. |

### 참조

* 클래스 [Outlines](../outlines/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)