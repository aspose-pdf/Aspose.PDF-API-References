---
title: Class FdfReader
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Annotations.FdfReader. Kelas yang melakukan pembacaan format FDF
type: docs
weight: 1700
url: /id/net/aspose.pdf.annotations/fdfreader/
---
## Kelas FdfReader

Kelas yang melakukan pembacaan format FDF.

```csharp
public sealed class FdfReader
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | Mengimpor anotasi dari file FDF dan menempatkannya ke dalam dokumen. |

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