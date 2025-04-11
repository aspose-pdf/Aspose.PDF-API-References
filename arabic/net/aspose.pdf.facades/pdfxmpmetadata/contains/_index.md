---
title: PdfXmpMetadata.Contains
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfXmpMetadata. تتحقق مما إذا كانت القاموس يحتوي على المفتاح المحدد
type: docs
weight: 130
url: /ar/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

تتحقق مما إذا كانت القاموس يحتوي على المفتاح المحدد.

```csharp
public bool Contains(string key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | المفتاح الذي سيتم التحقق منه. |

### Return Value

True - إذا كان القاموس يحتوي على المفتاح المحدد؛ خلاف ذلك، false.

## Examples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### See Also

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

تتحقق مما إذا كانت القاموس يحتوي على الخاصية المحددة.

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| Parameter | Type | Description |
| --- | --- | --- |
| property | DefaultMetadataProperties | الخاصية التي سيتم التحقق منها. |

### Return Value

True - إذا كان القاموس يحتوي على الخاصية المحددة؛ خلاف ذلك، false.

### See Also

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

تتحقق مما إذا كانت زوج المفتاح-القيمة المحدد موجود في القاموس.

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| item | KeyValuePair`2 | زوج المفتاح-القيمة. |

### Return Value

true إذا تم العثور على هذه الزوج.

### See Also

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)