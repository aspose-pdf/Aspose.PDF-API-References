---
title: ImagePlacementAbsorber
second_title: Aspose.PDF для справочника API .NET
description: Представляет объект-поглотитель объектов размещения изображений. Выполняет поиск использований изображений и предоставляет доступ к результатам поиска черезImagePlacements./imageplacementabsorber/imageplacements коллекция.
type: docs
weight: 3770
url: /ru/net/aspose.pdf/imageplacementabsorber/
---
## ImagePlacementAbsorber class

Представляет объект-поглотитель объектов размещения изображений. Выполняет поиск использований изображений и предоставляет доступ к результатам поиска через[`ImagePlacements`](./imageplacements) коллекция.

```csharp
public sealed class ImagePlacementAbsorber
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImagePlacementAbsorber](imageplacementabsorber)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements) { get; } | Получает коллекцию вхождений размещения изображений, представленных[`ImagePlacement`](../imageplacement) объекты. |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode) { get; set; } | Получает/устанавливает режим только для чтения для коллекции операций синтаксического анализа. Это может помочь против нехватки памяти исключений. |

## Методы

| Имя | Описание |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit#visit)(Document) | Выполняет поиск в указанном документе. |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit#visit_1)(Page) | Выполняет поиск на указанной странице. |

### Примечания

[`ImagePlacementAbsorber`](../imageplacementabsorber) объект в основном используется в сценарии поиска изображений. Когда поиск завершен, вхождения представлены с[`ImagePlacement`](../imageplacement) объекты, которые[`ImagePlacements`](./imageplacements) коллекция содержит. [`ImagePlacement`](../imageplacement) объект предоставляет доступ к свойствам размещения изображения: размеру, разрешению и т. д.

### Примеры

В примере показано, как найти изображения на первой странице документа PDF и получить свойства размещения изображения.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создаем объект ImagePlacementAbsorber для выполнения поиска размещения изображения
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Принять поглотитель для первой страницы
doc.Pages[1].Accept(abs);

// Показать свойства размещения изображения для всех мест размещения
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

### Смотрите также

* пространство имен [Aspose.Pdf](../../aspose.pdf)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
