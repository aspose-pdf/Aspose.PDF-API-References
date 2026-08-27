---
title: "PdfExtractor.GetNextImage"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfExtractor. Получает следующее изображение из PDF‑документа. Примечание: ExtractImage должен быть вызван до использования этого метода"
type: docs
weight: 170
url: /ru/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

Получает следующее изображение из PDF-документа. Примечание: перед использованием этого метода необходимо вызвать ExtractImage.

```csharp
public bool GetNextImage(string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Файл, в котором будет сохранено изображение |

### Возвращаемое значение

Истина, если изображение успешно извлечено

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

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

Получает следующее изображение из PDF-документа в указанном формате изображения. Примечание: перед использованием этого метода необходимо вызвать ExtractImage.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Файл, в котором будет сохранено изображение |
| формат | ImageFormat | Формат изображения. |

### Возвращаемое значение

Истина, если изображение успешно извлечено

### См. также

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

Получает следующее изображение из PDF-файла и сохраняет его в поток в указанном формате изображения.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток, в котором будут сохранены данные изображения |
| формат | ImageFormat | Формат изображения. |

### Возвращаемое значение

Истина в случае успешного извлечения изображения.

### См. также

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Получает следующее изображение из PDF-файла и сохраняет его в поток.

```csharp
public bool GetNextImage(Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток, в котором будут сохранены данные изображения |

### Возвращаемое значение

Истина в случае успешного извлечения изображения.

### См. также

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


