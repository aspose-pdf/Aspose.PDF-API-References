---
title: PdfXmpMetadata.Contains
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata-Methode. Überprüft, ob das Wörterbuch den angegebenen Schlüssel enthält
type: docs
weight: 130
url: /de/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

Überprüft, ob das Wörterbuch den angegebenen Schlüssel enthält.

```csharp
public bool Contains(string key)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | String | Schlüssel, der überprüft wird. |

### Rückgabewert

True - wenn das Wörterbuch den angegebenen Schlüssel enthält; andernfalls false.

## Beispiele

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### Siehe auch

* Klasse [PdfXmpMetadata](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

Überprüft, ob das Wörterbuch die angegebene Eigenschaft enthält.

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| property | DefaultMetadataProperties | Eigenschaft, die überprüft wird. |

### Rückgabewert

True - wenn das Wörterbuch die angegebene Eigenschaft enthält; andernfalls false.

### Siehe auch

* Enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* Klasse [PdfXmpMetadata](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

Überprüft, ob das angegebene Schlüssel-Wert-Paar im Wörterbuch enthalten ist.

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | KeyValuePair`2 | Schlüssel-Wert-Paar. |

### Rückgabewert

true, wenn dieses Paar gefunden wurde.

### Siehe auch

* Klasse [XmpValue](../../../aspose.pdf/xmpvalue/)
* Klasse [PdfXmpMetadata](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)