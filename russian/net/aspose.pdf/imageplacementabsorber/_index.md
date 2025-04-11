---
title: Class ImagePlacementAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.ImagePlacementAbsorber. Представляет объект-абсорбер объектов размещения изображений. Выполняет поиск использования изображений и предоставляет доступ к результатам поиска через коллекцию ImagePlacements
type: docs
weight: 5910
url: /ru/net/aspose.pdf/imageplacementabsorber/
---
## Класс ImagePlacementAbsorber

Представляет объект-абсорбер объектов размещения изображений. Выполняет поиск использования изображений и предоставляет доступ к результатам поиска через коллекцию [`ImagePlacements`](./imageplacements/).

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
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | Получает коллекцию случаев размещения изображений, которые представлены объектами [`ImagePlacement`](../imageplacement/). |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | Получает/устанавливает режим только для чтения для коллекции операций парсинга. Это может помочь избежать исключений недостатка памяти. |

## Методы

| Имя | Описание |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | Выполняет поиск в указанном документе. |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | Выполняет поиск на указанной странице. |

## Замечания

Объект `ImagePlacementAbsorber` в основном используется в сценарии поиска изображений. Когда поиск завершен, случаи представлены объектами [`ImagePlacement`](../imageplacement/), которые содержит коллекция [`ImagePlacements`](./imageplacements/). Объект [`ImagePlacement`](../imageplacement/) предоставляет доступ к свойствам размещения изображения: размеры, разрешение и т.д. Положительное вращение изображения против часовой стрелки, для страницы - по часовой стрелке. Здесь нам нужно представить угол вращения изображения, поэтому мы вычитаем угол страницы из угла изображения.

## Примеры

Пример демонстрирует, как найти изображения на первой странице PDF-документа и получить свойства размещения изображения.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Display image placement properties for all placements
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

* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)