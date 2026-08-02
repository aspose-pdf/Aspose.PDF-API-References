---
title: "Класс XfdfReader"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Annotations.XfdfReader. Класс, который выполняет чтение формата XFDF"
type: docs
weight: 2840
url: /ru/net/aspose.pdf.annotations/xfdfreader/
---
## XfdfReader class

Класс, который выполняет чтение формата XFDF.

```csharp
public sealed class XfdfReader
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XfdfReader](xfdfreader/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements/)(XmlReader) | Разбирает файл XFDF и возвращает информацию в виде hashtable. |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations/)(Stream, Document) | Импортирует аннотации из файла XFDF и помещает их в документ. |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields/)(Stream, Document) | Импортирует значения полей из файла XFDF. |

## Примеры

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### См. также

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


