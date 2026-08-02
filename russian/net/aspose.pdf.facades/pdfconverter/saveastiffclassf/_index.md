---
title: "PdfConverter.SaveAsTIFFClassF"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfConverter. Преобразует каждую страницу pdf‑документа в изображения и сохраняет изображения в один файл TIFF ClassF."
type: docs
weight: 170
url: /ru/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/
---
## SaveAsTIFFClassF(string, int, int) {#saveastiffclassf_5}

Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один файл TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile, int imageWidth, int imageHeight)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Поток для сохранения изображения TIFF. |
| imageWidth | Int32 | Ширина изображения, единица измерения — пиксель. |
| imageHeight | Int32 | Высота изображения, единица измерения — пиксель. |

## Примеры

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff",204,196);	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff",204,196)
```

### См. также

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string, PageSize) {#saveastiffclassf_4}

Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один файл TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Поток для сохранения изображения TIFF. |
| pageSize | PageSize | Размер страницы изображения. |

### См. также

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, int, int) {#saveastiffclassf_2}

Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один поток TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, int imageWidth, int imageHeight)
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

## SaveAsTIFFClassF(Stream, PageSize) {#saveastiffclassf_1}

Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один поток TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, PageSize pageSize)
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

## SaveAsTIFFClassF(string) {#saveastiffclassf_3}

Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один файл TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Поток для сохранения изображения TIFF. |

## Примеры

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff");	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff")
```

### См. также

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream) {#saveastiffclassf}

Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один поток TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения изображения TIFF. |

### См. также

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


