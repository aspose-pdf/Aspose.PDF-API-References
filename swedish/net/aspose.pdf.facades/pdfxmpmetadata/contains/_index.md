---
title: PdfXmpMetadata.Contains
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata-metod. Kontrollerar om ordboken innehåller den angivna nyckeln
type: docs
weight: 130
url: /sv/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

Kontrollerar om ordboken innehåller den angivna nyckeln.

```csharp
public bool Contains(string key)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | Sträng | Nyckel som kommer att kontrolleras. |

### Returvärde

True - om ordboken innehåller den angivna nyckeln; annars, false.

## Exempel

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### Se Även

* klass [PdfXmpMetadata](../)
* namnrum [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

Kontrollerar om ordboken innehåller den angivna egenskapen.

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| property | DefaultMetadataProperties | Egenskap som kommer att kontrolleras. |

### Returvärde

True - om ordboken innehåller den angivna egenskapen; annars, false.

### Se Även

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* klass [PdfXmpMetadata](../)
* namnrum [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

Kontrollerar om den angivna nyckel-värde-paret finns i ordboken.

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | KeyValuePair`2 | Nyckel-värde-par. |

### Returvärde

true om detta par hittades.

### Se Även

* klass [XmpValue](../../../aspose.pdf/xmpvalue/)
* klass [PdfXmpMetadata](../)
* namnrum [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)