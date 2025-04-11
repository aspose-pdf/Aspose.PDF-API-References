---
title: PdfXmpMetadata.Contains
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfXmpMetadata. Controlla se il dizionario contiene la chiave specificata
type: docs
weight: 130
url: /it/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

Controlla se il dizionario contiene la chiave specificata.

```csharp
public bool Contains(string key)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | String | Chiave che verrà controllata. |

### Valore di Ritorno

True - se il dizionario contiene la chiave specificata; altrimenti, false.

## Esempi

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### Vedi Anche

* classe [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

Controlla se il dizionario contiene la proprietà specificata.

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| property | DefaultMetadataProperties | Proprietà che verrà controllata. |

### Valore di Ritorno

True - se il dizionario contiene la proprietà specificata; altrimenti, false.

### Vedi Anche

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* classe [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

Controlla se la coppia chiave-valore specificata è contenuta nel dizionario.

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | KeyValuePair`2 | Coppia chiave-valore. |

### Valore di Ritorno

true se questa coppia è stata trovata.

### Vedi Anche

* classe [XmpValue](../../../aspose.pdf/xmpvalue/)
* classe [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)