---
title: "PdfConverter.SaveAsTIFF"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfConverter. Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один TIFF‑файл"
type: docs
weight: 160
url: /ru/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один файл TIFF.

```csharp
public void SaveAsTIFF(string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Файл для сохранения TIFF‑изображения. |

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

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один файл TIFF.

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

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

Преобразует каждую страницу pdf‑документа в изображения с размерами и сохраняет их в один файл TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения изображения TIFF |
| imageWidth | Int32 | Ширина изображения, единица измерения — пиксель. |
| imageHeight | Int32 | Высота изображения, единица измерения — пиксель. |

### См. также

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

Преобразует каждую страницу pdf‑документа в изображения с указанием размера страницы и сохраняет их в один файл TIFF.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения изображения TIFF |
| pageSize | PageSize | Размер страницы изображения. |

### См. также

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

Преобразует каждую страницу pdf‑документа в изображения с указанием размера страницы и сохраняет их в один файл TIFF.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения изображения TIFF |
| pageSize | PageSize | Размер страницы изображения. |
| настройки | TiffSettings | Объект Settings, определяющий параметры TIFF. |

### См. также

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

Преобразует каждую страницу pdf‑документа в изображения с размерами и сохраняет их в один файл TIFF.

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

### См. также

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

Преобразует каждую страницу pdf‑документа в изображения с размерами и сохраняет их в один файл TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения изображения TIFF |
| imageWidth | Int32 | Ширина изображения, единица измерения — пиксель. |
| imageHeight | Int32 | Высота изображения, единица измерения — пиксель. |
| настройки | TiffSettings | Объект Settings, определяющий параметры TIFF. |

### См. также

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

Преобразует каждую страницу pdf‑документа в изображения с размерами и сохраняет их в один файл TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения изображения TIFF |
| imageWidth | Int32 | Ширина изображения, единица измерения — пиксель. |
| imageHeight | Int32 | Высота изображения, единица измерения — пиксель. |
| настройки | TiffSettings | Объект Settings, определяющий параметры TIFF. |
| конвертер | IIndexBitmapConverter | Внешний конвертер |

### См. также

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один поток TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения TIFF. |

### См. также

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один файл TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Выходной поток. |
| compressionType | CompressionType | Тип сжатия. |

### См. также

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

Преобразует каждую страницу pdf‑документа в изображения с указанием размера страницы и сохраняет их в один поток TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения TIFF. |
| pageSize | PageSize | Размер страницы изображения. |

### См. также

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

Преобразует каждую страницу pdf‑документа в изображения с указанием размера страницы и сохраняет их в один поток TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения TIFF. |
| pageSize | PageSize | Размер страницы изображения. |
| настройки | TiffSettings | Объект Settings, определяющий параметры TIFF. |

### См. также

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

Преобразует каждую страницу pdf‑документа в изображения с размерами и сохраняет их в один поток TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения TIFF. |
| imageWidth | Int32 | Ширина изображения, единица измерения — пиксель. |
| imageHeight | Int32 | Высота изображения, единица измерения — пиксель. |

### См. также

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

Преобразует каждую страницу pdf‑документа в изображения с размерами и сохраняет их в один поток TIFF.

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

### См. также

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

Преобразует каждую страницу pdf‑документа в изображения с размерами и сохраняет их в один поток TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения TIFF. |
| imageWidth | Int32 | Ширина изображения, единица измерения — пиксель. |
| imageHeight | Int32 | Высота изображения, единица измерения — пиксель. |
| настройки | TiffSettings | Объект Settings, определяющий параметры TIFF. |

### См. также

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

Преобразует каждую страницу pdf‑документа в изображения с размерами и сохраняет их в один поток TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения TIFF. |
| imageWidth | Int32 | Ширина изображения, единица измерения — пиксель. |
| imageHeight | Int32 | Высота изображения, единица измерения — пиксель. |
| настройки | TiffSettings | Объект Settings, определяющий параметры TIFF. |
| конвертер | IIndexBitmapConverter | Внешний конвертер |

### См. также

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один файл TIFF.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения изображения TIFF |
| настройки | TiffSettings | Объект Settings, определяющий параметры TIFF. |

### См. также

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один файл TIFF.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Имя файла для сохранения изображения TIFF |
| настройки | TiffSettings | Объект Settings, определяющий параметры TIFF. |
| конвертер | IIndexBitmapConverter | Внешний конвертер |

### См. также

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один поток TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения TIFF. |
| настройки | TiffSettings | Объект Settings, определяющий параметры TIFF. |

### См. также

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один поток TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения TIFF. |
| настройки | TiffSettings | Объект Settings, определяющий параметры TIFF. |
| конвертер | IIndexBitmapConverter | Внешний конвертер |

### См. также

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


