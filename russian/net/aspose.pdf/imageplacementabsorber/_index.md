---
title: "Класс ImagePlacementAbsorber"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.ImagePlacementAbsorber. Представляет объект‑поглотитель объектов размещения изображений. Выполняет поиск использований изображений и предоставляет доступ к результатам поиска через коллекцию ImagePlacements"
type: docs
weight: 6040
url: /ru/net/aspose.pdf/imageplacementabsorber/
---
## ImagePlacementAbsorber class

Представляет объект‑поглотитель объектов размещения изображений. Выполняет поиск использований изображений и предоставляет доступ к результатам поиска через коллекцию [`ImagePlacements`](./imageplacements/).

```csharp
public sealed class ImagePlacementAbsorber
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImagePlacementAbsorber](imageplacementabsorber/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | Получает коллекцию вхождений размещения изображений, представленных объектами [`ImagePlacement`](../imageplacement/). |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | Получает/устанавливает режим только для чтения для коллекции операций разбора. Это может помочь избежать исключений недостатка памяти. |

## Методы

| Имя | Описание |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | Выполняет поиск в указанном документе. |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | Выполняет поиск на указанной странице. |

## Примечания

Объект `ImagePlacementAbsorber` в основном используется в сценарии поиска изображений. После завершения поиска вхождения представлены объектами [`ImagePlacement`](../imageplacement/), которые содержатся в коллекции [`ImagePlacements`](./imageplacements/). Объект [`ImagePlacement`](../imageplacement/) предоставляет доступ к свойствам размещения изображения: размеры, разрешение и т.д. Положительное вращение изображения — против часовой стрелки, для страницы — по часовой стрелке. Здесь нам нужно представить угол вращения изображения, поэтому мы вычитаем угол страницы из угла изображения.

## Примеры

В примере демонстрируется, как найти изображения на первой странице PDF‑документа и получить свойства размещения изображений.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект ImagePlacementAbsorber для выполнения поиска размещения изображений
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(abs);

// Отобразите свойства размещения изображений для всех размещений
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{     
    Console.Out.WriteLine("image width:" + imagePlacement.Rectangle.Width);
    Console.Out.WriteLine("image height:" + imagePlacement.Rectangle.Height);
    Console.Out.WriteLine("image LLX:" + imagePlacement.Rectangle.LLX);
    Console.Out.WriteLine("image LLY:" + imagePlacement.Rectangle.LLY);
    Console.Out.WriteLine("image horizontal resolution:" + imagePlacement.Resolution.X);
    Console.Out.WriteLine("image vertical resolution:" + imagePlacement.Resolution.Y);
}
```

### См. также

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


