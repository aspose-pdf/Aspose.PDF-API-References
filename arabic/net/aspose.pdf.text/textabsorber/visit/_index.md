---
title: "TextAbsorber.Visit"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة TextAbsorber. تستخرج النص في الصفحة المحددة"
type: docs
weight: 70
url: /ar/net/aspose.pdf.text/textabsorber/visit/
---
## Visit(Page) {#visit_1}

يستخرج النص من الـ page المحدد

```csharp
public virtual void Visit(Page page)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صفحة | صفحة | كائن صفحة مستند Pdf. |

## أمثلة

يوضح المثال كيفية استخراج النص من الصفحة الأولى لـ PDF document.

```csharp
// فتح المستند
Document doc = new Document(inFile);

// إنشاء كائن TextAbsorber لاستخراج النص
TextAbsorber absorber = new TextAbsorber();

// قبول الـ absorber لجميع صفحات المستند
absorber.Visit(doc.Pages[1]);

// احصل على النص المستخرج
string extractedText = absorber.Text;
```

### انظر أيضًا

* class [Page](../../../aspose.pdf/page/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

يستخرج النص على الـ XForm المحدد.

```csharp
public virtual void Visit(XForm form)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| نموذج | XForm | كائن نموذج Pdf. |

## أمثلة

يوضح المثال كيفية استخراج النص من الصفحة الأولى لـ PDF document.

```csharp
// فتح المستند
Document doc = new Document(inFile);

// إنشاء كائن TextAbsorber لاستخراج النص
TextAbsorber absorber = new TextAbsorber();

// قبول الـ absorber لجميع صفحات المستند
absorber.Visit(doc.Pages[1].Resources.Forms["Xform1"]);

// احصل على النص المستخرج
string extractedText = absorber.Text;
```

### انظر أيضًا

* class [XForm](../../../aspose.pdf/xform/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

يستخرج النص من الـ document المحدد

```csharp
public virtual void Visit(Document pdf)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| pdf | Document | كائن Pdf pocument. |

## أمثلة

يوضح المثال كيفية استخراج النص من مستند PDF.

```csharp
// فتح المستند
Document doc = new Document(inFile);

// إنشاء كائن TextAbsorber لاستخراج النص
TextAbsorber absorber = new TextAbsorber();

// قبول الـ absorber لجميع صفحات المستند
absorber.Visit(doc);

// احصل على النص المستخرج
string extractedText = absorber.Text;
```

### انظر أيضًا

* class [Document](../../../aspose.pdf/document/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


