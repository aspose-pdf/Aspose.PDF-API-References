---
title: PdfExtractor.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfExtractor. Извлекает следующее изображение из PDF-документа. Примечание: ExtractImage должен быть вызван перед использованием этого метода
type: docs
weight: 170
url: /ru/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

Извлекает следующее изображение из PDF-документа. Примечание: ExtractImage должен быть вызван перед использованием этого метода.

```csharp
public bool GetNextImage(string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Файл, в который будет сохранено изображение |

### Возвращаемое значение

True, если изображение успешно извлечено

## Примеры

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### См. также

* класс [PdfExtractor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

Извлекает следующее изображение из PDF-документа с заданным форматом изображения. Примечание: ExtractImage должен быть вызван перед использованием этого метода.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Файл, в который будет сохранено изображение |
| format | ImageFormat | Формат изображения. |

### Возвращаемое значение

True, если изображение успешно извлечено

### См. также

* класс [PdfExtractor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

Извлекает следующее изображение из PDF-файла и сохраняет его в поток с заданным форматом изображения.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток, в который будут сохранены данные изображения |
| format | ImageFormat | Формат изображения. |

### Возвращаемое значение

True в случае успешного извлечения изображения.

### См. также

* класс [PdfExtractor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Извлекает следующее изображение из PDF-файла и сохраняет его в поток.

```csharp
public bool GetNextImage(Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток, в который будут сохранены данные изображения |

### Возвращаемое значение

True в случае успешного извлечения изображения.

### См. также

* класс [PdfExtractor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)