---
title: "Класс FdfReader"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Annotations.FdfReader class. Класс, который выполняет чтение формата FDF"
type: docs
weight: 1790
url: /ru/net/aspose.pdf.annotations/fdfreader/
---
## FdfReader class

Класс, который выполняет чтение формата FDF.

```csharp
public sealed class FdfReader
```

## Методы

| Имя | Описание |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | Импортировать аннотации из файла FDF и поместить их в документ. |

## Примеры

```csharp
Document doc = new Document("example.pdf");
Stream fdfStream = File.OpenRead("file.fdf");
FdfReader.ReadAnnotations(fdfStream, doc);
fdfStream.Close();
doc.Save("example_out.pdf");
```

### См. также

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


