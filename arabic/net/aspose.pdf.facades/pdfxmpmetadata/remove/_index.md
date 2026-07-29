---
title: "PdfXmpMetadata.Remove"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfXmpMetadata. تزيل العنصر بالمفتاح المحدد"
type: docs
weight: 210
url: /ar/net/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## Remove(DefaultMetadataProperties) {#remove_2}

يزيل العنصر بالمفتاح المحدد.

```csharp
public void Remove(DefaultMetadataProperties key)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المفتاح | DefaultMetadataProperties | مفتاح العنصر الذي سيتم حذفه. |

## أمثلة

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove(DefaultMetadataProperties.Nickname);
```

### انظر أيضًا

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(string) {#remove_1}

يزيل المفتاح من القاموس.

```csharp
public bool Remove(string key)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المفتاح | String | المفتاح الذي سيتم إزالته. |

### قيمة الإرجاع

صحيح - إذا تم إزالة المفتاح؛ وإلا، خطأ.

## أمثلة

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove("xmp:Nickname");
```

### انظر أيضًا

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, XmpValue&gt;) {#remove}

يزيل زوج المفتاح/القيمة من المجموعة.

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| item | KeyValuePair`2 | زوج المفتاح/القيمة الذي سيتم إزالته. |

### قيمة الإرجاع

صحيح إذا تم العثور على الزوج وإزالته.

### انظر أيضًا

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


