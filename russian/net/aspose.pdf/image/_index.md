---
title: Class Image
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Image. Представляет изображение
type: docs
weight: 5860
url: /ru/net/aspose.pdf/image/
---
## Класс Image

Представляет изображение.

```csharp
public sealed class Image : BaseParagraph
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Image](image/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BitmapInfo](../../aspose.pdf/image/bitmapinfo/) { get; set; } | Получает или задает несжатые байты изображения. |
| [BitmapSize](../../aspose.pdf/image/bitmapsize/) { get; } | Получает размер битмапа изображения. |
| [File](../../aspose.pdf/image/file/) { get; set; } | Получает или задает файл изображения. |
| [FileType](../../aspose.pdf/image/filetype/) { get; set; } | Получает или задает тип файла изображения. |
| [FixHeight](../../aspose.pdf/image/fixheight/) { get; set; } | Получает или задает высоту изображения. |
| [FixWidth](../../aspose.pdf/image/fixwidth/) { get; set; } | Получает или задает ширину изображения. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Получает или задает горизонтальное выравнивание абзаца |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Получает или задает гиперссылку фрагмента (для генератора pdf). |
| [ImageScale](../../aspose.pdf/image/imagescale/) { get; set; } | Получает или задает масштаб изображения. |
| [ImageStream](../../aspose.pdf/image/imagestream/) { get; set; } | Получает или задает поток изображения. |
| [IsApplyResolution](../../aspose.pdf/image/isapplyresolution/) { get; set; } | Получает или задает логическое значение, указывающее, используется ли разрешение изображения при генерации |
| [IsBlackWhite](../../aspose.pdf/image/isblackwhite/) { get; set; } | Получает или задает логическое значение, указывающее, должно ли изображение быть черно-белым. Если используется TIFF изображение подформата CCITT, это свойство должно быть установлено в true. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующем столбце. По умолчанию false. (для генерации pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или задает, является ли абзац встроенным. По умолчанию false. (для генерации pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или задает логическое значение, которое заставляет этот абзац генерироваться на новой странице. По умолчанию false. (для генерации pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе с следующим абзацем. По умолчанию false. (для генерации pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или задает внешний отступ для абзаца (для генерации pdf) |
| [Title](../../aspose.pdf/image/title/) { get; set; } | Получает или задает строковое значение, указывающее заголовок изображения. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание абзаца |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, указывающее Z-упорядочение графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.pdf/image/clone/)() | Клонирует изображение. |
| static [GetMimeType](../../aspose.pdf/image/getmimetype/)(Image) | Возвращает mime-тип для изображения. |

## Примеры

Следующий пример показывает, как конвертировать изображения (PNG, JPEG, GIF, BMP или другие форматы изображений) в PDF файл.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your image (bmp, png, gif, jpeg, etc.) File.
	string imageFile = Path.Combine(dataDir, "Image-to-PDF.png");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf");

	//Initialize empty PDF document
	using(Document pdfDocument = new Document()) 
	{
	  pdfDocument.Pages.Add();
	  Image image = new Image();

	  // Load sample image file
	  image.File = imageFile;
	  pdfDocument.Pages[1].Paragraphs.Add(image);

	  // Save output PDF document
	  pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir = "YOUR_DATA_DIRECTORY"

    ' The path to your image (bmp, png, gif, jpeg, etc.) File.
    Dim imageFile = Path.Combine(dataDir, "Image-to-PDF.png")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf")
 
    'Initialize empty PDF document
    Using pdfDocument As Document = New Document()
        pdfDocument.Pages.Add()
        Dim image As Image = New Image()
 
        ' Load sample image file
        image.File = imageFile
        pdfDocument.Pages(1).Paragraphs.Add(image)
 
        ' Save output PDF document
        pdfDocument.Save(pdfFile)
    End Using
```

### См. также

* класс [BaseParagraph](../baseparagraph/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)