---
title: "Kelas XfdfReader"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Annotations.XfdfReader. Kelas yang melakukan pembacaan format XFDF"
type: docs
weight: 2840
url: /id/net/aspose.pdf.annotations/xfdfreader/
---
## XfdfReader class

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
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements/)(XmlReader) | Menganalisis file XFDF dan mengembalikan informasi sebagai hashtable. |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations/)(Stream, Document) | Impor anotasi dari file XFDF dan menempatkannya ke dalam dokumen. |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields/)(Stream, Document) | Impor nilai bidang dari file XFDF. |

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


