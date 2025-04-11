---
title: PageCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: PageCollection 메서드. 지정된 위치에 빈 페이지를 컬렉션에 삽입합니다. 문서에 이미 다양한 크기의 페이지가 포함되어 있는 경우 가장 자주 발생하는 페이지의 크기가 선택됩니다. 서로 다른 페이지가 두 개만 있는 경우 첫 번째 페이지의 크기가 사용됩니다.
type: docs
weight: 160
url: /ko/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

지정된 위치에 빈 페이지를 컬렉션에 삽입합니다. 문서에 이미 다양한 크기의 페이지가 포함되어 있는 경우 가장 자주 발생하는 페이지의 크기가 선택됩니다. 서로 다른 페이지가 두 개만 있는 경우 첫 번째 페이지의 크기가 사용됩니다.

```csharp
public Page Insert(int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | 새 페이지의 위치. |

### Return Value

삽입된 페이지.

### See Also

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

지정된 위치에 페이지를 페이지 컬렉션에 삽입합니다.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | 컬렉션에서 필요한 페이지 인덱스. |
| entity | Page | 삽입할 페이지. |

### Return Value

삽입된 페이지.

### See Also

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

컬렉션에서 문서로 페이지를 삽입합니다.

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | 새 페이지의 시작 위치. |
| pages | ICollection`1 | 페이지 컬렉션. |

### See Also

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_2}

배열의 페이지를 문서에 삽입합니다.

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | 새 페이지의 시작 번호. |
| pages | Page[] | 삽입될 페이지 배열. |

### See Also

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)