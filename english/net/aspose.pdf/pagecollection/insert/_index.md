---
title: PageCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: PageCollection method. Insert an empty page into the collection at the specified position. If the document already contains pages with varying sizes the size of the most frequently occurring page will be selected. In the case there are only two different pages the size of the first page will be used
type: docs
weight: 160
url: /net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

Insert an empty page into the collection at the specified position. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used.

```csharp
public Page Insert(int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Position of the new page. |

### Return Value

Inserted page.

### See Also

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

Inserts page into page collection at specified place.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Required page index in collection. |
| entity | Page | Page to be inserted. |

### Return Value

Inserted page.

### See Also

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

Inserts pages from the collection into document.

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Starting position of the new pages. |
| pages | ICollection`1 | Pages collection. |

### See Also

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_2}

Inserts pages of the array into document.

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Starting number of the new pages. |
| pages | Page[] | Array of pages which will be inserted. |

### See Also

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


