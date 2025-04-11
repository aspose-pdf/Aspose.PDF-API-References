---
title: PdfXmpMetadata.Remove
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfXmpMetadata. تزيل العنصر بالمفتاح المحدد
type: docs
weight: 210
url: /ar/net/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## Remove(DefaultMetadataProperties) {#remove_2}

تزيل العنصر بالمفتاح المحدد.

```csharp
public void Remove(DefaultMetadataProperties key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | DefaultMetadataProperties | مفتاح العنصر الذي سيتم حذفه. |

## Examples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove(DefaultMetadataProperties.Nickname);
```

### See Also

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(string) {#remove_1}

تزيل المفتاح من القاموس.

```csharp
public bool Remove(string key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | المفتاح الذي سيتم إزالته. |

### Return Value

True - إذا تم إزالة المفتاح؛ خلاف ذلك، false.

## Examples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove("xmp:Nickname");
```

### See Also

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, XmpValue&gt;) {#remove}

تزيل زوج المفتاح/القيمة من المجموعة.

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| item | KeyValuePair`2 | زوج المفتاح/القيمة الذي سيتم إزالته. |

### Return Value

true إذا تم العثور على الزوج وتم إزالته.

### See Also

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)