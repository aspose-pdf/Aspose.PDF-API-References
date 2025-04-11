---
title: Class PageCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PageCollection 클래스. PDF 문서 페이지의 컬렉션
type: docs
weight: 8080
url: /ko/net/aspose.pdf/pagecollection/
---
## PageCollection 클래스

PDF 문서 페이지의 컬렉션입니다.

```csharp
public sealed class PageCollection : ICollection<Page>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | 문서의 페이지 수를 가져옵니다. |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | 컬렉션이 읽기 전용인지 나타내는 값을 가져옵니다. 항상 false를 반환합니다. |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | 객체가 동기화되었는지 true를 반환합니다. |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | 인덱스로 페이지를 가져옵니다. |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | 컬렉션의 동기화 객체를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | 주석과 작업할 수 있는 기능을 제공하는 [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) 방문자 객체를 수락합니다. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | 이미지 배치 객체와 작업할 수 있는 기능을 제공하는 [`ImagePlacementAbsorber`](../imageplacementabsorber/) 방문자 객체를 수락합니다. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | 텍스트 객체와 작업할 수 있는 기능을 제공하는 [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) 방문자 객체를 수락합니다. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | 텍스트 객체와 작업할 수 있는 기능을 제공하는 [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) 방문자 객체를 수락합니다. |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | 빈 페이지를 추가합니다. 문서에 크기가 다른 페이지가 이미 포함되어 있는 경우, 가장 자주 발생하는 페이지의 크기가 선택됩니다. 두 개의 서로 다른 페이지만 있는 경우 첫 번째 페이지의 크기가 사용됩니다. |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | 목록의 모든 페이지를 컬렉션에 추가합니다. |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | 페이지를 컬렉션에 추가합니다. |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | 배열의 모든 페이지를 컬렉션에 추가합니다. |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | 페이지 컬렉션을 지웁니다. |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | 이 인스턴스가 객체를 포함하는지 여부를 결정합니다. |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | 페이지를 문서에 복사합니다. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | 컬렉션의 모든 페이지를 삭제합니다. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | 지정된 페이지를 삭제합니다. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | 배열에 지정된 번호의 페이지를 삭제합니다. |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | 페이지에 위치한 모든 필드를 제거하고 그 값을 대신 배치합니다. |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | 캐시된 데이터를 지웁니다. |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | 페이지의 열거자를 반환합니다. |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | 지정된 페이지의 인덱스를 반환합니다. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | 지정된 위치에 컬렉션에 빈 페이지를 삽입합니다. 문서에 크기가 다른 페이지가 이미 포함되어 있는 경우, 가장 자주 발생하는 페이지의 크기가 선택됩니다. 두 개의 서로 다른 페이지만 있는 경우 첫 번째 페이지의 크기가 사용됩니다. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | 컬렉션의 페이지를 문서에 삽입합니다. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | 지정된 위치에 페이지 컬렉션에 페이지를 삽입합니다. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | 배열의 페이지를 문서에 삽입합니다. |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | 지정된 항목을 제거하며, NotSupportedException을 발생시킵니다. |

### 참조

* 클래스 [Page](../page/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)