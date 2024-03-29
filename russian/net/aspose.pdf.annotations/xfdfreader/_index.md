---
title: XfdfReader
second_title: Aspose.PDF для справочника API .NET
description: Класс выполняющий чтение формата XFDF.
type: docs
weight: 1280
url: /ru/net/aspose.pdf.annotations/xfdfreader/
---
## XfdfReader class

Класс, выполняющий чтение формата XFDF.

```csharp
public sealed class XfdfReader
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XfdfReader](xfdfreader)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements)(XmlReader) | Разбирает файл XFDF и возвращает информацию в виде хеш-таблицы. |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations)(Stream, Document) | Импортировать аннотации из файла XFDF и помещать их в документ. |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields)(Stream, Document) | Импорт значений полей из файла XFDF. |

### Примеры

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### Смотрите также

* пространство имен [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
