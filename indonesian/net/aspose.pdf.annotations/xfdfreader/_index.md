---
title: Class XfdfReader
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Annotations.XfdfReader. Kelas yang melakukan pembacaan format XFDF
type: docs
weight: 2740
url: /id/net/aspose.pdf.annotations/xfdfreader/
---
## Kelas XfdfReader

Kelas yang melakukan pembacaan format XFDF.

```csharp
public sealed class XfdfReader
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [XfdfReader](xfdfreader/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements/)(XmlReader) | Mengurai file XFDF dan mengembalikan informasi sebagai hashtable. |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations/)(Stream, Document) | Mengimpor anotasi dari file XFDF dan menempatkannya ke dalam dokumen. |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields/)(Stream, Document) | Mengimpor nilai field dari file XFDF. |

## Contoh

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### Lihat Juga

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)