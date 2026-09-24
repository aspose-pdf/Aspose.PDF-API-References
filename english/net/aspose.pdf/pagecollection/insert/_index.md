---
title: "PageCollection.Insert"
linktitle: "Insert"
articleTitle: "Insert"
second_title: "Aspose.PDF for .NET"
description: "Insert an empty page into the collection at the specified position. If the document already contains pages with varying sizes, the size of the most frequentl..."
type: docs
weight: 120
url: "/net/aspose.pdf/pagecollection/insert/"
product_version: "26.9.0"
---
## Insert(int) {#insert}

Insert an empty page into the collection at the specified position.
 If the document already contains pages with varying sizes,
 the size of the most frequently occurring page will be selected.
 In the case there are only two different pages, the size of the first page will be used.

```csharp
public Page Insert(int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Position of the new page. |

### Return Value

[Page](../../../aspose.pdf/page/)

Inserted page.

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, [Page](../../../aspose.pdf/page/)) {#insert_1}

Inserts page into page collection at specified place.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Required page index in collection. |
| entity | Page | Page to be inserted. |

### Return Value

[Page](../../../aspose.pdf/page/)

Inserted page.

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection<Page>) {#insert_2}

Inserts pages from the collection into document.

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Starting position of the new pages. |
| pages | ICollection<Page> | Pages collection. |

### See Also

* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_3}

Inserts pages of the array into document.

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Starting number of the new pages. |
| pages | Page[] | Array of pages which will be inserted. |

### See Also

* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

