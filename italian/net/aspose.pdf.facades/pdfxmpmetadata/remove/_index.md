---
title: PdfXmpMetadata.Remove
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfXmpMetadata. Rimuove l'elemento con la chiave specificata
type: docs
weight: 210
url: /it/net/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## Remove(DefaultMetadataProperties) {#remove_2}

Rimuove l'elemento con la chiave specificata.

```csharp
public void Remove(DefaultMetadataProperties key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | DefaultMetadataProperties | Chiave dell'elemento che verrà eliminato. |

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

Rimuove la chiave dal dizionario.

```csharp
public bool Remove(string key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | Chiave che verrà rimossa. |

### Return Value

True - se la chiave è stata rimossa; altrimenti, false.

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

Rimuove la coppia chiave/valore dalla collezione.

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| item | KeyValuePair`2 | Coppia chiave/valore da rimuovere. |

### Return Value

true se la coppia è stata trovata e rimossa.

### See Also

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)