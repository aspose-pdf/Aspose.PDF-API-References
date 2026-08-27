---
title: "클래스 PageCollection"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.PageCollection 클래스. PDF 문서 페이지의 컬렉션."
type: docs
weight: 8220
url: /ko/net/aspose.pdf/pagecollection/
---
## PageCollection class

PDF Document 페이지의 컬렉션.

```csharp
public sealed class PageCollection : ICollection<Page>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | 문서의 페이지 수를 가져옵니다. |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | 컬렉션이 읽기 전용인지 나타내는 값을 가져옵니다. 항상 false를 반환합니다. |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | 객체가 동기화된 경우 true를 반환합니다. |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | 인덱스로 페이지를 가져옵니다. |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | 컬렉션의 동기화 객체를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | 주석 작업 기능을 제공하는 방문자 객체인 [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/)를 허용합니다. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | 이미지 배치 객체 작업 기능을 제공하는 방문자 객체인 [`ImagePlacementAbsorber`](../imageplacementabsorber/)를 허용합니다. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | 텍스트 객체 작업 기능을 제공하는 방문자 객체인 [`TextAbsorber`](../../aspose.pdf.text/textabsorber/)를 허용합니다. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | 텍스트 객체 작업 기능을 제공하는 방문자 객체인 [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/)를 허용합니다. |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | 빈 페이지를 추가합니다. 문서에 크기가 다른 페이지가 이미 포함되어 있는 경우, 가장 많이 나타나는 페이지의 크기가 선택됩니다. 두 종류의 페이지만 있는 경우, 첫 번째 페이지의 크기가 사용됩니다. |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | 목록의 모든 페이지를 컬렉션에 추가합니다. |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | 페이지를 컬렉션에 추가합니다. |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | 배열의 모든 페이지를 컬렉션에 추가합니다. |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | 페이지 컬렉션을 비웁니다. |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | 이 인스턴스가 해당 객체를 포함하는지 확인합니다. |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | 문서에 페이지를 복사합니다. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | 컬렉션에서 모든 페이지를 삭제합니다. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | 지정된 페이지를 삭제합니다. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | 배열에 지정된 번호의 페이지를 삭제합니다. |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | 페이지에 위치한 모든 필드를 제거하고 그 값을 대신 배치합니다. |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | 캐시된 데이터를 지웁니다. |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | 페이지 열거자를 반환합니다. |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | 지정된 페이지의 인덱스를 반환합니다. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | 지정된 위치에 빈 페이지를 컬렉션에 삽입합니다. 문서에 크기가 다른 페이지가 이미 포함되어 있는 경우, 가장 많이 나타나는 페이지의 크기가 선택됩니다. 두 개의 서로 다른 페이지만 있는 경우, 첫 번째 페이지의 크기가 사용됩니다. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | 컬렉션의 페이지를 문서에 삽입합니다. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | 지정된 위치에 페이지를 페이지 컬렉션에 삽입합니다. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | 배열의 페이지를 문서에 삽입합니다. |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | 지정된 항목을 제거하고 NotSupportedException을 발생시킵니다. |

### 또 보기

* class [Page](../page/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


