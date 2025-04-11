---
title: PdfXmpMetadata.Remove
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata-Methode. Entfernt Element mit dem angegebenen Schlüssel
type: docs
weight: 210
url: /de/net/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## Remove(DefaultMetadataProperties) {#remove_2}

Entfernt Element mit dem angegebenen Schlüssel.

```csharp
public void Remove(DefaultMetadataProperties key)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | DefaultMetadataProperties | Schlüssel des Elements, das gelöscht werden soll. |

## Beispiele

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove(DefaultMetadataProperties.Nickname);
```

### Siehe auch

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(string) {#remove_1}

Entfernt Schlüssel aus dem Wörterbuch.

```csharp
public bool Remove(string key)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | String | Schlüssel, der entfernt werden soll. |

### Rückgabewert

True - wenn der Schlüssel entfernt wurde; andernfalls false.

## Beispiele

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove("xmp:Nickname");
```

### Siehe auch

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, XmpValue&gt;) {#remove}

Entfernt Schlüssel/Wert-Paar aus der Sammlung.

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | KeyValuePair`2 | Schlüssel/Wert-Paar, das entfernt werden soll. |

### Rückgabewert

true, wenn das Paar gefunden und entfernt wurde.

### Siehe auch

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)