---
title: Class ImagePlacement
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.ImagePlacement. Представляет характеристики изображения, размещенного на странице документа Pdf
type: docs
weight: 5900
url: /ru/net/aspose.pdf/imageplacement/
---
## Класс ImagePlacement

Представляет характеристики изображения, размещенного на странице документа Pdf.

```csharp
public sealed class ImagePlacement
```

## Свойства

| Имя | Описание |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | Получает параметры композитинга графического состояния, активного для изображения, размещенного на странице. |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | Получает связанный объект ресурса XImage. |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | Текущая матрица преобразования для этого изображения. |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | Оператор, используемый для отображения изображения. |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | Получает страницу, содержащую изображение. |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | Получает прямоугольник изображения. |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | Получает разрешение изображения. |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | Получает угол поворота изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | Удаляет изображение со страницы. |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | Заменяет изображение в коллекции другим изображением. |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | Сохраняет изображение с соответствующими преобразованиями: масштабированием, поворотом и разрешением. |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | Сохраняет изображение с соответствующими преобразованиями: масштабированием, поворотом и разрешением. |

## Замечания

Когда изображение размещается на странице, оно может иметь размеры, отличные от физических размеров, определенных в [`Resources`](../resources/). Объект `ImagePlacement` предназначен для предоставления такой информации, как размеры, разрешение и так далее.

## Примеры

Пример демонстрирует, как найти изображения на первой странице PDF-документа и получить изображения в виде битмапов с видимыми размерами.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Retrieve images with visible dimensions
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // Retrieve image from resources
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // Create new bitmap with actual dimensions
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### См. также

* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)