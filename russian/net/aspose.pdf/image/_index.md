---
title: "Класс Image"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Image. Представляет изображение."
type: docs
weight: 5990
url: /ru/net/aspose.pdf/image/
---
## Image class

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
| [BitmapInfo](../../aspose.pdf/image/bitmapinfo/) { get; set; } | Получает или задаёт несжатые байты изображения. |
| [BitmapSize](../../aspose.pdf/image/bitmapsize/) { get; } | Получает размер битовой карты изображения. |
| [File](../../aspose.pdf/image/file/) { get; set; } | Получает или задаёт файл изображения. |
| [FileType](../../aspose.pdf/image/filetype/) { get; set; } | Получает или задаёт тип файла изображения. |
| [FixHeight](../../aspose.pdf/image/fixheight/) { get; set; } | Получает или задаёт высоту изображения. |
| [FixWidth](../../aspose.pdf/image/fixwidth/) { get; set; } | Получает или задаёт ширину изображения. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Получает или задает горизонтальное выравнивание абзаца |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Получает или задает гиперссылку фрагмента (для pdf‑генератора). |
| [ImageScale](../../aspose.pdf/image/imagescale/) { get; set; } | Получает или задаёт масштаб изображения. |
| [ImageStream](../../aspose.pdf/image/imagestream/) { get; set; } | Получает или задаёт поток изображения. |
| [IsApplyResolution](../../aspose.pdf/image/isapplyresolution/) { get; set; } | Получает или задаёт логическое значение, указывающее, использует ли изображение разрешение при генерации |
| [IsBlackWhite](../../aspose.pdf/image/isblackwhite/) { get; set; } | Получает или задает логическое значение, указывающее, принудительно ли изображение должно быть черно-белым. Если используется TIFF‑изображение субформата CCITT, это свойство должно быть установлено в true. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующей колонке. По умолчанию false. (для pdf‑генерации) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или задает, является ли абзац встроенным. По умолчанию false. (для pdf‑генерации) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или задает логическое значение, принуждающее этот абзац генерироваться на новой Page. По умолчанию false. (для pdf‑генерации) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или задает логическое значение, указывающее, остаётся ли текущий абзац на той же Page вместе со следующим абзацем. По умолчанию false. (для pdf‑генерации) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или задает внешний отступ для абзаца (для генерации PDF) |
| [Title](../../aspose.pdf/image/title/) { get; set; } | Получает или задает строковое значение, указывающее заголовок изображения. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание абзаца. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещён над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещён позади текста на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.pdf/image/clone/)() | Клонировать изображение. |
| static [GetMimeType](../../aspose.pdf/image/getmimetype/)(Image) | Возвращает MIME‑тип изображения. |

## Примеры

В следующем примере показано, как преобразовать изображения (PNG, JPEG, GIF, BMP или другие форматы изображений) в файл PDF.

```csharp
[C#]
	// Путь к каталогу документов.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Путь к вашему изображению (bmp, png, gif, jpeg и т.д.) Файл.
	string imageFile = Path.Combine(dataDir, "Image-to-PDF.png");

	// Путь к выходному PDF‑файлу.
	string pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf");

	//Инициализировать пустой документ PDF
	using(Document pdfDocument = new Document()) 
	{
	  pdfDocument.Pages.Add();
	  Image image = new Image();

	  // Загрузить пример файла изображения
	  image.File = imageFile;
	  pdfDocument.Pages[1].Paragraphs.Add(image);

	  // Сохранить результирующий документ PDF
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

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


