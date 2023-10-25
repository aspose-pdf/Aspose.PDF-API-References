---
title: PdfXmpMetadata.Contains
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata method. Checks if dictionary contains the specified key
type: docs
weight: 130
url: /net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

Checks if dictionary contains the specified key.

```csharp
public bool Contains(string key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | Key which will be checked. |

### Return Value

True - if the dictionary contains the specified key; otherwise, false.

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

Checks if dictionary contains the specified property.

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| Parameter | Type | Description |
| --- | --- | --- |
| property | DefaultMetadataProperties | Property which will be checked. |

### Return Value

True - if the dictionary contains the specified property; otherwise, false.

### See Also

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

Checks does specified key-value pair is contained in the dictionary.

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| item | KeyValuePair`2 | Key-value pair. |

### Return Value

true if this pauir was found.

### See Also

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


