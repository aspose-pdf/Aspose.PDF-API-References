---
title: Form
second_title: Aspose.PDF لمرجع .NET API
description: مُنشئ النموذج بدون معلمات.
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

### أنظر أيضا

* class [Form](../../form)
* مساحة الاسم [Aspose.Pdf.Facades](../../form)
* المجسم [Aspose.PDF](../../../)

---

## Form(string) {#constructor_8}

منشئ النموذج .

```csharp
public Form(string srcFileName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| srcFileName | String | مسار الملف المصدر. |

### أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
```

### أنظر أيضا

* class [Form](../../form)
* مساحة الاسم [Aspose.Pdf.Facades](../../form)
* المجسم [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

مُنشئ النموذج .

```csharp
public Form(Stream srcStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| srcStream | Stream | مصدر تيار. |

### أمثلة

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### أنظر أيضا

* class [Form](../../form)
* مساحة الاسم [Aspose.Pdf.Facades](../../form)
* المجسم [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

تهيئة جديد[`Form`](../../form) كائن على قاعدة*document* .

```csharp
public Form(Document document)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Document | مستند PDF . |

### أنظر أيضا

* class [Document](../../../aspose.pdf/document)
* class [Form](../../form)
* مساحة الاسم [Aspose.Pdf.Facades](../../form)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
