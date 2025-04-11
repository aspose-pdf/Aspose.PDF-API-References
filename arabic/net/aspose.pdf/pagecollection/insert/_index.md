---
title: PageCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: طريقة PageCollection. إدراج صفحة فارغة في المجموعة في الموضع المحدد. إذا كان المستند يحتوي بالفعل على صفحات بأحجام مختلفة، فسيتم اختيار حجم الصفحة الأكثر تكرارًا. في حالة وجود صفحتين مختلفتين فقط، سيتم استخدام حجم الصفحة الأولى.
type: docs
weight: 160
url: /ar/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

إدراج صفحة فارغة في المجموعة في الموضع المحدد. إذا كان المستند يحتوي بالفعل على صفحات بأحجام مختلفة، فسيتم اختيار حجم الصفحة الأكثر تكرارًا. في حالة وجود صفحتين مختلفتين فقط، سيتم استخدام حجم الصفحة الأولى.

```csharp
public Page Insert(int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | موضع الصفحة الجديدة. |

### Return Value

الصفحة المدخلة.

### See Also

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

يتم إدراج الصفحة في مجموعة الصفحات في المكان المحدد.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | فهرس الصفحة المطلوبة في المجموعة. |
| entity | Page | الصفحة التي سيتم إدراجها. |

### Return Value

الصفحة المدخلة.

### See Also

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

يتم إدراج الصفحات من المجموعة في المستند.

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | الموضع الابتدائي للصفحات الجديدة. |
| pages | ICollection`1 | مجموعة الصفحات. |

### See Also

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_2}

يتم إدراج صفحات المصفوفة في المستند.

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | الرقم الابتدائي للصفحات الجديدة. |
| pages | Page[] | مصفوفة الصفحات التي سيتم إدراجها. |

### See Also

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)