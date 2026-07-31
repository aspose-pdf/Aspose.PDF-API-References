---
title: "Class FdfReader"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.Annotations.FdfReader class. Kelas yang melakukan pembacaan format FDF"
type: docs
weight: 1790
url: /id/net/aspose.pdf.annotations/fdfreader/
---
## FdfReader class

Kelas yang melakukan pembacaan format FDF.

```csharp
public sealed class FdfReader
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | Impor anotasi dari file FDF dan masukkan ke dalam dokumen. |

## Contoh

```csharp
Document doc = new Document("example.pdf");
Stream fdfStream = File.OpenRead("file.fdf");
FdfReader.ReadAnnotations(fdfStream, doc);
fdfStream.Close();
doc.Save("example_out.pdf");
```

### Lihat Juga

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


