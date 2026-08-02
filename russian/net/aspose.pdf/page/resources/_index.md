---
title: "Page.Resources"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство Page. Получает ресурсы страницы. Объект Resources содержит коллекции изображений, форм и шрифтов. Resources"
type: docs
weight: 240
url: /ru/net/aspose.pdf/page/resources/
---
## Page.Resources property

Получает ресурсы страницы. Объект Resources содержит коллекции изображений, форм и шрифтов. `Resources`

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

* class [Resources](../../resources/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


