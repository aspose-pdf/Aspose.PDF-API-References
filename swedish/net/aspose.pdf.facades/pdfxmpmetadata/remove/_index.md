---
title: PdfXmpMetadata.Remove
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata metod. Tar bort element med angiven nyckel
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
| key | DefaultMetadataProperties | Nyckeln till det element som kommer att tas bort. |

## Exempel

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove(DefaultMetadataProperties.Nickname);
```

### Se Även

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(string) {#remove_1}

Tar bort nyckel från ordboken.

```csharp
public bool Remove(string key)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | String | Nyckel som kommer att tas bort. |

### Returvärde

True - om nyckeln togs bort; annars, false.

## Exempel

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove("xmp:Nickname");
```

### Se Även

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, XmpValue&gt;) {#remove}

Tar bort nyckel/värde-par från samlingen.

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | KeyValuePair`2 | Nyckel/värde-par som ska tas bort. |

### Returvärde

true om paret hittades och togs bort.

### Se Även

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)