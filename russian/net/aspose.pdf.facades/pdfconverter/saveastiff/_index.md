---
title: SaveAsTIFF
second_title: Aspose.PDF для справочника API .NET
description: Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF.
type: docs
weight: 160
url: /ru/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF.

```csharp
public void SaveAsTIFF(string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Файл для сохранения изображения TIFF. |

### Примеры

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

### Смотрите также

* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Выходной файл. |
| compressionType | CompressionType | Тип сжатия. |

### Примеры

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

### Смотрите также

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один файл TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения изображения TIFF |
| imageWidth | Int32 | Ширина изображения, единица измерения — пиксель. |
| imageHeight | Int32 | Высота изображения, единица измерения — пиксель. |

### Смотрите также

* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

Преобразует каждую страницу документа PDF в изображения с размером страницы и сохраняет изображения в один файл TIFF.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения изображения TIFF |
| pageSize | PageSize | Размер страницы изображения. |

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

Преобразует каждую страницу документа PDF в изображения с размером страницы и сохраняет изображения в один файл TIFF.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения изображения TIFF |
| pageSize | PageSize | Размер страницы изображения. |
| settings | TiffSettings | Объект настроек, определяющий параметры TIFF. |

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один файл TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения изображения TIFF |
| imageWidth | Int32 | Ширина изображения, единица измерения — пиксель. |
| imageHeight | Int32 | Высота изображения, единица измерения — пиксель. |
| compressionType | CompressionType | Тип сжатия. |

### Смотрите также

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один файл TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения изображения TIFF |
| imageWidth | Int32 | Ширина изображения, единица измерения — пиксель. |
| imageHeight | Int32 | Высота изображения, единица измерения — пиксель. |
| settings | TiffSettings | Объект настроек, определяющий параметры TIFF. |

### Смотрите также

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один файл TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения изображения TIFF |
| imageWidth | Int32 | Ширина изображения, единица измерения — пиксель. |
| imageHeight | Int32 | Высота изображения, единица измерения — пиксель. |
| settings | TiffSettings | Объект настроек, определяющий параметры TIFF. |
| converter | IIndexBitmapConverter | Внешний преобразователь |

### Смотрите также

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один поток TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения TIFF. |

### Смотрите также

* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Выходной поток. |
| compressionType | CompressionType | Тип сжатия. |

### Смотрите также

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

Преобразует каждую страницу pdf-документа в изображения с размером страницы и сохраняет изображения в один поток TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения TIFF. |
| pageSize | PageSize | Размер страницы изображения. |

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

Преобразует каждую страницу pdf-документа в изображения с размером страницы и сохраняет изображения в один поток TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения TIFF. |
| pageSize | PageSize | Размер страницы изображения. |
| settings | TiffSettings | Объект настроек, определяющий параметры TIFF. |

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один поток TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения TIFF. |
| imageWidth | Int32 | Ширина изображения, единица измерения — пиксель. |
| imageHeight | Int32 | Высота изображения, единица измерения — пиксель. |

### Смотрите также

* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один поток TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения TIFF. |
| imageWidth | Int32 | Ширина изображения, единица измерения — пиксель. |
| imageHeight | Int32 | Высота изображения, единица измерения — пиксель. |
| compressionType | CompressionType | Тип сжатия. |

### Смотрите также

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один поток TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения TIFF. |
| imageWidth | Int32 | Ширина изображения, единица измерения — пиксель. |
| imageHeight | Int32 | Высота изображения, единица измерения — пиксель. |
| settings | TiffSettings | Объект настроек, определяющий параметры TIFF. |

### Смотрите также

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один поток TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения TIFF. |
| imageWidth | Int32 | Ширина изображения, единица измерения — пиксель. |
| imageHeight | Int32 | Высота изображения, единица измерения — пиксель. |
| settings | TiffSettings | Объект настроек, определяющий параметры TIFF. |
| converter | IIndexBitmapConverter | Внешний преобразователь |

### Смотрите также

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения изображения TIFF |
| settings | TiffSettings | Объект настроек, определяющий параметры TIFF. |

### Смотрите также

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения изображения TIFF |
| settings | TiffSettings | Объект настроек, определяющий параметры TIFF. |
| converter | IIndexBitmapConverter | Внешний преобразователь |

### Смотрите также

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один поток TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения TIFF. |
| settings | TiffSettings | Объект настроек, определяющий параметры TIFF. |

### Смотрите также

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один поток TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения TIFF. |
| settings | TiffSettings | Объект настроек, определяющий параметры TIFF. |
| converter | IIndexBitmapConverter | Внешний преобразователь |

### Смотрите также

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
