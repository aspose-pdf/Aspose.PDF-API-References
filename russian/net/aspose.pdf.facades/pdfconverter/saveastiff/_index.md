---
title: PdfConverter.SaveAsTIFF
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfConverter. Преобразует каждую страницу PDF-документа в изображения и сохраняет изображения в один TIFF-файл
type: docs
weight: 160
url: /ru/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

Преобразует каждую страницу PDF-документа в изображения и сохраняет изображения в один TIFF-файл.

```csharp
public void SaveAsTIFF(string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Файл для сохранения TIFF-изображения. |

## Примеры

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFF(@"D:\Test\test.tiff");	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### См. также

* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

Преобразует каждую страницу PDF-документа в изображения и сохраняет изображения в один TIFF-файл.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Выходной файл. |
| compressionType | CompressionType | Тип сжатия. |

## Примеры

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFF(@"D:\Test\test.tiff");
[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter()
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### См. также

* перечисление [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

Преобразует каждую страницу PDF-документа в изображения с заданными размерами и сохраняет изображения в один TIFF-файл.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения TIFF-изображения |
| imageWidth | Int32 | Ширина изображения, единица измерения - пиксели. |
| imageHeight | Int32 | Высота изображения, единица измерения - пиксели. |

### См. также

* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

Преобразует каждую страницу PDF-документа в изображения с размером страницы и сохраняет изображения в один TIFF-файл.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения TIFF-изображения |
| pageSize | PageSize | Размер страницы изображения. |

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

Преобразует каждую страницу PDF-документа в изображения с размером страницы и сохраняет изображения в один TIFF-файл.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения TIFF-изображения |
| pageSize | PageSize | Размер страницы изображения. |
| settings | TiffSettings | Объект настроек, который определяет параметры TIFF. |

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

Преобразует каждую страницу PDF-документа в изображения с заданными размерами и сохраняет изображения в один TIFF-файл.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения TIFF-изображения |
| imageWidth | Int32 | Ширина изображения, единица измерения - пиксели. |
| imageHeight | Int32 | Высота изображения, единица измерения - пиксели. |
| compressionType | CompressionType | Тип сжатия. |

### См. также

* перечисление [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

Преобразует каждую страницу PDF-документа в изображения с заданными размерами и сохраняет изображения в один TIFF-файл.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения TIFF-изображения |
| imageWidth | Int32 | Ширина изображения, единица измерения - пиксели. |
| imageHeight | Int32 | Высота изображения, единица измерения - пиксели. |
| settings | TiffSettings | Объект настроек, который определяет параметры TIFF. |

### См. также

* класс [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

Преобразует каждую страницу PDF-документа в изображения с заданными размерами и сохраняет изображения в один TIFF-файл.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения TIFF-изображения |
| imageWidth | Int32 | Ширина изображения, единица измерения - пиксели. |
| imageHeight | Int32 | Высота изображения, единица измерения - пиксели. |
| settings | TiffSettings | Объект настроек, который определяет параметры TIFF. |
| converter | IIndexBitmapConverter | Внешний конвертер |

### См. также

* класс [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* интерфейс [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

Преобразует каждую страницу PDF-документа в изображения и сохраняет изображения в один TIFF-поток.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения TIFF-изображения. |

### См. также

* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

Преобразует каждую страницу PDF-документа в изображения и сохраняет изображения в один TIFF-файл.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Выходной поток. |
| compressionType | CompressionType | Тип сжатия. |

### См. также

* перечисление [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

Преобразует каждую страницу PDF-документа в изображения с размером страницы и сохраняет изображения в один TIFF-поток.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения TIFF-изображения. |
| pageSize | PageSize | Размер страницы изображения. |

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

Преобразует каждую страницу PDF-документа в изображения с размером страницы и сохраняет изображения в один TIFF-поток.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения TIFF-изображения. |
| pageSize | PageSize | Размер страницы изображения. |
| settings | TiffSettings | Объект настроек, который определяет параметры TIFF. |

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

Преобразует каждую страницу PDF-документа в изображения с заданными размерами и сохраняет изображения в один TIFF-поток.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения TIFF-изображения. |
| imageWidth | Int32 | Ширина изображения, единица измерения - пиксели. |
| imageHeight | Int32 | Высота изображения, единица измерения - пиксели. |

### См. также

* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

Преобразует каждую страницу PDF-документа в изображения с заданными размерами и сохраняет изображения в один TIFF-поток.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения TIFF-изображения. |
| imageWidth | Int32 | Ширина изображения, единица измерения - пиксели. |
| imageHeight | Int32 | Высота изображения, единица измерения - пиксели. |
| compressionType | CompressionType | Тип сжатия. |

### См. также

* перечисление [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

Преобразует каждую страницу PDF-документа в изображения с заданными размерами и сохраняет изображения в один TIFF-поток.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения TIFF-изображения. |
| imageWidth | Int32 | Ширина изображения, единица измерения - пиксели. |
| imageHeight | Int32 | Высота изображения, единица измерения - пиксели. |
| settings | TiffSettings | Объект настроек, который определяет параметры TIFF. |

### См. также

* класс [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

Преобразует каждую страницу PDF-документа в изображения с заданными размерами и сохраняет изображения в один TIFF-поток.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения TIFF-изображения. |
| imageWidth | Int32 | Ширина изображения, единица измерения - пиксели. |
| imageHeight | Int32 | Высота изображения, единица измерения - пиксели. |
| settings | TiffSettings | Объект настроек, который определяет параметры TIFF. |
| converter | IIndexBitmapConverter | Внешний конвертер |

### См. также

* класс [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* интерфейс [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

Преобразует каждую страницу PDF-документа в изображения и сохраняет изображения в один TIFF-файл.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения TIFF-изображения |
| settings | TiffSettings | Объект настроек, который определяет параметры TIFF. |

### См. также

* класс [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

Преобразует каждую страницу PDF-документа в изображения и сохраняет изображения в один TIFF-файл.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения TIFF-изображения |
| settings | TiffSettings | Объект настроек, который определяет параметры TIFF. |
| converter | IIndexBitmapConverter | Внешний конвертер |

### См. также

* класс [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* интерфейс [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

Преобразует каждую страницу PDF-документа в изображения и сохраняет изображения в один TIFF-поток.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения TIFF-изображения. |
| settings | TiffSettings | Объект настроек, который определяет параметры TIFF. |

### См. также

* класс [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

Преобразует каждую страницу PDF-документа в изображения и сохраняет изображения в один TIFF-поток.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения TIFF-изображения. |
| settings | TiffSettings | Объект настроек, который определяет параметры TIFF. |
| converter | IIndexBitmapConverter | Внешний конвертер |

### См. также

* класс [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* интерфейс [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)