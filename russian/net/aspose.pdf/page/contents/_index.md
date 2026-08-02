---
title: "Page.Contents"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство Page. Получает коллекцию операторов в потоке содержимого страницы. OperatorCollection"
type: docs
weight: 90
url: /ru/net/aspose.pdf/page/contents/
---
## Page.Contents property

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

* class [OperatorCollection](../../operatorcollection/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


