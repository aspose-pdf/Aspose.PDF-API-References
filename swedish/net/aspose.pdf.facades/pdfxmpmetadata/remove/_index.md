---
title: "PdfXmpMetadata.Remove"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfXmpMetadata-metoden. Tar bort element med angiven nyckel"
type: docs
weight: 210
url: /sv/net/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## Remove(DefaultMetadataProperties) {#remove_2}

Tar bort element med angiven nyckel.

```csharp
public void Remove(DefaultMetadataProperties key)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | DefaultMetadataProperties | Nyckeln för elementet som ska tas bort. |

## Exempel

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove(DefaultMetadataProperties.Nickname);
```

### Se även

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(string) {#remove_1}

Tar bort nyckeln från dictionary.

```csharp
public bool Remove(string key)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | String | Nyckel som kommer att tas bort. |

### Returvärde

Sant - om nyckeln togs bort; annars falskt.

## Exempel

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove("xmp:Nickname");
```

### Se även

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, XmpValue&gt;) {#remove}

Tar bort nyckel/värde‑par från samlingen.

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | KeyValuePair`2 | Nyckel/värde-par som ska tas bort. |

### Returvärde

Sant om paret hittades och togs bort.

### Se även

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


