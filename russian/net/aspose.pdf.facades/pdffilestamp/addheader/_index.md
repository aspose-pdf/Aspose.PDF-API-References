---
title: AddHeader
second_title: Aspose.PDF для справочника API .NET
description: Добавляет заголовок на страницу.
type: docs
weight: 160
url: /ru/net/aspose.pdf.facades/pdffilestamp/addheader/
---
## AddHeader(FormattedText, float) {#addheader}

Добавляет заголовок на страницу.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | FormattedText | Текст для заголовка и свойства текста. |
| topMargin | Single | Поля вверху страницы. |

### Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### Смотрите также

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* пространство имен [Aspose.Pdf.Facades](../../pdffilestamp)
* сборка [Aspose.PDF](../../../)

---

## AddHeader(FormattedText, float, float, float) {#addheader_1}

Добавляет заголовок к страницам файла.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | FormattedText | Форматированный текстовый объект, который содержит текст страницы и его свойства. |
| topMargin | Single | Поля вверху страницы. |
| leftMargin | Single | Поле в левой части страницы. |
| rightMargin | Single | Поля в правой части страницы. |

### Примеры

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### Смотрите также

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* пространство имен [Aspose.Pdf.Facades](../../pdffilestamp)
* сборка [Aspose.PDF](../../../)

---

## AddHeader(string, float) {#addheader_4}

Добавляет изображение в качестве заголовка к страницам файла.

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageFile | String | Путь к файлу изображения. |
| topMargin | Single | Поле вверху страницы. |

### Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### Смотрите также

* class [PdfFileStamp](../../pdffilestamp)
* пространство имен [Aspose.Pdf.Facades](../../pdffilestamp)
* сборка [Aspose.PDF](../../../)

---

## AddHeader(string, float, float, float) {#addheader_5}

Добавляет изображение в качестве заголовка на страницы.

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageFile | String | Путь к файлу изображения. |
| topMargin | Single | Поле вверху страницы. |
| leftMargin | Single | Поля в левой части страницы. |
| rightMargin | Single | Поля в правой части страницы. |

### Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Смотрите также

* class [PdfFileStamp](../../pdffilestamp)
* пространство имен [Aspose.Pdf.Facades](../../pdffilestamp)
* сборка [Aspose.PDF](../../../)

---

## AddHeader(Stream, float) {#addheader_2}

Добавляет изображение в качестве заголовка на страницы.

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | Stream | Поток изображения. |
| topMargin | Single | Поле вверху страницы. |

### Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Смотрите также

* class [PdfFileStamp](../../pdffilestamp)
* пространство имен [Aspose.Pdf.Facades](../../pdffilestamp)
* сборка [Aspose.PDF](../../../)

---

## AddHeader(Stream, float, float, float) {#addheader_3}

Добавляет изображение вверху страницы.

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток, содержащий данные изображения. |
| topMargin | Single | Поле вверху страницы. |
| leftMargin | Single | Поля в левой части страницы. |
| rightMargin | Single | Поля в правой части страницы. |

### Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### Смотрите также

* class [PdfFileStamp](../../pdffilestamp)
* пространство имен [Aspose.Pdf.Facades](../../pdffilestamp)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
