---
title: "PdfXmpMetadata.Remove"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "PdfXmpMetadata method. Rimuove l'elemento con la chiave specificata"
type: docs
weight: 210
url: /it/net/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## Remove(DefaultMetadataProperties) {#remove_2}

Rimuove l'elemento con la chiave specificata.

```csharp
public void Remove(DefaultMetadataProperties key)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chiave | DefaultMetadataProperties | Chiave dell'elemento che sarà eliminato. |

## Esempi

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove(DefaultMetadataProperties.Nickname);
```

### Vedi anche

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

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chiave | String | Chiave che sarà rimossa. |

### Valore di ritorno

True - se la chiave è rimossa; altrimenti, false.

## Esempi

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove("xmp:Nickname");
```

### Vedi anche

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, XmpValue&gt;) {#remove}

Rimuove la coppia chiave/valore dalla collezione.

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | KeyValuePair`2 | Coppia chiave/valore da rimuovere. |

### Valore di ritorno

true se la coppia è stata trovata e rimossa.

### Vedi anche

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


