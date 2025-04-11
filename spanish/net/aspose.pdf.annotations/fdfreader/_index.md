---
title: Class FdfReader
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Annotations.FdfReader. Clase que realiza la lectura del formato FDF
type: docs
weight: 1700
url: /es/net/aspose.pdf.annotations/fdfreader/
---
## Clase FdfReader

Clase que realiza la lectura del formato FDF.

```csharp
public sealed class FdfReader
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | Importar anotaciones desde un archivo FDF y colocarlas en el documento. |

## Ejemplos

```csharp
Document doc = new Document("example.pdf");
Stream fdfStream = File.OpenRead("file.fdf");
FdfReader.ReadAnnotations(fdfStream, doc);
fdfStream.Close();
doc.Save("example_out.pdf");
```

### Ver También

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)