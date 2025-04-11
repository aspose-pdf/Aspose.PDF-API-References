---
title: Form.Form
second_title: Aspose.PDF for .NET API Reference
description: مُنشئ النموذج. مُنشئ النموذج بدون معلمات
type: docs
weight: 10
url: /ar/net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

مُنشئ النموذج بدون معلمات.

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

مُنشئ النموذج.

```csharp
public Form(string srcFileName)
```

| Parameter | Type | Description |
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

مُنشئ للنموذج.

```csharp
public Form(Stream srcStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | Stream | تدفق المصدر. |

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

يُهيئ كائن [`Form`](../) جديد بناءً على *المستند*.

```csharp
public Form(Document document)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | مستند PDF. |

### انظر أيضًا

* class [Document](../../../aspose.pdf/document/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)