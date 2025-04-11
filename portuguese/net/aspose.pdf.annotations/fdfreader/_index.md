---
title: Class FdfReader
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.FdfReader. Classe que realiza a leitura do formato FDF
type: docs
weight: 1700
url: /pt/net/aspose.pdf.annotations/fdfreader/
---
## Classe FdfReader

Classe que realiza a leitura do formato FDF.

```csharp
public sealed class FdfReader
```

## Métodos

| Nome | Descrição |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | Importa anotações de um arquivo FDF e as coloca no documento. |

## Exemplos

```csharp
Document doc = new Document("example.pdf");
Stream fdfStream = File.OpenRead("file.fdf");
FdfReader.ReadAnnotations(fdfStream, doc);
fdfStream.Close();
doc.Save("example_out.pdf");
```

### Veja Também

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)