---
title: GetNextImage
second_title: Aspose.PDF для справочника API .NET
description: Получает следующее изображение из документа PDF. Примечание. Перед использованием этого метода необходимо вызвать ExtractImage.
type: docs
weight: 170
url: /ru/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

Получает следующее изображение из документа PDF. Примечание. Перед использованием этого метода необходимо вызвать ExtractImage.

```csharp
public bool GetNextImage(string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Файл, в котором будет храниться изображение |

### Возвращаемое значение

Правда, изображение успешно извлечено

### Примеры

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

### Смотрите также

* class [PdfExtractor](../../pdfextractor)
* пространство имен [Aspose.Pdf.Facades](../../pdfextractor)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

Получает следующее изображение из документа PDF с заданным форматом изображения. Примечание. Перед использованием этого метода необходимо вызвать ExtractImage.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Файл, в котором будет храниться изображение |
| format | ImageFormat | Формат изображения. |

### Возвращаемое значение

Правда, изображение успешно извлечено

### Смотрите также

* class [PdfExtractor](../../pdfextractor)
* пространство имен [Aspose.Pdf.Facades](../../pdfextractor)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

Получить следующее изображение из файла PDF и сохранить его в поток с заданным форматом изображения.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток, в котором будут сохранены данные изображения |
| format | ImageFormat | Формат изображения. |

### Возвращаемое значение

Истинно, если изображение успешно извлечено.

### Смотрите также

* class [PdfExtractor](../../pdfextractor)
* пространство имен [Aspose.Pdf.Facades](../../pdfextractor)
* сборка [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Получить следующее изображение из файла PDF и сохранить его в потоке.

```csharp
public bool GetNextImage(Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток, в котором будут сохранены данные изображения |

### Возвращаемое значение

Истинно, если изображение успешно извлечено.

### Смотрите также

* class [PdfExtractor](../../pdfextractor)
* пространство имен [Aspose.Pdf.Facades](../../pdfextractor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->