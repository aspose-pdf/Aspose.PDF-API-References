---
title: "Класс ImagePlacement"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.ImagePlacement. Представляет характеристики изображения, размещённого на странице документа PDF"
type: docs
weight: 6030
url: /ru/net/aspose.pdf/imageplacement/
---
## ImagePlacement class

Представляет характеристики изображения, размещённого на странице PDF‑документа.

```csharp
public sealed class ImagePlacement
```

## Свойства

| Имя | Описание |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | Получает параметры композитинга графического состояния, активные для изображения, размещённого на странице. |
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
| [Hide](../../aspose.pdf/imageplacement/hide/)() | Удалить изображение со страницы. |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | Заменить изображение в коллекции другим изображением. |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | Сохраняет изображение с соответствующими преобразованиями: масштабирование, вращение и разрешение. |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | Сохраняет изображение с соответствующими преобразованиями: масштабирование, вращение и разрешение. |

## Примечания

Когда изображение размещается на странице, оно может иметь размеры, отличные от физических размеров, определённых в [`Resources`](../resources/). Объект `ImagePlacement` предназначен для предоставления такой информации, как размеры, разрешение и т.д.

## Примеры

В примере демонстрируется, как найти изображения на первой странице PDF‑документа и получить изображения в виде битмапов с видимыми размерами.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект ImagePlacementAbsorber для выполнения поиска размещения изображений
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(abs);

// Получить изображения с видимыми размерами
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // Получить изображение из ресурсов
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // Создать новый битмап с фактическими размерами
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### См. также

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


