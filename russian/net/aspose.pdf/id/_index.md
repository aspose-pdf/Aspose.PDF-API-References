---
title: "Класс Id"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Id. Представляет структуру идентификатора файла."
type: docs
weight: 5980
url: /ru/net/aspose.pdf/id/
---
## Id class

Представляет структуру идентификатора файла.

```csharp
public class Id
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Modified](../../aspose.pdf/id/modified/) { get; } | Изменение идентификатора на основе содержимого документа на момент его последнего обновления. |
| [Original](../../aspose.pdf/id/original/) { get; } | Постоянный идентификатор, основанный на содержимом документа на момент его первоначального создания. |

## Примеры

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### См. также

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


