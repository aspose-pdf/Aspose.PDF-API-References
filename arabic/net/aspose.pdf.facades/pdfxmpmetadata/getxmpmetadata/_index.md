---
title: "PdfXmpMetadata.GetXmpMetadata"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfXmpMetadata. احصل على XmpMetadata لملف PDF المدخل بصيغة XML"
type: docs
weight: 190
url: /ar/net/aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/
---
## GetXmpMetadata() {#getxmpmetadata}

احصل على XmpMetadata لملف pdf المدخل بصيغة xml.

```csharp
public byte[] GetXmpMetadata()
```

### قيمة الإرجاع

البتات الخاصة بـ XmpMetadata.

## أمثلة

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata();
```

### انظر أيضًا

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetXmpMetadata(string) {#getxmpmetadata_1}

احصل على جزء من XmpMetadata لملف pdf المدخل وفقًا لاسم ميتا.

```csharp
public byte[] GetXmpMetadata(string name)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| الاسم | String | اسم البيانات الوصفية. |

### قيمة الإرجاع

البتات الخاصة بالبيانات الوصفية.

## أمثلة

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata("dc:creator");
```

### انظر أيضًا

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


