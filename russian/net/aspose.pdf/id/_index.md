---
title: Class Id
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Id. Представляет структуру идентификатора файла
type: docs
weight: 5850
url: /ru/net/aspose.pdf/id/
---
## Класс Id

Представляет структуру идентификатора файла.

```csharp
public class Id
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Измененный](../../aspose.pdf/id/modified/) { get; } | Изменение идентификатора на основе содержимого документа на момент его последнего обновления. |
| [Оригинальный](../../aspose.pdf/id/original/) { get; } | Постоянный идентификатор на основе содержимого документа на момент его первоначального создания. |

## Примеры

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### См. также

* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)