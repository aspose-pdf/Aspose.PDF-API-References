---
title: "PdfXmpMetadata.Contains"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfXmpMetadata. تتحقق مما إذا كان القاموس يحتوي على المفتاح المحدد"
type: docs
weight: 130
url: /ar/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

يتحقق مما إذا كان القاموس يحتوي على المفتاح المحدد.

```csharp
public bool Contains(string key)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المفتاح | String | المفتاح الذي سيتم التحقق منه. |

### قيمة الإرجاع

صحيح - إذا كان القاموس يحتوي على المفتاح المحدد؛ وإلا، خطأ.

## أمثلة

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### انظر أيضًا

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

يتحقق مما إذا كان القاموس يحتوي على الخاصية المحددة.

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| خاصية | DefaultMetadataProperties | الخاصية التي سيتم التحقق منها. |

### قيمة الإرجاع

صحيح - إذا كان القاموس يحتوي على الخاصية المحددة؛ وإلا، خطأ.

### انظر أيضًا

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

يتحقق مما إذا كان زوج المفتاح-القيمة المحدد موجودًا في القاموس.

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| item | KeyValuePair`2 | زوج المفتاح والقيمة. |

### قيمة الإرجاع

صحيح إذا تم العثور على هذا الزوج.

### انظر أيضًا

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


