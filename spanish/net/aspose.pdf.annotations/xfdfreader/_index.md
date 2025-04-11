---
title: Class XfdfReader
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Annotations.XfdfReader. Clase que realiza la lectura del formato XFDF
type: docs
weight: 2740
url: /es/net/aspose.pdf.annotations/xfdfreader/
---
## Clase XfdfReader

Clase que realiza la lectura del formato XFDF.

```csharp
public sealed class XfdfReader
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XfdfReader](xfdfreader/)() | El constructor por defecto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements/)(XmlReader) | Analiza el archivo XFDF y devuelve la información como un hashtable. |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations/)(Stream, Document) | Importa anotaciones del archivo XFDF y las coloca en el documento. |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields/)(Stream, Document) | Importa valores de campos del archivo XFDF. |

## Ejemplos

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### Ver También

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)