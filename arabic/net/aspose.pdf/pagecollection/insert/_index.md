---
title: "PageCollection.Insert"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PageCollection. تُدرج صفحة فارغة في المجموعة في الموضع المحدد. إذا كان المستند يحتوي بالفعل على صفحات بأحجام مختلفة، سيتم اختيار حجم الصفحة الأكثر تكرارًا. في حالة وجود صفحتين مختلفتين فقط، سيُستخدم حجم الصفحة الأولى."
type: docs
weight: 160
url: /ar/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

أدرج صفحة فارغة في المجموعة في الموضع المحدد. إذا كان المستند يحتوي بالفعل على صفحات بأحجام مختلفة، سيتم اختيار حجم الصفحة الأكثر تكرارًا. في حالة وجود صفحتين مختلفتين فقط، سيُستخدم حجم الصفحة الأولى.

```csharp
public Page Insert(int pageNumber)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| pageNumber | Int32 | موضع الصفحة الجديدة. |

### قيمة الإرجاع

الصفحة المُدرجة.

### انظر أيضًا

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

يدرج صفحة في مجموعة الصفحات في المكان المحدد.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| pageNumber | Int32 | فهرس الصفحة المطلوب في المجموعة. |
| كيان | صفحة | الصفحة التي سيتم إدراجها. |

### قيمة الإرجاع

الصفحة المُدرجة.

### انظر أيضًا

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

يدرج الصفحات من المجموعة في المستند.

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| pageNumber | Int32 | الموضع الابتدائي للصفحات الجديدة. |
| صفحات | ICollection`1 | مجموعة الصفحات. |

### انظر أيضًا

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_2}

يدرج الصفحات الموجودة في المصفوفة في المستند.

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| pageNumber | Int32 | العدد الابتدائي للصفحات الجديدة. |
| صفحات | Page[] | مصفوفة من الصفحات التي سيتم إدراجها. |

### انظر أيضًا

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


