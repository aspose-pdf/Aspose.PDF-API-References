---
title: Class XfdfReader
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.XfdfReader. Classe che esegue la lettura del formato XFDF
type: docs
weight: 2740
url: /it/net/aspose.pdf.annotations/xfdfreader/
---
## Classe XfdfReader

Classe che esegue la lettura del formato XFDF.

```csharp
public sealed class XfdfReader
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XfdfReader](xfdfreader/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements/)(XmlReader) | Analizza il file XFDF e restituisce informazioni come hashtable. |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations/)(Stream, Document) | Importa annotazioni dal file XFDF e le inserisce nel documento. |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields/)(Stream, Document) | Importa i valori dei campi dal file XFDF. |

## Esempi

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### Vedi Anche

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)