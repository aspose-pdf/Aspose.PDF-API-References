---
title: "PdfXmpMetadata.Contains"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfXmpMetadata. Verifica se il dizionario contiene la chiave specificata"
type: docs
weight: 130
url: /it/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

Verifica se il dizionario contiene la chiave specificata.

```csharp
public bool Contains(string key)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chiave | String | Chiave che sarà verificata. |

### Valore di ritorno

True - se il dizionario contiene la chiave specificata; altrimenti, false.

## Esempi

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### Vedi anche

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

Verifica se il dizionario contiene la proprietà specificata.

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | DefaultMetadataProperties | Proprietà che sarà verificata. |

### Valore di ritorno

True - se il dizionario contiene la proprietà specificata; altrimenti, false.

### Vedi anche

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

Verifica se la coppia chiave-valore specificata è contenuta nel dizionario.

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | KeyValuePair`2 | Coppia chiave-valore. |

### Valore di ritorno

true se questa coppia è stata trovata.

### Vedi anche

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


