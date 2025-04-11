---
title: Class XfdfReader
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.XfdfReader. Classe que realiza a leitura do formato XFDF
type: docs
weight: 2740
url: /pt/net/aspose.pdf.annotations/xfdfreader/
---
## Classe XfdfReader

Classe que realiza a leitura do formato XFDF.

```csharp
public sealed class XfdfReader
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [XfdfReader](xfdfreader/)() | O construtor padrão. |

## Métodos

| Nome | Descrição |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements/)(XmlReader) | Analisa o arquivo XFDF e retorna informações como um hashtable. |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations/)(Stream, Document) | Importa anotações do arquivo XFDF e as coloca no documento. |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields/)(Stream, Document) | Importa valores de campos do arquivo XFDF. |

## Exemplos

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### Veja Também

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)