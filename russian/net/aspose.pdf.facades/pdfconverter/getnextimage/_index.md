---
title: GetNextImage
second_title: Aspose.PDF для справочника API .NET
description: Сохраняет изображение в файл с форматом изображения по умолчанию - jpeg.
type: docs
weight: 140
url: /ru/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

Сохраняет изображение в файл с форматом изображения по умолчанию - jpeg.

```csharp
public void GetNextImage(string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Путь и имя файла для сохранения изображения. |

### Смотрите также

* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

Сохраняет изображение в файл с заданным размером страницы и форматом изображения по умолчанию - jpeg.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Путь и имя файла для сохранения изображения. |
| pageSize | PageSize | Размер страницы изображения. |

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

Сохраняет изображение в файл с заданным форматом изображения.

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Путь и имя файла для сохранения изображения. |
| format | ImageFormat | Формат изображения. |

### Примеры

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".png";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Png);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".png" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Png)
	imageCount = imageCount + 1
End While
```

### Смотрите также

* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

Сохраняет изображение в файл с заданным размером страницы и форматом изображения.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Путь и имя файла для сохранения изображения. |
| pageSize | PageSize | Размер страницы изображения. |
| format | ImageFormat | Формат изображения. |

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Сохраняет изображение в поток с форматом изображения по умолчанию - jpeg.

```csharp
public void GetNextImage(Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения. |

### Смотрите также

* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

Сохраняет изображение в поток с заданным размером страницы.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения. |
| pageSize | PageSize | Размер страницы изображения. |

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

Сохраняет изображение в поток с заданным форматом изображения.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения. |
| format | ImageFormat | Формат изображения. |

### Смотрите также

* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

Сохраняет изображение в поток с заданным размером страницы.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения. |
| pageSize | PageSize | Размер страницы изображения. |
| format | ImageFormat | Формат изображения. |

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

Сохраняет изображение в файл с заданным форматом, размерами и качеством изображения.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Путь и имя файла для сохранения изображения. |
| format | ImageFormat | Формат изображения. |
| imageWidth | Int32 | Ширина изображения в пикселях. |
| imageHeight | Int32 | Высота изображения в пикселях. |
| quality | Int32 | Качество файла Jpeg (0~100), 0 — самое низкое, 100 — самое высокое |

### Примеры

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50)
	imageCount = imageCount + 1
End While
```

### Смотрите также

* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

Сохраняет изображение в поток с заданным форматом изображения, размерами и качеством.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения. |
| format | ImageFormat | Формат изображения. |
| imageWidth | Int32 | Ширина изображения в пикселях. |
| imageHeight | Int32 | Высота изображения в пикселях. |
| quality | Int32 | Качество файла Jpeg (0~100), 0 — самое низкое, 100 — самое высокое |

### Смотрите также

* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

Сохраняет изображение в файл с заданным форматом, размером и качеством изображения.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Путь и имя файла для сохранения изображения. |
| format | ImageFormat | Формат изображения. |
| imageWidth | Double | Ширина изображения в пикселях. |
| imageHeight | Double | Высота изображения в пикселях.. |
| quality | Int32 | Качество файла Jpeg (0~100), 0 — самый низкий, а 100 — самый высокий |

### Примеры

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
float pixelX=800f;
float pixelY=600f;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim pixelX As float =800
Dim pixelY As float=600
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50)
	imageCount = imageCount + 1
End While
```

### Смотрите также

* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

Сохраняет изображение в поток с заданным форматом, размером и качеством изображения.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения. |
| format | ImageFormat | Формат изображения. |
| imageWidth | Double | Ширина изображения в пикселях. |
| imageHeight | Double | Высота изображения в пикселях. |
| quality | Int32 | Качество файла Jpeg (0~100), 0 — самое низкое, 100 — самое высокое |

### Смотрите также

* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

Сохраняет изображение в файл с указанным форматом и размером изображения.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Путь и имя файла для сохранения изображения. |
| format | ImageFormat | Формат изображения. |
| imageWidth | Int32 | Ширина изображения в пикселях. |
| imageHeight | Int32 | Высота изображения в пикселях. |

### Примеры

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000)
	imageCount = imageCount + 1
End While
```

### Смотрите также

* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

Сохраняет изображение в поток с заданным форматом, размером и качеством изображения.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения. |
| format | ImageFormat | Формат изображения. |
| imageWidth | Int32 | Ширина изображения в пикселях. |
| imageHeight | Int32 | Высота изображения в пикселях. |

### Смотрите также

* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

Сохраняет изображение в поток с заданным форматом и качеством изображения.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения. |
| format | ImageFormat | Формат изображения. |
| quality | Int32 | Качество файла Jpeg (0~100), 0 — самое низкое, 100 — самое высокое |

### Смотрите также

* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

Сохраняет изображение в поток с заданным размером страницы, форматом изображения и качеством.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения. |
| pageSize | PageSize | Размер страницы изображения. |
| format | ImageFormat | Формат изображения. |
| quality | Int32 | Качество файла Jpeg (0~100), 0 — самое низкое, 100 — самое высокое |

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

Сохраняет изображение в файл с заданным форматом и качеством изображения.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Путь и имя файла для сохранения изображения. |
| format | ImageFormat | Формат изображения. |
| quality | Int32 | Качество файла Jpeg (0~100), 0 — самое низкое, 100 — самое высокое |

### Смотрите также

* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

Сохраняет изображение в файл с заданным размером страницы, форматом изображения и качеством.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Путь и имя файла для сохранения изображения. |
| pageSize | PageSize | Размер страницы изображения. |
| format | ImageFormat | Формат изображения. |
| quality | Int32 | Качество файла Jpeg (0~100), 0 — самое низкое, 100 — самое высокое |

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
