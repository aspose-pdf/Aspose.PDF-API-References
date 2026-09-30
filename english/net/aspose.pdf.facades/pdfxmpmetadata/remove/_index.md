---
title: "PdfXmpMetadata.Remove"
linktitle: "Remove"
articleTitle: "Remove"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfXmpMetadata method. Removes element with specified key."
type: docs
weight: 90
url: "/net/aspose.pdf.facades/pdfxmpmetadata/remove/"
product_version: "26.9.0"
---
## Remove([DefaultMetadataProperties](../../../aspose.pdf.facades/defaultmetadataproperties/)) {#remove}

Removes element with specified key.

```csharp
public void Remove(DefaultMetadataProperties key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | DefaultMetadataProperties | Key of the element which will be deleted. |

## Examples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove(DefaultMetadataProperties.Nickname);
```

### See Also

* enum [DefaultMetadataProperties](../../../aspose.pdf.facades/defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(string) {#remove_1}

Removes key from the dictionary.

```csharp
public bool Remove(string key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | Key which will be removed. |

### Return Value

True - if key removed; otherwise, false.

## Examples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove("xmp:Nickname");
```

### See Also

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair<string, XmpValue>) {#remove_2}

Removes key/value pair from the collection.

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| item | KeyValuePair`2 | Key/value pair to be removed. |

### Return Value

true if pair was found and removed.

### See Also

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

