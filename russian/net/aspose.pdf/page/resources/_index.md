---
title: Page.Resources
second_title: Aspose.PDF for .NET API Reference
description: Свойство страницы. Получает ресурсы страницы. Объект ресурсов содержит коллекции изображений, форм и шрифтов. Ресурсы
type: docs
weight: 240
url: /ru/net/aspose.pdf/page/resources/
---
## Свойство Page.Resources

Получает ресурсы страницы. Объект ресурсов содержит коллекции изображений, форм и шрифтов. `Resources`

```csharp
public Resources Resources { get; }
```

## Примеры

Пример демонстрирует сканирование изображений страницы:

```csharp
Document document = new Document("sample.pdf");
DocumentActions actions = document.Actions;
Resources resources = document.Pages[1].Resources;
foreach(XImage image in resources.Images)
{
  Console.WriteLine(image.Width + ":" + image.Height);
}
```

### См. также

* класс [Resources](../../resources/)
* класс [Page](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)