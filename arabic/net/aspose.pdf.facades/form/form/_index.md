---
title: "Form.Form"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "منشئ Form. مُنشئ Form بدون معلمات"
type: docs
weight: 10
url: /ar/net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

منشئ Form بدون معلمات.

```csharp
Form form = new Aspose.Pdf.Facades.Form();
form.SrcFileName = "file.pdf";
```

```csharp
public Form()
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(string) {#constructor_7}

منشئ Form.

```csharp
public Form(string srcFileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| srcFileName | String | مسار ملف المصدر. |

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

منشئ للنموذج.

```csharp
public Form(Stream srcStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| srcStream | Stream | دفق المصدر. |

## أمثلة

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

يُهيئ كائن [`Form`](../) جديد على أساس *المستند*.

```csharp
public Form(Document document)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| document | Document | مستند Pdf. |

### انظر أيضًا

* class [Document](../../../aspose.pdf/document/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


