---
title: "PdfXmpMetadata.Contains"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfXmpMetadata‑metod. Kontrollerar om ordboken innehåller den angivna nyckeln"
type: docs
weight: 130
url: /sv/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

Kontrollerar om dictionary innehåller den angivna nyckeln.

```csharp
public bool Contains(string key)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | String | Nyckel som ska kontrolleras. |

### Returvärde

Sant - om ordboken innehåller den angivna nyckeln; annars falskt.

## Exempel

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### Se även

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

Kontrollerar om dictionary innehåller den angivna egenskapen.

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | DefaultMetadataProperties | Egenskap som ska kontrolleras. |

### Returvärde

Sant - om ordboken innehåller den angivna egenskapen; annars falskt.

### Se även

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

Kontrollerar om det angivna nyckel‑värde‑paret finns i dictionary.

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | KeyValuePair`2 | Nyckel‑värdepar. |

### Returvärde

true om detta par hittades.

### Se även

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


