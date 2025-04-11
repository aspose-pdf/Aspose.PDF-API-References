---
title: Class XfdfReader
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Annotations.XfdfReader. Класс, который выполняет чтение формата XFDF
type: docs
weight: 2740
url: /ru/net/aspose.pdf.annotations/xfdfreader/
---
## XfdfReader class

Класс, который выполняет чтение формата XFDF.

```csharp
public sealed class XfdfReader
```

## Constructors

| Name | Description |
| --- | --- |
| [XfdfReader](xfdfreader/)() | Конструктор по умолчанию. |

## Methods

| Name | Description |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements/)(XmlReader) | Парсит файл XFDF и возвращает информацию в виде хеш-таблицы. |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations/)(Stream, Document) | Импортирует аннотации из файла XFDF и добавляет их в документ. |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields/)(Stream, Document) | Импортирует значения полей из файла XFDF. |

## Examples

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### See Also

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)