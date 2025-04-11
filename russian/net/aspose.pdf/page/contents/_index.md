---
title: Page.Contents
second_title: Aspose.PDF for .NET API Reference
description: Свойство страницы. Получает коллекцию операторов в потоке содержимого страницы. OperatorCollection
type: docs
weight: 90
url: /ru/net/aspose.pdf/page/contents/
---
## Свойство Page.Contents

Получает коллекцию операторов в потоке содержимого страницы. [`OperatorCollection`](../../operatorcollection/)

```csharp
public OperatorCollection Contents { get; }
```

## Примеры

Пример демонстрирует, как сканировать поток операторов страницы.

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### См. также

* класс [OperatorCollection](../../operatorcollection/)
* класс [Page](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)